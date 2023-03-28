---
title: Manuel d'édition
description: apprenez à éditer une scène 3D en utilisant Voyager Story
---

# Voyager Story

## Editeur de scènes pour Voyager

<style>
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


 - {% include button.html name="pose" style="width:150px" icon="move" %} Positionner et redimensionner le modèle.
 - {% include button.html name="capture" style="width:150px" icon="camera" %} Prendre des captures d'écran et enregistrer l'état de la scène.
 - {% include button.html name="derivatives" style="width:150px" icon="hierarchy" %}  Gérer les dérivés (différents niveaux de détail).
 - {% include button.html name="annotations" style="width:150px" icon="comment" %}  Créer et modifier des annotations.
 - {% include button.html name="articles" style="width:150px" icon="file" %}  Créer et éditer des articles.
 - {% include button.html name="visites" style="width:150px" icon="globe" %}  Créer et modifier des visites guidées.
 - {% include button.html name="audio" style="width:150px" icon="audio" %}  Ajouter et organiser des audios.
 - {% include button.html name="parametres" style="width:150px" icon="eye" %}  Editer les paramètres de la scène.

## Créer une scène pas à pas

### Importer un modèle

<p>
  Importez un modèle en .glb en le glissant dans la liste de modèles à partir de vos fichiers, ou en cliquand sur le bouton "Créer une scène".
</p>
<p>
  Cliquez ensuite sur "story" pour acceder à l'éditeur de scène Voyager.
</p>

### Positionner et redimensionner le modèle

<p> 
  Allez dans l'onglet {% include button.html name="pose" icon="move" %} et selectionnez votre modèle pour ajuster sa position.
</p>

<img src="/assets/img/doc/Voyager-edit-pose.jpg" alt="screen de l'application Voyager, positionner le modèle">

<p>
  Vous pouvez alors le recenter dans la scène, puis ajuster sa position et sa rotation à l'aide des fenêtres de vue _top_, _left_ et _front_.
</p>

<p>
  Pensez à vérifier l'unité de mesure de la scène, ainsi que de l'object. Vous pouvez vous servir de l'outil _mesure_ dans les {% include button.html icon="tools" class="voyager-btn-rounded" %} paramètres pour vérifier la taille du modèle.
</p>

<img src="/assets/img/doc/Voyager-edit-mesure.jpg" alt="screen de l'application Voyager, mesurer le modèle">

### Prendre des captures d'écran et enregistrer l'état de la scène

<p>
  Une fois le modèle positionné comme voulu, allez dans l'onglet {% include button.html name="capture" icon="camera" %} pour enregistrer son positionnement et générer une image de miniature.
</p>

<img src="/assets/img/doc/Voyager-edit-capture.jpg" alt="screen de l'application Voyager, capturer la scène">

<p>
  Il est necessaire de capturer la scène pour enregistrer son état (position de l'objet, miniature...).
</p>

### Créer et modifier des annotations

<p>
  Dans l'onglet {% include button.html name="annotations" icon="comment" %}, selectionnez votre modèle puis cliquer sur le bouton _+ create_ pour créer votre nouvelle annotation.
</p>
<p>
  Cliquez ensuite sur l'élément à annoter sur votre modèle.
</p>

<img src="/assets/img/doc/Voyager-edit-annotations.jpg" alt="screen de l'application Voyager, ajouter une annotation">

<p>
  Attention, l'annotation sera par défaut en anglais. N'oubliez pas de changer la langue dans _language_ pour la mettre dans la langue de votre application.
</p>

### Créer et éditer des articles

<p>
  Dans l'onglet {% include button.html name="articles" icon="file" %}, selectionnez votre modèle puis cliquez sur le bouton _+ create_ pour créer votre nouvel article.
</p>

<img src="/assets/img/doc/Voyager-edit-article.jpg" alt="screen de l'application Voyager, ajouter un article">

<p>
  Comme pour les annotations, vérifiez que la langue sélectionnée soit bien celle de votre application.
</p>
<p>
  Vous pouvez alors lui définir un titre, un extrait, puis utiliser l'éditeur pour rédiger votre article.
</p>
<p>
  Vous pouvez revenir à tout moment éditer votre article en cliquand sur son nom dans la liste.
</p>

### Créer et modifier des visites guidées

<p>
  Dans l'onglet {% include button.html name="visites" icon="globe" %}, cliquez sur le bouton + pour créer une nouvelle visite guidée.
</p>

<p>
  Dans l'éditeur de tour, vous pouvez alors créer chaque étape de votre visite.
  Vérifiez bien que la langue sélectionnée soit bien celle de votre application.
</p>

<p>
  Ajoutez un titre puis modifiez la position de votre modèle, zoomez sur des éléments clefs, affichez ou non un article... puis cliquez sur _update_ afin de l'enregistrer et passer à l'étape suivante.
</p>

<img src="/assets/img/doc/Voyager-edit-visite.jpg" alt="screen de l'application Voyager, créer une visite guidée">

### Sauvegarder votre scène

<p>
  Il ne reste plus qu'à sauvegarder votre travail grâce au bouton {% include button.html name="Sauvegarder" icon="save" %}.
</p>

<p>
  Vous pouvez aussi sauvegarder votre scène en local en la téléchargeant avec le bouton {% include button.html name="Télécharger" icon="download" %} .
</p>