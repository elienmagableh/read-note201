# Chapter 16
## images 

Images are an important part of any web application. Including a lot of images in a web application is generally not recommended, but it is important to use the images wherever they required. CSS helps us to control the display of images in web applications.

Aligning an image means to position the image at center, left and right. We can use the float property and text-align property for the alignment of images.

If the image is in the div element, then we can use the text-align property for aligning the image in the div.

Example
In this example, we are aligning the images by using the text-align property. The images are in the div element.

<!DOCTYPE html>    
<html>    
<head>    
<style>    
div {    
 border: 2px solid red;  
 }  
 img{  
 height: 250px;  
 width: 250px;  
 }  
#left {    
 text-align: left;  
 }  
 #center {    
 text-align: center;  
 }  
 #right{    
 text-align: right;  
 }</style>    
</head>    
<body>   
<div id ="left">  
<img src="lion.png">  
</div>   
<div id ="center">  
<img src="lion.png">  
</div>  
<div id ="right">  
<img src="lion.png">  
</div>  
</body>    
</html>      

** the output is **
![image](https://static.javatpoint.com/csspages/images/how-to-align-images-in-css.png)


** Using float property **
The CSS float property is a positioning property. It is used to push an element to the left or right, allowing other elements to wrap around it. It is generally used with images and layouts.

Elements are floated only horizontally. So it is possible only to float elements left or right, not up or down. A floated element may be moved as far to the left or the right as possible. Simply, it means that a floated element can display at the extreme left or extreme right.

** background **
The background-image property sets one or more background images for an element.
By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.

Tip: The background of an element is the total size of the element, including padding and border (but not the margin).

Tip: Always set a background-color to be used if the image is unavailable.

** Example **
Sets two background images for the <body> element. Let the first image appear only once (with no-repeat), and let the second image be repeated:

body {
  background-image: url("img_tree.gif"), url("paper.gif");
  background-repeat: no-repeat, repeat;
  background-color: #cccccc;
}
** Example **
Use different background properties to create a "hero" image:

.hero-image {
  background-image: url("photographer.jpg"); /* The image used */
  background-color: #cccccc; /* Used if the image is unavailable */
  height: 500px; /* You must set a specified height */
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover; /* Resize the background image to cover the entire container */
}

![ground](https://www.wikihow.com/images/c/cb/Add-a-Background-to-a-Website-Step-14-Version-2.jpg)

# chapter 19 
## Practical 
![search](https://image.slidesharecdn.com/seooverview-180226060819/95/introduction-to-search-engine-optimization-3-638.jpg?cb=1519625449)
** what is SEO **
SEO, or search engine optimization, is a digital marketing channel by which website owners improve the quality of the site’s structure and content for the purpose of increasing traffic. In turn, the increased traffic and improved quality lead to better positioning in search engine rankings.

** How does SEO work? **
Search engines provide ranking results based on searched terms and their relevance to the content being featured on a given website. The more relevant the content, the higher the website will be ranked within the search engine. Webmasters and those who oversee SEO strategies strive to refine and maximize relevance of content in order to effectively deliver information that online visitors are searching for.

** How can SEO help my business? **
Any business with or without an online presence must consider leveraging SEO. The practice of optimizing content to ensure relevant keywords, phrases, and information are properly incorporated into the pages of a website will result in better search engine results for prospective customers. Because prospects usually begin the buying process by searching online, ensuring that a website incorporates a sound SEO strategy will result in more customers and increased revenue.

![seo](https://cdn.business2community.com/wp-content/uploads/2018/08/iStock-173242932-900x657.jpg)
