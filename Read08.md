# CSS Layout
**CSS's most important property for controlling layout.
Every element has a default display value depending on what type of element it is.
The default for most elements is usually block or inline. A block element is often called a block-level element.
An inline element is always just called an inline element.**

## block in css 

What is a block in CSS?

A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
The <div element is a block-level element. ... <div

## inline_block in css

What is inline-block in CSS?

inline-block It's formatted just like the inline element, where it doesn't start on a new line. BUT, you can set width and height values.
block The element will start on a new line and occupy the full width available. And you can set width and height values
span is the standard inline element. An inline element can wrap some text inside a paragraph <span like this </span without disrupting the flow of that paragraph.
The a element is the most common inline element, since you use them for links.

## none
Another common display value is none. Some specialized elements such as script use this as their default. It is commonly used with JavaScript to hide and show elements without really deleting and recreating them.

This is different from visibility. Setting display to none will render the page as though the element does not exist. visibility: hidden; will hide the element, but the element will still take up the space it would if it was fully visible.

## other display values
There are plenty of more exotic display values, such as list-item and table. Here is an exhaustive list. We'll discuss inline-block and flex later on.

## extra credit
As I mentioned, every element has a default display type. However, you can always override this! Though it wouldn't make sense to make an inline div, you can use this to customize the display of elements that have particular semantics. A common example is making inline li elements for horizontal menus.

![block](https://lh3.googleusercontent.com/proxy/DBwr63rfU6pWDUcJn2oymedjRQ-si-UV6DFfCDtt8rMKXfBzbVcGUr7BI9q1fo4a9fV_CltgjBhvrT3SPln-rh0kfyAUlvR_HW6iiSr6YsymmXoDnC8p2gXX3lcReoJEba5K4exsfq5JIb8upabAyTOEa-ZP)


## Screen Sizes
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

## Screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens. Most computers will allow owners to adjust the resolutionof the display or the number of pixels that are shown on the screen. For example, here you can see the options to change the screen size from 720 x 480 pixels up to 1280 x 800 pixels.

## Page Sizes
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

## Fixed Width Layouts
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend

## Advantages
Pixel values are accurate at controlling size and positioning of elements.

+ The designer has far greater control over the appearance and position of items on the page than with liquid layouts.

+ You can control the lengths of lines of text regardless of the size of the user’s window.

+ The size of an image will always remain the same relative to the rest of the page

Disadvantages
You can end up with big gaps around the edge of a page.

+ If the user’s screen is a much higher resolution than the designer’s screen, the page can look smaller and text can be harder to read.

+ If a user increases font sizes, text might not fit into the allotted spaces.

+ The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.

+ The page will often take up more vertical space than a liquid layout with the same content.

# Liquid Layouts
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend tomn use percentages

## Advantages
Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.

If the user has a small window, the page can contract to fit it without the user having to scroll to the side.

The design is tolerant of users setting font sizes larger than the designer intended (because the page can).

## Disadvantages
If you do not control the width of sections of the page then the design can look very different than you intended,with unexpected gaps around certain elements or items squashed together.

If the user has a wide window, lines of text can become very long, which makes them harder to read.

If the user has a very narrow window, words may be squashed and you can end up with few words on each line.

If a fixed width item (such as an image) is in a box that is too small to hold it (because the user has made the window smaller) the image can overflow over the text.


