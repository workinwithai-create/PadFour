# PadFour

Four-bar live pad desk for bedroom producers and AI-music finishers.

Suno and loop DAWs give you a bed that collapses without air. Session players write four live bars of sustained pads — violin holds, string swells, layered pads — so the section has space and finishes.

Live samples only: FluidR3 piano, upright bass, nylon guitar, trumpet, violin, and acoustic kit from the PreEight sample bank pinned to commit `d58301e4a494555f411a2afbc448b724136eee76`.

No oscillators. Audio never leaves the tab. Loop-ready samples with real attack/release envelopes.

## Distinct from yesterday and the line

| Tool | Job |
|------|-----|
| MelodyFour | Four-bar melodic phrase |
| RestFour | Intentional rests so the return lands |
| CrashFour | Fills and crashes |
| SpaceFour | Air by thinning |
| HushFour | Near-silence |
| **PadFour** | Four bars of live sustained pads so the bed has air and the track finishes |

Yesterday's ship was a different arrangement desk. PadFour is the missing sustain that makes the bed feel finished.

## Pricing recommendation

One-time **$29** on Lemon Squeezy (merchant of record). Mirror on Gumroad.

Do not subscribe. Forge Pass stays the $24/mo cloud bundle for AuraMix / MixForge.

This is a finite desk. Current build is free (no license gate). A priced build would require a Lemon Squeezy or Gumroad key check.

Best place to sell: Lemon Squeezy checkout linked from the Vercel landing + a pinned X demo. Bedroom producers and Suno finishers already buy one-shot desks this way.

## Export (production-ready milestone)

Default 48 kHz, 24-bit stereo WAV. At 92 BPM / 8 bars the file is exactly 1,001,739 samples. First downbeat at sample 0. Tail folded for seamless loop. Peak ≤ -1 dBFS. Matching MIDI with tempo, time signature, and chair tracks. OfflineAudioContext uses the same schedule path as live playback and the already-loaded raw ArrayBuffers (never re-downloads).

## Samples

Pinned commit SHA only. Never `@main` or `@gh-pages`.

## License

MIT. workinwithai-create.
