Proyecto de CM-274
===

## Instalación de la clase `kommaexa`

```bash
deepin@me:$ git clone git@github.com:carlosal1015/Lab1-CM-274.git
deepin@me:$ cd Lab1-CM-274
deepin@me:$ cp kommaexam.cls /opt/texlive/texmf-local/tex/latex/local 
deepin@me:$ texhash
```

## Compilación
```bash
deepin@me:$ cd First_Project
deepin@me:$ arara main.tex
deepin@me:$ xdg-open main.pdf
```

% TODO: Crear el makefile para todo el proyecto.