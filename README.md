LaTeX project skeleton
======================

A flexible spooky skelly for your LaTeX projects, intended for any size of
project.

I am the type of person who likes to start with some structure I know I can
trust. I've written this skeleton by stripping down old LaTeX projects of mine.


Features
--------

  * Modular: unwanted configuration can be disabled
  * Very simple: library = directory of TeX files that are `\input`
  * Every choice is commented, I don't blindly make typography choices
  * Engine-specific configs for pdfTeX, XeTeX, LuaTeX
  * (working on) CJK support


Installation
------------

I use TeXLive from the Arch Linux repos.

  * `texlive-langjapanese` is required for most Japanese-specific typesetting
    (e.g. `luatexja`).


Usage
-----

  1. Clone this repo.
  2. Choose what template you want. As of 2018-07-19, there is a beamer template
     and a LaTeX article template.
  3. Set up `main.tex`.
  4. For TeX to use `bin` and `build`, use my `tex-render` script
     (raehik/scripts).


Structure
---------

  * `main.tex`: main file that defines macros, includes preamble, and does title
    & TOC (by default), from which you include other source files
  * `cfg/`: config modules
  * `src/`: project TeX source
  * `img/`: images & diagrams
  * `build/`: build files created/used by LaTeX
  * `bin/`: output (PDFs)

There are extra files and folders in this skeleton due to it holding templates
for different types of project (that all share some configuration).


License
-------

This project and all source files are available under the MIT license. Please
see `LICENSE` for the full text.
