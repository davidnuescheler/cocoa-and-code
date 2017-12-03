# Intro to CSS

The same way how HTML defines the structure of a document you can think
of CSS as the language that describes the format and layout, things like fonts, colors, spacing, etc. 
CSS stands for Cascading Style Sheets.

## Your first CSS code

Other than HTML, CSS does not have tags and attributes, but instead a completely different syntax. It can be embedded in HTML though, with a `<style>` ... `</style>` tag.

So if you go back to your HTML document, let's style the `<h1>` heading and the body of the document by adding the following to your HTML document...

~~~~ html
<style>

h1 {
    font-family: Helvetica;
    font-size: 40px;
    color: aqua; 
    background-color: navy; 
    padding: 20px;
}

body {
    background-color: aqua;
}

</style>

~~~~


## Selectors and properties

CSS consists of `Selectors` and `Properties`, Selectors are used to identify what you are applying the styles to and the properties describe what it is that you are changing.

So in the above example `h1` is a selector, that says that you are applyinfg things to your `h1` tag in your HTML document, and what's in side the `{`...`}` are the properties, that describe what styling you want to apply.

In this example, we are changing the Font & Font Size, the foreground andbackground colors, and the padding around the text. `font-family`, `font-size` are called properties and `Helvetica`, `40px` are called values.

There is a very broad range of CSS properties, and we are only looking at a few here, every property has a type of values that make sense and we will look into the most basic ones.

## Colors

One of the most basic aspect of any styling of course are colors. There is a set of CSS properties that take a color as their values. The most important ones are already used in the example above `color` and `background-color`.

There are various ways to specify colors, like the short names used above like `aqua` or `navy`, the most popular way to specify a color in CSS though is through the HEX values.
HEX values are hexadecimal representation of RGB values and look like this `#001f3f` or `#7FDBFF`. You can select from over 16 million colors like this.

There are a lot of palettes or color pickers that help you find the color that you are looking for. here is one of my favourite ones.

https://color.adobe.com

As an example try, to change the colors of your CSS style from the blue colors to a nice green.


## Fonts

## Box Model (Margin, Border, Padding, Height and Width)

## Classes

## Pseudo Classes

## Referencing Styles

## Animations

