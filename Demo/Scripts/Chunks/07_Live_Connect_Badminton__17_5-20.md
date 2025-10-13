NIKATAM — Chunk 07: Live — Connect (Badminton) (0:17.5–0:20)

Purpose
Show the immediate human outcome of Connect: the first shared hit in a doubles rally.

Timing
0:17.5–0:20.0 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1021

Visuals
- Doodle animation two-beat micro-montage (within 2.5s):
- Beat 1 (~1.2s): match cut from avatar circle to FIRST hit of a badminton doubles rally; capture contact and shared glance.
- Beat 2 (~1.1s): carpool door opens; neighbours smile and get in; quick nod.

On-screen Text (OST)
- None.

Voiceover (VO)
- None (tail continues from Connect line).

Music & SFX
- Music: subtle lift; one crisp ‘thwack’; soft car door ‘thud’.

Camera / Lighting
- Camera: handheld‑like doodle jitter (very subtle); close framing.



Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. First hit in a badminton doubles rally between neighbours; capture contact and shared glance; thin squiggly lines, pencil texture, cream paper; no baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 7,
  "label": "Live Payoff — Connect (Badminton)",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":0.1, "text":"A quick hello becomes a rally… and a shared ride."}],
  "ost": [],
  "sfx": [{"t":0.6, "name":"shuttle_thwack"}, {"t":1.8, "name":"car_door_thud_soft"}],
  "camera": "handheld_like_close",
  "lighting": "neutral",
  "prompt": "Doodle badminton doubles rally first hit; contact + shared glance; pencil texture; no baked text.",
  "transition_in": "match_cut_from_avatar",
  "transition_out": "swipe_to_feed",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1021,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


