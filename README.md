# Nomic AI

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Nomic AI builds open and accessible AI infrastructure. The company is known for the open-source Nomic Embed family (nomic-embed-text-v1.5, nomic-embed-vision-v1.5) of multilingual text and vision embedding models, the Nomic Atlas platform for exploring, labelling, and operationalising unstructured data via interactive 2D maps, and the GPT4All open-source ecosystem for running large language models locally on consumer CPUs and GPUs. The Nomic Atlas REST API at api-atlas.nomic.ai exposes endpoints for datasets, maps, embeddings, file parsing, and task status, with official Python and TypeScript SDKs.

**Areas:** Embeddings · Data Exploration · LLM · Open Source · RAG · Atlas

## Nomic AI on APIs.io

Everything profiled for Nomic AI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nomic-ai/](https://apis.io/providers/nomic-ai/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Nomic Atlas API](https://apis.io/apis/nomic-ai/atlas/) — REST API for the Nomic Atlas platform. Exposes endpoints for creating and managing datasets, building 2D semantic maps over text and image data, querying…
- [Nomic Embedding API](https://apis.io/apis/nomic-ai/embeddings/) — Hosted embedding endpoint backed by the Nomic Embed model family (nomic-embed-text-v1.5 and nomic-embed-vision-v1.5). Returns dense multilingual text and…
- [Nomic Atlas File Parsing API](https://apis.io/apis/nomic-ai/file-parsing/) — Upload, parse, and extract endpoints for ingesting PDFs and other documents into Atlas as structured text and tables prior to embedding and map building.
- [Nomic Atlas Task Status API](https://apis.io/apis/nomic-ai/task-status/) — Polling endpoint that returns the status of long-running Atlas jobs (map builds, embeddings, dataset operations).
- [Nomic Python SDK](https://apis.io/apis/nomic-ai/python-sdk/) — Official Python client (nomic) for the Atlas platform, embedding API, and dataset/map workflows.
- [Nomic TypeScript SDK](https://apis.io/apis/nomic-ai/typescript-sdk/) — Official TypeScript / JavaScript client for the Nomic Atlas API.
- [GPT4All](https://apis.io/apis/nomic-ai/gpt4all/) — Open-source ecosystem for running large language models locally on consumer hardware. Ships a desktop chat client, a local OpenAI-compatible HTTP server,…
- [nomic-embed-text-v1.5 (Open Weights)](https://apis.io/apis/nomic-ai/embed-text-model/) — Open-weights multilingual text embedding model published on Hugging Face, Apache-2.0 licensed. Supports Matryoshka-style truncatable embeddings and…
- [nomic-embed-vision-v1.5 (Open Weights)](https://apis.io/apis/nomic-ai/embed-vision-model/) — Open-weights vision embedding model that shares an embedding space with nomic-embed-text-v1.5 to support cross-modal retrieval. Published on Hugging Face.
- [Nomic AI Embeddings API](https://apis.io/apis/nomic-ai/nomic-ai-embeddings-api/) — The Embeddings API from Nomic AI — 1 operation(s) for embeddings.
- [Nomic AI Files API](https://apis.io/apis/nomic-ai/nomic-ai-files-api/) — The Files API from Nomic AI — 2 operation(s) for files.
- [Nomic AI Tasks API](https://apis.io/apis/nomic-ai/nomic-ai-tasks-api/) — The Tasks API from Nomic AI — 1 operation(s) for tasks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nomic Ai Agentic Access](https://apis.io/agentic-access/nomic-ai/nomic-ai-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Nomic Atlas API](https://apis.io/collections/nomic-ai/open-nomic-ai/)
- [Nomic Atlas Embeddings API](https://apis.io/collections/nomic-ai/open-nomic-ai-embeddings-api/)
- [Nomic Atlas Embeddings Files API](https://apis.io/collections/nomic-ai/open-nomic-ai-files-api/)
- [Nomic Atlas Embeddings Tasks API](https://apis.io/collections/nomic-ai/open-nomic-ai-tasks-api/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Nomic Ai Authentication](https://apis.io/security/nomic-ai/nomic-ai-authentication/)
- [Nomic Ai Domain Security](https://apis.io/security/nomic-ai/nomic-ai-domain-security/)
- [Nomic Ai Trust Center](https://apis.io/security/nomic-ai/nomic-ai-trust-center/)
- [Nomic Ai Vulnerability Disclosure](https://apis.io/security/nomic-ai/nomic-ai-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nomic Ai Plans Pricing](https://apis.io/plans/nomic-ai/nomic-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nomic Ai Rate Limits](https://apis.io/rate-limits/nomic-ai/nomic-ai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nomic Ai Finops](https://apis.io/finops/nomic-ai/nomic-ai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nomic.ai/)
- [Documentation](https://docs.nomic.ai/)
- [Blog](https://www.nomic.ai/news)

## API Evangelist rating

**Kin Score 30.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 52.2 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 23.8 |
| Access clarity | 13.2 |

**Agent readiness 20.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nomic-ai/](https://apis.io/providers/nomic-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nomic AI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nomic-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
