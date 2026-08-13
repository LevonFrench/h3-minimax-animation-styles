# Research: variable-font kinetic typography

## Identification and provenance

This is contemporary kinetic typography using OpenType variable-font axes and per-character animation. Microsoft’s OpenType specification identifies weight and width as common continuous axes; Adobe documents animating weight/width axes and compensating character spacing. The breathing metaphor is a bespoke motion concept rather than a formal typography movement.

## Visual and motion mechanics

- Animate true glyph interpolation on weight and width axes, not a raster scale that distorts stroke proportions.
- Tracking and adaptive spacing must preserve optical centering as letters widen and narrow.
- Maintain exact phrase states; the midpoint change should be a clean readable replacement or controlled glyph interpolation, never scrambled intermediate text.
- Couple the circular field’s radius and luminance to the inhale/exhale cycle.

## Prompt implications

Use a locked planar composition and one smooth breath cycle. Keep “BREATHE IN” and “BREATHE OUT” exact, centered, and baseline-stable. Reserve time after returning to the opening phrase for a calm final settle.

## Sources

- [Adobe After Effects: working with variable-font axes](https://helpx.adobe.com/after-effects/using/working-with-variable-font-axes.html)
- [Microsoft OpenType: font variations overview](https://learn.microsoft.com/en-us/typography/opentype/otspec184/otvaroverview)
- [Adobe After Effects: text animators and selectors](https://helpx.adobe.com/uk/after-effects/desktop/animating-text/text-animation/animating-text.html)
