Metropolitan Technical Showdown 2026 website

Files:
- index.html: responsive website with section-by-section colour themes, character-level heading reveals, smooth navigation, high-contrast Coming Soon banner and embedded video player.
- technical-skills-showdown-2026-logo.svg: event logo.
- metropolitan-logo.png, canon-logo.png: brand assets.
- field-engineer-copier-scene.png: photographic engineer/copier hero scene.
- sanjika-perera.png, thilanka-warnakulasooriya.png: leadership portraits.
- canon-copier.png: copier visual asset.

Countdown setup:
Open index.html and find `const EVENT_DATE = '';` near the end. When the official event date and time are approved, set it to an ISO date with timezone, e.g. `const EVENT_DATE = '2026-12-15T09:00:00+05:30';`. Until then the site displays “Event date to be announced” and no countdown timer.

Video:
The previous-showdown video remains embedded using YouTube's privacy-enhanced iframe. Playback is subject to the video's availability and embedding permissions. The site cannot override restrictions imposed by YouTube or the video owner.

Publish:
Upload all files in this folder together to your HTTPS hosting or GitHub Pages. Do not upload only index.html; the images and SVG logo are required.
