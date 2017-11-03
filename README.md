<b>This repo is for recapulation of basic syntaxes in use in HTML. It also contains small projects to illustrate execution of common HTML tags. Hope this helps people who have to often switch languages and are baffled by the varying styles of development. Keep rocking codes! ;)</b>

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