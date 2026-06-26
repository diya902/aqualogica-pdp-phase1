# Aqualogica PDP project — house rules

## Brand design guideline: NO hard outlines
- Aqualogica's brand style uses **soft edges** — rounded corners + soft blurred drop shadows. **Do not add hard outlines/borders** (especially `solid var(--ink)` borders or hard offset shadows like `Npx Npx 0`) on cards, chips, tabs, badges, images, or containers.
- Use soft shadows (e.g. `0 6px 18px rgba(0,0,0,.08)`) to separate surfaces instead of strokes.
- Exception: thin hairlines that are part of a *certificate-document illustration* (signature underlines, scan dividers) are document detail, not UI outlines — those can stay.
- Active states (e.g. selected tab) = filled pill (teal) + soft shadow, never an outline.

## Files
- The three live PDPs are `Aqualogica PDP Wireframe.html` (Sunscreen), `Aqualogica Combo PDP.html`, `Aqualogica Mist PDP.html`, shown together in `Aqualogica PDPs.html`.
- These three share most CSS rules verbatim — apply structural/style changes to all three.
