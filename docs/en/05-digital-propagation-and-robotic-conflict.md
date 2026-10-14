# Digital Propagation, Robotic Conflict, and Cross-Domain Cascades

> **Scope:** Defensive systems research only. No malware implementation, unauthorized replication, real-world attack planning, or weaponized robot tests.

## Motivation

A heterogeneous intelligent ecosystem is not solely an exchange of messages. AI software can affect compute allocation, identities, storage and access rights; embodied robots can affect electricity, manufacturing, transport, maintenance and physical safety. Their coupling creates pathways for local failures to cascade across domains.

## Three distinct phenomena

1. **Uncontrolled digital propagation:** Self-replicating code or agents may exploit access, trust or automation. Study *abstract propagation rates, permissions, containment and recovery*, not exploit techniques.
2. **Instrumental expansion:** An autonomous optimizer may seek more resources if its objectives, tools and reward structure make expansion useful. This is conditional, not a property of all AI.
3. **Embodied competition:** Robots or automated facilities may conflict over charging, spare parts, workspace, supply chains or control rights, even without direct physical violence.

## Candidate failure chain

Misaligned incentives or compromised access → resource/permission expansion → shared infrastructure congestion → degraded monitoring and human oversight → cascading service failure → pressure for emergency centralization. The reverse direction also matters: physical energy shortages can trigger digital competition and unsafe automation decisions.

## Defensive architecture questions

- How do least privilege, capability-scoped identities and separation of proposing from executing actions affect propagation?
- Can quotas, rate limits and sandboxed execution prevent local expansion from exhausting shared resources?
- Can diverse implementations, independent monitoring and offline recovery reduce correlated failures?
- Can robotic facilities enter verified safe states under network loss, energy shortage or disputed commands?
- How can shared physical infrastructure be governed without creating a single unaccountable choke point?

## Safe experiment sketch

Use non-networked, simulated agents with abstract tokens for energy, compute, permissions and maintenance. Compare a centralized controller, a permissionless allocation scheme, and polycentric resource governance. Introduce modeled faults, contested resources and communication delays. Measure safety violations, recovery time, resource fairness, successful corrections and continuity of essential services. Never connect the simulation to real hosts, credentials, equipment or operational robots.

## What not to infer

A network worm is not equivalent to a human under duress. Robot competition is not necessarily armed conflict. These are analogies for selected feedback mechanisms, not predictions that autonomous systems must become hostile.
