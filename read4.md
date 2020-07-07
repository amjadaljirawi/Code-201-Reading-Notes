# links
* Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.using <a> element.
1. Linking to Other Sites .
2. Linking to Other Pages on the Sa me Site.
3. Email Links.
# layout
1. <div> elements are often used as containing elements to group together sections of a page.
2. Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
3. Pages can be fixed width or liquid (stretchy) layouts.
4. CSS Frameworks provide rules for common tasks.
5. You can include multiple CSS files in one page.
### examles 
* Multiple Style Sheets
<!DOCTYPE html>
<html>
<head>
<title>Multiple Style Sheets - Link</title>
<link rel="stylesheet" type="text/css"
href="css/site.css" />
<link rel="stylesheet" type="text/css"
href="css/tables.css" />
<link rel="stylesheet" type="text/css"
href="css/typography.css" />
</head>
<body>
<!-- HTML page content here -->
</body>
</html>
* Fixed Width Layout
<body>
<div id="header">
<h1>Logo</h1>
<div id="nav">
<ul>
<li><a href="">Home</a></li>
<li><a href="">Products</a></li>
<li><a href="">Services</a></li>
<li><a href="">About</a></li>
<li><a href="">Contact</a></li>
</ul>
</div>
</div>
<div id="content">
<div id="feature">
<p>Feature</p>
</div>
<div class="article column1">
<p>Column One</p>
</div>
<div class="article column2">
<p>Column Two</p>
</div>
<div class="article column3">
<p>Column Three</p>
</div>
</div>
<div id="footer">
<p>&copy; Copyright 2011</p>
</div>
</body>
# js read
## Functions, Methods, and Objects
* Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).
<!DOCTYPE html>
<html>
<head>
Before the closing </body>
tag, you can see the link to the
JavaScript file. The JavaScript
file starts with a variable used
to hold a new message, and is
followed by a function ca lled
updateMessage().
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="cs s/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></ script>
</ body>
</ html>
