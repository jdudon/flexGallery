# Flexbox – 10 exercices (style Material)

### Exercice 01 VF
Objectif : construire une barre d’outils.
- Placez le titre à gauche, un champ de recherche qui s’étire au centre, et trois actions à droite (text/tonal/primary).
- Utilisez un élément « espaceur » qui pousse les actions à droite (ex: `.spacer` avec `flex:1`).
- Gérez l’espacement avec `gap`. Le tout tient sur une ligne.
![exo1](/assets/exo1.png)

### Exercise 01 — EN
Goal: build a toolbar.
- Put the title on the left, a search field that grows in the middle, and three actions on the right (text/tonal/primary).
- Use a spacer element to push actions to the right (`flex:1`).
- Use `gap` for spacing. Everything on a single line.
![exo1](/assets/exo1.png)


### Exercice 02 VF
Objectif : centrer une rangée de boutons.
- Alignez verticalement et horizontalement les boutons.
- Empêchez le retour à la ligne (pas de wrap).
- Conservez un espacement régulier entre boutons.
![exo1](/assets/exo2.png)

### Exercise 02 — EN
Goal: center a row of buttons.
- Align both vertically and horizontally.
- Prevent wrapping (keep all buttons on one line).
- Keep consistent spacing between buttons.
![exo1](/assets/exo2.png)


### Exercice 03 VF
Objectif : créer une grille responsive.
- Affichez 6–9 cartes : 4 par ligne en large, 2 en moyen, 1 en étroit.
- Les cartes doivent avoir une base/largeur minimale et se réorganiser automatiquement (`flex-basis`, `flex-wrap`).
- La rangée d’actions au sein de chaque carte est alignée à droite.
![exo1](/assets/exo3.png)

### Exercise 03 — EN
Goal: create a responsive card grid.
- Show 6–9 cards: 4 per row on wide, 2 on medium, 1 on narrow.
- Cards should have a minimum base/width and wrap (`flex-basis`, `flex-wrap`).
- The action row inside each card is right-aligned.
![exo1](/assets/exo3.png)


### Exercice 04 VF
Objectif : composer un item de liste média.
- Chaque item a: image (gauche), textes (centre), actions (droite).
- Les hauteurs d’items sont cohérentes quelles que soient les longueurs de texte.
- Les actions restent alignées à droite.
![exo1](/assets/exo4.png)

### Exercise 04 — EN
Goal: compose a media list item.
- Each item has: image (left), texts (center), actions (right).
- Item heights remain consistent regardless of text length.
- Actions stay aligned to the right.
![exo1](/assets/exo4.png)


### Exercice 05 VF
Objectif : groupe de filtres (chips).
- Les chips reviennent à la ligne proprement: utilisez le wrap avec espacement régulier entre lignes.
- Les chips restent compacts et alignés sur plusieurs lignes.
- Prévoyez un conteneur avec padding et coins arrondis.
![exo1](/assets/exo5.png)


### Exercise 05 — EN
Goal: filter chips group.
- Chips should wrap neatly with consistent spacing between rows.
- Chips remain compact and aligned across multiple lines.
- Use a padded, rounded container.
![exo1](/assets/exo5.png)


### Exercice 06 VF
Objectif : section prix 3 colonnes.
- Centrez le groupe et donnez une largeur fluide aux cartes.
- Mettez en avant la carte du milieu (élévation/bordure).
- Sur mobile: passez en une seule colonne (ordre conservé).
![exo1](/assets/exo6.png)

### Exercise 06 — EN
Goal: 3-column pricing section.
- Center the group; give cards fluid width.
- Emphasize the middle card (elevation/border).
- On mobile: switch to a single column (keep order).
![exo1](/assets/exo6.png)


### Exercice 07 VF
Objectif : layout « split login » avec panneau de présentation/inscription.
- Deux panneaux de même importance : **Présentation/Inscription** (gauche) et **Formulaire de connexion** (droite).
- Le panneau gauche contient : un titre, un court texte et un **bouton d’inscription** avec icône (CTA).
- Le panneau droit contient : email, mot de passe, et un bouton **Se connecter**.
- Les deux panneaux doivent occuper chacun 50% en large (`flex:1`), avec une hauteur minimale de **60vh**.
- **Responsive** : sur mobile, passer en colonne (panneau Présentation au-dessus du formulaire).
![exo1](/assets/exo7.png)

### Exercise 07 — EN
Goal: split login layout with a presentation/sign‑up panel.
- Two equally important panels: **Presentation/Sign‑up** (left) and **Login form** (right).
- Left panel includes: a heading, a short paragraph, and a **sign‑up CTA button** with an icon.
- Right panel includes: email, password, and a **Sign in** button.
- Both panels should take 50% width on large screens (`flex:1`), with a minimum height of **60vh**.
- **Responsive**: on mobile, stack vertically (Presentation above the form).
![exo1](/assets/exo7.png)

### Exercice 08 VF
Objectif : rangée de widgets de dashboard.
- 4 petites cartes qui se réorganisent selon la largeur (4 → 2×2 → 1×4).
- Alignez et étirez correctement pour des hauteurs homogènes.
- Conservez un espacement régulier entre tous les widgets.
![exo1](/assets/exo8.png)

### Exercise 08 — EN
Goal: dashboard widget row.
- 4 small cards that reflow with screen width (4 → 2×2 → 1×4).
- Align and stretch properly for uniform heights.
- Keep consistent spacing between all widgets.
![exo1](/assets/exo8.png)


