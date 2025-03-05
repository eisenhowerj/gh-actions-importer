# Screwdriver Platform Configuration

This document provides details on how to configure the Screwdriver platform for use with the GitHub Actions Importer tool.

## Configuration

To configure the Screwdriver platform, follow the steps below:

1. Obtain a personal access token for Screwdriver.
2. Set the necessary environment variables:
   - `SCREWDRIVER_ACCESS_TOKEN`: Personal access token for Screwdriver.
   - `SCREWDRIVER_INSTANCE_URL`: Base URL of the Screwdriver instance (default: `https://api.screwdriver.cd`).
   - `SCREWDRIVER_ORGANIZATION`: Screwdriver organization name.
   - `SCREWDRIVER_PIPELINE_ID`: Screwdriver pipeline ID.

## Example

Here is an example of how to set the environment variables for Screwdriver:

```sh
export SCREWDRIVER_ACCESS_TOKEN=<your-screwdriver-access-token>
export SCREWDRIVER_INSTANCE_URL=https://api.screwdriver.cd
export SCREWDRIVER_ORGANIZATION=<your-screwdriver-organization>
export SCREWDRIVER_PIPELINE_ID=<your-screwdriver-pipeline-id>
```

## Documentation

For more details on Screwdriver platform configuration, refer to the official documentation: [Screwdriver Configuration](https://docs.screwdriver.cd/user-guide/configuration/).
