---
title: Gestion des modèles
category: guide
---

## Principes de base 

L'éditeur fonctionne principalement avec le format [gltf](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html). Plus particulièrement la variante `gltf-binary` décrite [ici](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html#glb-file-format-specification).

Des modèles au format [USD](https://openusd.org/release/intro.html) (`.usdz`) peuvent être fournis pour activer la réalité augmentée sur les appareils iOS mais ils ne peuvent pas être intégrés à la scène web3D pour le moment.


## Aller plus loin

### Niveaux de détail



L'application peut enregistrer plusieurs niveaux de détail pour un objet et tenter d'en afficher le plus pertinent. Les niveaux supportés sont :

    Thumb
    Low
    Medium
    High
    Highest

La selection se fait en fonction de la capacité `maxTextureSize` du moteur de rendu 

 > Voir la doc : [WebGLRenderer.capabilities.maxTextureSize](https://threejs.org/docs/?q=webGLRenderer#api/en/renderers/WebGLRenderer.capabilities)

En fonction de cette valeur, la qualité idéale sera:

 - si inférieur à 2048 : **Low**
 - si inférieur à 4096 : **Medium**
 - sinon               : **High**

Il est conseillé de fournir des textures de taille correspondante ou inférieure avec les modèles. 

### Shaders

En pratique, les modèles sont affublés d'un `MeshStandardMaterial`. Les bénéfices et limites en sont décrites dans la [documentation THREEJS](https://threejs.org/docs/#api/en/materials/MeshStandardMaterial).

