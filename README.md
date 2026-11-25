# Executive Feedback

Private, evidence-based coaching for clearer leadership communication. Show your reasoning, ask about concerns before defending your answer, and make decisions easier for your team to act on—all while sounding like yourself.

Executive Feedback is a portable skill you load into an AI assistant. **Onboarding runs in your conversation with that assistant.** It uses the assistant's available connections and scheduler; this repository doesn't run a service or provide its own integrations.

## Get started

If your agent supports skills, install the entire [`executive-feedback`](executive-feedback) folder using its documented process. Keep its `references` folder alongside `SKILL.md`.

In a regular AI chat, attach [`SKILL.md`](executive-feedback/SKILL.md). To set up ongoing feedback, also attach [`onboarding.md`](executive-feedback/references/onboarding.md), so the assistant can read both files.

### Set up ongoing feedback

Ask your assistant:

> Set up Executive Feedback for me. Help me connect Slack or Microsoft Teams and whatever I use to record or take notes in meetings. Review my communication every 30 minutes and send useful feedback privately. Check what this environment supports and help me finish the setup.

The assistant will help you connect your work chat and meeting recorder or notes source, establish what to review and where to send feedback, verify access, and create the automation. It will confirm the saved schedule and explain how to pause or change it. You can choose a narrower setup, such as Slack alone.

**The preferred cadence is every 30 minutes.** If your agent's scheduler only supports hourly runs, the assistant will explain that and ask before using hourly. If a connection or scheduler is unavailable, it will say what remains to be set up. Installing the files alone doesn't start monitoring or recording.

### Try one message first

Provide a draft, its audience, and enough context to understand what you're trying to accomplish. Then ask:

> Use Executive Feedback to review this draft. Is it clear whether I'm exploring, asking for input, or deciding? Flag the most useful change to my reasoning, curiosity, or next step, and suggest wording that still sounds like me. If there's no meaningful issue, say so.

This works without connected apps or a scheduler. For a sent message, include relevant prior discussion and the latest replies. For a meeting, provide authorized notes or a transcript and identify your speaker label.

## What it coaches

1. **Curiosity before rebuttal.** Understand a concern before defending your answer.
2. **Show the thinking.** Make evidence, rationale, uncertainty, and trade-offs visible.
3. **Label the intent.** Distinguish exploration, requests for input, and decisions. Make the next step and its owner clear.
4. **Keep what worked.** Reinforce good behavior and recognize repairs you've already made.

Feedback points to a specific message or comment, explains why it matters, and offers a small alternative where useful. It preserves your voice and separates what happened from an interpretation of how it might land. It doesn't manufacture criticism or assign routine scores.

See the [fictional examples](examples.md) for useful feedback, a message that needs no rewrite, and a meeting comment that can't reliably be attributed.

## What your assistant needs

| Mode | Required capabilities |
| --- | --- |
| One-off review | Ability to read the skill and the context you provide |
| Connected review | Authorized access to your chat and meeting material |
| Recurring review | Those connections available during scheduled runs, a supported scheduler, private delivery, and private state for checkpoints and duplicate detection |

Meeting reviews depend on notes or transcripts becoming available and on reliable speaker attribution. Scheduled checks produce feedback only when something useful and new appears. Missed access is reported as a coverage gap, not treated as a clean review.

## Privacy and control

Source access is read-only. The skill doesn't send or edit work messages, contact coworkers, or modify meeting records. Setup can create the coaching automation and deliver feedback to the private destination you choose. A one-off review doesn't create a task.

Use only material you're authorized to share with your assistant. Keep personal calibration and review history private. These instructions guide the assistant; your host's permissions provide the access controls. Check its feedback against the context and decide what to change yourself.

This repository adapts a private coaching workflow. It contains no private conversations, teammate identities, account settings, credentials, or automation state.
