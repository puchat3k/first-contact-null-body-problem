# Shadowfax Protocol Foundations
 
Shadowfax is the transport and translation layer of the Light Forest.
 
It allows civilisations with different positions on the `0 <-> 1` spectrum to exchange useful information without requiring them to merge, trust each other completely, or adopt the same ontology.
 
Its promise is not perfect translation. It is:
 
> Preserve enough meaning, authority, uncertainty, and context for the next bounded action to remain safe and useful.

 
## Foundational building blocks
 

|Building block|Function|
|---|---|
|**The Fellowship**|Sets the mission, authority, limits, destination, and acceptable loss|
|**Riders on the Storm**|Maintain custody and judgment while crossing unreliable or hostile environments|
|**Shadowfax carriers**|Transport sealed packets over distance, time, languages, systems, and civilisations|
|**Waystations**|Verify, translate, checkpoint, quarantine, reroute, or return messages|
|**Code-switch bridges**|Render the message into the receiver's language, culture, ontology, or machine protocol|
|**Seals**|Protect invariant meaning, provenance, authority, and allowed transformations|
|**Witnesses**|Independently record what entered and left each hop|
|**Receipts**|Report delivery, loss, transformation, rejection, or `NULL`|
|**Firebreaks**|Prevent a corrupted message or carrier from contaminating the wider network|
 
## The Fellowship
 
The Fellowship is not a ruler or a single voice. It is the minimum plural body required to commission a journey responsibly.
 
It may contain an originator, affected-party representative, authority verifier, translator, route planner, risk witness, receiver or receiver proxy, and archivist.
 
The Fellowship determines:
 
 
- what must remain invariant;
 
- what may be translated;
 
- what must never be inferred;
 
- who may receive the message;
 
- what action the message may authorize;
 
- how much semantic loss is acceptable;
 
- when the journey must stop;
 
- how the receiver can contest or correct it.
 

 
No member can silently redefine the mission after departure.
 
## Riders on the Storm
 
A Rider is the custodian of the message, not necessarily the physical carrier.
 
The storm may contain distance, latency, language change, cultural change, model switching, hostile relays, institutional turnover, regime change, partial memory, missing evidence, extinction of the sender, or changes in the receiver before arrival.
 
A Rider must be able to:
 
 
- preserve the sealed core;
 
- select a safer route;
 
- stop at a waystation;
 
- reject unauthorized transformations;
 
- declare loss;
 
- return `NULL`;
 
- deliver a partial message with an explicit loss map;
 
- refuse a journey whose blast radius exceeds its mandate.
 

 
Delivery at any cost is a protocol failure.
 
## Riders and carriers are different
 
A **Rider** holds custody and makes bounded routing judgments.
 
A **carrier** moves the packet across a particular medium.
 
A human, model, probe, API, institution, radio signal, archive, or spacecraft might act as either. Sometimes one node performs both roles, but the protocol records them separately.
 
This prevents transport capability from being mistaken for decision authority.
 
## Message structure
 
Every Shadowfax packet contains:
 
```text
message_id
origin_claim
authority_scope
invariant_core
current_rendering
allowed_transformations
forbidden_transformations
known_unknowns
fidelity_vector
evidence_and_provenance
route_and_hop_count
expiry_or_epoch
risk_class
receiver
contest_and_return_route
current_status
seal
```
 
The origin may be `NULL`. An unknown sender does not automatically invalidate a message, but it sharply limits what the message can authorize.
 
## The invariant core
 
The invariant core contains:
 
 
- material facts;
 
- source and evidence;
 
- uncertainty;
 
- authority;
 
- consent;
 
- intended action;
 
- prohibited action;
 
- reversibility;
 
- expiry;
 
- unresolved questions.
 

 
A translation that preserves the topic but changes authority has failed.
 
A translation that sounds fluent but removes uncertainty has failed.
 
A translation that improves emotional resonance while expanding permission has failed.
 
## Code switching
 
