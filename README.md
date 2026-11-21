# Portfolio — Bonaventure Danfi

Première version d'un portfolio personnel bilingue (français / anglais), responsive et sans framework.

## Lancer le site en local

1. Décompresser `bonaventure_portfolio.zip`.
2. Ouvrir le dossier `bonaventure_portfolio`.
3. Ouvrir `index.html` dans un navigateur.

Pour un aperçu local avec un petit serveur Python, ouvrir un terminal dans le dossier puis lancer :

```bash
python3 -m http.server 8000
```

Visiter ensuite `http://localhost:8000`.

## Personnalisations indispensables avant publication

Dans `index.html` :
- Remplacer `YOUR_EMAIL@example.com` par ton adresse e-mail réelle.
- Ajouter les liens vers tes profils LinkedIn et GitHub dans la section Contact.
- Ajouter une photo professionnelle si tu souhaites en afficher une.
- Ajouter les liens vers ton mémoire, tes rapports, tes présentations et tes dépôts de code.
- Vérifier les intitulés exacts des diplômes et des projets.

## Modifier le contenu

- `index.html` contient la structure et le contenu.
- `style.css` contient les couleurs, la mise en page et le responsive design.
- `script.js` contient les traductions et le comportement du menu.

Le changement de langue est géré dans `script.js`, dans les objets `translations.fr` et `translations.en`.

## Publication

Le site est compatible avec GitHub Pages : déposer les trois fichiers (`index.html`, `style.css`, `script.js`) à la racine d'un dépôt GitHub, puis activer Pages dans les paramètres du dépôt.

## Notes de cette première version

Les descriptions de projets sont volontairement prudentes. Le projet de modélisation stochastique est présenté comme une piste en cours d'exploration, et non comme un résultat final. Les coordonnées et liens personnels ne sont pas inventés.


## Ajouter les captures de simulation

La page contient une galerie avec trois emplacements préparés. Pour intégrer les captures, envoie les images dans la conversation et indique à quel modèle chacune correspond (banque, entrepôt ou autre). Les images pourront ensuite être placées dans `assets/simulations/` et affichées dans la galerie avec une légende.

Conseils : privilégier les captures nettes en PNG ou JPG, si possible en format paysage, et masquer les données personnelles ou confidentielles.
