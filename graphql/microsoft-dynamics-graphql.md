# Microsoft Dynamics 365 GraphQL Schema

## Overview

This conceptual GraphQL schema represents the Microsoft Dynamics 365 CRM and ERP platform, covering
the Dataverse Web API (OData v4) surface for Sales, Customer Service, Marketing, and related
engagement modules. The schema maps core Dynamics 365 entity sets to GraphQL types, enabling
familiar graph-based querying over the same data exposed through OData endpoints.

## Source APIs

- **Dataverse Web API**: `https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview`
- **Business Central API v2.0**: `https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/`
- **Finance & Operations OData**: `https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata`
- **Dynamics 365 Docs**: `https://docs.microsoft.com/en-us/dynamics365/`

## Schema File

See `microsoft-dynamics-schema.graphql` for the full type definitions.

## Type Coverage

The schema defines 72 named GraphQL types spanning:

| Domain | Types |
|---|---|
| CRM Core | Account, Contact, Lead, Opportunity, OpportunityProduct, Competitor |
| Sales | Quote, QuoteProduct, Order, OrderProduct, Invoice, InvoiceProduct |
| Organization | BusinessUnit, Territory, Team, SystemUser |
| Security | Role, SecurityRole, FieldPermission |
| Marketing | Campaign, CampaignActivity, CampaignResponse, List |
| Activities | Activity, Appointment, Email, Letter, Fax, PhoneCall, Task, RecurringAppointment |
| Service | ServiceActivity, Incident, IncidentResolution, Contract, ContractLine |
| Entitlements | Entitlement, EntitlementTemplate |
| Queues & SLA | Queue, QueueItem, SLA, SLAItem |
| Products & Pricing | Product, ProductPriceLevel, PriceLevel, UoM, UoMSchedule, Discount, DiscountType |
| Knowledge Base | KbArticle, KbArticleComment, KbArticleTemplate, Subject |
| Goals & Metrics | Goal, GoalRollupQuery, Metric, RollupField |
| Platform | Workflow, Action, Plugin, Organization, ConnectionRole |
| Reference | Currency, Language, ImportLog, Solution, Publisher, APIKey, Token |

## Authentication

All Dynamics 365 APIs authenticate via Microsoft Entra ID (formerly Azure AD) using OAuth 2.0
bearer tokens. A GraphQL gateway would require a valid access token scoped to the Dynamics 365
resource URI (e.g., `https://<org>.crm.dynamics.com`).

## Notes

- This is a conceptual schema derived from the OData v4 entity model of Dynamics 365 Dataverse.
- OData navigation properties are represented as GraphQL object and list fields.
- Entity primary keys use the `id` convention (mapping to OData `<entityname>id` GUIDs).
- Enum types represent OptionSet fields (picklists) from Dynamics 365 metadata.
