# Is-Vectoriel-Py

📄 **Is-Vectoriel-Py** est une fonction Python qui prend en entrée un fichier PDF et retourne `True` s'il est vectoriel, sinon `False`.


## Table des Matières
- [Exigences](#exigences)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exécution sur Windows](#exécution-sur-windows)
- [Exécution sur MacOS](#exécution-sur-macos)
- [Contribuer](#contribuer)
- [FAQ](#faq)
- [Licence](#licence)
- [Crédits](#crédits)

## Exigences
- Python 3.x
- [pypdf](https://pypi.org/project/pypdf/)

## Installation

```bash
pip install pypdf
```
## Utilisation

```python
from is_vectoriel import is_vectoriel

resultat = is_vectoriel("votrefichier.pdf")
print(resultat)
```

## Exécution

### Exécution sur Windows 🪟

Ouvrez l'invite de commande.
Allez dans votre répertoire de projet.
Exécutez les commandes suivantes :
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python votre_script.py
```
### Exécution sur MacOS 🍏

Ouvrez le terminal.
Allez dans votre répertoire de projet.
Exécutez les commandes suivantes :
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python votre_script.py
```
## Contribuer

Les contributions sont les bienvenues ! Veuillez soumettre un pull request ou ouvrir une issue pour discuter des modifications que vous souhaitez apporter.

## FAQ

### Comment savoir si un fichier PDF est vectoriel ?
Utilisez la fonction is_vectoriel avec le chemin du fichier PDF. La fonction retourne True si le PDF est vectoriel, sinon False.

### Quelles sont les dépendances nécessaires ?
Vous avez besoin de Python 3.x et du package pypdf.

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

## Crédits

pypdf [pypdf](https://pypi.org/project/pypdf/)
