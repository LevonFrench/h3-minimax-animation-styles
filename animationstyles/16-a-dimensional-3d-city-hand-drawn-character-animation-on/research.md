# Research — Hybrid stepped 2D character in smooth 3D world

## Style fingerprint

- **Visual/material vocabulary:** smooth 3D environment; hand-drawn character on twos; held graphic poses; halftone shadow; chromatic misregistration; ink contour; one-frame impact card; painted trail.
- **Motion logic:** The contrast is the style: environment and camera remain fluid at 24 fps while the skater advances in deliberate two-frame holds; use one impact frame only.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [ACM SIGGRAPH — integrating CG with filmed imagery](https://blog.siggraph.org/2018/06/jurassic-park-made-a-dinosaur-sized-leap-forward-in-computer-generated-animation-on-screen-25-years-ago.html)
- [Adobe — keyframes and interpolation](https://helpx.adobe.com/after-effects/desktop/animate-in-after-effects/animation-basics/animation-basics.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
