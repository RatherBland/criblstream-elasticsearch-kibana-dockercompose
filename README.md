Docker Compose configuration to spin up Cribl Stream with Elasticsearch and Kibana for testing.

The directory `cribl-config` is required at the root of the project

Run the following
```bash
docker-compose up -d --scale cribl-workers=1
```