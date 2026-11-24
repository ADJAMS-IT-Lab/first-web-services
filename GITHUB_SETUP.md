# Publication GitHub Pages — FWS_Libs
1. Sur https://github.com/organizations/ADJAMS-IT-Lab/repositories/new (ou bouton New de l'organisation), créer le dépôt public `mobile-ready-checker` avec propriétaire ADJAMS-IT-Lab.
2. Décompresser le ZIP et uploader son contenu, pas le dossier parent. Vérifier index.html et assets/ à la racine et conserver .nojekyll. Commit sur main.
3. Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
4. Attendre le déploiement (Actions), puis Visit site. URL attendue https://adjams-it-lab.github.io/mobile-ready-checker/ . Activer Enforce HTTPS si disponible.
5. Dans About du dépôt, saisir la description et l'URL publique. Topics: responsive-design, mobile-testing, javascript, github-pages, fws-libs.
6. Pour un portail commun, créer séparément le dépôt public `first-web-services`, uploader les fichiers du ZIP portail et appliquer la même procédure. URL attendue https://adjams-it-lab.github.io/first-web-services/ . Chaque future application peut avoir son dépôt et son chemin propre.
7. Si Pages est absent, vérifier les droits administrateur et la politique Pages de l'organisation. Ne pas saisir un domaine personnalisé sauf si vous en possédez un.

Documentation officielle : https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

Vérification : syntaxe JS contrôlée ; navigation Chromium bloquée dans l'environnement de préparation. Les visuels et la vidéo sont illustratifs. Tester le site publié avant diffusion.
