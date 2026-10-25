# Eden CV Studio

Générateur de CV et de lettres de motivation en HTML, CSS et JavaScript, sans étape de compilation.

## Tester localement

Ouvrir `index.html` dans un navigateur moderne. Les fonctions qui dépendent d'un environnement d'IA externe peuvent ne pas fonctionner sans le service correspondant.

## Publication GitHub Pages

Le workflow `.github/workflows/pages.yml` publie automatiquement le site à chaque push sur `main`.

1. Ajouter le fichier `index.html` à la racine du dépôt.
2. Dans **Settings → Pages**, choisir **GitHub Actions** comme source si GitHub demande une configuration initiale.
3. Attendre la réussite du workflow **Deploy GitHub Pages**.
4. Ouvrir https://tshibandachris.github.io/eden-cv-studio/.

## Confidentialité

Les informations saisies sont traitées côté navigateur et la sauvegarde locale utilise le stockage du navigateur. Éviter d'utiliser des données personnelles réelles pendant les tests sur un appareil partagé. Une publication Pages rend le code du site accessible publiquement puisque ce dépôt est public.
