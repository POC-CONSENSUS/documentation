## Repositories

| Component | Repo | Description |
| ----------- | ----------- | ----------- |
| Bakend | [Bakend](https://github.com/POC-CONSENSUS/backend) | Backend containing resteasy Quarkus services to expose crud entities with OpenAPI design. |
| Frontend | [Frontend](https://github.com/POC-CONSENSUS/frontend) | ReactJS GUI, it is a SPA. |
| Aggregator | [Aggregator](https://github.com/POC-CONSENSUS/aggregator) | Api composition middleware a Nginx Dockerfile to aggregate multiple endpoint into one. |
| PostgreSQL database |  | A database connected with the backend to store the assets. |
| 3Scale | [3Scale]([https://github.com/POC-CONSENSUS/aggregator](https://www.redhat.com/en/technologies/jboss-middleware/3scale)) | Api gateway middleware, used here to link aggregator endpoint to the frontend with a CORS policy. |
