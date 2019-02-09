My résumé.

All source is in one file: `chris_clark.tex`, which uses the `article`
documentclass. People have attempted making "resume" documentclasses, but I
found those to be rather constricting and overly complex. It's pretty
straightforward to just use the `article` documentclass.

Dependencies
------------

Packages which are not included in the `basictex` distribution (i.e. `brew cask
install basictex` on MacOS). Install a package with `tlmgr install
<package-name>`.

  - titlesec

Create PDF
----------

    pdflatex chris_clark.tex

Feedback
--------

Please feel free to open an issue, even if it's just a comment or suggestion. I
always love discussing how to design things better.
