# Getting Started

## Setting Up Your Project 

To set up your project, first (if you haven't already), create a folder somewhere on your computer and name it something like "Projects".  This is where all of your programming projects will be stored.  I recommend creating the "Projects" folder (also known as a directory) in your home folder.  Usually projects are labeled with the name of the user account that you are logged into.  If you are familiar with file paths, it would be located here: ~/Projects where the '~' is the symbol for the home directory.

After you have created your "Projects" directory, create another directory (or folder) inside of it and call it "Getting Started"

## Creating Your First Web Page

We are going to start by creating your first web page. This will be like the 'Home' page of your web site.  It will be called 'index.html'.  It is important to call it index.html because the web browser will be looking for it by that name.  So first create a file called index.html and copy and paste the following snippet of code (in html it is actually called markup instead of code) into your index.html file.
``` 
<!--index.html-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <title>My First Web Page</title>
</head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

Save your file.

You should be able to open your file in a web browser by double clicking on it. 

Your web page should open with a white screen and "Hello World" in the top left corner as shown in the 'Hello World.png' file

## Learning about tags

Tags are the basic building blocks of html.  A tag is created by using the '<', '/', and '>' characters with text between them like this:
```
  <div>Stuff</div>
```

The above example is called a *div* tag.  The '<' and '>' characters 'sandwich' the tag name which in this case is 'div'.  The '/' character is used to indicate the closing of a tag.  As explained on the [w3schools website](http://www.w3schools.com/tags/tag_div.asp), "The *\<div\>* tag defines a division or a section in an HTML document."  It is the most basic html tag.  It basically functions as a box or container for various other web page content.  Tags are composed to create full web pages.  Tags can be contained by other tags.  For example:
```
  <div>
    <div>
      <div>
        <div>There is stuff in this div tag</div>
      </div
    </div>
    <div>There is other stuff in this div tag</div>
    <div>More stuff</div>
  </div>
```

The above example demonstrates how div tags can be composed to create structure to our web page.  If we look at divs as boxes, we could say that there is one big box that has 3 other boxes in it.  And one of those 3 boxes has another box in it, which has another box in it.  Which has the text "There is stuff in this div tag" inside it.  The other two 2nd-level boxes each have text in them: "There is other stuff in this div tag" and "More stuff".  When a tag is inside another tag, we can say that it is 'nested' in the tag.

## What are 'Heading' or 'H' tags?

So we talk about tags...  Html is flexible and powerful, and that is, in part, due to the various types of tags that can be used.  Each of these tags is programmed to behave a specific way.  Heading tags or H tags are a way of adding text that is already formatted to be heading text.  They look like this:
```
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
```

Heading tags only exist for numbers 1 - 6.  There is no <h7></h7> tag.  Go ahead and remove the *<h1>Hello World</h1>* tag.  Then copy the above H tags and paste them into your index.html file here:
```
... 
  <body>
    
    <!-- PASTE IT HERE -->
    
  </body> 
...
```
Go to your web page in your browser and refresh the browser.  You page should now display the headings as shown in the heading-tags.png file.

Your index.html file should look something like this:
```
<!--index.html-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8"/>
    <title>My First Web Page</title>
  </head>
  <body>

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

  </body>
</html>
```

## Tasks

- [ ] Create your directory - [Setting Up Your Project](#setting-up-your-project)
- [ ] Create your index.html file - [Creating Your First Web Page](#creating-your-first-web-page)
- [ ] Make your page look like hello-world.png
- [ ] Make your page look like heading-tags.png