# The Heath's Vryburg M.C.C.

The club website. It's a single page, `index.html`, published with GitHub Pages
every time a change lands on `main`.

Live site: https://tzablaze.github.io/The-Heath-s.github.io/

## Updating the site

Club details live near the bottom of `index.html`, in the block marked
`EDIT THESE`:

- `whatsapp`, `email`, `facebook`, `instagram`: contact links. Anything left
  empty is hidden on the site.
- `meeting`, `rideDay`: where and when the club usually rides.
- `form`: a link to a join form (for example a Google Form).
- `album`: a link to a shared photo album.
- `GALLERY`: photos for the Gallery page, one per line, like
  `['images/gallery/small/ride-1.jpg', 'Sunday breakfast run', 'images/gallery/ride-1.jpg'],`
  The first picture is the small version shown on the page; the last one is
  the full-size picture that opens when tapped, and can be left out. The first
  three photos also appear on the home page.
- `EVENT_PHOTOS`: photos from a past event, in the same format, under that
  event's name (for example `'mielie-300'`).

Pictures go in the `images` folder.

## Events

The Mielie 300 Run moves itself to "Past events" the day after the run
(8 November 2026). The dates are set by `data-until` and `data-from` on those
sections of `index.html`; copy the same pattern for the next event.

Each page has its own link, for example `#events` or `#join`, so you can share
a page directly.
