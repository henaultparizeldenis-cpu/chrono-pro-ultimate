# 🚀 Guide de Déploiement GitHub

## Étape 1 : Créer un compte GitHub (si tu n'en as pas)

1. Va sur https://github.com
2. Clique "Sign up"
3. Crée ton compte

## Étape 2 : Créer un nouveau repository

1. Une fois connecté, clique sur le **+** en haut à droite
2. Sélectionne **"New repository"**
3. Remplis :
   - **Repository name** : `chrono-pro-ultimate` (ou autre nom)
   - **Description** : "Professional workout timer with gamification"
   - **Public** (laisse coché)
   - ✅ Coche **"Add a README file"**
   - Clique **"Create repository"**

## Étape 3 : Upload les fichiers

### Option A : Via l'interface web (plus simple)

1. Sur la page de ton nouveau repo, clique **"Add file"** → **"Upload files"**
2. Glisse-dépose ces fichiers :
   - `index.html` (le fichier principal)
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. En bas, écris "Initial commit" dans le message
4. Clique **"Commit changes"**

### Option B : Via Git (ligne de commande)

```bash
# Clone ton repo (remplace TON-USERNAME et TON-REPO)
git clone https://github.com/TON-USERNAME/chrono-pro-ultimate.git
cd chrono-pro-ultimate

# Copie les fichiers dedans
# (copie index.html, README.md, LICENSE, .gitignore)

# Ajoute les fichiers
git add .

# Commit
git commit -m "Initial commit - Chrono Pro Ultimate"

# Push
git push origin main
```

## Étape 4 : Activer GitHub Pages

1. Dans ton repository, clique sur **"Settings"** (en haut)
2. Dans le menu gauche, clique **"Pages"**
3. Sous "Source" :
   - **Branch** : sélectionne `main`
   - **Folder** : laisse `/ (root)`
4. Clique **"Save"**
5. **Attends 2-3 minutes** ⏳

## Étape 5 : Accéder à ton app !

Ton app sera disponible à :
```
https://TON-USERNAME.github.io/chrono-pro-ultimate/
```

Exemple : si ton username est `denis-fitness`, l'URL sera :
```
https://denis-fitness.github.io/chrono-pro-ultimate/
```

## 🎉 C'est fait !

Tu as maintenant :
- ✅ Une app hébergée gratuitement
- ✅ Une URL publique à partager
- ✅ Mise à jour facile (upload nouveau fichier)
- ✅ Installable comme PWA sur mobile

## 📱 Installer sur mobile

1. Ouvre l'URL sur ton Pixel 9 (Chrome)
2. Menu ⋮ → "Ajouter à l'écran d'accueil"
3. L'icône apparaît et fonctionne comme une vraie app !

## 🔄 Mettre à jour l'app

Pour modifier l'app plus tard :

**Via interface web** :
1. Va dans ton repo GitHub
2. Clique sur `index.html`
3. Clique l'icône crayon ✏️ (Edit)
4. Fais tes modifications
5. "Commit changes"
6. L'app se met à jour automatiquement en 1-2 minutes !

**Via Git** :
```bash
# Modifie index.html localement
# Puis :
git add index.html
git commit -m "Update: nouvelle fonctionnalité"
git push origin main
```

## 🌐 Domaine personnalisé (optionnel)

Si tu veux un domaine custom genre `chronopro.com` :

1. Achète un domaine (OVH, Google Domains, etc.)
2. Dans GitHub Settings → Pages → Custom domain
3. Entre ton domaine
4. Configure les DNS chez ton hébergeur

## 🔥 Tips

- GitHub Pages est **gratuit** et **illimité**
- L'app fonctionne **100% offline** après premier chargement
- Partage ton URL avec qui tu veux !
- Le code reste **open source** (d'autres peuvent le voir)

## ❓ Problèmes courants

**"Site non trouvé"** :
- Attends 5 minutes après activation de Pages
- Vérifie que le fichier s'appelle bien `index.html`
- Vérifie que Pages est activé (Settings → Pages)

**"App ne se met pas à jour"** :
- Vide le cache du navigateur (Ctrl+Shift+R)
- Attends 2-3 minutes après le push

## 🆘 Besoin d'aide ?

Contacte-moi ou ouvre une issue sur GitHub !

---

**Bon déploiement ! 🚀💪**
