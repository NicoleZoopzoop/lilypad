# lilypad

[![PyPI Version](https://img.shields.io/pypi/v/lilypad.svg?style=flat-square)](https://pypi.python.org/pypi/lilypad/)

A static site generator you don't need to learn.

No config; nothing but `jinja2` and `markdown`. `jinja2` for you templates,
pages, and `markdown` for your blog. All you need is something like this:


```
_src/

    markdown_blog/
        some-article-title.md
        all-about-ferrets.md
        yet-another-post.md

    templates/
        base.html

        lilypad/
            category-index.html
            blog-article.html
            blog.html

        pages/
            homepage.html
            about.html

whatever/
    style.css
    bg.png

```

For an example/demo, I use lilypad to generate
the [lillian.link](http://lillian.link) website,
see [lillian.link's source](https://github.com/lily-seabreeze/lillian.link').

For additional reading, please read `lilypad/lilypad.py`'s docstring.

## Features

  * No config
  * Nothing but `jinja2` for templates and pages and `markdown` for blog

Just `python3 -m pip install lilypad` then use `lilypad` where you have
a `_src` folder containing your jinja `templates/` directory and
`markdown_blog`.

For more info see the readme on Pypi or
the docstring of `lilypad/lilypad.py`.

## install from repo

install from repo: `sudo apt install python3-pip` and
`sudo apt install python3-pip`.
