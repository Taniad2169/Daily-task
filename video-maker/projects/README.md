# Video Maker projects (made by Claude for Tania)

Each `.json` file is one video project; `index.json` lists what shows in "📥 Videos Claude made for you".

Project format:
- `title`, `brand` (`ws` The WebSwan, `ds` Digital Solutions, `mn` Media Network), `format` (`9:16`, `1:1`, `16:9`)
- `template` (true = reusable template), `transDef` (fade, circle, slide, zoom, wipe, stars, flash, blur, none)
- `captions`, `karaoke`, `endCard` (true/false), `cta`, `contact`
- `scenes`: `[{ text, action, trans, cap, dur, avatar }]`
  - `avatar`: `"selected"` (her tapped photo), `"Folder name:3"` (photo 3 in that album folder), or empty
  - `action`: what Tania does on camera (used by lip sync / Jimmy-style options)

Rules for scripts: "Tania" only (no last name), no prices, no legal or medical advice, never say a site is or isn't compliant.
