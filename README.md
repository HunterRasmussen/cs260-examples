# Example code for CS 260

## HTTP/CSS

Our goal in this section is to show examples of layout accomplished with pure HTML/CSS. There are two
primary considerations: basic layout of content, and a menu system.

### gridflex

These examples show some basic usage of CSS Grid and Flexbox.

* index.html and style.css: Shows a basic grid system, with header,
  main, sidebar, and footer sections.

* portfolio.html and style2.css: Reuses the same grid system, but uses
  a flexbox within the main page area to display photos.

### menu

These examples show how to design a responsive menu in pure CSS. We
borrowed heavily from a tutorial at:

https://medialoot.com/blog/how-to-create-a-responsive-navigation-menu-using-only-css/

There are two different styles here:

* styles.css: mimics the styling found in the tutorial
* styles2.css: provides a more minimalistic style, to demonstrate how to customize the menu

You can switch between these styles by removing the comments around
the second CSS stylesheet link.

These examples use a basic CSS grid to layout content. We modify the grid layout with
a CSS media query to make the layout responsive to different screen sizes.

You can test responsive layout using the developer tools in your browser.

### bootstrap

These examples show how to use [Bootstrap 4](https://getbootstrap.com/).

* index.html and styles.css: Shows how to use a responsive menu from
  Bootstrap, with the same grid layout from previous examples.

* index2.html and styles2.css: Shows how to make a nearly identical
  layout using the grid system from Bootstrap, which is based on
  flexbox.

* examples.html and styles2.css: Shows various examples of Bootstrap
  components.

### bulma

These examples show how to use [Bulma](https://bulma.io/).

### vue-todo

This is an example todo list application using Vue
