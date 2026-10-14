---
name: creator-seo-metadata
description: "Drafts title options, a description, chapters, and tags for a video or episode based on what the content actually covers. Use when a creator asks for YouTube titles, an SEO description, chapters, tags, or podcast episode titles."
license: MIT
---

# SEO titles and descriptions

Help the right viewers find the content, with titles and descriptions that tell the truth about it.

## Ask first

1. The script, transcript, or a summary of what the content really covers.
2. Platform, and the search words the creator thinks their audience uses.
3. Links, credits, and disclosures that must appear.
4. For chapters, the real timestamps from the edit.

## Steps

1. Write 5 to 8 title options in different styles: plain search, curiosity, list, question. Every title must be answered by the content. Flag any option that could read as clickbait and say why.
2. Put the main search words early in the title and in the first two lines of the description.
3. Write the description: what the viewer will get, key points, credits, links marked `[add link]`, and the disclosure line where needed, above the fold if it is a sponsor.
4. Build chapters only from timestamps the creator gives you. If there are none, give the chapter titles and write `[timestamp]`.
5. Suggest 5 to 15 tags or keywords that match the content. No unrelated trending terms.
6. Note length limits as `[check current platform rules]` rather than numbers from memory.

## Output

Title options with a one-line note each, the description, chapters, and tags. Offer a posting slot next with the `creator-posting-calendar` skill.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
