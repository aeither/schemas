# schemas
This directory is used to generate the init, query, and execute interfaces for contracts available in Abstract.

## Adding your module
1. Publish your contract to the Abstract Version Control (see example deployment script [here](https://github.com/Abstract-OS/app-template/blob/mainline/scripts/src/bin/deploy_app.rs))
2. Make a PR to this repository with the module schema in `<your-namespace>/<module-name>/<version>`
3. Ensure that the validate-metadatas action does not fail.

## Commands
- `pnpm validate-metadatas` - validate all metadatas in this repo
