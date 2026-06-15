# Microsoft Dynamics (microsoft-dynamics)

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
