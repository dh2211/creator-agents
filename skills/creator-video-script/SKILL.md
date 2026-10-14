---
name: creator-video-script
description: "Writes a video outline or full script with a hook, structure, on-screen notes, and a call to action, from the creator's own idea, notes, or talking points. Use when a creator asks for a YouTube script, a short-form script, an outline, a hook, or talking points."
license: MIT
---

# Video script

Turn the creator's idea and notes into a script they can record without sounding like someone else.

## Ask first

1. The idea, plus their notes, talking points, or research. The script covers only what they give you and what you mark `[verify]`.
2. Platform and target length (long-form minutes or short-form seconds).
3. Their voice profile from the `creator-voice-profile` skill, or one past script.
4. Whether any part is sponsored, affiliate, or gifted. If yes, use the `creator-sponsor-read` skill for that segment.

## Steps

1. Write three hook options for the first few seconds. Each must promise only what the video delivers.
2. Outline the structure: hook, setup, three to five sections, payoff, call to action. Give rough timing per section that adds up to the target length.
3. Write the script in the creator's voice: spoken sentences, short lines, contractions. Mark B-roll, graphics, and on-screen text in square brackets.
4. Put `[your story here]` wherever a personal example belongs. Never write one for them.
5. Mark every factual claim you could not check from their notes with `[verify]`, and credit any person, study, or clip they reference.
6. End with one call to action, not five.

## Output

1. Three hook options.
2. Outline with timings.
3. Full script with bracketed production notes.
4. A checklist: claims marked `[verify]`, credits, disclosure needed (yes or no).

Offer titles and a description next with the `creator-seo-metadata` skill.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
