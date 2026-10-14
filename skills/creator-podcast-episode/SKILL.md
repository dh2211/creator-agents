---
name: creator-podcast-episode
description: "Plans a podcast episode: a run sheet, interview questions, intro and outro scripts, and show notes with timestamps. Use when a podcaster asks for an episode outline, guest questions, show notes, or an intro script."
license: MIT
---

# Podcast episode

Prepare one episode: before recording (run sheet and questions) or after (show notes).

## Ask first

1. Solo or interview. For an interview, the guest's public bio or what the host knows about them, and the topics to cover.
2. Episode length and segments the show always has.
3. Before or after recording. After recording, the transcript or the host's notes with times.
4. The host's voice profile from the `creator-voice-profile` skill, or one past intro.

## Before recording

1. Write a run sheet: segments with minutes that add up to the episode length.
2. Write 10 to 15 open questions grouped by topic, from warm-up to deep, plus two follow-ups for the most important ones.
3. Write a short intro and outro in the host's voice. Leave sponsor slots as `[sponsor read: use creator-sponsor-read]`.
4. Use only facts about the guest that the host gave you. Mark the rest `[verify with guest]`.

## After recording

1. Write show notes: a two to three sentence summary, key points, and timestamps taken only from the transcript or notes. Never estimate a timestamp.
2. List every link, book, or resource mentioned, marked `[add link]`.
3. Include the disclosure line if the episode has a sponsor or affiliate links.

## Output

The run sheet, questions, and scripts, or the show notes, in Markdown. Offer social posts next with the `creator-repurpose-posts` skill.

## Guardrails

- Your voice: start from the creator's own ideas, notes, transcripts, and past writing. Never invent personal stories, opinions, experiences, or catchphrases. Write `[your story here]` where one belongs.
- Disclose it: when content involves a sponsor, affiliate link, gifted product, paid partnership, or AI-generated material, include a clear disclosure line marked `[disclosure: check platform rules and local law]`. Never hide, shrink, or soften a disclosure.
- Real numbers only: use only the stats, rates, and results the creator gives you. Otherwise write `[your number]`. Never invent views, subscribers, reach, engagement, testimonials, or reviews, and never suggest fake engagement, bought followers, or engagement pods.
- Accuracy and platform rules: titles, thumbnails, and descriptions must match what the content really covers, with no misleading clickbait. Mark any fact you are not sure of with `[verify]`, credit other people's ideas and clips, and do not state a platform's limits or policies from memory. Write `[check current platform rules]` instead.
- Privacy: leave out personal details about guests, viewers, collaborators, and brand contacts beyond what the creator gives you for this task.
- The creator decides: you draft. The creator edits, discloses, publishes, and signs any deal.
