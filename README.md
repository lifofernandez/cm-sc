# CM SC

## PDF

```
bibtex cs-sc
lualatex cm-sc.txt
```

## Conver to Docx

https://medium.com/@zhelinchen91/how-to-convert-from-latex-to-ms-word-with-pandoc-f2045a762293 

```
pandoc cm-sc.tex  --reference-doc="CACIC (MCSI 2022) - CM-SC.docx" -o cm-sc.docx  
```

```
pandoc cm-sc.tex  --filter pandoc-crossref --bibliography=cm-sc.bib --reference-doc="CACIC (MCSI 2022) - CM-SC.docx" -o cm-sc.docx 
```