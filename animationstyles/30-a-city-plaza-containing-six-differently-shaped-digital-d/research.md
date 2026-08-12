# Research — Synchronized multi-screen DOOH

## Style fingerprint

- **Visual/material vocabulary:** fixed plaza sightline; six physical bezels; traveling handoff pulse; per-screen aspect adaptation; shared master canvas; synchronized final mosaic.
- **Motion logic:** Preserve every display boundary and geometry; the pulse should cross gaps as a timed visual handoff, while the final artwork aligns across one fixed viewpoint.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [IAB — DOOH definition and core features](https://www.iab.com/guidelines/dooh-defintion-and-core-features/)
- [IDOOH — DOOH Creative Specifications](https://idooh.media/download/IDOOH_DOOH_Creative_Specs_2022-09.pdf)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
