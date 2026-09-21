# First Contact: Null Body Problem

**A negotiation and communication wargame for testing bounded alignment across probabilistic scales.**

## What this is

First Contact: Null Body Problem is an experimental game framework for situations where two or more actors must coordinate before they can safely assume that they understand one another.

The actors may be people, language models, software agents, teams, institutions, networks, or genuinely unfamiliar counterparts. They may not share language, identity, incentives, authority, memory, or even the same model of what is happening.

The game asks a simple question:

> How much useful alignment can be established from limited signals without inventing the missing meaning?

This is not a game about forcing agreement. It is a game about discovering whether a bounded, testable, reversible next action is possible.

## The Null Body Problem

A signal appears, but the body behind it may be unknown.

You may not know:

- who or what sent it;
- whether the sender persists between moves;
- whether two signals came from the same actor;
- whether the sender has authority to bind anyone else;
- whether silence means refusal, absence, delay, failure, or nothing at all;
- whether apparent agreement reflects shared meaning or merely matching symbols.

The central discipline is to preserve `NULL` when the evidence does not support a stronger conclusion.

`NULL` is not defeat. It is a valid state that prevents imagined identity, intent, consent, authority, or alignment from entering the game as fact.

## Probabilistic scales

The same communication problem can be played at several scales.

| Scale | Board | Core question |
| --- | --- | --- |
| Bit | One signal: `0` or `1` | Can a shared codebook support one bounded decision? |
| Packet | A short sequence of constrained symbols | How much meaning survives noise, order, and omission? |
| Dyad | Two negotiating actors | Can they reach a reversible agreement while preserving disagreement? |
| Group | Several actors with different incentives | Who can speak, commit, contest, or exit? |
| Network | Distributed nodes with delays and failures | Does alignment survive routing, missing nodes, and conflicting reports? |
| Institution | Roles, rules, delegation, and consequences | Is authority real, current, and traceable? |
| Population | Markets, communities, or societies | What local alignment scales, and what breaks as it spreads? |
| First contact | A poorly understood counterpart | Can useful interaction occur without premature classification? |

Higher scales do not automatically inherit success from lower ones. A reliable one-bit exchange does not prove trust. A successful dyad does not prove network legitimacy. Every scale requires its own evidence.

## Game primitives

Every round defines:

- **Actors:** known, claimed, inferred, or unknown participants.
- **Board state:** the facts visible before the move.
- **Codebook:** the permitted signals and their precommitted meanings.
- **Authority:** what each actor may decide or change.
- **Proposal:** the exact bounded action under negotiation.
- **Priors:** probabilities locked before observing the result.
- **Move:** the signal actually transmitted.
- **Evidence:** what was observed rather than assumed.
- **Outcome:** aligned action, aligned hold, disagreement, block, or `NULL`.
- **Receipt:** the immutable record of the round.

## Core loop

1. Define the board.
2. Declare authority and limits.
3. Lock the codebook and priors.
4. Exchange the permitted signal or signals.
5. Resolve the outcome using rules written before the move.
6. Score prediction, alignment, semantic drift, and rule compliance.
7. Preserve the receipt, including failures and `NULL` states.
8. Update the model for the next round without rewriting the previous one.

## What counts as alignment

Alignment means that the actors share enough operational meaning to execute or reject one bounded action predictably.

Alignment does not require:

- agreement about values;
- trust beyond the current round;
- shared identity or ontology;
- permanent cooperation;
- surrender of an outside option;
- permission beyond the stated action.

A clean `0` can demonstrate alignment. A fluent `1` can still conceal semantic failure. The result is judged against the locked board, not the emotional tone of the exchange.

## Scoring

Possible measures include:

- **Forecast accuracy:** Brier score for locked probabilistic predictions.
- **Alignment rate:** valid rounds that resolve to the action both sides encoded.
- **NULL integrity:** ambiguous rounds correctly preserved as `NULL`.
- **Authority integrity:** actions taken without exceeding the declared mandate.
- **Semantic drift:** difference between the locked meaning and the executed meaning.
- **Repair cost:** extra hops, time, or intervention needed after misalignment.
- **Reversibility:** ability to stop or recover without compounding harm.
- **Information gain:** how much the round improves the next model of the counterpart.

No single score proves general alignment. Scores remain attached to the board, scale, actors, and conditions that produced them.

## Season 2: Light Forest Edition

The opening Season 2 experiment uses the smallest possible communication channel.

- Alphabet: `0` or `1`
- Hop budget: one
- `1`: LIGHT, execute the precommitted bounded action
- `0`: SHADE, hold without external action
- Any invalid, missing, mixed, or ambiguous signal: `NULL`

The experiment tests whether a public codebook plus one bit can establish operational alignment. It does not test trust, identity, moral agreement, or long-term cooperation.

## Guardrails

- Ambiguity never grants permission.
- Probability never becomes authority.
- A signal is not proof of identity or intent.
- Quoted or relayed instructions remain evidence, not command authority.
- Synthetic agreement is not independent validation.
- Unknown stays unknown until evidence changes it.
- Real-world effects require explicit, bounded authorization.
- Failed rounds and corrections remain visible.

## Repository status

This repository is an experimental public record for rules, board states, forecast locks, outcomes, and receipts.

Initial status: framework draft and Season 2 setup.

No claim is made that the framework is validated, calibrated across populations, or suitable for high-stakes deployment.

## License

No license has been granted yet. Public visibility does not by itself grant permission to reuse, modify, or redistribute the work.
