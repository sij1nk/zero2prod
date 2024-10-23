# zero2prod

<https://www.zero2prod.com>

## Setup instructions

- make sure the docker systemd service is running
- run `./scripts/init_db.sh` to launch the postgres container and to do the db migration

These steps are a prerequisite to running `cargo test`, and to get compile-time query verification for `sqlx`.
