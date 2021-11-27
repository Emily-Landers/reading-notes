# Class 4 Reading Notes
### Links
 **Links allow you to move from one web page to another**
 #### Writing Links
 - Created using < a >
 - < a > has an attribute called href 
 - the value of the href will be the full web address for the site, which is known as an absolute url
 - relative urls can be used when linking to pages within the same site, they are basically shorthand
 #### Directory Structure
 - Organize code by placing the pages for different sections into a new folder
    - Structure (top level folder known as the root folder, contains all other files)
    - Relationship (described using same terminology as a family tree)
    - Homepages (main home page of a website)
#### Relative URLs 
- can be used when linking to pages within your own website
- tells the browser where to find your files
- Relative links have multiple types
    - Same Folder links to a file in the same folder
    - Child Folder use the name of the child folder followed by / then the file name
    - Grandchild Folder uses the name of the child folder / the name of the grandchild folder / then the file name
    - Parent Folder uses ../ to indicate the folder above the current one then follow it with the file name
    - Grandparent Folder uses ../ followed by the file name
#### Email Links 
- to create a link that starts up the users email use mailto:
#### Opening Links in a New Window
- in the opening < a > tag use target="_blank" to open a link in a new window
**Linking to a specific part of the same page**
- use the command ID to link to a specific part of a page.
- ex. < h1 id="top" >
- use the < a > element again
# Chapter 15 CSS and HTML Layout 
- CSS treats each HTML element as if it is in its own box 
    - This box will either be a block-level box or an inline element
    - Block-level elements start on a new line < h1 > < p > < ul >
    - Inline elements flow in between surrounding text
- If one block level element sits inside another block level element then the outer box is known as the containing or parent element
- its common to group a number of elements together in a < div >
#### Positioning schemes in CSS
- **Normal Flow**
    - every block level element appears on a new line causing each element to appear lower on the page
- **Relative Positioning**
    -moves an element from the postion it would be in normal flow shifting it to the top, right, bottom, or left of where it would have been placed. does not affect the the postion of elements around it. 
- **Absolute Positioning**
    - positions the element in relation to its containing element
- when you move any element from normal flow boxes can overlap the z-index property allows you to control which box appears on top.
- **Normal Flow**
    - position:static
    - used to create default html flow
    - you can specify width 
- **Relative Positioning**
    - position:relative
    - moves the element in relation to where it would have been in normal flow
- **Absolute Positioning**
    - position:absolute
    - when the position property is given a value of absolute the box is taken out of normal flow and no longer affects the position of other elements on the page
- **Fixed Positioning**
    - position:fixed
    - requires the position property to have a position of fixed 
    - positions the element in relation to the browser window
    - when scrolling it will stay in the exact same place
- **Overlapping Elements**
    - z-index
    - used to control which element sits on top
    - value is a number, the higher the number the closer the element is to the front
- **Floating Elements**
    - float
    - allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible 
    - anything else in the element will flow arount the floated element
    - should be used with width to show how whide the element should be 
    - can be used to place elements side by side 
    height can affect where the floating elements sit
- **Clearing Floats**
    - clear
    - allows you to say that no element (within the same containing element) should touch the left or right hand sides of a box 
    - can take left, right, both, or none for value
- **Parents of Floated Elements Problems**
    - If a containing element only contains floating elements some browsers will treat it as if it is zero pixels
- **Sloution**
    - add an extra element after the last floated box to fix this problem 
    - alternatively in CSS you can apply the overflow property with a value of auto and set the width to 100%
- **Creating multi-column layouts with floats**
    - use the < div > element to represent each column 
    - use widts, float, and margin to position the columns
#### Screen Sizes
- **fixed width layout designs do not change size as the user increases or decreases the size of their browser window**
- measurements given in pixels 
- pixel values are accurate 
- more control over appearance 
- control over the length of lines of text regardless of the size of the users window 
- img size will always remain the same 
- can cause big gaps around the edges of the page
- if the users screen is higher resolution than the creators the page can look smaller and text can be harder to read 
- design works best on devices that have similar resolution to the designers 
- often takes up more vertical space than a liquid layout with the same content
- **Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window**
- tend to use percentages
- pages expand to fill the entire browser window so there are no spaces around the pages
- page can contract to fit a smaller screen 
- tolerant of user settings 
- 
