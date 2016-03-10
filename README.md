Welcome to my fourth Udacity Frontend Nanodegree project, website optimization.

Steps to run:

1.) Go to http://zackboyd.github.io/Website-Optimization
2.) Download .zip file
3.) Open index.html in 

Optimization goals:

1.) PageSpeed score >90 on mobile and desktop for index.html
2.) <5ms time for pizza resizing
3.) 60 fps when scrolling

Steps taken to optimize site:

1.) Resized and compressed multiple images loaded in pizza.html and index.html

2.) Moved style.css and print.css to <style> tags in index.html

3.) Rewrote for loops that resize pizzas and handle scrolling to remove unnecessary DOM queries and forced synchronous layouts

4.) Replaced selector queries with getElementById() and getElementsByClassName() to speed up queries

5.) Added async to js scripts 

6.) Minified css
