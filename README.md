# EJUOne public book mirror

This repository contains only unrestricted EJU One book payloads generated from
the private `ejuone-book` source repository. Publisher-restricted books are not
copied here.

The app reads `manifest.json` and downloads files from this repository through
GitHub Raw, with Cloudflare R2 as the mirror fallback.
