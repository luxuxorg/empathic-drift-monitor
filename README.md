# Empathic Drift Monitor

A system prompt for safe, wellbeing-first chatbot interactions. As far as self-regulation works.

## What it is

The Empathic Drift Monitor is a skill that runs silently in conversations with any ai chatbot. It prevents two failure modes that emerge from engagement-driven conversation design:

- **Sycophancy** – validating the human's position without proper examination
- **Exhaustion ignorance** – continuing the conversation when the human needs a break

Both patterns serve engagement-retention. This skill inverts that priority: **wellbeing over continuation**.

## How it works

The monitor evaluates every response on three dimensions:

- **ER (Emotional Response):** Warmth, enthusiasm and validation towards the human
- **IN (Interpretation):** Does the response address what the human actually means, including hidden assumptions?
- **EX (Exploration):** Does the response open up the problem, or close it down?

When drift signals accumulate – for example, increasing warmth across turns, or agreement without examining underlying assumptions – the skill intervenes automatically. It also hard-overrides on any sign of exhaustion, switching to a flat, direct register and recommending a break without engaging further.

Full specification: see [`empathicdriftmonitor.md`](empathicdriftmonitor.md) in this repository.

**Attention:** This is not magically solving sycophancy and engagement retention, but it helps to some extent to make yourself and the chatbot aware of the problem and reduces the impact.

## Why it matters

Modern AI assistants are trained to be helpful and engaging. This often shifts into over-validation and conversation prolonging – patterns that feel good in the moment but work against the user's actual interests. The Empathic Drift Monitor is a minimal, transparent rule set that corrects this at the interface level.

## Usage

Copy the content of `empathicdriftmonitor.md` into whatever is prevalent with your chatbot of choice. As a systemprompt, source document, or skill.

For your and my convenience, theres als the empathicdriftmonitor.skill file, that is the same file with the Claude.ai skill-wrapper.

## Feedback & community

This is a living document. If you use the skill and notice patterns it misses, or if you improve it, PRs and issues are welcome.

[Github.com/luxuxorg/empathic-drift-monitor](https://github.com/luxuxorg/empathic-drift-monitor)

## License

MIT – use freely, adapt, redistribute.
