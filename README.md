# LaTeX Tutorial CSSA Cambridge

![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)

This repo hosts the project files for a Latex Workshop presented by Daoming Dong (dd511, Darwin College) and Youchao Wang (yw479, Clare Hall) for CSSA Cambridge, UK, April 20th, 2019.

## A very important note

A special thanks to Dr Rich Wareham (github: rjw57) who responded to our "add a license request" in no time.

## Repository layout

`LaTeXTutorial.pdf`: The beamer slides used for the tutorial.

You may find all the source codes for the LaTeX presentation slides in the `BeamerSlides` folder. The main `.tex` file is `LaTeXTutorial.tex`. The easiest way to build the project is to use the following code (in your `bash`/`powershell` environment).

```
pdflatex LaTeXTutorial.tex
```

![Demo](BeamerSlides/Figures/Demo.gif)

## Useful references

Here is a [University of Cambridge style beamer template](https://github.com/rjw57/cambridge-beamer). The beamer presentation for this tutorial made use of this template.

Here is a [CUED (Engineering Department) PhD thesis template](https://github.com/kks32/phd-thesis-template). A modified thesis template is available in the submodule.

Here is a [one-hour LaTeX YouTube video](https://www.youtube.com/watch?v=VhmkLrOjLsw).

Here are the [Cambridge Computer Lab LaTeX tutorial slides by Dr Markus Kuhn](https://www.cl.cam.ac.uk/teaching/2122/TeX+MATLAB/latex-slides.pdf). Some of the contents in the presentation were referenced from this source.

## Cloning the repository

Since this repo contains `phd-thesis-template` as a submodule, the ideal way of cloning this repository is:

```
git clone --recursive https://github.com/Siegfriedchao/LatexTutorialCSSACambridge.git
```

To update recursively, i.e. to pull the updates from the submodules

```
git pull --recurse-submodules
git submodule update --remote --recursive
```

Whenever you find yourself pulling an empty submodle folder, do not panic, all you need to do is:

```
git submodule update --init
```

## Contributing

Contributions are welcome. Simply create a PR should anything need to be updated or improved.
