# 🐾 Atlas des animaux

Un site web pour découvrir et écouter des animaux du monde entier, en **français canadien**,
avec une voix naturelle (« Sylvie » dans Microsoft Edge).

## ✨ Ce qu'on peut faire
- Parcourir **130 animaux** avec photos, filtrés par continent.
- Écouter chaque animal grâce au bouton **« Lis-moi »** (les mots se surlignent au fil de la lecture).
- Cliquer une photo pour l'**agrandir** (fiche détaillée).
- Explorer une **carte du monde** : chaque animal a une épingle à son lieu d'origine.

## 🦁 La collection
Les 130 fiches regroupent les espèces des deux grands zoos du Québec —
le **Zoo de Granby** et le **Zoo sauvage de Saint-Félicien** — en plus de quelques
favoris comme le panda roux et le manchot Adélie.

## 🔊 Deux voix d'Amélie au choix
Chaque fiche est racontée par **Amélie** (ElevenLabs), enregistrée en deux générations.
Un sélecteur « Voix » au-dessus de la collection permet de choisir :
- **Amélie classique** — la narration originale (modèle Eleven v2), choisie par défaut.
- **Nouvelle Amélie** — la narration régénérée (modèle Eleven v3).

Le choix est mémorisé d'une visite à l'autre. Si un MP3 manque, le site se replie
sur la meilleure voix française du navigateur (« Sylvie » dans Microsoft Edge).

## 🗂️ Structure
- `index.html` — la page et toute la logique.
- `animals-data.js` — les données des animaux des deux zoos (généré).
- `audio/` — narration « Nouvelle Amélie » (v3) · `audio-v2/` — « Amélie classique » (v2).
- `images/` — photos (Wikimedia Commons) et carte du monde.

## 🚀 Version en ligne
Publié avec GitHub Pages — voir l'onglet **Pages** du dépôt pour l'adresse.
