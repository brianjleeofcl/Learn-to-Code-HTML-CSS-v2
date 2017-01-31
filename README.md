# Learn to Code HTML & CSS
Brought to you by Galvanize. Learn more about the way we teach code at [galvanize.com](http://galvanize.com).

## Overview
We're going to provide you with a fun introduction to the world of web development, starting with HTML and CSS. By the end you'll have created your own basic web page.

#### Here's what we'll be doing:
* Setting up our computers for web development
* Overview of basic HTML concepts
* Overview of CSS concepts
* Playing around in the sandbox

#### Before you begin, a quick gut check:
* This course is for absolute beginners
* Feel free to move ahead
* Help others when you can
* Be patient and nice
* You will get through it!

#### What web coding is (really)?
Recipes to give to your computer to “cook” up some awesome things for you online

## Setting up your computer
(Brace yourself...)

#### Please set up the following:
* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (http://chrome.google.com))
* A text editor to modify your files (Recommend the Atom text editor: [Atom.io](http://atom.io))
* Download the tutorial files on this page within the zip file  

#### Download the files for this class:
1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-HTML-CSS
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. IMPORTANT! Leave all the individual files in the downloaded folder (if you would like to move it out of the downloads folder move the entire folder, not individual items)
5. From Atom: File > open, select the folder and then click "Open"
6. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
7. *Now if you already know some of what we're talking about,* you're all set to poke around in the files -- `index.html` and `CSS/style.css` are the two files we will using.

Patience! Setting up your computer takes time and can be tricky, especially across platforms.

Once you're ready, you can move onto the next lesson.

## H.T.M.L. - "the building blocks of the internet"

Hyper Text Markup Language, or HTML, is the most elemental language of the internet. Everything you see within your web browser is an interpretation of HTML in some form of other, and it is essential to learn in all web development.

As web applications become more complex—and browsers more capable—it is useful to separate out different functionalities. HTML governs the structure and content of a webpage while CSS controls how the content is displayed on the page.

###### The syntax of most HTML is as follows:
* `<Tags>` - code that wraps around the content of HTML to designate a particular effect, sometimes inherent to the tag.
* `Attributes=""` - code inserted into tags to implement a particular effect that is external to the tag.
* Elements - the combined syntax of tags, attributes, and elements.

```
e.g. Element = <tag attribute=”blahblah”>content content</tag>
```

#### HTML Tags:
Tags are used to mark up the beginning and end of an HTML element.

Almost everything in HTML needs to start and end with a tag
Everything is wrapped like layers of an onion, `<opened>` and `</closed>`
- e.g. `<div>”Hello!”</div>`
- *Note: not every tag is like this!*

The index.html page currently has a number of elements already in place. Each element's tag contains clues for the appropriate content as well as the element's context in the overall structure.

###### Tags used mainly for structure:
- `<html>` designates document as HTML
- `<head>` contains undisplayed information
- `<body>` contains displayed information
- `<header>, <main>, <footer>` denotes which part of the page elements belong
- `<nav>` contains navigation menus
- `<section>` contains a section
- `<div>` creates a division of elements, often used for content-neutral grouping

###### Tags used mainly for content:
- `<h1> - <h6>` create section headings
- `<p>` creates paragraphs
- `<a href=""></a>` (anchor), activates a link in the page
- `<ul>, <ol>` creates lists
  - `<li>` contains items in lists

###### Self-closing Tags:
- `<img src="">` creates an image in the page
- `<br>` creates a break in the content
- `<input type="">` creates an input field

#### HTML Attributes:
HTML attributes inform the browser on what to do with a tagged piece of content.
Attributes generally appear as name-value pairs.
```
<p class="foo">This is the content of an element with class 'foo'.</p>
```
###### The most common attributes are:
- `id=""` - id is used on only a single element"
- `class=""` - class can be used on multiple elements"
- `style=""` - add some color, font, margins, etc.
- ^ *There’s a MUCH better way to do this via CSS - more on that later!*

How do we check elements for whether they're talking to the browser? Use the **inspect element** feature!

#### LET'S CODE!

###### Remember:
- Coding can be hard - be patient!
- Work in pairs! Even the pros do it
- Ask for help - we’re in a school!

#### Let's get started!
1. Open up your text editor
2. Navigate to your repo
3. Open up index.html

#### Fill out your website
1. In the index.html file, add the following:
	- Name of your website in the header (hint: consider using a heading tag)
	- A picture in the figure section of your main page
	- Two very short paragraphs in the middle section
	- An ordered list and an unordered list in the last section
	- A short copyright notice in the footer

2. (advanced) Add the following:
	- Insert a caption under your picture
	- Insert a youtube video in your main page
	- Add a link to your email address in the copyright notice
	- Add a navigation bar in the header of the page

But... how do we make HTML... better?

## Overview of CSS

What Does CSS Stand for?
- Cascading - prioritizing certain values over others
- Style - focusing on layout, colors, fonts, etc.
- Sheet - another name for the file we use here

The internet used to be ugly. Enter CSS - a consolidated way to make it prettier.

#### Three primary objects:
- Elements: e.g. h1, div, body, a - default HTML (already reviewed)
- IDs: everything that starts with a “#”
- Classes: everything that starts with a “.”

#### Syntax of CSS:
```
h1 {  // this is either an element, class, or ID
	font-size: 24px; // syntax is name: value;
	font-weight: bold;
	color: #000000; // hexadecimal, RGB, etc.
}
```
Don't forget the semicolon – *;* – otherwise the styles might not work!

#### What are IDs?
IDs are attributes that are used only on one element ONLY and noted with a “#” symbol in CSS
e.g.
```
HTML:
<a id=”leesName”>Lee Ngo</a>

CSS:
#leesName {
	color: white;
}
```
IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

*e.g clicking to a specific part of page*

#### What are Classes?

Classes are attributes something to multiple elements on a page noted with a “.” symbol in CSS.
```
HTML:
<a class=”ninja”>Lee Ngo</a>

CSS:
.ninja {
	color: black; margin: 10px;
}
```
Classes are used to change or affect multiple items in an HTML document at once

*e.g. everything with class=”ninja” should have the same attributes*

In tandem, you can do a lot with HTML & CSS! Let's give it a shot!

## LET'S CODE!

###### Remember:
- Coding can be hard - be patient!
- Work in pairs! Even the pros do it
- Ask for help - we’re in a school!
- There are many ways to accomplish the same task; eventually you'll develop a sense of what is preferred

#### Cleaning up your website
1. Using `height` and `width`, resize the image on your page
2. Make your header look distinct from the rest of the site. Add a `border`? Different `background` colors? Some `margin`? Plenty of ways to accomplish this; try different things and decide what you like.
3. Try using `text-align` with `left`, `center` and `right`
4. (adv.) Can you think of a way to have the two paragraphs in the middle section appear side-by-side? (hint: `display`)
5. (adv.) Can you think of a way to apply the same style to even-numbered elements on the ordered list?

#### Let's change the font!
1. Navigate to Google Fonts: https://www.google.com/fonts
2. Find a font you like and click "Add to Collection".
3. On the bottom right side of your screen click "Use".
4. On the "Use" page, scroll down to "Number 3" and copy the link tag provided.
5. Paste that link tag in your index.html file with the new link tag you copied from Google Fonts.
6. Copy the CSS code under “Number Four.”
7. Paste that code into your CSS under the body tag.
8. Save and refresh!

Did it work? Great! If not open up **Inspect Element** and see what happened.

## Play around in the sandbox!

Apply what you've learned so far to customize how your site looks. Stuck? Ask for help! Alternatively, there are lots of resources online as well.

# YOU DID IT! YOU'RE NOW A CODER!

Welcome to the cool kids club.

#### Want to code more? Check out Galvanize's Web Development Immersive Program!

- 24 Week Full-Time Program
- 91% Job Placement Rate within six months
- Average starting salary: $77,000 per annum
- Scholarships available for those who qualify
- Learn more at http://galvanize.com/courses/web-development/

For the most up-to-date figures, check out this [site](http://www.galvanize.com/citations/).

#### Looking for something more flexible? Check out our Evening Workshops!

- Learn more at http://www.galvanize.com/workshops/

#### About the Authors

[Brian Lee](https://linkedin.com/in/brianjleenet) needs to add his bio and contact information here, if so inclined.

[Lee Ngo](http://linkedin.com/in/leengo) is an evangelist for Galvanize based in Seattle. Previously he worked for UP Global (now Techstars) and founded his own ed-tech company in Pittsburgh, PA. Lee believes in learning by doing, engaging and sharing, and he teaches code through a combination of visual communication, teamwork, and project-oriented learning.

You can email him at lee.ngo@galvanize.com for any further questions.
