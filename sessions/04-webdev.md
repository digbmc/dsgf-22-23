# 04. Web Development

2022.11.18

## Agenda

1. Updates and announcements
2. Web development

## Meeting notes

Note-taker: Mallory 

**Updates:** 

Alexis

-Got the bare bones of her HTML file (SVG) functioning! 

-Made with Visual Studio Code 

-Still has to put content in the pages, but clicking on the pages works

-Still trying to figure out how to layer real image over tracing (possible using CSS layout) 

-Been using beginner’s book on HTML 


Kari

-Working with ArcGIS online

-Found a basemap with no borders on it

-Still uploading catalogue 


Mallory 

-Zoomified several image options 

-Other options for mind map screen shot? (deep zoom images don’t usually work very well for those—they’re usually too low resolution) 


**HTML**

-Every element in an HTML document has an opening tag and an almost identical ending tag with a forward slash (ex: <p example text</p>)

-Attributes- helpful for grouping or linking elements 

-Self-closing tags- things that don’t have text in them

-Example tags: <html lang=“en” dir=“ltr”>
  
-Useful HTML elements (resource: HTML Mozilla) 

    Section, div- to break up the structure of your page (not visible) 

    p- paragraph, basic text unit that appears on its own line 

    Img- image, you can’t usually describe in plain text, usually just contains a link to the image file you’re displaying 

    a- anchor, anchor to a link

    h1- top level header (only use those for things that should be in a header because of screen readers) 

    h2- second level header 

    nav- for a navigation menu

    li- list item 
  
-Comments- visible when looking at code, but invisible in display of the page
  
-Web inspector- Chrome and Firefox right click on a web page and select inspect element 

-You can also view the page source (by right clicking on Firefox) 

-Loading speeds- minimal styles will load faster and are more accessible to people who don’t have broad bands 
    -An issue with Scalar, Wordpress—the page is being built every time you navigate to it, so it takes a long time 
    -Lots of Javascript or interactivity takes a long time to load 

**CSS, Cascading Style Sheets** 
  
h1 { 
  
font-size: 42px; 
  
}
  
-h1 – selector, specifies where the rule is going to apply 
  
-Cascading- you have rules and they often contradict each other; later rules override earlier rules
  
-Specificity- more specific selectors override less specific ones 
  
-Inheritance- some CSS properties are inherited from parent elements 
  
-Box model- every element has a series of boxes around it and you can give specific section (a section is element) sizes via width and height, padding, borders 
  
-You can put CSS rules inside HTML, but the better way to do it is in its own file, linked to the HTML 

-href- hypertext reference 

 **Domain of One's Own**
 
-File manager- where you tell it what you want on the web
  
### Business

- Project updates
- Spring semester: dates for showcase, meeting times?

### Web Development

- [activity](../resources/html-instructions.md)
- [Web Development: HTML & CSS slides](https://brynmawr-my.sharepoint.com/:p:/g/personal/amcgrath1_brynmawr_edu/Ebk0Itz2FClIj1Sbk5boNCYBa7Ip2LI8AAozEOYU8XJjFw?e=xixKog)
- [HTML & CSS tutorial](https://github.com/tri-cods/html-css)

#### HTML & CSS Resources
- Learning HTML
  - Self-paced interactive [HTML Tutorial](https://www.w3schools.com/html/) from w3schools.com
  - Free Code Camp [Responsive Web Design course](https://www.freecodecamp.org/learn/responsive-web-design/#basic-html-and-html5)
  - LinkedIn Learning: [HTML Essential Training](https://www.linkedin.com/learning/html-essential-training-4/) (2h 45m)
- Learning CSS
  - [CSS Diner](https://flukeout.github.io/)
  - Self-paced interactive [CSS tutorial](https://www.w3schools.com/css/) from w3schools.com
  - LinkedIn Learning: [CSS Essential Training](https://www.linkedin.com/learning/css-essential-training-3/) (4h 28m)
  - Templates and models
    - https://html5up.net/
    - http://www.csszengarden.com/


## Action items
- [ ] Add your updates by Thursday morning
- [ ] Sketch a wireframe/outline of your professional website
- [ ] Follow the [HTML & CSS tutorial](https://github.com/tri-cods/html-css) through the end of the HTML section
- [ ] Continue adding to your simple website: follow the instructions on [the tutorial challenge](https://github.com/tri-cods/html-css/blob/main/sections/09-create_site.md)
- [ ] Optional: read ahead about CSS or review using the resources


[<<< Previous](03-git.md) | [Next >>>]()

[Return to syllabus](../syllabus.md)

[Home](../README.md)
