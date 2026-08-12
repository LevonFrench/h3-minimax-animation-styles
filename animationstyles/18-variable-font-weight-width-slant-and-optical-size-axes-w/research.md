# Research — Variable-font axis animation

## Style fingerprint

- **Visual/material vocabulary:** wght; wdth; slnt; opsz; continuous registered-axis interpolation; counter preservation; responsive frame; strict left grid.
- **Motion logic:** Do not fake the transformation with distortion: preserve glyph topology and counters while axes change; avoid simultaneous extremes that destroy legibility.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Adobe — Variable Font Axes support](https://helpx.adobe.com/uk/after-effects/using/variable-font-axes-support.html)
- [Adobe Fonts — Using variable fonts](https://helpx.adobe.com/fonts/using/using-variable-fonts.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
