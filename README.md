# canonlearning.ai

The landing site for [Canon Learning](https://github.com/canonlearning/canon):
a home page and an about page. It is plain HTML and one stylesheet, with no
build step, and GitHub Pages serves the files as they are.

- `index.html` is the home page.
- `about/index.html` is the about page and its questions.
- `style.css` styles both.
- `CNAME` sets the address, `canonlearning.ai`.

Each course is its own repository and publishes itself. GitHub Pages serves
a repository named `probability-1` at `canonlearning.ai/probability-1`, so
the links here to a course are relative (`probability-1/`).

To preview, serve this folder with any static file server. The links to a
course work only when a built course sits in a folder beside these files.

The text is CC BY 4.0 and the code is MIT.
