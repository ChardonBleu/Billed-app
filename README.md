# ![Billed](logo.png)

## Billed-app

Ce dépôt correspond au Projet 9 de la formation Javascript React d'Openclassrooms.

Il s'agit d'une applicattion SAAS RH de gestion des demandes de remboursement de frais professionnels.


## Exécution en local

Cloner le dépôt dans le dossier de votre choix:  
Attention: il s'agit d'un dépôt avec submodules git ! Il faut cloner le dépôt ET les sous modules:

```bash
git clone --recurse-submodules https://github.com/ChardonBleu/Billed-app
```

### Lancer le back  

[Readme du Back](Billed-Back/README.md)

### Lancer le front

[Readme du Front](Billed-Front/README.md)

Pour lancer le linter: 
```bash
npm run lint
```
Des warnings sont encore actifs dûs à l'utilisation de jquery dans le code et à des portions de code pour l'instant inutilisées.  

Pour lancer le prettier: 
```bash
npm run fmt
```

Pour lancer les tests: 
```bash
npm run test
```

Pour lancer un seul fichier de test: 
```bash
npm run st src/__tests__/mon_fichier_de_test.js
```

## Hébergement GitHub

[chardonbleu.github.io/Petits_plats/](https://chardonbleu.github.io/Billed-app/)

## Sources utilisées:

Ressources:

- Cours [Testez l'interface de votre site](https://openclassrooms.com/fr/courses/3504461-testez-linterface-de-votre-site).

- Cours [Testez vos applications Front End avec JavaScript](https://openclassrooms.com/fr/courses/7159306-testez-vos-applications-front-end-avec-javascript).


## Remerciements

Un très grand merci à Herbert Caffarel pour ses précieux conseils et retours.
