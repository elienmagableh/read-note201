# chapter 5
## image 
Images are very important to beautify as well as to depict many complex concepts in simple way on your web page. This tutorial will take you through simple steps to use images in your web pages.

Insert Image
You can insert any image in your web page by using <img> tag. Following is the simple syntax to use this tag.

<img src = "Image URL" ... attributes-list/>
The <img> tag is an empty tag, which means that, it can contain only list of attributes and it has no closing tag.

* A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one. *

Images can be used to set the tone for a site in less time than 
it takes to read a description. If you do not have photographs 
to use on your website, there are companies who sell stock images; these are images you

** Images should... **
- Be relevant
- Convey information
- Convey the right mood 
- Be instantly recognisable 
- Fit the color palette

Example
To try following example, let's keep our HTML file test.htm and image file test.png in the same directory −

Live Demo
<!DOCTYPE html>
<html>

   <head>
      <title>Using Image in Webpage</title>
   </head>
	
   <body>
      <p>Simple Image Insert</p>
      <img src = "/html/images/test.png" alt = "Test Image" />
   </body>
	
</html>
This will produce the following result 

![image](https://www.tutorialspoint.com/html/images/test.png)
You can use PNG, JPEG or GIF image file based on your comfort but make sure you specify correct image file name in src attribute. Image name is always case sensitive.

The alt attribute is a mandatory attribute which specifies an alternate text for an image, if the image cannot be displayed.

** Set Image Location **
Usually we keep all the images in a separate directory. So let's keep HTML file test.htm in our home directory and create a subdirectory images inside the home directory where we will keep our image test.png.
![html](https://www.wikihow.com/images/thumb/d/dc/Insert-Images-with-HTML-Step-5-Version-5.jpg/v4-460px-Insert-Images-with-HTML-Step-5-Version-5.jpg.webp)

# chapter 11
# color 
The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:
1. rgb values
  These express colors in terms of how much red, green and 
  blue are used to make it up. For example: rgb(100,100,90)
2. hex codes
  These are six-digit codes that represent the amount of red, 
  green and blue in a color, preceded by a pound or hash # 
  sign. For example: #ee3e80
3. color names
There are 147 predefined color names that are recognized by browser
** Color Numbers **
Color numbers are specified using hexadecimal (base 16) values.The hexidecimal digits are: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F
(where A through F equal the base 10 numbers: 10, 11, 12, 13, 14, 15)

The six digit color number is broken into three groups of two digits which specify the amount of Red, Green, and Blue in the color (using additive color...the way colored lights mix, not the way color pigments mix). Each two digit hex pair can have a value from 00 to FF (FF=256 in base 10). This gives over 16 million possible colors.

For example:

#FF0000 means FF worth of Red, and no Green or Blue. The result is RED.

#0000FF means no Red or Green, and FF worth of Blue. The result is BLUE.

#FFFF00 means FF worth of Red and Green, and Blue. The result is YELLOW.

#000000 means no Red, Green, or Blue. The result is BLACK.

#FFFFFF means full FF amounts of Red, Green, and Blue. The result is WHITE.

#FFEFD5 has high values for all colors, giving a light result: PAPAYAWHIP.
   (no, I don't know who thought up the color names.)

#556B2F has lower values for all colors, giving a darker result: DARKOLIVEGREEN.
![color](https://i.pinimg.com/originals/7b/f7/c6/7bf7c6e53128592dcd608f368571821c.gif)

# chapter 12
## text
There are properties to control the choice of font, size, 
weight, style, and spacing.
There is a limited choice of fonts that you can assume 
most people will have installed.
If you want to use a wider range of typefaces there are 
several options, but you need to have the right license 
to use them.
You can control the space between lines of text, 
individual letters, and words. Text can also be aligned 
to the left, right, center, or justified. It can also be 
indented.
You can use pseudo-classes to change the style of an 
element when a user hovers over or clicks on text, or 
when they have visited a link. 
 
 