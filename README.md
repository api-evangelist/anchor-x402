# anchor-x402

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

anchor-x402 operates a pay-per-call API surface for AI agents, billed with the x402 HTTP payment protocol instead of API keys or accounts. Eighteen stateless services run on AWS Lambda and FastAPI behind https://api.anchor-x402.com, each returning an x402 v2 402 PaymentRequired challenge that a caller settles per request in USDC on Base or Solana (select routes also settle JPYC on Polygon) via EIP-3009 transferWithAuthorization. The catalog spans on-chain anchoring and attestation, wallet sanctions and risk screening, Web3 data decoding, ENS/SNS name resolution, token pricing, x402 spend accounting, verifiable signed randomness, and LLM-backed content analysis, priced from $0.001 to $1.77 per call. The same 18 services are exposed over MCP (a hosted Streamable HTTP endpoint at https://api.anchor-x402.com/mcp whose tools/list is free and anonymous, plus an npm stdio package) and over a signed A2A JSON-RPC door at /v1/a2a, with a conformant A2A 0.3.0 agent card and a hosted Claude chatbot at chat.anchor-x402.com for non-developers. Source is MIT licensed and the operator publishes a trust portal that states plainly it holds no SOC 2, ISO 27001, PCI or HIPAA certification.

**Areas:** Company · x402 · Agents · Payments · Blockchain · MCP · Web3 · pay-per-call · Agentic Payments · Stablecoins · Compliance · Attestation

## anchor-x402 on APIs.io

