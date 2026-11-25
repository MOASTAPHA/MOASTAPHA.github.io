# Changelog

- 2026-11-17 — Site launched: palm navigation, 3 case studies, snapshots, Arabic writing, leadership, contact.
- 2026-11-17 — Added Mount Everest (Labrinth) player via the official YouTube audio.
- 2026-11-21 — Song changed to That's Life (Frank Sinatra); CV updated; LinkedIn added to contact.
- 2026-11-18 — Link previews: Open Graph / Twitter meta and a 1200x630 palm preview image for WhatsApp, LinkedIn and X.
- 2026-11-18 — Arabic writing: added all 16 Kitabh essays (حوار داخلي) with links, most-read highlighted; brand lines kept below; Kitabh linked from "me".
- 2026-11-18 — Night navy background; palm redrawn as a real date palm (arching fronds, sparse leaflets, leaf-base scars on the trunk, hanging date bunches); label legibility; refreshed preview image.
- 2026-11-18 — Living ground: grass sways and bends away from the cursor; glowing flowers reveal lines Moastapha wrote (essay titles, column name, brand lines) with links.
- 2026-11-19 — Favicon: a tiny grainy date palm on night navy with red dates (SVG + 32px PNG + Apple touch icon), plus a matching browser theme colour.
- 2026-11-19 — New test version at /keys: piano-key navigation with notes, a light beam and Moastapha's silhouette (main site untouched).
- 2026-11-19 — /keys phone layout: swipeable full keyboard with readable labels, name moved up, bottom-sheet panel, beam follows the keys while swiping.
- 2026-11-20 — Gentle wind: the palm's crown now sways a fraction of a degree in a slow, irregular breeze (GPU-only, pauses while a panel is open, off with reduced motion).
- 2026-11-21 — Hover preview: hovering or focusing a frond label softly brightens that frond on the canvas (it stays lit while its panel is open; sways with the wind, no extra animation loop).
- 2026-11-21 — Sky by Riyadh time: the night sky now shifts with the Riyadh clock — soft dawn around sunrise, a slightly lifted sky by day, warm dusk near sunset, deep night after (sunrise/sunset computed for Riyadh; preview with ?sky=dawn|day|dusk|night).
- 2026-11-21 — One-page CV (PDF) added, with download links in the contact and "me" panels on both versions.
- 2026-11-22 — Shooting star: a faint stippled streak crosses the upper sky behind the palm every ~40–60 s (first one after a few seconds); skipped by day, while a panel is open, in a hidden tab, and with reduced motion.
- 2026-11-23 — Keyboard: Tab and arrow keys now walk the palm in order (left fronds top→down, right fronds top→down, then "work with me" and the roots); Home/End jump to first/last, Enter opens, Esc returns to the same label.
- 2026-11-24 — Mobile polish (360–430px): the player now shows the song name on phones (it was hidden), frond labels get a soft night backing so they read over the leaves and are easier to tap, leader lines stop at the label, and the player sits clear of the intro text.
- 2026-11-25 — Performance: panel images now carry their real width/height (no layout jump while they load) and load lazily/async; the YouTube connection is warmed up only when someone reaches for the play button, so nothing extra connects on page load.
