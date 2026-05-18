# DHL Logistics Services – Site International de Suivi

## 🚀 Déploiement GitHub → Netlify

```bash
git init
git add .
git commit -m "DHL Logistics v2 - all fixes"
git branch -M main
git remote add origin https://github.com/ghoks2004/dhl-logistics.git
git push -u origin main
```
Puis sur netlify.com → Import from GitHub → sélectionner le dépôt → Deploy.

---

## 📧 Activer les emails (EmailJS – GRATUIT)

1. Va sur emailjs.com → Sign Up
2. Crée un Email Service (Gmail)
3. Crée un Template avec: {{to_email}}, {{to_name}}, {{track_num}}, {{content}}, {{fee}}
4. Dans index.html remplace:
   - YOUR_EMAILJS_PUBLIC_KEY → ta clé publique
   - YOUR_SERVICE_ID → ton service ID
   - YOUR_TEMPLATE_ID → ton template ID

---

## ✅ Corrections v2
- Documents CNI/facture : OPTIONNELS avec explication claire
- Impression propre : seul le bordereau s'imprime (pas le site)
- Bordereau professionnel : logo DHL, tableau, numéro de suivi
- 50+ pays dont toute l'Europe
- 4 langues complètes FR/EN/ES/DE
- Emails via EmailJS
- Responsive mobile corrigé

## 📞 Contact: romarthdongmo@gmail.com
