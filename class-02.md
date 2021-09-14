# HTML and CSS 
## Chapter 2

- 6 levels of headings h1-h6 largest being 1
- <p> is for paragraph 
- <b> will make text bold
- <i> will make text itallic
- <sup> used for superscript like raising a number to a power 
- <sub> used for subscript
- white space collapsing more than one space is read as one space
- <br /> makes a line break 
- <hr /> creates a break between themes
- visual editors are like word processors, they allow you to control the presentation of the text
- code views shows you the code created by the visual editor so you can manually edit it
- semantic are text elements that are not intended to affect the structure of your webpages, but add extra info to the pages 
- <strong> element shows strong importance
- <em> shows emphasis that subtly changes the meaning of a sentence, will show as itallic in browser
- <blockquote> used for longer quotes that take up an entire paragraph 
- <q> used for shorter quotes 
- <abbr> used for abbreviation or acronym 
- <cite> used for citations
- <dfn> first time you explain new terminology 
- <address> contains contact details for the author of the page 
- <ins> used to show content that has been inserted into a document
- <del> used to show previously deleted content
- <s> shows something that is no longer accurate or relevant

## Chapter 3
- css assigns rules to html elements with a declaration inside curly brackets
- <link> lives inside the head links the external css file
- link should contain href type and rel
- <style> is used for internal css
### Selectors
- universal selector *{} targets all elements on the page
- Tupe selector h1, h2, h3 etc {} targets the specific elements
- Class selector .note{} targets any with value of note or p.note{} targets only p elements
- ID selector #introduction {} targets any element with value of introduction 
- child selector li>a {} targets any a elements that are children of li elements 
- descendant selector p a {} targets and a elements in p elements
- adjacent sibling selector h1+p {} targets the first p element aafter any h1 element
- general sibling selector h1~p {} if you have two p elements that are siblings of h1 element it would apply to both

- CSS is cascading (last alteration will take precedence)
- use an external sheet to make all your webpages share the same style sheet
- external style sheets will make html code easier to read
- place css in the same sheet as your html if you are only creating a single page 
# JavaScript
- a script is a series of instructions for your computer to follor
- each individual step is a statement
- javascript is case sensitive
- curly braces are known as code blocks
- add comments using // to explain what your code does
- a variable is something that is assigned value
- a value for a variable can change each time a script runs
- find your keyword first then name your variable then assign it a value
### Data types
- Numerical data type handles numbers and is used for tasks that involve counting ex. 0.75
- String data types use letters and other characters, they can be used with any kind of text ex. 'Hi, Ivy!"
- Boolean data type can be true or false for their values, helpful in determining which part of a script should run
- variables can be used to store any of these data types
- the value of a variable can be changed later in the same script 
- just use the variable name and = and the new value
## Rules for naming variables
- must begin with a letter, dollar sign, or underscore
- the name can contain those characters as well, but not a period or dash
- can not use keywords, or reserved words
- they are case sensitive
- should describe the information that the varuable stores 
- if the name is made up of more than one word use a capital letter for the first letter of every word after the first 

#### Arrays 
- arrays store lists of variables
- looks like this: var colors; 
                    colors = ['white', 'black', 'custom']
- accessed as if in a numbered list 
- list numbering starts at zero 
- called an index
- to access will look like this: var itemThree; 
                                    itemThree = colors[2]
- length holds the number of items in an array
