# Check Matos

Appli web statique (un seul fichier HTML, aucune dépendance, fonctionne hors-ligne) pour vérifier le matériel vidéo avant un tournage (mariage, etc.) et au moment de repartir.

## Utilisation

Ouvrir `index.html` dans un navigateur (double-clic, ou le déposer sur n'importe quel hébergement statique : Cloudflare Pages, Netlify, GitHub Pages...).

- **Ajouter du matos** : taper ou dicter (bouton micro 🎤, Chrome/Safari). Séparer plusieurs objets par une virgule pour tout ajouter en une fois.
- **Catégorisation automatique** : caméras, objectifs, son, lumière, batteries & stockage, stabilisation, accessoires, administratif.
- **★ Essentiel** : marque un objet comme critique ; une alerte s'affiche s'il n'est pas coché.
- **Onglet "Avant le mariage"** : cocher ce qui est pris.
- **Onglet "Avant de partir"** : ne montre que ce qui a été pris, à cocher avant de quitter le lieu pour ne rien oublier.
- **Suggestions** : liste de matériel souvent oublié en tournage mariage, non présent dans la liste actuelle.
- **Nouvel évènement** : remet toutes les cases à zéro en gardant la liste de matériel.

Les données sont stockées uniquement dans le navigateur (`localStorage`), rien n'est envoyé sur un serveur.
