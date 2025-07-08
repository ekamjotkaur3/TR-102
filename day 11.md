
### **Training Day 11 Report:**

**Date:** 15 June 2024

**Location:** Science & Technology Entrepreneurs' Park

**Project Title:** *Introduction to Bootstrap and Bootstrap Containers*

On Day 11, we started learning about **Bootstrap**, which is a free tool used by web developers to design better websites in less time. Bootstrap helps make our websites look neat and work well on all screen sizes like mobile phones, tablets, and computers. It already has many built-in styles and layouts, so we don’t have to write everything from scratch.

We learned that **Bootstrap is used for front-end development**, which means designing the parts of a website that people see and use. This includes things like buttons, headings, images, forms, and more.

---

### Project Objectives:

* Understand what Bootstrap is and how it helps in designing web pages.
* Learn the differences between Bootstrap 3, 4, and 5.
* Learn about **containers** in Bootstrap and how they help in page layouts.
* Practice creating containers using Bootstrap 5.
* Apply spacing, border, and background color utilities to make the container look better.

---

### What is Bootstrap?

Bootstrap is a collection of ready-to-use code for building websites. Instead of writing long CSS code, we can use Bootstrap classes to quickly style elements. For example, if we want a button or a heading to look nice, we can just use a class from Bootstrap.

Bootstrap includes:

* HTML and CSS templates
* Built-in spacing, color, and layout tools
* JavaScript features (like modals and sliders)

---

### Bootstrap Versions:

We discussed three versions:

* **Bootstrap 3** – An older version, still used in many websites. Works with old browsers.
* **Bootstrap 4** – Faster and more responsive than Bootstrap 3.
* **Bootstrap 5** – The latest version. It is cleaner, modern, and doesn’t use jQuery anymore. We are learning Bootstrap 5 in this training.

---

### Bootstrap Containers:

The first thing we learned to use in Bootstrap is the **container**. It is used to hold the content of a page in one place. Containers help keep our layout clean and centered.

There are two types of containers:

1. **`.container`**

   * This is a fixed-width container. It is centered and changes size depending on screen size.
2. **`.container-fluid`**

   * This is a full-width container that always takes 100% of the screen.

---

### Example:

```html
<div class="container">
  <h1>This is a fixed container</h1>
  <p>It has a set width.</p>
</div>

<div class="container-fluid">
  <h1>This is a fluid container</h1>
  <p>It stretches full width of the screen.</p>
</div>
```

We created a sample webpage using both types of containers and saw how they behave differently when we resized the browser.

---

### Spacing, Borders, and Colors:

We also learned how to use Bootstrap’s utility classes for **spacing**, **padding**, and **background colors**. These classes make designing much easier.

* `.p-5` adds padding on all sides
* `.my-4` adds margin on top and bottom
* `.border` adds a border around the box
* `.bg-primary` makes the background blue
* `.text-white` changes text color to white

---

### Practice Example:

```html
<div class="container p-5 my-5 bg-primary text-white border">
  <h2>Styled Container</h2>
  <p>This box has padding, margin, background color, and a border.</p>
</div>
```

We tried these classes and saw the changes in real time. It was interesting to see how much we could do without writing any CSS.

---

### Sample Code:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Bootstrap Practice</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <header class="bg-dark text-white text-center p-4">
    <h1>Welcome to My Bootstrap Page</h1>
  </header>

  <div class="container mt-5 p-4 border bg-light">
    <h2>Fixed Container</h2>
    <p>This section is inside a fixed-width container.</p>
  </div>

  <div class="container-fluid mt-4 p-4 bg-secondary text-white">
    <h2>Fluid Container</h2>
    <p>This section uses the container-fluid class and stretches full screen.</p>
  </div>

  <footer class="bg-dark text-white text-center p-3 mt-5">
    &copy; 2025 Ekamjot Kaur
  </footer>

</body>
</html>
```

---

### What I Learned:

* Bootstrap helps us design websites easily and makes them responsive.
* Containers are important to start a layout. We can choose between `.container` and `.container-fluid` depending on the design.
* We can use Bootstrap classes like `.p-5`, `.my-4`, `.bg-primary`, `.text-white`, and `.border` to style boxes without writing custom CSS.
* Bootstrap 5 is the newest version and is good for modern web design.

---

### Conclusion:

Day 11 was all about getting started with Bootstrap. We understood its purpose, the benefits of using it, and how to start building a layout using containers. We also saw how much easier and faster it becomes to create good-looking web pages using Bootstrap’s ready classes. It was a fun and useful session that gave us a strong foundation for more advanced topics in the coming days.

---

**BY: Ekamjot Kaur**
**URN 2302867**
**CRN 2315264**
**Page no. 11**

---

