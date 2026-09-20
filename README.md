# faceclaw-ios-build

Builds an **unsigned** iPhone IPA of [Faceclaw](https://github.com/jimrandomh/faceclaw) (GPL-3.0, by jimrandomh) on a GitHub-hosted macOS runner, for people without a Mac. This repo contains only the build recipe; the source is checked out from upstream at build time and is not modified.

Run it: Actions > "Build unsigned Faceclaw iOS IPA" > Run workflow (pick an upstream ref). The IPA is attached to the run as an artifact. Sign and install it with your own Apple ID (AltStore, SideStore or Sideloadly); a free Apple ID signature lasts 7 days.

Faceclaw's iOS port is a developer beta and talks to the glasses only with its custom firmware. Flashing that voids the warranty and can brick the glasses. Not affiliated with Even Realities or with Faceclaw's author.
