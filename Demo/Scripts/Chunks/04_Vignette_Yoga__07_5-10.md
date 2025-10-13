NIKATAM — Chunk 04: Vignette — Yoga (0:07.5–0:10)

Purpose
Show everyday isolation around wellness; set up Activities solution.

Timing
0:07.5–0:10.0 (flex ±0.3s).

Global Settings (paste into generator)
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Phone/UI: hand‑drawn phone frame; large chips/buttons; micro‑interactions 300–350 ms.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

Per‑chunk Overrides
- Seed: 1012

Visuals
- Six stacked house windows: each stick-person attempts an awkward yoga pose.
- Quick wobble gag on two windows; one peeks toward off-screen (neighbour sounds), then resumes pose.
- Keep lines thin; minimal props (mat texture only) to set up later mat-to-UI transition.

On-screen Text (OST)
- Flash at ~0:01.0: “Together would be better” (short, small).

Voiceover (VO)
- 0:00.3: “Together, they could stretch…”
- 0:01.6: “Instead… they sit apart.”
- Delivery: gentle, observational; keep lines very short.

Music & SFX
- Music: maintain bed; light tom or breath accent on wobble.
- SFX: small ‘oom’ strain; faint neighbour ambience (very subtle).

Camera / Lighting
- Camera: stacked grid; slight handheld micro‑breathe.
- Lighting: flat clean; stick-figure palette.

Transitions
- In: cross-dissolve from commute if reordered, else standard line-morph.
- Out: yoga mat texture wipes into Activities card (later product section).

Generator Prompt (Veo3/InVideo)
“Doodle animation per StyleGuide. Six stacked windows; simple yoga poses; two wobble; one peeks off‑screen then resumes. Thin squiggly graphite, pencil fills; cream paper; minimal props (mat texture). No baked text/logos. 1080p, 24fps.”

JSON Shot Spec
```json
{
  "id": 4,
  "label": "Vignette — Yoga (Problems)",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [
    {"t":0.3, "text":"Together, they could stretch…"},
    {"t":1.6, "text":"Instead… they sit apart."}
  ],
  "ost": [{"t":1.0, "text":"Together would be better", "pos":"center", "style":"small_fade"}],
  "sfx": [
    {"t":0.6, "name":"yoga_oom"},
    {"t":1.2, "name":"neighbour_ambience_faint"}
  ],
  "camera": "stacked_grid",
  "lighting": "flat_clean",
  "prompt": "Doodle yoga stack; minimal props (mat texture); subtle wobble; no baked text.",
  "transition_in": "cross_dissolve_or_line_morph",
  "transition_out": "yoga_mat_wipe_to_activities",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.3,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1012,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos, minimal background"
}
```


