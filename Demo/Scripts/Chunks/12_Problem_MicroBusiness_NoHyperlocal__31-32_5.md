NIKATAM — Chunk 12: Problem — Micro‑Business, No Hyperlocal Reach (0:31–0:32.5)

Purpose
Show the core problem: local sellers lack a place where they’re actually seen.

Timing
0:31.0–0:32.5 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1026

- Doodle animation: quiet shop window / home baker counter with no customers; phone screen shows unread DMs (blurred/no legible names).
- Keep it tasteful, no negativity bias; just emptiness.

On-screen Text (OST)
- Small caption: “No platform where it matters”.

Voiceover (VO)
- Short tail from Events or a soft breath; no dedicated line.

Music & SFX
- Music: slight dip to underscore the problem.
- SFX: subtle room tone.

Camera / Lighting
- Camera: slow static; shallow DOF.
- Lighting: natural indoor light, slightly dimmer.

Transitions
- In: cut back to phone (or from 08B live cricket as a narrative pivot).
- Out: signage morphs into Business card (08D).

Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. Quiet home micro‑business (e.g., bakery counter), no customer traffic; phone shows unread DMs (no legible names). Cream paper, pencil textures; subdued mood; no baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 12,
  "label": "Problem — Micro-Business No Hyperlocal Reach",
  "duration_s": 1.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [],
  "ost": [{"t":0.3, "text":"No platform where it matters", "pos":"ll", "style":"small"}],
  "sfx": [
    {"t":0.2, "name":"room_tone_subtle"}
  ],
  "camera": "static_slow",
  "lighting": "natural_indoor_dim",
  "prompt": "Doodle micro-business, no customers; unread DMs; subdued; no baked text.",
  "transition_in": "cut",
  "transition_out": "signage_to_business_card_morph",
  "transition_in_duration_s": 0.1,
  "transition_out_duration_s": 0.25,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1026,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


