# EAU & TECHNIQUES – Portail documentaire de l'atelier BTS Métiers de l'Eau

Version V2 : maquette documentaire avec dossiers constructeurs PDF, pages de schémas d'origine, photographies sources disponibles et premiers repères interactifs.

## Démarrer
Aucune compilation n'est nécessaire. Ouvrir `index.html` dans un navigateur, ou lancer un serveur statique local.

## Publication GitHub / Netlify
1. Créer un dépôt GitHub vide.
2. Déposer le contenu de ce dossier à la racine du dépôt.
3. Connecter le dépôt à Netlify.
4. Paramètres Netlify : Build command vide ; Publish directory `.`.

## Contenu
- `assets/catalogue.js` : inventaire des 13 installations et liens documentaires.
- `assets/hotspots.js` : coordonnées des premiers repères interactifs du dossier CP155.
- `assets/app.js` : navigation, fiches techniques, affichage des documents et gestion des saisies de démonstration.
- `assets/schemas/` : rendus des pages schémas d'origine, sans redessin.
- `assets/photos/` : photographies originales extraites du dossier Delta Lab CP155.
- `documents/pilotes/` : dossiers PDF constructeurs et documents sources transmis.
- `docs/INVENTAIRE_DOCUMENTAIRE.md` : état précis de l'intégration documentaire.
- `docs/CAHIER_DES_CHARGES.md` et `docs/ROADMAP.md` : périmètre et étapes suivantes.

## Ce qui fonctionne dans cette version
- Consultation des 13 fiches d'installation.
- Ouverture des documents PDF sources dans un nouvel onglet.
- Affichage des photographies originales disponibles.
- Consultation des pages schématiques d'origine.
- Hotspots cliquables sur les deux synoptiques CP155 (physico-chimie et filtration) ; sélection d'un repère pour afficher une fiche composant.
- Zoom sur les photographies.
- Carnet d'atelier et maintenance générale : saisie de démonstration, modification des interventions et export CSV.

## Limites à connaître
- Les hotspots CP155 sont les premiers repérages interactifs construits à partir des pages sources. Ils devront être vérifiés sur le pilote réel avant d'être utilisés comme aide d'intervention.
- Pour les autres installations, les pages de schémas constructeur sont consultables, mais le positionnement des repères interactifs reste à faire/valider.
- Les photographies originales disponibles dans les sources reçues et extraites pour cette version concernent le CP155 Delta Lab. Les autres photos réelles devront être extraites des dossiers si elles y figurent ou fournies par l'atelier. Aucune photo générique n'est utilisée pour les remplacer.
- Le pilote 12 boues activées dispose uniquement du synoptique transmis ; le dossier constructeur complet reste attendu.
- Les fiches des pilotes 8 et 11 sont désormais reliées aux notices Pignat transmises.
- Les données de carnet et de maintenance sont conservées localement dans le navigateur (localStorage), sans partage entre postes.
- Les espaces TP restent une base de conception : les formulaires de mesures, calculs, graphiques et exports PDF étudiants ne sont pas encore développés.
- Aucune authentification ni base de données partagée n'est configurée.

## Important
Les dossiers PDF sont des documents sources transmis par l'utilisateur. Les informations techniques affichées dans les hotspots sont limitées aux éléments vérifiés dans ces dossiers. Ne pas utiliser cette maquette comme procédure de consignation, de maintenance ou de sécurité. Vérifier les notices et appliquer les consignes de l'établissement.
