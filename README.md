# M3ter

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

m3ter is a usage-based billing and metering engine providing real-time usage data ingestion, pricing logic, and billing automation for API and SaaS products. The m3ter platform exposes two HTTP-based REST APIs returning JSON responses: an Ingest API for submitting raw usage measurements and a Config API for configuration and billing management. Authentication uses OAuth 2.0 Client Credentials with a Service User Access Key id and Api Secret exchanged for a Bearer Token at https://api.m3ter.com/oauth/token.

**Areas:** FinOps · Usage-Based Billing · Metering · Billing · Pricing · Software-as-a-Service

## M3ter on APIs.io

Everything profiled for M3ter is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/m3ter/](https://apis.io/providers/m3ter/)** — or go straight to one of the APIs or properties below.

### APIs (58)

- [M3ter Account API](https://apis.io/apis/m3ter/m3ter-account-api/) — Endpoints for Account related operations such as creation, update, list and delete. An Account represents one of your end-customer accounts. Accounts do not…
- [M3ter AccountPlan API](https://apis.io/apis/m3ter/m3ter-accountplan-api/) — Endpoints for AccountPlan and AccountPlanGroup related operations such as creation, update, list and delete. **AccountPlans** An Account represents one of…
- [M3ter Aggregation API](https://apis.io/apis/m3ter/m3ter-aggregation-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Aggregations. An Aggregation links to a Meter and targets a Data Field or Derived Field…
- [M3ter Auth API](https://apis.io/apis/m3ter/m3ter-auth-api/) — Endpoint for retrieving a JSON Web Token (JWT) bearer token for a ServiceUser using the Client Credentials Grant flow. A ServiceUser represents the…
- [M3ter BalanceChargeSchedule API](https://apis.io/apis/m3ter/m3ter-balancechargeschedule-api/) — Endpoints for creating/updating/deleting BalanceChargeSchedules. **NOTE!** The BalanceChargeSchedule feature is available in Beta release version. See…
- [M3ter Balances API](https://apis.io/apis/m3ter/m3ter-balances-api/) — Endpoints for creating/retrieving/updating/deleting Balances on Accounts. When you have created a Balance for an Account, you can create a positive or…
- [M3ter BalanceTransactionSchedule API](https://apis.io/apis/m3ter/m3ter-balancetransactionschedule-api/) — Endpoints for creating/updating/deleting BalanceTransactionSchedules. **NOTE!** The BalanceTransactionSchedule feature is available in Beta release version.…
- [M3ter Bill API](https://apis.io/apis/m3ter/m3ter-bill-api/) — Endpoints for billing operations such as creating, updating, listing,downloading, and deleting Bills. Bills are generated for an Account, and are calculated…
- [M3ter BillConfig API](https://apis.io/apis/m3ter/m3ter-billconfig-api/) — Endpoints for updating and retreiving the Bill Configuration for an Organization. The Organization represents your company as a direct customer of the m3ter…
- [M3ter BillGroupingKey API](https://apis.io/apis/m3ter/m3ter-billgroupingkey-api/) — Endpoints for Bill Grouping Key operations such as creation, update, list, and delete. Bill Grouping Keys are stored for your Organization, and you can use…
- [M3ter BillJob API](https://apis.io/apis/m3ter/m3ter-billjob-api/) — Endpoints for creating, retrieving, listing, and cancelling Bill Jobs. Bill Jobs are critical components in billing management, providing asynchronous…
- [M3ter Charge API](https://apis.io/apis/m3ter/m3ter-charge-api/) — Endpoints for creating/updating/deleting Charges. Create Charges for your end-customer Accounts to create ad-hoc line items for Account billing. Charges…
- [M3ter Commitments API](https://apis.io/apis/m3ter/m3ter-commitments-api/) — Endpoints that manage Commitments *(also known as Prepayments)* in the context of usage-based pricing and billing. A Commitment represents an agreement…
- [M3ter CompoundAggregation API](https://apis.io/apis/m3ter/m3ter-compoundaggregation-api/) — Endpoints for Compound Aggregation related operations such as creation, update, list and delete. Use Compound Aggregations to create numerical measures from…
- [M3ter Contract API](https://apis.io/apis/m3ter/m3ter-contract-api/) — Endpoints for Contract related operations such as creation, update, list and delete. Contracts are created for Accounts, which are your end-user customers.…
- [M3ter Counter API](https://apis.io/apis/m3ter/m3ter-counter-api/) — Endpoints for listing, creating, retrieving, updating, or deleting Counters. You can create Counters for your m3ter Organization, which can then be used as…
- [M3ter CounterAdjustments API](https://apis.io/apis/m3ter/m3ter-counteradjustments-api/) — Endpoints for listing, creating, updating, retrieving, or deleting CounterAdjustments. If you attach a Plan to an Account which is priced using a Counter to…
- [M3ter CounterPricing API](https://apis.io/apis/m3ter/m3ter-counterpricing-api/) — Endpoints for listing, creating, updating, retrieving, or deleting CounterPricing. Create the CounterPricing for a Plan/PlanTemplate using a Counter, and…
- [M3ter CreditReason API](https://apis.io/apis/m3ter/m3ter-creditreason-api/) — Endpoints for CreditReason operations such as creation, update, list, and delete. You can create CreditReasons for your Organization, and then use them when…
- [M3ter Credits API](https://apis.io/apis/m3ter/m3ter-credits-api/) — Endpoints for Credit line item related operations such as creation, update, list and delete. These are line items on Bills that are specifically related to…
- [M3ter Currency API](https://apis.io/apis/m3ter/m3ter-currency-api/) — Endpoints for Currency operations such as creation, update, list, and delete. Currencies are stored for your Organization, and can then be used to specify…
- [M3ter DataExplorerV2 API](https://apis.io/apis/m3ter/m3ter-dataexplorerv2-api/) — Endpoints for querying and filtering Usage data collected for your Organization. **IMPORTANT: Request Rate Limits for Data Explorer v2!** As part of the…
- [M3ter DebitReason API](https://apis.io/apis/m3ter/m3ter-debitreason-api/) — Endpoints for DebitReason operations such as creation, update, list, and delete. You can create DebitReasons for your Organization, and then use them when…
- [M3ter Debits API](https://apis.io/apis/m3ter/m3ter-debits-api/) — Endpoints for Debit line item related operations such as creation, update, list and delete. These are line items on Bills that are specifically related to…
- [M3ter Events API](https://apis.io/apis/m3ter/m3ter-events-api/) — This section provides Endpoints for operations that allow you to retrieve detailed information about individual Events, list all Events or specific Event…
- [M3ter ExportAdHoc API](https://apis.io/apis/m3ter/m3ter-exportadhoc-api/) — Endpoints for triggering one-off, ad-hoc Data Exports. You can set up and run ad-hoc Exports to export two kinds of data from your m3ter Organization: *…
- [M3ter ExportDestination API](https://apis.io/apis/m3ter/m3ter-exportdestination-api/) — Endpoints for creating, updating, retrieving, or deleting Data Export Destinations. Before you can configure and run either [Export…
- [M3ter ExportSchedule API](https://apis.io/apis/m3ter/m3ter-exportschedule-api/) — Endpoints for creating, updating, retrieving, or deleting Data Export schedules. You can set up an Export Schedule to export one of two types of data from…
- [M3ter External Mapping API](https://apis.io/apis/m3ter/m3ter-external-mapping-api/) — Endpoints for managing External Mapping related operations such as creation, update, list and delete. When you integrate your 3rd-party systems with the…
- [M3ter Integrations API](https://apis.io/apis/m3ter/m3ter-integrations-api/) — A suite of endpoints for configuring and managing third party integrations within the m3ter platform. The integration endpoints in this section facilitate…
- [M3ter Invitations API](https://apis.io/apis/m3ter/m3ter-invitations-api/) — Endpoints for creating and retrieving user invitations. Use invitations to invite other people to join your m3ter Organization. An invitation sends an email…
- [M3ter Line Item API](https://apis.io/apis/m3ter/m3ter-line-item-api/) — Endpoint for retrieving a list of line items for Bills in an Organization.
- [M3ter LookupTableRevision API](https://apis.io/apis/m3ter/m3ter-lookuptablerevision-api/) — Endpoints for creating/updating/deleting Lookup Table Revisions. Lookup Tables utilize a "Table and Revision" model, which lets you update data cleanly, and…
- [M3ter LookupTableRevisionData API](https://apis.io/apis/m3ter/m3ter-lookuptablerevisiondata-api/) — Endpoints for creating/updating/deleting Data for specific Lookup Table Revisions. When you've added fields to create a data schema for a Lookup Table…
- [M3ter Marketplace Integrations API](https://apis.io/apis/m3ter/m3ter-marketplace-integrations-api/) — Endpoints for retrieving reporting data on Marketplace Integration runs
- [M3ter Measurements API](https://apis.io/apis/m3ter/m3ter-measurements-api/) — Endpoints for submitting usage data measurements to the m3ter platform: - **Directly:** You can use the **Submit Measurements** call to submit raw data…
- [M3ter Meter API](https://apis.io/apis/m3ter/m3ter-meter-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Meters. Use Meters to submit usage data for the consumption of your products and services…
- [M3ter Notifications API](https://apis.io/apis/m3ter/m3ter-notifications-api/) — This section provides endpoints for managing Event Notifications. You can create Notifications based on system Events generated by the platform. When you…
- [M3ter OrganizationConfig API](https://apis.io/apis/m3ter/m3ter-organizationconfig-api/) — Endpoints for retrieving or updating the Organization Config. Organization represents your company as a direct customer of m3ter. Use Organization…
- [M3ter OrgUsers API](https://apis.io/apis/m3ter/m3ter-orgusers-api/) — This section contains the endpoints for managing users within an Organization *(OrgUsers)*. These endpoints allow you to retrieve, update, and analyze user…
- [M3ter PermissionPolicy API](https://apis.io/apis/m3ter/m3ter-permissionpolicy-api/) — Endpoints for Permission Policy related operations such as creation, update, add and retrieve. Permission Policies can restrict or grant access to specific…
- [M3ter Plan API](https://apis.io/apis/m3ter/m3ter-plan-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Plans. A Plan is based on a PlanTemplate and represents a specific pricing plan for one…
- [M3ter PlanGroup API](https://apis.io/apis/m3ter/m3ter-plangroup-api/) — Endpoints for PlanGroup related operations such as creation, update, retrieve, list and delete. PlanGroups are constructs that group multiple plans…
- [M3ter PlanGroupLink API](https://apis.io/apis/m3ter/m3ter-plangrouplink-api/) — Endpoints for PlanGroupLink related operations such as creation, update, list and delete. PlanGroupLinks are the intersection table between a PlanGroup and…
- [M3ter PlanTemplate API](https://apis.io/apis/m3ter/m3ter-plantemplate-api/) — Endpoints for listing, creating, updating, retrieving, or deleting PlanTemplates. Use PlanTemplates to define default values for Plans. These default values…
- [M3ter Pricing API](https://apis.io/apis/m3ter/m3ter-pricing-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Pricing. Create the Pricing for a Plan/PlanTemplate with usage data Aggregations, and…
- [M3ter Product API](https://apis.io/apis/m3ter/m3ter-product-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Products. A Product represents the products and services you offer to your end customers.…
- [M3ter ResourceGroup API](https://apis.io/apis/m3ter/m3ter-resourcegroup-api/) — Endpoints for ResourceGroup related operations such as creation, update, list and delete. ResourceGroups are used in the context of Permission Policies,…
- [M3ter ScheduledEventConfigurations API](https://apis.io/apis/m3ter/m3ter-scheduledeventconfigurations-api/) — Endpoints for retrieving and managing scheduled Events' configurations. Scheduled Event Configurations define custom Event types that reference Date/Time…
- [M3ter StatementDefinition API](https://apis.io/apis/m3ter/m3ter-statementdefinition-api/) — Endpoints for listing, creating, updating, retrieving, or deleting Statement Definitions. Bill statements are informative backing sheets to invoices. They…
- [M3ter StatementJob API](https://apis.io/apis/m3ter/m3ter-statementjob-api/) — Endpoints for creating, retrieving, listing, and cancelling statement jobs. StatementJobs are tasks to asynchronously calculate and generate a bill…
- [M3ter Support API](https://apis.io/apis/m3ter/m3ter-support-api/) — Endpoints for requesting support and managing m3ter Support users. For troubleshooting purposes, you can grant m3ter Support access to your Organization.…
- [M3ter TransactionType API](https://apis.io/apis/m3ter/m3ter-transactiontype-api/) — Endpoints for TransactionType operations such as creation, update, list, retrieve, and delete. You can create TransactionTypes for your Organization, which…
- [M3ter User API](https://apis.io/apis/m3ter/m3ter-user-api/) — Endpoints for creating/updating Users
- [M3ter Custom Field API](https://apis.io/apis/m3ter/m3ter-custom-field-api/) — Endpoints for retrieving and updating Custom Fields at the Organization level for all entities that support them.
- [M3ter Data Explorer API](https://apis.io/apis/m3ter/m3ter-data-explorer-api/) — Endpoints for querying the Data Explorer and saving query selections.
- [M3ter Export Job API](https://apis.io/apis/m3ter/m3ter-export-job-api/) — Endpoints for retrieving/querying Data Export jobs.
- [M3ter Lookup Table API](https://apis.io/apis/m3ter/m3ter-lookup-table-api/) — Endpoints for creating/updating/deleting Lookup Tables.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [M3Ter Agentic Access](https://apis.io/agentic-access/m3ter/m3ter-agentic-access/)

#### Collections (59)

Postman and Open Collection request collections.

- [m3ter API](https://apis.io/collections/m3ter/open-m3ter/)
- [m3ter Account API](https://apis.io/collections/m3ter/open-m3ter-account-api/)
- [m3ter Account AccountPlan API](https://apis.io/collections/m3ter/open-m3ter-accountplan-api/)
- [m3ter Account Aggregation API](https://apis.io/collections/m3ter/open-m3ter-aggregation-api/)
- [m3ter Account Auth API](https://apis.io/collections/m3ter/open-m3ter-auth-api/)
- [m3ter Account BalanceChargeSchedule API](https://apis.io/collections/m3ter/open-m3ter-balancechargeschedule-api/)
- [m3ter Account Balances API](https://apis.io/collections/m3ter/open-m3ter-balances-api/)
- [m3ter Account BalanceTransactionSchedule API](https://apis.io/collections/m3ter/open-m3ter-balancetransactionschedule-api/)
- [m3ter Account Bill API](https://apis.io/collections/m3ter/open-m3ter-bill-api/)
- [m3ter Account BillConfig API](https://apis.io/collections/m3ter/open-m3ter-billconfig-api/)
- [m3ter Account BillGroupingKey API](https://apis.io/collections/m3ter/open-m3ter-billgroupingkey-api/)
- [m3ter Account BillJob API](https://apis.io/collections/m3ter/open-m3ter-billjob-api/)
- [m3ter Account Charge API](https://apis.io/collections/m3ter/open-m3ter-charge-api/)
- [m3ter Account Commitments API](https://apis.io/collections/m3ter/open-m3ter-commitments-api/)
- [m3ter Account CompoundAggregation API](https://apis.io/collections/m3ter/open-m3ter-compoundaggregation-api/)
- [m3ter Account Contract API](https://apis.io/collections/m3ter/open-m3ter-contract-api/)
- [m3ter Account Counter API](https://apis.io/collections/m3ter/open-m3ter-counter-api/)
- [m3ter Account CounterAdjustments API](https://apis.io/collections/m3ter/open-m3ter-counteradjustments-api/)
- [m3ter Account CounterPricing API](https://apis.io/collections/m3ter/open-m3ter-counterpricing-api/)
- [m3ter Account CreditReason API](https://apis.io/collections/m3ter/open-m3ter-creditreason-api/)
- [m3ter Account Credits API](https://apis.io/collections/m3ter/open-m3ter-credits-api/)
- [m3ter Account Currency API](https://apis.io/collections/m3ter/open-m3ter-currency-api/)
- [m3ter Account CustomField API](https://apis.io/collections/m3ter/open-m3ter-customfield-api/)
- [m3ter Account DataExplorer API](https://apis.io/collections/m3ter/open-m3ter-dataexplorer-api/)
- [m3ter Account DataExplorerV2 API](https://apis.io/collections/m3ter/open-m3ter-dataexplorerv2-api/)
- …and 34 more published on APIs.io

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [M3Ter Authentication](https://apis.io/security/m3ter/m3ter-authentication/)
- [M3Ter Domain Security](https://apis.io/security/m3ter/m3ter-domain-security/)
- [M3Ter Trust Center](https://apis.io/security/m3ter/m3ter-trust-center/)
- [M3Ter Vulnerability Disclosure](https://apis.io/security/m3ter/m3ter-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [M3Ter Scopes](https://apis.io/scopes/m3ter/m3ter-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [M3Ter Plans Pricing](https://apis.io/plans/m3ter/m3ter-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [M3Ter Rate Limits](https://apis.io/rate-limits/m3ter/m3ter-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [M3Ter Finops](https://apis.io/finops/m3ter/m3ter-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.m3ter.com/)
- [Documentation](https://docs.m3ter.com/)
- [API reference](https://docs.m3ter.com/api)
- [Blog](https://www.m3ter.com/blog/feed/)

## API Evangelist rating

**Kin Score 44.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 49.3 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 59.5 |
| Access clarity | 15.8 |

**Agent readiness 28.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 32.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/m3ter/](https://apis.io/providers/m3ter/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for M3ter: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/m3ter/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
