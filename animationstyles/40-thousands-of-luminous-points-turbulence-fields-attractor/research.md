# Research: deterministic particle-field morph loop

## Identification and provenance

This is a procedural particle-motion hybrid using force fields, turbulence, attractors, flocking-like coherence, and depth-of-field rendering. Blender’s manual documents force fields affecting particle simulations and enumerates vortex, turbulence, drag, boid, and related field types. The exact sphere–torus–hourglass loop is a bespoke motion design, not a named historical style.

## Visual and motion mechanics

- Use a fixed population of luminous points; each point follows a closed deterministic trajectory instead of dying and respawning.
- Shape change should preserve mass impression and point continuity through sphere, ring, torus, hourglass, and restored sphere.
- A violet wave travels through existing points and returns them to cyan; do not replace the cloud.
- Depth falloff and locked-center camera give dimensionality while the centroid remains stable.

## Prompt implications

Keep one coherent particle body on black. Favor smooth field-driven flow over explosive scatter. Restore distribution, velocity, brightness, color, focus, and rotation phase for the loop.

## Sources

- [Blender Manual: force fields affecting particles and simulations](https://docs.blender.org/manual/en/dev/physics/forces/force_fields/introduction.html)
- [Blender Manual: force-field types including turbulence, vortex, and boid](https://docs.blender.org/manual/en/2.83/physics/forces/force_fields/index.html)
- [Autodesk Maya: depth-of-field focus control](https://help.autodesk.com/cloudhelp/2022/ENU/Maya-Rendering/files/GUID-3FCD5E9C-98AF-4BA9-99A1-381B036724E3.htm)
