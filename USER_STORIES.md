# HarborPick — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Edge SRE

- As an edge SRE, I want jam-aware removal of servers from the feasible set, so clients stop retrying black holes.
- As an edge SRE, I want regret dashboards versus latency-only balancing, so I can prove the security-aware picker earns its keep.
- As an edge SRE, I want stochastic vs adversarial mode per site, so I can match the threat model.

### IoT application owner

- As an application owner, I want an offload pick API before each task, so my app stops hard-coding MEC endpoints.
- As an application owner, I want fail-closed local degrade when no server is acceptable, so bad edges never see sensitive payloads.

### Security architect

- As a security architect, I want contractual trust tiers to cap exploration, so the bandit cannot “learn” to use a prohibited node.
- As a security architect, I want tenant-scoped cooperation graphs, so side-observations do not leak across customers.
- As a security architect, I want outcome flags for privacy-prying suspicion, so risk vectors update faster than quarterly reviews.

### Device firmware engineer

- As a firmware engineer, I want a tiny client that samples from the returned distribution, so MCUs stay simple.
- As a firmware engineer, I want compact outcome reports, so learning works on constrained uplinks.

### Platform administrator

- As an administrator, I want to register and retire MEC servers with attestation metadata, so arms enter/exit cleanly.
- As an administrator, I want energy-avoided reports during jam weeks, so finance sees the alternative to power ramps.
