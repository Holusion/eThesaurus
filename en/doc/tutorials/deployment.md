---
title:  Quick setup
---

# Deploying an eCorpus instance

 > this section requiers some familiarity with common development tools: [git](https://git-scm.com/), [npm](https://docs.npmjs.com/).


### Quick setup

Creating a minimal instance for testing purposes:

    git clone --filter=blob:none
    cd eCorpus
    npm i
    npm run build-server
    npm start

 > also: docker install

In a browser, load [localhost:3000](http://localhost:3000).


### Create the first user account

The application initially launches in "open mode", allowing you to create a first user account from the command line:

    curl -XPOST -H "Content-Type: application/json" -d '{"username":"<...>", "password":"<...>", "email":"<...>", "isAdministrator": true}' "http://localhost:3000/api/v1/users"

Subsequently, other accounts can be created via the web interface.
