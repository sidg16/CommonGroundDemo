NIKATAM — Chunk 09: Live — Yoga Together (0:24–0:27)

[Purpose]
Make Activities feel tangible: a small group with an instructor, together.

[Timing]
0:24.0–0:27.0 (flex ±0.2s).

[Global Settings]
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

- [Visuals]
- Doodle animation: small yoga group + instructor; instructor gives a clear cue (hand gesture) and the group moves into one gentle synchronized pose.
- Keep wardrobe simple, natural smiles; no branding.

[On-screen Text (OST)]
- None.

[Voiceover (VO)]
- “Morning turns from plan to practice, with an instructor.”

[Music & SFX]
- Music: same bed; add a soft inhale/exhale layer.
- SFX: subtle ambient birds/leaf rustle.

[Camera / Lighting]
- Camera: slow lateral slide; shallow DOF; brief focus pull from instructor to group.
- Lighting: golden-hour or soft morning light.



[Generator Prompt]
“Doodle animation per StyleGuide. Small group with instructor outdoors; one gentle synchronized pose; thin squiggly graphite; cream paper; minimal props; no baked text/logos. 1080p, 24fps.”

[JSON Shot Spec]
```json
{
  "id": 9,
  "label": "Live Payoff — Yoga Together",
  "duration_s": 3.0,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [],
  "vo": [{"t":0.1, "text":"Morning turns from plan to practice, with an instructor."}],
  "ost": [],
  "sfx": [
    {"t":0.6, "name":"birds_soft"}
  ],
  "camera": "slow_lateral_slide",
  "lighting": "soft_morning_or_golden_hour",
  "prompt": "Doodle yoga group with instructor, one synchronized pose; soft light; pencil texture; no baked text.",
  "transition_in": "match_cut_from_activities_card",
  "transition_out": "swipe_back_to_phone",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1023,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


