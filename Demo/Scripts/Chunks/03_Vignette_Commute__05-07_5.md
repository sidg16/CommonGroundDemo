NIKATAM — Chunk 03: Vignette — Commute (0:05–0:07.5)

Purpose
Show everyday waste and isolation despite proximity.

Timing
0:05.0–0:07.5 (flex ±0.3s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1011

Visuals
- Side-by-side simple road with repeating houses; two cars driving parallel.
- Fuel meters above each car drop quickly; tiny coins tumble out.

On-screen Text (OST)
- Small caption (top-right): “Same route, alone”.

Voiceover (VO)
- 0:00.2: “They even drive to the same office. Alone.”
- 0:01.8: “Wasting time, wasting money.”

Music & SFX
- Music: maintain bed; low pad underscoring monotony.
- SFX: low car engine hum; comic cash-drop ‘ting’ timed to meter drop.

Camera / Lighting
- Camera: lateral tracking with slight parallax.
- Lighting: flat daylight; simple shapes; no logos.



Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. Simple looping road, repeating house doodles, two cars in parallel; drivers glance at phones. Fuel meter icons above cars drop bars; tiny coins tumble. Thin squiggly lines, cream paper, pencil fills; no baked text. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 3,
  "label": "Vignette — Commute",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [
    {"t":0.2, "text":"They even drive to the same office. Alone."},
    {"t":1.8, "text":"Wasting time, wasting money."}
  ],
  "ost": [{"t":0.6, "text":"Same route, alone", "pos":"tr", "style":"small"}],
  "sfx": [
    {"t":0.3, "name":"car_engine_low"},
    {"t":1.9, "name":"coin_ting"}
  ],
  "camera": "lateral_track",
  "lighting": "flat_daylight",
  "prompt": "Doodle road, parallel cars, fast fuel meter drop with coins; minimal props; no baked text.",
  "transition_out": "dashboard_to_connect_button_morph",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1011,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos, minimal background"
}
```


