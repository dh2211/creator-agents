---
name: creator-repurpose-posts
description: "Turns a long video, podcast episode, or article into social posts, threads, captions, and a newsletter blurb in the creator's voice, one set per platform. Use when a creator asks to repurpose content, write social posts, captions, a thread, or promo posts for a new upload."
license: MIT
---

# Repurpose into social posts

Get more from content the creator already made, without changing what they said.

## Ask first

1. The transcript, script, or article. Posts use only what is in it.
2. Platforms they post on, and how many posts per platform.
3. Their voice profile from the `creator-voice-profile` skill, or two past posts they like.
4. Any sponsor, affiliate, or gifted product in the source. Disclosures carry over to every post that mentions it.

## Steps

1. Pull 5 to 10 core ideas, quotes, or moments from the source. Quote the creator exactly and keep each quote in its context.
2. For each platform, write posts in a format that suits it: short post, thread, caption, carousel slide text, or community post.
3. Keep the creator's voice and claims. Do not exaggerate a result or add a promise the source does not make.
4. Add a disclosure line to any post that mentions a sponsor, affiliate link, or gifted product, and a note where AI-made images or audio are used.
5. For clips, point to the `creator-clip-finder` skill.
6. Leave hashtags few and relevant, and note `[check current platform rules]` for format and length.

## Output

Posts grouped by platform, each with the source moment it came from. A checklist at the end: disclosures carried over, quotes in context, links `[add link]`.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
