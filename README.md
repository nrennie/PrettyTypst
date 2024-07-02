# PrettyTypst

Quarto extension for a template to generate a PDF with (pretty) styling using either Typst. Use `PrettyTypst-typst` for the format. Note that version 1.4 or greater of Quarto is required.

> Note: see [github.com/nrennie/PrettyPDF](https://github.com/nrennie/PrettyPDF) for the LaTeX version of this template.

## Installation and use

To install the Quarto extension, create a directory, and use the template file:

``` bash
quarto use template nrennie/PrettyTypst
```

To use the extension in an existing project without installing the template file:

``` bash
quarto install extension nrennie/PrettyTypst
```
Note that you will need to update the output format to `format: PrettyTypst-typst` to enable use of the extension. For book projects, add:

```
project:
  type: PrettyTypst
```
to the `_quarto.yml` file.

### Logo

Either replace the `logo.png` file with a new file of your choosing, or change the file path in the YAML to point to a different logo file. Note that the file path is relative to your .qmd file.

## Blog

Read more about this extension, how it was built, and how to make your own in my blog post at [nrennie.rbind.io/blog/pdf-quarto/making-pdf-with-quarto-typst-latex](https://nrennie.rbind.io/blog/pdf-quarto/making-pdf-with-quarto-typst-latex/).





