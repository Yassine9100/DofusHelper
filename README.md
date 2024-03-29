# Dofus Helper

Repo pour diffuser le bot (projet perso).

## Installation

1. Installer [Python 3](https://www.python.org/downloads/)
2. Ajouter PIP (installé avec les dernières versions de Python) [à votre Path](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/). Si vous n'avez rien touché à l'installation de python, le dossier à ajouter devrait être 
'C:\Program Files\Python39\Scripts'.
2. Installer [Npcap](https://nmap.org/npcap/)
2. Exporter le git (bash, zip, ...)
3. Ouvrir une invite de commande / terminal et taper
```bash
pip install -r requirements.txt
```

## Utilisation

Le programme s'éxécute par le fichier main.py.

Soit ouvrir le fichier launch.bat (sous Windows), soit l'ouvrir dans une invite de commande à l'aide de 

```bash
py main.py
```
Une fois lancé, vous aurez accès une liste d'outils.
### Treasure Hunt Helper

Localise les indices de chasse au trésor. Une mini fenêtre s'ouvre pour afficher la position, la distance avec la joueur et la direction (style GPS). Détection de phorreur et d'archimonstre intégrée. Cliquer sur l'icône de drapeau, loupe ou combat clique directement sur le bouton respectif dans la fenêtre de chasse au trésor (si celle ci est ouverte).

### Treasure Hunt Bot

Mêmes fonctionnalités et fenêtre que le helper, mais tout est automatisé (sauf le combat). Les déplacements s'effectuent pas un clic. Pour le bas le bot recherche l'icône de changement de barre de sort, il faut donc que vous soyez à la première page pour le calibrage au lancement de l'application. Pour le reste des déplacements, le milieu de l'écran est pris. 

### HDV List

Liste les objets en vente dans un HDV, avec la différence entre les prix postés par le joueur et le prix actuel. Trie les objets par différence en %.

Cliquer sur le bouton 'Automate Prices' va actualiser tous les items dont la différence est strictement supérieur à la valeur spécifiée dans la cellule d'input. Chaque item sera alors posté à 1 Kamas moins cher.

### Fail Safe

Dans n'importe quel module, quand le bot pixel est utilisé, placer la souris dans le coin supérieur gauche de l'écran stoppera le bot (il faudra relancer l'application pour relancer le bot).

## Copyright
Merci à [LaBot](https://github.com/louisabraham/LaBot) pour son reader/writer de packet.

## License
[MIT](https://choosealicense.com/licenses/mit/)

