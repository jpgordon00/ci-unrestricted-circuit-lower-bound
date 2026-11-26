# Does any language in E^NP require Ω(n log n)-size unrestricted circuits?

Work on a circuit lower-bound question explicitly posed in a November 2026 preprint.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/unrestricted-circuit-lower-bound/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-unrestricted-circuit-lower-bound/pulls)

## Why this matters

The question concerns explicit Boolean functions in exponential time with an NP oracle, and unrestricted circuits. Depth-two conjunction/disjunction formulas with negations on inputs give a more accessible model in which parity has a provable exponential bound.

## What to contribute

Reproduce the odd-parity lower bound for depth-two disjunctive normal form. Identify the place in the argument that relies on each term being a conjunction of literals.

## How reviewers check it

Supply a proof of the bound and an independent small truth-table check. State the circuit model, size measure and which lower-bound claim remains open.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/unrestricted-circuit-lower-bound
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/unrestricted-circuit-lower-bound/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-unrestricted-circuit-lower-bound/security/advisories/new) for security reports.

## Sources

- [Chukhin et al., ECCC 2026/313 (Open Problem 1)](<https://eccc.weizmann.ac.il/report/2026/313/>)
