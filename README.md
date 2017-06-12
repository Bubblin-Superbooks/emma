# INTRODUCTION

A nifty [superbook](https://bubbl.in/faq) for book-lovers on the web.

Brought to you by [Bubblin Superbooks](https://bubbl.in/about) - an online café of books.

First of its kind, this manuscript uses only HTML, CSS and JavaScript to render a timeless English classic on your brwoser. Feel free to read or share this with anyone for FREE!

No fancy app to download, no random files to worry about. No stupid email required to start reading it and not even a software upgrade ever on your machine after this one fine morning.

Just a simple book. Straight on the web.

## Support
Almost everywhere - iPads, iPhones, Android phones & tablets, Kindle Fire, Desktops, TVs. See [details](https://bubbl.in/support) for more information on this.

…but guess what: books are best experienced on tablets lying down!

## THE MANUSCRIPT
The book is live on the url provided at the top.

Slight framerate (FPS) quirks might occur due to the dearth of web standards for books (We hope that this will change soon!).

## RECOMMENDED DEVICE:

Apple iPad, Google Chrome. Or you can also use Safari like so:

- Open the [book](https://bubbl.in/cover/emma-by-jane-austen) on Safari (or any of your favorite browser). Start reading…
- Or tap the `Share` button at the top of the screen.
- And tap `Add to Home Screen`… if you like that sort of a thing.


### HACK IT IN YOUR OWN STYLE

Feel free to clone and hack this project and implement its pages, layouts or visuals in your own style. Share your fork with us and we'll help you spread the word!

The how:

```
$ git clone [ *this manuscript* ]
$ npm install
$ bookiza server

```

Bookiza will automagically process the manuscript and open the book at `localhost:4567`.

Read about [node](https://nodejs.org/en/), [bookiza](http://bookiza.io) and [bubblin](https://bubbl.in) to get started.


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


```
## CREDITS:
The manuscript was sourced from [Gutenberg.org](http://gutenberg.org)

Please read license terms of other softwares/libraries and their respective writers (owners) who have directly or indirectly contributed to this project.

## CONTRIBUTION/FIXES

Feel free to submit fixes or report issues or simply help improve the code of this book!

1. Fork it using `git`.
2. Create your feature branch (`git checkout -b my-new-page`)
3. Commit your changes (`git commit -am 'Added a page on (/topic)'`)
4. Push to the branch (`git push origin my-new-page`)
5. Create a new Pull Request
6. <a href = "mailto:marvin@bubbl.in">Contact me</a> if I/someone on my team doesn't respond within 24 hours. I get a lot of mail, so do not follow-up with a second mail before 24 hours.

## Licenses
Various:

[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://www.mozilla.org/en-US/MPL/2.0/)

Part of the sourcecode of this project is licensed under <a href="http://opensource.org/licenses/mit-license.php">MIT</a> while there are other components and node modules sourced under their own respective licenses.