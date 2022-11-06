# Tutoriaux concernant le dépôt [MCO](https://github.com/JepEtau/mco)

- Il est conseillé pour les ceux qui souhaitent utiliser plusieurs environnements/versions de Python d'utiliser des environnements virtuels: Anaconda, pyenv, virtualenv, de multiples sessions Windows, WSL, ou autres.

N'est détaillé ici qu'une installation sous Windows 11 sans environnement virtuel et de façon simpliste. Le projet a été testé sur Windows 11 et sur une distribution Debian 11 (bullseye)


## Installations (Windows 11)

### Python

1) Télécharger Python **3.10**: https://www.python.org/downloads/
2) Installation
3) Vérifier que python a bien été installé en vérifiant la version dans une "invite de commande" (cmd.exe) ou "fenêtre Powershell":
en exécutant la commande:
```
python --version
```

### Modules python
1) Dans l'invite de commande ou fenêtre powershell exécuter les commandes suivantes
```
pip install numpy
pip install opencv-python
pip install scikit-image
```

Remarque: il vous sera sans doute demandé de mettre à jour 'pip' en exécutant la commande: ```python.exe -m pip install --upgrade pip``` ce qui est recommandé de faire!


### Téléchargement du projet
1) Sur la page principale, cliquer sur le bouton code et choisir 'Download ZIP'
2) Extraire les fichiers (le répertoir utilisé est D:\ dans les exemples suivants)
4) Installer les programmes et fichiers specifiés sur la [page principale du dépôt](https://github.com/JepEtau/mco)
3) Copier les fichiers video d'entrée dans les répertoires spécifiés. (voir la page principale du projet)

### Vérification
1) Exécuter la commande dans le répertoire (d:\mco\scripts) pour vérifier que tout fonctionne correctement
```
python run.py --episode 1 --vfilter deinterlace
```