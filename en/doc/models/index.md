---
title:  Models preparation
category: guide
---

# Models preparation

Models should be in **GLTF-binary** format (`.glb` files), though other formats might work.

Compression (using [Draco](https://google.github.io/draco/)) is supported and will generally speed up loading : faster network transfer and faster object parsing.

The Blender [GLTF export](https://github.com/KhronosGroup/glTF-Blender-IO) is a good reference implementation and should generally be trusted.

## Size

Recommended sizes (faces and map size):
 - **Thumb**   The lowest available representation. Always loaded first, with the goal of displaying a first representation of the model as quickly as possible. We recommend using a compressed GLB file with a total size of less than 200k.
 - **Low**     Used on older mobile devices. Maximum texture size: 1024 x 1024 pixels. Recommended mesh size: ~150k faces.
 - **Medium**  Used on newer mobile devices. Maximum texture size: 2048 x 2048 pixels. Recommended mesh size: ~150k faces.
 - **High**    Used on desktop devices. Maximum texture size: 4096 x 4096 pixels. Recommended mesh size: ~150k faces.
 - **Highest** Used for quality inspection. Texture size: 4k or 8k. Mesh size: ~500k faces.

## Import

Either import as a new scene or, to update an existing scene's model : 

```sh
curl -XPUT -u <username>:<password> -d @</path/.to/file.glb> https://ecorpus.holusion.com/scenes/<scene-name>/models/<filename.glb>
```
Then configure the model's derivatives (ref needed).
