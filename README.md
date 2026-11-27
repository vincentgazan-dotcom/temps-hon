# Temps intermédiaires · Head of Nantes

Pages de temps intermédiaires en direct (source Time-Team), hébergées sur Vercel.

- `index.html` : la page des temps.
- `course.html` : la course virtuelle avec la carte du parcours.
- `api/connecteur.js` : va chercher les temps chez Time-Team (toutes les 10 s au plus).
  Pour changer de course : modifier `API_BASE` et `EVENEMENTS` en haut du fichier.
