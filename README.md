LaTeX project structure
=======================

Generic spooky skelly for simple to semi-complex LaTeX projects.

To make TeX output to a different directory to your current working directory,
pass the option `-output-directory <dir>` to the engine. Or use my `tex-render`
script from [raehik/scripts](https://github.com/raehik/scripts/).


Features
--------

  * Nicely modular lib system
  * Tons and tons of comments
  * Good support for CJK, including basic support for XeLaTeX
  * i dun used it some


Structure
---------

  * `main.tex`: main file defining preamble, title, TOC etc., then
                includes other source files from `src/`
  * `src/`: TeX files i.e. chapters/sections
  * `lib/`: TeX macros & other stuff
  * `img/`: images & diagrams
  * `build/`: (temporary) build files created/used by LaTeX
  * `bin/`: resulting PDF(s)


Usage
-----

Copy/clone the repo and get to work. You'll want to delete the example source
files, and probably the library files you definitely won't use too.
