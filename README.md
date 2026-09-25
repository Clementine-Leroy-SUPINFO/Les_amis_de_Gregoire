# Les Copains de Grégoire
Site de vente en ligne fictif, réalisé dans le cadre d'un devoir universitaire portant sur les langages HTML et CSS.

## Contexte pédagogique
Ce projet a été développé en réponse à la consigne suivante : *« réaliser la construction d'un site de vente en ligne pour une association fictive »*. Il s'agit d'un exercice académique, sans vocation commerciale réelle.

## Stack technique
- **HTML** — structure des pages
- **CSS** — mise en forme et mise en page
- Aucun JavaScript n'est utilisé : le site est entièrement statique
- Hébergement en local et publication en ligne sur GitHub : https://clementine-leroy-supinfo.github.io/Les_copains_de_Gregoire/

## Fonctionnalités principales
- **Page d'accueil** (`index.html`)
- **Pages catégories** : 4 pages de catégories présentant les produits vendus:accessoires, goodies, gourmandises, papeterie
- **Pages descriptives** : une fiche détaillée par article, avec description, caractéristiques et un formulaire fonctionnel pour commander l'article
- **Page panier** : simulation statique d'un panier d'achat
- **Page de contact** : formulaire de prise de contact
- **Page d'erreur 404** personnalisée (`support_3_error_404.html`), accessible en cliquant sur le lien « Notre page Facebook » présent dans le pied de page de chaque page du site (comportement demandé tel quel dans la consigne de l'examen)
- **Accessibilité** : le site a été conçu en tentant de respecter les normes d'accessibilité (voir le rapport dans le dossier `documentation`)

## Arborescence du projet
```
.
├── index.html
├── support_3_error_404.html
├── LICENCE.txt
├── media/
│   ├── images/
│   │   ├── articles/       # Images des articles vendus
│   │   ├── logo/           # Logo du site
│   │   └── autres/         # Photos et icônes diverses
├── HTML/
│   ├── pages catégories/   # 4 pages, une par catégorie de produits
│   ├── pages descriptives/ # Fiches produits (une page par article)
│   └── pages supports/     # Panier et page de contact
├── CSS/                    # Feuilles de style du site
└── documentation/          # Livrables complémentaires demandés dans le cadre de l'examen
```

## Installation et lancement en local
1.Télécharger le projet.
2. Ouvrir le fichier `index.html` dans un navigateur web

Aucune installation de dépendance n'est nécessaire, le site ne reposant que sur du HTML et du CSS statiques.

## Documentation
Le dossier `documentation` contient les livrables complémentaires demandés dans le cadre de l'examen, ainsi qu'un rapport démontrant la conformité du site aux normes d'accessibilité.

## Licence
Voir le fichier [LICENCE.txt](./LICENCE.txt).

## Auteur
Projet réalisé dans le cadre d'un cours de HTML/CSS par Clémentine LEROY.
