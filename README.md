# Portfolio de Haytam Ghallous

Site portfolio statique en français pour présenter le profil de développeur ERP / Odoo / Python.

## Technologies utilisées

- HTML5
- CSS3
- JavaScript simple
- Site statique sans backend

## Structure des fichiers

- `index.html` : page principale
- `style.css` : styles et mise en page
- `script.js` : interactions JavaScript
- `README.md` : documentation du projet
- `assets/` : dossier prévu pour le CV et les ressources statiques

## Lancer le site en local

1. Ouvrez le dossier dans un éditeur.
2. Ouvrez `index.html` directement dans un navigateur.

Optionnel : utiliser un serveur local simple si besoin :

```bash
cd /Users/macos/Desktop/PORTFOLIOHAYTAM
python3 -m http.server 8000
```

Ensuite, ouvrir `http://localhost:8000` dans le navigateur.

## Déployer sur Vercel

1. Créez un compte Vercel si nécessaire.
2. Importez le projet depuis GitHub ou sélectionnez le dépôt local.
3. Utilisez les paramètres par défaut pour un site statique.
4. Déployez. Le site doit fonctionner immédiatement.

## Modifier le contenu

- Mettre à jour le texte et les sections dans `index.html`.
- Ajuster les couleurs et la mise en page dans `style.css`.
- Ajouter ou modifier des interactions légères dans `script.js`.
- Remplacer `assets/cv-haytam-ghallous.pdf` par le fichier CV final.

## Commandes Git pour GitHub

```bash
cd /Users/macos/Desktop/PORTFOLIOHAYTAM
git init
git add .
git commit -m "Initial commit - portfolio Haytam Ghallous"
git branch -M main
git remote add origin https://github.com/<votre-utilisateur>/<nom-du-depot>.git
git push -u origin main
```

## Conseils de déploiement

- Vérifiez que le CV est bien placé dans `assets/cv-haytam-ghallous.pdf`.
- Vérifiez les liens LinkedIn et GitHub dans `index.html`.
- Sur Vercel, choisissez le dossier racine comme répertoire de déploiement.
- Le site est prêt pour GitHub Pages, Netlify ou Vercel.
