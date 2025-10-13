NIKATAM — Chunk 05: Vignette — Cricket (0:10–0:12.5)

Purpose
Show desire for team play but no team; sets up Events solution.

Timing
0:10.0–0:12.5 (flex ±0.3s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1013

Visuals
- Single large TV frame shows cricket; multiple tiny viewers on couches feel isolated.
- Alternative option: one stick-figure at a local ground fumbles a solo catch; brief deflate.
- Keep composition simple for a fast morph to the Event card.

On-screen Text (OST)
- Flash ~0:01.0: “Wanted: team” (≤0.8s)

Voiceover (VO)
- 0:00.2: “Looking for a team…”
- 0:01.7: “No one to play with.”

Music & SFX
- Music: maintain bed; small rise into solution later.
- SFX: faint stadium ambience or single ‘miss’ rustle.

Camera / Lighting
- Camera: static TV frame with subtle push-in; or single‑subject medium shot at ground.
- Lighting: flat clean; stick-figure style.



Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. Large TV frame shows cricket; many tiny couch viewers, each isolated; or alt: solo fumbled catch at a local ground. Thin squiggly graphite, pencil fills, cream paper; no baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 5,
  "label": "Vignette — Cricket (Problems)",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [
    {"t":0.2, "text":"Looking for a team…"},
    {"t":1.7, "text":"No one to play with."}
  ],
  "ost": [{"t":1.0, "text":"Wanted: team", "dur":0.8, "pos":"center"}],
  "sfx": [
    {"t":0.6, "name":"stadium_ambience_faint"}
  ],
  "camera": "static_tv_pushin_or_medium_ground",
  "lighting": "flat_clean",
  "prompt": "Doodle cricket loneliness: TV viewers isolated or solo fumble; minimal props; no baked text.",
  "transition_in": "cross_dissolve",
  "transition_out": "tv_frame_to_event_card_morph",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1013,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos, minimal background"
}
```


