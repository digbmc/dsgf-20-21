# 04. Web Design & Development

## Agenda
1. [Business & Updates](#meeting-notes)
2. [Web development](#web-development)
3. [For next time](#for-next-time)

## Meeting notes
Note-taker: Zach

### Business
- Talked about DS vids Zach sent; And Anaconda. Alice does not run python through Atom.
Tutorials can be very specific but might include elements unessential for your task.
- Anaconda allows you to run multiple versions of Python at the same time.
- Virtual python environments
- A., K., Z. will meet at 2pm on Friday. Invite sent.
- Thu looked up database for papyri and epigraphy (not nec. philology)
- GitHub: see how it looks before you create pull request
- Be sure to save these markdown files as a .md
- "What is the internet?"
  - Seems less complicated than we thought. Satellite vs. wire based infrastructure.
  - Conversation about data security - not prioritized enough.
  - K. noted relationship between speed of distribution of info enabled by internet with demands of capitalism. Culture shift in time demands.
  - A. noted: Environmental issue - people thought it would be great for the environment (smaller carbon footprint). Environmental toll of servers and traffic. Data gets bigger and more complicated. Human rights imprint of tech.
  - "Digital divide" and economics due to Covid.
  - solar.lowtechmagazine.com - "static website" - flat set of html and css files rather than being based on a database that structures the data.

### Web Development

- html - building block of internet. Every webpage generates html.
- "The stack" = full stack programmer can do back end and front end web development (how things are structure (html) and displayed (css)).
- JavaScript gives interactivity through rewriting html and css (which we will not do).

- 1) HTML = Hypertext markup language.
-   Hypertext - text linked in various ways so you can move through it.
-   Early on there were hypertext novels and it did not change the world like was predicted. Hard to run now.
- 2) Markup - ways of encoding language - markdown "light structure"; html "heavy structure"

- 3) Basic structure - opening tag - text - closing text. <p> Hey there! <p>
-   head element is just intepreting the metadata of the site.
-   open with <html>
-   attributes - signal things like language lang="en", direction of text reading "ltr"
-   <!DOCTYPE html> - tells the doc it is an html documentation
-   indentation important for looking at things, keeping organized, but not crucial
-   charset="utf-8" - signals what type of text encoding to use.
-   <title> - what will appear in the tab. Label for the page.
-   close with <html>

- 4 )HTML trees & Nesting.
-   Root element - html, then most of body will be embedded as an element under the root.
-   use mozilla developer docs for front end development; also the w3 schools shows detailed html code
-   <div> somewhat meaningless but is good for dividing elements on a page.
-   <ul> unordered list. Lists items marked as <li>
-   to view page html and css - inspect element or go to view/developer in your browser.

- 5) CSS - "Cascading Style Sheets" and specificity
-   cascading - later rules override earlier rules (more specific overrides less specific)
-   selector h1 then curly brace {}
-   can apply styles to various elements of html such as <a> elements or the entire <li>. These are hierarchical - more specific overrides less specific.
-   Inheritence - properties not specified will take on the attributes of another element, also hierarchically arranged (parent-child, not nearest neighbor)

- 6) CSS box model - width < height < padding < border < margin
-   Common properties: TEXT - font-size, font-family, color, line-height, letter spacing; OTHER ELEMENTS - styles such as color and the box model.

- 7) CSS lives: inside the html head, inline html, or separate space (most common) best to. have in a  separate document

- ACTIVITY -
-   Lit Ipsum for generic text
-   Alt-text for image accessibility
-   unsplash for creative commons pictures

- OTHER NOTES:
-   Wireframing - draw out your site style before writing it in html/css
-   Revist CSS Diner for classes and id's (so different things can have different styles.)

- https://html5up.net/ 
- https://www.w3schools.com/w3css/defaulT.asp 
- https://tinyurl.com/web-int


#### Instructions

1. Use command line to navigate to the folder where you're keeping your dssf files  `cd`
2. Create a new directory (folder) for your new site `mkdir my-site`
3. Create a document in the directory and name it 'index.html' `touch my-site/index.html`
4. Create a css document in the same place `touch my-site/style.css`
5. Open the project in Atom
   Try `atom my-site/index.html` - if that doesn't work, open Atom --> File --> Add Project Folder
6. In Atom, type html and hit tab: voila! You have a web page!
7. Add some elements and text. Save it, and open index.html with a web browser. You should see your website.
8. Link your CSS: in the 'head' section of index.html, type this:

```html
<link rel="stylesheet" type="text/css" href="style.css">
```
9. Open style.css and write some css to style elements from your index.html file. Save it, open your browser, and refresh it to see your styled page.

### Resources

- Learning HTML
  - Self-paced interactive [HTML Tutorial](https://www.w3schools.com/html/) from w3schools.com
  - LinkedIn Learning: [HTML Essential Training](https://www.linkedin.com/learning/html-essential-training-4/) (2h 45m)
- Learning CSS
  - [CSS Diner](https://flukeout.github.io/)
  - Self-paced interactive [CSS tutorial](https://www.w3schools.com/css/) from w3schools.com
  - LinkedIn Learning: [CSS Essential Training](https://www.linkedin.com/learning/css-essential-training-3/) (4h 28m)
  - Templates and models
    - https://html5up.net/
    - http://www.csszengarden.com/
  - Examples of professional academic websites
    - [Rachel Starry](http://rachelstarry.org/)
    - [Sara Grossman](https://www.sarajgrossman.com/)
    - [Rachel Buurma](https://rachelsagnerbuurma.org/notes/)
    - [Jenni Glaser](http://jenniglaser.digital.brynmawr.edu/)

## For next time
- [ ] Add your updates by Monday morning
- [ ] Create a wireframe for your professional website
- [ ] Review the [slides on web design](https://tinyurl.com/web-int)

[<<< Previous](/03-disciplines.md) | [Next >>>](/05-web-publish.md)

[Return to syllabus](../syllabus.md)

[Home](../README.md)
