# Music Scales and Harmony

Interactive music theory explorer — 20 playable scales & modes, circle of fifths, 10 chord progressions, and 22 chords/arpeggios. Piano + staff display with WebAudio playback. Single-file web app.

**Live site:** https://profjoleong.github.io/music-scales-and-harmony/

## What it does

Built for listening first: every scale, chord, and progression is synthesised live in your browser — one octave, exact pitches, no recordings. Headphones make the lower tonic easiest to hear on a phone speaker.

The page has six sections:

1. **Scale Explorer** — 20 playable one-octave scales in any of 12 tonics, with scale degrees under every note, a piano keyboard, and a treble-clef staff that lights up in time with playback. Includes all 7 major modes, all 7 harmonic-minor modes, melodic minor, major/minor pentatonics, blues, whole-tone, and whole–half diminished.
2. **The seven modes compared** — the major modes and harmonic-minor modes side by side, each playable in place on its own tonic.
3. **Circle of fifths** — interactive wheel showing keys, sharps/flats, and relative minors.
4. **Chords & progressions** — 10 common chord progressions (including I–IV–V) playable in the selected key.
5. **Chords & arpeggios** — 22 chord types, from triads through 13ths (including ♭9/♯9 and half-diminished), each playable as a block chord or arpeggiated.
6. **All scales in D — listen & compare** — every scale rebuilt on the same tonic, D, so you can hear each mode's character against a fixed "home" note, with a Play-all-in-order option.

Each section's explanation is tucked behind an "Explanation" toggle to keep the page compact, especially on a phone. Tap any Play button once to wake up audio (browsers require a first tap).

## How to use it

Open the live site link above in any modern browser — desktop, tablet, or phone. No install, no account, no server. Pick a tonic, pick a scale, and press Play.

## Technical notes

- Single self-contained HTML file (`index.html`) — HTML, CSS, and JavaScript in one file, no build step.
- All sound is generated in the browser with the Web Audio API; there are no audio files.
- The only external load is Google Fonts, which falls back gracefully offline.
- Hosted as a static site on GitHub Pages.

## Copyright

© 2026 Jo L. All rights reserved.

No license is granted. This repository is public so the site can be hosted on GitHub Pages; the code and content may not be reproduced, re-uploaded, or distributed in any form without written permission.
