# CI service - Postgres

This image is used to have custom configuration files useful for CI jobs, because we cannot mount volumes to Gitlab CI services.

## Additional configuration

1. Add a `replication` entry to default `pg_hba.conf` to autorize replication from `all` sources.
