# sane.html
Template for building static HTML5 websites.  Building a web application instead?  Check out [sane.app](https://github.com/rchillard/sane.app).

## Usage

You can `git clone` or download this repository. There is no separate distribution folder.  View a [preview here](https://rchillard.github.io/sane.html/).

### Basic structure

A sane.html site initially has this structure:

```
.
├── css
│   ├── sane.css
│   └── styles.css
├── doc
├── img
│   └── originals
├── js
│   ├── main.js
│   ├── plugins.js
│   └── vendor
│       └── example-dependency.js
├── 404.html
├── favicon.ico
├── humans.txt
├── icon.png
├── index.html
├── robots.txt
├── tile.png
└── tile-wide.png
```

### css

This directory should contain all your project's CSS files. It includes some
initial CSS to help get you started from a solid foundation. [About CSS](doc/css.md).

### doc

This directory contains all the documentation. Use it as the location for your documentation. [Read Docs](doc/README.md).

### img

This directory contains processed images that have been resized and compressed.  The originals sub-directory can contain unprocessed images, if you choose to commit them to version control.

### js

This directory should contain all your project's JS files. Libraries, plugins,
and custom code can all be included here. It includes some initial JS to help
get you started. [About JavaScript](doc/js.md).

### 404.html

A helpful custom 404 to get you started.

### index.html

This is the default HTML skeleton that should form the basis of all pages on
your site. Make sure that you update the URLs for the referenced CSS and JavaScript if you
modify the directory structure at all.

### humans.txt

Edit this file to include the team that worked on your site/app, and the
technology powering it.

### robots.txt

Edit this file to include any pages you need hidden from search engines.

### Icons

Replace the default `favicon.ico`, `tile.png`, `tile-wide.png` and Apple Touch
Icon with your own.

## Influences
sane.html is primarily based off of [HTML5Boilerplate](https://github.com/h5bp/html5-boilerplate) with the following changes:
- Removal of editor and git configuration files
- Removal of build process and npm configuration files
- Removal of all extra elements supporting web applications
- Removal of signficant amounts of superfluous documentation
- Removal of Google Analytics (try out a privacy preserving alternative instead)
- Removal of explicit support for Internet Explorer (e.g. no browserconfig.xml)