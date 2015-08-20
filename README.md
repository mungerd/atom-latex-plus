# LaTeX-Plus
[![Build Status](https://travis-ci.org/andrewrynhard/atom-latex-plus.svg?branch=master)](https://travis-ci.org/andrewrynhard/atom-latex-plus)
[![Plugin installs!](https://img.shields.io/apm/dm/latex-plus.svg?style=flat-square)](https://atom.io/packages/latex-plus)
[![Package version!](https://img.shields.io/apm/v/latex-plus.svg?style=flat-square)](https://atom.io/packages/latex-plus)

Productivity tools for pdfLaTeX, LuaLaTeX, and XeLaTeX flavors of LaTeX.

## Installing
Atom package manager or `apm install latex-plus`.

## Usage
  * Define a project configuration file, `tex.json`, in the root of you latex project.
  * Compile the project with `ˆ⇧C`.

## Project Configuration Example
```` json
{
  "project": "Example LaTeX Project",
  "root": "main.tex",
  "program": "xelatex",
  "output": ".latex"
}
````

## Demo
![demo](https://cloud.githubusercontent.com/assets/3383143/9396324/eaa8358e-4748-11e5-8385-1a55967daeb4.gif)
