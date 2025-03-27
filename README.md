# Heterogeneous_Programming

Pour créer l'environement sur le finisterrae et s'y connecter:
- cd $STORE
- python3.7 -m venv my_env37
- source $STORE/my_env37/bin/activate
- pip install ipykernel
- python -m ipykernel install --user --name=my_env37 --display-name "Python 3.7 (my_env37)"
- jupyter lab --ip `hostname -i`
- Sélectionner le kernel "Python 3.7 (my_env37) (au lieu de myenv)