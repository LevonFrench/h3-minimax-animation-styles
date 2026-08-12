# Research — Deterministic Particle Morph

## Actionable vocabulary

- Particle systems become coherent through force fields, attractors, turbulence, and flocking/boid rules. For a loop, use cached deterministic trajectories rather than respawning particles.
- Preserve point count and particle identity through sphere → ring → torus → hourglass → sphere; avoid dissolves that disguise topology changes.
- Depth comes from size falloff, occlusion, controlled bloom, and a shallow but stable focus plane. Keep the camera locked to the particle centroid.
- A color wave should travel through neighboring points as a spatial phase front, then return the entire cloud to the opening cyan state.

## Sources

- [Blender Manual — Boids particle physics](https://docs.blender.org/manual/vi/3.6/physics/particles/emitter/physics/boids.html)
- [Blender Manual — force fields](https://docs.blender.org/manual/fi/4.5/physics/forces/force_fields/introduction.html)
- [Blender Manual — motion blur for particles](https://docs.blender.org/manual/fi/3.6/render/cycles/render_settings/motion_blur.html)
