# Hiro (hiro)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Hiro builds developer tooling for Bitcoin and the Stacks layer. Provides REST APIs (Stacks Blockchain API, Token Metadata API, Signer Metrics API, Chainhooks API, Platform API), Stacks Node JSON-RPC, plus the Hiro Platform for managing devnets and chainhooks.

OpenAPI specs for the Stacks Blockchain API, Stacks Node RPC, Token Metadata API, and Signer Metrics API are captured in [`openapi/`](openapi/).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/hiro/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hiro-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Stacks Blockchain API** - REST API for Stacks blockchain data: blocks, transactions, mempool, accounts, smart contracts, BNS names, fungible/non-fungible tokens, microblocks, faucets, fee rates.
- **Stacks Node RPC API** - JSON-RPC interface to a Stacks node: submit transactions, call read-only contracts, query mempool/state.
- **Hiro Token Metadata API** - REST API for fungible and non-fungible token metadata on Stacks.
- **Hiro Signer Metrics API** - REST API to monitor and analyze signer behavior and performance on the Stacks Nakamoto network.
- **Hiro Chainhooks API** - REST API for Chainhook predicate registration and event streaming for Bitcoin and Stacks.
- **Hiro Platform API** - REST API to programmatically manage Hiro Platform devnets and chainhooks.

## Tags
 - Web3, Blockchain, Bitcoin, Stacks, sBTC, Indexing

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.hiro.so/)
- [Plans](plans/hiro-plans-pricing.yml)
- [RateLimits](rate-limits/hiro-rate-limits.yml)
- [FinOps](finops/hiro-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
