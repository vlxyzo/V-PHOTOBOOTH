# V-Photobooth 📸

A fun, interactive web-based photobooth experience. Snap 4 pics, customize the layout, pick your vibe—and boom, you got yourself a shareable memory.

## What's This About?

Ever wanted a photobooth but didn't have a booth? Yeah, me too. So I built one.

**V-Photobooth** lets you:
- 📷 Take 4 selfies with a real countdown timer
- 🎨 Choose between classic strip (1×4) or modern grid (2×2) layouts
- 🌈 Pick your frame color (White, Black, or Soft Pink)
- ✨ Apply filters (Natural, Vintage, B&W, or Sharpen Glow)
- 📐 Play with different aspect ratios (3:4, 4:3, 9:16, 16:9)
- 💾 Download your final creation as a high-quality JPEG

## Quick Start

Just open `index.html` in your browser. No backend, no complicated setup. Everything runs locally.

```bash
# Clone it
git clone https://github.com/itsmekenzzx/V-PHOTOBOOTH.git
cd V-PHOTOBOOTH

# Open in browser
# Windows: start index.html
# Mac: open index.html
# Linux: xdg-open index.html
```

Or visit it online if you host it somewhere.

## How It Works

1. **Customize** — Pick your layout and frame color
2. **Filter & Ratio** — Choose the perfect filter and aspect ratio
3. **Camera** — Allow camera access and hit the shutter button
4. **Countdown** — 3...2...1... Smile! (happens 4 times)
5. **Download** — Save your masterpiece and share it

## Tech Stack

- Vanilla HTML/CSS/JavaScript (no frameworks, no dependencies... except for confetti 🎉)
- Canvas API for image compositing
- getUserMedia API for camera access
- CSS animations and gradient effects
- Canvas-confetti for that celebratory moment

## Features

✅ Real-time camera preview with mirroring  
✅ Live filter preview  
✅ Responsive design (works on desktop & mobile)  
✅ Custom font styling (Playfair Display, Plus Jakarta Sans)  
✅ Dark theme with pink accents  
✅ Flash effect on photo capture  
✅ High-quality output rendering  
✅ Instant downloads  

## Customization

Wanna change colors? Open `index.html` and look for the `:root` section in the CSS:

```css
:root {
    --bg: #0a0a0a;
    --surface: #161616;
    --primary: #ff477e;
    --text: #ffffff;
    --border: #2a2a2a;
}
```

Tweak these values and you're good.

## Browser Support

Works on:
- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Most modern mobile browsers ✅

(You'll need to allow camera access though)

## Known Quirks

- Mobile browsers might handle aspect ratios differently—totally normal
- Some older devices might struggle with real-time filters—but the final output will still be crisp
- Always download before closing the tab (the canvas data isn't persistent... yet)

## License

MIT License. Do whatever you want with it.

---

**Made by Velix** • 2026

Got feedback? Found a bug? Want to collab?

📧 **Email:** nxtzyrex@gmail.com  
📱 **Instagram:** [@vlxyzoo](https://www.instagram.com/vlxyzoo)  
💬 **Telegram:** [Join the channel](https://t.me/vlxzo)

---

Have fun capturing memories! 🎬✨
