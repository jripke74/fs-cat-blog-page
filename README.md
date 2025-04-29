# fs-cat-blog-page

In this workshop, you will build an HTML only blog page using semantic elements including the main, nav, article and footer elements.

Step 1
In this workshop, you will practice working with semantic HTML by building a blog page dedicated to Mr. Whiskers the cat.

To begin the project, add the <!DOCTYPE html>, and an html element with a lang attribute of en.

Remember that you learned how to build a basic HTML boilerplate like this in the previous module.

Example Code
<!DOCTYPE html>
<html lang="en">
<!--all other elements go here-->
</html>

Step 2
Inside the html element, add a head element.

Step 3
Inside your head element, nest a meta element with the charset attribute set to the value "UTF-8".

Below that meta element, add a title element.

The title element's text should be Mr. Whiskers' Blog.

Step 4
To prepare creating some actual content, add a body element below the head element.

Step 5
The first section you will build out is the page header.

The header element is used to represent introductory content like page navigation and other introductory information.

Here is an example using the header element:

Example Code
<header>
  <h1>Main Page Title Goes Here</h1>
  <img src="example-logo.png" alt="Example logo" />
</header>
Inside the body element, add a header element.

Step 6
The header will be responsible for displaying main title, image and page navigation for the blog.

Inside the header element, add an h1 with the text of Welcome to Mr. Whiskers' Blog Page!.

Step 7
In this introductory content, you will want to show an image of Mr. Whiskers with a caption.

Below the h1 element, start by adding a figure element.

Inside the figure element, add an img element.

The src attribute of the img should have a value of "https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg" and the alt text should have a value of "a cat peacefully sleeping".

Below your img element, add a figcaption with the text Mr. Whiskers Sleeping.

Step 8
For your blog, there should be a way for users to navigate to different sections on the page.

The nav element is used to provide navigation links to other sections in the document or other sections in the website. A lot of times you will see the nav element used for menus or table of contents.

Here is an example of using the nav element:

Example Code
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
Below your figure element, add a nav element with a ul element nested inside.

Inside the ul element, add three li elements.

Step 9
Inside each of the li elements, you will need to have an anchor element.

For the first anchor element, the text should be About and the href attribute value should be "#about". The hash symbol in front of the about represents an id name which be added later on in the project.

For the second anchor element, the text should be Posts and the href attribute value should be "#posts".

For the third anchor element, the text should be Contact and the href attribute value should be "#contact".

Step 10
Now that you are finished building out the page header, you will need to start adding your main content.

Below your header, add a main element.