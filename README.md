# Wedding Website

An animated wedding invitation site: a sealed envelope opens, the letter unrolls, and the full site appears with falling petals, a countdown, story timeline, venues, attire guide, program, entourage, FAQs, RSVP, gifts and gallery.

## Editing the content
All text lives in the `CONFIG` block near the top of the `<script>` in `index.html`:
names, date and time, venues and map links, story, attire palette, program, entourage, FAQs, reminders, RSVP form link, gift note, photos, and song.

- **RSVP:** paste the Google Form link into `rsvp.url`.
- **Photos:** upload images to a `photos/` folder in this repo, then list them, e.g. `photos: ["photos/01.jpg", "photos/02.jpg"]`.
- **Song:** upload an `.mp3` (e.g. `song.mp3`) and set `songUrl: "song.mp3"`. Leave empty for the built-in music box melody.

## Hosting
Served with GitHub Pages from the `main` branch root.

Website by Pvblicly.
