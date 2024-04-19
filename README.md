# Metabase on a sub-path in local dev

This repo is a setup for testing Metabase deployed on a subpath e.g. when you visit metabase at https://example.com/metabase rather than https://metabase.example.com

## How to run
```sh
docker compose up
```

This assumes you run your local Metabase instance at localhost:3000 and the metabase will be deployed at http://localhost:4000/metabase/