### Exercice 09 VF
Objectif : mini-Kanban 3 colonnes.
- Trois colonnes de même largeur; chaque colonne empile des cartes.
- Le conteneur s’adapte et garde des espacements constants.
- Les titres de colonnes restent alignés en haut.
![exo1](/assets/exo9.png)

### Exercise 09 — EN
Goal: mini-Kanban with 3 columns.
- Three equal-width columns; each stacks cards vertically.
- The container adapts and keeps consistent spacing.
- Column titles stay aligned to the top.
![exo1](/assets/exo9.png)


### Exercice 10 VF
Objectif : footer multi-colonnes.
- 4 colonnes en ligne; sur mobile, basculer en pile verticale.
- Espacements internes réguliers; titres mis en valeur.
- Bandeau inférieur: logo/titre à gauche, icônes à droite.
![exo1](/assets/exo10.png)

### Exercise 10 — EN
Goal: multi-column footer.
- 4 columns in a row; on mobile, stack vertically.
- Keep internal spacing consistent; emphasize headings.
- Bottom bar: logo/title on the left, icons on the right.
![exo1](/assets/exo10.png)

# 📎 Annexes – Icônes, Polices, Couleurs & Variables CSS

## 🎨 1) Icônes Material (Google Fonts)

**Ajout dans le `<head>` :**
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```

**Utilisation dans le HTML :**
```html
<span class="material-icons">help</span>
<span class="material-icons" aria-hidden="true">upload</span>
```

**Où les trouver :**  
🔗 [Material Icons – Google Fonts](https://fonts.google.com/icons)

> 💡 Astuce : les icônes s’alignent comme du texte. Pour les redimensionner, utilisez simplement `font-size` sur `.material-icons` (ex. `18px`, `24px`, `32px`…).

---

## 🖋️ 2) Polices

**Police utilisée dans la base du projet :**
```
system-ui, -apple-system, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Arial, sans-serif
```

**Option “Material Design” : ajouter Roboto**
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: Roboto, system-ui, -apple-system, "Segoe UI", Ubuntu, "Helvetica Neue", Arial, sans-serif;
  }
</style>
```

**Ressource :**  
🔗 [Roboto sur Google Fonts](https://fonts.google.com/specimen/Roboto)

---

## 🎨 3) Palette de couleurs (définie dans `base.css`)

| Rôle             | Variable           | Valeur       | Utilisation typique |
|------------------|--------------------|--------------|---------------------|
| Fond global      | `--bg`             | `#f7f7fb`    | Arrière-plan général |
| Surface          | `--surface`        | `#ffffff`    | Cartes, toolbars     |
| Texte principal  | `--text`           | `#1b1b1f`    | Contenu principal    |
| Texte atténué    | `--muted`          | `#6b7280`    | Sous-titres, labels  |
| Couleur primaire | `--primary`        | `#2962ff`    | Boutons, liens       |
| Texte primaire   | `--primary-ink`    | `#ffffff`    | Texte sur fond bleu  |

**Couleurs supplémentaires utilisées :**
- Tonal button → `rgba(41, 98, 255, 0.1)`
- Ombres → `0 2px 6px rgba(0,0,0,.08), 0 8px 24px rgba(0,0,0,.06)`
- Rayon par défaut → `--radius: 16px`

---

## 🧩 4) Variables CSS – Définition & Utilisation

Les **variables CSS** (ou *Custom Properties*) permettent de centraliser des valeurs (couleurs, espacements, tailles…) pour faciliter la maintenance et la cohérence visuelle.

### 📘 Déclaration (souvent dans `:root`)
```css
:root {
  --primary: #2962ff;
  --radius: 16px;
  --gap: 12px;
}
```

### 💡 Utilisation
```css
.btn.primary {
  background: var(--primary);
  border-radius: var(--radius);
  margin-right: var(--gap);
}
```

### 🎨 Thématisation locale
Vous pouvez redéfinir une variable dans un composant ou un conteneur spécifique :
```css
.theme-rose {
  --primary: #e91e63;
  --bg: #fff7fb;
}
```
```html
<div class="theme-rose">
  <!-- Tous les éléments à l’intérieur utiliseront ces nouvelles valeurs -->
</div>
```

### 🪄 Valeur de repli (fallback)
Si la variable n’est pas définie, une valeur par défaut peut être utilisée :
```css
.btn.primary {
  background: var(--primary, #007bff);
}
```

---

## 🌙 5) Exemple – Passage en mode sombre (Dark Mode)
```css
:root {
  --bg: #f7f7fb;
  --surface: #ffffff;
  --text: #1b1b1f;
}
.dark {
  --bg: #0b0b10;
  --surface: #13131a;
  --text: #f4f4f5;
}
```
```html
<body class="dark">
  <!-- retirer la classe “dark” pour repasser en clair -->
</body>
```

---

## 🧱 6) Ombres & coins arrondis

Ces propriétés donnent l’aspect “Material” :
```css
:root {
  --radius: 16px;
  --shadow: 0 2px 6px rgba(0,0,0,.08), 0 8px 24px rgba(0,0,0,.06);
}
.card {
  border-radius: var(--radius);
  box-shadow: var(--shadow);
}
```

---

> 💬 **En résumé :**
> - Les *variables CSS* permettent de créer des thèmes et de modifier les styles sans tout réécrire.  
> - Les *Material Icons* et *Roboto* sont gratuits et faciles à intégrer via Google Fonts.  
> - Les couleurs et les ombres sont centralisées dans `base.css` pour garantir une cohérence sur tous les exercices.