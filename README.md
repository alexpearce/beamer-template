Beamer template
===============

A small template for [Beamer](https://bitbucket.org/rivanvx/beamer/wiki/Home) presentations.
I clone this repo when I want to make a new presentation, then edit according to my needs.

Usage
-----

If you'd like to use this, there are just a couple of changes you'll probably want to make:

1. Change the institution logo,
2. Remove the `alxprc` package include.

The logo is defined in the `\logo` macro with an `\includegraphics` command.
To use your own, place the file in the `figures/` directory and update the `\logo` macro accordingly.

The `alxprc` package is a (currently) private package I use to define symbols I use a lot.
Just remove the `\usepackage{alxprc}` line.

License
-------

All files licensed under the [MIT license](http://opensource.org/licenses/MIT) unless stated otherwise.

