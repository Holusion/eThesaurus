---
title: Story Edition
---
# Voyager Story

## Editeur de scènes pour Voyager

<style>
  h1, h3{
    color: var(--color-primary-light)
  }
  .ff-button.ff-control{
    width: 150px;
  }
  .ff-button.ff-control.ff-disabled{
    color: white !important;
  }
  .ff-button.ff-control.ff-disabled > .ff-icon{
    fill: white !important;
  }
  .ff-button.ff-control.rounded{
    width: 40px;
    height: 40px;
    border-radius: 20px;
  }
  .inline{
    display:inline-block;
  }
  li{
    margin: 0.2rem;
    list-style: none;
  }
  li a{
    color: var(--color-light);
    text-decoration: none;
  }
  li a:hover{
    color: white;
  }
  img{
    max-width: 100%;
  }
</style>

### Editez votre scène

 - {% include button.html name="pose" %} Positionner et redimensionner le modèle.
 - {% include button.html name="capture" %}  Prendre des captures d'écran et enregistrer l'état de la scène.
 - {% include button.html name="derivatives" %}  Gérer les dérivés (différents niveaux de détail).
 - {% include button.html name="annotations" %}  Créer et modifier des annotations.
 - {% include button.html name="articles" %}  Créer et éditer des articles.
 - {% include button.html name="visites" %}  Créer et modifier des visites guidées.
 - {% include button.html name="audio" %}  Ajouter et organiser des audios.
 - {% include button.html name="parametres" %}  Editer les paramètres de la scène.

## Créer une scène pas à pas

### Importer un modèle

Importez un modèle en .glb en le glissant dans la liste de modèles à partir de vos fichiers, ou en cliquand sur le bouton "Créer une scène".

Cliquez ensuite sur "story" pour acceder à l'éditeur de scène Voyager.

### Positionner et redimensionner le modèle

Allez dans l'onglet <span class="inline"><ff-button text="Pose" icon="move" disabled></ff-button></span> et selectionnez votre modèle pour ajuster sa position.

<img src="/assets/img/doc/Voyager-edit-pose.jpg" alt="screen de l'application Voyager, positionner le modèle">

Vous pouvez alors le recenter dans la scène, puis ajuster sa position et sa rotation à l'aide des fenêtres de vue _top_, _left_ et _front_.

Pensez à vérifier l'unité de mesure de la scène, ainsi que de l'object. Vous pouvez vous servir de l'outil _mesure_ dans les <span class="inline"><ff-button class="rounded" icon="tools" disabled></ff-button></span> paramètres pour vérifier la taille du modèle.

<img src="/assets/img/doc/Voyager-edit-mesure.jpg" alt="screen de l'application Voyager, mesurer le modèle">

### Prendre des captures d'écran et enregistrer l'état de la scène

Une fois le modèle positionné comme voulu, allez dans l'onglet <span class="inline"><ff-button text="Capture" icon="camera" disabled></ff-button></span> pour enregistrer son positionnement et générer une image de miniature. 

<img src="/assets/img/doc/Voyager-edit-capture.jpg" alt="screen de l'application Voyager, capturer la scène">

Il est necessaire de capturer la scène pour enregistrer son état (position de l'objet, miniature...).

### Créer et modifier des annotations

Dans l'onglet <span class="inline"><ff-button text="Annotations" icon="comment" disabled></ff-button></span>, selectionnez votre modèle puis cliquer sur le bouton _+ create_ pour créer votre nouvelle annotation.

Cliquez ensuite sur l'élément à annoter sur votre modèle.

<img src="/assets/img/doc/Voyager-edit-annotations.jpg" alt="screen de l'application Voyager, ajouter une annotation">

Attention, l'annotation sera par défaut en anglais. N'oubliez pas de changer la langue dans _language_ pour la mettre dans la langue de votre application.

### Créer et éditer des articles

Dans l'onglet <span class="inline"><ff-button text="Articles" icon="file" disabled></ff-button></span>, selectionnez votre modèle puis cliquez sur le bouton _+ create_ pour créer votre nouvel article.

<img src="/assets/img/doc/Voyager-edit-article.jpg" alt="screen de l'application Voyager, ajouter un article">

Comme pour les annotations, vérifiez que la langue sélectionnée soit bien celle de votre application.

Vous pouvez alors lui définir un titre, un extrait, puis utiliser l'éditeur pour rédiger votre article.

Vous pouvez revenir à tout moment éditer votre article en cliquand sur son nom dans la liste.

### Créer et modifier des visites guidées

Dans l'onglet <span class="inline"><ff-button text="Visites" icon="globe" disabled></ff-button></span>, cliquez sur le bouton + pour créer une nouvelle visite guidée.

Dans l'éditeur de tour, vous pouvez alors créer chaque étape de votre visite.
Vérifiez bien que la langue sélectionnée soit bien celle de votre application.

Ajoutez un titre puis modifiez la position de votre modèle, zoomez sur des éléments clefs, affichez ou non un article... puis cliquez sur _update_ afin de l'enregistrer et passer à l'étape suivante.

<img src="/assets/img/doc/Voyager-edit-visite.jpg" alt="screen de l'application Voyager, créer une visite guidée">

### Sauvegarder votre scène

Il ne reste plus qu'à sauvegarder votre travail grâce au bouton <span class="inline"><ff-button text="Sauvegarder" icon="save" disabled></ff-button></span>.

Vous pouvez aussi sauvegarder votre scène en local en la téléchargeant avec le bouton <span class="inline"><ff-button text="Télécharger" icon="download" disabled></ff-button></span>.
