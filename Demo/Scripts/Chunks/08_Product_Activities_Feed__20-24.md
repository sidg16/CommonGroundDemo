NIKATAM — Chunk 07: Product — Activities & Feed (0:30–0:34)

Purpose
Showcase discovering and joining ongoing activities from the feed.

Timing
0:20–0:24 (flex ±0.3s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1022

Visuals
- Phone UI switches to Feed: cards like “Morning Yoga — Park — 7AM”, “Badminton meetup — Saturday 4PM”.
- ‘Join’ button pulses subtly on an activity card.
- Scroll reveals details; participants counter grows 2 → 9.

On-screen Text (OST)
- “Find and join activities near you”.

Voiceover (VO)
- 0:31.0: “From daily yoga sessions… to one-time cricket matches.”

Music & SFX
- Music: continuous; add soft riser on join.
- SFX: swipe whoosh; soft ding when joining.

Camera / Lighting
- Camera: over-the-shoulder feel in mockup; slight parallax.
- Lighting: soft studio; high readability.

Transitions
- In: swipe from previous (from 06B Live Payoff back to phone).
- Out: match-cut to live yoga payoff (07B) via mat texture or card color; after 07B, quick card flip into Events.

Generator Prompt (Veo3/InVideo)
“Doodled phone UI feed with cards: ‘Morning Yoga — Park — 7AM’, ‘Badminton meetup — Saturday 4PM’. Subtle pulsing ‘Join’; participants count animates 2→9 (≈0.8s). Hand‑drawn frame, chips, minimal icons; pencil shadow; smooth scroll 300–350ms; no baked text/logos.”

JSON Shot Spec
```json
{
  "id": 7,
  "label": "Product — Activities & Feed",
  "duration_s": 4,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":31.0, "text":"From daily yoga sessions… to one-time cricket matches."}],
  "ost": [{"t":30.4, "text":"Find and join activities near you", "pos":"ll"}],
  "sfx": [
    {"t":30.2, "name":"swipe_whoosh"},
    {"t":32.2, "name":"soft_ding"}
  ],
  "camera": "slight_parallax",
  "lighting": "soft_studio",
  "prompt": "Doodled feed cards: Morning Yoga/Badminton; join pulse; counter 2->9 in 0.8s; smooth scroll; no baked text.",
  "transition_in": "swipe",
  "transition_out": "card_flip",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1022,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


