---
title: db setup
label: Project Setup
---

Example schema (you will add the user table and user*id columns \_after* adding the auth schema later):

```mermaid
erDiagram
    user {
        integer id
        text name
        text email
        integer email_verified
        integer created_at
        integer updated_at
    }
    location {
        integer id
        text name
        text slug
        text description
        real latitude
        real longitude
        integer user_id
        integer created_at
        integer updated_at
    }
    location_log {
        integer id
        text name
        text description
        integer started_at
        integer ended_at
        real latitude
        real longitude
        integer location_id
        integer user_id
        integer created_at
        integer updated_at
    }
    location_log_image {
        integer id
        text key
        integer location_log_id
        integer user_id
        integer created_at
        integer updated_at
    }

    location }o--|| user : "user_id"
    location_log }o--|| location : "location_id"
    location_log }o--|| user : "user_id"
    location_log_image }o--|| location_log : "location_log_id"
    location_log_image }o--|| user : "user_id"
```

- [ ] Database schema is defined
- [ ] Migration system is configured
- [ ] Database is created / migrated locally (not in the cloud)
- [ ] Database connection is properly configured
- [ ] Environment variables are documented
