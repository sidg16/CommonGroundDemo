NIKATAM — Chunk 08D: Product — Businesses (≈2.5s)

[Purpose]
Solve the micro‑business problem: get seen where it matters, hyperlocally.

[Timing]
0:32.5–0:35.0 (flex ±0.2s).

[Global Settings]
- Engines: Veo3 or InVideo
- Art: doodle animation; strict stickman; cream paper #fff3e0; thin graphite #0E1012 (2–3 px) with 1–2 px jitter; pencil textures; no gradients; no baked text/logos.
- Format: 1920×1080 (16:9), 24 fps, Rec.709 gamma 2.4; subtle film grain ≈2%.
- Transitions default: in 0.25s, out 0.30s; easing cubic‑bezier(0.2,0.8,0.2,1).
- Audio mix: 48 kHz; −16 LUFS; peaks ≤ −1 dBTP; VO duck −6 dB; SFX −3 dB vs music.
- Negative prompts: no watermarks; no crowds/clutter; no extra captions; no third‑party logos.

 
[Visuals]
- Split UI (half–half screen): left shows a local bakery card “Open for bookings”; right shows a tuition card “Open for bookings”.
- Tap ‘Book’ on the bakery side; subtle confirmation tick. Tuition side shows ‘Message’ hover to suggest alternatives.
- Quick 0.3s insert: pastry/bag handoff (ties to Micro‑wins later).
 - Optional micro-badge: after the Book tick, flash “Seen by 32 neighbours” for ~0.6s above the bakery card OR a small “Neighbourhood picks” pill.

[On-screen Text (OST)]
- Lower left: “Local businesses seen where it matters”.

[Voiceover (VO)]
- 0:00.6: “Give micro‑businesses a storefront in the neighbourhood—be known, be booked, grow.”

[Music & SFX]
- Music: small uplift.
- SFX: soft slide; confirm chime.

[Camera / Lighting]
- Camera: static UI; micro parallax on card.
- Lighting: soft studio.



[Generator Prompt]
“Doodled phone UI split half–half: left bakery ‘Open for bookings’, right tuition ‘Open for bookings’. Tap ‘Book’ on bakery → subtle confirmation tick; tuition shows ‘Message’ hover. Hand‑drawn frame, minimal icons; pencil shadows; 300–350ms micro‑interactions; no baked text/logos.”

[JSON Shot Spec]
```json
{
  "id": 13,
  "label": "Product — Businesses",
  "duration_s": 2.5,
  "fps": 24,
  "resolution": "1920x1080",
  "engines": ["Veo3", "InVideo"],
  "vo": [{"t":0.6, "text":"Give micro‑businesses a storefront in the neighbourhood—be known, be booked, grow."}],
  "ost": [{"t":0.2, "text":"Local businesses seen where it matters", "pos":"ll"}],
  "sfx": [
    {"t":0.5, "name":"soft_slide"},
    {"t":1.2, "name":"confirm_chime"}
  ],
  "camera": "static_ui_parallax",
  "lighting": "soft_studio",
  "prompt": "Doodled split UI: bakery left (Book tap with tick), tuition right (Message hover); smooth micro‑interactions; no baked text.",
  "transition_in": "signage_to_business_card_morph",
  "transition_out": "flash_strip_in",
  "transition_in_duration_s": 0.25,
  "transition_out_duration_s": 0.25,
  "easing": "cubic-bezier(0.2, 0.8, 0.2, 1)",
  "seed": 1027,
  "negative_prompt": "no watermarks, no extra baked captions, no third-party logos"
}
```


