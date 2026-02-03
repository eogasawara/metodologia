# Ferramentas locais e ambientes colaborativos

* Post author: Eduardo Ogasawara  
* Post category: Notas  
* Post published: —  

---

## Ferramentas locais e ambientes colaborativos

- [TexStudio](https://texstudio.sourceforge.net/manual/current/usermanual_en.html)  
  - [MacTeX](https://www.tug.org/mactex/)  
- [Language Tool Installation](https://pt.sharelatex.com/)  
- [ShareLaTeX](https://pt.sharelatex.com/)

---

## Símbolos, Equações, Tabelas e Algoritmos

- [Symbols](https://www.artofproblemsolving.com/wiki/index.php/LaTeX:Symbols)  
- [Equation Generator](https://www.codecogs.com/latex/eqneditor.php?lang=pt-br)  
- [Tables Examples](./latex-dicas-tabelas.zip)
- [Examples of algorithms](https://en.wikibooks.org/wiki/LaTeX/Algorithms)  
  - [(Pseudocode - Portuguese)](https://barbaraquintela.com/2013/06/18/algoritmos-no-latex-em-portugues/)

---

## LaTeX → Word

```bash
pandoc -s $file.tex --bibliography=$references.bib -o $file.docx
```

**Referências numeradas:**

```bash
pandoc -s $file.tex --bibliography=$references.bib -o $file.docx --csl=ieee.csl
```

---

## Word → LaTeX

```bash
pandoc -s $docx -o $latex --extract-media=.
```

---

## Comparação de versões em LaTeX

Ferramenta: [LaTeXDiff](https://3142.nl/latex-diff/)

---

