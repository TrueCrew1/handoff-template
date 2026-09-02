# Repository AI Context — True Crew Handoff Template

Status: repository-local AI context. Engineer-standard remains the cross-repository engineering authority.

## Repository identity

- Repository: `TrueCrew1/handoff-template`
- Product/role: Reference/template artifact, not an operating product.
- Lifecycle: reference
- Canonical True Crew agent runtime: Node `24.19.0`

## Ownership

**Owns:** Only the retained handoff-template/reference files.

**Does not own:** Production workflow state, customer data, product runtime, or company operating-system authority.

## Data/runtime boundary

No database authority.

## Deployment boundary

Reference-only by default. Do not deploy or expand without explicit reclassification.

## AI execution contract

1. Run `node scripts/ai-preflight.mjs` from the intended isolated worktree before material mutation.
2. Treat `BLOCKED` as a stop condition. Never reset/stash/clean/rebase/discard unexpected state to make the preflight pass.
3. When a packet supplies branch/base expectations, set `TRUECREW_EXPECTED_BRANCH`, `TRUECREW_EXPECTED_HEAD`, and `TRUECREW_TASK_PACKET`.
4. `--allow-dirty` and `--allow-production-branch` are read-only/recovery snapshot controls only.
5. Reference/experimental lifecycle is a real constraint: do not expand a reference or experiment into a product/runtime without explicit portfolio reclassification.
6. Baseline validation: Minimal artifact integrity review only unless explicitly reclassified.

## Durable documents to load when applicable

- No additional repository-local governance document is currently canonical beyond `AGENTS.md` and this context.

## Cross-system rule

Provider and customer-product records remain owned by their source systems. Reference code never gains True Crew production authority merely because it is stored in a True Crew repository.
