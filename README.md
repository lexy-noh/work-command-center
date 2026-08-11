![Work Command Center preview](./assets/WMC-hero.png)

# 💼 Work Command Center

A natural-language work tracking system designed to turn everyday work context into an evolving source of truth.

Most productivity systems create another thing to maintain.

The Work Command Center is an experiment in doing the opposite: using an LLM as a lightweight reasoning layer across the work you are already doing.

Instead of updating fields, statuses, and dashboards, you interact with it naturally:

* “I have to finish the prototype before Thursday.”
* “Sent the deck.”
* “Waiting on engineering.”
* “What should I be doing right now?”
* “What am I forgetting?”
* “Give me a pulse check.”

The system interprets those updates against the context you have already given it and helps track work, commitments, blockers, decisions, dependencies, and progress over time.

---

## Quick start

1. Open the [Work Command Center Prompt](./work-command-center-prompt.md)
2. Copy it into a new ChatGPT conversation or another context-aware LLM
3. Start adding your real work as it happens
4. Ask things like “What should I do today?”, “What am I forgetting?”, or “Give me a pulse check”

---

## Why I built this

Work rarely arrives neatly organized.

It shows up in meetings, Slack threads, emails, screenshots, half-finished thoughts, decisions, deadlines, and conversations.

The idea behind Work Command Center is simple:

**What if the system did more of the organizing instead of asking the person to?**

The goal is not to replace project management tools. It is to create a more natural interface between a person and the complexity of their own work.

---

## What it can help with

* Maintain an evolving view of active work
* Track commitments and follow-ups
* Surface blockers and dependencies
* Preserve decisions and context
* Prioritize what deserves attention
* Identify work that may be getting forgotten
* Generate a concise weekly pulse check
* Look back at progress and accomplishments

---

## The interaction model

There is no required command syntax.

You can update the system the same way you would explain your work to another person.

For example:

```text
I need to review this before Friday.

Waiting on approval before I can move forward.

We decided not to pursue the second option.

Sent the final deck.

I have 45 minutes. What should I work on?
```

The Command Center is designed to determine whether something is a task, update, blocker, decision, dependency, or context without requiring the user to manually categorize it.

---

## Accuracy over completeness

The system is explicitly instructed not to invent missing information.

If a name, date, deadline, owner, status, project, or other important detail has not been established, it should ask rather than guess.

When information is uncertain, accuracy should take priority over making the tracker look complete.

---

## Try it

The full prompt is available here:

**[Work Command Center Prompt](./work-command-center-prompt.md)**

Copy it into a new ChatGPT conversation or another context-aware LLM and start adding whatever is currently on your plate.

It does not need to be organized.

---

## Examples

Example inputs and outputs are included in the [`examples`](./examples) folder.

---

## What this explores

This project is also an exploration of:

* natural language as an interface
* LLM context management
* designing around existing human behavior
* AI-assisted prioritization
* hallucination guardrails
* progressive disclosure of complex information
* reducing the maintenance cost of productivity systems

The underlying question is less about how to build a better to-do list and more about:

**How can emerging technology adapt to the way people already work, instead of asking people to adapt to the technology?**
