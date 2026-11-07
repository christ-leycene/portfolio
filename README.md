# portfolio

Site perso en thème sombre, navigation multi-pages via hash routing (pas de rechargement, pas de framework). Vanilla HTML/CSS/JS.

## Fichiers
- `index.html` — structure + nav
- `style.css` — thème sombre / accents verts
- `script.js` — données (projets, certifs) + routeur par hash + pluie matrix en hero
- `assets/photo.jpg` — ta photo

## Lancer en local
Ouvre `index.html` dans un navigateur, rien d'autre à installer.

## Déployer sur GitHub Pages
1. Push ce dossier dans un repo (ex. `gazoux/portfolio`).
2. Settings → Pages → Source: branch `main`, dossier `/ (root)`.
3. En ligne sur `https://<ton-username>.github.io/<repo>/`.

## À compléter toi-même
- Section contact (`script.js`, fonction `renderContact`) : ajoute ton numéro, GitHub, LinkedIn.
- Les boutons "Ouvrir le GitHub" / "Voir le code" de chaque projet pointent vers `#` — remplace `href` dans le tableau `PROJECTS` par tes vrais liens.
- Pour ajouter un projet : un nouvel objet dans `PROJECTS`, c'est tout — la page de détail se génère toute seule.
