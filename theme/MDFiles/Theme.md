[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

How to edit Team12 theme		(Designed by Team12 | Jason | Darcy | Anthony | Dom
===

The Team12 theme is a `WordPress theme` built around the Underscores_ skeleton theme; the Underscores_ theme uses `PHP` and `CSS` to create the `styling` used in a `WordPress site`, but `not the content`. To adjust the style of the Team12 theme you will need `only knowledge of CSS.`

EDITING
---------------------
### PHP
When editing the Team12 theme it is important you `DO NOT edit the PHP code`, this code is purely in compliance with WordPress to import your sites content, the `ONLY page` you will need to edit is the `style.css file.`

### CSS
Within the `style.css` file there are styling blocks that alter the look of all standard aspects of the website (p, body, h1 etc). It is recommended that these `AREN’T touched` but they can be altered if you are trying to change the look of all these elements.

### CHANGING DIV CLASSES 
At the `bottom of the style sheet` is the div classes. These div classes are what is used to alter the look of a specific section of a site. In these div classes you can alter the style of the `header, main body and the footer` of the site.

### ADDING DIV CLASSES
The theme is built of `many div classes` that `aren’t` altered `in this section`, to alter these sections simply look through the relevant PHP file, find the assigned div class and add it to the `BOTTOM of the stylesheet.`

### COLOURS
When choosing colours for a site it is important to think `minimalistic`, a good colour scheme has `three primary colours` that they apply to the `entire site`, these colours can have a `relation to your sites niche/topic` or can be `basic colours` that can be applied to all sites (white, black).

### DESIGN DECISIONS 
The theme has certain `design decisions` to create a `modern looking` style that can be applied to `all websites`, these include `not using a full width page` (15% white space on left and right side, this can be altered). Using a `hover feature` that `highlights a header` when a user hovers their cursor over it, this is done to make the `header option stand out` and to tell the user they are selecting it. 

