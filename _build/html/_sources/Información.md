# Alejandro Cabrera

Nacido y vive en Cuenca. Actualmente estudia en la Universidad Técnica Particular de Loja.

## Objetivo de la página

Esta página fue desarrollada como APE del primer bimestre de la materia de Desarrollo basado en plataformas web.

## Herramientas utilizadas

### JupyterBooks
Se utilizó la librería **JupyterBooks** para crear la página web estática.

Comandos utilizados:

````
pip3 install jupyter-books

jupyter-book create libro01

jupyter-book build libro01
````

### Git
Para el control de versiones se usó **Git**.

Comando utlizados:

````
git config --global user.email "aicabrera@utpl.edu.ec"
git config --global user.name "alejandro-cabrera"
git clone https://github.com/alejandro-cabrera/miprimeraweb.git .
git add . 
git commit -a -m "subiendo primera version de libro" 
git push
````

### GitHub
El repositorio de la página está alojada en **GitHub**.
Se utlizó **Actions** para incluir un script para renderizar automáticamente la página.
Se usó **GitHubPages** para desplegar la página. 
