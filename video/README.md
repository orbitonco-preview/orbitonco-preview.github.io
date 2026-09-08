Home hero video.

Drop `hero.mp4` (and optionally `hero.webm`) here and the home hero becomes a
video automatically. Leave the folder empty and the hero stays the flat dark
band — `lib/hero-media.ts` checks for the files at build time, so there is never
a broken <video> element.

The still frame goes to `public/images/hero/home.webp`. It is the <video>
poster, the prefers-reduced-motion fallback, and the page's LCP element.

See IMAGE-REQUIREMENTS.md for the encoding spec.
