# APA7-modelo
Un modelo en LaTeX que conforma con pautas de APA7 [link to document here]

# Como Usarlo
La mayoria de los archivos tienen ejemplos de como usarlos, junto a comentarios seguidos del charactér "%". La lista a continuacion ha sido compilada con los primeros pasos necesarios para poder usar este documento.

- [ ] Update the ```frontmatter.tex``` file. This is where all the basics are defined, your thesis title, your name, your committee members, etc.
- [ ] Start writing chapters! Every chapter goes inside of the ```chapters``` folder and should be imported in the ```chapter-outline.tex``` file using the ```\include{chapters/your-chapter}``` syntax. This makes reordering chapters a breeze! (Trust me, you'll do it)
- [ ] Drop all of your fancy graphs into the ```figures``` folder for safe keeping
- [ ] Got some appendices? You're covered, same idea as with chapters, but using ```appendix-outline.tex``` and the ```appendices``` folder instead.
- [ ] Write your abstract in ```abstract.tex```. That's it. The template takes care of all the formatting for you.
- [ ] Don't forget to thank your parents! Fill in ```acknowledgements.tex```.
- [ ] Be sure to cite your sources in ```bibliography.bib```. If you use Google Scholar to find your sources, it will provide you with ```bibtex``` output under the "cite" option.

# Overleaf
Want to take your thesis writing ***to the cloud?!?!*** Or, you know, don't want to install the ~3GB girthy monstrosity that is LaTeX on your pristine machine? Use [ShareLaTeX](https://www.sharelatex.com/).
Recomiendo el uso de [Overleaf](https://www.overleaf.com), el cual es un compilador con servidores en la nube el cual evita la necesidad de instalar LaTeX en un computador personal. A si mismo, permite la colaboracion entre varios colegas.

# Preguntas?
If you have a general question about LaTeX, I would recommend you do a Google search first and check out [the TeX Stack Exchange](http://tex.stackexchange.com/). If you have a question specifically about this template and its use, feel free to submit an issue using the "question" tag.
Si tienes preguntas generales acerca de LaTex, recomiendo hacer una busqueda en Google. Otros recursos utiles son [the TeX Stack Exchange](http://tex.stackexchange.com/), al igual que el servidor de Discord [LaTeX Support - Discord](https://disboard.org/server/570670498309210112)
