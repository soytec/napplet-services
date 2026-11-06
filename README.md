# napplet-services

Hosted services for [napplet.soy](https://napplet.soy), maintained by [Soytec](https://github.com/soytec).

**Status: repository bootstrap.** The proposed architecture is under maintainer review. Runtime code has not been extracted or deployed from this repository yet.

Review [the architecture PR](https://github.com/soytec/.github/pull/1) or read the [organization architecture proposal](https://github.com/soytec/.github/blob/codex/services-architecture/ARCHITECTURE.md) for the boundaries, deployment strategy and migration gates.

## Proposed scope

- Hosted Studio: private workspaces, job orchestration, inference broker, isolated build and capture jobs.
- Catalog, indexing, media caching and operator service interfaces.
- Independently deployed relay, Blossom, GRASP, public CVM and TURN service packaging.

The browser shell and Studio UI stay in [napplet-soy](https://github.com/soytec/napplet-soy). The local creator workflow lives in [soyli](https://github.com/soytec/soyli). Proprietary product CVMs remain in their own private repositories.

Until the extraction is reviewed and implemented, hosted runtime code and deployment instructions remain in [napplet-soy](https://github.com/soytec/napplet-soy). There is no install or deployment command for this bootstrap repository.
