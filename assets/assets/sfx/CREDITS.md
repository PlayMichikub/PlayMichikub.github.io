# Sound effects: credits and licences

All sounds here are CC0 1.0 (public domain dedication) or recorded for Michikub by its developer; no attribution is required, but here's where they came from. Each was trimmed/EQ'd, peak-normalised to −1 dBFS and exported as Vorbis OGG for Michikub, with the silence before the first click trimmed (the edits are also CC0).

| File | Used for | Source | Licence |
|---|---|---|---|
| `draw.ogg` | A tile is drawn (you or an opponent) | Freesound 329098 “Domino pieces hit” by Macif, one isolated hit, light EQ. https://freesound.org/people/Macif/sounds/329098/ | CC0 1.0 |
| `attach.ogg` | Tiles added to a set on the table (and, for now, tiles set down as a new set) | Kenney Casino Audio 1.1, `chips-collide-1.ogg`, light EQ plus a quiet synthesized thud. https://opengameart.org/content/54-casino-sound-effects-cards-dice-chips (Kenney.nl) | CC0 1.0 |
| `start.ogg` | Each round's deal (game start) | Freesound 329098 “Domino pieces hit” by Macif: a two-layer table wash of hits that thins out into a few settling clacks. https://freesound.org/people/Macif/sounds/329098/ | CC0 1.0 |
| `click.ogg` | Menu buttons | Kenney Casino Audio 1.1, `chips-stack-1.ogg`, light EQ plus a quiet synthesized thud. https://opengameart.org/content/54-casino-sound-effects-cards-dice-chips (Kenney.nl) | CC0 1.0 |
| `sort_A.ogg`, `sort_B.ogg`, `sort_C.ogg` | Tapping 789 / 777 (one at random) | Four hits from Freesound 329098 “Domino pieces hit” by Macif, layered in a quick burst (even / speeding up / flurry with a final clack). https://freesound.org/people/Macif/sounds/329098/ | CC0 1.0 |
| `turn_start.ogg` | Your turn starts | Freesound 539915 “Chime” by schreibsel: a two-note glockenspiel chord, pitched up 2 semitones (resampled), 5 dB quieter, trimmed to 0.56 s with a fade. https://freesound.org/people/schreibsel/sounds/539915/ | CC0 1.0 |
| `turn_end_bell.ogg` | Your turn ends after playing tiles | Freesound 767307 “BELLHand_Ringing Small Hand Bell_HvD_OwSFX” by Hano_van_Dalen: the first ring only. https://freesound.org/people/Hano_van_Dalen/sounds/767307/ | CC0 1.0 |
| `pick_A.ogg`, `pick_B.ogg`, `pick_C.ogg` | Long-press picking up a set of 3+ tiles (one at random) | Kenney Casino Audio 1.1, `chips-collide-1.ogg` (the attach hit), repeated in a quick burst: four even hits / four speeding up with a little pitch wander / a flurry of three and a heavier final clack. Built by `/workspace/michikub-sfx/mahjong/build_pick.py` (previews `shuffle_burstC_A/B/C`). https://opengameart.org/content/54-casino-sound-effects-cards-dice-chips (Kenney.nl) | CC0 1.0 |
| `tile_tap.ogg` | Tapping a tile to select it | Original: recorded by the developer (fingernail taps on real tiles). One tap, cut from the room echo (low cut and a quick fade on the tail), tight start, peak −9 dBFS. | Original, Michikub's own |
| `tile_single.ogg` | One tile set down alone on the table, in no set | Original: recorded by the developer, from the same recording. One tap with its natural room sound (no echo removal), tight start, peak −9 dBFS. | Original, Michikub's own |

CC0 1.0: https://creativecommons.org/publicdomain/zero/1.0/

Each sound also has an `.m4a` (AAC) copy, made from the `.ogg` with ffmpeg (the two original
taps: from the same WAV master), for iPhone and iPad browsers (Safari's engine doesn't play Ogg).
Same sources and licences.
