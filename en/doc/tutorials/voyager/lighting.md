---
title: Lighting manual
description: Learn to setup lights in dpo-voyager
---

## Prerequisites

This tutorial will use a lot of concepts from [THREE.js](https://threejs.org/). Some familiarity with the library is expected.

## Default lighting

The default scene is created with one **Sky** ([HemisphereLight](https://threejs.org/docs/?q=Hemisp#api/en/lights/HemisphereLight)) to provide global illumitation, and a **Sun** ([DirectionalLight](https://threejs.org/docs/?q=direct#api/en/lights/DirectionalLight)).

## Features

#### Light tuning

The easiest way to tune lights is to change the `elevation` and `azimuth` of the sun in the node's settings.

<center>
  <img class="img-fluid" style="max-width:600px" alt="directional light elevation and azimuth setup in DPO-Voyager/eCorpus" src="/assets/img/doc/azimuth.webp">
</center>
It might also be worthwhile to set the **Sun**'s color and the **Sky**'s color and ground-color.


#### Tone Mapping

The renderer [toneMapping](https://threejs.org/docs/index.html?q=renderer#api/en/renderers/WebGLRenderer.toneMapping) can be toggled between **no tone mapping** and **ACESFilmicToneMapping**.

See the [playground](https://threejs.org/examples/#webgl_tonemapping) for an example.

Tone Mapping defaults to true in eCorpus. It is especially useful for objects with high metalness or glossiness.

The recommendation is to always set it to `true` when working on advanced scene lighting.

#### Environment map

The environment is *not* used for light emission. It only contributes to metallic/specular reflections.

#### Shadows

Shadows defaults to false on all lights. It is recommended to have at most one light casting shadows in a scene.
