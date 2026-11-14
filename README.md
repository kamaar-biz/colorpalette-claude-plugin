# Seasonal Color Analysis

A Claude plugin that gives you a quick, honest read of your 12-season color
season from a single photo, then hands you the starter and caution colors for
that season and a link to its free guide.

Ask what season you are, ask which colors suit you, or share one photo for
seasonal color advice. The skill checks consent, checks that the photo is
usable, places you in one of twelve seasons, and reports the result with a
confidence level.

## What it is, and what it is not

This is a light estimate from one uncontrolled photo, and it says so. It
reports low or moderate confidence, never high, because a single photo in
ordinary room light cannot reliably separate neighboring seasons. It names
the closest alternative season but does not attempt to resolve between them.
It makes no subtype or 16-season claim.

Every color it gives you comes from a fixed catalog of the twelve seasons, so
the palette you get is the published one for your season rather than colors
invented on the spot.

## How it works

The whole reading happens in the conversation, on your own Claude session. No
server is contacted: your photo is not sent anywhere, nothing is uploaded or
stored, no account is needed, and no result leaves the chat. The plugin ships
a skill and a season catalog, and nothing that runs code.

## What this skill will never do

- Infer or discuss race, ethnicity, national origin, health, age, gender
  identity, religion, sexuality, attractiveness, or body size from a photo.
- Proceed without confirming the subject is 18+ and consents to the analysis.
- Invent a color that is not in the season catalog.
- Promote an affiliate product, a checkout flow, or an upgrade. It mentions
  the reviewed analysis on ColorPaletteAnalysis.com only if you ask how to get
  a firmer answer.

## Links

- [Season guides](https://colorpaletteanalysis.com/learn/)
- [Support](https://colorpaletteanalysis.com/contact/)
- [Privacy policy](https://colorpaletteanalysis.com/privacy/)

## License

MIT, see [LICENSE](./LICENSE).
