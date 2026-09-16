# Informatique CPGE — Mohammedia

Site statique regroupant le programme et les supports de cours d'informatique
pour les filières MPSI (1ère année), MP/PSI (2ème année) et TSI (2ème année).

## Structure

- `index.html` — accueil, liens vers les trois filières
- `mpsi1.html`, `mppsi2.html`, `tsi2.html` — hub de chaque filière (programme + liste des chapitres)
- `*-programme.html` — vue interactive du programme (carte / poster / frise)
- `*-support-XX.html` — support de cours par chapitre

## Aucune installation nécessaire

Tout le site est en HTML/CSS/JS statique avec des liens relatifs.
Ouvrir `index.html` dans un navigateur suffit pour naviguer localement.

## Déploiement sur GitHub Pages

1. Créer un dépôt GitHub (public ou privé selon ton compte).
2. Déposer tous les fichiers de ce dossier à la racine du dépôt.
3. Aller dans Settings → Pages, choisir la branche `main` et le dossier `/root`.
4. Le site sera disponible à l'adresse indiquée par GitHub (en général
   `https://<ton-nom-utilisateur>.github.io/<nom-du-depot>/`).

## Mettre à jour

Remplacer les fichiers modifiés (même nom) et re-déposer sur GitHub :
la page se met à jour automatiquement en quelques minutes.
