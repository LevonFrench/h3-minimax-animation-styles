# Title

Cyan Hourglass Particle Cycle

## Intent

Morph a deterministic point cloud through coherent topology states without respawning or losing particle identity.

## Shot Class

Centered particle macro, 65 mm equivalent, locked camera at cloud centroid.

## Subject / Continuity

One cloud of exactly coherent cyan luminous points; every point persists through sphere, ring, torus, hourglass, and returning sphere.

## Timed Action + Camera

100 BPM. Beat 1 (0.00-0.60): sphere holds. Beats 2-3 (0.60-1.80): force field opens sphere into a ring. Beats 4-5 (1.80-3.00): ring thickens into a torus without respawn. Beats 6-7 (3.00-4.20): opposing attractors pull torus into hourglass and release it back toward sphere. Beat 8 (4.20-4.80): original sphere geometry and cyan phase recur. Hold through 5.1667 s.

## Spatial Block

Cloud centered at (0,0,+0.4), radius 0.30 m; attractors at Y=±0.22 m. Camera fixed at (0,0,−1.7), shallow focus plane centered on centroid.

## Look + Lighting

Fine emissive points, deterministic trajectories, controlled bloom, size falloff, occlusion, stable shallow focus, restrained motion blur. One color wave passes cyan-to-violet-to-cyan.

## Sound

Silent; no voice, music, effects, or soundtrack.

## Limits

One topology cycle. No text, particle birth/death, dissolves, camera movement, centroid drift, cuts, logos, or motion after 4.80 s.

## Sources

- [Blender Manual — Boids particle physics](https://docs.blender.org/manual/vi/3.6/physics/particles/emitter/physics/boids.html)
- [Blender Manual — force fields](https://docs.blender.org/manual/fi/4.5/physics/forces/force_fields/introduction.html)
- [Blender Manual — motion blur for particles](https://docs.blender.org/manual/fi/3.6/render/cycles/render_settings/motion_blur.html)
