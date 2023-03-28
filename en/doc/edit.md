---
title: Editing Manual
description: Learn how to edit a 3D scene using Voyager Story.
---

# Voyager Story

## Scene Editor for Voyager

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

### Edit your scene


 - {% include button.html name="pose" style="width:150px" icon="move" %} Position and resize the model.
 - {% include button.html name="capture" style="width:150px" icon="camera" %} Take screenshots and save the state of the scene.
 - {% include button.html name="derivatives" style="width:150px" icon="hierarchy" %}  Manage derivatives (different levels of detail).
 - {% include button.html name="annotations" style="width:150px" icon="comment" %}  Create and edit annotations.
 - {% include button.html name="articles" style="width:150px" icon="file" %}   Create and edit articles.
 - {% include button.html name="tours" style="width:150px" icon="globe" %}  Create and edit guided tours.
 - {% include button.html name="audio" style="width:150px" icon="audio" %}  Add and organize audio.
 - {% include button.html name="parameters" style="width:150px" icon="eye" %}  Edit scene settings.

## Creating a scene step by step

### Import a model

<p>
  Import a .glb model by dragging it into the model list from your files or by clicking the "Create Scene" button.
</p>
<p>
  Then click on "story" to access the Voyager scene editor.
</p>

### Position and resize the model

<p>
  Go to the {% include button.html name="pose" icon="move" %} tab and select your model to adjust its position.
</p>

<img src="/assets/img/doc/Voyager-edit-pose.jpg" alt="screen of the Voyager application, position the model">

<p>
  You can then recenter it in the scene and adjust its position and rotation using the _top_, _left_, and _front_ view windows.
</p>

<p>
  Be sure to check the unit of measurement for the scene and object. You can use the measure tool in the {% include button.html icon="tools" class="voyager-btn-rounded" %} settings to check the size of the model.
</p>

<img src="/assets/img/doc/Voyager-edit-mesure.jpg" alt="screen of the Voyager application, measure the model">

### Take screenshots and save the state of the scene

<p>
  Once the model is positioned as desired, go to the {% include button.html name="capture" icon="camera" %} tab to save its position and generate a thumbnail image.
</p>

<img src="/assets/img/doc/Voyager-edit-capture.jpg" alt="screen of the Voyager application, capture the scene">

<p>
  It is necessary to capture the scene to save its state (object position, thumbnail, etc.).
</p>

### Create and edit annotations

<p>
  In the {% include button.html name="annotations" icon="comment" %} tab, select your model and click the _+ create_ button to create your new annotation.
</p>
<p>
  Then click on the element to annotate on your model.
</p>

<img src="/assets/img/doc/Voyager-edit-annotations.jpg" alt="screen of the Voyager application, add an annotation">

<p>
  Note that the annotation will be in English by default. Don't forget to change the language in the language settings to the language of your application.
</p>

### Create and edit articles

<p>
  In the {% include button.html name="articles" icon="file" %} tab, select your model and click the + create button to create your new article.
</p>

<img src="/assets/img/doc/Voyager-edit-article.jpg" alt="screen of the Voyager application, add an article">

<p>
  As with annotations, make sure the selected language is that of your application.
</p>
<p>
  You can then define a title, excerpt, and use the editor to write your article.
</p>
<p>
  You can edit your article at any time by clicking on its name in the list.
</p>

### Create and edit guided tours

<p>
  In the {% include button.html name="tours" icon="globe" %} tab, click the + button to create a new guided tour.
</p>

<p>
  In the tour editor, you can then create each step of your tour. Make sure the selected language is that of your application.
</p>

<p>
  Add a title, then adjust the position of your model, zoom in on key elements, display or hide an article... then click _update_ to save it and move on to the next step.
</p>

<img src="/assets/img/doc/Voyager-edit-visite.jpg" alt="screen of the Voyager application, create a guided tour">

### Save your scene

<p>
  All that's left is to save your work using the {% include button.html name="Save" icon="save" %} button.
</p>

<p>
  You can also save your scene locally by downloading it with the {% include button.html name="Download" icon="download" %} button.
</p>