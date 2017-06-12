# INTRODUCTION

A nifty [superbook](https://bubbl.in/about) for book-lovers on the web. Brought to you by [Bubblin Superbooks] - an online café for good books.

First of its kind, this manuscript uses only HTML, CSS and JavaScript to render a timeless English classic on to your brwoser. Feel free to read this book anywhere for FREE!

No fancy app to download, no random files to worry about. No stupid email required to start reading it and not even a software upgrade ever on your machine after this one fine morning.

Just a simple book. Straight on the web.

`Supported devices`: Everywhere - iPads, iPhones, Android Phones & tablets, Kindle, Desktops, TVs. See [details](https://bubbl.in/support) but guess what: books are best experienced on tablets lying down!

## THE MANUSCRIPT
The book is live on the url provided at the top.

Slight framerate (FPS) quirks might occur due to the dearth of web standards for books (We hope this will change soon!).

## RECOMMENDED DEVICE:

- Open the [book](https://bubbl.in/cover/emma-by-jane-austen) on Safari (or your favorite browser). Start reading…
- Or tap the `Share` button at the top of the screen.
- And tap `Add to Home Screen`… if you like that sort of a thing.


### HACK IT IN YOUR OWN STYLE

```
$ git clone [ *this repository* ]
$ npm install
$ bookiza server

```

This will open the book at `localhost:4567`.

### The Project
This app was created using [bookiza](https://bookiza.io) -- a "book reification" framework.

The TREE of the manuscript looks somewhat like this:

```

PROJECT/
├── README.md
├── assets
│   ├── css
│   ├── images
│   └── scripts
├── cover
│   ├── back.jpg
│   ├── cover.psd
│   ├── front.jpg
│   ├── spine.jpg
│   └── spine.psd
├── license.txt
├── manuscript
│   ├── page-1
│   │   ├── body.html
│   │   └── style.css
│   ├── page-2
│   │   ├── body.html
│   │   └── style.css
│   ├── page-3
│   │   ├── body.html
│   │   └── style.css
│   ├── page-4
│   │   ├── body.html
│   │   └── style.css
│   ├── page-5
│   │   ├── body.html
│   │   └
│   ├──
│   │  
│   │  
│   ├──
│   │  
│   │  
│   ├── page-2N-1
│   │   ├── body.html
│   │   └── style.css
│   └── page-2N
│       ├── body.html
│       └── style.css
├── templates
│   ├── head.html
│   ├── template.css
│   ├── template.html
│   └── template.js
└── trash

66 directories, 127 files

```
## CREDIT:
The content is licensed under the <a href="http://opensource.org/licenses/mit-license.php">MIT license </a> and was sourced from [Gutenberg.org](http://gutenberg.org)

## CONTRIBUTION/FIXES

Feel free to submit fixes or report issues or simply help improve the code of this book!

1. Fork it using `git`.
2. Create your feature branch (`git checkout -b my-new-page`)
3. Commit your changes (`git commit -am 'Added a page on (/topic)'`)
4. Push to the branch (`git push origin my-new-page`)
5. Create a new Pull Request
6. <a href = "mailto:marvin@bubbl.in">Contact me</a> if I don't respond within 24 hours.

## Licenses
![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)
