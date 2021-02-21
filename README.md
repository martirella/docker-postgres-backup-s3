# docker-backup-postgres-s3

Backup up your postgres database to S3 using docker.


## Envionment Variables

- `S3_ACCESS_KEY_ID`: AWS access key
- `S3_SECRET_ACCESS_KEY`: Your secret access key
- `S3_BUCKET`: S3 bucket
- `POSTGRES_HOST` - Hostname
- `POSTGRES_DATABASE`: Name of the database
- `POSTGRES_USER`: Postgres user
- `POSTGRES_PASSWORD` (optional): Password for the Postgres user
- `POSTGRES_PORT` (optional): Port (default: `5432`).
- `POSTGRES_EXTRA_OPTS` (optional): Extra arguments for `pg_dump`
- `S3_REGION` (optional): S3 region
- `AWS_EXTRA_OPTS` (optional): Extra arguments for the `aws` command
- `SCHEDULE` (optional): Cron schedule to run periodic backups

## Docker Compose example


## Acknowledgements

Based on [lucaspiller/docker-backup-postgres-s3](https://github.com/lucaspiller/docker-backup-postgres-s3).
