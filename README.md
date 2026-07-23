# Japan Dating App Chat Skill

A Codex skill for writing natural, send-ready Japanese dating-app messages.

The skill is designed around a calm and socially experienced style:

- read one concrete detail instead of sending generic praise;
- respond with matched self-disclosure rather than interviewing;
- calibrate warmth, humor, and invitations to visible reciprocity;
- make clear, low-pressure date and LINE transitions;
- stop chasing when effort remains one-sided;
- screen suspicious profiles before optimizing a reply.

It explicitly rejects negging, manipulation, sexual pressure, deception, and status-based performance.

## Structure

- `.codex/skills/japan-dating-app-chat/SKILL.md`: decision system and behavioral rules
- `.codex/skills/japan-dating-app-chat/references/playbook.md`: send-ready Japanese patterns
- `.codex/skills/japan-dating-app-chat/references/research.md`: research, surveys, and evidence boundaries
- `.codex/skills/japan-dating-app-chat/agents/openai.yaml`: Codex UI metadata

## Install

Copy `.codex/skills/japan-dating-app-chat` into a Codex skill root, or keep the repository as a project-local skill.

Invoke it with:

```text
$japan-dating-app-chat
```

Include the other person's profile or latest message, the conversation stage, and any facts that must be preserved. Remove names and private information before sharing examples publicly.

## Contributing

Issues and pull requests are welcome. Useful contributions include:

- anonymized Japanese conversation cases with enough context to evaluate the reply;
- corrections from native Japanese speakers;
- counterexamples where a rule produces stiff, pushy, or generic wording;
- better evidence on message timing, invitations, and platform-specific norms;
- eval cases covering openers, warm exchanges, stalled chats, dates, LINE, and safety.

When proposing a rule, separate peer-reviewed evidence, platform surveys, coaching opinion, and personal experience. Do not claim that wording guarantees a reply or date.

Never submit real names, handles, LINE IDs, phone numbers, exact workplaces, home locations, or identifiable screenshots.
