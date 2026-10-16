# Saran & Anitha – Digital Wedding Invitation

An animated wedding invitation: burgundy-and-gold envelope with a wax seal (your SA logo), a letter that comes out and dissolves into the cover, floral mandap artwork with parallax, falling petals, gold-foil scratch cards for the dates, an invitation card and a timeline.

## Files
| File | What it is |
|---|---|
| `index.html` | The editable site. Loads pictures from the `assets/` folder. |
| `invitation-standalone.html` | Same site as ONE file (pictures built in, about 2.7 MB). Easiest to send or upload. |
| `assets/floral-mandap.jpg` | Cover artwork. |
| `assets/envelope-floral-frame.webp` | Embossed floral frame on the envelope. |
| `assets/frame-clean.webp` | Same frame without the centre circle (used on the invitation card). |
| `assets/logo-sa.webp` | Your SA monogram, cropped round for the seal and letter. |
| `assets/tum-tum-instrumental-clip.mp3` | 35-second trimmed instrumental clip, played on the seal tap. |
| `assets/original/` | Your original uploaded images, untouched. |

## Open it
Double-click `index.html` (keep the `assets` folder next to it) or open `invitation-standalone.html`. Use Chrome, Safari or Edge. Fonts load from Google Fonts, so you need internet for the handwriting font. Music starts only after the first tap.

## Change the details (open `index.html` in any text editor)
Search for these texts and replace them:
- Names: `Saran`, `Anitha` (appear several times)
- Dates: `19`, `20`, `NOVEMBER · 2026`, `Thursday · 19 November`, `Friday · 20 November`
- Times: `Time to be announced`, `Muhurtham time to be announced`
- Venue: `Details to be announced`
- Parents / wording: the paragraph starting `With the blessings of our elders`
- Colours: at the top of the `<style>` block, the `:root{...}` list and the section marked `/* ROYAL */`
- Music: the supplied 35-second `Tum Tum` instrumental clip loops after the seal is tapped. Replace `assets/tum-tum-instrumental-clip.mp3` to use a different recording.

## Put it online (free)
1. Go to https://app.netlify.com/drop
2. Drag the whole `saran-anitha-wedding-invitation` folder onto the page.
3. You get a link to share. (GitHub Pages and Cloudflare Pages also work.)

## Notes
- Works best on a phone in portrait orientation.
- If the images are missing, check the `assets` folder is beside `index.html`.
