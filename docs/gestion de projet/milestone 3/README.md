# Milestone 3

## Retrospective de la revue 2

[Retrospective](retrospective.md)

## Date de la troisième revue

La 25 mars 2025 et installation des produits fini les 31 mars.

Soutenance final du projet: le 8 avril

## Tâches pour le sprint 3

### Embeded software

- [ ] Trouver et corriger tout les *// TODO*
- [ ] Implementer le mode sleep
- [ ] Produire une v1.0 du embeded software pour avoir un prototype viable
- [X] Description du protocol d'envoie de données // **En discuter avec M. Douze**
- [ ] Modification du code pour avoir un système modulaire, flexible et résiliant // En discuter avec M. Douze
- [ ] création de task descriptor pour un code modulable et avec un système plug and play pour les capteurs ??? A discuter ensemble

### Modélisation / impression 3D

- [X] modélisation des différentes pièce 3D
- [ ] impression 3D des pièces
- [ ] montage d'un prototype v1.0
- [ ] test de solidité mécanique
- [ ] test d'étanchéité
- [X] attention au respect de règles et contraintes de modilisation pour l'impression 3D

### PCB(s)

- [X] faire le schéma d'un PCB
- [X] impression du PCB
- [ ] Soudage des composants et mise en place de tests pour verifier le bon fonctionnement

### Site / app web

- [ ] création / rédaction de la page de présentation
- [ ] Rédaction des différentes pages de documentation du site + réorganisation des pages
- [ ] Documentation: documentation sur le site (usage, backend et outils, possibilitées de modification mise à jour)
- [ ] Documentation: tout les capteurs, les libraires, notre montage électronique / PCB
- [ ] Documentation: montage 3D et impression des composants
- [ ] Doc de tuto pour créer et intégrer un nouveau capteurs ou un nouveau objet
- [ ] Ranger les documentation de management du projet dans un sous dossier (c'est pas vraimenet des documentation du projet mais des documents juste pour la parte management)
- [ ] Améliorer la page device pour mieux visualiser les infos, changer les noms, les graphs ...
- [ ] Remplir le bandeau en haut de la page dashboard avec une section pour les notifs et une section pour les erreurs
- [ ] Section de configuration pour une nouvelle device, génération de code, tasks description blocs, insertion dans la base de données
- [ ] Pouvoir exporter les données de la base en données en mode SQL
- [ ] Pouvoir exporter l'historique des données d'un capteur en CSV
- [ ] Modifier le mode de chargement des données de l'interface pour charger chaque historique indépendement (une requette pour charque) et ainsi réduire le signle load time d'un capteur
- [ ] Ajouter une communication websocket pour mettre a jour les données sans recharger la page
- [ ] Utiliser les sockets (si disponible) pour charger les données plutot que des requettes HTTP/S
- [ ] Mode PWA ?

### Flow diagram
- [ ] Correct typo : disable all external **Compoenents**
