# Tampere University Proof Theory Lecture Notes

Lecture notes for the Tampere University course "Proof Theory",
originally written by Esko Turunen based on Gaisi Takeuti's book "Proof Theory".

## Compilation instructions

It is adviced to use the compiler `lualatex` to compile the `main.tex` file:
```sh
lualatex main.tex && biber main && lualatex main.tex
```
The file `main.tex` contains the document in its entirety.
The compiler `pdflatex` will most likely not work,
because of the included LaTeX package `fontspec`,
that relies on `lualatex` to function.

## License

See the file `LINCENSE.md`, located in the same directory as this file.
If this `LICENSE.md` file is missing, all rights are reserved.

## Contributing

Contributions to the handout are welcome,
either via pull requests or issue submissions on Github,
or similar facilities provided by other version control systems,
that this Work might be hosted on.
The authors of course reserve the right to withhold the inclusion
of said contributions, if deemed inapproppriate in any way.

Fixing typos is always a welcome contribution.
However, it should be kept in mind that this is a handout
for a very specific course at a very specific university
with very specific needs, and the contents should therefore
be kept as is, as much as possible.
