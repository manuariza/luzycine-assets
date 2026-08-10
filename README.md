# Cinema content assets

Public, static image assets for the Luzycine X publishing project.

This repository contains media for both language accounts; the images are shared while captions, scheduling state, automation code, and credentials live in the private `cinema-content-scheduler` repository.

The images are served through GitHub Pages so Buffer can retrieve a stable, public HTTPS URL when it publishes each scheduled X post.

## Updating assets

Asset namespaces are intentional:

- `images/cp-*.jpg` — cinematic stills.
- `images/cinema-collections/` — deduplicated source media for the 92 themed cinema collections.

Do not add macOS `._*` metadata files, source-library folders, captions, or credentials here. Use `content-library/cinema-collections/database/export_assets.py` to export new collection media with reproducible filenames, then rebuild the matching private bilingual catalog in `cinema-content-scheduler`.
