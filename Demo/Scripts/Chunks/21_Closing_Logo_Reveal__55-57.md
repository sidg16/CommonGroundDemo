NIKATAM — Chunk 15: Closing — Logo Reveal (0:55–0:57)

Purpose
Bridge from real-life back to identity; anchor the brand mark.

Timing
0:55–0:57 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Visuals
- Doodle style: smooth pull-back into a doodled neighborhood map (cream paper, pencil lines).
- A doodled “NIKATAM” wordmark is drawn-on (pencil line) at center.

On-screen Text (OST)
- Logo lockup: “NIKATAM”.

Voiceover (VO)
- 0:55.6: “Nikatam.” (short, confident) [pause ~0.4s]

Music & SFX
- Music: musical swell under reveal.
- SFX: soft rising whoosh.

Camera / Lighting
- Camera: smooth pull-back; slight parallax on map lines.
- Lighting: clean pastel sketch aesthetic; glowing dots.

Transitions
- In: straight cut from wide neighborhood.
- Out: hold into tagline panel; next chunk morphs doodled logo/lines to clean vector.

Generator Prompt (Sora/Veo3)
“Doodle animation: smooth pull-back to a hand-sketched neighborhood map on cream paper, warm pastels, small glowing orange dots. A doodled ‘NIKATAM’ wordmark is drawn-on (pencil line). No baked captions. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 15,
  "label": "Closing — Logo Reveal",
  "duration_s": 2,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":55.6, "text":"Nikatam."}],
  "ost": [{"t":55.5, "text":"NIKATAM", "pos":"center", "style":"logo_lockup"}],
  "sfx": [{"t":55.4, "name":"rising_whoosh"}],
  "camera": "smooth_pull_back",
  "lighting": "pastel_glow",
  "prompt": "Doodled map pull-back; doodled ‘NIKATAM’ drawn-on; warm pastels.",
  "transition_in": "straight_cut",
  "transition_out": "hold",
  "transition_out_duration_s": 0.3,
  "seed": 1040
}
```


