# Rayhane — Préparation ENA Sénégal, Cycle Direct B

Application web progressive (PWA), conçue pour être publiée sur GitHub Pages puis installée sur Android.

## Fichiers
- `index.html` : interface bleu clair et blanc.
- `content.json` : les 22 cours, enjeux, axes d'action, limites, exemples, plans de dissertation et QCM corrigés.
- `app.js` : navigation, recherche, favoris, progression, QCM et simulation.
- `manifest.json`, `sw.js`, `assets/icon.svg` : installation et cache hors connexion.

## Publication GitHub Pages
1. Crée un nouveau dépôt GitHub nommé `Rayhane-ENA-Cycle-Direct-B` (ne remplace pas le dépôt Bolo).
2. Téléverse le contenu de ce dossier à la racine du dépôt.
3. Dans **Settings → Pages**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Attends la publication et ouvre l’adresse GitHub Pages depuis Chrome sur Android.
5. Menu Chrome `⋮` → **Ajouter à l’écran d’accueil** ou **Installer l’application**.

## APK
GitHub Pages installe une PWA, pas un APK natif. Pour obtenir un APK, il faudra ensuite envelopper cette PWA avec un outil Android/PWA adapté et vérifier la signature. Ne télécharge pas d'APK depuis une source inconnue.

## Important
Les cours sont des fiches de travail structurées. Pour une dissertation de concours, enrichis-les avec les textes officiels, les données chiffrées les plus récentes et les exemples d'actualité vérifiés. La fiche « Laïcité » doit être traitée selon le droit et le contexte sénégalais, sans importer automatiquement les règles d'autres pays.
