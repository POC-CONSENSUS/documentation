# Consensus naming helper documentation

> [!IMPORTANT]
> This is a WIP need contributors to help me automate and continue the project. 

## Purpose

Generate naming for your videos with the right convention syntax. 
The convention syntax is to use with Consensus in presales activities (https://goconsensus.com/).

## Design

![image](https://github.com/POC-CONSENSUS/documentation/assets/10670618/c947001e-cc8e-4f2d-98c2-42aa4f494b73)

## Repositories

| Component | Repo | Description |
| ----------- | ----------- | ----------- |
| Bakend | [Bakend](https://github.com/POC-CONSENSUS/backend) | Backend containing resteasy Quarkus services to expose crud entities with OpenAPI design. |
| Frontend | [Frontend](https://github.com/POC-CONSENSUS/frontend) | ReactJS GUI, it is a SPA. |
| Aggregator | [Aggregator](https://github.com/POC-CONSENSUS/aggregator) | Api composition middleware a Nginx Dockerfile to aggregate multiple endpoint into one. |
| PostgreSQL database |  | A database connected with the backend to store the assets. |
| 3Scale | [3Scale]([https://github.com/POC-CONSENSUS/aggregator](https://www.redhat.com/en/technologies/jboss-middleware/3scale)) | Api gateway middleware, used here to link aggregator endpoint to the frontend with a CORS policy. |
