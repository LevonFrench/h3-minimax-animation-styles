# Research — Paint-on-glass animation

## Style fingerprint

- **Visual/material vocabulary:** wet oil translucency; luminous glass backlight; wiped and repainted passages; brush pressure ridges; pigment drag; soft edge migration; fluid metamorphosis.
- **Motion logic:** Avoid dissolves: the sail physically spreads into the fish fin while the hull pigment is pushed into the body; leave faint prior-frame smears as material memory.
- **MiniMax H3 translation:** Use one primary action, one continuous camera path (or a locked camera), one lighting progression, and a stable resolved endpoint. At 100 BPM, map beats 1–8 to 0.00–4.80 seconds and use the remaining H3 tail through 5.17 seconds as a clean hold. Treat exact typography and perfect loops as explicit constraints, but expect final frame-accurate enforcement in post.

## Sources

- [NFB — Hand-Crafted Cinema](https://www.nfb.ca/film/handcrafted_cinema/)
- [NFB — animation materials overview](https://www3.nfb.ca/sg/56975.pdf)

## Prompting takeaways

Name the physical medium before the subject, describe visible intermediate states rather than asking for a dissolve, bind each sound to one visible event, and state what must remain stable: subject identity, material texture, screen geometry, letterforms, or the loop phase.
