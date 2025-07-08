**Training Day 3 Report:**  
**Date:** 7 June 2024

**Location:** Science & Technology Entrepreneurs' Park  

**Project Title:** *How to Link Different Web Pages using HTML*

The main objective of Day 3 was to create **multi-page websites** using hyperlinks. This session built upon the foundational knowledge of HTML elements and introduced inter-page linking to simulate real-world website structures. We learned how individual HTML pages can be connected to form a complete and functional website. Through live demonstrations and a hands-on mini project, we focused on linking, navigation menus, and consistent layout design.

### Concepts Practiced:

#### Anchor Tags
- The anchor tag `<a>` is the primary HTML element used to create hyperlinks between web pages.  
- Syntax used:  
  ```html
  <a href="page.html">Page Name</a>
We explored different types of links: internal links (within the same website), external links (to other websites), and email links using `mailto:`.

Emphasized the importance of using descriptive link text for accessibility and SEO.

### Relative vs Absolute URLs
- Relative URLs refer to files within the website folder structure (e.g., `hobbies.html`).
- Absolute URLs specify full web addresses (e.g., `https://example.com`).
- We practiced linking both ways and discussed when to use each.

### Navigation Menus
- Created consistent navigation bars using `<nav>` containing multiple anchor tags.
- Ensured that navigation menus appeared on every page for seamless browsing.
- Styled menus with CSS to enhance user experience.

### Target Attribute
- Learned to use the `target` attribute in anchor tags to control where links open.
- Example: `target="_blank"` opens a link in a new browser tab or window.
- Discussed best practices for usability and security when opening new tabs.

### Linking to Sections within a Page (Anchor Links)
- Introduced fragment identifiers using `id` attributes and `href="#section-id"` links.
- This enabled quick navigation to specific parts of a long webpage.

### Hands-on Mini Project:
- Built a simple 3-page website: Home, About, and Contact pages.
- Implemented a navigation menu linking all pages using relative URLs.
- Added internal anchor links to jump to different sections within a page.
- Styled the navigation bar with basic CSS for a clean, consistent look.

### Additional Topics Covered:
- Proper folder and file organization to ensure links function correctly.
- Troubleshooting broken links and using browser developer tools to debug.
- Discussed accessibility considerations, such as using `title` attributes on links for additional context.

### Sample Code Snippet:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Simple Multi-page Site</title>
  <style>
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #555;
      font-weight: bold;
    }
    nav a:hover {
      color: #007BFF;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section id="introduction">
    <h2>Introduction</h2>
    <p>This is the homepage of our simple multi-page site.</p>
    <p>Jump to the <a href="#contact-section">Contact Section</a> below.</p>
  </section>

  <section id="contact-section">
    <h2>Contact Us</h2>
    <p>You can reach us via email or phone.</p>
  </section>
</body>
</html>
BY: Ekamjot Kaur

URN 2302867

CRN 2315264

Page no. 3