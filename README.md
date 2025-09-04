# A Basic HTML Page

This repository contains a single-file website (`index.html`) that displays required course info and a simple message, and is deployable via GitHub Pages.

## Overview of System Functionality
- Presents:
  - First & Last Name: **Brian O'Brien**
  - Course Name: **COP3363 — Introduction to Programming in C++ for Majors**
  - Major: **Computer Science**
  - SIS ID: **BSO23**
  - Simple message: **Hello, World!**
- Fully static and responsive, using only HTML/CSS.
- Works on mobile and desktop.

## Deployment (GitHub Pages)
1. Commit `index.html` to the root of this repository.
2. In your repository on GitHub:
   - Go to **Settings → Pages**.
   - Under **Build and deployment**, set:
     - **Source**: *Deploy from a branch*
     - **Branch**: `main` (or `master`), **/ (root)**
   - Click **Save**.
3. Wait for Pages to build (usually 1–2 minutes). Your site will be available at:
   ```
   https://<your-github-username>.github.io/<this-repo-name>/
   ```
   Example if your username were `brian-obrien` and the repo is `a-basic-html-page`:
   `https://brian-obrien.github.io/a-basic-html-page/`

> Tip: Your repo name can be anything, but it must contain `index.html` at the root for Pages to serve it correctly.

## Testing
- Load the public URL on your phone and another device to confirm accessibility.
- If you see a 404 initially, wait a minute and refresh.

## Known Issues / Assumptions
- Assumes you are using **GitHub Pages** with the default Pages build.
- If your repository uses a custom folder (like `/docs`), move `index.html` there and set that folder in **Settings → Pages**.
- If your repo is private, Pages must be configured to publish from private repos (available for paid plans). Otherwise, set the repo to public.

## Project Structure
```
/
├── index.html   # required deliverable
└── README.md    # documentation & deployment steps
```

## License
MIT (or class default).
