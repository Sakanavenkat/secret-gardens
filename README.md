# Garden Letters

A private letter-journaling app. Each letter you write "plants" a flower
in your garden — bouquets are procedurally generated per letter, so no two
look alike. Click a letter to see it bloom, with butterflies and a bird
visiting the scene.

## Features
- Simple name + password gate (client-side only — see note below)
- Write letters with an optional photo, video clip (under 4MB), or video link
- Procedurally generated flower bouquets, unique per letter
- Preferences: color palette, handwriting font, bouquet style
- Everything saves automatically via the app's built-in storage

## Running it
Just open `index.html` in a browser, or serve the folder with GitHub Pages.

## Note on the login gate
The name/password screen is a simple client-side lock for personal use —
not real security. It doesn't encrypt anything and could be bypassed by
anyone with access to the page source. Data is already private to your
own browser/account via the storage system either way.
