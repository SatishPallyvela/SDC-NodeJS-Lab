Experiment-01-HTML-CSS/README.md`

---

# 🧪 Experiment – 01

## Responsive Shopping Cart Website using HTML & CSS

---

## 📘 Course Information

* **Course Code:** CS409PC
* **Course Name:** NodeJS / ReactJS / Django
* **Program:** B.Tech – II Year II Semester
* **L T P C:** 0 0 2 1

---

## 🎯 Aim

To design and develop a **responsive shopping cart website** using **HTML and CSS** that includes **Registration, Login, Product Catalog, and Cart pages**.

---

## 📖 Introduction (Layman Explanation)

A website is built using **HTML** to create structure and **CSS** to add design and layout.
HTML acts like the **skeleton** of a webpage, while CSS acts like **clothes and styling**.

In this experiment, we design a simple shopping cart website similar to real-world e-commerce applications. This experiment helps beginners understand how web pages are structured and styled before adding programming logic.

---

## 🧠 Concepts Covered

* HTML basic structure
* Headings and paragraphs
* Forms (Registration & Login)
* Input elements (text, email, password)
* CSS styling
* CSS Flexbox
* CSS Grid
* Responsive web design

---

## 🛠 Tools / Software Used

* Visual Studio Code
* Web Browser (Chrome / Edge / Firefox)
* Operating System: Windows / Linux

---

## 🔄 Algorithm / Procedure

1. Create the basic HTML structure for all pages.
2. Design registration and login forms using HTML form elements.
3. Create a product catalog layout using CSS Flexbox or Grid.
4. Design a cart page to display selected products.
5. Apply CSS styles for layout, colors, and spacing.
6. Make the webpage responsive for different screen sizes.

---

## 💻 Program Code

The program consists of the following files:

* `index.html` – Home page
* `register.html` – Registration page
* `login.html` – Login page
* `catalog.html` – Product catalog
* `cart.html` – Cart page
* `style.css` – Styling and layout

*(Actual code files are available in this folder)*

---

## 🖥 Output

The output displays a responsive shopping cart website with:

* User registration page
* Login page
* Product listing page
* Cart page

The website adjusts its layout based on screen size.

---

## 📝 Observation

```
In this experiment, we observed that HTML is used to create the structure
of web pages, while CSS is used to control the layout and appearance.
Forms were designed for registration and login purposes. CSS Flexbox and
Grid helped in arranging products neatly. The website layout adjusted
according to different screen sizes, making it responsive.
```

---

## ✅ Result

```
Thus, a responsive shopping cart website with registration, login,
catalog, and cart pages was successfully developed using HTML and CSS.
```

---

## 🎓 Learning Outcomes

After completing this experiment, the student is able to:

* Understand basic website structure
* Design forms using HTML
* Apply CSS for layout and styling
* Create responsive web pages
* Build a basic e-commerce layout

---

## 🔗 References

* [https://www.w3schools.com/html/](https://www.w3schools.com/html/)
* [https://www.w3schools.com/css/](https://www.w3schools.com/css/)
* [https://www.w3schools.com/css/css_flexbox.asp](https://www.w3schools.com/css/css_flexbox.asp)
* [https://www.w3schools.com/css/css_grid.asp](https://www.w3schools.com/css/css_grid.asp)
* [https://www.w3schools.com/css/css_rwd_intro.asp](https://www.w3schools.com/css/css_rwd_intro.asp)

---

## 👨‍🏫 Faculty Note

This experiment forms the **foundation for JavaScript, Bootstrap, Node.js, React, and Django experiments**.

---

### ✅ What to do next

👉 Commit this to GitHub
👉 Then we write **Experiment–2 README.md**
👉 Or I can help you **review student code for Exp–1**

Just tell 👍
![alt text](image.png)


------------------------------------------------------------------

🧪 EXPERIMENT – 1
Responsive Shopping Cart using HTML + CSS (Flex & Grid)
📁 Folder Structure

Experiment-01-HTML-CSS/
│── index.html        (Registration + Login)
│── catalog.html     (Product listing)
│── cart.html        (Cart page)
│── style.css        (External CSS)


index.html (Registration + Login)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shopping Cart - Login</title>

    <!-- Linking external CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Shopping Cart Application</h1>

    <!-- Registration Form -->
    <section class="box">
        <h2>Registration</h2>

        <form>
            <label>Name</label>
            <input type="text" placeholder="Enter Name">

            <label>Email</label>
            <input type="email" placeholder="Enter Email">

            <label>Password</label>
            <input type="password" placeholder="Enter Password">

            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Login Form -->
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

-----------------------------------------------------------------------------------------------------------
catalog.html (Product Catalog – Flex + Grid)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Product Catalog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>Product Catalog</h1>

<!-- Product Grid -->
<div class="product-grid">

    <div class="product">
        <h3>Product 1</h3>
        <p>Price: ₹500</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <h3>Product 2</h3>
        <p>Price: ₹800</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <h3>Product 3</h3>
        <p>Price: ₹1200</p>
        <button>Add to Cart</button>
    </div>

</div>

</body>
</html>

-------------------------------------------------------------------------------------------------------------------------------
cart.html (Cart Page)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Cart</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>Your Shopping Cart</h1>

<div class="cart">
    <p>Product 1 - ₹500</p>
    <p>Product 2 - ₹800</p>
    <h3>Total: ₹1300</h3>

    <button>Checkout</button>
</div>

</body>
</html>
------------------------------------------------------------------------------------------------------------------------------------
style.css (CSS3 + Flex + Grid)

/* General styling */
body {
    font-family: Arial, sans-serif;
    padding: 20px;
}

/* Form box styling */
.box {
    width: 300px;
    padding: 20px;
    border: 1px solid #ccc;
    margin-bottom: 20px;
}

/* Inputs */
input {
    width: 100%;
    padding: 8px;
    margin: 5px 0;
}

/* Buttons */
button {
    width: 100%;
    padding: 10px;
    background-color: steelblue;
    color: white;
    border: none;
}

/* Product Grid using CSS Grid */
.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

/* Product Card */
.product {
    border: 1px solid #ccc;
    padding: 15px;
    text-align: center;
}

/* Cart */
.cart {
    border: 1px solid #aaa;
    padding: 20px;
    width: 300px;
}
