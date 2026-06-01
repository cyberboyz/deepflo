# deepflo

> *breathe with precision*

A minimalist, open-source breathing exercise app with 0.1-second timing precision and multiple instrument sound cues. No accounts. No ads. No noise.

---

## What it does

deepflo guides you through breathing patterns — inhale, hold, exhale, hold — with exact timing you control down to a tenth of a second. Each phase can be marked with a different musical instrument cue so your ears lead and your mind follows.

---

## Logo concept

```
  d e e p f l o
  ~~~~~~~~~~~
       〜
      〰〰
     〰〰〰
```

**Mark 1 — The deepening wave**
A single sine wave that drops and widens as it moves right — shallow at the *d*, deepest at the *o*. Wordmark only, lowercase, tracking slightly wide. No icon needed at launch.

**Mark 2 — The breath line**
One horizontal line that dips into a smooth U-curve at the center — like a lung filling. Works at 16px favicon size. Monochrome first, teal accent optional.

**Mark 3 — Stacked letterform**
`df` ligature where the crossbar of *f* becomes the crest of a wave bleeding into the descender of *d*. Bold, geometric, timeless.

**Color direction**
- Primary: `#0d1f2d` (deep ocean night)
- Accent: `#4ecdc4` (breath teal)
- Surface: `#f7f9fb` (clean air)
- Dark mode default — feels right for a breathing app you open at 2am

**Typography**
- Wordmark: [Geist](https://vercel.com/font) or [Inter](https://rsms.me/inter/), lowercase, weight 300–400
- Never bold the wordmark — lightness is the point

---

## Tagline options

| Tagline | Tone |
|---|---|
| *breathe with precision* | Clean, functional |
| *slow down on purpose* | Intentional, calm |
| *your rhythm, exactly* | Personal, confident |
| *go deeper, every breath* | Evocative |
| *the breath you control* | Empowering |
| *flow on your terms* | Soft, modern |

**Recommended:** `breathe with precision` — says everything, says nothing extra.

---

## Features

- **0.1s precision** on all four breath phases: inhale · hold in · exhale · hold out
- **5 built-in presets**: 4-7-8, Box, Calm, Wim Hof, Deep
- **9 instrument cues**: Sine Tone, Bell, Singing Bowl, Flute, Wind Chime, Ocean Drone, Breath, Harp Glide, Silent
- **Per-phase sound assignment** — different note pitch per phase
- **Animated breathing orb** with expanding/contracting visual feedback
- **Cycle counter** with dot progress indicator
- **Light / dark mode** toggle
- **Fullscreen mode**
- **Zero dependencies** — pure HTML, CSS, Web Audio API

---

## Getting started

### Use it instantly

Open `index.html` in any modern browser. No build step, no install, no server needed.

### Deploy to Vercel (30 seconds)

1. Fork or clone this repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Click **Deploy** — done

Or drag `index.html` straight into the Vercel dashboard.

### Run locally

```bash
git clone https://github.com/yourusername/deepflo
cd deepflo

# Option A — Python (built-in)
python3 -m http.server 3000

# Option B — Node
npx serve .

# Option C — just open the file
open index.html
```

---

## Breath presets

| Preset | Inhale | Hold in | Exhale | Hold out | Best for |
|---|---|---|---|---|---|
| 4-7-8 | 4.0s | 7.0s | 8.0s | 0.0s | Sleep, anxiety relief |
| Box | 4.0s | 4.0s | 4.0s | 4.0s | Focus, stress reset |
| Calm | 5.0s | 0.0s | 5.0s | 0.0s | Everyday use |
| Wim Hof | 2.0s | 0.0s | 2.0s | 0.0s | Energy, activation |
| Deep | 6.0s | 2.0s | 8.0s | 0.0s | Deep relaxation |
| Custom | — | — | — | — | Your own pattern |

---

## Instrument reference

| Instrument | Character | Good for |
|---|---|---|
| Sine Tone | Pure, clean | Focus sessions |
| Bell | Decaying shimmer | Meditation |
| Singing Bowl | Slow, harmonic | Deep relaxation |
| Flute | Breathy, warm | Gentle practice |
| Wind Chime | Cascading arpeggio | Stress relief |
| Ocean Drone | Low filtered pad | Sleep / background |
| Breath | Shaped white noise | Breath awareness |
| Harp Glide | Ascending arpeggio | Morning sessions |
| Silent | No audio | Visual-only |

---

## File structure

```
deepflo/
└── index.html      # the entire app — one file
```

That's it. Everything — layout, logic, audio engine — lives in one file. No frameworks, no bundler, no `node_modules`.

---

## Browser support

| Browser | Support |
|---|---|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari (iOS + macOS) | ✅ Full |
| Samsung Internet | ✅ Full |

Requires Web Audio API — supported in all modern browsers since 2013.

---

## Roadmap

- [ ] URL state — share custom patterns via link (e.g. `deepflo.app/?in=5.5&out=7.0`)
- [ ] PWA support — install to home screen, offline use
- [ ] Guided session presets (5 min, 10 min, 20 min)
- [ ] Haptic feedback on mobile
- [ ] Custom session name saving (localStorage)
- [ ] Stats page — sessions, total breath time
- [ ] Background audio mode (screen off)

---

## Contributing

PRs welcome. Keep it simple — this app's power is that it's one file. Any contribution should respect that philosophy.

```bash
git checkout -b feature/your-idea
# make changes to index.html
git commit -m "feat: your idea"
git push origin feature/your-idea
# open a PR
```

---

## Philosophy

Most breathing apps are too much. Timers, streaks, subscriptions, notifications, onboarding flows. deepflo does one thing: it counts your breath, plays a sound, and gets out of the way.

The 0.1s precision isn't a gimmick — when you're trying to hit a 5.5s exhale, rounding to 6 feels wrong. Your nervous system notices.

---

## License

MIT — use it, fork it, ship it, make it your own.

---

## Acknowledgements

Inspired by [xhalr.com](https://xhalr.com) by Hamilton Cline — the original, the OG.

---

*deepflo — breathe with precision*
