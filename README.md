#### Part 1: Optimize PageSpeed Insights score for index.html

Steps taken:

1- Added CSS Information to Index.html and removed link to style.css file
2- Added async to google analytics Java Script
3- Inlined print css
4- Inlined javascript from perfmatters
5- Added height/width attributes to pictures, alt text
4- Removed Google Font from index.html added font to CSS on page.
4- Used Kraken to minify profile pic and pizzeria picture

After above changes:
Mobile 97/100 (speed), 100/100 (user)
Desktop 98/100


#### Part 2: Optimize Frames per Second in pizza.html

Steps taken:

1- Found var adjectives noise was incorrect updated to noisy
2- changed the number to 31 for document.addEventListenter instead of max 200 when counting.
3- Created new variable in the updatePosition called top, and then used that for the var phase calculation.

Resize Pizza Change for Slider
1- updated width to 100px window.requestAnimationFram(updatePositions);
2- Moved determineDx function call inside the changePizzaSizes function out of the loop. Selected only the first .randomPizzaContainer in the document.
3- moved newwidth out of loop since its the same for all elements, instead of looping through each one.

 - minified the main.js file and made pizza.html point to that file.


#### Resources

https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path?hl=en
https://kraken.io/web-interface
http://jscompress.com/
http://addyosmani.com/blog/performance-optimisation-with-timeline-profiles/


#### Files used and modified in this project

readme.md
index.html (optimized CRP for PageSpeed)
project-2048.html
project-mobile.html
project-webperf.html
css/print.css (added media print so only used for printing)
css/style.css (inlined this css, removed link to this page)
img/2048.png
img/cam_be_like.jpg
img/mobilewebdev.jpg
img/profilepic.jpg (minified with Kraken)
views/pizza.html (modified to point to minified main.js)
views/css/bootstrap-grid.css
views/css/style.css
views/images/pizza-slider.png
views/images/pizza.png
views/images/pizzeria.jpg (minified with Kraken)
views/js/main.js (optimized for web performance)
views/js/main.min.js (minified version for improved performance)







