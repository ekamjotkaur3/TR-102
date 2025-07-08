# Training Day 7 Report  
**Date:** 12 June 2024  

**Location:** Science & Technology Entrepreneurs' Park  

**Project Title:** *Introduction to CSS – What is CSS & How to Use it in HTML*

---

On Day 7, the training took a significant step forward by introducing us to **CSS (Cascading Style Sheets)**, a crucial language that works hand-in-hand with HTML to enhance the appearance and layout of web pages. The session aimed to provide a comprehensive understanding of CSS, highlighting its role in separating content structure from presentation, and to demonstrate the various ways CSS can be applied to HTML documents for styling.

Understanding CSS is foundational for any aspiring web developer because it transforms plain HTML pages into visually engaging and user-friendly websites. This day’s session laid the groundwork for mastering web design principles and improving the overall user experience by controlling colors, fonts, spacing, positioning, and responsiveness.

### Learning Objectives:  
- Develop a clear understanding of what CSS is and why it is essential in web development.  
- Explore the three main ways CSS can be applied to HTML: **Inline**, **Internal**, and **External**.  
- Understand the advantages and disadvantages of each CSS application method.  
- Practice writing simple CSS rules and observe their effects on HTML elements.

---

### Key Topics Covered:

#### What is CSS?  
CSS, or Cascading Style Sheets, is a stylesheet language designed to describe the presentation of HTML documents. Unlike HTML, which focuses on the structure and content of a webpage, CSS controls **how** this content is displayed. This includes colors, fonts, layouts, spacing, borders, and many other visual aspects.

One of the primary benefits of CSS is its ability to style multiple web pages consistently by defining styles once and applying them across several documents. This separation of content (HTML) and presentation (CSS) allows for easier maintenance, improved accessibility, and more flexible designs.

During the session, we discussed that CSS can be applied not only to screens but also to other media types such as printers or mobile devices, enabling adaptive and responsive designs.

#### Using CSS in HTML  
We explored the three standard methods to include CSS styles in HTML:

1. **Inline CSS**  
   Inline CSS applies styles directly within an HTML tag using the `style` attribute. It affects only that specific element. This method is simple for quick, one-off style changes but is not scalable for larger projects because it mixes content with styling and can lead to code duplication.

   Example:  
   ```html
   <h1 style="color: blue;">A Blue Heading</h1>
