# HTML Images Syntax

### Who we add img?

_The HTML <img> tag is used to embed an image in a web page._

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax

### The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

Example
![img src="img_flowers"](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/diy-paper-flowers-1582662788.jpg)


# css color 
What are the colors in CSS?

Defining Colors in CSS
We've already seen some properties in CSS that take color values. Here's an example:
p {
  color: red;
}
There are several different ways to specify colors in CSS.

Color Keywords
RGB
RGBA
HSL
HSLA
Hexadecimal



![](https://cdn.educba.com/academy/wp-content/uploads/2020/03/CSS-Color-Codes.jpg)

## CSS Text 
Overflow, Word Wrap, Line Breaking Rules, and Writing Modes

In this chapter you will learn about the following properties:

text-overflow

word-wrap

word-break

writing-mode

CSS Text Overflow

The CSS text-overflow property specifies how overflowed content that is not displayed should be signaled to the user.
It can be clipped:
This is some long text that will not fit in the box
or it can be rendered as an ellipsis (...):
This is some long text that will not fit in the box
The CSS code is as follows:

Example

p.test1 {
  white-space: nowrap;
  width: 200px;
  border: 1px solid #000000;
  overflow: hidden;
  text-overflow: clip;
}

p.test2 {
  white-space: nowrap;
  width: 200px;
  border: 1px solid #000000;
  overflow: hidden;
  text-overflow: ellipsis;
}

#### Refranse 
[link 1](http://web.simmons.edu/~grovesd/comm244/notes/week3/css-colors)

[link 2](https://www.w3schools.com/css/css3_text_effects.asp)
