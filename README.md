# Orama (orama)

Orama is an open-source, in-memory search engine and RAG pipeline (full-text, vector, and hybrid search in under 2kb) plus Orama Cloud, a hosted REST platform for managing indexes, ingesting documents, running search, and building answer (RAG) experiences. The OSS engine is a JavaScript library; Orama Cloud is the managed API and dashboard layered on top.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/orama/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/orama/refs/heads/main/apis.yml)

## Tags

- Search
- Vector Search
- RAG
- Open Source
- Search as a Service

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Orama Cloud Indexes and Collections

Manage Orama Cloud indexes via the webhook management API - update the index schema, check for pending data, empty an index, and deploy queued changes worldwide. Index, project, and collection creation is performed in the Orama Cloud dashboard; the public API exposes per-index management operations.

- **Human URL:** [https://docs.orama.com/cloud](https://docs.orama.com/cloud)
- **Base URL:** `https://api.askorama.ai/api/v1`

#### Tags

- Indexes
- Collections
- Deployments

#### Properties

- [Documentation](https://docs.orama.com/cloud)
- [API Reference](https://docs.orama.com/cloud/data-sources/custom-integrations/rest-apis)
- [OpenAPI](openapi/orama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Orama Cloud Documents

Insert, update, and delete documents in an Orama Cloud index. The notify endpoint performs incremental upsert (by id) and remove operations; the snapshot endpoint bulk-replaces the entire index. Changes are published with a deploy call.

- **Human URL:** [https://docs.orama.com/cloud/data-sources/custom-integrations/rest-apis](https://docs.orama.com/cloud/data-sources/custom-integrations/rest-apis)
- **Base URL:** `https://api.askorama.ai/api/v1`

#### Tags

- Documents
- Ingestion
- Upsert

#### Properties

- [Documentation](https://docs.orama.com/cloud/data-sources/custom-integrations/rest-apis)
- [OpenAPI](openapi/orama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Orama Cloud Search

Run full-text, vector, and hybrid search queries against a deployed Orama Cloud index using a public read API key. Supports term, mode, where filters, limit, offset, threshold, and sortBy parameters.

- **Human URL:** [https://docs.orama.com/cloud/performing-search](https://docs.orama.com/cloud/performing-search)
- **Base URL:** `https://cloud.orama.run/v1/indexes`

#### Tags

- Search
- Full Text
- Vector
- Hybrid

#### Properties

- [Documentation](https://docs.orama.com/cloud/performing-search)
- [OpenAPI](openapi/orama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Orama Cloud Answer Sessions (RAG)

Generate grounded, conversational answers (retrieval-augmented generation) over an Orama Cloud index. The streaming answer endpoint powers the SDK AnswerSession (ask / askStream) with retrieved context and citations.

- **Human URL:** [https://docs.orama.com/cloud/answer-engine](https://docs.orama.com/cloud/answer-engine)
- **Base URL:** `https://answer.api.orama.com/v1`

#### Tags

- RAG
- Answer Engine
- Generative

#### Properties

- [Documentation](https://docs.orama.com/cloud/answer-engine)
- [OpenAPI](openapi/orama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Orama Open Source Engine

The open-source @orama/orama library (Apache 2.0) - a complete in-memory search engine and RAG pipeline that runs in the browser, on the server, or at the edge in under 2kb. Exposes JavaScript functions (create, insert, remove, search) for full-text, vector, and hybrid search; not an HTTP API.

- **Human URL:** [https://docs.orama.com/open-source](https://docs.orama.com/open-source)
- **Base URL:** `https://github.com/oramasearch/orama`

#### Tags

- Open Source
- Library
- In Memory

#### Properties

- [Documentation](https://docs.orama.com/open-source)
- [Source Code](https://github.com/oramasearch/orama)

## Common Properties

- [GitHub Organization](https://github.com/oramasearch)
- [LinkedIn](https://www.linkedin.com/company/askorama)
- [Website](https://orama.com)
- [Documentation](https://docs.orama.com)
- [Plans](plans/orama-plans-pricing.yml)
- [Rate Limits](rate-limits/orama-rate-limits.yml)
- [Fin Ops](finops/orama-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
