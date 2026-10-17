# Deepcore Research – Site web bilingue

Site statique bilingue (FR / EN) pour **Deepcore Research**.

## Structure

```
deepcore-research/
├── index.html
├── about.html
├── research.html          ← Page Recherche avec icônes
├── contact.html           ← Formulaire de contact
├── favicon.svg
├── css/style.css
├── images/
│   ├── logo.png           ← PLACEZ VOTRE LOGO ICI
│   ├── logo.svg           ← Logo de secours (SVG)
│   └── icons/             ← Icônes des domaines de recherche
│       ├── quantum.svg
│       ├── photonics.svg
│       ├── humanoids.svg
│       ├── defense.svg
│       ├── interconnects.svg
│       ├── materials.svg
│       └── other.svg
├── en/
│   ├── index.html
│   ├── about.html
│   ├── research.html
│   └── contact.html
└── README.md
```

## Installation rapide (GitHub Pages)

1. Créez un dépôt GitHub.
2. Uploadez tous les fichiers de ce dossier.
3. **Important** : placez votre logo dans `images/logo.png` (format PNG recommandé).
4. Settings → Pages → Source : `main` / root.
5. Votre site sera en ligne.

## Formulaire de contact

Utilise Formspree (gratuit).

1. Créez un compte sur [formspree.io](https://formspree.io)
2. Créez un formulaire et récupérez l’ID
3. Remplacez `YOUR_FORM_ID` dans `contact.html` et `en/contact.html`

## Contenu

- Recherche spécialisée DeepTech
- Domaines : quantique, photonique, humanoïdes, défense, connectique, matériaux avancés
- Section Souveraineté technologique
- Favicon + icônes SVG pour chaque domaine
- Formulaire de contact
