# Light Gayi

**When the power goes out, the whole building lights up.**

Interactive blackout-night experience for apartment blocks.  
Concept & prototype by Chandra Pavansai for **DJXHack Everyday Magic 2026**.

## Live / Download the working prototype

Full single-file prototype (updated 9.6 version with clarity & feasibility polish):

- **Direct download / open**: [LightGayi_App_updated.html](https://drive.google.com/file/d/1MFVRTsuEJqJvayEwyFi9zxAlxPqwjduu/view?usp=drivesdk)  
  (File → Download, then open in any modern browser. Camera & mic work when opened as a local file or on a real host.)

## What works right now

- Full event creation, RSVP, join codes, results & impact dashboard
- Live wall engine (torch reveal, 12 neighbour vignettes, shadow-bird, constellation)
- Camera bright-blob torch tracking
- Microphone clap detection
- Host setup guide, safety checklist, lumen calculator
- Clear real-vs-stand-in labelling for judges

Data stays in the browser (localStorage). No server required for the core loop.

## Deploy on Vercel (recommended)

1. Download the HTML above and rename it to `index.html`
2. Create a new Vercel project
3. Upload the single file (or drag the folder)
4. Framework Preset: **Other**
5. Deploy → public URL ready

Or from this repo after placing `index.html` in root:

```bash
npx vercel --prod
```

## GitHub Pages

Settings → Pages → Source: Deploy from a branch → main / root

## Credits

Concept, direction & build: Chandra Pavansai  
AI assistance: Claude (Anthropic) for research, writing and code  
All illustrations and sounds are original and generated in code.
