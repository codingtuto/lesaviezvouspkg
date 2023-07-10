# Lesaviezvous

Un package Python pour obtenir des informations intéressantes à partir de l'API Lesaviezvous.

## Installation

Installez le package à l'aide de `pip` :

```bash
pip install lesaviezvous
```

## Utilisation
Importez le package dans votre script Python et appelez la fonction get_info() pour obtenir des informations intéressantes :
```bash
import lesaviezvous
from lesaviezvous import get_info

info = get_info()
if info:
    print(info)
else:
    print("Impossible de récupérer les informations.")
```

## Exigences
- Python3
- Request

## Problème connu
Il est possible de rencontrer un délai lors de l'affichage de la réponse du serveur. Cela peut être dû à divers facteurs, tels que la vitesse du réseau ou le temps de réponse de l'API Lesaviezvous. Veuillez prendre en compte cette possibilité lors de l'utilisation du package.

