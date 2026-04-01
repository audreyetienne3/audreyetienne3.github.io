# Site académique — Audrey Etienne

Site personnel construit avec [Quarto](https://quarto.org/) et déployé via GitHub Pages.

## Démarrage rapide

### 1. Cloner et personnaliser

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

### 2. Ajouter tes fichiers

- **Photo** : place ta photo dans `images/photo.jpg` (carrée, ~400×400px min)
- **CV** : place ton PDF sous `cv-audrey-etienne.pdf` à la racine
- Modifie les `YOUR-USERNAME`, `YOUR-REPO-NAME`, `YOUR-ID` dans `_quarto.yml` et `index.qmd`

### 3. Preview local

```bash
quarto preview
```

### 4. Déployer

```bash
git add -A
git commit -m "Initial site"
git push origin main
```

Le GitHub Action se charge du build et du déploiement automatique.

### 5. Activer GitHub Pages

Dans ton repo GitHub : **Settings → Pages → Source → GitHub Actions**.

## Structure

```
├── _quarto.yml          # Configuration du site
├── index.qmd            # Page d'accueil / bio
├── research.qmd         # Publications & working papers
├── teaching.qmd         # Enseignement
├── cv.qmd               # CV (embed PDF)
├── styles.css           # Style personnalisé
├── images/              # Photo de profil, etc.
├── cv-audrey-etienne.pdf
└── .github/workflows/   # Déploiement automatique
```
