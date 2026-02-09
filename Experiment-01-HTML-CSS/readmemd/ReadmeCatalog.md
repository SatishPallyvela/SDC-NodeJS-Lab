Perfect 👍
This is the **CATALOG page** — the **most important page** in Experiment–1 because it introduces **CSS Grid** and **real e-commerce layout thinking**.

I’ll explain it **exactly like index.html & cart.html** so your students feel continuity.

---

# 🧪 EXPERIMENT–1

## 📄 File Explained: `catalog.html`

---

## 1️⃣ CONCEPTS COVERED IN THIS CATALOG PAGE

You can tell students:

> “This page shows multiple products in a structured layout like Amazon or Flipkart.”

---

### 🔹 A. Reusable HTML Structure

* Same base layout:

  * `<!DOCTYPE html>`
  * `<html>`
  * `<head>`
  * `<body>`

👉 Shows **standardization across pages**

---

### 🔹 B. Page Identification

```html
<title>Product Catalog</title>
```

* Helps browser & user identify page

---

### 🔹 C. External CSS Reuse

```html
<link rel="stylesheet" href="style.css">
```

* One CSS file controls design of:

  * Login
  * Catalog
  * Cart

---

### 🔹 D. Grid Layout Concept

```html
<div class="product-grid">
```

* Container for multiple products
* Styled using **CSS Grid**
* Makes layout responsive

---

### 🔹 E. Repeating Components

```html
<div class="product">
```

* Each product is a **card**
* Same structure reused
* Concept of **component-based design**

---

### 🔹 F. Buttons for Action

```html
<button>Add to Cart</button>
```

* Represents user action
* Functionality added later using JS

---

### 🔹 G. Currency & Text

* UTF-8 supports ₹
* `<p>` used for price info

---

## 2️⃣ SAME CODE WITH **DETAILED EXPLANATORY COMMENTS**

```html
<!DOCTYPE html>
<!-- 
Defines HTML5 document.
-->

<html lang="en">
<!-- 
Language is English.
-->

<head>
    <meta charset="UTF-8">
    <!-- 
    Supports special characters like ₹.
    -->

    <title>Product Catalog</title>
    <!-- 
    Title displayed on browser tab.
    -->

    <link rel="stylesheet" href="style.css">
    <!-- 
    External CSS file used for styling all pages.
    -->
</head>

<body>
    <!-- 
    Body contains visible content.
    -->

    <h1>Product Catalog</h1>
    <!-- 
    Main heading of the catalog page.
    -->

    <!-- Product Grid Container -->
    <div class="product-grid">
        <!-- 
        This div holds all product cards.
        Styled using CSS Grid.
        -->

        <!-- Product Card 1 -->
        <div class="product">
            <!-- 
            Each product is a card.
            -->

            <h3>Product 1</h3>
            <!-- Product name -->

            <p>Price: ₹500</p>
            <!-- Product price -->

            <button>Add to Cart</button>
            <!-- Button to add product to cart -->
        </div>

        <!-- Product Card 2 -->
        <div class="product">
            <h3>Product 2</h3>
            <p>Price: ₹800</p>
            <button>Add to Cart</button>
        </div>

        <!-- Product Card 3 -->
        <div class="product">
            <h3>Product 3</h3>
            <p>Price: ₹1200</p>
            <button>Add to Cart</button>
        </div>

    </div>

</body>
</html>
```

---

## 3️⃣ HOW TO EXPLAIN THIS PAGE IN CLASS (LAYMAN STYLE)

You can say:

> “This page displays multiple products in a grid layout. Each product has a name, price, and an action button. Later, we will use JavaScript to connect this page with the cart.”

---

## 4️⃣ WHAT STUDENTS SHOULD WRITE (OBSERVATION)

> In this experiment, we designed a product catalog page using HTML. We learned how to create reusable product cards and arrange them using CSS Grid. The page layout is clean and scalable for multiple products.

---

## 5️⃣ HOW THIS MAPS TO SYLLABUS

✔ HTML structure
✔ CSS Grid layout
✔ Responsive design basics
✔ Component-style layout
✔ E-commerce UI design

---

## 6️⃣ NEXT STEP (VERY IMPORTANT)

Now we **must write `style.css`**, because:

* Flexbox → Login & Cart layout
* Grid → Catalog layout
* Responsiveness → Experiment–1 core

👉 Say **“write style.css”** and I’ll give:

* Full CSS
* Flex + Grid
* Comments line-by-line
* Mobile responsiveness

You’re building this **perfectly like a real lab manual** 👏
