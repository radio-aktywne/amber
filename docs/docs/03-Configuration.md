---
slug: /config
title: Configuration
---

## Environment variables

You can configure the database at runtime using various environment variables:

- `AMBER__SERVER__HOST` -
  host on which the database will be listening
  (default: `0.0.0.0`)
- `AMBER__SERVER__PORTS__S3` -
  port on which the database will be listening
  (default: `29000`)
- `AMBER__SERVER__PORTS__WEB` -
  port on which the web interface will be available
  (default: `29001`)
- `AMBER__URLS__WEB` -
  public URL of the web interface
  (default: `http://localhost:29001`)
- `AMBER__CREDENTIALS__ADMIN__USER` -
  username for the admin user
  (default: `admin`)
- `AMBER__CREDENTIALS__ADMIN__PASSWORD` -
  password for the admin user
  (default: `password`)
- `AMBER__CREDENTIALS__READONLY__USER` -
  username for the readonly user
  (default: `readonly`)
- `AMBER__CREDENTIALS__READONLY__PASSWORD` -
  password for the readonly user
  (default: `password`)
- `AMBER__CREDENTIALS__READWRITE__USER` -
  username for the readwrite user
  (default: `readwrite`)
- `AMBER__CREDENTIALS__READWRITE__PASSWORD` -
  password for the readwrite user
  (default: `password`)
