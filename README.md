# DHL Logistics Services – Site de Suivi International

Site de tracking et gestion de colis professionnel, style DHL.

## 🚀 Déploiement sur Netlify via GitHub

### Étape 1 – Pousser sur GitHub
```bash
git init
git add .
git commit -m "DHL Logistics Services - initial commit"
git branch -M main
git remote add origin https://github.com/VOTRE_USERNAME/dhl-logistics.git
git push -u origin main
```

### Étape 2 – Connecter à Netlify
1. Allez sur [netlify.com](https://netlify.com) → "Add new site" → "Import an existing project"
2. Connectez votre compte GitHub
3. Sélectionnez le dépôt `dhl-logistics`
4. Laissez les paramètres par défaut (le `netlify.toml` s'occupe de tout)
5. Cliquez **Deploy site**

Votre site sera en ligne en ~60 secondes sur une URL `xxx.netlify.app`.

---

## ✨ Fonctionnalités

| Fonctionnalité | Détail |
|---|---|
| 🌍 Multilingue | FR / EN / ES / DE (dynamique, par bouton) |
| 📦 Formulaire expédition | 5 étapes : Expéditeur, Colis, Documents, Vitesse, Paiement |
| 📡 Suivi en temps réel | Numéro de suivi, statut, historique des événements |
| 🗺️ Navigation GPS | Google Maps, Waze, Apple Maps (liens automatiques) |
| 🚚 Espace Coursier | Envoi de mises à jour de position + statut |
| 📄 Factures | Générées automatiquement avec code-barres |
| 🖨️ Impression | Étiquette + facture imprimables |
| 💳 Paiements | MTN MoMo, Orange Money, Carte, Cash |

---

## 📁 Structure

```
/
├── index.html       ← Site complet (HTML + CSS + JS en un seul fichier)
├── netlify.toml     ← Configuration Netlify
└── README.md        ← Ce fichier
```

## 📧 Contact
romarthdongmo@gmail.com
