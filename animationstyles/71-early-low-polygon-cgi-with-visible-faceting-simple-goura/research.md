# Research — Early low-polygon CGI and Gouraud shading

## Provenance and identification

This is a deliberate evocation of early real-time/experimental CGI: coarse polygonal geometry, interpolated vertex shading, wireframe display, and black-background demo staging. The Academy guide distinguishes CGI's mathematical 3D models and camera freedom from physical animation. Blender's material and mesh documentation supplies current technical vocabulary, but does not make the shot historically authentic to a particular system.

## Visual mechanics

- Keep triangular facets visible through shape and reflected-light changes.
- Gouraud-like shading should interpolate across vertices while retaining a low-poly silhouette.
- Overlay one correctly registered wireframe, then fade it without replacing the shaded surface.
- Split geometry into latitudinal bands that rotate independently and rejoin without gaps.

## Prompt implications

Use “early-CGI evocation” rather than claiming provenance. Specify exact band continuity and final topology restoration.

## Sources

- [Academy — Animation Activities Guide](https://www.oscars.org/sites/oscars/files/complete_animation_activities_guide.pdf)
- [Blender Manual — Materials introduction](https://docs.blender.org/manual/en/2.91/render/materials/introduction.html)
- [Blender Manual — Mesh structure](https://docs.blender.org/manual/en/2.91/modeling/meshes/structure.html)
