NIKATAM — Chunk 14: Product — Flash Micro-Features (0:35.0–0:38.5)

Purpose
Rapidly surface SOS, Lost & Found, Complaints, and Noticeboard as quick-utility features.

Timing
0:35.0–0:38.5 (flex ±0.2s); each icon ~0.8–0.9s.

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1014
- Transition in: flash‑strip 0.25s; out: phone_slide_to_live_bleed 0.30s; easing: cubic‑bezier(0.2,0.8,0.2,1)

Visuals
- Rapid flash strip of icons on cream background with graphite labels: SOS (first), Lost & Found, Complaints, Notices.
- Micro-animations: SOS pulse; Lost & Found pin dropping; Complaints icon shakes; Noticeboard sheet pins with bounce.

On-screen Text (OST)
- Labels under each icon only; no extra captions.

Voiceover (VO)
- 0:37.0+: “…and everything else that makes a neighbourhood… neighbourly.”

Music & SFX
- Music: continuous; small accents aligned to icon pops.
- SFX: quick pops; subtle heartbeat pulse for SOS (calm, non-alarming); light pin ‘tock’ for Lost & Found.

Camera / Lighting
- Camera: static center; snappy cuts between icons.
- Lighting: clean studio; strong contrast.



Generator Prompt (Sora/Veo3)
“Minimal icon showcase on cream background with graphite labels. Sequence: SOS (pulsing), Lost & Found (pin drops), Complaints (shake), Community Noticeboard (paper pin with bounce). Clean vector style, snappy micro-animations, no clutter. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 9,
  "label": "Product — Flash Micro-Features",
  "duration_s": 3.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":37.0, "text":"…and everything else that makes a neighbourhood… neighbourly."}],
  "ost": [
    {"t":36.6, "text":"SOS", "pos":"bc"},
    {"t":37.5, "text":"Lost & Found", "pos":"bc"},
    {"t":38.3, "text":"Complaints", "pos":"bc"},
    {"t":39.1, "text":"Noticeboard", "pos":"bc"}
  ],
  "sfx": [
    {"t":36.7, "name":"alert_soft"},
    {"t":37.6, "name":"pin_tock"},
    {"t":38.4, "name":"paper_rustle"}
  ],
  "camera": "static_snappy",
  "lighting": "clean_studio",
  "prompt": "Icon strip: SOS pulse, L&F pin drop, Complaints shake, Noticeboard pin; clean minimal.",
  "transition_in": "flash_strip",
  "transition_out": "phone_slide_to_live_bleed",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1014,
  "negative_prompt": "no watermarks, no extra baked text/captions, no third-party logos, no crowds, minimal background"
}
```


