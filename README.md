# Basic scientific report — Overleaf template

## Get started

1. Upload all files from this folder (or the ZIP archive) into a new Overleaf project.
2. Open `main.tex` and edit the title, author, section headings, and text.
3. Replace `example-image` with your uploaded figure, e.g. `figures/my_figure.png`.
4. Connect your Zotero bibliography in Overleaf. If its filename differs from `references.bib`, update `\addbibresource{references.bib}` in `main.tex`.
5. Cite sources with `\parencite{key}` (parenthetical) or `\textcite{key}` (narrative). `\printbibliography` automatically produces the references section once you cite sources.

The template uses BibLaTeX with **Biber** and the `authoryear` citation style. `example-image` is provided by the `mwe` LaTeX package, so the template will show a placeholder figure even before you upload your own.

## Project files

- `main.tex`: Main LaTeX document.
- `references.bib`: Empty bibliography placeholder. Replace it or point the template to your existing Zotero-linked `.bib` file.
- `figures/`: Folder for figure files.
