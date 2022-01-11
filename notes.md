## HTML

<div> : the content division element
<span> : inline element
<hr> : a thematic break betwen paragraph-level elements
<br> : a line break in text
<sup> : superscript
<sub> : subscript

### Entities : &...;

### Semantic markup - relating to meaning
<section> a tandalone section which doesn't have a more specific semantic element to represent it
<article> a self-contained composition in a document
<nav> a section of a page whose purpose is to provide navigation links
<main> the dominant content of the <body> of a document
<header> introductory content
<footer>
<aside> a portion of a document whose content is only indirectly related to the document's main content
<summary>
<details>

### Forms & Tables

<table>
<td>
<tr>
<th>
<thead>
<tfoot>
<tbody>

### Validations

## CSS
EXTERNAL STYLESHEET

universal selector

* {}
  
element selector

button {}

selector list

h1, h2 {}

id selector

<button id="signup">Sign Up</button>

#signup {
    background-color: #1d3557;
}

class selector

.tag {
    background-color: ;
}

descendant selector

li a {
    color : teal;
}

.post a {
    color: ;
}

adjacent selector

select only the paragraphs that are immediately preceded by an h1

h1 + p {
    color: red;
}

direct child

select only the li that are direct children of a div element

div > li {
    color: white;
}

attribute selector 

select all input elements where the type attribute is set to "text"

input[type = "password"] {
    color: green; 
}

a[href*="google"] {
    color: red;
}

pseudo classes

keyword added to a selector that specifies a special state of the selected elements

a:hover {
    color: orange;
}

.post button:hover {
    background-color: red;
    text-decoration: underline;
}

.post:nth-of-type(3n) {
    background-color:gray;
}

psudo elements

h2::first-letter {

}

the cascade

the order your styles are declared in and linked to matters


Specificity

Specificity is how the browser decides which rules to apply when multiple rules could apply to the same element
It is a measure of how specific a given selector is. The more specific selector "wins"

IDs > Classes, attributes and pseudo-classes > elements and pseudo-elements

Chrome Dev Tools & CSS

inline styles 

!important
override any other decoration

CSS inheritance

### box model
