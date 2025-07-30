# Training Day 20 Report  
**Date:** 27 June 2024  
**Location:** Science & Technology Entrepreneurs' Park

Today, I started working on a new individual project — building a **Student Dashboard**. The purpose of this dashboard is to display useful features like timetable, attendance, announcements, and subject info, all in one organized and interactive webpage.

###  What I Did:

1. **Project Planning:**
   - Outlined the dashboard's layout: Header banner, Navigation Tabs, Timetable section, Attendance Tracker, and Subject Details.
   - Sketched the structure for future use of JavaScript interactivity.

2. **Setting Up Basic Structure:**
   - Created the `index.html` file with proper `<head>` and `<body>` structure.
   - Linked Bootstrap 5 and Google Fonts (Inter) for layout and typography.
   - Used `<div class="container">` to centralize the main content.

3. **Top Banner (Marquee):**
   - Added a scrolling banner at the top using `<div class="marquee">`.
   - Used JavaScript to show the current date dynamically:
     ```javascript
     document.getElementById("dateBanner").textContent =
       new Date().toLocaleDateString(undefined, {
         weekday: 'long', month: 'short', day: 'numeric', year: 'numeric'
       });
     ```

4. **Initial Layout with Bootstrap:**
   - Prepared placeholders for tabs: Welcome, Subjects, Timetable, Attendance.
   - Started styling using custom CSS and Bootstrap utility classes.

###  Summary:
I successfully set up the basic layout and styling of the student dashboard. The page now loads with a date banner, and the structure is ready to include more interactive features.

---

**BY:** Ekamjot Kaur  
**URN:** 2302867  
**CRN:** 2315264  
**Page No.:** 20
