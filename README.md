# 🇩🇿 Voyage Algérie 2026

PWA installable sur iPhone et Android. Programme complet Alger · Cherchell · Bou Saâda avec UV, météo et check-list.

## Déploiement sur GitHub Pages (5 minutes)

1. Crée un repo GitHub (ex: `voyage-algerie`)
2. Upload tous les fichiers de ce dossier
3. Va dans **Settings → Pages → Source → main branch → / (root)**
4. Ton URL sera : `https://TON-PSEUDO.github.io/voyage-algerie`

## Installer sur iPhone

1. Ouvre l'URL dans **Safari** (pas Chrome)
2. Appuie sur l'icône **Partager** (carré avec flèche)
3. Scroll → **"Sur l'écran d'accueil"**
4. L'app apparaît avec le logo de l'équipe d'Algérie ✅

## Fonctionnalités

- ✅ Installable sur iPhone (PWA)
- ✅ Fonctionne hors connexion (service worker)
- ✅ Check-list sauvegardée localement
- ✅ Navigation par onglets (Alger / Cherchell / Bou Saâda / Bronzage / Check-list)
- ✅ UV heure par heure + températures ressenties
- ✅ Programme jour par jour complet

## Structure

```
algerie-app/
├── index.html          ← App principale
├── manifest.json       ← Config PWA
├── sw.js               ← Service worker (offline)
└── icons/
    ├── icon-192.png    ← Logo Algérie
    ├── icon-512.png
    └── apple-touch-icon.png
```
