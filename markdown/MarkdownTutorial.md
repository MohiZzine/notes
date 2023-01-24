# Markdown Starter Worksheet

The main goal of Markdown is most commonly to write README file, in Github repos.

Markdown can also be used to write email.

The purpose is to learn to write  it  quickly like HTML and CSS.

Markdown, in comparison to HTML, is basically easy to read an write. The average person can typically understand markdown and would be able to learn and write it much quicker than HTML.

## Sections

* [Headers](#headers)
* [Quotes](#quotes)
* [Emphasis](#emphasis) (**bold** / *italics*)
* [Horizontal](#horizontal-rule)
* [Lists](#lists)
* [Links](#links)
* [Images](#images) 
* [Code](#code)
* [Tables](#tables)
* [Custom HTML](#custom-html)
* [Custom CSS](#custom-css)
* [Additional Resources](#additional-resources)

***

## Headers
Headers are defined with the "#" symbol. One "#" for H1, two for H2, etc.



> # Here is a H1 header
> ## Here is a H2 header
> ### Here is a H3 header
> #### Here is a H4 header


***

## Quotes

Quotes are defines by the ">" symbol:
<!-- 
  Example

 > # H1 Quote
-->
> Here is a Quote

***


## Emphasis

Add emphasis with asterisks "*" and underscores "_*
Two before and after (no spaces) a section of text makes it **bold**.

<!-- Example


  ** Bold with asterisks**
  __ Bold with underscores__    

 -->

One  emphasis with asterisks "*" and underscores "_*
Two before and after (no spaces) a section of text makes it *italicized*.

<!-- Example


  *itlalics with asterisks*
  _italics with underscores_    



 -->
> *italics sentence*

> **Bold sentence**

> __Bold with italics__


***

## Horizontal rule

A horizontal rule gives visible line break.
You can create one by putting three or more hyphen, asterisks or underscores (-, *, _)
<!--

Example: 
  ***
  ___

  ---

 -->

***

## Lists

Create unordered lists using '-', '+', '*'
<!-- 
  Example:
  
  - item
  + item
  * item
-->

- Item
* Another item
+ Plus item


You can also create sublists by indenting


- list1
  - Nested list1
- list2

Create ordered list this time using number prefix

1. first element
1. second element
0. third ..

**Note:** It is not mandatory to match the indexes with the order of elements, the numbers in order will be displayed automatically!

<!-- Example:

  1. first element
  2. second element
  3. third .. 

  is the same as ->

  1. first element
  1. second element
  5. third ..
  
-->

***

## Links

Create a link by surrounding it with angle brackets
<!-- 
  Example:
  
  <your link here>
  
-->

The Mozilla Developers Network's website link: <https://developer.mozilla.org/fr/>

Create a link around a text by surrounding the text inside brackets, [], and link immediatly following with parenthesis ()

<!-- 
  Example:
  
  [MDN](your link here) 

-->

If you need to reuse a link several times, instead of copying and pasting that link each line, you can create a reference style link by defining your link with the 'key' inside of brackets, colon, space and the link.

<!-- 
  Example :
  
  [key]: <your link here> 
  and you can now display it the following way :
  [your text][key]

-->

[website]: https://developer.mozilla.org/fr/


[MDN][website]

[another link to MDN][website]

You can also link to other locations on your markdown page. Remember, your MarkDown will get converte to HTML, so you can, in theory, use a anchor tag to link to an element with specific ID. You can find an example of this in the list of sections at the top of this document.

When we create a header tag for example, it implicitly creates an id property.

Ex '# Header' becomes `<h1 id="header">Header</h1>`

Names will be converted to ids by replacing spaces with hyphens and uppercase letters with lowercase letters (think css naming convention).

Ex "Header Info" become "header-info"

Create a link to a part of your page:

[Headers](#headers)

***


## Images

<!-- Not Completed Yet... -->



***

## Code

You do inline code with `backsticks` (``)

Here is some code inline `var items = {};`

You can do block of code by surrounding it with 3 backsticks(``````)


> You can display a block of code from your favourite language

You can specify the programming language immediatly following the oppening 3 backsticks. You should see a difference in highlighting!

> Without language
```
var item = {};
item.something = "smth"; 

```

> With language

``` javascript
var item = {};
item.something = "smth"; 

```

***

## Tables

















