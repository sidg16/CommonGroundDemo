NIKATAM — Chunk 16: Closing — Tagline, Waitlist, Fade (0:57–1:00)

Purpose
Deliver tagline and waitlist CTA; finish with a gentle fade.

Timing
0:57–1:00 (flex ±0.2s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Visuals
- Start with doodled logo/map held from previous.
- Over ~0.8s, the doodled logo and lines morph to clean vector (crisper edges, subtle glow settles).
- Tagline reveals below: “Coming soon — to your neighbourhood”.
- Visual CTA button graphic appears: “Join waitlist” (visual only).
- Final quick fade to black; logo holds faintly on the last frame.

On-screen Text (OST)
- “Join the waitlist: [website placeholder]” (small).

Voiceover (VO)
- 0:58.0: “Coming soon to your neighbourhood.” (final, warm)

Music & SFX
- Music: sustain; small final melodic bell.
- SFX: subtle UI sparkle on CTA appearance.

Camera / Lighting
- Camera: locked; minimal micro-drift on logo.
- Lighting: soft glow; clean contrast for readability.

Transitions
- In: hold from logo reveal.
- Out: fade to black.

Generator Prompt (Sora/Veo3)
“Cream paper background. Hold doodled ‘NIKATAM’ from previous, then morph it into a clean vector logo over ~0.8s, settling with a soft professional glow. Reveal the tagline ‘Coming soon — to your neighbourhood’ and a visual-only ‘Join waitlist’ CTA button. No extra text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 16,
  "label": "Closing — Tagline & Waitlist",
  "duration_s": 3,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":58.0, "text":"Coming soon to your neighbourhood."}],
  "ost": [
    {"t":57.2, "text":"Coming soon — to your neighbourhood", "pos":"center"},
    {"t":57.6, "text":"Join the waitlist: [website placeholder]", "pos":"bc", "style":"small"}
  ],
  "sfx": [{"t":57.5, "name":"ui_sparkle_subtle"}],
  "camera": "locked_micro_drift",
  "lighting": "soft_glow",
  "prompt": "Morph doodled logo to clean vector over 0.8s; reveal tagline + visual CTA; cream background; minimal motion.",
  "transition_in": "hold",
  "transition_out": "fade_to_black",
  "transition_in_duration_s": 0.0,
  "transition_out_duration_s": 0.3,
  "seed": 1041
}
```


