# Template for W3C Workshop home pages

(This template was originally modeled after the [Workshop on Web & Virtual Reality](https://www.w3.org/2016/06/vr-workshop/), but converted for into jakyll for an easier maintenance.)

## Some note on the template

- The template is meant to be used with [jakyll](https://jekyllrb.com/). This means that the main content of the pages are provided in Markdown (to be more precise, a jakyll dialect called “Kremdown”), and jakyll would convert those into a static Web site. You can install jekyll locally (which is probably a good idea for testing), but the best way of deploying the website is to install it as a github repository, and turn on the `Settings/Github Pages` option. Jekyll is automatically ran by github.
- The jekyll site generation is based on template HTML files in the `_layouts` folder, and may refer to html snippets in the `_includes` folder. Many of the changes (sponsors, title of the workshop, etc.) must be done in those files.
- The class `todo` has been used for all things that must be finalized eventually. These are displayed with a yellow background. Note that the Kremdown specific `{: .todo}` syntax is used in the Kremdown files time-to-time to set the classes.
- The "draft" watermark is generated via an SVG code incorporated in the CSS style in the `_layout` files. Obviously, this should be removed when the web site is final.
- You may want to use a bona fide W3C URL for the workshop; this can be done by setting a redirection to the `github.io` page. Do a `curl` on, for example, `https://www.w3.org/publishing/.htaccess` for a pattern.

You can look at this template, served as HTML after jekyll has done its job at the corresponding `github.io` page: https://w3c.github.io/ws-homepage-template/index.html.
