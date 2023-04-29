SITE STRUCTURE
==================

What are HTML and CSS?
--------------------------


All websites use HTML and CSS. After learning both of these languages, you will be ready to build your own website!

1. HTML stands for Hyper Text Markup Language. It is used to give websites structure with text, links, images, and other fundamental elements.

2. CSS stands for Cascading Style Sheets. It is used to change the appearance of HTML elements.


Instructions
===============

An individual page of a website is referred to as a webpage. Notice the webpage in the web browser. During this lesson, we will explore the HTML elements used to build it. Click Next to learn about the anatomy of an HTML element.

SITE STRUCTURE
Create an Unordered List
Impressive! With just five page elements, you’ve already created an interesting website!

Another essential HTML element is the unordered list. Items in an unordered list are referred to as list items. Each item is bulleted, not numbered. For example:

A list item
A second list item
A third list item
The HTML code for the list above:

<ul>
  <li>A list item</li>
  <li>A second list item</li>
  <li>A third list item</li>
</ul> 



About unordered lists:

ul tags create the unordered list.


li tags contain each list item.

Unordered list elements can be used to organize content on a webpage in a number of ways. Below we will use one to organize our website’s navigation menu, sometimes called a navbar.




Instructions
1.
Our navbar will go above the company heading h1 element, so first we will need to create some new lines. In index.html, press enter to create several new lines between <body> and <h1>.

First, we will create an h2 element to serve as the heading for the navbar. The text can read “Ollie”.

<h2>Ollie</h2>
Run your code to continue.

Checkpoint 2 Passed
2.
Below the navbar h2, create an unordered list element. The list items will be different pages a site user can visit:

<ul>
  <li>sign up</li>
  <li>search bikes</li>
  <li>reserve a bike</li>
  <li>about us</li>
</ul>
After you insert all the list items, don’t forget to close the unordered list with a closing </ul> tag.

Run your code to view the results in the web browser.

Checkpoint 3 Passed
Anchor Elements
=================

Nice work! The webpage is starting to come together.

What if you wanted to link users to a different webpage? The HTML anchor element makes it possible to do this with a single click.
-----------------------------------------------------------------------------------------------------------------------------------

<a href="http://google.com">Click here for Google!</a>
Anchor elements use an attribute to link users to websites. Attributes customize the behavior or appearance of HTML elements. Anchor elements use the href attribute, which specifies the webpage to link to. In the example above, the text “Click here for Google!” links to http://google.com.



IMPORTANT: Web addresses, such as http://google.com, have a technical name: URL.
---------------------------------------------------------------------------------

Instructions
1.
Let’s create an anchor element to send visitors to a webpage that lists cities where Ollie bike sharing is available.

Between the opening <p> and closing </p> tags, after the last sentence, enter this text:

Here is a list of cities where you can find us. 
Run your code to continue.

Checkpoint 2 Passed
2.
Next, use an anchor element to link the word “list” to the URL cities.html.

Here is a <a href="cities.html">list</a> of cities where you can find us. 
Note: cities.html is within the Ollie site folder, so we do not need to specify a full URL


Link to lesson below
=======================
https://www.codecademy.com/courses/make-a-website/lessons/site-structure/exercises/add-heading

SITE STRUCTURE
-----------------

Add a Heading
----------------

Now, let’s learn more about the heading element.

Headings are a frequently used HTML element. You can think of them like headlines in a newspaper. Your eyes may notice headings first because the words are large and bold compared to other text on the webpage.

There are six heading elements: h1, h2, h3, h4, h5, and h6. h1 is the largest heading and h6 is the smallest.

For best practice, you should avoid skipping heading levels. There should also be only one <h1> per HTML page. Although skipping heading levels or using multiple <h1> elements will not cause errors in your code, it is important to keep >

