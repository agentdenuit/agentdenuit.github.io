# Site Agent de Nuit

Site statique (HTML, CSS, un peu de JavaScript), publié avec GitHub Pages à l'adresse https://agentdenuit.github.io.

## Démo pour une agence prospect
Modifier uniquement le bloc `window.AGENCE`, tout en haut de `demo/index.html` (nom, initiale, logo, ville, adresse, couleurs).

## Passer à un nom de domaine
1. Créer un fichier `CNAME` à la racine, contenant uniquement le domaine (par exemple `www.exemple.fr`).
2. Remplacer `https://agentdenuit.github.io` par la nouvelle adresse dans : les balises `canonical` et `og:` des pages HTML, `sitemap.xml` et `robots.txt`.
3. Configurer le domaine chez le registraire, puis dans Settings > Pages du dépôt, et cocher « Enforce HTTPS ».

Tous les liens internes du site sont relatifs : rien d'autre à changer.
