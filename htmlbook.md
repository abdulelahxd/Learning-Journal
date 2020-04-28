## 21 STRUCTURE
Let's look closer at the code from the last page.
There are several different elements. Each
element has an opening tag and a closing tag.
Code
HTM L Us es El ements
to Describe the
Structure of Pages
``` <html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help
you follow the structure of what is being written.
There may even be sub-sub-headings (or lower-level
headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html> ```

## Body, Head, Title
<body>
You met the <body> element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.
<head>
Before the <body> element you
will often see a <head> element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a <title>
element inside the <head>
element.
<title>
The contents of the <title>
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).

## summary sturcture
HTML p  ages are text documents.
 HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
 Tags are often referred to as elements.
 Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
 Opening tags can carry attributes, which tell us more
about the content of that element.
 Attributes require a name and a value.
 To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

## summary extra markup
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


## Header & Footers
The <header> and <footer>
elements can be used for:
●● The main header or footer
that appears at the top or
bottom of every page on the
site.
●● A header or footer for an
individual <article> or
<section> within the page.
In this example, the <header>
element used to contain the site
name and the main navigation.
The <footer> element contains
copyright information, along
with links to the privacy policy
and terms and conditions.
Each individual <article> and
<section> element can also
have its own <header> and
<footer> elements to hold the
header or footer information for
that section within the page.
For example, on a page with
several blog posts, each
individual post can be thought
of as a separate section. The
<header> element can therefore
be used to contain the title and
date of each individual post, and
the <footer> might contain
links to share the article on
social networking sites.
Please note that all of the
code shown in this chapter
is referenced in one HTML
document which is called:
html5-layout.html


## Nav 
The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.
Going back to our blog example,
if you wanted to finish an article
with links to related blog posts,
these would not be counted as
major navigational blocks and
therefore should not sit inside a
<nav> element.
At the time of writing, some of
the developers that were already
using HTML5 decided to use the
<nav> element for the links that
appear at the bottom of every
page (links to things like privacy
policy, terms and conditions
and accessibility information).
Whether this will be widely
adopted is still yet to be seen.

## Artical
The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.
This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.
If a page contains several articles
(or even summaries of several
articles), then each individual
article would live inside its own
<article> element.
The <article> elements can
even be nested inside each
other. For example, a blog post
might live inside one <article>
element and each comment on
the article could live inside its
own child <article> element.

## Aside 

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
When the <aside> element is
used outside of an <article>
element, it acts as a container
for content that is related to
the entire page. For example,
it might contain links to other
sections of the site, a list of
recent posts, a search box, or
recent tweets by the author.

## Sections
The <section> element groups
related content together, and
typically each section would
have its own heading.
For example, on a homepage
there may be several <section>
elements to contain different
sections of the page, such as
latest news, top products, and
newsletter signup.
Because the <section> element
groups related items together,
it may contain several distinct
<article> elements that have a
common theme or purpose.
Alternatively, if you have a
page with a long article, the
<section> element can be
used to split the article up into
separate sections.
The <section> element should
not be used as a wrapper for
the entire page (unless the
page only contains one distinct
piece of content). If you want a
containing element for the entire
page, that job is still best left to
the <div> element.

## H1-H6
The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading.
For example, the <hgroup>
element could be used to contain
both a title inside an <h2>
element and a subtitle within an
<h3> element.
This element has had a mixed
reception. When it was first
proposed by the people
developing HTML5, there were
some complaints and it was
withdrawn from the HTML5
proposals. However, some
people changed their minds and
it has been added it back into the
language. Some developers do
not like the use of the <hgroup>
element, and prefer to place a
subtitle inside a <p> element
(using an attribute to indicate
that it is a subheading).
Some suggest that it is of little
use other than as a styling hook.
It has, however, been popular
with those developers who
believe that it is useful to group
together the primary heading
and the subheading (as both can
be integral parts of a heading).

## figure

You already met the <figure>
element in Chapter 5 when we
looked at images. It can be used
to contain any content that is
referenced from the main flow of
an article (not just images).
It is important to note that the
article should still make sense
if the content of the <figure>
element were moved (to another
part of the page, or even to a
different page altogether).
For this reason, it should only be
used when the content simply
references the element (and not
for something that is absolutely
integral to the flow of a page).
Examples of usage include:
●● Images
●● Videos
●● Graphs
●● Diagrams
●● Code samples
●● Text that supports the main
body of an article
The <figure> element should
also contain a <figcaption>
element which provides a text
decription for the content of
the <figure> element. In
this example, you can see a
<figure> has been added inside
the <article> element.

## div
It may seem strange to follow
these new elements by revisiting
the <div> element again. (After
all, the new elements are often
going to be used in its place.)
However, the <div> element
will remain an important way to
group together related elements,
because you should not be using
these new elements that you
have just met for purposes other
than those explicitly stated.
Where there is no suitable
element to group a set of
elements, the <div> element will
still be used. In this example, it is
used as a wrapper for the entire
page.
Some people have asked why
there is no <content> element
to contain the main part of
a page. The reason is that
anything that lies outside of the
<header>, <footer> or <aside>
elements can be considered as
the main content.

## summary html5 layout

The new HTML5 elements i  ndicate the purpose of
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


## A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

### A lot of designers will take the
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

## summary process & design
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


































