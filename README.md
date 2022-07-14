# pnpm deploy issue

When running pnpm deploy dev dependencies aren't included.

## Reproduction steps

1. Clone the repo
2. `pnpm deploy --filter=example out` 
3. `cd example` 
4. `pnpm build`  
