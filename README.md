# Personal Website

This repository contains a minimal example for creating your own static website.
It now lets you enter your information directly on the pages without editing the
code.

## Getting Started

1. Open `index.html` in your browser. Use the **Edit Your Details** form at the
   bottom of the page to add your name, a short introduction, list your skills,
   and describe your education. Click **Save** to store the information in your
   browser's local storage so it appears whenever you reopen the page.
2. Open `blog.html` to create blog posts related to networking and AI. Fill in
   the **Create Post** form with a title, date, and content to add a new entry.
   Posts are also stored in local storage and shown under the form.
3. Style the pages by editing `style.css` or adding your own CSS.
4. Serve the files locally by opening them directly or running a simple web
   server:

```bash
python3 -m http.server
```

Then navigate to `http://localhost:8000` in your browser.

All data is kept only in your browser, so if you clear local storage it will be
removed. You can expand this project further or integrate it with a static site
generator or hosting platform.
