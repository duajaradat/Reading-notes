# *The Duckett HTML book*

## *CH05: IMIGES*

There are many reasons why you mightwant to add an **image** to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

A picture can say a thousand words, and great **images** help make the difference between an average-looking site and a really engaging one.

If you are building a site from scratch, it is good practice to create a folder for all of the **images** the site uses.

![](imgfolder.png)

**Adding IMG**

`<img>` images.html HTML

To add an image into the page you need to use an `<img>` element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:

`src`

This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder
called images — relative URLs were covered on pages 83-84).

`alt`

This provides a text description of the image which describes the image if you cannot see it.
title You can also use the title attribute with the `<img>` element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

***You will also often see an `<img>` element use two other attributes that specify its size:

*height* : This specifies the height of the image in pixels.

*width* : This specifies the width of the image in pixels.

**Where to Place Images in Your Code**

1- before a paragraph.

2- inside the start of a paragraph.

3- in the middle of a paragraph.

![](imglocation.png)

**Cropping Images**

When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible.

**HTML 5: Figure and Figure Caption**

`<figure>`

Images often come with captions. HTML5 has introduced a new `<figure>` element to
contain images and their caption so that the two are associated.

`<figcaption>`

The `<figcaption>` element has been added to HTML5 in order to allow web page authors to add a caption to an image.



## *CH11: COLOR*

### **Foreground Color**


The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

*rgb values*


These express colors in terms of how much red, green and blue are used to make it up.

**For example: rgb(100,100,90)**

*hex codes*

These are six-digit codes that represent the amount of red, green and blue in a color,preceded by a pound or hash #
sign.

**For example: #ee3e80**

*color names*

There are 147 predefined color names that are recognized by browsers.

*For example:DarkCyan*

 ### **Background Color :background-color**

`body {`

`background-color: rgb(200,200,200);}`

`h1 {`

`background-color: DarkCyan;}`

`h2 {`

`background-color: #ee3e80;}`

`p {`

`background-color: white;}`


### **CSS 3: Opacity**
 ### **opacity, rgba**

 CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

### **CSS 3: HSL & HSLA**
**hsl, hsla**

The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed
by individual values inside parentheses for:

*hue*

This is expressed as an angle (between 0 and 360 degrees). *saturation *This is expressed as a percentage.

*lightness* This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.

*alpha* This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.



## **CH12: TEXT**

### **Typeface Terminology**

![text](text1.png)

