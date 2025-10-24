# 🚀 ICT Club Challenge - HTML Webpage Task

## 👋 Welcome to the ICT Club Challenge!

This task will help you build a complete HTML webpage for the ICT Club using semantic HTML elements, forms, tables, and ASCII art. You'll learn essential web development skills while creating a functional and visually appealing webpage.

---

## 📋 Task Overview

Create a complete HTML webpage for the ICT Club that includes:
- Header with navigation
- About section with image
- Events table
- Registration form
- ASCII art section
- Footer with contact information

---

## 🎯 Learning Objectives

By completing this task, you will learn:
- HTML semantic elements (`<header>`, `<section>`, `<footer>`, etc.)
- Form elements and validation
- Table structure and styling
- ASCII art using `<pre>` tags
- Image embedding and alt text
- Navigation with anchor links
- HTML comments and organization

---

## 📝 Detailed Instructions

### Step 1: Create the Basic HTML Structure

Create a new file called `ict-club.html` and start with the basic HTML5 structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>ICT Club Challenge Page</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

### Step 2: Build the Header Section

Create a header with:
- Main title with rocket emoji: "🚀 ICT Club"
- Tagline: "Think. Code. Build. Inspire."
- Horizontal rule (`<hr>`)
- Navigation menu with links to sections

**Required elements:**
- `<header>` tag
- `<h1>` for main title
- `<h3>` for tagline
- `<nav>` with unordered list (`<ul>`) and list items (`<li>`)
- Anchor links (`<a href="#section-id">`) for navigation

### Step 3: Create the About Section

Build the about section with:
- Section heading: "About ICT Club"
- Welcome paragraph
- Inspirational quote in `<blockquote>`
- Image with proper alt text

**Image to include:**
Use this image URL: `https://avatars.githubusercontent.com/u/238552231?v=4`
- Alt text: "ICT Club Image"

**Required elements:**
- `<section id="about">`
- `<h2>` for section heading
- `<p>` for paragraph
- `<blockquote>` for quote
- `<img>` with src and alt attributes

### Step 4: Build the Events Table

Create a table showing upcoming events with:
- Section heading: "Upcoming Events"
- Table with border, cellpadding, and cellspacing
- Caption: "Event Schedule"
- Table headers: Event Name, Date, Time
- Two event rows with the specified data

**Event Data:**
| Event Name | Date | Time |
|------------|------|------|
| DEv talk serious | every monday | 3:00 LT |
| Web Development Bootcamp | EVERY FRIDAY | 10:00 LT |

**Required elements:**
- `<section id="events">`
- `<table>` with border="1", cellpadding="5", cellspacing="0"
- `<caption>` for table title
- `<thead>` with `<tr>` and `<th>` elements
- `<tbody>` with `<tr>` and `<td>` elements

### Step 5: Create the Registration Form

Build a comprehensive registration form with three fieldsets:

#### Personal Info Fieldset:
- Full Name (text input, required)
- Email (email input, required)
- Gender (radio buttons: Male/Female)

#### Interest Areas Fieldset:
- Web Development (checkbox)
- Robotics (checkbox)
- Cyber Security (checkbox)
- Design (checkbox)

#### Department Fieldset:
- Select dropdown with options:
  - ICT (default selected)
  - Computer Science
  - Engineering
  - Mathematics

**Required elements:**
- `<section id="form">`
- `<form>` element
- Three `<fieldset>` elements with `<legend>`
- Various input types: text, email, radio, checkbox, select
- Proper `<label>` elements with `for` attributes
- Submit button

### Step 6: Create the ASCII Art Section

Build the ASCII art section with:
- Section heading: "Fun: HTML ASCII Drawing"
- Explanatory paragraph
- ASCII art using `<pre>` tags
- "Back to Top" link

**ASCII Art Pattern:**
```
          /\         /\ 
         /  \_______/  \ 
        /               \
       |   ICT CLUB ♥    |
        \               /
         \___     _____/
             \   /
              \_/
```

**Required elements:**
- `<section id="art">`
- `<h2>` for heading
- `<p>` for explanation
- `<pre>` for ASCII art
- Anchor link to top

### Step 7: Create the Footer

Build the footer with:
- Horizontal rule
- Email contact information
- Copyright notice

**Required elements:**
- `<footer id="footer">`
- `<hr>` for separation
- `<p>` elements for content
- Copyright symbol: `&copy;`

---

## 🎨 Visual Reference

The webpage should look like this:

