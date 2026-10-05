# Beatfox Sequencer — private Replit recovery

This repository preserves the self-hosting handoff for Beatfox Sequencer. It is owned by `cyberwavestudios`, not the former designer account.

`source-code-snapshot.zip` contains the reviewed TypeScript/React/Express source and its imported logo. It omits dependency caches, credentials, and large uploaded/audio files. It is for source inspection; by itself it does **not** contain all sounds.

For deployment, download **`BeatfoxSequencer-source-and-build.zip` from this repository's Releases page**. That complete handoff contains source, built frontend/server, samples, loops, and uploaded assets. Run it as a Node/Express application behind HTTPS as described in its `SELF-HOSTING.md`; do not expose the whole ZIP as a static web directory. Saved projects currently live only in process memory and are lost when the server restarts; add durable storage if persistence matters.

Project secrets are **not** in this repository. Keep Replit active until the replacement passes owner testing and DNS is changed.
