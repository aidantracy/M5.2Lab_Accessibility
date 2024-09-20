# Web Dev Starter Code

## Overview

This program is designed to further expand our knowledge of accessibility

## How to Compile
To compile, simply clone this repository to a directory of your choosing on your local machine.

Next CD into the directory you cloned and open up your preferred IDE that will run HTML, CSS, and JS (VS code is recommended)

Right click on the index.html and it should display "show preview" if live preview is installed. Of course, you may also drag the index.html file to a chrome browser and it should display there as well. 

## Accessibility Lab Answers

### Color

The text is difficult to read because of the current color scheme. Can you do a test of the current color contrast (text/background), report the results of the test, and then fix it by changing the assigned colors?

- They were hard to read at first but after I changed the background to white then the text was easier to read. 

### HTML Semantics
The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.
- It immediately jumps to the bear video in the middle of the page, then to the comments, then to the aside bar in a vertical order. 

Can you update the article text to make it easier for screen reader users to navigate? 

- Yes, by replacing "font" with h1 and headers it will help the screen readers navigate the page. 

The navigation menu part of the site (wrapped in `<div class="nav"></div>`) could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.
- This has been updated to `<nav></nav>`


### The Images
The images are currently inaccessible to screen reader users. Can you fix this?

- I updated the two images with the `alt` description to describe the images

### The Audio Player
The `<audio>` player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?
- I added a transcription. 

The `<audio>` player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio? 
- I added a link to the audio as well. 


### The Forms 

The `<input>` element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?
- adding an aria-label to each input will achieve this. 

The two `<input>` elements in the comment form have visible text labels, but they are not unambiguously associated with their labels — how do you achieve this?
- Added the `for` label within the label element. 

### The Show/Hide Comment Control

The show/hide comment control button is not currently keyboard-accessible. Can you make it keyboard-accessible, both in terms of focusing it using the tab key and activating it using the return key?

- Changing the div to a button makes the show/hide comment more accessible by the screen reader. 

### The Table

The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?

- Adding a caption will help describe the table to someone using a screen reader and adding the scope tag to each row helps indicate where in the table a specific data set is. 


# Other Considerations? 
1. Changing the text to be bold or a different font may help readers more.
2. Changed `font` tags to tags that would be recognized by a screen interpreter (h1, h2, h3, etc).


 

## Sources and Credits

I only used the readings provided in the README for this section. 