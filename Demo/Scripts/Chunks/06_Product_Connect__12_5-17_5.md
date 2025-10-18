NIKATAM — Chunk 06: Product — Connect Feature (0:12.5–0:17.5)

[Purpose]
Introduce the Connect feature: match neighbours via interest tags and quick hello.

[Timing]
0:12.5–0:17.5 (flex ±0.3s).

[Global Settings]
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

 
[Visuals]
- Centered phone mockup slides in from the right.
- Home screen shows profile card with interest tags: “Badminton”, “Yoga”, “Tutoring”.
- Badge shows: “12 neighbours match”.
- Finger taps “Connect”; modal pops with two neighbouring profiles and one-tap “Say Hi”.
 - Optional detail: dashboard cluster from Commute morph resolves into the “Connect” button to preserve continuity.

[On-screen Text (OST)]
- Lower third: “Connect with neighbours by interest”.

[Voiceover (VO)]
- 0:25.2: “Nikatam connects neighbours instantly—through shared interests—everyone connects.”
- Delivery: clear, slightly brighter tone — relief.

[Music & SFX]
- Music: keep bed; add subtle uplift at the tap moment.
- SFX: soft UI tap ‘click’; tag ‘pop’.

[Camera / Lighting]
- Camera: slight push-in during modal; micro parallax on cards.
- Lighting: clean studio; soft shadows.



[Generator Prompt]
“Doodled phone UI on cream paper (per StyleGuide). Home shows interest tag chips ‘Badminton’, ‘Yoga’, ‘Tutoring’; badge ‘12 neighbours match’. Tap ‘Connect’ reveals doodled modal with two neighbour profiles and ‘Say Hi’. Smooth micro‑interactions (300–350ms), soft pencil shadows, minimal design. No baked text/logos.”

[JSON Shot Spec]
```json
{
  "id": 6,
  "label": "Product — Connect",
  "duration_s": 5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":25.2, "text":"Nikatam connects neighbours instantly—through shared interests—everyone connects."}],
  "ost": [{"t":25.4, "text":"Connect with neighbours by interest", "pos":"ll"}],
  "sfx": [
    {"t":26.0, "name":"ui_tap_soft"},
    {"t":26.1, "name":"tag_pop"}
  ],
  "camera": "slight_push_in",
  "lighting": "soft_studio",
  "prompt": "Doodled phone UI: tags Badminton/Yoga/Tutoring, ‘12 neighbours match’, tap Connect -> modal with two profiles + Say Hi; 300–350ms micro‑interactions; dashboard‑to‑Connect morph continuity; no baked text.",
  "transition_in": "tv_to_phone_morph",
  "transition_out": "match_cut_avatar_to_live_then_swipe_to_feed",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1020,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


