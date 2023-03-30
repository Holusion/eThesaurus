
# site vitrine eThesaurus

eThesaurus est un projet d’histoire de l’art et des techniques, porté par une équipe d’universitaires français et belges, de conservateurs de musées et la société Holusion, spécialiste de l’affichage digital innovant.

Site hebergé sur [ethesaurus.holusion.com](https://ethesaurus.holusion.com).


## Développement

### Mise en route

Pour tester et construire ce site localement, il faut disposer d'une installation [ruby](https://rvm.io/) et de [git](https://git-scm.com/).

    git clone git@github.com:Holusion/eThesaurus.git
    cd eThesaurus

    gem install bundler
    bundle
    bundle exec jekyll serve

Puis explorez votre copie locale du site sur `http://localhost:4000`.

### Organisation

Le site est séparé en dossiers par langue : `fr` et `en`. 
Les pages qui doivent se renvoyer l'une vers l'autre doivent avec le même nom de fichier. 
Le nom de fichier est choisi généralement en anglais et sans espaces ou caractères spéciaux. 

Exemple:

    \- fr/
      \- about.html # title: "à Propos"
    \- en/
      \- about.html # title: "About"

Toutes les pages présentes dans le dossier `items` sont automatiquement ajoutées à la **collection** : la liste des objets présentés sur le site.
