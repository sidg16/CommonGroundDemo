NIKATAM Doodle Art Style Guide — v1.0

Principles
- Warm, human, lightly comic. Strict stickman figures; squiggly/wobbly linework.
- Minimal props; clean cream paper background; pencil-like fills only.
- Readable at small sizes; abundant negative space; no baked-in text.

Linework
- Stroke: thin graphite/soft black, 2–3 px at 1080p. Color `#0E1012`.
- Jitter: 1–2 px wobble; subtle line wobble on contours and motion lines.
- Texture: pencil/colored-pencil look; no vector-perfect edges, no gradients.

Characters (Strict Stickman)
- Anatomy: circle head; single-line torso/limbs; no clothing details.
- Expression: simple eyes/mouth with eyebrows; legible emotion from 25% scale.
- Posture: slightly exaggerated for clarity (bent knees, head tilt, arm angle).

Color & Background
- Paper: cream `#fff3e0`. Accents: orange `#f08a4b`, green `#9ec89b`.
- Background doodles per room: ≤2 (e.g., window outline, potted plant). Very light pencil fills.
- Shadows: light hatch/smudge; avoid heavy shading or directional realism.

Composition Patterns
- Top/Bottom stacked rooms (preferred for mirroring).
- Side-by-side split; Triptych (three narrow panels).
- Centered doodled phone/UI frame with large touch targets and simple chips.
- Safe margins: ≥10% of canvas; preserve OST/caption safe areas in edit.

Motion & Transitions (for video)
- Frame rate: 24 fps output; permit draw-on-twos feel with micro-jitter.
- Camera: minimal (locked, slight drift, gentle push).
- Transitions: line-morph; cross-dissolve; swipe on UI; avoid wipes/glitches.

Phone/UI (Doodled)
- Frame: hand-drawn rectangle with soft inner line; maintain 8–12% bezel.
- Elements: large legible cards; simple chips; toggles and buttons with single-line outlines.
- Micro-interactions: tap pop, slide, snap; keep motion under 350 ms.

Captions & Text
- Do NOT bake text into generated images/clips. Add captions in edit only.
- External captions: 80% white on black rounded pill (60% opacity), safe area respected.

Export Specs
- Stills: PNG, 1920×1080 (primary). Variants: 1080×1920, 1080×1080.
- Video: 1080p, 24 fps. ProRes 422 LT or high-bitrate H.264.

Global Defaults (Video) — Applies to all chunks
- Engines: Veo3, InVideo
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4
- Grade: warm pastel look; subtle film grain ≈2%
- Audio mix: 48 kHz; target −16 LUFS integrated; peaks ≤ −1 dBTP; VO ducking −6 dB under VO, SFX −3 dB vs music
- Transitions: default in 0.25s, out 0.30s; easing: cubic‑bezier(0.2, 0.8, 0.2, 1)
- Negative prompts: no watermarks; no baked-in text; no third‑party logos; no busy/crowded backgrounds
- Export default: H.264 High@4.2 (~25 Mbps). ProRes 422 LT optional master

Determinism & Seeds
- Use stable seeds per segment family to preserve look continuity
  - Opening 1001; Problems 1010–1013; Product 1020–1023; Flash 1014; Montage 1030–1034; Closing 1040–1041

Doodle‑only Directive (entire video)
- All segments (Problems, Product UI, Montage, Closing) render in this doodle style. No photoreal footage.
- Phone/UI is doodled (hand‑drawn frame, simple chips, large touch targets).

Closing Treatment
- 21 (Logo Reveal): doodled map + doodled “NIKATAM” logo appears.
- 22 (Tagline): over 0.8s, doodled logo/lines morph to clean vector on cream; slight glow settles → professional feel.


Tokens Snapshot
```json
{
  "color": {"paper": "#fff3e0", "line": "#0E1012", "accent_orange": "#f08a4b", "accent_green": "#9ec89b"},
  "stroke": {"width_px_at_1080p": 2.5, "jitter_px": [1, 2], "texture": "pencil/colored-pencil"},
  "layout": {"safe_margin_percent": 10, "split_patterns": ["top_bottom","side_by_side","triptych"]},
  "export": {"aspect_primary": "16:9", "variants": ["9:16","1:1"], "fps_video": 24, "resolution": "1920x1080"}
}
```

Prompt Snippets
- Still (base):
  “Doodle art, strict stickman. Cream paper (#fff3e0), thin squiggly graphite lines (#0E1012), no gradients. [COMPOSITION]. 1–2 faint background doodles (window, plant). Pencil-like fills only. Mood: lightly comic, relatable. No text/logos. 1920×1080 PNG.”

- Motion (base):
  “Doodle animation, 24fps with subtle line jitter (1–2px), draw-on-twos feel. Thin squiggly strokes (≈2–3px at 1080p). Cream paper, pencil textures, no gradients. Camera minimal. Transitions: line‑morph/cross‑dissolve. [SCENE ACTION]. No baked-in text.”

UI Prompt Macro (doodled phone)
- “Hand‑drawn phone rectangle with soft inner line (8–12% bezel), large legible cards and chip tags, minimal icons, warm pastels; micro‑interaction 300–350ms; no baked text.”

Do / Don’t (quick)
- Do: keep strokes thin and wobbly; ≤2 background doodles; ample negative space.
- Don’t: gradients, vector-perfect edges, photoreal elements, baked-in text.


