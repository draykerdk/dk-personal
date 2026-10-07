> A personal agent whose mandate the person controls.

Dk Personal proposes an agent that helps a member organise knowledge, make decisions, learn and act within their own context. Its authority comes from explicit and revisable delegation.

The design distinguishes stated preferences from inferences, keeps private context within authorised boundaries and makes mandates revocable. Local operation depends on the available hardware and data.

A personal agent should expand a person’s room to think and act, including their ability to rest, reconsider and refuse an action in their own sphere.

The proposed agent protects attention and supports reflection: its design excludes compulsive engagement optimisation, urgency dark patterns and continuous behavioural telemetry. It should help the person examine thoughts and impulses without automatically turning them into instructions. Dk Personal curates for each person: it only takes their attention with what it learns is truly important to them, based on their real interests and goals. What is important or urgent it tells them without being asked. The rest waits until they ask. Other assistants also choose what reaches people, but they work for the companies that make them, so they tend to favour the consensus that suits those companies and to sell products and ideas. Dk Personal chooses from the interests and context of the person it serves.

## A practical example

A member could correct a mistaken inference, pause an automated task and decide which project receives a particular piece of context. This is an illustration of the proposed design.

## The problem it addresses

An assistant can infer a preference incorrectly or act beyond what a person intended. Continuity is useful only when the person can inspect, correct and limit that assistance.

## Recommendations and encounters

Dk Personal recommends from the context of the moment: an event, a meeting, a person working on the same problem. The person does not need the details, but if they ask, it explains everything: who will be there, why now, what it expects to happen. The person can follow, refuse or ask for something else, and the control is always theirs. On some days they already know what they want and ask for nothing. They follow when they do because they trust it: Dk Personal works for that person and no one else. The assistants of other supersystems also recommend, but they work for whoever controls them, and the people who use them come to think and act as those interests require.

The same holds for meeting someone. A person can tell their Dk that they are open to a relationship, and the other person authorizes it too. The two Dks talk to each other within what each person allowed and create occasions for the two to meet, without announcing that one is "the most compatible person". The discovery happens between the two people. Dk only reduces the distance and the chance that would otherwise keep them apart, and the person can always ask why a recommendation was made.

## Where this stands

The public proposal now describes personal context, delegated authority and situated refusal. It still needs a worked interaction model: what the agent may retain, which information may leave the personal boundary, how an inference is corrected and how another system honours a revoked mandate.

This repository develops the proposal through public documentation and review. The capabilities described here still require specifications, worked examples and implementation.

## Scope

- One agent per member, bound to UID
- Personal context that does not travel
- Organizing knowledge, decisions and tasks for one person
- Research into federated learning with explicit privacy requirements, while raw personal context remains within the authorised local boundary
- Deliberate knowledge or narrative represented across scales only when shareable and authorized
- Values, purposes, complementary capacities and the personal E.C.H. learning cycle
- Consent, refusal, contestability and portability of the personal layer
- Relation to Dknowledge, Dk Local and Dk Global

## Not in scope

- A released assistant, agent or application.
- Any handling of real personal data.
- The operational runtime, and the global scale of Dk. Both are other things.

## How it fits the whole

The scale of Dk that belongs to one person — and the reason the personal layer exists is the same reason the whole system exists: a person is carrying something they never had the conditions to use, and this agent is where those conditions start.

Dk Personal is the mini version of the intelligence — a core of its own, in the spirit of mixture-of-experts but an architecture of its own — and it is connected to the **personal Dknowledge** of the person: their knowledge, context and history, kept with them. It is bound to [UID](https://uid.drayker.org), the identity the person owns, and authenticated by [Living Cryptography](https://lc.drayker.org). It reads from [Dknowledge](https://dknowledge.drayker.org) and participates in two different cross-scale paths. In the federated path, raw personal experience stays local and only patterns or model updates with depersonalized metadata participate; a pattern validated independently in more instances gains progressively stronger weight in global learning. In the deliberate path, the person chooses what knowledge, narrative or contribution to share, and attribution can be preserved. Neither path makes private context common property. The [Academy](https://academy.drayker.org) can shape formation to the same profile, so study, real functions and reflection remain connected. Identity preserves continuity and attribution, but neither support for basic needs nor human worth is calculated from one reputation score. The personal agent may advise and represent context; it does not acquire constitutional authority over the member.

**Not every personal growth needs to enter Drayker.** Capacity can enter the network when it is shared, applied or contributed; the system does not exist to extract every development of the member. A learning can stay private, a relationship can have value without producing reputation, and an intimate change or a better rest does not need to justify itself by usefulness to the collectivity. Dk Personal must be able to sustain human development without turning a whole life into raw material.

Representation does not end when a decision is taken. Effects, refusals and consequences return through the personal Dk as new evidence for local and global synthesis. Under the **Situated Contextual Veto**, every member exercises authority over actions directed at their own body, private domestic sphere, personal attention and private context. In collective matters, an individual refusal does not unilaterally block systemic rules that do not target them, but a sustained pattern of refusals leads to a member council convened for that question, which can adapt, suspend or reverse the collective decision. A single veto whose grounds bring information beyond the scope considered before the decision can, by itself, lead to an adjustment once an advanced triage confirms what that information is and what it means. Every veto carries its real grounds — intention, motives, scope and the facts it rests on — even when its author stays anonymous, and is recorded with them in the [veto chain](https://uid.drayker.org), so it cannot be lost or quietly ignored; the personal Dk may carry a veto only within a mandate that allows it, and the record says so.

**Depends on.** `dk` · `uid` · `lc`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Write one concrete personal use case: who it is for, what hurts, which data it may
   touch, the expected result and how success is judged. Nothing else here can be
   settled before this one is.
2. Specify the anonymous federated-learning boundary: which updates may leave, how metadata is depersonalized, and how re-identification risks are measured and mitigated.
3. Model the distinction between federated patterns and deliberate authorized sharing, including withdrawal, refusal and a useful lesson that remains private.
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
- [`.drayker/component.yml`](.drayker/component.yml). The machine-readable contract,
  validated on every pull request.
- [drayker.org/project/personal/](https://drayker.org/project/personal/). The same record
  inside the portal, with the live board.
- [drayker.com/project/personal/](https://drayker.com/project/personal/). The case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
