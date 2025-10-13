NIKATAM — Chunk 14: Montage — Alive Neighborhood Wide (0:51.5–0:55)

Purpose
Show the transformed neighbourhood: clusters interacting, motif lights.

Timing
0:49.5–0:52.5 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1034

Visuals
- Doodle wide establishing shot: multiple small clusters interacting — chatting, mini yoga group, two playing catch.

On-screen Text (OST)
- Center, small: “A neighbourhood that feels like family”.

Voiceover (VO)
- 0:52.0: “A community that feels like family again.” (warm, uplifted)

Music & SFX
- Music: mild crescendo; add warm strings.
- SFX: soft ambient chatter; light breeze.

Camera / Lighting
- Camera: slow aerial dolly or crane rise; subtle parallax.
- Lighting: golden late-afternoon daylight.



Generator Prompt (Sora/Veo3)
“Photoreal wide establishing shot of a cozy neighborhood with small groups interacting (chatting, micro-yoga, two playing catch). Subtle orange-dot motif as lit windows/signs. Late-afternoon warm light, slow aerial dolly, 1080p 24fps.”

JSON Shot Spec
```json
{
  "id": 14,
  "label": "Montage — Alive Neighborhood Wide",
  "duration_s": 3.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":52.0, "text":"A community that feels like family again."}],
  "ost": [{"t":51.6, "text":"A neighbourhood that feels like family", "pos":"center"}],
  "sfx": [
    {"t":51.7, "name":"ambient_chatter_soft"},
    {"t":52.6, "name":"breeze_soft"}
  ],
  "camera": "slow_aerial_dolly",
  "lighting": "late_afternoon_warm",
  "prompt": "Doodle wide neighborhood with clusters interacting; warm light; no baked text.",
  "transition_in": "dissolve",
  "transition_out": "straight_cut",
  "transition_in_duration_s": 0.2,
  "transition_out_duration_s": 0.1,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1034,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


