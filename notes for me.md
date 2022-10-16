# adriannachong.github.io

--- How CSS ID Selector is Used ---

The id selector is used for selecting a single HTML element with a unique id attribute value.
    For example: header, footer

Note the use of # (hash) in front of the id name while applying the CSS rule. 


Will look like this in your HTML:
   
   
Will look like this in your CSS:

    #header { 
        width: 100%; 
        height: 80px; 
        background: blue 
        }

--- How CSS Class Selector is Used --- 

The class selector is used for selecting a single or a group of HTML elements with the same class attribute value. In the example below, you will see three paragraph elements <p> with a class attribute value of content.

How it will look in your CSS:

    .content { margin: 20px 0; line-height: 24px; font-size: 15px }

Note the use of . (dot) in front of the class value while applying the CSS rule.

--- When to Use Class vs ID in CSS --- 

The basic rule that you need to keep in mind while using classes and ids in CSS is that, id is used for single elements that appear on the page for only once (e.g. header, footer, menu), whereas class is used for single or multiple elements that appear on the page for once or more than once (e.g. paragraphs, links, buttons, input boxes). While you can also use a class for a single element, in order to get used to this distinction and use these separators as they are intended, it is better to make a habit of using classes to control the style of multiple of the same type of element.