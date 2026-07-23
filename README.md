# Personal Portfolio Website

This repository holds the source for a personal portfolio website hosted with GitHub Pages at https://jsf3467v.github.io. The site presents machine learning and data science work across health care, aviation, and the physical sciences. Each project links to the source code that produced it, and where one exists, to a written paper or a live demonstration.

The site is a single static web page. All of its content and layout live in one `index.html` file, and the visual design is written in Cascading Style Sheets within that same file. The project therefore carries no build step and depends on no external framework. This keeps the page fast to load and simple to maintain, and it allows GitHub Pages to serve the file without additional configuration.

The projects gathered on the site share a common emphasis. Each one pairs a working model or system with a careful evaluation, so that every stated result rests on a measured comparison rather than a single run. The subject matter reaches across several fields, yet the approach stays consistent, and each entry reports a concrete outcome next to the code that generated it.

To view the site on a local machine, serve the folder with any static file server. The command below uses only a standard Python installation.

```
python -m http.server 8000
```

After the server starts, open `http://localhost:8000` in a web browser. Because the page is static, opening the `index.html` file directly in a browser also works, although serving it over a local address more closely reflects how GitHub Pages delivers the page to visitors.

Publication happens automatically. GitHub Pages rebuilds the site from the default branch, so any commit pushed to that branch updates the live page within a short time, and no separate release process is required.