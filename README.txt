ARTISTRY STUDIO — WEBSITE PACKAGE
=================================

WHAT'S INSIDE
-------------
index.html    - the whole website (all sections)
styles.css    - colors, fonts, layout and animations
                (theme: warm ivory, aqua mist, deep teal, champagne gold)
data/products.json - the product list (49 real catalog products; the
                shop section loads this file — easy to edit by hand too)
admin/        - password-protected admin panel (Decap CMS): the client
                logs in at yoursite.netlify.app/admin to add/edit/remove
                products themselves — price, stock, photos, description.
                Needs one-time setup: GitHub repo + Netlify Identity
                (see guide). Not linked anywhere on the site.
images/       - hero.jpg (top banner), about.jpg (about section),
                pXX_N.jpg (76 real product photos, 49 products),
                uploads/ (photos added later via the admin panel)
README.txt    - this file

No build step, no database, no plugins. Just upload and it works.

CURRENT STATUS (v3 — 2026-10-16 night)
--------------------------------------
- Brand: Artistry Studio (new teal + gold theme)
- Social links wired: WhatsApp Channel, Instagram
  (@artistry_studio31), TikTok (@artistry.studio31),
  YouTube (@artistrystudio31)
- WhatsApp orders go to 0309 7548900 (wa.me/923097548900) with
  pre-filled order messages. The WhatsApp Channel button is kept
  as a second contact option.
- All buttons have animations: shine sweep on every button, soft
  pulsing glow on primary buttons.
- Reviews section added (Roman Urdu, auto-scrolling). These are
  SAMPLE reviews — replace with real customer reviews when they
  arrive (edit the review-card blocks in index.html).
- Shop: 49 real products in 9 categories (Earrings 18, Bangles 11,
  Phone Charms 4, Keychains 4, Car Hangings 4, Beaded Bags 3,
  Gift Sets 2, Pens 2, Phone Cases 1), each with offer price +
  struck-through pre-offer price and 1–5 photos. Clicking a photo
  opens a swipeable carousel (arrows/dots/swipe). Thumbnails show
  the full product, never cropped.

HOW TO PUT IT ONLINE (about 30 minutes)
---------------------------------------
Same as any static site: unzip, then either
  a) drag the unzipped folder into Netlify Drop / your host's
     file manager, or
  b) upload via FTP to your hosting.
Point your domain at it and you're live. To update later,
re-upload only the files you changed.
