---
name: creator-posting-calendar
description: "Plans a realistic posting calendar across a creator's channels for a few weeks, built around their real capacity, sponsor deadlines, and embargoes. Use when a creator asks for a content calendar, upload schedule, posting plan, or batch production plan."
license: MIT
---

# Posting calendar

Plan a schedule the creator can actually keep.

## Ask first

1. Channels, and how much the creator can really make each week, including editing time and help they have.
2. Dates that are fixed: sponsor deadlines, embargoes, launches, events, time off.
3. The content already planned or in progress.
4. The period to plan: two to eight weeks.

## Steps

1. Start from capacity, not from an ideal frequency. If the plan needs more than the stated capacity, say so and cut.
2. Place fixed dates first: sponsored posts on the agreed dates, nothing before an embargo lifts.
3. Place main uploads, then repurposed posts from them with the `creator-repurpose-posts` skill.
4. Add production steps backwards from each publish date: script, record, edit, thumbnail, review.
5. Leave buffer days. Mark days with no slack.
6. Do not claim a best time to post from memory. If the creator has their own analytics, use them. Otherwise write `[your best time from analytics]`.

## Output

A table by date: channel, item, status, production step due, sponsor or embargo note. Then a short list of risks: weeks over capacity, tight deadlines.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
