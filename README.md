# Apps1D76 — Outils numériques pour l'école primaire

Page d'accueil des outils de la Mission Numérique Éducatif 76, réorganisée en rubriques.

## Structure

```
index.html     Page d'accueil (rubriques : En classe, Outils pour la classe,
               Suivre et évaluer, Direction d'école)
randomizer/    Randomizer — tirage au sort d'un nom dans une liste
fonts/         Police Marianne (marque de l'État), hébergée dans le site :
               voir fonts/README.md pour la source et les conditions d'utilisation
```

Les autres outils référencés par la page d'accueil (`prompteurs/`, `carnet.html`,
`evalaide/`, `course/`, `250consignes/`, `Litteranum/`, `outildir/`,
`generateur-etiquettes-deplacables/`, `images/Logo_DSDEN76.png`) sont à ajouter
à côté de `index.html`.

## Utiliser en local

Projet 100 % statique, sans dépendance :

```bash
python3 -m http.server 8080
```

Puis ouvrez `http://localhost:8080`.
