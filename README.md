Jupyterlab
==========

Quelques *Jupyter Notebook* utilisés lors du cours de *Scripts serveurs* dans le cadre du *Brevet de Webdeveloper* à l'EICVN.

Installer un environnement virtuel Jupyterlab
---------------------------------------------

### Prérequis

Version de Python supérieure ou égale à 3.8.

	python --version

### Windows

	mkdir jupyterlab
	cd jupyterlab
	python -m venv .
	.\Scripts\pip install jupyterlab
	mkdir notebooks
	cd notebooks
	..\Scripts\jupyter-lab

### Linux/MacOSX

	mkdir jupyterlab
	cd jupyterlab
	python -m venv .
	./bin/pip install jupyterlab
	mkdir notebooks
	cd notebooks
	../bin/jupyter-lab

### Installer les dépendances

    ../bin/pip install -r requirements.txt

Raccourcis Jupyter Notebook
---------------------------

- http://maxmelnick.com/2016/04/19/python-beginner-tips-and-tricks.html

Tips
----

- Ajouter le caractère ";" à la fin d'une cellule pour ne pas afficher la valeur de la dernière expression de la cellule.
