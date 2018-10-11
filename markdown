What is markdown

# from wikipedia.org

Markdown is a lightweight markup language with plain text formatting syntax.
It is designed so that it can be converted to HTML and many other formats using a tool by the same name.
Markdown is often used to format readme files,
for writing messages in online discussion forums,
and to create rich text using a plain text editor.

## from daringfireball.net

Markdown is a text-to-HTML conversion tool for web writers.
It allows you to write using an easy-to-read, easy-to-write
plain text format, then convert it to structurally valid XHTML(or HTML).

The overriding design goal for Markdown's formatting syntax is to make it as readable as possible.

# Installation and requirements.
Markdown requires Perl 5.6.0 or later.
Welcome to the 21st Century.
Markdown also requires the standard Perl library module
Digest::MD5, which is probably already install on your server.

### syntax ###

# pictures
![foo](http://path.to/your/nice.jpg)

# blank row (br)
It's automatic work. Force to generate a new line,
you just need type two blank mark at the end one line. 

# emphasis and overemphasis
*words or sentences to be emphasised*
**words or sentences to be overemphasised**
or
__words or sentences to be overemphasised__
# or you can use a tab or four blank spaces as below:
	first line to be emphasised by tab
    second line to be emphasised by four blank spaces
	second line to be emphasised as you wish
# this method will let markdown keep all the blank characters
# normally, markdown will delete all the blank characters

# title
# This is "<h1>"
#### This is "<h4>"
or
h1 title
========
h2 title
--------

# reference

> This all paragraph will be regard as block quote element.
And so is this line.
And it is reflowable.

> Also it can contain multiple reference
This is still the first block.
>> This is the second block
This is the second line of the second block.

# href

[word](src)
example [Markdown](http://zh.wikipedia.com/wiki/Markdown)

# add a horizontal line

* * *
***
******
- - -
-----------

all the five above is available

# editor suggestion

Mou
MacDown
