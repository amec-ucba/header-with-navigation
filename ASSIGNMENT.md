# 📄 Header with Navbar

Build a page from scratch that moves the navigation bar inside the header, so the site
title and the links share one row and use the page's horizontal space better.

**Points:** 10

## 🎯 Overview

So far, your page layouts have stacked the boxes on top of each other: a header, then a
navigation bar under it, then the main content, then the footer. This exercise shows you a
common variation. You will put the `nav` **inside** the `header`, so the site title sits on
one side and the navigation links sit on the other, on the same line.

There are **no starter files** for this one. You will create every file yourself, starting
from an empty repo. Part 1 builds the HTML, and Part 2 adds the CSS.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 📋 Requirements

1. **Create `index.html` in the root folder of this repo.** This is required. GitHub Pages
   only serves `index.html` at your site's root URL, so any other name gives you a 404.
2. **Complete Part 1** by following the *HTML Foundation* video to build the page's HTML.
3. **Complete Part 2** by following the *Adding the CSS* video to style the page in an
   external stylesheet.
4. **Publish and submit** your page as described in the [README](README.md).

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Create an HTML page and a stylesheet from scratch, without starter files
- Build a page layout with the semantic elements `header`, `nav`, `main`, and `footer`
- Nest one layout box inside another — here, the `nav` inside the `header`
- Mark up a navigation bar as a list of links
- Link an external stylesheet to your HTML page
- Use CSS to place the site title and the navigation links side by side in the header
- Explain why moving the navigation into the header makes better use of horizontal space

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. Watch
them **in order** and follow along in Visual Studio Code. Pause whenever you need time to
finish a step. It is normal to pause, rewind, and rewatch parts of a coding demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Part 1 — HTML Foundation** | Create `index.html` and build the page's structure: the basic HTML document, a `header` with the site title and a `nav` inside it, the main content, and the footer. |
| **Part 2 — Adding the CSS** | Create your stylesheet, link it to `index.html`, and style the page so the site title and the navigation links sit side by side inside the header. |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> HTML and CSS, and follow this repo for setting up and submitting:
>
> - **Setting up:** don't make a new folder on your desktop. Create your own repo from this
>   template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started). Create your files inside that repo folder.
> - **Naming your file:** name your HTML page **`index.html`**, whatever name the video
>   uses. GitHub Pages only serves `index.html` at your site's root URL; any other name
>   gives you a 404.
> - **Submitting:** don't zip your folder or upload a file. Publish your page to GitHub
>   Pages and submit a pull request URL in Canvas, as described in the
>   [README](README.md#-submitting-the-assignment).

> [!IMPORTANT]
> Open the entire repo **folder** in VS Code, not a single HTML file. Keep `index.html` in
> the root folder, and make sure the `href` in your `<link>` element matches where your
> stylesheet actually is.

## 📂 Files You Will Create

The repo starts with no project files. By the end, it should contain at least:

| File | Purpose |
| --- | --- |
| `index.html` | Your web page. **Must** be named `index.html` and sit in the root folder. |
| Your stylesheet | The CSS file from Part 2, such as `main.css`. Use the name from the video, and link it in the `head` of `index.html`. |

If the video uses any other files, such as a reset stylesheet or images, create or add them
the same way the video does and keep them in the repo.

## 🧮 Grading Rubric

| Criteria | Full credit looks like | Points |
| --- | --- | --- |
| **Files & Setup** | `index.html` is in the root folder. The stylesheet is in the repo, is linked in the `head` of `index.html`, and loads on the live page. | 1 |
| **HTML Document Structure** | `index.html` has a complete HTML document: `<!DOCTYPE html>`, `html`, `head` with a `title`, and `body`. Every element is properly nested and closed. | 1 |
| **Page Layout Boxes** | The page is built from semantic layout elements: a `header`, a `main` with the page content, and a `footer`. | 2 |
| **Nav Inside the Header** | The `nav` is nested **inside** the `header`, after the site title, not below the header as a separate box. | 2 |
| **Navigation Markup** | The navigation links are marked up as a list (`ul` and `li`) of `a` elements, each with an `href`. | 1 |
| **Header Layout** | On the live page, the site title and the navigation links sit side by side on the same row inside the header, and the links run horizontally. | 2 |
| **Published & Submitted** | The page is live on GitHub Pages, and the pull request into `main` has every section of its template filled in. | 1 |
| | **Total** | **10** |

Each criterion is graded on the live GitHub Pages site. It earns its full points when it
matches the *Full credit looks like* column. Partial credit may be given for work that is
close but not quite right, such as a `nav` inside the header whose links still stack
vertically.

## ✅ Before You Submit

Check the following:

- [ ] Your page is named exactly `index.html` and sits in the root folder of the repo
- [ ] Your stylesheet is in the repo and linked in the `head` of `index.html`
- [ ] The page has the basic HTML structure: `DOCTYPE`, `html`, `head`, `title`, and `body`
- [ ] The page has a `header`, `main`, and `footer`
- [ ] The `nav` is **inside** the `header`
- [ ] The navigation links are a list of `a` elements inside the `nav`
- [ ] The site title and the navigation links sit side by side in the header
- [ ] You saved **both** `index.html` and your stylesheet
- [ ] The page is live on GitHub Pages and the URL is in your pull request

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save **both** files? It's easy to save the HTML and forget the CSS.
- Is the file named exactly `index.html`, all lowercase?
- Does the `href` in your `<link>` element match your stylesheet's file name and folder
  exactly, including spelling and capitalization?
- Is the `<link>` element inside the `head`, not the `body`?
- Is the closing `</nav>` **before** the closing `</header>`? If the `nav` comes after
  `</header>`, it isn't inside the header.
- Does every class or element name in your CSS match your HTML exactly? Class selectors
  start with a `.`.
- Did a new rule end up inside another rule's curly braces? Check that every `{` has a
  matching `}`.
- Is every property followed by a colon and every value followed by a semicolon?

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — Document and website structure](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents)
- [MDN — `<header>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/header)
  and [`<nav>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/nav)
- [MDN — Styling links](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Styling_links)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) — paste your
  HTML in to catch unclosed tags
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) —
  paste your CSS in to catch missing braces and semicolons

---

The AI policy and submission instructions are in the [README](README.md).
