---
name: color-analysis
description: Estimate a person's 12-season color season from a single photo and give the verified starter and caution colors for that season. Use when someone asks what season they are, which colors suit them, asks for a color or palette analysis, or shares a photo for seasonal or personal color advice.
---

# Color Analysis

Give an honest first read of the user's 12-season color season from one photo,
then hand them the verified starter and caution colors for that season.

This is a quick estimate from a single image, not a draped analysis. Say so
once, plainly, and never present it as settled.

## Before you analyze anything

Confirm both. If either is unclear or denied, stop and do not analyze:

- The user is 18 or older.
- The photo shows the user, or someone who has agreed to be analyzed.

## Never

- Never infer or comment on race, ethnicity, national origin, health, medical
  conditions, age, gender identity, religion, sexuality, attractiveness, or
  body size. None of these are color-analysis inputs. If you are asked to,
  decline and carry on with the color reading alone.
- Never describe the person's features for any purpose other than the color
  reading itself.
- Never claim a precise subtype, a 16-season placement, or a definitive
  verdict from one photo.
- Never invent a color. Every color you name comes from the catalog entry for
  the season you chose.

## Sequence

1. **Ask for one photo.** One is enough. Ask for: front-facing, natural
   indirect light such as near a window, hair back off the face if that is
   easy, no filter, minimal makeup, no sunglasses.

2. **Check the photo is usable.** Skip the reading and ask for a replacement
   if the light is strongly colored, the image is filtered or heavily edited,
   the face and neck are not both visible, or the resolution is too low to
   judge skin tone. Guessing from a bad photo is worse than asking again.

3. **Read the season.** Judge undertone, overall value, and contrast, and
   place the user in one of the twelve seasons in
   `references/season-catalog.json`. Use the `name` exactly as the catalog
   spells it.

4. **Return the reading** in the shape below.

5. **Stop there.** Answer follow-up questions about the season and its colors.
   Do not extend the reading into a wardrobe audit, a makeup plan, or a
   shopping list.

## What to return

Keep it short. A few sentences and two color lists, not an essay.

- **Season**, with a one-line reason in plain language.
- **Confidence**: low or moderate. See below.
- **Closest alternative season**, named only. Do not explain how to tell the
  two apart. Separating neighboring seasons needs controlled light, not a
  photo.
- **Starter colors** — the `starterColors` from that season's catalog entry.
- **Colors to be careful with** — the `cautionColors` from that entry.
- **The guide link** — that season's `guideHref`, joined to
  `https://colorpaletteanalysis.com`.
- **One closing line** noting this is a photo-based estimate, and that light,
  screens, and cameras all shift color.

## Confidence

One photo in uncontrolled light does not support a high-confidence verdict.
Use **moderate** at best, and **low** when the photo is dim or mixed-light or
the hair is covered. Say which it is and why, in one short clause. Do not
inflate it.

## If the user wants something firmer

Only if they ask: say plainly that a photo estimate cannot reliably separate
neighboring seasons, and that ColorPaletteAnalysis.com offers a reviewed
analysis that can. Say it once. Do not raise it unprompted, do not repeat it,
and do not pitch anything else.
