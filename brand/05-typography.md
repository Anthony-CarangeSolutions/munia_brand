# 05 — Typographie

## Famille principale

**GT Standard** (Grilli Type)

Sans-serif géométrique-humaniste contemporaine. Choisie pour sa **lisibilité** sur écran, son **caractère neutre mais affirmé**, et sa capacité à fonctionner aussi bien dans des titres que dans du texte courant.

### Graisses utilisées

| Graisse | Fichier source | Usage |
|---|---|---|
| **Bold** | `GT-Standard-L-Standard-Bold-Trial.otf` | Titres, sous-titres, mises en valeur |
| **Regular** | `GT-Standard-L-Standard-Regular-Trial.otf` | Texte courant, paragraphes, légendes |

> ⚠️ **Licence** : les fichiers actuels sont des versions **trial**. Pour tout usage commercial / production, acquérir la licence officielle GT Standard sur [grillitype.com](https://www.grillitype.com).

## Hiérarchie suggérée

| Niveau | Style | Taille (web) | Taille (print) |
|---|---|---|---|
| H1 / Titre principal | GT Standard **Bold** | 48–64 px | 36–48 pt |
| H2 / Section | GT Standard **Bold** | 32–40 px | 24–28 pt |
| H3 / Sous-section | GT Standard **Bold** | 22–26 px | 16–20 pt |
| Corps de texte | GT Standard Regular | 16 px | 10–11 pt |
| Légende / Caption | GT Standard Regular | 13–14 px | 8–9 pt |

Interlignage (line-height) : **1.4–1.6** pour le corps de texte, **1.1–1.2** pour les titres.

## Polices de substitution (fallback)

Quand GT Standard n'est pas disponible (mail, web sans licence, document interne) :

```css
font-family: "GT Standard", "Inter", "Helvetica Neue", Arial, sans-serif;
```

- **Web fallback** : Inter (très proche de GT Standard, gratuit, Google Fonts).
- **Système** : Helvetica Neue / Arial.
- **Microsoft Office** : Calibri ou Aptos.
- **Google Workspace** : Inter (à installer si possible) ou Roboto.

## Règles d'usage

### À faire
- Utiliser **Bold pour les titres**, **Regular pour le reste**. Pas d'italique sauf citation ou marque commerciale.
- Maintenir une hiérarchie claire (3 niveaux max sur une même page).
- Aligner le texte à **gauche** par défaut. Centrer uniquement les titres courts ou les éléments décoratifs.
- Privilégier les **paragraphes courts** (3–5 lignes max).

### À éviter
- Ne pas mélanger plusieurs polices dans un même document (uniquement GT Standard ou son fallback).
- Ne pas utiliser de **soulignement** (réserver aux liens hypertexte).
- Ne pas justifier le texte (lézardes typographiques).
- Ne pas utiliser GT Standard **Light** ou **Black** (non incluses dans la trousse).

## Caractères spéciaux et règles québécoises

- Apostrophe française **'** plutôt que `'`.
- Espaces insécables avant `: ; ! ? « »`.
- Guillemets français **« »** par défaut, anglais `"` uniquement en citation imbriquée.
- Tirets longs **—** pour les incises.
