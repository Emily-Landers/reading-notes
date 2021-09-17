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


