# Introducing CSS


##  What CSS does  
## How CSS works 
## Rules, properties, and values

CSS Associates Style
rules with HTML
elements, CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
P {}
* This rule indicates that all <p>
elements should be shown in the
Arial typeface. 
* Selectors indicate which
element the rule applies to.
The same rule can apply to
more than one element if you
separate the element names
with commas.
* Declarations indicate how
the elements referred to in
the selector should be styled.
Declarations are split into two
parts (a property and a value),
and are separated by a colon.

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

h1, h2, h3 {
 font-family: Arial;
 color: yellow;}
Property Value


* This rule indicates that all h1>,
h2> and h3> elements
should be shown in the Arial
typeface, in a yellow color.

* Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.
* Values specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

# Color

## How to specify colors
## Color terminology and contrast
## Background color

Understanding Color, Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.

* Computer monitors are made
up of thousands of tiny squares
called pixels (if you look very
closely at your monitor you
should be able to see them)
* When the screen is not turned
on, it's black because it's not
emitting any light. When it's
on, each pixel can be a different
color, creating a picture.
* The color of every pixel on the
screen is expressed in terms of
a mix of red, green, and blue —
just like on a television screen.

Color picking tools are available
in image editing programs like
Photoshop and GIMP. You can
see the RGB values specified
next to the radio buttons that
say R, G, B.
The hex value is provided
next to the pound or hash
# symbol. There is also a
good color picking tool at:
colorschemedesigner.com

##  HSL Colors
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.

* Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.

