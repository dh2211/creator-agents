# Contributing

Creators, editors, producers, and developers are all welcome. The most useful contributions are fixes from real use: "the show notes skill ignores timestamps" is worth more than a new skill.

## Report a problem

Open an issue with:

- the skill and the agent you used (for example, `creator-repurpose-posts` in Cursor),
- what you asked for, with private details and real brand terms removed,
- what you got and what you expected.

## Change a skill

1. Fork the repository and create a branch.
2. Edit the `SKILL.md`. Follow [docs/authoring.md](docs/authoring.md).
3. Try the skill in at least one agent. Say which one in the pull request.
4. Run the checks:

   ```bash
   npm run validate
   npm test
   ```

5. Open a pull request that says what changed and why.

## Add a skill

Open an issue first and describe the creator's problem it solves. Then follow [docs/authoring.md](docs/authoring.md) and include a worked example in `examples/`.

## Rules for all content

- Plain English.
- No real channel stats, private messages, or brand contract terms in issues, examples, or tests. Use invented channels and say that they are invented.
- No fake engagement tactics, and no advice to hide or skip a disclosure.
- No copyrighted scripts or transcripts beyond short quotations.
- Keep the Guardrails section identical across skills.
- Start every skill and agent name with `creator-`.

By contributing, you agree that your contribution is licensed under the [MIT License](LICENSE).
