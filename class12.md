# Chart.js
** Chart Prototype Methods **
For each chart, there are a set of global prototype methods on the shared chart type which you may find useful. These are available on all charts created with Chart.js, but for the examples, let's use a line chart we've made

 For example:
var myLineChart = new Chart(ctx, config);

** destroy() **
Use this to destroy any chart instances that are created. This will clean up any references stored to the chart object within Chart.js, along with any associated event listeners attached by Chart.js. This must be called before the canvas is reused for a new chart.

Destroys a specific chart instance
myLineChart.destroy();

** update(config) **
Triggers an update of the chart. This can be safely called after updating the data object. This will update all scales, legends, and then re-render the chart.

duration is the time for the animation of the redraw in milliseconds
lazy is a boolean. if true, the animation can be interrupted by other animations
myLineChart.data.datasets[0].data[2] = 50; // Would update the first dataset's value of 'March' to be 50
myLineChart.update(); // Calling update now animates the position of March from 90 to 50.

The following properties are supported:

1. duration (number): Time for the animation of the redraw in milliseconds
2. lazy (boolean): If true, the animation can be interrupted by other animations
3. easing (string): The animation easing function. See Animation Easing for possible values.

Example:

myChart.update({
    duration: 800,
    easing: 'easeOutBounce'
});

reset()
Reset the chart to it's state before the initial animation. A new animation can then be triggered using update.

myLineChart.reset();

** render(config) **
Triggers a redraw of all chart elements. Note, this does not update elements for new data. Use .update() in that case.

See .update(config) for more details on the config object.

// duration is the time for the animation of the redraw in milliseconds
// lazy is a boolean. if true, the animation can be interrupted by other animations
myLineChart.render({
    duration: 800,
    lazy: false,
    easing: 'easeOutBounce'
});

** stop() **
Use this to stop any current animation loop. This will pause the chart during any current animation frame. Call .render() to re-animate.

// Stops the charts animation loop at its current frame
myLineChart.stop();

** clear() **
Will clear the chart canvas. Used extensively internally between animation frames, but you might find it useful.

// Will clear the canvas that myLineChart is drawn on
myLineChart.clear()

![chart](https://i.stack.imgur.com/UUQ3g.png)
