# NYAH PAIE — Site vitrine

Site vitrine one-page pour NYAH PAIE, externalisation de la paie pour TPE/PME françaises.

**URL de production :** https://nyahpaie.fr
**Hébergement :** GitHub Pages (gratuit)
**Nom de domaine :** IONOS (nyahpaie.fr)

---

## Structure des fichiers

```
nyahpaie-site/
├── index.html                      ← site complet (HTML + CSS + JS en un seul fichier)
├── mentions-legales.html           ← page mentions légales
├── cgv.html                        ← conditions générales de vente
├── politique-confidentialite.html  ← politique de confidentialité (RGPD)
├── sitemap.xml                     ← plan du site pour Google
├── robots.txt                      ← instructions pour les moteurs de recherche
├── CNAME                           ← lie le domaine nyahpaie.fr à GitHub Pages
├── assets/
│   └── logo.png                    ← logo NYAH PAIE
└── README.md
```

---

## Déploiement

Le site est hébergé sur **GitHub Pages** via le dépôt :
`https://github.com/Nyahpaie/nyahpaie-site`

Chaque `git push` sur la branche `master` met à jour le site automatiquement en 1 à 2 minutes.

```bash
git add .
git commit -m "Description du changement"
git push origin master
```

---

## Formulaire de contact

Le formulaire utilise **Web3Forms** (web3forms.com).
- Les messages sont reçus sur : contact@nyahpaie.fr
- La clé d'accès est dans `index.html` (champ `access_key` du formulaire)
- Aucun compte à maintenir, la clé est permanente

---

## DNS (IONOS)

Le domaine nyahpaie.fr pointe vers GitHub Pages via ces enregistrements :

| Type  | Nom | Valeur               |
|-------|-----|----------------------|
| A     | @   | 185.199.108.153      |
| A     | @   | 185.199.109.153      |
| CNAME | www | nyahpaie.github.io   |

Les enregistrements Microsoft (MX, TXT SPF, CNAME autodiscover) sont liés à la messagerie contact@nyahpaie.fr — **ne pas toucher**.

---

## SEO

- Meta description, titre, balises H1/H2/H3 optimisés
- Open Graph configuré (partage LinkedIn/Facebook)
- Schema.org (données structurées pour Google)
- Canonical URL définie
- Sitemap soumis à Google Search Console (à faire)
- **Manquant :** image og:image pour les partages sociaux

---

## Personnalisation

- **Couleurs** : variables CSS dans `:root` au début de `<style>` dans `index.html`
- **Textes** : directement dans le HTML
- **Formulaire** : clé Web3Forms dans le champ `access_key` (ne pas modifier)
- **Pages légales** : modifier directement les fichiers HTML correspondants

---

## Informations légales enregistrées

- **Société :** NYAH PAIE — SAS
- **SIREN :** 103 747 119 | **RCS :** R.C.S. Melun
- **SIRET :** 103 747 119 00016
- **TVA :** FR88103747119
- **Présidente :** EGNAKOU Akassi Nadège (NIANZOU)
- **Adresse :** 25 Route de Chalmaison, 77157 Everly
- **Tél :** 07 52 62 32 36 | **Email :** contact@nyahpaie.fr
