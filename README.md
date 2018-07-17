### HTML CSS Inception
This repository is for recapitulation of basic syntaxes in use in HTML. It also contains small projects to illustrate 
execution of common HTML tags. Hope this helps people who have to often switch languages and are baffled by the varying 
styles of development. Keep rocking codes! ;)

#### Validators 
<!--complete from screenshot-->

#### What is W3C?
<!--complete from screenshot-->

#### Few W3C Standards
<p>Web accessibility means people with any disability or without any, both access web equally. Few things that support 
web accessibility are: proper page title, alt text in images, etc.</p>
<p>Internationalization means making web content available to any society, state, nation or organization. 
'Internationalization' is sometimes abbreviated to 'i18n' in English, because there are 18 characters between the 'i' 
and the 'n'. Unicode is a universal character set, ie. a standard that defines, in one place, all the characters needed 
for writing languages in use on computers. Some steps to support internationalization are: defining character set,

```html
<head>
    <meta charset="utf-8"/>
</head>
```
primary language declaration
```html
<html lang="fr">
```
</p>

#### HyperText
Hypertext is built on the idea of linking information together. The idea was to "Mark Up" your document with links and 
define how to break it down into different segments (chapters, sections, paragraphs, tables, figures, etc.).
This lead to the definition of HTML: Hypertext Markup Language, to provide a simple, uniform way to incorporate 
Hyperlinks in a text document. The metaphor of a Web is used to emphasize the importance of connections between 
documents. HTML's ancestor language is SGML (Standard Generalized Markup Language),from which it borrowed the use of 
angle brackets.

#### Terms
**Elements** are pieces of a webpage. **Tags** are used to represent an element. **Attributes** add meaning to tags and 
qualifies the element. **Comments** in HTML are written as follows:
```html
<!-- this is a comment. Can be single line or multi line-->
```

#### First HTML page
The first thing in a html page is: `<!DOCTYPE html>`. This indicates that this is a HTML5 file. The next tag will be 
`<html>`. This is where the document resides. The `<head>` tag inside `<html>` stores information about the document. 
`<body>` inside `<html>` stores the content of the document. `<p>` is used for paragraphs.

<!--Unformatted-->
Linking to elements on the same page or to other pages on the same site is called navigation. HTML has a special tag called <nav> that is used to wrap these links in order to organize the content on your web page.

Some of the tags we have used, such as <div>, are called non-semantic tags. This means that they do not describe the content that is inside of them. However, many tags are used to describe the content that they surround, which helps us modify and style our content later. These are called semantic tags

<a href="/">Brown Bear</a>
web browsers respond to index.html and / the same way

The use of the 'scope' attribute, which can take one of two values:
row - this value makes it clear that the heading is for a row.
col - this value makes it clear that the heading is for a column.
E.g. <th scope="col">Sunday</th>

<table border="2"></table>
This method of adding border is outdated. Please do not use it. This is for you to be able to understand other developer's code. The same effect can be achieved using CSS.

If the table contains data that spans multiple columns, use 'colspan' attribute in 'td' tag. Specify how many columns you want to cover.
E.g. <td colspan="2">Hello There! :)</td>
Similarly 'rowspan' features rows.

Long tables can be sectioned off using the table body element: <tbody>. The <tbody> element should contain the all of the table's data, excluding the table headings. Similarly <thead> and <tfoot> tags are used to add header and footer to table.
