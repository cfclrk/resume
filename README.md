My résumé.

<img
    width="100"
    height="100"
    src="https://user-images.githubusercontent.com/452309/174818847-dbf1133a-1dc7-4f09-98ab-f66fb10559b3.png" />

# Dependencies

Install dependencies using `./deps.sh`. The following dependencies are required:

- [fontawesome](https://ctan.org/pkg/fontawesome)
- [tcolorbox](https://ctan.org/pkg/tcolorbox)
- [titlesec](https://ctan.org/pkg/titlesec)
- [environ](https://ctan.org/pkg/environ)

Also, the `deps.sh` script installs [cm-super](https://ctan.org/pkg/cm-super)
which provides _significantly_ improved fonts for the T1 font encoding.

# Create the PDF

``` sh
pdflatex resume.tex
```
