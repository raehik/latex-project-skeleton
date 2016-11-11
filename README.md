LaTeX project structure
=======================

Generic spooky skelly for simple to semi-complex LaTeX projects. Includes some
support for XeLaTeX. Relies on my `tex-render` script for now, though it
shouldn't really (can't move the output file w/o script though :[)

  * `main.tex`: main file defining preamble, title, TOC etc., then
                includes other source files from `src/`
  * `src/`: TeX files i.e. chapters/sections
  * `lib/`: TeX macros & other stuff
  * `img/`: images & diagrams
  * `build/`: (temporary) build files created/used by LaTeX
  * `bin/`: resulting PDF(s)
