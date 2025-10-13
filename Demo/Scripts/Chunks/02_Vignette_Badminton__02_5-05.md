NIKATAM — Chunk 02: Vignette — Badminton (0:02.5–0:05)

Purpose
Depict the relatable loneliness of wanting a partner for a game.

Timing
0:02.5–0:05.0 (flex ±0.3s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1010

Visuals
- Split-frame: two stick figures in separate rooms bouncing a shuttlecock against the wall.
- One synchronized miss; shuttlecocks fall in both frames.
- Brief glance across frame, wistful.

On-screen Text (OST)
- Flash ~0:01.0: “Wanted: partner” (≤0.8s)

Voiceover (VO)
- 0:00.2: “Both want a game…”
- 0:01.6: “…but end up playing badminton with themselves.”

Music & SFX
- Music: keep bed; light metronome-like tick.
- SFX: shuttlecock ‘thwack’; soft ‘plop’ on fall.

Camera / Lighting
- Camera: locked split; subtle camera drift.
- Lighting: clean flat; minimal props to keep focus on action.

Transitions
- In: cross-dissolve.
- Out: shuttlecock spins into circular avatar; morph to phone (Connect).

Generator Prompt (Sora/Veo3)
“Doodle animation (per StyleGuide). Split-frame; two simple rooms; strict stickman bouncing a shuttlecock against a wall. Comedic rhythm; synchronized miss; shuttlecocks fall; expressive but simple faces; thin squiggly graphite lines; cream paper background; ≤2 background doodles (window, plant). No baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 2,
  "label": "Vignette — Badminton",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [
    {"t":0.2, "text":"Both want a game…"},
    {"t":1.6, "text":"…but end up playing badminton with themselves."}
  ],
  "ost": [{"t":1.0, "text":"Wanted: partner", "dur":0.8, "pos":"center"}],
  "sfx": [
    {"t":0.6, "name":"shuttle_thwack"},
    {"t":1.8, "name":"shuttle_plop"}
  ],
  "camera": "locked_split",
  "lighting": "flat_clean",
  "prompt": "Doodle split rooms; shuttle bounces; synchronized miss; pencil texture; no baked text.",
  "transition_in": "cross_dissolve",
  "transition_out": "shuttle_to_avatar_phone_morph",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1010,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos, minimal background"
}
```


