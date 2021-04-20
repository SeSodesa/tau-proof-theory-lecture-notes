# Tampere University Proof Theory Lecture Notes

Lecture notes for the Tampere University course "Proof Theory", originally written by Esko Turunen based on Gaisi Takeuti's book "Proof Theory".

## Compilation instructions

It is adviced to use the compiler `lualatex` to compile the `main.tex` file:

    lualatex main.tex && biber main && lualatex main.tex

The file contains the document in its entirety.
The compiler `pdflatex` will most likely not work,
because of the included LaTeX package `fontspec`,
that relies on `lualatex` to function.
