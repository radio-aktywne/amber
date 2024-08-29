---
slug: /config
title: Configuration
---

## Environment variables

You can configure the database at runtime using various environment variables:

- `MEDIALOUNGE__SERVER__HOST` -
  host on which the database will be listening
  (default: `0.0.0.0`)
- `MEDIALOUNGE__SERVER__PORTS__S3` -
  port on which the database will be listening
  (default: `29000`)
- `MEDIALOUNGE__SERVER__PORTS__WEB` -
  port on which the web interface will be available
  (default: `29001`)
- `MEDIALOUNGE__URLS__WEB` -
  public URL of the web interface
  (default: `http://localhost:29001`)
- `MEDIALOUNGE__CREDENTIALS__ADMIN__USER` -
  username for the admin user
  (default: `admin`)
- `MEDIALOUNGE__CREDENTIALS__ADMIN__PASSWORD` -
  password for the admin user
  (default: `password`)
- `MEDIALOUNGE__CREDENTIALS__READONLY__USER` -
  username for the readonly user
  (default: `readonly`)
- `MEDIALOUNGE__CREDENTIALS__READONLY__PASSWORD` -
  password for the readonly user
  (default: `password`)
- `MEDIALOUNGE__CREDENTIALS__READWRITE__USER` -
  username for the readwrite user
  (default: `readwrite`)
- `MEDIALOUNGE__CREDENTIALS__READWRITE__PASSWORD` -
  password for the readwrite user
  (default: `password`)
