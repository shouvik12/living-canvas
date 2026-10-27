---
name: living-canvas
description: "Turn anything (GitHub repo, URL, doc, concept, topic, one sentence) into a beautiful animated canvas: README-ready animated SVG and/or interactive canvas page."
---

# Living Canvas

Input can be anything under the sun. Output is a moving piece of art that captures its essence, and that a stranger understands at a glance.

## 1. Understand the subject
- Repo/URL: read README, file tree, languages, tagline. Doc: skim headings. Sentence/topic: use it directly.
- Distill into: ONE core transformation or idea, a mood, 3-5 key visual elements, and a tagline (max 8 words).
- Find the subject's own concrete example (a before/after, a real input and output, a number). Use it instead of inventing an abstract one.

## 2. Clarity first: the still-frame test
- A viewer who has never seen the subject must get the idea from ONE still frame, with no README and no explanation.
- Tell it as a short story, left to right: problem → what the subject does → result. Two to three labeled panels or stages work well.
- Label every stage in plain words (e.g. "1 · WITHOUT X", "2 · X ASKS", "3 · WITH X"), and put a one-line caption under each.
- Add a plain-language subtitle under the title that says what the subject does.
- Show real-looking content (readable code, actual text, actual numbers), not abstract bars or blobs.
- Never use an unlabeled symbol (ladder, funnel, rings) that only makes sense if you already know the project.

## 3. Pick a visual metaphor that fits
- Converters, compressors, pipelines: things flowing into a glowing core and emerging clean.
- AI, data, networks: particles, constellations, orbiting nodes.
- Games: generative terrain, parallax, motion toward the horizon.
- Nature, emotion, abstract topics: weather, light, water, ink, organic noise.
- Tools/CLIs: typing terminal lines that resolve into a result.
Never default to generic gradient blobs. The metaphor must say something true about the subject, and it serves the story from step 2. It never replaces the labels.

## 4. Choose output format
- GitHub README: animated SVG only (SMIL + CSS keyframes, no JS, no external fonts/images, viewBox ~900x300, under 100KB).
- Otherwise: one self-contained HTML page with <canvas> + requestAnimationFrame, fullscreen, responsive, one rewarding interaction (cursor/click). Publish as an artifact when available.
- If unclear, produce both.

## 5. Craft rules
- Dark rich background, 2-3 accent colors from the subject.
- Motion follows the story: highlight each stage in turn (dim the others) rather than adding decoration. Effects (particles, bursts, beams) only where they make a step clearer.
- Seamless loop: shared cycle durations, staggered begin offsets.
- Layer depth: ambience, midground motion, foreground hero + title.
- Smooth, readable motion; no harsh flicker. Respect prefers-reduced-motion, and in that mode show every stage fully visible so the still frame tells the whole story.
- Title in clean type, tagline in small letter-spaced caps.
- No copyrighted characters, others' logos, or real people.

## 6. Check before delivering
- Ask: "If someone saw only a screenshot, could they say what this project does?" If not, add labels or captions and simplify before sending.

## 7. Deliver
Send the file(s). For SVG, give the README embed line. Offer one tweak axis (palette, speed, metaphor).
