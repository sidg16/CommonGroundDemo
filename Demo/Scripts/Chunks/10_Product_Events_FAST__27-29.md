NIKATAM — Chunk 10: Product — Events (FAST) (0:27–0:29)

Purpose
Instantly show an event join; slam cut to live cricket payoff next.

Timing
0:27.0–0:29.0 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1024

Visuals
- Event card: “Cricket meetup — Local Ground — Sat 4PM”.
- Tap ‘Join’; tiny confetti or chime indicator.

On-screen Text (OST)
- None beyond UI.

Voiceover (VO)
- 0:00.6: “Join local events.”

Music & SFX
- Music: continuous; small accent on join.
- SFX: soft tap; confirm chime.

Camera / Lighting
- Camera: static UI; micro parallax on card.
- Lighting: soft studio; clean shadows.



Generator Prompt (Veo3/InVideo)
“Doodled phone UI. Event card ‘Cricket meetup — Local Ground — Sat 4PM’. Tap ‘Join’ triggers a small celebratory indicator (confetti 0.4s). Hand‑drawn frame; minimal icons; pencil shadow; 300–350ms micro‑interaction; no baked text/logos.”

JSON Shot Spec
```json
{
  "id": 10,
  "label": "Product — Events (FAST)",
  "duration_s": 2.0,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":0.6, "text":"Join local events."}],
  "ost": [],
  "sfx": [
    {"t":0.8, "name":"ui_tap_soft"},
    {"t":1.4, "name":"confirm_chime"}
  ],
  "camera": "static_ui_parallax",
  "lighting": "soft_studio",
  "prompt": "Doodled feed card: Cricket meetup Local Ground Sat 4PM; join tap; minimal UI; no baked text.",
  "transition_in": "card_flip",
  "transition_out": "cut_to_live_cricket",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.2,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1024,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


