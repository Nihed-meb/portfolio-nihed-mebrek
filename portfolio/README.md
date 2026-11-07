# Portfolio — Nihed Mebrek

## Ouvrir dans VS Code
1. Dézippez le dossier, puis dans VS Code : **Fichier > Ouvrir le dossier…** et choisissez `portfolio`.
2. Installez l'extension **Live Server** (Ritwick Dey), clic droit sur `index.html` > **Open with Live Server**.
   (Vous pouvez aussi simplement double-cliquer sur `index.html`.)

## Structure
- `index.html` — contenu de la page
- `css/style.css` — design (couleurs en haut du fichier, dans `:root`)
- `js/main.js` — traductions FR/EN (objet `dict`), animations, formulaire
- `assets/signature.png` — votre signature (logo), `assets/icons/` — icônes des compétences
- `autres-versions/` — les autres designs créés (fichiers autonomes)

## À personnaliser
- Textes FR / EN / العربية : objet `dict` (clés `fr`, `en`, `ar`) dans `js/main.js` (et le texte français par défaut dans `index.html`)
- Liens des projets, LinkedIn, GitHub : remplacer les `href="#"` dans `index.html`
- Projets : cartes dans la section `#work` de `index.html`

## Publier en ligne
Déposez le dossier sur GitHub Pages, Netlify ou Vercel (`index.html` est à la racine).


## Ouvrir sur téléphone
Le site est responsive (testé de 320 px à 1280 px). Pour le voir sur votre téléphone : mettez le dossier en ligne (GitHub Pages, Netlify ou Vercel) puis ouvrez le lien, ou avec Live Server ouvrez l'adresse « Network » affichée en bas de VS Code (téléphone et PC sur le même Wi-Fi).
