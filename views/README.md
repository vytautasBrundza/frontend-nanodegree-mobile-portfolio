## Website Performance Optimization portfolio project

HOW TO RUN

To run this project, open pizzas.html file or navigate to http://kiaurutis.co.nf/udacity/p4/pizza.html in your browser.

CHANGES EXPLAINED

The load speed has not increased a lot, as I was unable to optimise the generation of 100 pizzas. Any changes caused higher loading speeds. However minimising files and dropping code into html reduced the loading time. I had a lot of issues with server response time, as I am using free hosting solution.

The scrolling of pizzas speed was increased by reducing number of pizzas generated. 200!? waste of resources! 40 keeps the aspect ratio of covered area pretty logical (http://prntscr.com/7w7bmg) and reduces the number of calculations.

Resizing pizzas - my best achievement. Instead of iterating 100 elements, just change parent element class and use combined selector to apply widths via CSS.
And no silly calculations- use % in CSS instead of calculating and setting each element width.
The resize function now runs in a blink: 0.28100001509301364ms. Though actual rebuild of CSSOOM and repainting takes a few miliseconds.