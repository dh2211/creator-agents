# creator-agents

CreatorAgentsKit: free, open-source Agent Skills that help YouTubers, podcasters, and creators draft video and podcast scripts, SEO titles and descriptions, social posts from long-form content, posting calendars, and brand-pitch emails, all from their own ideas and in their own voice.

Each skill is a folder with a `SKILL.md` file in the open [Agent Skills](https://agentskills.io/specification) format. Claude Code, Codex, Cursor, Grok, OpenCode, and other agents that read that format document a folder for these files. You bring your own AI tool, install the skills once, then ask in plain English: "Turn this transcript into five posts for my channels."

**Status: early.** The skills have not yet been tested live in any AI tool. The validator checks their format, not their output. Please tell us what you find.

## Quick start

1. Clone the repository:

   ```bash
   git clone https://github.com/dh2211/creator-agents.git
   ```

2. Copy or link the `skills/` folders into the skills folder your agent reads. For Claude Code on macOS or Linux:

   ```bash
   mkdir -p ~/.claude/skills
   cp -R creator-agents/skills/* ~/.claude/skills/
   ```

   [docs/install.md](docs/install.md) lists the folder for each agent, with links to each tool's documentation. You don't need Node.js or any other software to use the skills.

3. Start your agent and ask for what you need:

   > Here are two of my past scripts and my notes for a video on budget home espresso. Write a 10-minute script in my voice, then give me title options.

   The agent picks the matching skills, asks for anything missing, and drafts.

## Skills

| Skill | What it makes |
| --- | --- |
| [creator-voice-profile](skills/creator-voice-profile/SKILL.md) | A voice profile built from your own past scripts and posts, with quoted evidence |
| [creator-video-script](skills/creator-video-script/SKILL.md) | Hook options, a timed outline, and a full script with production notes |
| [creator-podcast-episode](skills/creator-podcast-episode/SKILL.md) | An episode run sheet, guest questions, intro and outro, or show notes with timestamps |
| [creator-seo-metadata](skills/creator-seo-metadata/SKILL.md) | Honest title options, a description, chapters, and tags |
| [creator-repurpose-posts](skills/creator-repurpose-posts/SKILL.md) | Social posts, threads, and captions per platform from your long-form content |
| [creator-clip-finder](skills/creator-clip-finder/SKILL.md) | A ranked clip list with start and end times, hooks, and captions |
| [creator-posting-calendar](skills/creator-posting-calendar/SKILL.md) | A posting and production calendar built around your real capacity and deadlines |
| [creator-brand-pitch](skills/creator-brand-pitch/SKILL.md) | A brand pitch email and two follow-ups using only your real, dated numbers |
| [creator-sponsor-read](skills/creator-sponsor-read/SKILL.md) | A disclosed sponsor segment from the brand's approved talking points |
| [creator-media-kit](skills/creator-media-kit/SKILL.md) | A one-page media kit with dated stats, formats, and approved past partners |

## Agents

An agent here is a short role file that names the skills it uses and the order to use them in. It adds no new instructions about the work. Those live in the skills.

| Agent | Role |
| --- | --- |
| [creator-content-agent](agents/creator-content-agent.md) | Takes one video or episode from script to titles, posts, clips, and calendar, pausing for your approval at each step |
| [creator-partnerships-agent](agents/creator-partnerships-agent.md) | Media kit, pitch, disclosed sponsor read, and delivery dates |

You don't need the agents. Every skill works on its own.

## Examples

[examples/](examples/) has worked outputs written by following the skills. Channels, stats, and brands in them are invented.

- [Coffee channel: one video, full package](examples/coffee-channel-video-package.md). Script, titles, description, and social posts.
- [Interview podcast: one episode](examples/interview-podcast-episode.md). Run sheet, guest questions, show notes, and a clip list.
- [Craft channel: a brand pitch](examples/craft-channel-brand-pitch.md). Pitch, follow-ups, a disclosed sponsor read, and a calendar.

## What the skills always do

Every skill ends with the same Guardrails section, and the validator fails if one is missing or different. The agent:

- starts from your ideas and past writing, and never invents your stories or opinions,
- adds a disclosure line for sponsors, affiliate links, gifted products, and AI-made material,
- uses only your real numbers and writes `[your number]` otherwise, with no fake engagement,
- keeps titles and descriptions true to the content and marks unsure facts `[verify]`,
- leaves out personal details about guests, viewers, and contacts,
- drafts, and leaves editing, disclosing, publishing, and deals to you.

## Before you hit publish

Disclosure rules for sponsorships, affiliate links, gifted products, and AI-made content depend on the platform and on local law. The skills remind you; you make sure it's done. Read every draft out loud, check every fact and number, and check each platform's current rules.

## Privacy

Your AI tool sends what you paste to its provider. Don't paste private messages, guests' personal details, contracts, or unpublished brand terms unless your tool's settings and the brand agreement allow it.

## Why Agent Skills

[docs/format.md](docs/format.md) explains the choice. In short, a skill is plain Markdown in a folder, several major agents already load the same folder layout, and you can read and edit every instruction.

## Documentation

- [Install for your agent](docs/install.md)
- [Use the skills](docs/usage.md)
- [Write a new skill](docs/authoring.md)
- [Why this format](docs/format.md)
- [Contributing](CONTRIBUTING.md)

## License

[MIT](LICENSE).
