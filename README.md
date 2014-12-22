NEDAutoParts_Example
====================

A brief intro in to some of the work I have done on www.nedautoparts.com.

This is a website built on Shopify, which is an e-commerce CMS solution. You can choose a theme, and then code on top of it with whatever you see fit. Shopify's API makes it easy to mold things to the site using your own coding. This is beneficial as Shopify's own custimization falls short at times. 

The page above involves a variety of different items, and is a page that is passed through when called upon from the main page of the site. Shopify uses a markup language called "Liquid" and it is very simliar to Ruby.

As it sets up the page, it uses typical HTML elements to break the page up in to it's proper parts, and then various CSS selectors for styling. Within those elements, you can see the Liquid markup that passes various FOR loops and IF/ELSIF conditions. This allows us to pass through various "tags" as Shopify calls them, related to whatever options the user picks from drop down menus. 

This is still a work in progress, and will continue to evolve. I am working on adding a Filter Menu that will allow the user to be able to pin point what parts they are looking for even further. This will be accomplished using AJAX and jQuery. 
