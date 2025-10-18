NIKATAM — Chunk 14A: Montage — Multi‑Context Workspaces (≈2.5–3.0s)

[Purpose]
Show that the app works in any hyperlocal circle: Society → Company → College.

[Timing]
0:52.5–0:55.0 (flex ±0.2s).

[Global Settings]
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

 
[Visuals]
- A small group remains centered; the background parallax wallpaper swaps: Housing Society signage → Company lobby signage → College noticeboard.
- The phone top nav shows a “Workspace” dropdown; a tap cycles contexts (no heavy text).
 - Use signage names: “Your Society”, “Your Company”, “Your College”.

[On-screen Text (OST)]
- None; rely on signage and UI affordance.

[Voiceover (VO)]
- None (keep visual demonstration crisp).

[Music & SFX]
- Music: bed continuous; light UI ‘select’ tick on workspace change.
- SFX: subtle ambience changes per context (hallway vs lobby vs campus), very soft.

[Camera / Lighting]
- Camera: locked center; subtle parallax on background swap.
- Lighting: neutral bright indoor.



[Generator Prompt]
“Clean minimal composition: same small group center; background signage swaps across Housing Society → Company → College; phone UI top nav shows a Workspace selector tapped to cycle contexts. Soft shadows, subtle parallax, no text overlays. 1080p, 24fps.”

[JSON Shot Spec]
```json
{
  "id": 20,
  "label": "Montage — Multi-Context Workspaces",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [],
  "ost": [],
  "sfx": [
    {"t":0.6, "name":"ui_select_tick"}
  ],
  "camera": "locked_center_parallax_bg",
  "lighting": "neutral_bright_indoor",
  "prompt": "Same group; signage swaps Stick Society -> Stick Company -> Stick College; phone Workspace selector tap cycles contexts; no baked text.",
  "transition_in": "dissolve",
  "transition_out": "cut_to_logo",
  "transition_in_duration_s": 0.2,
  "transition_out_duration_s": 0.1,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1035,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


