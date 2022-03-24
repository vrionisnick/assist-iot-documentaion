.. _Smart Orchestrator:

##################
Smart Orchestrator
##################

.. contents::
  :local:
  :depth: 1

***************
Introduction
***************

***************
Features
***************

*********************
Place in architecture
*********************

***************
User guide
***************

***************
Prerequisites
***************

***************
Installation
***************

*********************
Configuration options
*********************

***************
Developer guide
***************

***************************
Version control and release
***************************

***************
License
***************

********************
Notice(dependencies)
********************



h1 Heading 8-)
==============

h2 Heading
----------

h3 Heading
~~~~~~~~~~

h4 Heading
^^^^^^^^^^

h5 Heading
''''''''''

h6 Heading
          

Horizontal Rules
----------------

--------------

--------------

--------------

Typographic replacements
------------------------

Enable typographer option to see result.

(c) 

    (C) 

        (r) 

            (R) (tm) (TM) (p) (P) +-

test.. test… test….. test?….. test!….

!!!!!! ???? ,, – —

“Smartypants, double quotes” and ‘single quotes’

Emphasis
--------

**This is bold text**

**This is bold text**

*This is italic text*

*This is italic text*

[STRIKEOUT:Strikethrough]

Blockquotes
-----------

   Blockquotes can also be nested… > …by using additional greater-than
   signs right next to each other… > > …or with spaces between arrows.

Lists
-----

Unordered

-  Create a list by starting a line with ``+``, ``-``, or ``*``
-  Sub-lists are made by indenting 2 spaces:

   -  Marker character change forces new list start:

      -  Ac tristique libero volutpat at
      -  Facilisis in pretium nisl aliquet
      -  Nulla volutpat aliquam velit

-  Very easy!

Ordered

1. Lorem ipsum dolor sit amet

2. Consectetur adipiscing elit

3. Integer molestie lorem at massa

4. You can use sequential numbers…

5. …or keep all the numbers as ``1.``

Start numbering with offset:

57. foo
58. bar

Code
----

Inline ``code``

Indented code

::

   // Some comments
   line 1 of code
   line 2 of code
   line 3 of code

Block code “fences”

::

   Sample text here...

Syntax highlighting

.. code:: js

   var foo = function (bar) {
     return bar++;
   };

   console.log(foo(5));

Tables
------

+------------------------+---------------------------------------------+
| Option                 | Description                                 |
+========================+=============================================+
| data                   | path to data files to supply the data that  |
|                        | will be passed into templates.              |
+------------------------+---------------------------------------------+
| engine                 | engine to be used for processing templates. |
|                        | Handlebars is the default.                  |
+------------------------+---------------------------------------------+
| ext                    | extension to be used for dest files.        |
+------------------------+---------------------------------------------+

Right aligned columns

+-------------------------+--------------------------------------------+
| Option                  | Description                                |
+=========================+============================================+
| data                    | path to data files to supply the data that |
|                         | will be passed into templates.             |
+-------------------------+--------------------------------------------+
| engine                  | engine to be used for processing           |
|                         | templates. Handlebars is the default.      |
+-------------------------+--------------------------------------------+
| ext                     | extension to be used for dest files.       |
+-------------------------+--------------------------------------------+

Links
-----

`link text <http://dev.nodeca.com>`__

`link with title <http://nodeca.github.io/pica/demo/>`__

Autoconverted link https://github.com/nodeca/pica (enable linkify to
see)

Images
------

|Minion| |Stormtroopocat|

Like links, Images also have a footnote style syntax

.. figure:: vertopal_1df5cf1f9f5940649b2d0c8e33f0b302/68978aa8ea003a9878d750332d99ddeb683a6840.jpg
   :alt: The Dojocat

   Alt text

With a reference later in the document defining the URL location:

Plugins
-------

The killer feature of ``markdown-it`` is very effective support of
`syntax
plugins <https://www.npmjs.org/browse/keyword/markdown-it-plugin>`__.

`Emojies <https://github.com/markdown-it/markdown-it-emoji>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:

   Shortcuts (emoticons): :-) :-( 8-) ;)

see `how to change
output <https://github.com/markdown-it/markdown-it-emoji#change-output>`__
with twemoji.

`Subscript <https://github.com/markdown-it/markdown-it-sub>`__ / `Superscript <https://github.com/markdown-it/markdown-it-sup>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  19\ :sup:`th`
-  H\ :sub:`2`\ O

`<ins> <https://github.com/markdown-it/markdown-it-ins>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

++Inserted text++

`<mark> <https://github.com/markdown-it/markdown-it-mark>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

==Marked text==

`Footnotes <https://github.com/markdown-it/markdown-it-footnote>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Footnote 1 link [1]_.

Footnote 2 link [2]_.

Inline footnote [3]_ definition.

Duplicated footnote reference [4]_.

`Definition lists <https://github.com/markdown-it/markdown-it-deflist>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Term 1
   Definition 1 with lazy continuation.

Term 2 with *inline markup*
   Definition 2

   ::

      { some code, part of Definition 2 }

   Third paragraph of definition 2.

*Compact style:*

Term 1
   Definition 1
Term 2
   Definition 2a
   Definition 2b

`Abbreviations <https://github.com/markdown-it/markdown-it-abbr>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This is HTML abbreviation example.

It converts “HTML”, but keep intact partial entries like “xxxHTMLyyy”
and so on.

\*[HTML]: Hyper Text Markup Language

`Custom containers <https://github.com/markdown-it/markdown-it-container>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. warning::

   *here be dragons*

.. [1]
   Footnote **can have markup**

   and multiple paragraphs.

.. [2]
   Footnote text.

.. [3]
   Text of inline footnote

.. [4]
   Footnote text.

.. |Minion| image:: vertopal_1df5cf1f9f5940649b2d0c8e33f0b302/6ae5cb1103ddbafbb97a15860f7f47f5701955b7.png
.. |Stormtroopocat| image:: vertopal_1df5cf1f9f5940649b2d0c8e33f0b302/30e9e8d68f4e35eeffb5bcdad83c48953b1f1116.jpg
