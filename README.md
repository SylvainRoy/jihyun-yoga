# Jihyun Lee — Viniyoga · Côte d'Azur

Site statique (HTML/CSS, sans étape de build) pour Jihyun Lee, professeure de Viniyoga à Opio.

## Prévisualiser en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000/ (depuis la racine du dépôt).

## Publier sur GitHub Pages

1. Pousser la branche `main` vers le dépôt GitHub.
2. Dans le dépôt : **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Choisir la branche `main`, dossier `/ (root)`, puis **Save**.
4. Le site sera disponible sur `https://<utilisateur>.github.io/jihyun-yoga/`.

Le fichier `.nojekyll` désactive le traitement Jekyll. Tous les chemins sont relatifs, le site fonctionne donc sous un sous-chemin.

## Contenu à remplacer (placeholders)

- Textes de présentation du Viniyoga (`viniyoga.html`)
- Extraits et articles d'actualités (`index.html`, `actualites.html`)
- Tarifs (`cours.html`) — montants indicatifs
- Informations pratiques et horaires (`cours.html`, `index.html`)
- Liens Instagram / Facebook (pied de page)
- Texte des mentions légales (`mentions-legales.html`)
- Adresse e-mail et paragraphe « Comment venir » (`contact.html`)
