Changes to Optimize CODE

Project #4 Udacity's Front-End Web Development Nanodegree Overview -  We were given a task to optimize a website with a number of performance issues.

Build

No build tools or compression was required to meet performance Objecitves.  No instructions are necessary to setup server.  To run application bring up index.html in browser of choice.


The Following changes were made

CSS -    Inlined all the CSS into the head of the document and added HTML media="print" to style sheet.
JS -     Added the HTML async attribute to the script tags where necessary.
Images - Resized Images and compressed using GIF.

Sliding Pizza's - Required Optimizing JavaScript with the following changes

pizza main.js 
	1 Changed querrySelector class of calls to the faster web API call getElementById(), this was done for both classes and elements.
	2 Moved out unneeded calculations from FOR loops, this included creating variables to math calculations.
	3 Reduced the number of DOM calls and Resizing by doing it once for all elements.
	4 Fixed syntax error of noisy that had been noise
	5 Reduced the number of slidding Pizza Elements from 200 to 24 (Major Improvement)
	6 Used translateX and translateZ in place of transform
	7 Removed height and width styles from generated pizza elements and resized pizza.