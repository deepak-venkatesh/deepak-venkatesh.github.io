---
title: Deepak's Notes
description: Personal blog/notes on computing, mathematics, fitness and thoughtful simplicity.
keywords: [computing, mathematics, running, blog, minimalism]
header-includes:
  - <link rel="icon" type="image/x-icon" href="favicon.ico">
---

# Plan to build a website for my notes
## Notes about computer science, electronics, fitness and else
### This page is just so that I can see if others can see

This is a link to the first [post](https://deepak-venkatesh.github.io/posts/post1.html) on the blog.

All text below this is from the github page on using [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

I am using pandoc and it is super simple. Just have a markdown file which I can edit in say vscode and a css.
The website url will be this for the time [being](https://deepak-venkatesh.github.io/).
This is made into an html via this command in the terminal.

```
pandoc -s index.md -c main.css --mathjax -o index.html
```

This site was built using [GitHub Pages](https://pages.github.com/).

**This is bold text**

_This text is italicized_

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

This is a <sub>subscript</sub> text

This is a <sup>superscript</sup> text

This is an <ins>underlined</ins> text

Text that is not a quote

> Text that is a quote

# Example headings

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).

This is an example: $E = mc^2$.

$$
\int_a^b f(x)\,dx = F(b) - F(a)
$$


$$
\begin{aligned}
a &= b + c \\
  &= d + e
\end{aligned}
$$






<footer class="footer">
  <a href="/index.html" class="home-link">↑ back to top</a>
</footer>