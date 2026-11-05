# Aleksandar Atanasov — Portfolio (v15)

Static portfolio for Cloudflare Pages / GitHub Pages.

## Video previews
- Desktop: muted previews start on hover/focus and stop when the pointer leaves.
- Mobile/touch: the most visible project preview starts when at least 62% of its card enters the viewport; it stops when mostly out of view. Only one mobile preview plays at a time.
- **Измами ме (project 03)** now streams directly from the supplied Cloudflare R2 MP4 using a native HTML5 video element for its hover/scroll preview. Its WATCH FILM link opens the same R2 MP4.
- The other project previews remain muted YouTube embeds. Preview media is created on demand and removed on pause.
- The R2 object must remain publicly readable for the preview and WATCH FILM link to work.

## Deploy
Upload the contents of this folder to the existing GitHub repository connected to Cloudflare Pages. No build step is required.
