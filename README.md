# TasteSocial — public demo

**[Open the demo](https://victorathomas01-thinker.github.io/tastesocial-demo/demo.html)** · [Tasteprint source project](https://github.com/victorathomas01-thinker/tasteprint) · [Tasteprint portfolio overview](https://github.com/victorathomas01-thinker/tasteprint/blob/main/README.md)

TasteSocial is an **isolated, static browser demo** of the larger Tasteprint project's social discovery ideas. It lets reviewers explore sample UI flows without an account or live backend.

## What to expect

- A self-contained public preview built from Tasteprint's development source
- Guided sample-data experiences for discovering and comparing preferences, with no real people or live bookings
- Browser-rendered assets that can be opened directly at the public URL

## Technology and boundaries

**Stack:** JavaScript, HTML/CSS, GitHub Pages. This repository contains **generated demo assets**, not the application's primary development source; for architecture, tests, and code review, use the [Tasteprint repository](https://github.com/victorathomas01-thinker/tasteprint).

**Not enabled:** Real accounts, live friend connections, social consent, stored private plans, bookings, or production Supabase data. The demo does not represent a launched social network or booking service.

The exact source version used to produce the demo is recorded in [demo-build.json](demo-build.json). The separate [Tasteprint consumer site](https://victorathomas01-thinker.github.io/tasteprint/) is another deployment and is not modified by changes to this repository.

## Why this is a separate repository

Keeping the sample-data preview outside the consumer deployment allows the newer interaction design to be demonstrated without changing the existing working Tasteprint experience. Real-user functionality still requires hosted staging, security validation, and a separately approved release.
