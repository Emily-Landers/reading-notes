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

