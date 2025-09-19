# 🚀 Site connecté à Meta (Facebook)

Ce projet est un site HTML simple intégrant :
- Meta Pixel (Facebook Pixel)
- Bouton de connexion Facebook (Facebook Login)
- Page Plugin Facebook

## ⚡ Déploiement sur Vercel

1. Forkez ou clonez ce dépôt.
2. Connectez votre repo GitHub à [Vercel](https://vercel.com/).
3. Vercel détectera automatiquement `index.html` et utilisera `vercel.json` pour la configuration.
4. L’URL de votre site sera de la forme :
   ```
   https://votre-projet.vercel.app
   ```

## 🔧 Configuration Meta

- Remplacez `YOUR_APP_ID` par l’ID de votre app Facebook (Meta for Developers).
- Remplacez `YOUR_PIXEL_ID` par l’ID de votre Pixel (Meta Business Suite).
- Ajoutez l’URL de production dans **Valid OAuth Redirect URIs** (Meta for Developers).

## 📂 Structure du projet
```
/ (racine du repo)
├── index.html       # Site principal
├── vercel.json      # Configuration Vercel
└── README.md        # Documentation
```
---
👨‍💻 Auteur : Votre Nom
