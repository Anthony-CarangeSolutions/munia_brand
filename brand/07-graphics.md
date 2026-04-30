# 07 — Éléments graphiques

## Les flèches Munia

Les flèches sont l'**élément graphique signature** de la marque. Elles déclinent une métaphore visuelle : une trajectoire (le trait) qui aboutit à un point cible (le cercle de couleur), symbolisant l'**accompagnement** et la **progression**.

## Deux familles

### Flèche « base » (angle droit)
Trajectoire en angle droit, avec rotation 45°. Plus sobre, plus institutionnelle. Recommandée pour :
- Documents officiels
- Slides corporate
- Rapports

Fichiers : `Flèche-base-{couleur}.{svg,png,jpg}`

### Flèche « arrondi » (courbe)
Trajectoire courbe et longue. Plus dynamique, plus organique. Recommandée pour :
- Communications réseaux sociaux
- Site web (sections hero)
- Visuels énergiques / inspirationnels

Fichiers : `Flèche-arrondi-{couleur}.{svg,png,jpg}`

## Variations de couleurs

Chaque flèche est disponible avec un **point cible** dans une couleur d'accent au choix :

| Couleur | Code | Connotation |
|---|---|---|
| Vert | `#65DC8A` | Croissance, succès |
| Bleu | `#6A8BFF` | Information, axe institutionnel |
| Orange | `#FF9602` | Énergie, mise en avant |
| Jaune | `#FFD75F` | Optimisme, surlignage |
| Gris | `#B8CAC5` | Neutre, secondaire |
| Blanc | `#F3F3F3` | Sur fond foncé |

Le **trait** de la flèche reste toujours **noir #252525**.

## Règles d'usage

### À faire
- Utiliser **une seule flèche** par composition simple.
- Aligner la flèche pour qu'elle pointe vers l'**élément clé** (chiffre, citation, CTA).
- Choisir la couleur en cohérence avec le message :
  - Bonne nouvelle / résultat positif → vert
  - Information / partenariat → bleu
  - CTA / urgence → orange
- Conserver les **proportions** et la **densité du trait**.

### À éviter
- Ne **pas combiner** les deux styles (base + arrondi) dans la même image.
- Ne **pas étirer** ou déformer la courbe.
- Ne **pas recolorer** le trait noir.
- Ne **pas appliquer** d'effet (ombre, contour, glow).

## Formats fournis

Pour chaque combinaison `{base|arrondi} × {6 couleurs}` :
- `SVG` — vectoriel, recommandé.
- `PNG` — transparence supportée.
- `JPG` — fond opaque, qualité 2× (suffixe `@2x-100`).
- `EPS` — un fichier maître `fleches.eps` pour tous les vecteurs.

Disponibles dans `assets/graphics/arrows/`.

## Combinaison avec les icônes

Les flèches peuvent **pointer vers** une icône Munia pour créer un visuel narratif :

```
[texte]  ───arc──→  [icône Hôtel de ville]
```

Garder une **respiration** suffisante (au moins 2× la hauteur du cercle de la flèche) entre la flèche et l'élément ciblé.
