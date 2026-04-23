## File includes:

- Localstack SQS

## Prerequisites

Requires Docker to be installed on local machine.

## Installation

Create an `.env` file based on `.env.example`.

Environment variables:

```bash
LOCALSTACK_AUTH_TOKEN=change-me-to-your-localstack-auth-token
AWS_DEFAULT_REGION=us-east-1
AWS_ACCESS_KEY_ID=test
AWS_SECRET_ACCESS_KEY=test
```

Then run:

```bash
$ docker compose up
```

## Description

This repository contains local infrastructure for SQS emulation through LocalStack.
