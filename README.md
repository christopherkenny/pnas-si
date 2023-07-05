
# PNAS Supporting Information Quarto Template

This is a companion to the [PNAS Quarto Template](https://github.com/christopherkenny/pnas).

## Creating a New Article

To create a new article using this format:

```bash
quarto use template christopherkenny/pnas-si
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add christopherkenny/pnas-si
```

Then, add the format to your document options:

```yaml
format:
  pnas-si-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

<!-- pdftools::pdf_convert('template.pdf',pages = 1) 
![[template.qmd](template.qmd)](template_1.png) -->

## License

This modifies the Overleaf PNAS Template for Supplementary Information, available at <https://www.overleaf.com/latex/templates/pnas-template-for-supplementary-information/wqfsfqwyjtsd>. The original template is licensed under the [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/lppl-1-3c/). The template within is derived from this and makes modifications to separate into the full document into Quarto "partials". All modifications can be seen in this repo. 

