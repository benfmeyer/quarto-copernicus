# Copernicus Article Template

Port of `rticles::copernicus_article()` to Quarto. This extension will create documents for Copernicus journals. 

# Creating new articles

You can use this as a template to create articles for Copernicus journals. To use an empty template run:

`quarto use template benfmeyer/quarto-copernicus`

from the terminal.

# Installation in existing document

To use this template with an existing Quarto document run:

`quarto add benfmeyer/quarto-copernicus`

from the terminal.

# Usage

To use the Copernicus format in your document add `format: copernicus-pdf` to your YAML. Currently, this only compiles using `pdflatex`. The default used by Quarto is `xelatex`, so, be sure to set `pdf-engine: pdflatex` in the YAML.

# Further information

For more information on quarto templates and how to install, use, or create your own see the official documentation at: https://quarto.org/docs/extensions/starter-templates.html#extensions-templates



