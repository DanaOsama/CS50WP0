# Project 0

Web Programming with Python and JavaScript

**The Homepage**
Everything in the page is contained within a div, known as the parent container, whiich has a maximum width of 1200 pixels, a margin of zero auto and a padding of zero.

All my pages start with the navigation bar on top. It is mobile-friendly and is built with the help of Bootstrap CSS classes. The active link has an active class attached to it.

They all start with a jumbotron as well, with the name of the page and a little sentence underneath that.

Using Bootstrap's grid system, I create two columns (without including any numbers, which means that both columns will be the same size) one with text and one with a picture. The text explains why the website visitor would want to visit Egypt. 

Finally, I embedded a short video from youtube about Egypt in an iframe.

The libraries included below are used for the buttons (the toggle button in this case) to work.

At the bottom of this page - and every page - is a fluid container with the words "All rights reserved © 2019".
__________________________________________________________________

**The Places To Visit Page**

After the navigation bar and the jumbotron, a small container (a div with a class of container) introduces the page. The page uses cards to display the different monuments of Egypt. The cards are placed in a Bootstrap grid. Each one of the cards has an image on top, and some text at the bottom.

__________________________________________________________________

**The Plan Your Stay Page**

As usual. Navigation bar. Jumbotron.

I created a container with two columns (same as before). The first column contains a paragraph explaining how the "company's" packages work, and the second column has a picture related to Egypt with a caption underneath. 

Following this, I created a responsive 5x5 table (using Bootstrap classes). Each column in the table describes one of four packages, the time at which the tour will take place, and the prices (normal and premium).

After this table, I created a container with some text decribing how the user should use the form below.

I made yet ANOTHER container with two columns. The first column is a picture, and the second is a form. 
The form allows the user to enter his/her _full name_ and  _email address_, choose a package from a drop-down list (which is a form-group Bootstrap class), select whether its a premium or normal bundle using radio buttons, enter the number of adults and children and finally choose a week for the trip from a drop-down menu. Then a submit button.

__________________________________________________________________

**The Contact Us Page**

Navbar. Jumbotron.

A small container contains text in h3 just to introduce the page.

Another container with two columns (a picture in one and a form in another). The form lets the user enter his/her name, email, and a message. Then a submit button. 

Following this, a small container has contact informtation like address, phone number, and email.

__________________________________________________________________

**styles1.css**

It specifies where each font is used and whatnot, using sass.




