Weekly digests about what is happening in OSS around ROCm / model serving.

## Digests

Curated PRs and issues, grouped by repo, with impact and portability notes.

- [2026-10-30 → 2026-11-06](digests/2026-11-06_digest.md)
- [2026-11-06 → 2026-11-13](digests/2026-11-13_digest.md)

## Full indexes

Every cached item for the period, unfiltered and unranked — the appendix behind each digest.

- [2026-10-30 → 2026-11-06](digests/2026-11-06_full_index.md)
- [2026-11-06 → 2026-11-13](digests/2026-11-13_full_index.md)

## How are digests built?

1. **Collect** every PR and issue opened or closed in the window from `ROCm/aiter`, `vllm-project/vllm`, `sgl-project/sglang`, `sgl-project/sgl-amd-mono`, `ROCm/ATOM`, `ROCm/rocm-systems` (runtime/collectives/profilers) and `lightseekorg/tokenspeed`.
2. **Explore** in batches — items are read with their descriptions and discussion, then ranked against three lenses: ROCm (gfx942/gfx950), quantization, and other accelerators (NVIDIA, gfx1250, XPU).
3. **Verify** the claims worth repeating against the actual code and review threads, rather than trusting PR titles.
4. **Write** two files: the curated digest, and the full index of everything collected. The index is what makes "nothing important was missed" checkable, so the two are reconciled — high-impact items left out of the digest are accounted for, and every quantization item is either written up or cited.

Periods are weeks ending on a Friday, named by their end date and overlapping by a day with the previous run.
