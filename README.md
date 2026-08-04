# Nomic AI (nomic-ai)

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

Nomic AI builds open and accessible AI infrastructure. The company is known for the open-source Nomic Embed family (nomic-embed-text-v1.5, nomic-embed-vision-v1.5) of multilingual text and vision embedding models, the Nomic Atlas platform for exploring, labelling, and operationalising unstructured data via interactive 2D maps, and the GPT4All open-source ecosystem for running large language models locally on consumer CPUs and GPUs. The Nomic Atlas REST API at api-atlas.nomic.ai exposes endpoints for datasets, maps, embeddings, file parsing, and task status, with official Python and TypeScript SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nomic-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nomic-ai/refs/heads/main/apis.yml)

## Tags

- Embeddings
- Vector Database
- Data Exploration
- LLM
- Open Source
- RAG
- Atlas

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Nomic Atlas API

REST API for the Nomic Atlas platform. Exposes endpoints for creating and managing datasets, building 2D semantic maps over text and image data, querying and updating points, and orchestrating long-running map build jobs. Authentication is via an Atlas-issued API key.

- **Human URL:** [https://docs.nomic.ai/reference/getting-started](https://docs.nomic.ai/reference/getting-started)
- **Base URL:** `https://api-atlas.nomic.ai`

#### Tags

- Datasets
- Maps
- Vector Search
- REST

#### Properties

- [Documentation](https://docs.nomic.ai/reference/getting-started)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomic Embedding API

Hosted embedding endpoint backed by the Nomic Embed model family (nomic-embed-text-v1.5 and nomic-embed-vision-v1.5). Returns dense multilingual text and image vectors with Matryoshka-style configurable output dimensions for retrieval, clustering, and RAG.

- **Human URL:** [https://docs.nomic.ai/atlas/embeddings-and-retrieval/text-embeddings](https://docs.nomic.ai/atlas/embeddings-and-retrieval/text-embeddings)
- **Base URL:** `https://api-atlas.nomic.ai`

#### Tags

- Embeddings
- Text
- Vision
- Multilingual

#### Properties

- [Documentation](https://docs.nomic.ai/atlas/embeddings-and-retrieval/text-embeddings)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomic Atlas File Parsing API

Upload, parse, and extract endpoints for ingesting PDFs and other documents into Atlas as structured text and tables prior to embedding and map building.

- **Human URL:** [https://docs.nomic.ai/atlas/data/file-upload](https://docs.nomic.ai/atlas/data/file-upload)
- **Base URL:** `https://api-atlas.nomic.ai`

#### Tags

- File Upload
- Parsing
- Extraction

#### Properties

- [Documentation](https://docs.nomic.ai/atlas/data/file-upload)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomic Atlas Task Status API

Polling endpoint that returns the status of long-running Atlas jobs (map builds, embeddings, dataset operations).

- **Human URL:** [https://docs.nomic.ai/reference/getting-started](https://docs.nomic.ai/reference/getting-started)
- **Base URL:** `https://api-atlas.nomic.ai`

#### Tags

- Jobs
- Tasks
- Async

#### Properties

- [Documentation](https://docs.nomic.ai/reference/getting-started)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomic Python SDK

Official Python client (nomic) for the Atlas platform, embedding API, and dataset/map workflows.

- **Human URL:** [https://github.com/nomic-ai/nomic](https://github.com/nomic-ai/nomic)
- **Base URL:** `https://github.com/nomic-ai/nomic`

#### Tags

- SDK
- Python
- Atlas

#### Properties

- [Repository](https://github.com/nomic-ai/nomic)
- [Package](https://pypi.org/project/nomic/)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomic TypeScript SDK

Official TypeScript / JavaScript client for the Nomic Atlas API.

- **Human URL:** [https://github.com/nomic-ai/ts-nomic](https://github.com/nomic-ai/ts-nomic)
- **Base URL:** `https://github.com/nomic-ai/ts-nomic`

#### Tags

- SDK
- TypeScript
- JavaScript

#### Properties

- [Repository](https://github.com/nomic-ai/ts-nomic)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GPT4All

Open-source ecosystem for running large language models locally on consumer hardware. Ships a desktop chat client, a local OpenAI-compatible HTTP server, and Python and TypeScript bindings. MIT-licensed.

- **Human URL:** [https://www.nomic.ai/gpt4all](https://www.nomic.ai/gpt4all)
- **Base URL:** `https://github.com/nomic-ai/gpt4all`

#### Tags

- LLM
- Local Inference
- Open Source
- On-Device

#### Properties

- [Repository](https://github.com/nomic-ai/gpt4all)
- [Website](https://www.nomic.ai/gpt4all)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### nomic-embed-text-v1.5 (Open Weights)

Open-weights multilingual text embedding model published on Hugging Face, Apache-2.0 licensed. Supports Matryoshka-style truncatable embeddings and task-type prefixes.

- **Human URL:** [https://huggingface.co/nomic-ai/nomic-embed-text-v1.5](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)
- **Base URL:** `https://huggingface.co/nomic-ai/nomic-embed-text-v1.5`

#### Tags

- Model
- Embeddings
- Open Weights
- Hugging Face

#### Properties

- [Repository](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### nomic-embed-vision-v1.5 (Open Weights)

Open-weights vision embedding model that shares an embedding space with nomic-embed-text-v1.5 to support cross-modal retrieval. Published on Hugging Face.

- **Human URL:** [https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5](https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5)
- **Base URL:** `https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5`

#### Tags

- Model
- Embeddings
- Vision
- Open Weights

#### Properties

- [Repository](https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5)
- [Postman Collection](collections/nomic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nomic-ai)
- [Website](https://www.nomic.ai/)
- [Documentation](https://docs.nomic.ai/)
- [Git Hub](https://github.com/nomic-ai)
- [Hugging Face](https://huggingface.co/nomic-ai)
- [Plans](plans/nomic-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/nomic-ai-rate-limits.yml)
- [Fin Ops](finops/nomic-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
