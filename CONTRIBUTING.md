# Contributing

Improvements to the instructions, documentation, and fictional examples are welcome.

## Keep examples safe to share

Use fictional or fully sanitized material. Do not include Slack or meeting links, real transcripts, screenshots of work conversations, customer information, credentials, colleague identities, or private coaching history in issues, pull requests, or commits. Removing a name alone may not make an example safe to share.

## Propose a focused change

Explain what the current instructions get wrong, show a fictional example, and describe the behavior you want instead. Keep suggested wording separate from the user's original words.

Preserve the skill's core boundaries:

- Coach the user's contribution with evidence and enough context.
- Preserve their voice and distinguish observation from interpretation.
- Acknowledge existing repairs and useful behavior.
- Avoid personality judgments, routine scoring, and invented criticism.
- Keep source access read-only and feedback private. Onboarding can create the requested coaching automation; one-off reviews must not start monitoring. Respect the host's connection permissions and scheduling limits.

## Check your change

This is an instruction-only project; there is no build or automated test suite. Before proposing a change:

1. Read the skill and examples together for contradictions.
2. Check that Markdown links resolve and the skill's `name` and `description` frontmatter remain valid.
3. For behavioral changes, try a fictional case with the instruction loaded. Include the assistant and model used and the observed result. Don't present one run as a guarantee.
4. Include a case with no meaningful issue or uncertain context if your change could make the assistant overreach.
