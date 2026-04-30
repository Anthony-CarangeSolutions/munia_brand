# 04 — Couleurs

> Les codes ci-dessous sont extraits directement des fichiers SVG officiels Munia (flèches `arrondi-*` et `base-*`). Ils représentent la palette technique exacte utilisée en production.

## Palette principale

### Noir Munia — couleur signature
| Token | Valeur | Usage |
|---|---|---|
| `noir` | `#252525` | Texte principal, logo, traits, structure |

C'est la couleur dominante de la marque. Toujours utilisée pour le texte courant et les éléments structurants.

### Blanc / Fond clair
| Token | Valeur | Usage |
|---|---|---|
| `blanc` | `#FFFFFF` | Fond principal, texte sur fond foncé |
| `blanc-doux` | `#F3F3F3` | Fond secondaire, blocs de respiration |

## Palette d'accent

Cinq couleurs vives qui ponctuent la marque. Elles sont **utilisées avec parcimonie** — généralement une seule couleur d'accent par composition, pour souligner un point, une donnée ou un appel à l'action.

| Token | Valeur | Aperçu | Usage suggéré |
|---|---|---|---|
| `vert` | `#65DC8A` | 🟢 vert frais | Croissance, succès, validation, données positives |
| `bleu` | `#6A8BFF` | 🔵 bleu vif | Information, liens, axe institutionnel |
| `orange` | `#FF9602` | 🟠 orange vif | Énergie, attention, mise en avant |
| `jaune` | `#FFD75F` | 🟡 jaune doux | Surlignage, points clés, optimisme |
| `gris-pale` | `#B8CAC5` | ⚫ gris vert pâle | Neutre, secondaire, fonds discrets |

## Codes pour design

```css
:root {
  --munia-noir: #252525;
  --munia-blanc: #FFFFFF;
  --munia-blanc-doux: #F3F3F3;
  --munia-vert: #65DC8A;
  --munia-bleu: #6A8BFF;
  --munia-orange: #FF9602;
  --munia-jaune: #FFD75F;
  --munia-gris-pale: #B8CAC5;
}
```

```json
{
  "noir":       "#252525",
  "blanc":      "#FFFFFF",
  "blancDoux":  "#F3F3F3",
  "vert":       "#65DC8A",
  "bleu":       "#6A8BFF",
  "orange":     "#FF9602",
  "jaune":      "#FFD75F",
  "grisPale":   "#B8CAC5"
}
```

## Règles d'utilisation

### Hiérarchie
1. **Noir + Blanc** = base de toute composition (90 % de la surface).
2. **Une couleur d'accent** par composition (10 % de la surface max).
3. Mixer plusieurs accents seulement pour des **systèmes graphiques** (graphiques, catégories, icônes différenciées).

### Contraste et accessibilité
- Texte courant : **noir #252525** sur **blanc** ou **blanc-doux**.
- Texte sur fond coloré : utiliser **noir #252525** sur jaune, vert, gris-pâle ; utiliser **blanc** sur orange et bleu pour respecter WCAG AA.
- Ne **jamais** utiliser une couleur d'accent comme couleur de texte courant.

### À éviter
- Ne pas inventer de teintes intermédiaires : s'en tenir à la palette ci-dessus.
- Ne pas appliquer de dégradés entre couleurs d'accent.
- Ne pas utiliser plus de 3 couleurs (noir + accent + 1 autre) dans une même composition simple.

## Versions des accents

À utiliser dans les **flèches** et **éléments graphiques** : disponibles en SVG dans `assets/graphics/arrows/` pour chacune des couleurs d'accent + base, blanc, gris.
