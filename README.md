# Site CV — Simon Hamery

Site personnel statique (HTML/CSS) présentant trois profils professionnels : développeur frontend freelance, mécanicien cycle (en reconversion) et aménageur/loueur de vans.

## Structure du projet

```
.
├── index.html                          # Page d'accueil — présentation des 3 profils
├── cv_developpeur_frontend.html        # CV détaillé — Développeur Frontend Vue.js/TypeScript
├── cv_mecanicien_cycle_alternance.html # CV détaillé — Mécanicien Cycle en alternance
└── assets/
    └── photos/
        ├── portrait/                   # Photo de portrait (hero)
        ├── dev/                        # Photo du setup de développement
        ├── vélo/                       # Photos vélo (bikepacking, mécanique, coursier)
        └── aménagement van/             # Photos des vans aménagés
```

## Aperçu en local

Aucune installation ni dépendance n'est nécessaire, ce sont des fichiers HTML statiques. Pour les consulter :

1. Ouvrir directement `index.html` dans un navigateur, **ou**
2. Lancer un petit serveur local (recommandé pour que les chemins relatifs des images fonctionnent bien) :
   ```bash
   python3 -m http.server 8000
   ```
   puis ouvrir [http://localhost:8000](http://localhost:8000)

## Déploiement

Le site est 100 % statique, il peut être déployé tel quel sur GitHub Pages, Netlify, Vercel ou tout hébergement statique : il suffit de pousser le contenu du dossier (avec le dossier `assets/`) sans étape de build.

## Tech stack

- HTML5 / CSS3 (pas de framework, pas de JS hors `window.print()` pour le téléchargement PDF des CV)
- Polices via Google Fonts : Bebas Neue, DM Sans, Space Mono
- Chaque CV (`cv_*.html`) intègre une mise en page imprimable au format A4 (`@media print`) avec un bouton « Télécharger au format PDF »

## À faire / pistes d'amélioration

- [ ] Vérifier l'accessibilité (contraste, alternatives textuelles) sur les trois pages
- [ ] Ajouter un favicon
- [ ] Éventuellement un fichier `CNAME` / config

## Contact

- Email : [shamery@free.fr](mailto:shamery@free.fr)
- GitHub : [github.com/shamzic](https://github.com/shamzic)
- Localisation : Montpellier (34)
