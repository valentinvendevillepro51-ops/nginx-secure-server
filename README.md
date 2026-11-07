# nginx-secure-server
Serveur web Nginx exécuté avec Docker sur Ubuntu Server (VM), avec plusieurs
sites, HTTPS, pare-feu et accès SSH par clé.
Projet personnel réalisé pendant ma 1re année de bachelor informatique (ESGI).

## Environnement

- Ubuntu Server dans une VM (QEMU/virt-manager)
- Docker
- Nginx (image officielle, dans un conteneur)

## Avancement

- [ ] Installation de Docker sur la VM
- [ ] Nginx lancé dans un conteneur avec `docker run`
- [ ] Deux sites avec virtual hosts (configuration montée en volume)
- [ ] HTTPS avec certificat auto-signé et redirection HTTP vers HTTPS
- [ ] Pare-feu `ufw`
- [ ] SSH par clé
- [ ] (optionnel) Reverse proxy
- [ ] (optionnel) Certificat Let's Encrypt, avec un nom de domaine public

## Détail des étapes

(pour chaque étape terminée : ce que j'ai fait, les commandes utilisées,
une capture d'écran du résultat)

## Problèmes rencontrés

(erreurs et solutions)

## Ce que j'ai appris

(à compléter à la fin)

## Pistes d'amélioration

- Passer à Docker Compose pour gérer le conteneur dans un fichier.
