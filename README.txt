PEEPZ! — PWA GitHub Pages

À mettre à la racine du dépôt GitHub Pages :
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

IMPORTANT
Le service worker de cette version utilise le réseau en priorité pour index.html.
Cela évite que Safari/Chrome continue d'afficher une ancienne version après une mise à jour.

Mise en ligne :
1. Supprimer/remplacer les anciens fichiers du dépôt.
2. Envoyer les 5 fichiers ci-dessus à la racine.
3. Vérifier Settings > Pages :
   Deploy from a branch / main / root.
4. Attendre la fin du déploiement.
5. Ouvrir l'URL GitHub Pages dans le navigateur.
6. Android Chrome : menu ⋮ > Installer l'application.
7. iPhone Safari : Partager > Sur l'écran d'accueil.

Si une ancienne version reste installée :
- supprimer l'ancienne icône PWA du téléphone,
- ouvrir le site dans le navigateur,
- recharger,
- puis réinstaller.
