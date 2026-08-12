# Research — Glitch typography with controlled recovery

## Style fingerprint

- **Visual/material vocabulary:** scan-line slice; RGB channel offset; block compression; temporal displacement; data smear; sync bar; stable post-glitch lockup.
- **Motion logic:** Corrupt only the title layers, not the whole frame; escalate displacement in bounded bands, then let one vertical sync line restore geometry and channel registration.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Adobe — channel data and displacement inputs](https://helpx.adobe.com/nz/after-effects/using/3d-channel-effects.html)
- [Adobe — keyframed effect changes](https://helpx.adobe.com/after-effects/desktop/animate-in-after-effects/animation-basics/animation-basics.html)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
