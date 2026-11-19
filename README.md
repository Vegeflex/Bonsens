# BONSENS — première version fonctionnelle

BONSENS est une PWA statique, bilingue français/anglais, conçue pour être hébergée gratuitement sur un service de fichiers statiques.

## Fonctionnalités incluses
- Comparateur de prix unitaires (masse, volume, unités).
- Calculateur de réductions.
- Estimation du coût annuel d'une dépense récurrente.
- Estimation du coût électrique d'un appareil.
- Historique et total des économies enregistrés localement.
- Interface responsive et installable comme PWA.
- Mise en cache hors ligne après la première visite.
- Confidentialité locale : pas de compte, pas de connexion bancaire, pas de backend.

## Lancer en local
Ouvre un terminal dans ce dossier et lance un serveur statique, par exemple :
`python -m http.server 8000`
Puis visite `http://localhost:8000`.

Pour tester l'installation PWA et le service worker, utilise localhost ou un hébergement HTTPS. L'ouverture directe du fichier `index.html` ne permet pas toutes les fonctions PWA.

## Publication gratuite (exemple Cloudflare Pages)
1. Créer un compte GitHub et un compte Cloudflare.
2. Créer un dépôt GitHub et y envoyer le contenu de ce dossier.
3. Dans Cloudflare Pages, importer le dépôt.
4. Choisir un projet de site statique : pas de commande de build, dossier de sortie `/`.
5. Déployer et tester le lien `*.pages.dev`.

Les offres gratuites ont des conditions et limites qui peuvent changer. Vérifier les conditions au moment du déploiement.

## Avant une diffusion commerciale
- Vérifier le nom BONSENS, les marques et les domaines disponibles.
- Faire relire les traductions et tester les calculs.
- Ajouter un vrai contact éditeur et les mentions légales adaptées au pays de publication.
- Rédiger une politique de confidentialité complète si des outils tiers, de l'analytique, de la publicité ou des comptes sont ajoutés.
- Mettre en place les consentements requis avant tout traceur non essentiel.
- Les revenus publicitaires/affiliation ne sont pas inclus dans cette version.
- Cette application ne récupère pas automatiquement les prix des magasins : les comparaisons sont manuelles.
