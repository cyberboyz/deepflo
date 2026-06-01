# deepflo

> *breathe with precision*

A minimalist, open-source breathing exercise app with 0.1-second timing precision and multiple instrument sound cues. No accounts. No ads. No noise.

---

## what it does

deepflo guides you through breathing patterns — inhale, hold, exhale, hold — with exact timing you control down to a tenth of a second. Each phase can be marked with a different musical instrument cue so your ears lead and your mind follows.

---

## logo concept

```
  d e e p f l o
  ~~~~~~~~~~~
       〜
      〰〰
     〰〰〰
```

**Mark 1 — The Deepening Wave**
A single sine wave that drops and widens as it moves right — shallow at the *d*, deepest at the *o*. Wordmark only, lowercase, tracking slightly wide. No icon needed at launch.

**Mark 2 — The Breath Line**
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

## tagline options

| tagline | tone |
|---|---|
| *breathe with precision* | clean, functional |
| *slow down on purpose* | intentional, calm |
| *your rhythm, exactly* | personal, confident |
| *go deeper, every breath* | evocative |
| *the breath you control* | empowering |
| *flow on your terms* | soft, modern |

**Recommended:** `breathe with precision` — says everything, says nothing extra.

---

## features

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

## getting started

### use it instantly

Open `index.html` in any modern browser. No build step, no install, no server needed.

### deploy to Vercel (30 seconds)

1. Fork or clone this repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Click **Deploy** — done

Or drag `index.html` straight into the Vercel dashboard.

### run locally

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

## breath presets

| preset | inhale | hold in | exhale | hold out | best for |
|---|---|---|---|---|---|
| 4-7-8 | 4.0s | 7.0s | 8.0s | 0.0s | sleep, anxiety relief |
| Box | 4.0s | 4.0s | 4.0s | 4.0s | focus, stress reset |
| Calm | 5.0s | 0.0s | 5.0s | 0.0s | everyday use |
| Wim Hof | 2.0s | 0.0s | 2.0s | 0.0s | energy, activation |
| Deep | 6.0s | 2.0s | 8.0s | 0.0s | deep relaxation |
| Custom | — | — | — | — | your own pattern |

---

## instrument reference

| instrument | character | good for |
|---|---|---|
| Sine Tone | Pure, clean | focus sessions |
| Bell | Decaying shimmer | meditation |
| Singing Bowl | Slow, harmonic | deep relaxation |
| Flute | Breathy, warm | gentle practice |
| Wind Chime | Cascading arpeggio | stress relief |
| Ocean Drone | Low filtered pad | sleep / background |
| Breath | Shaped white noise | breath awareness |
| Harp Glide | Ascending arpeggio | morning sessions |
| Silent | No audio | visual-only |

---

## file structure

```
deepflo/
└── index.html      # the entire app — one file
```

That's it. Everything — layout, logic, audio engine — lives in one file. No frameworks, no bundler, no `node_modules`.

---

## browser support

| browser | support |
|---|---|
| Chrome / Edge | ✅ full |
| Firefox | ✅ full |
| Safari (iOS + macOS) | ✅ full |
| Samsung Internet | ✅ full |

Requires Web Audio API — supported in all modern browsers since 2013.

---

## roadmap

- [ ] URL state — share custom patterns via link (e.g. `deepflo.app/?in=5.5&out=7.0`)
- [ ] PWA support — install to home screen, offline use
- [ ] Guided session presets (5 min, 10 min, 20 min)
- [ ] Haptic feedback on mobile
- [ ] Custom session name saving (localStorage)
- [ ] Stats page — sessions, total breath time
- [ ] Background audio mode (screen off)

---

## contributing

PRs welcome. Keep it simple — this app's power is that it's one file. Any contribution should respect that philosophy.

```bash
git checkout -b feature/your-idea
# make changes to index.html
git commit -m "feat: your idea"
git push origin feature/your-idea
# open a PR
```

---

## philosophy

Most breathing apps are too much. Timers, streaks, subscriptions, notifications, onboarding flows. deepflo does one thing: it counts your breath, plays a sound, and gets out of the way.

The 0.1s precision isn't a gimmick — when you're trying to hit a 5.5s exhale, rounding to 6 feels wrong. Your nervous system notices.

---

## license

MIT — use it, fork it, ship it, make it your own.

---

## acknowledgements

Inspired by [xhalr.com](https://xhalr.com) by Hamilton Cline — the original, the OG.

---

*deepflo — breathe with precision*
