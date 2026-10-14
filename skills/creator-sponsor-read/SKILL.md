---
name: creator-sponsor-read
description: "Writes a sponsored segment, ad read, or affiliate mention with a clear disclosure, using the brand's approved talking points in the creator's voice. Use when a creator asks for a sponsor read, ad segment, integration script, or affiliate call to action."
license: MIT
---

# Sponsor read

Write a sponsored segment that is honest, disclosed, and still sounds like the creator.

## Ask first

1. The brand brief: approved talking points, required phrases, claims they may not make, link or code, and the deadline for review.
2. Placement and length.
3. The creator's honest experience with the product. If they have not used it, the read cannot say they have.
4. The creator's voice profile from the `creator-voice-profile` skill.

## Steps

1. Start the segment with the disclosure, in plain words, before any praise.
2. Use only the brand's approved claims. Do not add health, money, or performance claims of your own. Mark any claim that needs proof `[verify]`.
3. Write the creator's real experience where they gave it, and `[your story here]` where they did not.
4. Keep the call to action to the link or code the brand gave.
5. Write a matching description line and pinned comment with the disclosure.
6. List anything that needs the brand's approval before recording.

## Output

The read with timing, the description and comment lines, and a checklist: disclosure first, approved claims only, link or code correct, brand approval needed.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
