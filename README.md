# Garbage Friends Visualizers

**Small characters. Big cinematic chaos.**

A home for GLB character animation experiments, looping Blender environments, and reusable visual-effects workflows. Started with a Garbage Friends character walking through a burning street.

## Project direction

- Solid shoes, smoother strides, and reliable foot contact.
- Separate walk and expressive head-animation clips.
- Textured city buildings, climbing vines, plants, and street clutter.
- Fire, smoke, embers, and falling debris.
- Seamless video loops and documented checks that can be repeated with another GLB.

## Current status

This repository is the public project starting point. The local prototype includes a 15-second, 1280×720 animation rendered at 24 fps, an animated character GLB, and an editable Blender scene. Those model and media files are not included in this initial repository.

The prototype remains stylized. Cleaner organic joint deformation and higher-fidelity fire are active improvement areas. This is not yet a general-purpose automatic rigger.

## Repeatable workflow

1. Preserve and inspect the source GLB: dimensions, axes, geometry, materials, and existing bones.
2. Locate joints for the actual model; separate accessories from limb calculations.
3. Rig the character, keep shoes rigid, and test deformation before building a scene.
4. Animate contact, down, passing, and up poses; match environment travel to foot motion.
5. Export and reimport the GLB. Check shoe shape, limb intersections, and loop endpoints.
6. Build textured surroundings and add layered effects with readable character lighting.
7. Review stills, render every output frame, and compare the beginning and end of the loop.
8. Deliver the GLB, editable scene, video, credits, and validation results separately.

New characters require their own joint placement and skinning. Blender volume effects need engine-native particles or baked flipbooks for use in a game; they do not transfer directly through standard GLB.

## Related project

[RigMint](https://github.com/MetaMu/rigmint) — the GLB refresher and rigging-tool project.

## Asset credits

The prototype uses CC0 materials from [Poly Haven](https://polyhaven.com/license): Brick Wall 02, Rough Plaster Broken, Asphalt 02, and Rusty Metal 02. Knoll Keepers project assets are tracked separately with their original credits. Character and third-party artwork rights remain with their respective owners; this repository does not grant rights to those assets.
