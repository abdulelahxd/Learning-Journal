# in this artical I will talk about CSS .
![CSS](https://www.tutorialrepublic.com/lib/images/css-illustration.png)

## In this section, we will look at how to
make your web pages more attractive,
controlling the design of them using CSS.
CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.
Once you have learned how to write a CSS rule, learning CSS
mostly involves learning the different properties you can use.
So this chapter will:
Introduce you to how CSS works
Teach you how to write CSS rules
Show you how CSS rules apply to HTML pages
The remaining chapters in this section will look at all of the
various CSS properties you can use.


* The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.


* CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

* CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

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

* CSS Properties Affect
How El ements Are
Displayed 
        * CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

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

## Summary inrtoducing CSS

CSS treats each HTML e  lement as if it appears inside
its own box and uses rules to indicate how that
element should look.
 Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
 Different types of selectors allow you to target your
rules at different elements.
 Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
 CSS rules usually appear in a separate document,
although they may appear within an HTML page.



# CSS COLOR 

* The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

        * rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

        * hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80

        * color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread.



## summary color

Color not only brings your s  ite to life, but also helps
convey the mood and evokes reactions.
There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
Color pickers can help you find the color you want.
It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.






