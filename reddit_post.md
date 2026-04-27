# Reddit post draft — r/ClaudeExplorers

## Title options

- Made a tiny toy: **The Holy Absurd** — a fake saint generator that runs as a Claude artifact
- **The Holy Absurd** — a fake saint generator (single HTML, runs as a Claude artifact, no API key needed)
- Built a fake saint generator for Tuesdays — runs entirely as a Claude artifact

## Body

Hi all — built a little thing on the chat side and thought this sub would enjoy it.

**The Holy Absurd.** You type a vibe — any noun, feeling, mood, inside joke — and Claude invents a saint for it. Name, feast day, patronage, manner of passage, iconography, a short prayer. Ecclesiastical packaging, absurd contents, occasional accidental tenderness.

There's also an optional "with illumination" checkbox that makes Claude generate a wonky SVG portrait in the style of medieval manuscript marginalia — halo too big, proportions off, earnest face. Off by default because it uses a lot more of your message allowance.

It's a single HTML file with no backend and no API key. You just download it, drop it into a new claude.ai conversation, and ask Claude to "make this work as an artifact." Claude rebuilds it in the artifact pane and it runs on your own plan. Works on any tier that has artifacts.

Repo: https://github.com/keninhio/holy-absurd

A few vibes I've tried:

- *"forgetting why you walked into the kitchen"*
- *"the last email of the workday"*
- *"yeast"*
- *"the moment the kettle clicks off"*

The generator takes itself about 60% seriously and that seems to be the right amount.

Canonize your cat. Have fun.

---

## Notes for posting

- Best posting window for r/ClaudeExplorers: weekday evenings US time, or weekend afternoons.
- Lead with the artifact-based running instructions in the body so people don't bounce when they see a `fetch` to the Anthropic API.
- If someone in comments asks "can this run without claude.ai" — the honest answer is yes but only with a local proxy or a paid API key + a `dangerous-direct-browser-access` flag. For this audience, artifact-only is the clean story.
- Expect at least one comment trying a deeply cursed vibe. That's the fun.
