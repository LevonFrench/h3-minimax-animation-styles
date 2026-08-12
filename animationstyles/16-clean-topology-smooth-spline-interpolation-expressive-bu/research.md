# Research — Feature-quality stylized CG character animation

## Style fingerprint

- **Visual/material vocabulary:** clean subdivision topology; spline interpolation; eye-led action; controlled facial shapes; soft PBR bounce; subsurface skin response; strap lag; contact compression.
- **Motion logic:** Lead with eyes, then head, torso, and backpack straps in descending order; preserve hand anatomy and seed identity through the catch and final held smile.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Pixar Research — Subdivision Surfaces in Character Animation](https://research.pixar.com/docs/1998.SiggraphPapers.DKT.pdf)
- [ACM SIGGRAPH — CG history](https://blog.siggraph.org/2023/07/50-years-in-a-blink-of-the-eye.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
