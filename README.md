Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Part 1 Changes to HTML
======================

Changes made to the HTML of the Gutenberg stories used:
- Removal of existing embedded CSS code

Changes made to the style of the Gutenberg stories:
- centralized CSS to style.css file
- fixed background image of old_paper.jpg applied to all stories
- body content justify aligned
- paragraph content is displayed using font family Georgia
- paragraph content has a overall 15% margin applied
- first line of all paragraph content is indented 1em
- margin for the top and bottom of paragraph content is overrided to .5em
- header content is center aligned
- header content is displayed using font family Lucida Bright
- preformatted content is italicized
- preformatted content has font sized reduced to 90%
- preformetted content has it's margin shifted 10% in from the left
- links on pages are set to be blue when not hovered or clicked, red when hovered and purple when clicked
- links are also set to be underlined when hovered
- div class fig content, which hold images, are center aligned
- images within div.fig content are allowed to be a max of 700px in height and width
- tables with class bold are set to have their contents bold