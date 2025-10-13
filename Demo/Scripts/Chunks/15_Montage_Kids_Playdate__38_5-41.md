NIKATAM — Chunk 10: Montage — Kids Playdate (0:40–0:42.5)

Purpose
Open the transformation montage with genuine childlike joy.

Timing
0:38.5–0:41.0 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1030

Visuals
- Doodle animation: small balcony playdate, toys, laughing, high‑fives.
- Insert 0.8s: quick study moment with shared workbook or puzzle, heads together.
- Handheld camera; warm golden-hour light; shallow DOF.

On-screen Text (OST)
- Small lower third: “Kids — play & learn”.

Voiceover (VO)
- 0:40.4: “Smiling kids, playing together.” (soft tone)

Music & SFX
- Music: add gentle strings pad; maintain bed.
- SFX: softened giggles; ambient laughter; faint page flip or pencil scratch during study insert (very soft).

Camera / Lighting
- Camera: handheld, minor sway; focus pulls between faces and hands.
- Lighting: golden-hour; warm highlights, soft shadows.



Generator Prompt (Sora/Veo3)
“Photoreal candid scene of kids (ages 3–7) on a small balcony playdate, warm golden-hour sunlight, shallow depth of field, natural smiles and high-fives. Handheld camera feel, subtle film grain, no logos, 1080p 24fps.”

JSON Shot Spec
```json
{
  "id": 10,
  "label": "Montage — Kids Playdate",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":40.4, "text":"Smiling kids, playing together."}],
  "ost": [{"t":40.2, "text":"Kids — play & learn", "pos":"ll"}],
  "sfx": [
    {"t":40.3, "name":"kids_giggle_soft"}
  ],
  "camera": "handheld_focus_pulls",
  "lighting": "golden_hour",
  "prompt": "Doodle kids balcony playdate; warm feel; pencil textures; no baked text.",
  "transition_in": "color_bleed",
  "transition_out": "dissolve",
  "transition_in_duration_s": 0.2,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1030,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


