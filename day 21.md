# Training Day 21 Report  
**Date:** 28 June 2024  
**Location:** Science & Technology Entrepreneurs' Park

Today, I worked on building the **Timetable and Attendance** features for my Student Dashboard using HTML, Bootstrap, and JavaScript.

###  What I Did:

1. **Timetable Section:**
   - Used JavaScript arrays and objects to store timetable data (subjects, timings, days).
   - Created a dynamic function `renderTimetable()` to loop through data and display it on the page.
   - Used Bootstrap tables and cards to make the timetable responsive.

2. **Attendance Tracking:**
   - Implemented JavaScript functions to:
     - Mark sessions as Present, Absent, or Cancelled.
     - Save attendance data in `localStorage` so it’s not lost on reload.
     - Update UI to show status changes live.

3. **Initialization Function:**
   - Wrote `initAttendance()` to create default keys for each subject/session in local storage.
   - Ensured attendance only updates when a valid mark (present/absent) is selected.

4. **Testing & Debugging:**
   - Ran tests on page load, session switching, and user interactions.
   - Used browser developer tools to debug `localStorage` and DOM issues.

###  Summary:
The dashboard now includes a fully functional timetable and attendance tracker. Users can interact with each session and mark their status, and it will be saved even after refreshing the page.

---
**BY:** Ekamjot Kaur  
**URN:** 2302867  
**CRN:** 2315264  
**Page No.:** 21

