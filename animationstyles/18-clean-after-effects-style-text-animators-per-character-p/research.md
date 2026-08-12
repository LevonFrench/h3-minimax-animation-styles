# Research — Per-character kinetic typography

## Style fingerprint

- **Visual/material vocabulary:** text animator range selector; baseline discipline; cap-height guides; per-character Y position; shallow 3D rotation; overshoot; motion blur; final lockup.
- **Motion logic:** Animate selectors rather than whole-word drift; keep characters readable during overshoot and reserve the final tail for a perfectly stable exact title.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [Adobe — Animating text](https://helpx.adobe.com/after-effects/desktop/animating-text/text-animation/animating-text.html)
- [Adobe Learn — Create and animate text](https://www.adobe.com/learn/after-effects/web/creating-animating-text)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
