NIKATAM — Chunk 01: Opening Soul (0:00–0:02.5)

Purpose
Establish hopeful tone, hand-drawn style, and the orange-dot motif before narration begins.

Timing
0:00.0–0:02.5 (flex ±0.3s). VO begins near 0:00.8.

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1001

Visuals
- Soft cream background.
- Hand-drawn outline of a neighbourhood street fades in left→right; buildings pop gently in sequence.
- A warm sun (simple circle) rises above the neighborhood.

On-screen Text (OST)
- At ~0:00.7 lower-left, small: "Imagine…"

Voiceover (VO)
- 0:00.8: “Imagine if your neighbourhood wasn’t just buildings and doors…”
- Delivery: gentle, inviting; slight pause after the ellipsis.

Music & SFX
- Music: light indie-acoustic bed (≈95 BPM) starts low; add faint melodic bells at 0:00.7.
- SFX: ambient porch wind chime very faint.

Camera / Lighting
- Camera: static with subtle parallax on the map lines.
- Lighting: soft, even daylight; pastel palette warmth.

Transitions
- In: fade-up from black.
- Out: gentle whoosh as line-art morph prepares for stick-figure world.

Generator Prompt (Veo3/InVideo)
"Doodle animation (per StyleGuide). Hand‑sketched neighborhood map on cream paper (#fff3e0), warm pastels (#9ec89b, #f08a4b). Gentle pop‑ins of buildings left→right, subtle parallax. Simple sun rises. No baked text/logos. 1080p, 24fps."

JSON Shot Spec
```json
{
  "id": 1,
  "label": "Opening Soul",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": "Imagine if your neighbourhood wasn’t just buildings and doors…",
  "ost": [{"t":0.7,"text":"Imagine…","pos":"ll","style":"small"}],
  "music": {"bed":"indie_acoustic_95bpm","bells_at":0.7},
  "sfx": [{"t":0.2,"name":"porch_chime_faint"}],
  "camera": "static_parallax",
  "lighting": "soft_daylight",
  "prompt": "Doodle map, cream paper, warm pastels, building pop-ins, rising sun; no baked text.",
  "transition_out": "whoosh_line_morph",
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1001,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


