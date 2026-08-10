# Luzycine assets

Public, static image assets for the Luzycine X publishing project.

This repository intentionally contains only the Spanish-language publishing images. Captions, scheduling state, automation code, and credentials live in the private `luzycine-scheduler` repository.

The images are served through GitHub Pages so Buffer can retrieve a stable, public HTTPS URL when it publishes each scheduled X post.

## Updating assets

Do not add macOS `._*` metadata files, the legacy `movies` archive, captions, or credentials here. Use the catalog export tool in the scheduler repository to create reproducible image filenames and its matching private catalog.
