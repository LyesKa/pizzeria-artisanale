# L'Artisanale — site vitrine

Site statique HTML / CSS / JavaScript, prêt pour GitHub Pages.

## Structure

- `index.html` : page d'accueil
- `css/style.css` : styles et responsive design
- `js/main.js` : navigation mobile, animations, année automatique
- `js/data.js` : coordonnées et données faciles à modifier
- `pages/` : mentions légales et confidentialité (modèles à compléter)
- `assets/` : icône et ressources locales

## Publication sur GitHub Pages

1. Créez un dépôt GitHub public, par exemple `pizzeria-artisanale`.
2. Importez **tout le contenu** de ce dossier à la racine du dépôt (pas le dossier parent).
3. Ouvrez `Settings` → `Pages`.
4. Dans `Build and deployment`, choisissez `Deploy from a branch`.
5. Sélectionnez `main` et `/ (root)`, puis `Save`.
6. Après le déploiement, ouvrez l'URL affichée par GitHub Pages.

## À vérifier avant publication

Les annuaires consultés ne donnent pas tous les mêmes horaires. Les horaires ne sont donc pas publiés dans cette version. Confirmez-les avec le propriétaire.

Le téléphone utilisé dans les liens est le 04 13 59 74 24, retrouvé dans plusieurs fiches publiques. Confirmez qu'il s'agit bien du numéro à afficher.

Les photos sont des visuels d'ambiance temporaires chargés depuis Unsplash. Remplacez-les par des photos de l'établissement et de ses pizzas, avec les autorisations nécessaires. Les images externes nécessitent une connexion Internet.

La carte et les prix ne sont pas inventés : cette version invite le visiteur à appeler pour obtenir la carte à jour. Ajoutez les véritables recettes, ingrédients et prix après validation.

Complétez les mentions légales et la politique de confidentialité avec les informations exactes de l'exploitant. Le texte fourni est un modèle, pas un avis juridique.

## Modifier les coordonnées

Ouvrez `js/data.js`. Modifiez le nom, l'adresse, le téléphone et les liens. Le numéro de téléphone doit être au format international dans `phoneLink`, sans espace.

## Remplacer les photos

Dans `index.html`, recherchez `images.unsplash.com` et remplacez chaque URL par le chemin de votre photo, par exemple `assets/images/pizza-signature.webp`.

Pour de bonnes performances, utilisez des images WebP optimisées, idéalement moins de 300 à 400 Ko chacune.

## Important

GitHub Pages héberge des sites statiques. Aucun backend, paiement en ligne, base de données ou formulaire avec traitement serveur n'est inclus.
