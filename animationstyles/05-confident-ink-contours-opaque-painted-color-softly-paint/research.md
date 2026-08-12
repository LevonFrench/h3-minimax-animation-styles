# Research — Classical cel animation with multiplane depth

## Style fingerprint

- **Visual/material vocabulary:** inked contour; opaque cel color; watercolor background; multiplane separation; anticipation; follow-through; clean silhouettes; warm theatrical key.
- **Motion logic:** Keep character color fields stable and edges inked; use foreground, character, and background planes for parallax while preserving a single readable action.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Library of Congress — Fantasia animation cel](https://www.loc.gov/exhibits/music-and-animation/fantasia-1940.html)
- [Library of Congress — Music and Animation](https://www.loc.gov/exhibits/music-and-animation/about.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
