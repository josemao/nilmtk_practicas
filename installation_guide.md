
---- Preparación del SO. ---------------
- Ubuntu 14.04 LTS (20Gb - 4Gb RAM) 
- Instalar Guest Additions
- Usr: nilm pwd: nilm
- install git: sudo apt-get install git
- sudo apt-get install libpq-dev python-dev (para psycopg2)
- sudo apt-get install graphviz
---------------------------------------

1. Install Anaconda
https://www.continuum.io/downloads

2. conda install anaconda-navigator
	(anaconda-navigator para llamarlo)

3. Install nilmtk as in: 
https://github.com/nilmtk/nilmtk/blob/master/docs/manual/user_guide/
4. conda install jupyter
5. pip install networkx==1.10; pip install pydot
6. pip install ipdb


* Importante: Cada vez que se abra el terminal activar la virtualenvr
	source activate nilmtk-env
* para arrancar el notebook: jupyter notebook