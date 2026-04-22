# NYAH PAIE — Site vitrine

Site one-page pour NYAH PAIE, externalisation de la paie pour TPE/PME françaises.

## Ouvrir localement

Double-cliquez sur `index.html` — s'ouvre directement dans le navigateur, aucune installation requise.

## Déploiement

### Netlify (recommandé — gratuit)
1. Créez un compte sur [netlify.com](https://www.netlify.com)
2. Glissez le dossier `nyahpaie-site/` dans l'interface Netlify Drop
3. Le site est en ligne en 30 secondes

### Vercel
1. Installez la CLI : `npm i -g vercel`
2. Dans ce dossier : `vercel --prod`

### OVH / hébergement FTP classique
Uploadez `index.html` et le dossier `assets/` à la racine de votre hébergement via FileZilla ou l'interface OVH.

## Structure
```
nyahpaie-site/
├── index.html       ← site complet (CSS + JS intégrés)
├── assets/
│   └── logo.png     ← logo NYAH PAIE
└── README.md
```

## Personnalisation rapide
- **Couleurs** : variables CSS dans `:root` en haut du `<style>`
- **Textes** : directement dans le HTML
- **Formulaire** : l'action `mailto:contact@nyahpaie.fr` est déjà configurée
