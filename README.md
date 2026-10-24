# Site de la MSP Le Colibri – Merville

Fichiers : `index.html` (site complet, images incluses), `robots.txt`, `sitemap.xml`.

## 1. Mise en ligne gratuite sur GitHub Pages
1. Créer un compte sur github.com (idéalement au nom de la MSP, ex. `msp-lecolibri`).
2. **New repository** → nom : `msp-merville` → **Public** → Create.
3. **Add file → Upload files** : déposer `index.html`, `robots.txt`, `sitemap.xml` → **Commit changes**.
4. **Settings → Pages** → Source : *Deploy from a branch* → `main` / `(root)` → **Save**.
5. Après 1–2 minutes : `https://<compte>.github.io/msp-merville/`.
6. Dans `robots.txt` et `sitemap.xml`, remplacer `VOTRE-COMPTE` par le nom du compte GitHub.

## 2. Être trouvé sur Google
1. **Google Search Console** (search.google.com/search-console) : ajouter l'adresse du site, valider la propriété, puis soumettre `sitemap.xml` et demander l'indexation de la page d'accueil.
2. **Fiche Google Business Profile** (business.google.com) : créer/revendiquer la fiche « Maison de Santé Le Colibri » et y mettre le lien du site. C'est ce qui fait apparaître la MSP dans Google Maps et les recherches locales (« maison de santé Merville »).
3. **Liens entrants** : demander à la mairie (page Santé), à la CPTS Cœur des Flandres et à la FEMAS d'ajouter un lien vers le site.
4. Facultatif : **nom de domaine** propre (ex. `msp-merville.fr`, ~10 €/an chez OVH, Gandi…), relié à GitHub Pages via *Settings → Pages → Custom domain*.

Le site contient déjà les balises utiles au référencement (titre, description, données structurées « MedicalClinic » avec adresse, téléphone et horaires).

## À compléter
- Liens Doctolib exacts : dans `index.html`, section `const TEAM`, remplacer `d:DOCTOLIB` par l'URL de chaque fiche.
- Mentions légales (lien en pied de page).
- Téléphone de Mme Hortense Revillion (ostéopathe), si souhaité.
