📌 What is <head>?
The <head> section contains information ABOUT the webpage,
 not the content shown on the page.
👉 Nothing inside <head> is directly visible on the webpage.
🧠 Layman Explanation
Think of <head> as:
 🧠 Brain of the website
Stores instructions


Stores settings


Stores rules


While <body> is the face that users see.
📦 What Does <head> Contain?
1️⃣ Page Title
<title>My First Website</title>

📌 Shown on:
Browser tab


Bookmark name



2️⃣ CSS (Styling)
Used to design the webpage.
<link rel="stylesheet" href="style.css">

or
<style>
  body { background-color: lightblue; }
</style>


3️⃣ JavaScript
Used for interactivity and logic.
<script>
  alert("Welcome!");
</script>


4️⃣ Meta Information
Used to give extra information about the page.
<meta charset="UTF-8">
<meta name="description" content="Shopping Cart Website">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

📌 Helps:
Browser


Search engines


Mobile responsiveness



🧪 Example: Complete <head> Section
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Cart</title>
    <link rel="stylesheet" href="style.css">
</head>


❌ What NOT to put in <head>
❌ Images
 ❌ Headings
 ❌ Paragraphs
Those belong in <body>.


NOTES FROM REFERENCE AND PRACTICE OF HEADINGS

HTML Headings
HTML headings are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading.
<!DOCTYPE html>
<html>
<body>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

</body>
</html>
Note: Browsers automatically add some white space (a margin) before and after a heading.


Headings Are Important
Search engines use the headings to index the structure and content of your web pages.
Users often skim a page by its headings. It is important to use headings to show the document structure.
<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on.
For example:
<h1> - Page title
<h2> - Section titles
<h3> - Sub-sections
TILL H6.
Example


<!DOCTYPE html>
<html>
<body>

<h1>Travel Guide</h1>

<h2>Europe</h2>
<h3>France</h3>
<h3>Italy</h3>

<h2>Asia</h2>
<h3>India</h3>
<h3>Thailand</h3>

</body>
</html>

Tip: Use only one <h1> per page - it represents the main topic or title.
Note: Use HTML headings for headings only. Don't use headings to make text BIG or bold.


Bigger Headings
Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
Example
<!DOCTYPE html>
<html>
<body>

<h1 style="font-size:60px;">Heading 1</h1>

<p>You can change the size of a heading with the style attribute, using the font-size property.</p>

</body>
</html>



PRACTICING ON HTML - THE HEAD ELEMENT
HTML - The Head Element
The HTML <head> element is a container for the following elements: <title>, <style>, <meta>, <link>, <script>, and <base>.

The HTML <head> Element
The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.
HTML metadata is data about the HTML document. Metadata is not displayed on the page.
Metadata typically define the document title, character set, styles, scripts, and other meta information.
The HTML <title> Element
The <title> element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.
The <title> element is required in HTML documents!
The content of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.
The <title> element:
defines a title in the browser toolbar
provides a title for the page when it is added to favorites
displays a title for the page in search engine-results
So, try to make the title as accurate and meaningful as possible!

A simple HTML document:
Example
<!DOCTYPE html>
<html>
<head>
  <title>A Meaningful Page Title</title>
</head>
<body>

<p>The content of the body element is displayed in the browser window.</p>
<p>The content of the title element is displayed in the browser tab, in favorites and in search-engine results.</p>

</body>
</html>

The HTML <style> Element
The <style> element is used to define style information for a single HTML page:
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
  <style>
    body {background-color: powderblue;}
    h1 {color: red;}
    p {color: blue;}
  </style>
</head>  
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
  
<p>The content of the body element is displayed in the browser window.</p>
<p>The content of the title element is displayed in the browser tab, in favorites and in search-engine results.</p>

</body>
</html>

The HTML <link> Element
The <link> element defines the relationship between the current document and an external resource.

The <link> tag is most often used to link to external style sheets:
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
  <link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>
  
</body>
</html>

Mystyle.css

/* Apply style to the entire page */
body {
    background-color: yellow;
    font-family: Arial, Helvetica, sans-serif;
    margin: 20px;
}

/* Style for heading */
h1 {
    color: black;
    font-size: 36px;
    margin-bottom: 10px;
}

/* Style for paragraph */
p {
    color: blue;
    font-size: 18px;
}

The HTML <meta> Element
The <meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.
The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.
Examples
Define the character set used:
<meta charset="UTF-8">
Define keywords for search engines:
<meta name="keywords" content="HTML, CSS, JavaScript">
Define a description of your web page:
<meta name="description" content="Free Web tutorials">
Define the author of a page:
<meta name="author" content="John Doe">
Refresh document every 30 seconds:
<meta http-equiv="refresh" content="30">
Setting the viewport to make your website look good on all devices:
<meta name="viewport" content="width=device-width, initial-scale=1.0">


Example of <meta> tags:

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
</head>
<body>

<p>All meta information goes inside the head section.</p>

</body>
</html>

More information about meta tags in HTML
Meta tags in HTML

Setting The Viewport
The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.
You should include the following <meta> element in all your web pages:
<meta name="viewport" content="width=device-width, initial-scale=1.0">
This gives the browser instructions on how to control the page's dimensions and scaling.
The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.
Tip: If you are browsing this page with a phone or a tablet, you can click on the two links below to see the difference.
