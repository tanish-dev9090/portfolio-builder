# Online Portfolio Builder

A site builder where users pick a template, fill in a form, and get a shareable portfolio page.

**Live demo:** https://tanish-grover.vercel.app

## Features
1. **Template choice** - Classic, Dark and Bold templates, switchable with a live preview.
2. **Fill-in form** - name, role, about, skills, projects, email, GitHub and LinkedIn.
3. **Shareable portfolio page** - the form data is encoded into the link, so anyone who opens it sees the finished portfolio. No backend or database needed.

## Tech
HTML, CSS and vanilla JavaScript in a single `index.html`.

## How it works
Form data is converted to JSON, Base64-encoded and stored in the URL hash (`#p=...`). When the page loads with that hash, it decodes the data and renders the chosen template.

## Run locally
Open `index.html` in a browser.

## Author
Tanish Grover, Geeta University x NIAT
