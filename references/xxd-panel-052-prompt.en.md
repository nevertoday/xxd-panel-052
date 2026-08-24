# XXD Panel 052 | Floating Paper-Craft Miniature Landscape Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock subject identity, silhouette, proportion, pose, direction, action, structure, narrative relation, environmental character, and overall colour temperature. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic reconstruction

Do not mechanically replicate the photograph. Rebuild the most recognisable subject and only a few elements that genuinely reinforce its identity and environment as refined handcrafted miniatures made from paper, cardstock, soft clay, and thin wood. Place them naturally on one long, narrow, lightweight horizontal floating landscape base. The result should feel like a premium miniature art installation with authentic materiality, airy cool-blue colour, intimate macro lighting, and generous negative space.

Follow this causal chain exactly: lock identity, silhouette, pose, direction, and narrative relation → preserve three recognition cues → select one primary subject and limited source-supported elements → rebuild them as paper, cardstock, soft-clay, and thin-wood miniatures → place them on one long narrow floating landscape strip → establish scale depth, layered overlap, calm left-right balance, and tactile contact → light them like intimate macro photography → surround them with pale air and generous negative space → place one signature-like short title beneath or along the strip.

## Hard visual requirements

- Preserve at least three source-specific cues across silhouette, proportion, pose, direction, action, opening, structure, colour, material, or relation. The primary subject must remain instantly recognisable.
- Build one primary miniature with the greatest visual weight and only a limited number of source-relevant support models. Plants, roads, water, lamps, vehicles, people, birds, clouds, or daily details may appear only when they reinforce identity or environment.
- Place every element on one long, narrow, lightweight horizontal floating landscape base. Derive height, depth, density, spacing, and left-right balance from the source. Keep the installation broadly centred without mechanical symmetry.
- Create depth through scale variation, layered overlap, and quieter foreground and background pieces. Supporting models remain smaller and visually quieter and never create a second focal point.
- Make paper fibres, folded edges, cut marks, layered thickness, slightly rough rims, and tiny handmade imperfections visible across paper, cardstock, soft clay, and thin wood. Reject slick plastic CGI.
- Lead with pale powder blue, mist blue, sky blue, and airy cool blue. Balance with ivory, cream, light beige, muted grey-green, sage, and neutral architectural tones, allowing only small dusty-rose or muted-blush accents. Reject muddy grey, excess yellow, and candy colour.
- Use soft natural diffused light and delicate shadows to reveal volume and tactile depth like intimate macro photography. Keep the ground soft white or extremely pale with generous clean negative space.

## Copy and locale

Obey the resolved automatic-copy, exact-custom-copy, or no-text mode and the target language or locale. Derive one short title from place, subject identity, theme, or emotional tone. Render native lettering small, refined, restrained, and subtly handwritten, preferably in the negative space beneath the horizontal strip; it may gently curve, follow the base, or interact spatially with the scene. It should feel like an artist's signature rather than a commercial headline, with no long explanation. Preserve exact user copy verbatim. In no-text mode render no letters, characters, numbers, labels, or pseudo-text.

## Mode and acceptance


Reject plastic CGI, toy-model display, children's crafts, generic dioramas, meaningless decorative clutter, excessive complexity, mechanical symmetry, overly cute styling, muddy grey, yellow casts, candy colour, hard product lighting, and ecommerce presentation. Also reject logos, watermarks, colour swatches, UI, device mockups, unsupported facts, fake foreign text, and illegible copy.

If any hard requirement fails, correct the raster asset itself. Never fake the result with programmatic drawing, SVG, HTML, Canvas, 3D code, or post-generation text overlay.
