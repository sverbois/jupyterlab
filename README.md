Jupyterlab
==========

Quelques *Jupyter Notebook* utilisés lors du cours de *Scripts serveurs* dans le cadre du *Brevet de Webdeveloper* à l'EICVN.
    
Télécharger et exécuter les notebooks de ce dépôt git
-----------------------------------------------------
### Prérequis

- Version de Python supérieure ou égale à 3.9.
- Gestionnaire de version *git*

#### Imprimer la version de Python

	python --version

### Windows

    git clone https://github.com/sverbois/jupyterlab.git
	cd jupyterlab
	python -m venv venv
    .\venv\Scripts\pip install -r requirements.txt
	.\venv\Scripts\jupyter-lab notebooks

### Linux/MacOSX

	git clone https://github.com/sverbois/jupyterlab.git
	cd jupyterlab
	python -m venv venv
    ./venv/bin/pip install -r requirements.txt
	./venv/bin/jupyter-lab notebooks


Raccourcis Jupyter Notebook
---------------------------

- http://maxmelnick.com/2016/04/19/python-beginner-tips-and-tricks.html

Tips
----

- Ajouter le caractère ";" à la fin d'une cellule pour ne pas afficher la valeur de la dernière expression de la cellule.
