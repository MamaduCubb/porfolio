# 🚀 Comment publier votre portfolio sur GitHub

Le code est prêt. Il vous reste 3 étapes à faire vous-même
car GitHub demande une authentification sécurisée.

---

## ÉTAPE 1 — Créer un jeton d'accès GitHub (token)

1. Allez sur → https://github.com/settings/tokens/new
2. **Note** : écrivez "Portfolio push"
3. **Expiration** : choisissez "No expiration"
4. **Cochez** la case : `repo` (accès complet aux dépôts)
5. Cliquez **"Generate token"**
6. **⚠️ Copiez le token** (il commence par `ghp_...`) — vous ne le verrez qu'une seule fois !

---

## ÉTAPE 2 — Ouvrir un terminal et pousser les fichiers

### Sur Windows :
1. Appuyez sur `Win + R`, tapez `cmd`, puis Entrée
2. Collez ces commandes une par une :

```
cd C:\Users\votre-nom\...\Site web
git push -u origin main
```

Quand GitHub demande le **Username** → tapez : `MamaduCubb`  
Quand GitHub demande le **Password** → collez votre **token** (pas votre mot de passe !)

### Sur Mac / Linux :
```bash
cd "/chemin/vers/Site web"
git push -u origin main
```

---

## ÉTAPE 3 — Activer GitHub Pages (site en ligne gratuit)

1. Allez sur → https://github.com/MamaduCubb/porfolio/settings/pages
2. **Source** : sélectionnez `Deploy from a branch`
3. **Branch** : choisissez `main` → dossier `/ (root)`
4. Cliquez **Save**
5. Attendez 2-3 minutes ⏳

Votre site sera accessible à l'adresse :
👉 **https://mamaducubb.github.io/porfolio**

---

## ✅ Récapitulatif des fichiers publiés

| Fichier | Description |
|---------|-------------|
| `index.html` | Portfolio principal (8 sections) |
| `blog.html` | Blog avec éditeur intégré |
| `CV_ElHadji_Mamadou_THIOUBE.pdf` | Votre CV téléchargeable |
| `images/` | Toutes vos photos |
| `README.md` | Description du projet |

---

*Une fois le site en ligne, pensez à mettre à jour les liens LinkedIn
et GitHub dans votre portfolio avec votre vraie URL.*
