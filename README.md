<h1 align="center">LaTeX Boilerplate</h1>
<p align="center">A simple yet comprehensive LaTeX presentation boilerplate (example) for giving killer presentations (<a href="https://github.com/tijme/latex-boilerplate-presentation/blob/master/.github/preview.pdf">PDF preview</a>).<br><i>Do you want to write an academic paper? Take a look at <a href="https://github.com/tijme/latex-boilerplate-paper">this</a> LaTex boilerplate.</i></p>

![https://github.com/tijme/latex-boilerplate-presentation/blob/master/.github/preview.pdf](https://github.com/tijme/latex-boilerplate-presentation/raw/master/.github/preview.png)

## Build Commands

**Compile to PDF**

`$ make pdf`

This runs [*pdflatex*, *pdflatex*, *pdflatex*], a command that is available by default in most graphical LaTex editors.

**Clean temporary files**

`$ make clean`

## The Document Structure

* assets/ *(add all your assets here)*
    * **image1.jpg**
    * **image2.jpg**
    * ***[another asset]*.png**
* section/ *(add all your section here)*
    * **introduction.tex**
    * **examples.tex**
    * **conclusion.tex**
    * ***[another section]*.tex**
* config/
    * **globals.tex** *(variables/settings)*
    * **style.sty** *(the document style/design)*
* **main.tex** *(defines the document structure)*

## Issues

Issues or new features can be reported via the GitHub issue tracker. Please make sure your issue or feature has not yet been reported by anyone else before submitting a new one.

## License

LaTex Boilerplate is open-sourced software licensed under the [MIT license](https://github.com/tijme/latex-boilerplate-presentation/blob/master/LICENSE.md).
