# Code-journal
## Feb 1,2022 Journal Entry
### Why Responsive Galleries?
Mobile web traffic share has been growing every year and is over 65% now. People search for information, read, watch videos, buy goods and order services via mobile devices.
### To create a responsive image gallery with flex box.
- First, create the HTML. It’s a simple ``` <div> ```  that includes a couple of img tags. (add some class to your tag)
- Reset CSS before doing anything. Also add the ``` box-sizing: border-box ``` property to the whole page so that the paddings and borders will be included in the total width and height. I need remember to use this CSS rule for flexbox, as otherwise paddings and borders might disappear at the end of the rows.
- Set the flex container to ``` display: flex``` .
- Wrap the images. To wrapp images, use ``` flex-wrap:    ;``` default value is nowrap which means that all items are laid out in a single line. If we set it to wrap, the images will flow into a grid. 
- Use ``` justify-content``` to align the images.
### To create a responsive image gallery with grid
- I would consider about this procedure. link: https://www.freecodecamp.org/news/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c/
## Jan 28, 2022 Journal Entry
## Class notes 
### User Input types
-text
-radio buttons
-checkboxes
-datetime
-email
-color
-date
-tel
-and more...
### Add a label to each input
### Input type="submit" is used for the submit button
### Dropdown Menus use label, select, and option
```
<label for="desserts">Food Choices</label>
<select name="desserts">
  <option value="cake">Cake</option>
  <option value="pie">Pie</option>
  <option value="ice-cream">Ice Cream</option>
  <option value="cupcake">Cupcake</option>
</select> 
```
### TODO
To code a shipping information form with different type of ``` <input> ``` 
make it looks good and functional right.
practice with ``` dislay: grid;``` 
### issues
super confuse about ``` grid-item(grid column 1/-1)``` 
super confuse about  auto fit ? auto fill?
### how to resovle the problems
#### look up the documents.
https://www.w3schools.com/css/css_grid.asp
https://www.w3schools.com/css/css_grid_container.asp
https://www.w3schools.com/css/css_grid_item.asp
after read these , a lot better. but still a little confused.
will do more practices next week.



## Jan 24, 2022 Journal Entry
## class notes
### Terminology
- display
This property is used to set the layout of an element and its children.
- main-axis
This is defined by the `flex-direction`. If your flex-direction is set to row _(this is the default)_, then the main axis is horizontal. If your flex-direction is set to column, then the main axis is vertical. - items are set along this axis by using `justify-content`
- cross-axis
This is the other axis of a flex layout. It changes depending on your flex-direction - Items are positioned along this axis by using `align-items`
### Terminology
- flex container
: The parent element of flex items. A flex container can also be a flex item. Use properties such as `flex-wrap`, `flex-flow` etc to customize how the items in the container will be positioned and respond to one another.
- flex item
: Children of flex containers. Use properties such as `flex-grow`, `flex-shrink`, `align-self` to customize how flex items look and function.
### Site Navigation
Navigation should use a nav tag.
- You can have more than one nav
- It is conventional to put an unordered list inside your nav for links, but not essential
- To link to content on the same page, add an id tag to the link location and specify it in your link
- nav link = <a href="#link-on-page">Link</a>, then add the id to the element like: <h2 id="link-on-page">Text</h2>
- To open the link in a new tab use target="_blank" in your link tag-
- A nav is often found inside a header or above a header. It depends on the site.
## issue 
Things to watch out for:

Use heading and paragraph tags around text (all text should have a tag saying what kind of text it is
use the text types for font-size
be consistent with use of white space in css
add more white space and comments to code.
## TODO
Going to be more careful about the tags, font-size, white space.
Going to try validator before publish a page.
## Jan21, 2022 Journal Entry
### TODO
-understand basic html, and load font to html.
#### Basic HTML
##### basic sections of a document
- header
- navigation bar
- main content
- side bar
- footer
##### HTML for structuring content
To implement such semantic mark up, HTML provides dedicated tags that you can use to represent such sections, for example:
- -header: <header>.
- -navigation bar: <nav>.
- -main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
- -sidebar: <aside>; often placed inside <main>.
- -footer: <footer>.
##### HTML layout elements in more detail
  - -semantic wrappers
  - -Non-semantic wrappers
      span,div
  #### Font
  ##### font loading strategies
  - FOUT with Class – Best approach for most situations. (This works whether we use a font-hosting company or hosting our own fonts.)
  - Critical FOFT – Most performant approach. (This only works if we host our own fonts.)
  ##### Loading fonts with cloud-hosted fonts
  - link rel="stylesheet" href="https://use.typekit.net/your-kit-id.css"
### What I did
  - watched vedio on youtube: “Modern Layouts: Getting Out of Our Ruts” by Jen Simmons – An Event Apart Austin 2015
  - download a doccument software called Zeal. 
  - look up the wrappers and try to understand
### Problem and Resolve
  - Didn't meet any problems. but there are couple things need to be careful.
  - 1. download font as a file will make load in speed faster.
  - 2. when linking a font to html, i should be careful of copyrights.
  
## Jan 19,2022 Journal Entry

### I have to finish and submit the Dated Journal Entry today.
### I learnt Colour, typography and visual hierarchy.
1. Visual Hierarchy is used to rank design elements and influence in the order you want your users to view them. By using principles like contrast, scale, balance and, more, you can help establish each element in its rightful place and help the most important elements stand out.
2. Typography is the art and technique of arranging type to make written language legible, readable and appealing when displayed.
### Goal
My goal is try to be skilled in using figma.
### Todo
1. I gotta watch more coure vedios on youtube.
2. Find some practice and try to figure that out myself. 
3. Record the questions I couldn't solve.
4. Ask experienced people and remember the proper way to resovle that problem.
5. Repractice couple days later.

## Jan 12, 2022

##Jan 17, 2022
assignment due on today.
