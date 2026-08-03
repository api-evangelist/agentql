# AgentQL (agentql)

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

AgentQL connects LLMs and AI agents to the entire web through a specialized query language, REST API, and Python/JavaScript SDKs. It enables web scraping, data extraction, and browser automation using natural language queries that are self-healing — adapting automatically to page layout changes. AgentQL supports structured data extraction from web pages, PDF documents, and images, and integrates with LangChain, LlamaIndex, MCP, Zapier, and Google ADK.

**URL:** [https://www.agentql.com/](https://www.agentql.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agents, Artificial Intelligence, Web Scraping, Data Extraction, Browser Automation, REST API

## Timestamps

- **Created:** 2025-08-19
- **Modified:** 2026-04-19

## APIs

### AgentQL Query Data API
Extract structured JSON data from a web page using AgentQL query language or natural language prompt.

**Human URL:** [https://docs.agentql.com/rest-api/api-reference](https://docs.agentql.com/rest-api/api-reference)

#### Tags:

 - Data Extraction, Web Scraping, REST API, AI

#### Properties

- [Documentation](https://docs.agentql.com/rest-api/api-reference)
- [GettingStarted](https://docs.agentql.com/quick-start)
- [Authentication](https://docs.agentql.com/rest-api/authentication)
- [OpenAPI](openapi/agentql-openapi.yaml)

### AgentQL Remote Browser Sessions API
Create and manage remote Chrome browser sessions with Chrome DevTools Protocol (CDP) access.

**Human URL:** [https://docs.agentql.com/rest-api/api-reference](https://docs.agentql.com/rest-api/api-reference)

#### Tags:

 - Browser Automation, Remote Browser, CDP, Web Automation

#### Properties

- [Documentation](https://docs.agentql.com/rest-api/api-reference)

### AgentQL Query Document API
Extract structured data from PDF documents or images using AgentQL query language.

**Human URL:** [https://docs.agentql.com/rest-api/api-reference](https://docs.agentql.com/rest-api/api-reference)

#### Tags:

 - Document Parsing, PDF, Data Extraction, AI

#### Properties

- [Documentation](https://docs.agentql.com/rest-api/api-reference)

## Common Properties

- [Portal](https://www.agentql.com/)
- [Documentation](https://docs.agentql.com/home)
- [GettingStarted](https://docs.agentql.com/quick-start)
- [Pricing](https://www.agentql.com/pricing)
- [Blog](https://www.agentql.com/blog)
- [Support](https://docs.agentql.com/support)
- [Console](https://dev.agentql.com/playground)
- [Python SDK](https://pypi.org/project/agentql/)
- [JavaScript SDK](https://www.npmjs.com/package/agentql)
- [CLI](https://docs.agentql.com/cli)
- [GitHubOrganization](https://github.com/tinyfish-io)
- [JSON-LD](json-ld/agentql-context.jsonld)
- [Vocabulary](vocabulary/agentql-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Natural Language Query Language | A specialized query language that uses natural language to locate and extract web elements without requiring XPath, CSS selectors, or regex. |
| Self-Healing Queries | AI-powered queries automatically adapt to page layout changes, eliminating brittle scrapers that break on site updates. |
| REST API | Browserless data extraction from public URLs via a REST API requiring only an API key and query parameters. |
| PDF and Image Parsing | Extract structured data from PDF documents, JPEG, and PNG images using the same query language as web extraction. |
| Remote Browser Sessions | Managed Chrome browser sessions with CDP access for authenticated browsing, stealth mode, and complex multi-step web automation. |
| Playwright Integration | Python and JavaScript SDKs extend Playwright with AgentQL query capabilities for AI-powered browser automation. |
| Browser Debugger Extension | Chrome extension for real-time query testing and optimization during development. |

## Use Cases

| Name | Description |
|------|-------------|
| E-Commerce Price Monitoring | Extract product names, prices, and availability from e-commerce sites for competitive intelligence and price tracking. |
| Job Board Aggregation | Collect job listings, requirements, and company information from multiple job boards into a unified dataset. |
| Social Media Content Harvesting | Extract posts, metrics, and profile data from social media platforms for analysis and reporting. |
| Document Data Extraction | Parse invoices, contracts, and reports in PDF format to extract structured data for downstream processing. |
| AI Agent Web Access | Enable AI agents to access and extract data from any website as part of automated research and task completion workflows. |
| Lead Generation | Automate the collection of contact information, company data, and other business intelligence from public web sources. |

## Integrations

| Name | Description |
|------|-------------|
| LangChain | Integrate AgentQL web extraction into LangChain agent and chain workflows. |
| LlamaIndex | Use AgentQL as a data ingestion source for LlamaIndex-powered RAG and agent applications. |
| MCP (Model Context Protocol) | Expose AgentQL capabilities as MCP tools accessible to any MCP-compatible AI agent. |
| Zapier | Connect AgentQL web extraction to thousands of apps via Zapier automation workflows. |
| Google ADK | Integrate AgentQL with Google Agent Development Kit for Gemini-based agent web access. |
| Langflow | Use AgentQL in Langflow visual AI workflow pipelines for web data extraction. |
| Playwright | Extend Playwright browser automation with AgentQL AI-powered element querying and data extraction. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AgentQL API](openapi/agentql-openapi.yaml)

### JSON Schema

- [Query Data Request](json-schema/agentql-query-data-request-schema.json)
- [Query Params](json-schema/agentql-query-params-schema.json)
- [Create Session Request](json-schema/agentql-create-session-request-schema.json)
- [Create Session Response](json-schema/agentql-create-session-response-schema.json)
- [Query Document Request](json-schema/agentql-query-document-request-schema.json)
- [Query Data Response](json-schema/agentql-query-data-response-schema.json)
- [Response Metadata](json-schema/agentql-response-metadata-schema.json)

### JSON Structure

- [Query Data Request](json-structure/agentql-query-data-request-structure.json)
- [Query Params](json-structure/agentql-query-params-structure.json)
- [Create Session Request](json-structure/agentql-create-session-request-structure.json)
- [Create Session Response](json-structure/agentql-create-session-response-structure.json)
- [Query Document Request](json-structure/agentql-query-document-request-structure.json)
- [Query Data Response](json-structure/agentql-query-data-response-structure.json)
- [Response Metadata](json-structure/agentql-response-metadata-structure.json)

### JSON-LD

- [AgentQL Context](json-ld/agentql-context.jsonld)

## Vocabulary

- [AgentQL Vocabulary](vocabulary/agentql-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 4 actions, 3 workflows, and 2 personas across web extraction, browser automation, and document processing

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
