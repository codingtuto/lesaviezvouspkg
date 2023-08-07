![Lesaviezvous](https://telegra.ph/file/2a876a854c0693e55ef7e.jpg)

Un package Python pour obtenir des informations intéressantes à partir de l'API Lesaviezvous.
- Version du package sur PyPI : ![PyPi Package Version](https://img.shields.io/pypi/v/lesaviezvous.svg)
- Versions de Python supportées : ![Supported Python versions](https://img.shields.io/pypi/pyversions/lesaviezvous.svg)
- Nombre de téléchargements totales : ![PyPi downloads](https://img.shields.io/pypi/dm/lesaviezvous.svg)

## Quoi de neuf dans la dernière version (0.2.6) :
- Ajout d'une fonctionnalité pour obtenir des faits aléatoires sans répétition (Avec cette version, vous pouvez maintenant obtenir des faits aléatoires sans répétition en appelant simplement la fonction obtenir_fait() à plusieurs reprises. Chaque appel renverra un fait différent jusqu'à ce que tous les faits aient été utilisés une fois. Vous pouvez également réinitialiser la liste des faits utilisés avec reinitialiser_faits_utilises() pour recommencer à obtenir de nouveaux faits sans répétition. Profitez de la découverte de faits passionnants et divertissants avec la version 0.2.6 !)

## Installation

Installez le package à l'aide de `pip` :

```bash
pip install lesaviezvous
```

## Utilisation
Importez le package dans votre script Python et appelez la fonction faits() pour obtenir des informations intéressantes :
```bash
from lesaviezvous.lesaviezvous import obtenir_fait, reinitialiser_faits_utilises
# Obtenir un fait aléatoire
print(obtenir_fait())


# Obtenir un autre fait aléatoire (différent du premier)
print(obtenir_fait())


# Réinitialiser les faits utilisés pour pouvoir en obtenir de nouveaux sans répétition
reinitialiser_faits_utilises()


# Obtenir un nouveau fait après la réinitialisation
print(obtenir_fait())


# Obtenir un autre fait aléatoire (différent du précédent)
print(obtenir_fait())
```

## Exigences
- Python3
