![Lesaviezvous](https://telegra.ph/file/2a876a854c0693e55ef7e.jpg)

Un package Python pour obtenir des informations intéressantes à partir de l'API Lesaviezvous.

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
import lesaviezvous
from lesaviezvous.lesaviezvous import faits

fact = faits()
print(fact)
```

## Exigences
- Python3

## Quoi de neuf
### Version 0.2.5:
- Amélioration des performances pour une génération plus rapide des faits.
- Ajout de nouveaux faits à la base de données.
- Correction de bugs mineurs.
