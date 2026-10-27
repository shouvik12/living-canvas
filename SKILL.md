---
name: living-canvas
description: Turn anything (GitHub repo, URL, doc, concept, topic, one sentence) into a beautiful animated canvas: README-ready animated SVG and/or interactive canvas page.
---

# Living Canvas

Input can be anything under the sun. Output is a moving piece of art that captures its essence.

## 1. Understand the subject
- Repo/URL: read README, file tree, languages, tagline. Doc: skim headings. Sentence/topic: use it directly.
- Distill into: ONE core transformation or idea, a mood, 3-5 key visual elements, and a tagline (max 8 words).

## 2. Pick a visual metaphor that fits
- Converters, compressors, pipelines: things flowing into a glowing core and emerging clean.
- AI, data, networks: particles, constellations, orbiting nodes.
- Games: generative terrain, parallax, motion toward the horizon.
- Nature, emotion, abstract topics: weather, light, water, ink, organic noise.
- Tools/CLIs: typing terminal lines that resolve into a result.
Never default to generic gradient blobs. The metaphor must say something true about the subject.

## 3. Choose output format
- GitHub README: animated SVG only (SMIL + CSS keyframes, no JS, no external fonts/images, viewBox ~900x300, under 100KB).
- Otherwise: one self-contained HTML page with <canvas> + requestAnimationFrame, fullscreen, responsive, one rewarding interaction (cursor/click). Publish as an artifact when available.
- If unclear, produce both.

## 4. Craft rules
- Dark rich background, 2-3 accent colors from the subject.
- Seamless loop: shared cycle durations, staggered begin offsets.
- Layer depth: ambience, midground motion, foreground hero + title.
- Smooth, readable motion; no harsh flicker. Respect prefers-reduced-motion.
- Title in clean type, tagline in small letter-spaced caps.
- No copyrighted characters, others' logos, or real people.

## 5. Deliver
Send the file(s). For SVG, give the README embed line. Offer one tweak axis (palette, speed, metaphor).
