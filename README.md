# hello-world
<hr>
<h1>Best practices for the hello-world project</h1>
<hr>

<h2>Github best practices</h2>
<h3>Inserting code into github comments</h3>
If you want to insert code into any github comments, use the "<>" (insert code) button. You will get two ` ` (signal next to 1 on keyboard), where you will insert your code like this:

`code`

The code should come out with a grey background surrounding the code you typed. 
If there is a problem, check the ` ` carefully!
Note: You can also use these signals to specify code in documents like this, by typing your code between the signals.

<hr>

<h2>Linux best practices</h2>
<h3>Regarding file names for uploaded file</h3>
If a file name includes a space (" "), Linux will change the space in the name to a backlash space("\ ").

Thus, whenever we want to upload a file, change the name to not have any spaces (" ").
Change the file according to the following rubric:

Dad Hello.jpeg -> Dad_Hello.jpeg

<hr>

<h2>HTML best practices</h2>
<h3>Adding links</h3>

When adding links using `<a ref .....>`, the better practice would be to do:

`<a ref ...... /linkname.html>` rather than

`<a ref ..... IP address/linkname.html>`

This is because /linkname.html works no matter what, whereas IP address/linkname.html might not be seem from either outside or inside our home.

<h3>Using br breaks</h3>

 HTML elements with no content are called empty elements.
`<br>` defines a line break and it is an empty element.
Close this break using `<br/>`. 

Note, one need not close empty elements in HTML5. However, for stricter validations, or if you want your document to be readable by xml parsers, it is better practice to close empty elements properly.

<h3>Using p title</h3>

`<p title ... >` is used to pop up text when you hover your mouse over some paragraph element in your web page. It should be used in place of the normal `<p>` with the code>: 

`<p title="text you want to use">`
  
<hr>
