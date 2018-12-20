# sass-demo

## What is Sass?
  - a CSS Extension
  - pre-processed (browsers do not understand sass)
  - extensible
  - written in Ruby

  (it is a Ruby gem, that is just what Ruby packages are called)

## What is the big deal you may ask?
  - variables
  - nesting (sort of like media queries, there is some nesting going on) recommend not nesting too much.. not more than 3 or so
  - partials (like include command so you don't have to have 1 large file)
  - extend (a CSS rule could be based on another rule)
  - operators (you could multiply the width * 5)
  - mixins (macros - like adding JavaScript into your CSS)

## 2 different ways to write Sass:
  - .sass (indentation is relevant, no semi colons, older way, super consise)
  - .scss (similar to CSS)


## Installation instructions for Mac:

  - Ruby is already installed
  - `gem install sass`


## Workflow
  - command line (`sass input.scss output.css`)
  - Gulp.js (workflow tool to minimize your JavaScript, process your Sass, combine different files, etc.)
  - Webpack
  - Koala

``` sass --watch input.scss:output.css```



