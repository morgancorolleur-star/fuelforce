# FuelForce

Application web de planification nutritionnelle pour les sports d'endurance (vélo, trail, course à pied, triathlon).

Fonctionne entièrement dans le navigateur — sans serveur, sans inscription, sans installation.

## Fonctionnalités

- Calcul des besoins en glucides, hydratation et sodium basé sur les METs Ainsworth 2011
- Wizard en 5 étapes : profil athlète → paramètres de sortie → sélection produits → timeline → résultats
- Mode Express : plan complet en 3 questions
- Base de 95+ produits référencés (boissons, gels, solides, naturels, récupération)
- Stacks préconfigurés par budget (Budget / Équilibré / Premium / Naturel)
- Timeline heure par heure avec timing de digestion
- Alertes scientifiques : ratio fructose/glucose, sodium, BCAA, tolérance digestive
- Sauvegarde locale de plusieurs plans (localStorage)
- Export texte, impression, partage natif
- Météo automatique via GPS (Open-Meteo)
- Compatible PWA (installable sur mobile)

## Lancer en local

Aucune dépendance à installer. Il suffit d'ouvrir le fichier dans un navigateur :

```
double-clic sur index.html
```

Ou via un serveur local (recommandé pour que la géolocalisation GPS fonctionne) :

```bash
# avec Python
python -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Stack

HTML · CSS · JavaScript vanilla — fichier unique `index.html`.

## Données

Base produits mise à jour en juin 2025. Les calculs sont indicatifs — consulter un nutritionniste du sport pour un protocole de compétition.
