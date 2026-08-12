# Research — Tweened vector symbol animation

## Style fingerprint

- **Visual/material vocabulary:** resolution-independent contours; reusable symbol parts; pivot hinges; flat gradient; shape interpolation; telescoping increments; snappy ease; elastic settle.
- **Motion logic:** Keep every limb and telescoping segment mechanically connected; emphasize three discrete extension increments and one clean parabolic leap rather than freeform morphing.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Adobe — vector shapes and paths](https://helpx.adobe.com/in/after-effects/using/overview-shape-layers-paths-vector.html)
- [Adobe — animation basics and Graph Editor](https://helpx.adobe.com/after-effects/desktop/animate-in-after-effects/animation-basics/animation-basics.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
