# Template for W3C Workshop home pages

(This template was originally modeled after the [Workshop on Web & Virtual Reality](https://www.w3.org/2016/06/vr-workshop/), but converted for into jekyll for an easier maintenance.)

## Using the template

The template is meant to be cloned for a new Workshop and used to set up as the Workshop's home page through the suitable modification of the content. Here are some notes on modifying the content:

- The template is to be used in conjunction with [jekyll](https://jekyllrb.com/). This means that the main content of the pages are provided in Markdown (to be more precise, a dialect called [“Kramdown”](https://kramdown.gettalong.org/syntax.html)), and jekyll would convert those on the server side into a static Web site. You can install jekyll locally (which is probably a good idea for testing), but the best way of deploying the website is to keep it as a github repository, turning on the `Settings/Github Pages` option. Jekyll is automatically ran by github, and the Web site will be available as a `https://w3c.github.io/yourreponame/index.html` (provided that cloned repository is kept within the W3C organization).
- The jekyll site generation is based on template HTML files in the `_layouts` folder, and may refer to html snippets in the `_includes` folder. Many of the changes (sponsors, title of the workshop, etc.) must be done in those files.
- The class `todo` has been used for all things that must be finalized eventually. These are displayed with a yellow background in the template. (Note that the Kramdown specific `{: .todo}` syntax is also used time-to-time in the Kramdown files to set the class.)
- The “draft” watermark is generated via an SVG code incorporated in the CSS style in the `_layout` files. Obviously, this should be removed when the web site is final.
- You may want to use a bona fide W3C URL for the workshop; this can be done by setting a redirection to the `github.io` page. Do a `curl` on, for example, `https://www.w3.org/publishing/.htaccess` for a pattern.

You can look at this template, served as HTML after jekyll has done its job at the corresponding `github.io` page: https://w3c.github.io/ws-homepage-template/index.html.

---

Ivan Herman, ivan@w3.org
