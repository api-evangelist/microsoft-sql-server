# Microsoft SQL Server (microsoft-sql-server)

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

A relational database management system developed by Microsoft for enterprise-scale data management and business intelligence solutions.

**APIs.json:** [https://www.microsoft.com/sql-server](https://www.microsoft.com/sql-server)

## Tags

- Cloud
- Data Management
- Database
- Enterprise
- Relational Database
- SQL

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### SQL Server Database Engine API

Core database engine APIs for querying, managing, and administering SQL Server databases.

- **Human URL:** [https://docs.microsoft.com/sql/sql-server/](https://docs.microsoft.com/sql/sql-server/)
- **Base URL:** `https://your-server.database.windows.net`

#### Tags

- Database
- Query
- Transact-SQL

#### Properties

- [Documentation](https://docs.microsoft.com/sql/sql-server/sql-server-technical-documentation)
- [OpenAPI](https://docs.microsoft.com/sql/connect/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/sql/relational-databases/security/authentication-access/)
- [Getting Started](https://learn.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SQL Server Management Objects (SMO) API

.NET API for managing and administering SQL Server programmatically.

- **Human URL:** [https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/](https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/)
- **Base URL:** `https://api.example.com/smo`

#### Tags

- .NET
- Administration
- Management

#### Properties

- [Documentation](https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/overview-smo)
- [SDK](https://www.nuget.org/packages/Microsoft.SqlServer.SqlManagementObjects)
- [Code  Samples](https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/create-program/)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure SQL Database REST API

REST API for managing Azure SQL Database resources and configurations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/sql/](https://learn.microsoft.com/en-us/rest/api/sql/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Azure
- Cloud
- Database Management
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/sql/)
- [OpenAPI](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/azure/active-directory/develop/)
- [Pricing](https://azure.microsoft.com/pricing/details/sql-database/)
- [Getting Started](https://learn.microsoft.com/en-us/rest/api/sql/rest-api-sql-create-or-update-database)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SQL Server Reporting Services (SSRS) API

REST API for managing reports, subscriptions, and data sources in SQL Server Reporting Services.

- **Human URL:** [https://docs.microsoft.com/sql/reporting-services/](https://docs.microsoft.com/sql/reporting-services/)
- **Base URL:** `https://your-server/reports/api/v2.0`

#### Tags

- Business Intelligence
- Reporting
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/reporting-services/developer/rest-api)
- [OpenAPI](https://app.swaggerhub.com/apis/microsoft-rs/SSRS/2.0) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Tutorial](https://docs.microsoft.com/sql/reporting-services/tutorial-access-rest-api)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/sql-server-reporting/)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SQL Server Integration Services (SSIS) Catalog API

API for managing SSIS packages, projects, and execution in the SSIS Catalog.

- **Human URL:** [https://docs.microsoft.com/sql/integration-services/](https://docs.microsoft.com/sql/integration-services/)
- **Base URL:** `https://your-server/SSISDB`

#### Tags

- Data Pipeline
- ETL
- Integration

#### Properties

- [Documentation](https://docs.microsoft.com/sql/integration-services/service/package-management-ssis-service)
- [Stored  Procedures](https://docs.microsoft.com/sql/integration-services/system-stored-procedures/)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure SQL Managed Instance REST API

REST API for creating, configuring, and managing Azure SQL Managed Instances including databases, operations, and scheduling.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance](https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance)
- **Base URL:** `https://management.azure.com`

#### Tags

- Azure
- Cloud
- Database Management
- Managed Instance
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/sql/managed-instances)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/instance-create-quickstart)
- [Pricing](https://azure.microsoft.com/pricing/details/azure-sql-managed-instance/)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Data API Builder

Open source configuration-based engine that creates REST and GraphQL APIs for SQL Server, Azure SQL, Azure Cosmos DB, PostgreSQL, and MySQL databases.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/data-api-builder/overview](https://learn.microsoft.com/en-us/azure/data-api-builder/overview)
- **Base URL:** `https://localhost:5000/api`

#### Tags

- CRUD
- Data Access
- GraphQL
- Open Source
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/data-api-builder/)
- [Source Code](https://github.com/Azure/data-api-builder)
- [Getting Started](https://learn.microsoft.com/en-us/azure/data-api-builder/overview)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Analysis Services REST API

REST API for managing Azure Analysis Services resources and performing asynchronous data refreshes of tabular models.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/analysisservices/](https://learn.microsoft.com/en-us/rest/api/analysisservices/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Analysis Services
- Azure
- Business Intelligence
- REST API
- Tabular Models

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/analysisservices/)
- [Client Libraries](https://learn.microsoft.com/en-us/analysis-services/client-libraries)
- [T M S L Reference](https://learn.microsoft.com/en-us/analysis-services/tmsl/tabular-model-scripting-language-tmsl-reference)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft SqlClient Data Provider (ADO.NET)

ADO.NET data provider for .NET Framework and .NET Core used for connecting to SQL Server, executing commands, and retrieving results.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/ado-net/overview-sqlclient-driver](https://learn.microsoft.com/en-us/sql/connect/ado-net/overview-sqlclient-driver)

#### Tags

- .NET
- ADO.NET
- Data Provider
- SqlClient

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/ado-net/overview-sqlclient-driver)
- [API Reference](https://learn.microsoft.com/en-us/dotnet/api/microsoft.data.sqlclient)
- [SDK](https://www.nuget.org/packages/Microsoft.Data.SqlClient)
- [Download](https://learn.microsoft.com/en-us/sql/connect/ado-net/download-microsoft-sqlclient-data-provider)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft JDBC Driver for SQL Server

Type 4 JDBC driver providing database connectivity to SQL Server through standard JDBC application program interfaces on the Java platform.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server](https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server)

#### Tags

- Cross-Platform
- Driver
- Java
- JDBC

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server)
- [API Reference](https://learn.microsoft.com/en-us/sql/connect/jdbc/reference/jdbc-driver-api-reference)
- [Download](https://learn.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server)
- [Source Code](https://github.com/microsoft/mssql-jdbc)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft ODBC Driver for SQL Server

ODBC driver providing native-code API connectivity to SQL Server and Azure SQL Database for applications on Windows, Linux, and macOS.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server](https://learn.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server)

#### Tags

- Cross-Platform
- Driver
- Native Code
- ODBC

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server)
- [Download](https://learn.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft OLE DB Driver for SQL Server

Stand-alone OLE DB data access API for low-level COM components requiring high-performance access to SQL Server.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server](https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server)

#### Tags

- COM
- Driver
- OLE DB
- Windows

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server)
- [Programming Guide](https://learn.microsoft.com/en-us/sql/connect/oledb/ole-db/oledb-driver-for-sql-server-programming)
- [Download](https://learn.microsoft.com/en-us/sql/connect/oledb/download-oledb-driver-for-sql-server)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Python Driver for SQL Server (mssql-python)

Python driver using Direct Database Connectivity for direct connections to SQL Server without requiring an external driver manager, compliant with Python DB-API 2.0.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python](https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python)

#### Tags

- Cross-Platform
- DB-API
- Driver
- Python

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python)
- [Getting Started](https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python-quickstart)
- [Source Code](https://github.com/microsoft/mssql-python)
- [SDK](https://pypi.org/project/mssql-python/)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Node.js Driver for SQL Server (tedious)

Open-source JavaScript implementation of the TDS protocol for connecting to SQL Server from Node.js on Windows, Linux, or macOS.

- **Human URL:** [https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server](https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server)

#### Tags

- Cross-Platform
- Driver
- JavaScript
- Node.js
- TDS

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server)
- [Source Code](https://github.com/tediousjs/tedious)
- [SDK](https://www.npmjs.com/package/mssql)
- [Postman Collection](collections/microsoft-sql-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sql-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/msft-sql-server)
- [Getting Started](https://docs.microsoft.com/sql/sql-server/sql-server-get-started)
- [Downloads](https://www.microsoft.com/sql-server/sql-server-downloads)
- [Pricing](https://www.microsoft.com/sql-server/sql-server-2022-pricing)
- [Support](https://support.microsoft.com/sql)
- [Blog](https://cloudblogs.microsoft.com/sqlserver/)
- [Community](https://techcommunity.microsoft.com/t5/sql-server/ct-p/SQLServer)
- [Training](https://docs.microsoft.com/learn/sql-server/)
- [Release Notes](https://docs.microsoft.com/sql/sql-server/sql-server-version-information)
- [Driver  History](https://learn.microsoft.com/en-us/sql/connect/connect-history)
- [GitHub Organization](https://github.com/microsoft/sql-server-samples)
- [Changelog](https://learn.microsoft.com/en-us/sql/sql-server/what-s-new-in-sql-server-2025)
- [Forum](https://learn.microsoft.com/en-us/answers/tags/191/sql-server)
- [Feedback](https://feedback.azure.com/d365community/forum/04fe6ee0-3b25-ec11-b6e6-000d3a4f0da0)
- [Videos](https://learn.microsoft.com/en-us/shows/data-exposed/)
- [Integrations](https://www.microsoft.com/en-us/marketplace)
- [M C P Server](https://github.com/microsoft/clarity-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
