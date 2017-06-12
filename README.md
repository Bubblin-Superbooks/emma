# INTRODUCTION

A nifty [superbook](https://bubbl.in/about) for book lovers on the web. Brought to you by web people.

First of its kind, this manuscript uses only CSS, HTML and JavaScript to open up a timeless English classic. Help yourself with this book and read it as a *first class citizen* of the web. No fancy corporate style card sliding interface (it's a book not a powerpoint presentation), no stupid half-scroll half-click bait website, no pesky files to download and not even useless software upgrades one fine morning.

Just a simple book. And, straight on the web.

`Supported devices`: Everywhere - iPads, iPhones, Android Phones & tablets, Kindle, Desktops, TVs. See [details](https://bubbl.in/support) but guess what: Books are vest experienced on tablets!

## THE BOOK
The book is live on the url at the top.

Slight framerate (FPS) quirks might occur due to dearth of web standards for books (We hope that will change soon!).

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
## LICENSE:
The content is licensed under the <a href="http://opensource.org/licenses/mit-license.php">MIT license </a> and was sourced from [Gutenberg.org]()

## CONTRIBUTION/FIXES

Feel free to contribute, fix or help improve the code of this book!

1. Fork it ( https://github.com/marvindanig/A-B-C-D-Animals-Book/fork )
2. Create your feature branch (`git checkout -b my-new-page`)
3. Commit your changes (`git commit -am 'Added a page on (/topic)'`)
4. Push to the branch (`git push origin my-new-page`)
5. Create a new Pull Request
6. <a href = "mailto:marvin@bubbl.in">Contact me</a> if I don't respond within 24 hours.

## Licenses
[![Creative Commons License](https://i.creativecommons.org/l/by/3.0/us/88x31.png)](http://creativecommons.org/licenses/by/3.0/us/)
All content of this superbook is licensed under a [Creative Commons Attribution 3.0 United States License](http://creativecommons.org/licenses/by/3.0/us/).

The underlying HTML & CSS3 code used to format and design the content is licensed under the <a href="http://opensource.org/licenses/mit-license.php">MIT license </a>.
template.