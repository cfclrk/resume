My résumé.

<img
    width="100"
    height="100"
    src="https://user-images.githubusercontent.com/452309/174818847-dbf1133a-1dc7-4f09-98ab-f66fb10559b3.png" />

Dependencies
------------

Install with `tlmgr install <package-name>` if you don't have them:

- [fontawesome](https://ctan.org/pkg/fontawesome)
- [tcolorbox](https://ctan.org/pkg/tcolorbox)
- [titlesec](https://ctan.org/pkg/titlesec)
- [environ](https://ctan.org/pkg/environ)

Also, ensure that you have installed [cm-super](https://ctan.org/pkg/cm-super)
(`tlmgr install cm-super`) which provides _significantly_ improved fonts for the
T1 font encoding.

Create PDF
----------

``` shell
xelatex resume.tex
```

`pdflatex` works as well.

Feedback
--------

Please feel free to open an issue, even if it's just a comment or suggestion. I
always love discussing how to design things better.
