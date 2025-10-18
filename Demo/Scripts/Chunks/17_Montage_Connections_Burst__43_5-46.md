NIKATAM — Chunk 17: Montage — Connections Burst (0:43.5–0:46)

[Purpose]
Make the breadth of connection types feel limitless without cluttering UI.

[Timing]
0:43.5–0:46.0 (flex ±0.2s).

[Global Settings]
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

 
[Visuals]
- Doodle style: cream paper; central phone; orbiting chip tags animate and snap toward the phone.
- Chips (icons first; minimal text if needed): interests, hobbies, location, company, kids, wants.

[On-screen Text (OST)]
- None beyond minimal chip labels.

[Voiceover (VO)]
- “Connect by interests, hobbies, location, your company, your kids—just a tap away.”

[Music & SFX]
- Music: bed continues; soft whooshes as chips orbit and snap.
- SFX: light UI pops as chips settle.

[Camera / Lighting]
- Camera: static phone center; slight dolly in.
- Lighting: soft studio, high readability.



[Generator Prompt]
“Minimal phone-center composition on cream background. Orbiting connection chips (icons with minimal labels): interests, hobbies, location, company, kids, wants. Smooth motion, soft shadows, subtle whooshes. 1080p, 24fps.”

[JSON Shot Spec]
```json
{
  "id": 12,
  "label": "Montage — Connections Burst",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [],
  "ost": [],
  "sfx": [
    {"t":0.4, "name":"whoosh_soft"},
    {"t":1.2, "name":"ui_pop_soft"}
  ],
  "camera": "static_phone_center",
  "lighting": "soft_studio",
  "prompt": "Doodle phone centered; orbiting chips (icons minimal labels) for interests, hobbies, location, company, kids, wants; soft whooshes/pops; no baked text.",
  "transition_in": "straight_cut",
  "transition_out": "dissolve_to_micro_wins",
  "transition_in_duration_s": 0.1,
  "transition_out_duration_s": 0.2,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1032,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


