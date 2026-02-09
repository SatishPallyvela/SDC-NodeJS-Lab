🧪 EXPERIMENT–1
📄 File Explained: index.html
1️⃣ CONCEPTS COVERED IN THIS FILE (WHAT YOU SHOULD EXPLAIN)

You can literally tell students:

“In this single HTML file, we are learning many core web concepts.”

🔹 A. HTML Document Structure

<!DOCTYPE html>

<html>, <head>, <body>

👉 Why browser needs structure
Browser reads HTML top-to-bottom. Structure tells:

what version of HTML

what is metadata

what is visible content

🔹 B. Language Declaration
<html lang="en">


Declares page language as English

Helps:

Screen readers

Search engines

Accessibility

🔹 C. Character Encoding
<meta charset="UTF-8">


Supports:

English

Indian languages

Emojis

Prevents symbol errors

🔹 D. Meta Information (Head Section)

<head> content is not visible

Used for:

Page info

SEO

Browser behavior

🔹 E. Title Tag
<title>Shopping Cart - Login</title>


Appears on:

Browser tab

Search engine result title

🔹 F. External CSS Linking
<link rel="stylesheet" href="style.css">


Separation of concerns:

HTML → structure

CSS → design

🔹 G. Semantic Elements
<section>


Gives meaning to content

Better than only <div>

🔹 H. Headings & Text

<h1> → Main title

<h2> → Section titles

🔹 I. HTML Forms

<form>

<label>

<input>

<button>

🔹 J. Input Types
type="text"
type="email"
type="password"


Browser-level validation

Better user experience

🔹 K. Placeholder Attribute
placeholder="Enter Email"


User guidance

UX improvement

🔹 L. Class Attribute
<section class="box">


Used by CSS

Enables styling & layout

2️⃣ SAME CODE WITH DETAILED TEACHING COMMENTS

You can paste this directly and explain line by line in lab 👇

<!DOCTYPE html>
<!-- 
DOCTYPE tells the browser that this document follows HTML5 standard.
Without this, browser may go into quirks/old mode.
-->

<html lang="en">
<!-- 
The lang attribute specifies the language of the document.
"en" means English.
Helps search engines and screen readers.
-->

<head>
    <!-- 
    Head section contains metadata.
    Metadata is information ABOUT the page.
    It is NOT visible on the webpage.
    -->

    <meta charset="UTF-8">
    <!-- 
    UTF-8 supports all languages and symbols.
    Prevents character display issues.
    -->

    <title>Shopping Cart - Login</title>
    <!-- 
    Title appears on browser tab and search engine results.
    -->

    <!-- Linking external CSS file -->
    <link rel="stylesheet" href="style.css">
    <!-- 
    This connects HTML with CSS.
    CSS is used for design and layout.
    -->
</head>

<body>
    <!-- 
    Body contains the visible content of the webpage.
    -->

    <h1>Shopping Cart Application</h1>
    <!-- 
    h1 is the main heading.
    Only one h1 should be used per page.
    -->

    <!-- Registration Form Section -->
    <section class="box">
        <!-- 
        section tag groups related content.
        class="box" is used for CSS styling.
        -->

        <h2>Registration</h2>

        <form>
            <!-- 
            form tag is used to collect user input.
            -->

            <label>Name</label>
            <!-- Label describes input field -->
            <input type="text" placeholder="Enter Name">
            <!-- 
            text input allows user to enter name.
            placeholder gives hint to user.
            -->

            <label>Email</label>
            <input type="email" placeholder="Enter Email">
            <!-- 
            email type checks valid email format.
            -->

            <label>Password</label>
            <input type="password" placeholder="Enter Password">
            <!-- 
            password type hides entered characters.
            -->

            <button type="submit">Register</button>
            <!-- 
            submit button sends form data.
            -->
        </form>
    </section>

    <!-- Login Form Section -->
    <section class="box">

        <h2>Login</h2>

        <form>

            <label>Email</label>
            <input type="email" placeholder="Enter Email">

            <label>Password</label>
            <input type="password" placeholder="Enter Password">

            <button type="submit">Login</button>
        </form>
    </section>

</body>
</html>

3️⃣ HOW YOU CAN EXPLAIN IN CLASS (SIMPLE LINE)

You can say:

“This file teaches how a real website starts — structure, metadata, forms, inputs, and external styling. We are not storing data yet; we are only designing UI.”

4️⃣ WHAT STUDENTS SHOULD WRITE (OBSERVATION – SHORT)

In this experiment, we designed a basic shopping cart interface using HTML. We learned the structure of an HTML document, usage of head and body sections, form elements, input types, and external CSS linking.

If you want next:

🔹 Explain style.css line by line

🔹 Explain why we use <section> not <div>

🔹 Convert this explanation into README.md

Just say next 👍