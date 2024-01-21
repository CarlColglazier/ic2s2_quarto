# Article Format Template (AFT)

This is a Quarto template that assists you in creating an extended abstract for [IC2S2](https://ic2s2-2024.org/). More details about the submission format can be found on the [conference website](https://ic2s2-2024.org/submit_abstract).

## Creating a New Article

You can use this as a template to create an extended abstract for IC2S2. To do this, use the following command:

```bash
quarto use template carlcolglazier/ic2s2_quarto
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add carlcolglazier/ic2s2_quarto
```

## Usage

To use the format, you can use the format name `ic2s2-pdf`. For example:

```bash
quarto render article.qmd --to aft-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  ic2s2-pdf:
    keep-tex: true    
```
