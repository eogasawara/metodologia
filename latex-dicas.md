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
- [Tables Examples](https://eic.cefet-rj.br/~eogasawara/wp-content/uploads/2015/02/tabelas.zip)  
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

## Modelos

- [Graduation Template](https://eic.cefet-rj.br/~eogasawara/wp-content/uploads/2015/02/grad-tcc-template-latex.zip)  
- [PhD and Master Degree Template](https://pt.overleaf.com/latex/templates/cefet-rj-nortese-2019/ghbyqcbzyhxn)  
- [SBC Template](https://eic.cefet-rj.br/~eogasawara/wp-content/uploads/2017/05/sbc-template-latex.zip)

---

© Copyright – WordPress Theme by OceanWP
