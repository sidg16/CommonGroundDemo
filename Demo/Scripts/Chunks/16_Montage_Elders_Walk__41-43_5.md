NIKATAM — Chunk 11: Montage — Elders Walk (0:42.5–0:45)

Purpose
Convey care, safety, and companionship among elders.

Timing
0:41.0–0:43.5 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1031

Visuals
- Doodle animation sequence within 2.5s:
- Beat 1 (0.8s): two elders tap cards on a small table, light chuckle.
- Beat 2 (0.7s): quick cut to a laughing‑therapy circle; shared laugh moment.
- Beat 3 (1.0s): sidewalk walk together sharing a thermos; close‑up hands.

On-screen Text (OST)
- “Elders — safer, seen”.

Voiceover (VO)
- 0:43.0: “Elders walking side by side…” (gentle)

Music & SFX
- Music: warm strings continue; slight swell.
- SFX: soft card tap; group chuckle; soft footsteps; ambient birds.

Camera / Lighting
- Camera: table close-up → medium circle → slow gimbal walk; shallow DOF.
- Lighting: soft daylight; slight backlight for rim.



Generator Prompt (Sora/Veo3)
“Photoreal scene of two elderly neighbours walking together on a sidewalk, sharing a thermos, gentle conversation. Close-ups on hands. Soft daylight, shallow depth of field, natural soundscape. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 11,
  "label": "Montage — Elders Walk",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":43.0, "text":"Elders walking side by side…"}],
  "ost": [{"t":42.7, "text":"Elders — safer, seen", "pos":"ll"}],
  "sfx": [
    {"t":42.8, "name":"footsteps_soft"},
    {"t":42.9, "name":"birds_ambience"}
  ],
  "camera": "slow_gimbal",
  "lighting": "soft_daylight_backlit",
  "prompt": "Doodle elders: cards tap, laughing therapy, sidewalk walk; pencil textures; no baked text.",
  "transition_in": "dissolve",
  "transition_out": "straight_cut",
  "transition_in_duration_s": 0.2,
  "transition_out_duration_s": 0.1,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1031,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


