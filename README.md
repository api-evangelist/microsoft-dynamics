# Microsoft Dynamics (microsoft-dynamics)

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

Microsoft Dynamics 365 is a suite of enterprise resource planning (ERP) and customer relationship management (CRM) applications. It provides APIs across three main platforms: Business Central for small and mid-sized business ERP, Dataverse Web API for CRM and customer engagement, and Finance & Operations for enterprise-grade ERP covering finance, supply chain, manufacturing, and human resources. All APIs use OData v4 conventions and authenticate via Microsoft Entra ID.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CRM
- ERP
- Microsoft Dynamics

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-30

## APIs

### Microsoft Dynamics 365 Business Central API

The Microsoft Dynamics 365 Business Central API (v2.0) provides a RESTful OData v4 interface for integrating with Business Central. It exposes standard business entities including companies, customers, vendors, items, sales orders, sales invoices, purchase orders, purchase invoices, journals, general ledger entries, accounts, and employees. The API supports both cloud (SaaS) and on-premises deployments, authenticated via Microsoft Entra ID.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)

#### Tags

- Business Central
- ERP
- Finance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- [OpenAPI](openapi/microsoft-dynamics-business-central-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-dynamics-business-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-business-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/vendor.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/item.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sales-order.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sales-invoice.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/employee.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-dynamics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Microsoft Dynamics 365 Dataverse Web API

The Microsoft Dynamics 365 Dataverse Web API provides a RESTful OData v4 endpoint for Dynamics 365 Sales, Customer Service, Field Service, and other customer engagement applications. It supports CRUD operations on core CRM entities such as accounts, contacts, leads, opportunities, cases (incidents), and activities. Authentication is handled via Microsoft Entra ID (Azure AD).

- **Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)

#### Tags

- CRM
- Customer Engagement
- Sales

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- [OpenAPI](openapi/microsoft-dynamics-dataverse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-dynamics-dataverse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-dataverse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](openapi/microsoft-dynamics-dataverse-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Webhook Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/use-webhooks)
- [JSON Schema](json-schema/account.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/contact.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/lead.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/opportunity.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-dynamics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Microsoft Dynamics 365 Finance & Operations Data API

The Microsoft Dynamics 365 Finance & Operations Data API exposes business data entities via OData v4 RESTful endpoints. It provides access to finance, supply chain, manufacturing, and human resources data including customers, vendors, released products, sales order headers, purchase order headers, general journal entries, and workers. The API supports cross- company queries and is authenticated via Microsoft Entra ID.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata)

#### Tags

- ERP
- Finance
- Supply Chain

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata)
- [OpenAPI](openapi/microsoft-dynamics-finance-operations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-dynamics-finance-operations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-finance-operations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/microsoft-dynamics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [GitHub Organization](https://github.com/microsoft)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-dynamics)
- [Documentation](https://learn.microsoft.com/en-us/dynamics365/)
- [Support](https://community.dynamics.com/)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/get-started/)
- [Blog](https://cloudblogs.microsoft.com/dynamics365/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
