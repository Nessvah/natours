# Natours

A fully responsive and beautiful webpage for a tours company created with only HTML and CSS (SCSS).

## Demo

[Live demo](https://silviavanessa-natours.netlify.app/)

## Table of contents

- [Natours](#natours)
  - [Demo](#demo)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Features](#features)
  - [FAQ](#faq)
    - [How to install Sass via Command Line using NPM](#how-to-install-sass-via-command-line-using-npm)
    - [How to compile one particular file](#how-to-compile-one-particular-file)
    - [How to watch for changes in individual files](#how-to-watch-for-changes-in-individual-files)
    - [How to watch for changes in multiple files without re-compiling](#how-to-watch-for-changes-in-multiple-files-without-re-compiling)
  - [Future optimizations](#future-optimizations)
  - [Acknowledgements](#acknowledgements)
  - [Authors](#authors)
  - [License](#license)

## Overview

This webpage was developed in the old way of building layouts of all sizes, using the float CSS property.
Still in use, but getting outdated.

- **Why use a float layout on this project?**

The focus of this project is on using modern CSS properties and techniques: clips, transforms, animations, background videos, etc.

Even though flexbox and CSS grid are more modern and easier to use, every web developer should still know how the float layouts work. As professional developers, our job will include working with older CSS codebases, which will contain float layouts.

This project was also designed using the desktop-first approach which I think it's easier when we have a lot more going on on bigger screens and we need to consider that. After that, it's just a matter of shrinking and making everything responsive and nicely fitted.

<hr>

## Screenshots

- Web version

![App Screenshot Web](/img/screenshot.png)

- Mobile version

![Mobile Screenshot](/img/mobile-screenshot.png)

<hr>

## Features

- Toggle menu
- Pop Up
- Fully Responsive
- Animations
- Custom Form

<hr>

## FAQ

### How to install Sass via Command Line using NPM

- If you use Node.js, you can install Sass using npm by running

`npm install -g sass`

- If you use the Chocolatey package manager for Windows, you can install Dart Sass by runnin

`choco install sass`

- Install on Mac OS X or Linux (Homebrew)

  If you use the Homebrew package manager for Mac OS X or Linux, you can install Dart Sass by running

`brew install sass/sass/sass`

For more information about the instalation process or others way to install and/or use it, please check their [website](https://sass-lang.com/install).

### How to compile one particular file

You'll need to tell Sass which file to build from, and where to output CSS to.
For example, running:

`sass input.scss output.css`

Tells sass to take a single Sass file, `input.scs`, and compile that file to `output.css`.

### How to watch for changes in individual files

You can also watch individual files or directories with the **--watch** flag.
The watch flag tells Sass to watch your source files for changes, and re-compile
CSS each time you save your Sass.

You'd just add the watch flag to your command, like so:

`sass --watch input.scss output.css`

### How to watch for changes in multiple files without re-compiling

You can watch and output to directories by using folder paths as your input and
output, and separating them with a colon. In this example:

`sass --watch app/sass:public/stylesheets`

Sass would watch all files in the **app/sass** folder for changes, and compile CSS
to the **public/stylesheets** folder.

<hr>

## Future optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility

<hr>

## Acknowledgements

Credits for the design of this project:

- [Jonas](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)

<hr>

## Authors

Project developed by:

- [@nessvah](https://www.github.com/octokatherine) (Sílvia Vanessa)
<hr>

## License

[MIT](https://choosealicense.com/licenses/mit/)
