# Microsoft Dynamics (microsoft-dynamics)
Microsoft Dynamics 365 is a suite of enterprise resource planning (ERP) and customer relationship management (CRM) applications. It provides APIs across three main platforms: Business Central for small and mid-sized business ERP, Dataverse Web API for CRM and customer engagement, and Finance & Operations for enterprise-grade ERP covering finance, supply chain, manufacturing, and human resources. All APIs use OData v4 conventions and authenticate via Microsoft Entra ID.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - ERP, CRM, Microsoft Dynamics

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-16 

## APIs

### Microsoft Dynamics 365 Business Central API
The Microsoft Dynamics 365 Business Central API (v2.0) provides a RESTful OData v4 interface for integrating with Business Central. It exposes standard business entities including companies, customers, vendors, items, sales orders, sales invoices, purchase orders, purchase invoices, journals, general ledger entries, accounts, and employees. The API supports both cloud (SaaS) and on-premises deployments, authenticated via Microsoft Entra ID.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)


#### Tags:

 - ERP, Finance, Business Central

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- [OpenAPI](openapi/microsoft-dynamics-business-central-openapi.yml)
- [JSONSchema](json-schema/customer.json)
- [JSONSchema](json-schema/vendor.json)
- [JSONSchema](json-schema/item.json)
- [JSONSchema](json-schema/sales-order.json)
- [JSONSchema](json-schema/sales-invoice.json)
- [JSONSchema](json-schema/employee.json)
- [JSONLD](json-ld/microsoft-dynamics-context.jsonld)

### Microsoft Dynamics 365 Dataverse Web API
The Microsoft Dynamics 365 Dataverse Web API provides a RESTful OData v4 endpoint for Dynamics 365 Sales, Customer Service, Field Service, and other customer engagement applications. It supports CRUD operations on core CRM entities such as accounts, contacts, leads, opportunities, cases (incidents), and activities. Authentication is handled via Microsoft Entra ID (Azure AD).

**Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)


#### Tags:

 - CRM, Sales, Customer Engagement

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- [OpenAPI](openapi/microsoft-dynamics-dataverse-openapi.yml)
- [JSONSchema](json-schema/account.json)
- [JSONSchema](json-schema/contact.json)
- [JSONSchema](json-schema/lead.json)
- [JSONSchema](json-schema/opportunity.json)
- [JSONLD](json-ld/microsoft-dynamics-context.jsonld)

### Microsoft Dynamics 365 Finance & Operations Data API
The Microsoft Dynamics 365 Finance & Operations Data API exposes business data entities via OData v4 RESTful endpoints. It provides access to finance, supply chain, manufacturing, and human resources data including customers, vendors, released products, sales order headers, purchase order headers, general journal entries, and workers. The API supports cross- company queries and is authenticated via Microsoft Entra ID.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata)


#### Tags:

 - ERP, Finance, Supply Chain

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata)
- [OpenAPI](openapi/microsoft-dynamics-finance-operations-openapi.yml)
- [JSONLD](json-ld/microsoft-dynamics-context.jsonld)

## Common Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/)
- [Support](https://community.dynamics.com/)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/get-started/)
- [Blog](https://cloudblogs.microsoft.com/dynamics365/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
