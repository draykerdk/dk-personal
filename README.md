> An assistant that is yours rather than a company’s, and that keeps what it knows about you to itself.

**The agent that belongs to one person.**

Each member’s own agent, bound to their identity and working in their context: organizing what they know, what they have decided, what they are doing and what to give the day to. It contributes what it learns upward without handing over the context that produced it.

It is the personal scale of Dk — not the operational runtime, and not Dk Global. Confusing the three is the easiest mistake to make here.

## The problem it addresses

An assistant that belongs to a platform ultimately works for the platform. An agent that belongs to the person is the only version of this anyone should trust with a life.

**How it works today.** Every helpful assistant is owned by a company that also decides what happens to what it learns about you.

**What would change.** The agent is bound to an identity you own; what it learns can travel upward, what it knows about you does not.

**Why the rest depends on it.** If the most personal layer answers to someone else, none of the guarantees above it mean very much.

## Where this stands

This is the thinnest of the components, and saying so is more useful than implying otherwise. Internally it exists as an index note and a portfolio reading of it — an interpretation, not a product decision. There is no specification held back: what the agent may keep, what it may send upward and what it must refuse are genuinely unwritten, and the first document about them decides them.

Nothing described here is implemented. This repository exists so that the first
document about it has somewhere to live and someone can argue with it in public.

## Scope

- One agent per member, bound to UID
- Personal context that does not travel
- Organizing knowledge, decisions and tasks for one person
- Learning contributed upward
- Relation to Dknowledge, Dk Local and Dk Global

## Not in scope

- A released assistant, agent or application.
- Any handling of real personal data.
- The operational runtime, and the global scale of Dk — both are other things.

## Role in the system

The scale of Dk that belongs to one person.

**Relations.** Bound to UID · authenticated by LCrypt · reads from Dknowledge · sends learning up to Dk Local and Dk Global.

**Depends on.** `dk` · `uid` · `lc`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Write one concrete personal use case: who it is for, what hurts, which data it may
   touch, the expected result and how success is judged. Nothing else here can be
   settled before this one is.
2. Write what a personal agent must never send upward.
3. Model the boundary between personal and collective learning.
4. Describe one ordinary day it would actually help with.

## How to contribute

Read [CONTRIBUTING.md](https://github.com/draykerdk/.github/blob/master/CONTRIBUTING.md)
and [GOVERNANCE.md](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md) in
the organization. In short: open or find an issue, say in the thread that you are taking
it, branch as `fn/<issue-number>-<short-name>`, and open a pull request against
`master`. There is no separate review branch.

Participation is voluntary and implies no compensation, employment or future claim.

## Sources of truth

- This repository, for what Dk Personal is and is not.
- [`.drayker/component.yml`](.drayker/component.yml) — the machine-readable contract,
  validated on every pull request.
- [drayker.org/project/personal/](https://drayker.org/project/personal/) — the same record
  inside the portal, with the live board.
- [drayker.com/project/personal/](https://drayker.com/project/personal/) — the case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
