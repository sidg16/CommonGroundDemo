NIKATAM — Chunk 13: Montage — Micro-Wins (Chef, Tutor, Lost Dog) (0:48–0:51.5)

Purpose
Celebrate small community wins that feel personal and real.

Timing
0:46–0:49.5 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1033

Visuals
- Doodle cross‑dissolve montage: home chef handing a pastry to a new customer; tutor running a mini‑class; lost dog returned with happy reunion.

On-screen Text (OST)
- None; let images breathe.

Voiceover (VO)
- 0:49.0: “Week by week—skills swapped, activities done together, rides shared, classes formed, customers found.”

Music & SFX
- Music: gentle, warm; soft harmonic lift.
- SFX: small bell ‘ding’ hits aligned to each micro-win.

Camera / Lighting
- Camera: slow push-ins; close-ups on hands and faces.
- Lighting: natural indoor light; warm color temperature.

Transitions
- In: dissolve from Connections Burst.
- Out: dissolve to wide neighbourhood.

Generator Prompt (Veo3/InVideo)
“Doodle montage: 1) home chef passes a pastry to a neighbour customer; 2) tutor teaching a small living-room lesson; 3) a happy reunion as a lost dog is returned; plus subtle feature echo ticks (Say Hi, Joined, Booked, confetti). Pencil textures, warm indoor light, 1080p 24fps.”

JSON Shot Spec
```json
{
  "id": 13,
  "label": "Montage — Micro-Wins",
  "duration_s": 3.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":49.0, "text":"Week by week—skills swapped, activities done together, rides shared, classes formed, customers found."}],
  "sfx": [
    {"t":48.4, "name":"bell_ding_soft"},
    {"t":49.6, "name":"bell_ding_soft"},
    {"t":50.8, "name":"bell_ding_soft"}
  ],
  "camera": "slow_push_ins",
  "lighting": "warm_indoor",
  "prompt": "Doodle micro-wins: pastry handoff, tutor mini-class, lost dog reunion; subtle feature echo ticks (Say Hi, Joined, Booked, confetti); pencil textures; no baked text.",
  "transition_in": "cross_dissolve",
  "transition_out": "dissolve",
  "transition_in_duration_s": 0.2,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1033,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


