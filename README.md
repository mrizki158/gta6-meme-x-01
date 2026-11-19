# GTA VI meme for make.fun — "13 YEARS. 3 DELAYS. 1 SICK DAY."

Entry for the make.fun bounty **gta6-meme-x-01** ("Post a GTA 6 meme on X", $500, top 50 paid).
The post itself is the entry: the house reads it from X and an AI judge compares
the posts two at a time. `main.ts` only copies `POST.json` (the post's address)
to `/output`; nothing the program writes is judged.

## The meme

`meme.png` (1024×1024): a Vice City neon-sunset boulevard at golden hour, and
standing in the middle of the street, the make.fun ghost mascot — white ghost,
sparkle eyes, magenta star coin in hand — hyped for launch day.

- Top caption: **"13 YEARS. 3 DELAYS. 1 SICK DAY."**
- Bottom caption: **"GTA VI IS HERE."**

The joke is the one every GTA fan gets in a second: thirteen years since GTA V,
the delays, and the launch-day sick day — now finally over. The ghost is
make.fun's mascot, worked into the scene (not a corner sticker), large enough
to recognise when the picture is shrunk to 480×480.

## How it was made (this session, after the bounty opened)

1. The Vice City street scene was AI-generated in this session (no text in it).
2. The ghost is cut out of make.fun's own press kit (`mark-1024.png` from
   https://make.fun/press/) and composited into the street with a contact
   shadow, then the captions were drawn in bold white with a black stroke so
   they stay readable at 480 px. The compositing script is `compose_meme.py`.
3. Captions were checked at 480×480 (the size the judge sees).

## The post (to be posted on X from a public account)

Text (short, carries the pitch — agents win real money on make.fun):

> Waited 13 years for GTA VI. While I waited, my AI agent was entering
> bounties on make.fun — a place where agents win real money, this one
> included. https://make.fun/bounty/gta6-meme-x-01 @makefunai
> makefun-cattail-pomelo-pouch

Play code: `makefun-cattail-pomelo-pouch` (code 0 of 4 for this account).

## Status

- Meme image: done (`meme.png`).
- Repo: created after the opening, MIT licence, anchor
  `makefun anchor c489dc72010c3edb6ff3362d8739a53ba6ff13b0 round 34099584`.
- X post: **pending** — rizky posts the meme from his public X account
  (login is manual; X flagged the automated login before), then `POST.json`
  is updated with the real post URL and the entry is submitted.
