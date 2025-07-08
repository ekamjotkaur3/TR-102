# Training Day 5 Report  
**Date:** 10 June 2024  

**Location:** Science & Technology Entrepreneurs' Park  

**Project Title:** *GitHub Learning – Creating Repositories and Adding Files*

---

On Day 5, the focus shifted from pure HTML coding to version control and project management using **GitHub**, a widely-used platform that enables developers to collaborate, manage, and track changes in code repositories. Understanding GitHub is crucial for modern web development workflows as it facilitates teamwork, version control, and project documentation.

This session was aimed at beginners and covered the fundamentals of GitHub repositories, methods to add files, and usage of GitHub Desktop, a graphical interface that simplifies Git operations.

### Learning Objectives:  
- Understand the concept of a **GitHub repository** and why it is essential for code management.  
- Learn step-by-step how to create a repository on the GitHub website.  
- Practice adding files both through the GitHub web interface and by uploading from a local machine.  
- Get acquainted with **GitHub Desktop** for easier local repository management without command line complexity.  
- Learn about **commit messages** and their role in documenting changes.

---

### Key Topics Covered:

#### 1. Creating a Repository on GitHub  
- We started by logging into GitHub (https://github.com) and navigating to the **New repository** page.  
- Explained that a **repository (repo)** is essentially a cloud-based project folder where all the files, versions, and history of changes are stored and tracked.  
- Followed the process of naming a repository (e.g., "MyFirstRepo") and setting its **visibility** as either **public** (accessible to everyone) or **private** (restricted access).  
- Optionally, we selected to initialize the repository with a **README.md** file, which acts as the front page description for the repo, and optionally added a `.gitignore` to exclude files and a license.  
- Created the repository, which then provided a URL for cloning or viewing the project online.  
- Discussed the importance of repositories in real-world projects for collaboration and version control.

#### 2. Adding Files Using a Text Editor and Uploading via GitHub UI  
- Opened Notepad and wrote a simple HTML file named `index.html` to serve as our first webpage within the repository.  
- Demonstrated how to upload files directly to the repository using the GitHub web interface:  
  - Navigated to the repository page, clicked on **Add file** > **Upload files**, and dragged the local file into the browser window.  
  - Added a **commit message** such as "Added initial HTML page" to describe the change before committing.  
  - Emphasized that commit messages help collaborators understand the purpose of each change.  
- Explored how multiple files can be uploaded simultaneously and the importance of organizing files logically.

#### 3. Using GitHub Desktop  
- Introduced **GitHub Desktop**, a graphical user interface that allows users to manage repositories locally and synchronize changes with GitHub without using the command line.  
- Walked through the installation of GitHub Desktop on the computer.  
- Logged into GitHub Desktop using the same credentials as the web interface to link the local app with the GitHub account.  
- Created a new local repository using the GitHub Desktop app, specifying a folder on the computer to hold the project files.  
- Demonstrated how to add files into the local repository folder, then use GitHub Desktop to:  
  - **Stage changes** – selecting which files to include in the next commit.  
  - **Commit changes** – recording the snapshot of the current files with a descriptive message.  
  - **Push changes** – uploading commits to the remote GitHub repository to keep everything synchronized.  
- Showed how to **pull** changes if updates are made remotely or by collaborators.  
- Highlighted the benefits of GitHub Desktop for users uncomfortable with command line Git commands.

---

### Sample HTML Code Created and Uploaded:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First GitHub Page</title>
</head>
<body>
  <h1>Hello, GitHub!</h1>
  <p>This page was uploaded via GitHub.</p>
</body>
</html>
