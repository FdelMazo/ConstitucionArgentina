# ConstitucionArgentina
Reimaginación digital de la Constitución de la Nación Argentina

Una sencilla reimaginación de como evolucionó la Constitución de la Nación Argentina a través de los años, usando git como herramienta. El historial de diferencias que dió cada reforma constitucional termina dando un panorama de como cambió el pais en su historia, pasando por las distintas dictaduras y etapas. Utiliza todo lo que provee git y github para ser lo más completa posible, sea el tiempo del commit, un Pull Request declinado, u otras cosas.

La mejor manera de verlo es con los diffs entre commit y commit, siguiendo [el historial entero](https://github.com/FdelMazo/ConstitucionArgentina/commits/master)

Este proyecto surgió de ver el genial laburo puesto sobre [france.code-civil](https://github.com/steeve/france.code-civil) (y proyectos similares) y de las ganas de aprender algunos comandos y conceptos de git un poco más avanzados de lo normal (en particular, `git rebase -i` y `git add -p` terminaron siendo de gran ayuda). Al final, termine aprendiendo mucho más de la historia de la Nación de lo que esperaba, y tener una cronología clara ayuda bastante.

El proyecto utiliza [pandoc](http://pandoc.org/) (que se instala con `sudo apt install pandoc`) para generar los PDF desde los archivos de Markdown, con el comando `pandoc --toc --toc-depth=4 Constitucion.md -H header.tex -o Constitucion.pdf`

La mayor fuente para lo histórico fue... Wikipedia. Entre la [Historia del constitucionalismo argentino](https://es.wikipedia.org/wiki/Historia_del_constitucionalismo_argentino) y la página dedicada a la [Constitución de la Nación Argentina](https://es.wikipedia.org/wiki/Constituci%C3%B3n_de_la_Naci%C3%B3n_Argentina), pude cubrir la mayoría de lo que está acá.

La mayor fuente para los textos, más alla de buscar algunas Proclamas por separado, fue Wikisource, una biblioteca libre con muchísimo contenido, en particular, una [página dedicada](https://es.wikisource.org/wiki/Categor%C3%ADa:Constituciones_nacionales_de_Argentina) a los textos de las distintas constituciones/reformas.

Intente ser lo más preciso posible, sea con autores de commits, fechas, firmas, o más, pero la realidad es que la historia argentina es mucho más extensa y compleja que lo que una página de wikipedia o unos ~15 commits puedan mostrar, así que cuando hizo falta tuve que optar por ser conciso frente a ser 100% fiel.
