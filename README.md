Jupyterlab
==========

Quelques *Jupyter Notebook* utilisés lors du cours de *Scripts serveurs* dans le cadre du *Brevet de Webdeveloper* à l'EICVN.

Installer un environnement virtuel Jupyterlab
---------------------------------------------

### Prérequis

- Version de Python supérieure ou égale à 3.8.
- Gestionnaire de version *git*

### Imprimer la version de Python

	python --version

### Windows

	mkdir jupyterlab
	cd jupyterlab
	python -m venv .
	.\Scripts\pip install jupyterlab

### Linux/MacOSX

	mkdir jupyterlab
	cd jupyterlab
	python -m venv .
	./bin/pip install jupyterlab
    
Télécharger et exécuter les notebooks de ce dépôt git
-----------------------------------------------------

### Windows

    git clone https://github.com/sverbois/notebooks.git
	cd notebooks
    ..\Scripts\pip install -r requirements.txt
	..\Scripts\jupyter-lab

### Linux/MacOSX

	git clone https://github.com/sverbois/notebooks.git
	cd notebooks
    ../bin/pip install -r requirements.txt
	../bin/jupyter-lab


Raccourcis Jupyter Notebook
---------------------------

- http://maxmelnick.com/2016/04/19/python-beginner-tips-and-tricks.html

Tips
----

- Ajouter le caractère ";" à la fin d'une cellule pour ne pas afficher la valeur de la dernière expression de la cellule.
