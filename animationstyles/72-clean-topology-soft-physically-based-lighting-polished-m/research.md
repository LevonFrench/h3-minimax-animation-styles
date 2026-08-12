# Research — Contemporary polished PBR motion design

## Provenance and identification

The source is contemporary stylized CG/product motion rather than a historical named style. Blender's Principled BSDF documentation describes a layered physically based surface model, while its animation graph documentation explains F-curves for smooth interpolated transforms. The Academy guide supplies the broader CGI context. “Premium” and “polished” are quality directions, not techniques by themselves.

## Visual mechanics

- Use clean sphere topology and stable specular response through an exact half-turn.
- Shape spline easing without overshoot at the turn endpoints.
- Preserve perceived volume through a modest gel compression and rebound.
- Keep light particles few, small, and in one coherent orbit before dissolution.

## Prompt implications

Define surface roughness/highlight continuity, exact turn amount, compression axis, and final shading restoration.

## Sources

- [Blender Manual — Principled BSDF](https://docs.blender.org/manual/nb/5.0/render/shader_nodes/shader/principled.html)
- [Blender Manual — F-Curves introduction](https://docs.blender.org/manual/en/4.2/editors/graph_editor/fcurves/introduction.html)
- [Academy — Animation Activities Guide](https://www.oscars.org/sites/oscars/files/complete_animation_activities_guide.pdf)
