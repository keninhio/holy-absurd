# The Holy Absurd

A tiny toy. You give it a vibe — any noun, feeling, mood, inside joke — and Claude invents a saint for it. Name, feast day, patronage, manner of martyrdom or ascension, iconography, a short prayer. Ecclesiastical packaging, absurd contents, occasional accidental tenderness.

Optional toggle: **with illumination**. Turn it on and Claude also generates a wonky SVG portrait in the style of medieval manuscript marginalia — halo too big, proportions off, earnest face staring out at you. Off by default because it uses a lot more of your message allowance per saint.

## How to run it

You don't need an API key or a server. You run it inside a Claude artifact.

1. Download `saint_generator.html`.
2. Open [claude.ai](https://claude.ai) in a browser, start a new conversation.
3. Drop the file in (or paste the code). Say something like:

   > make this work as an artifact

4. Claude will recreate it in the artifact pane. Type a vibe, canonize, receive a saint.

The generation uses your Claude plan's usage — not a separate API key, no billing surprises.

## Why this shape

It's a single HTML file with no backend. The `fetch` call to `api.anthropic.com` has no API key in it, and that's intentional — Claude's artifact sandbox proxies the call through your session. Open the HTML on a regular webserver and it won't work; it was built to live inside an artifact.

## Tinker freely

Change the prompt, change the card, change the fonts, canonize your cat. MIT-ish — do what you want with it.
