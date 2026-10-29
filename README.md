# Sneakerjunkie — website concept

A concept website for [Sneakerjunkie](https://www.facebook.com/profile.php?id=61578929663578): their pairs as die-cut stickers on their own checkerboard.

Photos come from the shop's Facebook page; prices and sizes are placeholders for the demo.

Concept & design: LADZE studio

## Shop panel

[`admin.html`](https://akultange.github.io/sneakerjunkie/admin.html) is the shop's own panel. Add a pair from a photo (the background is lifted right in the browser), change prices, sizes, photos and descriptions, arrange the wall, take pairs off the site or delete them.

Every change is a draft on that device, and the site shows it there with a "Draft" badge, until **Publish**. Publish writes one commit straight into this repo: new images go under `assets/img/u/`, the list goes to `assets/data/catalog.json`, and GitHub Pages puts it live in about a minute. No server, no database.

Publishing needs a fine-grained personal access token for this repository with **Contents: Read and write**. The panel walks through creating one and keeps it only in that browser. Without one, the panel runs as a demo and changes stay on the device.
