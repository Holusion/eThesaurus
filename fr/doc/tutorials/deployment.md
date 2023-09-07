---
title:  Installation rapide
---

# Déploiement d'une instance eCorpus

 > cette section requiers une certaine familiarité avec des outils de développement usuels : [git](https://git-scm.com/), [npm](https://docs.npmjs.com/).

### Installation rapide

Exemple de création d'une instance minimale à des fins de tests:

    git clone --filter=blob:none git@github.com:Holusion/eCorpus
    cd eCorpus
    npm i
    npm run build-server
    npm start

 > Voir aussi: installation via docker

Dans un navigateur, chargez [localhost:3000](http://localhost:3000).


### Création du premier compte utilisateur

L'application se lance initialement en "mode ouvert", vous permettant la création c'un premier compte utilisateur en ligne de commande :

    curl -XPOST -H "Content-Type: application/json" -d '{"username":"<...>", "password":"<...>", "email":"<...>", "isAdministrator": true}' "http://localhost:3000/api/v1/users"

Par la suite, d'autres comptes pourront être créés via l'interface web.