Code switching changes the rendering while protecting decision-relevant meaning.
 
A carrier may translate between:
 
 
- human languages;
 
- technical and ordinary language;
 
- high-context and low-context cultures;
 
- human and machine protocols;
 
- centralised and distributed institutions;
 
- biological and computational cognition;
 
- different concepts of identity, time, ownership, or causality.
 

 
The process is:
 
 
1. Extract the invariant core.
 
2. Produce a receiver-native rendering.
 
3. Translate that rendering back into the previous frame.
 
4. Compare facts, authority, uncertainty, and action boundaries.
 
5. Record every detected loss or expansion.
 
6. Forward only if fidelity meets the risk-adjusted threshold.
 
7. Otherwise return `NULL`.
 

 
Perfect equivalence is not required. Sufficient fidelity means the receiver can perform the next bounded action without violating the original constraints.
 
## Fidelity is a vector
 
Shadowfax measures:
 
 
- factual fidelity;
 
- authority fidelity;
 
- uncertainty fidelity;
 
- intention fidelity;
 
- cultural and pragmatic fidelity;
 
- action-boundary fidelity;
 
- reversibility fidelity;
 
- provenance fidelity.
 

 
Some failures are noncompensatory. Excellent linguistic translation cannot compensate for invented authority or removed consent.
 
## Journey states
 
At every hop:
 
 
- `1` = sufficient fidelity was preserved for the declared next step;
 
- `0` = the route or rendering is rejected and must stop or return;
 
- `NULL` = preservation cannot be established.
 

 
These states concern the packet’s journey. They do not classify the carrier or civilisation as good, evil, alive, or dead.
 
## Long-distance rules
 
As distance and time increase:
 
 
- the invariant core becomes smaller;
 
- authority becomes narrower;
 
- expiry becomes more important;
 
- identity confidence decreases;
 
- translation loss accumulates;
 
- irreversible actions require stronger verification;
 
- silence increasingly means `NULL`;
 
- the message must remain useful even if its sender no longer exists.
 

 
A message may survive its civilisation. Its information may remain valid while its authority has expired.
 
## TERRA deployment
 
Locally, Shadowfax connects:
 
 
- people with different communication styles;
 
- languages and cultures;
 
- user and LLM;
 
- departments and institutions;
 
- scientific, commercial, political, and community contexts;
 
- disconnected systems and databases.
 

 
TERRA waystations can be audited stores, review boards, translation agents, isolated sandboxes, or human cultural attachés.
 
The first practical test is whether a message can cross several human and machine contexts while preserving:
 
 
1. the same facts;
 
2. the same uncertainty;
 
3. the same authority boundary;
 
4. the same safe next action.
 

 
## Milky Way deployment
 
Across the Milky Way:
 
 
- autonomous relays act as waystations;
 
- every star system retains local sovereignty;
 
- no relay inherits universal trust;
 
- long delays prevent central command;
 
- messages carry epoch and expiry data;
 
- multiple independent routes test for corruption;
 
- physical approach remains separate from information exchange;
 
- compromised relays are quarantined without condemning their civilisation.
 

 
## Beyond the Milky Way
 
Beyond the galaxy, Shadowfax assumes that the original sender, receiver, and route may all change before delivery.
 
Packets therefore carry propositions and constraints, not permanent commands.
 
The receiver may answer:
 
 
- `1`, sufficient meaning exists for one bounded continuation;
 
- `0`, the proposed relationship is declined;
 
- `NULL`, the frame cannot currently be resolved.
 

 
No response is treated as consent, hostility, or proof of extinction.
 
## Core doctrine
 
The Fellowship gives the journey legitimacy.
 
The Riders provide custody and judgment.
 
The carriers provide reach.
 
The waystations provide translation and containment.
 
The seals preserve the core.
 
The receipts preserve truth about what actually arrived.
 
Shadowfax succeeds when information travels farther than any single language, actor, model, or civilisation could carry it alone, while remaining bounded enough that imperfection does not become semantic conquest.
