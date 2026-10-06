# Lemma Compass

Turn uncertainty into a decision you can act on.

Compass untangles a situation you're stuck in, compares options you already
have, attacks a direction before you commit to it, and writes down why you
decided — so that in six months you can tell a bad decision from a bad outcome.

It focuses on the few tradeoffs and unknowns that actually change the answer. No
invented scores, no weighted matrices built from numbers nobody measured, and no
committee of AI personas arguing with itself.

## Try it

> "I have three competing options and I can't tell what actually matters."

> "Two offers: A is $180k remote, B is $220k onsite. Which one should I take?"

> "I think I've decided. Tell me what would have to go wrong for this to be a
> mistake."

> "I'm taking the second one. Capture why, and tell me when I should reconsider."

You don't have to name anything. Describe the situation and Claude picks the
right one; type `/` if you'd rather choose yourself.

## What's in it

| Skill | For |
| :- | :- |
| `untangle` | You're stuck and don't yet know what you're deciding |
| `compare-options` | The alternatives are named and you need the deciding differences |
| `stress-test` | You're close to committing and want it attacked first |
| `decision-note` | It's decided, and you want to remember why |

## How it works

Four skills, nothing else: no server, no connector to authorise, no account,
nothing that runs on your machine. The plugin is Markdown and a manifest: it
makes no network requests of its own and stores no data anywhere. Everything it
does happens in the conversation you're already having, under whatever terms
that conversation already has.

That also means Compass has no memory between conversations. A decision note is
yours to keep wherever you keep things.

## Principles

**Use the least ceremony the decision needs.** A reversible lunch choice gets a
sentence. Selling the company gets the long version. A framework applied to a
small decision is a cost, not a service.

**An analysis has to change something.** If you finish reading and see nothing
new, and do nothing differently, it didn't work. Every one of these ends in a
clarified choice, a decisive tradeoff, the unknown that matters, a cheap
experiment, a next step, or a condition for revisiting.

**No false precision.** Numbers appear when they're real — actual salaries,
actual runway, actual hours — and not as a way of dressing a judgement up as
arithmetic.

## Install

Claude Code:

```
claude plugin marketplace add Lemma-Company/lemma-compass
claude plugin install lemma-compass@lemma-compass
```

Claude app and Cowork: **Customize → Plugins**.

## Licence

MIT. Built by [Lemma](https://lemma.company).
