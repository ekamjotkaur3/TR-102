### **Training Day 14 Report:**

**Date:** 18 June 2024

**Location:** Science & Technology Entrepreneurs' Park

**Project Title:** *Bootstrap 5 Images, Alerts, Buttons, Progress Bars, and Spinners*

On Day 14, we learned about important Bootstrap 5 components like images, alerts, buttons, progress bars, and spinners. These components help make websites interactive, visually pleasing, and user-friendly.

---

### Project Objectives:

* Understand how to style images using Bootstrap.
* Learn to create alert messages to show notifications.
* Explore different styles of Bootstrap buttons.
* Study progress bars to show task progress.
* Learn how to use spinners as loading indicators.

---

### 2.4.9 Bootstrap 5 Images

Bootstrap provides classes to easily style images with rounded corners, circles, or thumbnails.

---

### Rounded Corners

Add the `.rounded` class to give an image soft rounded corners.

Example:

```html
<img src="cinqueterre.jpg" class="rounded" alt="Cinque Terre">
```

---

### Circle Image

Use the `.rounded-circle` class to make the image circular.

Example:

```html
<img src="cinqueterre.jpg" class="rounded-circle" alt="Cinque Terre">
```

---

### Thumbnail Image

Add `.img-thumbnail` to give the image a border and padding, making it look like a photo thumbnail.

Example:

```html
<img src="cinqueterre.jpg" class="img-thumbnail" alt="Cinque Terre">
```

---

### 2.4.10 Bootstrap 5 Alerts

Alerts show important messages to users, like success, warning, or error notifications.

---

### Basic Alerts

Use the `.alert` class with a contextual class to create alerts:

* `.alert-success` (green)
* `.alert-danger` (red)
* `.alert-info` (blue)
* `.alert-warning` (orange)

Example:

```html
<div class="alert alert-success">
  <strong>Success!</strong> Indicates a successful action.
</div>
```

---

### Alert Links

Links inside alerts can use `.alert-link` to match the alert style.

Example:

```html
<div class="alert alert-success">
  <strong>Success!</strong> You should <a href="#" class="alert-link">read this message</a>.
</div>
```

---

### Closing Alerts

Add `.alert-dismissible` and a close button to allow users to close the alert.

Example:

```html
<div class="alert alert-success alert-dismissible">
  <button type="button" class="btn-close" data-bs-dismiss="alert"></button>
  <strong>Success!</strong> This alert can be closed.
</div>
```

---

### Animated Alerts

Add `.fade` and `.show` classes to smoothly fade out alerts when closed.

Example:

```html
<div class="alert alert-danger alert-dismissible fade show">
  <button type="button" class="btn-close" data-bs-dismiss="alert"></button>
  <strong>Danger!</strong> This is an animated alert.
</div>
```

---

### 2.4.11 Bootstrap Buttons

Bootstrap offers many button styles using the `.btn` class with color and size options.

---

### Button Colors

Some examples of button color classes:

* `.btn-primary` (blue)
* `.btn-secondary` (gray)
* `.btn-success` (green)
* `.btn-danger` (red)
* `.btn-warning` (orange)
* `.btn-info` (light blue)
* `.btn-dark` (dark gray)
* `.btn-light` (light gray)
* `.btn-link` (looks like a link)

---

### Outline Buttons

Use `.btn-outline-*` classes to create buttons with colored borders and transparent backgrounds.

Example:

```html
<button class="btn btn-outline-primary">Primary Outline</button>
```

---

### Button Sizes

Change button sizes with `.btn-lg` (large) or `.btn-sm` (small).

---

### Block Level Buttons

Use `.d-grid` on the container to make buttons stretch full width.

Add `.gap-*` classes to add spacing between multiple buttons.

---

### Active and Disabled Buttons

Use `.active` class to show an active state.

Use `disabled` attribute or `.disabled` class to disable buttons.

---

### Buttons with Spinners

Add spinners inside buttons to show loading state.

Example:

```html
<button class="btn btn-primary">
  <span class="spinner-border spinner-border-sm"></span> Loading...
</button>
```

Disable the button while loading with the `disabled` attribute.

---

### 2.4.12 Bootstrap 5 Progress Bars

Progress bars show how far a task has progressed.

---

### Basic Progress Bar

Use `.progress` container and `.progress-bar` to create a bar.

Example:

```html
<div class="progress">
  <div class="progress-bar" style="width: 70%"></div>
</div>
```

---

### Progress Bar Height

Default height is 1rem. Change height using inline style:

```html
<div class="progress" style="height: 20px">...</div>
```

---

### Progress Bar Labels

Add text inside the progress bar:

```html
<div class="progress-bar" style="width: 70%">70%</div>
```

---

### Colored Progress Bars

Add background color classes like `.bg-success`, `.bg-info`, `.bg-warning`, `.bg-danger`.

---

### Striped and Animated Bars

Add `.progress-bar-striped` for stripes.

Add `.progress-bar-animated` for moving stripes.

---

### Multiple Progress Bars

Stack multiple `.progress-bar` elements inside one `.progress`.

Example:

```html
<div class="progress">
  <div class="progress-bar bg-success" style="width:40%">Free Space</div>
  <div class="progress-bar bg-warning" style="width:10%">Warning</div>
  <div class="progress-bar bg-danger" style="width:20%">Danger</div>
</div>
```

---

### 2.4.13 Bootstrap 5 Spinners

Spinners show loading animations.

---

### Basic Spinner

Use `.spinner-border` for spinning effect.

```html
<div class="spinner-border"></div>
```

---

### Colored Spinners

Add text color classes to change spinner color:

* `.text-primary`
* `.text-success`
* `.text-info`
* `.text-warning`
* `.text-danger`
* `.text-secondary`
* `.text-dark`
* `.text-light`

Example:

```html
<div class="spinner-border text-primary"></div>
<div class="spinner-border text-success"></div>
```

---

### Growing Spinners

Use `.spinner-grow` for pulsing effect.

```html
<div class="spinner-grow text-info"></div>
```

---

### Spinner Sizes

Add `.spinner-border-sm` or `.spinner-grow-sm` for smaller spinners.

---

### Spinner Inside Buttons

Put spinners inside buttons to indicate loading:

```html
<button class="btn btn-primary">
  <span class="spinner-border spinner-border-sm"></span> Loading..
</button>
```

Disable button when loading:

```html
<button class="btn btn-primary" disabled>
  <span class="spinner-grow spinner-grow-sm"></span> Loading..
</button>
```

---

### Summary:

On Day 14, I learned how to use Bootstrap 5 to style images, create alerts, design different buttons, add progress bars, and show spinners. These components improve the look and feel of websites and make them interactive. I practiced examples with simple code and now feel confident using these Bootstrap elements in my projects.

---

**BY: Ekamjot Kaur**
**URN 2302867**
**CRN 2315264**
**Page no. 14**

