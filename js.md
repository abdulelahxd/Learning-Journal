# HTML, CSS, Javascript 

*as you see there are three parts to any web page on internet*

![html, css, js](https://skywell.software/wp-content/uploads/2019/01/javascript-vs-html-vs-css-1024x683.jpg)

1. HTML CONTENT LAYER .html 
        1. This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.

2. CSS PRESENTATION LAYER .css
        1. he CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).

3. Javascript BEHAVIOR LAYER .js
        1. This is where we can change
how the page behaves, adding
interact ivity. We will aim to keep
as much of our JavaScript as
possible in separate files.


## LINKING JAVASCRIPT TO HTML FILE 
THERE ARE THREE WAYS TO PUT A SCRIPT INTO HTML FILE 
1. BETWEEN HEAD TAGS FOR EXTERNAL JS FILE
2. OR ENTERNAL BY '<SCRPIT>' TAG  
IT SHOULD BE BEFORE BODY END TAG FOR MOST PRACTICE ALSO THIS WILL ALLOW TO STRUCTUER LOAD FIRST 
BECAUSE JAVASCRIPT RUNS WHERE IT IS FOUND IN HTML 
'When the browser comes across a <script> element, it stops to
load the script and then checks to see if it needs to do anything.'


## WHAT IS A VARIABLE?

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect.
Think about calculating the area of a wall; in math
the area of a rectangle is obtained by multiplying two
numbers:
width x height = area
You may be able to do calcula tions like this in
your head, bu t when writing a script to do this
calculation, you need to give the computer very
detailed instructions. You might tell it to perform the
following four steps in order:
1. Remember the value for width
2. Remember the value for height
3. Multiply width by height to get the area
4. Return the result to the user
In this case, you would use vari ables to "remember"
the va lues for width and height. (This also illustrates
how a scrip( contains very explicit instructions about
exactly what you want the computer to do.)
You can compare variables to short-term memory,
because once you leave the page, the browser will
forget any information it holds.



## DATA TYPES
JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans.
NUMERIC DATA TYPE
The numeric data type handles
numbers.
0.75
For tasks that involve counting
or calculating sums, you will
use numbers 0-9. For example,
five thousand, two hundred and
seventy-two would be written
5272 (note there is no comma
between the thousands and
the hundreds). You can also
have negative numbers (such
as -23678) and decimals (three
quarters is written as 0.75).
Numbers are not only used for
things like calculators; they
are also used for tasks such
as determining the size of the
screen, moving the position of
an element on a page, or setting
the amount of time an element
should take to fade in.


STRING DATA TYPE
The strings data type consists of
letters and other characters.

Hi, Ivy!
Note how the string data type is
enclosed within a pair of quotes.
These can be single or double
quotes, but the opening quote
must match the closing quote.
Strings can be used when
working with any kind of text.
They are frequently used to add
new content into a page and they
can contain HTML markup.
BOOLEAN DATA TYPE
Boolean data types can have one
of two va lues: true or false.
true
It might seem a little abstract at
first, but the Boolean data type is
actually very helpful.
You can think of it a little like a
light switch - it is either on or off.
As you will see in Chapter 4,
Booleans are helpful when
determining which part of a
script should run.
In addition to these three data types, JavaScript also has others (arrays,
objects, undefined, and null) that you will meet in later chapters.
Unlike some other programming languages, when declaring a variable in
JavaScript, you do not need to specify what type of data it will hold.

## rules for naming variables

1. The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number.

2.  name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.

3. You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.

4. All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.

5. Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age.

6. If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash).