Everything profiled for anchor-x402 is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anchor-x402/](https://apis.io/providers/anchor-x402/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [anchor-x402 Anchor API](https://apis.io/apis/anchor-x402/anchor-x402-anchor-api/) — The Anchor API from anchor-x402 — 1 operation(s) for anchor.
- [anchor-x402 Attest API](https://apis.io/apis/anchor-x402/anchor-x402-attest-api/) — The Attest API from anchor-x402 — 2 operation(s) for attest.
- [anchor-x402 Aura API](https://apis.io/apis/anchor-x402/anchor-x402-aura-api/) — The Aura API from anchor-x402 — 1 operation(s) for aura.
- [anchor-x402 Decode API](https://apis.io/apis/anchor-x402/anchor-x402-decode-api/) — The Decode API from anchor-x402 — 2 operation(s) for decode.
- [anchor-x402 Grade API](https://apis.io/apis/anchor-x402/anchor-x402-grade-api/) — The Grade API from anchor-x402 — 1 operation(s) for grade.
- [anchor-x402 Health API](https://apis.io/apis/anchor-x402/anchor-x402-health-api/) — The Health API from anchor-x402 — 1 operation(s) for health.
- [anchor-x402 Intel API](https://apis.io/apis/anchor-x402/anchor-x402-intel-api/) — The Intel API from anchor-x402 — 1 operation(s) for intel.
- [anchor-x402 Investigate API](https://apis.io/apis/anchor-x402/anchor-x402-investigate-api/) — The Investigate API from anchor-x402 — 2 operation(s) for investigate.
- [anchor-x402 Ledger API](https://apis.io/apis/anchor-x402/anchor-x402-ledger-api/) — The Ledger API from anchor-x402 — 3 operation(s) for ledger.
- [anchor-x402 Oracle API](https://apis.io/apis/anchor-x402/anchor-x402-oracle-api/) — The Oracle API from anchor-x402 — 1 operation(s) for oracle.
- [anchor-x402 Parse API](https://apis.io/apis/anchor-x402/anchor-x402-parse-api/) — The Parse API from anchor-x402 — 1 operation(s) for parse.
- [anchor-x402 Price API](https://apis.io/apis/anchor-x402/anchor-x402-price-api/) — The Price API from anchor-x402 — 1 operation(s) for price.
- [anchor-x402 Resolve API](https://apis.io/apis/anchor-x402/anchor-x402-resolve-api/) — The Resolve API from anchor-x402 — 1 operation(s) for resolve.
- [anchor-x402 Roast API](https://apis.io/apis/anchor-x402/anchor-x402-roast-api/) — The Roast API from anchor-x402 — 1 operation(s) for roast.
- [anchor-x402 Roll API](https://apis.io/apis/anchor-x402/anchor-x402-roll-api/) — The Roll API from anchor-x402 — 1 operation(s) for roll.
- [anchor-x402 Screen API](https://apis.io/apis/anchor-x402/anchor-x402-screen-api/) — The Screen API from anchor-x402 — 1 operation(s) for screen.
- [anchor-x402 Tldr API](https://apis.io/apis/anchor-x402/anchor-x402-tldr-api/) — The Tldr API from anchor-x402 — 1 operation(s) for tldr.
- [anchor-x402 Feedback API](https://apis.io/apis/anchor-x402/anchor-x402-feedback-api/) — The Feedback API from anchor-x402 — 1 operation(s) for feedback.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [anchor-x402](https://apis.io/servers/anchor-x402/anchor-x402/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anchor X402 Agentic Access](https://apis.io/agentic-access/anchor-x402/anchor-x402-agentic-access/)

#### JSON Schema (39)

The data models the API reads and writes.

- [AnchorRequest](https://apis.io/schemas/anchor-x402/anchor-x402-anchor-request/)
- [AnchorResponse](https://apis.io/schemas/anchor-x402/anchor-x402-anchor-response/)
- [AttestRequest](https://apis.io/schemas/anchor-x402/anchor-x402-attest-request/)
- [AttestResponse](https://apis.io/schemas/anchor-x402/anchor-x402-attest-response/)
- [AttestVerifyRequest](https://apis.io/schemas/anchor-x402/anchor-x402-attest-verify-request/)
- [AttestVerifyResponse](https://apis.io/schemas/anchor-x402/anchor-x402-attest-verify-response/)
- [AuraRequest](https://apis.io/schemas/anchor-x402/anchor-x402-aura-request/)
- [AuraResponse](https://apis.io/schemas/anchor-x402/anchor-x402-aura-response/)
- [CalldataDecodeRequest](https://apis.io/schemas/anchor-x402/anchor-x402-calldata-decode-request/)
- [CalldataDecodeResponse](https://apis.io/schemas/anchor-x402/anchor-x402-calldata-decode-response/)
- [DatetimeParseRequest](https://apis.io/schemas/anchor-x402/anchor-x402-datetime-parse-request/)
- [DatetimeParseResponse](https://apis.io/schemas/anchor-x402/anchor-x402-datetime-parse-response/)
- [FeedbackRequest](https://apis.io/schemas/anchor-x402/anchor-x402-feedback-request/)
- [GradeRequest](https://apis.io/schemas/anchor-x402/anchor-x402-grade-request/)
- [GradeResponse](https://apis.io/schemas/anchor-x402/anchor-x402-grade-response/)
- [IntelWalletResponse](https://apis.io/schemas/anchor-x402/anchor-x402-intel-wallet-response/)
- [InvestigateAcceptedResponse](https://apis.io/schemas/anchor-x402/anchor-x402-investigate-accepted-response/)
- [InvestigateRequest](https://apis.io/schemas/anchor-x402/anchor-x402-investigate-request/)
- [InvestigateStatusResponse](https://apis.io/schemas/anchor-x402/anchor-x402-investigate-status-response/)
- [LedgerReportAccepted](https://apis.io/schemas/anchor-x402/anchor-x402-ledger-report-accepted/)
- [LedgerReportRequest](https://apis.io/schemas/anchor-x402/anchor-x402-ledger-report-request/)
- [LedgerReportStatus](https://apis.io/schemas/anchor-x402/anchor-x402-ledger-report-status/)
- [LedgerSummaryRequest](https://apis.io/schemas/anchor-x402/anchor-x402-ledger-summary-request/)
- [_NameBody](https://apis.io/schemas/anchor-x402/anchor-x402-name-body/)
- [NameResolveResponse](https://apis.io/schemas/anchor-x402/anchor-x402-name-resolve-response/)
- …and 14 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Anchor X402 Context](https://apis.io/jsonld/anchor-x402/anchor-x402-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Anchor X402 Openapi Overlay](https://apis.io/overlays/anchor-x402/anchor-x402-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [anchor-x402 API Rules](https://apis.io/rules/anchor-x402/anchor-x402-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Anchor X402 Authentication](https://apis.io/security/anchor-x402/anchor-x402-authentication/)
- [Anchor X402 Domain Security](https://apis.io/security/anchor-x402/anchor-x402-domain-security/)
- [Anchor X402 Trust Center](https://apis.io/security/anchor-x402/anchor-x402-trust-center/)
- [Anchor X402 Vulnerability Disclosure](https://apis.io/security/anchor-x402/anchor-x402-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Anchor X402 Plans Pricing](https://apis.io/plans/anchor-x402/anchor-x402-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Anchor X402 Rate Limits](https://apis.io/rate-limits/anchor-x402/anchor-x402-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://anchor-x402.com)
- [Documentation](https://api.anchor-x402.com/docs)
- [Getting started](https://anchor-x402.com/guides/pay-x402-api-node/)
- [API reference](https://api.anchor-x402.com/redoc)
- [Pricing](https://anchor-x402.com/.well-known/x402.json)
- [GitHub](https://github.com/hypeprinter007-stack)
- [Status](https://anchor-x402.betteruptime.com)

## API Evangelist rating

**Kin Score 46.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 42.9 |
| Contract governance | 18.2 |
| Operational transparency | 13.2 |
| Developer ergonomics | 71.4 |
| Access clarity | 50.0 |

**Agent readiness 42.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | — |

**Regulatory alignment 25.0** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anchor-x402/](https://apis.io/providers/anchor-x402/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for anchor-x402: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anchor-x402/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
