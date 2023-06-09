# Posit Quarto Theme

## Installing

If you have not created the Quarto document yet, and would like to use the Posit-themed template, run the following:

``` bash
quarto use template ryjohnson09/posit_theme
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

If you have a preexisting Quarto document and would like to apply the Posit theme to it, run the following:

``` bash
quarto add ryjohnson09/posit_theme
```

Make sure to add the following to your YAML:

---
format:
  posit-html: default
---
