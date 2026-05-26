# Axel — Portfolio BTS SIO SISR

Portfolio professionnel créé pour le BTS Services Informatiques aux Organisations, option SISR.

---

## 🚀 Mettre en ligne sur GitHub Pages — Guide complet

### Étape 1 — Créer un compte GitHub

1. Rends-toi sur **https://github.com**
2. Clique sur **Sign up** en haut à droite
3. Remplis le formulaire (username, email, mot de passe)
4. Choisis le plan **Free**
5. Vérifie ton adresse e-mail

---

### Étape 2 — Créer le dépôt (repository)

1. Une fois connecté, clique sur **+** (haut à droite) → **New repository**
2. **Repository name** : `portfolio-sisr` *(ou ton prénom ex: `axel-portfolio`)*
3. Laisse en **Public** *(nécessaire pour GitHub Pages gratuit)*
4. Coche **Add a README file**
5. Clique **Create repository**

---

### Étape 3 — Uploader les fichiers du portfolio

**Option A — Via l'interface web GitHub (la plus simple)**

1. Dans ton dépôt, clique sur **Add file** → **Upload files**
2. Glisse-dépose **tous** les fichiers du dossier `portfolio-sisr` :
   - `index.html`
   - `css/style.css`
   - `js/main.js`
   - `pages/e5.html`
   - `pages/e6.html`
   - `pages/veille.html`
   - `pages/contact.html`
3. ⚠️ **Important** : respecte la structure des dossiers (`css/`, `js/`, `pages/`)
4. Dans le message de commit, écris : `Premier commit — portfolio SISR`
5. Clique **Commit changes**

**Option B — Via Git (ligne de commande)**

```bash
# Installer Git si ce n'est pas fait : https://git-scm.com
git clone https://github.com/TON_USERNAME/portfolio-sisr.git
# Copie tes fichiers dans ce dossier, puis :
cd portfolio-sisr
git add .
git commit -m "Premier commit — portfolio SISR"
git push origin main
```

---

### Étape 4 — Activer GitHub Pages

1. Dans ton dépôt, clique sur **Settings** (onglet en haut)
2. Dans le menu gauche, clique sur **Pages**
3. Sous **Branch**, sélectionne **main** et le dossier **/ (root)**
4. Clique **Save**
5. Attends 1 à 2 minutes, puis une bannière verte apparaît avec ton URL

🎉 Ton portfolio sera accessible à l'adresse :
```
https://TON_USERNAME.github.io/portfolio-sisr/
```

---

### Étape 5 — Personnaliser le contenu

Édite les fichiers HTML pour remplacer les zones de texte génériques :

| Fichier | Ce qu'il faut modifier |
|---|---|
| `index.html` | Ton prénom, ta région, tes infos |
| `pages/e5.html` | Tes vraies situations professionnelles SP1, SP2... |
| `pages/e6.html` | Tes projets cybersécurité réels |
| `pages/veille.html` | Tes articles de veille avec liens |
| `pages/contact.html` | Ton email, LinkedIn, GitHub |

---

### Étape 6 — Activer le formulaire de contact (optionnel)

1. Crée un compte gratuit sur **https://formspree.io**
2. Crée un nouveau formulaire → copie l'ID
3. Dans `pages/contact.html`, remplace `VOTRE_ID` par ton ID Formspree :
   ```html
   <form action="https://formspree.io/f/TON_ID" method="POST">
   ```

---

### Étape 7 — Mettre à jour le portfolio

À chaque modification :
- **Via l'interface web** : clique sur le fichier → icône crayon → modifie → **Commit changes**
- **Via Git** : `git add . && git commit -m "Mise à jour" && git push`

Les changements sont en ligne en **quelques secondes**.

---

## 📁 Structure des fichiers

```
portfolio-sisr/
├── index.html          ← Page d'accueil
├── css/
│   └── style.css       ← Tous les styles
├── js/
│   └── main.js         ← Animations & menu
└── pages/
    ├── e5.html         ← Épreuve E5
    ├── e6.html         ← Épreuve E6
    ├── veille.html     ← Veille technologique
    └── contact.html    ← Formulaire de contact
```

---

## 🎨 Personnalisation rapide

Pour changer la couleur d'accent bleue par une autre couleur, ouvre `css/style.css` et modifie la ligne :
```css
--accent: #4f8ef7;  /* Remplace par ex: #00d4aa (vert), #f97316 (orange) */
```

---

*Portfolio BTS SIO SISR — © 2026*
