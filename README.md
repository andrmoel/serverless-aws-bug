# serverless-aws-bug

This project reproduces https://github.com/serverless/serverless/issues/11561

## Pre-requisites

- Use Node.js >=16.10.0
- Run `corepack enable` to use yarn version from package.json

## Setup

1. Setup AWS credentials in `~/.aws/credentials`
2. Run `yarn`
3. Run `yarn deploy`

The following error occurs:

```bash
Error:
Request is missing Authentication Token
error Command failed with exit code 1.
```
