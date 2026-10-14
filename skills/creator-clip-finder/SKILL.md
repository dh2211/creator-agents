---
name: creator-clip-finder
description: "Finds short-clip moments in a transcript and writes a clip list with start and end times, a hook caption, and why each moment works on its own. Use when a creator asks for Shorts, Reels, TikTok clips, highlights, or audiograms from a long video or episode."
license: MIT
---

# Clip finder

Pick the moments from a long recording that stand alone as short clips.

## Ask first

1. A transcript with timestamps. Without timestamps, give quotes and write `[timestamp]`.
2. Target clip length and platforms.
3. How many clips they want, and any moments that are off limits.
4. Whether the recording includes guests. Guests should know their words will be clipped.

## Steps

1. Look for moments with a clear start and payoff: a strong opinion, a surprising fact, a story, a how-to step, a funny exchange.
2. For each, give start and end times copied from the transcript. Never estimate times.
3. Check that the clip does not change the meaning when cut from its context. Drop any clip that does.
4. Write a short on-screen hook and a caption in the creator's voice.
5. Mark clips that mention a sponsor or product so the disclosure goes on the clip too.

## Output

A table: clip number, start, end, quote, why it works, hook text, caption, disclosure needed. Rank the list best first.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
