# Eligibility Criteria Database

These csv data files contains example eligibility criteria for clinical trials.

## Data loading instructions

1. git clone the contents of this repo.
2. The format of each data file is as follows:

   - header record
   - UTF8 character set
   - Comma field separator
   - CSV

## Docker

### Configuration

To change the postgres user credentials, change ```POSTGRES_USER``` and ```POSTGRES_PASSWORD``` in ```Dockerfile```

### Run container

```bash
docker-compose up
```