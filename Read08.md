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


