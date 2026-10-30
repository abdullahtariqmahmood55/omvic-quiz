# OMVIC Quiz — rules for every update

## Always bump the version
Every change pushed to this repo must bump the version shown on the page.

- The version lives in `index.html`, in the header pill: `<span class="ver" id="ver" ...>vX.Y.Z</span>`.
- Bump the patch number (`v1.0.3` → `v1.0.4`) for fixes and small tweaks; bump the minor number (`v1.0.x` → `v1.1.0`) for new features.
- Put the new version in the commit message, e.g. `Center answer letters (v1.0.3)`.
- Never push a commit to `main` without bumping the version, even for one-line changes.

## Where updates go
This repo (GitHub `abdullahtariqmahmood55/omvic-quiz`) is the source of truth. When asked to "push an update", commit and push here to `main`.
