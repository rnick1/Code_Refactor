# Code_Refactor


# This repository is the first homework assignment for the University of Washington Full-Stack Coding Bootcamp!

### Refactoring is the process of taking an existing webpage and making it more efficient without changing it's visual appearance.

## The Assignment:

> GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

### To accomplish this, the coding for the webpage needed to be inspected for completeness, consistency, semantics, and other issues. Here is what I did:

## On HTML:

-I replaced less semantic tags such as ```<div>``` with ```<section>```tags. This will make it easier for browsers to read. I also added ```<nav>``` and ```<img>``` tags where possible.

-I also improved the spacing and indentation in the HTML code to better reflect the different parts of the webpage 
![Screenshot](Code_Refactor\assets\Content_Section.png)

-There were some instances where classes and id's were refined slightly to reflect the improvements made on the stylesheet.

-Also worth noting, the original webpage had a nav link (titled "Search Engine Optimization) that wasn't functional which I was able to repair by fixing issues with the id.

## On the stylesheet:
-I was able to condense the stylesheet by consolidating many of the redundant parts. This was especially obvious in the styles for the sidebox of the webpage. ![Screenshot](Code_Refactor\assets\Aside.png)

### Overall, after my edits, this webpage should be more readable with simpler HTML and CSS code!

### Note: This website is live! The URL is: