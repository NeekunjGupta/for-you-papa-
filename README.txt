FOR YOU, PAPA — setup guide
============================

This is a complete, working website. Open index.html in a browser right now
and it already works end-to-end (it shows tasteful placeholder cards for any
photo that's missing). To make it yours, drop your files into the "assets"
folder using these exact names:

PHOTOS
------
assets/box1.jpg        Box 1 — you, Papa & your sister (one large photo)
assets/box2.jpg        Box 2 — a family photo
assets/box3.jpg        Box 3 — another family photo
assets/box4-1.jpg
assets/box4-2.jpg
assets/box4-3.jpg      Box 4 — small collage (3 photos)
assets/box5-1.jpg
assets/box5-2.jpg
assets/box5-3.jpg
assets/box5-4.jpg      Box 5 — larger collage (4 photos)
assets/box6-1.jpg
assets/box6-2.jpg
assets/box6-3.jpg
assets/box6-4.jpg      Box 6 — trips, adventures, celebrations (4 photos)
assets/box7-then.jpg
assets/box7-now.jpg    Box 7 — "Then vs Now" pair
assets/box8.jpg        Box 8 — the future family portrait (see note below)

Box 9 has no photo — it's the closing text screen, already built.

Any size works, but for the best crop, use portrait photos (taller than
wide, roughly 4:5). JPEG or PNG both work — just keep the filenames above.

If you want fewer or more photos in a collage box, open index.html and edit
the `images:[...]` array for that box in the BOXES list near the top of the
<script> section — the layout (.c3 / .c4) adapts automatically to 3 or 4
images.

MUSIC
-----
assets/papa-meri-jaan.mp3

I haven't included the actual song file — it's commercially released music,
so it isn't something I can generate or embed for you. Add your own copy of
the "Papa Meri Jaan" whistle section (trimmed to the length you want) at
that path and it will play automatically, fading in gradually exactly as
you spec'd: 0% → 5% → 10% → 20% → 35% → 50% → 70% → 90% → 100% across the
nine boxes. Any MP3 works as a drop-in replacement if you'd rather use a
different track.

BOX 8 — THE "FUTURE FAMILY PORTRAIT"
-------------------------------------
This one is the AI-generated portrait of you, Papa, Mom and your sister,
all together, smiling at the camera. I'm not able to generate a realistic
image of real, identifiable people myself — so this is the one asset you'll
want to create separately (an image-generation tool that lets you upload
reference photos of your family works well for this) and then save as
assets/box8.jpg. Until you add it, that box will show a clean placeholder
card rather than a broken image.

HOSTING / SHARING
------------------
This is a single static folder — no build step, no server required.
Easiest options:
  • Double-click index.html to preview it locally.
  • Drag the whole "for-you-papa" folder into Netlify Drop
    (https://app.netlify.com/drop) for a free instant link to share.
  • Or host it on GitHub Pages / Vercel if you'd rather.

Everything else — the gift-box opening animation, the volume fades, the
particle effects, the then/now layout, and the final "Happy Father's Day"
screen — is already built and working.
