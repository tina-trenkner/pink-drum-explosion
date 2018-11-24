# pink-drum-explosion
a visualization based off of Wes Bos's JS drum kit. While watching the video for this tutorial, I thought it would be so much cooler to have the background change colors (instead of have a static image as the background).

I followed the video tutorial to improve my vanilla JS skills, then researched how to change the background colors as an added CSS/JS challenged.

## To start the interactive (in process):
Download the folder from this repo to your desktop.
Open index-START.html
Click a key in the home row (a-s-d-f-g-h-j-k-l) to play a different sound. 

## Concepts reviewed in this tutorial

### key codes and <kbd></kbd>
kbd is a HTML element for input via keyboard. The key code is a numeric value assigned to keys on the keyboard. 

### data as an HTML attribute
https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes

I'm not terribly clear on if/when I'll need to use data attributes in say front-end dev for Magento, probs never for Shopify. So it remains to be seen how useful this will be, beyond this JS project. 

### tick marks in ES6

### using window.addEventListener instead of say document.addEventListener
https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener

## Steps to complete tutorial

1. Set a keydown event listener on the window
2. Console log the keydown event to review what attributes the object has. Review the info in dev tools.
3. Refine JS script to listen for e.keyCode in the console.log. 
4.

## Ways to improve the responsiveness of this interactive

Add an event listern for an onclick, so that mouse users (and maybe mobile users?) can play the sounds

Add breakpoints so that the buttons move to a 2x4 formation on vertical mobile devices

