# Site web de François Pilet

Ce site est construit avec [Jekyll](https://jekyllrb.com/), un générateur de site statique, et hébergé sur [GitHub Pages](https://pages.github.com/).

## Comment exécuter le site localement

1. Assurez-vous d'avoir Ruby installé (version 2.5.0 ou supérieure)
2. Installez les dépendances :
   ```
   bundle install
   ```
3. Exécutez le serveur Jekyll :
   ```
   bundle exec jekyll serve
   ```
4. Accédez au site à l'adresse [http://localhost:4000](http://localhost:4000)

## Structure du site

- `_posts/` : Contient tous les articles du site
- `_layouts/` : Contient les modèles de mise en page
- `_includes/` : Contient les éléments réutilisables (en-tête, pied de page, etc.)
- `assets/` : Contient les fichiers statiques (images, CSS, JavaScript)
- `_config.yml` : Fichier de configuration principal de Jekyll

## Comment ajouter un nouvel article

1. Créez un nouveau fichier dans le dossier `_posts/` avec le format de nom suivant : `AAAA-MM-JJ-titre-de-l-article.md`
2. Ajoutez l'en-tête YAML au début du fichier :
   ```yaml
   ---
   layout: post
   title: "Titre de l'article"
   date: AAAA-MM-JJ HH:MM:SS +0200
   author: "François Pilet"
   categories: [catégorie1, catégorie2]
   tags: [tag1, tag2]
   excerpt: "Un court extrait de l'article qui apparaîtra sur la page d'accueil."
   image: /assets/images/AAAA/MM/image.jpg
   ---
   ```
3. Ajoutez le contenu de l'article en Markdown après l'en-tête YAML
4. Utilisez `<!--more-->` pour définir l'extrait qui sera affiché sur la page d'accueil

## Déploiement

Le site est automatiquement déployé sur GitHub Pages lorsque des modifications sont poussées sur la branche principale.

Pour déployer manuellement :
1. Ajoutez vos modifications : `git add .`
2. Validez vos modifications : `git commit -m "Description des modifications"`
3. Poussez vos modifications : `git push origin main`

## Personnalisation

- Pour modifier l'apparence, modifiez les fichiers CSS dans `assets/css/`
- Pour modifier la structure des pages, modifiez les fichiers dans `_layouts/` et `_includes/`
- Pour modifier les paramètres globaux, modifiez le fichier `_config.yml`
