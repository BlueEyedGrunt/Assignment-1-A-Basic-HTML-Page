# Assignment Submission Template

## 1. Student Registration Information
- **Full Name:** Brian O'Brien
- **Student ID (SIS):** BSO23
- **Course Name:** COP3363 — Introduction to Programming in C++ for Majors
- **Instructor Name:** Dr Ahsan Abdullah
- **Date of Submission:** 09-03-2025

---

## 2. Assignment Overview (0.5 Points)
**Title:** A Basic HTML Page

**Objective:**  
The goal of this assignment is to design and deploy a simple, publicly accessible HTML webpage using GitHub Pages. The page demonstrates essential HTML structure and hosting deployment.

---

## 3. Code Implementation (2.0 Points)
- All code is contained in `index.html`.
- Code includes:
  - Proper HTML5 structure.
  - Required fields: Name, Course, Major, SIS ID, and “Hello, World!” message.
- Code is properly indented and formatted.
- Inline comments explain purpose of key sections (student info block, message block, footer).

---

## 4. Results Screenshot(s) (1.0 Point)
- Screenshot(s) of deployed webpage (accessible at https://blueeyedgrunt.github.io/Assignment-1-A-Basic-HTML-Page/) should be attached separately when submitting on Canvas.  
- The screenshot shows the page rendered with all required fields and the message.

---

## 5. Data or Output Results (2.0 Points)
**Output (rendered webpage fields):**
- Brian O'Brien
- COP3363 — Introduction to Programming in C++ for Majors
- Computer Science
- SIS ID: BSO23
- Message: Hello, World!

The page loads correctly at: https://blueeyedgrunt.github.io/Assignment-1-A-Basic-HTML-Page/

---

## 6. Analysis of Results (1.5 Points)
- The output is correct and matches all assignment requirements.
- No issues were encountered beyond the short wait time for GitHub Pages to build.
- Insight: This exercise demonstrated how to connect static HTML code to a live, publicly accessible site, reinforcing both version control and deployment concepts.

---

## 7. Conclusion (1.0 Point)
This assignment successfully produced a static HTML page and deployed it using GitHub Pages.  
Lessons learned include:
- Importance of correct repo structure (`index.html` at root).
- GitHub Pages setup workflow.
Future improvements could include adding CSS/JS interactivity, but the base requirements were met.

---

## 8. Key Reflective Questions (1.5 Points)

**1. Explain a specific part of your code that was most challenging to implement. Why was it difficult, and how did you resolve it?**  
The most challenging part was ensuring the `index.html` was structured and deployed correctly with GitHub Pages. Initially, the site returned 404 errors because the deployment branch/folder wasn’t configured properly. Adjusting the **Pages settings to `/ (root)`** resolved the issue.

**2. If you had to modify your code to handle an additional feature (e.g., session expiration message or logging login attempts), where would you make the changes and why?**  
I would add a `<script>` block at the bottom of `index.html` or link a JavaScript file. This would allow me to implement client-side features like session timers, logging interactions, or other dynamic functionality without altering the static content.

**3. Describe a mistake you made during development and what you learned from it.**  
A mistake I made was initially forgetting to commit the `index.html` file to the repository root. GitHub Pages requires the entry file at the root or `/docs` folder. From this, I learned to double-check repo structure and deployment configurations.

---

## Final Deliverables
- **Public URL:** https://blueeyedgrunt.github.io/Assignment-1-A-Basic-HTML-Page/  
- **Source Code Files:** `index.html`, `README.md`, `SUBMISSION.md`
