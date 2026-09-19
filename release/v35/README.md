# Verified v35 itch.io source

The current @venturerer III itch.io release is a single 9.49 MB HTML file. The connected GitHub API could not reliably accept that file in one request, so the source is stored here in ordered text parts.

Original file: `av3_v35.html`  
Application version: **35**  
SHA-256 of the publisher-supplied original:

`fc46acdfb5af61e1a01b915fb0e88494151cc622d7dd06febc54d47a45134591`

Reassemble:

```sh
cat parts/index.html.part* > index.html
sha256sum index.html
```

The resulting hash must equal the value above. The root `index.html` remains the older historical build until the exact v35 file can be committed as one blob without altering it.
