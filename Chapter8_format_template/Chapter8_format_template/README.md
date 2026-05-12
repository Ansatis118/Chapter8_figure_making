# Chapter8 format reference template

This package contains a LaTeX reference template extracted from the uploaded `Chapter8.tex` formatting.

Included:

- `Chapter8_format_reference_template.tex` — reusable LaTeX template with the original formatting structure preserved and original body content removed.
- `figures/.gitkeep` — placeholder folder for figure files.

Format features preserved:

- `ctexart` two-column A4 layout
- 10pt base font size
- XeLaTeX compilation target
- Narrow academic-style margins and 7 mm column separation
- `newtxtext` / `newtxmath` font stack
- `microtype`, `booktabs`, `caption`, `subcaption`, `titlesec`, `enumitem`, `hyperref`, `footmisc`
- Section and subsection title formatting
- Caption formatting
- Itemize/enumerate spacing
- Reusable term, abbreviation, translator-note, single-column figure, double-column figure, and figure-placeholder macros

Suggested compile command:

```bash
xelatex Chapter8_format_reference_template.tex
```

Before compiling, replace the placeholder metadata commands near the top of the file:

```tex
\newcommand{\TemplateTitle}{<Document Title>}
\newcommand{\TemplateAuthor}{<Author Name>}
\newcommand{\TemplateSubject}{<Document Subject>}
\newcommand{\TemplateKeywords}{<keyword one, keyword two>}
```
