# latex-mimosis: A minimal & modern template for your thesis

This repository contains a minimal & modern LaTeX template for
dissertations and other university documents.

For the impatient or curious: [this is what the template looks
like](Thesis.pdf).
You may also want to take a look at my [my Ph.D. dissertation](http://bastian.rieck.me/research/Dissertation_Rieck_2017.pdf), which uses a predecessor of this template.

# Advantages

This template aims to be&hellip;
- clean: no LaTeX trickery
- minimal: no unnecessary adjustments and decorations
- modern: typographically pleasing

It is specifically suited for the European education system because it
uses A4 paper size by default&mdash;this can be easily adjusted to fit
your personal needs, though&nbsp;(see below).

The class is based on [`KOMA-script`](komascript.de), so it should be
flexible enough to suit virtually any purpose.

# How to use

- Clone this repository
- Copy the file `mimosis.cls` into your document directory
- Add `\documentclass{mimosis}` to your document preamble
- Optionally copy the file `Thesis.tex` and the files in `Sources` as
  a starting point
- Use `latexmk` to build the document using `pdflatex`
- Write a nice thesis in LaTeX

# How to customize

The template is based on the excellent [`KOMA-script`](https://ctan.org/pkg/koma-script)
class. You can thus change the appearance of many things quite easily.
For example, if you want the thesis to use the `letter` paper format,
just add

    \KOMAoptions{paper=letter}

in the preamble of the document and recompile.

# Example

The repository comes with an example file called `Thesis.tex`. Please
take a look at this file in order for more detailed instructions about
how to use the class.

It is recommended to use `latexmk` to build your LaTeX documents. Your
distribution might already have this command. If so, you can use

    latexmk

in the main directory of this repository in order to build the example
file.

# Contributing

If you require additional features, find some bugs, or just have some
generic inquiries, please just open an issue in this repository.

# Contributors

Here is a list of contributors:

- [Miloslav Číž (drummyfish)](https://github.com/drummyfish): grammar/style corrections for `README` file
- [Bastian Rieck (Submanifold)](https://github.com/Submanifold): original creator and maintainer
