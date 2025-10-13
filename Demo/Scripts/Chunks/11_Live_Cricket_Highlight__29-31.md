NIKATAM — Chunk 11: Live — Cricket Highlight (0:29–0:31)

Purpose
Deliver an immediate emotional payoff after joining an event.

Timing
0:29.0–0:31.0 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1025

- Doodle animation: local ground, wicket moment, then a quick 3–4 person team moment (micro‑huddle or chain of high‑fives).
- Keep framing tight; capture the smile and contact.

On-screen Text (OST)
- None.

Voiceover (VO)
- “Game on—strangers become teammates.”

Music & SFX
- Music: slight rise.
- SFX: one realistic leather‑on‑willow ‘thwack’; light crowd cheer.

Camera / Lighting
- Camera: handheld sideline; shallow DOF.
- Lighting: late-afternoon warm daylight.



Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. Local cricket ground; wicket taken; two neighbours exchange a crisp high‑five; joyful reaction. Thin squiggly graphite, pencil textures, cream paper; no baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 11,
  "label": "Live Cricket Highlight",
  "duration_s": 3.0,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":0.1, "text":"Game on—strangers become teammates."}],
  "ost": [],
  "sfx": [
    {"t":0.5, "name":"cricket_bat_ball_thwack"},
    {"t":1.8, "name":"crowd_cheer_light"}
  ],
  "camera": "handheld_like_sideline",
  "lighting": "neutral",
  "prompt": "Doodle wicket + quick 3–4 person team celebration; pencil textures; no baked text.",
  "transition_in": "cut_from_events_fast",
  "transition_out": "cut_back_to_phone_or_flash",
  "transition_in_duration_s": 0.1,
  "transition_out_duration_s": 0.2,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1025,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


