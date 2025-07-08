### **Training Day 13 Report:**

**Date:** 17 June 2024

**Location:** Science & Technology Entrepreneurs' Park

**Project Title:** *Bootstrap 5 Text, Colors, and Tables*

On Day 13, we explored different ways to style text, apply colors, and create tables using Bootstrap 5. These features help make websites more attractive and easy to read.

---

### Project Objectives:

* Understand Bootstrap 5 text classes for headings and display styles.
* Learn how to use Bootstrap colors for text and backgrounds.
* Study Bootstrap 5 tables, including different styles and features.
* Practice creating colored and responsive tables.

---

### 2.4.5 Bootstrap 5 Text

Bootstrap styles HTML headings (from `<h1>` to `<h6>`) with bold fonts and sizes that change depending on the screen size. This means the headings will look good on both big and small screens.

---

### Headings Example:

You can apply Bootstrap heading styles to any text by using classes like `.h1`, `.h2`, etc.

```html
<p class="h1">h1 Bootstrap heading</p>
<p class="h2">h2 Bootstrap heading</p>
<p class="h3">h3 Bootstrap heading</p>
<p class="h4">h4 Bootstrap heading</p>
<p class="h5">h5 Bootstrap heading</p>
<p class="h6">h6 Bootstrap heading</p>
```

This will style the paragraphs to look like the different heading sizes.

---

### Display Headings

Bootstrap has special larger heading classes for titles or big text, called **display headings**.

Example:

```html
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
<h1 class="display-5">Display 5</h1>
<h1 class="display-6">Display 6</h1>
```

These headings are much bigger and useful for main page titles.

---

### 2.4.7 Bootstrap 5 Colors

Bootstrap makes it easy to change the color of text and backgrounds using classes.

---

### Text Colors

There are many classes to change text color:

* `.text-muted` (grayish)
* `.text-primary` (blue)
* `.text-success` (green)
* `.text-info` (light blue)
* `.text-warning` (orange)
* `.text-danger` (red)
* `.text-secondary` (gray)
* `.text-white` (white)
* `.text-dark` (dark gray or black)
* `.text-body` (default text color)
* `.text-light` (light color)

Example:

```html
<p class="text-primary">This text is blue.</p>
<p class="text-danger">This text is red.</p>
```

---

### Background Colors

To change the background color of a container or any element, Bootstrap provides these classes:

* `.bg-primary`
* `.bg-success`
* `.bg-info`
* `.bg-warning`
* `.bg-danger`
* `.bg-secondary`
* `.bg-dark`
* `.bg-light`

Example:

```html
<div class="bg-primary text-white p-3">Blue background with white text</div>
<div class="bg-warning p-3">Orange background</div>
```

---

### 2.4.8 Bootstrap 5 Tables

Tables are very useful to show data clearly. Bootstrap adds style and different features to HTML tables.

---

### Basic Table

Use the `.table` class to style a basic table. This adds padding and horizontal lines between rows.

Example:

```html
<table class="table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ekamjot</td>
      <td>22</td>
      <td>Delhi</td>
    </tr>
    <tr>
      <td>Simran</td>
      <td>24</td>
      <td>Chandigarh</td>
    </tr>
  </tbody>
</table>
```

---

### Table Variants and Features

Bootstrap offers many classes to style tables:

* `.table-striped`: adds stripes (alternating background color) to rows for better readability.
* `.table-bordered`: adds borders around cells and table.
* `.table-hover`: changes row color on mouse hover.
* `.table-dark`: dark background with white text.
* `.table-borderless`: removes all borders from table.

You can combine these classes for different effects:

Example:

```html
<table class="table table-striped table-bordered table-hover">
  ...
</table>
```

---

### Contextual Classes

Bootstrap provides color classes to highlight rows or cells in tables:

* `.table-primary`
* `.table-success`
* `.table-danger`
* `.table-info`
* `.table-warning`
* `.table-active`
* `.table-secondary`
* `.table-light`
* `.table-dark`

Example:

```html
<tr class="table-success">
  <td>Success row</td>
</tr>
<tr class="table-danger">
  <td>Danger row</td>
</tr>
```

These classes are useful to show status or importance in data tables.

---

### Summary of Bootstrap Text, Colors, and Tables:

* Bootstrap styles headings with different sizes and boldness.
* Display headings are large titles for important text.
* Text and background colors are easy to add with utility classes.
* Tables are styled with padding, borders, stripes, and hover effects.
* Contextual color classes help highlight table rows or cells.
* Combining table classes improves readability and looks professional.

---

### Sample Code We Tried:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Bootstrap Text and Tables</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <div class="container mt-4">

    <h1 class="display-3">Bootstrap Display Heading</h1>
    <p class="h4 text-primary">This is a primary colored heading.</p>

    <table class="table table-striped table-bordered table-hover mt-4">
      <thead>
        <tr class="table-dark">
          <th>Name</th>
          <th>Age</th>
          <th>City</th>
        </tr>
      </thead>
      <tbody>
        <tr class="table-success">
          <td>Ekamjot</td>
          <td>22</td>
          <td>Delhi</td>
        </tr>
        <tr class="table-warning">
          <td>Simran</td>
          <td>24</td>
          <td>Chandigarh</td>
        </tr>
        <tr class="table-danger">
          <td>Raj</td>
          <td>26</td>
          <td>Mumbai</td>
        </tr>
      </tbody>
    </table>

  </div>

</body>
</html>
```

---

### What I Learned:

* Text styles help organize information and improve reading.
* Colors make the website look attractive and help in signaling meaning.
* Tables can be styled easily with Bootstrap classes.
* Using stripes, borders, and hover effects make data easier to understand.
* Contextual classes give additional meaning by coloring rows.

---

### Conclusion:

Day 13 was interesting because text, colors, and tables are key parts of every website. Learning these Bootstrap features will help me build clean, colorful, and readable pages. I practiced several examples and now feel confident in using Bootstrap text and table utilities. Next, I look forward to learning about images, alerts, and buttons.

---

**BY: Ekamjot Kaur**
**URN 2302867**
**CRN 2315264**
**Page no. 13**


