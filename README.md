# Rendu pour le 4 Avril.

# Sujet : ResNet - Classification d’images

# Heterogeneous_Programming

Pour créer l'environement sur le finisterrae et s'y connecter:
- cd $STORE
- python3.7 -m venv my_env37
- source $STORE/my_env37/bin/activate
- pip install ipykernel
- python -m ipykernel install --user --name=my_env37 --display-name "Python 3.7 (my_env37)"
- jupyter lab --ip `hostname -i`
- Sélectionner le kernel "Python 3.7 (my_env37) (au lieu de myenv)


# Techniques d’optimisation

## 1 Pruning (Élagage des réseaux de neurones)
...
...
...


2. Quantification

La quantification s'est révélée plus complexe que prévu. En effet, il existe trois types de quantification, dont l'une est dite dynamique. Cette dernière est la plus simple à mettre en place, mais malheureusement, elle ne peut pas être appliquée efficacement à notre modèle. En effet, comme précisé dans la documentation, les couches convolutives (conv layers) ne sont pas affectées par cette méthode de quantification.

![Quantification statique](https://raw.githubusercontent.com/maul0803/Heterogeneous_Programming/main/pas_dynamique.png)