![ICT Club Webpage](https://avatars.githubusercontent.com/u/238552231?v=4)

**Key visual elements:**
- Clean, minimal design with white background
- Black text on white background
- Proper spacing between sections
- Table with borders
- Form elements properly labeled
- ASCII art in monospace font
- Navigation links that scroll to sections

---

## ✅ Checklist

Before submitting, ensure you have:

- [ ] Created `ict-club.html` file
- [ ] Used proper HTML5 DOCTYPE
- [ ] Included all semantic elements (`<header>`, `<section>`, `<footer>`)
- [ ] Added navigation with working anchor links
- [ ] Included the specified image with alt text
- [ ] Created the events table with proper structure
- [ ] Built the registration form with all required fields
- [ ] Added ASCII art using `<pre>` tags
- [ ] Included footer with contact information
- [ ] Used proper HTML comments for organization
- [ ] Tested all form elements
- [ ] Verified navigation links work
- [ ] Checked for proper HTML structure

---

## 🚀 Bonus Challenges

If you want to go further, try these enhancements:

1. **Add CSS styling** to make the page more visually appealing
2. **Add form validation** using HTML5 attributes
3. **Create a responsive design** that works on mobile devices
4. **Add more ASCII art** patterns
5. **Include additional form fields** like phone number or year of study
6. **Add JavaScript** for interactive features

---

## 📚 HTML Elements Reference

Here are the key HTML elements you'll need:

```html
<!-- Semantic Elements -->
<header>, <nav>, <section>, <footer>

<!-- Text Elements -->
<h1>, <h2>, <h3>, <p>, <blockquote>

<!-- List Elements -->
<ul>, <li>

<!-- Table Elements -->
<table>, <thead>, <tbody>, <tr>, <th>, <td>, <caption>

<!-- Form Elements -->
<form>, <fieldset>, <legend>, <label>, <input>, <select>, <option>

<!-- Other Elements -->
<img>, <pre>, <hr>, <a>
```

---

## 🆘 Need Help?

If you encounter any issues:
- Check the HTML documentation: https://developer.mozilla.org/en-US/docs/Web/HTML
- Validate your HTML: https://validator.w3.org/
- Ask your peers in the DDU ICT Club
- Reach out to the instructors

---

## 📤 Submission

### Step 1: Create Your Repository

1. **Go to GitHub** and create a new repository
2. **Repository Name Format:** `my-first-html-ict001`
   - Replace `ict001` with your actual student ID or name tag
   - Examples: `my-first-html-ict123`, `my-first-html-john-doe`, `my-first-html-ddu456`
3. **Make it Public** so instructors can view it
4. **Add a Description:** "ICT Club HTML Challenge - My First Webpage"
5. **Initialize with README** (optional)

### Step 2: Clone and Set Up Your Repository

```bash
# Clone your repository
git clone https://github.com/your-username/my-first-html-ict001.git
cd my-first-html-ict001

# Configure Git (if not already done)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: Add Your HTML File

1. Save your file as `ict-club.html` in the repository folder
2. Test it in a web browser to ensure everything works
3. Ensure all sections are properly linked
4. Verify the form elements work correctly
5. Check that the ASCII art displays properly

### Step 4: Commit and Push Your Code

```bash
# Add your HTML file
git add ict-club.html

# Commit with a meaningful message
git commit -m "Add ICT Club HTML webpage with all required sections"

# Push to your repository
git push origin main
```

### Step 5: Create a README.md (Optional but Recommended)

Create a `README.md` file in your repository with:

```markdown
# ICT Club HTML Challenge

## Project Description
This is my first HTML webpage created for the ICT Club challenge. The webpage includes a complete ICT Club website with navigation, events table, registration form, and ASCII art.

## Features
- ✅ Header with navigation
- ✅ About section with image
- ✅ Events table
- ✅ Registration form
- ✅ ASCII art section
- ✅ Footer with contact info

## How to View
Simply open `ict-club.html` in any web browser to view the webpage.

## Student Info
- **Name:** Your Name
- **Student ID:** Your ID (e.g., ICT001)
- **Department:** Your Department
```

### Step 6: Final Push

```bash
# Add README if you created one
git add README.md
git commit -m "Add README with project description"
git push origin main
```

---

## 📋 Final Submission Checklist

Before submitting, ensure you have:

- [ ] Created repository with proper naming: `my-first-html-ict001`
- [ ] Saved file as `ict-club.html`
- [ ] Tested webpage in browser
- [ ] All navigation links work
- [ ] Form elements function properly
- [ ] ASCII art displays correctly
- [ ] Committed and pushed code to GitHub
- [ ] Repository is public and accessible
- [ ] Added README.md (optional but recommended)

---

## 🎯 Repository Naming Examples

Here are some examples of proper repository names:

- `my-first-html-ict001`
- `my-first-html-ict123`
- `my-first-html-john-doe`
- `my-first-html-ddu456`
- `my-first-html-sarah-smith`

**Important:** Use lowercase letters and hyphens (-) only!

---

**Good luck and happy coding! 💻✨**

*DDU ICT Club - Web Development Challenge*
