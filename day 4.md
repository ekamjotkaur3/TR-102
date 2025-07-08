**Training Day 4 Report:**  
**Date:** 8 June 2024

**Location:** Science & Technology Entrepreneurs' Park  

**Project Title:** *Create a Personal Hobby Website using HTML*

On Day 4, we applied everything we learned over the past three days to develop a **fully functional personal website** centered around the theme of hobbies. This practical project was designed to consolidate our HTML knowledge and introduce more refined structuring and styling techniques. The goal was to produce a multi-page website that is both visually appealing and easy to navigate, showcasing personal interests with descriptive content and images.

### Project Objectives:
- Showcase at least **3 hobbies**, each accompanied by images, descriptive paragraphs, and semantic layout.
- Include **internal navigation** between pages using hyperlinks for smooth user experience.
- Apply **styling** through inline and internal CSS to enhance the website’s look.
- Use tables where appropriate to organize information such as schedules or lists.
- Develop a well-structured folder and file system for organizing the website files.

### Website Sections:
The website was divided into four main pages, each focusing on a specific aspect of the hobby site:

1. **Home Page**
   - Welcoming visitors with an engaging introduction.
   - Included a **navigation menu** with links to the other pages.
   - Used semantic tags such as `<header>`, `<nav>`, and `<footer>` for a meaningful page structure.
   - Basic styling applied to headings and navigation links for consistency and readability.

2. **Hobbies Page**
   - Detailed list of hobbies displayed using an unordered list `<ul>`.
   - Each hobby was described within `<section>` tags to logically group content.
   - Used headings `<h2>` to differentiate each hobby.
   - Included short paragraphs highlighting why the hobby is important or enjoyable.
   - Incorporated inline CSS to add color and spacing to each section.

3. **Gallery Page**
   - Showcased images related to the hobbies using the `<img>` tag.
   - Discussed image attributes such as `alt` for accessibility and `width`/`height` for size control.
   - Arranged images in a visually pleasing grid using basic CSS techniques like margins and display properties.
   - Added captions below images using `<figcaption>` inside `<figure>` tags to provide context.
   - Highlighted the importance of optimizing images for faster loading and better performance.

4. **Contact Page**
   - Provided contact details including email and social media links.
   - Used anchor tags `<a>` for clickable email (`mailto:`) and external social profiles.
   - Introduced a simple contact form layout using form elements (though non-functional at this stage).
   - Encouraged use of placeholder text in form inputs for better UX.
   - Applied internal CSS to style the form and contact details for a professional appearance.

### Features Implemented:

- **Semantic Tags for Layout:**  
  We used tags like `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>` to give structure and meaning to different parts of the website. This approach improves accessibility for screen readers and enhances SEO.

- **Internal Linking Using `<a>`:**  
  Each page was linked via a navigation bar, enabling easy movement between Home, Hobbies, Gallery, and Contact pages. This internal linking is fundamental for creating cohesive websites.

- **Tables for Organizing Information:**  
  On the Hobbies page, a small table was used to display a weekly book reading schedule. This helped us understand how tabular data can be presented clearly.

- **Inline and Internal CSS for Styling:**  
  - Inline CSS was used for quick changes like setting colors and font sizes on specific elements.  
  - Internal CSS (within the `<style>` tag in the `<head>`) managed broader styles, including body fonts, navigation layout, and spacing.  
  - This combination gave us insight into when and how to apply different CSS techniques effectively.

### Sample Code Snippet:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Hobbies</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f4f4f4; margin: 0; padding: 0; }
    nav a { margin: 10px; text-decoration: none; color: #333; font-weight: bold; }
    nav a:hover { color: #007BFF; }
    header, footer { background-color: #222; color: white; padding: 20px 0; text-align: center; }
    section { background-color: white; margin: 20px auto; padding: 20px; max-width: 800px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1);}
    h1, h2 { margin-bottom: 15px; }
  </style>
</head>
<body>
  <header>
    <h1>My Personal Hobby Site</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="hobbies.html">Hobbies</a>
    <a href="gallery.html">Gallery</a>
    <a href="contact.html">Contact</a>
  </nav>
  <section>
    <h2>Photography</h2>
    <p>I love capturing landscapes and city life through my camera lens. It helps me appreciate the beauty around us and express creativity.</p>
  </section>
  <footer>
    <p>© 2025 Ekamjot Kaur</p>
  </footer>
</body>
</html>
