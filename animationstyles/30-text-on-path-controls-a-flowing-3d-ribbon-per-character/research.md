# Research — Text-on-path ribbon animation

## Style fingerprint

- **Visual/material vocabulary:** mask-path text; perpendicular character orientation; force alignment; spline ribbon; depth-aware occlusion; stable reading direction; character release.
- **Motion logic:** Keep the phrase attached to one continuous ribbon and upright at every bend; occlusion must be brief and physically caused by the ribbon crossing itself.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Adobe — Creating and animating text on a path](https://helpx.adobe.com/after-effects/desktop/animating-text/text-animation/animating-text.html)
- [Adobe — Bezier paths](https://helpx.adobe.com/ca/after-effects/using/overview-shape-layers-paths-vector.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
