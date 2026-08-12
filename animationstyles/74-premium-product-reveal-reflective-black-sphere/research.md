# Research — Reflective studio product reveal

## Provenance and identification

“Premium product reveal” is commercial direction rather than an art-historical style. The technically grounded components are a polished reflective material, controlled studio environment, continuous highlight design, and deliberate camera/object relationship. Blender's Principled BSDF documentation explains layered PBR response including roughness, metallic behavior, and specular/reflection controls; F-curves support smooth controlled motion.

## Visual mechanics

- A black polished sphere reads through reflected environment gradients, not black fill alone.
- Drive one continuous highlight sweep by a slow environment/object rotation while preserving the centered silhouette.
- Bloom and contract one halo reflection beneath the contact area.
- Condensation-like points should be sparse surface glints, not droplets that alter the object.

## Prompt implications

Specify a single controlled camera move and distinguish it from the environment rotation. Avoid impossible reflection discontinuities and preserve the opening clean-black state.

## Sources

- [Blender Manual — Principled BSDF](https://docs.blender.org/manual/nb/5.0/render/shader_nodes/shader/principled.html)
- [Blender Manual — Materials introduction](https://docs.blender.org/manual/en/2.91/render/materials/introduction.html)
- [Blender Manual — F-Curves introduction](https://docs.blender.org/manual/en/4.2/editors/graph_editor/fcurves/introduction.html)
