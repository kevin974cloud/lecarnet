# Le Carnet — Instructions de déploiement sur GitHub Pages

## Fichiers inclus
- `index.html` — l'application complète
- `manifest.json` — configuration PWA
- `sw.js` — service worker (mode hors-ligne)
- `icon-192.png` / `icon-512.png` — icônes de l'app

## Étapes pour déployer sur GitHub Pages

### 1. Créer un compte GitHub
Rends-toi sur [github.com](https://github.com) et crée un compte gratuit si tu n'en as pas.

### 2. Créer un nouveau dépôt
- Clique sur le **+** en haut à droite → **New repository**
- Nom : `lecarnet` (ou ce que tu veux)
- Laisse tout le reste par défaut
- Clique **Create repository**

### 3. Uploader les fichiers
- Dans ton nouveau dépôt, clique **uploading an existing file**
- Glisse-dépose les 6 fichiers de ce dossier
- Clique **Commit changes**

### 4. Activer GitHub Pages
- Va dans **Settings** (onglet en haut du dépôt)
- Dans le menu gauche, clique **Pages**
- Sous **Source**, sélectionne **Deploy from a branch**
- Branch : **main** / Folder : **/ (root)**
- Clique **Save**

### 5. Accéder à l'app
Au bout de ~1 minute, ton app sera disponible à :
`https://TON-PSEUDO.github.io/lecarnet/`

GitHub t'envoie un lien dans la section Pages dès que c'est prêt.

## Installer sur ton iPhone
1. Ouvre le lien dans **Safari** (pas Chrome)
2. Appuie sur l'icône **Partager** (carré avec flèche vers le haut)
3. Sélectionne **Sur l'écran d'accueil**
4. Confirme → L'app apparaît comme une vraie app !

## Installer sur Android
1. Ouvre le lien dans **Chrome**
2. Le navigateur propose automatiquement **Installer l'app**
3. Sinon : menu ⋮ → **Ajouter à l'écran d'accueil**
