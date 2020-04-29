# DOCTYPES
Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.
As you will see when we come to
look at CSS and its box model on
page 316, the use of a DOCTYPE
can also help the browser to
render a page correctly.
Because XHTML was written
in XML, you will sometimes
see pages that use the XHTML
strict DOCTYPE start with
the optional XML declaration.
Where this is used, it should be
the first thing in a document.
There must be nothing before it,
not even a space.



## HTML comments 
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
```<!-- comment goes here -->```

## Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).
As you will see when you
come to look at CSS in the next
section, giving an element a
unique identity allows you to
style it differently than any other
instance of the same element
on the page. For example,
you might want to assign one
paragraph within the page
(perhaps a paragraph containing
a pull quote) a different style
than all of the other paragraphs.
In the example on the right, the
paragraph with the id attribute
whose value is pullquote is
made uppercase using CSS.
If you go on to learn about
JavaScript (a language that
allows you to add interactivity to
your pages), id attributes can be
used to allow the script to work
with that particular element.
The id attribute is known as a
global attribute because it can
be used on any element.

## Class attribute
Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.
To do this you can use the
class attribute. Its value
should describe the class it
belongs to. In the example on
the left, key paragraphs have a
class attribute whose value is
important.
The class attribute on any
element can share the same
value. So, in this example, the
value of important could be
used on headings and links, too.

## inline elements
Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.
Examples of inline elements are
<a>, <b>, <em>, and <img>.


## Div
The <div> element allows you to
group a set of elements together
in one block-level box.
For example, you might create
a <div> element to contain all
of the elements for the header
of your site (the logo and the
navigation), or you might create
a <div> element to contain
comments from visitors.
In a browser, the contents of
the <div> element will start on
a new line, but other than this
it will make no difference to the
presentation of the page.
Using an id or class attribute
on the <div> element, however,
means that you can create
CSS style rules to indicate how
much space the <div> element
should occupy on the screen and
change the appearance of all the
elements contained within it.
It can also make it easier to
follow your code if you have used
<div> elements to hold each
section of the page.


## Summary extra markup
DOCTYPES tell browsers which version of HTML you
are using.
You can add comments to your code between the
<!-- and --> markers.
The id and class attributes allow you to identify
particular elements.
The <div> and <span> elements allow you to group
block-level and inline elements together.
<iframes> cut windows into your web pages through
which other pages can be displayed.
The <meta> tag allows you to supply all kinds of
information about your web page.
Escape characters are used to include special
characters in your pages such as <, >, and ©.







# HTML5 LAYOUT ELEMENTS

HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.


This example has exactly the
same structure as seen on the
previous page. However, many
of the <div> elements have been
replaced by new HTML5 layout
elements.
For example, the header sits
inside a new <header> element,
the navigation in a <nav>
element, and the articles are in
individual <article> elements.
The point of creating these
new elements is so that web
page authors can use them to
help describe the structure of
the page. For example, screen
reader software might allow
users to ignore headers and
footers and get straight to
the content. Similarly, search
engines might place more
weight on the content in an
<article> element than that
in the <header> or <footer>
elements. I think you will agree
that it also makes the code
easier to follow.


The <header> and <footer>
elements can be used for:
●● The main header or footer
that appears at the top or
bottom of every page on the
site.
●● A header or footer for an
individual <article> or
<section> within the page.

The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.



The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not.
When the <aside> element
is used inside an <article>
element, it should contain
information that is related to the
article but not essential to its
overall meaning. For example, a
pullquote or glossary might be
considered as an aside to the
article it relates to.

The <section> element groups
related content together, and
typically each section would
have its own heading.


The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading.

## Summary HTML5 LAYOUT

he new HTML5 elements i  ndicate the purpose of
different parts of a web page and help to describe
its structure.
The new elements provide clearer code (compared
with using multiple <div> elements).
Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.



# Who is the Site For?

Every website should be designed for the
target audience—not just for yourself or the
site owner. It is therefore very important to
understand who your target audience is.

## WireFrames

A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

A lot of designers will take the
elements that need to appear on
each page and start by creating
wireframes. This involves
sketching or shading areas
where each element of the page
will go (such as the logo, primary
navigation, headings and main
bodies of text, user logins etc).
By creating a wireframe you can
ensure that all of the information
that needs to be on a page is
included.
You should not include the
color scheme, font choices,
backgrounds or images for
the website in the wireframe.
It should focus on what
information needs to be on
each page and create a visual
hierarchy to indicate the most
important parts of each page.
The wireframes make design
easier because you know what
information needs to appear on
which page before considering
how the the page should look.
It can be very helpful to show the
wireframes of a site to a client
before showing them a design.
It enables the client to ensure
the site has all the functions and
information it needs to offer.
If you just present a site design
to a client, it is common for them
to focus on how the site looks,
which means they may not raise
issues about its function after
the site has been built.

## Summary Process & Design

It's important to understand w  ho your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
Site maps allow you to plan the structure of a site.
Wireframes allow you to organize the information that
will need to go on each page.
Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
You can differentiate between pieces of information
using size, color, and style.
You can use grouping and similarity to help simplify
the information you present.










