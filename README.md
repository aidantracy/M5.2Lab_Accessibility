# Web Dev Starter Code

## Overview

This program is designed to further expand our knowledge of accessibility 

## Accessibility Lab Answers

### Color

The text is difficult to read because of the current color scheme. Can you do a test of the current color contrast (text/background), report the results of the test, and then fix it by changing the assigned colors?

### HTML Semantics
The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.
- It immediately jumps to the bear video in the middle of the page, then to the comments, then to the aside bar in a vertical order. 

Can you update the article text to make it easier for screen reader users to navigate? 
- Yes, by replacing "font" with h1 and headers it will help the screen readers navigate the page. 

The navigation menu part of the site (wrapped in `<div class="nav"></div>`) could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.
- This has been updated to `<nav></nav>`


### The Images
The images are currently inaccessible to screen reader users. Can you fix this?

### The Audio Player
The `<audio>` player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?
The `<audio>` player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?


### The Forms 

The `<input>` element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?
The two `<input>` elements in the comment form have visible text labels, but they are not unambiguously associated with their labels — how do you achieve this? Note that you'll need to update some of the CSS rule as well.

### The Show/Hide Comment Control

The show/hide comment control button is not currently keyboard-accessible. Can you make it keyboard-accessible, both in terms of focusing it using the tab key and activating it using the return key?

### The Table

The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?


# Other Considerations? 
1.
2.





Changed `font` tags to tags that would be recognized by a screen interpreter (h1, h2, h3, etc).

Removed `div`s and replaced with appropriate tags like `nav`. 

Changed the background color to allow the text to be more readable. 

## Sources and Credits

TODO: You must credit the sources and authors of any code, libraries, or other assets you use in your project. If you leave this section blank, your project will be considered in violation of the Academic Honesty policy unless you truly created everything from scratch with no outside help. If you need to use a source that you cannot credit (e.g. a classmate's work), you must get explicit permission from your instructor.

A simple bulleted list below is sufficient. For example:

- Bootstrap: https://getbootstrap.com/
- jQuery: https://jquery.com/
- Background image: https://unsplash.com/photos/...
- Sound effects: https://freesound.org/people/...
- Icons: https://fontawesome.com/
- Fonts: https://fonts.google.com/
- etc.
