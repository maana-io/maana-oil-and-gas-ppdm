# maana-ppdm

Create a [PPDM](https://ppdm.org/ppdm/PPDM/Standards/PPDM_Data_Model/PPDM_3_9_Data_Model/PPDM/PPDM_3.9_Data_Model.aspx?hkey=fed7573b-c57d-4909-b15a-a61880fb8d2b) GraphQL endpoint for us in Oil and Gas domain.

- Create a PostgreSQL database from: [https://github.com/rbhughes/pg_ppdm](https://github.com/rbhughes/pg_ppdm)
- Use [PostGraphile](https://www.graphile.org/) to generate a GraphQL endpoint

## Setup

### Azure Database for PostgreSQL

- [Quick Start](https://docs.microsoft.com/en-us/azure/postgresql/quickstart-create-server-database-portal)

### Install PostgreSQL Locally

During development, it is useful to have both a local copy of the database, but you'll also need the tools (e.g., psql) to work with Azure.

#### Ubuntu

- [Ubuntu 19.04](https://www.osradar.com/how-to-install-postgresql-on-ubuntu-19-04/)
