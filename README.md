# Gleb's Article Format (GAT)

**Warning**: This quarto extension is still under active development.
Using it might lead to unexpected results.
You can bookmark, star or watch this repository for future updates.

This is a Quarto template that assists you in creating a nicely formatted
document and is based on
[Quarto's Article Format Template (AFT)](https://github.com/quarto-journals/article-format-template)
I created it during my PhD at ETH Zurich and use it for any written documents
that don't require a particular format.

## Creating a New Article

You can use this as a template to create an article using the following command:

```bash
quarto use template gl-eb/glebs-article-template
```

This will install the extension and create an example qmd file and bibiography
that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document.
From the quarto project or document directory, run the following command to
install this format:

```bash
quarto install extension gl-eb/glebs-article-format
```

## Usage

Set the format name to `gat-pdf` to use the template.
For example:

```bash
quarto render article.qmd --to gat-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  gat-pdf:
    keep-tex: true
```
