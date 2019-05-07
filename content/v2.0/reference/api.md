---
title: InfluxDB v2 API
description: >
  The InfluxDB v2 API provides a programmatic interface for interactions with InfluxDB.
  Access the InfluxDB API using the `/api/v2/` endpoint.
menu: v2_0_ref
weight: 2
v2.0/tags: [api]
---

The InfluxDB v2 API provides a programmatic interface for interactions with InfluxDB.
Access the InfluxDB API using the `/api/v2/` endpoint.

## Authentication
InfluxDB uses [authentication tokens](/v2.0/security/tokens/) to authorize API requests.
Include your authentication token as an `Authorization` header in each request.

```sh
curl --request GET \
  --url http://localhost:9999/api/v2/ \
  --header 'Authorization: Token YOURAUTHTOKEN'
```

## View Influx v2 API Documentation
Full InfluxDB v2 API documentation is built into the `influxd` service.
To view the API documentation, [start InfluxDB](/v2.0/get-started/#start-influxdb)
and visit the `/docs` endpoint in a browser.

<a class="btn" href="http://localhost:9999/docs" target="\_blank">localhost:9999/docs</a>