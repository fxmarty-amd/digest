# Complete index — 2026-11-06 → 2026-11-13

Every cached item, unfiltered and unranked, for completeness. The curated digest is the separate file.

### aiter — Merged / closed (226 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#5186](https://github.com/ROCm/aiter/pull/5186) `[CK] [OPUS] [CI] Mi300a enablement` | infra | ? | - |
| P0 | [#5194](https://github.com/ROCm/aiter/pull/5194) `Cache the MLA split count, not the split indptr tensor` | perf | main | - |
| - | [#5500](https://github.com/ROCm/aiter/pull/5500) `[Config] configs: GLM-5.3-Flash a8w8 blockscale fused-MoE configs for gfx942` | perf,quant,rocm | main | - |
| - | [#5555](https://github.com/ROCm/aiter/pull/5555) `[FlyDSL] QuickAllReduce INT5/INT6 and all-reduce cleanup` | rocm | ? | - |
| - | [#5757](https://github.com/ROCm/aiter/pull/5757) `[ASM] [HIP] Qwe38 flash mxfp4 asm` | quant,rocm | ? | - |
| - | [#5793](https://github.com/ROCm/aiter/pull/5793) `[Triton/Gluon] [fix] Triton FA decode: bound K/V loads in non-paged split-K tail` | bug,rocm | ? | - |
| - | [#5794](https://github.com/ROCm/aiter/pull/5794) `[ASM] [HIP] feat(fmoe): add SwiGLU OAI MXFP4 FLAT kernels for Minimax M3 (gfx950)` | perf,quant,rocm | ? | - |
| - | [#5899](https://github.com/ROCm/aiter/pull/5899) `[FlyDSL] [gfx1250] MegaMoE: stage-1 fused kernel for DSV4.1 Flash EP2/EP4` | perf,rocm | ? | - |
| - | [#5985](https://github.com/ROCm/aiter/pull/5985) `[HIP] Opt group quant gfx1250` | infra,quant,rocm | ? | - |
| - | [#6091](https://github.com/ROCm/aiter/pull/6091) `[HIP] [MLA] Fix non-uniform query offsets after head folding` | bug,infra,rocm | ? | - |
| - | [#6238](https://github.com/ROCm/aiter/pull/6238) `[Triton/Gluon] [gfx1250] batched a16w8/a8w8/bf16: fp8 output + tuned MLA-absorb decode tiles` | perf,quant,rocm | ? | - |
| P1 | [#6484](https://github.com/ROCm/aiter/pull/6484) `[Feature][MoE] fused_moe: skip moe_sorting when the caller registers a BM=16 presort` | infra,perf | ? | - |
| P1 | [#6496](https://github.com/ROCm/aiter/pull/6496) `[FlyDSL] [gfx950] Add gdn fused prefill kernel` | perf,rocm | ? | - |
| - | [#6502](https://github.com/ROCm/aiter/pull/6502) `[Triton/Gluon] [CI] Streamline Flash Attentions api` | infra,rocm | ? | - |
| P1 | [#6575](https://github.com/ROCm/aiter/pull/6575) `[Triton/Gluon] [ASM] [HIP] MHAv4 per-row block-sparse geometry, LSE and ragged KV on gfx950` | rocm | ? | - |
| - | [#6682](https://github.com/ROCm/aiter/pull/6682) `[Triton/Gluon] : (QUANT, CE AND TRANS) Add RotatingBufferBench support` | perf,quant,rocm | ? | - |
| - | [#6684](https://github.com/ROCm/aiter/pull/6684) `[Triton/Gluon] : (DeepSeek) Add RotatingBufferBench support` | perf,rocm | ? | - |
| - | [#6689](https://github.com/ROCm/aiter/pull/6689) `feat(gemm_fusion): route sp_qkv_fused v1; keep a reference native, implementation moves to a provider` | perf | ? | - |
| P1 | [#6734](https://github.com/ROCm/aiter/pull/6734) `[HIP] Fuse a 32-point Hadamard rotation into the MXFP4 per-1x32 quant and AR + RMSNorm epilogue` | infra,perf,quant,rocm | ? | - |
| - | [#6779](https://github.com/ROCm/aiter/pull/6779) `[Triton/Gluon] fused_qkv_split_qk_norm_rope_cache: MRoPE, shuffle KV layout, optional outputs` | perf,rocm | ? | - |
| - | [#6784](https://github.com/ROCm/aiter/pull/6784) `[Triton/Gluon] gfx1250 pa decode update and tuning` | infra,perf,rocm | ? | - |
| - | [#6808](https://github.com/ROCm/aiter/pull/6808) `[HIP] Added an optional pre-quant k_out_unquantized under fp8 kv-cache to fused_qk_norm_rope_cache_pts_quant_s` | perf,quant,rocm | ? | - |
| - | [#6821](https://github.com/ROCm/aiter/pull/6821) `[HIP] [JIT] [Build] fused_norm_rope_att_rope_cast kernel` | infra,perf,rocm | ? | - |
| - | [#6835](https://github.com/ROCm/aiter/pull/6835) `[Triton/Gluon] Add fused Qwen3-Next attention prologue (gfx950)` | perf,rocm | ? | - |
| - | [#6839](https://github.com/ROCm/aiter/pull/6839) `[Triton/Gluon] : (UNIFIED ATTENTION) Add RotatingBufferBench support` | perf,rocm | ? | - |
| - | [#6842](https://github.com/ROCm/aiter/pull/6842) `[Triton/Gluon] Add sigmoid output gate to pa_decode_gluon` | infra,rocm | ? | - |
| P0 | [#6854](https://github.com/ROCm/aiter/pull/6854) `[Triton/Gluon] [Bugfix] Fix uneven split-K bug in fused a8w8 blockscale GEMMs` | bug,perf,quant,rocm | main | - |
| - | [#6895](https://github.com/ROCm/aiter/pull/6895) `[Feat] Add tuner event pid recovery and fix deadlock` | bug,perf,risk | ? | - |
| P0 | [#6926](https://github.com/ROCm/aiter/pull/6926) `[MoE] [Bugfix] Zero the a2 buffer before dynamic per-tensor quant` | quant | main | - |
| - | [#6941](https://github.com/ROCm/aiter/pull/6941) `[tuner] Reject zero timing measurements` | perf | ? | - |
| - | [#6951](https://github.com/ROCm/aiter/pull/6951) `[Triton/Gluon] Fix Triton A8W8 Per-token Preshuffled GEMM` | bug,infra,quant,rocm | ? | - |
| - | [#6952](https://github.com/ROCm/aiter/pull/6952) `[HIP] [OPUS] [JIT] MXFP4 MQA logits update: one API for V4 and V4.1 with Table/Free/Prefill schedules` | quant,rocm | ? | - |
| - | [#6958](https://github.com/ROCm/aiter/pull/6958) `[HIP] [JIT] [MSA] nvfp4 index key cache for the MSA indexer: decode and prefill scores` | perf,quant,rocm | ? | - |
| - | [#6960](https://github.com/ROCm/aiter/pull/6960) `[HIP] Add `all_gather_lastdim_add` to the custom all-reduce` | infra,rocm | ? | - |
| - | [#6972](https://github.com/ROCm/aiter/pull/6972) `[FlyDSL] [Kernel] Add a DCP mailbox query gather and LSE combine` | perf,rocm | ? | - |
| - | [#6981](https://github.com/ROCm/aiter/pull/6981) `[HIP] [MXFP4 MoE] cover Qwen3.5-397B TP4: shape gate entry and tuned rows` | perf,quant,rocm | ? | - |
| P1 | [#6990](https://github.com/ROCm/aiter/pull/6990) `[CK] [Bugfix] Align batch prefill full-attention dispatch` |  | ? | - |
| - | [#6995](https://github.com/ROCm/aiter/pull/6995) `[FlyDSL] [CI] [Feature] Add explicit clamped SiLU to FlyDSL a16w-mix GEMM1` | infra,rocm | ? | - |
| - | [#7008](https://github.com/ROCm/aiter/pull/7008) `[Triton/Gluon] [QSA] FP8 KV and FP8 / FP4 index caches, stacked-head decode scorer` | infra,quant,rocm | ? | - |
| P1 | [#7019](https://github.com/ROCm/aiter/pull/7019) `[HIP] [CK] [JIT] Enable swiglu_limit for FP8 per_1x128 blockscale MoE` | quant,rocm | ? | - |
| P1 | [#7022](https://github.com/ROCm/aiter/pull/7022) `[Triton/Gluon] fp8_mqa_logits: Do not recompile per batch size on gfx950` | rocm | ? | - |
| - | [#7040](https://github.com/ROCm/aiter/pull/7040) `[Triton/Gluon] : Add padding-mode support to specialized Triton Conv2D APIs` | rocm | ? | - |
| - | [#7043](https://github.com/ROCm/aiter/pull/7043) `[Config] Add M=4096 Qwen3.8-27B TP1 a8w8 blockscale GEMM rows for gfx942` | quant,rocm | ? | - |
| P0 | [#7047](https://github.com/ROCm/aiter/pull/7047) `[Triton/Gluon] Mask OOB e8m0 scales on the ragged-K path of batched_gemm_afp4wfp4` | quant,rocm | main | - |
| - | [#7072](https://github.com/ROCm/aiter/pull/7072) `[Triton/Gluon] [Config] Add gfx1150 fused_indexed_gated_residual config` | perf,rocm | ? | - |
| - | [#7080](https://github.com/ROCm/aiter/pull/7080) `[HIP] Speed up gfx1250 two-stage AR RMSNorm FP8 amax reduction` | perf,quant,rocm | ? | - |
| P0 | [#7092](https://github.com/ROCm/aiter/pull/7092) `[FlyDSL] pa_decode: zero V rows past the context before PV` | rocm | main | - |
| - | [#7098](https://github.com/ROCm/aiter/pull/7098) `[FlyDSL] [gfx1250] FMHA prefill m32x8: skip query tiles past a varlen sequence's end` | rocm | ? | - |
| P0 | [#7099](https://github.com/ROCm/aiter/issues/7099) `ROCm 10.1 (clang 24): 8-wave cktile blockscale GEMMs no longer inlined, 7-15x slower` | perf,quant,rocm | ? | - |
| - | [#7100](https://github.com/ROCm/aiter/pull/7100) `[Triton/Gluon] [GFX12] Add SPEC_DECODE mode to UA with tunned Qwen35 config` | rocm | ? | - |
| P0 | [#7103](https://github.com/ROCm/aiter/pull/7103) `[JIT] Add -mllvm -ignore-tti-inline-compatible=true for the 10.1 LLVM compiler to avoid some performance loss ` | perf,rocm | main | - |
| P1 | [#7104](https://github.com/ROCm/aiter/pull/7104) `[FlyDSL] moe_reduce: guard against -1 topk_ids padding sentinel` | rocm | ? | - |
| P0 | [#7126](https://github.com/ROCm/aiter/pull/7126) `[Triton/Gluon] [FlyDSL] [CI] [Bugfix] Never share scratch buffers whose zero fill was recorded into a graph` | infra,rocm | main | - |
| - | [#7128](https://github.com/ROCm/aiter/pull/7128) `[HIP] [FlyDSL] Add OPUS FP4 MQA writer and query scale layouts` | quant,rocm | ? | - |
| - | [#7133](https://github.com/ROCm/aiter/pull/7133) `[Triton/Gluon] [MLA] gfx1250: write the asm MLA decode KV layout from fused_qk_rope_cat_and_cache_mla` | infra,perf,rocm | ? | - |
| P0 | [#7134](https://github.com/ROCm/aiter/pull/7134) `[HIP] [Perf] Route gfx950 E=128..255 decode at M>=17 to multi-phase MoE sorting` | perf,rocm | main | - |
| P0 | [#7136](https://github.com/ROCm/aiter/pull/7136) `[CK] [CI] [Bugfix] Fix CK-Tile MXFP4 MoE stage1 split-k for unaligned or padded K` | bug,infra,quant | main | - |
| - | [#7138](https://github.com/ROCm/aiter/pull/7138) `[Config] Tune Kimi-K3 gfx1250 gemm_a4w4` | perf,quant,rocm | ? | - |
| - | [#7169](https://github.com/ROCm/aiter/pull/7169) `[Config] Add Kimi-K3 gfx950 BF16 GEMM rows that beat 3% on every repeat` | rocm | ? | - |
| - | [#7178](https://github.com/ROCm/aiter/pull/7178) `[FlyDSL] [gfx1250] flydsl batched mxfp8 GEMM: optional fused mxfp8 quant epilogue` | perf,quant,rocm | ? | - |
| P0 | [#7182](https://github.com/ROCm/aiter/pull/7182) `[Bugfix] MLA decode: merge only the splits gfx950 bf16 gqa32 stage 1 writes` | rocm | main | - |
| P1 | [#7192](https://github.com/ROCm/aiter/pull/7192) `[Triton/Gluon] [GFX950] Mha v4 production` | rocm | ? | - |
| P1 | [#7203](https://github.com/ROCm/aiter/pull/7203) `[Triton/Gluon] [Bugfix] gfx1250 unified attention 2D: store decode outputs from registers` | infra,rocm | ? | - |
| P1 | [#7204](https://github.com/ROCm/aiter/pull/7204) `[Config] [Tuning] Qwen3.8-Flash-Next TP4 prefill BF16 GEMMs on MI308X (gfx942, 80 CU)` | perf,rocm | ? | - |
| P1 | [#7215](https://github.com/ROCm/aiter/pull/7215) `[ASM] [HIP] feat(fmha_bwd): gfx950 sliding window attention backward kernels` | perf,rocm | ? | - |
| P1 | [#7218](https://github.com/ROCm/aiter/pull/7218) `[Config] Add tuned GEMM and fused-MoE configs for MI350P (gfx950, 128 CUs)` | perf,rocm | ? | - |
| P1 | [#7226](https://github.com/ROCm/aiter/pull/7226) `[Docs] FlyDSL review guidance: live-GPU test gates, test quality, Copilot checks, aiter FlyDSL notes` | rocm | ? | - |
| P1 | [#7227](https://github.com/ROCm/aiter/pull/7227) `review-pr: correct FlyDSL D10/D10b and add D13/D14 from review outcomes` | rocm | ? | - |
| P1 | [#7228](https://github.com/ROCm/aiter/pull/7228) `[Triton/Gluon] Fused a16w16 GEMM with a separate tile and split-K per output` | perf,rocm | ? | - |
| P1 | [#7232](https://github.com/ROCm/aiter/pull/7232) `[Triton/Gluon] [Feature] MHA: add out_dtype to the Triton forward entry point` | infra,rocm | ? | - |
| - | [#7234](https://github.com/ROCm/aiter/pull/7234) `[Config] [gfx1250] Tune DeepSeek-V4.1-Flash dense FP8 GEMM tiles for intermediate-M decode` | perf,quant,rocm | ? | - |
| P1 | [#7235](https://github.com/ROCm/aiter/pull/7235) `[Config] Mistral Large 4 gfx950 tuned tables (TP8 + TP4)` | perf,rocm | ? | - |
| P1 | [#7238](https://github.com/ROCm/aiter/pull/7238) `[FlyDSL] [AITER] FlyDSL a8w8 256x256 nb4/nb2 persistent kernel improvement` | perf,quant,rocm | ? | - |
| P1 | [#7239](https://github.com/ROCm/aiter/pull/7239) `[Triton/Gluon] Pipelining for fused GDN decode kernel, add ba partials reduction` | perf,rocm | ? | - |
| P1 | [#7254](https://github.com/ROCm/aiter/pull/7254) `[Config] Add MI350P (gfx950, 128 CU) a8w8 blockscale GEMM configs for Gemma-4-31B FP8-block` | quant,rocm | ? | - |
| P0 | [#7258](https://github.com/ROCm/aiter/pull/7258) `[FlyDSL] QuickAllReduce INT4: E5M2 group scale so groups above 480 no longer clip` | quant,rocm | main | - |
| P1 | [#7278](https://github.com/ROCm/aiter/issues/7278) `[Issue]: Triton MHA prefill attn_fwd (flash_attn_triton_amd) computes q/k/v/out row offsets in int32, which ov` | nvidia,risk,rocm | ? | - |
| P1 | [#7289](https://github.com/ROCm/aiter/pull/7289) `[Triton/Gluon] [gfx1250] gemm_a16w16: GPT-OSS decode buckets retuned with rotating weights; LM-head files` | perf,rocm | ? | - |
| P1 | [#7291](https://github.com/ROCm/aiter/pull/7291) `[ASM] [gfx1250] asm mha bf16 fwd: allow D64 without a sink` | rocm | ? | - |
| P0 | [#7294](https://github.com/ROCm/aiter/pull/7294) `[FlyDSL] [CI] [MoE] gemm2: bound atomic rows by the sort's valid token count` | infra,rocm | main | - |
| P0 | [#7297](https://github.com/ROCm/aiter/pull/7297) `[FlyDSL] [CI] [gfx950] Megamoe Ep Internode Impl` | infra,rocm | main | - |
| P1 | [#7298](https://github.com/ROCm/aiter/pull/7298) `[Fix] Build DeepSeek RoPE caches on the default device, not hard-coded cuda` | bug,infra,nvidia | ? | - |
| P0 | [#7317](https://github.com/ROCm/aiter/pull/7317) `[HIP] [CK] [FlyDSL] [GEMM][gfx950] Tune narrow-N MXFP4 with CSV-selected preshuffle kernels` | perf,quant,rocm | main | - |
| - | [#7330](https://github.com/ROCm/aiter/pull/7330) `[CI] Scope test_moe_2stage.py to representative tokens in standard CI` | infra | ? | - |
| P1 | [#7335](https://github.com/ROCm/aiter/pull/7335) `[Config] Qwen3.5-397B: FlyDSL rows for the 528-row MoE router GEMM (gfx950)` | rocm | ? | - |
| P1 | [#7350](https://github.com/ROCm/aiter/issues/7350) `[Issue]: FlyDSL fused_compress_attn corrupts the first compressed entry of each sequence (negative-history sta` | perf,risk,rocm | ? | - |
| P1 | [#7356](https://github.com/ROCm/aiter/issues/7356) `[Issue]: AITER_AR_1STAGE_MAX_KB is compared as bytes, not KiB, in the fused all-reduce one-stage limit` | perf,rocm | ? | - |
| P1 | [#7357](https://github.com/ROCm/aiter/pull/7357) `[Bugfix] Clarify fused all-reduce limit units with MAX_BYTES` | perf | ? | - |
| P0 | [#7361](https://github.com/ROCm/aiter/pull/7361) `[CK] [JIT] [aiter] Clamp FP8 per_Token / per_Tensor SiLU on #7019's runtime swiglu_limit` | infra,quant,rocm | main | - |
| P1 | [#7371](https://github.com/ROCm/aiter/pull/7371) `[ASM] [HIP] perf(pa): update gfx950 unified MTP code objects` | perf,rocm | ? | - |
| P1 | [#7376](https://github.com/ROCm/aiter/pull/7376) `[HIP] [Bugfix] Skip grouped top-k launches with zero tokens` | rocm | ? | - |
| P1 | [#7381](https://github.com/ROCm/aiter/pull/7381) `[Config] [Tune] GLM-5.3 a8w8 blockscale GEMM rows for gfx950` | perf,quant,rocm | ? | - |
| P1 | [#7385](https://github.com/ROCm/aiter/pull/7385) `[CI] ci: cache CK submodule checkout` | infra,perf | ? | - |
| P1 | [#7388](https://github.com/ROCm/aiter/pull/7388) `[FlyDSL] [Misc] pa_decode: key the tile kernel on FlyDSL dtypes and drop the batch-first plan grid` | perf,rocm | ? | - |
| P1 | [#7389](https://github.com/ROCm/aiter/pull/7389) `[Config] [Perf] Tune DeepSeek V4.1 EP16 A4W4 for routed and shared experts` | perf,quant | ? | - |
| P1 | [#7407](https://github.com/ROCm/aiter/pull/7407) `[ASM] [HIP] [CI] Add gfx1250 MLA v4.1 a8w4 fused sparse prefill kernel` | infra,perf,rocm | ? | - |
| P1 | [#7414](https://github.com/ROCm/aiter/pull/7414) `[Config] [Tuning][gfx950] Retune MiniMax-M3.1 TP4 A16W4 decode rows (E=128, top-4) for 8/16/32/64/128 tokens` | perf,quant,rocm | ? | - |
| P1 | [#7421](https://github.com/ROCm/aiter/pull/7421) `[Triton/Gluon] [GFX12] A8K4V8 Attention` | rocm | ? | - |
| - | [#7424](https://github.com/ROCm/aiter/pull/7424) `[FlyDSL] Move _e8m0_byte_to_f32 into mxfp4_gemm_common` | quant,rocm | ? | - |
| P1 | [#7432](https://github.com/ROCm/aiter/pull/7432) `[HIP] perf(custom_ar): gfx1250 LL two-shot all-reduce for 1 MiB+ messages` | perf,rocm | ? | - |
| P0 | [#7452](https://github.com/ROCm/aiter/pull/7452) `[HIP] fea: impl lamport allreduce on gfx9` | rocm | main | - |
| P1 | [#7456](https://github.com/ROCm/aiter/pull/7456) `[Config] gfx1250: grouped-MoE tiles for Kimi-K2 Thinking TP8` | rocm | ? | - |
| P1 | [#7457](https://github.com/ROCm/aiter/pull/7457) `[Config] Add gfx950 BF16 GEMM tunings for Gemma-4-26B-A4B` | perf,rocm | ? | - |
| P1 | [#7462](https://github.com/ROCm/aiter/pull/7462) `[ASM] [HIP] Optimize gfx950 MXFP6 GEMMs for Ideogram DiT shapes` | perf,quant,rocm | ? | - |
| P1 | [#7463](https://github.com/ROCm/aiter/pull/7463) `[HIP] Split MXFP6 GEMM launches whose output exceeds 2 GiB` | quant,rocm | ? | - |
| P1 | [#7464](https://github.com/ROCm/aiter/pull/7464) `[HIP] [MLA] Align gfx942 QH64 FP8 page-size planning` | quant,rocm | ? | - |
| P1 | [#7465](https://github.com/ROCm/aiter/pull/7465) `[Build] [RFC #7240] Kernel provider interface: configuration, priority, provenance, observability` | infra,perf | ? | - |
| P1 | [#7466](https://github.com/ROCm/aiter/pull/7466) `[CI] Run the provider interface tests as a CPU-only gate on every PR` | infra | ? | - |
| - | [#7482](https://github.com/ROCm/aiter/pull/7482) `[CI] Make PR Self-Review verdicts evidence-driven instead of event-driven` | infra | ? | - |
| P1 | [#7484](https://github.com/ROCm/aiter/pull/7484) `[JIT] Route five ops through the provider interface, and let a compiled op report its signature` |  | ? | - |
| P1 | [#7489](https://github.com/ROCm/aiter/pull/7489) `[Triton/Gluon] fused_clamp_act_mul: accept rows of whole quant groups` | perf,quant,rocm | ? | - |
| P1 | [#7494](https://github.com/ROCm/aiter/pull/7494) `[Triton/Gluon] [FlyDSL] [MoE] Kimi-K3 HERD on gfx1250: K+1 sigmoid top-k and one route+psum kernel` | perf,rocm | ? | - |
| P1 | [#7499](https://github.com/ROCm/aiter/pull/7499) `[HIP] fea: impl gfx1250 lamport ar+rms` | rocm | ? | - |
| P1 | [#7500](https://github.com/ROCm/aiter/pull/7500) `[FlyDSL] [MoE] Support row-strided MXFP4 activations` | quant,rocm | ? | - |
| P1 | [#7501](https://github.com/ROCm/aiter/pull/7501) `[FlyDSL] [MoE] [gfx1250] give each MX combine chunk its own scale line` | quant,rocm | ? | - |
| P1 | [#7503](https://github.com/ROCm/aiter/pull/7503) `[HIP] [FlyDSL] Conv3d gfx1250 Optimization` | perf,rocm | ? | - |
| P1 | [#7505](https://github.com/ROCm/aiter/pull/7505) `[OPUS] [gfx1250] Clear HIP sticky error after A0 strict-CO probe failure (#7185 follow-up)` | rocm | ? | - |
| - | [#7507](https://github.com/ROCm/aiter/pull/7507) `[Config] [gfx1250] Tune MiniMax-M3 DP4/EP4 dense GEMMs` | perf,rocm | ? | - |
| P1 | [#7513](https://github.com/ROCm/aiter/pull/7513) `[Triton/Gluon] [Config] gfx950: tune gemm_a16w16 for kimik3/glm5/qwen3.5 model shapes` | perf,rocm | ? | - |
| P1 | [#7515](https://github.com/ROCm/aiter/pull/7515) `[Config] [Tuning] Add Kimi-K3 gfx950 BF16 decode rows for qkv_a+gate a…` | perf,rocm | ? | - |
| P1 | [#7518](https://github.com/ROCm/aiter/pull/7518) `[Triton/Gluon] Cast strides to int64 in MHA prefill attn_fwd to prevent overflow` | risk,rocm | main | - |
| P1 | [#7534](https://github.com/ROCm/aiter/issues/7534) `[Issue]: module_moe_sorting_opus does not build for gfx1250 (DPP row_bcast in dpp_inclusive_scan_wave)` | infra,rocm | ? | - |
| P1 | [#7535](https://github.com/ROCm/aiter/issues/7535) `[Issue]: FlyDSL AOT replay aborts on ROCm 10: ROCR_VISIBLE_DEVICES=-1 is rejected` | rocm | ? | - |
| P1 | [#7540](https://github.com/ROCm/aiter/pull/7540) `[HIP] Fix/7534 moe sorting opus gfx1250` | bug,rocm | ? | - |
| - | [#7541](https://github.com/ROCm/aiter/pull/7541) `[CI] Skip Flash Attention CI on draft PRs` | infra | ? | - |
| P1 | [#7546](https://github.com/ROCm/aiter/pull/7546) `[HIP] [FlyDSL] [CI] Add tunable HGEMM K-stagger and B streaming loads` | infra,rocm | ? | - |
| P1 | [#7550](https://github.com/ROCm/aiter/pull/7550) `[FlyDSL] fused_compress_attn: zero padding kv in Phase 1` | perf,rocm | ? | - |
| P1 | [#7551](https://github.com/ROCm/aiter/pull/7551) `[FlyDSL] [AOT] Hide the GPUs from replays with empty device lists, not -1` | rocm | ? | - |
| P1 | [#7553](https://github.com/ROCm/aiter/pull/7553) `[FlyDSL] [FMHA] Paged-KV forward prefill` | rocm | ? | - |
| P1 | [#7555](https://github.com/ROCm/aiter/pull/7555) `[HIP] perf: gfx1250 LL all-gather lines carry 12 bytes and one flag` | perf,rocm | ? | - |
| P1 | [#7559](https://github.com/ROCm/aiter/pull/7559) `[ASM] [HIP] [gfx1250] asm mha bf16 hd256: batch and varlen forward` | rocm | ? | - |
| P1 | [#7560](https://github.com/ROCm/aiter/pull/7560) `[CI] Add area contacts and review guide; document merge rules and review timeline` | infra | ? | - |
| P1 | [#7563](https://github.com/ROCm/aiter/pull/7563) `review-pr: route the design judgment instead of making it (Step 7.8)` |  | ? | - |
| P1 | [#7568](https://github.com/ROCm/aiter/pull/7568) `[CI] Install the amd-mori 1.2.5 release for the multi-GPU tests` | infra,rocm | ? | - |
| P1 | [#7570](https://github.com/ROCm/aiter/pull/7570) `[HIP] [Perf] Add a wide split-K reduce for MLA decode and verify with few units and many splits` | perf,rocm | ? | - |
| P1 | [#7572](https://github.com/ROCm/aiter/pull/7572) `[FlyDSL] [MoE] comm-fused MoE: launch clear_missing_routes over the whole route scratch` | perf,rocm | ? | - |
| P1 | [#7573](https://github.com/ROCm/aiter/pull/7573) `[HIP] [JIT] gfx1250 Mega-MHC: XCD-local and clustered split tiles, sublayer TDM, res_preshuffle helpers` | rocm | ? | - |
| P0 | [#7574](https://github.com/ROCm/aiter/pull/7574) `[ASM] Fix LDS race between V reads and R re-layout in gfx950 BF16 QH3…` | bug,risk,rocm | main | - |
| - | [#7583](https://github.com/ROCm/aiter/pull/7583) `[FlyDSL] Fix main CI: missing DROPPED_ROUTE_ROW import in moe_contiguous_psum` | bug,infra,rocm | ? | - |
| - | [#7584](https://github.com/ROCm/aiter/pull/7584) `[HIP] [Feature] Add group/varlen and sliding-window support to the hd128 opus forward` | rocm | ? | - |
| - | [#7591](https://github.com/ROCm/aiter/pull/7591) `[Triton/Gluon] GEMM: compute GRID_MN at runtime instead of as a constexpr` | rocm | ? | - |
| - | [#7598](https://github.com/ROCm/aiter/pull/7598) `[FlyDSL] Target the AOT dry run through FLYDSL_GPU_ARCH only` | rocm | ? | - |
| - | [#7600](https://github.com/ROCm/aiter/pull/7600) `[FlyDSL] [CI] [Build] Bump FlyDSL pin to v0.5.0` | infra,rocm | ? | - |
| - | [#7601](https://github.com/ROCm/aiter/pull/7601) `[FlyDSL] [Bugfix] Zero consumed kv in the gfx1250 HCA Phase 2 loop` | rocm | ? | - |
| - | [#7602](https://github.com/ROCm/aiter/pull/7602) `[Config] [MoE] retune DeepSeek-V4.1-Flash TP2 decode buckets` | perf | ? | - |
| - | [#7610](https://github.com/ROCm/aiter/issues/7610) `PR#6952 breaks ATOM main: pa_mqa_logits_mxfp4_plan removed without backward compat` | quant | ? | - |
| P1 | [#7613](https://github.com/ROCm/aiter/pull/7613) `[Bugfix] MLA decode: merge only the splits gfx950 fp8 gqa16 stage 1 writes` | quant,rocm | ? | - |
| - | [#7615](https://github.com/ROCm/aiter/pull/7615) `review-pr: the queue notice was wrong in both directions` |  | ? | - |
| P0 | [#7617](https://github.com/ROCm/aiter/pull/7617) `[ASM] [Bugfix] Fix LDS race in gfx950 FP8 QH16 qseqlen1 MLA decode` | bug,quant,risk,rocm | main | - |
| - | [#7619](https://github.com/ROCm/aiter/pull/7619) `[FlyDSL] gfx1250 PA decode: wider page-local softmax steps, shared clusters and wave-pair MTP4 for MiniMax-M3` | rocm | ? | - |
| - | [#7620](https://github.com/ROCm/aiter/pull/7620) ` [MoE] [FlyDSL] BM16 adaptive aux sort writes into the caller's output; retune kimik3 a8w4 token-16 inter-384` | perf,rocm | ? | - |
| P0 | [#7622](https://github.com/ROCm/aiter/pull/7622) `[ASM] Fix LDS races in gfx950 FP8 QH16 qseqlen1 persistent MLA decode` | bug,quant,rocm | main | - |
| - | [#7624](https://github.com/ROCm/aiter/pull/7624) `[Perf] DeepSeek-V4.1-Flash TP2 decode: indexer top-k split gate and router GEMM row` | perf | ? | - |
| - | [#7634](https://github.com/ROCm/aiter/pull/7634) `[CI] Run Windows smoke on Radeon R9700 runner` | infra | ? | - |
| - | [#7636](https://github.com/ROCm/aiter/pull/7636) `[CI] CI: auto-update split test times` | infra | ? | - |
| - | [#7638](https://github.com/ROCm/aiter/pull/7638) `[CI] review-pr: watch for review requests starved of a hosted runner` | infra | ? | - |
| P0 | [#7639](https://github.com/ROCm/aiter/issues/7639) `[MLA][gfx950] non-persistent fp8 gqa16 qlen 3-4 (mla_a8w8_qh64_qseqlen4_gqaratio16) computes only KV split 0 a` | quant,rocm | ? | - |
| - | [#7641](https://github.com/ROCm/aiter/pull/7641) `[CI] CI: add MI300X standard label trigger` | infra,rocm | ? | - |
| - | [#7642](https://github.com/ROCm/aiter/pull/7642) `review-pr: a queued run past its gate is the box's queue, not a starved one` |  | ? | - |
| P1 | [#7644](https://github.com/ROCm/aiter/pull/7644) `[Config] [Perf] Tune DeepSeek-V4-Pro small-M FP8 GEMMs on gfx1250` | perf,quant,rocm | ? | - |
| - | [#7645](https://github.com/ROCm/aiter/pull/7645) `[CI] Fix SGLang downstream human-eval patches for $CI_CONTAINER_NAME` | bug,infra | ? | - |
| - | [#7646](https://github.com/ROCm/aiter/issues/7646) `mxfp4_moe_sort_fwd zeroes the last token's final scales when K // 32 is not a multiple of 4 (e.g. K=2880)` | quant | ? | - |
| - | [#7647](https://github.com/ROCm/aiter/pull/7647) `MHA v4: fix torch 2.10 Dynamo graph break` | bug,infra,rocm | ? | - |
| - | [#7652](https://github.com/ROCm/aiter/pull/7652) `[FlyDSL] [AOT] Scan gfx1250 GEMM rows at representative M, not every M` | rocm | ? | - |
| P0 | [#7653](https://github.com/ROCm/aiter/pull/7653) `[HIP] [Bugfix] mxfp4_moe_sort: keep the last row's tail scales when model_dim / 32 is not a multiple of 4` | quant,rocm | main | - |
| - | [#7654](https://github.com/ROCm/aiter/pull/7654) `[RFC #7240] Let a provider report what a kernel costs, and record it unchanged` | bug,perf | ? | - |
| - | [#7655](https://github.com/ROCm/aiter/pull/7655) `[FlyDSL] V0.4.2 Tdm new interface refactor: make_tdm_atom -> make_tiled_tdm_atom` | rocm | ? | - |
| - | [#7656](https://github.com/ROCm/aiter/pull/7656) `[Config] [DSv4.1] gfx950 FP8 fused_moe: retune TP4 prefill rows (token 4096-16384)` | perf,quant,rocm | ? | - |
| - | [#7660](https://github.com/ROCm/aiter/pull/7660) `[CI] Schedule release automation on Sunday` | infra | ? | - |
| - | [#7661](https://github.com/ROCm/aiter/pull/7661) `[FlyDSL] [gfx1250] MegaMoE: fold the shared expert output into the fused combine reduce` | perf,rocm | ? | - |
| - | [#7662](https://github.com/ROCm/aiter/pull/7662) `[FlyDSL] [gfx1250] Radix top-k: 512-thread blocks for long decode rows, index-sort output for streaming rows` | rocm | ? | - |
| - | [#7664](https://github.com/ROCm/aiter/pull/7664) `[FlyDSL] [gfx1250] MegaMoE: bf16-wire combine reduce reads its inputs directly` | rocm | ? | - |
| - | [#7669](https://github.com/ROCm/aiter/pull/7669) `[CI] Add biweekly guard for release automation` | infra | ? | - |
| - | [#7683](https://github.com/ROCm/aiter/pull/7683) `[Triton/Gluon] [GFX950] Unified Attention Improve SW masking` | rocm | ? | - |
| - | [#7694](https://github.com/ROCm/aiter/pull/7694) `[CI] docker_pull_with_retry: Fall back to mirror.gcr.io when a Docker Hub pull fails` | infra | ? | - |
| - | [#7695](https://github.com/ROCm/aiter/pull/7695) `[Docs] [RFC #7240] How to serve an AITER op from an out-of-tree kernel library` | perf,rocm | ? | - |
| - | [#7696](https://github.com/ROCm/aiter/pull/7696) `[RFC #7240] aiter-kernel-plugin skill: how an agent ports a kernel library onto the interface` | perf,rocm | ? | - |
| P1 | [#7700](https://github.com/ROCm/aiter/pull/7700) `[FlyDSL] [Perf] pa_decode: gfx950 fused BF16 MTP4 verify tile, decode load scheduling and lean FP8 MTP4; four ` | perf,quant,rocm | ? | - |
| - | [#7702](https://github.com/ROCm/aiter/pull/7702) `[ASM] [HIP] Build gfx1250 MLA v4 sparse prefill from in-tree sources` | infra,rocm | ? | - |
| - | [#7708](https://github.com/ROCm/aiter/pull/7708) `review-pr: register the ten rule ids derive() can emit but ALL_RULES omits` |  | ? | - |
| P0 | [#7709](https://github.com/ROCm/aiter/pull/7709) `[FlyDSL] [Perf] pa_decode: gfx942 schedule tuning (K/V streaming, latency hiding, grid-size policies)` | perf,rocm | main | - |
| - | [#7713](https://github.com/ROCm/aiter/pull/7713) `[Test] [RFC #7240] Pin what a provider's first call may do inside a graph capture` | infra | ? | - |
| - | [#7723](https://github.com/ROCm/aiter/pull/7723) `[Test] test_custom_allreduce_lamport: one PASS/FAIL line per case` | infra | ? | - |
| - | [#7724](https://github.com/ROCm/aiter/pull/7724) `[FlyDSL] [Perf] gfx1250 gather_kv_b_proj: write FP8 K/V with caller descales` | perf,quant,rocm | ? | - |
| - | [#7726](https://github.com/ROCm/aiter/pull/7726) `[FlyDSL] [gfx1250] Optimize grouped MoE prefill and DSR1 EP tuning` | perf,rocm | ? | - |
| - | [#7728](https://github.com/ROCm/aiter/pull/7728) `[RFC #7240] Route the DeepSeek V4.1 op surface: seven contracts` |  | ? | - |
| - | [#7729](https://github.com/ROCm/aiter/pull/7729) `[Triton/Gluon] Sol-Attn: block pooling, routing and low-rank tilt factors` | rocm | ? | - |
| - | [#7731](https://github.com/ROCm/aiter/pull/7731) `[Config] [MoE] Add DeepSeek-V4.1-Flash EP8 fused-MoE rows for gfx950` | perf,rocm | ? | - |
| - | [#7748](https://github.com/ROCm/aiter/pull/7748) `[CI] [DI] Fix AITER vLLM & ATOM workflows.` | bug,infra,rocm | ? | - |
| - | [#7758](https://github.com/ROCm/aiter/pull/7758) `[ASM] Mha v4: shorter gfx950 hd128/hd256 prologue` | rocm | ? | - |
| - | [#7765](https://github.com/ROCm/aiter/pull/7765) `[FlyDSL] fix aot/flydsl/mxfp4_moe.py test` | bug,quant,rocm | ? | - |
| - | [#7774](https://github.com/ROCm/aiter/pull/7774) `[FlyDSL] Fix a16wfp4 stage2 cache-key test for FlyDSL 0.5.0` | bug,perf,rocm | ? | - |
| P1 | [#7784](https://github.com/ROCm/aiter/pull/7784) `[ASM] [HIP] [JIT] [Perf] Replace gfx950 MLA v4 prefill 16mx8 kernels with 32mx4 kernels` | infra,perf,rocm | ? | - |
| - | [#7787](https://github.com/ROCm/aiter/pull/7787) `[RFC #7240] Document every routed contract, and gate that it stays documented` |  | ? | - |
| - | [#7791](https://github.com/ROCm/aiter/pull/7791) `[OPUS] [RFC #7240] Route MLA sparse prefill where its two public spellings converge` | infra | ? | - |
| - | [#7794](https://github.com/ROCm/aiter/pull/7794) `[ASM] [HIP] Sol-Attn: gfx950 kernels` | perf,rocm | ? | - |
| - | [#7802](https://github.com/ROCm/aiter/pull/7802) `[Triton/Gluon] op_benchmarks: time the mha_v4 Sol-Attn rows` | perf,rocm | ? | - |
| - | [#7804](https://github.com/ROCm/aiter/pull/7804) `[FlyDSL] Fix attention A2A MX Q-scale backing for mha_v4 query-tile gather` | bug,infra,quant,rocm | ? | - |
| - | [#7807](https://github.com/ROCm/aiter/pull/7807) `[RFC #7240] Route the three attention entry points frameworks call` |  | ? | - |
| - | [#7812](https://github.com/ROCm/aiter/pull/7812) `[FlyDSL] [Fix] gfx1250 paged FP8 MQA logits: read index rows padded past 132 bytes` | bug,quant,rocm | ? | - |
| - | [#7829](https://github.com/ROCm/aiter/pull/7829) `[Config] Add M=8320 MiniMax-M3 MXFP8 GEMM rows for gfx950` | quant,rocm | ? | - |
| - | [#7833](https://github.com/ROCm/aiter/issues/7833) `[Issue]: gfx1250 FlyDSL AOT fails for 37 mxfp8 block-128 GEMM configs since #7655` | quant,rocm | ? | - |
| - | [#7842](https://github.com/ROCm/aiter/pull/7842) `[Config] Add gfx942 a8w8 blockscale tunings for Qwen3.5 GDN input projections` | perf,quant,rocm | ? | - |
| - | [#7848](https://github.com/ROCm/aiter/pull/7848) `[RFC #7240] Build the plugin config snapshot at import, not on first dispatch` | infra | ? | - |
| - | [#7850](https://github.com/ROCm/aiter/pull/7850) `[RFC #7240] Let a routed op be an opaque node instead of traced Python` | infra | ? | - |
| - | [#7851](https://github.com/ROCm/aiter/pull/7851) `[HIP] [FlyDSL] [gfx1250] Port BF16/FP16 TDM GEMM into the existing AITER tuner` | perf,rocm | ? | - |
| - | [#7853](https://github.com/ROCm/aiter/pull/7853) `[ASM] [HIP] [gfx1250] asm mha bf16 d192x128 varlen: launch options per call` | rocm | ? | - |
| - | [#7854](https://github.com/ROCm/aiter/pull/7854) `[RFC #7240] Route the three remaining DSV4.1 ops that already have a guard` | infra | ? | - |
| P1 | [#7858](https://github.com/ROCm/aiter/pull/7858) `[FlyDSL] [Perf] pa_decode: K/V streaming, MTP query split and sparse split-major on gfx950` | perf,rocm | ? | - |
| - | [#7871](https://github.com/ROCm/aiter/pull/7871) `[Triton/Gluon] [Bugfix] Guard gfx1250 scheduling hints on older Triton` | rocm | ? | - |
| - | [#7874](https://github.com/ROCm/aiter/pull/7874) `[Plugin] Route topk_gating and top_k_per_row_decode as custom ops` | infra | ? | - |
| - | [#7875](https://github.com/ROCm/aiter/pull/7875) `[Triton/Gluon] [Plugin] Route fused_dual_rmsnorm_mxfp8_quant` | infra,perf,quant,rocm | ? | - |
| - | [#7878](https://github.com/ROCm/aiter/pull/7878) `[FlyDSL] [Perf] Enable small-k row top-k on gfx1250` | perf,rocm | ? | - |
| - | [#7881](https://github.com/ROCm/aiter/pull/7881) `[Plugin] Register the routed ops that can be, and gate the rest` | infra | ? | - |
| - | [#7886](https://github.com/ROCm/aiter/issues/7886) `fused_moe_2stages: doesn't check metadata.run_1stage before composing a two-stage pipeline` | perf | ? | - |
| - | [#7889](https://github.com/ROCm/aiter/pull/7889) `Add benchmarking for padding mode` | perf | ? | - |
| - | [#7892](https://github.com/ROCm/aiter/pull/7892) `[FlyDSL] [AOT] Fix the Nightly's FlyDSL AOT replay on torch 2.9.1 (#7805 + #7561)` | bug,rocm | ? | - |
| - | [#7897](https://github.com/ROCm/aiter/pull/7897) `[ASM] [HIP] Walk prefix and extend as one tile stream in gfx950 MLA sparse prefill` | rocm | ? | - |
| - | [#7903](https://github.com/ROCm/aiter/pull/7903) `[HIP] [MSA] Fix nvfp4 prefill multi-arch wheel build` | bug,infra,quant,rocm | ? | - |
| - | [#7908](https://github.com/ROCm/aiter/pull/7908) `[Triton/Gluon] fused_clamp_act_mul: guard the Triton quant tile width` | perf,quant,rocm | ? | - |
| P1 | [#7915](https://github.com/ROCm/aiter/pull/7915) `[Config] [MoE] Add gfx942 FMoE rows for Muse Spark Open PTPC FP8 under expert parallelism` | quant,rocm | ? | - |
| - | [#7919](https://github.com/ROCm/aiter/pull/7919) `[FlyDSL] [gfx1250] Absorb grouped MoE GEMM1 prefill opts into mega stage-1` | rocm | ? | - |
| - | [#7920](https://github.com/ROCm/aiter/pull/7920) `[FlyDSL] [gfx1250] Pass arg_scale_out on every cached launch_gemm_a8w8 launch` | quant,rocm | ? | - |
| - | [#7924](https://github.com/ROCm/aiter/pull/7924) `[FlyDSL] [gfx1250] Compile mxfp8_128 GEMMs whose scale-B tile is one element` | quant,rocm | ? | - |
| - | [#7926](https://github.com/ROCm/aiter/pull/7926) `[Plugin] Fix torch auto_functionalized_v2 assert: route() gains explicit mutates_args` | bug,infra,rocm | ? | - |
| - | [#7930](https://github.com/ROCm/aiter/pull/7930) `[CI] FFM Triton: fall back to main when the suite source ref is gone` | infra,rocm | ? | - |

### aiter — Open / submitted (237 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#7230](https://github.com/ROCm/aiter/pull/7230) `[HIP] [Tuning] [gfx950] Add MiniMax-M3 MXFP4 MoE configs for TP8 (E=128, top-4, inter_dim 384)` | perf,quant,rocm | main | - |
| P0 | [#7349](https://github.com/ROCm/aiter/pull/7349) `[FlyDSL] Fix LDS race in MoE sorting p23 kernel` | bug,perf,risk,rocm | main | - |
| P0 | [#7355](https://github.com/ROCm/aiter/pull/7355) `[FlyDSL] [Bugfix] MoE sorting: allocate the multiphase workspace per call` | rocm | main | - |
| P0 | [#7393](https://github.com/ROCm/aiter/issues/7393) `[MLA] gfx942 persistent a8w8 decode returns output / kv_scale at q_len 3 and 4` | quant,rocm | ? | - |
| P0 | [#7509](https://github.com/ROCm/aiter/pull/7509) `[OPUS] [Bugfix] Fix LDS race in gfx942 A8W8 blockscale B-preshuffle GEMM` | bug,quant,risk,rocm | main | - |
| P1 | [#7536](https://github.com/ROCm/aiter/issues/7536) `[Issue]: grouped MoE GEMM tests require an AOT entry for moe_fused_route_quant_scatter that run_aot does not b` | infra,perf,quant | ? | - |
| P1 | [#7537](https://github.com/ROCm/aiter/pull/7537) `[FlyDSL] FP4 row-group MQA logits: opt-in \|s\| epilogue and 16-key tile maxima` | quant,rocm | ? | - |
| P1 | [#7538](https://github.com/ROCm/aiter/pull/7538) `[CK] [JIT] [Feature] Add model-specific MXFP4 A4W4 tuning profiles` | perf,quant | ? | - |
| P1 | [#7539](https://github.com/ROCm/aiter/pull/7539) `[Triton/Gluon] Clamp gfx950 unified attention block-table prefetch in all modes` | rocm | ? | - |
| P1 | [#7542](https://github.com/ROCm/aiter/pull/7542) `[CK] [FlyDSL] Dev/ms ep32 support` | rocm | ? | - |
| P1 | [#7543](https://github.com/ROCm/aiter/pull/7543) `[FlyDSL] perf(flydsl): fold the gfx1250 TP MoE route into the activation quant` | perf,quant,rocm | ? | - |
| P1 | [#7544](https://github.com/ROCm/aiter/pull/7544) `[Triton/Gluon] Explicit tl.fma in blockscale GEMM kernels for Triton 3.9` | infra,perf,quant,rocm | ? | - |
| P1 | [#7547](https://github.com/ROCm/aiter/pull/7547) `[FlyDSL] perf(flydsl): route the gfx1250 TP prefill MoE in one launch` | perf,rocm | ? | - |
| P1 | [#7548](https://github.com/ROCm/aiter/pull/7548) `[HIP] [FlyDSL] Port gfx1250 TDM HGEMM and source tuning space` | perf,rocm | ? | - |
| P0 | [#7552](https://github.com/ROCm/aiter/pull/7552) `[HIP] getPaddedM: fall back to the M=16 row for M<16 when no power-of-two row is tuned` | perf,rocm | main | - |
| P0 | [#7554](https://github.com/ROCm/aiter/pull/7554) `[Triton/Gluon] [Bugfix] gemm_afp4wfp4: mask K-tail scales with 0, not 127` | quant,rocm | main | - |
| P1 | [#7556](https://github.com/ROCm/aiter/pull/7556) `[FlyDSL] [QSA] Sparse prefill attention on gfx950: union and packed-direct ports, strided K/V, routing` | rocm | ? | - |
| P0 | [#7558](https://github.com/ROCm/aiter/pull/7558) `[fused_moe] Keep Swiglu MXFP4 A4W4 off a numerically-broken shape` | perf,quant | main | - |
| P1 | [#7564](https://github.com/ROCm/aiter/pull/7564) `[Triton/Gluon] gfx950: add opt-in ping-pong Gluon kernel for MXFP4 GEMM` | infra,perf,quant,rocm | ? | - |
| P1 | [#7565](https://github.com/ROCm/aiter/pull/7565) `[MOE] Rotate the SwiGLU output between the two GEMMs` |  | ? | - |
| P0 | [#7566](https://github.com/ROCm/aiter/pull/7566) `[Triton/Gluon] [gfx950] One query block per short sequence; split-KV and 128-key tile for decode` | rocm | main | - |
| P0 | [#7567](https://github.com/ROCm/aiter/pull/7567) `[FlyDSL] [Bugfix] Fix MoE XCD swizzle on grids not divisible by 8` | bug,rocm | main | - |
| P1 | [#7569](https://github.com/ROCm/aiter/pull/7569) `[HIP] [Bugfix] Saturate the fp8 rope output of fused_qk_rope_concat_and_cache_mla` | perf,quant,rocm | ? | - |
| P1 | [#7571](https://github.com/ROCm/aiter/pull/7571) `[Docs] Update ruff version in contribution guidelines to match CI` | infra | ? | - |
| P1 | [#7576](https://github.com/ROCm/aiter/pull/7576) `[HIP] [Bugfix] sample: Map exponential's top uniform bucket to a positive sample` | rocm | ? | - |
| P1 | [#7577](https://github.com/ROCm/aiter/pull/7577) `[Triton] [Config] Add gfx1201 gemm_a16w4 configs` | quant,rocm | ? | - |
| P1 | [#7580](https://github.com/ROCm/aiter/pull/7580) `[Tune] GLM-5 MQA logits: retune with clean_logits=False, add GLM-5.3-Flash rows` | perf | ? | - |
| P1 | [#7581](https://github.com/ROCm/aiter/pull/7581) `[Config] [Perf] Retune DeepSeek-V4.1-Flash EP4 MXFP4 (a4w4) fused-MoE rows for gfx950` | infra,perf,quant,rocm | ? | - |
| - | [#7585](https://github.com/ROCm/aiter/pull/7585) `[Triton] [Config] Add gfx1201 SonicMoE config` | rocm | ? | - |
| P0 | [#7586](https://github.com/ROCm/aiter/pull/7586) `[Bugfix] Keep gfx942 asm 1-stage fmoe off expert weights past 4 GiB` | rocm | main | - |
| - | [#7587](https://github.com/ROCm/aiter/pull/7587) `[Triton/Gluon] [GFX12] Optimize mxfp8 gfx1250 gluon` | perf,quant,rocm | ? | - |
| P1 | [#7589](https://github.com/ROCm/aiter/pull/7589) `[CK] [Bugfix] Give every GPU_ARCHS arch its own ck2stages MoE kernel table` | infra,perf,rocm | ? | - |
| P1 | [#7590](https://github.com/ROCm/aiter/issues/7590) `gfx942 MLA a8w8 asm kernels cast softmax P to fp8 e4m3fnuz without scaling: small probabilities become subnorm` | perf,quant,rocm | ? | - |
| - | [#7592](https://github.com/ROCm/aiter/issues/7592) `NameError: DROPPED_ROUTE_ROW not defined in moe_contiguous_psum.py (TP4 mode crash)` | bug | ? | - |
| - | [#7593](https://github.com/ROCm/aiter/issues/7593) `[issue] gfx942 (MI300X) result for pytest op_tests/test_mha_fp8.py op_tests/test_mha_varlen_fp8.py` | rocm | ? | - |
| - | [#7594](https://github.com/ROCm/aiter/pull/7594) `[Triton/Gluon] mha variant for varlen` | rocm | ? | - |
| - | [#7596](https://github.com/ROCm/aiter/pull/7596) `[FlyDSL] [Perf] gfx950 A16W16: rectangular tiles, nonuniform loads and tunable split-K workspace for Kimi-K3 s` | perf,rocm | ? | - |
| - | [#7597](https://github.com/ROCm/aiter/pull/7597) `[Triton] [Config] Add gfx1201 sparse_mla_dsv4_train config` | rocm | ? | - |
| - | [#7603](https://github.com/ROCm/aiter/pull/7603) `[Triton/Gluon] Add more support to mxfp8 attention` | quant,rocm | ? | - |
| P1 | [#7604](https://github.com/ROCm/aiter/issues/7604) `[Issue]: [gfx1250] DeepSeek-V4-Pro accuracy collapses under sustained load: TDM-store stale LDS in MoE GEMMs +` | bug,risk,rocm | ? | - |
| - | [#7605](https://github.com/ROCm/aiter/pull/7605) `[FlyDSL] [Bugfix] gfx1250 grouped MoE GEMM: store the output tile without the TDM store` | rocm | ? | - |
| - | [#7606](https://github.com/ROCm/aiter/pull/7606) `[HIP] [JIT] [MoE] NVFP4 routed-expert MoE for gfx950` | quant,rocm | ? | - |
| - | [#7607](https://github.com/ROCm/aiter/pull/7607) `[Triton/Gluon] [gfx1250] MLA decode: tune H64 and TP8, add split-FP8 compute for bf16 queries` | perf,quant,rocm | ? | - |
| - | [#7608](https://github.com/ROCm/aiter/pull/7608) `[FlyDSL] gfx1201 flash attention: support head_dim % 8 (PixArt, DiT, SD1.5, HunyuanDiT)` | rocm | ? | - |
| - | [#7611](https://github.com/ROCm/aiter/pull/7611) `[ASM] [HIP] [MoE] Run the FLAT and EMSORT MXFP4 fmoe tiles on padded intermediate widths` | quant,rocm | ? | - |
| - | [#7612](https://github.com/ROCm/aiter/pull/7612) `[Bugfix] MHA varlen forward: copy inputs with a zero stride before dispatch` |  | ? | - |
| P1 | [#7614](https://github.com/ROCm/aiter/pull/7614) `[Triton/Gluon] [Config] [Perf] Tune gfx950 FP8 blockscale selections for DSv4 decode` | perf,quant,rocm | ? | - |
| - | [#7616](https://github.com/ROCm/aiter/pull/7616) `[Triton/Gluon] [gfx1250] gemm_a16w16: optional accumulate epilogue (y…` | rocm | ? | - |
| - | [#7618](https://github.com/ROCm/aiter/pull/7618) `[FlyDSL] Optimize gfx1250 MiniMax-M3 paged attention and planning` | perf,rocm | ? | - |
| P0 | [#7621](https://github.com/ROCm/aiter/pull/7621) `[ASM] Fix LDS races in gfx950 FP8 QH16 qseqlen2 MLA decode` | bug,quant,rocm | main | - |
| P0 | [#7623](https://github.com/ROCm/aiter/pull/7623) `[ASM] Fix MFMA operand race in gfx950 FP8 QH16 qseqlen4 v3 MLA decode` | bug,quant,risk,rocm | main | - |
| - | [#7625](https://github.com/ROCm/aiter/pull/7625) `[Triton/Gluon] [Config] gfx1151 sparse_mla_dsv4_train: forward num_warps 2` | rocm | ? | - |
| - | [#7626](https://github.com/ROCm/aiter/pull/7626) `[Triton/Gluon] [Config] gfx1151 SonicMoE: measured grouped-GEMM buckets` | rocm | ? | - |
| - | [#7627](https://github.com/ROCm/aiter/pull/7627) `[Triton] [Config] Add gfx1150 batched_gemm_a16w16 configs` | rocm | ? | - |
| - | [#7628](https://github.com/ROCm/aiter/pull/7628) `[Triton] [Config] gfx1151 gemm_a16w16: shape-specific configs and DEFAULT.json re-pick` | rocm | ? | - |
| - | [#7629](https://github.com/ROCm/aiter/pull/7629) `[Triton/Gluon] fused_clamp_act_mul: Do not recompile per row count` | perf,rocm | ? | - |
| - | [#7630](https://github.com/ROCm/aiter/pull/7630) `[Triton/Gluon] Add arch_info.is_cdna3()` | rocm | ? | - |
| P0 | [#7631](https://github.com/ROCm/aiter/issues/7631) `[gfx950] mla_dec_stage1_bf16_a16w16_subQ128_mqa128.co gives nondeterministic, wrong output when a workgroup ha` | risk,rocm | ? | - |
| - | [#7632](https://github.com/ROCm/aiter/pull/7632) `[Triton/Gluon] [Bugfix] gfx1250 a4w4 MoE decode: store the output tile without the TDM store` | quant,rocm | ? | - |
| - | [#7633](https://github.com/ROCm/aiter/pull/7633) `[Config] [FlyDSL] MiniMax-M3.1 EP4/EP8 fused-MoE tuned rows (gfx950, M=32768 tier)` | perf,rocm | ? | - |
| - | [#7635](https://github.com/ROCm/aiter/pull/7635) `[Triton] [Config] Add gfx1151 gemm_a16w16_atomic configs` | rocm | ? | - |
| - | [#7637](https://github.com/ROCm/aiter/pull/7637) `[Triton/Gluon] gemm_a16w16_atomic: fix wrong results when the split-K length is not a multiple of BLOCK_SIZE_K` | bug,rocm | ? | - |
| P0 | [#7640](https://github.com/ROCm/aiter/pull/7640) `[HIP] fix(moe_sorting): pad ids name the tensor's height, not num_local_tokens` | bug,rocm | main | - |
| - | [#7648](https://github.com/ROCm/aiter/pull/7648) `[FlyDSL] [Feature] Add quantized attention-output intranode all-to-all for Ulysses sequence-parallel attention` | quant,rocm | ? | - |
| - | [#7649](https://github.com/ROCm/aiter/issues/7649) `gfx950 unified_attention: full measurements and analysis for #7566` | rocm | ? | - |
| - | [#7650](https://github.com/ROCm/aiter/pull/7650) `[Triton/Gluon] [Config] [Perf] gfx950: tune gemm_a16w16 for Qwen3-Next shapes (N=32, N=512, K=2048)` | perf,rocm | ? | - |
| - | [#7657](https://github.com/ROCm/aiter/pull/7657) `[CK] [Tuner] fmoe FlyDSL: random routing for v2 tuning data, e2e testing and skip stage-1 tiles the runtime fo` | perf,rocm | ? | - |
| - | [#7658](https://github.com/ROCm/aiter/pull/7658) `[FlyDSL] [CI] [Bugfix] Run the a16w4 SiTUv2 MoE test in CI and reject gate/up-interleaved w1 on that route` | infra,quant,rocm | ? | - |
| - | [#7663](https://github.com/ROCm/aiter/pull/7663) `[Triton/Gluon] [gfx1250] DSv4.1 router GEMM (N=384, K=5120): Gluon buckets and bf16 rows for M 576/672/768` | infra,rocm | ? | - |
| - | [#7667](https://github.com/ROCm/aiter/pull/7667) `[FlyDSL] [gfx1250] Batched mxfp8 GEMM fused-quant epilogue: quantize from the accumulators, use the tuned row` | perf,quant,rocm | ? | - |
| - | [#7668](https://github.com/ROCm/aiter/pull/7668) `[FlyDSL] [gfx1250] mx32 GEMM: software-pipelined K loop; DSv4.1 rows use it` | rocm | ? | - |
| - | [#7673](https://github.com/ROCm/aiter/pull/7673) `[FlyDSL] [gfx1250] Compute GEMM: fused MXFP8 epilogue; untuned prefill-sized batched mxfp8_32 runs the compute` | perf,quant,rocm | ? | - |
| - | [#7674](https://github.com/ROCm/aiter/pull/7674) `[FlyDSL] Add FP32 output to gfx950 skinny HGEMM` | rocm | ? | - |
| - | [#7675](https://github.com/ROCm/aiter/pull/7675) `[Triton/Gluon] [gfx1250] unified_attention: call tdm.async_gather with the Triton 3.8 signature` | rocm | ? | - |
| - | [#7676](https://github.com/ROCm/aiter/pull/7676) `[Triton/Gluon] [gfx1250] fused_qk_norm_mrope_cache: fp8 KV cache` | perf,quant,rocm | ? | - |
| - | [#7677](https://github.com/ROCm/aiter/pull/7677) `[Triton/Gluon] [gfx1250] unified_attention 2D: bound gathered page ids by the sequence` | rocm | ? | - |
| - | [#7678](https://github.com/ROCm/aiter/pull/7678) `[Triton/Gluon] [gfx1250] fused_qk_norm_mrope_cache: A8K4V8 cache write (NVFP4 K, fp8 V)` | perf,quant,rocm | ? | - |
| - | [#7679](https://github.com/ROCm/aiter/pull/7679) `[FlyDSL][gfx1250] moe_topk_route_quant_prefill: TDM gather payload store, 16 waves` | quant,rocm | ? | - |
| P0 | [#7680](https://github.com/ROCm/aiter/pull/7680) `[Triton/Gluon] pa_prefill_sparse: single-pass gluon kernel for gfx950 at H=32 and 64` | perf,rocm | main | - |
| P1 | [#7681](https://github.com/ROCm/aiter/pull/7681) `[Triton/Gluon] mla_sparse_prefill: triton backend on gfx950, the default at H=32 without a sink` | rocm | ? | - |
| - | [#7684](https://github.com/ROCm/aiter/pull/7684) `[MoE] [gfx950] a16w4 rows with 16-row FlyDSL kernels for MiniMax-M3 TP8 and Kimi-K3 TP4 at 1-256 tokens` | perf,quant,rocm | ? | - |
| - | [#7685](https://github.com/ROCm/aiter/issues/7685) `[Issue]: On Windows, load_hip_runtime() loads the display driver's amdhip64.dll beside torch's HIP runtime` | rocm | ? | - |
| - | [#7686](https://github.com/ROCm/aiter/pull/7686) `[Triton/Gluon] [Perf] Tune MLA decode launch configuration for BF16 KV on gfx1100` | perf,rocm | ? | - |
| - | [#7687](https://github.com/ROCm/aiter/pull/7687) `[Triton] [Config] Add gfx1151 ff_a16w16_fused configs` | perf,rocm | ? | - |
| - | [#7688](https://github.com/ROCm/aiter/pull/7688) `[Config] [MoE] [gfx950] BF16 rows with a narrower block_m for Qwen3.6-35B-A3B and Kimi-Linear-48B-A3B` | rocm | ? | - |
| - | [#7689](https://github.com/ROCm/aiter/pull/7689) `[Triton] [Config] Add gfx1151 fused_reduce_add_rmsnorm config` | perf,rocm | ? | - |
| - | [#7690](https://github.com/ROCm/aiter/pull/7690) `[Config] [MoE] [gfx950] GLM-5.3-Flash FP8: 32768-tier rows from the tuned 16384 rows` | perf,quant,rocm | ? | - |
| - | [#7691](https://github.com/ROCm/aiter/pull/7691) `[Config] [MoE] [gfx950] MXFP4 TP1 rows for Qwen3.5-397B and Qwen3.8-2.4T from their TP2/TP4 FlyDSL rows` | quant,rocm | ? | - |
| - | [#7693](https://github.com/ROCm/aiter/pull/7693) `[FlyDSL] Add static-ring BF16 projection GEMM for gfx950` | rocm | ? | - |
| - | [#7697](https://github.com/ROCm/aiter/pull/7697) `[Triton/Gluon] [gfx1250] gemm_a16w16: add compute_bound_cluster kernel` | perf,rocm | ? | - |
| - | [#7698](https://github.com/ROCm/aiter/pull/7698) `[HIP] [FlyDSL] conv3d gfx1250: fold small-C convs, FlyDSL pre-transpose, three retuned rows` | perf,rocm | ? | - |
| - | [#7699](https://github.com/ROCm/aiter/pull/7699) `[FlyDSL] MegaMoEV2: enable, tune and speed up small_m / large_m for Kimi-K2.6 EP8 A8W4` | perf,rocm | ? | - |
| - | [#7703](https://github.com/ROCm/aiter/pull/7703) `[Triton] [Config] Add gfx1151 gemm_a16w16_persistent configs` | rocm | ? | - |
| - | [#7704](https://github.com/ROCm/aiter/pull/7704) `[Triton] [Config] Add gfx1150 gemm_a16w16_atomic configs` | rocm | ? | - |
| - | [#7705](https://github.com/ROCm/aiter/pull/7705) `[Triton] [Config] Add gfx1150 fused_reduce_add_rmsnorm config` | perf,rocm | ? | - |
| - | [#7707](https://github.com/ROCm/aiter/pull/7707) `[Triton] [Config] Add gfx1150 ff_a16w16_fused configs` | perf,rocm | ? | - |
| - | [#7711](https://github.com/ROCm/aiter/issues/7711) `Tracking issue for #7341: allowlist dtype bug + CI red on MoE 2-stage full-matrix job` | infra | ? | - |
| - | [#7712](https://github.com/ROCm/aiter/pull/7712) `[Config] [Perf] gfx950: tune a8w8 bpreshuffle GEMM for Qwen3-14B dense shapes` | perf,quant,rocm | ? | - |
| - | [#7714](https://github.com/ROCm/aiter/pull/7714) `[FlyDSL] Add hc_seam: fused hyper-connection gated-residual seam with finished next gate` | perf,rocm | ? | - |
| - | [#7718](https://github.com/ROCm/aiter/pull/7718) `[Triton/Gluon] [Perf] gfx950: tune the act_mul_and_fp8_group_quant launch (depends on #7231)` | infra,perf,quant,rocm | ? | - |
| - | [#7720](https://github.com/ROCm/aiter/pull/7720) `[JIT] [Bugfix] Config merge: catch live duplicates that differ only in _tag` |  | ? | - |
| - | [#7721](https://github.com/ROCm/aiter/pull/7721) `[CK] [Bugfix] MoE tuner: skip v2 stage-1 k_wave splits that do not divide K` | perf | ? | - |
| - | [#7722](https://github.com/ROCm/aiter/pull/7722) `[Triton/Gluon] [GFX12] MLA decode: partitioned-LDS kernel for H128 FP…` | perf,rocm | ? | - |
| - | [#7732](https://github.com/ROCm/aiter/pull/7732) `[Triton][MoE] Add a16w16 Triton stages to the fused_moe 2-stage dispatch` | perf,rocm | ? | - |
| - | [#7733](https://github.com/ROCm/aiter/pull/7733) `[Triton/Gluon] [HIP] [Perf] gfx1250: wave32 register top-k for MoE routing` | infra,perf,rocm | ? | - |
| - | [#7734](https://github.com/ROCm/aiter/pull/7734) `[Triton] [Config] Add gfx1201 gemm_a16w16_atomic configs` | rocm | ? | - |
| - | [#7735](https://github.com/ROCm/aiter/pull/7735) `[Build] Prebuild opus fwd and three more mha_varlen_fwd variants at PREBUILD_KERNELS=1` | infra,rocm | ? | - |
| - | [#7736](https://github.com/ROCm/aiter/pull/7736) `[JIT] [Bugfix] Exclude FP8 kernels from BF16 varlen attention builds` | perf,quant | ? | - |
| - | [#7737](https://github.com/ROCm/aiter/issues/7737) `[Issue]: Triton MHA backward kernels (flash_attn_triton_amd/bwd.py) compute offsets in int32, overflowing for ` | nvidia,perf,risk,rocm | ? | - |
| - | [#7738](https://github.com/ROCm/aiter/pull/7738) `[Triton] [Config] Add gfx1151 extend_attention config` | rocm | ? | - |
| - | [#7739](https://github.com/ROCm/aiter/pull/7739) `[HIP] fused_qk_rope_concat_and_cache_mla: cut decode latency on gfx1250` | infra,perf,rocm | ? | - |
| - | [#7740](https://github.com/ROCm/aiter/pull/7740) `[Triton] [Config] Add gfx1151 grouped GEMM (gmm / ptgmm / nptgmm) config` | rocm | ? | - |
| - | [#7741](https://github.com/ROCm/aiter/pull/7741) `Fix/jit runtime arch fullgraph` | bug | ? | - |
| - | [#7742](https://github.com/ROCm/aiter/pull/7742) `[Triton/Gluon] Cast strides to int64 in MHA backward kernels to prevent overflow` | perf,risk,rocm | main | - |
| - | [#7743](https://github.com/ROCm/aiter/pull/7743) `[Triton/Gluon] [Perf] [gfx1250] unified attention 3D: tuned split for plain bf16 and fp8 decode` | perf,quant,rocm | ? | - |
| - | [#7744](https://github.com/ROCm/aiter/pull/7744) `[Config] [gfx1250] gpt-oss prefill a8w4: 128x256x256, no cluster` | rocm | ? | - |
| - | [#7745](https://github.com/ROCm/aiter/pull/7745) `[Triton/Gluon] [Perf] [gfx1250] gluon UA2D: BLOCK_M 256 only when the batch has <= 8 sequences` | perf,rocm | ? | - |
| - | [#7746](https://github.com/ROCm/aiter/pull/7746) `[Triton/Gluon] [Perf] [gfx1250] RMSNorm forward: 4 programs per CU` | perf,rocm | ? | - |
| - | [#7749](https://github.com/ROCm/aiter/pull/7749) `[Triton/Gluon] [Config] [gfx950] unified_attention: 128-CU split values for head-64 window decode and verify` | rocm | ? | - |
| - | [#7750](https://github.com/ROCm/aiter/pull/7750) `[Bugfix] Fix wrong GLM-5 FP8 MoE output on gfx942 at 9-16 tokens` | bug,quant,rocm | ? | - |
| P1 | [#7752](https://github.com/ROCm/aiter/pull/7752) `[Perf] Retune gfx942 Qwen3.8-27B a8w8 blockscale decode rows for cold weights` | perf,quant,rocm | ? | - |
| - | [#7753](https://github.com/ROCm/aiter/pull/7753) `[CI] [Bugfix] perftest: time candidates on cold inputs regardless of num_iters and input size` | infra | ? | - |
| P1 | [#7754](https://github.com/ROCm/aiter/pull/7754) `[HIP] Mha v4: run the K-smoothing gate as one HIP call` | rocm | ? | - |
| - | [#7755](https://github.com/ROCm/aiter/pull/7755) `[Triton/Gluon] bench_sage: run mha4_mxfp8 --e2e through mha_v4` | perf,quant,rocm | ? | - |
| - | [#7757](https://github.com/ROCm/aiter/pull/7757) `[Triton/Gluon] bench_sage: hd256 producers for mha4_mxfp8` | perf,quant,rocm | ? | - |
| - | [#7761](https://github.com/ROCm/aiter/pull/7761) `[FlyDSL] Fuse a two-norm residual boundary into INT4 QuickReduce` | perf,quant,rocm | ? | - |
| - | [#7762](https://github.com/ROCm/aiter/pull/7762) `[Kimi-K3] Tune a8w8 bpreshuffle 6144x7168 prefill buckets on gfx950` | perf,quant,rocm | ? | - |
| - | [#7763](https://github.com/ROCm/aiter/pull/7763) `[Triton] [Config] Add gfx1151 mla_decode_rope config` | rocm | ? | - |
| - | [#7764](https://github.com/ROCm/aiter/pull/7764) `[JIT] Bind load_hip_runtime to the HIP runtime already loaded on Windows` | rocm | ? | - |
| - | [#7766](https://github.com/ROCm/aiter/pull/7766) `[Triton/Gluon] [gfx1250] unified_attention 3D: causal-mask only the tiles past safe_tile_end` | rocm | ? | - |
| - | [#7767](https://github.com/ROCm/aiter/pull/7767) `[Triton/Gluon] [JIT] gfx1250-strict enablment fixes` | rocm | ? | - |
| - | [#7768](https://github.com/ROCm/aiter/pull/7768) `[Triton/Gluon][gfx1250] gemm_a16w16: workgroup clusters on bandwidth_bound and compute_bound, sliced K on comp` | perf,rocm | ? | - |
| - | [#7770](https://github.com/ROCm/aiter/pull/7770) `[Triton/Gluon] Add gemm_a16w32: bf16 x fp32-weight GEMM (fp32 FMA at small M, bf16x3 MFMA above)` | rocm | ? | - |
| - | [#7771](https://github.com/ROCm/aiter/pull/7771) `[Triton/Gluon] [Feature] Fused MoE top-k combine + reduce-scatter for gfx950` | perf,rocm | ? | - |
| - | [#7772](https://github.com/ROCm/aiter/pull/7772) `[Config] [Perf] MiniMax-M3.1 MXFP8 GEMM tunings (gfx950)` | perf,quant,rocm | ? | - |
| - | [#7775](https://github.com/ROCm/aiter/issues/7775) `[VLLM] https://github.com/vllm-project/vllm/pull/64545` |  | ? | - |
| - | [#7776](https://github.com/ROCm/aiter/issues/7776) `[Issue]: test_triton_unified_attn_3d case never completes on gfx1250 and leaves the GPU busy` | rocm | ? | - |
| - | [#7777](https://github.com/ROCm/aiter/issues/7777) `[Issue]: pa_decode_sparse fp8 and v4-unified paths wrong at kv_len=136 on gfx1250; with_extra fails` | quant,rocm | ? | - |
| - | [#7778](https://github.com/ROCm/aiter/issues/7778) `[Issue]: gemm_afp4wfp4 preshuffled split-K raises KeyError NUM_BUFFERS on gfx1250` | rocm | ? | - |
| - | [#7779](https://github.com/ROCm/aiter/issues/7779) `[Issue]: test_mla_decode_pagesize64 fails instead of skipping on MI450 A0 (B0-only ASM)` |  | ? | - |
| - | [#7780](https://github.com/ROCm/aiter/issues/7780) `[Issue]: benchmark-style op_tests are not runnable under pytest (test_mhc argv, positional test_* sweeps)` | perf | ? | - |
| - | [#7781](https://github.com/ROCm/aiter/issues/7781) `[Issue]: test_mla_flydsl page-faults on gfx1250 when the GPU is initialized before aiter is imported` | rocm | ? | - |
| - | [#7782](https://github.com/ROCm/aiter/pull/7782) `[Triton] [Config] Add gfx1201 gemm_a16w16_persistent configs` | rocm | ? | - |
| - | [#7783](https://github.com/ROCm/aiter/pull/7783) `[MLA] [RFC #7240] Route mla_sparse_prefill_v41 through the kernel provider interface` | perf | ? | - |
| - | [#7785](https://github.com/ROCm/aiter/pull/7785) `[Config] Add gfx950 BF16 GEMM tunings for Muse Spark` | perf,rocm | ? | - |
| - | [#7786](https://github.com/ROCm/aiter/pull/7786) `[Triton/Gluon] unified_attention: mask the block-table read of partial tiles` | rocm | ? | - |
| P1 | [#7788](https://github.com/ROCm/aiter/pull/7788) `[FlyDSL] [CI] MegaMoEV2: one route plan for every path, shared arenas, and the DeepSeek-V4.1-Flash EP2 / EP4 /` | infra,perf,rocm | ? | - |
| - | [#7789](https://github.com/ROCm/aiter/pull/7789) `[Triton/Gluon] attn_res_gate: gfx1250 Gluon kernel that loads the rows with TDM` | perf,rocm | ? | - |
| - | [#7792](https://github.com/ROCm/aiter/pull/7792) `[Triton/Gluon] [Feature] Fused all-reduce + RMSNorm + MXFP8 quant for TP decode on gfx950` | perf,quant,rocm | ? | - |
| - | [#7795](https://github.com/ROCm/aiter/pull/7795) `[FlyDSL] Cache gfx1250 decode MoE gather routes within each wave` | perf,rocm | ? | - |
| - | [#7800](https://github.com/ROCm/aiter/pull/7800) `[Triton/Gluon] MoE: batch-invariant MXFP4 MoE forward (moe_mxfp4_bi)` | quant,rocm | ? | - |
| - | [#7805](https://github.com/ROCm/aiter/pull/7805) `[FlyDSL] [AOT] Assign into FakeTensor slices without reaching HIP on torch 2.9.1` | rocm | ? | - |
| - | [#7806](https://github.com/ROCm/aiter/pull/7806) `fused_moe: take a caller presort on moe_sorting-layout pipelines` | perf | ? | - |
| - | [#7808](https://github.com/ROCm/aiter/pull/7808) `custom all-reduce: MXFP8 mode for fused AR + RMSNorm + per-group quant` | perf,quant | ? | - |
| P1 | [#7810](https://github.com/ROCm/aiter/pull/7810) `[Comm] Prefetch gfx1250 TP4 PullQ4 peer loads; M3 prefill-serving A/B` | rocm | ? | - |
| - | [#7811](https://github.com/ROCm/aiter/issues/7811) `fmha_v3_varlen_fwd ASM kernel (fmha_fwd_hd128_bf16_causal_group) crashes with GPU memory access fault on paged` | bug,perf | ? | - |
| - | [#7815](https://github.com/ROCm/aiter/pull/7815) `[Triton/Gluon] [QSA] Add qsa_select_paged_groups for row-sharded selection` | rocm | ? | - |
| - | [#7816](https://github.com/ROCm/aiter/pull/7816) `[Recipe] Guarded M3 TP4 M16/M32 MoE decode overlays with serving A/B` |  | ? | - |
| - | [#7817](https://github.com/ROCm/aiter/pull/7817) `[Triton/Gluon] unified_attention: run causal=False on the gfx950 Gluon kernel` | perf,rocm | ? | - |
| P1 | [#7818](https://github.com/ROCm/aiter/pull/7818) `[HIP] Mega-MHC: faster large-M prefill (split tail for any T, ping-pong post tiles)` | perf,rocm | ? | - |
| - | [#7819](https://github.com/ROCm/aiter/pull/7819) `[FlyDSL] route sequence-parallel reduce-scatter / all-gather to INT4 by payload size` | quant,rocm | ? | - |
| P1 | [#7821](https://github.com/ROCm/aiter/pull/7821) `[Triton/Gluon] [HIP] [OPUS] FP8 DMA deepseek prefill` | quant,rocm | ? | - |
| P1 | [#7822](https://github.com/ROCm/aiter/pull/7822) `[MoE] [Bugfix] Give stage 1 only the padding columns its stage 2 skips` |  | ? | - |
| P1 | [#7823](https://github.com/ROCm/aiter/pull/7823) `[Triton/Gluon] [gfx950] Fix LDS WAR race in single-warp fp8_mqa_logits` | bug,risk,rocm | ? | - |
| - | [#7827](https://github.com/ROCm/aiter/pull/7827) `[FlyDSL] [gfx1250] DSv4.1 Flash 32x32 GEMMs: tune C1024 decode, prefetch a8w8/a4w4 compute kernel code` | perf,quant,rocm | ? | - |
| - | [#7830](https://github.com/ROCm/aiter/pull/7830) `[Triton] gemm_afp4wfp4: enable the software-emulated FP4 path on gfx1201` | quant,rocm | ? | - |
| - | [#7831](https://github.com/ROCm/aiter/pull/7831) `[Triton] [Config] Add gfx1201 fused_reduce_add_rmsnorm config` | perf,rocm | ? | - |
| - | [#7832](https://github.com/ROCm/aiter/pull/7832) `[Triton/Gluon] [Feature] Fused all-reduce + RMSNorm + MoE router + top-k + moe_sorting for TP decode on gfx950` | perf,rocm | ? | - |
| - | [#7834](https://github.com/ROCm/aiter/pull/7834) `[Bugfix] gfx1250 MLA decode: fix the NVFP4 KV cache's PV token order` | bug,perf,quant,rocm | ? | - |
| - | [#7835](https://github.com/ROCm/aiter/pull/7835) `[Feature] gfx1250 MLA: MXFP4 packed KV cache formats (writers and LDS-pipeline decode)` | perf,quant,rocm | ? | - |
| - | [#7836](https://github.com/ROCm/aiter/pull/7836) `[Triton/Gluon] [gfx1250] unified_attention: bound 2D gathered page ids by the sequence, fp8 configs for Qwen3.` | quant,rocm | ? | - |
| - | [#7838](https://github.com/ROCm/aiter/pull/7838) `[HIP] [Bugfix] topk_gating: distinct expert ids for rows with too few valid experts` | rocm | ? | - |
| - | [#7839](https://github.com/ROCm/aiter/pull/7839) `[FlyDSL] [Fix] Preserve inverse route map for gfx1250 TP A-preshuffle` | bug,rocm | ? | - |
| - | [#7840](https://github.com/ROCm/aiter/pull/7840) `fix: set _layout_ = "ms" on packed ctypes structs in mla_decode_v4 (Python 3.14 warning)` | bug | ? | - |
| - | [#7841](https://github.com/ROCm/aiter/pull/7841) `[Triton/Gluon] Add gfx1250 RMSNorm forward kernel using TDM + LDS` | perf,rocm | ? | - |
| - | [#7843](https://github.com/ROCm/aiter/pull/7843) `[Triton] [Config] Add gfx1201 ff_a16w16_fused configs` | perf,rocm | ? | - |
| - | [#7845](https://github.com/ROCm/aiter/pull/7845) `[Triton] [Config] Add gfx1201 grouped GEMM (gmm / ptgmm / nptgmm) config` | rocm | ? | - |
| - | [#7849](https://github.com/ROCm/aiter/pull/7849) `[CI] Re-enable single-node multi-GPU MoE tests` | infra | ? | - |
| - | [#7852](https://github.com/ROCm/aiter/pull/7852) `[Triton] [Config] Add gfx1201 mla_decode_rope config` | rocm | ? | - |
| - | [#7855](https://github.com/ROCm/aiter/pull/7855) `[FlyDSL] [gfx950] Batched mxfp8 GEMM: fused MXFP8 quant epilogue` | perf,quant,rocm | ? | - |
| - | [#7859](https://github.com/ROCm/aiter/pull/7859) `[FlyDSL] MegaMoE EP: expert-parallel MoE as one persistent kernel` | perf,rocm | ? | - |
| P1 | [#7864](https://github.com/ROCm/aiter/pull/7864) `[FlyDSL] [Perf] pa_decode: K/V streaming, MTP query split and sparse split-major on gfx950` | perf,rocm | ? | - |
| - | [#7867](https://github.com/ROCm/aiter/pull/7867) `[FlyDSL] MegaMoEV2 EP4 V4.1-Flash: fix the large-input scale-load fault, faster decode (into #7788)` | bug,perf,quant,rocm | ? | - |
| - | [#7868](https://github.com/ROCm/aiter/pull/7868) `[FlyDSL] [gfx1250] Compute GEMMs: cluster_m as a launch argument, DSv4.1 Flash prefill rows` | rocm | ? | - |
| - | [#7869](https://github.com/ROCm/aiter/pull/7869) `[FlyDSL] perf(flydsl): launch a repeated gfx1250 pa_decode call without re-checking it` | perf,rocm | ? | - |
| - | [#7870](https://github.com/ROCm/aiter/pull/7870) `[HIP] Add Muse Spark one-launch mega attention kernel (TP4, gfx950)` | perf,rocm | ? | - |
| - | [#7873](https://github.com/ROCm/aiter/pull/7873) `[Triton] [Config] Add gfx1201 extend_attention config` | rocm | ? | - |
| - | [#7876](https://github.com/ROCm/aiter/pull/7876) `[HIP] [Perf] Wave-per-head MLA reduce for wave32 (gfx1250) decode with few splits per tile` | perf,rocm | ? | - |
| P1 | [#7879](https://github.com/ROCm/aiter/pull/7879) `[FlyDSL] [Bugfix] Support gfx950 GEMM operands of 4 GiB or more` | rocm | ? | - |
| P1 | [#7880](https://github.com/ROCm/aiter/pull/7880) `[OPUS] [Bugfix] Fix unwritten output tiles in the gfx950 A16W16 GEMM` | bug,rocm | ? | - |
| - | [#7882](https://github.com/ROCm/aiter/pull/7882) `[CK] [Bugfix] Reject K that is not a multiple of the CKTile flatmm warp-tile K` |  | ? | - |
| P1 | [#7883](https://github.com/ROCm/aiter/pull/7883) `[ASM] [Bugfix] Make the bf16 and a4w4 ASM GEMMs exact past 4 GiB` | infra,quant,rocm | ? | - |
| - | [#7884](https://github.com/ROCm/aiter/pull/7884) `[Bugfix] Apply scale_a and scale_b in BF16 tgemm.mm instead of ignoring them` |  | ? | - |
| - | [#7887](https://github.com/ROCm/aiter/pull/7887) `[Triton/Gluon] [Config] [Perf] Retune gfx1250 96-CU Gluon bf16 GEMMs for Kimi-K2 TP8 prefill (M > 8192)` | perf,rocm | ? | - |
| - | [#7888](https://github.com/ROCm/aiter/pull/7888) `fused_moe: make fused_moe_2stages respect metadata.run_1stage` | perf | ? | - |
| - | [#7890](https://github.com/ROCm/aiter/pull/7890) `[FlyDSL] Remove padding copies from gfx1201 attention` | rocm | ? | - |
| - | [#7891](https://github.com/ROCm/aiter/pull/7891) `[Triton/Gluon] [GFX12] sparse_mla_fwd wiring for 640-B aligned format and sparse MLA prefill` | rocm | ? | - |
| - | [#7893](https://github.com/ROCm/aiter/pull/7893) `[Config] [gfx942] Qwen3.8-Flash-Next BF16 TP4 GEMM rows for 304 CUs` | rocm | ? | - |
| - | [#7894](https://github.com/ROCm/aiter/pull/7894) `[OPUS] [Bugfix] Refuse A16W16 operands of 4 GiB or more on kernels without 64-bit addressing` | perf | ? | - |
| - | [#7895](https://github.com/ROCm/aiter/pull/7895) `[FlyDSL] [Perf] Use transposed V loads in gfx1201 Flash Attention` | perf,rocm | ? | - |
| - | [#7898](https://github.com/ROCm/aiter/pull/7898) `[Triton/Gluon] [gfx942] sparse_mla_dsv4_train: retune the forward config` | infra,perf,rocm | ? | - |
| - | [#7899](https://github.com/ROCm/aiter/pull/7899) `[Triton/Gluon] sparse_mla_dsv4_train: chunked backward with fp32 dQ` | infra,rocm | ? | - |
| - | [#7900](https://github.com/ROCm/aiter/pull/7900) `[Triton/Gluon] : [PA_DECODE] Add rot_bufs and do_bench_aiter_triton support` | perf,rocm | ? | - |
| - | [#7901](https://github.com/ROCm/aiter/pull/7901) `[ASM] Tune conc 256 and 128 for qwen3.8-flash` | perf | ? | - |
| P1 | [#7902](https://github.com/ROCm/aiter/pull/7902) `[Triton/Gluon] Tune gfx1250 Gluon A4W4 MoE prefill GEMM1 BLOCK_N` | perf,quant,rocm | ? | - |
| - | [#7904](https://github.com/ROCm/aiter/pull/7904) `[FlyDSL] Prune gfx1250 TDM GEMM tuning search space` | perf,rocm | ? | - |
| P1 | [#7905](https://github.com/ROCm/aiter/pull/7905) `[Triton/Gluon] gfx950: recover three regressions from the LLVM 18f9e623 bump` | bug,infra,rocm | ? | - |
| - | [#7906](https://github.com/ROCm/aiter/pull/7906) `[Triton/Gluon] Flashkda k2 pipelined pass a doc` | rocm | ? | - |
| - | [#7907](https://github.com/ROCm/aiter/pull/7907) `[Triton/Gluon] [Config] [gfx1250] Drop ambiguous no-B batched_gemm_bf16 decode configs` | rocm | ? | - |
| - | [#7909](https://github.com/ROCm/aiter/pull/7909) `[ASM] [HIP] fix(mla): use native MI350 Q32 kernel for BF16 QH128` | bug,perf,rocm | ? | - |
| P0 | [#7910](https://github.com/ROCm/aiter/pull/7910) `[Triton] [Bugfix] gemm_afp4wfp4: run short K loops with a masked tail unpipelined on gfx950` | rocm | main | - |
| - | [#7911](https://github.com/ROCm/aiter/pull/7911) `[CI] [Build] [DO NOT MERGE] Use amd-triton/amd-triton-kernels from public pypi` | infra,perf,rocm | ? | - |
| - | [#7913](https://github.com/ROCm/aiter/pull/7913) `[FlyDSL] [gfx1250] MLA PS1: take 32/64-head multi-token decode as several qo tiles` | rocm | ? | - |
| - | [#7914](https://github.com/ROCm/aiter/pull/7914) `[HIP] [gfx1250] MLA reduce: run kn_mla_reduce_v1_wide on wave32 GPUs` | rocm | ? | - |
| - | [#7916](https://github.com/ROCm/aiter/pull/7916) `[Triton/Gluon] Optimize gfx1250 KDA decode with cached launch and packed write-back` | perf,rocm | ? | - |
| - | [#7917](https://github.com/ROCm/aiter/pull/7917) `[FlyDSL] MoE v2 stage 2: skip the inter_dim padding` | rocm | ? | - |
| - | [#7918](https://github.com/ROCm/aiter/pull/7918) `[FlyDSL] MoE stage 1: XCD remap over the valid rows only` | rocm | ? | - |
| - | [#7921](https://github.com/ROCm/aiter/pull/7921) `[FlyDSL] [gfx1250] grouped MoE GEMM1 opts into mega` | rocm | ? | - |
| - | [#7923](https://github.com/ROCm/aiter/pull/7923) `[FlyDSL] pa_decode: MXFP4 K/V on gfx1250 (MTP, sliding window, query splits)` | quant,rocm | ? | - |
| - | [#7929](https://github.com/ROCm/aiter/pull/7929) `[FlyDSL] Reduce gfx1250 TDM split-K synchronization overhead and pipeline NT operands` | rocm | ? | - |
| - | [#7931](https://github.com/ROCm/aiter/pull/7931) `[FlyDSL] gfx950 ring GEMM for the DSv4.1 router (16384x384x5120 BF16)` | rocm | ? | - |
| - | [#7932](https://github.com/ROCm/aiter/pull/7932) `[Tuning] Add MiMo V2.6 A8W8 prefill configs for gfx950` | perf,quant,rocm | ? | - |
| - | [#7933](https://github.com/ROCm/aiter/pull/7933) `[OPUS] Add gfx950 opus a16w16 NT/NN/TT/TN layout gemm` | rocm | ? | - |
| - | [#7934](https://github.com/ROCm/aiter/pull/7934) `[ASM] Update gfx1250 MLA V4.1 kernel` | perf,rocm | ? | - |
| - | [#7935](https://github.com/ROCm/aiter/pull/7935) `[ASM] [TEST] Cover V4.1 sliding windows and use host-selected benchmark splits` | perf | ? | - |
| - | [#7936](https://github.com/ROCm/aiter/pull/7936) `[HIP] [Bugfix] Return per-row quant vectors by value instead of dangling pointers` | quant,rocm | ? | - |
| - | [#7937](https://github.com/ROCm/aiter/pull/7937) `[HIP] perf(custom_ar): gfx1250 two-shot all-reduce moves 16-byte Lamport lines` | perf,rocm | ? | - |
| - | [#7938](https://github.com/ROCm/aiter/pull/7938) `[HIP] Generate MXFP4 MoE aux kernels for (64, 4096, 4096, 2)` | perf,quant,rocm | ? | - |
| - | [#7940](https://github.com/ROCm/aiter/pull/7940) `[FlyDSL] [MoE] Use streaming loads for large FP8 stage-2 reductions` | quant,rocm | ? | - |
| - | [#7941](https://github.com/ROCm/aiter/pull/7941) `[ASM] [gfx950] Add single-launch fused TP MXFP4/MXFP8 MoE + device-SDMA op` | perf,quant,rocm | ? | - |
| - | [#7942](https://github.com/ROCm/aiter/pull/7942) `Mha v4: kv_splits="auto" from a wave-rounding cost model` |  | ? | - |
| - | [#7945](https://github.com/ROCm/aiter/pull/7945) `Implement Per-token Quant on Gluon All-reduce` | quant,rocm | ? | - |
| - | [#7946](https://github.com/ROCm/aiter/pull/7946) `[gfx1250] [Perf] FP8 varlen ASM prefill: split the keys of a non-causal call that underfills the GPU` | perf,quant,rocm | ? | - |
| P1 | [#7949](https://github.com/ROCm/aiter/pull/7949) `[FlyDSL] MoE stage 2: fix the fp8 route-out scale group for tile_n=128` | bug,quant,rocm | ? | - |
| - | [#7950](https://github.com/ROCm/aiter/pull/7950) `[FlyDSL] MoE reduce: drop padded (negative topk id) slots` | rocm | ? | - |
| - | [#7951](https://github.com/ROCm/aiter/pull/7951) `gfx1250: HIP kernel for the KDA ReplaySSM decode / verify step` | perf,rocm | ? | - |
| - | [#7952](https://github.com/ROCm/aiter/pull/7952) `[Triton/Gluon] [Bugfix] fused_qk_rope_cat_and_cache_mla: Use 64-bit row and head offsets to avoid int32 overfl` | perf,risk,rocm | ? | - |

### aiter — Closed unmerged (1 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#7351](https://github.com/ROCm/aiter/pull/7351) `[FlyDSL] [Bugfix] Fix first-entry corruption in fused_compress_attn` | bug,perf,risk,rocm | main | - |

### vLLM — Merged / closed (849 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#31624](https://github.com/vllm-project/vllm/issues/31624) `[Bug]: ModelOpt Llama-4 Checkpoints Take 5+ minutes to load` | bug | ? | - |
| - | [#32588](https://github.com/vllm-project/vllm/issues/32588) `[Bug]: Wrong timestamps if audio > 30s` | bug | ? | - |
| - | [#38693](https://github.com/vllm-project/vllm/issues/38693) `[Feature]: Parity with CUDA: vLLM router should have ROCm CI` | infra,nvidia,rocm | ? | - |
| - | [#39479](https://github.com/vllm-project/vllm/issues/39479) `[torch.compile] config hashing refactor follow-ups` |  | ? | - |
| - | [#42186](https://github.com/vllm-project/vllm/issues/42186) `[Bug][flashinfer 0.6.8]: worker hang on Qwen3.5-397B-A17B-NVFP4 EP=8 (B200 SM100) - bisected to flashinfer-pyt` | bug,nvidia,quant | ? | - |
| - | [#42390](https://github.com/vllm-project/vllm/issues/42390) `[Bug]: Gemma-4 MoE Initialization Hang and Segfault` | bug,risk | ? | - |
| - | [#42659](https://github.com/vllm-project/vllm/issues/42659) `[RFC]: Per-Layer Parallelism Policy` |  | ? | - |
| - | [#42744](https://github.com/vllm-project/vllm/issues/42744) `[Bug]: rejection sampler skips argmax-invariant procs — patching the min_p/logit_bias 400 alone is insufficien` |  | ? | - |
| - | [#42821](https://github.com/vllm-project/vllm/issues/42821) `[Bug]: `model.load_weights` silently corrupts MoE forward on second call` | bug,risk | ? | - |
| - | [#42837](https://github.com/vllm-project/vllm/pull/42837) `[feature] shuffle safetensor weight files` |  | ? | - |
| - | [#43765](https://github.com/vllm-project/vllm/issues/43765) `[Feature]: Support PD disaggregation / KV transfer for hybrid SSM/GDN models such as Qwen3.5-397B-A17B-W8A8` | quant | ? | - |
| - | [#43885](https://github.com/vllm-project/vllm/issues/43885) `[Bug]: Qwen3.6-27B-FP8 on GB10: get_output() spin-loop on stuck CUDA stream during prefill burst (run<6, KV<5%` | bug,nvidia,quant | ? | - |
| - | [#43916](https://github.com/vllm-project/vllm/issues/43916) `[Parity with CUDA]: Add top 5-10 popular OSS models into mi355, mi325, mi300 into vLLM nightly performance  & ` | bug,nvidia,perf,risk,rocm | ? | - |
| - | [#44290](https://github.com/vllm-project/vllm/issues/44290) `[Feature]: Improving NVFP4 Quantization via Fast and Accurate Sweep on FP8 Block Scale` | quant | ? | - |
| - | [#44486](https://github.com/vllm-project/vllm/issues/44486) `[Bug]: vllm process crashed because of dp coordinator receives unexpected message which send by safety scan so` | bug | ? | - |
| - | [#44882](https://github.com/vllm-project/vllm/issues/44882) `[Feature]: Avoid duplicate KV block allocation for shared external-prefix hits` |  | ? | - |
| - | [#45268](https://github.com/vllm-project/vllm/issues/45268) `[Bug]: EngineDeadError after first L1 sleep/wake cycle with --kv-offloading-backend native + --enable-sleep-mo` |  | ? | - |
| - | [#45293](https://github.com/vllm-project/vllm/issues/45293) `[Bug]:GGUF model crashes API on v0.22 with T4 GPU (worked on v0.21)` | bug,quant | ? | - |
| - | [#45317](https://github.com/vllm-project/vllm/issues/45317) `[Feature/Gap] DSA models (GLM-5.1 / DeepSeek-V3.2-family, use_sparse=True) cannot select any attention backend` | nvidia | ? | - |
| - | [#45405](https://github.com/vllm-project/vllm/issues/45405) `[RFC]: Forward ReqContext from CPUOffloadingManager to CachePolicy for session-aware KV eviction` |  | ? | - |
| - | [#45647](https://github.com/vllm-project/vllm/issues/45647) `[Bug]: nvidia/Kimi-K2.6-nvfp4 & v0.23.0 cannot find huggingface downloader file` | bug,nvidia,quant | ? | - |
| - | [#45847](https://github.com/vllm-project/vllm/issues/45847) `[Bug]: Kimi-K2.6 VIT attention dispatch asserts on SM120 in flash_fwd_sm100` | nvidia | ? | - |
| - | [#45861](https://github.com/vllm-project/vllm/issues/45861) `[Feature]: Performance Optimization for Deepseek V4` | perf | ? | - |
| - | [#46221](https://github.com/vllm-project/vllm/issues/46221) `[Feature]: Add a 2-bit KV-cache quantisation backend from Together AI` | perf,quant | ? | - |
| - | [#46558](https://github.com/vllm-project/vllm/pull/46558) `[Bugfix][Attention] Enable FlashInfer mm-prefix attention` | bug,nvidia | ? | - |
| - | [#46613](https://github.com/vllm-project/vllm/issues/46613) `[RFC]: KVarN: a calibration-free, variance-normalized sub-8-bit KV-cache quantization backend` | perf,quant | ? | - |
| - | [#46631](https://github.com/vllm-project/vllm/issues/46631) `[Bug]: Multimodal image inputs fail on /v1/responses while identical inputs work on /v1/chat/completions` | bug | ? | - |
| - | [#46641](https://github.com/vllm-project/vllm/issues/46641) `[Bug]: gpt-oss-20b NVFP4 inference is broken` | bug,quant | ? | - |
| - | [#46871](https://github.com/vllm-project/vllm/pull/46871) `[XPU] All-to-all Expert-Parallellism backend for batched MoE` | nvidia,perf | ? | - |
| - | [#46985](https://github.com/vllm-project/vllm/issues/46985) `[Bug]: Why does kv-cache-dtype=fp8 OOM more easily than bf16/fp16 on long-context GLM-5.1-AWQ runs?` | bug,perf,quant | ? | - |
| - | [#47264](https://github.com/vllm-project/vllm/issues/47264) `[RFC]: Qwen3-ASR pseudo-streaming can repeat or miss segments` |  | ? | - |
| - | [#47430](https://github.com/vllm-project/vllm/issues/47430) `[Bug]: vllm==0.23.0 Qwen3.6-27B, system prompt same in multi requests, But prefix cache failure.` | bug,perf | ? | - |
| - | [#47547](https://github.com/vllm-project/vllm/pull/47547) `[Model] Use FlashInfer for Gemma 4 with an NVFP4 KV cache when FA4 is unavailable` | nvidia,perf,quant | ? | - |
| - | [#47582](https://github.com/vllm-project/vllm/issues/47582) `[RFC]: Opt-in incremental prompt encoding for multi-turn chat` |  | ? | - |
| - | [#47600](https://github.com/vllm-project/vllm/issues/47600) `[Bug]: ValueError: The supplied chat template string (examples/tool_chat_template_gemma4.jinja) appears path-l` | bug,rocm | ? | - |
| - | [#47620](https://github.com/vllm-project/vllm/issues/47620) `[Bug]: collect_env.py crashes on Windows/macOS and pip-less uv environments` | bug | ? | - |
| - | [#47626](https://github.com/vllm-project/vllm/issues/47626) `[Bug]: RuntimeError: scheduler_metadata must have shape (metadata_size) when using dspark speculative decoding` | bug,quant | ? | - |
| - | [#47651](https://github.com/vllm-project/vllm/issues/47651) `[Bug]: `vllm bench sweep serve_workload` crashes with "non-positive request rate" when max throughput < 1 req/` | bug,perf | ? | - |
| - | [#47652](https://github.com/vllm-project/vllm/pull/47652) `[Security][Model] Preserve Gemma audio frame dimensions and unified token counts` |  | ? | - |
| - | [#47684](https://github.com/vllm-project/vllm/issues/47684) `[RFC]: FlashInfer NVFP4 KV serving on pre-SM100 GPUs` | nvidia,quant | ? | - |
| - | [#47746](https://github.com/vllm-project/vllm/issues/47746) `[Bug]: AnthropicContentBlock missing per-type field validation for tool_use blocks` | bug | ? | - |
| - | [#47749](https://github.com/vllm-project/vllm/issues/47749) `[Bug]: RTX 5090 / SM120 ModelOpt mixed NVFP4 checkpoint falls back to Marlin W4A16 path and warns no native FP` | bug,nvidia,quant | ? | - |
| P1 | [#47763](https://github.com/vllm-project/vllm/issues/47763) `[Performance]: MiniMax-M3 verify-as-decode re-streams the sparse KV from HBM once per draft token` | perf | ? | - |
| - | [#47768](https://github.com/vllm-project/vllm/issues/47768) `[RFC]: vLLM gRPC server API for downstream integrations` |  | ? | - |
| P1 | [#47783](https://github.com/vllm-project/vllm/issues/47783) `[Bug]: DSV4 sparse MLA emits garbage (gsm8k ~0%) with the packed KV layout from #44577` | bug,risk | ? | - |
| - | [#47788](https://github.com/vllm-project/vllm/issues/47788) `[Bug]: Qwen3-Omni use_audio_in_video via --mm-processor-kwargs is broken in online serving: engine crash at st` | bug,risk | ? | - |
| - | [#47802](https://github.com/vllm-project/vllm/issues/47802) `[Feature]: Priority scheduling is not reflected in KV/prefix cache retention under cache pressure` | perf | ? | - |
| - | [#47846](https://github.com/vllm-project/vllm/issues/47846) `[Feature]: model runner v2 support prefill context parallelism & cp8+tp8=worldsize8` |  | ? | - |
| P1 | [#47847](https://github.com/vllm-project/vllm/issues/47847) `[Bug]: disable_flashinfer_q_quantization + fp8 KV + spec decode silently corrupts sliding-window models on SM1` | nvidia,quant,risk | ? | - |
| - | [#47918](https://github.com/vllm-project/vllm/issues/47918) `[Bug]: V1 + Ray distributed executor + LoRA — execute_model returns NoneType on NVIDIA GPU` | nvidia | ? | - |
| - | [#47919](https://github.com/vllm-project/vllm/issues/47919) `[RFC]   guard-gated sparse MLA topology index policy` |  | ? | - |
| - | [#47974](https://github.com/vllm-project/vllm/issues/47974) `[Bug]: vllm 校验arguments合法性` | bug | ? | - |
| - | [#47982](https://github.com/vllm-project/vllm/issues/47982) `[Bug]: flashinfer_b12x MoE broken after PR #43328: "num_tokens exceeds max_num_tokens" with dp_size>1 and OOM ` | bug,nvidia | ? | - |
| - | [#48005](https://github.com/vllm-project/vllm/issues/48005) `[Bug]: VLLM concurrent requests: the last request does not return` | bug | ? | - |
| - | [#48029](https://github.com/vllm-project/vllm/issues/48029) `[RFC]: Composite Attention Backends` |  | ? | - |
| P1 | [#48043](https://github.com/vllm-project/vllm/issues/48043) `[Bug][ROCm] Triton kernel_paged_attention_2d illegal memory access (hipErrorLaunchFailure) on gfx950 (MI350X) ` | bug,perf,risk,rocm | ? | - |
| - | [#48066](https://github.com/vllm-project/vllm/issues/48066) `[Performance]: Marlin MoE block_size_m heuristic over-selects a large M-tile for expert-parallel decode (up to` | perf,quant | ? | - |
| - | [#48077](https://github.com/vllm-project/vllm/issues/48077) `[Usage]: Does it support the deployment of P node TEP and D node DEP modes` |  | ? | - |
| - | [#48080](https://github.com/vllm-project/vllm/issues/48080) `[RFC]: Confident Decoding — entropy-guided intermediate-layer logits selection` |  | ? | - |
| - | [#48082](https://github.com/vllm-project/vllm/issues/48082) `[Bug]: Gemma-4 MTP crashes on B200 after FlashInfer selects a missing head_dim=512 TRTLLM-Gen cubin` | bug,nvidia | ? | - |
| - | [#48106](https://github.com/vllm-project/vllm/issues/48106) `[Feature]: PrefillDelayer for performant DPA` | rocm | ? | - |
| - | [#48147](https://github.com/vllm-project/vllm/issues/48147) `[RFC]: Optimizing Asynchronous Stream Serialization in OpenAI API Entrypoint` | perf | ? | - |
| - | [#48148](https://github.com/vllm-project/vllm/issues/48148) `[RFC]: Remove Group Activation Ordering (actorder=group) Support from vLLM and Compression Libraries` |  | ? | - |
| - | [#48172](https://github.com/vllm-project/vllm/issues/48172) `[Feature]: Prefix LM kernel on ROCm_ATTN` | perf,rocm | ? | - |
| - | [#48191](https://github.com/vllm-project/vllm/issues/48191) `[Feature]: [Parity with AMD SGLang] MoRI UMBP Offloading support` | rocm | ? | - |
| - | [#48207](https://github.com/vllm-project/vllm/issues/48207) `[Bug]: Analysis for an Automated Request Validation and Normalization Module at the Upstream of vLLM (Hard Int` | bug | ? | - |
| - | [#48208](https://github.com/vllm-project/vllm/issues/48208) `[Feature]:  Proposal for an Automated Request Validation and Normalization Module at the Upstream of vLLM (Har` |  | ? | - |
| - | [#48224](https://github.com/vllm-project/vllm/issues/48224) `[Bug]: KV connector "Throughput (MB/s)" sums overlapping transfer durations; propose reporting avg per-transfe` | perf | ? | - |
| - | [#48229](https://github.com/vllm-project/vllm/issues/48229) `V1 multiprocess engine: sporadic 0.7-2s frozen engine step once per generate batch (absent with VLLM_ENABLE_V1` |  | ? | - |
| - | [#48231](https://github.com/vllm-project/vllm/issues/48231) `[Bug]: Gemma4 Unified image requests produce all-NaN logits after BF16-to-FP16 fallback` | bug,risk | ? | - |
| - | [#48236](https://github.com/vllm-project/vllm/issues/48236) `LMCache + vLLM: pipeline parallelism now works with MLA models (Kimi K2, GLM-4.6)` |  | ? | - |
| - | [#48238](https://github.com/vllm-project/vllm/issues/48238) `[Bug]: Gemma4 dense NVFP4 (nvidia/Gemma-4-31B-IT-NVFP4) fails on v0.24.0 with NotImplementedError in quant_met` | bug,nvidia,quant | ? | - |
| - | [#48242](https://github.com/vllm-project/vllm/issues/48242) `[Feature]: Operator opt-out for the expandable_segments KV-connector rejection (copy-based connectors have no ` |  | ? | - |
| - | [#48274](https://github.com/vllm-project/vllm/issues/48274) `[Bug][Responses API] Zero-delta streaming items skip added/in_progress lifecycle events` |  | ? | - |
| - | [#48277](https://github.com/vllm-project/vllm/issues/48277) `Platform plugin registration failures are silently swallowed, causing undiagnosed CPU fallback` | risk | ? | - |
| - | [#48283](https://github.com/vllm-project/vllm/issues/48283) `[Feature]: Folding per-platform default arguments into the vLLM engine` |  | ? | - |
| - | [#48285](https://github.com/vllm-project/vllm/issues/48285) `TRITON_MLA_SPARSE fallback crashes on SM80 during CUDA graph capture` | bug,nvidia | ? | - |
| - | [#48319](https://github.com/vllm-project/vllm/issues/48319) `[Bug]: Responses API: explicit "background": null or "truncation": null fails response construction (confusing` | perf,risk | ? | - |
| - | [#48332](https://github.com/vllm-project/vllm/issues/48332) `[Bugfix] Dynamic video sampling should reject invalid video metadata before decoding` |  | ? | - |
| - | [#48380](https://github.com/vllm-project/vllm/issues/48380) `[Bug]: DSpark/DFlash speculative decoding fails to load with --kv-cache-dtype fp8_ds_mla: draft inherits an ML` | perf | ? | - |
| - | [#48401](https://github.com/vllm-project/vllm/issues/48401) `[Bug]: Prefix caching silently inert on hybrid Mamba2 models when max_model_len < auto-selected block size` | risk | ? | - |
| - | [#48405](https://github.com/vllm-project/vllm/issues/48405) `[Bug]: glm-5.2-fp8 with --kvcache-dtype fp8 with h20-3e error` | bug,quant | ? | - |
| - | [#48406](https://github.com/vllm-project/vllm/issues/48406) `[Bug]: glm-5.2-fp8 with --kvcache-dtype fp8 with h20-3e with dspark error` | bug,quant | ? | - |
| - | [#48423](https://github.com/vllm-project/vllm/issues/48423) `[Bug]: MiniCPM-V-4.6 fails to load in vLLM 0.25.0: qkv_proj is incorrectly mapped to qkqkv_proj` | bug | ? | - |
| - | [#48441](https://github.com/vllm-project/vllm/issues/48441) `[Bug]: Local PP Rank0 stalls in legacy non-SPMD Ray AsyncLLMEngine under imbalanced pipeline stages` | bug | ? | - |
| - | [#48455](https://github.com/vllm-project/vllm/issues/48455) `HybridKVCacheCoordinator: DSpark draft-model KV-cache group's ephemeral content incorrectly vetoes GPU-tier pr` | perf | ? | - |
| - | [#48465](https://github.com/vllm-project/vllm/issues/48465) `[Bug]: deepseek-v4-pro-dspark --max-num-batched-tokens 16384 no use` | bug | ? | - |
| - | [#48486](https://github.com/vllm-project/vllm/issues/48486) `[Bug]: Hang in CUDA Graph replay with PyTorch symmetric-memory all-reduce when profiling with Nsight Systems` | bug,nvidia | ? | - |
| - | [#48489](https://github.com/vllm-project/vllm/issues/48489) `[Bug]: Deferred block-free path loses per-group eviction ordering for hybrid KV cache configs` | bug,perf | ? | - |
| - | [#48492](https://github.com/vllm-project/vllm/issues/48492) `[Bug]: Missing quant_config in MTP eh_proj causes severe silent precision loss during W8A8 quantization` | bug,quant,risk | ? | - |
| - | [#48503](https://github.com/vllm-project/vllm/issues/48503) `[Bug]: Gemma 4 MTP speculative decoding crashes during CUDA graph capture (`_suppress_token_ids` is a Python l` | bug,nvidia | ? | - |
| - | [#49459](https://github.com/vllm-project/vllm/pull/49459) `[Model Loader] Remove per-load completeness checks` | quant | ? | - |
| - | [#49529](https://github.com/vllm-project/vllm/issues/49529) `[Perf][Kernel] Adopt PTX 9.4 `ldmatrix.s8.s4` (hardware INT4→INT8 expanding load) in W4A8-INT8 paths` | perf,quant | ? | - |
| - | [#49539](https://github.com/vllm-project/vllm/pull/49539) `[Bugfix][Quantization] Keep unquantized routed experts unquantized under AutoGPTQ` | bug,quant,rocm | ? | - |
| - | [#50265](https://github.com/vllm-project/vllm/pull/50265) `[Feature] add the option to continue serving unfinished requests after the recovery` |  | ? | - |
| - | [#50449](https://github.com/vllm-project/vllm/pull/50449) `[ROCm] Unify ViT FlashAttention backend selection` | infra,rocm | ? | - |
| - | [#50738](https://github.com/vllm-project/vllm/issues/50738) `[RFC]: Dual Batch Overlap (DBO) for Model Runner V2` | perf | ? | - |
| - | [#50788](https://github.com/vllm-project/vllm/issues/50788) `[Feature][Gemma4]: Allow configuring max_soft_tokens for video frames` |  | ? | - |
| - | [#50961](https://github.com/vllm-project/vllm/issues/50961) `[Bug]: GraniteMoeHybrid fails to load with pipeline_parallel_size > 1 (KeyError on another rank's layer)` |  | ? | - |
| - | [#51006](https://github.com/vllm-project/vllm/pull/51006) `[MoE] Make fused MoE routers pluggable` | perf | ? | - |
| - | [#51205](https://github.com/vllm-project/vllm/issues/51205) `[Bug]:  Inkling-Small-NVFP4 wont start on 2 H200 GPUs.` | bug,nvidia,quant | ? | - |
| - | [#51441](https://github.com/vllm-project/vllm/issues/51441) `[Bug]: Hybrid sparse attention + Eagle results in full cache miss for certain prompt lengths` | bug,perf | ? | - |
| - | [#51465](https://github.com/vllm-project/vllm/issues/51465) `[Bug]: Kimi K3 usage.prompt_tokens over-counts trailing channel-open stub (+3)` | bug | ? | - |
| - | [#51859](https://github.com/vllm-project/vllm/pull/51859) `[Frontend] Honour --host for the run-batch Prometheus metrics server` |  | ? | - |
| - | [#51951](https://github.com/vllm-project/vllm/pull/51951) `[Bugfix][Model] Fix Inkling NVIDIA sconv cache block-size mismatch` | bug,nvidia,perf | ? | - |
| - | [#52051](https://github.com/vllm-project/vllm/issues/52051) `[Bug]: gpt-oss-120b MXFP4 + --enable-expert-parallel crashes at startup: modular MoE finalize allocates padded` | bug,quant | ? | - |
| - | [#52652](https://github.com/vllm-project/vllm/pull/52652) `[Perf][Kernel][Quantization] Tensor-descriptor path for int4 fused_moe_kernel_gptq_awq (XPU default, sm100 opt` | infra,nvidia,perf,quant | ? | - |
| - | [#52738](https://github.com/vllm-project/vllm/issues/52738) `[Feature]: Map unsupported reasoning_effort values to the nearest level the chat template accepts` | quant | ? | - |
| P1 | [#52833](https://github.com/vllm-project/vllm/issues/52833) `[Bug]: GLM-5.2 MTP accepts 0% of drafts on MI355X (gfx950); disabling expert parallelism hits hipErrorIllegalA` | rocm | ? | - |
| - | [#52875](https://github.com/vllm-project/vllm/pull/52875) `[Perf][Frontend] Render plain completion stream deltas from a template` | perf | ? | - |
| - | [#53369](https://github.com/vllm-project/vllm/pull/53369) `[Bugfix][Frontend] Match default MM LoRA for OpenAI input_audio parts` | bug | ? | - |
| - | [#53488](https://github.com/vllm-project/vllm/issues/53488) `[Bug]: `prompt_logprobs` silently corrupted for some requests when MTP speculative decoding is enabled (Qwen3.` | quant,risk | ? | - |
| - | [#54548](https://github.com/vllm-project/vllm/pull/54548) `[Bugfix][Frontend] Keep is_embed when round-tripping rendered placeholders` | bug | ? | - |
| - | [#54555](https://github.com/vllm-project/vllm/issues/54555) `[Bug]: V1 spec-decode proposer never constructs the positions buffer a both-XD-RoPE drafter seeds from` |  | ? | - |
| - | [#54737](https://github.com/vllm-project/vllm/pull/54737) `[Doc] Fix stale attention_kernels.cu reference in paged_attention.md` | bug,infra | ? | - |
| - | [#54761](https://github.com/vllm-project/vllm/issues/54761) `[Bug]: On ROCm, DCP and non-FP8 KV dtypes are unreachable, but the errors suggest fixes that don't exist there` | quant,rocm | ? | - |
| P1 | [#54775](https://github.com/vllm-project/vllm/issues/54775) `[Bug]: KDA/gated-delta-rule chunked-scan buffers are outside memory profiling — runtime OOM at large --max-num` | rocm | ? | - |
| - | [#54820](https://github.com/vllm-project/vllm/pull/54820) `[ROCm] Avoid DSpark placeholder shared vocab allocations` | rocm | ? | - |
| - | [#54843](https://github.com/vllm-project/vllm/issues/54843) `[Bug][CPU][Spec Decode]: --use-fp64-gumbel silently ignored in CPU recovered-token sampling (inv_q downcast to` | risk | ? | - |
| - | [#54899](https://github.com/vllm-project/vllm/pull/54899) `[ROCm][MLA][DCP] Pad the AITER MLA decode head count to a native tile` | infra,rocm | ? | - |
| - | [#55005](https://github.com/vllm-project/vllm/issues/55005) `[Bug][CPU][Spec Decode]: CPU expand_kernel shim discards its output — non-greedy spec decode consumes uninitia` |  | ? | - |
| - | [#55050](https://github.com/vllm-project/vllm/issues/55050) `[Bug]: encoder prompt embeddings trigger a compiled AttributeError` | bug | ? | - |
| - | [#55229](https://github.com/vllm-project/vllm/pull/55229) `[Bugfix][DP] Prevent mismatched collectives on duplicate resume` | bug | ? | - |
| - | [#55233](https://github.com/vllm-project/vllm/pull/55233) `[Bugfix] Reject prompt embeddings for BERT/RoBERTa models` | bug | ? | - |
| - | [#55383](https://github.com/vllm-project/vllm/issues/55383) `AOT compile cache key ignores the LoRA module tree, loading an incompatible artifact (`KeyError: 'weight'`)` | perf | ? | - |
| - | [#55387](https://github.com/vllm-project/vllm/pull/55387) `[CI/Build] Move the default CUDA build from 13.0 to 13.2` | infra,nvidia | ? | - |
| - | [#55518](https://github.com/vllm-project/vllm/issues/55518) `[Bug]: kv_cache_utils warns that prefix-cache reuse is disabled even when disable_eagle_block_drop keeps it wo` | perf | ? | - |
| - | [#55581](https://github.com/vllm-project/vllm/issues/55581) `[Bug]: FlashInfer get_cudagraph_support() divides the *target* model's head count by the *draft* group's num_k` | nvidia | ? | - |
| - | [#55718](https://github.com/vllm-project/vllm/issues/55718) `[Bug]: Benchmark endpoint validation rejects URLs with query parameters` | perf | ? | - |
| - | [#55719](https://github.com/vllm-project/vllm/pull/55719) `[Bugfix] Allow query parameters in benchmark endpoint URLs` | bug,perf | ? | - |
| - | [#55855](https://github.com/vllm-project/vllm/issues/55855) `[Feature]: Add RDMA-capable NIXL OBJ support for KV offload secondary tier` |  | ? | - |
| - | [#56192](https://github.com/vllm-project/vllm/pull/56192) `[Feature][KV Offload] Add RDMA-capable OBJ tier (#55855)` |  | ? | - |
| - | [#56246](https://github.com/vllm-project/vllm/pull/56246) `[CI][XPU] Add Rust Frontend CI coverage for Intel GPU` | infra,nvidia | ? | - |
| - | [#56451](https://github.com/vllm-project/vllm/pull/56451) `[ROCm][Spec Decode] Enable adaptive DSpark verification for MiniMax M3` | nvidia,rocm | ? | - |
| P0 | [#56492](https://github.com/vllm-project/vllm/pull/56492) `[Core] Extensible KV cache` | infra,nvidia,perf | main | - |
| - | [#56507](https://github.com/vllm-project/vllm/issues/56507) `[Doc]: ec_cpu_connector.md refers to a no-NIXL import test that doesn't exist` |  | ? | - |
| - | [#56508](https://github.com/vllm-project/vllm/pull/56508) `[Test][EC Connector] Add the no-NIXL import test the docs refer to` |  | ? | - |
| - | [#56900](https://github.com/vllm-project/vllm/issues/56900) `[Bug]: Qwen/Qwen1.5-MoE-A2.7B-Chat produces degenerate output with torch.compile (VLLM_COMPILE) but correct ou` | nvidia,perf,quant | ? | - |
| - | [#57224](https://github.com/vllm-project/vllm/issues/57224) `[Bug]: Silent garbage output on GPUs in Confidential Computing mode: V2 model runner's UVA views of pinned hos` | infra,risk | ? | - |
| - | [#57796](https://github.com/vllm-project/vllm/pull/57796) `[Frontend][Multimodal] Accept features together with content_parts in /generate` | bug | ? | - |
| - | [#57810](https://github.com/vllm-project/vllm/pull/57810) `[Core][KVConnector] Keep the offloaded KV tier across pause/sleep` |  | ? | - |
| - | [#57823](https://github.com/vllm-project/vllm/pull/57823) `[Bugfix][MoE] Respect padded row strides in top-k routing` | bug | ? | - |
| - | [#57851](https://github.com/vllm-project/vllm/pull/57851) `[Bugfix][LoRA] Handle leading missing packed groups` | bug | ? | - |
| - | [#57985](https://github.com/vllm-project/vllm/pull/57985) `[Model] Extend device-side mm normalization to DeepSeekV4 Vision / DeepSeekV41` | nvidia | ? | - |
| - | [#58080](https://github.com/vllm-project/vllm/issues/58080) `[Bug] MTP draft model does not inherit --hf-overrides (YaRN): length gate + dummy-0 drafts silently kill specu` | risk | ? | - |
| - | [#58094](https://github.com/vllm-project/vllm/pull/58094) `[Bugfix][Spec Decode] Propagate rope hf_overrides to MTP draft` | bug | ? | - |
| - | [#58485](https://github.com/vllm-project/vllm/issues/58485) `[Bug]: V1 thinking budget corrupts a multi-token reasoning_end_str under speculative decoding` | risk | ? | - |
| - | [#58532](https://github.com/vllm-project/vllm/issues/58532) `[Bug]: Triton fused MoE incorrectly indexes per-channel weight scales with per-tensor activations` | bug,perf,quant,rocm | ? | - |
| - | [#58619](https://github.com/vllm-project/vllm/pull/58619) `[Bugfix][KV Offload] Enable partial-tail offload for hybrid models under DCP` | bug,infra | ? | - |
| - | [#58795](https://github.com/vllm-project/vllm/pull/58795) `[CI] Prebuild mamba-ssm and causal-conv1d from pinned commits in a torch-keyed test-image stage` | infra,nvidia | ? | - |
| - | [#58931](https://github.com/vllm-project/vllm/issues/58931) `[Bug]: MooncakeStoreConnector crashes EngineCore when a request is preempted by `reset_prefix_cache(reset_runn` | bug | ? | - |
| - | [#58986](https://github.com/vllm-project/vllm/pull/58986) `[Perf] Tune GLM-5.3-Flash block-FP8 MoE for H20` | bug,infra,perf,quant | ? | - |
| - | [#59025](https://github.com/vllm-project/vllm/pull/59025) `[Kernel] Register the cudnn backend for FlashInfer BF16 mm` | nvidia,perf | ? | - |
| - | [#59116](https://github.com/vllm-project/vllm/issues/59116) `[Bug]: SMG MoRI-IO PD disagg` | bug,rocm | ? | - |
| - | [#59176](https://github.com/vllm-project/vllm/issues/59176) `[Bug]: GLM-5.3-Flash with HiSparse has no compatible KV cache layout (LBHNC vs BLHNC)` | bug,perf | ? | - |
| - | [#59384](https://github.com/vllm-project/vllm/pull/59384) `[Kernel] Fuse native BF16 ReLU2 with NVFP4 quantization` | nvidia,perf,quant | ? | - |
| - | [#59460](https://github.com/vllm-project/vllm/pull/59460) `[Quantization] Make activation-quantization fallbacks explicit, add VLLM_STRICT_QUANT_SCHEME` | nvidia,quant | ? | - |
| - | [#59746](https://github.com/vllm-project/vllm/pull/59746) `[Bugfix][NIXL] Pair P/D blocks by the last token with different block sizes` | bug | ? | - |
| - | [#59767](https://github.com/vllm-project/vllm/pull/59767) `[Model] Migrate Aria to the Transformers modeling backend` |  | ? | - |
| P1 | [#59818](https://github.com/vllm-project/vllm/issues/59818) `[ROCm]: run-to-run GSM8K accuracy variance for simple-nemotron-h-8b in KV-Offload test on MI300` | infra,risk,rocm | ? | - |
| - | [#59981](https://github.com/vllm-project/vllm/pull/59981) `[Perf] V2 runner decode optimizations for NVIDIA Confidential Computing` | nvidia,perf | ? | - |
| - | [#59988](https://github.com/vllm-project/vllm/issues/59988) `[Bug]: With --api-server-count > 1, gauges such as vllm:num_requests_running have no samples until the first r` |  | ? | - |
| - | [#59994](https://github.com/vllm-project/vllm/pull/59994) `[Bugfix] Offload model runner construction buffers on sleep` | bug | ? | - |
| - | [#60001](https://github.com/vllm-project/vllm/pull/60001) `[Metrics] Export scheduler-state gauges before the first request with --api-server-count > 1` |  | ? | - |
| - | [#60010](https://github.com/vllm-project/vllm/pull/60010) `[Bugfix][Benchmark] Clean up sweep workers after the server exits` | bug,perf | ? | - |
| - | [#60035](https://github.com/vllm-project/vllm/pull/60035) `[Bugfix][Pooling] Make MEAN pooling batch invariant when the flag asks for it` | bug,infra | ? | - |
| - | [#60047](https://github.com/vllm-project/vllm/pull/60047) `[Bugfix] Register the aten::mm out_dtype overloads for batch invariance` | bug,infra | ? | - |
| - | [#60112](https://github.com/vllm-project/vllm/pull/60112) `[Security] Fall back to eager when encoder CUDA graph replay exceeds capture` | nvidia | ? | - |
| - | [#60130](https://github.com/vllm-project/vllm/pull/60130) `[KV Offload] SimpleCPUOffload: one host buffer per rank, opt-in HugeTLB pages` | nvidia | ? | - |
| - | [#60274](https://github.com/vllm-project/vllm/pull/60274) `[Rust Frontend] support --enable-force-include-usage` |  | ? | - |
| - | [#60303](https://github.com/vllm-project/vllm/issues/60303) `[Bug]: Images above Pillow's pixel limit get HTTP 500 instead of 400` |  | ? | - |
| - | [#60308](https://github.com/vllm-project/vllm/pull/60308) `[Bugfix][Frontend] Return 400 for images rejected by Pillow's bomb check` | bug | ? | - |
| - | [#60314](https://github.com/vllm-project/vllm/pull/60314) `[Model] Support data-parallel multimodal encoder for Gemma-4` |  | ? | - |
| - | [#60321](https://github.com/vllm-project/vllm/pull/60321) `[ROCm][Attention] Add an mxfp4_mla KV cache for rope-free sparse MLA (read/write path)` | perf,quant,rocm | ? | - |
| - | [#60390](https://github.com/vllm-project/vllm/pull/60390) `[Model][Core] Share the CPU-offloaded Qwen4Exp PLE table across co-located DP replicas` |  | ? | - |
| P0 | [#60408](https://github.com/vllm-project/vllm/issues/60408) `[Bug][ROCm] gfx950: ROCM_AITER_UNIFIED_ATTN decode regressed in v0.31.0 (-19%, and MTP decode decays with cont` | rocm | ? | - |
| - | [#60438](https://github.com/vllm-project/vllm/pull/60438) `[Bugfix] Fall back from DeepGEMM when nvcc is older than 12.9` | bug,nvidia | ? | - |
| P0 | [#60487](https://github.com/vllm-project/vllm/pull/60487) `[Bugfix][ROCm] Count attention sinks once in AITER FA chunked-context extend` | bug,rocm | main | - |
| - | [#60531](https://github.com/vllm-project/vllm/pull/60531) `[Bugfix][Kernel] Preserve batch invariance in Triton unified attention on SM100` | bug,nvidia,perf,rocm | ? | - |
| - | [#60609](https://github.com/vllm-project/vllm/pull/60609) `[XPU] Bump up kernel 0.1.17, change MoE and MLA interfaces` | bug,infra,nvidia,perf | ? | - |
| P0 | [#60895](https://github.com/vllm-project/vllm/pull/60895) `[Perf][GLM-5.3-Flash] DeepGEMM FP8 MegaMoE with fused shared experts` | perf,quant | main | - |
| - | [#60977](https://github.com/vllm-project/vllm/issues/60977) `[Bug]: EmbeddingGemma 2 rejects dimensions=768 despite returning 768-dimensional embeddings` |  | ? | - |
| - | [#60978](https://github.com/vllm-project/vllm/pull/60978) `[Bugfix][Pooling] Use embedding_dim for pooling output size` | bug | ? | - |
| - | [#61076](https://github.com/vllm-project/vllm/pull/61076) `[RL] Add configurable staging and parallel stage pulls to sharded RDT` | infra | ? | - |
| - | [#61243](https://github.com/vllm-project/vllm/pull/61243) `[HiSparse] GLM-5.3-Flash support` | infra,nvidia,perf,rocm | ? | - |
| - | [#61395](https://github.com/vllm-project/vllm/pull/61395) `[EPLB] Support heterogeneous DeepSeek V4/V4.1 DSpark draft experts` |  | ? | - |
| - | [#61424](https://github.com/vllm-project/vllm/pull/61424) `[Core][Metrics] Collect iteration details during scheduling` |  | ? | - |
| P1 | [#61448](https://github.com/vllm-project/vllm/pull/61448) `[ROCm][Model] Add fusions for Muse Glimmer for AMD backend` | perf,rocm | ? | - |
| - | [#61452](https://github.com/vllm-project/vllm/pull/61452) `[Core][KV Cache] Move KV cache allocation policy out of KVCacheSpecs (RFC #42449 part 2)` | infra,nvidia,perf,rocm | ? | - |
| - | [#61486](https://github.com/vllm-project/vllm/issues/61486) `[Bug]: [ROCm] Qwen4Exp (AMD path): PLE n-gram IDs read a stale query_start_loc tail during PIECEWISE CUDA-grap` | bug,nvidia,quant,rocm | ? | - |
| - | [#61492](https://github.com/vllm-project/vllm/pull/61492) `[Bugfix][Metrics] Periodic stats line: dead Preemptions field + Finished count` | bug | ? | - |
| P0 | [#61498](https://github.com/vllm-project/vllm/pull/61498) `[ROCm][Perf][Kimi-K3] Mono decode layer for Kimi-K3 on MI355X w/ vanilla decode` | infra,perf,rocm | main | - |
| - | [#61501](https://github.com/vllm-project/vllm/pull/61501) `[Perf][Mamba] Opt-in FlashInfer SSD prefill scan; per-step ReplaySSM seed` | nvidia,perf,quant | ? | - |
| - | [#61530](https://github.com/vllm-project/vllm/pull/61530) `[Model][DSV4.1] Support MXFP4-packed Engram embedding tables` | quant | ? | - |
| - | [#61539](https://github.com/vllm-project/vllm/issues/61539) `[RFC]: Explicit row layouts for routed-expert capture` |  | ? | - |
| - | [#61593](https://github.com/vllm-project/vllm/pull/61593) `[CPU] Enable gelu_tanh activation support for Gemma4 MoE` |  | ? | - |
| - | [#61630](https://github.com/vllm-project/vllm/pull/61630) `[XPU][Attention] Enable tuned large-head prefill config on XPU` | nvidia,perf | ? | - |
| - | [#61666](https://github.com/vllm-project/vllm/pull/61666) `[Quantization] Support compressed-tensors MXFP6 (mxfp6-pack-quantized)` | infra,quant | ? | - |
| - | [#61669](https://github.com/vllm-project/vllm/pull/61669) `[Bugfix][Model] DiffusionGemma: stop sampler recompiles during serving` | bug,perf | ? | - |
| - | [#61725](https://github.com/vllm-project/vllm/pull/61725) `[Core] Add max_async_kv_loads_per_step to cap new async KV loads per step` |  | ? | - |
| P0 | [#61770](https://github.com/vllm-project/vllm/pull/61770) `[Bugfix][ROCm][Qwen4Exp] Remap Quark layer names for the MTP draft model` | bug,rocm | main | - |
| - | [#61796](https://github.com/vllm-project/vllm/pull/61796) `[Test][UMBP][8/10] Add standalone runtime coverage` | infra,rocm | ? | - |
| - | [#61797](https://github.com/vllm-project/vllm/pull/61797) `[UMBP][9/10] Add lazy GPU cache offloading` | infra,perf,rocm | ? | - |
| - | [#61798](https://github.com/vllm-project/vllm/pull/61798) `[Test][UMBP][10/10] Add lazy offload and token restore coverage` | infra | ? | - |
| - | [#61813](https://github.com/vllm-project/vllm/pull/61813) `[Chore] Use upstream Transformers MiniMaxM3VLConfig` | nvidia | ? | - |
| - | [#61815](https://github.com/vllm-project/vllm/pull/61815) `[Quantization] Allow online per-channel fp8 quantization of an unquantized lm_head` | quant | ? | - |
| P0 | [#61816](https://github.com/vllm-project/vllm/pull/61816) `[ROCm][Bugfix] Stop declaring the MXFP4 MoE intermediate padding to AITER` | bug,quant,rocm | main | - |
| P1 | [#61821](https://github.com/vllm-project/vllm/pull/61821) `[Perf][Kernel] Add the bias in the SM120 NVFP4 CUTLASS GEMM epilogue` | nvidia,perf,quant | ? | - |
| - | [#61853](https://github.com/vllm-project/vllm/issues/61853) `[Bug]: enable_lora on Jamba (ai21labs/Jamba-tiny-dev) causes a CUDA illegal memory access followed by an uncau` | bug,nvidia,risk | ? | - |
| P0 | [#61866](https://github.com/vllm-project/vllm/issues/61866) `[ROCm][Perf] gfx950 spec-decode verify attention is up to 48x slower with AITER <= v0.1.25; bump to a release ` | infra,perf,rocm | ? | - |
| - | [#61869](https://github.com/vllm-project/vllm/pull/61869) `[Perf][DSv4.1] DSpark draft on the specialized decode` | infra,nvidia,perf | ? | - |
| - | [#61872](https://github.com/vllm-project/vllm/pull/61872) `[Bugfix][ROCm] Restore MoE weight padding dropped by #46009` | bug,rocm | ? | - |
| - | [#61897](https://github.com/vllm-project/vllm/pull/61897) `[Feature][MoE] Support routed experts capture (R3) with pipeline parallelism` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#61942](https://github.com/vllm-project/vllm/pull/61942) `[ROCm][Perf] Skip DSA indexer scoring for short dense-MHA prefills` | infra,perf,rocm | ? | - |
| P0 | [#62270](https://github.com/vllm-project/vllm/pull/62270) `[ROCm][Perf][MiniMax-M3] Enable the fp8 indexer cache on gfx942` | infra,perf,quant,rocm | main | - |
| - | [#62298](https://github.com/vllm-project/vllm/pull/62298) `[CI][ROCm] Run ROCm-capable tests that are currently skipped on AMD` | infra,nvidia,rocm | ? | - |
| - | [#62309](https://github.com/vllm-project/vllm/pull/62309) `[XPU] support adaptive verification for deepseek-v4` | nvidia | ? | - |
| - | [#62345](https://github.com/vllm-project/vllm/pull/62345) `[Bugfix][Security] muse: fix quadratic attribute scans in tool-call extraction` | bug | ? | - |
| - | [#62515](https://github.com/vllm-project/vllm/pull/62515) `[Spec Decode] Enable adaptive verification for `FlashInferMLASparseSM90Backend`` | nvidia | ? | - |
| - | [#62517](https://github.com/vllm-project/vllm/pull/62517) `[Bugfix][Parser] DeepSeek V4.1: don't leak a `<｜DSML｜ tool_calls>` opener into content` | bug | ? | - |
| - | [#62529](https://github.com/vllm-project/vllm/pull/62529) `[Tests] Add TP2 PCP2 canonical mapping byte coverage` |  | ? | - |
| P0 | [#62565](https://github.com/vllm-project/vllm/pull/62565) `[ROCm][Perf] Fix Kimi-K2.6 int4 MoE prefill regression on Triton 3.8 (gfx950 tuned config)` | bug,perf,quant,rocm | main | - |
| - | [#62566](https://github.com/vllm-project/vllm/pull/62566) `[KV Offload] Warn when secondary-tier KV is tied to the parallel config` |  | ? | - |
| - | [#62603](https://github.com/vllm-project/vllm/pull/62603) `[Perf][MoE] Enable SM90 block-FP8 MegaMoE via FlashInfer MoE-EP` | nvidia,perf,quant | ? | - |
| P0 | [#62606](https://github.com/vllm-project/vllm/issues/62606) `[Bug][ROCm]: ROCM_AITER_UNIFIED_ATTN gives wrong output on gfx950 when a layer's KV cache is 2–4 GiB` | perf,risk,rocm | ? | - |
| - | [#62656](https://github.com/vllm-project/vllm/pull/62656) `[XPU][CI] Re-enable `test_reset_prefix_cache_e2e` and `test_scheduler_e2e` on XPU` | infra,nvidia | ? | - |
| P1 | [#62675](https://github.com/vllm-project/vllm/pull/62675) `[Bugfix][ROCm] Pad Qwen4Exp PLE n-gram inputs for piecewise CUDA graph replays` | bug,nvidia,rocm | ? | - |
| - | [#62687](https://github.com/vllm-project/vllm/issues/62687) `[Bug]: CPU backend: a seeded request whose prompt is split by chunked prefill kills the engine ("CPU Generator` |  | ? | - |
| - | [#62718](https://github.com/vllm-project/vllm/pull/62718) `[ROCm][Build][3/5] Speed up ROCm build: split the skinny GEMMs per kernel family and trim torch headers` | infra,perf,rocm | ? | - |
| P0 | [#62725](https://github.com/vllm-project/vllm/pull/62725) `[ROCm][Bugfix] Serve gfx942 MLA verify past 4 tokens with a Triton kernel` | bug,perf,rocm | main | - |
| P0 | [#62750](https://github.com/vllm-project/vllm/pull/62750) `[Quantization] Block Hadamard input rotation for linear layers: online `mxfp4_hadamard32` and Quark online-rot` | quant,rocm | main | - |
| - | [#62769](https://github.com/vllm-project/vllm/pull/62769) `[Bugfix][Spec Decode] Synchronize adaptive DSpark decisions across TP ranks` | bug,nvidia | ? | - |
| - | [#62785](https://github.com/vllm-project/vllm/pull/62785) `[Bugfix][Pooling] Honor the CrossEncoder activation saved by Sentence Transformers v6` | bug | ? | - |
| - | [#62791](https://github.com/vllm-project/vllm/pull/62791) `[Bugfix][Benchmark] Take openai-audio input tokens from server usage` | bug,perf | ? | - |
| - | [#62800](https://github.com/vllm-project/vllm/pull/62800) `[Bugfix] Fix KV cache pages for hybrid models with draft layers` | bug,nvidia,perf | ? | - |
| - | [#62808](https://github.com/vllm-project/vllm/issues/62808) `[Bug]: Built-in LMCacheConnectorV1 does not forward shutdown(), so LMCache never stops and EngineCore is force` |  | ? | - |
| - | [#62964](https://github.com/vllm-project/vllm/pull/62964) `[Bugfix][Spec Decode] Keep FlashInfer CUDA graphs for drafters with their own head count` | bug,nvidia,perf | ? | - |
| - | [#63043](https://github.com/vllm-project/vllm/issues/63043) `[Bug]: Native FlashInfer produces garbage output with BF16 Q and non-unit q_scale` | nvidia,quant,risk | ? | - |
| P0 | [#63049](https://github.com/vllm-project/vllm/issues/63049) `[Bug]: TritonW4A16 GEMM faults on ROCm once M × N or M × K passes 2^31` | quant,rocm | ? | - |
| P0 | [#63054](https://github.com/vllm-project/vllm/pull/63054) `[Bugfix][ROCm] Use 64-bit row offsets in the Triton W4A16 GEMM` | bug,quant,rocm | main | - |
| - | [#63096](https://github.com/vllm-project/vllm/pull/63096) `[ROCm][Spec Decode] Enable fused multi-step draft decode for ROCM_AITER_UNIFIED_ATTN` | perf,rocm | ? | - |
| - | [#63097](https://github.com/vllm-project/vllm/pull/63097) `[Model] Load q/k/v scales for the quantized Kimi-K2.6` | quant | ? | - |
| - | [#63102](https://github.com/vllm-project/vllm/pull/63102) `[Perf][GLM-5.3-Flash] Specialized decode for GB300 TP4` | infra,nvidia,perf | ? | - |
| - | [#63106](https://github.com/vllm-project/vllm/pull/63106) `[Feature][DSv4.1] Support arbitrary pipeline stage partitions` | perf | ? | - |
| - | [#63162](https://github.com/vllm-project/vllm/issues/63162) `[Bug]: `return_tokens_as_token_ids` is ignored on derender paths` | bug | ? | - |
| - | [#63166](https://github.com/vllm-project/vllm/pull/63166) `[ROCm][CI] Fix the test_qwen.py failure when AITER is on` | bug,infra,rocm | ? | - |
| - | [#63173](https://github.com/vllm-project/vllm/pull/63173) `[Bugfix][Frontend] Honor token ID logprob overrides on derender paths` | bug | ? | - |
| - | [#63304](https://github.com/vllm-project/vllm/pull/63304) `[Frontend] Remove dead helpers and sync type annotations in entrypoints and config` |  | ? | - |
| - | [#63330](https://github.com/vllm-project/vllm/pull/63330) `[XPU][Model] Gemma4: route MoE with topk_softmax on XPU` | nvidia | ? | - |
| - | [#63337](https://github.com/vllm-project/vllm/pull/63337) `[Bugfix] Tell a stopped engine core apart from a dead one during AsyncLLM shutdown` | bug | ? | - |
| - | [#63349](https://github.com/vllm-project/vllm/pull/63349) `[MOE oracle][Refactor][1/N] Deduplicate the MoE oracle selection and backend code` | nvidia | ? | - |
| - | [#63352](https://github.com/vllm-project/vllm/pull/63352) `[CI][Test] Bias test_stop_reason toward the stop token` | infra | ? | - |
| - | [#63356](https://github.com/vllm-project/vllm/issues/63356) `[Bug]: Chat derender ignores `--response-role`, `add_generation_prompt: false` and `echo`` | bug | ? | - |
| - | [#63357](https://github.com/vllm-project/vllm/pull/63357) `[Bugfix][Frontend] Honor --response-role and echo in chat derender` | bug | ? | - |
| - | [#63365](https://github.com/vllm-project/vllm/pull/63365) `[ROCm][Build][5/5] Speed up ROCm build: instantiate the fused MUSE-Spark op per head size` | infra,perf,rocm | ? | - |
| - | [#63373](https://github.com/vllm-project/vllm/pull/63373) `[Core] Remove Model Runner V1` | infra,nvidia,perf,rocm | ? | - |
| - | [#63383](https://github.com/vllm-project/vllm/pull/63383) `[ROCm][gfx1151] ROCM_RDNA_ATTN: attention backend for RDNA` | infra,rocm | ? | - |
| - | [#63392](https://github.com/vllm-project/vllm/pull/63392) `[ROCm][Perf] AITER FA: trim the sliding-window decode table with fewer ops` | perf,rocm | ? | - |
| - | [#63401](https://github.com/vllm-project/vllm/pull/63401) `[Bugfix][ROCm] Size the extensible KV cache from exact VRAM use, not 2 MB-rounded free memory` | bug,infra,nvidia,perf,rocm | ? | - |
| - | [#63405](https://github.com/vllm-project/vllm/pull/63405) `[CI] Leave GPU headroom in the offline ColBERT plugin tests` | infra | ? | - |
| - | [#63432](https://github.com/vllm-project/vllm/pull/63432) `[Bugfix][Spec Decode] Keep nested-config and YaRN drafts within their rotary cache` | bug,perf | ? | - |
| P0 | [#63440](https://github.com/vllm-project/vllm/pull/63440) `[ROCm][Perf][Muse Spark] FlyDSL decode monokernel for DSpark verify steps on MI355X (--monokernel)` | infra,nvidia,perf,rocm | main | - |
| P1 | [#63467](https://github.com/vllm-project/vllm/issues/63467) `[Bug]: Wrong token ids from fastokens' split cache before 0.3.4 (Rust frontend, VLLM_USE_FASTOKENS)` | perf | ? | - |
| - | [#63505](https://github.com/vllm-project/vllm/issues/63505) `[Bug]: Qwen3.8-27B (GDN hybrid) with PP=3 on sm_86: illegal memory access (Xid 31) with prefix caching, gibber` | bug,perf,risk | ? | - |
| - | [#63540](https://github.com/vllm-project/vllm/pull/63540) `[Perf][DSv4] Process 4 heads per program in fused_inv_rope_fp8_quant` | perf,quant | ? | - |
| - | [#63574](https://github.com/vllm-project/vllm/pull/63574) `[Security] Raise patched runtime and test dependency floors` | infra,rocm | ? | - |
| - | [#63598](https://github.com/vllm-project/vllm/issues/63598) `[Bug]: Qwen3.5/3.6 MoE GPTQ checkpoint with BF16 fused MTP experts: `mtp.layers.0.mlp.experts has no parameter` | perf,quant,rocm | ? | - |
| - | [#63627](https://github.com/vllm-project/vllm/pull/63627) `[Perf] Tuned batch-invariant fused MoE configs on Blackwell` | nvidia,perf | ? | - |
| - | [#63636](https://github.com/vllm-project/vllm/pull/63636) `[Bugfix][Transformers] Infer mm encoder dynamic_arg_dims from forward signature` | bug,infra | ? | - |
| P0 | [#63721](https://github.com/vllm-project/vllm/pull/63721) `[ROCm][Perf][MoE] Fuse SiLU-and-mul with per-token FP8 quant in TritonExperts and skip remote EP routes` | perf,quant,rocm | main | - |
| - | [#63724](https://github.com/vllm-project/vllm/pull/63724) `[ROCm][Perf][Muse Spark] Enable the bf16x3 router GEMM on gfx942` | perf,rocm | ? | - |
| P0 | [#63727](https://github.com/vllm-project/vllm/pull/63727) `[ROCm][Perf][Muse Spark] Add gfx942 FP8 W8A8 fused-MoE configs for E=32,N=4096` | perf,quant,rocm | main | - |
| P1 | [#63732](https://github.com/vllm-project/vllm/issues/63732) `[Bug]: Gemma 4 + online --quantization fp8: image requests crash since v0.23.0 (FP8-cast pixel values reach qu` | bug,quant | ? | - |
| - | [#63751](https://github.com/vllm-project/vllm/issues/63751) `[Bug]: IndexError in _create_chat_logprobs / _create_completion_logprobs (top_logprobs shorter than token_ids)` | bug | ? | - |
| - | [#63753](https://github.com/vllm-project/vllm/pull/63753) `[Fast Start] Seed compiled caches through the D2D transport` | nvidia | ? | - |
| - | [#63795](https://github.com/vllm-project/vllm/pull/63795) `[Spec Decode] DSpark: sliding-window MLA draft layers` | perf | ? | - |
| - | [#63796](https://github.com/vllm-project/vllm/pull/63796) `[Spec Decode][DCP] DSpark: run sliding-window MLA drafts under DCP` | perf | ? | - |
| - | [#63838](https://github.com/vllm-project/vllm/pull/63838) `[ROCm][Kimi-K3] Keep the AttnRes block bank in a persistent workspace` | rocm | ? | - |
| - | [#63847](https://github.com/vllm-project/vllm/pull/63847) `[ROCm][Kernel] Support persistent_topk on ROCm` | infra,nvidia,perf,rocm | ? | - |
| P1 | [#63878](https://github.com/vllm-project/vllm/pull/63878) `[ROCm][Perf][DSA] Honor skip_kv_gather in the ROCm sparse-indexer prefill loop` | perf,rocm | ? | - |
| - | [#63890](https://github.com/vllm-project/vllm/pull/63890) `[ROCm][Perf] Use AITER's all-gather for small TP all-gathers` | nvidia,perf,rocm | ? | - |
| - | [#63893](https://github.com/vllm-project/vllm/pull/63893) `[ROCm][Perf][DSv4.1] Mono: tuned K1 at TP4` | perf,rocm | ? | - |
| P0 | [#63944](https://github.com/vllm-project/vllm/issues/63944) `[Bug]: int8_per_token_head scale-view fill overwrites Gated DeltaNet state in hybrid models` | quant | ? | - |
| P0 | [#63971](https://github.com/vllm-project/vllm/pull/63971) `[Bugfix][Mooncake] Let decodes reuse divergent local hybrid prefix hits` | bug | main | - |
| - | [#64001](https://github.com/vllm-project/vllm/pull/64001) `[ROCm][DSv4.1] Avoid runtime JIT for offset combine_topk_swa_indices inputs` | rocm | ? | - |
| P0 | [#64004](https://github.com/vllm-project/vllm/pull/64004) `[ROCm][Kimi-K3][Perf] Cut gfx942 MXFP4-to-int4 requant time under pure TP` | perf,quant,rocm | main | - |
| - | [#64038](https://github.com/vllm-project/vllm/issues/64038) `[Bug]: `/v1/chat/completions/derender` usage omits `reasoning_tokens` and `cached_tokens` that `/v1/chat/compl` | bug | ? | - |
| - | [#64041](https://github.com/vllm-project/vllm/pull/64041) `[Bugfix] Report reasoning and cached tokens in chat derender usage` | bug | ? | - |
| - | [#64055](https://github.com/vllm-project/vllm/pull/64055) `[ROCm][RDNA][Perf][MoE] Use w2 scatter + topk sum for the tk 3.8 OAI MoE combine on RDNA` | perf,rocm | ? | - |
| - | [#64056](https://github.com/vllm-project/vllm/pull/64056) `[Quantization][OOT] Fix OnlineQuantizationConfig overriding the registered OOT online quantization config` | bug,quant | ? | - |
| - | [#64061](https://github.com/vllm-project/vllm/pull/64061) `[Kernel][Perf] Run DeepGEMM Mega MoE on SM90 with MXFP4 experts` | infra,nvidia,perf,quant | ? | - |
| - | [#64070](https://github.com/vllm-project/vllm/pull/64070) `[Recipe] Qwen3.5: keep configuration-specific content out of the guides` | infra | ? | - |
| - | [#64086](https://github.com/vllm-project/vllm/pull/64086) `[Bugfix][MoE] Preserve invalid expert IDs in NIXL round-robin mapping` | bug,infra | ? | - |
| P0 | [#64087](https://github.com/vllm-project/vllm/pull/64087) `[Bugfix][Kernel] Fix reshape & cache dropping KV heads past 512 chunks` | bug,perf,rocm | main | - |
| P0 | [#64094](https://github.com/vllm-project/vllm/pull/64094) `[ROCm][DSv4.1][Perf]  Enable prefix-cache SWA replay on gfx950` | perf,rocm | main | - |
| - | [#64099](https://github.com/vllm-project/vllm/issues/64099) `[RFC]: Consistent semantics for drafted, verified and accepted spec decode tokens` |  | ? | - |
| P0 | [#64106](https://github.com/vllm-project/vllm/issues/64106) `[Bug]: Kimi-K3 on MI355X: --kv-cache-dtype fp8 silently breaks accuracy (GSM8K 0.975 -> 0.305)` | perf,quant,risk,rocm | ? | - |
| - | [#64131](https://github.com/vllm-project/vllm/pull/64131) `[ROCm][CI] Keep nightlies off PR-writable images and trim the csrc cache key` | infra,perf,rocm | ? | - |
| - | [#64152](https://github.com/vllm-project/vllm/pull/64152) `[ROCm][Perf][DSv4.1] Mono: tuned K1 at TP8` | perf,rocm | ? | - |
| - | [#64153](https://github.com/vllm-project/vllm/pull/64153) `[ROCm][Perf][DSv4.1] Mono: batch TP8 K2's X8 copies, load its push's peer bases late` | perf,rocm | ? | - |
| - | [#64156](https://github.com/vllm-project/vllm/pull/64156) `[Spec Decode] Consistent drafted, verified and accepted token counts` | perf | ? | - |
| - | [#64159](https://github.com/vllm-project/vllm/pull/64159) `[Bugfix][DP] Log cross-engine step statistics ordering at debug level` | bug | ? | - |
| - | [#64164](https://github.com/vllm-project/vllm/pull/64164) `[Bugfix][Metrics] Keep Ray metrics usable without Ray Serve` | bug | ? | - |
| - | [#64165](https://github.com/vllm-project/vllm/pull/64165) `[Bugfix] Fix FlashInfer plan buffer race causing illegal memory access with PP` | bug,nvidia,risk | ? | - |
| P1 | [#64168](https://github.com/vllm-project/vllm/pull/64168) `[Bugfix] Fix Gemma 4 vision crash with online FP8 quantization` | bug,infra,nvidia,quant | ? | - |
| - | [#64275](https://github.com/vllm-project/vllm/issues/64275) `[Bug]: Adaptive-verification cost profiling OOMs at startup after KV-cache allocation (DeepSeek-V4.1-Flash-101` | bug,perf,rocm | ? | - |
| - | [#64286](https://github.com/vllm-project/vllm/pull/64286) `[KV Offload] Add a store trigger and isolated store trigger handlers` |  | ? | - |
| - | [#64298](https://github.com/vllm-project/vllm/pull/64298) `[Bugfix][KV Offload][P2P] Fail never-sent fetches locally` | bug | ? | - |
| - | [#64315](https://github.com/vllm-project/vllm/pull/64315) `[Model][Qwen4Exp] Run routed experts on DeepGEMM MegaMoE (MXFP8 or MXFP4)` | infra,quant | ? | - |
| - | [#64324](https://github.com/vllm-project/vllm/pull/64324) `[Bugfix] Forward shutdown() in LMCacheConnectorV1 so EngineCore is not force-killed` | bug | ? | - |
| - | [#64329](https://github.com/vllm-project/vllm/pull/64329) `[Bugfix] Apply the layer q_scale only to FP8 queries in FlashInfer` | bug,nvidia,quant | ? | - |
| - | [#64331](https://github.com/vllm-project/vllm/pull/64331) `[ROCm][RDNA][Perf] Bump triton_kernels to ROCm 3.8.x with the RDNA MXFP4 configs` | infra,perf,quant,rocm | ? | - |
| P1 | [#64352](https://github.com/vllm-project/vllm/pull/64352) `[Model Loader] Direct reload: reset MoE expert padding at begin` | infra,quant | ? | - |
| - | [#64403](https://github.com/vllm-project/vllm/pull/64403) `[Bugfix][ROCm] Avoid unused index caches in MiniMax-M3 sharing layers` | bug,rocm | ? | - |
| - | [#64410](https://github.com/vllm-project/vllm/pull/64410) `[Quantization] Support w4afp8 checkpoints on the W4A8 FP8 MoE path` | quant | ? | - |
| - | [#64436](https://github.com/vllm-project/vllm/issues/64436) `[Bug]: Gemma4 MoE cannot load PEFT expert LoRA adapters without --enable-mixed-moe-lora-format` |  | ? | - |
| - | [#64437](https://github.com/vllm-project/vllm/pull/64437) `[Bugfix][LoRA] Use 3D MoE LoRA wrapper for Gemma4` | bug | ? | - |
| - | [#64476](https://github.com/vllm-project/vllm/pull/64476) `[Spec Decode][DSpark] Fuse the Markov bias and block combine into Gumbel sampling` | perf | ? | - |
| - | [#64478](https://github.com/vllm-project/vllm/pull/64478) `[XPU][UT] Temporarily Skip CUDA-IPC weight cache test` | nvidia,perf,rocm | ? | - |
| - | [#64485](https://github.com/vllm-project/vllm/pull/64485) `[Bugfix][EPLB] Start the async rearrangement interval after the last layer commits` | bug | ? | - |
| - | [#64497](https://github.com/vllm-project/vllm/issues/64497) `[Bug]: [CPU] DP×TP with explicit binds crashes with IndexError on 2-NUMA hosts` | bug | ? | - |
| - | [#64499](https://github.com/vllm-project/vllm/pull/64499) `[Bugfix][CPU] Name the cause when a DP rank's assigned NUMA nodes don't exist` | bug | ? | - |
| - | [#64528](https://github.com/vllm-project/vllm/pull/64528) `[Misc] Bump ruff to v0.17.2 and enable UP032, UP042, B007, F403 and F405` | infra,nvidia,perf,quant | ? | - |
| - | [#64530](https://github.com/vllm-project/vllm/pull/64530) `[Bugfix][Model Runner V2] Embed randomized dummy input ids for inputs_embeds models` | bug | ? | - |
| - | [#64531](https://github.com/vllm-project/vllm/pull/64531) `[Perf] Zero bubble draft tokens handoff for structured outputs` | infra,perf | ? | - |
| - | [#64534](https://github.com/vllm-project/vllm/pull/64534) `[Model] Add Mistral Large 4` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#64541](https://github.com/vllm-project/vllm/issues/64541) `[Bug]: dots.ocr produces identical "blurry image" output for every region with tensor-parallel size 2` |  | ? | - |
| - | [#64543](https://github.com/vllm-project/vllm/pull/64543) `[Bugfix][Model] Fix dots_ocr vision tower QKV split for TP > 1` | bug | ? | - |
| P1 | [#64560](https://github.com/vllm-project/vllm/pull/64560) `[ROCm][Perf][MLA] Fuse the decode W_UK absorb, q concat + fp8 quant and head pad via AITER` | perf,quant,rocm | ? | - |
| - | [#64588](https://github.com/vllm-project/vllm/pull/64588) `[Doc][Recipe] MiMo-V2.5-Pro: split fused --max-model-len base arg` | infra,perf | ? | - |
| - | [#64604](https://github.com/vllm-project/vllm/pull/64604) `[CI] Enroll Language Models (Hybrid) and Granite Compatibility in automatic sharding` | infra | ? | - |
| - | [#64606](https://github.com/vllm-project/vllm/pull/64606) `[CI] Enroll 8 jobs in automatic sharding` | infra | ? | - |
| - | [#64622](https://github.com/vllm-project/vllm/pull/64622) `[Startup] Skip the CUDA graph memory profile when its estimate is disabled` | nvidia | ? | - |
| - | [#64652](https://github.com/vllm-project/vllm/issues/64652) `[Bug]: EAGLE3 draft acceptance collapses after the first position with --block-size > 128 (MiniMax-M3, GB200)` | nvidia | ? | - |
| - | [#64663](https://github.com/vllm-project/vllm/pull/64663) `[Doc] Named and required tool_choice need a tool parser` |  | ? | - |
| P0 | [#64677](https://github.com/vllm-project/vllm/pull/64677) `[Bugfix][UMBP] Copy every KV cache layout's per-head runs` | bug,infra,perf,rocm | main | - |
| - | [#64681](https://github.com/vllm-project/vllm/pull/64681) `[Bugfix][LoRA] Give Mamba-1 LoRA layers every row of the batch` | bug,infra | ? | - |
| P1 | [#64693](https://github.com/vllm-project/vllm/pull/64693) `[ROCm][MoRIIO] Support PP for prefill instance in PD disaggregated serving with MoRI WRITE mode` | rocm | ? | - |
| P1 | [#64715](https://github.com/vllm-project/vllm/pull/64715) `[ROCm][UMBP] Support UMBP standalone mode for DeepSeek-V4.1-Flash` | rocm | ? | - |
| - | [#64742](https://github.com/vllm-project/vllm/pull/64742) `[Bugfix][Rust Frontend] Fix cancellation during request submission` | bug | ? | - |
| P0 | [#64763](https://github.com/vllm-project/vllm/pull/64763) `[ROCm][HY4] Use breakable graphs without torch.compile` | infra,rocm | main | - |
| - | [#64765](https://github.com/vllm-project/vllm/pull/64765) `[Misc] Use the b12x package shipped with flashinfer-python` | infra,nvidia | ? | - |
| - | [#64767](https://github.com/vllm-project/vllm/pull/64767) `[Quantization] Load ModelOpt NVFP4 W4A16 token embeddings in mixed-precision checkpoints` | infra,quant | ? | - |
| P1 | [#64777](https://github.com/vllm-project/vllm/pull/64777) `[Bugfix][Spec Decode] Use the target's kernel block sizes for EAGLE draft attention` | bug,perf | ? | - |
| - | [#64778](https://github.com/vllm-project/vllm/issues/64778) `[Bug]: Non-streaming `/v1/chat/completions/derender` and `/v1/completions/derender` report `usage.prompt_token` | bug | ? | - |
| - | [#64781](https://github.com/vllm-project/vllm/pull/64781) `[Bugfix] Read generate usage.prompt_tokens in non-streaming derender` | bug | ? | - |
| - | [#64822](https://github.com/vllm-project/vllm/pull/64822) `[Perf][Model] Muse vision encoders: no GPU<->CPU syncs, build Glimmer's vision prep once per call` | infra,perf | ? | - |
| - | [#64829](https://github.com/vllm-project/vllm/pull/64829) `[CPU][Perf] Speed up GDN speculative-decode recurrent update` | perf | ? | - |
| - | [#64831](https://github.com/vllm-project/vllm/pull/64831) `[Bugfix][Benchmark] Fix bench mm-processor crash with HF datasets` | bug,perf | ? | - |
| - | [#64834](https://github.com/vllm-project/vllm/pull/64834) `[CI][XPU] Use supported block sizes in UCX backend tests` | infra,nvidia | ? | - |
| - | [#64845](https://github.com/vllm-project/vllm/issues/64845) `[Bug]: EmbeddingGemma 2 rejects `dimensions` by default although the model supports Matryoshka (128/256/512/76` |  | ? | - |
| P1 | [#64874](https://github.com/vllm-project/vllm/issues/64874) `[Bug]: [ROCm][GLM-5.3-Flash]: "Workspace is locked" AssertionError in rocm_fp8_paged_mqa_logits under high dec` | bug,rocm | ? | - |
| P1 | [#64883](https://github.com/vllm-project/vllm/pull/64883) `[ROCm][Perf][DSv4.1] Mono: tuned K2 FFN seam at TP4 / TP8` | perf,rocm | ? | - |
| - | [#64885](https://github.com/vllm-project/vllm/pull/64885) `[Bugfix][Pooling] Enable Matryoshka dimensions for EmbeddingGemma 2` | bug,infra | ? | - |
| - | [#64897](https://github.com/vllm-project/vllm/pull/64897) `[Bugfix][Spec Decode][XPU] greedy_argmax: treat NaN as -inf on the torch fallback` | bug,nvidia,risk | ? | - |
| - | [#64923](https://github.com/vllm-project/vllm/pull/64923) `[Bugfix][V2 runner] Keep idle-DP dummy requests within max_model_len` | bug | ? | - |
| P0 | [#64958](https://github.com/vllm-project/vllm/pull/64958) `[ROCm][Kimi-K3] Support Mooncake consumers with specialized decode` | rocm | main | - |
| - | [#64985](https://github.com/vllm-project/vllm/issues/64985) `[Bug]: KV-sharing fast prefill hangs under async scheduling (non-blocking D2H copy of query_start_loc_cpu)` | bug | ? | - |
| P1 | [#64986](https://github.com/vllm-project/vllm/pull/64986) `[Bugfix][Attention] Fix KV-sharing fast prefill hang from unsynchronized host offsets` | bug | ? | - |
| - | [#64994](https://github.com/vllm-project/vllm/pull/64994) `[Perf][DCP] Up-project the MLA decode output before the A2A merge` | infra,perf | ? | - |
| - | [#65028](https://github.com/vllm-project/vllm/pull/65028) `[Perf][Rust Frontend] Serialize SSE chunks before building the event` | perf | ? | - |
| - | [#65029](https://github.com/vllm-project/vllm/pull/65029) `[Bugfix][Frontend] Report the line of a run-batch request rejected by request validators` | bug | ? | - |
| P0 | [#65030](https://github.com/vllm-project/vllm/pull/65030) `[Perf][Model] DeepSeek V4/V4.1 Vision: encode a call's images in packed passes` | perf | main | - |
| - | [#65077](https://github.com/vllm-project/vllm/pull/65077) `[Perf][Quantization] Honor FP8 activations for Humming linear on SM100/SM110` | infra,nvidia,perf,quant | ? | - |
| P0 | [#65080](https://github.com/vllm-project/vllm/pull/65080) `[Bugfix][ROCm] Muse Spark: merge the two process_weights_after_loading hooks` | bug,rocm | main | - |
| - | [#65084](https://github.com/vllm-project/vllm/pull/65084) `[Multimodal] Refactor encoder cuda graph to support share graph buffer reuse` | nvidia,rocm | ? | - |
| P0 | [#65087](https://github.com/vllm-project/vllm/pull/65087) `[ROCm][Perf][MiniMax-M3.1] Four-wave decode top-k for the NVFP4 indexer` | perf,quant,rocm | main | - |
| P0 | [#65092](https://github.com/vllm-project/vllm/pull/65092) `[Bugfix][ROCm] Reserve kpool decode indexer logits in workspace during profiling` | bug,rocm | main | - |
| P1 | [#65105](https://github.com/vllm-project/vllm/issues/65105) `[Bug]: [ROCm] AITER MLA `paged_kv_indices` sized max_num_seqs x max_model_len (4 GiB per builder) pins a cache` | infra,rocm | ? | - |
| P1 | [#65106](https://github.com/vllm-project/vllm/issues/65106) `[Bug]: [ROCm][Kimi-K3] DBO: MoE workspace locked smaller than the DP-gathered batch, first request fails` | rocm | ? | - |
| P1 | [#65132](https://github.com/vllm-project/vllm/pull/65132) `[ROCm][Perf] Build AITER MLA full-graph decode metadata in one kernel` | infra,perf,rocm | ? | - |
| P1 | [#65137](https://github.com/vllm-project/vllm/pull/65137) `[Bugfix][KV Connector] Keep same-host NIXL on NVLink with the extensible KV cache` | bug,perf | ? | - |
| - | [#65145](https://github.com/vllm-project/vllm/pull/65145) `[CI] Bake hash-locked KV connectors into the CI image and re-enable their jobs` | infra | ? | - |
| - | [#65149](https://github.com/vllm-project/vllm/pull/65149) `[Quantization][Fusion] Extend manual activation fusion to more NVFP4 linear backends` | infra,nvidia,perf,quant | ? | - |
| - | [#65156](https://github.com/vllm-project/vllm/pull/65156) `[Bugfix][Frontend] Close the parent's listening sockets after launching the Rust frontend` | bug | ? | - |
| - | [#65158](https://github.com/vllm-project/vllm/pull/65158) `[CI] Add check-docstring-style pre-commit hook and use single backticks in docstrings` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#65168](https://github.com/vllm-project/vllm/pull/65168) `[Fast start] Pluggable shared stores for daemon warmup caches` | infra | ? | - |
| P1 | [#65177](https://github.com/vllm-project/vllm/pull/65177) `[Bugfix][Quantization] Index INT8 MoE per-channel weight scales independently of act quant - #58570` | bug,infra,nvidia,perf,quant,rocm | ? | - |
| P0 | [#65190](https://github.com/vllm-project/vllm/issues/65190) `[ROCm][Bug] Muse Spark long-context c40 on MI350X: serial prefill and ~0 decode when the working set exceeds G` | rocm | ? | - |
| - | [#65191](https://github.com/vllm-project/vllm/pull/65191) `[CPU][Test] Add INT8 W4A8 smoke tests for Arm CPUs` | infra,quant | ? | - |
| - | [#65203](https://github.com/vllm-project/vllm/pull/65203) `[Attention] Sync FA with upstream (54b044c8)` | infra | ? | - |
| - | [#65217](https://github.com/vllm-project/vllm/pull/65217) `[Spec Decode][MRV2] Add prefill_context_kv_only for P/D prefill instances` |  | ? | - |
| - | [#65227](https://github.com/vllm-project/vllm/pull/65227) `[Perf][Multimodal] Encoder CUDA graphs: one replay per batch, finer grid up to one max budget` | nvidia,perf,rocm | ? | - |
| P1 | [#65229](https://github.com/vllm-project/vllm/pull/65229) `[Bugfix][Spec Decode] Avoid catastrophic cancellation in the acceptance estimator` | bug | ? | - |
| - | [#65235](https://github.com/vllm-project/vllm/pull/65235) `[RL][Model Loader] Load plan: plan_loads and TraceTensor` |  | ? | - |
| P0 | [#65249](https://github.com/vllm-project/vllm/pull/65249) `[ROCm][DSv4.1] Enable prefix-cache SWA replay on gfx942` | perf,rocm | main | - |
| P1 | [#65267](https://github.com/vllm-project/vllm/pull/65267) `[Perf][ROCm][MiniMax-M3.1] Add opt-in parallel decode top-k` | infra,perf,rocm | ? | - |
| - | [#65270](https://github.com/vllm-project/vllm/pull/65270) `[MRV2][Spec Decode] Fix mixed draft-model warmup token budget` | bug | ? | - |
| P1 | [#65272](https://github.com/vllm-project/vllm/pull/65272) `[Quantization] Support ModelOpt INT8_PB_WO (per-block INT8 weight-only) linear layers` | quant | ? | - |
| P1 | [#65275](https://github.com/vllm-project/vllm/pull/65275) `[Bugfix][MRV2] Use promised max_query_len for encoder-only FULL CUDA graphs` | bug,infra,nvidia | ? | - |
| - | [#65323](https://github.com/vllm-project/vllm/pull/65323) `[XPU][UT] Preserve RoPE buffer dtype for HF reference in the privacy-filter model test on XPU` | nvidia | ? | - |
| - | [#65349](https://github.com/vllm-project/vllm/pull/65349) `[Perf] Warm up JIT kernels that only long prefills, eager drafters and constrained decoding reach` | perf | ? | - |
| P1 | [#65351](https://github.com/vllm-project/vllm/pull/65351) `[Multimodal][Bugfix] Fix Step3-VL encoder output aliasing and guard shared CUDA graph capture buffers` | bug,nvidia,rocm | ? | - |
| - | [#65363](https://github.com/vllm-project/vllm/pull/65363) `[Bugfix][Multimodal] Handle media cache eviction during reads` | bug,perf | ? | - |
| P1 | [#65373](https://github.com/vllm-project/vllm/pull/65373) `Share DeepSeek V4.1 CPU KV across TP ranks` | perf | ? | - |
| P1 | [#65386](https://github.com/vllm-project/vllm/pull/65386) `Minimax m3.1 dspark drafter monokernel` | infra | ? | - |
| - | [#65400](https://github.com/vllm-project/vllm/pull/65400) `[Recipe] Kimi-K3, MiniMax-M3.1-Flash: add Rubin VR200 support` | infra | ? | - |
| - | [#65405](https://github.com/vllm-project/vllm/issues/65405) `[Bug]: MoE w2_bias is added tp_size times under tensor parallelism` |  | ? | - |
| P1 | [#65406](https://github.com/vllm-project/vllm/pull/65406) `[Bugfix][MoE] Count the expert down-projection bias once under TP` | bug | ? | - |
| - | [#65446](https://github.com/vllm-project/vllm/pull/65446) `[torch.compile] Only flag `_buffers.update` in the cudagraph buffer assignment check` | nvidia | ? | - |
| - | [#65448](https://github.com/vllm-project/vllm/pull/65448) `[KV Connector][Spec Decode] Support lookahead block hashes in remaining KV connectors` | perf | ? | - |
| P1 | [#65461](https://github.com/vllm-project/vllm/pull/65461) `[ROCm][Perf][DSv4.1] Mono: merge K2(l) and K1(l + 1) into one launch at TP8` | infra,perf,rocm | ? | - |
| P1 | [#65463](https://github.com/vllm-project/vllm/pull/65463) `[Bugfix][KV Cache] Re-fit `--max-model-len auto` after the extensible KV cache shrinks` | bug,perf | ? | - |
| P0 | [#65465](https://github.com/vllm-project/vllm/issues/65465) `[Bug][Spec Decode][Structured Output] Reverting #54442 reopens grammar-invalid proposal acceptance in async sc` |  | ? | - |
| P1 | [#65478](https://github.com/vllm-project/vllm/pull/65478) `[ROCm][Perf][MiniMax-M3.1] Fuse the FFN-side MXFP8 activation quant into the post-attention norm and swiglu` | perf,quant,rocm | ? | - |
| P0 | [#65479](https://github.com/vllm-project/vllm/pull/65479) `[ROCm][MiniMax-M3.1] MXFP8 linear on AITER's tuned FlyDSL GEMM` | perf,quant,rocm | main | - |
| P1 | [#65481](https://github.com/vllm-project/vllm/pull/65481) `[ROCm][Perf][MiniMax-M3.1] Pick the NVFP4 sparse decode splits per XCD, not per CU` | infra,perf,quant,rocm | ? | - |
| P1 | [#65508](https://github.com/vllm-project/vllm/pull/65508) `[ROCm][Perf][MiniMax-M3.1] Emit the o_proj MXFP8 input from the NVFP4 sparse decode kernel` | perf,quant,rocm | ? | - |
| - | [#65514](https://github.com/vllm-project/vllm/pull/65514) `[CI] Run PyTorch Compilation root tests in one pytest, with test_config.py's forked tests spawned` | infra | ? | - |
| P1 | [#65517](https://github.com/vllm-project/vllm/pull/65517) `[Bugfix][ROCm][MoE] Fix tkw1 rejecting count-free expert metadata, rename AITER QuantMethod` | bug,quant,rocm | ? | - |
| - | [#65521](https://github.com/vllm-project/vllm/pull/65521) `[Perf][mHC] use FlashInfer mega mHC for MHCFusedPostPreOp (GLM-5.3-Fl…` | nvidia,perf | ? | - |
| - | [#65523](https://github.com/vllm-project/vllm/issues/65523) `[Bug]:  MiMo-V2.6 video timestamps ignore real frame times (every clip is labelled 00:00–00:30)` | bug | ? | - |
| - | [#65524](https://github.com/vllm-project/vllm/pull/65524) `[Perf][DSv4.1] Replay one row for far prefill chunks` | nvidia,perf | ? | - |
| P1 | [#65530](https://github.com/vllm-project/vllm/pull/65530) `[ROCm][Perf][MiniMax-M3.1] Retune the MXFP8 dot_scaled GEMM tiles for M=17-256` | perf,quant,rocm | ? | - |
| - | [#65531](https://github.com/vllm-project/vllm/issues/65531) `[Bug]: Precomputed image or video embeddings crash the engine when the encoder CUDA graph is on` | bug,nvidia | ? | - |
| - | [#65533](https://github.com/vllm-project/vllm/issues/65533) `[Bug]: GLM-4.7-AWQ on Blackwell (sm_120) produces degenerate/looping output on v0.25.1 but correct on v0.14.0 ` | bug,nvidia,perf,quant | ? | - |
| - | [#65535](https://github.com/vllm-project/vllm/pull/65535) `[Bugfix][Multimodal] Skip the encoder CUDA graph for precomputed embeddings` | bug,nvidia | ? | - |
| - | [#65541](https://github.com/vllm-project/vllm/pull/65541) `[Rust][Benchmark] Align vllm-bench result files and requests with Python` | perf | ? | - |
| - | [#65554](https://github.com/vllm-project/vllm/pull/65554) `[Bugfix] Fix startup illegal memory access from unaligned extensible KV cache segments` | bug,perf,risk | ? | - |
| - | [#65557](https://github.com/vllm-project/vllm/pull/65557) `[Doc] Add vllm-iluvatar core Gpu to the Vllm support list` |  | ? | - |
| P1 | [#65559](https://github.com/vllm-project/vllm/pull/65559) `[ROCm][KV Offload] SimpleCPUOffload: batch copies on SDMA with hipMemcpyFlagExtPreferCE (HIP 7.16+)` | nvidia,rocm | ? | - |
| - | [#65576](https://github.com/vllm-project/vllm/pull/65576) `[docker] Install AWS EFA in the main image; build DeepEP-EFA separately` | infra,nvidia | ? | - |
| - | [#65583](https://github.com/vllm-project/vllm/pull/65583) `[Bugfix][Benchmark] Fix bench throughput crash with BlazeEdit HF datasets` | bug,perf | ? | - |
| - | [#65587](https://github.com/vllm-project/vllm/issues/65587) `[Bug]: VLLM_BATCH_INVARIANT=1 is not batch-invariant for Gemma-2-9B on H100 (FlashAttention sliding-window pat` | bug,nvidia | ? | - |
| - | [#65589](https://github.com/vllm-project/vllm/pull/65589) `[Perf][Startup] Don't import vllm.parser from vllm.v1.structured_output` | perf | ? | - |
| P1 | [#65599](https://github.com/vllm-project/vllm/pull/65599) `[ROCm][Step5] Use one warp for CSA prefill sparse attention on CDNA3/CDNA4` | rocm | ? | - |
| - | [#65607](https://github.com/vllm-project/vllm/pull/65607) `[Perf][HiSparse] Batch the coordinator's per-page residency bookkeeping` | perf | ? | - |
| - | [#65620](https://github.com/vllm-project/vllm/pull/65620) `[Doc] Document multimodal requirements for the Transformers modeling …` | infra | ? | - |
| - | [#65627](https://github.com/vllm-project/vllm/pull/65627) `[Bugfix][Attention] Keep FA sliding window active under batch invariance` | bug | ? | - |
| - | [#65629](https://github.com/vllm-project/vllm/pull/65629) `[Rust Frontend][Perf] Reduce per-request output channel memory` | perf | ? | - |
| - | [#65640](https://github.com/vllm-project/vllm/pull/65640) `[Bugfix][KV Offload] Refresh streaming request keys after preemption` | bug | ? | - |
| - | [#65652](https://github.com/vllm-project/vllm/pull/65652) `[torch.compile] Replace config `compute_hash` with `compile_factors`` | nvidia | ? | - |
| P1 | [#65667](https://github.com/vllm-project/vllm/pull/65667) `[Bugfix][MRV2]  Read routed experts from unkeyed full blocks` | bug,infra | ? | - |
| P1 | [#65685](https://github.com/vllm-project/vllm/pull/65685) `[Model] Kimi K3.1 Pro (split 5/6: ROCm DCP, P/D, indexer top-k)` | infra,nvidia,perf,rocm | main | - |
| - | [#65697](https://github.com/vllm-project/vllm/pull/65697) `[Bugfix][Frontend] Count prompts over max_model_len in Anthropic count_tokens` | bug | ? | - |
| - | [#65704](https://github.com/vllm-project/vllm/pull/65704) `[Bugfix][GLM-5.3] Build the MTP eh_proj low-latency GEMM plan` | bug,infra,perf | ? | - |
| P1 | [#65710](https://github.com/vllm-project/vllm/pull/65710) `[Bugfix][Structured Output] Handle EOS in speculative Guidance batches` | bug | ? | - |
| P0 | [#65722](https://github.com/vllm-project/vllm/pull/65722) `[Bugfix][ROCm] Stop AITER FA from skipping 1-token prompts in prefill/extend` | bug,rocm | main | - |
| - | [#65724](https://github.com/vllm-project/vllm/pull/65724) `[MM] Support mm_device_do_normalize for Gemma 4 Unified` |  | ? | - |
| - | [#65725](https://github.com/vllm-project/vllm/pull/65725) `[Recipe] Kimi-K3.1-Pro: add TPU serving via vllm-torchtpu` | infra | ? | - |
| - | [#65733](https://github.com/vllm-project/vllm/pull/65733) `[CI] Make DSpark sharded-sampling test deterministic under torch.compile` | infra | ? | - |
| - | [#65735](https://github.com/vllm-project/vllm/pull/65735) `[Model] Add transcription to the Transformers modeling backend` |  | ? | - |
| - | [#65743](https://github.com/vllm-project/vllm/pull/65743) `[Refactor] Remove dead code kernels` | perf,quant | ? | - |
| - | [#65744](https://github.com/vllm-project/vllm/pull/65744) `[Bugfix][Frontend] Normalize Chat Completions tools and tool_choice validation` | bug | ? | - |
| - | [#65746](https://github.com/vllm-project/vllm/pull/65746) `[GLM 5.3 Perf] Expand fp8 moe tma for sm100, 1.03~1.60x kernel performance improvement` | nvidia,perf,quant | ? | - |
| P1 | [#65755](https://github.com/vllm-project/vllm/pull/65755) `[Bugfix][Step5] Fix FP32 residual truncation at pipeline boundaries` | bug,risk | ? | - |
| - | [#65765](https://github.com/vllm-project/vllm/pull/65765) `[CI/Build][NVIDIA] Move Rubin nightly images to CUDA 13.5` | infra,nvidia | ? | - |
| - | [#65766](https://github.com/vllm-project/vllm/pull/65766) `[DeepSeek-V4] Support sequence parallelism with pipeline parallelism for MegaMoE` |  | ? | - |
| - | [#65768](https://github.com/vllm-project/vllm/pull/65768) `[Perf][Rust][Benchmark] Reuse allowed tokens in multi-turn generation` | perf | ? | - |
| - | [#65778](https://github.com/vllm-project/vllm/pull/65778) `[Bugfix][Multimodal] Fix FlashInfer ViT attention for GLM-4.1V, GLM-OCR and GLM-5.3-Flash` | bug,nvidia | ? | - |
| - | [#65791](https://github.com/vllm-project/vllm/pull/65791) `[Perf] Vectorize silu_and_mul_per_block_quant for large inputs` | perf,quant | ? | - |
| P1 | [#65792](https://github.com/vllm-project/vllm/pull/65792) `[BugFix][DP] Hash the parallel config before engine init for DP validation` | bug | ? | - |
| - | [#65804](https://github.com/vllm-project/vllm/pull/65804) `[Spec Decode] Treat standalone draft model prefill as decode` |  | ? | - |
| - | [#65808](https://github.com/vllm-project/vllm/pull/65808) `[Bugfix] Fix DP ViT all-gather dtype mismatch when the first parameter is fp32` | bug | ? | - |
| - | [#65811](https://github.com/vllm-project/vllm/issues/65811) `[Bug]: Qwen3.5-122B + LoRA crashes at startup: _inject_lora_into_fused_moe asserts TritonExperts, but FlashInf` | bug,nvidia,perf | ? | - |
| P1 | [#65816](https://github.com/vllm-project/vllm/pull/65816) `[Bugfix][DeepSeek-V4] Share the target embedding with the MTP drafter under PP` | bug | ? | - |
| - | [#65818](https://github.com/vllm-project/vllm/pull/65818) `[Bugfix] Fix Granite 4.1 Vision deepstack handoff between pipeline stages` | bug | ? | - |
| P0 | [#65822](https://github.com/vllm-project/vllm/pull/65822) `[Perf][KV Connector][ROCm] MoRIIO WRITE: skip blocks the decoder prefix cache already holds` | perf,rocm | main | - |
| - | [#65826](https://github.com/vllm-project/vllm/pull/65826) `[Model] Add LFM3-Text` |  | ? | - |
| - | [#65827](https://github.com/vllm-project/vllm/pull/65827) `[Model] Add LFM3-VL` |  | ? | - |
| - | [#65828](https://github.com/vllm-project/vllm/pull/65828) `[Model] Add LFM3-Audio` |  | ? | - |
| P1 | [#65831](https://github.com/vllm-project/vllm/pull/65831) `[Perf][Core] Reduce per-block CPU cost of KV block allocation and caching` | perf | ? | - |
| - | [#65840](https://github.com/vllm-project/vllm/pull/65840) `[XPU][Kimi-K3] Run KDA metadata tests on XPU` | nvidia | ? | - |
| P1 | [#65842](https://github.com/vllm-project/vllm/pull/65842) `[Bugfix][MoE] Only divide shared expert output in FP16 for models that compensate` | bug | ? | - |
| - | [#65848](https://github.com/vllm-project/vllm/pull/65848) `[Model] Add Ling VL video, YaRN, and vision DP support` | infra | ? | - |
| - | [#65856](https://github.com/vllm-project/vllm/issues/65856) `[Bug]: Draft-model speculative decoding exceeds the token budget during warmup` | bug | ? | - |
| - | [#65864](https://github.com/vllm-project/vllm/pull/65864) `[Rust Frontend] Return routed experts on non-streaming chat and completions` |  | ? | - |
| - | [#65866](https://github.com/vllm-project/vllm/pull/65866) `[Bugfix] Move model inspection RPC out of LLM.__repr__` | bug | ? | - |
| P1 | [#65868](https://github.com/vllm-project/vllm/issues/65868) `[Bug]: MRV2 extensible KV cache commits all KV before encoder CUDA graph capture, so cudagraph_mm_encoder OOMs` | nvidia,perf | ? | - |
| - | [#65874](https://github.com/vllm-project/vllm/pull/65874) `[Kernel][Perf] Fused GDN MTP: Support DSpark K=8 and use idle SMs at small batch sizes` | perf | ? | - |
| - | [#65877](https://github.com/vllm-project/vllm/pull/65877) `[Misc] Separate Mooncake PD and Store connectors into sibling packages` | infra | ? | - |
| - | [#65881](https://github.com/vllm-project/vllm/pull/65881) `[CI] Let ci-selector decide CMakeLists.txt changes on CUDA` | bug,infra,nvidia | ? | - |
| - | [#65888](https://github.com/vllm-project/vllm/pull/65888) `[HiSparse] Alternative to #55398: promote P/D imports into GPU pages without NIXL changes` | bug,perf | ? | - |
| - | [#65896](https://github.com/vllm-project/vllm/pull/65896) `[Perf][PP] Copy-engine PP transport, on by default where supported (NVLink only)` | infra,nvidia,perf | ? | - |
| P1 | [#65904](https://github.com/vllm-project/vllm/pull/65904) `[Model] Move MiniMax-M3 to `AutoWeightsLoader`` | quant | ? | - |
| P1 | [#65914](https://github.com/vllm-project/vllm/pull/65914) `[Model Loader] One finish for every update path; drop refresh_derived_weights` |  | ? | - |
| P0 | [#65926](https://github.com/vllm-project/vllm/pull/65926) `[Bugfix][DSv4.1] Use int64 row offsets in the K-cache gather kernels` | bug,perf | main | - |
| - | [#65930](https://github.com/vllm-project/vllm/pull/65930) `[Dependency] Upgrade FlashInfer to 0.7.3` | infra,nvidia | ? | - |
| - | [#65932](https://github.com/vllm-project/vllm/pull/65932) `[Bugfix][Frontend] Pool HF fast tokenizers in BaseRenderer so concurrent truncation stays per request` | bug,risk | ? | - |
| - | [#65934](https://github.com/vllm-project/vllm/issues/65934) `[Bug]: [InferHunt] olmo3 tool parser silently drops HTML-like plain text in streaming responses` | risk | ? | - |
| - | [#65936](https://github.com/vllm-project/vllm/pull/65936) `[Bugfix][Tool Parser] Olmo3: stream plain text that starts with "<"` | bug | ? | - |
| P1 | [#65937](https://github.com/vllm-project/vllm/pull/65937) `[ROCm] Bump AITER to v0.1.28.post1` | infra,rocm | ? | - |
| - | [#65939](https://github.com/vllm-project/vllm/pull/65939) `[Bugfix][Mooncake] Bound store prefix lookups with a circuit breaker` | bug,infra | ? | - |
| - | [#65940](https://github.com/vllm-project/vllm/pull/65940) `[ROCm][CI] Run the MI355 BF16 AR-RMS fusion E2E matrices nightly with a per-PR subset` | infra,perf,rocm | ? | - |
| - | [#65943](https://github.com/vllm-project/vllm/pull/65943) `[KVConnector] Reuse the Mooncake PD TransferEngine in the store connector` |  | ? | - |
| - | [#65945](https://github.com/vllm-project/vllm/issues/65945) `[Bug]: GPT-J silently ignores FP8 KV-cache scales from compressed-tensors (LLM Compressor) checkpoints` | perf,quant,risk | ? | - |
| - | [#65949](https://github.com/vllm-project/vllm/pull/65949) `[Bugfix] Map compressed-tensors KV-cache scale names for GPT-J` | bug,perf,quant | ? | - |
| P1 | [#65951](https://github.com/vllm-project/vllm/pull/65951) `[Bugfix][Quantization] Handle dict-valued Quark `algo_config` in `maybe_update_config`` | bug,quant,rocm | ? | - |
| P1 | [#65952](https://github.com/vllm-project/vllm/issues/65952) `[Bug]: [ROCm] GLM-5.3 TP8 hangs with MTP and CPU KV offload` | bug,rocm | ? | - |
| - | [#65955](https://github.com/vllm-project/vllm/pull/65955) `[Quantization] Avoid importing humming when resolving quantization configs` | quant | ? | - |
| - | [#65957](https://github.com/vllm-project/vllm/pull/65957) `[ROCm][CI] Cache only a ROCm stack the PR's CI pushed itself` | infra,perf,rocm | ? | - |
| P1 | [#65965](https://github.com/vllm-project/vllm/pull/65965) `[Bugfix] Apply `WeightsMapper` stacked rules last, and fix the `--mm-encoder-only` shared root check` | bug,quant | ? | - |
| - | [#65968](https://github.com/vllm-project/vllm/pull/65968) `[Docs][ROCm] Fix stale AMD recipe images for GLM-5 and GLM-5.1` | bug,infra,rocm | ? | - |
| - | [#65971](https://github.com/vllm-project/vllm/pull/65971) `[ROCm][Kernel] Follow-ups to the gfx942 MLA Triton verify kernel` | perf,rocm | ? | - |
| - | [#65972](https://github.com/vllm-project/vllm/pull/65972) `[Perf][MoE] Skip DP padding rows in TRT-LLM monolithic MoE with vLLM's top-k` | nvidia,perf | ? | - |
| - | [#65975](https://github.com/vllm-project/vllm/pull/65975) `[Perf][Quantization] Use fast SiLU intrinsics in Humming MoE activations` | perf,quant | ? | - |
| - | [#65976](https://github.com/vllm-project/vllm/pull/65976) `[Bugfix][Frontend] Reject Anthropic max_tokens=0 prewarm with an actionable error` | bug | ? | - |
| - | [#65977](https://github.com/vllm-project/vllm/pull/65977) `[Misc] Add NIXL team to nixl label` | infra | ? | - |
| - | [#65979](https://github.com/vllm-project/vllm/pull/65979) `[CI] Enroll Language Models (Extended Generation) in automatic sharding; spawn in test_gemma's dummy-loader te` | infra | ? | - |
| - | [#65983](https://github.com/vllm-project/vllm/pull/65983) `[Bugfix][Model] Build the tied embedding on the last PP rank for ERNIE 4.5 MoE and Falcon-H1` | bug,infra | ? | - |
| - | [#65987](https://github.com/vllm-project/vllm/pull/65987) `[Bugfix] Make fused MoE expert weights contiguous before GPU copy in Llama-4` | bug,perf | ? | - |
| - | [#65988](https://github.com/vllm-project/vllm/pull/65988) `[ROCm][CI] Let /ci rocm cache start its main build on AMD CI` | infra,perf,rocm | ? | - |
| P1 | [#65989](https://github.com/vllm-project/vllm/pull/65989) `[Bugfix][Gemma4] Read per-layer embeddings on later pipeline stages` | bug | ? | - |
| - | [#65993](https://github.com/vllm-project/vllm/pull/65993) `[Rust Frontend] Multimodal and LoRA in the engine-free renderer` |  | ? | - |
| - | [#65994](https://github.com/vllm-project/vllm/pull/65994) `[Rust Frontend][gRPC] Add the Render service with RenderChat` |  | ? | - |
| P0 | [#65995](https://github.com/vllm-project/vllm/pull/65995) `[Bugfix][ROCm] Support AITER's preload() in FlyDSL INT4 QuickReduce init` | bug,quant,rocm | main | - |
| - | [#65996](https://github.com/vllm-project/vllm/pull/65996) `[Bugfix][MRV2] Build multimodal prefix-LM attention ranges on every PP stage` | bug,infra | ? | - |
| P1 | [#65998](https://github.com/vllm-project/vllm/pull/65998) `[ROCm] Revert #59420: pass the (B, next_n) context lengths to AITER as is` | rocm | ? | - |
| - | [#66000](https://github.com/vllm-project/vllm/pull/66000) `[Bugfix][Step5][Spec Decode] Skip VllmConfig re-validation for the MTP draft config` | bug | ? | - |
| - | [#66005](https://github.com/vllm-project/vllm/pull/66005) `[CI][Frontend] Pin the derender n2 parity cases to top-1 sampling` | infra | ? | - |
| - | [#66006](https://github.com/vllm-project/vllm/issues/66006) `[Bug]: With `HF_HUB_OFFLINE=1`, a Hub-ID speculative draft model logs `ERROR ... Error retrieving safetensors:` |  | ? | - |
| - | [#66007](https://github.com/vllm-project/vllm/pull/66007) `[Bugfix][Model] Fix GraniteMoeHybrid pipeline-parallel startup` | bug | ? | - |
| - | [#66010](https://github.com/vllm-project/vllm/pull/66010) `[Sleep Mode] Level 2 discards only parameters` | bug | ? | - |
| - | [#66012](https://github.com/vllm-project/vllm/pull/66012) `[Bugfix] Do not retry safetensors metadata lookup in offline mode` | bug | ? | - |
| - | [#66015](https://github.com/vllm-project/vllm/pull/66015) `[Bugfix][MoE] Stop DeepGEMM's MLOPart helper once MegaMoE caches its SM map` | bug | ? | - |
| - | [#66016](https://github.com/vllm-project/vllm/pull/66016) `[Build][Bugfix] Never fall back from an x.yf CUDA arch to a lower minor` | bug,infra,nvidia | ? | - |
| - | [#66017](https://github.com/vllm-project/vllm/pull/66017) `[Bugfix][Qwen3-Omni] Size the video encoder budget from the processor's video limits` | bug | ? | - |
| P1 | [#66018](https://github.com/vllm-project/vllm/pull/66018) `[Attention][MiniMax-M3] Add FlashInfer MSA backend for SM90 and SM120/SM121` | nvidia | ? | - |
| - | [#66019](https://github.com/vllm-project/vllm/pull/66019) `[CI][KV Offload] Pin GPU block size in test_p2p_cache_reset_with_absent_decoder` | infra | ? | - |
| - | [#66021](https://github.com/vllm-project/vllm/pull/66021) `[Perf][RL] Validate sparse weight patches in one pass` | perf | ? | - |
| - | [#66024](https://github.com/vllm-project/vllm/issues/66024) `[CI Failure]: Entrypoints Integration - test_derender_parity.py::test_inline_derender_parity[n2]` | infra | ? | - |
| - | [#66028](https://github.com/vllm-project/vllm/pull/66028) `[Rust Frontend] Kimi K3.1 chat renderer (Kimi K3.1 split 2/5)` |  | ? | - |
| - | [#66029](https://github.com/vllm-project/vllm/pull/66029) `[XPU] increase gpu_memory_utilization for test_granite4_vision.py` | nvidia | ? | - |
| - | [#66030](https://github.com/vllm-project/vllm/pull/66030) `[Model] Kimi K3.1: model files and NVIDIA specialized decode (Kimi K3.1 split 1/5)` | infra,nvidia,perf | ? | - |
| - | [#66034](https://github.com/vllm-project/vllm/pull/66034) `[XPU][CI]Migrate several B70 jobs from intel_gpu to intel_gpu_k8s` | infra,nvidia | ? | - |
| P1 | [#66036](https://github.com/vllm-project/vllm/pull/66036) `[ROCm][DSv4/4.1] Enable Tensor scale FP8 KV Cache for Sparse MLA` | nvidia,perf,quant,rocm | ? | - |
| - | [#66037](https://github.com/vllm-project/vllm/pull/66037) `[Core][Kimi K3.1] KV cache and attention changes to serve Kimi K3.1 at TP8 (Kimi K3.1 split 3/5)` | bug,nvidia,perf | ? | - |
| - | [#66039](https://github.com/vllm-project/vllm/pull/66039) `[XPU][CI] Correct deselected file path in entrypoints/scale_out test` | infra,nvidia | ? | - |
| - | [#66044](https://github.com/vllm-project/vllm/pull/66044) `[Doc][Bugfix] Fix strict docs build broken by unresolved autorefs` | bug,infra,nvidia | ? | - |
| - | [#66046](https://github.com/vllm-project/vllm/pull/66046) `[ROCm][CI] Skip the unlimited OCR tests until the ROCm CK OCR2 DASH updates land` | infra,rocm | ? | - |
| P1 | [#66047](https://github.com/vllm-project/vllm/pull/66047) `[ROCm][Perf][DSv4.1] Shard the sparse-indexer decode rows across TP` | perf,rocm | ? | - |
| P1 | [#66048](https://github.com/vllm-project/vllm/pull/66048) `[BugFix] Fix/spec decode insert resampled race` | bug,risk | ? | - |
| P1 | [#66051](https://github.com/vllm-project/vllm/pull/66051) `[ROCm][Muse Spark] DSpark Markov sampling with one launch a round (--monokernel)` | infra,rocm | ? | - |
| - | [#66062](https://github.com/vllm-project/vllm/pull/66062) `[Doc][Bugfix] Fix strict docs build broken by subclassing mocked torch classes` | bug,infra | ? | - |
| - | [#66063](https://github.com/vllm-project/vllm/pull/66063) `[Spec Decode][PP] Run draft models as a single pipeline stage` | bug,infra,perf | ? | - |
| P1 | [#66064](https://github.com/vllm-project/vllm/pull/66064) `[Perf][GDN] Fuse prefill state gather/scatter with the shared Triton kernels` | infra,perf,rocm | ? | - |
| - | [#66073](https://github.com/vllm-project/vllm/pull/66073) `[Multimodal] Add keyframe-aware sampling to PyNvVideoCodec backend` |  | ? | - |
| - | [#66079](https://github.com/vllm-project/vllm/pull/66079) `[CI][Bugfix] Fix EmbeddingGemma2 encoder contract test after Gemma-4 DP encoder` | bug,infra | ? | - |
| - | [#66080](https://github.com/vllm-project/vllm/pull/66080) `[Bugfix][DeepGEMM] Match relax warmup M values to the vendored SM100 heuristic` | bug,nvidia | ? | - |
| P1 | [#66081](https://github.com/vllm-project/vllm/pull/66081) `[Bugfix][Spec Decode] Fix non-deferred structured-output draft retrieval` | bug | ? | - |
| - | [#66092](https://github.com/vllm-project/vllm/pull/66092) `[Doc] Raise the bar for in-tree kernel translation units` | perf | ? | - |
| - | [#66097](https://github.com/vllm-project/vllm/pull/66097) `[Model] Use the upstream config for Qwen3-ASR` |  | ? | - |
| - | [#66100](https://github.com/vllm-project/vllm/pull/66100) `[CPU][Refactor] Move CPU ops wrappers to vllm/_cpu_ops.py` | infra,perf | ? | - |
| - | [#66103](https://github.com/vllm-project/vllm/pull/66103) `[Rust Frontend] Join text parts in the renderer for DeepSeek V3.2 and /v1/responses` |  | ? | - |
| - | [#66104](https://github.com/vllm-project/vllm/pull/66104) `[Rust Frontend] Export vllm:request_render_duration_seconds` |  | ? | - |
| - | [#66105](https://github.com/vllm-project/vllm/pull/66105) `[Rust Frontend] Export SimpleCPUOffload KV connector metrics` |  | ? | - |
| - | [#66106](https://github.com/vllm-project/vllm/pull/66106) `[Rust Frontend] Support tool_reference content parts` |  | ? | - |
| - | [#66107](https://github.com/vllm-project/vllm/pull/66107) `[Rust Frontend] Accept `spaces_between_special_tokens` as a no-op` |  | ? | - |
| - | [#66111](https://github.com/vllm-project/vllm/pull/66111) `[CI] Reuse the HF reference across use_prompt_embeds` | infra | ? | - |
| - | [#66117](https://github.com/vllm-project/vllm/pull/66117) `[Bugfix][Frontend] Reject translation on models that cannot translate` | bug | ? | - |
| - | [#66119](https://github.com/vllm-project/vllm/pull/66119) `[Rust Frontend] Support --log-level and --logging-config` |  | ? | - |
| - | [#66123](https://github.com/vllm-project/vllm/pull/66123) `[Bugfix] Preserve embedding size overrides` | bug | ? | - |
| - | [#66125](https://github.com/vllm-project/vllm/pull/66125) `[XPU] skip test_online_hadamard_target_wraps_resolved_method UT` | nvidia | ? | - |
| - | [#66139](https://github.com/vllm-project/vllm/pull/66139) `[Model][Quantization] Muse Spark: online FP8 routed experts (fp8_per_channel) on Hopper` | infra,nvidia,quant | ? | - |
| P0 | [#66141](https://github.com/vllm-project/vllm/issues/66141) `[Bug][ROCm]: ROCM_AITER_MLA can select an aiter MLA decode kernel that silently returns uncorrelated output (g` | perf,quant,risk,rocm | ? | - |
| - | [#66165](https://github.com/vllm-project/vllm/pull/66165) `[Sleep] Warn when level-2 sleep discards draft weights` |  | ? | - |
| - | [#66175](https://github.com/vllm-project/vllm/pull/66175) `[CI] Recompile the KV connector lock against the raised opentelemetry floors` | infra | ? | - |
| - | [#66177](https://github.com/vllm-project/vllm/pull/66177) `[Spec Decode][PP] Centralize auxiliary hidden-state relay` | nvidia,perf | ? | - |
| - | [#66187](https://github.com/vllm-project/vllm/pull/66187) `[Rust Frontend] Accept media_io_kwargs video fps over gRPC` |  | ? | - |
| - | [#66188](https://github.com/vllm-project/vllm/pull/66188) `[Recipe][ROCm] MiniMax-M3.1-Flash MI355X AgentX: nightly image and the opt-in optimizations` | infra,perf,rocm | ? | - |
| - | [#66189](https://github.com/vllm-project/vllm/pull/66189) `[ROCm][CI] Wait for DPX GPU lock to avoid collisions` | infra,rocm | ? | - |
| - | [#66190](https://github.com/vllm-project/vllm/pull/66190) `[Bugfix][Qwen2.5-Omni] Size the video encoder budget from the processor's video limits` | bug | ? | - |
| - | [#66195](https://github.com/vllm-project/vllm/issues/66195) `[Bug]: Block-FP8 Triton fused_moe_kernel fails to compile with Triton 3.9 since #64760 (`too many indices for ` | perf,quant,rocm | ? | - |
| - | [#66196](https://github.com/vllm-project/vllm/pull/66196) `[CI] Run the NIXL PD accuracy core sweep as pytest and shard it` | infra,risk | ? | - |
| - | [#66197](https://github.com/vllm-project/vllm/pull/66197) `[Bugfix] Exclude FlashInfer autotune peak from KV cache sizing` | bug,nvidia,perf | ? | - |
| - | [#66201](https://github.com/vllm-project/vllm/pull/66201) `[Bugfix][Model] MiMo-V2 omni: label video grids with the sampled frames' media time` | bug | ? | - |
| - | [#66203](https://github.com/vllm-project/vllm/pull/66203) `[Doc][Recipe] Muse Spark Open: DSpark + specialized decode mode; gate Kimi-K3.1 low-latency decode off AMD` | infra,perf,rocm | ? | - |
| - | [#66205](https://github.com/vllm-project/vllm/pull/66205) `[ROCm][CI] Fix skip condition for test_block_fp8.py ` | bug,infra,rocm | ? | - |
| - | [#66206](https://github.com/vllm-project/vllm/pull/66206) `[ROCm][Test] Cover the MXFP4 W4A16 intermediate pad that reaches AITER` | quant,rocm | ? | - |
| - | [#66207](https://github.com/vllm-project/vllm/pull/66207) `[CI] Fix B200 nightly gsm8k evals: ReplaySSM and DeepEP LL` | bug,infra,nvidia | ? | - |
| - | [#66217](https://github.com/vllm-project/vllm/pull/66217) `[ROCm][CI] Set speculative_config in test_rocm_triton_attn_dsv4.py to fix (MI355 DPX) Attention Kernels Shard ` | bug,infra,perf,rocm | ? | - |
| - | [#66219](https://github.com/vllm-project/vllm/pull/66219) `[ROCm][Perf][GLM-5.3-Flash] Keep the fused gated RMSNorm for the KDA o_norm` | perf,rocm | ? | - |
| - | [#66222](https://github.com/vllm-project/vllm/pull/66222) `[Rust Frontend] Match response_template regexes with PCRE2 in the hf parser` |  | ? | - |
| - | [#66224](https://github.com/vllm-project/vllm/pull/66224) `[Core] Simplify `prefill_schedule_interval` outside data parallelism` |  | ? | - |
| - | [#66227](https://github.com/vllm-project/vllm/pull/66227) `[Perf][MiniMax-M3] Warm up DeepGEMM NVFP4 MegaMoE kernels before serving` | perf,quant | ? | - |
| - | [#66228](https://github.com/vllm-project/vllm/pull/66228) `[Build][MiniMax-M3] Bump fmha_sm100 to 51f4f5c` | infra,nvidia | ? | - |
| - | [#66238](https://github.com/vllm-project/vllm/pull/66238) `[CPU][recipes] Add Qwen3-VL-4B-Instruct support for Intel Xeon 6` | infra | ? | - |
| - | [#66239](https://github.com/vllm-project/vllm/issues/66239) `[Bug][KV Offload] FS tier reports EIO instead of ENOSPC when the disk fills` | bug | ? | - |
| - | [#66243](https://github.com/vllm-project/vllm/issues/66243) `[Bug][Model] dots.ocr/dots.mocr: vision tower host syncs make the model untestable under VLLM_GPU_SYNC_CHECK` | rocm | ? | - |
| - | [#66244](https://github.com/vllm-project/vllm/issues/66244) `[Bug]: Qwen2.5-0.5B crashes with CUDA illegal memory access during initialization warmup` | bug,nvidia,risk | ? | - |
| - | [#66257](https://github.com/vllm-project/vllm/pull/66257) `[Security] Require native chat encoding in Kimi K3 mode` |  | ? | - |
| - | [#66263](https://github.com/vllm-project/vllm/pull/66263) `[Bugfix] Do not initialize CUDA when importing vendored FLA` | bug,nvidia | ? | - |
| - | [#66266](https://github.com/vllm-project/vllm/issues/66266) `[Transformers v5] Restore PaddleOCR-VL generation tests with a native HF reference` |  | ? | - |
| - | [#66267](https://github.com/vllm-project/vllm/pull/66267) `[Test] Restore PaddleOCR-VL generation coverage on Transformers v5` |  | ? | - |
| - | [#66268](https://github.com/vllm-project/vllm/pull/66268) `[Recipe][ROCm] MiniMax-M3.1-Flash MI355X AgentX PD disaggregation over MoRI-IO` | infra,rocm | ? | - |
| - | [#66273](https://github.com/vllm-project/vllm/pull/66273) `[Kimi-K3] Keep the latent-MoE tail fusion under sleep mode` | perf | ? | - |
| - | [#66274](https://github.com/vllm-project/vllm/pull/66274) `[Bugfix] Broadcast scalar block scales in Triton fused MoE` | bug,perf,quant,rocm | ? | - |
| - | [#66287](https://github.com/vllm-project/vllm/pull/66287) `[Sleep Mode] Remove level-2 workarounds that #66010 makes unnecessary` | quant | ? | - |
| - | [#66288](https://github.com/vllm-project/vllm/issues/66288) `[Bug]: Qwen3.5 RMSNorm JIT-compiles FlashInfer kernels on sm75 (T4)` | nvidia,perf | ? | - |
| - | [#66289](https://github.com/vllm-project/vllm/pull/66289) `[Bugfix][Qwen3.5] Replace FlashInfer GemmaRMSNorm JIT with Triton for arch<sm80` | bug,nvidia,rocm | ? | - |
| - | [#66291](https://github.com/vllm-project/vllm/pull/66291) `[CI][Test] Add pipeline-parallel equivalence tests for text models` | infra | ? | - |
| - | [#66292](https://github.com/vllm-project/vllm/pull/66292) `[GLM 5.3 Perf] enable fp8 kv cache for glm 5.3 flash draft model, 790MB GPU memory saved each rank` | perf,quant | ? | - |
| - | [#66297](https://github.com/vllm-project/vllm/pull/66297) `[ROCm][CI] Make Zen5 CPU tests optional` | infra,rocm | ? | - |
| - | [#66306](https://github.com/vllm-project/vllm/pull/66306) `[CI][ROCm] Run EP Weight Filter with EPLB on MI355` | infra,rocm | ? | - |
| - | [#66307](https://github.com/vllm-project/vllm/pull/66307) `[CI][ROCm] Add AMD HC kernel tests for Qwen4 Exp and mirror the B200 HC step` | infra,nvidia,perf,rocm | ? | - |
| - | [#66308](https://github.com/vllm-project/vllm/pull/66308) `[CI][ROCm] Mirror BF16x3 Router GEMM Kernels on MI355` | infra,perf,rocm | ? | - |
| - | [#66309](https://github.com/vllm-project/vllm/pull/66309) `[ROCm][CI] Run XPress on MI355 with a GEMM latent MLP and mirror its nightly` | infra,rocm | ? | - |
| - | [#66310](https://github.com/vllm-project/vllm/pull/66310) `[CI][ROCm] Mirror MiniMax-M3 Model Tests on MI355` | infra,rocm | ? | - |
| - | [#66311](https://github.com/vllm-project/vllm/issues/66311) `[Feature]: EAGLE-3 / DSpark support (aux hidden states) for Lfm3ForCausalLM` |  | ? | - |
| - | [#66312](https://github.com/vllm-project/vllm/pull/66312) `[CI][ROCm] Add an AMD mirror for the DeepGEMM kernels step with AITER block-FP8 tests` | infra,perf,quant,rocm | ? | - |
| - | [#66313](https://github.com/vllm-project/vllm/pull/66313) `[Deps] Bump tensorizer to 2.12.1 for Python 3.14` | infra,rocm | ? | - |
| - | [#66315](https://github.com/vllm-project/vllm/pull/66315) `[Bugfix][Mamba] Validate CLI stochastic rounding against the platform` | bug | ? | - |
| - | [#66316](https://github.com/vllm-project/vllm/pull/66316) `[CI][ROCm] Mirror LM Eval ReplaySSM on MI355` | infra,rocm | ? | - |
| - | [#66318](https://github.com/vllm-project/vllm/pull/66318) `[Kernel][Mamba] Support Mamba2 ReplaySSM speculative decoding on the Triton backend` | infra,perf,rocm | ? | - |
| - | [#66319](https://github.com/vllm-project/vllm/pull/66319) `[ROCm][Mamba] Support Mamba cache stochastic rounding on gfx950` | infra,perf,rocm | ? | - |
| - | [#66321](https://github.com/vllm-project/vllm/pull/66321) `[ROCm][CI] Support prefill context parallel for GLM-5.2 sparse MLA and mirror LM Eval PCP` | infra,rocm | ? | - |
| - | [#66325](https://github.com/vllm-project/vllm/pull/66325) `[Perf][Frontend] Trim per-chunk and per-request work in the completions stream` | perf | ? | - |
| - | [#66328](https://github.com/vllm-project/vllm/pull/66328) `[CI][ROCm] Force fork in test_preprocess_error_handling` | infra,rocm | ? | - |
| - | [#66329](https://github.com/vllm-project/vllm/pull/66329) `[CI][ROCm][UMBP] Run the load setup store outside the 200 ms runtime` | infra,rocm | ? | - |
| - | [#66334](https://github.com/vllm-project/vllm/pull/66334) `[Model] Muse Spark Open Cleanup` | nvidia,perf,rocm | ? | - |
| - | [#66338](https://github.com/vllm-project/vllm/pull/66338) `[CI][ROCm] Restore the AMD mirror of Fault Tolerance E2E` | infra,rocm | ? | - |
| - | [#66343](https://github.com/vllm-project/vllm/pull/66343) `[Recipe] Kimi-K3.1-Pro: add MI355X concurrency-1 preset, align with InferenceX#4887` | infra,rocm | ? | - |
| - | [#66348](https://github.com/vllm-project/vllm/pull/66348) `[Bugfix] granite_20b_fc: render conversations that carry a system message` | bug | ? | - |
| - | [#66349](https://github.com/vllm-project/vllm/issues/66349) `[Bug]: granite_20b_fc chat template fails to render any conversation with a system message` |  | ? | - |
| - | [#66350](https://github.com/vllm-project/vllm/pull/66350) `[Bugfix][ROCm] Let the FP8 MoE oracle fall back when the global AITER flag can't serve the layer` | bug,quant,rocm | ? | - |
| - | [#66358](https://github.com/vllm-project/vllm/pull/66358) `[CI] Fix ruff on main after dots_ocr test change` | bug,infra | ? | - |
| - | [#66362](https://github.com/vllm-project/vllm/issues/66362) `[Bug][XPU]: Expert weights transposed twice with vllm_xpu_kernels 0.1.17` | nvidia | ? | - |
| - | [#66370](https://github.com/vllm-project/vllm/pull/66370) `[Bugfix][Core] Re-prepare model state after extensible KV cache extension (Kimi-K3 AMD specialized decode)` | bug,perf,rocm | ? | - |
| - | [#66377](https://github.com/vllm-project/vllm/issues/66377) `[Bug]: Async EPLB worker asserts `device_index is not None` on Ascend NPU` |  | ? | - |
| - | [#66380](https://github.com/vllm-project/vllm/pull/66380) `[Bugfix][Rust Frontend] Don't reopen reasoning after the prompt closed it` | bug | ? | - |
| - | [#66384](https://github.com/vllm-project/vllm/pull/66384) `[KV Connector] Mooncake Store: keep a request re-admitted in the step that reports its preemption` |  | ? | - |
| - | [#66388](https://github.com/vllm-project/vllm/pull/66388) `[Model] Use the upstream config for MOSS-Transcribe-Diarize` |  | ? | - |
| - | [#66390](https://github.com/vllm-project/vllm/pull/66390) `[Bugfix][Model] Avoid host synchronization in dots.ocr vision encoder` | bug | ? | - |
| - | [#66391](https://github.com/vllm-project/vllm/pull/66391) `[Perf][KV Offload] Split the shared Tiering region and skip the scheduler pre-fault` | perf | ? | - |
| - | [#66393](https://github.com/vllm-project/vllm/pull/66393) `[Transformers backend] Migrate Gemma and StableLM` |  | ? | - |
| - | [#66397](https://github.com/vllm-project/vllm/pull/66397) `[ROCm][Bugfix] Build DSv4.1 replay builders at warmup and the DSv4/DSv4.1 mono runner at load` | bug,infra,rocm | ? | - |
| - | [#66398](https://github.com/vllm-project/vllm/pull/66398) `[ROCm][Bugfix] Stash DiffusionGemma logprobs on device without host syncs` | bug,perf,rocm | ? | - |
| - | [#66399](https://github.com/vllm-project/vllm/pull/66399) `[ROCm][Bugfix] Remove step-path GPU syncs in EPLB skip-rearrange, AITER GDN prefill metadata, Moondream3 BOS a` | bug,quant,rocm | ? | - |
| P0 | [#66400](https://github.com/vllm-project/vllm/pull/66400) `[ROCm][Bugfix] Drop sparse MLA metadata host sync; use persistent AITER for gfx950 long BF16 prefills` | bug,rocm | main | - |
| - | [#66402](https://github.com/vllm-project/vllm/issues/66402) `[Bug]: prompt_text is null when return_prompt_text is used with reused kv_transfer_params.prompt_token_ids` | bug | ? | - |
| - | [#66403](https://github.com/vllm-project/vllm/pull/66403) `[Bugfix][Frontend] Render messages for return_prompt_text with reused prompt token ids` | bug | ? | - |
| - | [#66412](https://github.com/vllm-project/vllm/pull/66412) `[CI][KV Connector] Shard the NIXL PD accuracy core sweep and use decode-only CUDA graphs` | infra,nvidia,risk | ? | - |
| - | [#66413](https://github.com/vllm-project/vllm/pull/66413) `[Transformers backend] Support LoRA on lm_head and on any input embedding name` |  | ? | - |
| - | [#66414](https://github.com/vllm-project/vllm/pull/66414) `[CI] Rebalance Arm CPU test shards` | infra | ? | - |
| - | [#66417](https://github.com/vllm-project/vllm/pull/66417) `[Bugfix][Pooling] Keep CLIP and SigLIP special tokens for chat text embeddings` | bug | ? | - |
| - | [#66419](https://github.com/vllm-project/vllm/pull/66419) `[Bugfix][Offload] Apply --cpu-offload-gb to models served by the Transformers modeling backend` | bug | ? | - |
| - | [#66422](https://github.com/vllm-project/vllm/issues/66422) `[Bug]: Cross-Request Multimodal Cache Poisoning via Untagged Identifiers in vLLM` | bug,perf | ? | - |
| - | [#66425](https://github.com/vllm-project/vllm/pull/66425) `[CI][Deps] Bump truststore to 0.10.5 to stop the OpenSSL segfault in HF downloads` | bug,infra,risk | ? | - |
| - | [#66432](https://github.com/vllm-project/vllm/pull/66432) `[Bugfix][Multimodal] Fill the Qwen2-VL video budget up to the context length` | bug | ? | - |
| - | [#66433](https://github.com/vllm-project/vllm/pull/66433) `[Recipe] Kimi-K3.1-Pro: add B300 AgentX presets, align with InferenceX#4871` | infra | ? | - |
| - | [#66434](https://github.com/vllm-project/vllm/pull/66434) `[CI][ROCm] Keep FLA's shared memory probe from initializing HIP` | infra,rocm | ? | - |
| - | [#66435](https://github.com/vllm-project/vllm/issues/66435) `[Bug][Spec Decode][LoRA] DFlash drafter reuses target-side LoRA metadata → CUDA illegal memory access in `lora` | bug,nvidia,risk | ? | - |
| - | [#66441](https://github.com/vllm-project/vllm/pull/66441) `[CI] Fix docstring style in benchmark_batched_moe.py` | bug,infra,perf | ? | - |
| - | [#66446](https://github.com/vllm-project/vllm/pull/66446) `[XPU][CI] Keep all devices visible for external LB` | infra,nvidia | ? | - |
| - | [#66461](https://github.com/vllm-project/vllm/pull/66461) `[Bugfix][Qwen4Exp] Exclude the HC padding shard from the loaded-shard check` | bug | ? | - |
| - | [#66465](https://github.com/vllm-project/vllm/pull/66465) `[MRV2][PP] Support different CUDA graph padding across pipeline stages` | bug,infra,nvidia | ? | - |
| - | [#66473](https://github.com/vllm-project/vllm/pull/66473) `[Bugfix][Multimodal] Domain-separate content digests and caller uuids in mm hashes` | bug | ? | - |
| - | [#66476](https://github.com/vllm-project/vllm/pull/66476) `[Rust Frontend] Accept FastAPI boolean spellings for reset_connector` |  | ? | - |
| - | [#66477](https://github.com/vllm-project/vllm/pull/66477) `[Rust Frontend] Keep special tokens' spelling in logprob tokens` |  | ? | - |
| - | [#66478](https://github.com/vllm-project/vllm/pull/66478) `[Frontend] Default --enable-scale-out to VLLM_SERVER_DEV_MODE` | quant | ? | - |
| - | [#66479](https://github.com/vllm-project/vllm/pull/66479) `[CI] Enroll 4 steps in automatic sharding` | infra | ? | - |
| - | [#66480](https://github.com/vllm-project/vllm/pull/66480) `[CI] Move the MoRIIO unit tests into their own folder and shard the step` | infra,rocm | ? | - |
| - | [#66481](https://github.com/vllm-project/vllm/pull/66481) `[Frontend] Mark disabled scale-out routes in the startup route log` | quant | ? | - |
| - | [#66482](https://github.com/vllm-project/vllm/pull/66482) `[Core][Bugfix] Run the warmup dummy forward on every PP rank before the GPU sync check` | bug | ? | - |
| - | [#66483](https://github.com/vllm-project/vllm/pull/66483) `[Bench] Time target sampling in vllm bench forward` | perf | ? | - |
| - | [#66486](https://github.com/vllm-project/vllm/pull/66486) `[Bugfix][LoRA] Fix MoE LoRA correctness under DP + EP` | bug,nvidia | ? | - |
| - | [#66489](https://github.com/vllm-project/vllm/pull/66489) `[Bugfix][Frontend] Reject empty messages in ChatCompletionRequest` | bug | ? | - |
| - | [#66495](https://github.com/vllm-project/vllm/pull/66495) `[Bugfix][XPU] Remove CUDA-only dependencies from Unlimited-OCR-2 DASH attention` | bug,infra,nvidia | ? | - |
| - | [#66500](https://github.com/vllm-project/vllm/pull/66500) `[ROCm][DSv4.1] Look up only local Engram hashes for peer-read tables` | rocm | ? | - |
| - | [#66504](https://github.com/vllm-project/vllm/pull/66504) `[CI][Bugfix] Use a free port for the Mooncake client in the weight-cache tests` | bug,infra,perf | ? | - |
| - | [#66512](https://github.com/vllm-project/vllm/pull/66512) `[Perf][Qwen4Exp] Faster QSA kernel for large fp8 batches on Blackwell` | infra,nvidia,perf,quant | ? | - |
| - | [#66518](https://github.com/vllm-project/vllm/pull/66518) `[Refactor][SleepMode] Make CuMemAllocator helpers overridable` |  | ? | - |
| - | [#66523](https://github.com/vllm-project/vllm/pull/66523) `[Bugfix] Extensible KV cache: release warmup's blocks before CUDA graph capture` | bug,infra,nvidia,perf | ? | - |
| - | [#66528](https://github.com/vllm-project/vllm/pull/66528) `[Rust Frontend] Write tool-call arguments in the template's JSON style` |  | ? | - |
| - | [#66529](https://github.com/vllm-project/vllm/pull/66529) `[Rust Frontend] Stream DeepSeek DSML tool-call arguments` |  | ? | - |
| - | [#66530](https://github.com/vllm-project/vllm/pull/66530) `[Rust Frontend] Stream Kimi K3 tool-call arguments` |  | ? | - |
| - | [#66531](https://github.com/vllm-project/vllm/pull/66531) `[Rust Frontend] Stream MiniMax M3 tool-call arguments` |  | ? | - |
| - | [#66532](https://github.com/vllm-project/vllm/pull/66532) `[Model] Kimi K3.1: NVIDIA specialized decode and AMD model updates, ROCm TP8 support (Kimi K3.1 split 4/6)` | infra,nvidia,rocm | main | - |
| - | [#66537](https://github.com/vllm-project/vllm/pull/66537) `[Perf][MoE] Add H200 FP8 config for GLM-5.3-Flash TP8` | nvidia,perf,quant | ? | - |
| - | [#66539](https://github.com/vllm-project/vllm/pull/66539) `[Rust Frontend] Support the JSON log formatter` |  | ? | - |
| - | [#66540](https://github.com/vllm-project/vllm/pull/66540) `[Rust Frontend] Support stop strings on the generate route` |  | ? | - |
| - | [#66544](https://github.com/vllm-project/vllm/pull/66544) `[Bugfix][KV Offload] Preserve confirmed junction after lookup retry` | bug | ? | - |
| - | [#66545](https://github.com/vllm-project/vllm/pull/66545) `[Transformers backend] Support batch-sharded sampling` |  | ? | - |
| - | [#66546](https://github.com/vllm-project/vllm/pull/66546) `[Transformers backend] Support EAGLE3 aux hidden states with pipeline parallelism and layer 0` |  | ? | - |
| - | [#66548](https://github.com/vllm-project/vllm/pull/66548) `[ROCm][CI] Fix stale W4A16 intermediate_pad expectation in AITER MXFP4 padding test` | bug,infra,quant,rocm | ? | - |
| - | [#66549](https://github.com/vllm-project/vllm/pull/66549) `[Perf][GLM-5.3] Extend ShardQ token sharding to norms and A projections` | infra,perf | ? | - |
| - | [#66552](https://github.com/vllm-project/vllm/pull/66552) `[Perf][DSv4.1] Engram: 128-row lookup tiles; split GPU tables across engines` | perf | ? | - |
| - | [#66559](https://github.com/vllm-project/vllm/pull/66559) `[Transformers backend] Migrate Phi3` |  | ? | - |
| - | [#66561](https://github.com/vllm-project/vllm/pull/66561) `[Bugfix] Use max_split_size_mb:21 so freed 1-10 MiB tensors are reused` | bug | ? | - |
| - | [#66568](https://github.com/vllm-project/vllm/pull/66568) `[CI][XPU] skip one more TP=2 test in Distributed Shutdown job` | infra,nvidia | ? | - |
| - | [#66593](https://github.com/vllm-project/vllm/pull/66593) `[Spec Decode][FLy][ROCm] Normalize the top-k entropy gate and allow a FLy cost overlay with synthetic acceptan` | rocm | ? | - |
| - | [#66596](https://github.com/vllm-project/vllm/pull/66596) `[ROCm] AITER bump to v0.1.29` | infra,rocm | ? | - |
| - | [#66598](https://github.com/vllm-project/vllm/pull/66598) `[ROCm][Perf] MXFP8 native linear: 256x256x128 tile for large prefill GEMMs on gfx950` | perf,quant,rocm | ? | - |
| - | [#66603](https://github.com/vllm-project/vllm/pull/66603) `[XPU][CI]Migrate more B70 jobs from intel_gpu to intel_gpu_k8s` | infra,nvidia | ? | - |
| - | [#66604](https://github.com/vllm-project/vllm/pull/66604) `[Core][Kimi K3.1] Write draft KV at block-stride slots instead of translating slot mappings` | nvidia | ? | - |
| - | [#66605](https://github.com/vllm-project/vllm/pull/66605) `[KVConnector] Let external connectors declare KV cache memory registration` | perf | ? | - |
| - | [#66608](https://github.com/vllm-project/vllm/pull/66608) `[Bugfix][Multimodal] Pass only the video count to get_num_frames_with_most_features` | bug | ? | - |
| - | [#66611](https://github.com/vllm-project/vllm/pull/66611) `[ROCm][CI] Restore the simple-nemotron-h-8b GSM8K threshold on ROCm` | infra,rocm | ? | - |
| - | [#66616](https://github.com/vllm-project/vllm/pull/66616) `[CI] Fit the GLM-5.2 TP1-PCP4 eval's KV cache on B200` | infra,nvidia,perf | ? | - |
| - | [#66624](https://github.com/vllm-project/vllm/pull/66624) `[Bugfix][Pooling] Use the SigLIP chat template over the Gemma one for SigLIP2` | bug | ? | - |
| - | [#66625](https://github.com/vllm-project/vllm/pull/66625) `[Docs][ROCm] Add AMD verified autotrust/JEV-27B-VL recipe` | infra,rocm | ? | - |
| - | [#66638](https://github.com/vllm-project/vllm/pull/66638) `[Bugfix][Multimodal] Cache multi-page Unlimited-OCR-2 requests in the processor cache` | bug,perf | ? | - |
| - | [#66642](https://github.com/vllm-project/vllm/pull/66642) `[Recipe] Kimi-K3.1-Pro: add GB300 AgentX presets, align with InferenceX#4907` | infra,nvidia | ? | - |
| - | [#66644](https://github.com/vllm-project/vllm/pull/66644) `[ROCm][DSv4.1] Wire AITER MegaMoE into the V4.1 model` | rocm | ? | - |
| - | [#66645](https://github.com/vllm-project/vllm/pull/66645) `[CI] Split the platform and stat logger plugin tests out of Plugin Integration and shard it` | infra | ? | - |
| - | [#66646](https://github.com/vllm-project/vllm/pull/66646) `[ROCm][Disagg][CI] Set token budgets for the MiniMax-M3 wide-EP cells` | infra,rocm | ? | - |
| - | [#66652](https://github.com/vllm-project/vllm/pull/66652) `[Perf][DSv4.1] CuTe DSL mHC boundary for decode batches up to 336 tokens` | perf | ? | - |
| - | [#66654](https://github.com/vllm-project/vllm/pull/66654) `[Bugfix][DSv4.1] Avoid runtime JIT of two prefill sparse-attention kernels` | bug,perf | ? | - |
| - | [#66660](https://github.com/vllm-project/vllm/pull/66660) `[Perf][EPLB] Copy rebalanced experts back from the buffer in one launch per weight` | perf | ? | - |
| - | [#66661](https://github.com/vllm-project/vllm/pull/66661) `[Refactor] Clean up MRv1 remaining stuff` |  | ? | - |
| - | [#66669](https://github.com/vllm-project/vllm/pull/66669) `[Build][MiniMax-M3] Bump fmha_sm100 to 1443786` | infra,nvidia | ? | - |
| - | [#66674](https://github.com/vllm-project/vllm/pull/66674) `[KVConnector] Allocate the extensible KV cache exportable for EXPORTS_FD (LMCache MP)` | perf | ? | - |
| - | [#66678](https://github.com/vllm-project/vllm/pull/66678) `[CI] Run the offline examples as pytest and shard the Examples step` | infra | ? | - |
| - | [#66688](https://github.com/vllm-project/vllm/pull/66688) `[Deprecate] We will remove legacy grpc_server, api_server, and run_batch in v0.37.0.` |  | ? | - |
| - | [#66689](https://github.com/vllm-project/vllm/pull/66689) `[Docs][ROCm] Add AMD verified inclusionAI/Ming-3.0-asr-tiny recipe` | infra,rocm | ? | - |
| - | [#66690](https://github.com/vllm-project/vllm/pull/66690) `[MM] Support mm_device_do_normalize for Qwen2.5-Omni` |  | ? | - |
| - | [#66691](https://github.com/vllm-project/vllm/pull/66691) `[Frontend] Bump xgrammar to 0.2.9 and compose Lark answers as Lark` | infra | ? | - |
| - | [#66692](https://github.com/vllm-project/vllm/pull/66692) `[Rust Frontend] Bump xgrammar-structural-tag to 0.5 and compose Lark answers` | infra | ? | - |
| - | [#66693](https://github.com/vllm-project/vllm/pull/66693) `[Misc] Normalize filename by replacing typing with types.` |  | ? | - |
| - | [#66704](https://github.com/vllm-project/vllm/pull/66704) `[Misc] Warn when gpu_memory_utilization withholds memory from the extensible KV cache` | perf | ? | - |
| - | [#66710](https://github.com/vllm-project/vllm/pull/66710) `[ROCm][CI] Fix aiter sparse MLA KV-connector test after parameter rename` | bug,infra,rocm | ? | - |
| - | [#66721](https://github.com/vllm-project/vllm/pull/66721) `[Docs][ROCm] Add AMD verified ricursiveAI/Ripple-65B-Preview recipe` | infra,rocm | ? | - |
| - | [#66731](https://github.com/vllm-project/vllm/pull/66731) `[Bugfix] Size extensible KV cache reserve on the full token budget` | bug,perf | ? | - |
| - | [#66737](https://github.com/vllm-project/vllm/pull/66737) `Revert "[ZenCPU] Add zen5 CPU tests reusing the pushed zen image (#60824)"` | infra | ? | - |
| - | [#66744](https://github.com/vllm-project/vllm/pull/66744) `[Bugfix][Tests] Fix iteration-details recomputation test setup` | bug | ? | - |
| - | [#66750](https://github.com/vllm-project/vllm/issues/66750) `[CI Failure]: pre-commit undefined _start_decoding in tests/v1/core/test_scheduler.py` | infra | ? | - |
| - | [#66758](https://github.com/vllm-project/vllm/pull/66758) `[XPU] fix test_dots_ocr.py::test_dots_ocr_vision_without_host_sync` | bug,nvidia | ? | - |
| - | [#66764](https://github.com/vllm-project/vllm/pull/66764) `[Perf][Muse Spark] Fuse DSpark draft norms and Markov sampling on NVIDIA` | infra,nvidia,perf | ? | - |
| - | [#66767](https://github.com/vllm-project/vllm/pull/66767) `[Rust Frontend] Match MiniMax M3 markers by token identity` |  | ? | - |
| - | [#66773](https://github.com/vllm-project/vllm/pull/66773) `[Bugfix][Rust Frontend] Exit on permanent engine failure` | bug | ? | - |
| - | [#66777](https://github.com/vllm-project/vllm/pull/66777) `[Bugfix][Frontend] Report the matching request type's error from SageMaker /invocations` | bug | ? | - |
| - | [#66780](https://github.com/vllm-project/vllm/pull/66780) `[Rust Frontend] Carry weight versions as per-output deltas` |  | ? | - |
| - | [#66781](https://github.com/vllm-project/vllm/pull/66781) `[Rust Frontend] Run more Python server tests against the Rust frontend` | infra | ? | - |
| - | [#66784](https://github.com/vllm-project/vllm/pull/66784) `[Bugfix][Model Loader] Handle merged-linear padding for Qwen4Exp and Kimi KDA` | bug,infra | ? | - |
| - | [#66786](https://github.com/vllm-project/vllm/issues/66786) `[Bug]: Prefix cache hits always 0 on identical prompts (v0.33.0rc3, FLASH_ATTN, LBNHC KV cache layout)` | nvidia,perf | ? | - |
| - | [#66798](https://github.com/vllm-project/vllm/pull/66798) `[ROCm][CI] Stub owns_indexer and index_epoch in the merged-cache sparse MLA test` | infra,perf,rocm | ? | - |
| - | [#66803](https://github.com/vllm-project/vllm/pull/66803) `[Quantization] Skip kernel dispatch for online requantization sources` | perf,quant | ? | - |
| - | [#66809](https://github.com/vllm-project/vllm/pull/66809) `[Transformers backend] Fuse the GLU activation with the down projection's input quant` | perf,quant | ? | - |
| - | [#66810](https://github.com/vllm-project/vllm/issues/66810) `[Bug]:  --cpu-offload-gb is silently ignored with --model-impl transformers` | bug,risk | ? | - |
| - | [#66819](https://github.com/vllm-project/vllm/pull/66819) `[Bugfix][Model] Let DomynEdge mix sliding and full attention layers` | bug | ? | - |
| - | [#66824](https://github.com/vllm-project/vllm/pull/66824) `[ROCm][CI] Re-enable ROCM_AITER_UNIFIED_ATTN in Whisper transcription tests` | infra,rocm | ? | - |
| - | [#66827](https://github.com/vllm-project/vllm/pull/66827) `[Transformers backend] Serve Qwen2-MoE with the Transformers modeling backend` |  | ? | - |
| - | [#66830](https://github.com/vllm-project/vllm/pull/66830) `[CI] Enroll 7 more jobs in automatic sharding` | infra | ? | - |
| - | [#66833](https://github.com/vllm-project/vllm/pull/66833) `[Transformers backend] Fix M-RoPE models under CUDA graphs` | bug,nvidia | ? | - |
| - | [#66834](https://github.com/vllm-project/vllm/pull/66834) `[Chore] Remove the dual-chunk attention leftovers` |  | ? | - |
| - | [#66848](https://github.com/vllm-project/vllm/pull/66848) `[Bugfix][Tokenizers] Raise ValueError on unknown message role in deepseek_v41_encoding` | bug | ? | - |
| - | [#66853](https://github.com/vllm-project/vllm/pull/66853) `[Frontend] Log outputs for batched chat completions` |  | ? | - |
| - | [#66854](https://github.com/vllm-project/vllm/pull/66854) `[ROCm][CI] Add  `vllm/v1/attention/backend.py` to the :`amd: (MI355 DPX) MLA Kernels` test group in main CI` | infra,perf,rocm | ? | - |
| - | [#66855](https://github.com/vllm-project/vllm/pull/66855) `[CPU][Perf] Split oversized final attention spans` | perf | ? | - |
| - | [#66859](https://github.com/vllm-project/vllm/pull/66859) `[MoE] Replace routed-scale bool flags with a RoutedScaleMode enum` | quant | ? | - |
| - | [#66875](https://github.com/vllm-project/vllm/pull/66875) `[ROCm][Bugfix] Key the FSE MXFP8 scale-layout test check on the selected backend` | bug,quant,rocm | ? | - |
| - | [#66876](https://github.com/vllm-project/vllm/pull/66876) `[ROCm][Bugfix] Allow lut_b_moe online quantization on ROCm` | bug,quant,rocm | ? | - |
| - | [#66891](https://github.com/vllm-project/vllm/pull/66891) `[Bugfix][Frontend] Render tool-result media in the Inkling renderer` | bug | ? | - |
| - | [#66892](https://github.com/vllm-project/vllm/pull/66892) `[Attention][MiniMax-M3] Allow the BLHNC KV cache layout with an NVFP4 KV cache` | perf,quant | ? | - |
| - | [#66902](https://github.com/vllm-project/vllm/issues/66902) `[Bug]: Gemma 4: a LoRA on k_proj is not applied to the value on attention_k_eq_v layers (silent mismatch with ` | risk | ? | - |
| - | [#66910](https://github.com/vllm-project/vllm/pull/66910) `[CI] Run the NIXL PD tests as pytest and enroll every Disaggregated step` | infra | ? | - |
| - | [#66922](https://github.com/vllm-project/vllm/issues/66922) `[Installation]: Bug / Enhancement][Blackwell HGX B300] Pre-flight check for nvcc/ninja before multi-TB shard l` | nvidia | ? | - |
| - | [#66924](https://github.com/vllm-project/vllm/pull/66924) `[XPU][CI] Skip LMCacheMPConnector tests when lmcache is not installed` | infra,nvidia | ? | - |
| - | [#66952](https://github.com/vllm-project/vllm/pull/66952) `[XPU][UT] Add device-specific logic to enable DFlash MXFP8 context KV test for XPU` | nvidia,quant | ? | - |
| - | [#66973](https://github.com/vllm-project/vllm/pull/66973) `[XPU][CI]Update working_dir from /workspace/vllm to /vllm-workspace/` | infra,nvidia | ? | - |
| - | [#66978](https://github.com/vllm-project/vllm/pull/66978) `[XPU][UT] Increase the prompt length in the late chunking test to allow prefix cache hits on XPU` | nvidia,perf | ? | - |
| - | [#66979](https://github.com/vllm-project/vllm/pull/66979) `[Rust Frontend] Log the finished request count in the periodic stats line` |  | ? | - |
| - | [#66980](https://github.com/vllm-project/vllm/pull/66980) `[Rust Frontend] Resolve tool_choice without tools like Python` |  | ? | - |
| - | [#66981](https://github.com/vllm-project/vllm/pull/66981) `[XPU][Test] Make test_shardq device-agnostic` | nvidia | ? | - |
| - | [#66982](https://github.com/vllm-project/vllm/pull/66982) `[XPU][Test] Skip Unlimited-OCR-2 tests on non-CUDA platforms` | nvidia | ? | - |
| - | [#66986](https://github.com/vllm-project/vllm/pull/66986) `[Bugfix][Muse Spark] Avoid the FlashInfer Cake PDL race in gated_residual_rmsnorm` | bug,nvidia,risk | ? | - |
| - | [#66990](https://github.com/vllm-project/vllm/issues/66990) `[Feature]: EC events: publish encoder cache presence and eviction from the EC connector` | perf | ? | - |
| - | [#66994](https://github.com/vllm-project/vllm/pull/66994) `[CI][Multimodal] Run the Unlimited-OCR-2 preemption test batch-invariant` | infra | ? | - |
| - | [#67002](https://github.com/vllm-project/vllm/pull/67002) `[Bugfix] Fix M-RoPE position preparation with PCP` | bug | ? | - |
| - | [#67003](https://github.com/vllm-project/vllm/issues/67003) `[Tracking]: Llama and Qwen2 on the Transformers modeling backend` |  | ? | - |
| - | [#67005](https://github.com/vllm-project/vllm/pull/67005) `[Spec Decode] Keep dynamic speculative decoding for dense models with DP` |  | ? | - |
| - | [#67007](https://github.com/vllm-project/vllm/issues/67007) `[Bug]: Scale-out `/render` endpoints and `/inference/v1/generate` ignore the `X-Vllm-Priority` header` | bug,quant | ? | - |
| - | [#67008](https://github.com/vllm-project/vllm/pull/67008) `[Bugfix] Honor X-Vllm-Priority in scale-out generate.` | bug,quant | ? | - |
| - | [#67024](https://github.com/vllm-project/vllm/issues/67024) `[Feature]: Super Prefill: keep generating on the prefill instance while the KV cache transfers (P/D, opt-in)` | perf | ? | - |
| - | [#67026](https://github.com/vllm-project/vllm/pull/67026) `[CI] Only warn on VibeVoice-ASR mixed-length syncs before Transformers 5.23` | infra | ? | - |
| - | [#67035](https://github.com/vllm-project/vllm/pull/67035) `[Model] Remove TeleChat2 and TeleChat3` |  | ? | - |
| - | [#67038](https://github.com/vllm-project/vllm/pull/67038) `[CI][ROCm] Pin the AMD monokernel steps to explicit test files` | infra,rocm | ? | - |
| - | [#67040](https://github.com/vllm-project/vllm/pull/67040) `[Perf][GLM-5.3] DeepGEMM BF16 MegaMoE for unquantized checkpoints` | perf,quant | ? | - |
| - | [#67041](https://github.com/vllm-project/vllm/pull/67041) `[HiSparse] Revert the FlashInfer all-reduce backend override (#65201, #65522)` | nvidia | ? | - |
| - | [#67042](https://github.com/vllm-project/vllm/pull/67042) `[Dependency] Upgrade FlashInfer to 0.7.4` | infra,nvidia | ? | - |
| - | [#67050](https://github.com/vllm-project/vllm/pull/67050) `[Recipe][ROCm] MiMo-V2.6: use ROCM_AITER_UNIFIED_ATTN and add encoder-parallel opt-in` | infra,rocm | ? | - |
| - | [#67056](https://github.com/vllm-project/vllm/pull/67056) `[ROCm][DI-CI] Enable Kimi K3 in AMD DI CI pipeline for nightly runs` | infra,rocm | ? | - |
| - | [#67061](https://github.com/vllm-project/vllm/pull/67061) `[Bugfix][Spec Decode] Allow min_p and logit_bias with speculative decoding` | bug,infra | ? | - |
| - | [#67068](https://github.com/vllm-project/vllm/pull/67068) `[Bugfix][Elastic EP] Recreate stat loggers before starting new engines` | bug | ? | - |
| - | [#67071](https://github.com/vllm-project/vllm/pull/67071) `[Doc][Tests] Stop setting `gpu_memory_utilization` in most extensible KV cache cases` | infra,nvidia,perf | ? | - |
| - | [#67073](https://github.com/vllm-project/vllm/pull/67073) `[CI][ROCm] Move the AMD monokernel steps into a Monokernels test area` | infra,rocm | ? | - |
| - | [#67080](https://github.com/vllm-project/vllm/pull/67080) `[Bugfix][KV Connector] Skip Mooncake saves after failed existence checks` | bug | ? | - |
| - | [#67081](https://github.com/vllm-project/vllm/pull/67081) `[Bugfix] Remove compiled models' bytecode hooks at in-process shutdown` | bug | ? | - |
| - | [#67085](https://github.com/vllm-project/vllm/pull/67085) `[Refactor] Remove dead code models` |  | ? | - |
| - | [#67092](https://github.com/vllm-project/vllm/pull/67092) `[Docs] Remove RunLLM widget` |  | ? | - |
| - | [#67093](https://github.com/vllm-project/vllm/pull/67093) `[PP] Require exact intermediate-tensor match on every PP transport` |  | ? | - |
| - | [#67096](https://github.com/vllm-project/vllm/pull/67096) `[Bugfix] Let SIGTERM during engine startup stop the API server` | bug | ? | - |
| - | [#67098](https://github.com/vllm-project/vllm/pull/67098) `[Bugfix][KV Offload] Evict a running request’s ARC chunks tail first` | bug | ? | - |
| P1 | [#67099](https://github.com/vllm-project/vllm/pull/67099) `[GLM-5.3-Flash Perf] Enable `latency_specialized` by default, 27.0% E2E Throughput improvement` | perf | ? | - |
| - | [#67104](https://github.com/vllm-project/vllm/pull/67104) `[GLM-5.3-Flash Perf] Skip unused MTP post-attention rows, 4.2% E2E throughput improvement` | perf | ? | - |
| P1 | [#67107](https://github.com/vllm-project/vllm/pull/67107) `[ROCm][Bugfix] Route biased softmax/sigmoid top-k to AITER topk_gating` | bug,rocm | ? | - |
| - | [#67121](https://github.com/vllm-project/vllm/issues/67121) `[CI Failure]: V1 KV Connectors Shard 2/4 - test_lmcache_connector.py::test_engine_shutdown_stops_lmcache_threa` | infra | ? | - |
| - | [#67148](https://github.com/vllm-project/vllm/pull/67148) `[XPU][CI]Skip seed instability issue in Intel GPU CI ` | infra,nvidia | ? | - |
| - | [#67150](https://github.com/vllm-project/vllm/pull/67150) `[Bugfix][P/D] Proxies: return text/event-stream for streaming requests` | bug | ? | - |
| - | [#67152](https://github.com/vllm-project/vllm/pull/67152) `[Bugfix][KV Offload] Clear partial-tail pending state on a required group miss` | bug | ? | - |
| - | [#67175](https://github.com/vllm-project/vllm/pull/67175) `[Build] Bump FlashMLA to enable SM90 small-head ETAP sparse prefill` | infra,nvidia | ? | - |
| - | [#67177](https://github.com/vllm-project/vllm/issues/67177) `[Bug]:  EngineCore fails to start on SM120 (Blackwell) due to unsupported PTX toolchain in FlashAttention` | bug,nvidia | ? | - |
| - | [#67181](https://github.com/vllm-project/vllm/pull/67181) `[Bugfix][Kernel] Bump DeepGEMM for the MegaMoE combine-readiness fix under CUDA graph replay` | bug,infra,nvidia,perf | ? | - |
| - | [#67184](https://github.com/vllm-project/vllm/pull/67184) `[Recipe] MiniMax-M3.1-Flash: sync the GB300 Dynamo AgentX presets to InferenceX #4998` | infra,nvidia | ? | - |
| - | [#67187](https://github.com/vllm-project/vllm/pull/67187) `[Rust Frontend] Fail in-flight requests when an engine disconnects` |  | ? | - |
| - | [#67194](https://github.com/vllm-project/vllm/pull/67194) `[Perf][GLM-5.3] build eager attention metadata on the host for ViT` | infra,perf | ? | - |
| - | [#67196](https://github.com/vllm-project/vllm/pull/67196) `[XPU][Perf][Spec Decode] Enable triton greedy_argmax on XPU` | nvidia,perf,rocm | ? | - |
| - | [#67201](https://github.com/vllm-project/vllm/pull/67201) `[Bugfix] Reset the global CUDA graph pool on engine shutdown` | bug,infra,nvidia | ? | - |
| - | [#67205](https://github.com/vllm-project/vllm/pull/67205) `[Model Loader] Load tensorized vLLM models into the other model implementation` |  | ? | - |
| - | [#67210](https://github.com/vllm-project/vllm/pull/67210) `[Test][Model Loader] Leave reload headroom in the LoRA-MoE and online-quantize reload tests` | quant | ? | - |
| - | [#67212](https://github.com/vllm-project/vllm/pull/67212) `[Bugfix] build with param.dtype when one is not specified` | bug,infra | ? | - |
| - | [#67217](https://github.com/vllm-project/vllm/issues/67217) `[RFC] Reuse vLLM vocab-parallel TopK for DFlash2 on Ascend` |  | ? | - |
| - | [#67225](https://github.com/vllm-project/vllm/pull/67225) `[Bugfix][MoE] Skip DeepGEMM localizer cleanup on SM90` | bug,nvidia | ? | - |
| - | [#67226](https://github.com/vllm-project/vllm/pull/67226) `[ROCm][RDNA] ROCM_RDNA_ATTN: work around an LLVM VGPR regression that spills decode kernels on gfx11` | bug,perf,rocm | ? | - |
| - | [#67235](https://github.com/vllm-project/vllm/pull/67235) `[Kernel][GLM-5.3-Flash] Fused in-place q/k RMSNorm + RoPE and residual add inside RMSNorm` | perf | ? | - |
| - | [#67256](https://github.com/vllm-project/vllm/pull/67256) `[Bugfix][Rust Frontend] Resolve auxiliary frames of add requests in the mock engine` | bug | ? | - |
| - | [#67257](https://github.com/vllm-project/vllm/pull/67257) `[Rust Frontend] Return requested logprobs from the mock engine` |  | ? | - |
| - | [#67263](https://github.com/vllm-project/vllm/pull/67263) `[CI][Quantization] Skip ModelOpt INT8_PB_WO routing test on ROCm` | infra,quant,rocm | ? | - |
| - | [#67269](https://github.com/vllm-project/vllm/pull/67269) `[Recipe] Enable Muse Spark MegaMoE and B300 specialized decode` | infra | ? | - |
| - | [#67272](https://github.com/vllm-project/vllm/pull/67272) `[Recipe] MiniMax-M3.1-Flash: MI355X Agent` | infra,rocm | ? | - |
| - | [#67279](https://github.com/vllm-project/vllm/pull/67279) `[Bugfix] Clear cuBLAS workspaces at in-process shutdown to free the graph pool` | bug | ? | - |
| - | [#67280](https://github.com/vllm-project/vllm/pull/67280) `[Build] Bump vllm-flash-attn to 8dd9eaea (flash-attention#218, #208)` | infra,nvidia | ? | - |
| - | [#67286](https://github.com/vllm-project/vllm/pull/67286) `[Bugfix] Avoid duplicate values in `compile_ranges_endpoints` for compilation config` | bug | ? | - |
| - | [#67288](https://github.com/vllm-project/vllm/pull/67288) `[Bugfix][Benchmark] Fix prefix_repetition crash and custom_audio --output-len in bench throughput` | bug,perf | ? | - |
| - | [#67295](https://github.com/vllm-project/vllm/pull/67295) `[Misc] Fix override and context manager type annotations` | bug,nvidia,quant | ? | - |
| - | [#67296](https://github.com/vllm-project/vllm/pull/67296) `[Bugfix] Keep extensible KV cache headroom for measured allocator fragmentation` | bug,perf | ? | - |
| - | [#67304](https://github.com/vllm-project/vllm/pull/67304) `Delete tools/flashinfer-build.sh` | infra,nvidia | ? | - |
| - | [#67307](https://github.com/vllm-project/vllm/issues/67307) `[CI Failure]: NVIDIA nightly failures` | infra,nvidia,quant | ? | - |
| - | [#67309](https://github.com/vllm-project/vllm/pull/67309) `[CI] Use torch.cuda.CUDAGraph in the DFlash MXFP8 context KV test on CUDA` | infra,nvidia,quant | ? | - |
| - | [#67310](https://github.com/vllm-project/vllm/pull/67310) `[CI] Run the Kimi K3 prefix cache Mooncake test over TCP on NVIDIA` | infra,nvidia,perf | ? | - |
| - | [#67311](https://github.com/vllm-project/vllm/pull/67311) `[CI] Fix the precompiled wheel variant and wait in python_only_compile.sh` | bug,infra | ? | - |
| - | [#67312](https://github.com/vllm-project/vllm/pull/67312) `[Transformers backend] Support DeepStack vision features` |  | ? | - |
| - | [#67319](https://github.com/vllm-project/vllm/pull/67319) `[Recipe] Add Inkling 2 Small` | infra | ? | - |
| - | [#67322](https://github.com/vllm-project/vllm/pull/67322) `[Recipe] Use the inkling-2-small image for Inkling 2 Small` | infra | ? | - |
| - | [#67326](https://github.com/vllm-project/vllm/pull/67326) `[CI] Wait for the server to exit before checking its children in shutdown tests` | infra | ? | - |
| - | [#67331](https://github.com/vllm-project/vllm/pull/67331) `[Bugfix] Shut down the executor when EngineCore fails to start` | bug | ? | - |
| - | [#67333](https://github.com/vllm-project/vllm/pull/67333) `[Bugfix][KV Connector] Stop forwarding shutdown() to LMCache until it no longer aborts` | bug | ? | - |
| - | [#67344](https://github.com/vllm-project/vllm/pull/67344) `[ROCm][gfx1151] ROCM_RDNA_ATTN: prefer 16-token KV blocks` | rocm | ? | - |
| - | [#67346](https://github.com/vllm-project/vllm/pull/67346) `docs: typo in Elastic EP error and ASR comment` |  | ? | - |
| - | [#67359](https://github.com/vllm-project/vllm/pull/67359) `[Rust Frontend] Support output_mode="text" on the generate route` |  | ? | - |
| - | [#67369](https://github.com/vllm-project/vllm/pull/67369) `[CI][Bugfix] Pin the GLM5-next shared-expert fusion test to the stock decode` | bug,infra,perf | ? | - |
| - | [#67378](https://github.com/vllm-project/vllm/pull/67378) `[ROCm][Docs] Add DeepSeek-V4.1-Flash MI355X DP2 AgentX preset with UMBP KV offload` | infra,rocm | ? | - |
| - | [#67379](https://github.com/vllm-project/vllm/pull/67379) `[XPU] reduce memory footprint for test_sagemaker_invocation_validation` | nvidia,perf | ? | - |
| - | [#67383](https://github.com/vllm-project/vllm/pull/67383) `[XPU][CI] Use platform dist backend in dist_init test fixture` | infra,nvidia | ? | - |
| - | [#67394](https://github.com/vllm-project/vllm/pull/67394) `[ROCm][CI] Fix Sharded RDT bake test replay under persisted ROCm MoE padding` | bug,infra,rocm | ? | - |
| - | [#67398](https://github.com/vllm-project/vllm/pull/67398) `[Rust Frontend] Render tool-result media in the Inkling renderer` |  | ? | - |
| - | [#67407](https://github.com/vllm-project/vllm/issues/67407) `[Bug]: `/inference/v1/generate` ignores `sampling_params.bad_words` with a 200 on `--tokens-only` and `--skip-` | bug | ? | - |
| - | [#67409](https://github.com/vllm-project/vllm/pull/67409) `[Rust Frontend] Keep the mock engine alive in the test_app fixture` |  | ? | - |
| - | [#67420](https://github.com/vllm-project/vllm/pull/67420) `[CI][Bugfix] Migrate UMBP lazy offload tests to the ManagerConfig KV cache API` | bug,infra,perf | ? | - |
| - | [#67437](https://github.com/vllm-project/vllm/pull/67437) `[CI] Retry the CUDA image bake when the registry rate-limits the push` | infra,nvidia | ? | - |
| - | [#67466](https://github.com/vllm-project/vllm/pull/67466) `[ROCm][DI-CI] Enable MiniMax-M3.1-Flash in AMD CI pipeline` | infra,rocm | ? | - |
| - | [#67476](https://github.com/vllm-project/vllm/pull/67476) `[CI][Bugfix] Read sliding_window from ManagerConfig.params in voxtral realtime test` | bug,infra | ? | - |
| - | [#67479](https://github.com/vllm-project/vllm/pull/67479) `[Bugfix][Multimodal] Preserve values from non-native-endian NumPy embeddings` | bug | ? | - |
| - | [#67485](https://github.com/vllm-project/vllm/pull/67485) `[Bugfix] Fix startup OOM in KV cache sizing warmup by releasing kernel warmup's KV blocks` | bug,perf | ? | - |
| - | [#67516](https://github.com/vllm-project/vllm/pull/67516) `[Bugfix][HiSparse] Fix GLM-5.3-Flash startup: derive resident/hot specs without grouping on workers` | bug | ? | - |
| - | [#67533](https://github.com/vllm-project/vllm/pull/67533) `[Chore] Remove deprecated `rope_scaling` usage and forbid it in pre-commit` | infra | ? | - |
| - | [#67549](https://github.com/vllm-project/vllm/pull/67549) `[CI/Build] Fix docstring Markdown style in test_quark.py` | bug,infra | ? | - |
| - | [#67553](https://github.com/vllm-project/vllm/pull/67553) `[CI] Split ReplaySSM E2E into 1-GPU, TP2 and nightly H100 steps` | infra,nvidia | ? | - |
| - | [#67568](https://github.com/vllm-project/vllm/pull/67568) `[Cherry-pick][v0.34.0] [Model] Add Mistral Large 4 (#64534)` | infra,nvidia,quant,rocm | ? | - |

### vLLM — Open / submitted (991 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#64640](https://github.com/vllm-project/vllm/pull/64640) `[ROCm][MoE] Add opt-in AITER FlyDSL clamped MXFP4 BF16 experts` | infra,quant,rocm | main | - |
| P0 | [#64643](https://github.com/vllm-project/vllm/pull/64643) `[Feature][ROCm][DSv4.1] Relay KV-sharing state across ROCm pipeline stages` | infra,rocm | main | - |
| P0 | [#64662](https://github.com/vllm-project/vllm/pull/64662) `[ROCm][Perf] Add MI325X FP8 fused MoE configs for Qwen3.8-Flash-Next` | perf,quant,rocm | main | - |
| P0 | [#64679](https://github.com/vllm-project/vllm/issues/64679) `[Bug]: fuse_rope_kvcache breaks draft_model/EAGLE spec decode when the drafter's attention shape differs from ` | perf,rocm | ? | - |
| P0 | [#64737](https://github.com/vllm-project/vllm/pull/64737) `[ROCm][Bugfix] Fix AITER shared-expert fusion routing for gate-less MoE (DeepSeek-V2-Lite)` | bug,perf,rocm | main | - |
| P0 | [#64855](https://github.com/vllm-project/vllm/issues/64855) `[Bug] Sparse-attention indexer: native padded decode (`requires_padding`) gives wrong logits/top-k on ragged s` | rocm | ? | - |
| P0 | [#64888](https://github.com/vllm-project/vllm/pull/64888) `[Bugfix][ROCm] Fix AITER FA extend_forward zero-chunk and drafter KV workspace (#64680)` | bug,rocm | main | - |
| P0 | [#64929](https://github.com/vllm-project/vllm/pull/64929) `[To close when vLLM pins AITER >= v0.1.29] [ROCm] Add VLLM_ROCM_USE_AITER_QUICK_REDUCE to keep INT4 QuickReduc` | infra,perf,quant,rocm | main | - |
| P0 | [#65022](https://github.com/vllm-project/vllm/pull/65022) `[ROCm][Bugfix] Keep AITER MLA split metadata alive for CUDA graph replay` | bug,nvidia,rocm | main | - |
| P0 | [#65034](https://github.com/vllm-project/vllm/issues/65034) `[Bug]: Quark `exclude` entries written as weight names (e.g. `mtp.fc.weight`) are silently never matched, brea` | bug,quant,risk,rocm | ? | - |
| P0 | [#65108](https://github.com/vllm-project/vllm/pull/65108) `[Bugfix][LoRA] Fix GPT-OSS triton_kernels 3.8 MoE LoRA row order` | bug | main | - |
| P0 | [#65128](https://github.com/vllm-project/vllm/pull/65128) `[MORI][DBO] Dual batch overlap with MoRI EPv2 (native and AsyncLL), and DBO fixes` | nvidia,perf,rocm | main | - |
| P0 | [#65188](https://github.com/vllm-project/vllm/pull/65188) `[ROCm][Perf] Qwen3.8-Flash-Next specialized decode at 1-192 rows on MI355X (--monokernel)` | infra,perf,rocm | main | - |
| P0 | [#65219](https://github.com/vllm-project/vllm/pull/65219) `[Bugfix][NIXL] Reject NVFP4 KV cache when the prefill block size is smaller than decode's` | bug,perf,quant | main | - |
| P0 | [#65410](https://github.com/vllm-project/vllm/pull/65410) `[ROCm][Step5] Give the CSA prefill indexer its own ROCm kernel, with native fnuz FP8 MFMA on gfx942` | infra,perf,quant,rocm | main | - |
| P0 | [#65421](https://github.com/vllm-project/vllm/pull/65421) `[ROCm][Perf][DSv4.1] Asm decode layers for 17-256-row decode steps (gfx950, TP4)` | infra,perf,rocm | main | - |
| P0 | [#65474](https://github.com/vllm-project/vllm/pull/65474) `[ROCm][Perf][Qwen4Exp] Tune QSA sparse GQA and indexer on gfx942 and gfx950` | perf,rocm | main | - |
| P0 | [#65512](https://github.com/vllm-project/vllm/pull/65512) `[WIP][ROCm][Perf][DeepSeek-V4.1] Mega-attention prefill kernel for gfx942` | infra,nvidia,perf,rocm | main | - |
| P0 | [#65555](https://github.com/vllm-project/vllm/pull/65555) `[ROCm][DSv4.1] Score the sparse-indexer prefill on ShardQ token slices` | rocm | main | - |
| P0 | [#65611](https://github.com/vllm-project/vllm/issues/65611) `[Bug]: gpt-oss-20b + nebius/EAGLE3-gpt-oss-20b gives corrupted greedy output at num_speculative_tokens >= 5 on` | risk,rocm | ? | - |
| P0 | [#65618](https://github.com/vllm-project/vllm/issues/65618) `[Bug]: DSpark draft for DeepSeek-V4 models has no `packed_modules_mapping` → fused layers ignore `ignored_laye` | bug,perf,quant,rocm | ? | - |
| P0 | [#65734](https://github.com/vllm-project/vllm/issues/65734) `[Bug][ROCm]: Dense attention output allocated with torch.empty — CUDA-graph padding rows poison the dynamic pe` | nvidia,quant,risk,rocm | ? | - |
| P0 | [#65820](https://github.com/vllm-project/vllm/pull/65820) `[Bugfix][Attention] Zero-init dense attention output buffers to prevent CUDA-graph padding corruption (#65734)` | bug,nvidia,risk | main | - |
| P0 | [#65830](https://github.com/vllm-project/vllm/pull/65830) `[Bugfix][Attention] Prevent overlapping query tile writes in Triton unified attention` | bug,rocm | main | - |
| P0 | [#65871](https://github.com/vllm-project/vllm/pull/65871) `[Bugfix][Attention] Fix V masking for non-causal sliding-window attention` | bug | main | - |
| P0 | [#65899](https://github.com/vllm-project/vllm/pull/65899) `[ROCm][MiniMax-M3] Serve --kv-cache-dtype mxfp4 on gfx942` | perf,quant,rocm | main | - |
| P0 | [#66011](https://github.com/vllm-project/vllm/pull/66011) `[Bugfix][NIXL] Decline remote prefill reads after the producer's KV lease expired` | bug | main | - |
| - | [#66020](https://github.com/vllm-project/vllm/pull/66020) `[Bugfix] Added CUDA graph capturing enabled flag management in MRV2` | bug,nvidia | ? | - |
| - | [#66023](https://github.com/vllm-project/vllm/issues/66023) `[Feature]: Tighter integration with Compressed-Tensors by consolidating and converting targets to vLLM` | quant | ? | - |
| - | [#66025](https://github.com/vllm-project/vllm/pull/66025) `[Bugfix][DSv4.1] Run decoder replay on a PP stage that starts at the cut` | bug | ? | - |
| P1 | [#66026](https://github.com/vllm-project/vllm/pull/66026) `[Bugfix][Spec Decode] Don't specialize MRV2 _gather_draft_sampled_kernel on num_logits` | bug | ? | - |
| P1 | [#66027](https://github.com/vllm-project/vllm/pull/66027) `[Attention][DCP] Sparse MLA DCP optimizations: packed top-k merge, direct A2A, DCP ShardQ (Kimi K3.1 split 6/6` | infra,nvidia,perf,rocm | ? | - |
| - | [#66035](https://github.com/vllm-project/vllm/pull/66035) `[HiSparse] Flush hot-buffer stats on the metrics logging timescale` |  | ? | - |
| - | [#66038](https://github.com/vllm-project/vllm/pull/66038) `[Perf][DSv4.1] Reuse the gathered compressed KV across consumers in FlashMLA prefill` | nvidia,perf | ? | - |
| - | [#66040](https://github.com/vllm-project/vllm/pull/66040) `[Kimi-K3] Deferred RecoverSSM verify kernels for FP32-state KDA layers` | perf | ? | - |
| - | [#66041](https://github.com/vllm-project/vllm/pull/66041) `[Perf][DSA] Keep ShardQ projections sequence-sharded under SP` | perf | ? | - |
| - | [#66043](https://github.com/vllm-project/vllm/pull/66043) `[Bugfix][Worker] Apply the startup plan on every rank or on none` | bug | ? | - |
| - | [#66045](https://github.com/vllm-project/vllm/pull/66045) `[Bugfix][Model Loader] Stop the EP weight filter from skipping a draft model's experts` | bug,infra | ? | - |
| - | [#66049](https://github.com/vllm-project/vllm/pull/66049) `[Bugfix][Core] Reject negative block counts in the free-block pool APIs` | bug,perf | ? | - |
| - | [#66050](https://github.com/vllm-project/vllm/pull/66050) `[Model] Enable audio-conditioned hidden-state extraction for Ming ASR` | infra | ? | - |
| P1 | [#66052](https://github.com/vllm-project/vllm/pull/66052) `[Bugfix][DSA] Stage ShardQ indexer indices in fresh host memory each step` | bug | ? | - |
| - | [#66053](https://github.com/vllm-project/vllm/pull/66053) `[Rust Frontend] Add the Poolside tool parser` |  | ? | - |
| - | [#66054](https://github.com/vllm-project/vllm/pull/66054) `[Perf][MiniMax-M3] Shard large batches by token and fuse the MoE finalize into the reduce-scatter` | infra,perf | ? | - |
| - | [#66055](https://github.com/vllm-project/vllm/issues/66055) `[Bug]: thinking_token_budget turns off reasoning when an earlier message mentions <think>` |  | ? | - |
| - | [#66056](https://github.com/vllm-project/vllm/pull/66056) `[Bugfix][Reasoning] Don't count a start marker quoted in an earlier message against thinking_token_budget` | bug,perf | ? | - |
| - | [#66059](https://github.com/vllm-project/vllm/pull/66059) `[Fast start] Support D2D scaling for multi-node serving` | infra | ? | - |
| - | [#66060](https://github.com/vllm-project/vllm/pull/66060) `[RL][Model Loader] Load plan: per-family plan == load_weights tests` |  | ? | - |
| - | [#66061](https://github.com/vllm-project/vllm/pull/66061) `[Feature][Model] Add NCP-OLMo support for pure HF checkpoints` | infra | ? | - |
| - | [#66066](https://github.com/vllm-project/vllm/pull/66066) `[XPU] Allow StatelessGroupCoordinator and elastic EPLB ` | infra,nvidia | ? | - |
| P1 | [#66068](https://github.com/vllm-project/vllm/pull/66068) `[ROCm][Quantization] Add tuned W8A8 block-FP8 Triton GEMM configs for MI355X` | perf,quant,rocm | ? | - |
| - | [#66070](https://github.com/vllm-project/vllm/issues/66070) `[Bug]: Qwen3.5 vision RoPE angle precision differs from HF (public 9B reproduction, mixed FP32 workaround resu` | bug,quant | ? | - |
| - | [#66072](https://github.com/vllm-project/vllm/pull/66072) `docs: fix broken FusedMoE imports in quantization guide` | bug,perf,quant | ? | - |
| P1 | [#66074](https://github.com/vllm-project/vllm/issues/66074) `[Bug]: MXFP4 linear layers on Hopper (default Humming kernel) silently round or zero weights whose E8M0 scale ` | nvidia,perf,quant,risk | ? | - |
| - | [#66075](https://github.com/vllm-project/vllm/pull/66075) `[Test][Core] Regression tests for EAGLE prefix caching with multiple attention groups and mixed block sizes` | bug,perf | ? | - |
| P1 | [#66076](https://github.com/vllm-project/vllm/pull/66076) `[Kernel] Add GC-MoE backend with fused shared experts for DeepSeek-V4.1` | perf | ? | - |
| - | [#66077](https://github.com/vllm-project/vllm/pull/66077) `[Quantization][Kernel] Unify MXFP6 linear activation scheme gate and propagate per-layer target overrides` | perf,quant | ? | - |
| - | [#66078](https://github.com/vllm-project/vllm/pull/66078) `[Feature][Rust Frontend] Support parallel sampling in gRPC GenerateStream` |  | ? | - |
| P0 | [#66082](https://github.com/vllm-project/vllm/pull/66082) `[Perf][ROCm][ROCM_ATTN] Run large fp8 decode batches on the AITER asm paged attention` | perf,quant,rocm | main | - |
| - | [#66083](https://github.com/vllm-project/vllm/pull/66083) `[Bugfix] Handle OOV multimodal prompt logprobs` | bug | ? | - |
| P1 | [#66084](https://github.com/vllm-project/vllm/pull/66084) `[ROCm][Spec Decode] Support draft_lm_head_quantization on RDNA (int4 drafter head, 18% faster MTP decode)` | perf,quant,rocm | ? | - |
| - | [#66085](https://github.com/vllm-project/vllm/issues/66085) `[Performance]: Avoid extra logits passes for temperature-only sampling` | perf | ? | - |
| P1 | [#66086](https://github.com/vllm-project/vllm/pull/66086) `[Perf][MRV2] Avoid extra passes for temperature-only sampling` | infra,perf | ? | - |
| P1 | [#66087](https://github.com/vllm-project/vllm/pull/66087) `[Bugfix][EPLB] Fix startup failure with MoE layers on multiple pipeline stages` | bug,infra | ? | - |
| P1 | [#66088](https://github.com/vllm-project/vllm/pull/66088) `[Bugfix] Make GLM-5.3 sparse MLA batch invariant under VLLM_BATCH_INVARIANT` | bug,infra | ? | - |
| - | [#66089](https://github.com/vllm-project/vllm/pull/66089) `[ROCm][CI] Bound DeepSeek V4 MoE output by per-token error` | infra,quant,rocm | ? | - |
| - | [#66093](https://github.com/vllm-project/vllm/issues/66093) `[Feature]: Carry the HTTP EPD multimodal handoff on the Rust gRPC frontend` |  | ? | - |
| - | [#66094](https://github.com/vllm-project/vllm/pull/66094) `[Frontend][gRPC] Carry the HTTP EPD handoff on the Rust frontend` |  | ? | - |
| - | [#66095](https://github.com/vllm-project/vllm/pull/66095) `[Build] Rewrite CUDA arch selection per target and preserve plain arch coverage` | infra,nvidia | ? | - |
| - | [#66096](https://github.com/vllm-project/vllm/pull/66096) `[Doc] Correct docstrings that promise a return value` |  | ? | - |
| - | [#66098](https://github.com/vllm-project/vllm/pull/66098) `[Bugfix][Frontend] Reject legacy functions/function_call in Chat Completions` | bug | ? | - |
| - | [#66101](https://github.com/vllm-project/vllm/issues/66101) `[Spec Decode] Broaden NVFP4 draft LM-head validation beyond GB10: Memra results and Blackwell/model matrix` | nvidia,quant | ? | - |
| - | [#66102](https://github.com/vllm-project/vllm/pull/66102) `feat: Add apply_router_weight_on_input support for CPU MoE expert classes` |  | ? | - |
| - | [#66108](https://github.com/vllm-project/vllm/pull/66108) `[Core] Reject the guidance backend for unsupported tokenizers in EngineCore` |  | ? | - |
| - | [#66109](https://github.com/vllm-project/vllm/issues/66109) `[Bug]: Marlin NVFP4 zeroes E4M3 subnormal block scales with float16 activations, although its float16 path dec` | quant | ? | - |
| - | [#66110](https://github.com/vllm-project/vllm/pull/66110) `[Bugfix] Keep small NVFP4 block scales in Marlin with float16 activations` | bug,quant | ? | - |
| - | [#66112](https://github.com/vllm-project/vllm/pull/66112) `[Bugfix][Quantization] Avoid Humming's fused-E8M0 path for MXFP4 layers it would round` | bug,perf,quant | ? | - |
| - | [#66113](https://github.com/vllm-project/vllm/issues/66113) `[Bug]: Ministral-3 / Devstral-Small-2 FP8 with `--config-format hf`: vision tower and projector are built as F` | quant | ? | - |
| - | [#66114](https://github.com/vllm-project/vllm/pull/66114) `[Bugfix] Keep modules listed in FP8 modules_to_not_convert unquantized` | bug,quant | ? | - |
| - | [#66115](https://github.com/vllm-project/vllm/issues/66115) `[Bug]: LFM2, LFM2-MoE, Jamba, Zamba2, Step3, Bailing MoE and PLaMo3 build `Attention` without `quant_config`, ` | infra,perf,quant | ? | - |
| - | [#66116](https://github.com/vllm-project/vllm/pull/66116) `[Bugfix] Pass quant_config to Attention in hybrid and MoE models` | bug,quant | ? | - |
| - | [#66120](https://github.com/vllm-project/vllm/issues/66120) `[Bug]: MiniMax-M3 sparse attention layers drop checkpoint FP8 KV-cache scales and run with scale 1.0` | perf,quant | ? | - |
| - | [#66121](https://github.com/vllm-project/vllm/pull/66121) `feat: CPU WNA16 MoE INT8 weight-only support for mixed INT4/INT8 models (issue #65070)` | quant | ? | - |
| - | [#66122](https://github.com/vllm-project/vllm/issues/66122) `[Feature]: Selectable fused prefill top-k backend for the sparse indexer (add FlashTopK; SM90 + SM100)` | nvidia,perf | ? | - |
| - | [#66124](https://github.com/vllm-project/vllm/issues/66124) `[Bug]: `enable_weights_track` refuses correct weight-only NVFP4 checkpoints (input scales that no export write` | perf,quant | ? | - |
| - | [#66126](https://github.com/vllm-project/vllm/pull/66126) `[Perf][Kernel] CUTLASS FP8 scaled_mm: smaller tiles for narrow-N decode GEMMs on SM90 and SM100` | nvidia,perf,quant | ? | - |
| P1 | [#66128](https://github.com/vllm-project/vllm/pull/66128) `[ROCm][Perf][DSv4.1] Score adaptive-verification decode steps as varlen sequences in the MXFP4 indexer` | perf,quant,rocm | ? | - |
| - | [#66129](https://github.com/vllm-project/vllm/issues/66129) `[Bug]: compressed-tensors loads checkpoint FP8 k/v scales into layers kept in BF16 by kv_cache_dtype_skip_laye` | bug,nvidia,quant | ? | - |
| - | [#66130](https://github.com/vllm-project/vllm/pull/66130) `[ROCm] Add a FlyDSL MXFP4 linear backend for RDNA4` | infra,quant,rocm | ? | - |
| - | [#66131](https://github.com/vllm-project/vllm/issues/66131) `[Bug][KV Connector][Kimi-K3.1-Pro] Local hybrid hit can exceed draft-attention coverage` |  | ? | - |
| - | [#66132](https://github.com/vllm-project/vllm/pull/66132) `[Bugfix][KV Connector] Reconcile local hits when draft attention lags` | bug,infra,perf | ? | - |
| P1 | [#66133](https://github.com/vllm-project/vllm/pull/66133) `[ROCm][Perf] W4A16: fix the gfx1151 bf16 tile cliff at decode-sized M (up to +44% decode throughput)` | bug,perf,quant,rocm | ? | - |
| - | [#66134](https://github.com/vllm-project/vllm/issues/66134) `[RFC]: Text sessions on /v1/realtime with streaming-input prefill` |  | ? | - |
| - | [#66135](https://github.com/vllm-project/vllm/pull/66135) `[Bugfix][Parser] DeepSeek DSML: keep a closer inside a tool-argument value` | bug | ? | - |
| - | [#66137](https://github.com/vllm-project/vllm/issues/66137) `[Bug][Prefix Cache][Kimi-K3.1-Pro] DSpark does not enable shared Mamba checkpoints` | perf | ? | - |
| - | [#66138](https://github.com/vllm-project/vllm/pull/66138) `[Prefix Cache] Learn shared Mamba checkpoints for DSpark sibling prompts` | infra,perf | ? | - |
| - | [#66140](https://github.com/vllm-project/vllm/pull/66140) `[Perf][Kernel] Parallelize mHC post for small SM100 batches` | nvidia,perf | ? | - |
| - | [#66142](https://github.com/vllm-project/vllm/pull/66142) `[Perf][Kernel] Partition mHC input-norm stores on SM100` | nvidia,perf | ? | - |
| - | [#66144](https://github.com/vllm-project/vllm/issues/66144) `[Bug]: With --enable-fault-tolerance, an async EPLB worker exception stalls EPLB silently instead of making th` | risk | ? | - |
| - | [#66146](https://github.com/vllm-project/vllm/pull/66146) `[Bugfix][EPLB] Report async EPLB worker failures to fault tolerance instead of stalling` | bug,infra | ? | - |
| - | [#66149](https://github.com/vllm-project/vllm/pull/66149) `[Bugfix] Accept weight-only NVFP4 checkpoints in enable_weights_track` | bug,quant | ? | - |
| - | [#66150](https://github.com/vllm-project/vllm/pull/66150) `[Frontend] Rust gRPC: support bounded per-request multimodal kwargs` |  | ? | - |
| - | [#66151](https://github.com/vllm-project/vllm/pull/66151) `[Test][Rust] Select engine 0 in sampling metrics test` |  | ? | - |
| - | [#66154](https://github.com/vllm-project/vllm/pull/66154) `[KV Offload] Bound PUT staging and schedule aligned batches` |  | ? | - |
| - | [#66156](https://github.com/vllm-project/vllm/pull/66156) `[Frontend] Accept `reasoning_content` and `join` in response templates` |  | ? | - |
| - | [#66157](https://github.com/vllm-project/vllm/pull/66157) `[Frontend] Serve PelaAI/KnowLine-35B-A3B-Gen1.5 on /v1/systemone` |  | ? | - |
| - | [#66158](https://github.com/vllm-project/vllm/pull/66158) `[MoE][NVIDIA] Support MXFP4 experts on SM107 in flashinfer_moe_ep_cutedsl` | nvidia,quant | ? | - |
| - | [#66159](https://github.com/vllm-project/vllm/pull/66159) `[ROCm] Support DP in AiterW4A16ExpertsMonolithic` | quant,rocm | ? | - |
| - | [#66160](https://github.com/vllm-project/vllm/pull/66160) `[ROCm][Perf] Skip the z copy in the Qwen GDN gated RMSNorm` | perf,rocm | ? | - |
| - | [#66162](https://github.com/vllm-project/vllm/pull/66162) `[Bugfix] Resolve speculative draft model to local path in offline mode` | bug | ? | - |
| - | [#66163](https://github.com/vllm-project/vllm/issues/66163) `[RFC][ROCm]: Batch-invariant kernels for Kimi-K3.1 on MI355X (KDA, DSA/indexer, MXFP4 MoE, LoRA, all-reduce)` | perf,quant,rocm | ? | - |
| - | [#66164](https://github.com/vllm-project/vllm/pull/66164) `[Test][KV Events] Check a reference consumer against a real engine` | infra | ? | - |
| - | [#66166](https://github.com/vllm-project/vllm/pull/66166) `[Model] Add Dhir dense and MoE models` |  | ? | - |
| - | [#66167](https://github.com/vllm-project/vllm/pull/66167) `[RL][Model Loader] Inkling: derive expert input scales from input_amax after loading` | quant | ? | - |
| - | [#66168](https://github.com/vllm-project/vllm/pull/66168) `[CPU] Support 2D (batched) weights in rms_norm, fixing DFlash acceptance on CPU` | infra | ? | - |
| - | [#66169](https://github.com/vllm-project/vllm/pull/66169) `[Feature][Hybrid] K0 spec-window slot release for hybrid mamba models` | infra,nvidia,perf,quant | ? | - |
| - | [#66170](https://github.com/vllm-project/vllm/issues/66170) `[Feature]: Enable and validate pipeline parallelism for Domyn Edge` | quant | ? | - |
| P1 | [#66172](https://github.com/vllm-project/vllm/pull/66172) `[ROCm][Kimi-K3.1] Specialized decode: run DCP1 without M1 on vLLM's MLA ops (enables K3.1; K3 fallback)` | rocm | ? | - |
| - | [#66173](https://github.com/vllm-project/vllm/issues/66173) `[Bug]: Pythonic tool parsers silently drop calls with Python reserved keywords as parameter names` | risk | ? | - |
| - | [#66174](https://github.com/vllm-project/vllm/pull/66174) `fix(tool_parsers): support Python reserved keywords as tool arguments in pythonic parsers` | bug | ? | - |
| - | [#66176](https://github.com/vllm-project/vllm/pull/66176) `[Perf][Core] Look up single-group prefix-cache hits with one dict get per block` | perf | ? | - |
| - | [#66178](https://github.com/vllm-project/vllm/issues/66178) `[Bug]: Granite20bFCToolParser streaming misses tool calls when preceded by content` |  | ? | - |
| - | [#66179](https://github.com/vllm-project/vllm/pull/66179) `fix(tool_parsers): stream content preceding <function_call> in Granite20bFCToolParser` | bug | ? | - |
| - | [#66180](https://github.com/vllm-project/vllm/issues/66180) `[Bug]: xLAM non-streaming tool parser drops single tool call object in <tool_call> tags` |  | ? | - |
| - | [#66181](https://github.com/vllm-project/vllm/pull/66181) `fix(tool_parsers): accept single tool call object in xLAM non-streaming parser` | bug | ? | - |
| - | [#66182](https://github.com/vllm-project/vllm/issues/66182) `[Bug]: Step3ReasoningParser.extract_content_ids excludes think_end_token at last index` |  | ? | - |
| - | [#66183](https://github.com/vllm-project/vllm/pull/66183) `fix(reasoning): check input_ids directly in Step3ReasoningParser.extract_content_ids` | bug | ? | - |
| - | [#66184](https://github.com/vllm-project/vllm/pull/66184) `[ROCm][MiniMax-M3] Select the whole-layer mono decode with --monokernel and remove mono/envs.py` | infra,rocm | ? | - |
| - | [#66185](https://github.com/vllm-project/vllm/pull/66185) `[Bugfix] Fix fast detokenizer output for adjacent non-special added tokens` | bug | ? | - |
| - | [#66192](https://github.com/vllm-project/vllm/issues/66192) `[Bug]: SM100 default prefill CUDA-graph grid (up to 8192 tokens, #63406) adds ~5 GiB/GPU graph memory and brea` | nvidia,quant | ? | - |
| - | [#66193](https://github.com/vllm-project/vllm/issues/66193) `[Bug]: Extensible KV cache reserves the one-off FlashInfer autotune peak as a serving transient, cutting KV 2.` | bug,nvidia,perf,quant | ? | - |
| - | [#66198](https://github.com/vllm-project/vllm/pull/66198) `[Feature][Rust Frontend] Stream Qwen Coder string arguments` |  | ? | - |
| - | [#66199](https://github.com/vllm-project/vllm/pull/66199) `[Feature][Rust Frontend] Stream Gemma 4 string arguments` |  | ? | - |
| - | [#66200](https://github.com/vllm-project/vllm/pull/66200) `[Bugfix] Use 64-bit row offsets in the block-FP8 Triton GEMM` | bug,quant,rocm | ? | - |
| - | [#66202](https://github.com/vllm-project/vllm/pull/66202) `[Bugfix][MoE] Fix Triton block-FP8 scalar scale indexing` | bug,quant,rocm | ? | - |
| - | [#66204](https://github.com/vllm-project/vllm/pull/66204) `[Rust Frontend] Read client IPs from trusted proxies` |  | ? | - |
| - | [#66208](https://github.com/vllm-project/vllm/pull/66208) `[ROCm][gfx1250] Kimi-K3 FP8 MLA: aiter FP8 MHA + MLA Prefill/Decode` | quant,rocm | ? | - |
| - | [#66211](https://github.com/vllm-project/vllm/issues/66211) `[Bug]: Compressed-tensors NVFP4/MXFP4 row-parallel layers load with other groups' block scales when the TP spl` | quant | ? | - |
| - | [#66213](https://github.com/vllm-project/vllm/pull/66213) `[Bugfix] Refuse TP splits that cut compressed-tensors FP4 scale groups` | bug,perf,quant | ? | - |
| - | [#66214](https://github.com/vllm-project/vllm/pull/66214) `[ROCm][gfx1250] Run per-token FP8 linear layers on aiter's gemm_a8w8` | quant,rocm | ? | - |
| - | [#66215](https://github.com/vllm-project/vllm/pull/66215) `[ROCm] Read the DSv4.1 mono target arch from FLYDSL_GPU_ARCH` | rocm | ? | - |
| - | [#66216](https://github.com/vllm-project/vllm/pull/66216) `[ROCm][Model] Add Flint support on AMD GPUs` | infra,quant,rocm | ? | - |
| - | [#66218](https://github.com/vllm-project/vllm/issues/66218) `GLM-5.3-Flash FP4-Local in production on 2x RTX PRO 6000 (SM120): what's missing for a full community-main bas` | nvidia,quant | ? | - |
| - | [#66221](https://github.com/vllm-project/vllm/pull/66221) `[Quantization] feat: add support for lossless NF12 online quantization` | infra,quant | ? | - |
| - | [#66226](https://github.com/vllm-project/vllm/pull/66226) `[Feature][Spec Decode] Add spec config to shorten drafts on prefill-heavy steps` | nvidia | ? | - |
| - | [#66230](https://github.com/vllm-project/vllm/pull/66230) `[Perf] Fill unconstrained bitmask rows from a cached template` | perf | ? | - |
| - | [#66231](https://github.com/vllm-project/vllm/issues/66231) `[RFC]: P/D disaggregation for continuous RL rollouts (S1): order-free, seconds-long weight-update pauses` |  | ? | - |
| - | [#66232](https://github.com/vllm-project/vllm/issues/66232) `[Bug][Perf]: W4A16 HummingLinearKernel is non-deterministic across processes and faster than the default Mache` | nvidia,perf,quant | ? | - |
| - | [#66233](https://github.com/vllm-project/vllm/pull/66233) `[Bugfix] Apply max_tokens caps to explicit null on generate` | bug | ? | - |
| - | [#66234](https://github.com/vllm-project/vllm/pull/66234) `[Refactor][KV Cache] Remove EAGLE block dropping and default to lookahead hashes` | perf | ? | - |
| - | [#66235](https://github.com/vllm-project/vllm/pull/66235) `[Bugfix][LoRA] Fix LLaVA-NeXT tower and connector buffer sizing` | bug,infra | ? | - |
| - | [#66236](https://github.com/vllm-project/vllm/pull/66236) `[Perf][MoE] Shard replicated TP prefill tokens for SM90 MegaMoE` | infra,nvidia,perf,quant | ? | - |
| - | [#66237](https://github.com/vllm-project/vllm/pull/66237) `[Security] Validate decoded scale-out multimodal features` | quant | ? | - |
| - | [#66240](https://github.com/vllm-project/vllm/pull/66240) `[Bugfix][Model] Zero Kimi-Audio's Whisper k_proj bias so the model loads again` | bug | ? | - |
| - | [#66241](https://github.com/vllm-project/vllm/issues/66241) `[Bug]: `compilation_config.backend` accepts arbitrary strings and dies with a bare `AttributeError: module '__` | bug | ? | - |
| - | [#66242](https://github.com/vllm-project/vllm/issues/66242) `[Bug]:  Phi-2 crashes with CUDA illegal memory access during compile/warmup at size 32` | bug,nvidia,risk | ? | - |
| - | [#66246](https://github.com/vllm-project/vllm/issues/66246) `[Bug]: Single-token benchmark probes inherit generation-length overrides from the main workload` | perf | ? | - |
| - | [#66247](https://github.com/vllm-project/vllm/pull/66247) `[Perf][Attention] Tune single-request FP16 Triton decode on SM80` | perf,rocm | ? | - |
| - | [#66248](https://github.com/vllm-project/vllm/issues/66248) `[Bug]: Invalid `SamplingParams.structured_outputs` type raises `AttributeError` during request validation` | bug | ? | - |
| - | [#66249](https://github.com/vllm-project/vllm/pull/66249) `[Bugfix] Validate compilation config backend` | bug | ? | - |
| - | [#66250](https://github.com/vllm-project/vllm/issues/66250) `[Bug]: phi-2 crashes with CUDA illegal memory access during compile/warmup at size 32` | bug,nvidia,risk | ? | - |
| - | [#66252](https://github.com/vllm-project/vllm/pull/66252) `[Feature][LoRA] Allow DP for the TRTLLM MXFP4 MoE-LoRA experts` | nvidia,quant | ? | - |
| - | [#66254](https://github.com/vllm-project/vllm/pull/66254) `[Bugfix][LoRA][Spec Decode] Build the DSpark drafter without the target's LoRA config` | bug,infra | ? | - |
| - | [#66255](https://github.com/vllm-project/vllm/issues/66255) `[Bug]: MoE oracle picks LoRA-aware experts from the global lora_config, ignoring the per-layer target_modules ` | bug | ? | - |
| - | [#66256](https://github.com/vllm-project/vllm/pull/66256) `[Bugfix] Reject a structured_outputs value that is not StructuredOutputsParams` | bug | ? | - |
| - | [#66258](https://github.com/vllm-project/vllm/issues/66258) `[Performance]: Whisper encoder runs eagerly; compiling it gives ~+10% transcription throughput` | perf | ? | - |
| - | [#66259](https://github.com/vllm-project/vllm/pull/66259) `[Perf] Whisper: torch.compile the encoder layer stack with compile_mm_encoder` | perf | ? | - |
| - | [#66260](https://github.com/vllm-project/vllm/pull/66260) `[Bugfix][Benchmark] Isolate probe generation length from workload extra_body (#66246)` | bug,perf | ? | - |
| - | [#66262](https://github.com/vllm-project/vllm/pull/66262) `[Bugfix][Benchmark] Preserve fractional workload sweep rates` | bug,perf | ? | - |
| - | [#66264](https://github.com/vllm-project/vllm/issues/66264) `[Bug]: UVA CPU offload silently undone when replace_parameter rebinds .data (marker survives, re-offload skipp` | quant,risk | ? | - |
| - | [#66265](https://github.com/vllm-project/vllm/pull/66265) `[Bugfix][Offload] Re-offload UVA params whose data replace_parameter rebound` | bug | ? | - |
| - | [#66269](https://github.com/vllm-project/vllm/pull/66269) `[Bugfix][Gemma4] Preserve assistant content before tool calls` | bug,infra | ? | - |
| - | [#66270](https://github.com/vllm-project/vllm/pull/66270) `[Refactor][MoE] Move unquantized backend selection into its oracle` | quant | ? | - |
| - | [#66271](https://github.com/vllm-project/vllm/pull/66271) `[KV Connector][Mooncake] Generalize cache registration and payload layouts` | perf | ? | - |
| - | [#66272](https://github.com/vllm-project/vllm/pull/66272) `[Perf][Parser] Skip intermediate argument conversion in buffered parsing` | infra,perf | ? | - |
| - | [#66275](https://github.com/vllm-project/vllm/pull/66275) `[Feature][Spec Decode] Add Ampere (SM80) Native Specialized Decode for DeepSeek-V4.1-Flash` |  | ? | - |
| - | [#66276](https://github.com/vllm-project/vllm/pull/66276) `[Bugfix][Parser] Gemma4: keep tool-call flush beside a partial thought prefix` | bug | ? | - |
| - | [#66277](https://github.com/vllm-project/vllm/pull/66277) `[Bugfix] Keep B12X kernels loaded for captured CUDA graphs` | bug,nvidia,perf | ? | - |
| - | [#66279](https://github.com/vllm-project/vllm/pull/66279) `[Bugfix][Model] Prefill DiffusionGemma image tokens bidirectionally` | bug,infra,perf | ? | - |
| - | [#66280](https://github.com/vllm-project/vllm/pull/66280) `[ROCm][gfx1250] Kimi-K3: run the W_UK/W_UV bmms and the latent up-pro…` | rocm | ? | - |
| - | [#66281](https://github.com/vllm-project/vllm/pull/66281) `[Bugfix][Frontend] Follow tools/list pagination in MCP tool discovery` | bug | ? | - |
| - | [#66282](https://github.com/vllm-project/vllm/pull/66282) `[Bugfix][MTP] Add packed_modules_mapping and MTP quant alignment to DeepSeek-V4 NVIDIA/XPU MTP` | bug,nvidia,quant | ? | - |
| - | [#66283](https://github.com/vllm-project/vllm/pull/66283) `[Bugfix][Spec Decode] Use KV-only rope insert for DeepSeek-V4/V4.1 DSpark context KV` | bug | ? | - |
| - | [#66284](https://github.com/vllm-project/vllm/issues/66284) `[Performance]: ~1.4 s gpt-oss serving stalls from per-batch-size recompiles of the bundled triton_kernels v3.5` | perf | ? | - |
| - | [#66285](https://github.com/vllm-project/vllm/pull/66285) `[Perf][MoE] Backport triton#10875 to the bundled triton_kernels v3.5.1` | perf,rocm | ? | - |
| - | [#66286](https://github.com/vllm-project/vllm/pull/66286) `[Qwen3.5] FP16 partial sums for the deferred row-parallel all-reduces` | infra,nvidia | ? | - |
| - | [#66290](https://github.com/vllm-project/vllm/issues/66290) `[RFC]: Pipeline-parallel equivalence tests for every model that declares `SupportsPP`` |  | ? | - |
| - | [#66293](https://github.com/vllm-project/vllm/issues/66293) `[Bug]: vllm/vllm-openai:muse-spark-open needs to be rebuilt with the issue fixed in #62374` | bug | ? | - |
| - | [#66294](https://github.com/vllm-project/vllm/pull/66294) `[KV Connector][Mooncake] Support device adapters and typed TP state views` |  | ? | - |
| - | [#66296](https://github.com/vllm-project/vllm/pull/66296) `[Bugfix][MoE][LoRA] Align expert selection with target_modules` | bug | ? | - |
| - | [#66298](https://github.com/vllm-project/vllm/issues/66298) `[Bug]: gemma3_pythonic chat template renders tool call arguments with no separator, so the pythonic parser rej` |  | ? | - |
| - | [#66299](https://github.com/vllm-project/vllm/pull/66299) `[Bugfix][Tool Parser] gemma3_pythonic: emit argument separators so rendered tool calls parse` | bug | ? | - |
| - | [#66300](https://github.com/vllm-project/vllm/issues/66300) `[Bug]: llama3.2_pythonic and toolace chat templates render string arguments unquoted, so the pythonic parser d` |  | ? | - |
| - | [#66301](https://github.com/vllm-project/vllm/issues/66301) `[Feature]: Deploying vLLM with Ray on SLURM-based university HPC clusters` |  | ? | - |
| - | [#66302](https://github.com/vllm-project/vllm/issues/66302) `[Bug]: llama4_pythonic chat template quotes every tool call argument, losing argument types and breaking on st` |  | ? | - |
| - | [#66303](https://github.com/vllm-project/vllm/issues/66303) `[Bug]: NCCL symmetric all-reduce uses the wrong group when TP and ETP differ` | nvidia | ? | - |
| - | [#66304](https://github.com/vllm-project/vllm/pull/66304) `[Bugfix][Distributed] Route NCCL symmetric all-reduce to the calling group` | bug,infra,nvidia,perf | ? | - |
| - | [#66305](https://github.com/vllm-project/vllm/pull/66305) `[Bugfix][Parser] Merge Cohere tool grammars with xgrammar union` | bug | ? | - |
| - | [#66317](https://github.com/vllm-project/vllm/pull/66317) `[Core] Add collective_rpc_per_engine to return every data-parallel engine's worker results` |  | ? | - |
| - | [#66322](https://github.com/vllm-project/vllm/pull/66322) `[ROCm][Attention] Support PCP and DCP on ROCM_AITER_MLA_SPARSE and mirror LM Eval PCP on MI355` | infra,rocm | ? | - |
| - | [#66326](https://github.com/vllm-project/vllm/pull/66326) `[Bugfix][Tool Parser] Quote string arguments in llama3.2/toolace pythonic templates` | bug | ? | - |
| - | [#66327](https://github.com/vllm-project/vllm/pull/66327) `[Bugfix][Rust Frontend] Bump fastokens to 0.3.6` | bug,infra | ? | - |
| - | [#66330](https://github.com/vllm-project/vllm/pull/66330) `[ROCm][Perf] MXFP8 native linear: 128x128x128 two-stage tile for short-K large prefill on gfx950` | perf,quant,rocm | ? | - |
| - | [#66331](https://github.com/vllm-project/vllm/pull/66331) `[Bugfix][Scheduler] Bound cache-aware admission probe by request reuse limit` | bug,perf | ? | - |
| - | [#66332](https://github.com/vllm-project/vllm/issues/66332) `[Bug]: /v1/audio/transcriptions and /translations reject stream_include_usage=false (form strings checked befo` |  | ? | - |
| - | [#66335](https://github.com/vllm-project/vllm/pull/66335) `[Bugfix][Frontend] Validate speech-to-text stream options after form coercion` | bug | ? | - |
| - | [#66336](https://github.com/vllm-project/vllm/pull/66336) `fix(tool_parsers): preserve trailing content in Hermes2ProToolParser` | bug | ? | - |
| - | [#66337](https://github.com/vllm-project/vllm/pull/66337) `fix(parser): don't leak buffered prefix when a PreLexedTerminal supersedes it` | bug | ? | - |
| - | [#66339](https://github.com/vllm-project/vllm/pull/66339) `[CI][ROCm] Mirror NixlConnector PD accuracy core on MI355` | infra,risk,rocm | ? | - |
| - | [#66340](https://github.com/vllm-project/vllm/pull/66340) `[Frontend] Return Cohere grounding citations from derender` |  | ? | - |
| - | [#66341](https://github.com/vllm-project/vllm/pull/66341) `[Core] Add cache_salt_start_idx for divergence-point prefix-cache salting` | perf | ? | - |
| - | [#66342](https://github.com/vllm-project/vllm/pull/66342) `[Feature][Quantization] Rewrite compressed-tensors regex targets on load` | quant | ? | - |
| - | [#66344](https://github.com/vllm-project/vllm/issues/66344) `[RFC]: Word-level timestamps for speech models from per-request encoder outputs` |  | ? | - |
| - | [#66345](https://github.com/vllm-project/vllm/issues/66345) ``llguidance` is an unconditional dependency and is loaded by `from vllm import LLM`; it blocks install and imp` |  | ? | - |
| - | [#66346](https://github.com/vllm-project/vllm/pull/66346) `[Bugfix][Tool Parser] llama4_pythonic: render argument values as literals, not quoted strings` | bug | ? | - |
| - | [#66347](https://github.com/vllm-project/vllm/pull/66347) `[Benchmark] benchmark_moe: read GLM-5.3-Flash's MoE shape from its text config` | perf | ? | - |
| - | [#66351](https://github.com/vllm-project/vllm/issues/66351) `[Bug]: Background /v1/responses requests that fail during generation stay "queued" forever (streaming case not` | bug | ? | - |
| - | [#66352](https://github.com/vllm-project/vllm/pull/66352) `[Perf][DSA] Rank BF16 prefill indexer logits with DeepSelect by default on SM100` | infra,nvidia,perf | ? | - |
| - | [#66354](https://github.com/vllm-project/vllm/pull/66354) `[Perf][Kimi-K3] Parse streamed reasoning and tool output in O(delta)` | perf | ? | - |
| - | [#66355](https://github.com/vllm-project/vllm/pull/66355) `[Tests] Make multi-GPU config tests independent of the host GPU count` |  | ? | - |
| - | [#66356](https://github.com/vllm-project/vllm/pull/66356) `[Online quantization] Add requantize_from to select re-quantized checkpoint layers based on dtype` | quant | ? | - |
| - | [#66359](https://github.com/vllm-project/vllm/issues/66359) `[Bug]: Rust vllm-bench random dataset sends prompts shorter than --random-input-len` | perf | ? | - |
| - | [#66360](https://github.com/vllm-project/vllm/pull/66360) `[Rust][Benchmark] Pad random text prompts to the target length` | perf | ? | - |
| - | [#66361](https://github.com/vllm-project/vllm/pull/66361) `[Core][Scheduler] Add opt-in aging to cache-aware admission` | perf | ? | - |
| - | [#66364](https://github.com/vllm-project/vllm/issues/66364) `[Bug][XPU]: UVA expert offload of an int4 MoE loses the device (UR_RESULT_ERROR_DEVICE_LOST) in the first deco` | nvidia,quant | ? | - |
| - | [#66365](https://github.com/vllm-project/vllm/pull/66365) `[XPU][Offload] Keep MoE weight scales on the device without vllm-xpu-kernels#605` | nvidia,perf,quant | ? | - |
| - | [#66366](https://github.com/vllm-project/vllm/issues/66366) `[Bug]: FlashAttention cache write fails with an explicit `"kv_cache_dtype": "bfloat16"` (e.g. a BF16 draft ove` | perf,quant | ? | - |
| - | [#66367](https://github.com/vllm-project/vllm/pull/66367) `[Bugfix][Attention] reshape_and_cache_flash: accept an explicit plain KV dtype` | bug | ? | - |
| - | [#66368](https://github.com/vllm-project/vllm/issues/66368) `[Feature][XPU][Offload]: Spend `--cpu-offload-gb` per routed expert, by routing rank, instead of whole layers ` | nvidia | ? | - |
| - | [#66369](https://github.com/vllm-project/vllm/pull/66369) `[XPU][Offload] Place offloaded routed experts per expert by routing rank` | infra,nvidia,quant | ? | - |
| - | [#66371](https://github.com/vllm-project/vllm/pull/66371) `[XPU][Offload] Learn the expert rankings while serving` | infra,nvidia,quant | ? | - |
| - | [#66372](https://github.com/vllm-project/vllm/pull/66372) `[XPU][Offload] Let the hot experts follow the traffic` | infra,nvidia,quant | ? | - |
| - | [#66373](https://github.com/vllm-project/vllm/pull/66373) `[XPU][MoE] Stage UVA-offloaded experts on XPU` | nvidia | ? | - |
| - | [#66374](https://github.com/vllm-project/vllm/pull/66374) `[Offload] Prefetch the next layer's staged experts on a side stream` | nvidia | ? | - |
| - | [#66378](https://github.com/vllm-project/vllm/pull/66378) `[MiniMax-M3] Experimental: replicate attention across TP ranks for slow inter-node TP` | infra | ? | - |
| - | [#66379](https://github.com/vllm-project/vllm/pull/66379) `[Bugfix][KV Connector] Preserve parked load reservations across KV allocations` | bug,perf | ? | - |
| - | [#66381](https://github.com/vllm-project/vllm/pull/66381) `[Model Loader] Add opt-in scoped weight-loading thread cap` |  | ? | - |
| - | [#66382](https://github.com/vllm-project/vllm/pull/66382) `[Bugfix][Frontend] Collect all MCP tool pages in list_server_and_tools (#65074)` | bug | ? | - |
| - | [#66383](https://github.com/vllm-project/vllm/pull/66383) `[Bugfix][Frontend] Reject orphan tool results` | bug | ? | - |
| - | [#66385](https://github.com/vllm-project/vllm/pull/66385) `[Docs] Explain hybrid KV cache configuration metrics` | perf | ? | - |
| - | [#66386](https://github.com/vllm-project/vllm/pull/66386) `[Docs] Explain Engram host-memory exhaustion diagnostics` |  | ? | - |
| - | [#66387](https://github.com/vllm-project/vllm/issues/66387) `[Bug]: DFlash acceptance collapses at tensor parallel > 1 (MiMo-V2.6-Flash-MOPD, TP1 fine)` |  | ? | - |
| - | [#66389](https://github.com/vllm-project/vllm/pull/66389) `[Recipes] Add Kimi-K2.6 overlay placement anchors and dynamic client model` | infra | ? | - |
| - | [#66392](https://github.com/vllm-project/vllm/issues/66392) `[Bug]: /v1/systemone caps Clef-Flash choice questions at 26 options, though the joint-schema read uses no labe` | bug | ? | - |
| - | [#66394](https://github.com/vllm-project/vllm/pull/66394) `[Bugfix][KV Offload] Include model revision in FileMapper cache identity` | bug,perf | ? | - |
| - | [#66395](https://github.com/vllm-project/vllm/pull/66395) `[FEAT][Rust Frontend] Attribute Responses output logprobs to visible text` |  | ? | - |
| - | [#66396](https://github.com/vllm-project/vllm/pull/66396) `[Bugfix] Fingerprint skipped multimodal components in the weight cache key` | bug,perf | ? | - |
| - | [#66404](https://github.com/vllm-project/vllm/issues/66404) `[Bug]: BatchedTritonExperts silently ignores expert projection biases` | risk | ? | - |
| - | [#66405](https://github.com/vllm-project/vllm/pull/66405) `[Perf][Multimodal][CG] Enable encoder CUDA Graph for MiniCPM-V-4.6 and 4.7` | nvidia,perf | ? | - |
| - | [#66406](https://github.com/vllm-project/vllm/issues/66406) `[Performance]: Block FP8 MoE on SM120 with expert parallel: Triton decodes 10–20% faster than the auto-selecte` | nvidia,perf,quant,rocm | ? | - |
| - | [#66408](https://github.com/vllm-project/vllm/pull/66408) `[Bugfix][Frontend] Fix speech-to-text chunk spacing and unsupported verbose_json errors` | bug | ? | - |
| - | [#66410](https://github.com/vllm-project/vllm/pull/66410) `[Bugfix] Cap compile-range warmup at reachable batch sizes` | bug | ? | - |
| - | [#66411](https://github.com/vllm-project/vllm/issues/66411) `[RFC]: Breakdown PR time to signal from ~73 to ~30 minutes` | rocm | ? | - |
| P1 | [#66415](https://github.com/vllm-project/vllm/pull/66415) `[ROCm][Perf][Muse Spark] Specialized decode for PTPC FP8 on gfx942 (--monokernel, TP8 EP8)` | perf,quant,rocm | ? | - |
| - | [#66416](https://github.com/vllm-project/vllm/pull/66416) `[Transformers backend] Migrate InternLM3 and IQuestCoder` |  | ? | - |
| - | [#66418](https://github.com/vllm-project/vllm/issues/66418) `[RFC]: DBO support for the DeepEP v2 backend in Model Runner V2` | nvidia | ? | - |
| - | [#66420](https://github.com/vllm-project/vllm/pull/66420) `[DBO] Support DBO in the DeepEP v2 backend on MRV2` | nvidia | ? | - |
| - | [#66423](https://github.com/vllm-project/vllm/issues/66423) `[Bug]: Segfault during engine init with any --reasoning-parser on SM120 + NVFP4 W4A4 (flashinfer_cutlass MoE)` | bug,nvidia,quant,risk | ? | - |
| P1 | [#66424](https://github.com/vllm-project/vllm/pull/66424) `[ROCm][Perf] Route sink-less sparse MLA prefill to AITER OPUS on gfx950` | perf,rocm | ? | - |
| - | [#66426](https://github.com/vllm-project/vllm/issues/66426) `[Feature]: Support mm_processor_kwargs and media_io_kwargs across vllm.Render and vllm.Inference` |  | ? | - |
| - | [#66427](https://github.com/vllm-project/vllm/issues/66427) `[Feature]: Support output_mode: derender, parse_context, and decoded logprobs in vllm.Inference` |  | ? | - |
| - | [#66428](https://github.com/vllm-project/vllm/pull/66428) `[Bugfix][Spec Decode] Don't compile multi-module MTP drafters that pick their module by draft step` | bug | ? | - |
| - | [#66429](https://github.com/vllm-project/vllm/pull/66429) `docs(spec-decode): update stale V0 test links to current V1 paths` |  | ? | - |
| - | [#66430](https://github.com/vllm-project/vllm/issues/66430) `[Bug]: Gemma 4 tool chat template: with enable_thinking=false, no empty thought channel after a tool response` |  | ? | - |
| - | [#66431](https://github.com/vllm-project/vllm/pull/66431) `[Bugfix] Reserve SWA decode gather workspace in Dots3Note MLA backend` | bug | ? | - |
| - | [#66436](https://github.com/vllm-project/vllm/issues/66436) `[Bug]: Streaming /v1/responses drops logprobs for tokens with empty text deltas` | bug | ? | - |
| - | [#66437](https://github.com/vllm-project/vllm/issues/66437) `[Bug]: HummingLinearKernel (W4A16) computes wrong output for group sizes that don't tile its K-blocks; can_imp` | quant,risk | ? | - |
| - | [#66438](https://github.com/vllm-project/vllm/pull/66438) `[CI] Add registry layer cache to arm64 CPU image build` | infra,perf | ? | - |
| - | [#66439](https://github.com/vllm-project/vllm/pull/66439) `[CI] Start the test-deps pull earlier in the CUDA test stage` | infra,nvidia | ? | - |
| - | [#66440](https://github.com/vllm-project/vllm/pull/66440) `[Perf][Spec Decode] Keep full CUDA graphs when extracting hidden states` | nvidia,perf | ? | - |
| - | [#66442](https://github.com/vllm-project/vllm/pull/66442) `[MOE oracle][Refactor][2/N] Move INT8 backend priority and selection to base oracle` | quant | ? | - |
| - | [#66443](https://github.com/vllm-project/vllm/pull/66443) `[Bugfix][KV Connector] Renew push leases and fail expired receives` | bug,infra | ? | - |
| P1 | [#66444](https://github.com/vllm-project/vllm/pull/66444) `[ROCm] wvSplitK: keep bf16 N=5 at YTILE 2 on wave64 to avoid VGPR spills` | rocm | ? | - |
| - | [#66449](https://github.com/vllm-project/vllm/pull/66449) `[Bugfix] Preserve Responses API logprobs across empty text deltas` | bug | ? | - |
| - | [#66451](https://github.com/vllm-project/vllm/issues/66451) `[Performance][KV Cache][Kimi-K3.1-Pro] DCP8 wastes shared-pool capacity on replicated draft KV` | perf | ? | - |
| - | [#66452](https://github.com/vllm-project/vllm/issues/66452) `[Bug]: FlashInfer pinned planner workspace reuse corrupts async prefill/decode; fixes tracked upstream` | infra,nvidia,risk | ? | - |
| P1 | [#66454](https://github.com/vllm-project/vllm/pull/66454) `[ROCm][Bugfix] Route gfx950 BF16 sparse MLA sink layers to Triton` | bug,rocm | ? | - |
| - | [#66455](https://github.com/vllm-project/vllm/pull/66455) `Allow joint-schema decisions beyond 26 options` |  | ? | - |
| - | [#66456](https://github.com/vllm-project/vllm/pull/66456) `[MoE][Kernel] Support MXFP8 in FlashInfer CuteDSL batched experts for DeepEP low-latency` | infra,nvidia,perf,quant | ? | - |
| - | [#66457](https://github.com/vllm-project/vllm/pull/66457) `Fix NO DATA in query statistic dashboard  by fixing Deployment_ID query variables binding to DS_PROMETHEUS` | bug | ? | - |
| P1 | [#66459](https://github.com/vllm-project/vllm/issues/66459) `[Bug]: fused_recurrent_kda silently ignores num_accepted_tokens` | perf,risk | ? | - |
| - | [#66460](https://github.com/vllm-project/vllm/issues/66460) `ROCm FlexAttention paged-mask lookup changes BF16 output versus contiguous FlexAttention` | bug,rocm | ? | - |
| - | [#66463](https://github.com/vllm-project/vllm/pull/66463) `Refine Prometheus queries with model_name filtering in Performance Statistics Dashboard` | perf | ? | - |
| - | [#66464](https://github.com/vllm-project/vllm/pull/66464) `[Engram] PLE disk_offload: batched O_DIRECT reader (io_uring with pread fallback)` | infra | ? | - |
| - | [#66466](https://github.com/vllm-project/vllm/pull/66466) `[Perf][Multimodal] Reuse OpenCV capture for video metadata` | perf | ? | - |
| - | [#66467](https://github.com/vllm-project/vllm/issues/66467) `[RFC]: Faster Engram / PLE `disk_offload`: io_uring + O_DIRECT row reader and read/compute overlap` | perf | ? | - |
| - | [#66469](https://github.com/vllm-project/vllm/pull/66469) `[Bugfix][Kernel] Apply batched MoE biases before output rounding` | bug,perf | ? | - |
| - | [#66471](https://github.com/vllm-project/vllm/pull/66471) `fix: ignore compressed KV scales for unquantized caches` | bug,quant | ? | - |
| - | [#66472](https://github.com/vllm-project/vllm/pull/66472) `[Fast Start] Persist CUDA graphs with Foundry and prepare them during preload` | infra,nvidia | ? | - |
| - | [#66474](https://github.com/vllm-project/vllm/pull/66474) `[Tool Parser] Fall invoke-less DSML blocks back to content and drop name-truncated calls` | risk | ? | - |
| - | [#66475](https://github.com/vllm-project/vllm/pull/66475) `[Frontend][Responses] Reject empty assistant message content with 400 instead of 500` |  | ? | - |
| P0 | [#66484](https://github.com/vllm-project/vllm/pull/66484) `[ROCm][Perf] Tune MXFP4 MoE tiles on gfx942` | perf,quant,rocm | main | - |
| P0 | [#66485](https://github.com/vllm-project/vllm/pull/66485) `[ROCm][Perf] Use 64 split-KV segments for small decode batches on gfx942` | perf,rocm | main | - |
| - | [#66488](https://github.com/vllm-project/vllm/pull/66488) `[Bugfix][Quantization] Accept AWQ key names in MoeWNA16Config` | bug,quant | ? | - |
| - | [#66491](https://github.com/vllm-project/vllm/issues/66491) `[RFC]: Packed-weight INT4 GEMM (W4A16 / W4A8) for RDNA4 (gfx1200/gfx1201)` | quant,rocm | ? | - |
| - | [#66492](https://github.com/vllm-project/vllm/pull/66492) `[Perf][CPU] Speed up structured-output mask expansion` | perf | ? | - |
| - | [#66493](https://github.com/vllm-project/vllm/issues/66493) `[Bug]: Boolean env vars are parsed six different ways - "true" either crashes or is silently ignored` | bug,risk | ? | - |
| - | [#66496](https://github.com/vllm-project/vllm/pull/66496) `[Recipes] Add a 3x DGX Spark (GB10) TP3 capacity-first preset to DeepSeek-V4.1-Flash` | infra | ? | - |
| - | [#66498](https://github.com/vllm-project/vllm/pull/66498) `[Bugfix][Core] Raise a clear error for zero data_parallel_size_local in DP node layout` | bug | ? | - |
| - | [#66499](https://github.com/vllm-project/vllm/pull/66499) `[Bugfix][Attention] Honor num_accepted_tokens in fused_recurrent_kda (#66459)` | bug,perf | ? | - |
| - | [#66501](https://github.com/vllm-project/vllm/pull/66501) `[Quantization][Kernel] Honor non-MXFP4 activation overrides in MXFP4 MoE emulation` | perf,quant | ? | - |
| - | [#66502](https://github.com/vllm-project/vllm/pull/66502) `[Feature][KV Connector][Mooncake] Support HiSparse host-pool imports` |  | ? | - |
| - | [#66503](https://github.com/vllm-project/vllm/pull/66503) `[Perf][KV Cache] Automatically fit packed groups to draft pages` | perf | ? | - |
| - | [#66505](https://github.com/vllm-project/vllm/pull/66505) `[Quantization] Support compressed-tensors online transforms on routed MoE experts` | quant | ? | - |
| - | [#66506](https://github.com/vllm-project/vllm/pull/66506) `[Bench] Pad vllm bench forward batches as serving's CUDA graphs would` | nvidia,perf | ? | - |
| - | [#66507](https://github.com/vllm-project/vllm/issues/66507) `[Bug]: Streaming /v1/responses always emits empty logprobs=[] in response.output_text.done event` |  | ? | - |
| - | [#66508](https://github.com/vllm-project/vllm/pull/66508) `[Model][Frontend] Support /v1/audio/transcriptions for LFM3-Audio` |  | ? | - |
| - | [#66509](https://github.com/vllm-project/vllm/pull/66509) `[Test][Multimodal] Add HF-vs-vLLM generation tests for LFM3-VL and LFM3-Audio` |  | ? | - |
| - | [#66510](https://github.com/vllm-project/vllm/pull/66510) `[Perf][KV Offload] Select the canonical load path by fragment size` | perf | ? | - |
| - | [#66511](https://github.com/vllm-project/vllm/pull/66511) `[Perf][KV Offload] Autotune the DMA/Triton load cutoff at worker init (opt-in)` | perf,rocm | ? | - |
| - | [#66513](https://github.com/vllm-project/vllm/pull/66513) `[Bugfix][Responses] Populate logprobs in response.output_text.done streaming event` | bug | ? | - |
| - | [#66515](https://github.com/vllm-project/vllm/issues/66515) `enable_gqa=True can be 2.59x slower than materializing the KV cache - silent MATH-backend fallback at decode` | perf,risk | ? | - |
| - | [#66517](https://github.com/vllm-project/vllm/pull/66517) `[Frontend] Report created_cache_tokens in /inference/v1/generate and /v1/completions usage` |  | ? | - |
| - | [#66519](https://github.com/vllm-project/vllm/pull/66519) `[Bugfix][Quantization] Keep unit k/v scales on layers whose KV cache is not quantized` | bug,perf,quant | ? | - |
| - | [#66521](https://github.com/vllm-project/vllm/pull/66521) `[Perf][Sampler] CUDA top-k/top-p masking kernel for Hopper and Blackwell` | infra,nvidia,perf | ? | - |
| - | [#66522](https://github.com/vllm-project/vllm/pull/66522) `[Frontend][Perf] Add --tokenize-backend recipe for Rust segmented parallel prompt tokenization` | perf | ? | - |
| - | [#66524](https://github.com/vllm-project/vllm/issues/66524) `[Bug]: Kimi K3.1 low-latency decode with DSpark cannot start at TP8 on GPUs with fewer than 152 SMs (hardcoded` | perf | ? | - |
| - | [#66525](https://github.com/vllm-project/vllm/issues/66525) `[Bug]: Gemma4 suppression-token cache causes UnexpectedTracerError on TPU` | bug,perf | ? | - |
| - | [#66526](https://github.com/vllm-project/vllm/pull/66526) `[Misc] VLLM_TRITON_SYNC_AUTOTUNE_TP: same Triton autotune choice on every TP rank` | infra,perf,rocm | ? | - |
| - | [#66527](https://github.com/vllm-project/vllm/pull/66527) `[Perf][KV Offload] Load pages of any size through the Triton kernel (opt-in)` | perf,rocm | ? | - |
| - | [#66534](https://github.com/vllm-project/vllm/pull/66534) `[Perf][Spec Decode] Apply top-k (and top-p) cutoffs as target logits load in verification` | infra,perf | ? | - |
| - | [#66535](https://github.com/vllm-project/vllm/pull/66535) `[Bugfix][Frontend] Treat empty tools array as no tools in /tokenize` | bug | ? | - |
| - | [#66536](https://github.com/vllm-project/vllm/pull/66536) `Unify boolean environment variable parsing` |  | ? | - |
| - | [#66538](https://github.com/vllm-project/vllm/issues/66538) `[Feature]: Configurable request-header labels for Prometheus per-request metrics` |  | ? | - |
| - | [#66542](https://github.com/vllm-project/vllm/pull/66542) `[Bugfix][Prefix] Retain the SWA window block that lookahead hashing costs` | bug,perf | ? | - |
| - | [#66543](https://github.com/vllm-project/vllm/pull/66543) `[Bugfix] Unify boolean env-var parsing in vllm/envs.py` | bug | ? | - |
| - | [#66550](https://github.com/vllm-project/vllm/pull/66550) `[Docs] Point batch invariance users to zero-mismatch-rl recipes` |  | ? | - |
| - | [#66551](https://github.com/vllm-project/vllm/pull/66551) `[GLM-5.3-Flash] KDA RecoverSSM with the deferred verify` | perf | ? | - |
| - | [#66553](https://github.com/vllm-project/vllm/pull/66553) `docs: fix inaccurate return values in docstrings for in-place functions` | bug | ? | - |
| - | [#66554](https://github.com/vllm-project/vllm/pull/66554) `[Refactor][Quantization] Use QuantKey in Int8ScaledMMLinearLayerConfig` | nvidia,quant | ? | - |
| - | [#66555](https://github.com/vllm-project/vllm/pull/66555) `[Refactor] Encoder cache extension hooks for MRV2` | perf | ? | - |
| - | [#66556](https://github.com/vllm-project/vllm/issues/66556) `[RFC]: Define an Optional In-Tree Integration Path for Hardware Backends` |  | ? | - |
| - | [#66557](https://github.com/vllm-project/vllm/issues/66557) `[Performance]: Adaptive verification's varlen decode graphs lose Triton split-KV at small batches` | perf,rocm | ? | - |
| - | [#66558](https://github.com/vllm-project/vllm/pull/66558) `[Core] Count KV connector hits in cache-aware admission` | perf | ? | - |
| - | [#66560](https://github.com/vllm-project/vllm/pull/66560) `[Kernel] Fuse the elementwise chain around get_top_tokens' all-gather` | perf | ? | - |
| - | [#66562](https://github.com/vllm-project/vllm/pull/66562) `[Perf][MoE] Raise the SM100 Triton fallback bound in TritonOrCutlassExperts to 32 tokens` | nvidia,perf,rocm | ? | - |
| - | [#66563](https://github.com/vllm-project/vllm/pull/66563) `[ROCm][Perf] Extend default CUDA graph sizes for speculative decoding with breakable graphs on CDNA4` | nvidia,perf,rocm | ? | - |
| - | [#66564](https://github.com/vllm-project/vllm/pull/66564) `[Quark][ROCm] MXFP4 MoE with dynamic MXFP8 activations` | quant,rocm | ? | - |
| - | [#66565](https://github.com/vllm-project/vllm/pull/66565) `[Bugfix][NIXL] Preserve SSM prefix reuse with EAGLE/MTP` | bug,perf | ? | - |
| - | [#66566](https://github.com/vllm-project/vllm/pull/66566) `[Feature][KV Connector][Mooncake] Add a verified-transfer debug mode` |  | ? | - |
| - | [#66567](https://github.com/vllm-project/vllm/pull/66567) `[Core] Share snapshot resource operations across sessions and checkpoints` | infra | ? | - |
| - | [#66569](https://github.com/vllm-project/vllm/pull/66569) `[Feature][KV Connector] Add a KV compatibility identity enforced by NIXL and offloading` | infra | ? | - |
| - | [#66570](https://github.com/vllm-project/vllm/issues/66570) `[RFC]: Async CPU tier setup for OffloadingConnector` |  | ? | - |
| - | [#66571](https://github.com/vllm-project/vllm/pull/66571) `[Bugfix] Acquire at cluster scope on the DSMEM mailbox waits and wait for the correction tcgen05.ld in the Dee` | bug,perf | ? | - |
| - | [#66572](https://github.com/vllm-project/vllm/pull/66572) `[ROCm][DSv4.1] Fuse the q RMSNorm and MXFP8 quant into one launch` | infra,perf,quant,rocm | ? | - |
| - | [#66573](https://github.com/vllm-project/vllm/issues/66573) `[Bug]: Qwen3.5 `qwen3_5.py` embedding does not receive `quant_config` (no dense fallback observed locally)` | quant | ? | - |
| - | [#66574](https://github.com/vllm-project/vllm/pull/66574) `[Feature][KV Connector] Notify connectors after startup KV cache preparation` | infra,perf | ? | - |
| - | [#66575](https://github.com/vllm-project/vllm/pull/66575) `[Perf][Rust Frontend] Compute multimodal prompt block hashes with canonical CBOR` | perf | ? | - |
| - | [#66576](https://github.com/vllm-project/vllm/pull/66576) `[Quantization] Support NGQ2 Qwen4Exp PLE tables` | infra,quant | ? | - |
| P1 | [#66578](https://github.com/vllm-project/vllm/pull/66578) `[Bugfix][ROCm] Kimi-K3: don't bake the fused decode MLA path into PIECEWISE graphs` | bug,infra,nvidia,perf,rocm | ? | - |
| - | [#66579](https://github.com/vllm-project/vllm/pull/66579) `[Metrics] Configurable request-header labels for per-request Prometheus metrics` | infra | ? | - |
| P0 | [#66580](https://github.com/vllm-project/vllm/pull/66580) `[Bugfix][ROCm] Convert ModelOpt FP8 MoE expert weights to e4m3fnuz` | bug,quant,rocm | main | - |
| - | [#66581](https://github.com/vllm-project/vllm/pull/66581) `[Model] Add Granite Docling` |  | ? | - |
| - | [#66585](https://github.com/vllm-project/vllm/pull/66585) `[Attention][Spec Decode] Capture varlen graphs at the split-K request bound` | nvidia | ? | - |
| P0 | [#66586](https://github.com/vllm-project/vllm/pull/66586) `[Bugfix][ROCm] Apply the e4m3fnuz KV-scale factor for compressed-tensors` | bug,quant,rocm | main | - |
| - | [#66587](https://github.com/vllm-project/vllm/issues/66587) `[ROCm][AMD] DeepSeek-V4.1-Flash gfx950 / MI355X Performance Optimization (vLLM)` | perf,rocm | ? | - |
| - | [#66588](https://github.com/vllm-project/vllm/issues/66588) `[ROCm][AMD] MiniMax-M3 gfx950 / MI355X Performance Optimization (vLLM)` | perf,rocm | ? | - |
| - | [#66590](https://github.com/vllm-project/vllm/issues/66590) `[Performance]: On H100, the default FP8 KV cache path (FA3, FP8 query) is ~11% slower than FlashInfer and its ` | nvidia,perf,quant | ? | - |
| - | [#66592](https://github.com/vllm-project/vllm/pull/66592) `[ROCm][Muse] Run BF16 MoE layers through AITER a16w16` | infra,rocm | ? | - |
| - | [#66594](https://github.com/vllm-project/vllm/pull/66594) `[Bugfix][KV Offload] Fix SimpleCPUOffload pinning for host pools over 256 GiB` | bug | ? | - |
| - | [#66595](https://github.com/vllm-project/vllm/pull/66595) `[KDA][Spec Decode] RecoverSSM: replay the accepted tokens in the next verify` |  | ? | - |
| - | [#66597](https://github.com/vllm-project/vllm/pull/66597) `[Model][Hardware][AMD] Enable DSR1 MXFP4 on gfx1250` | quant,rocm | ? | - |
| - | [#66599](https://github.com/vllm-project/vllm/pull/66599) `[Bugfix] Support Python reserved keywords as parameter names in pythonic tool parsers` | bug | ? | - |
| - | [#66601](https://github.com/vllm-project/vllm/pull/66601) `[Bugfix][Spec Decode] Fix DSpark top-k drafting with FP32 head logits` | bug | ? | - |
| - | [#66602](https://github.com/vllm-project/vllm/pull/66602) `[Core][KV Connector] Exclude cache-bypass requests from capped async KV load queues` | perf | ? | - |
| - | [#66607](https://github.com/vllm-project/vllm/pull/66607) `[Quant] LUT-B online quantization for linear layers` | quant | ? | - |
| - | [#66609](https://github.com/vllm-project/vllm/pull/66609) `[Bugfix][CI] Fix b12x default block size test after #63231` | bug,infra | ? | - |
| - | [#66610](https://github.com/vllm-project/vllm/issues/66610) `[Bug]: /detokenize returns 200 and silently drops out-of-vocabulary token IDs` | bug,risk | ? | - |
| - | [#66612](https://github.com/vllm-project/vllm/pull/66612) `[Spec Decode] Narrow the DFlash/DFlash2 draft block to the scheduled K under dynamic SD` | nvidia | ? | - |
| - | [#66614](https://github.com/vllm-project/vllm/pull/66614) `[Bugfix][Frontend] Reject out-of-vocabulary token ids in /detokenize` | bug | ? | - |
| - | [#66615](https://github.com/vllm-project/vllm/pull/66615) `[Bugfix][MoE] Pass activation_type in modular TRT-LLM FP8/MXFP8 experts` | bug,infra,nvidia,quant | ? | - |
| - | [#66619](https://github.com/vllm-project/vllm/pull/66619) `[Bugfix][Multimodal] Profile LLaVA-OneVision-2 with the frames its video budget admits` | bug | ? | - |
| - | [#66621](https://github.com/vllm-project/vllm/pull/66621) `[Kernel][Perf] Add fused MoE FP8 config for DeepSeek-V2-Lite on RTX 5090` | perf,quant | ? | - |
| - | [#66622](https://github.com/vllm-project/vllm/pull/66622) `[KVConnector][Core] Add MultiConnector opt-in to only load from first matching connector` |  | ? | - |
| - | [#66623](https://github.com/vllm-project/vllm/pull/66623) `[Feature][Kernel] Add opt-in CuTe DSL AOT cache` | infra,perf | ? | - |
| - | [#66627](https://github.com/vllm-project/vllm/issues/66627) `[Bug]: Cross-Tenant KV Cache Disclosure in vLLM MoRIIO WRITE Mode` | bug,perf,rocm | ? | - |
| - | [#66628](https://github.com/vllm-project/vllm/pull/66628) `[ROCm][BatchInvariant] Add gfx950 tuned tile table for the persistent matmul` | perf,rocm | ? | - |
| - | [#66629](https://github.com/vllm-project/vllm/issues/66629) `[Bug]: Cross-Request Prompt Leakage in vLLM Suffix Speculative Decoding` | bug | ? | - |
| - | [#66630](https://github.com/vllm-project/vllm/pull/66630) `[Perf][Sampler] CuTe DSL top-k/top-p filter (hierarchical maxima)` | infra,nvidia,perf | ? | - |
| - | [#66631](https://github.com/vllm-project/vllm/pull/66631) `[HiSparse] Batch owner bookkeeping when unpinning pages` | perf | ? | - |
| - | [#66634](https://github.com/vllm-project/vllm/pull/66634) `[Bugfix][V1] Enforce VLLM_ALLOW_INSECURE_SERIALIZATION in run_method (+ tests)` | bug | ? | - |
| - | [#66635](https://github.com/vllm-project/vllm/pull/66635) `[Recipe] Kimi-K3.1-Pro: set MI355X spec-decode block size to 1024 on Day 0 image case` | infra,rocm | ? | - |
| - | [#66636](https://github.com/vllm-project/vllm/pull/66636) `[Bugfix] Canonicalize case-insensitive environment choices before use` | bug | ? | - |
| - | [#66637](https://github.com/vllm-project/vllm/pull/66637) `[Feature][KV Offload] Enable compressed-MLA support for TP agnostic offloading` | perf | ? | - |
| - | [#66639](https://github.com/vllm-project/vllm/pull/66639) `[Perf][Sampler] Sample top-k rows from their kept tokens instead of masked logits` | perf | ? | - |
| - | [#66641](https://github.com/vllm-project/vllm/pull/66641) `[CI][XPU] Run Triton unified attention kernel tests on Intel GPU` | infra,nvidia,perf,rocm | ? | - |
| - | [#66647](https://github.com/vllm-project/vllm/pull/66647) `[Bugfix][Spec Decode] Key dynamic-SD tier on the running batch, not per-step scheduled count` | bug | ? | - |
| - | [#66648](https://github.com/vllm-project/vllm/issues/66648) `[Bug]: Grafana example latency panels scale with request rate` | perf,quant | ? | - |
| - | [#66649](https://github.com/vllm-project/vllm/pull/66649) `fix(observability): correct latency panel queries in Grafana dashboard` | bug,perf | ? | - |
| - | [#66650](https://github.com/vllm-project/vllm/issues/66650) `[RFC]: Classify GPU faults in fault-tolerance status and mark sticky CUDA errors dead` | nvidia | ? | - |
| - | [#66651](https://github.com/vllm-project/vllm/pull/66651) `[LoRA][BatchInvariant] Match an fp32-add LoRA reference: round the expand epilogue once under batch invariance` |  | ? | - |
| - | [#66656](https://github.com/vllm-project/vllm/pull/66656) `Update DeepEPV2 to 2.5` | nvidia | ? | - |
| - | [#66657](https://github.com/vllm-project/vllm/pull/66657) `[Perf][DSv4.1] Allow the specialized decode on SM107` | nvidia,perf | ? | - |
| - | [#66658](https://github.com/vllm-project/vllm/pull/66658) `[Bugfix][Spec Decode] Reject lossy verifiers with the shared suffix corpus` | bug | ? | - |
| - | [#66659](https://github.com/vllm-project/vllm/pull/66659) `[Model][Qwen4Exp] Fuse the gated shared expert into DeepGEMM MegaMoE` | perf | ? | - |
| - | [#66662](https://github.com/vllm-project/vllm/pull/66662) `[Perf] Batch and CUDA-graph the Voxtral Realtime audio frontend` | nvidia,perf | ? | - |
| - | [#66663](https://github.com/vllm-project/vllm/pull/66663) `[Test][Quantization] Cover Humming environment guards and the MoE enum priority path` | quant | ? | - |
| - | [#66664](https://github.com/vllm-project/vllm/pull/66664) `fix(parser): catch RecursionError in response_parser to prevent HTTP 500 on deeply nested payloads` | bug | ? | - |
| - | [#66665](https://github.com/vllm-project/vllm/pull/66665) `[Model] Add experimental request-level Nemotron-H Elastic widths` | infra,nvidia | ? | - |
| - | [#66666](https://github.com/vllm-project/vllm/pull/66666) `[Bugfix][Attention] FP8 KV cache on MLA loads checkpoint scales and follows reloads` | bug,infra,nvidia,perf,quant | ? | - |
| - | [#66667](https://github.com/vllm-project/vllm/pull/66667) `[Bugfix][Spec Decode] Preserve data_parallel_index across ParallelConfig replace for draft models` | bug | ? | - |
| - | [#66668](https://github.com/vllm-project/vllm/pull/66668) `[Model] Share one M-RoPE cache across ERNIE-4.5-VL layers without 4x headroom` | infra,perf | ? | - |
| - | [#66671](https://github.com/vllm-project/vllm/pull/66671) `[Core] Add --independent-data-parallel to run MoE DP ranks as independent replicas` |  | ? | - |
| - | [#66673](https://github.com/vllm-project/vllm/pull/66673) `[Bugfix][Spec Decode] Break the online acceptance estimator's separation feedback loop with a circuit breaker` | bug | ? | - |
| - | [#66675](https://github.com/vllm-project/vllm/pull/66675) `[Perf] Optimize GB10 Mamba2 projections and ReplaySSM dispatch` | infra,nvidia,perf | ? | - |
| - | [#66680](https://github.com/vllm-project/vllm/pull/66680) `[Bugfix][Core] Opt in to lifecycle-aware KV admission (#64460)` | bug,perf | ? | - |
| - | [#66681](https://github.com/vllm-project/vllm/pull/66681) `[FlashInfer] Enable distributed managed autotune caches` | infra,nvidia,perf | ? | - |
| - | [#66683](https://github.com/vllm-project/vllm/pull/66683) `[Docs] keep the prompt prefix cacheable in agent workloads` |  | ? | - |
| - | [#66684](https://github.com/vllm-project/vllm/pull/66684) `[Bugfix][Tool Parser] Fix Jamba, InternLM2 and Granite 20B FC streaming scientific notation` | bug | ? | - |
| - | [#66686](https://github.com/vllm-project/vllm/pull/66686) `[Bugfix][Mamba] Honor --mamba-ssm-cache-dtype for the shared KDA layers` | bug,infra,perf | ? | - |
| - | [#66694](https://github.com/vllm-project/vllm/pull/66694) `[Bugfix] Restore exact division in per-token-group FP8 quantization for non-UE8M0 scales` | bug,quant | ? | - |
| - | [#66696](https://github.com/vllm-project/vllm/issues/66696) `[Bug][KV Offload] A request with more unstored chunks than the CPU tier is never offloaded ("cannot store chun` |  | ? | - |
| - | [#66697](https://github.com/vllm-project/vllm/pull/66697) `[ROCm][MORI][Perf] Read the EPv2 AsyncLL segmented receive in place` | perf,rocm | ? | - |
| - | [#66698](https://github.com/vllm-project/vllm/issues/66698) `[Bug]: `vllm bench serve --num-warmups` primes the prefix cache, so the first measured request is a cache hit` | perf | ? | - |
| - | [#66699](https://github.com/vllm-project/vllm/issues/66699) `[ROCm Product Quality Control]: Weekly Kimi Vendor Verifier (KVV) accuracy regression testing CI on AMD` | bug,infra,risk,rocm | ? | - |
| - | [#66700](https://github.com/vllm-project/vllm/issues/66700) `[Bug]: In-process engine: requests aborted by a sleep or pause never finish, so `LLMEngine` stays busy forever` |  | ? | - |
| - | [#66701](https://github.com/vllm-project/vllm/pull/66701) `[Bugfix][Benchmark] Keep bench serve warmups and ready check out of the prefix cache` | bug,perf | ? | - |
| - | [#66703](https://github.com/vllm-project/vllm/pull/66703) `[Bugfix][Core] Deliver abort outputs of a pause to an in-process caller, and finish pooling requests ended wit` | bug | ? | - |
| - | [#66705](https://github.com/vllm-project/vllm/pull/66705) `[Core][Scheduler] Add shortest_prefill_first scheduling policy` |  | ? | - |
| - | [#66707](https://github.com/vllm-project/vllm/pull/66707) `[Bugfix][Benchmark] Keep vllm-bench warmups and ready check out of the prefix cache` | bug,perf | ? | - |
| - | [#66708](https://github.com/vllm-project/vllm/pull/66708) `[Perf][KV Offload] Lazy SimpleCPUOffload: offload before every GPU eviction, evict CPU copies of loaded blocks` | perf | ? | - |
| - | [#66712](https://github.com/vllm-project/vllm/pull/66712) `[Bugfix][MoRIIO] Validate WRITE prompt identity and coverage` | bug,rocm | ? | - |
| - | [#66713](https://github.com/vllm-project/vllm/issues/66713) `[EFA Product Quality Control]: Nightly multi-node E2E functionality, accuracy & performance testing for EFA NI` | nvidia,perf,risk | ? | - |
| - | [#66714](https://github.com/vllm-project/vllm/pull/66714) `Bump bufbuild/buf-action from 1.6.0 to 1.7.0` | infra | ? | - |
| - | [#66715](https://github.com/vllm-project/vllm/pull/66715) `[Metrics][Frontend] Record render duration for Responses requests` |  | ? | - |
| - | [#66717](https://github.com/vllm-project/vllm/pull/66717) `[Quantization] Support ModelOpt INT8_PB_WO routed experts` | infra,quant | ? | - |
| - | [#66718](https://github.com/vllm-project/vllm/pull/66718) `[ROCm][Kimi-K3][BatchInvariant] Use a fixed AttnRes tiling under batch invariance` | rocm | ? | - |
| - | [#66719](https://github.com/vllm-project/vllm/pull/66719) `[Bugfix][KV Offload] Store the chunks that fit when a request exceeds the CPU tier` | bug | ? | - |
| - | [#66720](https://github.com/vllm-project/vllm/pull/66720) `[Bugfix] Don't report sibling cache hits in n>1 prefill stats` | bug,perf | ? | - |
| - | [#66722](https://github.com/vllm-project/vllm/pull/66722) `[Model] Support Decision 3.0 prefix_bidir attention (vllm-sr/d3-turbo)` |  | ? | - |
| - | [#66724](https://github.com/vllm-project/vllm/issues/66724) `[Bug]: Prefill node livelocks forever (Running: 0, 0 tokens/step) with sliding-window KV groups and async KV l` |  | ? | - |
| - | [#66725](https://github.com/vllm-project/vllm/pull/66725) `[Bugfix][Core] Count only recyclable held blocks against the SWA admission cap` | bug,perf | ? | - |
| - | [#66726](https://github.com/vllm-project/vllm/pull/66726) `[Perf][DSv4.1] Look up Engram rows straight into the WKV's MXFP8 input` | perf,quant | ? | - |
| - | [#66727](https://github.com/vllm-project/vllm/issues/66727) `[Feature]: Release whl for torch 2.15.0 and cu134` | infra | ? | - |
| - | [#66728](https://github.com/vllm-project/vllm/pull/66728) `[Bugfix] functiongemma chat template: write the argument format the parser documents` | bug | ? | - |
| - | [#66729](https://github.com/vllm-project/vllm/issues/66729) `[Bug]: functiongemma chat template renders tool call arguments as Python reprs, not the format its parser docu` |  | ? | - |
| - | [#66732](https://github.com/vllm-project/vllm/pull/66732) `[test only][XPU] test UMD 26.35` | infra,nvidia | ? | - |
| - | [#66733](https://github.com/vllm-project/vllm/pull/66733) ` [MORI] Run MORI EPv2 on Quark MXFP4 MoE models; stop passing the received-row count` | quant,rocm | ? | - |
| - | [#66734](https://github.com/vllm-project/vllm/pull/66734) `[Bugfix] DBO and async EP fixes: Quark MoE shared experts, text-only multimodal DBO, padding-only DBO microbat` | bug,quant,rocm | ? | - |
| - | [#66735](https://github.com/vllm-project/vllm/pull/66735) `[MORI] Run MORI EPv2 across hosts (opt-in)` |  | ? | - |
| - | [#66736](https://github.com/vllm-project/vllm/pull/66736) `[ROCm][Perf][Kimi-K3] Merge the MoE router, latent, and shared gate_up bf16 GEMMs` | perf,rocm | ? | - |
| - | [#66738](https://github.com/vllm-project/vllm/pull/66738) `[Core][Scheduler] Add opt-in prefill chunk backoff for steps that would idle` | perf | ? | - |
| - | [#66739](https://github.com/vllm-project/vllm/pull/66739) `[Perf][Attention] Cache HPC attention K/V cache views per tensor` | perf | ? | - |
| - | [#66740](https://github.com/vllm-project/vllm/pull/66740) `[Bugfix][KV Offload] Refund unused sync-load budget` | bug | ? | - |
| - | [#66741](https://github.com/vllm-project/vllm/pull/66741) `[ROCm][Perf] Opt-in paged MTP verification in AITER FA` | perf,rocm | ? | - |
| - | [#66742](https://github.com/vllm-project/vllm/pull/66742) `[ROCm][Perf] Paged FP8 extend attention with efficient Q quantization` | perf,quant,rocm | ? | - |
| - | [#66743](https://github.com/vllm-project/vllm/pull/66743) `[ROCm][Perf] FP8 wide-batch verification with split-major scheduling` | perf,quant,rocm | ? | - |
| - | [#66748](https://github.com/vllm-project/vllm/pull/66748) `[ROCm][DCP] Opt-in DCP optimizations: global-key indexer prefill, AITER all-gather (stacked on #65685)` | infra,nvidia,perf,rocm | ? | - |
| - | [#66749](https://github.com/vllm-project/vllm/pull/66749) `[Kernel][MoE] Add FlashInfer CuTe-DSL unquantized MoE backend for Hopper (SM90)` | infra,nvidia,perf,quant | ? | - |
| - | [#66751](https://github.com/vllm-project/vllm/issues/66751) `[RFC]: Draft Window KV: Dual-Boundary Recovery and Sparse P/D Page Fill` |  | ? | - |
| - | [#66752](https://github.com/vllm-project/vllm/pull/66752) `[XPU][LoRA] Use dense GEMM for single-adapter prefill batches` | nvidia | ? | - |
| - | [#66753](https://github.com/vllm-project/vllm/issues/66753) `[RFC]: Tree speculative decoding in vLLM` |  | ? | - |
| - | [#66754](https://github.com/vllm-project/vllm/pull/66754) `[Perf][DSV4.1] Defer all-gather until after attention input projections` | perf | ? | - |
| - | [#66755](https://github.com/vllm-project/vllm/pull/66755) `[Perf][GLM-5.3 Flash] Defer all-gather until after attention input projections` | perf | ? | - |
| - | [#66756](https://github.com/vllm-project/vllm/pull/66756) `[Structured Outputs] Resolve special tokens when validating Lark grammars` | infra | ? | - |
| - | [#66759](https://github.com/vllm-project/vllm/pull/66759) `[Bugfix][Frontend] Exit the gRPC server when EngineCore dies` | bug | ? | - |
| - | [#66760](https://github.com/vllm-project/vllm/pull/66760) `[Perf][Attention] Cache Triton K/V cache views per tensor identity` | perf,rocm | ? | - |
| - | [#66761](https://github.com/vllm-project/vllm/pull/66761) `[Bugfix][Structured Output] Allow the template's newline after `</think>` before a constrained answer` | bug | ? | - |
| - | [#66762](https://github.com/vllm-project/vllm/pull/66762) `add xing4_0 tool parser_support` |  | ? | - |
| - | [#66763](https://github.com/vllm-project/vllm/pull/66763) `[Bugfix][Model] Fix pipeline-parallel loading and generation for LongCat-Flash-Lite` | bug | ? | - |
| - | [#66765](https://github.com/vllm-project/vllm/pull/66765) `[Perf][Core] Avoid scanning cache-aware queue backlog` | perf | ? | - |
| - | [#66766](https://github.com/vllm-project/vllm/pull/66766) `[Bugfix][KV Offload] Widen the lazy SimpleCPUOffload walk to cover CPU loads` | bug | ? | - |
| P1 | [#66769](https://github.com/vllm-project/vllm/pull/66769) `[ROCm][Attention][Kimi-K3.1] Accept fp8_ds_mla on gfx942 when AITER reads it in fnuz` | rocm | ? | - |
| - | [#66770](https://github.com/vllm-project/vllm/pull/66770) `[Bugfix] Fix FlashInfer DCP with FP8 KV cache` | bug,nvidia,perf,quant | ? | - |
| - | [#66771](https://github.com/vllm-project/vllm/pull/66771) `[ROCm] MXFP8 dispatch for AITER MXFP4 MoE under data parallelism` | quant,rocm | ? | - |
| - | [#66772](https://github.com/vllm-project/vllm/pull/66772) `[Bugfix][CPU] Apply e_score_correction_bias in CPU softmax routing` | bug,infra | ? | - |
| - | [#66775](https://github.com/vllm-project/vllm/pull/66775) `[ROCm] QuickReduce reduce-scatterv for the DP MoE combine` | nvidia,rocm | ? | - |
| - | [#66776](https://github.com/vllm-project/vllm/pull/66776) `[Bugfix][SpecDecode] Honor scheduled K in the suffix speculator under dynamic speculative decoding` | bug | ? | - |
| - | [#66778](https://github.com/vllm-project/vllm/pull/66778) `[Perf][Kernel][Quantization] Accelerate SM90 UE8M0 group FP8 prefills` | infra,nvidia,perf,quant | ? | - |
| - | [#66779](https://github.com/vllm-project/vllm/pull/66779) `[TPU] Support vllm_jax backend resolution and drop stale tpu-inference pin` | infra | ? | - |
| - | [#66782](https://github.com/vllm-project/vllm/issues/66782) `[RFC]: [KV Offload] Request-level KV promotions: decide at promotion time, pin until load` | infra | ? | - |
| - | [#66785](https://github.com/vllm-project/vllm/pull/66785) `[Feature] extract_hidden_states: stream hidden states to CPU pages with token-hash prefix backfill` |  | ? | - |
| - | [#66787](https://github.com/vllm-project/vllm/pull/66787) `[Model] Capture Qwen4Exp auxiliary states for PP speculative decoding` | infra | ? | - |
| - | [#66788](https://github.com/vllm-project/vllm/pull/66788) `[KV Events] Add source attribution and resource sharing scope` | infra,perf | ? | - |
| - | [#66790](https://github.com/vllm-project/vllm/pull/66790) `[Model][Spec Decode] Support DFlash with pipeline parallelism for MiMo-V2` |  | ? | - |
| - | [#66791](https://github.com/vllm-project/vllm/pull/66791) `[Perf][Qwen4Exp] Fuse HyperConnection up projection and gate mix on SM90` | nvidia,perf | ? | - |
| P1 | [#66792](https://github.com/vllm-project/vllm/pull/66792) `[Perf][Sampler] Exact Triton top-k/top-p kernel, ~3x faster` | perf,rocm | ? | - |
| - | [#66793](https://github.com/vllm-project/vllm/pull/66793) `[Attention] Add FlashInfer SM120 FP8 PRIMS prefill backend` | nvidia,quant | ? | - |
| - | [#66794](https://github.com/vllm-project/vllm/issues/66794) `[RFC]: extract_hidden_states — stream hidden states to CPU pages with token-hash prefix backfill` |  | ? | - |
| - | [#66795](https://github.com/vllm-project/vllm/pull/66795) `[Bugfix][NIXL] Push: stop WRITE submission stalls and early block release; lock the NIXL agent` | bug,infra | ? | - |
| - | [#66796](https://github.com/vllm-project/vllm/pull/66796) `[Refactor][ROCm] Add shared C++ AMD architecture utilities` | infra,rocm | ? | - |
| - | [#66797](https://github.com/vllm-project/vllm/pull/66797) `[Perf][CPU] Speed up sampling-mask packing` | perf | ? | - |
| - | [#66800](https://github.com/vllm-project/vllm/pull/66800) `[Perf][Spec Decode] Fuse DSpark Markov bias into greedy argmax` | perf | ? | - |
| - | [#66801](https://github.com/vllm-project/vllm/issues/66801) `[Bug]: Gemma 4 audio LoRA skips valid frames when batching unequal-length clips` |  | ? | - |
| - | [#66802](https://github.com/vllm-project/vllm/pull/66802) `[Benchmark][ROCm] Run the top-k/top-p benchmark without FlashInfer` | nvidia,perf,rocm | ? | - |
| - | [#66805](https://github.com/vllm-project/vllm/pull/66805) `[KV Offload] GDS kv offloading support` |  | ? | - |
| - | [#66806](https://github.com/vllm-project/vllm/issues/66806) `[Bug]: Investigate DeepSeek V4.1 producer prefill graph and replay output differences` |  | ? | - |
| - | [#66807](https://github.com/vllm-project/vllm/pull/66807) `[Bugfix][LoRA] Fix Gemma 4 audio adapter mappings for unequal-length clips` | bug,infra | ? | - |
| - | [#66808](https://github.com/vllm-project/vllm/pull/66808) `[Bugfix] Preserve valid candidates in structured beam search` | bug,infra | ? | - |
| - | [#66812](https://github.com/vllm-project/vllm/pull/66812) `[Kernel][Perf] Run GLM-5.3-Flash FP8 routed experts in SM90 DeepGEMM Mega MoE` | infra,nvidia,perf,quant | ? | - |
| - | [#66814](https://github.com/vllm-project/vllm/pull/66814) `[Bugfix][Spec Decode] Fix DeepSeek/GLM PP inputs for DFlash2` | bug,infra | ? | - |
| - | [#66815](https://github.com/vllm-project/vllm/pull/66815) `[Quantization] Make Humming MoE integer re-encoding optional` | infra,quant | ? | - |
| - | [#66816](https://github.com/vllm-project/vllm/pull/66816) `[Bugfix][CPU] Validate indices in the CPU block table ops` | bug | ? | - |
| - | [#66817](https://github.com/vllm-project/vllm/pull/66817) `[Bugfix][Kimi-K3.1-Pro] Preserve instructions and tools when rendering` | bug | ? | - |
| - | [#66818](https://github.com/vllm-project/vllm/pull/66818) `[Fast Start] Add PCP/DCP support` | infra,nvidia | ? | - |
| - | [#66820](https://github.com/vllm-project/vllm/pull/66820) `[Perf][Core] Add encoder length bucketing for padded audio encoders` | infra,perf | ? | - |
| P0 | [#66822](https://github.com/vllm-project/vllm/pull/66822) `[Bugfix][ROCm][GLM-5.3-Flash] Clamp num_warps for the kpool decode tail-ring update` | bug,rocm | main | - |
| - | [#66825](https://github.com/vllm-project/vllm/pull/66825) `[Feature][RL] Return logprobs aligned with the sampling mask, captured compactly per request` | perf | ? | - |
| - | [#66826](https://github.com/vllm-project/vllm/pull/66826) `[Bugfix][Kimi-K3.1] Find sparse MLA layers in flashinfer prefill hyperparam scan` | bug,nvidia | ? | - |
| - | [#66828](https://github.com/vllm-project/vllm/pull/66828) `[Model] Enable pipeline parallelism for GLM-5.3-Flash` |  | ? | - |
| - | [#66829](https://github.com/vllm-project/vllm/pull/66829) `[ROCm] Fuse Muse Spark's attention boundary into FlyDSL QuickReduce` | perf,rocm | ? | - |
| - | [#66831](https://github.com/vllm-project/vllm/pull/66831) `Log adaptive-verification budgets and per-request verified widths` |  | ? | - |
| - | [#66832](https://github.com/vllm-project/vllm/pull/66832) `[MoE][FlashInfer] Select the NVLink one-sided sync protocol, default auto` | nvidia | ? | - |
| - | [#66835](https://github.com/vllm-project/vllm/issues/66835) `[Bug]:  LFM2.5-2.6B GGUF fails to load: missing embed_tokens.qweight_type` | bug,quant | ? | - |
| - | [#66836](https://github.com/vllm-project/vllm/pull/66836) `MI350P mono` |  | ? | - |
| - | [#66837](https://github.com/vllm-project/vllm/pull/66837) `[KV Connector] Spec-driven TP slicing for NIXL (stacked on #61452)` | infra,nvidia,perf,rocm | ? | - |
| - | [#66838](https://github.com/vllm-project/vllm/pull/66838) `[Quantization] Route batch-invariant GPTQ linear through Humming when selection picks it` | infra,nvidia,quant | ? | - |
| - | [#66840](https://github.com/vllm-project/vllm/pull/66840) `[Kernel] Trap when a top-k scatter claims more than top_k output slots` | perf | ? | - |
| - | [#66843](https://github.com/vllm-project/vllm/pull/66843) `[ROCm][Perf] Run mixed batches through AITER's `fused_rearrange_sigmoid_gated_delta_rule`, and remove zero fil` | perf,rocm | ? | - |
| - | [#66844](https://github.com/vllm-project/vllm/issues/66844) `[RFC]: Exact-end Mamba states and whole-state eviction for hybrid prefix caching` | perf | ? | - |
| - | [#66845](https://github.com/vllm-project/vllm/pull/66845) `[Bugfix][GLM-5.3-Flash] Bound the accepted-count state lookup in the vendored KDA kernels` | bug,perf | ? | - |
| - | [#66847](https://github.com/vllm-project/vllm/pull/66847) `[Bugfix][Quantization] Backfill missing MIXED_PRECISION quantized_layers from hf_quant_config.json` | bug,quant | ? | - |
| - | [#66849](https://github.com/vllm-project/vllm/pull/66849) `[Model] Kimi-K3: accept video input` | infra | ? | - |
| - | [#66850](https://github.com/vllm-project/vllm/pull/66850) `[Frontend] Add vllm_server::serve_with_llm for a caller-supplied Llm` |  | ? | - |
| - | [#66851](https://github.com/vllm-project/vllm/pull/66851) `[Bugfix][Reasoning] Guard streaming split when marker text is stripped` | bug | ? | - |
| - | [#66856](https://github.com/vllm-project/vllm/pull/66856) `[ROCm][DSv4.1] Fuse the wo_a MXFP8 quant into the wo_a epilogue` | perf,quant,rocm | ? | - |
| - | [#66857](https://github.com/vllm-project/vllm/pull/66857) `[LoRA] Pin adapter tensors once, after expert-parallel slicing` | infra | ? | - |
| - | [#66858](https://github.com/vllm-project/vllm/issues/66858) `[RFC]: One rule for tools + response_format under tool_choice="auto" (Python and Rust frontends disagree)` |  | ? | - |
| - | [#66860](https://github.com/vllm-project/vllm/pull/66860) `[Benchmarks] Fix missing hash_block_size in benchmark_block_pool.py` | bug,perf | ? | - |
| - | [#66861](https://github.com/vllm-project/vllm/issues/66861) `[ROCm] routed_mxfp8 cases of test_fse_online_quantization_routed_shared fail with scale shape mismatch` | quant,rocm | ? | - |
| - | [#66862](https://github.com/vllm-project/vllm/pull/66862) `[Core][Rust] Rust engine core: scheduler, KV cache manager and connectors with bitwise parity` | infra,perf | ? | - |
| - | [#66863](https://github.com/vllm-project/vllm/pull/66863) `[Bugfix][Model] Fix LFM2 GGUF embedding and short conv weight shape` | bug,quant | ? | - |
| - | [#66864](https://github.com/vllm-project/vllm/pull/66864) `[Bugfix] Cap FlashInfer JIT build parallelism by available host memory` | bug,infra,nvidia | ? | - |
| - | [#66865](https://github.com/vllm-project/vllm/pull/66865) `[Perf][Qwen4Exp] Qwen3.8-Flash-Next specialized decode on GB300` | infra,nvidia,perf | ? | - |
| - | [#66867](https://github.com/vllm-project/vllm/pull/66867) `[DSA] Experimental: replicate sparse-MLA attention across TP ranks, with per-step routing` | infra,nvidia | ? | - |
| - | [#66868](https://github.com/vllm-project/vllm/pull/66868) `[GLM-5.x-Next] Experimental: replicate KDA and MLA mixers across TP ranks for slow inter-node TP` | infra,perf | ? | - |
| - | [#66869](https://github.com/vllm-project/vllm/pull/66869) `[DeepSeek-V4.1] Experimental: replicate attention across TP ranks for slow inter-node TP` | infra | ? | - |
| - | [#66870](https://github.com/vllm-project/vllm/pull/66870) `[Qwen4Exp] Experimental: replicate GDN and QSA mixers across TP ranks for slow inter-node TP` | infra | ? | - |
| - | [#66871](https://github.com/vllm-project/vllm/pull/66871) `[Muse Spark] Experimental: replicate attention across TP ranks for slow inter-node TP` | infra | ? | - |
| - | [#66872](https://github.com/vllm-project/vllm/pull/66872) `[NemotronH] Experimental: replicate Mamba2 and attention mixers across TP ranks for slow inter-node TP` | infra | ? | - |
| - | [#66873](https://github.com/vllm-project/vllm/issues/66873) `[RFC]: Replicate selected blocks across TP ranks for tensor parallelism over slow inter-node links` |  | ? | - |
| - | [#66874](https://github.com/vllm-project/vllm/pull/66874) `[Quant] Load compressed-tensors LUT-B MoE checkpoints` | quant | ? | - |
| - | [#66877](https://github.com/vllm-project/vllm/pull/66877) `[Frontend] Support X-Priority and RFC 9218 Priority headers` |  | ? | - |
| - | [#66879](https://github.com/vllm-project/vllm/pull/66879) `[Rust Frontend] Mirror the engine's LRU multimodal receiver cache` | perf | ? | - |
| - | [#66880](https://github.com/vllm-project/vllm/pull/66880) `[CPU] Support prompt embeds in the standalone CPU model runner` | infra | ? | - |
| - | [#66881](https://github.com/vllm-project/vllm/pull/66881) `[Core][Perf] Exact-end Mamba checkpoints and GreedyDual-Size eviction for hybrid prefix caching` | perf | ? | - |
| - | [#66882](https://github.com/vllm-project/vllm/pull/66882) `[Model][GLM-5.3] Load ModelOpt mixed-precision checkpoints into BF16 attention and vision` | quant | ? | - |
| - | [#66883](https://github.com/vllm-project/vllm/pull/66883) `[Quant] Add compressed-tensors LUT-B linear emulation` | quant | ? | - |
| - | [#66884](https://github.com/vllm-project/vllm/pull/66884) `[Perf][GLM-5.3-Flash] KDA: planar short conv for chunked prefill on SM10x` | infra,perf | ? | - |
| - | [#66885](https://github.com/vllm-project/vllm/issues/66885) `[Bug]: Cross-Tenant Vision-LoRA Cache Poisoning via Caller-Controlled UUIDs` | bug,perf | ? | - |
| - | [#66886](https://github.com/vllm-project/vllm/issues/66886) `[Bug]: MultiModuleMTPSpeculator Leaks Stale Request State into New Draft Contexts` | bug | ? | - |
| - | [#66888](https://github.com/vllm-project/vllm/pull/66888) `[CI][torch.compile] Keep Triton kernel caches in TestBackend` | infra,perf,rocm | ? | - |
| - | [#66889](https://github.com/vllm-project/vllm/pull/66889) `[Core][Rust] Native xgrammar structured output for the Rust engine core` | infra | ? | - |
| - | [#66890](https://github.com/vllm-project/vllm/pull/66890) `[ROCm][Kimi-K3][Spec Decode] Run the DSpark backbone with persistent kernels on MI355X` | infra,perf,rocm | ? | - |
| - | [#66893](https://github.com/vllm-project/vllm/pull/66893) `[Recipe] Add DFlash speculative decoding to Qwen3.5-35B-A3B` | infra | ? | - |
| - | [#66894](https://github.com/vllm-project/vllm/issues/66894) `[Feature]: Jetson AGX Thor (sm_110) support for sparse-attention models (GLM-5.3, DeepSeek-V4.1)` |  | ? | - |
| - | [#66895](https://github.com/vllm-project/vllm/pull/66895) `[Bugfix][DSv4.1] Copy Engram tables to integrated GPUs in cloned chunks` | bug | ? | - |
| - | [#66896](https://github.com/vllm-project/vllm/issues/66896) `[Bug]: DeepSeek-V4.1 image delimiter parameters escape `_mark_tower_model`` |  | ? | - |
| - | [#66897](https://github.com/vllm-project/vllm/pull/66897) `[Hardware][NVIDIA] Run DSA sparse attention on Jetson AGX Thor (sm_110)` | infra,nvidia | ? | - |
| - | [#66898](https://github.com/vllm-project/vllm/issues/66898) `[Bug]: RunAI streamer OOMs on DeepSeek-V4.1-Flash: Engram tables are streamed to the device instead of CPU` |  | ? | - |
| - | [#66901](https://github.com/vllm-project/vllm/pull/66901) `[Bugfix] Fix wrong per-row topk weights in Marlin MoE GEMM2` | bug,quant | ? | - |
| - | [#66903](https://github.com/vllm-project/vllm/pull/66903) `[Perf][Core] Skip idle KV cache groups in per-step allocation` | perf | ? | - |
| - | [#66904](https://github.com/vllm-project/vllm/issues/66904) `[MoE] Expose FlashInfer CUTLASS MoE's fused-finalize opt-out for run-to-run reproducibility (NVFP4, SM121)` | nvidia,perf,quant | ? | - |
| - | [#66905](https://github.com/vllm-project/vllm/pull/66905) `[MoE] Add VLLM_FLASHINFER_MOE_FUSED_FINALIZE to opt out of FlashInfer fused finalize` | nvidia,perf | ? | - |
| - | [#66906](https://github.com/vllm-project/vllm/pull/66906) `[Perf][MLA][DCP] Gather prefill queries before latent expansion` | infra,perf | ? | - |
| - | [#66907](https://github.com/vllm-project/vllm/pull/66907) `[Bugfix][Rust Frontend] Honor top-level thinking controls` | bug | ? | - |
| - | [#66908](https://github.com/vllm-project/vllm/pull/66908) `[Bugfix][Rust Frontend] Preserve system-message tool declarations` | bug | ? | - |
| - | [#66909](https://github.com/vllm-project/vllm/pull/66909) `[Bugfix][MLA][SM120] Enable sparse DCP through the shared MLA path` | bug,infra,nvidia | ? | - |
| - | [#66911](https://github.com/vllm-project/vllm/pull/66911) `[ROCm][Recipe] Qwen3.8-Flash-Next: verify BF16 on MI325X with AITER` | infra,rocm | ? | - |
| - | [#66912](https://github.com/vllm-project/vllm/issues/66912) `[Bug]: TP ranks can silently sample different tokens when their sampler configuration differs (FlashInfer fall` | nvidia,risk | ? | - |
| - | [#66913](https://github.com/vllm-project/vllm/pull/66913) `[XPU] Load AWQ int4 MoE checkpoints with zero-points` | nvidia,quant | ? | - |
| - | [#66915](https://github.com/vllm-project/vllm/issues/66915) `[Feature]: AMD Ryzen AI Halo aka strix halo vLLM upstream CI` | infra,rocm | ? | - |
| - | [#66916](https://github.com/vllm-project/vllm/pull/66916) `[Bugfix] TP ranks agree on the sampler backend and refuse mismatched sampling config` | bug,infra,perf | ? | - |
| - | [#66917](https://github.com/vllm-project/vllm/pull/66917) `[Bugfix][SM120] Enable CUTLASS FP8 grouped GEMM for MoE on SM12x (opt-in)` | bug,infra,nvidia,quant | ? | - |
| - | [#66918](https://github.com/vllm-project/vllm/pull/66918) `[Perf][MoE] Gather activation scales inside the moe_permute kernel` | perf,quant | ? | - |
| - | [#66919](https://github.com/vllm-project/vllm/pull/66919) `[Kernel][Perf] Add fused MoE FP8 config for Qwen3-30B-A3B TP2 on RTX 5090` | perf,quant | ? | - |
| - | [#66920](https://github.com/vllm-project/vllm/pull/66920) `[Bugfix][Multimodal] Domain-separate base and LoRA encoder-cache identifiers` | bug,perf | ? | - |
| - | [#66921](https://github.com/vllm-project/vllm/pull/66921) `[ROCm] Fuse the markov sampler and other kernels for Minimax M3.1` | infra,perf,rocm | ? | - |
| - | [#66923](https://github.com/vllm-project/vllm/pull/66923) `[Docs][Multimodal] Point the UUID docs at the security guidance and fix a stale note` | bug | ? | - |
| - | [#66926](https://github.com/vllm-project/vllm/pull/66926) `[XPU][CI] Enable v1/engine tests on XPU` | infra,nvidia | ? | - |
| - | [#66927](https://github.com/vllm-project/vllm/pull/66927) `[Core][DP] Add a cost-based cross-DP prefill hold` | infra | ? | - |
| - | [#66928](https://github.com/vllm-project/vllm/pull/66928) `[Core][EPD] Fail metadata-only items no EC or KV transfer covers` |  | ? | - |
| - | [#66929](https://github.com/vllm-project/vllm/pull/66929) `[Frontend] Support --allowed-local-media-path and --allowed-media-domains in the Rust frontend` |  | ? | - |
| - | [#66930](https://github.com/vllm-project/vllm/pull/66930) `[Core][EPD] Keep metadata-only items out of the receiver cache` | perf | ? | - |
| - | [#66931](https://github.com/vllm-project/vllm/pull/66931) `[Bugfix] Close HTTP clients when reuse is disabled` | bug | ? | - |
| - | [#66935](https://github.com/vllm-project/vllm/pull/66935) `[Fast start] EPLB support` | infra,rocm | ? | - |
| - | [#66936](https://github.com/vllm-project/vllm/pull/66936) `[Bugfix][Model] Stub DeepSeek-V4.1 image delimiter weights with the vision tower` | bug,nvidia | ? | - |
| - | [#66939](https://github.com/vllm-project/vllm/issues/66939) `[Bug]: kimi_k2 truncated tool-call markers corrupt arguments and function names, and leak into content` | risk | ? | - |
| - | [#66940](https://github.com/vllm-project/vllm/pull/66940) `[Bugfix] Drop marker fragments flushed into tool-call arguments at finish` | bug | ? | - |
| - | [#66941](https://github.com/vllm-project/vllm/pull/66941) `[Engram] PLE disk_offload: read the next prefill chunk's rows during the current step` | infra | ? | - |
| - | [#66942](https://github.com/vllm-project/vllm/issues/66942) `[RFC]: KV Trace monitoring` |  | ? | - |
| - | [#66943](https://github.com/vllm-project/vllm/pull/66943) `[Model][ROCm][Inkling]: Add support for Lamport P2P(hip kernels) collective on ROCm/AMD` | perf,rocm | ? | - |
| - | [#66944](https://github.com/vllm-project/vllm/pull/66944) `[Bugfix][RL] Stop sparse weight patches from storing NaN markers` | bug,risk | ? | - |
| - | [#66945](https://github.com/vllm-project/vllm/pull/66945) `[Bugfix][Spec Decode] Apply draft overrides atomically and name all2all conflicts` | bug | ? | - |
| - | [#66946](https://github.com/vllm-project/vllm/pull/66946) `[Perf][Kernel] Order head/feature blocks inner in GDN prefill conv & post-conv grids` | perf | ? | - |
| - | [#66947](https://github.com/vllm-project/vllm/issues/66947) `[Feature]: [KV Connector] Configure Mooncake Mamba snapshot write intervals` |  | ? | - |
| - | [#66948](https://github.com/vllm-project/vllm/pull/66948) `[Feature][KV Connector] Add Mamba snapshot intervals to Mooncake Store` | infra | ? | - |
| - | [#66949](https://github.com/vllm-project/vllm/issues/66949) `[RFC]: DWDP: Distributed Weight Data Parallelism for MoE Prefill` |  | ? | - |
| - | [#66950](https://github.com/vllm-project/vllm/pull/66950) `[Bugfix] Reject unsupported ALiBi in FlashInfer` | bug,nvidia | ? | - |
| - | [#66951](https://github.com/vllm-project/vllm/pull/66951) `[Bugfix][Spec Decode] Bound multi-module MTP re-prefill to valid request history` | bug | ? | - |
| - | [#66953](https://github.com/vllm-project/vllm/pull/66953) `[ROCm][Perf] Specialize full-K MXFP8 Block32 tile launches` | perf,quant,rocm | ? | - |
| - | [#66955](https://github.com/vllm-project/vllm/issues/66955) `[Bug]: MooncakeStoreConnector closes the store while transfer threads are still active` |  | ? | - |
| - | [#66956](https://github.com/vllm-project/vllm/pull/66956) `[Bugfix][KV Connector] Stop Mooncake store threads before closing` | bug | ? | - |
| - | [#66957](https://github.com/vllm-project/vllm/pull/66957) `[Bugfix][KV Connector] LMCache cpu offload example` | bug | ? | - |
| - | [#66958](https://github.com/vllm-project/vllm/pull/66958) `[ROCm][Perf] RDNA: head-first grid and vectorized stores for GDN prefill w/u and o kernels` | perf,rocm | ? | - |
| - | [#66959](https://github.com/vllm-project/vllm/pull/66959) `[Bugfix][KV Offload] Keep shared sliding-window blocks offloadable` | bug | ? | - |
| - | [#66960](https://github.com/vllm-project/vllm/issues/66960) `[Feature]: Sparse-MLA (DSA) attention on SM80/Ampere (A100): no selectable backend since the Triton fallback r` | rocm | ? | - |
| - | [#66961](https://github.com/vllm-project/vllm/pull/66961) `[Bugfix] Load Engram tables on CPU in the RunAI streamer loader` | bug | ? | - |
| - | [#66962](https://github.com/vllm-project/vllm/pull/66962) `[Core][DP] Keep requests with a session ID on one DP engine` |  | ? | - |
| - | [#66963](https://github.com/vllm-project/vllm/pull/66963) `[Perf][Attention] Cache DiffKV K/V cache views per tensor` | perf | ? | - |
| - | [#66964](https://github.com/vllm-project/vllm/pull/66964) `[ROCm][MORI] Dispatch the activation format AITER's fused MoE consumes in MORI EPv2` | perf,rocm | ? | - |
| - | [#66966](https://github.com/vllm-project/vllm/pull/66966) `[Bugfix] Stop weak_ref_tensor from keeping the base of 0-size views alive` | bug | ? | - |
| - | [#66967](https://github.com/vllm-project/vllm/pull/66967) `[ROCm][Perf] RDNA: head-first grid, vectorized stores and spill-free configs for GDN prefill kkt/solve_tril/fw` | perf,rocm | ? | - |
| - | [#66968](https://github.com/vllm-project/vllm/pull/66968) `[Bugfix][Core] Publish KV cache events immediately after prefix cache reset` | bug,perf | ? | - |
| - | [#66969](https://github.com/vllm-project/vllm/pull/66969) `[KVConnector] Enable HF3FS KV connector on non-CUDA devices` | nvidia | ? | - |
| - | [#66970](https://github.com/vllm-project/vllm/pull/66970) `[KV Connector][NIXL] Opt-in whole-row regions for GQA caches under block-outermost layouts` |  | ? | - |
| - | [#66972](https://github.com/vllm-project/vllm/pull/66972) `[Perf][Attention] Cache FlashInfer KV write views per tensor` | nvidia,perf | ? | - |
| - | [#66974](https://github.com/vllm-project/vllm/issues/66974) `[RFC]: Shared stream conformance cases for `vllm bench serve` and `vllm-bench`` | perf | ? | - |
| - | [#66975](https://github.com/vllm-project/vllm/pull/66975) `[XPU][Test] Enable Ray-based test_comm_ops tests on XPU` | nvidia | ? | - |
| - | [#66976](https://github.com/vllm-project/vllm/pull/66976) `[CI] Switch lm-eval GSM8K accuracy tests to gsm8k_platinum` | infra,risk | ? | - |
| - | [#66983](https://github.com/vllm-project/vllm/pull/66983) `[XPU][CI] Ignore direct DCP distributed tests in Intel CI` | infra,nvidia | ? | - |
| - | [#66987](https://github.com/vllm-project/vllm/pull/66987) `[MM][Kernel] FP8 ViT attention on SM 12.0 via FlashInfer's SM120 FP8 FMHA` | nvidia,perf,quant | ? | - |
| - | [#66989](https://github.com/vllm-project/vllm/issues/66989) `[Bug][Rust Frontend] gpt-oss can't be served through `vllm serve` with any tool/reasoning-parser flags` |  | ? | - |
| - | [#66991](https://github.com/vllm-project/vllm/issues/66991) `[Feature]: EC events: publish encoder cache presence and eviction from the EC connector` | perf | ? | - |
| - | [#66992](https://github.com/vllm-project/vllm/pull/66992) `[Bugfix][MoE] Reject topk exceeding selected-group capacity in grouped_topk` | bug | ? | - |
| - | [#66993](https://github.com/vllm-project/vllm/pull/66993) `[Bugfix] Fix FlashAttention DiffKV DCP output shape` | bug | ? | - |
| - | [#66996](https://github.com/vllm-project/vllm/pull/66996) `[LoRA] Synchronize MoE adapter slots across DP/EP ranks` | infra | ? | - |
| - | [#66997](https://github.com/vllm-project/vllm/pull/66997) `[Security] Validate native Pixtral image bounds before encoding` |  | ? | - |
| - | [#67000](https://github.com/vllm-project/vllm/pull/67000) `[Bugfix][KV Offload] Handle split kernel blocks in canonical mappings` | bug,perf | ? | - |
| - | [#67001](https://github.com/vllm-project/vllm/pull/67001) `[Bugfix][Frontend] Preserve DP rank in beam search and speech-to-text requests` | bug | ? | - |
| - | [#67004](https://github.com/vllm-project/vllm/pull/67004) ` [Model][Core] Share the PLE table between separate engine processes on one node` |  | ? | - |
| - | [#67010](https://github.com/vllm-project/vllm/pull/67010) `[ROCm] Route TP reduce-scatter through AITER's IPC kernel` | nvidia,perf,rocm | ? | - |
| - | [#67011](https://github.com/vllm-project/vllm/pull/67011) `[Bugfix] Fit speculative draft pages to TurboQuant targets` | bug,infra,perf,quant | ? | - |
| - | [#67012](https://github.com/vllm-project/vllm/issues/67012) `Weight loading: warn (optionally fail) when a single-file checkpoint coexists with an index/shard set in a loc` |  | ? | - |
| - | [#67013](https://github.com/vllm-project/vllm/pull/67013) `[ROCm][Attention] Support non-causal attention in ROCM_AITER_UNIFIED_ATTN` | rocm | ? | - |
| - | [#67014](https://github.com/vllm-project/vllm/pull/67014) `[MoE][Kernel] Quantize MXFP8 in the DeepEP low-latency dispatch (VLLM_DEEPEPLL_MXFP8_DISPATCH)` | infra,nvidia,perf,quant | ? | - |
| - | [#67016](https://github.com/vllm-project/vllm/pull/67016) `[Bugfix][Frontend] Keep developer messages in place for templates without the role` | bug | ? | - |
| - | [#67017](https://github.com/vllm-project/vllm/issues/67017) `[Bug]: The hard judgment of IMAGE_PLACEHOLDER is not elegant enough in Deepseekv4.1-flash on version of 0.33.0` | bug | ? | - |
| - | [#67018](https://github.com/vllm-project/vllm/pull/67018) `[Transformers backend] Serve bidirectional Llama with the Transformers modeling backend` |  | ? | - |
| - | [#67019](https://github.com/vllm-project/vllm/issues/67019) `[RFC]: Async EPLB: one owner for all state, worker runs self-contained jobs` |  | ? | - |
| - | [#67020](https://github.com/vllm-project/vllm/pull/67020) `[EPLB] Run async EPLB transfers as functions returning futures` | infra | ? | - |
| - | [#67021](https://github.com/vllm-project/vllm/pull/67021) `[Frontend][ToolParser] Stream Kimi K3 tool arguments incrementally` |  | ? | - |
| - | [#67027](https://github.com/vllm-project/vllm/pull/67027) `[CPU][RISC-V] Add a SpacemiT A100 vmadot.hp int4 GEMM` | infra,quant | ? | - |
| - | [#67028](https://github.com/vllm-project/vllm/issues/67028) `[Bug][KV Offload]: canonical_layout refuses to start with FlashInfer on pre-Blackwell GPUs: kernel-split block` | nvidia,perf | ? | - |
| - | [#67029](https://github.com/vllm-project/vllm/issues/67029) `[Bug]: Structured output tool-call grammar admits unbounded whitespace — generation runs away until max_tokens` |  | ? | - |
| - | [#67030](https://github.com/vllm-project/vllm/pull/67030) `[Feature] Add encoder cache events` | perf | ? | - |
| - | [#67031](https://github.com/vllm-project/vllm/pull/67031) `[Structured Output] Cap whitespace runs in tool-call grammars` |  | ? | - |
| - | [#67032](https://github.com/vllm-project/vllm/pull/67032) `[Bugfix][Rust][Benchmark] Reject unsupported prompt token ID configurations` | bug,perf | ? | - |
| - | [#67033](https://github.com/vllm-project/vllm/issues/67033) `[Bug][CPU]: VLLM_CPU_KVCACHE_SPACE=0 gives a 0-byte KV cache and the env var silently overrides --kv-cache-mem` | perf,risk | ? | - |
| - | [#67034](https://github.com/vllm-project/vllm/pull/67034) `[Spec Decode][Perf] Accelerate DSpark windowed MLA drafts with FlashMLA` | infra,nvidia,perf | ? | - |
| - | [#67036](https://github.com/vllm-project/vllm/pull/67036) `[ROCm][Perf][Qwen4Exp] Optimize QSA prefill scoring and FlyDSL attention` | perf,rocm | ? | - |
| - | [#67037](https://github.com/vllm-project/vllm/pull/67037) `[Frontend] Support grammar custom tools on Qwen Responses` |  | ? | - |
| - | [#67039](https://github.com/vllm-project/vllm/pull/67039) `[ROCm][MiniMax-M3.1] All gather in FP4 in TP configs` | quant,rocm | ? | - |
| - | [#67043](https://github.com/vllm-project/vllm/pull/67043) `[Benchmark] Share stream conformance cases between the Python and Rust bench clients` | infra,perf | ? | - |
| - | [#67044](https://github.com/vllm-project/vllm/pull/67044) `[Determinism] Canonical sparse-indexer top-k: deterministic set and order behind VLLM_DETERMINISTIC_SPARSE_TOP` | infra | ? | - |
| - | [#67045](https://github.com/vllm-project/vllm/pull/67045) `[Core][Spec Decode] Exact Mamba states under speculative decoding for hybrid prefix caching` | perf | ? | - |
| - | [#67046](https://github.com/vllm-project/vllm/pull/67046) `[Perf] Precompute Voxtral Realtime's constant AdaRMSNorm time-conditioning scale` | perf,quant | ? | - |
| - | [#67047](https://github.com/vllm-project/vllm/pull/67047) `[Bugfix][CPU] Stop VLLM_CPU_KVCACHE_SPACE from overriding kv_cache_memory_bytes` | bug | ? | - |
| - | [#67048](https://github.com/vllm-project/vllm/pull/67048) `[KV Connector] Support KV Sharing across Non-Divisible Tensor Parallel Sizes` | infra | ? | - |
| - | [#67049](https://github.com/vllm-project/vllm/pull/67049) `[Bugfix][Core] Publish connector KV events while idle` | bug,infra | ? | - |
| - | [#67051](https://github.com/vllm-project/vllm/pull/67051) `[MoE] Add Mooncake EP backend for XPU` | nvidia | ? | - |
| - | [#67052](https://github.com/vllm-project/vllm/pull/67052) `[KV Offload] Track the outcome of promoted chunks` |  | ? | - |
| - | [#67054](https://github.com/vllm-project/vllm/issues/67054) `[Bug]: Redundant EPLB experts are never loaded from stacked expert checkpoints (e.g. Qwen3.5-MoE)` | bug | ? | - |
| - | [#67057](https://github.com/vllm-project/vllm/pull/67057) `[Bugfix][Model] Fix ERNIE 4.5 VL pipeline startup and visual routing` | bug | ? | - |
| - | [#67059](https://github.com/vllm-project/vllm/pull/67059) `[Perf][Attention] Tile the Triton decode split-KV reduction on CUDA` | nvidia,perf,rocm | ? | - |
| - | [#67060](https://github.com/vllm-project/vllm/pull/67060) ` [Bugfix][Offload] Pin UVA-offloaded weights directly at their exact size` | bug,infra,nvidia | ? | - |
| - | [#67062](https://github.com/vllm-project/vllm/pull/67062) `[Bugfix][Model Loader] Warn on ambiguous local safetensors layouts` | bug | ? | - |
| - | [#67064](https://github.com/vllm-project/vllm/pull/67064) `[KV Connector][NIXL] Cut P/D loads at the Mamba prefix-cache checkpoint` | perf | ? | - |
| - | [#67065](https://github.com/vllm-project/vllm/issues/67065) `[Bug]: NixlConnector: with n > 1, prefill releases KV blocks after the first decode child's read, later childr` | infra | ? | - |
| - | [#67069](https://github.com/vllm-project/vllm/pull/67069) `[KV Offload] Add SchedulerView.lookup_request (RFC #66782)` |  | ? | - |
| P0 | [#67074](https://github.com/vllm-project/vllm/pull/67074) `[Bugfix][ROCm][MoRIIO] Make MoRIIO READ wait for pending KV block zeroing and copies` | bug,rocm | main | - |
| - | [#67075](https://github.com/vllm-project/vllm/pull/67075) `[NIXL] Pair KV pages by logical position for asymmetric P/D region layouts` |  | ? | - |
| - | [#67076](https://github.com/vllm-project/vllm/pull/67076) `[Model][DSv4.1] Token-shard the pre-replay decoder stream under ShardQ` | infra | ? | - |
| P1 | [#67077](https://github.com/vllm-project/vllm/pull/67077) `[Bugfix][P/D] Keep NIXL prefill blocks until every parallel sample has read them` | bug,infra | ? | - |
| - | [#67078](https://github.com/vllm-project/vllm/pull/67078) `[Bugfix][Tool Parser] Fix truncated DeepSeek V3 streaming tool arguments` | bug,risk | ? | - |
| - | [#67082](https://github.com/vllm-project/vllm/pull/67082) `[Bugfix][ROCm] Avoid KFD queue eviction after the first IPC weight update` | bug,rocm | ? | - |
| - | [#67084](https://github.com/vllm-project/vllm/pull/67084) `[Bugfix] Keep warmup block IDs within each KV block pool` | bug,nvidia | ? | - |
| - | [#67086](https://github.com/vllm-project/vllm/pull/67086) `[Observability] Deprecate --collect-detailed-traces instead of failing startup` |  | ? | - |
| - | [#67088](https://github.com/vllm-project/vllm/issues/67088) `[Bug]: Encoder cache not invalidated consistently on weight reload: `reload_weights` crashes (`Encoder cache m` | bug,perf | ? | - |
| - | [#67089](https://github.com/vllm-project/vllm/pull/67089) `[Core] Add prefill_schedule_backlog_interval to bound prefill bursts` |  | ? | - |
| - | [#67090](https://github.com/vllm-project/vllm/pull/67090) `[Core] Return per-item encoder outputs with the request's final output` |  | ? | - |
| - | [#67091](https://github.com/vllm-project/vllm/pull/67091) `[Frontend] Word timestamps in /v1/audio/transcriptions through a model hook` |  | ? | - |
| - | [#67095](https://github.com/vllm-project/vllm/pull/67095) `[ROCm][GLM-5.3] Specialized decode for GLM-5.3, on top of #60889` | infra,rocm | ? | - |
| - | [#67097](https://github.com/vllm-project/vllm/pull/67097) `[Bugfix][Model Loader] Map safetensors checkpoints read-only on integrated GPUs` | bug | ? | - |
| - | [#67100](https://github.com/vllm-project/vllm/pull/67100) `[Bugfix][Attention] Store TurboQuant k8v4 FP8 keys as real E4M3 below sm_89` | bug,infra,quant | ? | - |
| - | [#67101](https://github.com/vllm-project/vllm/pull/67101) `[Bugfix] Stream plain text that starts with [ in pythonic tool parsers` | bug | ? | - |
| - | [#67103](https://github.com/vllm-project/vllm/issues/67103) `[RFC]: int8-key / int4-value per-token-head KV cache dtype (between int8 and int4)` | perf,quant | ? | - |
| - | [#67106](https://github.com/vllm-project/vllm/pull/67106) `[Perf][Audio] Cache torchcodec load failure; honour audio_backend in STT` | perf | ? | - |
| - | [#67108](https://github.com/vllm-project/vllm/pull/67108) `[Bugfix][Frontend] Order complete tool-result batches by call ID` | bug | ? | - |
| - | [#67109](https://github.com/vllm-project/vllm/pull/67109) `[Perf][KV Connector] Serve Mooncake store lookups from a separate process` | perf | ? | - |
| P1 | [#67110](https://github.com/vllm-project/vllm/issues/67110) `[ROCm][Performance] `wvSplitK` skinny GEMM is 3 to 8x slower than hipBLASLt at 3 and 5 activation rows on gfx9` | perf,rocm | ? | - |
| - | [#67111](https://github.com/vllm-project/vllm/pull/67111) `[Bugfix][Multimodal] Size multimodal profiling from the processor's effective kwargs` | bug | ? | - |
| - | [#67112](https://github.com/vllm-project/vllm/pull/67112) `[Bugfix][Multimodal] Size the Gemma 4 profiling dummies to their token budgets` | bug | ? | - |
| - | [#67122](https://github.com/vllm-project/vllm/pull/67122) `[Recipe] Add SmolLM3-3B deployment recipe` | infra | ? | - |
| - | [#67123](https://github.com/vllm-project/vllm/pull/67123) `[CI] Add Qwen3-VL multimodal serving benchmark (refs #16353)` | infra,perf | ? | - |
| - | [#67124](https://github.com/vllm-project/vllm/pull/67124) `[MM][CG] ViT full CUDA graph support for Skywork-R1V (refs #38175)` | nvidia | ? | - |
| - | [#67125](https://github.com/vllm-project/vllm/pull/67125) `[Bugfix] Apply soft cap before scale in get_top_k_tokens (refs #65401)` | bug,quant | ? | - |
| - | [#67126](https://github.com/vllm-project/vllm/pull/67126) `[Bugfix][Quantization] Keep unit k/v scales on compressed-tensors layers (refs #66129)` | bug,quant | ? | - |
| - | [#67127](https://github.com/vllm-project/vllm/pull/67127) `Validate compilation_config.backend for torch.compile modes (refs #66241)` |  | ? | - |
| - | [#67128](https://github.com/vllm-project/vllm/pull/67128) `[Bugfix] Reject non-StructuredOutputsParams structured_outputs with a validation error (refs #66248)` | bug | ? | - |
| - | [#67129](https://github.com/vllm-project/vllm/pull/67129) `[Bugfix][Responses] Keep logprobs of empty-text tokens in streaming deltas (refs #66436)` | bug | ? | - |
| - | [#67130](https://github.com/vllm-project/vllm/pull/67130) `[Env] Add get_bool_env and migrate bool(int) boolean env getters (refs #66493)` |  | ? | - |
| - | [#67131](https://github.com/vllm-project/vllm/pull/67131) `[Frontend] Validate token ids in /detokenize instead of silently dropping them (refs #66610)` | bug,risk | ? | - |
| - | [#67132](https://github.com/vllm-project/vllm/pull/67132) `[Bugfix][Spec Decode] Reset multi-module MTP cache on slot admission (fixes #66886)` | bug,perf | ? | - |
| - | [#67133](https://github.com/vllm-project/vllm/pull/67133) `[ROCm][Attention] AITER FA: dedicated split-KV kernels for decode and speculative-decode verify (GQA 8, head 6` | perf,quant,rocm | ? | - |
| - | [#67134](https://github.com/vllm-project/vllm/pull/67134) `[KVConnector][Mooncake] Run store prefix lookups concurrently over DEALER/ROUTER` |  | ? | - |
| - | [#67137](https://github.com/vllm-project/vllm/issues/67137) `[Bug]: `vllm launch render` accepts `--lora-modules` but returns 404 for the adapter name on `/render` and `/d` | bug | ? | - |
| - | [#67138](https://github.com/vllm-project/vllm/pull/67138) `[Bugfix] Register --lora-modules names on the render server` | bug | ? | - |
| - | [#67139](https://github.com/vllm-project/vllm/pull/67139) `[Bugfix][Frontend] Refuse new /v1/realtime sessions during shutdown.` | bug,perf | ? | - |
| - | [#67140](https://github.com/vllm-project/vllm/pull/67140) `[Bugfix][CPU] Derive hybrid Mamba cache defaults after platform setup` | bug,perf | ? | - |
| - | [#67141](https://github.com/vllm-project/vllm/pull/67141) `[KV Events] Add opt-in complete full-attention snapshots` | infra | ? | - |
| - | [#67142](https://github.com/vllm-project/vllm/pull/67142) `[Recipe] DeepSeek-V4.1-Flash: add 4x RTX PRO 6000 (SM120) row` | infra,nvidia | ? | - |
| - | [#67143](https://github.com/vllm-project/vllm/pull/67143) `[XPU][KV Offload] Support SimpleCPUOffloadConnector on XPU` | infra,nvidia | ? | - |
| - | [#67144](https://github.com/vllm-project/vllm/pull/67144) `[Bugfix][Frontend] Fail speech-to-text requests that finish with error or abort` | bug | ? | - |
| - | [#67145](https://github.com/vllm-project/vllm/pull/67145) `[ROCm][Attention] AITER FA: FP8-query prefill attention (use_prefill_query_quantization)` | quant,rocm | ? | - |
| - | [#67146](https://github.com/vllm-project/vllm/pull/67146) `[Bugfix] Ripple parser: avoid O(N^2) argument conversion while streaming tool calls` | bug | ? | - |
| - | [#67147](https://github.com/vllm-project/vllm/issues/67147) `[Bug][MRV2] thinking_token_budget silently overrides allowed_token_ids and bad_words` | risk | ? | - |
| - | [#67149](https://github.com/vllm-project/vllm/pull/67149) `[Kernel] Selectable fused MQA+top-k prefill backend: add FlashTopK (SM90, SM100)` | infra,nvidia,perf | ? | - |
| - | [#67151](https://github.com/vllm-project/vllm/pull/67151) `[Frontend] Pass use_beam_search and max_completion_tokens to speech-to-text models` |  | ? | - |
| - | [#67153](https://github.com/vllm-project/vllm/pull/67153) `[Perf][Frontend] Seed the fast detokenizer with a prompt tail, not the full prompt` | perf | ? | - |
| P1 | [#67154](https://github.com/vllm-project/vllm/pull/67154) `[Bugfix][Attention] Fix TRITON_MLA NaN logits under CUDA graphs at batch>=3` | bug,nvidia,risk | ? | - |
| - | [#67155](https://github.com/vllm-project/vllm/pull/67155) `[Bugfix] Profile the forward again after a profiling pass that compiled` | bug | ? | - |
| - | [#67156](https://github.com/vllm-project/vllm/pull/67156) `[Bugfix] ParserEngine: scan for the tool name incrementally while streaming` | bug | ? | - |
| - | [#67157](https://github.com/vllm-project/vllm/issues/67157) `[Bug]: Qwen3-0.6B with --tool-call-parser qwen3_xml returns an empty message (Python) / leaked text (Rust fron` |  | ? | - |
| - | [#67159](https://github.com/vllm-project/vllm/pull/67159) `fix: reject thinking budgets conflicting with token constraints` | bug | ? | - |
| - | [#67160](https://github.com/vllm-project/vllm/pull/67160) `[Core][KV Events] KV cache events for recovery units and frontier keys in hybrid prefix caching` | perf | ? | - |
| - | [#67161](https://github.com/vllm-project/vllm/issues/67161) `[Bug]: A text-only Gemma 4 class keeps `is_mm_prefix_lm` true when its text config says `use_bidirectional_att` | bug | ? | - |
| - | [#67162](https://github.com/vllm-project/vllm/issues/67162) `[Bug]: Gemma 4 placeholder count ignores `do_resize=False`` | bug | ? | - |
| - | [#67163](https://github.com/vllm-project/vllm/pull/67163) `[Bugfix][Core] Reset the scheduler-side encoder cache on weight replacement` | bug,perf | ? | - |
| - | [#67164](https://github.com/vllm-project/vllm/pull/67164) `[Bugfix] qwen3 parser: recover hermes-style JSON tool bodies in <tool_call>` | bug | ? | - |
| - | [#67165](https://github.com/vllm-project/vllm/pull/67165) `[Bugfix] Clear mm_prefix for text-only classes of prefix-LM checkpoints` | bug | ? | - |
| - | [#67166](https://github.com/vllm-project/vllm/pull/67166) `[Bugfix] Don't re-append default custom ops on every `replace()`` | bug,quant,rocm | ? | - |
| - | [#67168](https://github.com/vllm-project/vllm/pull/67168) `[Bugfix][Multimodal] Honor Gemma 4 image resize settings` | bug | ? | - |
| - | [#67169](https://github.com/vllm-project/vllm/issues/67169) `[ROCm][AMD] MiniMax-M3.1-Flash gfx950 / MI355X Performance Optimization (vLLM)` | perf,rocm | ? | - |
| - | [#67170](https://github.com/vllm-project/vllm/issues/67170) `[Feature]:` |  | ? | - |
| - | [#67171](https://github.com/vllm-project/vllm/pull/67171) `[Bugfix][KV Cache] Let packed state groups fill the block_stride_alignment padding` | bug,perf | ? | - |
| - | [#67173](https://github.com/vllm-project/vllm/pull/67173) `[Bugfix] Don't align slot-mapped token caches to kernel blocks` | bug,perf | ? | - |
| - | [#67174](https://github.com/vllm-project/vllm/pull/67174) `[Bugfix][KV Connector] Fix MultiConnector handshake metadata routing` | bug | ? | - |
| - | [#67176](https://github.com/vllm-project/vllm/issues/67176) `[RFC]: UltraQuant: the scale constant c = 0.156 is MSE-optimal before the UE8M0 snap, not after; c ≈ 0.2 cuts ` | quant | ? | - |
| - | [#67180](https://github.com/vllm-project/vllm/pull/67180) `[Frontend] Add chat and multimodal options to offline pooling APIs` |  | ? | - |
| - | [#67183](https://github.com/vllm-project/vllm/issues/67183) `[Bug]: Regression from #47692 - `--data-parallel-start-rank 0` with `data_parallel_size == 1` crashes at start` | bug | ? | - |
| - | [#67185](https://github.com/vllm-project/vllm/pull/67185) `[Bugfix][HiSparse] Reclaim resident pages before allocating the next prefill chunk` | bug,perf | ? | - |
| - | [#67186](https://github.com/vllm-project/vllm/pull/67186) `[Bugfix][ROCm] Skip AITER RMSNorm + dynamic FP8 quant fusion when the norm weight dtype differs from the input` | bug,perf,quant,rocm | ? | - |
| - | [#67189](https://github.com/vllm-project/vllm/pull/67189) `[Bugfix][Responses] Keep empty reasoning blocks in Responses output` | bug | ? | - |
| - | [#67190](https://github.com/vllm-project/vllm/pull/67190) `[Bugfix][Multimodal] Fix Qwen2.5-VL M-RoPE input positions for pruned videos` | bug | ? | - |
| - | [#67191](https://github.com/vllm-project/vllm/pull/67191) `[ROCm][Muse Spark] Online MXFP4 target for the BF16 first/last-layer experts` | infra,quant,rocm | ? | - |
| - | [#67192](https://github.com/vllm-project/vllm/issues/67192) `[Bug]: top_k_per_row_prefill` (DSA sparse-attention indexer top-k) returns the selected indices in a non-deter` | bug | ? | - |
| - | [#67193](https://github.com/vllm-project/vllm/pull/67193) `[Perf][EPLB] Prepare routing maps on the async worker` | perf | ? | - |
| - | [#67195](https://github.com/vllm-project/vllm/pull/67195) `docs(logits_processor): explain scale-before-softcap order in get_top_k_tokens` | quant | ? | - |
| - | [#67197](https://github.com/vllm-project/vllm/issues/67197) `[RFC]: Resource bound for the `/tokenize` endpoint` |  | ? | - |
| - | [#67198](https://github.com/vllm-project/vllm/pull/67198) `[Perf][Mamba] Mamba2 SSD prefill: FlashInfer for checkpoint prefills` | infra,nvidia,perf | ? | - |
| - | [#67199](https://github.com/vllm-project/vllm/pull/67199) `[Spec Decode] Support draft_lm_head_quantization for LiLiCorr` | quant | ? | - |
| - | [#67200](https://github.com/vllm-project/vllm/pull/67200) `[Bugfix][Rust Frontend] Accept hermes-style JSON tool bodies in qwen3_xml` | bug | ? | - |
| - | [#67202](https://github.com/vllm-project/vllm/pull/67202) `[Perf][Kernel] Prefer FlashInfer b12x over FlashInfer CUTLASS for NVFP4 linear on SM120` | nvidia,perf,quant | ? | - |
| - | [#67203](https://github.com/vllm-project/vllm/pull/67203) `[KVConnector][NIXL] Chunked prefill push for full-attention models` |  | ? | - |
| - | [#67204](https://github.com/vllm-project/vllm/issues/67204) `[Feature]: Add a workload-aware E+PD sizing example` |  | ? | - |
| - | [#67206](https://github.com/vllm-project/vllm/pull/67206) `[Bugfix] Preserve attention sinks in FlashAttention DCP` | bug | ? | - |
| - | [#67207](https://github.com/vllm-project/vllm/issues/67207) `[RFC]: add chunked push for NixlPushConnector` |  | ? | - |
| - | [#67208](https://github.com/vllm-project/vllm/pull/67208) `[ROCm][Perf][GLM-5.3-Flash] Shard the kpool indexer prefill across TP` | infra,perf,rocm | ? | - |
| - | [#67209](https://github.com/vllm-project/vllm/pull/67209) `[Bugfix][Elastic EP] Rebuild weight-derived state after scale-up weight transfer` | bug,infra,quant | ? | - |
| - | [#67213](https://github.com/vllm-project/vllm/pull/67213) `[Bugfix][PCP] Use rank-local request counts for decode graph dispatch` | bug | ? | - |
| - | [#67214](https://github.com/vllm-project/vllm/pull/67214) `[Kernel] Guard cooperative_topk on SM12x and check cudaFuncSetAttribute` | nvidia,perf | ? | - |
| - | [#67216](https://github.com/vllm-project/vllm/pull/67216) `[Bugfix][ROCm][MoRIIO] READ mode restore the cached recurrent state for hybrid prefixes that end on a block` | bug,rocm | ? | - |
| - | [#67218](https://github.com/vllm-project/vllm/pull/67218) `[Bugfix][ROCm][MoRIIO] WRITE mode free prefill blocks released during prefill or under reused transfer id` | bug,infra,rocm | ? | - |
| - | [#67219](https://github.com/vllm-project/vllm/pull/67219) `[Perf][DSv4.1] Compose ShardQ with the candidate-only indexer prefill` | infra,perf | ? | - |
| - | [#67220](https://github.com/vllm-project/vllm/issues/67220) `[Tracking][Spec Decode] Context Aware Sparse LM Head Tracker` | quant | ? | - |
| - | [#67221](https://github.com/vllm-project/vllm/pull/67221) `[ROCm][Perf] Fix gfx11 paged attention register spill from V padding mask` | bug,perf,rocm | ? | - |
| - | [#67222](https://github.com/vllm-project/vllm/pull/67222) `[Refactor][Spec Decode] Share the draft vocabulary mapping in a DraftVocab helper` |  | ? | - |
| - | [#67223](https://github.com/vllm-project/vllm/pull/67223) `[Perf][Spec Decode] Fuse the sparse LM head logits scatter into one kernel` | infra,perf | ? | - |
| - | [#67224](https://github.com/vllm-project/vllm/pull/67224) `fix(sampler): ensure deterministic index ordering in top_k_per_row_prefill` | bug | ? | - |
| - | [#67227](https://github.com/vllm-project/vllm/issues/67227) `[Performance]: Mamba1 packed prefill sizes the selective scan launch from the total packed length, so many sho` | perf | ? | - |
| - | [#67229](https://github.com/vllm-project/vllm/pull/67229) `[DRAFT] Autotune gemm BF16 in offline mode` | nvidia,perf | ? | - |
| - | [#67230](https://github.com/vllm-project/vllm/pull/67230) `[Perf][Kernel] Size Mamba1 varlen selective scan launch from the longest sequence` | perf | ? | - |
| - | [#67231](https://github.com/vllm-project/vllm/issues/67231) `[Feature]:  Support Hugging Face Tokenizers v1` |  | ? | - |
| P0 | [#67232](https://github.com/vllm-project/vllm/pull/67232) `[Bugfix][ROCm] Fix fp8 NoPE NaN, fp16 crash and a decode-path sync in ROCM_AITER_MLA_SPARSE` | bug,quant,risk,rocm | main | - |
| - | [#67233](https://github.com/vllm-project/vllm/pull/67233) `[CI][ROCm] Add a ROCM_AITER_MLA_SPARSE and DSA indexer test suite` | infra,nvidia,perf,rocm | ? | - |
| - | [#67234](https://github.com/vllm-project/vllm/pull/67234) `[CI][ROCm] Add a ROCM_FLASHMLA_SPARSE_DSV41 backend test suite` | infra,nvidia,rocm | ? | - |
| - | [#67236](https://github.com/vllm-project/vllm/pull/67236) `[Spec Decode] Default the NVFP4 draft lm_head for MTP on DGX Spark (SM121)` | nvidia,quant | ? | - |
| - | [#67238](https://github.com/vllm-project/vllm/pull/67238) `[Spec Decode] Quantized rows for the context aware sparse LM head` | infra,quant | ? | - |
| - | [#67239](https://github.com/vllm-project/vllm/pull/67239) `[Doc] Fix the free queue order in the prefix caching design doc` | bug,perf | ? | - |
| - | [#67240](https://github.com/vllm-project/vllm/pull/67240) `[Bugfix][KV Offload] Create the shared region reservation memfd via libc` | bug | ? | - |
| - | [#67241](https://github.com/vllm-project/vllm/pull/67241) `[ROCm][Quantization][Perf] Fuse the 32-wide input Hadamard into the gated-norm MXFP4 GEMM fusion` | perf,quant,rocm | ? | - |
| - | [#67242](https://github.com/vllm-project/vllm/pull/67242) `[Bugfix][CPU] Validate extents and strides in the CPU FP8 quant ops` | bug,quant | ? | - |
| - | [#67245](https://github.com/vllm-project/vllm/pull/67245) `[Spec Decode] Log the resolved speculative config at startup` |  | ? | - |
| - | [#67246](https://github.com/vllm-project/vllm/pull/67246) `[Perf][Attention] Prefer FlashInfer for FP8 KV cache on Hopper` | infra,nvidia,perf,quant | ? | - |
| - | [#67247](https://github.com/vllm-project/vllm/issues/67247) `[Bug]: Streaming `/inference/v1/generate` ignores `--enable-force-include-usage`: no usage without `stream_opt` | bug | ? | - |
| - | [#67248](https://github.com/vllm-project/vllm/pull/67248) `[ROCm][CI] Run the MI355 spec decode sharded sampling test nightly only to reduce queue backlog` | infra,rocm | ? | - |
| - | [#67249](https://github.com/vllm-project/vllm/pull/67249) `[Bugfix] Apply --enable-force-include-usage to streaming generate` | bug | ? | - |
| - | [#67250](https://github.com/vllm-project/vllm/issues/67250) `[Feature]: Honor request priority (`X-Vllm-Priority` / `priority`) on `/v1/audio/transcriptions` and `/v1/audi` |  | ? | - |
| - | [#67252](https://github.com/vllm-project/vllm/pull/67252) `[CI] Allow opt-in job keys in /ci run` | infra | ? | - |
| - | [#67253](https://github.com/vllm-project/vllm/pull/67253) `[Responses] Track per-turn token usage and explicit incomplete reason` |  | ? | - |
| - | [#67254](https://github.com/vllm-project/vllm/pull/67254) `[Perf][MoE] Prefer Humming over DeepGEMM for DeepSeek-V4 MXFP4 MoE on SM120` | nvidia,perf,quant | ? | - |
| - | [#67255](https://github.com/vllm-project/vllm/pull/67255) `[Frontend] Honor request priority on the transcription and translation APIs` |  | ? | - |
| - | [#67259](https://github.com/vllm-project/vllm/issues/67259) `[Bug]: v0.32.0 GPU image ships incompatible OpenTelemetry dependencies` | bug | ? | - |
| - | [#67260](https://github.com/vllm-project/vllm/pull/67260) `[Security] Bound structured decision media per request` |  | ? | - |
| - | [#67261](https://github.com/vllm-project/vllm/issues/67261) `[RFC]: Clarify AMD target and architecture semantics across vLLM` | quant,rocm | ? | - |
| - | [#67262](https://github.com/vllm-project/vllm/pull/67262) `[HiSparse][Kimi K3.1] Support Kimi-K3.1's hybrid KDA + DSA layout` | nvidia,perf | ? | - |
| - | [#67264](https://github.com/vllm-project/vllm/issues/67264) `[Bug]: BLIP-2 tower/connector LoRA rejects a non-divisible encoder budget` | bug | ? | - |
| - | [#67265](https://github.com/vllm-project/vllm/pull/67265) `[Bugfix][Frontend] Keep Anthropic streamed tool calls whose name follows the arguments` | bug | ? | - |
| - | [#67266](https://github.com/vllm-project/vllm/pull/67266) `[Bugfix] Render DeepSeek image placeholder in text-only prompts` | bug,infra | ? | - |
| - | [#67270](https://github.com/vllm-project/vllm/pull/67270) `[WIP][ROCm][Perf][Qwen3.8] Use AITER tgemm for tuned shapes on gfx942` | infra,perf,rocm | ? | - |
| - | [#67271](https://github.com/vllm-project/vllm/pull/67271) `[Bugfix][LoRA] Allow non-divisible BLIP-2 encoder budgets` | bug | ? | - |
| - | [#67274](https://github.com/vllm-project/vllm/pull/67274) `[Bugfix][Docker] Keep vLLM's OpenTelemetry versions when installing KV connectors` | bug,infra | ? | - |
| - | [#67275](https://github.com/vllm-project/vllm/issues/67275) `[RFC][Performance] Generic batch-size-aware matmul configs for untuned batch-invariant shapes` | perf | ? | - |
| - | [#67276](https://github.com/vllm-project/vllm/pull/67276) `[ROCm][Perf][DSv4] DSV4 Sparse MLA Optimization` | perf,rocm | ? | - |
| - | [#67277](https://github.com/vllm-project/vllm/pull/67277) `[Transformers backend] Migrate A.X-K1 to the Transformers modeling backend` |  | ? | - |
| - | [#67278](https://github.com/vllm-project/vllm/pull/67278) `[CPU] Balance SGL INT8 MoE tile scheduling` | quant | ? | - |
| - | [#67281](https://github.com/vllm-project/vllm/pull/67281) `[Kernel] LUT-B SM107: store 256 B of codebooks per tile instead of 512 B` | nvidia,perf,quant | ? | - |
| - | [#67283](https://github.com/vllm-project/vllm/pull/67283) `[Transformers backend] Support ROCm AITER fused shared experts` | infra,perf,rocm | ? | - |
| - | [#67284](https://github.com/vllm-project/vllm/pull/67284) `[Perf][KV Connector] Serve Mooncake store lookups in parallel` | perf | ? | - |
| - | [#67285](https://github.com/vllm-project/vllm/pull/67285) `[Qwen3.5] Experimental: replicate the dense MLP across TP ranks (VLLM_QWEN3_5_REPLICATE_FFN)` | infra | ? | - |
| - | [#67287](https://github.com/vllm-project/vllm/issues/67287) `[Feature]: [KV Offload] Keep a request’s stored prefix when the request is larger than the CPU tier` |  | ? | - |
| - | [#67289](https://github.com/vllm-project/vllm/pull/67289) `[Docs] Document adding vLLM CPU to a uv project` |  | ? | - |
| - | [#67290](https://github.com/vllm-project/vllm/issues/67290) `[Feature]: Quantize MoE experts one at a time during loading for every online quantization scheme` | quant | ? | - |
| - | [#67292](https://github.com/vllm-project/vllm/issues/67292) `[Bug]: With chunked prefill off and async scheduling, a multimodal request deferred for encoder limits can be ` | bug | ? | - |
| - | [#67293](https://github.com/vllm-project/vllm/pull/67293) `warn when an FT-adjacent timeout is not shorter than the recovery timeout` |  | ? | - |
| - | [#67294](https://github.com/vllm-project/vllm/pull/67294) `[Frontend] Add endpoint plugin readiness and coordinated draining` | infra | ? | - |
| - | [#67298](https://github.com/vllm-project/vllm/issues/67298) `[Bug]: `vllm bench forward` hangs intermittently on ROCm` | bug,perf,rocm | ? | - |
| - | [#67300](https://github.com/vllm-project/vllm/pull/67300) `[Spec Decode] Add BF16 hierarchical LM head backends for Nemotron MTP` | infra,perf | ? | - |
| - | [#67301](https://github.com/vllm-project/vllm/pull/67301) `[Bugfix][KV Connector] Fix HF3FS storage rank derivation with pipeline parallelism` | bug,infra | ? | - |
| - | [#67303](https://github.com/vllm-project/vllm/pull/67303) `[Security] Validate request-local reasoners before scheduling` | infra | ? | - |
| - | [#67306](https://github.com/vllm-project/vllm/pull/67306) `[ROCm][Muse Spark] Decode MoE on native routes` | infra,rocm | ? | - |
| - | [#67313](https://github.com/vllm-project/vllm/issues/67313) `[Bug]: Tower/connector LoRA crashes or applies the wrong adapter when one step runs the MM encoder more than o` | bug | ? | - |
| - | [#67320](https://github.com/vllm-project/vllm/pull/67320) `[CI][torch.compile] Give each test its own torch.compile cache` | infra,perf | ? | - |
| - | [#67323](https://github.com/vllm-project/vllm/pull/67323) `[Bugfix][LoRA] don't swallow CancelledError in resolve_lora` | bug | ? | - |
| - | [#67324](https://github.com/vllm-project/vllm/pull/67324) `[ROCm][Perf][Kimi-K3] KDA speculative verify through AITER FlyDSL with a ReplaySSM ring` | infra,perf,rocm | ? | - |
| - | [#67325](https://github.com/vllm-project/vllm/pull/67325) `[Model] Add Inkling 2 Small` | infra,nvidia,quant | ? | - |
| - | [#67327](https://github.com/vllm-project/vllm/pull/67327) `[Feat] [AMD] ultraquant: Add MTP verify decode` | quant,rocm | ? | - |
| - | [#67328](https://github.com/vllm-project/vllm/pull/67328) `fix(dp): do not infer hybrid LB from --data-parallel-start-rank on one rank` | bug | ? | - |
| - | [#67329](https://github.com/vllm-project/vllm/pull/67329) `[Bugfix][KV Connector] Fix handshake metadata key collision across PCP ranks` | bug | ? | - |
| - | [#67330](https://github.com/vllm-project/vllm/issues/67330) `[RFC]: Kernel-owned LoRA fusion for quantized linear layers, starting with gfx1151 W4A16` | perf,quant,rocm | ? | - |
| - | [#67332](https://github.com/vllm-project/vllm/pull/67332) `[Bugfix][Offload] Keep UVA-offloaded weights offloaded when processing rebinds them` | bug | ? | - |
| - | [#67334](https://github.com/vllm-project/vllm/issues/67334) `[RFC]: Bidirectional attention spans, set per request` |  | ? | - |
| - | [#67335](https://github.com/vllm-project/vllm/pull/67335) `[Feat] Support multiple structured-output backends on one server` |  | ? | - |
| - | [#67340](https://github.com/vllm-project/vllm/pull/67340) `[Spec Decode][ROCm][Muse Spark] FP8 DSpark draft through the speculative config` | infra,quant,rocm | ? | - |
| - | [#67341](https://github.com/vllm-project/vllm/pull/67341) `[ROCm][gfx12][Do Not Merge] mxfp4 HIP kernel dense + moe` | infra,perf,quant,rocm | ? | - |
| - | [#67343](https://github.com/vllm-project/vllm/pull/67343) `[Bugfix][Rust Frontend]Validate missing coordinated DP config hashes` | bug | ? | - |
| - | [#67347](https://github.com/vllm-project/vllm/pull/67347) `[Model Loader] Share the disk_offload checkpoint row reader` |  | ? | - |
| - | [#67348](https://github.com/vllm-project/vllm/pull/67348) ` [RFC] implementation for #67197 to align on the CLI/env interface and default ceiling before polishing edge c` |  | ? | - |
| - | [#67349](https://github.com/vllm-project/vllm/pull/67349) `[Model][PP] Create embeddings, final norms, and LM heads only on pipeline stages that use them` |  | ? | - |
| - | [#67350](https://github.com/vllm-project/vllm/pull/67350) `[PP][MRV2] Add per-field tensor layouts for pipeline transport` | infra,nvidia | ? | - |
| - | [#67351](https://github.com/vllm-project/vllm/pull/67351) `[Perf] Tune Gemma 4 E2B/E4B batch-invariant matmuls on SM120` | nvidia,perf | ? | - |
| - | [#67352](https://github.com/vllm-project/vllm/pull/67352) `[Bugfix][Granite Speech] Fix encoder OOMs on long and mixed-length audio` | bug | ? | - |
| - | [#67353](https://github.com/vllm-project/vllm/pull/67353) `[Bugfix][Core] Align multimodal encoder profiling with encoder co-scheduling` | bug | ? | - |
| - | [#67354](https://github.com/vllm-project/vllm/pull/67354) `[CI][ROCm] Mirror PP equivalence tests on AMD` | infra,rocm | ? | - |
| - | [#67356](https://github.com/vllm-project/vllm/pull/67356) `fix(v1): keep spec-decode draft padding out of input_ids under async scheduling` | bug | ? | - |
| - | [#67357](https://github.com/vllm-project/vllm/issues/67357) `[RFC]: Decoder Append-Prefill for Multi-Turn Workloads in P/D Disaggregated Serving` |  | ? | - |
| - | [#67358](https://github.com/vllm-project/vllm/pull/67358) `[Rust Frontend] Share server startup and shutdown between serve and render` |  | ? | - |
| - | [#67360](https://github.com/vllm-project/vllm/issues/67360) `[Bug]: MiniCPM-V 4.7 canvas M-RoPE silently falls back to sequential positions when user text contains `</imag` | risk | ? | - |
| - | [#67361](https://github.com/vllm-project/vllm/pull/67361) `[Bugfix][Model] MiniCPM-V 4.7: pair image/slice markers by position` | bug | ? | - |
| - | [#67363](https://github.com/vllm-project/vllm/pull/67363) `[ROCm][Perf][DSv4.1] Build the MXFP4 indexer decode metadata in one launch` | infra,perf,quant,rocm | ? | - |
| P1 | [#67364](https://github.com/vllm-project/vllm/pull/67364) `[ROCm][Perf][DSv4.1] Insert the compressed KV cache inside the compression launch` | perf,rocm | ? | - |
| - | [#67365](https://github.com/vllm-project/vllm/pull/67365) `[ROCm][Perf][DSv4.1] Pack the decode sparse-MLA ragged top-k in one launch from the MXFP4 indexer's row bounds` | perf,quant,rocm | ? | - |
| - | [#67366](https://github.com/vllm-project/vllm/pull/67366) `[ROCm][Perf][DSv4.1] Fold the consumer remap into top-512; skip the -1 fill on all decode rows` | perf,rocm | ? | - |
| - | [#67367](https://github.com/vllm-project/vllm/pull/67367) `[ROCm][Perf][DSv4.1] Keep few-row gfx950 top-512 calls in one block up to 36K` | perf,rocm | ? | - |
| - | [#67368](https://github.com/vllm-project/vllm/pull/67368) `[ROCm][Perf][DSv4.1] Compute the indexer head weights inside the MXFP4 Q quant launch` | perf,quant,rocm | ? | - |
| - | [#67370](https://github.com/vllm-project/vllm/pull/67370) `[Bugfix][KV Connector][Mooncake] Use MEDIUM_CPU for Store BlockStored events` | bug | ? | - |
| - | [#67371](https://github.com/vllm-project/vllm/pull/67371) `[CI/Build] Bump lmcache to 0.5.7.post1 and check that its CUDA ops load` | infra,nvidia | ? | - |
| - | [#67372](https://github.com/vllm-project/vllm/pull/67372) `[ROCm] Add opt-in DSpark context projection sharding` | rocm | ? | - |
| - | [#67373](https://github.com/vllm-project/vllm/pull/67373) `[ROCm] Add opt-in Kimi AttnRes historical norm cache` | perf,rocm | ? | - |
| - | [#67374](https://github.com/vllm-project/vllm/pull/67374) `[Core] Persistent state: state pool, scheduling and release fence` | infra,nvidia,perf | ? | - |
| - | [#67375](https://github.com/vllm-project/vllm/pull/67375) `[Core] Persistent state: stream admission and admitted streams in AsyncLLM` | infra,nvidia,perf | ? | - |
| - | [#67376](https://github.com/vllm-project/vllm/pull/67376) `[Perf][BatchInvariant] Add generic Hopper matmul fallback` | nvidia,perf | ? | - |
| - | [#67380](https://github.com/vllm-project/vllm/pull/67380) `[ROCm][Muse Spark] Ulysses sequence parallelism for TEP prefill` | infra,rocm | ? | - |
| - | [#67381](https://github.com/vllm-project/vllm/pull/67381) `[ROCm][Muse Spark] Online fp8_per_channel dense linears on tuned FP8 kernels` | infra,perf,quant,rocm | ? | - |
| - | [#67382](https://github.com/vllm-project/vllm/pull/67382) `[ROCm][Spec Decode][Muse Spark] Fuse the DSpark Markov sampling steps` | infra,perf,rocm | ? | - |
| - | [#67384](https://github.com/vllm-project/vllm/issues/67384) `[ROCm][AMD] MiniMax-M3.1-Flash gfx950 / MI355X Performance Optimization (vLLM)` | perf,rocm | ? | - |
| - | [#67385](https://github.com/vllm-project/vllm/pull/67385) `[Bugfix][Scheduler] Don't let later image requests overtake a request deferred for encoder limits` | bug | ? | - |
| - | [#67386](https://github.com/vllm-project/vllm/pull/67386) `[Bugfix][Spec Decode] Preserve DFlash per-layer causality` | bug,infra,nvidia | ? | - |
| - | [#67387](https://github.com/vllm-project/vllm/pull/67387) `[Bugfix][Benchmark] Warn when custom dataset sampling truncates under --no-oversample` | bug,perf,risk | ? | - |
| - | [#67388](https://github.com/vllm-project/vllm/pull/67388) `[ROCm][Perf] W4A16: deferred-scale bf16 kernel for gfx1151 decode-sized M` | perf,quant,rocm | ? | - |
| - | [#67389](https://github.com/vllm-project/vllm/issues/67389) `[Bug]: fused_add_rms_norm launches a zero-sized grid on zero-token input` | bug,perf | ? | - |
| - | [#67390](https://github.com/vllm-project/vllm/pull/67390) `[Bugfix][Model] Use FP32 vision RoPE in Qwen3_VisionTransformer` | bug | ? | - |
| - | [#67392](https://github.com/vllm-project/vllm/pull/67392) `[ROCm][Perf][Muse Spark] Run the PTPC FP8 routed experts through AITER with `--moe-backend aiter`` | perf,quant,rocm | ? | - |
| - | [#67395](https://github.com/vllm-project/vllm/pull/67395) `[Bugfix][Core] Keep scheduler-only knobs out of the compile cache key` | bug,perf | ? | - |
| - | [#67396](https://github.com/vllm-project/vllm/pull/67396) `[Bugfix][Model Loader] Do not merge load-plan writes into a negative stride` | bug | ? | - |
| - | [#67397](https://github.com/vllm-project/vllm/pull/67397) `[Core][Spec Decode] Add independent Draft KV pools and divergent-hit recovery` | perf | ? | - |
| - | [#67401](https://github.com/vllm-project/vllm/issues/67401) `[Bug]: rotary_embedding silently miscomputes q/k with non-unit last-dimension stride` | bug,risk | ? | - |
| - | [#67402](https://github.com/vllm-project/vllm/pull/67402) `[Feature][KV Connector] Identify the KV identity's weights by checkpoint content` | infra | ? | - |
| - | [#67403](https://github.com/vllm-project/vllm/pull/67403) `[Feature][Frontend] Implement /kv_identity in the Rust frontend` | infra | ? | - |
| - | [#67404](https://github.com/vllm-project/vllm/pull/67404) `[Feature][KV Connector] Update the KV identity when weights change at runtime` | bug,infra | ? | - |
| - | [#67405](https://github.com/vllm-project/vllm/pull/67405) `[Feature][KV Connector] Check KV peers again after a KV identity change` | bug,infra | ? | - |
| - | [#67406](https://github.com/vllm-project/vllm/pull/67406) `[Fast start] Fix engram offloading compatibility with deepseek-v4.1-flash` | bug,infra | ? | - |
| - | [#67410](https://github.com/vllm-project/vllm/pull/67410) `[Bugfix][Kernel] Handle zero-token inputs in RMSNorm` | bug,perf | ? | - |
| - | [#67411](https://github.com/vllm-project/vllm/issues/67411) `[Bug]: fused_add_rms_norm silently produces incorrect results for non-unit innermost input strides` | bug,perf,risk | ? | - |
| - | [#67412](https://github.com/vllm-project/vllm/issues/67412) `[Feature]: Add native support for ZAQERIS AXIOM (ZaqerisAxiomForCausalLM)` | quant | ? | - |
| - | [#67413](https://github.com/vllm-project/vllm/pull/67413) `[Bugfix][Quantization] Keep checkpoint-excluded routed experts unquantized under moe_wna16` | bug,quant | ? | - |
| - | [#67414](https://github.com/vllm-project/vllm/pull/67414) `[Bugfix][Quantization] Remove the Qwen3.5 MTP draft quantization workaround` | bug,quant | ? | - |
| - | [#67415](https://github.com/vllm-project/vllm/pull/67415) `[KV Connector][Spec Decode] Add sparse Draft-window page fill for Mooncake` | perf | ? | - |
| - | [#67416](https://github.com/vllm-project/vllm/issues/67416) `[Bug]: sharded_state reload fails for DeepSeek-V4.1-Flash (TP4): "size of tensor a (1792) must match the size ` |  | ? | - |
| - | [#67417](https://github.com/vllm-project/vllm/pull/67417) `Patch 1.cathleentico` | infra | ? | - |
| - | [#67418](https://github.com/vllm-project/vllm/pull/67418) `[Bugfix] Handle zero-token inputs in fused_add_rms_norm` | bug,perf | ? | - |
| - | [#67419](https://github.com/vllm-project/vllm/pull/67419) `[Perf][DSA] Avoid CatArray in ShardQ nope/rope query exchange` | bug,perf | ? | - |
| - | [#67421](https://github.com/vllm-project/vllm/pull/67421) `[ROCm][Perf][Qwen3.8] Specialized decode up to 64 rows for Qwen3.8-2.4T on MI355X (--monokernel)` | infra,perf,rocm | ? | - |
| - | [#67422](https://github.com/vllm-project/vllm/pull/67422) `[Bugfix] Reject unsupported feature strides in rotary_embedding` | bug | ? | - |
| - | [#67423](https://github.com/vllm-project/vllm/pull/67423) `[Spec Decode][Perf] Project only missing Draft-window pages` | perf | ? | - |
| - | [#67425](https://github.com/vllm-project/vllm/issues/67425) `[Bug]: A request that declares no `tools` still runs the tool parser and loses the model text` |  | ? | - |
| - | [#67427](https://github.com/vllm-project/vllm/pull/67427) `[Bugfix][Frontend] Skip tool parsing for requests that declare no tools` | bug | ? | - |
| - | [#67428](https://github.com/vllm-project/vllm/pull/67428) `[XPU][CI] Split the XPU base image and reuse it across CI builds with docker bake` | infra,nvidia | ? | - |
| - | [#67429](https://github.com/vllm-project/vllm/pull/67429) `[Metrics] Size vector metric values per label set in reader` | bug | ? | - |
| - | [#67430](https://github.com/vllm-project/vllm/issues/67430) `[Feature]: vllm.Inference: retryable KV and EC load errors` |  | ? | - |
| - | [#67431](https://github.com/vllm-project/vllm/pull/67431) `[Bugfix] Honor EOS inclusion consistently in beam-search outputs` | bug,infra | ? | - |
| - | [#67434](https://github.com/vllm-project/vllm/pull/67434) `[Bugfix][Kernel] fused_add_rms_norm: reject input with non-unit last-dim stride` | bug,perf | ? | - |
| - | [#67436](https://github.com/vllm-project/vllm/pull/67436) `[DSv4.1][DSpark] Support adaptive verification in the native NVIDIA inverse-CDF sampler` | nvidia | ? | - |
| - | [#67440](https://github.com/vllm-project/vllm/pull/67440) `[CI][ROCm][DSv4.1] Allow a third of the tokens to flip an expert at TP8 in the mono layers test` | infra,rocm | ? | - |
| - | [#67441](https://github.com/vllm-project/vllm/pull/67441) `[Bugfix][Quantization] NVFP4 linear: fold per-shard weight global scales of merged layers into the block scale` | bug,quant | ? | - |
| - | [#67442](https://github.com/vllm-project/vllm/pull/67442) `[Core][Feature] Add opt-in per-request prefix-cache miss attribution` | perf | ? | - |
| - | [#67443](https://github.com/vllm-project/vllm/pull/67443) `[Docs][ROCm] Add Step-5-Preview recipe for MI325X and MI355X` | infra,rocm | ? | - |
| - | [#67444](https://github.com/vllm-project/vllm/pull/67444) `[ROCm][Attention][Perf][Kimi-k3.1] Add a gfx942 FlyDSL sparse MLA kernel for fp8_ds_mla prefill` | perf,rocm | ? | - |
| - | [#67445](https://github.com/vllm-project/vllm/pull/67445) `[ROCm][RDNA] ROCM_RDNA_ATTN: gfx1150..gfx1153 and RDNA4 tables, default on gfx115x` | infra,perf,rocm | ? | - |
| P0 | [#67446](https://github.com/vllm-project/vllm/pull/67446) `[ROCm][Bugfix] Route CDNA3 FP8 MLA decode to Triton past a 4 GiB KV view` | bug,quant,rocm | main | - |
| - | [#67447](https://github.com/vllm-project/vllm/pull/67447) `[Perf][Kernel] Fuse mixed-dtype casts into Triton causal-conv prefill and decode` | perf,rocm | ? | - |
| - | [#67448](https://github.com/vllm-project/vllm/pull/67448) `[Kernel] Enable DeepGEMM MegaMoE on SM120` | infra,nvidia,perf | ? | - |
| - | [#67449](https://github.com/vllm-project/vllm/pull/67449) `[Bugfix] Reject nonpositive offline beam concurrency limits` | bug | ? | - |
| - | [#67450](https://github.com/vllm-project/vllm/pull/67450) `[Bugfix] Preserve stable candidate ordering for online beam ties` | bug | ? | - |
| - | [#67451](https://github.com/vllm-project/vllm/pull/67451) `[Bugfix][Core] Defer partial-hit CoW whose source block is keyed in the same step` | bug,perf | ? | - |
| - | [#67452](https://github.com/vllm-project/vllm/pull/67452) `[Feature] Add opt-in prefix-cache miss diagnostics` | perf | ? | - |
| - | [#67454](https://github.com/vllm-project/vllm/issues/67454) `[Bug]: [InferHunt] Gemma4 offline parse_thinking_output returns an unfinished thought in the answer field` |  | ? | - |
| - | [#67457](https://github.com/vllm-project/vllm/pull/67457) `[Bugfix][MRV2] Map slot positions past a block-table row to the pad slot` | bug | ? | - |
| - | [#67459](https://github.com/vllm-project/vllm/pull/67459) `[Bugfix][LoRA] Keep an in-place LoRA reload when the adapter is evicted and reloaded` | bug | ? | - |
| - | [#67460](https://github.com/vllm-project/vllm/pull/67460) `[Bugfix][Reasoning] Extract unfinished Gemma4 thinking in parse_thinking_output` | bug | ? | - |
| - | [#67461](https://github.com/vllm-project/vllm/pull/67461) `[Bugfix][Multimodal][KV Connector] Make request-local multimodal IDs unique per renderer instance` | bug,infra | ? | - |
| - | [#67462](https://github.com/vllm-project/vllm/issues/67462) `[Performance]: [V1] [Performance Benchmark] Find benchmark setups that can test the effectiveness of combining` | perf | ? | - |
| - | [#67463](https://github.com/vllm-project/vllm/pull/67463) `[Bugfix][LoRA] Set multimodal tower/connector LoRA mappings per encoder batch` | bug | ? | - |
| - | [#67464](https://github.com/vllm-project/vllm/issues/67464) `[Bug]: Non-streaming Responses API puts reasoning-token logprobs on output_text` |  | ? | - |
| - | [#67465](https://github.com/vllm-project/vllm/issues/67465) `[Bug]: Request state and the DP routing entry leak when the send to the engine core fails` |  | ? | - |
| - | [#67467](https://github.com/vllm-project/vllm/pull/67467) `[Bugfix][Frontend] Release request state and the DP routing entry when the send to the engine core fails` | bug,infra | ? | - |
| - | [#67468](https://github.com/vllm-project/vllm/pull/67468) `[Perf][Attention] Use native small-head FlashMLA on H20 and H100` | nvidia,perf | ? | - |
| - | [#67470](https://github.com/vllm-project/vllm/pull/67470) `[CI] Shard the Arm CPU tests automatically (slowest Arm job 20.5 → ~15.5 min)` | infra | ? | - |
| - | [#67471](https://github.com/vllm-project/vllm/issues/67471) `[Bug] glm47 tool parser converts a quoted tag in prose into a real tool call with empty arguments` |  | ? | - |
| - | [#67472](https://github.com/vllm-project/vllm/pull/67472) `[Bugfix][Model] Initialize configured ColBERT projections after module setup` | bug | ? | - |
| - | [#67473](https://github.com/vllm-project/vllm/pull/67473) `[Perf][Pooling] Bound reference MaxSim matrices for long inference pairs` | perf | ? | - |
| - | [#67475](https://github.com/vllm-project/vllm/pull/67475) `[Bugfix] Preserve lanes when packing narrow integer quantized weights` | bug,quant | ? | - |
| - | [#67477](https://github.com/vllm-project/vllm/pull/67477) `[Bugfix][CPU] Preserve token logprobs under large shared logit offsets` | bug | ? | - |
| - | [#67478](https://github.com/vllm-project/vllm/issues/67478) `[Feature]: Bound the lifetime of per-name LoRA locks in serving` |  | ? | - |
| - | [#67480](https://github.com/vllm-project/vllm/pull/67480) `[Bugfix][Parser] Reject tool calls that omit schema-required arguments` | bug | ? | - |
| - | [#67481](https://github.com/vllm-project/vllm/pull/67481) `[Bugfix][Pooling] Honor configured precision in BERT MLM and SPLADE heads` | bug | ? | - |
| - | [#67482](https://github.com/vllm-project/vllm/pull/67482) `[Bugfix][Model] Load standard tied SPLADE checkpoint aliases` | bug | ? | - |
| - | [#67483](https://github.com/vllm-project/vllm/issues/67483) `[Bug]: rms_norm_static_fp8_quant and fused_add_rms_norm_static_fp8_quant mishandle inputs with a non-unit inne` | perf,quant | ? | - |
| - | [#67484](https://github.com/vllm-project/vllm/pull/67484) `[Bugfix][Kernel] Support inputs with a non-unit innermost stride in static FP8 RMSNorm` | bug,perf,quant | ? | - |
| - | [#67488](https://github.com/vllm-project/vllm/issues/67488) `[Bug]: v0.33.0 illegal memory access (Xid 31) during CUDA graph capture, Qwen3.6-27B-FP8 + LoRA on RTX PRO 600` | bug,nvidia,quant,risk | ? | - |
| - | [#67491](https://github.com/vllm-project/vllm/pull/67491) `[Bugfix][Tool Parser] Keep unparsed DeepSeek V3.1 tool calls as content` | bug | ? | - |
| - | [#67492](https://github.com/vllm-project/vllm/pull/67492) `Add TTL for cache entries` | infra,perf | ? | - |
| - | [#67493](https://github.com/vllm-project/vllm/pull/67493) `[Bugfix][GLM-5.3-Flash] Respect configured video budget during startup profiling` | bug | ? | - |
| P1 | [#67494](https://github.com/vllm-project/vllm/pull/67494) `[Perf][ROCm] AWQ: keep awq_gemm for decode under torch.compile` | perf,quant,rocm | ? | - |
| - | [#67495](https://github.com/vllm-project/vllm/pull/67495) `[Kernel][ROCm] AWQ Triton: decode-friendly block sizes for M<=16` | perf,quant,rocm | ? | - |
| - | [#67496](https://github.com/vllm-project/vllm/pull/67496) `[Bugfix][Tool Parser] Keep unparsed HY V3 tool calls as content` | bug | ? | - |
| - | [#67498](https://github.com/vllm-project/vllm/pull/67498) `[Bugfix][MoE] Reject expert biases in backends that cannot apply them` | bug,nvidia | ? | - |
| - | [#67499](https://github.com/vllm-project/vllm/pull/67499) `[ROCm][Kimi-K3] Run the specialized decode with online FP8 linears` | infra,quant,rocm | ? | - |
| - | [#67500](https://github.com/vllm-project/vllm/pull/67500) `[ROCm][Kimi-K3] Fuse the FP8 per-token quant into the HIP communicator's AttnRes epilogue` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#67501](https://github.com/vllm-project/vllm/pull/67501) `[ROCm][Kimi-K3] Run the token-sharded prefill's residual RS / AG on AITER's INT4 collectives` | infra,quant,rocm | ? | - |
| - | [#67503](https://github.com/vllm-project/vllm/pull/67503) `[Doc] Add Atomic Agent deployment guide` |  | ? | - |
| - | [#67504](https://github.com/vllm-project/vllm/pull/67504) `[TieredOffloading][Benchmarks] Add benchmarks for TieredOffloading ` | perf | ? | - |
| - | [#67506](https://github.com/vllm-project/vllm/pull/67506) `[Perf] Batch per-output sample logprobs in EngineCoreOutputs for transport` | perf | ? | - |
| P1 | [#67507](https://github.com/vllm-project/vllm/pull/67507) `[ROCm][Bugfix][Kimi-K3] Label the fused MLA fp8 outputs with the platform fp8 dtype` | bug,infra,perf,quant,rocm | ? | - |
| - | [#67508](https://github.com/vllm-project/vllm/pull/67508) `[Bugfix][Frontend] Replace invalid tool call names by a placeholder in the Mistral renderer history` | bug | ? | - |
| - | [#67509](https://github.com/vllm-project/vllm/pull/67509) `[Bugfix][Reasoning] Keep text before <think> in Hunyuan A13B output` | bug | ? | - |
| - | [#67510](https://github.com/vllm-project/vllm/pull/67510) `[Perf][HiSparse] Token-sharded sparse-MLA prefill under TP` | perf | ? | - |
| - | [#67511](https://github.com/vllm-project/vllm/issues/67511) `[Feature]: Support fastino/GLiNER2.5-Decide in vLLM's Decisions APIs` |  | ? | - |
| - | [#67512](https://github.com/vllm-project/vllm/pull/67512) `[Model] Add GLiNER2.5 Decide` |  | ? | - |
| - | [#67513](https://github.com/vllm-project/vllm/issues/67513) `[Bug]: When max_tokens cuts a tool call, non-streaming tool parsers disagree on content` |  | ? | - |
| - | [#67514](https://github.com/vllm-project/vllm/pull/67514) `[Metrics][Parser] Add parser latency histograms and opt-in slow-parse warnings` | perf | ? | - |
| - | [#67515](https://github.com/vllm-project/vllm/pull/67515) `[Bugfix][Spec Decode] Isolate Mistral EAGLE draft configuration` | bug | ? | - |
| - | [#67517](https://github.com/vllm-project/vllm/pull/67517) `[Bugfix][Rust] Support metadata-only inference media` | bug | ? | - |
| - | [#67518](https://github.com/vllm-project/vllm/pull/67518) `[Model][MiniMax-M3] SM120 Blackwell NVFP4 KV cache Triton reader` | nvidia,perf,quant,rocm | ? | - |
| - | [#67520](https://github.com/vllm-project/vllm/issues/67520) `[Bug]: 15 tests in tests/parser/mistral fail on main since #65744 (tool_choice=None now normalized to "none")` | bug | ? | - |
| - | [#67521](https://github.com/vllm-project/vllm/issues/67521) `[Bug]: FlashInfer PCIe IPC all-reduce workspace is allocated after KV cache sizing` | nvidia,perf | ? | - |
| - | [#67522](https://github.com/vllm-project/vllm/pull/67522) `[ROCm] Add AITER Triton W4A16 to MXFP4 MoE fallback` | quant,rocm | ? | - |
| - | [#67523](https://github.com/vllm-project/vllm/pull/67523) `[Test][ROCm] Move Kimi-K3 AMD tests and added parity to nvidia` | infra,nvidia,rocm | ? | - |
| - | [#67525](https://github.com/vllm-project/vllm/pull/67525) `[Compile][Quantization] Add RMSNorm fusion for dynamic per-token INT8` | infra,perf,quant | ? | - |
| - | [#67526](https://github.com/vllm-project/vllm/pull/67526) `[Core] Log the backends each kind of layer selected after model load` | nvidia,quant,rocm | ? | - |
| - | [#67528](https://github.com/vllm-project/vllm/pull/67528) `[Test][Mistral] Give the engine driver request tools after tool_choice normalization` |  | ? | - |
| - | [#67529](https://github.com/vllm-project/vllm/pull/67529) `[Online quantization] Deprecate `VLLM_FP8_MOE_REQUANT`/`VLLM_FP8_MOE_REQUANT_ACT`/`VLLM_ROCM_MUSE_MOE_ONLINE_Q` | infra,quant,rocm | ? | - |
| - | [#67531](https://github.com/vllm-project/vllm/pull/67531) `[Bugfix][LoRA] Clear load_inplace on cached resolver requests` | bug,infra | ? | - |
| - | [#67532](https://github.com/vllm-project/vllm/pull/67532) `[KV Connector][Mooncake] Support KV cache reuse across different PP sizes or layer partitions` | perf | ? | - |
| - | [#67534](https://github.com/vllm-project/vllm/pull/67534) `[CI] Enroll 8 CPU steps in automatic sharding` | infra | ? | - |
| - | [#67535](https://github.com/vllm-project/vllm/pull/67535) `[Perf][KV Offload] Report tiering lookup metrics once per request` | perf | ? | - |
| - | [#67536](https://github.com/vllm-project/vllm/pull/67536) `[Perf][GLM-5.3-Flash] Specialized decode on Hopper (H200 TP4)` | nvidia,perf | ? | - |
| - | [#67537](https://github.com/vllm-project/vllm/pull/67537) `[Benchmark] Keep the client prompt length when usage reports zero prompt tokens` | perf | ? | - |
| - | [#67538](https://github.com/vllm-project/vllm/pull/67538) `[Benchmark] vllm-bench: accept SSE data lines without a space after the colon` | perf | ? | - |
| - | [#67539](https://github.com/vllm-project/vllm/pull/67539) `[Feature][DSv4.1] Engram pool: split Engram tables across engines over NVLink or RDMA` | infra | ? | - |
| - | [#67541](https://github.com/vllm-project/vllm/pull/67541) `[ROCm][RDNA][MLA] Add opt-in AITER Triton MLA decode on gfx1100` | rocm | ? | - |
| - | [#67543](https://github.com/vllm-project/vllm/pull/67543) `[Fix] lora: Support partial 3D MoE adapters` | bug | ? | - |
| - | [#67546](https://github.com/vllm-project/vllm/pull/67546) `[Bugfix][Frontend] Keep reasoning-token logprobs out of non-streaming Responses output_text` | bug | ? | - |
| - | [#67547](https://github.com/vllm-project/vllm/pull/67547) `[Core][Prefix Caching] Support fine-grained prefix-cache hits for sliding-window groups` | perf | ? | - |
| - | [#67548](https://github.com/vllm-project/vllm/pull/67548) `[Core][KV Cache] Let a backend keep a layer's KV cache as named components` | nvidia,perf | ? | - |
| - | [#67550](https://github.com/vllm-project/vllm/pull/67550) `[ROCm][Model][Perf] Fold the k_out dequant and fp8 query quant into the QK-norm+RoPE+KV-cache fusion for ROCM_` | perf,quant,rocm | ? | - |
| - | [#67551](https://github.com/vllm-project/vllm/issues/67551) `[Feature]: Enable libtorch-ABI-stable vLLM ROCm wheels` | rocm | ? | - |
| - | [#67552](https://github.com/vllm-project/vllm/issues/67552) `[Feature]: Carry repetition_detection and extra_args on vllm.Inference GenerateRequest` |  | ? | - |
| - | [#67554](https://github.com/vllm-project/vllm/pull/67554) `[Bugfix][DeepSeek-V3.2] Pass a key to rotary_emb in the fp8-query dense-MHA prefill` | bug,infra,quant | ? | - |
| - | [#67556](https://github.com/vllm-project/vllm/issues/67556) `[Bug]: --api-key does not protect LoRA load/unload through the SageMaker /adapters routes` |  | ? | - |
| - | [#67557](https://github.com/vllm-project/vllm/pull/67557) `[Bugfix][Frontend] Require API key for SageMaker LoRA /adapters routes` | bug | ? | - |
| - | [#67558](https://github.com/vllm-project/vllm/issues/67558) `[Bug]: video/jpeg frame lists share cache entries across different per-request image decode options` | perf | ? | - |
| - | [#67559](https://github.com/vllm-project/vllm/pull/67559) `[KV Connector] Spec-driven TP slicing for NIXL` | nvidia | ? | - |
| - | [#67560](https://github.com/vllm-project/vllm/pull/67560) `[ROCm][DSv4.1] Enable Tensor scale FP8 KV Cache for Sparse MLA of Mono Kernel` | infra,perf,quant,rocm | ? | - |
| - | [#67561](https://github.com/vllm-project/vllm/pull/67561) `[Bugfix][Multimodal] Hash image decode options for video/jpeg frames` | bug | ? | - |
| - | [#67562](https://github.com/vllm-project/vllm/pull/67562) `[Core] Session-based retention and lookup for the prefix cache` | perf | ? | - |
| - | [#67566](https://github.com/vllm-project/vllm/pull/67566) `[Bugfix][Compile] Key the AOT compile cache on loaded general plugins` | bug,perf | ? | - |
| P1 | [#67569](https://github.com/vllm-project/vllm/pull/67569) `[ROCm][Perf][Qwen4Exp] Add --enable-hc-sp-replicated-moe` | infra,perf,rocm | ? | - |
| - | [#67570](https://github.com/vllm-project/vllm/pull/67570) `[ROCm][Perf][Qwen4Exp] Allow replicated MoE with --monokernel` | infra,perf,rocm | ? | - |
| - | [#67572](https://github.com/vllm-project/vllm/pull/67572) `[Doc] Make CUDA 13 the default in the GPU install guide` | nvidia | ? | - |
| - | [#67573](https://github.com/vllm-project/vllm/pull/67573) `[ROCm][Build] Install device code via ROCM_DEVICE_EXTRAS in the ROCm base images` | infra,rocm | ? | - |

### vLLM — Closed unmerged (3 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#65638](https://github.com/vllm-project/vllm/pull/65638) `[ROCm][MiniMax-M3] Mono decode on the NVFP4 KV and index caches` | quant,rocm | main | - |
| P0 | [#65645](https://github.com/vllm-project/vllm/pull/65645) `[ROCm][MiniMax-M3] Default to breakable CUDA graphs tests on ROCM` | nvidia,rocm | main | - |
| P0 | [#66090](https://github.com/vllm-project/vllm/pull/66090) `[Bugfix] Stop advertising fp8_e5m2 where the KV writer stores e4m3` | bug,quant,rocm | main | - |

### sglang — Merged / closed (880 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#22084](https://github.com/sgl-project/sglang/issues/22084) `[Feature] Distributed Weight Data Parallelism (DWDP) for Sparse MoE Models` |  | ? | - |
| - | [#22935](https://github.com/sgl-project/sglang/issues/22935) `[Bug] Mamba radix cache can turn fresh prefill prefix hits into 0-hit after split` | perf | ? | - |
| - | [#25760](https://github.com/sgl-project/sglang/issues/25760) `[Roadmap] SGLang's new lightweight SessionAware Router module for bucket-based PD serving` |  | ? | - |
| - | [#26890](https://github.com/sgl-project/sglang/issues/26890) `[AITER-Upgrade] AITER Scout Status` | rocm | ? | - |
| - | [#27267](https://github.com/sgl-project/sglang/pull/27267) `[Feat] mem_cache: Add hugepage preflight and allocation modes for host pools` | infra,nvidia | ? | - |
| P1 | [#29857](https://github.com/sgl-project/sglang/issues/29857) `[Bug] v0.5.14: With EAGLE/MTP on, KV pool profiler leaves ~50 GB VRAM idle on hybrid GDN model (Qwen3.6-27B NV` | quant | ? | - |
| - | [#29913](https://github.com/sgl-project/sglang/issues/29913) `FP4 KV Roadmap` | quant | ? | - |
| - | [#30122](https://github.com/sgl-project/sglang/issues/30122) `Bug Report: SGLang 0.5.14 Multi-Node GGUF MoE Deployment — 9 Bugs Fixed by a Finance Guy with an AI Agent` | quant | ? | - |
| - | [#30550](https://github.com/sgl-project/sglang/issues/30550) `[Bug] [MLX] SchedulerProfilerManager._start_profile returns success=False under mocked Metal capture` |  | ? | - |
| - | [#30893](https://github.com/sgl-project/sglang/pull/30893) `[Refactor] hisparse: unify device-pool mapping and selection` | infra | ? | - |
| - | [#31206](https://github.com/sgl-project/sglang/issues/31206) `[Bug] sgl-router (PD): open circuit breaker still dispatches to decode, producing a permanent fake-dead prefil` |  | ? | - |
| - | [#31447](https://github.com/sgl-project/sglang/pull/31447) `[Fix] Confidential-Computing: enable Flashinfer all-reduce fusion` | bug,infra,nvidia,perf | ? | - |
| - | [#31504](https://github.com/sgl-project/sglang/issues/31504) `[Proposal] Fuse static FP8 activation quantization into producer kernels (norm / activation / allreduce epilog` | perf,quant | ? | - |
| - | [#32441](https://github.com/sgl-project/sglang/issues/32441) `[Bug] [MLX] test_batched_decode_matches_solo asserts bitwise solo/batched token equality, which no batch-shape` |  | ? | - |
| - | [#33059](https://github.com/sgl-project/sglang/pull/33059) `[Fix] [AMD] dsa: Align Aiter paged rows with DP-attention metadata` | bug,infra,rocm | ? | - |
| - | [#33185](https://github.com/sgl-project/sglang/issues/33185) `[Bug] DeepSeek-V4-Flash-0731: reasoning_effort mapped one level off — `high` is a no-op and vendor `max` is un` |  | ? | - |
| - | [#33226](https://github.com/sgl-project/sglang/pull/33226) `[Feat] cp: Support FlashInfer prefill context parallelism` | nvidia | ? | - |
| - | [#33483](https://github.com/sgl-project/sglang/issues/33483) `[Bug] `max_running_requests` (4096) and `cuda_graph_max_bs` (32) defaults are derived independently; crossing ` |  | ? | - |
| - | [#33549](https://github.com/sgl-project/sglang/issues/33549) `[Bug] DeepSeek-V4 (dsv4 backend + DSPARK) TP=8 on 8×H20: decode forward hangs indefinitely at ~245K context — ` | bug | ? | - |
| P0 | [#34212](https://github.com/sgl-project/sglang/pull/34212) `[Fix] [AMD] DSP: skip unused QuickAllReduce allocation for DCP groups` | bug,infra,rocm | main | - |
| - | [#34572](https://github.com/sgl-project/sglang/issues/34572) `[Bug][PP] PP disaggregated prefill hangs: bootstrap queue history diverges across stages under abort storms (R` | bug | ? | - |
| - | [#34716](https://github.com/sgl-project/sglang/issues/34716) `[Bug] /v1/responses: `created_at` is a float in streaming events but an int in non-streaming responses` |  | ? | - |
| - | [#34772](https://github.com/sgl-project/sglang/issues/34772) `[Bug][Diffusion] Native-fallback component loading drops all CPU-offload decisions (should_offload called with` | perf | ? | - |
| - | [#34815](https://github.com/sgl-project/sglang/issues/34815) `PP8 disaggregated prefill has a load-independent ~30 s TTFT floor on Kimi-K3` |  | ? | - |
| - | [#34857](https://github.com/sgl-project/sglang/issues/34857) `[Bug] [ROCm] Router GEMM output should always be fp32, and the expert correction bias should not be cast to bf` | rocm | ? | - |
| - | [#35223](https://github.com/sgl-project/sglang/issues/35223) `[Tracking] Host allocator: page-aligned allocation with host-side bookkeeping` |  | ? | - |
| - | [#35826](https://github.com/sgl-project/sglang/issues/35826) `[Bug] Grammar token sync initializes a singleton NCCL group under DP attention` | nvidia | ? | - |
| - | [#36224](https://github.com/sgl-project/sglang/issues/36224) `[RFC] First-Class, Versioned KV Hint Envelope for SGLang` |  | ? | - |
| - | [#36678](https://github.com/sgl-project/sglang/issues/36678) `[Feature] Expose opt-in per-request metrics in OpenAI-compatible responses` |  | ? | - |
| - | [#36741](https://github.com/sgl-project/sglang/issues/36741) `[Bug] Anthropic endpoint: output_config.effort forwarded unvalidated -> 500, and xhigh is made unreachable` |  | ? | - |
| P1 | [#36807](https://github.com/sgl-project/sglang/issues/36807) `[Bug] fast_topk_v2 can silently return wrong top-k sets when a radix threshold bucket exceeds its 4096-entry c` | risk | ? | - |
| - | [#36906](https://github.com/sgl-project/sglang/issues/36906) `[Bug] GLM-5.3-Flash crashes at startup under pipeline parallelism — KeyError: 'residual'` | bug | ? | - |
| P1 | [#37326](https://github.com/sgl-project/sglang/issues/37326) `[Bug] NEXTN/MTP draft acceptance decays to ~0 over server uptime on qwen4_exp (Qwen3.8-Flash-Next), fully rest` |  | ? | - |
| - | [#37354](https://github.com/sgl-project/sglang/pull/37354) `[Feat] [Apple] mlx: Add an architecture-independent ATen-to-MLX lowering layer` | infra | ? | - |
| - | [#37430](https://github.com/sgl-project/sglang/issues/37430) `[Bug] Kimi-K3 tool_choice=required requests hang until ReadTimeout in 2P2D TP8/DCP8 deployment` | bug | ? | - |
| - | [#37451](https://github.com/sgl-project/sglang/issues/37451) `[Failure Tracker] PR Test (AMD)` | infra,rocm | ? | - |
| - | [#37472](https://github.com/sgl-project/sglang/pull/37472) `[Fix] dspark: Keep verify bookkeeping in range for rows without candidates` | bug,perf | ? | - |
| P0 | [#37478](https://github.com/sgl-project/sglang/issues/37478) `[ROCm] IndexerKPool calls aiter fp8_mqa_logits unbounded; >2 GiB logits abort every TP rank (#36960 does not c` | rocm | ? | - |
| - | [#37585](https://github.com/sgl-project/sglang/issues/37585) `[Bug] Eager hybrid target verify fails when TP padding breaks fixed-width request groups` | bug | ? | - |
| - | [#37609](https://github.com/sgl-project/sglang/issues/37609) `[Bug] Spark2.5 MLP uses tanh-approximate GELU instead of reference GELU` |  | ? | - |
| - | [#37892](https://github.com/sgl-project/sglang/issues/37892) `[Bug] DeepSeek-V4 long-context prefill: illegal memory access in the DSA indexer top-k kernel (`topk_v1.cuh:34` | bug,perf,risk | ? | - |
| - | [#37983](https://github.com/sgl-project/sglang/issues/37983) `[Bug] VisionTritonAttention drops MiMo-style window attention and sinks` |  | ? | - |
| - | [#38004](https://github.com/sgl-project/sglang/issues/38004) `[RFC] Quantization module layout: Config, Scheme, backend kernels` | perf,quant | ? | - |
| - | [#38009](https://github.com/sgl-project/sglang/issues/38009) `[Bug] [DFlash2] Greedy output diverges from target-only Qwen3.8-27B when thinking is enabled` |  | ? | - |
| P0 | [#38029](https://github.com/sgl-project/sglang/issues/38029) `[Bug] EAGLE DSA draft backend misses KVIndexTranslator in FP8 MHA prefix reads` | quant | ? | - |
| - | [#38031](https://github.com/sgl-project/sglang/issues/38031) `[Bug] GLM-5.3-Flash (DSA): HiCache host-tier load-back corrupts generation even without speculative decoding —` | nvidia,risk | ? | - |
| - | [#38069](https://github.com/sgl-project/sglang/issues/38069) `[Feature] Per-request opt-out from prefix cache insertion (skip_cache_insert)` | perf | ? | - |
| - | [#38104](https://github.com/sgl-project/sglang/issues/38104) `[Bug] `--default-chat-template-kwargs` with `reasoning_effort` silently overrides the per-request `reasoning_e` | risk | ? | - |
| P1 | [#38143](https://github.com/sgl-project/sglang/issues/38143) `[Bug] MiniMax-M3 W4A16 (compressed-tensors) on 2x DGX Spark (sm_121, TP=2): serves but every token is id 0 — a` | quant,rocm | ? | - |
| - | [#38156](https://github.com/sgl-project/sglang/issues/38156) `[Bug] HiCache host-memory sizing guard charges co-located ranks twice and rejects pools that fit (host_memory_` |  | ? | - |
| - | [#38196](https://github.com/sgl-project/sglang/issues/38196) `[Bug] [NPU] ascend attention backend silently corrupts output with page_size 16 (128 OK, 1 rejected per #25169` | risk | ? | - |
| P1 | [#38207](https://github.com/sgl-project/sglang/issues/38207) `[Bug] GLM-5.3 DPC crashes` | bug | ? | - |
| - | [#38236](https://github.com/sgl-project/sglang/issues/38236) `[Bug] DeepseekV4ForCausalLM hook rejects `--speculative-algorithm NEXTN` because the NEXTN->EAGLE alias is res` |  | ? | - |
| - | [#38291](https://github.com/sgl-project/sglang/issues/38291) `[Bug] `fp8e4nv` not supported on A100 (SM80) when serving Qwen3.8-Flash-Next-FP8` | quant | ? | - |
| - | [#38312](https://github.com/sgl-project/sglang/issues/38312) `[Playground] Verified cell: h100 / flash-official / fp4 / high-throughput / single` | nvidia,perf,quant | ? | - |
| - | [#38319](https://github.com/sgl-project/sglang/issues/38319) `[Bug] Chunked Prefill + Radix Insert race corrupts KV pages (QSA, Qwen3.8-Flash-Next)` | bug,risk | ? | - |
| - | [#38341](https://github.com/sgl-project/sglang/issues/38341) `[decode] Spec-decode with large draft-token counts OOMs mid-traffic on the decode instance - no upfront capaci` |  | ? | - |
| - | [#38357](https://github.com/sgl-project/sglang/issues/38357) `[RFC / Feature]: Zero-Copy In-Place KV-Cache Compactor via In-Situ Cycle Permutations (1.65x Speedup, 0 Bytes ` | perf | ? | - |
| - | [#38360](https://github.com/sgl-project/sglang/issues/38360) `[Bug] /v1/score returns validation error for single-label cross-encoder rerankers (e.g. bge-reranker-v2-m3)` |  | ? | - |
| - | [#38424](https://github.com/sgl-project/sglang/issues/38424) `[First-time contributor] Looking for beginner-friendly issues to contribute` |  | ? | - |
| - | [#38428](https://github.com/sgl-project/sglang/issues/38428) `[Bug] HiCache backup thread dies on any storage backend exception; queued backups and their host memory are ne` | infra | ? | - |
| - | [#38448](https://github.com/sgl-project/sglang/issues/38448) `[Bug] HiCache: prefill forward stalls behind the entire host-to-device load burst because round-head H2D copie` |  | ? | - |
| - | [#38450](https://github.com/sgl-project/sglang/issues/38450) `[Bug] DeepSeek-V4-Flash-Vision preview image: multi-turn tool calls come back wrapped in {"arguments": {...}}` |  | ? | - |
| - | [#38470](https://github.com/sgl-project/sglang/issues/38470) `[Feature] HiCache: run the host->device load-back enqueue on a loader thread so it can overlap the forward` | perf | ? | - |
| - | [#38478](https://github.com/sgl-project/sglang/issues/38478) `[Feature] Scheduler: opt-in NO_TOKEN admission lookahead with head-prefix pinning (head-of-line relief for pre` |  | ? | - |
| - | [#38485](https://github.com/sgl-project/sglang/issues/38485) `[Bug] ReplaySSM CPU backup/restore loses pending accepted updates` |  | ? | - |
| - | [#38513](https://github.com/sgl-project/sglang/issues/38513) `supports_fp8() always True; _apply_fallback_scaled_mm still calls torch._scaled_mm (no escape on SM<89)` |  | ? | - |
| - | [#38514](https://github.com/sgl-project/sglang/issues/38514) `Docs: official BFL FLUX.2-klein FP8 is Comfy split-QKV, not a packed SGLang --transformer-weights-path drop-in` | quant | ? | - |
| - | [#38552](https://github.com/sgl-project/sglang/issues/38552) `Error deploy GPT OSS-120B with heterogeneous TP in a P/D` |  | ? | - |
| - | [#38557](https://github.com/sgl-project/sglang/issues/38557) `[Playground] Verified cell: h100 / flash-vision / fp4 / balanced / single` | nvidia,quant | ? | - |
| - | [#38573](https://github.com/sgl-project/sglang/issues/38573) `[Bug] compressed-tensors W4AFP8 MoE: cutlass_w4a8_moe passes a literal chunk_size=128, so a group_size≠128 che` | nvidia,quant,risk | ? | - |
| - | [#38580](https://github.com/sgl-project/sglang/issues/38580) `[Feature] Enforce attention metadata consistency after post-plan padding` |  | ? | - |
| - | [#38589](https://github.com/sgl-project/sglang/issues/38589) `Qwen4Exp (Qwen3.8-Flash-Next) cannot emit DFlash aux hidden states: DFlash/DSpark drafters cannot be served` |  | ? | - |
| - | [#38606](https://github.com/sgl-project/sglang/issues/38606) `HYV4 (Hunyuan-V4) with an all-to-all MoE backend silently computes 1 token in attn_tp_size` | risk | ? | - |
| - | [#38618](https://github.com/sgl-project/sglang/issues/38618) `[Bug] GLM-5.3: checkpoints written by transformers load with MoE/mHC/KDA weights silently dropped` | risk | ? | - |
| - | [#38622](https://github.com/sgl-project/sglang/issues/38622) `[Bug] Triton causal_conv1d_update mishandles oversized and circular conv states` | rocm | ? | - |
| - | [#38627](https://github.com/sgl-project/sglang/issues/38627) `[Bug] Chunked prefill splits the encoder region of encoder-decoder models, corrupting `extend_num_tokens` and ` | bug,risk | ? | - |
| - | [#38651](https://github.com/sgl-project/sglang/issues/38651) `[Feature] Allow caller-provided multimodal cache IDs to avoid repeated hashing and preprocessing` | perf | ? | - |
| - | [#38669](https://github.com/sgl-project/sglang/issues/38669) `[Bug] 主线版本ascend后端对swa模型的注意力计算有bug` |  | ? | - |
| - | [#38676](https://github.com/sgl-project/sglang/issues/38676) `[Feature] Expose multimodal preprocessing latency metrics (media download / load / processor) in Prometheus` | perf | ? | - |
| - | [#38708](https://github.com/sgl-project/sglang/issues/38708) `[Bug][ROCm] --cuda-graph-backend-decode breakable fails at startup on DSA models: 'NoneType' object has no att` | nvidia,rocm | ? | - |
| - | [#38745](https://github.com/sgl-project/sglang/issues/38745) ``DUAL_STREAM_TOKEN_THRESHOLD` makes the DSA indexer's dual-stream gate unsatisfiable on ROCm — the leftover #1` | rocm | ? | - |
| - | [#38749](https://github.com/sgl-project/sglang/pull/38749) `[Feat] kernels: Add out-of-tree dispatch for gated RMSNorm` | infra,perf | ? | - |
| - | [#38768](https://github.com/sgl-project/sglang/issues/38768) `[Bug] Qwen3ForSequenceClassification retains random head bias when loading bias-free checkpoints` |  | ? | - |
| - | [#38769](https://github.com/sgl-project/sglang/issues/38769) `Bump bundled NVSHMEM to 3.7.2: 3.4.5 lacks NVSHMEM_IB_GID_INDEX, which restricted IB fabrics require` | infra | ? | - |
| - | [#38788](https://github.com/sgl-project/sglang/issues/38788) `[Bug] Scripted-runtime rid reuse loses a race with rid_to_state release, surfacing as a 60s recv timeout (3 te` | bug,infra,risk | ? | - |
| - | [#38794](https://github.com/sgl-project/sglang/issues/38794) `[Feature] Korean Localization for SGLang Cookbook` |  | ? | - |
| - | [#38815](https://github.com/sgl-project/sglang/issues/38815) `[Bug] SWA branching attaches a later Mamba checkpoint to an earlier prefix` | bug | ? | - |
| - | [#38817](https://github.com/sgl-project/sglang/issues/38817) `[Bug] RuntimeError: Promotion for Float8 Types is not supported, attempted to promote Float8_e4m3fn and BFloat` | quant | ? | - |
| - | [#38840](https://github.com/sgl-project/sglang/issues/38840) `[Bug] Encoder-decoder KV cache: shared boundary page is double-freed when page_size > 1` | perf | ? | - |
| - | [#38849](https://github.com/sgl-project/sglang/issues/38849) `[Bug] GLM 5.3 segfault on MI300 in SGLang scheduler` | bug,risk,rocm | ? | - |
| - | [#38856](https://github.com/sgl-project/sglang/issues/38856) `[Feature] Batched asynchronous Engram host-row prefetch` |  | ? | - |
| - | [#38863](https://github.com/sgl-project/sglang/issues/38863) `[Perf] xgrammar backend: rollback() does an O(N) list copy -> O(N^2) grammar bitmask cost under speculative de` | perf | ? | - |
| - | [#38866](https://github.com/sgl-project/sglang/issues/38866) `[HiCache] Track HybridLinear/Mamba pipeline-parallel correctness and support` | bug | ? | - |
| - | [#38889](https://github.com/sgl-project/sglang/issues/38889) `[Feature] Move shared cache transfer types out of hicache_storage.py` | perf | ? | - |
| - | [#38899](https://github.com/sgl-project/sglang/issues/38899) `[Bug] DSpark compact SPS profiling ignores forced budgets and fails on ragged mRoPE positions` |  | ? | - |
| - | [#38980](https://github.com/sgl-project/sglang/issues/38980) `[Bug] sgl_kernel flash_attn: is_fa3_supported() accepts sm_89 but no sm_89 cubin ships, and `ver` is ignored` | nvidia | ? | - |
| - | [#38981](https://github.com/sgl-project/sglang/issues/38981) `[Bug] Kimi-K3: aborting a request mid-prefill kills every rank — `free_kv_row_segments` asserts "segment at N ` |  | ? | - |
| - | [#39070](https://github.com/sgl-project/sglang/issues/39070) `[Bug] FLUX.2 rejects --attention-backend sage_attn: model-level whitelist excludes SAGE_ATTN (regression since` | bug | ? | - |
| - | [#39073](https://github.com/sgl-project/sglang/issues/39073) `[Bug] Fatal multimodal processor lookup errors omit processor import failures` |  | ? | - |
| - | [#39087](https://github.com/sgl-project/sglang/issues/39087) `[Bug] Quantized DFlash2 draft silently yields ~0% acceptance — no error, no warning (the quiet counterpart to ` | quant,risk | ? | - |
| - | [#39192](https://github.com/sgl-project/sglang/issues/39192) `[RFC] Contention-aware batching for dynamic EPLB expert migration` |  | ? | - |
| - | [#39193](https://github.com/sgl-project/sglang/issues/39193) `[Bug] DeepSeek-V4.1 fp8 wo_a absorb GEMM is silently ~25% wrong when DEEPGEMM_SCALE_UE8M0 is false (SM121)` | nvidia,quant,risk | ? | - |
| - | [#39226](https://github.com/sgl-project/sglang/issues/39226) `[Bug] --moe-runner-backend deep_gemm accepted for DSV4.1 MXFP4 experts, then fails in CUDA graph capture (layo` | nvidia,quant | ? | - |
| - | [#39235](https://github.com/sgl-project/sglang/issues/39235) `[Bug] DeepSeek-V4 SM120 decode pads q to 64 heads for an SM90 constraint; removing the pad changes greedy outp` | bug,nvidia,perf | ? | - |
| - | [#39260](https://github.com/sgl-project/sglang/issues/39260) `[Bug] Streaming top_logprobs reports the first token's alternatives for every token in a multi-token chunk` |  | ? | - |
| - | [#39274](https://github.com/sgl-project/sglang/issues/39274) `[Bug] DeepSeek-V4.1: user text containing the image placeholder token is rejected with 400 (encoding_dsv41)` |  | ? | - |
| - | [#39279](https://github.com/sgl-project/sglang/issues/39279) `[Feature] Interleaved Prefill Pipeline Parallelism for DeepSeek-V4.1: PP4 x CP2 with Two Virtual Stages per Ra` |  | ? | - |
| - | [#39311](https://github.com/sgl-project/sglang/issues/39311) `[Bug] DeepSeek-V4 checkpoint with fp8 routed experts scores 10pp lower on AIME25 than vLLM (same weights, same` | quant | ? | - |
| - | [#40139](https://github.com/sgl-project/sglang/pull/40139) `[Fix] [Intel] cpu-kernel: Fix rope for VLA model` | bug,infra,perf | ? | - |
| - | [#40141](https://github.com/sgl-project/sglang/pull/40141) `[Feat] [NPU] startup-weight-load: Support overlap mode on NPU` | infra,perf | ? | - |
| - | [#40729](https://github.com/sgl-project/sglang/issues/40729) `[Bug] PD decode scheduler crashes with NotImplementedError when retracting a request under --enable-hisparse` | bug | ? | - |
| - | [#40962](https://github.com/sgl-project/sglang/pull/40962) `[Fix] speculative: build target graphs outside draft contexts` | bug,infra | ? | - |
| P1 | [#41204](https://github.com/sgl-project/sglang/pull/41204) `[Fix] processor: Restore BOS/EOS flags for processor-owned tokenizers` | bug,infra | ? | - |
| - | [#41293](https://github.com/sgl-project/sglang/pull/41293) `[Fix] gemma4: Honor OOT attention defaults` | bug,infra | ? | - |
| P1 | [#41301](https://github.com/sgl-project/sglang/pull/41301) `[Perf] [NVIDIA] quantization: Add tuned W8A8 block-FP8 GEMM configs for H20` | infra,nvidia,perf,quant | ? | - |
| - | [#41372](https://github.com/sgl-project/sglang/issues/41372) `[Bug]: scheduler Req.decoded_text is never written: dead stop-string fallback at schedule_batch.py:1846 and em` |  | ? | - |
| - | [#41495](https://github.com/sgl-project/sglang/pull/41495) `[Feat] [NPU] weight-cache: Add NPU weight cache support` | infra,perf | ? | - |
| - | [#41501](https://github.com/sgl-project/sglang/pull/41501) `[Feat] diffusion/sana-video2: Support breakable CUDA graphs` | infra,nvidia,perf | ? | - |
| P1 | [#41532](https://github.com/sgl-project/sglang/pull/41532) `[Feat] [XPU] quant: Add MXFP8 W8A8 compressed-tensors` | infra,nvidia,quant | ? | - |
| - | [#41635](https://github.com/sgl-project/sglang/pull/41635) `[Feat] gemma4: Add out-of-tree MoE expert executor selection` | infra | ? | - |
| - | [#41794](https://github.com/sgl-project/sglang/pull/41794) `[Perf] [AMD] kimi-k3: Run the fused KDA decode with a BF16 state and Quark weights` | infra,perf,quant,rocm | ? | - |
| - | [#42119](https://github.com/sgl-project/sglang/pull/42119) `[Feat] [AMD] quantization: enable GPTQ and AutoRound INT4 checkpoints` | infra,perf,quant,rocm | ? | - |
| - | [#42566](https://github.com/sgl-project/sglang/pull/42566) `[Fix] quantization: Load block-FP8 MoE TP shards that split checkpoint blocks` | bug,infra,quant | ? | - |
| - | [#42790](https://github.com/sgl-project/sglang/pull/42790) `[Feat] mamba: Allow skipping per-draft intermediate SSM state` |  | ? | - |
| - | [#42855](https://github.com/sgl-project/sglang/pull/42855) `[Perf] [NVIDIA] dspark: Opt-in fused int8 Markov walk kernel for bs <= 64 on Hopper` | infra,nvidia,perf,quant | ? | - |
| - | [#42977](https://github.com/sgl-project/sglang/pull/42977) `[Feat] [NPU] dsa: Shard indexer prefill queries across attention TP (1/2)` | infra | ? | - |
| - | [#43032](https://github.com/sgl-project/sglang/pull/43032) `[Feat] Qwen3.8-Flash-Next: Avoid padded PLE prefill activations` | infra,perf | ? | - |
| - | [#43136](https://github.com/sgl-project/sglang/pull/43136) `[Perf] [AMD] DCP: Slice gathered MHA prefixes with host offsets to drop GPU syncs` | infra,perf,rocm | ? | - |
| - | [#43409](https://github.com/sgl-project/sglang/issues/43409) `[Bug] [diffusion] /v1/images/edits accepts a mask upload but silently ignores it` | perf,risk | ? | - |
| - | [#43517](https://github.com/sgl-project/sglang/pull/43517) `[Feat] [NPU] sampling: Add sampling-mask support for Ascend` | infra | ? | - |
| - | [#43583](https://github.com/sgl-project/sglang/pull/43583) `[Feat] comfyui: Run LTX-2.5 / LTX-2.3 in SGLD integrated mode` | infra,perf,quant | ? | - |
| - | [#43675](https://github.com/sgl-project/sglang/pull/43675) `[Fix] Kimi-K3: Fix derived weight buffers across CUDA graph reloads` | bug,infra,nvidia | ? | - |
| - | [#43703](https://github.com/sgl-project/sglang/pull/43703) `[Perf] [NVIDIA] unquant: Autotune low-M BF16 GEMMs via FlashInfer mm_bf16` | infra,nvidia,perf,quant | ? | - |
| - | [#43739](https://github.com/sgl-project/sglang/pull/43739) `[Feat] [Ascend] quantization: :sparkles: Support online W4A8 MoE` | infra,perf,quant | ? | - |
| P0 | [#43788](https://github.com/sgl-project/sglang/pull/43788) `[Fix] [AMD] deterministic: Bypass AITER GEMM and MoE in deterministic mode on gfx950` | bug,infra,quant,rocm | main | - |
| - | [#43886](https://github.com/sgl-project/sglang/pull/43886) `[Fix] multimodal: Preserve empty media in parallel sampling` | bug,infra | ? | - |
| - | [#44017](https://github.com/sgl-project/sglang/pull/44017) `[Feat] [XPU] GDN: support speculative decoding` | infra,nvidia | ? | - |
| - | [#44047](https://github.com/sgl-project/sglang/pull/44047) `[Fix] openai: Validate sampling bounds and preserve chat output limits` | bug,infra | ? | - |
| - | [#44115](https://github.com/sgl-project/sglang/pull/44115) `[Perf] [NVIDIA] flashinfer: Pass uniform_q_len to the target-verify plan for EAGLE speculative decoding` | infra,nvidia,perf | ? | - |
| - | [#44152](https://github.com/sgl-project/sglang/pull/44152) `[Feat] score/embedding: Add raw embeddings, score rids, encode input_ids, and schedule-decision logging` | infra | ? | - |
| - | [#44176](https://github.com/sgl-project/sglang/pull/44176) `[Fix] dsa: Route mixed-chunk batches to the RAGGED top-k transform for bf16-only sparse prefill` | bug,infra | ? | - |
| - | [#44236](https://github.com/sgl-project/sglang/pull/44236) `[Fix] metrics: Populate pending_prealloc_token_usage` | bug,infra | ? | - |
| P0 | [#44268](https://github.com/sgl-project/sglang/pull/44268) `[Fix] moe: Fix --enable-fused-moe-sum-all-reduce outside CUDA and with LoRA hooks` | bug,infra,nvidia,perf | main | - |
| - | [#44396](https://github.com/sgl-project/sglang/pull/44396) `[Perf] kda-replayssm: Reuse the verify-fused commit step indices` | infra,perf,rocm | ? | - |
| - | [#44399](https://github.com/sgl-project/sglang/pull/44399) `[Feat] gemma4: per-layer attention backend` | infra | ? | - |
| P1 | [#44437](https://github.com/sgl-project/sglang/pull/44437) `[Fix] mem_cache: Move FP4 MLA block scales with their KV in `move_kv_cache`` | bug,infra,quant | ? | - |
| - | [#44458](https://github.com/sgl-project/sglang/pull/44458) `[Perf] [AMD] attention: Use aiter's Triton MLA decode in the aiter backend on gfx1250` | infra,perf,rocm | ? | - |
| - | [#44477](https://github.com/sgl-project/sglang/pull/44477) `[Fix] metrics: Handle process CPU clock resets after restore` | bug,infra,perf | ? | - |
| - | [#44486](https://github.com/sgl-project/sglang/pull/44486) `[Perf] quantization: Add the bias in the cuBLASLt epilogue for per-tensor FP8 linears` | infra,perf,quant | ? | - |
| P0 | [#44489](https://github.com/sgl-project/sglang/pull/44489) `[Perf] [AMD] deterministic: Allow AITER decode attention on gfx950` | infra,perf,rocm | main | - |
| - | [#44566](https://github.com/sgl-project/sglang/pull/44566) `[Perf] [AMD] Qwen3-Next: consume the fused AR+norm+quant output` | infra,perf,quant,rocm | ? | - |
| - | [#44588](https://github.com/sgl-project/sglang/pull/44588) `[Feat] spec: Online acceptance estimator for DSpark confidence-scheduled verification` | infra,nvidia,perf | ? | - |
| - | [#44615](https://github.com/sgl-project/sglang/pull/44615) `[Perf] NIXL: KV packing for TP-heterogeneous transfer (Muse Spark Open)` | infra,perf | ? | - |
| - | [#44753](https://github.com/sgl-project/sglang/pull/44753) `[Refactor] RoPE: Support RotaryEmbedding class usage for DiT models` | infra,perf | ? | - |
| - | [#44810](https://github.com/sgl-project/sglang/issues/44810) `[Bug] DeepSeek-V4 BF16 checkpoint is routed to the MXFP4 expert path and fails in fused MoE` | perf,quant | ? | - |
| - | [#44813](https://github.com/sgl-project/sglang/pull/44813) `[Fix] deepseek_v4: route unquantized BF16/F16/F32 checkpoints off the MXFP4 expert path` | bug,infra,quant | ? | - |
| - | [#44823](https://github.com/sgl-project/sglang/pull/44823) `[Fix] scheduler: Park a chunked prefill continuation when its chunk or KV budget is spent` | bug,infra | ? | - |
| - | [#44955](https://github.com/sgl-project/sglang/pull/44955) `[Feat] diffusion: Support multiple dynamic LoRA adapters` | infra,perf | ? | - |
| - | [#45106](https://github.com/sgl-project/sglang/pull/45106) `[Perf] mooncake: Group and parallelize direct linker layer-wise loads` | infra,perf | ? | - |
| - | [#45149](https://github.com/sgl-project/sglang/pull/45149) `[Feat] [MLU] platform: Add initial support for Cambricon MLUs` | infra,perf | ? | - |
| - | [#45203](https://github.com/sgl-project/sglang/pull/45203) `[Fix] multimodal: Compact CPU tensor views before inline transport` | bug,infra | ? | - |
| - | [#45262](https://github.com/sgl-project/sglang/pull/45262) `[Perf] [NVIDIA] fp8: Use FlashInfer b12x for block-fp8-as-MXFP8 linears on SM12x` | infra,nvidia,perf,quant | ? | - |
| - | [#45263](https://github.com/sgl-project/sglang/pull/45263) `[Perf] [NVIDIA] fp8: Add Triton block-fp8 GEMM configs for RTX PRO 5000` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#45264](https://github.com/sgl-project/sglang/pull/45264) `[Perf] [NVIDIA] mhc: Use BLOCK_K=32 for the hc_mix kernel on SM120` | infra,nvidia,perf | ? | - |
| - | [#45367](https://github.com/sgl-project/sglang/issues/45367) `[Bug] Kimi-K3 DCP a2a produces garbled decode output on 2-node GB300; NCCL_GRAPH_REGISTER=0 restores smoke-tes` | nvidia | ? | - |
| P0 | [#45486](https://github.com/sgl-project/sglang/pull/45486) `[Fix] [AMD] MoE: Preserve CT FP8 Triton layout and reduction dimensions` | bug,infra,perf,quant,rocm | main | - |
| - | [#45497](https://github.com/sgl-project/sglang/pull/45497) `[Perf] attention: avoid concatenating MLA queries for zigzag CP` | infra,perf | ? | - |
| - | [#45534](https://github.com/sgl-project/sglang/pull/45534) `[Fix] [NVIDIA] DeepSeek-v4.1: scatter the replay tail before the prefill CP gather with DSpark` | bug,infra,nvidia | ? | - |
| - | [#45599](https://github.com/sgl-project/sglang/pull/45599) `[Perf] [AMD] batch-invariant: Segmented split-K bf16 matmul for gfx950` | infra,perf,rocm | ? | - |
| - | [#45600](https://github.com/sgl-project/sglang/pull/45600) `[Feat] linker: Add prefetch mode for the Mooncake external linker` | infra,perf | ? | - |
| P0 | [#45601](https://github.com/sgl-project/sglang/pull/45601) `[Perf] [AMD] deterministic: Allow AITER prefill attention on gfx950` | infra,perf,rocm | main | - |
| - | [#45727](https://github.com/sgl-project/sglang/pull/45727) `[Feat] hisparse: Support shared KV sources in HiSparse MLA swap kernels` | infra,perf | ? | - |
| - | [#45730](https://github.com/sgl-project/sglang/pull/45730) `[Fix] diffusion: Keep ComfyUI patches in the plugin and refresh H3 compatibility` | bug,infra,perf | ? | - |
| - | [#45737](https://github.com/sgl-project/sglang/pull/45737) `[Feat] kv-events: Report caller multimodal routing labels as block spans` | infra,perf | ? | - |
| - | [#45770](https://github.com/sgl-project/sglang/issues/45770) `[Bug] EPD encoder allocates unused pinned embedding pools on nonzero TP ranks` | infra | ? | - |
| - | [#45772](https://github.com/sgl-project/sglang/pull/45772) `[Fix] encoder: allocate embedding cache resources only on rank 0` | bug,infra,perf | ? | - |
| - | [#45798](https://github.com/sgl-project/sglang/pull/45798) `[Fix] llava: Load LLaVA-1.5 CLIP tower` | bug,infra | ? | - |
| - | [#45807](https://github.com/sgl-project/sglang/pull/45807) `[Perf] [NVIDIA] deepseek-v4.1: Fuse BF16 prefill indexer score epilogue` | infra,nvidia,perf | ? | - |
| - | [#45835](https://github.com/sgl-project/sglang/issues/45835) `[Failure Tracker] PR Test (AMD)` | infra,rocm | ? | - |
| - | [#45859](https://github.com/sgl-project/sglang/pull/45859) `[Feat] rust/grpc: Report orchestrator launch facts in api.v1 discovery` | infra | ? | - |
| - | [#45886](https://github.com/sgl-project/sglang/pull/45886) `[Fix] InstantTensor: return load-time GPU memory to the KV cache` | bug,infra,perf | ? | - |
| - | [#45891](https://github.com/sgl-project/sglang/pull/45891) `[Perf] dsa: Run the packed prefill top-k on CUDA` | infra,nvidia,perf | ? | - |
| - | [#45905](https://github.com/sgl-project/sglang/pull/45905) `[Refactor] moe: simplify FlashInfer MegaMoE autotune handoff` | infra,nvidia,perf | ? | - |
| - | [#45945](https://github.com/sgl-project/sglang/pull/45945) `[Feat] comm: Gated background transfers` | infra | ? | - |
| - | [#45947](https://github.com/sgl-project/sglang/pull/45947) `[Feat] Comm: Add gated allgather in kv cache sharding` | infra,perf | ? | - |
| - | [#45953](https://github.com/sgl-project/sglang/issues/45953) `[Bug] Glm47MoeDetector.detect_and_parse drops tool calls when the function name is followed by a newline (non-` |  | ? | - |
| - | [#46003](https://github.com/sgl-project/sglang/pull/46003) `[Perf] dsv-v4.1: Score only candidate positions in indexer consumers` | infra,perf | ? | - |
| - | [#46050](https://github.com/sgl-project/sglang/pull/46050) `[Doc] diffusion: Fix documented snippets that cannot load a model` | bug,infra,perf | ? | - |
| - | [#46052](https://github.com/sgl-project/sglang/pull/46052) `[Doc] cookbook: Fix the dead MiniMax-H3 "Learn more" anchors` | bug,infra | ? | - |
| - | [#46053](https://github.com/sgl-project/sglang/pull/46053) `[Fix] function_call: Normalize GLM non-streaming tool names` | bug,infra | ? | - |
| - | [#46062](https://github.com/sgl-project/sglang/pull/46062) `[Perf] [NVIDIA] deepseek-v4.1: Keep one zeroed MegaAttention packed-query buffer instead of zeroing it per lay` | infra,nvidia,perf | ? | - |
| - | [#46132](https://github.com/sgl-project/sglang/pull/46132) `[Perf] cuda-graph: Raise the decode graph ceiling default to 128 for 35 to 60 GiB GPUs` | infra,nvidia,perf | ? | - |
| - | [#46168](https://github.com/sgl-project/sglang/pull/46168) `[Perf] mooncake: Cut the host time of direct linker layer-wise loads` | infra,perf | ? | - |
| - | [#46175](https://github.com/sgl-project/sglang/pull/46175) `[CI] rust: Publish sglang-api-types on crates.io` | infra | ? | - |
| - | [#46185](https://github.com/sgl-project/sglang/pull/46185) `[Feat] gdn: run DFLASH and DSPARK verify on the ReplaySSM spec ring` | infra,perf | ? | - |
| - | [#46186](https://github.com/sgl-project/sglang/pull/46186) `[Perf] spec: radix top-k for speculative verify target probabilities` | infra,perf | ? | - |
| - | [#46200](https://github.com/sgl-project/sglang/pull/46200) `[Fix] swa: Start the SWA KV pool at its first layer under pipeline parallelism` | bug,infra | ? | - |
| - | [#46213](https://github.com/sgl-project/sglang/pull/46213) `[Perf] flashinfer-megamoe: Add an optional decode workspace` | infra,nvidia,perf,quant | ? | - |
| - | [#46214](https://github.com/sgl-project/sglang/pull/46214) `[Fix] flashinfer: Apply the sliding window in ragged prefill for hybrid-SWA models` | bug,infra,nvidia | ? | - |
| P0 | [#46225](https://github.com/sgl-project/sglang/pull/46225) `[Fix] attention: Zero padded KDA/GDN recurrent outputs` | bug,infra,perf | main | - |
| - | [#46291](https://github.com/sgl-project/sglang/pull/46291) `[Feat] rust-server: multimodal (image) preprocessing through sglang-processor` | infra | ? | - |
| - | [#46301](https://github.com/sgl-project/sglang/issues/46301) `[Perf] diffusion quantization layer: fix 6 real perf/overhead bugs` | bug,perf,quant | ? | - |
| P0 | [#46325](https://github.com/sgl-project/sglang/pull/46325) `[Perf] [AMD] deterministic: Use a fixed-order two-stage all-reduce for large inputs` | infra,perf,rocm | main | - |
| - | [#46408](https://github.com/sgl-project/sglang/pull/46408) `[Refactor] multimodal: [MM refactor 2/9] Initialize multimodal processors from a processor config` | infra | ? | - |
| - | [#46425](https://github.com/sgl-project/sglang/pull/46425) `[Refactor] diffusion: Move the Nomas segment KV cache under layers/kvcache` | infra,perf | ? | - |
| - | [#46429](https://github.com/sgl-project/sglang/issues/46429) `[Bug] FLUX.3 Image: TP/SP ranks pick packed or sequential CFG independently and can hang` | bug | ? | - |
| - | [#46430](https://github.com/sgl-project/sglang/pull/46430) `[Fix] diffusion/flux3: Make TP and SP ranks agree on sequential CFG` | bug,infra,perf | ? | - |
| - | [#46483](https://github.com/sgl-project/sglang/pull/46483) `[Perf] [NPU] attention: Avoid CPU sequence length synchronization for Kimi K3` | infra,perf | ? | - |
| - | [#46517](https://github.com/sgl-project/sglang/issues/46517) `[Bug] Disconnected OpenAI chat requests can continue decoding after client disconnect` |  | ? | - |
| - | [#46548](https://github.com/sgl-project/sglang/pull/46548) `[Fix] PD/PP: Fix consensus checker failure while using PP prefill` | bug,infra | ? | - |
| - | [#46552](https://github.com/sgl-project/sglang/pull/46552) `[Perf] multimodal_cache: reuse precomputed combined_hash in MultiModalStaticCache.get` | infra,perf | ? | - |
| - | [#46572](https://github.com/sgl-project/sglang/issues/46572) `[Bug] Inkling: fused attention prologue stores CUDA-graph padding rows into KV slot 0 → NaN logits (`probabili` | bug,nvidia,perf,risk | ? | - |
| - | [#46577](https://github.com/sgl-project/sglang/pull/46577) `[Fix] inkling: Skip KV stores for CUDA-graph padding tokens in the fused attn prologue` | bug,nvidia,perf | ? | - |
| - | [#46586](https://github.com/sgl-project/sglang/pull/46586) `[Fix] srt: Promptly abort running requests on client disconnect (#46517)` | bug,infra | ? | - |
| - | [#46597](https://github.com/sgl-project/sglang/pull/46597) `[Perf] [NVIDIA] minimax-sparse: Run the decode indexer CP on Hopper at TP4 and TP8` | infra,nvidia,perf | ? | - |
| - | [#46610](https://github.com/sgl-project/sglang/pull/46610) `[Feat] [Intel] mem_cache: Enable the HiCache Mamba host pool on XPU` | infra,nvidia | ? | - |
| P1 | [#46662](https://github.com/sgl-project/sglang/pull/46662) `[Doc] [AMD] GLM-5.3: Enable MTP on MI355X and add the agentic recipe with the AMD monokernel` | rocm | ? | - |
| - | [#46663](https://github.com/sgl-project/sglang/pull/46663) `[Fix] gemma4: Fix Bolt E4B and Gemma4 prefill CUDA graphs` | bug,infra,nvidia | ? | - |
| - | [#46693](https://github.com/sgl-project/sglang/pull/46693) `[Feat] [AMD] minimax: Support MiniMax-M3.1-Flash on MI350X / MI355X (gfx950)` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#46694](https://github.com/sgl-project/sglang/pull/46694) `[Perf] [AMD] minimax: decode indexer CP for DSpark verify on the NVFP4 index cache` | infra,nvidia,perf,quant,rocm | ? | - |
| P0 | [#46800](https://github.com/sgl-project/sglang/pull/46800) `[Fix] [AMD] quark: Keep MXFP8 shared experts out of the MXFP4 fused slot on dense-first models` | bug,infra,perf,quant,rocm | main | - |
| - | [#46820](https://github.com/sgl-project/sglang/pull/46820) `[Fix] metrics: Avoid blocking the scheduler on KV metrics backpressure` | bug,infra | ? | - |
| - | [#46830](https://github.com/sgl-project/sglang/pull/46830) `[Fix] dsa: Remove host syncs from rank-divergent eager paths` | bug,infra | ? | - |
| P0 | [#46833](https://github.com/sgl-project/sglang/pull/46833) `[Fix] [AMD] aiter: Use the layer's softmax scale in MHA prefill and decode` | bug,infra,quant,rocm | main | - |
| - | [#46855](https://github.com/sgl-project/sglang/pull/46855) `[Fix] scheduler: Reserve member rows of beam leaders admitted in the same prefill` | bug,infra | ? | - |
| P0 | [#46928](https://github.com/sgl-project/sglang/pull/46928) `[Fix] [AMD] aiter: Fix garbage decode output with unified attention at page size 1 under CUDA graph` | bug,infra,nvidia,risk,rocm | main | - |
| - | [#46929](https://github.com/sgl-project/sglang/pull/46929) `[Fix] mnnvl: Match FlashInfer's arch-specific CuTe DSL AR profiles` | bug,infra,nvidia | ? | - |
| - | [#46934](https://github.com/sgl-project/sglang/pull/46934) `[Fix] hicache: Restore sub-window SWA L3 hits under a mid-tree anchor` | bug,infra,perf | ? | - |
| - | [#46944](https://github.com/sgl-project/sglang/pull/46944) `[CI] [AMD] minimax-m3.1: Add a MI35x MXFP4 + DSpark nightly accuracy gate` | infra,quant,risk,rocm | main | - |
| - | [#46965](https://github.com/sgl-project/sglang/pull/46965) `[Feat] [NVIDIA] flash-attn: FA4 SM90 FP8 e4m3 KV cache for head_dim 256 and 512 (Gemma-4)` | infra,nvidia,perf,quant | ? | - |
| - | [#47025](https://github.com/sgl-project/sglang/pull/47025) `[Feat] disaggregation: Add opt-in Mooncake TENT transfer engine backend for PD` | infra | ? | - |
| P0 | [#47029](https://github.com/sgl-project/sglang/pull/47029) `[Fix] attention: Compute extend attention KV offsets in int64` | bug,infra,perf | main | - |
| P0 | [#47030](https://github.com/sgl-project/sglang/pull/47030) `[Fix] [AMD] aiter: Use the layer's KV scales in the legacy target-verify attention` | bug,infra,quant,rocm | main | - |
| - | [#47090](https://github.com/sgl-project/sglang/pull/47090) `[Perf] qwen-image21: Pack BF16 gate/up projections on SM120` | infra,nvidia,perf | ? | - |
| - | [#47093](https://github.com/sgl-project/sglang/pull/47093) `[Fix] anthropic: Accept thinking enabled without budget_tokens` | bug,infra | ? | - |
| - | [#47096](https://github.com/sgl-project/sglang/pull/47096) `[Fix] responses: Merge replayed tool calls into the preceding commentary message` | bug,infra | ? | - |
| - | [#47129](https://github.com/sgl-project/sglang/pull/47129) `[Perf] [NVIDIA] muse-spark: Bound B200 projection dispatch and allocator compilation` | infra,nvidia,perf | ? | - |
| - | [#47247](https://github.com/sgl-project/sglang/pull/47247) `[Perf] deepseek-v4.1: Use reduce-scatter for CP MoE output` | infra,perf | ? | - |
| - | [#47253](https://github.com/sgl-project/sglang/pull/47253) `[Perf] diffusion: Enable verified eager LN fusion for SANA-Video` | infra,perf | ? | - |
| - | [#47267](https://github.com/sgl-project/sglang/pull/47267) `[Fix] dflash: Gather candidate top-k over the target lm_head's own shard group` | bug,infra | ? | - |
| - | [#47354](https://github.com/sgl-project/sglang/pull/47354) `[Perf] [NVIDIA] glm5: Route small-M BF16 GEMMs to FlashInfer warp split-K with PDL on SM107` | infra,nvidia,perf,quant | ? | - |
| P1 | [#47371](https://github.com/sgl-project/sglang/pull/47371) `[Feat] [AMD] muse-spark: Add the ROCm day0 implementation` | infra,nvidia,perf,quant,rocm | main | - |
| P1 | [#47398](https://github.com/sgl-project/sglang/pull/47398) `[Feat] [AMD] gpt-oss: Mixed W4A8 MoE on gfx1250, Gluon below a token count and FlyDSL above` | infra,rocm | ? | - |
| - | [#47406](https://github.com/sgl-project/sglang/pull/47406) `[Fix] deepseek-v4.1: Fix bounded replay with CP and DSpark` | bug,infra | ? | - |
| - | [#47444](https://github.com/sgl-project/sglang/issues/47444) `[Bug] NemotronHConfig rejects transformers 5 layer types `linear_attention` / `full_attention` in config.json` |  | ? | - |
| P1 | [#47458](https://github.com/sgl-project/sglang/pull/47458) `[Fix] nemotron: Accept transformers 5 layer types in NemotronHConfig` | bug | ? | - |
| - | [#47468](https://github.com/sgl-project/sglang/pull/47468) `[Fix] diffusion: Align Pika H3 Flex inference numerics` | bug,infra,perf | ? | - |
| - | [#47469](https://github.com/sgl-project/sglang/pull/47469) `[Perf] [NVIDIA] attention: Add opt-in LiteTopK prefill indexer top-k for DSA (FP8) and DeepSeek-V4.1 (FP4) on ` | infra,nvidia,perf,quant | ? | - |
| - | [#47490](https://github.com/sgl-project/sglang/issues/47490) `[Bug] EAGLE draft extend crashes with negative dimension under DP attention + FlashInfer A2A + prefill CUDA gr` | bug,nvidia | ? | - |
| P1 | [#47491](https://github.com/sgl-project/sglang/pull/47491) `[Fix] [AMD] scheduler: Keep Muse Spark's scheduler GPU work on the forward stream under monokernel` | bug,infra,rocm | ? | - |
| - | [#47493](https://github.com/sgl-project/sglang/pull/47493) `[Fix] dp-attention: Trim MLP-sync pad rows from extend outputs before the draft extend` | bug,infra | ? | - |
| P1 | [#47513](https://github.com/sgl-project/sglang/pull/47513) `[Perf] attention: Support attention sinks in the split-KV EAGLE verify kernel (gpt-oss)` | infra,perf | ? | - |
| P0 | [#47521](https://github.com/sgl-project/sglang/pull/47521) `[Fix] scheduler: Abort retracted requests whose KV the recompute cannot rebuild` | bug,infra | main | - |
| - | [#47529](https://github.com/sgl-project/sglang/pull/47529) `[Fix] RL: Fix crash when returning routed experts under DCP or KV sharding` | bug,infra | ? | - |
| - | [#47538](https://github.com/sgl-project/sglang/pull/47538) `[Feat] http_server: Dispatch SageMaker /invocations to completions and embeddings by request body` | infra | ? | - |
| - | [#47581](https://github.com/sgl-project/sglang/pull/47581) `[Perf] [NPU] dspark: Integrate argmax and verify scheduler kernels` | infra,perf | ? | - |
| P1 | [#47585](https://github.com/sgl-project/sglang/pull/47585) `[Fix] [AMD] quark: Widen the Quark MXFP4 W4A16 MoE gate to consumer RDNA and fail clearly without aiter` | bug,infra,quant,rocm | ? | - |
| - | [#47617](https://github.com/sgl-project/sglang/pull/47617) `[Fix] hicache: keep the storage ack sequence on backend failures, stop workers in lockstep, fail the rank when` | bug,infra,perf | ? | - |
| - | [#47620](https://github.com/sgl-project/sglang/pull/47620) `[Fix] hicache: vote the prefetch timeout once per tick, not per admission poll` | bug,infra,perf | ? | - |
| - | [#47624](https://github.com/sgl-project/sglang/issues/47624) `[RFC] NPU RL Test Consolidation: File Ownership, Coverage Docstrings, and CI Integration (Ascend)` | infra | ? | - |
| P1 | [#47626](https://github.com/sgl-project/sglang/pull/47626) `[Fix] hicache: settle storage backups at the rank-agreed written prefix` | bug,infra,perf | ? | - |
| - | [#47627](https://github.com/sgl-project/sglang/pull/47627) `[Perf] [NVIDIA] dspark: Stage DSv4.1 long-context target verify metadata beside the draft` | nvidia,perf | ? | - |
| P0 | [#47645](https://github.com/sgl-project/sglang/pull/47645) `[Fix] [AMD] aiter: Plan the DCP asm verify shard with the draft tokens under CUDA graph replay` | bug,infra,nvidia,rocm | main | - |
| - | [#47658](https://github.com/sgl-project/sglang/pull/47658) `[Perf] SM120: honour SGLANG_OPT_DEEPGEMM_HC_PRENORM for the DeepSeek-V4.1 compensated mhc projection` | infra,nvidia,perf | ? | - |
| P0 | [#47670](https://github.com/sgl-project/sglang/pull/47670) `[Fix] mem_cache: Keep K/V in separate allocations under torch.compile` | bug,infra | main | - |
| - | [#47685](https://github.com/sgl-project/sglang/pull/47685) `[Perf] [NVIDIA] dflash: Top up decode KV pages for the whole batch on allocation steps` | nvidia,perf | ? | - |
| P1 | [#47695](https://github.com/sgl-project/sglang/pull/47695) `[Feat] [AMD] quark: Quark int4 W4A16 on ROCm, and gfx1151 kernels for Strix Halo decode and prefill` | infra,perf,quant,rocm | ? | - |
| - | [#47696](https://github.com/sgl-project/sglang/pull/47696) `[Perf] diffusion: Run a single packed FA3 sequence through the batch kernel` | infra,nvidia,perf | ? | - |
| - | [#47724](https://github.com/sgl-project/sglang/pull/47724) `[Perf] diffusion: qknorm_complex_rope keeps two Q/K rows in flight per half-warp` | infra,perf | ? | - |
| - | [#47749](https://github.com/sgl-project/sglang/pull/47749) `[CI] [Intel] ci/xpu: Move remaining XPU CI installs to uv and set SGLANG_IS_IN_CI` | infra,nvidia | ? | - |
| - | [#47750](https://github.com/sgl-project/sglang/pull/47750) `[Fix] score: Validate logical item and MIS hidden-state row counts` | bug,infra | ? | - |
| - | [#47765](https://github.com/sgl-project/sglang/pull/47765) `[Perf] dflash: Fuse the simulated-acceptance overwrite into one kernel` | infra,perf | ? | - |
| P0 | [#47802](https://github.com/sgl-project/sglang/pull/47802) `[Fix] attention: Triton decode reads wrong KV head for GQA groups > 16 not divisible by 16 (GLM-4-32B breaks)` | bug,infra,perf,rocm | main | - |
| - | [#47808](https://github.com/sgl-project/sglang/pull/47808) `cherry-pick #47810 [Feat] deepseek-recipe: [sglang-miles] Expose convert and encode_conversation on DeepSeekRe` |  | ? | - |
| - | [#47827](https://github.com/sgl-project/sglang/issues/47827) `[Bug] Simulator Replay startup eagerly imports optional AIConfigurator dependency` |  | ? | - |
| - | [#47828](https://github.com/sgl-project/sglang/pull/47828) `[Fix] simulator: Lazily import optional AIConfigurator dependency` | bug,infra | ? | - |
| - | [#47842](https://github.com/sgl-project/sglang/pull/47842) `[Fix] diffusion: Enable Cosmos 3 Edge and Nano fused QK-norm/RoPE on SM 121 (GB10)` | bug,infra,perf | ? | - |
| - | [#47857](https://github.com/sgl-project/sglang/pull/47857) `[Feat] [NPU] attention: enable mixed-chunk for pure MLA on the ascend backend` | infra | ? | - |
| P1 | [#47862](https://github.com/sgl-project/sglang/pull/47862) `[Feat] [AMD] aiter: One folder of in-tree aiter tuned rows for every model` | infra,perf,rocm | ? | - |
| P0 | [#47870](https://github.com/sgl-project/sglang/pull/47870) `[Fix] [AMD] ct-fp8-moe: Mark the pre-shuffled CT FP8 MoE weights is_shuffled` | bug,infra,quant,rocm | main | - |
| P0 | [#47892](https://github.com/sgl-project/sglang/pull/47892) `[Fix] quantization: Store --quantization-param-path KV scales the way checkpoint KV scales are stored` | bug,infra,quant | main | - |
| P1 | [#47893](https://github.com/sgl-project/sglang/pull/47893) `[Perf] [NVIDIA] glm5_next: Run the fused KDA decode kernel at 8 and 16 heads per rank` | infra,nvidia,perf | ? | - |
| P1 | [#47896](https://github.com/sgl-project/sglang/issues/47896) `[Bug] Qwen3.5 GatedDeltaNet: finalize_fused_in_proj builds the fused in_proj weight on CPU under --cpu-offload` | perf | ? | - |
| P1 | [#47899](https://github.com/sgl-project/sglang/pull/47899) `[Fix] qwen3.5: Keep CPU-offloaded GDN input projections separate` | bug,infra | ? | - |
| - | [#47903](https://github.com/sgl-project/sglang/pull/47903) `[Feature] multimodal: [sglang-miles] Cache token-space media features per item before loading` | perf | ? | - |
| P1 | [#47908](https://github.com/sgl-project/sglang/pull/47908) `[Fix] [AMD] quark: Match aiter's column-major scale layout in the MXFP4 quant fake` | bug,infra,quant,rocm | ? | - |
| P0 | [#47911](https://github.com/sgl-project/sglang/pull/47911) `[Fix] [AMD] aiter: Skip the unused decode workspace on the vectorized_5d KV layout` | bug,infra,rocm | main | - |
| P1 | [#47916](https://github.com/sgl-project/sglang/issues/47916) `[Bug] [mamba/hybrid] MambaPool.copy_from gathers all source temporal states into one temporary (n x state_size` | nvidia | ? | - |
| - | [#47917](https://github.com/sgl-project/sglang/pull/47917) `[Feat] [NPU] longcat: Support Longcat2.0 for arch22 NPU` | infra | ? | - |
| - | [#47921](https://github.com/sgl-project/sglang/pull/47921) `[Feat] [Apple] mps: Serve Unlimited-OCR v2 BF16 on the Torch MPS runtime` | infra,perf,quant | ? | - |
| P1 | [#47923](https://github.com/sgl-project/sglang/pull/47923) `[Feat] [AMD] tokenizer: Install fastokens in the ROCm image` | infra,rocm | ? | - |
| - | [#47930](https://github.com/sgl-project/sglang/pull/47930) `[Feat] [NVIDIA] megakernel: Support prefill and extend steps` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#47934](https://github.com/sgl-project/sglang/pull/47934) `[Fix] [NPU] dsv4: transfer A3 C4 state using peer-local rows` | bug,infra | ? | - |
| - | [#47943](https://github.com/sgl-project/sglang/pull/47943) `[Fix] ZeroMQ: make blocking send wait for queue space` | bug | ? | - |
| P0 | [#47944](https://github.com/sgl-project/sglang/pull/47944) `[Fix] attention: Migrate FLA Triton kernels off tl.make_block_ptr` | bug,infra,perf,rocm | main | - |
| - | [#47956](https://github.com/sgl-project/sglang/pull/47956) `[Feat] xpu: Consolidate simple XPU enablements` | infra,nvidia,perf,quant | ? | - |
| P0 | [#47960](https://github.com/sgl-project/sglang/pull/47960) `[Perf] [NVIDIA] dsv4/topk_v2: Exactness modes (fast / exact / deterministic) and an exact cluster path` | infra,nvidia,perf | main | - |
| - | [#47963](https://github.com/sgl-project/sglang/pull/47963) `[Fix] rust-server: Park the idle scheduler on its request ring only with --sleep-on-idle` | bug,infra | ? | - |
| P1 | [#47964](https://github.com/sgl-project/sglang/pull/47964) `[Feat] [AMD] custom-all-reduce: Run the JIT custom all-reduce v2 on ROCm` | infra,perf,rocm | ? | - |
| - | [#47968](https://github.com/sgl-project/sglang/pull/47968) `[Refactor] multimodal: Share the CUDA VMM chunk copy and let the transport pick its pool class` | infra,nvidia | ? | - |
| P1 | [#47984](https://github.com/sgl-project/sglang/pull/47984) `[Fix] mem_cache: Chunk MambaPool temporal state copy to avoid OOM spike` | bug,infra | ? | - |
| - | [#47999](https://github.com/sgl-project/sglang/pull/47999) `[CI] [NVIDIA] docker: Publish the CUDA 13.4 nightly image for x86_64 as well as aarch64` | infra,nvidia | ? | - |
| - | [#48006](https://github.com/sgl-project/sglang/pull/48006) `[Refactor] mem_cache: Name each unified window sub-pool by its own window length` | nvidia,perf | ? | - |
| - | [#48007](https://github.com/sgl-project/sglang/pull/48007) `[Refactor] mem_cache: Address prefix-tree window slots, cursors and evictions by sub-pool name` | perf | ? | - |
| - | [#48008](https://github.com/sgl-project/sglang/pull/48008) `[Refactor] mem_cache: Gate unified page reuse and moves on one per-band page ledger` | infra,nvidia,perf | ? | - |
| - | [#48009](https://github.com/sgl-project/sglang/pull/48009) `[Refactor] disaggregation: Track unified PD transfers per row and reuse their pages only once quiescent` | perf | ? | - |
| - | [#48010](https://github.com/sgl-project/sglang/pull/48010) `[Refactor] mem_cache: Give unified request rows one lifecycle state and one reset` | perf | ? | - |
| - | [#48011](https://github.com/sgl-project/sglang/pull/48011) `[Refactor] mem_cache: Add a layout planner and request demand for the unified chain` | perf | ? | - |
| - | [#48012](https://github.com/sgl-project/sglang/pull/48012) `[Refactor] mem_cache: Plan, admit and reclaim unified memory through one layout search` | nvidia,perf | ? | - |
| - | [#48013](https://github.com/sgl-project/sglang/pull/48013) `[Refactor] mem_cache: Give each window sub-pool its own host pool, PD entry and metrics` | perf | ? | - |
| - | [#48014](https://github.com/sgl-project/sglang/pull/48014) `[Feat] attention: Serve several window sub-pools per runner in the Triton backend` | infra,nvidia,perf,rocm | ? | - |
| - | [#48031](https://github.com/sgl-project/sglang/pull/48031) `[Feat] [NPU] hicache: Support AIV transfers for MLA and DeepSeek V4` | infra | ? | - |
| P1 | [#48043](https://github.com/sgl-project/sglang/pull/48043) `[Perf] [AMD] qwen3: Fuse the 1x128 FP8 input quant into RMSNorm and SiLU-and-mul for block-FP8 linears on gfx9` | infra,perf,quant,rocm | ? | - |
| P1 | [#48044](https://github.com/sgl-project/sglang/pull/48044) `[Perf] [AMD] qwen3-next: Fuse the full-attention Q/K GemmaRMSNorm and partial RoPE into one Triton kernel on g` | infra,perf,rocm | ? | - |
| P1 | [#48061](https://github.com/sgl-project/sglang/pull/48061) `[Fix] batch-invariant: restore the dispatcher state when a scope exits` | bug | ? | - |
| - | [#48117](https://github.com/sgl-project/sglang/pull/48117) `[Fix] spec: Prune the draft branch instead of crashing when the grammar rejects a token` | bug,infra | ? | - |
| - | [#48122](https://github.com/sgl-project/sglang/pull/48122) `[Perf] diffusion: Cache MiniMax-H3 reference and keyframe rows per image` | infra,perf | ? | - |
| - | [#48126](https://github.com/sgl-project/sglang/pull/48126) `[Feat] [NPU] attention: Support Modelslim GQA mxfp8 kvcache for 950 NPU` | infra,quant | ? | - |
| - | [#48127](https://github.com/sgl-project/sglang/issues/48127) `[Bug] RadixArk/Muse-Glimmer-NVFP4 fails at load since #45632 (MXFP8 lm_head), and on Hopper also at DeepGEMM w` | nvidia,quant | ? | - |
| - | [#48128](https://github.com/sgl-project/sglang/pull/48128) `[Fix] quantization: Load Muse-Glimmer-NVFP4's MXFP8 lm_head, and run its MXFP8 dense layers as block-FP8 off B` | bug,infra,nvidia,quant | ? | - |
| - | [#48165](https://github.com/sgl-project/sglang/pull/48165) `[Perf] quantization: Speed up Hopper group32 FP8 quantization with FP32 scales` | infra,nvidia,perf,quant | ? | - |
| - | [#48174](https://github.com/sgl-project/sglang/pull/48174) `[Perf] [NVIDIA] moe: Re-land the JIT moe_finalize_fuse_shared with the shared row read after the PDL wait` | infra,nvidia,perf | ? | - |
| - | [#48200](https://github.com/sgl-project/sglang/pull/48200) `[Doc] diffusion: Document IMAGEIO_FFMPEG_EXE for faster MP4 encoding` | infra,perf | ? | - |
| P1 | [#48207](https://github.com/sgl-project/sglang/pull/48207) `[Fix] routed-experts: reset routed_experts_start_len when a request is rejected at intake` | bug,infra | ? | - |
| - | [#48211](https://github.com/sgl-project/sglang/pull/48211) `[Fix] openai: do not render a null tool-level defer_loading` | bug,infra | ? | - |
| - | [#48218](https://github.com/sgl-project/sglang/pull/48218) `[Perf] diffusion: Enable image-prefix sequence parallelism for ERNIE-Image` | infra,perf | ? | - |
| P0 | [#48219](https://github.com/sgl-project/sglang/pull/48219) `[Fix] [AMD] moe: Keep is_shuffled on AITER-shuffled unquantized MoE weights` | bug,quant,rocm | main | - |
| - | [#48228](https://github.com/sgl-project/sglang/pull/48228) `[Fix] scheduler: use OpenAI's context-length wording when a prompt exceeds the KV pool` | bug,infra | ? | - |
| P1 | [#48230](https://github.com/sgl-project/sglang/issues/48230) `[Bug] PD + Mooncake: different DSA backends on prefill and decode silently corrupt the decode KV ("Requested a` | risk | ? | - |
| P1 | [#48231](https://github.com/sgl-project/sglang/pull/48231) `[Fix] disaggregation: Reject a decode peer whose KV page stride differs at Mooncake registration` | bug,infra | ? | - |
| P1 | [#48241](https://github.com/sgl-project/sglang/pull/48241) `[Feat] weight-sync: let one serialized payload serve every TP rank` |  | ? | - |
| - | [#48260](https://github.com/sgl-project/sglang/issues/48260) `[Bug] DSA models crash on first prefill with --cpu-offload-gb: breakable prefill CUDA graph replays the DSA in` | bug,nvidia | ? | - |
| P1 | [#48263](https://github.com/sgl-project/sglang/pull/48263) `[Perf] [NVIDIA] nvfp4: Fuse SiLU-and-mul with the next linear layer's NVFP4 activation quant` | infra,nvidia,perf,quant | ? | - |
| - | [#48264](https://github.com/sgl-project/sglang/pull/48264) `[Feat] beam: support LoRA for BF16 and FP8` | infra,quant | ? | - |
| - | [#48271](https://github.com/sgl-project/sglang/pull/48271) `[Perf] qsa: drop the per-layer RoPE cache length check in the indexer` | infra,perf | ? | - |
| - | [#48272](https://github.com/sgl-project/sglang/pull/48272) `[Fix] mem_cache: report the CUDA error when host registration fails` | bug,infra,nvidia | ? | - |
| - | [#48281](https://github.com/sgl-project/sglang/pull/48281) `[Perf] diffusion/helios: Keep timestep conditioning compact` | infra,perf | ? | - |
| - | [#48285](https://github.com/sgl-project/sglang/pull/48285) `[Feature] multimodal: [sglang-miles] Share the token-space item feature cache on disk` | perf | ? | - |
| - | [#48286](https://github.com/sgl-project/sglang/pull/48286) `[Feature] multimodal: [sglang-miles] Item feature cache key sanity check` | perf | ? | - |
| - | [#48290](https://github.com/sgl-project/sglang/pull/48290) `[Test] [NPU] kimi_k3: run the decode perf case via the aisbench prefix mode` | perf | ? | - |
| - | [#48295](https://github.com/sgl-project/sglang/pull/48295) `[Feat] modelopt: Quantize block-FP8 MTP draft experts to NVFP4 for MIXED_PRECISION checkpoints` | infra,quant | ? | - |
| - | [#48304](https://github.com/sgl-project/sglang/pull/48304) `[Feature] multimodal: [sglang-miles] Write item feature cache entries behind the request` | perf | ? | - |
| - | [#48305](https://github.com/sgl-project/sglang/pull/48305) `[Feature] multimodal: [sglang-miles] Write each item feature cache key once` | perf | ? | - |
| P1 | [#48316](https://github.com/sgl-project/sglang/pull/48316) `[Fix] offload: Keep DSA indexer parameters resident on GPU under CPU offload` | bug,infra | ? | - |
| P0 | [#48328](https://github.com/sgl-project/sglang/pull/48328) `[Fix] mamba: Give a lazy boundary snapshot its own slot instead of overwriting the keep slot` | bug,infra,perf | main | - |
| - | [#48350](https://github.com/sgl-project/sglang/pull/48350) `[Perf] flashinfer_cutedsl: Use swap-AB MoE on Blackwell` | infra,nvidia,perf,quant | ? | - |
| - | [#48364](https://github.com/sgl-project/sglang/pull/48364) `[Feat] [CPU] model: Support Intern-S2-Mobius models on CPU` | infra,perf | ? | - |
| - | [#48366](https://github.com/sgl-project/sglang/pull/48366) `[Refactor] kernels/diffusion/tests: Prune new dead code and make silently skipped tests run` | infra,nvidia,perf,quant,risk,rocm | ? | - |
| - | [#48367](https://github.com/sgl-project/sglang/pull/48367) `[Perf] speculative: Fuse the draft proposal's Gumbel-max sample into one pass` | infra,perf | ? | - |
| P1 | [#48370](https://github.com/sgl-project/sglang/pull/48370) `[Perf] gemma3: Fuse q_norm and k_norm into gemma_rmsnorm for rank above 2` | infra,perf | ? | - |
| - | [#48375](https://github.com/sgl-project/sglang/pull/48375) `[Feat] PD: Publish spec_kv_layout so DSpark/DFlash prefill and decode must match` | infra | ? | - |
| P1 | [#48382](https://github.com/sgl-project/sglang/pull/48382) `[Fix] [AMD] disaggregation: Pair MoRI DSA state across PP prefill stages` | bug,infra,rocm | ? | - |
| - | [#48383](https://github.com/sgl-project/sglang/pull/48383) `[Perf] diffusion: reuse bit-exact RoPE in HiDream-O1-Image` | infra,perf | ? | - |
| P0 | [#48385](https://github.com/sgl-project/sglang/pull/48385) `[Fix] multimodal: keep placeholder token ids at multimodal positions of input_ids` | bug,infra | main | - |
| - | [#48393](https://github.com/sgl-project/sglang/pull/48393) `[Fix] kimi-k3: Cap cached_tokens at prompt_tokens in the Rust processor` | bug,infra | ? | - |
| - | [#48394](https://github.com/sgl-project/sglang/pull/48394) `[Perf] diffusion: Fuse Anima gated residuals during BCG capture` | infra,perf | ? | - |
| P0 | [#48397](https://github.com/sgl-project/sglang/pull/48397) `[Fix] [AMD] moe: Stop dropping FP32 partials in GLM Gluon TP8 32K MoE` | bug,infra,perf,rocm | main | - |
| P1 | [#48399](https://github.com/sgl-project/sglang/pull/48399) `[Refactor] env: Dispatch on the GPU architecture instead of env vars that restate it` | infra,perf,quant,rocm | ? | - |
| - | [#48401](https://github.com/sgl-project/sglang/pull/48401) `[Test] [Intel] jit: Stub tvm_ffi paths in test_jit_cache when tvm_ffi is absent` | infra,nvidia | ? | - |
| - | [#48403](https://github.com/sgl-project/sglang/issues/48403) `[Bug] EPLB crashes with per_pass/per_token recorder modes` | bug | ? | - |
| - | [#48404](https://github.com/sgl-project/sglang/pull/48404) `[Fix] eplb: reject incompatible recorder modes` | bug,infra | ? | - |
| P1 | [#48405](https://github.com/sgl-project/sglang/pull/48405) `[Perf] [AMD] kvcache: Fuse fp8 quantization into the vectorized_5d KV-cache write` | infra,perf,quant,rocm | ? | - |
| P1 | [#48406](https://github.com/sgl-project/sglang/pull/48406) `[Perf] [AMD] qwen3: Let the fused QK-norm + RoPE + KV write serve the vectorized_5d layout` | infra,perf,rocm | ? | - |
| - | [#48410](https://github.com/sgl-project/sglang/pull/48410) `[CI] arm64: Publish Arm CPU Docker images` | infra | ? | - |
| P1 | [#48412](https://github.com/sgl-project/sglang/pull/48412) `[Feat] pp: Relay routed experts through pipeline-parallel stages` | infra | ? | - |
| - | [#48418](https://github.com/sgl-project/sglang/pull/48418) `[Fix] diffusion: Count reclaimable page cache as available inside a cgroup cap` | bug,infra,perf | ? | - |
| - | [#48433](https://github.com/sgl-project/sglang/pull/48433) `[Feat] weight_update: Let platforms serve weight transports through /plugin_weight_update` | infra | ? | - |
| P0 | [#48434](https://github.com/sgl-project/sglang/pull/48434) `[Fix] [AMD] aiter: Quantize q with its own scale in the fp8 prefills over a gathered cache` | bug,infra,perf,quant,rocm | main | - |
| P0 | [#48437](https://github.com/sgl-project/sglang/pull/48437) `[Perf] [AMD] dsa: Split-K HIP sparse MLA for decode/verify` | perf,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48438](https://github.com/sgl-project/sglang/pull/48438) `[Test] [AMD] aiter: Run the HD128 ASM prefill test on gfx950 with a routed pool` | infra,rocm | ? | - |
| - | [#48442](https://github.com/sgl-project/sglang/pull/48442) `[Perf] diffusion: Accelerate exact SANA-Video RoPE on SM103` | infra,nvidia,perf | ? | - |
| - | [#48444](https://github.com/sgl-project/sglang/pull/48444) `[Perf] [NVIDIA] gdn: deferred-fold ReplaySSM target verify on FlashInfer u-cache kernels` | nvidia,perf | ? | - |
| P1 | [#48446](https://github.com/sgl-project/sglang/pull/48446) `[Fix] io_struct: Give each request its own sampling_params dict during normalization` | bug | ? | - |
| - | [#48447](https://github.com/sgl-project/sglang/pull/48447) `[Fix] dp-attention: Carry a rank's ShutdownReq to its DP peers through the MLP-sync gather` | bug | ? | - |
| - | [#48448](https://github.com/sgl-project/sglang/pull/48448) `[CI] server_args: Isolate two tests from process state and host hardware` | infra | ? | - |
| - | [#48449](https://github.com/sgl-project/sglang/pull/48449) `[Refactor] scheduler: Run a prefill batch's KV calls from one overridable _flush_prefill` |  | ? | - |
| P1 | [#48450](https://github.com/sgl-project/sglang/pull/48450) `[Fix] mem_cache: Order lazy unified-pool page reuse after the latest forward` | bug,infra | ? | - |
| - | [#48451](https://github.com/sgl-project/sglang/pull/48451) `[Perf] pd: Poll the prefill result wait per attention-DP shard and pump HiCache storage events in it` | infra,perf | ? | - |
| - | [#48453](https://github.com/sgl-project/sglang/pull/48453) `[Test] load-snapshot: Pin the Python server mode in TestZmqReaderOwner` | infra | ? | - |
| - | [#48455](https://github.com/sgl-project/sglang/pull/48455) `[Feat] rust-server: Log requests like the Python server` |  | ? | - |
| P1 | [#48456](https://github.com/sgl-project/sglang/pull/48456) `[Perf] [NVIDIA] dsv41: Run the side-stream mHC mix in BF16x3 for Blackwell decode batches` | infra,nvidia,perf | ? | - |
| - | [#48457](https://github.com/sgl-project/sglang/pull/48457) `[Feat] rust-server: Write --crash-dump-folder dumps from the Rust frontend` | bug,infra | ? | - |
| P1 | [#48458](https://github.com/sgl-project/sglang/pull/48458) `[Fix] disaggregation: Keep non-final KV sends inside the protected prefix` | bug,infra | ? | - |
| - | [#48468](https://github.com/sgl-project/sglang/pull/48468) `[Chore] [NVIDIA] deps: Bump FlashInfer to 0.7.3 and migrate the NVLink one-sided all-to-all to flashinfer.moe_` | infra,nvidia,perf | ? | - |
| - | [#48470](https://github.com/sgl-project/sglang/pull/48470) `[Perf] diffusion: Tune LingBot MoE TMA for B300 SXM6 AC` | infra,perf | ? | - |
| - | [#48479](https://github.com/sgl-project/sglang/pull/48479) `[CI] [AMD] nightly: Add Kimi-K3.1-Pro nightly test` | infra,rocm | ? | - |
| P0 | [#48485](https://github.com/sgl-project/sglang/pull/48485) `[Fix] [AMD] mooncake: Bump Mooncake to pick up the HIP IPC sub-allocation fix` | bug,infra,rocm | main | - |
| - | [#48487](https://github.com/sgl-project/sglang/pull/48487) `[Fix] sampler: skip the token-id all-reduce when the TP sync group has one rank` | bug,infra | ? | - |
| - | [#48492](https://github.com/sgl-project/sglang/pull/48492) `[Fix] rust-server: Let DP rank 0's drain wait for every attention-DP listener` | bug | ? | - |
| - | [#48496](https://github.com/sgl-project/sglang/pull/48496) `[Perf] mem_cache: Order recycled unified-page writers after the forward instead of the current stream` | infra,perf | ? | - |
| - | [#48506](https://github.com/sgl-project/sglang/issues/48506) `[Bug] [NVIDIA] test/manual/ep/test_flashinfer_dispatcher.py: Every test errors on main, and the test needs a r` | nvidia | ? | - |
| - | [#48507](https://github.com/sgl-project/sglang/pull/48507) `[Fix] multimodal: Cap receive-time CUDA VMM feature copies per GPU and stage the rest in pinned host memory` | bug,infra,nvidia | ? | - |
| - | [#48508](https://github.com/sgl-project/sglang/pull/48508) `[Perf] tokenizer_manager: Keep the crash-dump request history pickled so the cyclic GC never scans it` | bug,infra,perf | ? | - |
| - | [#48511](https://github.com/sgl-project/sglang/pull/48511) `[Test] rust-server: Cover the embedded Rust frontend in a two-node TP engine` | infra | ? | - |
| - | [#48512](https://github.com/sgl-project/sglang/pull/48512) `[Feat] rust-server: Refuse ignored flags, enforce API keys, exit on a failed warmup, declare the SSE charset` | perf | ? | - |
| - | [#48513](https://github.com/sgl-project/sglang/pull/48513) `[Feat] rust-server: Export extension metric families and hand media admission timing to the MM processor` | infra | ? | - |
| - | [#48515](https://github.com/sgl-project/sglang/pull/48515) `[Fix] rust-server: Freeze the scheduler's garbage collector after the startup warmup` | bug,risk | ? | - |
| - | [#48518](https://github.com/sgl-project/sglang/pull/48518) `[Fix] server-args: Redact the access keys from /server_info, logs, launch_command and crash dumps` | bug | ? | - |
| P1 | [#48522](https://github.com/sgl-project/sglang/pull/48522) `[Fix] hicache: Stop L3 prefetch at the match key limit` | bug,infra | ? | - |
| - | [#48523](https://github.com/sgl-project/sglang/pull/48523) `[Feat] rust-server: Decompress x-body-compressed request bodies` | infra | ? | - |
| - | [#48525](https://github.com/sgl-project/sglang/pull/48525) `[Chore] flashmla: bump sgl-flash-mla to 1.0.2` | infra,nvidia | ? | - |
| - | [#48531](https://github.com/sgl-project/sglang/pull/48531) `[Perf] [NVIDIA] fp8: Let the Hopper block GEMV take K=6144 for MiniMax M3.1` | infra,nvidia,perf,quant | ? | - |
| P1 | [#48536](https://github.com/sgl-project/sglang/pull/48536) `[Perf] [AMD] quantization: Fuse SiLU-and-mul with the dynamic per-tensor fp8 quant of dense MLPs on gfx95` | infra,perf,quant,rocm | ? | - |
| - | [#48545](https://github.com/sgl-project/sglang/pull/48545) `[Fix] [CPU] cpu-graph: Preserve return_logprob and request metadata in dynamic prefill` | bug,infra | ? | - |
| - | [#48547](https://github.com/sgl-project/sglang/pull/48547) `[Feat] model: Support ERNIE 5.5 Flash` | infra,perf,quant | main | - |
| - | [#48554](https://github.com/sgl-project/sglang/pull/48554) `[Fix] [NVIDIA] custom-allreduce: Scope a zero NVLink fabric cluster UUID to its own node` | bug,infra,nvidia | ? | - |
| P1 | [#48556](https://github.com/sgl-project/sglang/pull/48556) `[Fix] moe: Fix illegal memory access in the W4A16/W8A16 Triton MoE kernel (unmasked K tail)` | bug,infra,perf,quant,risk,rocm | main | - |
| - | [#48563](https://github.com/sgl-project/sglang/pull/48563) `[Perf] [NVIDIA] gemma4: fuse the TP all-reduce with the layer epilogue and FP8 quant on NVLink multicast` | infra,nvidia,perf,quant | ? | - |
| - | [#48572](https://github.com/sgl-project/sglang/pull/48572) `[Feat] rust-server: Report the serving DP rank in /generate meta_info` |  | ? | - |
| - | [#48583](https://github.com/sgl-project/sglang/pull/48583) `[Feat] [Intel] xpu_kernel: update sglang-kernel-xpu to 0.6.0` | infra,nvidia,perf | ? | - |
| P1 | [#48584](https://github.com/sgl-project/sglang/pull/48584) `[Perf] kimi-k3.1: TP-shard the decode MoE front and latent-up tail` | infra,perf | ? | - |
| P1 | [#48585](https://github.com/sgl-project/sglang/pull/48585) `[Perf] gdn: reduce MIS output and QK preparation overhead` | infra,perf | ? | - |
| P1 | [#48586](https://github.com/sgl-project/sglang/pull/48586) `[Perf] kimi-k3: Fuse the decode MoE routing for 1-256 rows into one kernel` | infra,perf,quant | ? | - |
| - | [#48602](https://github.com/sgl-project/sglang/pull/48602) `[Perf] dsa: Add an opt-in FlashInfer Prims-TS sparse MLA backend` | infra,nvidia,perf | ? | - |
| - | [#48603](https://github.com/sgl-project/sglang/issues/48603) `[Bug] EPLB statistics include empty draft records during speculative decoding` |  | ? | - |
| - | [#48605](https://github.com/sgl-project/sglang/pull/48605) `[Perf] moe/paged-experts: decide block-wide and skip empty page-ins` | infra,perf,quant | ? | - |
| - | [#48613](https://github.com/sgl-project/sglang/pull/48613) `[Perf] kda: Run the fused CuTe DSpARK verify kernel on a BF16 SSM state` | infra,perf | ? | - |
| - | [#48615](https://github.com/sgl-project/sglang/pull/48615) `[Fix] diffusion: Keep explicit cuDNN attention inside LTX breakable CUDA graphs` | bug,infra,nvidia,perf | ? | - |
| - | [#48616](https://github.com/sgl-project/sglang/pull/48616) `[Fix] gemm: Order the CuTe DSL kernels' TMEM release after the epilogue's tcgen05.ld` | bug,infra,perf | ? | - |
| - | [#48619](https://github.com/sgl-project/sglang/pull/48619) `[CI] test: Give TestLlavaServer's llava preprocessing more time` | infra | ? | - |
| - | [#48629](https://github.com/sgl-project/sglang/pull/48629) `[Perf] models: use fused apply_qk_norm in Exaone, HunYuan-V3, AfMoE, and BailingMoE` | infra,perf | ? | - |
| - | [#48638](https://github.com/sgl-project/sglang/pull/48638) `[Perf] [NVIDIA] moe: Add an opt-in persistent MXFP4 decode MoE kernel for Kimi-K3.1` | infra,nvidia,perf,quant | ? | - |
| - | [#48642](https://github.com/sgl-project/sglang/pull/48642) `[Feat] paged-experts: keep experts on disk so later starts skip loading them` | infra | ? | - |
| P1 | [#48654](https://github.com/sgl-project/sglang/pull/48654) `[Fix] scheduler: Match arrival prefixes on every PP stage` | bug,infra | ? | - |
| - | [#48656](https://github.com/sgl-project/sglang/pull/48656) `[Fix] comfyui: Load FastH3, H3 FP8, Qwen-Image 2.1 Turbo and community INT8 single files` | bug,infra,perf,quant | ? | - |
| - | [#48662](https://github.com/sgl-project/sglang/pull/48662) `[Feat] cli: Export Cookbook commands as per-checkpoint JSON files` | infra | ? | - |
| - | [#48666](https://github.com/sgl-project/sglang/pull/48666) `[Fix] tbo: Capture routed experts at each child's parent rows` | bug,infra | ? | - |
| P1 | [#48668](https://github.com/sgl-project/sglang/pull/48668) `[Fix] sgl-router: Keep a worker's cached chain visible when another worker holds its prefix` | bug,infra | ? | - |
| - | [#48677](https://github.com/sgl-project/sglang/issues/48677) `[CI] attention/unittests/mla/test_flashinfer.py fails on main: FlashInfer MLA EAGLE draft CUDA-graph outputs m` | infra,nvidia | ? | - |
| - | [#48688](https://github.com/sgl-project/sglang/pull/48688) `[Perf] longcat-image: Reuse timestep conditioning for serial CFG` | infra,perf | ? | - |
| - | [#48689](https://github.com/sgl-project/sglang/pull/48689) `[Feat] qwen4-exp: accept HMM devices for the file-backed PLE table` | infra | ? | - |
| - | [#48692](https://github.com/sgl-project/sglang/pull/48692) `[CI] [AMD] spur: Take HF_TOKEN from the runner environment` | infra,rocm | ? | - |
| - | [#48693](https://github.com/sgl-project/sglang/pull/48693) `[Fix] hicache: Do not count staged-prefetch deferrals while KV awaits a PD transfer` | bug,infra | ? | - |
| - | [#48699](https://github.com/sgl-project/sglang/pull/48699) `[CI] [AMD] disaggregation: Send aux data over TCP in the PP disaggregation test` | infra,rocm | ? | - |
| P1 | [#48709](https://github.com/sgl-project/sglang/pull/48709) `[Feat] kimi-k3.1: Prefill context parallelism (CP-TP group sharing)` |  | ? | - |
| - | [#48710](https://github.com/sgl-project/sglang/pull/48710) `[Feat] kimi-k3.1: MegaMoE, breakable prefill graphs and DFlash under prefill CP` |  | ? | - |
| - | [#48711](https://github.com/sgl-project/sglang/pull/48711) `[Perf] kimi-k3.1: Fuse MegaMoE padding masks, DSA indexer Q prep and CP row copies` | perf,quant | ? | - |
| - | [#48712](https://github.com/sgl-project/sglang/pull/48712) `[Feat] cuda-graph: Kimi-K3.1 breakable prefill graphs with PP x prefill CP` | infra,nvidia | ? | - |
| - | [#48713](https://github.com/sgl-project/sglang/pull/48713) `[Feat] kimi-k3.1: Let shared-expert TP span interleave prefill CP` |  | ? | - |
| - | [#48714](https://github.com/sgl-project/sglang/pull/48714) `[Feat] kimi-k3.1: Opt-in trtllm DSA backend` |  | ? | - |
| - | [#48719](https://github.com/sgl-project/sglang/pull/48719) `[Fix] docker: update NVIDIA megakernel pin for Qwen3.5 follow-up kernels` | bug,infra,nvidia,perf | ? | - |
| P1 | [#48721](https://github.com/sgl-project/sglang/pull/48721) `[Feat] kimi-k3.1: DSA decode context parallelism runtime` | infra | ? | - |
| - | [#48722](https://github.com/sgl-project/sglang/pull/48722) `[CI] [AMD] nightly-disagg: Install the checkout's runtime deps over the image` | infra,rocm | ? | - |
| - | [#48723](https://github.com/sgl-project/sglang/pull/48723) `[Perf] mega_moe: reserve 18 SMs for MegaMoE in sm107 decode and target-verify` | nvidia,perf | ? | - |
| P1 | [#48726](https://github.com/sgl-project/sglang/pull/48726) `[CI] [AMD] miles: Skip MI30x FP8 and DeepSeek-V4 tests that cannot run on gfx942` | infra,quant,rocm | ? | - |
| - | [#48731](https://github.com/sgl-project/sglang/pull/48731) `[Perf] [NVIDIA] dsv41: Gather 16 local Engram rows per program on SM103 and SM107` | nvidia,perf | ? | - |
| P1 | [#48732](https://github.com/sgl-project/sglang/pull/48732) `[Fix] gemm: Keep Kimi-K3's tiny GEMM shapes on SIMT at every batch size` | bug,perf | ? | - |
| - | [#48733](https://github.com/sgl-project/sglang/pull/48733) `[Perf] [NVIDIA] dsv41: Index-Q RoPE + fp4 pack runs one thread per fp4 block for prefill-sized calls` | nvidia,perf,quant | ? | - |
| P0 | [#48734](https://github.com/sgl-project/sglang/pull/48734) `[Fix] spec: Make per-step draft `out_cache_loc` contiguous for KV writes` | bug,infra | main | - |
| - | [#48739](https://github.com/sgl-project/sglang/pull/48739) `[Feat] kimi-k3.1: DSPARK and DFLASH under decode context parallelism` | infra | ? | - |
| - | [#48740](https://github.com/sgl-project/sglang/pull/48740) `[Perf] kimi-k3.1: Faster DCP decode reduce (push-combine, V pre-projection, direct exchange)` | bug,perf | ? | - |
| - | [#48741](https://github.com/sgl-project/sglang/pull/48741) `[Feat] kimi-k3.1: PD disaggregation under decode context parallelism` | infra | ? | - |
| P1 | [#48751](https://github.com/sgl-project/sglang/pull/48751) `[Fix] eplb: Keep draft forwards out of the target expert window` | bug | ? | - |
| - | [#48752](https://github.com/sgl-project/sglang/pull/48752) `[Fix] rust-server: Publish 127.0.0.1 for an IPv6 loopback SGLANG_HOST_IP on an IPv4 wildcard bind` | bug | ? | - |
| - | [#48753](https://github.com/sgl-project/sglang/pull/48753) `[Feat] rust-server: Refuse more ignored settings, add a launch-time GenerateValidator, and catalogue the Pytho` | perf | ? | - |
| - | [#48755](https://github.com/sgl-project/sglang/pull/48755) `[Chore] utils: Guard `srt.utils` imports and remove dead code` | infra | ? | - |
| - | [#48756](https://github.com/sgl-project/sglang/pull/48756) `[CI] spec: Shrink the radix workload in the EAGLE retract stress tests` | infra | ? | - |
| - | [#48757](https://github.com/sgl-project/sglang/pull/48757) `[Fix] scheduler: Abort beam groups on a retract pause and close three request-drop gaps` | bug,infra | ? | - |
| - | [#48758](https://github.com/sgl-project/sglang/pull/48758) `[Refactor] utils: Move domain-dependent modules out of `srt.utils`` | infra,perf | ? | - |
| - | [#48761](https://github.com/sgl-project/sglang/pull/48761) `[Perf] mhc: halve the DeepGEMM prenorm slices when the grid overflows one wave` | perf,risk | ? | - |
| - | [#48762](https://github.com/sgl-project/sglang/pull/48762) `[Refactor] scheduler: Run every state check through SchedulerInvariantChecker.run` | infra | ? | - |
| P0 | [#48773](https://github.com/sgl-project/sglang/pull/48773) `[Fix] [AMD] topk-v2: Fix wrong picks on split-launch short rows` | bug,infra,perf,rocm | main | - |
| - | [#48775](https://github.com/sgl-project/sglang/pull/48775) `[Feat] kimi-k3: Stream tool-call arguments incrementally` | infra | ? | - |
| - | [#48776](https://github.com/sgl-project/sglang/pull/48776) `[Feat] kimi-k3: Read the `thinking` object and map reasoning effort onto K3 tiers` | infra | ? | - |
| - | [#48777](https://github.com/sgl-project/sglang/pull/48777) `[Feat] kimi-k3: Shape chat responses to the K3 wire format` | infra | ? | - |
| - | [#48778](https://github.com/sgl-project/sglang/pull/48778) `[Fix] multimodal: Fail bad client media with a client error` | bug,infra | ? | - |
| - | [#48781](https://github.com/sgl-project/sglang/pull/48781) `[Refactor] utils: Split `common.py` into topic modules and owner packages` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#48784](https://github.com/sgl-project/sglang/pull/48784) `[Perf] eplb: Vectorize the static per-rank dispatch map` | perf | ? | - |
| - | [#48786](https://github.com/sgl-project/sglang/pull/48786) `[Feat] HiCache: add tma copy kernel for unified layout` | infra,perf | ? | - |
| - | [#48789](https://github.com/sgl-project/sglang/pull/48789) `[Chore] sgl-kernel: Remove the vendored FlashMLA build and wrappers` | infra,nvidia,perf | ? | - |
| - | [#48790](https://github.com/sgl-project/sglang/pull/48790) `[Fix] [Intel] ci/xeon: Build image from the checked-out revision` | bug,infra | ? | - |
| - | [#48797](https://github.com/sgl-project/sglang/pull/48797) `[Test] server-info: Pin the Python frontend in two /server_info unit tests` | infra | ? | - |
| - | [#48798](https://github.com/sgl-project/sglang/pull/48798) `[Feat] rust-server: Let the launching process list the ports its node's Rust listeners bind` |  | ? | - |
| - | [#48799](https://github.com/sgl-project/sglang/pull/48799) `[CI] [NPU] coverage: publish baseline to OBS only and fail loud on missing data` | infra | ? | - |
| - | [#48800](https://github.com/sgl-project/sglang/pull/48800) `[Feat] request_logger: Summarize media inputs per modality in request logs` | infra | ? | - |
| - | [#48801](https://github.com/sgl-project/sglang/pull/48801) `[Feat] sgl-router: Log per-request image, video and audio counts in the access log` | infra | ? | - |
| - | [#48807](https://github.com/sgl-project/sglang/pull/48807) `[Test] [Ascend] npu: GLM-5.3 1P1D accuracy cases + weekday gsm8k` | infra,risk | ? | - |
| - | [#48808](https://github.com/sgl-project/sglang/issues/48808) `[CI] multimodal-gen-test-1-gpu (llada_image) fails on main: 'NoneType' object has no attribute 'takes_deferred` | infra | ? | - |
| - | [#48809](https://github.com/sgl-project/sglang/pull/48809) `[Fix] overlap: Skip deferred-relay flush when future_map is None` | bug,perf | ? | - |
| P1 | [#48810](https://github.com/sgl-project/sglang/pull/48810) `[Fix] [AMD] mxfp4: Keep MoE weight layout and dispatch consistent with the selected runner` | bug,infra,quant,rocm | ? | - |
| - | [#48812](https://github.com/sgl-project/sglang/pull/48812) `[Fix] weight_checker: Compare weights on the live weight's device` | bug,infra | ? | - |
| - | [#48815](https://github.com/sgl-project/sglang/pull/48815) `[Fix] rust-server: Keep the DP control fan-out off an inherited HTTP proxy` | bug,infra | ? | - |
| - | [#48816](https://github.com/sgl-project/sglang/pull/48816) `[CI] sgl-router: Stop label events from cancelling and restarting the router tiers` | infra | ? | - |
| - | [#48818](https://github.com/sgl-project/sglang/pull/48818) `[Feat] rust-server: Let an embedding package register scheduler state fields for /server_info` |  | ? | - |
| - | [#48827](https://github.com/sgl-project/sglang/pull/48827) `[Refactor] utils: Keep sglang.srt and sglang.kernels off sglang.utils` | infra,perf,quant | ? | - |
| - | [#48828](https://github.com/sgl-project/sglang/pull/48828) `[Refactor] radix-cache: Keep only the read pool names in the Rust `PoolName`` | infra,perf | ? | - |
| - | [#48829](https://github.com/sgl-project/sglang/pull/48829) `[Chore] deps: Drop flash-attn-4 from default dependencies` | infra,nvidia,perf,rocm | ? | - |
| - | [#48830](https://github.com/sgl-project/sglang/pull/48830) `[CI] [AMD] spur: Run 1-, 2- and 4-GPU suites on part of a node` | infra,rocm | ? | - |
| - | [#48831](https://github.com/sgl-project/sglang/pull/48831) `[Perf] dspark: Prepare the DSpark draft attention metadata through the glue graph under every verify mode` | perf | ? | - |
| - | [#48832](https://github.com/sgl-project/sglang/pull/48832) `[Perf] dsv4: Run compact target verify's ratio 1 and 2 compressors through the fused kernels` | perf | ? | - |
| - | [#48833](https://github.com/sgl-project/sglang/pull/48833) `[Perf] dspark: Build the compact verify window and stage its padded layout in one launch each` | infra,perf | ? | - |
| P0 | [#48840](https://github.com/sgl-project/sglang/pull/48840) `[Fix] hisparse: disambiguate __ffsll for HIP's dual overloads` | bug,infra,perf,rocm | main | - |
| P1 | [#48846](https://github.com/sgl-project/sglang/pull/48846) `[Feat] hisparse: reject unvalidated speculative algorithms by name` | infra | ? | - |
| P1 | [#48852](https://github.com/sgl-project/sglang/pull/48852) `[Perf] mem_cache: Defer reuse of freed unified pages instead of waiting on every free` | perf | ? | - |
| - | [#48853](https://github.com/sgl-project/sglang/pull/48853) `[Chore] flash-attn: Remove the kernels-hub FA3 loader and the kernels dependency` | infra,nvidia,perf | ? | - |
| - | [#48856](https://github.com/sgl-project/sglang/pull/48856) `[HiCache] Linker: Drop the shared PCP namespace from the Mooncake direct linker` |  | ? | - |
| - | [#48857](https://github.com/sgl-project/sglang/pull/48857) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main ce35bc93` |  | ? | - |
| P1 | [#48860](https://github.com/sgl-project/sglang/pull/48860) `[Fix] cuda_graph: Retain capture inputs for full graph replay` | bug,infra | ? | - |
| - | [#48868](https://github.com/sgl-project/sglang/pull/48868) `[Feat] kimi-k3.1: Sync the prefill-CP review fixes from the port PRs` | perf | ? | - |
| - | [#48871](https://github.com/sgl-project/sglang/pull/48871) `[Fix] modelopt_fp4: Skip swizzled NVFP4 MoE blockscales on Marlin paths` | bug,infra,nvidia,quant | ? | - |
| - | [#48877](https://github.com/sgl-project/sglang/pull/48877) `[Feat] kimi-k3.1: HiCache under decode context parallelism` |  | ? | - |
| - | [#48879](https://github.com/sgl-project/sglang/pull/48879) `[Doc] cookbook: Fix Qwen3.8-Flash-Next thinking-mode description` | bug | ? | - |
| - | [#48882](https://github.com/sgl-project/sglang/pull/48882) `[Fix] [NPU] dsa: Allow DSA DCP with PD disaggregation` | bug,infra | ? | - |
| - | [#48891](https://github.com/sgl-project/sglang/pull/48891) `[Perf] [SM100] attention: optimize sparse MLA prefill for small heads` | infra,nvidia,perf | ? | - |
| - | [#48892](https://github.com/sgl-project/sglang/issues/48892) `[CI] multimodal-gen-test-2-gpu (test_kandinsky6_sr_decode_parallel spatial-2) fails on main: Tensor-likes are ` | infra | ? | - |
| - | [#48895](https://github.com/sgl-project/sglang/pull/48895) `[Perf] [NVIDIA] dsa/dcp: Fused DCP8 indexer top-k for decode` | infra,nvidia,perf | ? | - |
| - | [#48896](https://github.com/sgl-project/sglang/pull/48896) `[Doc] blogs: Sync LMSYS SGLang blog cards` |  | ? | - |
| - | [#48903](https://github.com/sgl-project/sglang/pull/48903) `[Test] kandinsky6-sr: Check spatial-shard decode exactly in fp32 and with a calibrated bf16 outlier budget` | infra,perf | ? | - |
| - | [#48928](https://github.com/sgl-project/sglang/pull/48928) `[Perf] DeepSeek-V4.1-Flash: Use segmented fastokens for prompt encoding` | infra,perf | ? | - |
| - | [#48936](https://github.com/sgl-project/sglang/pull/48936) `[CI] ep: Log Mooncake EP JIT events in test_mooncake_ep_small` | infra | ? | - |
| - | [#48938](https://github.com/sgl-project/sglang/pull/48938) `[Fix] watchdog: Let py-spy attach to watched processes in CI` | bug,infra | ? | - |
| - | [#48941](https://github.com/sgl-project/sglang/pull/48941) `[Perf] layernorm: rmsnorm_mxfp8 on 2 warps for 1280-wide rows; hc_combine_norm loads its weight before the red` | perf,quant | ? | - |
| - | [#48942](https://github.com/sgl-project/sglang/pull/48942) `[Refactor] jit: Unify FP32 activation functions in sgl_kernel/activation.cuh` | infra,perf,quant | ? | - |
| - | [#48946](https://github.com/sgl-project/sglang/pull/48946) `[Refactor] moe: Remove the bailing_moe_topk and JIT moe_topk_sigmoid routers` | infra,perf | ? | - |
| - | [#48947](https://github.com/sgl-project/sglang/pull/48947) `[Perf] layernorm_sp: Add --layernorm-sp-min-tokens to run small extend passes replicated` | infra,perf | ? | - |
| - | [#48949](https://github.com/sgl-project/sglang/pull/48949) `[Perf] reject_sampling: Vocabulary-tiled final-token pass at small batch` | infra,perf | ? | - |
| - | [#48952](https://github.com/sgl-project/sglang/pull/48952) `[CI] ep: Port the FlashInfer dispatcher test to flashinfer.moe_ep and run it in CI` | infra,nvidia,perf | ? | - |
| - | [#48953](https://github.com/sgl-project/sglang/pull/48953) `[Feat] multimodal: [sglang-miles] Let a token-space strategy load its own media and choose its image decoder a` | infra | ? | - |
| - | [#48955](https://github.com/sgl-project/sglang/pull/48955) `[Fix] [AMD] imports: [sglang-miles] Skip import-time device probes when no GPU is visible` | bug,perf,rocm | ? | - |
| - | [#48956](https://github.com/sgl-project/sglang/pull/48956) `[Chore] CODEOWNERS: Update score, decisions, and embeddings API owners` |  | ? | - |
| - | [#48959](https://github.com/sgl-project/sglang/pull/48959) `[Feature] diffusion RL: a TensorStash in radix_transfer_plugins and a rollout request that puts its tensors in` | perf | ? | - |
| - | [#48966](https://github.com/sgl-project/sglang/pull/48966) `[CI] [AMD] hc_mix: Skip the FlyDSL hc_mix dispatch tests when AITER lacks the kernel` | infra,perf,rocm | ? | - |
| - | [#48971](https://github.com/sgl-project/sglang/pull/48971) `[Perf] dsv4: route wo_b and Engram KV MXFP8 GEMMs to cuDNN on CC 10.7 above 8K rows` | perf,quant | ? | - |
| - | [#48974](https://github.com/sgl-project/sglang/pull/48974) `[Fix] dspark: [sglang-miles] Target verify passes the forward's routed-experts, indexer top-k and KV-version c` | bug | ? | - |
| - | [#48977](https://github.com/sgl-project/sglang/pull/48977) `[Fix] kimi-k3.1: Sync the PCP stack's CI fixes (DSA trtllm row plan, MegaMoE pre-allocation, DCP fixture)` | bug,infra | ? | - |
| - | [#48978](https://github.com/sgl-project/sglang/pull/48978) `[CI] [AMD] jit: Use the platform full warp mask in the DSA indexer RoPE helpers` | infra,perf,rocm | ? | - |
| - | [#48980](https://github.com/sgl-project/sglang/pull/48980) `[Fix] deepseek-v4.1: Run attention on the real rows of an MLP-sync-padded extend` | bug,infra | ? | - |
| - | [#48983](https://github.com/sgl-project/sglang/pull/48983) `[Chore] ci: Remove the runtime Docker image release workflow` | infra | ? | - |
| - | [#48984](https://github.com/sgl-project/sglang/pull/48984) `[Perf] mhc: one-pass DeepGEMM prenorm GEMM; revert the sm107 decode MegaMoE SM reserve` | infra,nvidia,perf | ? | - |
| - | [#48986](https://github.com/sgl-project/sglang/pull/48986) `[Fix] dsa: Accept metadata padding past q inside a breakable prefill graph` | bug | ? | - |
| - | [#48988](https://github.com/sgl-project/sglang/pull/48988) `[Fix] radix-cache: Use Rust TreeCore with PyTorch 2.15 in the cu134 image instead of slow python backend` | bug,perf | ? | - |
| - | [#48990](https://github.com/sgl-project/sglang/pull/48990) `[CI] ci: Remove 13 nightly CUDA tests` | infra,nvidia | ? | - |
| - | [#48992](https://github.com/sgl-project/sglang/pull/48992) `[Fix] scheduler: Honor pause_generation under PP and release aborted PD rooms and rejected sessions` | bug,infra | ? | - |
| - | [#48993](https://github.com/sgl-project/sglang/pull/48993) `[Refactor] attention: Let the DSV4 backend count the query rows of its prefill shared-read snapshot` | infra | ? | - |
| - | [#48994](https://github.com/sgl-project/sglang/pull/48994) `[Refactor] moe: Rename --moe-a2a-backend flashinfer to flashinfer_nvlink_one_sided` | infra,nvidia | ? | - |
| - | [#48995](https://github.com/sgl-project/sglang/pull/48995) `[CI] labeler: Label Reflection Beam PRs and issues` | infra | ? | - |
| - | [#48996](https://github.com/sgl-project/sglang/pull/48996) `[Perf] [AMD] dsa: Default the DSA KV cache to fp8_e4m3 on gfx950` | infra,perf,quant,rocm | ? | - |
| - | [#48997](https://github.com/sgl-project/sglang/pull/48997) `[Feat] scheduler: Run the state checks in the PD and PP loops and after a flush` | infra | ? | - |
| - | [#48998](https://github.com/sgl-project/sglang/pull/48998) `[Feat] comfyui: Add an offline workflow converter and reject weight patches on SGLD models` | infra,perf | ? | - |
| - | [#48999](https://github.com/sgl-project/sglang/pull/48999) `[Chore] docker: Remove muse_spark folder` | infra | ? | - |
| - | [#49000](https://github.com/sgl-project/sglang/pull/49000) `[Fix] [NPU] dsv4: Use explicit compressor state on Ascend 950` | bug,infra | ? | - |
| - | [#49001](https://github.com/sgl-project/sglang/pull/49001) `[Feat] [AMD] custom-all-reduce: Run carv2 on MI450 with FABRIC handles and a gfx1250 table` | infra,perf,rocm | ? | - |
| - | [#49003](https://github.com/sgl-project/sglang/pull/49003) `[Feat] [AMD] custom-all-reduce: Run carv2 across gfx1250 UALink nodes` | infra,perf,rocm | ? | - |
| - | [#49004](https://github.com/sgl-project/sglang/pull/49004) `[Fix] [AMD] rocprofiler-sdk: fix torch.profiler hang on TP for gfx1250-rocm1010` | bug,rocm | ? | - |
| - | [#49006](https://github.com/sgl-project/sglang/pull/49006) `[Feat] rust-server: Pass the image item detail hint to multimodal processors` |  | ? | - |
| - | [#49008](https://github.com/sgl-project/sglang/pull/49008) `[Feat] rust-server: Serve a generation on the DP rank its routed_dp_rank names` |  | ? | - |
| - | [#49016](https://github.com/sgl-project/sglang/pull/49016) `[Test] unit: Pin the Python frontend in tests of Python-frontend-only behaviour` | infra | ? | - |
| - | [#49017](https://github.com/sgl-project/sglang/pull/49017) `[Fix] moe: Match the Triton renormalize sum order in the warp MoE router` | bug,perf,rocm | ? | - |
| - | [#49018](https://github.com/sgl-project/sglang/pull/49018) `[Test] scheduler: Check that a request exits and sends its final output at most once` | infra | ? | - |
| - | [#49019](https://github.com/sgl-project/sglang/pull/49019) `[Refactor] scheduler: Commit a step's result only on the rows of requests still in the batch` | infra | ? | - |
| - | [#49020](https://github.com/sgl-project/sglang/pull/49020) `[CI] diffusion: Add H100 computable runner baselines for loading and E2E` | infra,nvidia,perf | ? | - |
| - | [#49022](https://github.com/sgl-project/sglang/pull/49022) `[Doc] [AMD] cookbook: Match the Kimi-K3.1-Pro MI35x single-node cells to the current recipe` | rocm | ? | - |
| - | [#49023](https://github.com/sgl-project/sglang/pull/49023) `[Feat] rust-server: Log requests as JSON lines and to log directories, and log OpenAI requests as received` | infra | ? | - |
| - | [#49024](https://github.com/sgl-project/sglang/pull/49024) `[Perf] [AMD] wan2.2: Gate FlyDSL norm and scale-shift fusion on high quality` | infra,perf,quant,rocm | ? | - |
| - | [#49028](https://github.com/sgl-project/sglang/pull/49028) `[Test] kv_canary: Ignore EOS in the PD fixture for the SWA model` | infra | ? | - |
| - | [#49030](https://github.com/sgl-project/sglang/pull/49030) `[Feat] rust-server: Report cached prompt tokens under --enable-cache-report on the OpenAI routes` | infra,perf | ? | - |
| - | [#49032](https://github.com/sgl-project/sglang/pull/49032) `[Fix] scheduler: Relay multimodal requests to later PP stages without raw features` | bug,infra | ? | - |
| - | [#49034](https://github.com/sgl-project/sglang/pull/49034) `[Fix] hicache: Return int page slots from `_storage_page_index` without DCP` | bug | ? | - |
| - | [#49037](https://github.com/sgl-project/sglang/pull/49037) `[Test] [NVIDIA] megakernel: Stub the DCP push-combine warmup hook in the runtime test` | infra,nvidia | ? | - |
| - | [#49043](https://github.com/sgl-project/sglang/pull/49043) `[Fix] linker: Renew Mooncake read leases that lapse during a load` | bug,infra | ? | - |
| - | [#49053](https://github.com/sgl-project/sglang/pull/49053) `[CI] [AMD] spur: Schedule stage-b-test-1-gpu-small-amd-mi35x on the Spur runners` | infra,rocm | ? | - |
| - | [#49054](https://github.com/sgl-project/sglang/pull/49054) `[Feat] [NPU] HiCache: Support Mooncake L3 for DeepSeek-V4 and GLM-5.2` | infra | ? | - |
| - | [#49071](https://github.com/sgl-project/sglang/pull/49071) `[Doc] GLM-5.3-Flash: Add B300 TP4 AgentX tuning results` | infra,perf | ? | - |
| - | [#49078](https://github.com/sgl-project/sglang/pull/49078) `[Perf] [ROCM] diffusion: Ring attention on aiter, and reuse the ring's K/V buffers` | infra,perf,rocm | ? | - |
| - | [#49081](https://github.com/sgl-project/sglang/pull/49081) `[Feat] cli: Add the CLI Guide` | infra | ? | - |
| - | [#49087](https://github.com/sgl-project/sglang/pull/49087) `[Doc] [AMD] cookbook: Update Muse Spark Open MI355X AgentX recipe to the 1106 image` | rocm | ? | - |
| - | [#49088](https://github.com/sgl-project/sglang/pull/49088) `[Perf] [NVIDIA] minimax-sparse: Run the decode indexer CP on Hopper at TP8 with attention DP2` | infra,nvidia,perf | ? | - |
| - | [#49091](https://github.com/sgl-project/sglang/pull/49091) `[Perf] [NVIDIA] moe: Generalize the MXFP4 decode MoE kernel to covered shapes and DeepSeek-V4` | infra,nvidia,perf,quant | ? | - |
| - | [#49092](https://github.com/sgl-project/sglang/pull/49092) `[Fix] kv-canary: Pass token-oracle request ids into the warmup dummy forward` | bug | ? | - |
| - | [#49093](https://github.com/sgl-project/sglang/pull/49093) `[Fix] ernie55: Import layer helpers from their current modules` | bug,infra | ? | - |
| - | [#49096](https://github.com/sgl-project/sglang/pull/49096) `[Fix] megamoe: Accept FlashInfer 0.7.3 knob cache and enum config fields in startup autotune` | bug,nvidia,perf | ? | - |
| - | [#49097](https://github.com/sgl-project/sglang/pull/49097) `[Test] kv-canary: Serve the EAGLE canary fixture in bf16 to avoid an fp16 overflow` | risk | ? | - |
| - | [#49102](https://github.com/sgl-project/sglang/pull/49102) `[Perf] dsa: bf16 MQA logits for the prefill indexer` | perf | ? | - |
| - | [#49105](https://github.com/sgl-project/sglang/pull/49105) `[Feat] kimi-k3.1: HiCache with DFLASH under decode context parallelism` |  | ? | - |
| - | [#49106](https://github.com/sgl-project/sglang/pull/49106) `[Feat] kimi-k3.1: trtllm DSA backend under decode context parallelism` |  | ? | - |
| - | [#49118](https://github.com/sgl-project/sglang/pull/49118) `Revert "[Perf] [NVIDIA] unquant: Autotune low-M BF16 GEMMs via FlashInfer mm_bf16 (#43703)"` | nvidia,perf,quant | ? | - |
| - | [#49126](https://github.com/sgl-project/sglang/pull/49126) `[Feat] multimodal: [sglang-miles] Inkling token-space strategy and serving spec` |  | ? | - |
| - | [#49128](https://github.com/sgl-project/sglang/pull/49128) `[Fix] test: Keep a passed precision baseline row pointing at its own tensors` | bug | ? | - |
| - | [#49135](https://github.com/sgl-project/sglang/pull/49135) `[Perf] kda: shorten the MTP verify phase-1 critical path (-11% at N=32, -12% at N=64 on VR)` | perf | ? | - |
| - | [#49139](https://github.com/sgl-project/sglang/pull/49139) `[Perf] [NVIDIA] unquant: Re-land low-M BF16 autotune via FlashInfer CuTe DSL mm_bf16` | infra,nvidia,perf,quant | ? | - |
| - | [#49143](https://github.com/sgl-project/sglang/pull/49143) `[Feat] diffusion: [sglang-miles] Let a rollout request skip the VAE decode and return only its trajectory` | perf | ? | - |
| - | [#49144](https://github.com/sgl-project/sglang/pull/49144) `[Refactor] scheduler: Move the pause state into PauseState` | infra | ? | - |
| - | [#49149](https://github.com/sgl-project/sglang/pull/49149) `[CI] diffusion: Run diffusion lanes through a shared stage and runner configs` | infra,perf | ? | - |
| - | [#49151](https://github.com/sgl-project/sglang/pull/49151) `[Fix] scheduler: Finish rejected requests and offloaded releases through the request retirer` | bug,infra | ? | - |
| - | [#49152](https://github.com/sgl-project/sglang/pull/49152) `[AMD] Kimi-K3: pass gate_mode INTERLEAVE for GU-interleaved SiTU w13` | infra,rocm | ? | - |
| - | [#49153](https://github.com/sgl-project/sglang/pull/49153) `[Test] scheduler: Record embedding sends and check at idle that every taken request sent its final output` | infra | ? | - |
| - | [#49154](https://github.com/sgl-project/sglang/pull/49154) `[CI] xeon: Prune dangling docker images and check free disk before the build` | infra | ? | - |
| - | [#49156](https://github.com/sgl-project/sglang/pull/49156) `[Fix] disagg: Fail startup when Mooncake rejects KV buffer registration` | bug | ? | - |
| - | [#49159](https://github.com/sgl-project/sglang/pull/49159) `[Test] kv_canary: Compare median decode time in the self-bench speed test` | perf | ? | - |
| - | [#49160](https://github.com/sgl-project/sglang/pull/49160) `[Test] gemma4: Stop the AR fusion test from deadlocking on a tolerance miss` | perf,risk | ? | - |
| - | [#49162](https://github.com/sgl-project/sglang/pull/49162) `[Fix] cosmos3: Keep single-GPU BF16 CFG arithmetic under CFG parallel` | bug,infra,perf | ? | - |
| - | [#49163](https://github.com/sgl-project/sglang/pull/49163) `[Doc] skills: Add a code-cleanup skill cataloging refactor and cleanup patterns` | infra,perf | ? | - |
| - | [#49171](https://github.com/sgl-project/sglang/pull/49171) `[Fix] rope/env: Remove the leftover Dual Chunk Attention RoPE, make env alias warnings visible, restore the DG` | bug,infra,perf | ? | - |
| - | [#49173](https://github.com/sgl-project/sglang/issues/49173) `[Bug] #48399 drops SM120/SM121 from the DSV4.1 DeepGEMM indexer gates — 8x prefill regression on GB10 (torch f` | bug,nvidia | ? | - |
| - | [#49182](https://github.com/sgl-project/sglang/pull/49182) `[Fix] [NVIDIA] dsv4: Restore SM120/SM121 to the DeepGEMM indexer gates` | bug,infra,nvidia | ? | - |
| - | [#49189](https://github.com/sgl-project/sglang/pull/49189) `[Refactor] cleanup: Prune dead code and env vars, fix silent failures found by the code-cleanup skill` | bug,infra,perf,quant,risk,rocm | ? | - |
| - | [#49192](https://github.com/sgl-project/sglang/pull/49192) `[Fix] sgl-router: Count media in typed gRPC Generate, embeddings and rerank access logs` | bug,infra | ? | - |
| - | [#49195](https://github.com/sgl-project/sglang/pull/49195) `[Feat] paged-experts: a disk tier for experts that do not fit host memory` | infra,perf | ? | - |
| - | [#49201](https://github.com/sgl-project/sglang/pull/49201) `[Fix] ci: Update the rerun-test reply status when a run is rerun` | bug,infra | ? | - |
| - | [#49204](https://github.com/sgl-project/sglang/pull/49204) `[Refactor] session: Remove the replace session parameter and the turn tree it pruned` | infra | ? | - |
| - | [#49205](https://github.com/sgl-project/sglang/pull/49205) `[Feat] [AMD] custom-all-reduce: Add a DPX hierarchical 2shot_push to carv2 on MI450 (gfx1250)` | infra,perf,rocm | ? | - |
| - | [#49207](https://github.com/sgl-project/sglang/pull/49207) `[Fix] session: Defer a session close while an unfinished turn still reads its media` | bug,infra | ? | - |
| - | [#49218](https://github.com/sgl-project/sglang/pull/49218) `[Fix] disaggregation: Unregister a failed staging room before releasing its KV` | bug | ? | - |
| - | [#49219](https://github.com/sgl-project/sglang/pull/49219) `[Perf] diffusion: Run SANA-Video 2.0 anchor attention on BF16 inputs at quality=high` | infra,perf | ? | - |
| - | [#49220](https://github.com/sgl-project/sglang/pull/49220) `[CI] NPU: Bump lb-actions/precision-test to v1.0.9` | infra | ? | - |
| - | [#49224](https://github.com/sgl-project/sglang/pull/49224) `[Fix] diffusion: Let FLUX.3 Image start with --num-gpus alone` | bug,infra,perf | ? | - |
| - | [#49225](https://github.com/sgl-project/sglang/pull/49225) `[Fix] diffusion: Use K/V gather when auto SP cannot split the DiT's heads (Z-Image on 4 GPUs)` | bug,infra,perf | ? | - |
| - | [#49227](https://github.com/sgl-project/sglang/pull/49227) `[CI] [CPU] cpu-graph: Import STATE_PART from decl instead of router` | infra | ? | - |
| - | [#49235](https://github.com/sgl-project/sglang/pull/49235) `[Test] comfyui: Attach loaded plugin modules to their parents so mock.patch works on Python 3.10` | infra,perf | ? | - |
| - | [#49237](https://github.com/sgl-project/sglang/pull/49237) `[Fix] CI: Avoid coverage fail-fast cycles on diffusion reruns` | bug,infra,perf | ? | - |
| - | [#49239](https://github.com/sgl-project/sglang/pull/49239) `[Doc] cookbook: Sort company groups in the sidebar alphabetically` |  | ? | - |
| - | [#49247](https://github.com/sgl-project/sglang/pull/49247) `[Fix] [NVIDIA] dsv4: Import get_eager_max_batch_size from dp_attention in the mega backend` | bug,nvidia | ? | - |
| - | [#49253](https://github.com/sgl-project/sglang/pull/49253) `[Fix] scheduler: Retract every KV holder on pause and order a few releases behind in-flight steps` | bug,infra | ? | - |
| - | [#49260](https://github.com/sgl-project/sglang/pull/49260) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main 0d7f94e7` |  | ? | - |
| - | [#49262](https://github.com/sgl-project/sglang/pull/49262) `[Perf] [NVIDIA] dsv41: Write the MegaMoE input from the fused decode mHC post` | nvidia,perf | ? | - |
| - | [#49263](https://github.com/sgl-project/sglang/pull/49263) `[Fix] cuda-graph: Pause automatic GC during CUDA graph capture` | bug,infra,nvidia,rocm | ? | - |
| - | [#49268](https://github.com/sgl-project/sglang/pull/49268) `[Fix] diffusion: Fix Cosmos 3 ignoring number of output per request for image and video requests` | bug,infra,perf | ? | - |
| - | [#49277](https://github.com/sgl-project/sglang/pull/49277) `[Fix] [NPU] MoE: Optimize Ascend MoE AllGather` | bug,infra,perf | ? | - |
| - | [#49279](https://github.com/sgl-project/sglang/pull/49279) `[Fix] diffusion: Compute CFG normalization over the whole latent under sequence parallelism (Z-Image)` | bug,infra,perf | ? | - |
| - | [#49299](https://github.com/sgl-project/sglang/pull/49299) `[Fix] mem_cache: Reset a reused request row's state in the next forward` | bug | ? | - |
| - | [#49300](https://github.com/sgl-project/sglang/pull/49300) `[Refactor] mem_cache: Ask unified memory every capacity question as a demand` | perf | ? | - |
| - | [#49301](https://github.com/sgl-project/sglang/pull/49301) `[Feat] mem_cache: Ask every unified memory capacity question of every pipeline stage` |  | ? | - |
| - | [#49308](https://github.com/sgl-project/sglang/pull/49308) `[Perf] [NVIDIA] diffusion/nomas: Fuse exact head-128 mean-square reduction` | infra,nvidia,perf | ? | - |
| - | [#49309](https://github.com/sgl-project/sglang/pull/49309) `[Fix] mamba: Commit verified states into the slots the verify forward resolved` | bug | ? | - |
| - | [#49310](https://github.com/sgl-project/sglang/pull/49310) `[Fix] scheduler: Apply the write-after-read barrier in the PP loops and on every unified-memory device` | bug | ? | - |
| - | [#49311](https://github.com/sgl-project/sglang/pull/49311) `[Fix] mem_cache: Signal a double free of unified pages when invariant checks are on` | bug,infra,perf | ? | - |
| - | [#49312](https://github.com/sgl-project/sglang/pull/49312) `[Doc] mem_cache: Document unified memory` |  | ? | - |
| - | [#49318](https://github.com/sgl-project/sglang/pull/49318) `[Test] npu/glm5.3: Add 2P2D 32P PD-separation perf case` | perf | ? | - |
| - | [#49321](https://github.com/sgl-project/sglang/pull/49321) `[Perf] [NVIDIA] dsv41: Fork the decode attention mHC mix at the MegaAttention core` | nvidia,perf | ? | - |
| - | [#49334](https://github.com/sgl-project/sglang/issues/49334) `[Bug] moe_route_warp crashes on CPU-offloaded correction_bias with --cpu-offload-gb (Tensor match failed ... d` | bug | ? | - |
| - | [#49335](https://github.com/sgl-project/sglang/pull/49335) `[CI] pp: Launch the PP test servers on DEFAULT_URL_FOR_TEST` | infra | ? | - |
| - | [#49337](https://github.com/sgl-project/sglang/pull/49337) `[Fix] moe: Validate the scale grid and use logical K for even_Ks in the GPTQ/AWQ Triton MoE kernel` | bug,infra,perf,quant,rocm | ? | - |
| - | [#49338](https://github.com/sgl-project/sglang/pull/49338) `[Fix] compressed-tensors: Reject WNA16 MoE TP shards that split a scale group` | bug,infra,quant | ? | - |
| - | [#49340](https://github.com/sgl-project/sglang/issues/49340) `[CI] jit-kernel: B200 runs time out on a cold JIT cache after shared-header changes` | bug,infra,nvidia,perf | ? | - |
| - | [#49346](https://github.com/sgl-project/sglang/pull/49346) `[Test] gemma4: Cover the multimem.ld_reduce rounding in the AR fusion residual check` | infra,perf | ? | - |
| - | [#49350](https://github.com/sgl-project/sglang/pull/49350) `[Fix] test: Drop the removed SGLANG_HICACHE_TMA_TRANSFER from the page-unified HiCache TMA test` | bug,infra | ? | - |
| - | [#49354](https://github.com/sgl-project/sglang/pull/49354) `[Perf] [NVIDIA] diffusion/nomas: Fuse VAE QK normalization and MRoPE epilogue` | infra,nvidia,perf | ? | - |
| - | [#49355](https://github.com/sgl-project/sglang/pull/49355) `[Feat] linker: Support Kimi-K3.1 DSA, MLA draft and DCP pools in the direct linker` | infra | ? | - |
| - | [#49357](https://github.com/sgl-project/sglang/pull/49357) `[Fix] compressed-tensors: Size the FP8 MoE w13 by the layer's gating` | bug,infra,quant | ? | - |
| - | [#49362](https://github.com/sgl-project/sglang/pull/49362) `[Chore] deps: Bump sgl-flash-mla to 1.0.4` | infra | ? | - |
| - | [#49364](https://github.com/sgl-project/sglang/pull/49364) `[Chore] docker: Drop the DeepGEMM and FlashMLA build steps from the K3.1 image` | infra,nvidia,perf | ? | - |
| - | [#49365](https://github.com/sgl-project/sglang/pull/49365) `[Refactor] custom-ar-v2: Single-word push epoch and consume-style pull semaphores` | infra,perf | ? | - |
| - | [#49369](https://github.com/sgl-project/sglang/issues/49369) `[Bug] GLM-4.7-Flash compressed-tensors W4A16: MLA post-load step reads kv_b_proj.weight, which a packed layer ` | quant | ? | - |
| - | [#49370](https://github.com/sgl-project/sglang/pull/49370) `[Refactor] custom-ar-v2: Move the DPX pair stages into their own header` | infra,perf | ? | - |
| - | [#49374](https://github.com/sgl-project/sglang/pull/49374) `[Perf] R3: [sglang-miles] Keep routed-expert caches only on the output rank (cherry-pick #47552, #47553)` | perf | ? | - |
| - | [#49376](https://github.com/sgl-project/sglang/pull/49376) `[Perf] [NVIDIA] kimi-k3: Bound q6 preparation by server concurrency` | infra,nvidia,perf | ? | - |
| - | [#49380](https://github.com/sgl-project/sglang/pull/49380) `[Fix] moe/router: Reject CPU-offloaded bias in warp router` | bug,infra,perf | ? | - |
| - | [#49382](https://github.com/sgl-project/sglang/pull/49382) `[Refactor] custom-ar-v2: Share one symmetric workspace per group` | infra,perf | ? | - |
| - | [#49385](https://github.com/sgl-project/sglang/issues/49385) `[Bug] dsv4: top-k v2 JIT module fails to build on Vera Rubin (CC 10.7, cu134 image): cluster kernels exceed 48` | infra,perf | ? | - |
| - | [#49386](https://github.com/sgl-project/sglang/pull/49386) `[Fix] scheduler: Record every PP result completion event after the local forward` | bug,infra | ? | - |
| - | [#49387](https://github.com/sgl-project/sglang/pull/49387) `[CI] [AMD] spur: Schedule stage-c-test-large-8-gpu-amd-mi35x on the Spur runners` | infra,rocm | ? | - |
| - | [#49388](https://github.com/sgl-project/sglang/pull/49388) `[Fix] [NVIDIA] mega_moe: Accept MXFP4 activations at DeepSeek-V4.1-Flash's 2304 intermediate size` | bug,nvidia,quant | ? | - |
| - | [#49389](https://github.com/sgl-project/sglang/pull/49389) `[CI] [AMD] spur: Run PR Test (AMD)'s scheduled stage-b MI35x job on the Spur runners` | infra,rocm | ? | - |
| - | [#49390](https://github.com/sgl-project/sglang/pull/49390) `[Refactor] kimi-k3.1: Run FlashMLA from the sgl-flash-mla wheel and drop sgl-kernel's FlashMLA build` | infra,nvidia,perf | ? | - |
| - | [#49391](https://github.com/sgl-project/sglang/pull/49391) `[Perf] [NVIDIA] diffusion/joy: Reuse FP32 residual gate for large image updates on SM103` | infra,nvidia,perf | ? | - |
| - | [#49392](https://github.com/sgl-project/sglang/pull/49392) `[Feat] sgl-router: Render StepFun (Step-3.5-Flash, Step-3.7-Flash, Step-5-Preview) through sglang-processor` | infra | ? | - |
| - | [#49394](https://github.com/sgl-project/sglang/pull/49394) `[CI] chore: add CI permissions for aaronlinear` | infra | ? | - |
| - | [#49397](https://github.com/sgl-project/sglang/pull/49397) `[Fix] http_server: Exit when a scheduler dies with multiple tokenizer workers` | bug,infra | ? | - |
| - | [#49398](https://github.com/sgl-project/sglang/pull/49398) `[CI] whl-release: Prefix sgl-project/whl release tags with the package name` | infra | ? | - |
| - | [#49399](https://github.com/sgl-project/sglang/pull/49399) `[Fix] ernie55: Import FlashMLA from the sgl-flash-mla wheel` | bug,nvidia | ? | - |
| - | [#49401](https://github.com/sgl-project/sglang/pull/49401) `[Doc] cookbook: Move Rubin hardware row above AMD` | rocm | ? | - |
| - | [#49402](https://github.com/sgl-project/sglang/pull/49402) `[Refactor] graph: Introduce device-neutral graph backend bases (1/3)` | infra | ? | - |
| - | [#49405](https://github.com/sgl-project/sglang/pull/49405) `[Feat] diffusion/sana-video2: Support sequence parallelism` | infra,perf | ? | - |
| - | [#49410](https://github.com/sgl-project/sglang/pull/49410) `[CI] docker: Follow Mega main for nightly and pin releases` | infra | ? | - |
| - | [#49411](https://github.com/sgl-project/sglang/pull/49411) `[Feat] kernels: Kimi-K3.1 kernel changes split out of #48414` | bug,perf | main | - |
| - | [#49414](https://github.com/sgl-project/sglang/pull/49414) `[Fix] logprobs: Bound top_logprobs to [0,vocab_size]` | bug,infra | ? | - |
| - | [#49417](https://github.com/sgl-project/sglang/pull/49417) `[Perf] [NVIDIA] diffusion/joy: Enable packed-image QK normalization and RoPE on SM103` | infra,nvidia,perf | ? | - |
| - | [#49420](https://github.com/sgl-project/sglang/pull/49420) `[Fix] [NVIDIA] jit: Build sm_107a on CC 10.7, keeping sm_100f only for modules that use CUTLASS` | bug,infra,nvidia,perf | ? | - |
| - | [#49422](https://github.com/sgl-project/sglang/pull/49422) `[Feat] dsa: Run prims_ts on SM107 with the FlashInfer Prims-TS overlay from main` | nvidia | ? | - |
| - | [#49423](https://github.com/sgl-project/sglang/pull/49423) `[Test] diffusion: Make cancellation backpressure deterministic` | infra,perf | ? | - |
| - | [#49428](https://github.com/sgl-project/sglang/pull/49428) `[Fix] [AMD] monokernels: Pin sgl-amd-mono at 7113024f for DSpark on current SGLang` | bug,infra,rocm | ? | - |
| - | [#49430](https://github.com/sgl-project/sglang/pull/49430) `[Feat] mem_cache: Evict Mamba states by GreedyDual-Size (--radix-eviction-policy gds)` | infra,perf | ? | - |
| - | [#49434](https://github.com/sgl-project/sglang/pull/49434) `[Feat] linker: Describe the direct linker's Mooncake objects in the L3 layout` | infra | ? | - |
| - | [#49436](https://github.com/sgl-project/sglang/pull/49436) `[Fix] dspark: Write deferred draft KV only for carried requests` | bug,infra,perf | ? | - |
| - | [#49440](https://github.com/sgl-project/sglang/pull/49440) `[Feat] diffusion: [sglang-miles] Stop a rollout at a requested step inside the rollout controller` | perf | ? | - |
| - | [#49442](https://github.com/sgl-project/sglang/pull/49442) `[Fix] diffusion/qwen-image-edit: Run n > 1 edit outputs one by one` | bug,infra,perf | ? | - |
| - | [#49443](https://github.com/sgl-project/sglang/pull/49443) `[CI] [AMD] nightly-benchmark: Run InferenceX's AgentX DeepSeek-V4.1-Flash curve on MI35x` | infra,perf,rocm | ? | - |
| - | [#49444](https://github.com/sgl-project/sglang/pull/49444) `[Perf] diffusion: Size FLUX.2 checkpoints for the all-resident auto tier` | infra,perf | ? | - |
| - | [#49447](https://github.com/sgl-project/sglang/pull/49447) `[Fix] diffusion/flux2: Size edit outputs from an input image that needs no resize` | bug,infra,perf | ? | - |
| - | [#49448](https://github.com/sgl-project/sglang/pull/49448) `[Perf] diffusion: Apply the Qwen3 text encoder's RoPE with one FlashInfer kernel` | infra,nvidia,perf | ? | - |
| - | [#49452](https://github.com/sgl-project/sglang/issues/49452) `[Feat] kda: run the Kimi-K3 fused FlashInfer decode on a BF16 SSM state (NVIDIA SM100/103)` | nvidia,perf | ? | - |
| - | [#49453](https://github.com/sgl-project/sglang/pull/49453) `[Doc] [AMD] cookbook: Match the Kimi-K3.1-Pro MI35x cells to InferenceX #4928 and mount the Ionic provider for` | rocm | ? | - |
| - | [#49456](https://github.com/sgl-project/sglang/pull/49456) `[Perf] diffusion/ming: Fuse lossless RMSNorm scale and residual epilogues` | infra,perf,quant | ? | - |
| - | [#49458](https://github.com/sgl-project/sglang/pull/49458) `[Feat] kimi-k3: add video support via frame sampling` | infra | ? | - |
| - | [#49459](https://github.com/sgl-project/sglang/pull/49459) `[CI] rust-server: Pass architectures to ModelConfig in the crash-dump test` | bug,infra | ? | - |
| - | [#49460](https://github.com/sgl-project/sglang/issues/49460) `[CI] test_rust_server_crash_dump fails on main: ModelConfig missing required 'architectures'` | bug,infra | ? | - |
| - | [#49461](https://github.com/sgl-project/sglang/pull/49461) `[Fix] rust-server: Pass architectures to ModelConfig in test_rust_server_crash_dump` | bug | ? | - |
| - | [#49470](https://github.com/sgl-project/sglang/pull/49470) `[Fix] CODEOWNERS: Restore prefill-only test ownership` | bug | ? | - |
| - | [#49475](https://github.com/sgl-project/sglang/pull/49475) `[Fix] openai: Reject assistant tool calls without a function name (HTTP 500 -> 400)` | bug,infra | ? | - |
| - | [#49476](https://github.com/sgl-project/sglang/pull/49476) `[Fix] dsv4/topk_v2: Move the cluster kernels' top-k buffer to dynamic shared memory` | bug,perf | ? | - |
| - | [#49477](https://github.com/sgl-project/sglang/pull/49477) `[Perf] attention: Optimize FA3/FA4 tree attention` | infra,nvidia,perf | ? | - |
| - | [#49478](https://github.com/sgl-project/sglang/pull/49478) `[Perf] kimi-k3.1: Per-M decode GEMM tactics and side-stream attention GEMMs` | perf | ? | - |
| - | [#49496](https://github.com/sgl-project/sglang/pull/49496) `[Refactor] scheduler: Move a request between owner lists in one call` | infra | ? | - |
| - | [#49497](https://github.com/sgl-project/sglang/pull/49497) `[Perf] flashinfer-autotune: Tune MoE with varied warm-up tokens` | nvidia,perf | ? | - |
| - | [#49499](https://github.com/sgl-project/sglang/pull/49499) `[Perf] dsv4: Size expand_prefill_causally's token block by batch size` | perf | ? | - |
| - | [#49504](https://github.com/sgl-project/sglang/pull/49504) `[Perf] diffusion/anima: Reuse timestep modulation across serial CFG branches` | infra,perf | ? | - |
| - | [#49509](https://github.com/sgl-project/sglang/pull/49509) `[CI] NPU: increase NPU coverage timeout and relax non-denoise stage tolerance` | infra | ? | - |
| - | [#49524](https://github.com/sgl-project/sglang/pull/49524) `[Perf] distributed: Keep the multimem logits all-gather on a multi-node NVLink clique` | perf | ? | - |
| - | [#49531](https://github.com/sgl-project/sglang/pull/49531) `[Fix] GLM-4.7-Flash: Load compressed-tensors W4A16 checkpoints` | bug,infra,perf,quant | ? | - |
| - | [#49534](https://github.com/sgl-project/sglang/pull/49534) `[CI] [AMD] nightly-benchmark: Run InferenceX's AgentX Qwen3.5 MXFP4 MTP curve on MI35x` | infra,perf,quant,rocm | ? | - |
| - | [#49538](https://github.com/sgl-project/sglang/pull/49538) `[Refactor] moe: Remove the SM120 top-22 small-M router path` | infra,nvidia,perf | ? | - |
| - | [#49544](https://github.com/sgl-project/sglang/pull/49544) `[Test] [NPU] qwen3.6-27b: enable expandable_segments for 1080p perf case` | perf | ? | - |
| - | [#49549](https://github.com/sgl-project/sglang/issues/49549) `[Bug] [NPU] Ascend 950: SelfAttentionOperation CreateOperation failed on Qwen3-0.6B` |  | ? | - |
| - | [#49552](https://github.com/sgl-project/sglang/pull/49552) `[Feat] diffusion/model: Support MiniMaxAI/MiniMax-H3-Image` | infra,perf | main | - |
| - | [#49564](https://github.com/sgl-project/sglang/pull/49564) `[CI] diffusion: Stabilize test execution and resource usage` | infra,perf | ? | - |
| - | [#49567](https://github.com/sgl-project/sglang/pull/49567) `[Perf] [AMD] aiter: write the breakable-graph attention output in place` | infra,perf,rocm | ? | - |
| - | [#49568](https://github.com/sgl-project/sglang/pull/49568) `[Doc] skills: One implementation per kernel contract, plus JIT kernel style rules` | infra,perf | ? | - |
| - | [#49570](https://github.com/sgl-project/sglang/pull/49570) `[Fix] diffusion: Stop normalizing bright edit inputs a second time before VAE encoding` | bug,infra,perf | ? | - |
| - | [#49573](https://github.com/sgl-project/sglang/pull/49573) `[Fix] bench: Check the chat template on the tokenizer the benchmark loads` | bug,infra,perf | ? | - |
| - | [#49574](https://github.com/sgl-project/sglang/pull/49574) `[Fix] diffusion: MiniMax-H3 follow-ups: load the public H3-Image snapshot, keep H3 video conditioning, fix pro` | bug,infra,perf | ? | - |
| - | [#49576](https://github.com/sgl-project/sglang/pull/49576) `[Perf] diffusion: Make conditioning cache eviction O(1) and raise its entry limit to 4096` | infra,perf | ? | - |
| - | [#49577](https://github.com/sgl-project/sglang/pull/49577) `[CI] ci: Raise jit-kernel Run test timeout to 90 minutes` | infra,perf | ? | - |
| - | [#49593](https://github.com/sgl-project/sglang/pull/49593) `[Doc] diffusion: Surface measured H3-Image deployment performance` | infra,perf | ? | - |
| - | [#49595](https://github.com/sgl-project/sglang/pull/49595) `[Perf] dspark: opt-in MXFP8 draft lm_head on SM10x via --speculative-dspark-lm-head-dtype` | perf,quant | ? | - |
| - | [#49600](https://github.com/sgl-project/sglang/pull/49600) `[Feat] function_call: Add granite_toolcall_parser for Granite 4.2` | infra | ? | - |
| - | [#49601](https://github.com/sgl-project/sglang/pull/49601) `[Fix] [NVIDIA] moe: Stop DeepGEMM's MLOPart helper once MegaMoE creates its buffer` | bug,infra,nvidia | ? | - |
| - | [#49603](https://github.com/sgl-project/sglang/pull/49603) `[Fix] [AMD] docker: Pin UCX and NIXL commits for ROCm PD disaggregation` | bug,infra,rocm | ? | - |
| - | [#49606](https://github.com/sgl-project/sglang/pull/49606) `[Fix] sgl-router: Render and tokenize off the async workers` | bug,infra | ? | - |
| - | [#49614](https://github.com/sgl-project/sglang/pull/49614) `[CI] [AMD] nightly-benchmark: Run InferenceX's AgentX GLM-5.2 MXFP4 MTP curve on MI35x` | infra,perf,quant,rocm | ? | - |
| - | [#49615](https://github.com/sgl-project/sglang/pull/49615) `[CI] [AMD] nightly: Drop the MiniCPM 2.6 models from the VLM MMMU test` | infra,rocm | ? | - |
| - | [#49616](https://github.com/sgl-project/sglang/pull/49616) `[Fix] dsa: Give each FlashMLA decode graph its own schedule for native-head kernels` | bug,infra,nvidia,perf | ? | - |
| - | [#49620](https://github.com/sgl-project/sglang/pull/49620) `[CI] [AMD] nightly: Drop models older than the latest two generations` | infra,rocm | ? | - |
| - | [#49621](https://github.com/sgl-project/sglang/pull/49621) `[Feat] dflash: Serve the Kimi-K3.1 DFlash2 sliding-window MLA draft` | infra,nvidia,rocm | main | - |
| - | [#49622](https://github.com/sgl-project/sglang/pull/49622) `[Fix] sgl-router: pass a streaming prefill's in-band 4xx through to the client` | bug,infra | ? | - |
| - | [#49623](https://github.com/sgl-project/sglang/pull/49623) `[Refactor] scheduler: Each request records the list that holds it` | infra | ? | - |
| - | [#49631](https://github.com/sgl-project/sglang/pull/49631) `[Perf] srt: Encode the load snapshot before taking the shared-memory file lock` | infra,perf | ? | - |
| - | [#49632](https://github.com/sgl-project/sglang/pull/49632) `[Test] crash-dump: Pin the Python frontend in the tests that resolve --ssl-keyfile-password` | bug,infra | ? | - |
| - | [#49633](https://github.com/sgl-project/sglang/pull/49633) `[Perf] hicache: Stage kernel-backend host index uploads in pinned memory` | infra,perf | ? | - |
| - | [#49635](https://github.com/sgl-project/sglang/pull/49635) `[Fix] rust-server: Keep the /v1/loads snapshot lock wait off the async workers` | bug | ? | - |
| - | [#49636](https://github.com/sgl-project/sglang/pull/49636) `[Feat] kv-shard: Let out-of-tree backends and pools join logical-page KV sharding` | infra | ? | - |
| - | [#49640](https://github.com/sgl-project/sglang/pull/49640) `[Fix] rust-server: Answer a full tokenizer queue with 503 instead of blocking intake, take extension metrics o` | bug,infra | ? | - |
| - | [#49642](https://github.com/sgl-project/sglang/pull/49642) `[CI] megakernel: Run sgl-nvidia-mega PRs' tests on SGLang's GB300 runners` | infra,nvidia | ? | - |
| - | [#49646](https://github.com/sgl-project/sglang/pull/49646) `[Fix] sgl-router: Skip the worker handoff for small request bodies` | bug,infra | ? | - |
| - | [#49647](https://github.com/sgl-project/sglang/pull/49647) `[Fix] test: pin speculative_dspark_lm_head_dtype in the resolvable-field whitelist` | bug,infra | ? | - |
| - | [#49650](https://github.com/sgl-project/sglang/pull/49650) `[Feat] rust-server: Serve media the MM processor already holds without a fetch slot, and fail fetches at its d` |  | ? | - |
| - | [#49652](https://github.com/sgl-project/sglang/pull/49652) `[CI] diffusion: Bound async video lifecycle polling` | infra,perf | ? | - |
| - | [#49653](https://github.com/sgl-project/sglang/pull/49653) `[Fix] rust-server: Answer and log request rejections as Python does, and refuse generate fields it would drop` | bug,perf | ? | - |
| - | [#49655](https://github.com/sgl-project/sglang/pull/49655) `[Fix] constrained: Reject a token in llguidance without poisoning the matcher` | bug,infra | ? | - |
| - | [#49656](https://github.com/sgl-project/sglang/pull/49656) `[Fix] kernels: Synchronize AOT MoE prefix before expert lookup` | bug,infra,perf | ? | - |
| - | [#49659](https://github.com/sgl-project/sglang/pull/49659) `[Refactor] quantization: Quantize MXFP8 weights with a JIT kernel instead of triton_kernels` | perf,quant | ? | - |
| - | [#49660](https://github.com/sgl-project/sglang/pull/49660) `[Refactor] moe: Remove the triton_kernel MoE runner backend` | nvidia,perf,quant | ? | - |
| - | [#49661](https://github.com/sgl-project/sglang/pull/49661) `[Refactor] mxfp4: Dequantize MXFP4 MoE weights with a JIT kernel instead of triton_kernels` | perf,quant | ? | - |
| - | [#49662](https://github.com/sgl-project/sglang/pull/49662) `[Chore] sgl-kernel: Stop bundling triton_kernels in the sglang-kernel wheel` | perf | ? | - |
| - | [#49663](https://github.com/sgl-project/sglang/pull/49663) `[Fix] rust-server: Name the type and retryability of streamed /generate errors` | bug,infra | ? | - |
| - | [#49664](https://github.com/sgl-project/sglang/pull/49664) `[Perf] dflash: Keep a sliding-window MLA draft's KV in a per-request ring` | infra,nvidia,perf,rocm | ? | - |
| - | [#49665](https://github.com/sgl-project/sglang/pull/49665) `[Feat] dflash: Send the draft KV ring over PD disaggregation (Mooncake)` | infra,nvidia,rocm | ? | - |
| - | [#49669](https://github.com/sgl-project/sglang/pull/49669) `[Fix] disaggregation: Bound unsharded PD prefill prompts at bootstrap` | bug,infra | ? | - |
| - | [#49670](https://github.com/sgl-project/sglang/pull/49670) `[CI] kimi-k3.1: Add B300 CI tests for the Balanced and Low Latency recipes` | infra,perf | ? | - |
| - | [#49673](https://github.com/sgl-project/sglang/pull/49673) `[Feat] multimodal: Decode HEIF images and read relative BMP, TIFF and HEIF paths` | infra | ? | - |
| - | [#49675](https://github.com/sgl-project/sglang/pull/49675) `[Doc] diffusion: Fix feature guides that disagree with the code` | bug,infra,perf,quant | ? | - |
| - | [#49677](https://github.com/sgl-project/sglang/pull/49677) `[Refactor] scheduler: Edit request lists only through move and the retirer` | infra | ? | - |
| - | [#49686](https://github.com/sgl-project/sglang/pull/49686) `[Feat] disaggregation: Make the PD top-logprobs metadata width configurable` | infra | ? | - |
| - | [#49688](https://github.com/sgl-project/sglang/pull/49688) `[Fix] muse_spark: [sglang-miles] Refresh derived weight caches after a weight sync` | bug,perf | ? | - |
| - | [#49693](https://github.com/sgl-project/sglang/pull/49693) `[Refactor] diffusion-rl: store latents and debug tensors as one output-store field per step` | perf | ? | - |
| - | [#49699](https://github.com/sgl-project/sglang/pull/49699) `[Test] disaggregation: Give the fake draft pool follows_target_swa_ids` | infra | ? | - |
| - | [#49701](https://github.com/sgl-project/sglang/pull/49701) `[Fix] [NPU] EPLB: preserve NZ storage, reuse TP, and isolate draft capture` | bug,infra | ? | - |
| - | [#49704](https://github.com/sgl-project/sglang/pull/49704) `[Perf] [AMD] muse-spark: Prefill and decode optimization` | infra,perf,rocm | ? | - |
| - | [#49706](https://github.com/sgl-project/sglang/pull/49706) `[CI] diffusion: run MiniMax-H3-Image T2I and edit in the B200 suite` | infra,nvidia,perf | ? | - |
| - | [#49707](https://github.com/sgl-project/sglang/pull/49707) `[Feat] [AMD] diffusion: Run MiniMax-H3-Image on ROCm and add MI300X/MI325X/MI350X/MI355X cookbook recipes` | infra,perf,rocm | ? | - |
| - | [#49714](https://github.com/sgl-project/sglang/pull/49714) `[Fix] diffusion/zimage: Align request sizes to the 16-pixel patch grid` | bug,infra,perf | ? | - |
| - | [#49715](https://github.com/sgl-project/sglang/pull/49715) `[Refactor] mm: import MM_PAD_SHIFT_VALUE instead of re-declaring it` | infra | ? | - |
| - | [#49716](https://github.com/sgl-project/sglang/pull/49716) `[Doc] cookbook: Drop the PP chunk sizing flags from the Kimi-K3.1-Pro prefill cells` |  | ? | - |
| - | [#49718](https://github.com/sgl-project/sglang/pull/49718) `[CI] diffusion: refresh 5090 host-anon baselines for two cases` | infra,perf | ? | - |
| - | [#49719](https://github.com/sgl-project/sglang/pull/49719) `[Refactor] mem_cache: Keep the GDN speculative ReplaySSM ring in a request sub-pool of unified memory` | perf | ? | - |
| - | [#49720](https://github.com/sgl-project/sglang/pull/49720) `[Refactor] mem_cache: Keep the KDA speculative ReplaySSM ring in the request sub-pool` | perf | ? | - |
| - | [#49722](https://github.com/sgl-project/sglang/pull/49722) `[Fix] scheduler: Apply pending chunked-prefill aborts in the PP PD prefill loop` | bug,infra | ? | - |
| - | [#49727](https://github.com/sgl-project/sglang/pull/49727) `[Feat] sgl-router: Add production API compatibility` | infra | ? | - |
| - | [#49750](https://github.com/sgl-project/sglang/pull/49750) `[CI] [NPU] docker: Bump SGLANG_KERNEL_NPU_TAG to 2026.11.0.post3` | infra | ? | - |
| - | [#49751](https://github.com/sgl-project/sglang/pull/49751) `[Refactor] scheduler: Remove the remaining direct request-list edits` | infra | ? | - |
| - | [#49755](https://github.com/sgl-project/sglang/pull/49755) `[Chore] sgl-router: Remove a local design-doc path from the crate docs` | infra | ? | - |
| - | [#49756](https://github.com/sgl-project/sglang/pull/49756) `[Fix] server_args: Reject --scheduler-recv-interval above 1 with pipeline parallelism` | bug,infra | ? | - |
| - | [#49758](https://github.com/sgl-project/sglang/pull/49758) `[Fix] tokenizer_manager: Reject logprob_start_len below -1 with a 400` | bug,infra | ? | - |
| - | [#49762](https://github.com/sgl-project/sglang/pull/49762) `[Perf] minimax-h3: Calibrate quality=high with a per-step cache schedule` | infra,perf | ? | - |
| - | [#49763](https://github.com/sgl-project/sglang/pull/49763) `[CI] [AMD] nightly: Stop running DeepSeek-V3.2` | infra,rocm | ? | - |
| - | [#49771](https://github.com/sgl-project/sglang/pull/49771) `[Chore] deps: Bump FlashInfer to 0.7.4` | infra,nvidia | ? | - |
| - | [#49775](https://github.com/sgl-project/sglang/pull/49775) `[Fix] mem_cache: Size a fused draft's KV region in the dtype the draft resolves` | bug,perf,quant | ? | - |
| - | [#49787](https://github.com/sgl-project/sglang/pull/49787) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main a0f8080c` |  | ? | - |
| - | [#49793](https://github.com/sgl-project/sglang/pull/49793) `[CI] [NPU] accuracy: Add 8-NPU suite for MiniMax-M2.5 W8A8 4p GPQA` | infra,quant,risk | ? | - |
| - | [#49796](https://github.com/sgl-project/sglang/issues/49796) `[Bug] Qwen-VL image preprocessing OOMs on GPU: 2.87x peak from torch.cat(processed_images) plus a cache that n` | perf | ? | - |
| - | [#49798](https://github.com/sgl-project/sglang/pull/49798) `[Fix] scheduler: Answer release_memory_occupation only after every pipeline stage released` | bug,infra | ? | - |
| - | [#49808](https://github.com/sgl-project/sglang/pull/49808) `[Perf] diffusion: Replay the Qwen3 text encoder from breakable CUDA graphs` | infra,nvidia,perf | ? | - |
| - | [#49820](https://github.com/sgl-project/sglang/issues/49820) `[CI] test_dsa_eager_metadata_no_host_sync fails on main: stub backend lacks _dcp_topk_length_buffer` | infra | ? | - |
| - | [#49821](https://github.com/sgl-project/sglang/pull/49821) `[Test] dsa: Stub _dcp_topk_length_buffer in the eager-metadata no-host-sync test` |  | ? | - |
| - | [#49825](https://github.com/sgl-project/sglang/pull/49825) `[Fix] simulator: Keep the replaced HiCache storage workers alive` | bug,infra | ? | - |
| - | [#49826](https://github.com/sgl-project/sglang/pull/49826) `[Fix] minimax-h3: preserve per-layer AdaLN parameters with Cache-DiT` | bug,infra,perf | ? | - |
| - | [#49839](https://github.com/sgl-project/sglang/pull/49839) `[Chore] diffusion: Fix wrong and stale comments and docstrings in runtime` | bug,infra,perf | ? | - |
| - | [#49841](https://github.com/sgl-project/sglang/pull/49841) `[Refactor] diffusion: Remove dead code in layers, quantization and runtime utils` | perf,quant | ? | - |
| - | [#49842](https://github.com/sgl-project/sglang/pull/49842) `[Refactor] diffusion: Remove dead code in configs and loaders` | perf | ? | - |
| - | [#49843](https://github.com/sgl-project/sglang/pull/49843) `[Refactor] diffusion: Remove dead code in models and pipeline stages` | perf | ? | - |
| - | [#49844](https://github.com/sgl-project/sglang/pull/49844) `[Refactor] diffusion: Remove dead test helpers, orphan perf baselines and unused CI code` | infra,perf | ? | - |
| - | [#49848](https://github.com/sgl-project/sglang/pull/49848) `[Fix] lora: [sglang-miles] Keep kv_b_proj adapters off the MHA cached-prefix paths` | bug,perf | ? | - |
| - | [#49851](https://github.com/sgl-project/sglang/pull/49851) `[Feat] kimi_k3: Support ModelOpt MXFP8 KDA for Kimi-K3.1-Pro` | infra,quant | ? | - |
| - | [#49865](https://github.com/sgl-project/sglang/issues/49865) `[Bug] sgl-kernel: FA3 kernels are compiled and linked twice (hdimdiff sm90 and softcapall sm80 files)` | nvidia,perf | ? | - |
| - | [#49866](https://github.com/sgl-project/sglang/pull/49866) `[Fix] sgl-kernel: Do not compile FA3 instantiation files twice` | bug,infra,nvidia,perf | ? | - |
| - | [#49867](https://github.com/sgl-project/sglang/pull/49867) `[Chore] codeowners: paged-experts` | infra | ? | - |
| - | [#49868](https://github.com/sgl-project/sglang/pull/49868) `[Fix] test: Seed the retracted queue through move() in test_prealloc_token_usage` | bug,infra | ? | - |
| - | [#49871](https://github.com/sgl-project/sglang/issues/49871) `[Bug] Decode HiCache reports host and storage cache hits as device hits` | perf | ? | - |
| - | [#49872](https://github.com/sgl-project/sglang/pull/49872) `[Feat] diffusion: runway praxis 1 support` | infra,perf | ? | - |
| - | [#49877](https://github.com/sgl-project/sglang/pull/49877) `[Feat] diffusion: [sglang-miles] Put a training rollout's generated output in the output store` | perf | ? | - |
| - | [#49878](https://github.com/sgl-project/sglang/pull/49878) `[Fix] disaggregation: Attribute decode HiCache hits to host and storage` | bug,infra | ? | - |
| - | [#49881](https://github.com/sgl-project/sglang/issues/49881) `[Bug][GLM-5.3-Flash][EAGLE] NaN logits latched for all later requests after a decode step whose batch is padde` | bug,nvidia,risk | ? | - |
| - | [#49886](https://github.com/sgl-project/sglang/pull/49886) `[Feat] mem_cache: Checkpoint hybrid Mamba state only at fork points and request ends` | infra,perf | ? | - |
| - | [#49890](https://github.com/sgl-project/sglang/pull/49890) `[Fix] benchmark: Accept --dtype int4_w4a16 in tuning_fused_moe_triton_sep.py` | bug,infra,perf,quant | ? | - |
| - | [#49894](https://github.com/sgl-project/sglang/pull/49894) `[Fix] entrypoints: Apply API keys in tokenizer workers and on WebSocket routes` | bug,infra | ? | - |
| - | [#49897](https://github.com/sgl-project/sglang/issues/49897) `[Docs] Clarify streaming tool argument guarantees when a Chat Completions response ends with length` |  | ? | - |
| - | [#49906](https://github.com/sgl-project/sglang/pull/49906) `[Fix] mem_cache: Keep freeing SWA slots for an unpublished prefill with a pending SWA branch` | bug,infra,perf | ? | - |
| - | [#49907](https://github.com/sgl-project/sglang/pull/49907) `[Feat] rust-server: Let a multimodal processor fail a request once its result is processed` |  | ? | - |
| - | [#49908](https://github.com/sgl-project/sglang/pull/49908) `[CI] profiling: Check stage-profiler sync against the kernel's measured time` | infra,perf | ? | - |
| - | [#49912](https://github.com/sgl-project/sglang/pull/49912) `[Feat] dsa: Honor the page stride of index-K buffers` | perf | ? | - |
| - | [#49913](https://github.com/sgl-project/sglang/pull/49913) `[Feat] kimi_k3: Serve Kimi-K3.1 on the unified memory pool` | perf,quant | ? | - |
| - | [#49917](https://github.com/sgl-project/sglang/pull/49917) `[Fix] hicache: Lock the window a staged buffer-mode load-back keeps` | bug,infra | ? | - |
| - | [#49922](https://github.com/sgl-project/sglang/pull/49922) `[Perf] dsa: Stage the DCP top-k merge push in smem and fall back in registers for up to two ranks` | infra,perf | ? | - |
| - | [#49923](https://github.com/sgl-project/sglang/pull/49923) `[Perf] kimi-k3: Build the fused routing metadata in a separate 1024-thread PDL kernel` | infra,perf | ? | - |
| - | [#49927](https://github.com/sgl-project/sglang/pull/49927) `[Doc] tool-parser: Clarify streamed argument completion` |  | ? | - |
| - | [#49929](https://github.com/sgl-project/sglang/pull/49929) `[Fix] [AMD] kimi-k3: Skip the CuTe DSL TGV tactic registration on ROCm` | bug,infra,rocm | ? | - |
| - | [#49931](https://github.com/sgl-project/sglang/pull/49931) `[Fix] [NVIDIA] unquant: restore eager low-M BF16 performance` | bug,nvidia,perf,quant | ? | - |
| - | [#49943](https://github.com/sgl-project/sglang/pull/49943) `[Perf] dcp: Replay prefix hits under breakable prefill graphs` | perf | ? | - |
| - | [#49947](https://github.com/sgl-project/sglang/issues/49947) `[CI] test_unified_row_state_reset fails on main: GDN speculative ring length 8 < 16` | infra | ? | - |
| - | [#49948](https://github.com/sgl-project/sglang/pull/49948) `[Test] mem_cache: Use a 16-slot GDN spec ring in the row-state reset test` |  | ? | - |
| - | [#49951](https://github.com/sgl-project/sglang/pull/49951) `[CI] disaggregation: Move Mooncake's handshake port range off the PD test ports` | infra | ? | - |
| - | [#49964](https://github.com/sgl-project/sglang/pull/49964) `[Fix] kimi_k25: Run the vision projection under the caller's grad mode` | bug,infra | ? | - |
| - | [#49966](https://github.com/sgl-project/sglang/pull/49966) `[Refactor] mem_cache: Compose same-lifetime parts into one unified sub-pool` |  | ? | - |
| - | [#49967](https://github.com/sgl-project/sglang/pull/49967) `[CI] deepgemm: pin apache-tvm-ffi for the release test jobs` | infra | ? | - |
| - | [#49972](https://github.com/sgl-project/sglang/pull/49972) `[CI] fa3: Add the sgl-fa3 release workflow` | infra,nvidia,perf | ? | - |
| - | [#49980](https://github.com/sgl-project/sglang/pull/49980) `[Perf] dsa: Native-head FlashMLA and a precomputed schedule for DCP decode` | nvidia,perf | ? | - |
| - | [#49983](https://github.com/sgl-project/sglang/pull/49983) `[Doc] README: update the readme logo` |  | ? | - |
| - | [#49986](https://github.com/sgl-project/sglang/issues/49986) `[CI] test_page_sharded_dsa_attention fails on main: stub backend lacks sparse_prefill_small_heads` | infra | ? | - |
| - | [#49987](https://github.com/sgl-project/sglang/pull/49987) `[Test] mem_cache: Set sparse_prefill_small_heads on the page-sharded DSA test backend` |  | ? | - |
| - | [#50003](https://github.com/sgl-project/sglang/pull/50003) `[Chore] hicache: Remove request-end-only Mamba storage backups from the Kimi-K3.1 Day-0 branch` | perf | ? | - |
| - | [#50004](https://github.com/sgl-project/sglang/pull/50004) `[Fix] [NPU] moe: Add ascend_ops backend checks across MoE models` | bug,infra | ? | - |
| - | [#50005](https://github.com/sgl-project/sglang/pull/50005) `[Feat] hisparse: Support Kimi-K3.1 DSA layers on PD decode with DFLASH` | infra | ? | - |
| - | [#50006](https://github.com/sgl-project/sglang/issues/50006) `[Bug] Native runtime.v1 gRPC reports asynchronous input validation failures as INTERNAL` |  | ? | - |
| - | [#50009](https://github.com/sgl-project/sglang/pull/50009) `[Fix] mamba: Clear a stale COW source when an unadmitted request is matched again` | bug,infra,perf | ? | - |
| - | [#50016](https://github.com/sgl-project/sglang/pull/50016) `[Chore] deps: Bump sgl-deep-gemm to 0.2.8 and sgl-flash-mla to 1.0.5` | infra | ? | - |
| - | [#50018](https://github.com/sgl-project/sglang/pull/50018) `[Perf] model_overrides: Default GLM-5.3-Flash to an agentic Mamba pool split` | infra,perf | ? | - |
| - | [#50033](https://github.com/sgl-project/sglang/pull/50033) `[Doc] hybrid: Document sizing the state and KV pools for multi-turn reuse` | infra | ? | - |
| - | [#50039](https://github.com/sgl-project/sglang/pull/50039) `[Fix] deepseek-v4.1: Preserve compact DSpark outputs with CP bounded replay` | bug,infra | ? | - |
| - | [#50041](https://github.com/sgl-project/sglang/pull/50041) `[Doc] cookbook: Pin GLM-5.3-Flash high-throughput recipes to mamba ratio 0.9` | infra,perf | ? | - |
| - | [#50052](https://github.com/sgl-project/sglang/pull/50052) `[Fix] sgl-router: Close the PD gaps that block replacing sgl-model-gateway in CI` | bug,infra | ? | - |
| - | [#50055](https://github.com/sgl-project/sglang/pull/50055) `[CI] NPU: upgrade lb-actions/precision-test from v1.0.9 to v1.0.11` | infra | ? | - |
| - | [#50056](https://github.com/sgl-project/sglang/pull/50056) `[Fix] hicache: resolve prefetch trailing-window keys before the storage read` | bug,infra | ? | - |
| - | [#50081](https://github.com/sgl-project/sglang/pull/50081) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main f4c7f821` |  | ? | - |
| - | [#50096](https://github.com/sgl-project/sglang/pull/50096) `[Feat] [NPU] attention: Support FP8 KV for DSA prefill context parallelism` | infra,quant | ? | - |
| - | [#50098](https://github.com/sgl-project/sglang/pull/50098) `[Fix] diffusion: Align Wan2.2-TI2V-5B request sizes to its 32-pixel patch grid` | bug,infra,perf | ? | - |
| - | [#50101](https://github.com/sgl-project/sglang/pull/50101) `[Fix] diffusion: Keep fused QKNorm+RoPE rounding exact on SM100` | bug,infra,nvidia,perf | ? | - |
| - | [#50102](https://github.com/sgl-project/sglang/pull/50102) `[Perf] kda: Reuse int64 prefill offsets across layers` | infra,perf | ? | - |
| - | [#50107](https://github.com/sgl-project/sglang/pull/50107) `[Fix] [NPU] kimi-k3: Skip the CuTe DSL TGV tactic registration on NPU` | bug,infra | ? | - |
| - | [#50108](https://github.com/sgl-project/sglang/pull/50108) `[CI] NPU: Add base-a CPU coverage collection` | infra | ? | - |
| - | [#50114](https://github.com/sgl-project/sglang/pull/50114) `[Fix] diffusion: Align Cosmos3 request sizes to the 16-pixel latent grid` | bug,infra,perf | ? | - |
| - | [#50115](https://github.com/sgl-project/sglang/pull/50115) `[CI] NPU: Scope CPU coverage to NPU unit tests` | infra | ? | - |
| - | [#50118](https://github.com/sgl-project/sglang/pull/50118) `Revert "[Feat] mem_cache: Evict Mamba states by GreedyDual-Size (--radix-eviction-policy gds)"` | perf | ? | - |
| - | [#50136](https://github.com/sgl-project/sglang/issues/50136) `[Bug] DP attention with --enable-prefill-delayer and --prefill-decode-interval-min-bs: ranks enter different c` |  | ? | - |
| - | [#50137](https://github.com/sgl-project/sglang/issues/50137) `[Bug] DP attention: an abort of a running request can be lost and the request runs to max_new_tokens` |  | ? | - |
| - | [#50144](https://github.com/sgl-project/sglang/pull/50144) `[Feat] jit: Add SGLANG_JIT_ENABLE_LINEINFO for profiler source views` | infra,perf | ? | - |
| - | [#50161](https://github.com/sgl-project/sglang/pull/50161) `[Feat] sgl-router: Make the request-body cap configurable via SGLANG_ROUTER_MAX_BODY_BYTES` | infra | ? | - |
| - | [#50177](https://github.com/sgl-project/sglang/pull/50177) `[Fix] DeepSeek-V4: Skip decode attention TP setup when it is off` | bug,infra | ? | - |
| - | [#50178](https://github.com/sgl-project/sglang/pull/50178) `[Fix] DeepSeek-V4: Default input_embeds to None in DS4 forward` | bug,infra | ? | - |
| - | [#50181](https://github.com/sgl-project/sglang/pull/50181) `[Fix] hicache: Refuse a runtime write_back policy under buffer_only host memory` | bug,infra,perf | ? | - |
| - | [#50185](https://github.com/sgl-project/sglang/pull/50185) `[Doc] cookbook: Add Inkling-2-Small deployment recipes` |  | ? | - |
| - | [#50189](https://github.com/sgl-project/sglang/pull/50189) `[Feat] rust-server: Honor --warmups and --gc-warning-threshold-secs` |  | ? | - |
| - | [#50190](https://github.com/sgl-project/sglang/pull/50190) `[Feat] rust-server: Tell a model package's abort hook which requests an abort names` | infra | ? | - |
| - | [#50193](https://github.com/sgl-project/sglang/pull/50193) `[CI] fa3: Build the sgl-fa3 wheel with Python 3.10 for cp310-abi3` | infra,nvidia | ? | - |
| - | [#50199](https://github.com/sgl-project/sglang/pull/50199) `[Perf] rust-server: Keep a multimodal item's identity on the item so its feature is hashed once` | infra,perf | ? | - |
| - | [#50204](https://github.com/sgl-project/sglang/pull/50204) `[Perf] rust-server: Use the CPU's SHA-256 instructions on aarch64 Linux` | infra,perf | ? | - |
| - | [#50218](https://github.com/sgl-project/sglang/issues/50218) `[CI] diffusion MiniMax-H3 tests fail on main: stale ComfyUI H3 SOURCE_SHA256 and B200 consistency mismatch` | infra,nvidia,perf | ? | - |
| - | [#50219](https://github.com/sgl-project/sglang/pull/50219) `[Fix] comfyui: Refresh the reviewed MiniMax-H3 source hash after #49826` | bug,perf | ? | - |
| - | [#50231](https://github.com/sgl-project/sglang/pull/50231) `[Doc] [NPU] docs: restructure the Ascend parameter tuning guide and align its dependents` | perf | ? | - |
| - | [#50237](https://github.com/sgl-project/sglang/pull/50237) `[Fix] inkling: declare tools first and render tool_choice instructions` | bug | ? | - |
| - | [#50252](https://github.com/sgl-project/sglang/pull/50252) `[CI] [NPU] tests: Move DSV4-Flash W8A8 16-card cases to the full-test suites` | infra,quant | ? | - |
| - | [#50258](https://github.com/sgl-project/sglang/pull/50258) `[Fix] [NPU] test: Set TRITON_CACHE_DIR to /tmp/triton_cache` | bug | ? | - |
| - | [#50260](https://github.com/sgl-project/sglang/pull/50260) `[Chore] fa3: Serve FA3 from the sgl-fa3 wheel and remove it from sglang-kernel` | infra,nvidia,perf | ? | - |
| - | [#50267](https://github.com/sgl-project/sglang/pull/50267) `[Doc] [NPU] tutorials: Add deployment scripts for  dsv4-flash，glm5.2-w4a8，qwen3.6-27b` |  | ? | - |
| - | [#50289](https://github.com/sgl-project/sglang/pull/50289) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main 8f29d8dc` |  | ? | - |
| - | [#50348](https://github.com/sgl-project/sglang/issues/50348) `[Bug] sgl-router: /v1/messages returns 400 for requests with inline role="system"` |  | ? | - |
| - | [#50363](https://github.com/sgl-project/sglang/pull/50363) `[Perf] [AMD] hicache: Submit staged write-back copies with hipMemcpyBatchAsync on ROCm` | infra,perf,rocm | ? | - |
| - | [#50364](https://github.com/sgl-project/sglang/pull/50364) `[Feat] quantization: Support dense SiLU+mul fusion for masked per_token_group_quant` | infra,perf,quant | ? | - |
| - | [#50369](https://github.com/sgl-project/sglang/pull/50369) `[Chore] release: Bump sgl-kernel version to 0.4.11` | infra,perf,rocm | ? | - |
| - | [#50373](https://github.com/sgl-project/sglang/pull/50373) `[Test] server_args: Stop two PortArgs tests from probing fixed host ports` | infra | ? | - |
| - | [#50394](https://github.com/sgl-project/sglang/pull/50394) `[Chore] flash-attn: Restore the kernels-hub FA3 loader and the kernel…` | infra,nvidia,perf | ? | - |

### sglang — Open / submitted (933 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#47410](https://github.com/sgl-project/sglang/pull/47410) `[Perf] deterministic: Launch a fixed number of Triton decode blocks for large split budgets` | infra,perf,rocm | main | - |
| P0 | [#47412](https://github.com/sgl-project/sglang/pull/47412) `[Fix] [AMD] deterministic: Run block-FP8 linears through Triton on ROCm` | bug,quant,rocm | main | - |
| P0 | [#47414](https://github.com/sgl-project/sglang/pull/47414) `[Fix] [AMD] deterministic: Run FP8 MoE experts through the Triton runner on ROCm` | bug,quant,rocm | main | - |
| P0 | [#47418](https://github.com/sgl-project/sglang/pull/47418) `[Perf] [AMD] DFlash: FP8 KV and tuned launch for draft SWA verify` | perf,quant,rocm | main | - |
| P0 | [#47430](https://github.com/sgl-project/sglang/pull/47430) `[Perf] [AMD] aiter: FP8 Q for EAGLE target_verify and draft_extend attention with an FP8 KV cache` | perf,quant,rocm | main | - |
| P0 | [#47434](https://github.com/sgl-project/sglang/pull/47434) `[Fix] spec: Greedy requests keep the argmax prefill draft under rejection sampling` | bug | main | - |
| P0 | [#47439](https://github.com/sgl-project/sglang/pull/47439) `[Fix] [AMD] Keep QK-norm RoPE shuffles within logical warps` | bug,perf,rocm | main | - |
| P0 | [#47809](https://github.com/sgl-project/sglang/pull/47809) `[Fix] attention: Honor custom masks past the causal tile in Triton extend` | bug,perf,rocm | main | - |
| P0 | [#47813](https://github.com/sgl-project/sglang/pull/47813) `[Fix] [AMD] aiter: Decode DCP over a non-fp8 KV cache on Gluon instead of the asm kernel` | bug,perf,quant,rocm | main | - |
| P0 | [#47872](https://github.com/sgl-project/sglang/pull/47872) `[Perf] [AMD] dsa: Opt-in single-pass Triton top-k for long-context decode rows` | infra,perf,rocm | main | - |
| P0 | [#47886](https://github.com/sgl-project/sglang/pull/47886) `[Fix] [AMD] w8a8_fp8: Load and run per-channel FP8 DeepSeek-V4 checkpoints on ROCm` | bug,quant,rocm | main | - |
| P0 | [#47888](https://github.com/sgl-project/sglang/pull/47888) `[Perf] [AMD] dsv4: Token-parallel prefill on ROCm (opt-in)` | perf,rocm | main | - |
| P0 | [#47897](https://github.com/sgl-project/sglang/pull/47897) `[Perf] [AMD] dsa: In-tree gfx950 paged MQA logits for decode / MTP-verify rows` | infra,perf,rocm | main | - |
| P0 | [#47938](https://github.com/sgl-project/sglang/pull/47938) `[Fix] [AMD] dsv4: transfer unified C4 state by request-local rows` | bug,rocm | main | - |
| P0 | [#48084](https://github.com/sgl-project/sglang/pull/48084) `[Fix] sampling: Make penalizer execution order deterministic` | bug | main | - |
| P0 | [#48139](https://github.com/sgl-project/sglang/pull/48139) `[Fix] models: Set k/v_scale_float when loading KV cache scales from file` | bug,perf,quant | main | - |
| P0 | [#48302](https://github.com/sgl-project/sglang/pull/48302) `[Fix] [AMD] dsa: One decode graph variant on every attention-DP rank, one verify graph` | bug,infra,rocm | main | - |
| P0 | [#48356](https://github.com/sgl-project/sglang/issues/48356) `[Bug] disaggregation: Qwen EAGLE PD decode can produce corrupted output after retraction` | risk | ? | - |
| P0 | [#48425](https://github.com/sgl-project/sglang/pull/48425) `[Fix] deterministic: replay hybrid Mamba prefix instead of restoring donated state` | bug | main | - |
| P0 | [#48500](https://github.com/sgl-project/sglang/pull/48500) `[Fix] deepseek_v4: floor amax before the division in the V4.1 fp8 KV scale` | bug,perf,quant | main | - |
| P0 | [#48620](https://github.com/sgl-project/sglang/pull/48620) `[Fix] [AMD] JIT: Port per-token group FP8 quantization v2 to ROCm` | bug,perf,quant,rocm | main | - |
| P0 | [#48649](https://github.com/sgl-project/sglang/pull/48649) `[Perf] [AMD] qsa: Faster decode MQA logits on ROCm (padded Q, group-strided launch)` | infra,perf,rocm | main | - |
| P0 | [#48700](https://github.com/sgl-project/sglang/pull/48700) `[Fix] [AMD] aiter: Reserve the decode workspace in the automatic mem_fraction_static` | bug,infra,rocm | main | - |
| P0 | [#48747](https://github.com/sgl-project/sglang/issues/48747) `[Bug] FlashInfer and Triton apply checkpoint KV-cache scales to a BF16 KV cache, so decode output is garbage (` | nvidia,perf,quant,risk,rocm | ? | - |
| P0 | [#48748](https://github.com/sgl-project/sglang/pull/48748) `[Fix] attention: do not apply KV-cache scales to a BF16 KV cache in FlashInfer and Triton` | bug,nvidia,perf,quant,rocm | main | - |
| - | [#48759](https://github.com/sgl-project/sglang/pull/48759) `[Fix] qwen4_exp: decode the fp8 PLE table on SM80` | bug,quant | ? | - |
| - | [#48760](https://github.com/sgl-project/sglang/pull/48760) `[Perf] rotary_embedding: Short-circuit absent modality token scans in M-RoPE get_rope_index` | perf | ? | - |
| - | [#48763](https://github.com/sgl-project/sglang/pull/48763) `[Feat] dflash: Serve MoE FFN drafts for DFlash and DSpark` | infra | ? | - |
| P1 | [#48764](https://github.com/sgl-project/sglang/pull/48764) `[Fix] cache: Register UMBP GPU buffers with device metadata` | bug,perf | ? | - |
| - | [#48765](https://github.com/sgl-project/sglang/pull/48765) `[Fix] anthropic: Preserve Kimi Messages stream usage` | bug | ? | - |
| - | [#48766](https://github.com/sgl-project/sglang/issues/48766) `[Feature] Support SID-based generative retrieval with constrained decoding and optimized beam search` | perf | ? | - |
| - | [#48767](https://github.com/sgl-project/sglang/pull/48767) `[Perf] [AMD] diffusion: Mount the Wan FFN linear+GELU site on gfx1250 with a bit-exact GELU` | infra,perf,rocm | ? | - |
| P1 | [#48768](https://github.com/sgl-project/sglang/pull/48768) `[Perf] [AMD] diffusion: Let aiter RMSNorm read strided Q/K rows instead of copying them` | infra,perf,rocm | ? | - |
| - | [#48769](https://github.com/sgl-project/sglang/pull/48769) `[Perf] [AMD] diffusion: Build the ROCm batched-Conv2D VAE input in one Triton pass` | infra,perf,rocm | ? | - |
| P1 | [#48770](https://github.com/sgl-project/sglang/pull/48770) `[Perf] [AMD] DeepSeek-V4.1: Exchange only the indexer selection part attention reads under the HIP row shard` | bug,perf,rocm | ? | - |
| P1 | [#48771](https://github.com/sgl-project/sglang/pull/48771) `[Perf] [AMD] DeepSeek-V4.1: Opt-in SDMA exchange for the HIP indexer row shard` | bug,perf,rocm | ? | - |
| P1 | [#48772](https://github.com/sgl-project/sglang/pull/48772) `[Perf] [AMD] DeepSeek-V4.1: Faster HIP dense prefill indexer (row-group scoring, \|s\| epilogue, tile-gated top-` | perf,rocm | ? | - |
| P1 | [#48774](https://github.com/sgl-project/sglang/pull/48774) `[Perf] attention: Parallelize MLA chunked-prefix KV index construction` | perf | ? | - |
| - | [#48780](https://github.com/sgl-project/sglang/pull/48780) `[Feature] Add bitsandbytes support for Qwen3-VL / Qwen3-VL-MoE` |  | ? | - |
| - | [#48782](https://github.com/sgl-project/sglang/pull/48782) `[Fix] hicache: Wait for overlapping write-through acknowledgements` | bug,perf | ? | - |
| - | [#48783](https://github.com/sgl-project/sglang/pull/48783) `[Perf] [NVIDIA] bf16-gemm: SM107 split-K and cute_ext tactics` | nvidia,perf,quant | ? | - |
| - | [#48787](https://github.com/sgl-project/sglang/pull/48787) `[Perf] [XPU] fp8: Run FP8 dense layers weight-only (W8A16) through sgl_kernel.fp8_linear` | infra,nvidia,perf,quant | ? | - |
| P1 | [#48788](https://github.com/sgl-project/sglang/pull/48788) `[Fix] kimi-k3: Rebuild derived weights in place on weight updates` | bug | ? | - |
| - | [#48791](https://github.com/sgl-project/sglang/issues/48791) `[Bug] Reasoning parser splits on first occurrence of closing think tag: quoted </think> inside reasoning trunc` | risk | ? | - |
| - | [#48792](https://github.com/sgl-project/sglang/pull/48792) `[Perf] [XPU] vae-layernorm-silu: add Xpu triton path to replace torch` | nvidia,perf,rocm | ? | - |
| - | [#48793](https://github.com/sgl-project/sglang/issues/48793) `[Bug] Model gateway silently drops `cache_salt` on chat completions` | risk | ? | - |
| - | [#48795](https://github.com/sgl-project/sglang/pull/48795) `[Fix] responses: Merge a commentary preamble with its tool calls when replaying history` | bug | ? | - |
| - | [#48796](https://github.com/sgl-project/sglang/pull/48796) `[Feat] cp: Add Qwen3.5/Qwen3.8 prefill with Symm and MegaMoE` | infra,nvidia,perf | ? | - |
| - | [#48802](https://github.com/sgl-project/sglang/issues/48802) `[Bug] Decode HiCache restore returns HTTP 500 under host-cache pressure with GLM-5.3-Flash` | perf | ? | - |
| P1 | [#48806](https://github.com/sgl-project/sglang/pull/48806) `[Perf] [AMD] GLM5.3: Allow an FP8 E4M3 KV cache for Triton sparse attention on gfx950` | infra,perf,quant,rocm | ? | - |
| P1 | [#48811](https://github.com/sgl-project/sglang/pull/48811) `[Fix] disaggregation: Fail a prefill KV transfer whose decode never completes it` | bug | ? | - |
| - | [#48813](https://github.com/sgl-project/sglang/pull/48813) `[Fix] disaggregation: Advance a Mamba request's unpublished KV under a write-through cache` | bug,perf | ? | - |
| - | [#48814](https://github.com/sgl-project/sglang/pull/48814) `[Feat] simulator: Add source-bound staged execution` | infra | ? | - |
| - | [#48819](https://github.com/sgl-project/sglang/issues/48819) `[Bug] SAIL/PPU memory capacity query incorrectly invokes nvidia-smi and warns about NVIDIA drivers` | nvidia | ? | - |
| P1 | [#48820](https://github.com/sgl-project/sglang/pull/48820) `[Feat] linker: Support async lookup in prefetch mode` | infra,perf | ? | - |
| - | [#48822](https://github.com/sgl-project/sglang/issues/48822) `[RFC] Add NPU RLHF Lifecycle Tests` |  | ? | - |
| - | [#48823](https://github.com/sgl-project/sglang/pull/48823) `[Feat] linker: Support lmcache external linker` | perf | ? | - |
| P1 | [#48824](https://github.com/sgl-project/sglang/pull/48824) `[Fix] dp-attention: Preserve original forward mode in prefill graph replay` | bug | ? | - |
| - | [#48825](https://github.com/sgl-project/sglang/pull/48825) `[Fix] [SAIL] utils: Use device properties for memory capacity` | bug | ? | - |
| - | [#48826](https://github.com/sgl-project/sglang/pull/48826) `[Feat] speculative: Report completed adaptive round execution by tier` |  | ? | - |
| - | [#48834](https://github.com/sgl-project/sglang/pull/48834) `[Fix] grpc: preserve Prometheus metric names` | bug | ? | - |
| - | [#48835](https://github.com/sgl-project/sglang/pull/48835) `[Fix] [NPU] eplb: Preserve expert storage and reuse TP communication` | bug | ? | - |
| - | [#48836](https://github.com/sgl-project/sglang/pull/48836) `[Fix] [SAIL] utils: Query device memory without nvidia-smi` | bug,nvidia | ? | - |
| - | [#48837](https://github.com/sgl-project/sglang/issues/48837) `[Bug] PD decode server fails to start with CUDA OOM on hybrid mamba models: mamba memory budget ignores decode` | nvidia | ? | - |
| P1 | [#48838](https://github.com/sgl-project/sglang/pull/48838) `[Fix] mem_cache: charge PD decode pre-allocated slots in the mamba memory budget` | bug,infra | ? | - |
| - | [#48842](https://github.com/sgl-project/sglang/pull/48842) `[Feat] dflash: Support sliding-window draft KV pools for NIXL PD` |  | ? | - |
| - | [#48843](https://github.com/sgl-project/sglang/pull/48843) `[Fix] distributed: Isolate local SHM writer ports by rank` | bug | ? | - |
| - | [#48845](https://github.com/sgl-project/sglang/pull/48845) `[Fix] sgl-model-gateway: Preserve cache_salt on chat completions` | bug | ? | - |
| - | [#48847](https://github.com/sgl-project/sglang/pull/48847) `[Perf] [XPU] graph: Support full prefill graph for GDN/Mamba and Gemma models` | nvidia,perf | ? | - |
| P1 | [#48848](https://github.com/sgl-project/sglang/pull/48848) `[Fix] HiCache: Wait for decode prefetch before publishing prefix length` | bug | ? | - |
| - | [#48850](https://github.com/sgl-project/sglang/pull/48850) `[Fix] deepseek_v4: Capture decoder-tail graphs at startup, never on a step a DP rank skips` | bug | ? | - |
| - | [#48854](https://github.com/sgl-project/sglang/pull/48854) `[CI] [AMD] ci: Run 16 kernel tests per PR on AMD, as CUDA does` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#48855](https://github.com/sgl-project/sglang/pull/48855) `[Perf]cosmos3: Explore opt-in BF16 DiT CUDA Graphs` | nvidia,perf | ? | - |
| - | [#48858](https://github.com/sgl-project/sglang/pull/48858) `[Feat] simulator: Simulate prefill-decode disaggregation with modelled KV transfer` | infra | ? | - |
| - | [#48861](https://github.com/sgl-project/sglang/pull/48861) `[Perf] [CPU] graph: Move SWA index translation into Intel AMX attention kernels and prune masked prefix loads` | infra,perf | ? | - |
| P1 | [#48862](https://github.com/sgl-project/sglang/pull/48862) `[Fix] [AMD] all-reduce: Check quick reduce before custom AR so ROCM_QUICK_REDUCE_QUANTIZATION takes effect` | bug,infra,quant,rocm | ? | - |
| P1 | [#48863](https://github.com/sgl-project/sglang/pull/48863) `[Perf] [AMD] dsa: Use a spill-free BF16 tile for the triton sparse-MLA split-K decode on gfx950` | perf,rocm | ? | - |
| P1 | [#48864](https://github.com/sgl-project/sglang/pull/48864) `[Perf] [AMD] kda: Row-streamed chunked verify for ReplaySSM ring mode on gfx950` | perf,rocm | ? | - |
| P1 | [#48865](https://github.com/sgl-project/sglang/pull/48865) `[Perf] [AMD] deepseek-v4.1: Reuse the low-ratio identity extend fill across the layers of a ratio` | infra,perf,rocm | ? | - |
| P1 | [#48866](https://github.com/sgl-project/sglang/pull/48866) `[Perf] [AMD] deepseek-v4: Fill a run of identity prefill requests in one batched write` | infra,perf,rocm | ? | - |
| - | [#48870](https://github.com/sgl-project/sglang/pull/48870) `[Perf] utils: Avoid per-element list allocation in flatten_hidden for flat float rows` | perf | ? | - |
| P1 | [#48872](https://github.com/sgl-project/sglang/pull/48872) `[Fix] disaggregation: Make the KV checksum digest each state component's own transfer payload` | bug | ? | - |
| - | [#48874](https://github.com/sgl-project/sglang/pull/48874) `[Fix] [NPU] mooncake: Pair DSV4 and MLA KV buffers by global layer ID` | bug,infra,nvidia,perf,quant,rocm | ? | - |
| P0 | [#48875](https://github.com/sgl-project/sglang/pull/48875) `[Fix] [AMD] GLM-5.3-Flash: Let breakable prefill graphs replay cached-prefix extends, with HIP KDA` | bug,infra,perf,rocm | main | - |
| - | [#48876](https://github.com/sgl-project/sglang/pull/48876) `[Perf] qwen2.5-vl: Avoid empty vision windows` | perf | ? | - |
| P1 | [#48878](https://github.com/sgl-project/sglang/pull/48878) `[Perf] [AMD] kimi-k3: Write the fp8-Q asm verify query in the fused Q/cache launch` | infra,perf,quant,rocm | ? | - |
| - | [#48881](https://github.com/sgl-project/sglang/pull/48881) `[Perf] multimodal: Avoid CPU thread-pool fanout in SHM copy` | perf | ? | - |
| - | [#48884](https://github.com/sgl-project/sglang/pull/48884) `[Fix] multimodal: Preserve processor options when splitting requests` | bug | ? | - |
| - | [#48887](https://github.com/sgl-project/sglang/pull/48887) `[Fix] sampling: Validate parallel sample counts before batch expansion` | bug | ? | - |
| - | [#48890](https://github.com/sgl-project/sglang/pull/48890) `[Feat] diffusion: Add LoRA merge mode disabled` | perf | ? | - |
| P1 | [#48893](https://github.com/sgl-project/sglang/pull/48893) `[Perf] [AMD] attention: fused prefix K and FP8 MLA prefill attention via ASM FMHA on gfx1250` | infra,perf,quant,rocm | ? | - |
| P1 | [#48897](https://github.com/sgl-project/sglang/pull/48897) `[Perf] [AMD] aiter: Opt unified verify out of the host seq_lens mirror for spec-v2 overlap` | perf,rocm | ? | - |
| - | [#48898](https://github.com/sgl-project/sglang/pull/48898) `[Feat] [NVIDIA] DSA: Add FlashInfer GVR V2 top-k backend` | nvidia,perf | ? | - |
| - | [#48899](https://github.com/sgl-project/sglang/pull/48899) `[Feat] hisparse: support DFLASH speculative decoding` | infra | ? | - |
| P1 | [#48900](https://github.com/sgl-project/sglang/pull/48900) `[Feat] quantization: Route named layers to a second online quantization format` | perf,quant | ? | - |
| P1 | [#48901](https://github.com/sgl-project/sglang/pull/48901) `[Fix] speculative: Preserve repetition penalties in DFLASH and DSPARK` | bug | ? | - |
| P0 | [#48904](https://github.com/sgl-project/sglang/issues/48904) `[Bug] Qwen3, Qwen3-VL, Qwen3-VL-MoE, Qwen3-Omni-MoE, Qwen3-ASR and Qwen3 rerankers ignore checkpoint FP8 KV-ca` | perf,quant | ? | - |
| - | [#48906](https://github.com/sgl-project/sglang/issues/48906) `[Bug] NVFP4 Marlin path (default on SM80-SM90) decodes E4M3 subnormal block scales as 0 with bfloat16 activati` | nvidia,quant | ? | - |
| - | [#48907](https://github.com/sgl-project/sglang/pull/48907) `[Fix] marlin: Decode E4M3 subnormal NVFP4 block scales exactly with bfloat16 activations` | bug,nvidia,perf,quant | ? | - |
| - | [#48908](https://github.com/sgl-project/sglang/pull/48908) `[Perf] [NVIDIA] deepseek_v4: Token-shard SM90 sparse-MLA prefill under attention TP` | nvidia,perf | ? | - |
| - | [#48909](https://github.com/sgl-project/sglang/pull/48909) `[Feat] [Ascend] Add A3 MegaMoE support for SwiGLU/SiTU and BF16/INT experts` |  | ? | - |
| - | [#48910](https://github.com/sgl-project/sglang/pull/48910) `[Perf] [XPU] minimax-h3: Use bit-exact fused XPU kernels in the DiT` | nvidia,perf | ? | - |
| P1 | [#48911](https://github.com/sgl-project/sglang/issues/48911) `[Bug] More model loaders drop checkpoint FP8 KV-cache scales (Qwen1.5/2-MoE, Qwen2.5-VL, Qwen3-Next, AFMoE, Ge` | perf,quant | ? | - |
| P1 | [#48912](https://github.com/sgl-project/sglang/pull/48912) `[Fix] models: map checkpoint KV-cache scale names in more model loaders` | bug,perf,quant | ? | - |
| P1 | [#48913](https://github.com/sgl-project/sglang/issues/48913) `[Bug] Gemma 4 and Gemma 3n KV-shared layers read the FP8 KV cache with scale 1.0 instead of the writing layer'` | perf,quant | ? | - |
| P1 | [#48914](https://github.com/sgl-project/sglang/pull/48914) `[Fix] gemma: KV-shared layers use the KV-cache scales of the layer whose cache they read` | bug,perf,quant | ? | - |
| P1 | [#48915](https://github.com/sgl-project/sglang/pull/48915) `[Fix] spec: load FP8 KV-cache scales in the DFlash and LLaMA EAGLE-3 draft loaders` | bug,perf,quant | ? | - |
| P1 | [#48916](https://github.com/sgl-project/sglang/pull/48916) `[Fix] parser: split reasoning on last think end token` | bug | ? | - |
| - | [#48917](https://github.com/sgl-project/sglang/issues/48917) `[Bug] TorchNativeLlamaForCausalLM / TorchNativePhi3ForCausalLM load no checkpoint tensors and no KV-cache scal` | perf,quant | ? | - |
| - | [#48918](https://github.com/sgl-project/sglang/pull/48918) `[Fix] torch_native_llama: load checkpoint tensors and KV-cache scales` | bug,perf,quant | ? | - |
| - | [#48919](https://github.com/sgl-project/sglang/issues/48919) `[Bug] NVFP4 W4A4 linear keeps the largest weight global scale of fused q/k/v and gate/up layers without a chec` | perf,quant | ? | - |
| - | [#48920](https://github.com/sgl-project/sglang/pull/48920) `[Fix] quantization: Apply each fused projection's own NVFP4 global scale in linear layers` | bug,nvidia,perf,quant | ? | - |
| - | [#48921](https://github.com/sgl-project/sglang/pull/48921) `[Perf] mlp: Extend dense SwiGLU/block-FP8 quant fusion to SM90, prefill and TP>1` | nvidia,perf,quant | ? | - |
| - | [#48922](https://github.com/sgl-project/sglang/issues/48922) `[Bug] SM120 DeepSeek-V4.1: low-ratio indexer decode dies with schedule_meta=None (fp8_fp4_paged_mqa_logits arg` | nvidia | ? | - |
| - | [#48923](https://github.com/sgl-project/sglang/pull/48923) `[Feat] [Ascend] Integrate A5 MXFP experts with MegaMoE` |  | ? | - |
| - | [#48925](https://github.com/sgl-project/sglang/pull/48925) `[Fix] dp-attention: Take single-node control-plane ports from a free block` | bug | ? | - |
| - | [#48926](https://github.com/sgl-project/sglang/pull/48926) `[Feat] dsv41: FP8 MegaAttention prefill workspace for DeepSeek-V4.1-Flash` | perf,quant | ? | - |
| - | [#48927](https://github.com/sgl-project/sglang/pull/48927) `[Fix] cpu: Cap default OpenMP thread binding by the cgroup CPU quota` | bug | ? | - |
| - | [#48929](https://github.com/sgl-project/sglang/pull/48929) `[Perf] hicache_nixl: vectorize strided page-offset extraction across v1 and v2 paths` | perf | ? | - |
| - | [#48930](https://github.com/sgl-project/sglang/issues/48930) `[Bug] NVFP4 MoE: the Marlin backend applies the gate's global scale to the up projection` | quant | ? | - |
| - | [#48931](https://github.com/sgl-project/sglang/pull/48931) `[Fix] marlin: Apply the up projection's own global scale in NVFP4 MoE` | bug,quant | ? | - |
| - | [#48932](https://github.com/sgl-project/sglang/pull/48932) `[Feat] [Apple] mps: Size the Unlimited-OCR v2 KV pool in document windows and add an opt-in warmup` | infra,perf | ? | - |
| - | [#48933](https://github.com/sgl-project/sglang/pull/48933) `[Perf] [Apple] mps: Encode and prefill the next Unlimited-OCR v2 window under the current decode` | perf | ? | - |
| - | [#48937](https://github.com/sgl-project/sglang/pull/48937) `[Feat] sgl-router: Route DeepSeek image chats by prefix cache` | perf | ? | - |
| - | [#48939](https://github.com/sgl-project/sglang/pull/48939) `[Perf] radix_cache: Reuse the eviction heap across calls` | perf | ? | - |
| - | [#48940](https://github.com/sgl-project/sglang/pull/48940) `[Fix] sgl-router: Honor --cache-pending-prefix-consult-below under reorg routing` | bug,perf | ? | - |
| - | [#48943](https://github.com/sgl-project/sglang/pull/48943) `[Feat] nemotron_labs_diffusion: Add AR and block-diffusion support` | infra,perf | ? | - |
| - | [#48944](https://github.com/sgl-project/sglang/issues/48944) `[CI] cuda: uv pip install -e times out waiting for the shared uv editable-build lock` | infra,nvidia | ? | - |
| - | [#48945](https://github.com/sgl-project/sglang/pull/48945) `[Feat] hicache: Allow dynamic storage backends that support DCP` |  | ? | - |
| - | [#48948](https://github.com/sgl-project/sglang/pull/48948) `[Perf] dflash: Side-stream context projection and a one-kernel verify commit` | perf | ? | - |
| - | [#48954](https://github.com/sgl-project/sglang/pull/48954) `[Feat] multimodal: Let a token-space strategy load its own media and choose its image decoder and RGB conversi` | infra | ? | - |
| - | [#48961](https://github.com/sgl-project/sglang/pull/48961) `[Perf] [NVIDIA] dsv41: run MegaAttention's wo_a on FlashInfer's SM107 batched MXFP8 GEMM` | nvidia,perf,quant | ? | - |
| - | [#48963](https://github.com/sgl-project/sglang/issues/48963) `[Feature] Share a prompt's KV among requests admitted in the same prefill batch` |  | ? | - |
| - | [#48964](https://github.com/sgl-project/sglang/issues/48964) `[Bug] GLM-5.3-Flash: engine state corrupted after a 1M-token request on v0.5.23 (MTP accept rate 0.00, all sub` | risk | ? | - |
| - | [#48965](https://github.com/sgl-project/sglang/pull/48965) `[Fix] gemma4: Fix infinite loop in tool-call array parser` | bug,infra | ? | - |
| - | [#48967](https://github.com/sgl-project/sglang/issues/48967) `[Bug] [AMD] decode attention: MLA-shaped Triton decode returns NaN / wrong rows on ragged batches (gfx1151)` | bug,risk,rocm | ? | - |
| - | [#48968](https://github.com/sgl-project/sglang/issues/48968) `[Bug] [AMD] --enable-deterministic-inference fails at startup on RDNA: batch-invariant matmul needs 99 KB LDS ` | rocm | ? | - |
| - | [#48969](https://github.com/sgl-project/sglang/pull/48969) `[Perf] [AMD] decode-attention: Skip the CDNA launch hints on RDNA3/3.5/4 for GQA decode` | perf,rocm | ? | - |
| - | [#48970](https://github.com/sgl-project/sglang/pull/48970) `[Fix] function_call: support Python reserved keywords as parameter names in PythonicDetector` | bug | ? | - |
| - | [#48972](https://github.com/sgl-project/sglang/pull/48972) `[Fix] quantization: [sglang-miles] FP4-dequantized MoE experts report their 128x128 blocks to the runners` | bug,quant | ? | - |
| - | [#48973](https://github.com/sgl-project/sglang/pull/48973) `[Fix] moe: [sglang-miles] DeepGEMM masked activation quant takes any group count with FP32 scales` | bug,quant | ? | - |
| - | [#48975](https://github.com/sgl-project/sglang/pull/48975) `[Chore] dspark: [sglang-miles] Backport the per-architecture DSpark DP a2a allowlist from main (#48547)` |  | ? | - |
| - | [#48976](https://github.com/sgl-project/sglang/pull/48976) `[Feat] deepseek_v4: [sglang-miles] DSpark over DeepEP under attention DP` | nvidia | ? | - |
| - | [#48981](https://github.com/sgl-project/sglang/pull/48981) `[Fix] io_struct: Preserve video_config when slicing requests` | bug | ? | - |
| - | [#48985](https://github.com/sgl-project/sglang/pull/48985) `[Fix] health_check: Require completed inference for /health_generate, not any scheduler message` | bug | ? | - |
| - | [#48987](https://github.com/sgl-project/sglang/pull/48987) `[Fix] [AMD] decode-attention: Use two pipeline stages for MLA decode on RDNA3.5 (gfx115x)` | bug,perf,rocm | ? | - |
| - | [#48989](https://github.com/sgl-project/sglang/pull/48989) `[Fix] constrained: make json_schema_validation subschema traversal deterministic and skip boolean no-op recurs` | bug | ? | - |
| - | [#49002](https://github.com/sgl-project/sglang/pull/49002) `[Fix] pplx: Import the FP8 group quantizer from sglang.kernels` | bug,perf,quant | ? | - |
| - | [#49005](https://github.com/sgl-project/sglang/pull/49005) `Add DeepSeek V4.1 NPU support and align with upstream changes` | bug,perf | ? | - |
| - | [#49007](https://github.com/sgl-project/sglang/pull/49007) `[Fix] model_loader: Load checkpoint weights for every module in layered mode` | bug | ? | - |
| - | [#49010](https://github.com/sgl-project/sglang/pull/49010) `[Fix] diffusion: Read encoder folding dims from a nested text_config` | bug,perf | ? | - |
| - | [#49011](https://github.com/sgl-project/sglang/pull/49011) `[Perf] diffusion: Keep a folded Gemma-4 encoder's vocab table on the host` | perf | ? | - |
| - | [#49012](https://github.com/sgl-project/sglang/pull/49012) `[Perf] [NVIDIA] diffusion: Exchange Q/K/V as E4M3 under Ulysses with fp8_fa_sm120` | bug,nvidia,perf,quant | ? | - |
| - | [#49013](https://github.com/sgl-project/sglang/pull/49013) `[Fix] model_loader: Support BF16 weights in NumPy cache` | bug,perf | ? | - |
| - | [#49014](https://github.com/sgl-project/sglang/pull/49014) `[Feat] nemotron_labs_diffusion: Add self-speculative decoding` | perf | ? | - |
| - | [#49015](https://github.com/sgl-project/sglang/pull/49015) `[Fix] [NVIDIA] blackwell: Keep SM120 off kernels that ship for SM100 only` | bug,nvidia,perf | ? | - |
| - | [#49025](https://github.com/sgl-project/sglang/pull/49025) `[Perf] Hunyuan3D: Speed up QEM mesh decimation (Lossless)` | perf | ? | - |
| - | [#49027](https://github.com/sgl-project/sglang/pull/49027) `[Spec][XPU]Dspark compact mode with sps cost table support added` | nvidia,perf | ? | - |
| - | [#49029](https://github.com/sgl-project/sglang/pull/49029) `[Fix] [NPU] mem_cache: Fall back to pageable KV backups on pinned host OOM` | bug,infra | ? | - |
| - | [#49031](https://github.com/sgl-project/sglang/pull/49031) `[Fix] [NPU] disaggregation: Preserve MLA KV layer mapping across PP stages` | bug | ? | - |
| - | [#49033](https://github.com/sgl-project/sglang/pull/49033) `[Perf] diffusion: load MiniMax H3 reference VAEs on demand` | perf | ? | - |
| - | [#49035](https://github.com/sgl-project/sglang/pull/49035) `[Refactor] hicache: Key DCP L3 pages by `logical_page_size`` |  | ? | - |
| - | [#49036](https://github.com/sgl-project/sglang/pull/49036) `[Perf] [AMD] GLM5.3: Run KDA decode and HIP prefill on a BF16 state pool on gfx950` | infra,perf,rocm | ? | - |
| - | [#49042](https://github.com/sgl-project/sglang/pull/49042) `[Fix] linker: Offload Mamba branch checkpoints on stored nodes` | bug,perf | ? | - |
| - | [#49044](https://github.com/sgl-project/sglang/pull/49044) `[Fix] attention: Fence SM120 attention K/V shared-memory reads before buffer reuse` | bug,nvidia,perf | ? | - |
| - | [#49045](https://github.com/sgl-project/sglang/pull/49045) `[Feat] benchmark: add synthetic audio input to serving benchmark` | perf | ? | - |
| - | [#49046](https://github.com/sgl-project/sglang/pull/49046) `[Fix] attention: Account for allocator cache in MQA logits budgets` | bug,perf | ? | - |
| - | [#49047](https://github.com/sgl-project/sglang/pull/49047) `[Doc] sampling: Clarify CUDA greedy ties and LM-head output precision` | nvidia | ? | - |
| - | [#49049](https://github.com/sgl-project/sglang/pull/49049) `fix(scheduler): abort overlong embedding requests` | bug | ? | - |
| - | [#49050](https://github.com/sgl-project/sglang/pull/49050) `[Fix] utils: Keep next_power_of_2 callable from Triton JIT kernels (#48460)` | bug,perf,rocm | ? | - |
| - | [#49052](https://github.com/sgl-project/sglang/pull/49052) `[Test] tokenizer: cover multimodal embedding cleanup` |  | ? | - |
| - | [#49055](https://github.com/sgl-project/sglang/issues/49055) `[Performance][Non-blocking] Rust server stack #48815 follow-ups` | perf | ? | - |
| - | [#49056](https://github.com/sgl-project/sglang/pull/49056) `[Perf] debug_utils: Track token budget and shared groups incrementally in FIFOScheduler` | perf | ? | - |
| - | [#49057](https://github.com/sgl-project/sglang/pull/49057) `[Fix] benchmark: Honor max_completion_tokens in OpenAI datasets` | bug,perf | ? | - |
| - | [#49058](https://github.com/sgl-project/sglang/pull/49058) `[Fix] cache: Support standard MiniMax sparse pools in direct linker` | bug,perf | ? | - |
| - | [#49059](https://github.com/sgl-project/sglang/pull/49059) `[Fix] mem_cache: Grow the auto-fit Mamba state cache to honor an explicit --max-running-requests` | bug,perf | ? | - |
| - | [#49060](https://github.com/sgl-project/sglang/pull/49060) `[Fix] rust-server: Reject Rust-only punctuation in stop regex capture names` | bug | ? | - |
| - | [#49061](https://github.com/sgl-project/sglang/issues/49061) `[Bug] Gemma 3 and Mistral 3 build ignored vision layers quantized: the quantization ignore list is not renamed` | infra,quant | ? | - |
| - | [#49062](https://github.com/sgl-project/sglang/pull/49062) `[Fix] gemma3/mistral3: Match vision layers in quantization ignore lists` | bug,quant | ? | - |
| - | [#49063](https://github.com/sgl-project/sglang/pull/49063) `[Feat] hicache: Re-back up hit host prefixes missing from L3 storage` | perf | ? | - |
| - | [#49064](https://github.com/sgl-project/sglang/pull/49064) `[Feat] hicache: Expose host-tier occupancy and write-back blocking metrics` | perf | ? | - |
| - | [#49065](https://github.com/sgl-project/sglang/issues/49065) `[Bug] ComfyUI SGLD loader: Fun ControlNet on Qwen-Image 2.1 fails with AttributeError` |  | ? | - |
| - | [#49068](https://github.com/sgl-project/sglang/pull/49068) `[Perf] dsv41-flash: Reuse paged Indexer key tiles during verification` | infra,perf | ? | - |
| - | [#49069](https://github.com/sgl-project/sglang/pull/49069) `[Perf] dsv41-flash: Fuse Hopper prefill candidate selection and writeback` | infra,nvidia,perf | ? | - |
| - | [#49070](https://github.com/sgl-project/sglang/pull/49070) `[Fix] disaggregation: Keep a decode request without bootstrap_host from crashing the scheduler` | bug | ? | - |
| - | [#49072](https://github.com/sgl-project/sglang/pull/49072) `[Feat] cache: Support plain MHA direct-linker views` | perf | ? | - |
| - | [#49073](https://github.com/sgl-project/sglang/pull/49073) `[Feat] dLLM: Add HierarchyBlock decoding for Fast-dVLM (text, radix cache on)` | perf | ? | - |
| - | [#49074](https://github.com/sgl-project/sglang/pull/49074) `[Fix] lmcache: wait for pending loads before ending sessions` | bug,perf | ? | - |
| - | [#49075](https://github.com/sgl-project/sglang/pull/49075) `[Fix] PD: Retain Mooncake buffers until transfer drain` | bug | ? | - |
| - | [#49076](https://github.com/sgl-project/sglang/pull/49076) `[Feat] attention: Support sparse query positions in FlashInfer prefill` | nvidia | ? | - |
| - | [#49077](https://github.com/sgl-project/sglang/pull/49077) `[Fix] mooncake: Support Ascend Direct endpoint naming` | bug | ? | - |
| - | [#49079](https://github.com/sgl-project/sglang/pull/49079) `[Fix] kt: Pass the layer's SwiGLU clamp and SwiGLU-OAI to the CPU experts` | bug | ? | - |
| - | [#49080](https://github.com/sgl-project/sglang/pull/49080) `[Perf] diffusion: Extend NVENC video encoding to Wan2.1, LTX-2, SANA-WM, and MiniMax-H3` | infra,perf | ? | - |
| - | [#49082](https://github.com/sgl-project/sglang/pull/49082) `[Perf] [NVIDIA] kda: Use 8-row value tiles for the FP32-state packed decode on SM90 and SM10x` | nvidia,perf | ? | - |
| - | [#49083](https://github.com/sgl-project/sglang/pull/49083) `[Fix] mooncake: Use native shared memory registrations for PD and Store` | bug,infra | ? | - |
| - | [#49084](https://github.com/sgl-project/sglang/pull/49084) `[Perf] rust-server: Bound log-string truncation to the kept prefix and suffix` | perf,risk | ? | - |
| - | [#49085](https://github.com/sgl-project/sglang/pull/49085) `[Perf] kv_canary: Batch active slot D2H transfer and SWA LUT translation in KV canary perturb` | perf | ? | - |
| - | [#49090](https://github.com/sgl-project/sglang/pull/49090) `[Doc] cookbook: Correct the GLM-5.3-Flash note on prefill CP with PD disaggregation` |  | ? | - |
| - | [#49094](https://github.com/sgl-project/sglang/pull/49094) `[Fix] dspark: Forward target capture outputs from verification` | bug,infra | ? | - |
| - | [#49095](https://github.com/sgl-project/sglang/pull/49095) `[Perf] SANA: dispatch strided fused LayerNorm` | perf | ? | - |
| - | [#49098](https://github.com/sgl-project/sglang/pull/49098) `[Perf] [NVIDIA] dsa: Run FlashInfer's fused SM120 indexer for DSA top-k` | nvidia,perf | ? | - |
| - | [#49099](https://github.com/sgl-project/sglang/pull/49099) `[Perf] DeepSeek-V4.1: pack multi-image ViT encoding` | perf | ? | - |
| - | [#49100](https://github.com/sgl-project/sglang/pull/49100) `[Perf] kimi-k3.1: Sequence-parallel layer tail for large eager prefill batches` | perf | ? | - |
| - | [#49103](https://github.com/sgl-project/sglang/pull/49103) `[Fix] [PD] Allow bounded backfill past KV-blocked decode requests` | bug | ? | - |
| - | [#49104](https://github.com/sgl-project/sglang/pull/49104) `[Fix] lang: Avoid mutating StreamExecutor.messages_ in Anthropic backend and pop(0) loop in VertexAI` | bug | ? | - |
| - | [#49107](https://github.com/sgl-project/sglang/pull/49107) `[Fix] function_call: stream multiple DeepSeek V3.1 tool calls correctly` | bug | ? | - |
| - | [#49108](https://github.com/sgl-project/sglang/issues/49108) `[Bug] Rust extension loader: cargo --version probe can deadlock in launcher spawn context (defensive timeout s` | risk | ? | - |
| - | [#49109](https://github.com/sgl-project/sglang/pull/49109) `[Fix] glm47: Keep string-typed tool-call argument values verbatim` | bug | ? | - |
| - | [#49111](https://github.com/sgl-project/sglang/pull/49111) `[Feat] server: Allow cache flushes to retain allocator memory` | perf | ? | - |
| P1 | [#49113](https://github.com/sgl-project/sglang/pull/49113) `[Fix] [AMD] dsv4: Read preshuffled indexer keys in TileLang` | bug,perf,rocm | ? | - |
| - | [#49114](https://github.com/sgl-project/sglang/pull/49114) `[Fix] model_runner: Cast input_embeds to the model dtype` | bug,infra | ? | - |
| - | [#49115](https://github.com/sgl-project/sglang/issues/49115) `[Bug] Kimi-K3.1-Pro: PP output relay stalls while pickling nested tensor metadata` |  | ? | - |
| - | [#49116](https://github.com/sgl-project/sglang/pull/49116) `[Fix] pp: Materialize nested output metadata before serialization` | bug | ? | - |
| - | [#49117](https://github.com/sgl-project/sglang/pull/49117) `[Perf] [NPU] attention: reuse eager sparse KV lengths across layers` | perf | ? | - |
| - | [#49119](https://github.com/sgl-project/sglang/pull/49119) `[Feat] engine: Accept positional_embed_overrides on generate and async_generate` | infra | ? | - |
| - | [#49120](https://github.com/sgl-project/sglang/pull/49120) `[Feat] EPD: per-item encoder prefix cache for batched multimodal requests` | perf | ? | - |
| - | [#49122](https://github.com/sgl-project/sglang/pull/49122) `[Perf] [NVIDIA] kda: Skip the row-streaming packed decode kernel on SM90 and SM10x` | nvidia,perf | ? | - |
| - | [#49123](https://github.com/sgl-project/sglang/issues/49123) `[Feature] moe: FlashInfer cuTile NVFP4 MoE as the default runner on SM12x` | nvidia,quant | ? | - |
| - | [#49124](https://github.com/sgl-project/sglang/pull/49124) `[Perf] [AMD] extend-attention: Use 8 warps for head_dim 256 prefill on RDNA3.5 (gfx115x)` | perf,rocm | ? | - |
| - | [#49125](https://github.com/sgl-project/sglang/pull/49125) `[Perf] [NVIDIA] attention: Skip unused V4 FlashMLA schedule preparation` | nvidia,perf | ? | - |
| - | [#49127](https://github.com/sgl-project/sglang/pull/49127) `[Feat] linker: Expose external cache linker lookup, load, offload and wait metrics` | infra,perf | ? | - |
| - | [#49129](https://github.com/sgl-project/sglang/issues/49129) `[Bug] macOS: /v1/loads returns no ranks because load snapshots use /dev/shm` |  | ? | - |
| - | [#49130](https://github.com/sgl-project/sglang/pull/49130) `[Fix] [Apple] load-snapshots: Use an available mmap directory on macOS` | bug | ? | - |
| - | [#49131](https://github.com/sgl-project/sglang/pull/49131) `[Fix] disaggregation: propagate Mooncake memory registration failures` | bug | ? | - |
| - | [#49132](https://github.com/sgl-project/sglang/issues/49132) `[Bug] Qwen3-VL vision encoder: full-size transient tensors (pos-embed blend `[4, patches, 1152]`, MLP `[patche` |  | ? | - |
| - | [#49133](https://github.com/sgl-project/sglang/issues/49133) `[Bug] Breakable prefill CUDA graph: short prefills padded to a capture bucket give different logprobs than eag` | nvidia,quant | ? | - |
| - | [#49134](https://github.com/sgl-project/sglang/pull/49134) `[Fix] multimodal: Decode images on CPU when the PIL image processor is used` | bug | ? | - |
| - | [#49136](https://github.com/sgl-project/sglang/pull/49136) `[Fix] utils: Match the CUDA driver's default coredump pipe name` | bug,nvidia | ? | - |
| - | [#49137](https://github.com/sgl-project/sglang/pull/49137) `[Fix] sgl-router: Refuse --route-by-uncached-tokens under reorg routing` | bug,perf | ? | - |
| - | [#49140](https://github.com/sgl-project/sglang/pull/49140) `[Feat] observability: report token usage on the request span under the current GenAI conventions` |  | ? | - |
| - | [#49141](https://github.com/sgl-project/sglang/pull/49141) `[Fix] mamba: Keep the decode-track ping-pong parity under overlap interleavings` | bug,perf | ? | - |
| - | [#49142](https://github.com/sgl-project/sglang/pull/49142) `[Feat] bailing: Add option to disable router gate matvec` |  | ? | - |
| - | [#49145](https://github.com/sgl-project/sglang/issues/49145) `[Bug] d3 decision checkpoints: the readout load erases the embedding matrix` |  | ? | - |
| - | [#49146](https://github.com/sgl-project/sglang/pull/49146) `[Fix] d3: Keep the decision readout out of the embedding matrix` | bug | ? | - |
| - | [#49147](https://github.com/sgl-project/sglang/pull/49147) `[Perf] scheduler: Defer duplicate prompts until KV checkpoint` | perf | ? | - |
| - | [#49148](https://github.com/sgl-project/sglang/pull/49148) `[Feat] scheduler: Expose single-iteration API` |  | ? | - |
| - | [#49150](https://github.com/sgl-project/sglang/pull/49150) `[Fix] utils: Fix info_once message deduplication, is_same_type symmetry, and trim_overlap slicing` | bug | ? | - |
| - | [#49158](https://github.com/sgl-project/sglang/pull/49158) `[Fix] hicache: Keep write-back admission from promising device KV that eviction cannot free` | bug,infra,perf | ? | - |
| - | [#49161](https://github.com/sgl-project/sglang/pull/49161) `[Perf] dsa: Enable K-only short prefill with PCP` | perf | ? | - |
| - | [#49164](https://github.com/sgl-project/sglang/pull/49164) `[Test] mem_cache: Skip DSA indexer sharding test below SM 8.9` |  | ? | - |
| - | [#49165](https://github.com/sgl-project/sglang/pull/49165) `[Feat] [Intel] monokernel: --enable-xpu-monokernel, the Intel XPU backend of the monokernel binding` | nvidia,perf | ? | - |
| - | [#49167](https://github.com/sgl-project/sglang/pull/49167) `[Doc] [NPU] cookbook: Add Ascend A3 deployment scenarios for DeepSeek-v3.2` |  | ? | - |
| - | [#49168](https://github.com/sgl-project/sglang/pull/49168) `[Fix] mamba: Preserve completed checkpoints across overlap gaps` | bug,perf | ? | - |
| - | [#49169](https://github.com/sgl-project/sglang/pull/49169) `[Fix] benchmark: reject a range ratio outside [0, 1]` | bug,perf | ? | - |
| - | [#49174](https://github.com/sgl-project/sglang/issues/49174) `Post-hoc Req.finished_len mutation desyncs pool accounting — invariant checker fires with negative residue (un` |  | ? | - |
| - | [#49175](https://github.com/sgl-project/sglang/issues/49175) `[Bug] Non-positive n (n=0 or negative) crashes batch /generate with IndexError instead of a 400` | bug | ? | - |
| - | [#49176](https://github.com/sgl-project/sglang/pull/49176) `[Fix] io_struct: Reject non-positive parallel sampling count n in request normalization` | bug | ? | - |
| - | [#49177](https://github.com/sgl-project/sglang/pull/49177) `[Feat] [NPU] quant: Serve serialized block-FP8 MoE weights as MXFP8 on Ascend A5` | quant | ? | - |
| - | [#49179](https://github.com/sgl-project/sglang/pull/49179) `[Fix] [NPU] attention: Run page_size<16 models on the reference attention path` | bug | ? | - |
| - | [#49181](https://github.com/sgl-project/sglang/pull/49181) `[Fix] docker: Exclude nested Python bytecode from Docker contexts` | bug,infra | ? | - |
| - | [#49183](https://github.com/sgl-project/sglang/pull/49183) `[Feat] hicache: Add an independent draft host memory budget` |  | ? | - |
| - | [#49184](https://github.com/sgl-project/sglang/pull/49184) `[Perf] sparsity: Vectorize BaseSparseAlgorithmImpl.retrieve_topk across active requests` | perf | ? | - |
| - | [#49185](https://github.com/sgl-project/sglang/issues/49185) `[Bug] Qwen3-MoE: a router stored quantized (compressed-tensors) is never loaded, and the server answers garbag` | quant,risk | ? | - |
| - | [#49186](https://github.com/sgl-project/sglang/issues/49186) `[Bug] Whisper: fc1/fc2 are built without the quantization config, so a quantized checkpoint transcribes nothin` | quant | ? | - |
| - | [#49187](https://github.com/sgl-project/sglang/pull/49187) `[Fix] qwen3_moe/mixtral/llama4: Build the MoE router as the checkpoint stores it` | bug,infra,quant | ? | - |
| - | [#49188](https://github.com/sgl-project/sglang/pull/49188) `[Fix] whisper: Build fc1 and fc2 with the quantization config` | bug,infra,quant | ? | - |
| - | [#49190](https://github.com/sgl-project/sglang/issues/49190) `[Rust server] Tokenization runs on a single thread by default and becomes the tail-latency bottleneck for long` | perf | ? | - |
| - | [#49191](https://github.com/sgl-project/sglang/pull/49191) `[Feat] memory: preserve partial-rollout KV across CPU offload` |  | ? | - |
| - | [#49193](https://github.com/sgl-project/sglang/pull/49193) `[Perf] rust-server: Size the tokenizer pool from the frontend cores` | perf | ? | - |
| - | [#49194](https://github.com/sgl-project/sglang/pull/49194) `[Doc] hicache: Add recipe for attributing cache misses and HiCache restores via --kv-events-config` | perf | ? | - |
| - | [#49196](https://github.com/sgl-project/sglang/pull/49196) `K31 sm90 fixes` | infra,nvidia,perf,quant | ? | - |
| - | [#49197](https://github.com/sgl-project/sglang/pull/49197) `[Perf] [NVIDIA] minimax-sparse: Gather the decode indexer CP queries and candidates with multimem on Hopper` | nvidia,perf | ? | - |
| - | [#49198](https://github.com/sgl-project/sglang/issues/49198) `[Bug] Mixtral, Llama 4 and FP8 Qwen3-MoE: a router stored in FP8 is loaded without its scale, with no error` | quant | ? | - |
| - | [#49199](https://github.com/sgl-project/sglang/issues/49199) `[Bug] DFlash and EAGLE-3 drafts build their layers without layer names, so a draft's quantization exclusions n` | infra,quant | ? | - |
| - | [#49202](https://github.com/sgl-project/sglang/issues/49202) `[Bug] TorchNativeLlamaForCausalLM / TorchNativePhi3ForCausalLM build plain torch.nn.Linear layers, so a quanti` | infra,quant | ? | - |
| - | [#49203](https://github.com/sgl-project/sglang/pull/49203) `[Perf] Qwen4-Exp: default --boundary-reduction to reduce-scatter under DP attention` | perf | ? | - |
| - | [#49206](https://github.com/sgl-project/sglang/issues/49206) `[Bug] SGLANG_ENABLE_NV_MEGA_RUNTIME_OPTIMIZATION: post-verify CUDA graph capture crashes on first sampled requ` | bug,nvidia,perf | ? | - |
| - | [#49208](https://github.com/sgl-project/sglang/pull/49208) `[Fix] io_struct: Fix `/generate` Http Native API behavior for the requests passing empty list element in `inpu` | bug | ? | - |
| - | [#49209](https://github.com/sgl-project/sglang/issues/49209) `[Bug] sm_120 (RTX 50-series consumer Blackwell) cannot run any model out-of-the-box with CUDA 13 wheel install` | nvidia | ? | - |
| - | [#49210](https://github.com/sgl-project/sglang/pull/49210) `[Chore] ci: Update test est_time values` | infra,nvidia,perf,quant,rocm | ? | - |
| - | [#49211](https://github.com/sgl-project/sglang/pull/49211) `[Feat] gemma4-diffusion: Support quantized checkpoints (FP8 and NVFP4)` | perf,quant | ? | - |
| - | [#49212](https://github.com/sgl-project/sglang/pull/49212) `[Fix] dflash/eagle3: Build draft layers under their checkpoint names` | bug,infra,quant | ? | - |
| - | [#49213](https://github.com/sgl-project/sglang/pull/49213) `[Fix] ollama: Normalize Ollama options and propagate length done_reason in OllamaServing` | bug | ? | - |
| - | [#49214](https://github.com/sgl-project/sglang/pull/49214) `[Feat] [MLU] attention: Add GQA and MLA support` | infra,perf | ? | - |
| - | [#49215](https://github.com/sgl-project/sglang/pull/49215) `[Fix] Qwen3-VL: chunk position embedding interpolation for large images` | bug | ? | - |
| - | [#49216](https://github.com/sgl-project/sglang/pull/49216) `[Fix] muse-spark: Honor decrypted config in architecture probe` | bug,infra | ? | - |
| - | [#49221](https://github.com/sgl-project/sglang/issues/49221) `[Bug] HiCache L3 prefetch hits are evicted before admission under L2 pressure` |  | ? | - |
| - | [#49222](https://github.com/sgl-project/sglang/pull/49222) `[Fix] minicpm5: Update the MiniCPM5 XML tool detector` | bug | ? | - |
| - | [#49226](https://github.com/sgl-project/sglang/pull/49226) `[Fix] hicache: retain prefetched host pages until admission` | bug,perf | ? | - |
| - | [#49228](https://github.com/sgl-project/sglang/pull/49228) `[Feat] [MLU] ops: Add fused operator support` | infra,perf | ? | - |
| - | [#49230](https://github.com/sgl-project/sglang/issues/49230) `[Bug] Quark utility import writes optional AITER cache before quantization` | perf,quant,rocm | ? | - |
| - | [#49231](https://github.com/sgl-project/sglang/pull/49231) `[Fix] quark: Defer optional AITER quantizer imports` | bug,quant,rocm | ? | - |
| - | [#49232](https://github.com/sgl-project/sglang/pull/49232) `[Perf] cp: Reuse interleave row copy for ragged gathers` | perf | ? | - |
| - | [#49233](https://github.com/sgl-project/sglang/pull/49233) `[Doc] sampling_params: Improve `/generate` Http Native API documentation` | perf | ? | - |
| - | [#49238](https://github.com/sgl-project/sglang/pull/49238) `[Perf] diffusion: Route SANA-Video 2.0 RoPE through the fused fp64 interleaved RoPE kernel` | perf | ? | - |
| - | [#49240](https://github.com/sgl-project/sglang/pull/49240) `[Fix] Harden CPU bootstrap and bound capacity search` | bug | ? | - |
| - | [#49241](https://github.com/sgl-project/sglang/pull/49241) `[Fix] Preserve packed KV geometry on CPU` | bug | ? | - |
| - | [#49242](https://github.com/sgl-project/sglang/pull/49242) `[Feat] Add resource-based KV capacity budgets` | infra | ? | - |
| - | [#49243](https://github.com/sgl-project/sglang/pull/49243) `[Feat] simulator: Add empirical and explicit acceptance-progress policies` | infra | ? | - |
| - | [#49244](https://github.com/sgl-project/sglang/pull/49244) `[Feat] simulator: Bound record memory and add retention codecs` | infra | ? | - |
| - | [#49245](https://github.com/sgl-project/sglang/pull/49245) `[Perf] simulator: Add an opt-in metrics-only numeric path` | infra,perf | ? | - |
| - | [#49246](https://github.com/sgl-project/sglang/pull/49246) `[Feat] sampling: Honor per-request sampling_seed without deterministic inference` |  | ? | - |
| - | [#49249](https://github.com/sgl-project/sglang/pull/49249) `[Fix] rust_extensions: Include C++ flags in the TreeCore build cache key` | bug,infra,perf | ? | - |
| - | [#49250](https://github.com/sgl-project/sglang/issues/49250) `[Bug] ignore_eos requests finish early when their grammar terminates` |  | ? | - |
| - | [#49251](https://github.com/sgl-project/sglang/pull/49251) `[Fix] scheduler: Do not finish ignore_eos requests on grammar termination` | bug | ? | - |
| - | [#49252](https://github.com/sgl-project/sglang/pull/49252) `[Perf] [XPU] model: Performance Optimization of Qwen3-ASR-1.7B on XPU` | nvidia,perf | ? | - |
| - | [#49254](https://github.com/sgl-project/sglang/pull/49254) `[Feat] scheduler: Add SLA-constrained dynamic batching for decode phase optimization` | perf | ? | - |
| - | [#49255](https://github.com/sgl-project/sglang/pull/49255) `[Test] [NPU] npu_memcache: Add L3 hit-rate checks and MetaService bootstrap` |  | ? | - |
| - | [#49256](https://github.com/sgl-project/sglang/issues/49256) `[Bug] NIXL decode listener exits on malformed STAGING_REQ` |  | ? | - |
| - | [#49257](https://github.com/sgl-project/sglang/issues/49257) `[Feature][RFC] STANDALONE PD: homogeneous TP=2 handoff and rank-consistent seed rejection` |  | ? | - |
| - | [#49258](https://github.com/sgl-project/sglang/pull/49258) `[Fix] pd: Isolate malformed NIXL decode staging requests` | bug | ? | - |
| - | [#49261](https://github.com/sgl-project/sglang/issues/49261) `[Bug] Profiling state conflicts return bare HTTP 500 responses` |  | ? | - |
| - | [#49264](https://github.com/sgl-project/sglang/pull/49264) `[Feat] [NPU] memory-saver: Release device communication domains on sleep mode` | infra | ? | - |
| - | [#49265](https://github.com/sgl-project/sglang/pull/49265) `[Feat] [NPU] attention: support FP8 KV with DSA context parallelism` | infra,quant | ? | - |
| - | [#49266](https://github.com/sgl-project/sglang/pull/49266) `[Fix] Return HTTP 409 for profiling state conflicts` | bug | ? | - |
| - | [#49267](https://github.com/sgl-project/sglang/pull/49267) `[Feat] disagg: Let the PD prefill linker load without offloading` | perf | ? | - |
| - | [#49271](https://github.com/sgl-project/sglang/pull/49271) `[Feat] [NPU] dcp: Switch MLA and DSA to token sharding` |  | ? | - |
| - | [#49272](https://github.com/sgl-project/sglang/pull/49272) `[Fix] HiCache: whole-page Mooncake IO with mixed-result preservation and staging safety` | bug | ? | - |
| - | [#49273](https://github.com/sgl-project/sglang/pull/49273) `[Fix] [XPU] graph: fake registration for optional MLA kernels` | bug,nvidia,perf | ? | - |
| P0 | [#49274](https://github.com/sgl-project/sglang/issues/49274) `Silent deterministic output corruption: first token id 0 ("!") then [PAD] (id 163839) loop, spec accept-length` | infra,quant,risk,rocm | ? | - |
| - | [#49275](https://github.com/sgl-project/sglang/pull/49275) `[Perf] [NVIDIA] quantization: Add tuned channelwise FP8 GEMM tile configs for RTX PRO 5000` | infra,nvidia,perf,quant | ? | - |
| - | [#49276](https://github.com/sgl-project/sglang/pull/49276) `[Perf] ASR: Lazily encode cumulative WAV prefixes on demand in split_audio_chunks` | perf | ? | - |
| P0 | [#49278](https://github.com/sgl-project/sglang/pull/49278) `[Fix] [AMD] moe: Stop declaring zero-filled A8W4 intermediate padding` | bug,rocm | main | - |
| P1 | [#49280](https://github.com/sgl-project/sglang/pull/49280) `[Perf] [AMD] distributed: Run QuickReduce ahead of the custom all-reduce from a size threshold` | perf,rocm | ? | - |
| - | [#49281](https://github.com/sgl-project/sglang/pull/49281) `[Perf] [AMD] dspark: Accept on target vocab shards in verify` | perf,rocm | ? | - |
| P0 | [#49282](https://github.com/sgl-project/sglang/pull/49282) `[Perf] [AMD] dsa: Prefill rope-free bf16 KV pools with aiter's OPUS sparse kernel` | perf,rocm | main | - |
| P1 | [#49283](https://github.com/sgl-project/sglang/pull/49283) `[Perf] [AMD] deepseek-v4.1: Run the closed mHC seams through Mega-mHC in prefill` | perf,rocm | ? | - |
| - | [#49284](https://github.com/sgl-project/sglang/pull/49284) `[Perf] [AMD] deepseek-v4.1: Run the DSpark draft's mHC seams through Mega-mHC` | perf,rocm | ? | - |
| - | [#49285](https://github.com/sgl-project/sglang/pull/49285) `[Perf] deepseek_v4: Score the DeepSeek-V4.1 prefill indexer on Hopper…` | nvidia,perf | ? | - |
| - | [#49286](https://github.com/sgl-project/sglang/pull/49286) `[Fix] [AMD] quark: do not declare the MiniMax-M3 TP8 MoE pad to CK-Tile` | bug,rocm | ? | - |
| - | [#49287](https://github.com/sgl-project/sglang/pull/49287) `[Feat] metrics: measure router-to-detokenizer delivery latency` | perf | ? | - |
| - | [#49288](https://github.com/sgl-project/sglang/pull/49288) `[Fix] attention: Refuse fa4 for KDA hybrids on consumer Blackwell` | bug,nvidia,perf | ? | - |
| - | [#49291](https://github.com/sgl-project/sglang/issues/49291) `[Bug] [NPU] DeepEP on Ascend A2 aborts mid decode-graph capture with a misleading EH0012 when the MC2 scratch ` | nvidia | ? | - |
| - | [#49293](https://github.com/sgl-project/sglang/pull/49293) `[Feat] [NPU] deepep: Add an opt-in guard for the MC2 scratch allocated during decode graph capture` | nvidia | ? | - |
| - | [#49295](https://github.com/sgl-project/sglang/issues/49295) `[Bug] Breakable prefill CUDA graphs return wrong, non-repeatable prompt logprobs for short prompts on Qwen3.8-` | nvidia,quant | ? | - |
| - | [#49296](https://github.com/sgl-project/sglang/issues/49296) `[Feature] flashinfer: Split the extend into ragged and paged passes under full prefill CUDA graphs with an FP8` | nvidia,perf,quant | ? | - |
| - | [#49297](https://github.com/sgl-project/sglang/pull/49297) `[Feat] rust: Add per-request output detokenization bypass` | infra | ? | - |
| - | [#49298](https://github.com/sgl-project/sglang/pull/49298) `[Fix] rerank: Route structured text content through the text decoder` | bug | ? | - |
| - | [#49303](https://github.com/sgl-project/sglang/pull/49303) `[Feat] [NPU] attention: Support ModelSlim INT8 DSA indexer quantization` | quant | ? | - |
| - | [#49305](https://github.com/sgl-project/sglang/pull/49305) `[Doc] tests: Fix docstrings that point at test paths that do not exist` | bug,perf | ? | - |
| - | [#49306](https://github.com/sgl-project/sglang/pull/49306) `[Fix] scheduler: Prevent pool accounting desync on finished_len trim` | bug | ? | - |
| - | [#49313](https://github.com/sgl-project/sglang/pull/49313) `[Doc] multimodal_gen: Drop docstring params the functions do not take` | perf | ? | - |
| - | [#49314](https://github.com/sgl-project/sglang/issues/49314) `[Feature] Support single-worker Replay simulation on Apple Silicon macOS` |  | ? | - |
| P0 | [#49315](https://github.com/sgl-project/sglang/pull/49315) `[Fix] [AMD] kimi-k3: Give AITER's A16W4 SiTU MoE the separated w13 la…` | bug,quant,rocm | main | - |
| - | [#49316](https://github.com/sgl-project/sglang/pull/49316) `[Feat] [Apple] simulator: Support single-worker Replay simulation on macOS` |  | ? | - |
| - | [#49319](https://github.com/sgl-project/sglang/pull/49319) `[Perf] attention: Let SM12x FA4 split KV outside the architecture decode policy` | nvidia,perf | ? | - |
| - | [#49322](https://github.com/sgl-project/sglang/pull/49322) `[Fix] RL: Flush cache after partial distributed weight update` | bug,perf | ? | - |
| - | [#49323](https://github.com/sgl-project/sglang/pull/49323) `[Fix] Keep tokenizers parallelism on for multimodal models` | bug | ? | - |
| - | [#49324](https://github.com/sgl-project/sglang/issues/49324) `[ROCm][AMD] Qwen3.8-27B gfx950 / MI355X Performance Optimization (SGLang)` | perf,rocm | ? | - |
| - | [#49325](https://github.com/sgl-project/sglang/pull/49325) `[CI] labeler: cover the rust sglang-mm and sglang-server crates` | infra | ? | - |
| - | [#49326](https://github.com/sgl-project/sglang/pull/49326) `[Feat] hisparse: Share prompt prefixes on the decode host-tier radix cache` | perf | ? | - |
| - | [#49327](https://github.com/sgl-project/sglang/issues/49327) `[ROCm][AMD] DeepSeek-V4.1-Flash gfx950 / MI355X Performance Optimization (SGLang)` | perf,rocm | ? | - |
| - | [#49329](https://github.com/sgl-project/sglang/pull/49329) `[Perf] hicache: Add an opt-in O_DIRECT path to the fast_file backend` | infra,perf | ? | - |
| P1 | [#49330](https://github.com/sgl-project/sglang/pull/49330) `[Perf] [AMD] deepseek-v4.1: Opt into Mega-mHC on decode and verify steps` | perf,rocm | ? | - |
| - | [#49331](https://github.com/sgl-project/sglang/pull/49331) `[Fix] cohere_command4: Strip an echoed think-start and keep same-chunk answers in streaming` | bug | ? | - |
| - | [#49332](https://github.com/sgl-project/sglang/pull/49332) `[Perf] [AMD] mori: Read MORI EPv2 AsyncLL segmented receive in place, skipping the receive copy` | perf,rocm | ? | - |
| - | [#49333](https://github.com/sgl-project/sglang/pull/49333) `[Feat] models: add public registration for runtime classes` |  | ? | - |
| - | [#49336](https://github.com/sgl-project/sglang/issues/49336) `[Perf] SM90 decode regression v0.5.22 → v0.5.23: +33~45% per-step at concurrency 12 (8K–64K), and `use_deep_se` | bug,nvidia,perf | ? | - |
| - | [#49339](https://github.com/sgl-project/sglang/pull/49339) `[Fix] [AMD] custom-all-reduce: Support expandable segments` | bug,infra,rocm | ? | - |
| - | [#49341](https://github.com/sgl-project/sglang/pull/49341) `[Feat] NPU: support shared-expert fusion across MoE A2A backends` | infra,perf | ? | - |
| - | [#49342](https://github.com/sgl-project/sglang/pull/49342) `[Perf] kimi-k3.1: Share ViT work across prefill CP ranks` | perf | ? | - |
| - | [#49343](https://github.com/sgl-project/sglang/pull/49343) `[Feat] disagg: Admit SWA-compress models such as Inkling in the PD decode radix cache` | perf | ? | - |
| - | [#49344](https://github.com/sgl-project/sglang/pull/49344) `[Fix] process: Don't send SIGQUIT to PID 1 when the launcher dies during startup` | bug | ? | - |
| - | [#49345](https://github.com/sgl-project/sglang/pull/49345) `[Perf] rotary_embedding: Avoid tail slicing and redundant scans in bailing_3drope_get_input_positions_tensor` | perf | ? | - |
| - | [#49347](https://github.com/sgl-project/sglang/pull/49347) `[Perf] [AMD] mla: Read the fused_qkv_a slices in place in the gfx1250 q_a / kv_a RMSNorm, one launch` | infra,perf,rocm | ? | - |
| - | [#49349](https://github.com/sgl-project/sglang/pull/49349) `[Fix] pd: Keep a transfer Success terminal when a client abort lands late` | bug,infra | ? | - |
| - | [#49351](https://github.com/sgl-project/sglang/pull/49351) `[Perf] deepseek-v4.1: Fuse vision Q/K rotary on CUDA` | nvidia,perf | ? | - |
| - | [#49352](https://github.com/sgl-project/sglang/pull/49352) `[Fix] disagg: Notify decode when prefill aborts a request` | bug,infra | ? | - |
| - | [#49358](https://github.com/sgl-project/sglang/pull/49358) `[Fix] eplb: Reject expert distribution record calls when the recorder is disabled` | bug | ? | - |
| - | [#49359](https://github.com/sgl-project/sglang/pull/49359) `[Feat] scheduler: Add --disable-model-stop-tokens to disable model defaults stop tokens ` |  | ? | - |
| - | [#49360](https://github.com/sgl-project/sglang/pull/49360) `[Fix] [NVIDIA] moe: Fall back for strided router logits` | bug,nvidia,perf | ? | - |
| - | [#49361](https://github.com/sgl-project/sglang/issues/49361) `[Bug] Use-After-Free in SGLang UnifiedRadixCache Exposes Tenant KV Data` |  | ? | - |
| - | [#49363](https://github.com/sgl-project/sglang/pull/49363) `[Fix] logging: Respect request log levels for prompt token IDs` | bug | ? | - |
| - | [#49366](https://github.com/sgl-project/sglang/issues/49366) `[Bug] compressed-tensors: block-FP8 checkpoints that list modules as targets fail to load (`weight_block_size`` | quant | ? | - |
| - | [#49367](https://github.com/sgl-project/sglang/pull/49367) `[Fix] compressed-tensors: Find the weight block size when modules are listed as targets` | bug,quant | ? | - |
| - | [#49368](https://github.com/sgl-project/sglang/issues/49368) `[Bug] DeepSeek-V2/V2.5 with per-tensor FP8 scales (compressed-tensors): fusing q_a_proj and kv_a_proj_with_mqa` | perf,quant | ? | - |
| - | [#49371](https://github.com/sgl-project/sglang/pull/49371) `[Perf] [AMD] quark: Use smaller MXFP4 W4A16 MoE tiles on gfx1151` | perf,quant,rocm | ? | - |
| - | [#49372](https://github.com/sgl-project/sglang/issues/49372) `[Bug] compressed-tensors: a shared expert kept unquantized in `ignore` is still fused into the quantized MoE (` | perf,quant | ? | - |
| - | [#49373](https://github.com/sgl-project/sglang/pull/49373) `[Fix] compressed-tensors: Do not fuse a shared expert that the ignore list keeps unquantized` | bug,perf,quant | ? | - |
| - | [#49378](https://github.com/sgl-project/sglang/issues/49378) `[Bug] MiniCPM5, Poolside V1 and Step3 detectors mistype Optional[...] tool arguments` |  | ? | - |
| - | [#49379](https://github.com/sgl-project/sglang/pull/49379) `[Fix] metrics: Make sglang:utilization follow load by using max_running_requests as the capacity` | bug | ? | - |
| - | [#49381](https://github.com/sgl-project/sglang/pull/49381) `[Fix] function_call: keep declared types for Optional params in MiniC…` | bug | ? | - |
| - | [#49393](https://github.com/sgl-project/sglang/pull/49393) `[Fix] hf_transformers: Repair v5 tokenizer components on processor-loaded tokenizers` | bug | ? | - |
| - | [#49395](https://github.com/sgl-project/sglang/issues/49395) `[Bug] ModelOpt MIXED_PRECISION: layers with an unsupported quant_algo (FP8_PER_CHANNEL_PER_TOKEN) are built un` | quant | ? | - |
| - | [#49396](https://github.com/sgl-project/sglang/pull/49396) `[Perf] [AMD] quark: Compile each layer_quant_config pattern once` | perf,quant,rocm | ? | - |
| - | [#49400](https://github.com/sgl-project/sglang/pull/49400) `[Fix] ModelOpt: Refuse layers whose quant_algo SGLang cannot build` | bug,infra,perf,quant | ? | - |
| - | [#49403](https://github.com/sgl-project/sglang/issues/49403) `[Bug] EAGLE/EAGLE3 verify applies repetition_penalty to only one token per step, so speculative output differs` |  | ? | - |
| - | [#49404](https://github.com/sgl-project/sglang/pull/49404) `[Fix] speculative: Apply repetition penalty per draft position in EAGLE verify` | bug | ? | - |
| - | [#49406](https://github.com/sgl-project/sglang/pull/49406) `[Perf] model_loader: Stage weight copies to the GPU through pinned memory` | infra,perf | ? | - |
| - | [#49412](https://github.com/sgl-project/sglang/pull/49412) `[Perf] Engine: freeze GC after startup, as the HTTP server does` | perf | ? | - |
| - | [#49413](https://github.com/sgl-project/sglang/pull/49413) `[Perf] multi-item-scoring: avoid host syncs in label-logprob readback and embed overrides` | infra,perf | ? | - |
| - | [#49415](https://github.com/sgl-project/sglang/pull/49415) `[Doc] blogs: Sync LMSYS SGLang blog cards` |  | ? | - |
| - | [#49416](https://github.com/sgl-project/sglang/pull/49416) `[Fix] sampling: Reject oversized n before it fans out` | bug | ? | - |
| - | [#49418](https://github.com/sgl-project/sglang/pull/49418) `[Fix] openai: handle string-keyed id2label and boolean inputs in OpenAIServingClassify` | bug | ? | - |
| - | [#49419](https://github.com/sgl-project/sglang/pull/49419) `[Fix] radix-cache: keep streaming-session KV in its prefix namespace` | bug,perf | ? | - |
| - | [#49424](https://github.com/sgl-project/sglang/pull/49424) `[NPU] Verify DSPARK drafts in mixed chunk prefill` |  | ? | - |
| - | [#49425](https://github.com/sgl-project/sglang/pull/49425) `[Refactor] kda: Rename SGLANG_OPT_FUSED_KDA_VERIFY to SGLANG_OPT_KDA_TRITON_CHAIN_VERIFY` | perf | ? | - |
| - | [#49429](https://github.com/sgl-project/sglang/pull/49429) `[Perf] beam-search: Speed up trie-constrained beam search on SM120` | nvidia,perf | ? | - |
| - | [#49431](https://github.com/sgl-project/sglang/pull/49431) `[Chore] server-args: Drop stale references to removed cuda-graph flags` | nvidia | ? | - |
| - | [#49437](https://github.com/sgl-project/sglang/pull/49437) `[Feat] Dspark: Support PP decode with stage-local draft owners` |  | ? | - |
| - | [#49438](https://github.com/sgl-project/sglang/pull/49438) `[Fix] model-gateway: Cancel paired PD requests promptly on failure` | bug | ? | - |
| - | [#49439](https://github.com/sgl-project/sglang/pull/49439) `[Feat] profiler: Add per-shape traces for prefill CUDA-graph capture` | nvidia | ? | - |
| - | [#49441](https://github.com/sgl-project/sglang/issues/49441) `[ROCm Product Quality Control]: Weekly Kimi Vendor Verifier (KVV) accuracy regression testing on AMD` | bug,risk,rocm | ? | - |
| - | [#49445](https://github.com/sgl-project/sglang/pull/49445) `[Fix] disaggregation: Bound the connect phase of the retract rebootstrap POST` | bug | ? | - |
| - | [#49446](https://github.com/sgl-project/sglang/pull/49446) `[Feat] hicache: Expose drain and L3 backup failure metrics` | perf | ? | - |
| - | [#49449](https://github.com/sgl-project/sglang/issues/49449) `[EFA Product Quality Control]: Nightly multi-node E2E functionality, accuracy & performance testing for EFA NI` | nvidia,perf,risk | ? | - |
| - | [#49450](https://github.com/sgl-project/sglang/pull/49450) `[Fix] deepseek: Remap block-FP8 weight_scale for stacked gate_up params` | bug,quant | ? | - |
| - | [#49451](https://github.com/sgl-project/sglang/pull/49451) `[Feat][PoC] beam_search: Add paged KV support and item-catalog constraints for GR` |  | ? | - |
| - | [#49454](https://github.com/sgl-project/sglang/issues/49454) `[Feat] kda: run the Kimi-K3 fused FlashInfer decode on a BF16 SSM state (NVIDIA SM100/103)` | nvidia,perf | ? | - |
| - | [#49455](https://github.com/sgl-project/sglang/pull/49455) `[Perf] dcp: pack each peer's send slots from one program` | perf | ? | - |
| - | [#49462](https://github.com/sgl-project/sglang/pull/49462) `[Perf] linker: Build Mooncake grouped load range metadata with numpy` | infra,perf | ? | - |
| - | [#49463](https://github.com/sgl-project/sglang/pull/49463) `[Perf] linker: Resolve slot locations before the forward fence` | perf | ? | - |
| - | [#49464](https://github.com/sgl-project/sglang/pull/49464) `[Perf] linker: Complete landed Mooncake layer groups between submits` | perf | ? | - |
| - | [#49465](https://github.com/sgl-project/sglang/pull/49465) `[Perf] linker: Fill the restorable-prefix mask with one vectorized store` | perf | ? | - |
| - | [#49466](https://github.com/sgl-project/sglang/pull/49466) `[Perf] linker: Load DSpark draft KV with the last transfer layers` | perf | ? | - |
| - | [#49467](https://github.com/sgl-project/sglang/pull/49467) `[Fix] linker: Cover published prefetch KV with its request's session` | bug,perf | ? | - |
| - | [#49468](https://github.com/sgl-project/sglang/pull/49468) `[Perf] linker: Build every Mooncake layer group's range reads before the forward fence` | infra,perf | ? | - |
| - | [#49469](https://github.com/sgl-project/sglang/pull/49469) `[Perf] SANA-Video: Compact Masked Cross Attention tokens with Dual Width BCG capture` | perf | ? | - |
| - | [#49474](https://github.com/sgl-project/sglang/pull/49474) `[Feat] mem_cache: Read KV pages from a peer engine over NVLink` | perf | ? | - |
| - | [#49479](https://github.com/sgl-project/sglang/pull/49479) `[Fix] [Ascend] mHC: Use PyTorch fallback on NPU` | bug,perf | ? | - |
| - | [#49482](https://github.com/sgl-project/sglang/pull/49482) `[Feat] [CPU] model: Support Phi-4-W4A16-AutoRound model on CPU` | infra,quant | ? | - |
| - | [#49483](https://github.com/sgl-project/sglang/issues/49483) `[Bug] ModelOpt MIXED_PRECISION on Llama / Mistral 3: fused qkv_proj and gate_up_proj are built unquantized (th` | perf,quant | ? | - |
| - | [#49484](https://github.com/sgl-project/sglang/pull/49484) `[Fix] Llama, Llava: Declare packed_modules_mapping so ModelOpt MIXED_PRECISION resolves qkv_proj and gate_up_p` | bug | ? | - |
| - | [#49485](https://github.com/sgl-project/sglang/pull/49485) `[Feat] scheduler: Expose scheduler idle state in server info` |  | ? | - |
| - | [#49486](https://github.com/sgl-project/sglang/issues/49486) `[Bug] FP8 checkpoint whose lm_head and embed_tokens are stored in FP8 but listed in modules_to_not_convert: SG` | quant | ? | - |
| - | [#49487](https://github.com/sgl-project/sglang/pull/49487) `[Fix] VocabParallelEmbedding: Refuse a float8 checkpoint weight in an unquantized embedding or lm_head` | bug,perf,quant | ? | - |
| - | [#49489](https://github.com/sgl-project/sglang/pull/49489) `[Test] attention: Cover Triton merge state with an unsplit oracle` | rocm | ? | - |
| - | [#49490](https://github.com/sgl-project/sglang/pull/49490) `[Feat] deepseek: Support mid-conversation tool loading` |  | ? | - |
| - | [#49491](https://github.com/sgl-project/sglang/issues/49491) `[Bug] ModelOpt NVFP4 fused linear: unwritten parts decide the global scales (Gemma 4 KV-shared layers store on` | perf,quant | ? | - |
| - | [#49492](https://github.com/sgl-project/sglang/pull/49492) `[Fix] ModelOpt NVFP4: Do not let unwritten fused parts decide the global scales` | bug,nvidia,perf,quant | ? | - |
| - | [#49493](https://github.com/sgl-project/sglang/issues/49493) `[Bug] Qwen4-Exp PLE: BF16 n-gram shards are cast to FP8 with a unit scale when the checkpoint's config sets pl` | quant | ? | - |
| - | [#49494](https://github.com/sgl-project/sglang/issues/49494) `[Bug] scheduler_0 crashes with exit code -3 (SIGQUIT) during normal decode operation — no Python exception log` | bug | ? | - |
| - | [#49495](https://github.com/sgl-project/sglang/pull/49495) `[Doc] [Apple] apple_metal: Make pyproject swap safe to re-run` | infra | ? | - |
| - | [#49498](https://github.com/sgl-project/sglang/pull/49498) `[Perf] hicache: Overlap PD-prefill write_back eviction backups with the in-flight forward` | perf | ? | - |
| P1 | [#49500](https://github.com/sgl-project/sglang/pull/49500) `[Fix] [AMD] dsv4: Use the gfx942 FP4 indexer kernels` | bug,perf,quant,rocm | ? | - |
| - | [#49502](https://github.com/sgl-project/sglang/pull/49502) `[Feat] [NPU] dsa: Store the DSA MLA KV cache as INT8 on Ascend A2` | perf,quant | ? | - |
| - | [#49503](https://github.com/sgl-project/sglang/pull/49503) `[Perf] [NPU] DCP: Optimize DSA Verify preparation and communication` | perf | ? | - |
| - | [#49505](https://github.com/sgl-project/sglang/pull/49505) `[Perf] [AMD] fp8: Opt-in per-channel requant of block-FP8 dense linears on gfx950` | infra,perf,quant,rocm | ? | - |
| - | [#49506](https://github.com/sgl-project/sglang/pull/49506) `[DON'T MERGE] [Perf] [AMD] gfx1250: fused all-reduce + add + RMSNorm for custom all-reduce v2` | perf,rocm | ? | - |
| - | [#49507](https://github.com/sgl-project/sglang/pull/49507) `[WIP] [Feat] [NPU] dspark: Support DeepSeek-V4 tree verification` |  | ? | - |
| - | [#49508](https://github.com/sgl-project/sglang/pull/49508) `[Fix] [AMD] diffusion: Pin VAE attention to math SDPA on all gfx11/gfx12` | bug,infra,perf,rocm | ? | - |
| - | [#49510](https://github.com/sgl-project/sglang/pull/49510) `[Perf] expert_pack: Deduplicate route_ids and use .tolist() in ExpertPackStore.acquire` | perf | ? | - |
| - | [#49512](https://github.com/sgl-project/sglang/pull/49512) `[Feat] [AMD] sgl-kernel: Enable gfx11xx/gfx12xx (RDNA3/RDNA4) AOT builds` | perf,rocm | ? | - |
| - | [#49513](https://github.com/sgl-project/sglang/pull/49513) `[Test] sampling: cover softcap row argmax boundary and tie semantics` |  | ? | - |
| - | [#49515](https://github.com/sgl-project/sglang/pull/49515) `[Feat] kv-cache: Mooncake v2 adds statistics for bandwidth and page count.` | perf | ? | - |
| - | [#49516](https://github.com/sgl-project/sglang/pull/49516) `[Test] mamba: cover hybrid radix checkpoints taken in mixed chunked-prefill forwards` |  | ? | - |
| - | [#49517](https://github.com/sgl-project/sglang/issues/49517) `[Bug] diffusion_num_queue_reqs does not reflect requests pending in the ZMQ transport` | perf | ? | - |
| - | [#49518](https://github.com/sgl-project/sglang/pull/49518) `[Feat] hicache: Add a Mamba/KDA L3 snapshot interval` | perf | ? | - |
| - | [#49519](https://github.com/sgl-project/sglang/issues/49519) `[Bug] rust-server: /generate text prompts get no BOS when the tokenizer relies on add_bos_token` |  | ? | - |
| - | [#49520](https://github.com/sgl-project/sglang/pull/49520) `[Perf] [AMD] deepseek-v4.1: Run the HIP OPUS sparse prefill over MXFP8 rows with mla_sparse_prefill_v41` | perf,quant,rocm | ? | - |
| - | [#49521](https://github.com/sgl-project/sglang/pull/49521) `[Perf] function_call: Drain Kimi-K2 arguments incrementally` | perf | ? | - |
| - | [#49522](https://github.com/sgl-project/sglang/pull/49522) `[Feat] [NPU] unlimited-ocr: Support Unlimited-OCR reference sliding windows on Ascend` |  | ? | - |
| - | [#49523](https://github.com/sgl-project/sglang/pull/49523) `[Feat] observability: Expose HiSparse device and host cache metrics` | perf | ? | - |
| - | [#49525](https://github.com/sgl-project/sglang/pull/49525) `[Fix] rust-server: Prepend BOS for text prompts when tokenizer relies on add_bos_token` | bug | ? | - |
| - | [#49526](https://github.com/sgl-project/sglang/pull/49526) `[CI] sail: add a release workflow for the sglang-kernel wheel` | infra,perf | ? | - |
| - | [#49528](https://github.com/sgl-project/sglang/pull/49528) `[Perf] [NPU] sampling: threshold top-k/top-p renormalization instead of a full-vocabulary scatter` | perf | ? | - |
| - | [#49529](https://github.com/sgl-project/sglang/pull/49529) `[Perf] [NPU] sampling: fuse top-k/top-p truncation into a candidate-set pass` | perf,risk | ? | - |
| - | [#49530](https://github.com/sgl-project/sglang/pull/49530) `[Fix] rust-server: Restore add_bos_token as the Python tokenizer does` | bug | ? | - |
| - | [#49532](https://github.com/sgl-project/sglang/pull/49532) `[Perf] cosmos3: batch clean refresh and enable VAE fast paths for Bimanual model` | perf | ? | - |
| - | [#49533](https://github.com/sgl-project/sglang/pull/49533) `[Fix] xing4_0: Number streamed tool calls by ordinal and keep Optional[str] args as strings` | bug | ? | - |
| - | [#49535](https://github.com/sgl-project/sglang/pull/49535) `[Fix] [NVIDIA] qwen3.5: Give text-only Qwen3.5 checkpoints the Qwen3 MoE family overrides` | bug,nvidia | ? | - |
| - | [#49536](https://github.com/sgl-project/sglang/issues/49536) `[RFC] Kimi K3 decode: FlashInfer reuse and integration scope` | nvidia | ? | - |
| - | [#49537](https://github.com/sgl-project/sglang/pull/49537) `[Feat] kv-cache: Metrics for write latency distribution from L2 to L3` | perf | ? | - |
| - | [#49541](https://github.com/sgl-project/sglang/issues/49541) `[Bug] FA3 SM90 FP8 two-level accumulation rebuild is ~2.6x slower for paged head_dim=256` | nvidia,perf,quant | ? | - |
| - | [#49542](https://github.com/sgl-project/sglang/pull/49542) `[Perf] sgl-router: Index prefix-cache depths by worker URL` | perf | ? | - |
| - | [#49543](https://github.com/sgl-project/sglang/pull/49543) `[Doc] cookbook: Point the omni FishAudio card at the route Mintlify serves` |  | ? | - |
| - | [#49545](https://github.com/sgl-project/sglang/pull/49545) `[Fix] deepseek: Merge per-tensor q_a/kv_a scales into the fused projection` | bug,perf,quant | ? | - |
| - | [#49547](https://github.com/sgl-project/sglang/pull/49547) `[Feat] [NPU] DSpark: GLM-5.2 support DSpark compact mode` | perf,quant | ? | - |
| - | [#49550](https://github.com/sgl-project/sglang/issues/49550) `[Bug] /v1/responses: late system/developer messages are moved to the top of the prompt, so the prefix cache mi` | perf | ? | - |
| - | [#49551](https://github.com/sgl-project/sglang/pull/49551) `[Quantization] Fix vision layer ignore-list renaming for Gemma 3 / Mistral 3` | bug,quant | ? | - |
| P1 | [#49554](https://github.com/sgl-project/sglang/pull/49554) `[Perf] [AMD] batch-invariant: Faster small-M launch for the segmented bf16 matmul on gfx950` | infra,perf,rocm | ? | - |
| - | [#49556](https://github.com/sgl-project/sglang/pull/49556) `[CI] [NPU] ci: Cap acc-2 nightly partition concurrency` | infra | ? | - |
| - | [#49557](https://github.com/sgl-project/sglang/pull/49557) `[Fix] kernels/jit: Honor the unified cache root` | bug,perf | ? | - |
| - | [#49558](https://github.com/sgl-project/sglang/pull/49558) `[Perf] qwen3-vl: Bound vision MLP activation memory for large patch batches` | perf | ? | - |
| - | [#49559](https://github.com/sgl-project/sglang/pull/49559) `[Fix] hicache: Drop the warning and comments that blame copy-engine queueing for forward stalls` | bug,perf | ? | - |
| - | [#49560](https://github.com/sgl-project/sglang/pull/49560) `[Fix] [CPU] kvcache: Validate indices range in store_cache_cpu` | bug,perf | ? | - |
| - | [#49562](https://github.com/sgl-project/sglang/pull/49562) `[Feat] linker: Export load and offload bytes by pool` | perf | ? | - |
| - | [#49563](https://github.com/sgl-project/sglang/pull/49563) `[Perf] [AMD] dsv4: Decoder tail graphs and any-context breakable prefill graph for V4.1 on HIP` | infra,perf,rocm | ? | - |
| - | [#49565](https://github.com/sgl-project/sglang/pull/49565) `[Feat] bench: Record per-request HTTP status and finish reason` | perf | ? | - |
| - | [#49566](https://github.com/sgl-project/sglang/pull/49566) `[Perf] [AMD] rotary_embedding: tile fused RoPE and KV write for large T on gfx1250` | infra,perf,rocm | ? | - |
| - | [#49569](https://github.com/sgl-project/sglang/issues/49569) `[Feature] Optimize Qwen3-VL reranking with concurrent, exact-label, prefill-only scoring` | perf | ? | - |
| - | [#49571](https://github.com/sgl-project/sglang/pull/49571) `[Feat] flashinfer: Add opt-in scoped caching for single-rank decode graphs` | infra,nvidia | ? | - |
| - | [#49572](https://github.com/sgl-project/sglang/pull/49572) `[Feat] spec: Add EXTERNAL speculative decoding algorithm` |  | ? | - |
| - | [#49575](https://github.com/sgl-project/sglang/pull/49575) `[Feat] http_server: py-spy dump every sglang process when /health fails (opt-in)` |  | ? | - |
| - | [#49578](https://github.com/sgl-project/sglang/pull/49578) `[CI] [AMD] miles: Keep /root/models and /root/datasets on /sgl-data` | infra,rocm | ? | - |
| - | [#49580](https://github.com/sgl-project/sglang/pull/49580) `[Fix] scheduler: pause generation in abort mode to ensure idle release` | bug,infra | ? | - |
| - | [#49592](https://github.com/sgl-project/sglang/pull/49592) `[Fix] weight-checker: Skip non-persistent axis_map buffer in reset_tensors` | bug | ? | - |
| - | [#49594](https://github.com/sgl-project/sglang/pull/49594) `[Refactor] trtllm: derive TRTLLMHAAttnBackend from AttentionBackend directly` | nvidia | ? | - |
| - | [#49596](https://github.com/sgl-project/sglang/pull/49596) `[Perf] [NVIDIA] moe: Skip padded DSpark EP8 CUTLASS rows on Hopper` | nvidia,perf | ? | - |
| - | [#49597](https://github.com/sgl-project/sglang/pull/49597) `[Perf] [NVIDIA] deepseek-v4: Enable Hopper G8 token-major WO-A verify` | nvidia,perf | ? | - |
| - | [#49598](https://github.com/sgl-project/sglang/pull/49598) `[Perf] [NVIDIA] dp-attention: Use short Hopper DPA8 collective paths` | nvidia,perf | ? | - |
| - | [#49602](https://github.com/sgl-project/sglang/issues/49602) `nightly-test-amd.yml reports "All ROCm nightly test jobs passed" when 46 of 48 jobs were skipped` | rocm | ? | - |
| - | [#49604](https://github.com/sgl-project/sglang/pull/49604) `[Feat] frontend: Support X-Priority and RFC 9218 Priority headers` | infra | ? | - |
| - | [#49605](https://github.com/sgl-project/sglang/pull/49605) `[Fix] benchmark: Keep the image placeholder token out of random image prompts for processor-less checkpoints` | bug,perf | ? | - |
| - | [#49607](https://github.com/sgl-project/sglang/pull/49607) `[Chore] deps: Bump xgrammar to 0.2.9` | infra | ? | - |
| - | [#49608](https://github.com/sgl-project/sglang/pull/49608) `[Doc] server_args: --mem-fraction-static is a fraction of free memory at startup` |  | ? | - |
| - | [#49609](https://github.com/sgl-project/sglang/pull/49609) `[Fix] lora: Report adapter weights that should_apply_lora leaves unapplied` | bug | ? | - |
| - | [#49610](https://github.com/sgl-project/sglang/pull/49610) `[Test] lora: Check every Qwen3.5 LoRA module group against HF+PEFT` |  | ? | - |
| - | [#49611](https://github.com/sgl-project/sglang/pull/49611) `[CI] lint: Normalize workflow paths in check_opt_in_ci_tiers on Windows` | infra | ? | - |
| - | [#49612](https://github.com/sgl-project/sglang/pull/49612) `[Fix] rerank: Drop duplicated "Value error" prefix from top_n validation` | bug | ? | - |
| - | [#49613](https://github.com/sgl-project/sglang/pull/49613) `[Fix] cuda-graph: Prevent M-dependent prefill logprob drift on Gated-DeltaNet models` | bug,infra,nvidia,perf,quant | ? | - |
| - | [#49618](https://github.com/sgl-project/sglang/pull/49618) `[Fix] [CPU] moe: Validate topk_ids range in fused_experts_cpu` | bug,perf | ? | - |
| - | [#49619](https://github.com/sgl-project/sglang/pull/49619) `[Perf] gdn: Use the fused decode projection + Conv1D kernel on Triton-capable out-of-tree platforms` | perf,rocm | ? | - |
| - | [#49624](https://github.com/sgl-project/sglang/issues/49624) `[Bug] SGLang FlexKV Exposes Tenant and LoRA KV Cache Across Namespaces` | perf | ? | - |
| - | [#49625](https://github.com/sgl-project/sglang/pull/49625) `[Feat] openai: Support DSV4.1 dynamic tools in Responses and Messages` | infra | ? | - |
| - | [#49626](https://github.com/sgl-project/sglang/issues/49626) `[Bug] Cross-Tenant Oracle Leak via NGRAM Speculative Decoding Metrics in SGLang` |  | ? | - |
| - | [#49627](https://github.com/sgl-project/sglang/pull/49627) `[Doc] observability: Document KV cache events and how to subscribe to them` | perf | ? | - |
| - | [#49628](https://github.com/sgl-project/sglang/pull/49628) `[Fix] speculative: Pad MLP-sync speculative batches by whole requests` | bug,perf | ? | - |
| - | [#49629](https://github.com/sgl-project/sglang/pull/49629) `[Perf] sgl-router: Encode DeepSeek-V4 prompts on the router's fastokens tokenizer` | infra,perf | ? | - |
| - | [#49638](https://github.com/sgl-project/sglang/pull/49638) `[Fix] [AMD] config: Reject explicit AITER fusion in deterministic mode` | bug,perf,rocm | ? | - |
| - | [#49643](https://github.com/sgl-project/sglang/pull/49643) `[Doc] [AMD] GLM-5.3-Flash: add the MI355X MXFP4 recipe with the AMD monokernel` | quant,rocm | ? | - |
| - | [#49648](https://github.com/sgl-project/sglang/pull/49648) `[Feat] dflash: Run DFLASH on a pipelined PD prefill` | infra | ? | - |
| - | [#49654](https://github.com/sgl-project/sglang/pull/49654) `[Perf] tp_worker: load the worker's tokenizer on first use` | perf | ? | - |
| - | [#49657](https://github.com/sgl-project/sglang/issues/49657) `[Bug] [AMD gfx12] HIP custom all-reduce 1-stage gives wrong, rank-divergent sums over PCIe (2x R9700): relaxed` | rocm | ? | - |
| - | [#49667](https://github.com/sgl-project/sglang/pull/49667) `[Feat] scheduler: in-process output sink` |  | ? | - |
| - | [#49668](https://github.com/sgl-project/sglang/pull/49668) `[Refactor] moe: Unify MoE router GEMM behind shared RouterGate layer` |  | ? | - |
| - | [#49672](https://github.com/sgl-project/sglang/pull/49672) `[Perf] server_args: leave the ModelConfig memo out of a pickled record` | perf | ? | - |
| - | [#49674](https://github.com/sgl-project/sglang/pull/49674) `[Fix] processor: Preserve reasoning content in Rust renderers` | bug | ? | - |
| - | [#49676](https://github.com/sgl-project/sglang/issues/49676) `[Feature] Share GPU memory between the KV pool and the mamba/linear-attention state pool instead of a static s` |  | ? | - |
| P1 | [#49679](https://github.com/sgl-project/sglang/pull/49679) `[Fix] [AMD] quantization: Keep ROCm UE8M0 group-32 FP8 quant on the v2 kernel` | bug,perf,quant,rocm | ? | - |
| - | [#49680](https://github.com/sgl-project/sglang/pull/49680) `[Fix] mistral_eagle: Use mm_input_embeds in the draft's prefill for multimodal requests` | bug,infra | ? | - |
| - | [#49681](https://github.com/sgl-project/sglang/pull/49681) `[Feat] models: Public attention-layer lookup and FA kernel hooks for external models` | perf | ? | - |
| - | [#49682](https://github.com/sgl-project/sglang/pull/49682) `[Fix] serving_chat: Avoid a second BOS on multimodal text-only chats` | bug | ? | - |
| - | [#49683](https://github.com/sgl-project/sglang/pull/49683) `[Fix] tokenizer_manager: Reject input_embeds requests when speculative decoding is enabled` | bug,infra | ? | - |
| - | [#49685](https://github.com/sgl-project/sglang/pull/49685) `[Fix] [Apple] mlx: provide tree slots to auxiliary-state test fixtures` | bug | ? | - |
| - | [#49687](https://github.com/sgl-project/sglang/pull/49687) `[Perf] function_call: Avoid quadratic rescanning in MuseGlimmerDetector streaming` | perf | ? | - |
| - | [#49691](https://github.com/sgl-project/sglang/pull/49691) `[Feat] [NVIDIA] multimodal: Honor SGLANG_FORCE_CPU_IMAGE_PREPROCESSING in the base multimodal processor` | nvidia | ? | - |
| - | [#49692](https://github.com/sgl-project/sglang/pull/49692) `[Perf] pp: Defer steady decode output packing until after forward submission` | perf | ? | - |
| - | [#49694](https://github.com/sgl-project/sglang/pull/49694) `[CI] diffusion: Allow 6% host anon memory headroom on 5090` | infra,perf | ? | - |
| - | [#49696](https://github.com/sgl-project/sglang/pull/49696) `[Feat] linker: Prefetch SSD-resident KV into store DRAM while queued` | perf | ? | - |
| - | [#49698](https://github.com/sgl-project/sglang/pull/49698) `[Perf] hybrid: Reuse cached full-attention KV during GDN state replay` | perf | ? | - |
| - | [#49700](https://github.com/sgl-project/sglang/pull/49700) `[Test] diffusion: Pass --trust-remote-code for the custom VAE path case` | perf | ? | - |
| - | [#49702](https://github.com/sgl-project/sglang/pull/49702) `[Fix] openai: Accept `reasoning` as an alias for assistant `reasoning_content`` | bug | ? | - |
| - | [#49703](https://github.com/sgl-project/sglang/pull/49703) `[Fix] [AMD] minimax: Run the gfx950 Gluon sparse prefill with several KV heads per rank` | bug,perf,rocm | ? | - |
| - | [#49705](https://github.com/sgl-project/sglang/pull/49705) `[Perf] [NVIDIA] fp8: enable SPLIT_K/SWAP_AB block-fp8 configs on sm_120` | nvidia,perf,quant | ? | - |
| - | [#49708](https://github.com/sgl-project/sglang/pull/49708) `[Perf] diffusion: Encode large compressed PNG outputs in parallel strips` | perf | ? | - |
| - | [#49712](https://github.com/sgl-project/sglang/pull/49712) `[Fix] benchmark: Isolate shared-prefix caches by tokenizer` | bug,perf | ? | - |
| - | [#49713](https://github.com/sgl-project/sglang/pull/49713) `[Feat] mem_cache: Direct-linker support for plain MLA/MHA KV pools` | perf | ? | - |
| - | [#49723](https://github.com/sgl-project/sglang/pull/49723) `[Fix] flexkv: Isolate FlexKV KV by the request's cache namespace` | bug,perf | ? | - |
| - | [#49725](https://github.com/sgl-project/sglang/pull/49725) `[Perf] [NPU] sampling: skip full-vocabulary un-sort in top-k renorm` | perf | ? | - |
| - | [#49726](https://github.com/sgl-project/sglang/pull/49726) `[Fix] function_call: Align DeepSeek DSML streaming with one-shot parsing` | bug | ? | - |
| - | [#49728](https://github.com/sgl-project/sglang/pull/49728) `[Feat] eplb: Add ring-buddy expert replication (--ep-dispatch-algorithm ring) for Muse Spark` | perf | ? | - |
| - | [#49729](https://github.com/sgl-project/sglang/pull/49729) `[Feat] dp: Add shape-aware DP load balancing method` |  | ? | - |
| - | [#49730](https://github.com/sgl-project/sglang/pull/49730) `[Fix] moe: Support more than 1024 expert buckets in the AOT moe_align_block_size` | bug,perf | ? | - |
| - | [#49734](https://github.com/sgl-project/sglang/pull/49734) `[Feat] api-codegen: Tagged payload presence rules and multi-arm untagged lists` | infra | ? | - |
| - | [#49735](https://github.com/sgl-project/sglang/pull/49735) `[Feat] rust-server: Pause and continue generation, freeze_gc, ping and ready, and the frontend state` | infra | ? | - |
| - | [#49736](https://github.com/sgl-project/sglang/pull/49736) `[Feat] rust-server: set_internal_state, profiling, expert distribution, slow_down and memory occupation contro` | infra | ? | - |
| - | [#49737](https://github.com/sgl-project/sglang/pull/49737) `[Feat] rust-server: pd_role_switch and update_weight_version over the model-facts cache` | infra,perf | ? | - |
| - | [#49738](https://github.com/sgl-project/sglang/pull/49738) `[Feat] rust-server: Weight reads, update groups, weight updates and LoRA refusals` | infra | ? | - |
| - | [#49739](https://github.com/sgl-project/sglang/pull/49739) `[Feat] rust-server: /parse_function_call and /separate_reasoning` | infra | ? | - |
| - | [#49740](https://github.com/sgl-project/sglang/pull/49740) `[Feat] rust-server: External corpus routes for NGRAM speculative decoding` | infra | ? | - |
| - | [#49741](https://github.com/sgl-project/sglang/pull/49741) `[Feat] rust-server: /open_session, /close_session and session_params on generate` | infra | ? | - |
| - | [#49742](https://github.com/sgl-project/sglang/pull/49742) `[Feat] rust-server: configure_logging, the dumper routes, the HiCache L3 layout and elastic EP state` | infra | ? | - |
| - | [#49743](https://github.com/sgl-project/sglang/pull/49743) `[Feat] rust-server: The Ollama routes over HTTP and gRPC` | infra | ? | - |
| - | [#49744](https://github.com/sgl-project/sglang/pull/49744) `[Feat] rust-server: The Anthropic Messages API over HTTP and gRPC` | infra | ? | - |
| - | [#49745](https://github.com/sgl-project/sglang/pull/49745) `[Feat] api: The OpenAI completions and chat completions schema and gRPC surface` | infra | ? | - |
| - | [#49746](https://github.com/sgl-project/sglang/pull/49746) `[Feat] rust-server: /v1/score, and the embeddings, classify, rerank and tokenize schema` | infra | ? | - |
| - | [#49747](https://github.com/sgl-project/sglang/pull/49747) `[Feat] rust-server: Vertex and SageMaker generation wrappers, PUT /generate and slashed model ids` | infra | ? | - |
| - | [#49748](https://github.com/sgl-project/sglang/pull/49748) `[Feat] rust-server: The stateless /v1/responses API over the chat route` | infra,nvidia,perf,rocm | ? | - |
| - | [#49753](https://github.com/sgl-project/sglang/pull/49753) `[Feat] [AMD] minimax: PD with a pipeline-parallel prefill and a different decode attention TP (Mooncake)` | nvidia,rocm | ? | - |
| - | [#49754](https://github.com/sgl-project/sglang/pull/49754) `[Perf] diffusion/cache: Hash CUDA conditioning tensors on the GPU with keyed NH` | nvidia,perf | ? | - |
| - | [#49757](https://github.com/sgl-project/sglang/pull/49757) `[Test] [NPU] npu_memcache: Add L3 hit-rate checks and MetaService bootstrap` |  | ? | - |
| - | [#49764](https://github.com/sgl-project/sglang/pull/49764) `[Fix] attention: Return zeros instead of NaN from merge_state_v2 when both states are empty` | bug,perf,risk | ? | - |
| - | [#49765](https://github.com/sgl-project/sglang/pull/49765) `[CI] [AMD] nightly: Pause the MI30x Qwen3.8-Flash-Next test until the gfx942 LDS fix` | bug,infra,rocm | ? | - |
| - | [#49767](https://github.com/sgl-project/sglang/pull/49767) `[Feat] [AMD] minimax: DSpark on a pipeline-parallel PD prefill (PP4 x TP1 -> TP4)` | nvidia,perf,rocm | ? | - |
| - | [#49768](https://github.com/sgl-project/sglang/pull/49768) `[Perf] kimi-k3.1: Route and quantize the SP tail's MoE input on each rank's rows` | perf,quant | ? | - |
| - | [#49769](https://github.com/sgl-project/sglang/pull/49769) `[Perf] diffusion/cache: Prefetch tile digests so hashing overlaps the VAE encode` | perf | ? | - |
| - | [#49770](https://github.com/sgl-project/sglang/pull/49770) `[Perf] rust-server: Avoid raw state materialization for default /server_info` | perf | ? | - |
| - | [#49773](https://github.com/sgl-project/sglang/pull/49773) `[Doc] hicache: Document buffer_only anchor-lock cap and DP-attention scaling of schedule conservativeness` |  | ? | - |
| - | [#49774](https://github.com/sgl-project/sglang/pull/49774) `[CI] [AMD] schedule: Run the ROCm 7.2.0 and 7.2.4 lanes on weekends only` | infra,rocm | ? | - |
| - | [#49776](https://github.com/sgl-project/sglang/pull/49776) `[Fix] mxfp8: scope the triton_kernels parity check to 16-bit inputs` | bug,perf,quant | ? | - |
| - | [#49777](https://github.com/sgl-project/sglang/pull/49777) `[Refactor] scheduler: Add the guards for aborting a request on receipt` |  | ? | - |
| - | [#49778](https://github.com/sgl-project/sglang/pull/49778) `[Fix] openai: Route a bare LoRA adapter name in `model` to the adapter` | bug | ? | - |
| - | [#49779](https://github.com/sgl-project/sglang/issues/49779) `[Bug][DeepSeek-V4.1][SM120] candidate_topk_blocks: 0 does not disable the candidate scheme: layers 24-39 silen` | nvidia,risk | ? | - |
| - | [#49780](https://github.com/sgl-project/sglang/pull/49780) `[Perf] [NPU] attention: Use QuantLightningIndexerV2 for DSA context parallelism` | perf,quant | ? | - |
| - | [#49782](https://github.com/sgl-project/sglang/pull/49782) `[Fix] [Intel] gemma4-diffusion: Serve DiffusionGemma on Intel XPU` | bug,nvidia,perf,quant | ? | - |
| - | [#49784](https://github.com/sgl-project/sglang/pull/49784) `[Fix] dsv4: Turn the V4.1 candidate scheme off when candidate_topk_blocks is 0` | bug | ? | - |
| - | [#49785](https://github.com/sgl-project/sglang/pull/49785) `[Fix] lang: Handle empty options and NaN/None token logprobs in `ChoicesSamplingMethod`` | bug,risk | ? | - |
| - | [#49786](https://github.com/sgl-project/sglang/pull/49786) `[Feat][Intel] Quantization: Service Initialization support for AutoRound INT4 models on CPU` | perf,quant | ? | - |
| - | [#49788](https://github.com/sgl-project/sglang/pull/49788) `[Perf] [NPU] sampling: fuse top-p and top-k verify renorm` | perf | ? | - |
| - | [#49789](https://github.com/sgl-project/sglang/issues/49789) `[Bug] SM12x: block-fp8-as-MXFP8 gate (k%32) is looser than b12x dispatch (K%128); K%128!=0 layers regress sile` | quant,risk | ? | - |
| - | [#49790](https://github.com/sgl-project/sglang/pull/49790) `[Fix] [NPU] qwen3_5_mtp: adapt mtp.fc quantization as ReplicatedLinear` | bug,infra,quant | ? | - |
| - | [#49791](https://github.com/sgl-project/sglang/pull/49791) `[Feat] [NVIDIA] moe: opt-in FlashInfer cuTile NVFP4 W4A4 runner for MiniMax-M3.1 on SM12x` | nvidia,quant | ? | - |
| - | [#49792](https://github.com/sgl-project/sglang/pull/49792) `[Fix] gateway: cancel pending prefill on early decode failures` | bug | ? | - |
| - | [#49794](https://github.com/sgl-project/sglang/pull/49794) `[Feat] [Intel] diffusion: Run ConvRot INT8 linears on native sgl-kernel-xpu ops` | nvidia,perf,quant | ? | - |
| - | [#49795](https://github.com/sgl-project/sglang/pull/49795) `[Feat] [NVIDIA] moe: Add opt-in cuTile NVFP4 support for MiniMax on SM12x` | nvidia,quant | ? | - |
| - | [#49797](https://github.com/sgl-project/sglang/pull/49797) `[Feature] Add pipeline-parallel EAGLE support for PD decode` |  | ? | - |
| - | [#49799](https://github.com/sgl-project/sglang/issues/49799) `[Feature] [Intel] weight-cache: Support the weight cache daemon on Intel XPU` | nvidia,perf | ? | - |
| P1 | [#49800](https://github.com/sgl-project/sglang/pull/49800) `[Feat] [AMD] qwen4_exp: Use the packed PLE prefill short conv on ROCm` | perf,rocm | ? | - |
| - | [#49801](https://github.com/sgl-project/sglang/issues/49801) `[Bug] dsv4: Eager SWA bounded replay masks valid TP-to-EP tail rows` |  | ? | - |
| - | [#49802](https://github.com/sgl-project/sglang/pull/49802) `[Fix] dsv4: Rebind eager replay tail and MoE shard counts` | bug | ? | - |
| - | [#49804](https://github.com/sgl-project/sglang/pull/49804) `[Fix] compressed-tensors: Treat actorder aliases like their canonical form in WNA16 MoE` | bug,quant | ? | - |
| - | [#49806](https://github.com/sgl-project/sglang/pull/49806) `[Fix] [AMD] kv-cache: Reject unsupported FP8 E5M2 requests` | bug,perf,quant,rocm | ? | - |
| - | [#49807](https://github.com/sgl-project/sglang/pull/49807) `[Feat] [NVIDIA] attention: Extend LiteTopK prefill to support LongCat, ERNIE 5.5, HY-4-family, Kimi K3.1` | nvidia,perf | ? | - |
| - | [#49809](https://github.com/sgl-project/sglang/pull/49809) `[Fix] kv-cache: Ignore checkpoint k/v scales when the KV cache is 16-bit` | bug,perf,quant | ? | - |
| - | [#49810](https://github.com/sgl-project/sglang/pull/49810) `[Perf] [NVIDIA] fp8: keep K%128!=0 block-fp8 linears on the Triton kernel under the MXFP8 view` | nvidia,perf,quant,rocm | ? | - |
| - | [#49811](https://github.com/sgl-project/sglang/pull/49811) `[Perf] openai: Cache stable chunks within long chat segments` | perf | ? | - |
| P0 | [#49812](https://github.com/sgl-project/sglang/pull/49812) `[Fix] [AMD] deterministic: Batch-invariant mHC pre for GLM-5.3 on ROCm` | bug,perf,rocm | main | - |
| - | [#49813](https://github.com/sgl-project/sglang/pull/49813) `[Fix] function_call: Accept underscore-prefixed Pythonic identifiers` | bug | ? | - |
| - | [#49814](https://github.com/sgl-project/sglang/pull/49814) `[Fix] deterministic: Put DSA k-pool prefill chunk ends on the chunked-prefill grid` | bug | ? | - |
| - | [#49815](https://github.com/sgl-project/sglang/pull/49815) `[Fix] deterministic: Deterministic k-pool top-k for the DSA indexer` | bug | ? | - |
| - | [#49816](https://github.com/sgl-project/sglang/pull/49816) `[Refactor] [Intel] weight-cache: Platform hooks for Intel XPU support` | nvidia,perf,rocm | ? | - |
| - | [#49817](https://github.com/sgl-project/sglang/pull/49817) `[Perf] kimi-k3.1: Run the SP tail's shared experts on a high-priority stream` | perf,quant | ? | - |
| - | [#49818](https://github.com/sgl-project/sglang/pull/49818) `[Perf] kimi-k3.1: Fuse o_proj with its reduce-scatter in the SP tail` | perf,quant | ? | - |
| - | [#49819](https://github.com/sgl-project/sglang/pull/49819) `[Perf] kimi-k3.1: Unroll the SP tail's NVLS collectives and gather routed inputs in one launch` | perf,quant | ? | - |
| - | [#49822](https://github.com/sgl-project/sglang/pull/49822) `[Fix] diffusion: Bound VRAM during resident FP8 weight loading` | bug,perf,quant | ? | - |
| - | [#49824](https://github.com/sgl-project/sglang/pull/49824) `[Fix] realtime: Preserve omitted transcription settings in partial updates` | bug | ? | - |
| - | [#49827](https://github.com/sgl-project/sglang/pull/49827) `[Perf] [NVIDIA] minimax-h3: add prepared QKV exchange for dense and SubBlock Sage` | bug,nvidia,perf | ? | - |
| - | [#49828](https://github.com/sgl-project/sglang/pull/49828) `[Fix] processor: Lower chat requests that declare deferred tools` | bug | ? | - |
| - | [#49829](https://github.com/sgl-project/sglang/pull/49829) `[Feat] offloader: Let OffloaderV1 offload only the model-declared submodule` |  | ? | - |
| - | [#49845](https://github.com/sgl-project/sglang/pull/49845) `[Perf] Z-Image: Batch CFG branches in eager inference` | perf | ? | - |
| - | [#49849](https://github.com/sgl-project/sglang/pull/49849) `[Test] attention_unittest: Dead code clean up. Drop the duplicated draft-extend prefix-len helper` |  | ? | - |
| - | [#49850](https://github.com/sgl-project/sglang/pull/49850) `[Fix] deepseek-v4: Pass expert offloader_kwargs so --offload-group-size works` | bug | ? | - |
| P1 | [#49852](https://github.com/sgl-project/sglang/pull/49852) `[Perf] [AMD] quark: Pad W4A4 MXFP4 MoE to 128 columns for AITER FlyDSL` | perf,quant,rocm | ? | - |
| - | [#49853](https://github.com/sgl-project/sglang/pull/49853) `[Fix] EPLB: Support pipeline-parallel EPLB with TP-Group` | bug | ? | - |
| - | [#49854](https://github.com/sgl-project/sglang/pull/49854) `[Refactor] scheduler: Name the forward-on-its-own-stream condition once` | infra | ? | - |
| - | [#49855](https://github.com/sgl-project/sglang/pull/49855) `[Refactor] scheduler: Move a retract's release work into RequestRetirer.retract` | infra | ? | - |
| - | [#49856](https://github.com/sgl-project/sglang/pull/49856) `[Chore] http server: Dead code clean up` |  | ? | - |
| - | [#49858](https://github.com/sgl-project/sglang/pull/49858) `[Fix] gemma4: Keep closed bracket pairs in undelimited tool-call array elements` | bug | ? | - |
| - | [#49859](https://github.com/sgl-project/sglang/pull/49859) `[Feat] disaggregation: Support DSA cache layer split with the NIXL transfer backend` | perf | ? | - |
| - | [#49861](https://github.com/sgl-project/sglang/pull/49861) `[Fix] loads: Answer an unknown include section with 400 instead of 500` | bug | ? | - |
| - | [#49862](https://github.com/sgl-project/sglang/pull/49862) `[Fix] [Intel] quantization: Serve GLM-4.7-Flash int4 AutoRound, Ling-3.0-flash-VL-fp4 and Ling-2.6/3.0-flash-f` | bug,nvidia,quant | ? | - |
| - | [#49863](https://github.com/sgl-project/sglang/pull/49863) `[Refactor] scheduler: Give the PD queues and preemption the retirer explicitly, and read the PD role from conf` | infra | ? | - |
| - | [#49864](https://github.com/sgl-project/sglang/pull/49864) `[Perf] [NVIDIA] attention: Reduce head72 value accumulation on SM120` | nvidia,perf | ? | - |
| - | [#49869](https://github.com/sgl-project/sglang/pull/49869) `[Fix] speculative: Validate QSA draft window before loading weights` | bug | ? | - |
| - | [#49873](https://github.com/sgl-project/sglang/pull/49873) `[Fix] humming: correct local work estimates for EP tuning` | bug,perf | ? | - |
| - | [#49874](https://github.com/sgl-project/sglang/issues/49874) `[Feature] Accept `reasoning_content` and `join` in response templates` |  | ? | - |
| - | [#49875](https://github.com/sgl-project/sglang/pull/49875) `[Fix] qwen3-coder: Recover unescaped inner quotes in JSON parameters` | bug | ? | - |
| - | [#49876](https://github.com/sgl-project/sglang/pull/49876) `[Fix] mimo: Preserve ModelOpt policies for packed projections` | bug | ? | - |
| - | [#49879](https://github.com/sgl-project/sglang/pull/49879) `[Fix] Z-Image: Correct and optimize Ulysses sequence layout` | bug,perf | ? | - |
| - | [#49880](https://github.com/sgl-project/sglang/pull/49880) `[Fix] jit: link libcudart from lib/ when CUDA root has no lib64/` | bug,nvidia,perf | ? | - |
| - | [#49882](https://github.com/sgl-project/sglang/pull/49882) `[Fix] [AMD] hicache: Honor UMBP anchor key namespaces` | bug,rocm | ? | - |
| - | [#49883](https://github.com/sgl-project/sglang/pull/49883) `[Perf] [AMD] aiter: Run EAGLE target verify on unified_attention by default on gfx942` | infra,perf,rocm | ? | - |
| - | [#49885](https://github.com/sgl-project/sglang/pull/49885) `[Fix] parser: Accept reasoning_content and empty join in response templates` | bug | ? | - |
| - | [#49887](https://github.com/sgl-project/sglang/pull/49887) `[Fix] jit: Build four JIT kernels with CUDA 13.5 and 12.x nvcc` | bug,infra,nvidia,perf,quant | ? | - |
| - | [#49888](https://github.com/sgl-project/sglang/pull/49888) `[Feat] model: Add Solar-Open2-250B support` | perf | ? | - |
| - | [#49892](https://github.com/sgl-project/sglang/pull/49892) `[Perf] utils: Cache child Gauge handles and validate bounds in GaugeHistogram` | perf | ? | - |
| - | [#49893](https://github.com/sgl-project/sglang/pull/49893) `[Fix] ngram: Isolate the speculative corpus by cache namespace` | bug,perf | ? | - |
| - | [#49898](https://github.com/sgl-project/sglang/pull/49898) `[Fix] speculative: Isolate NGRAM drafts by cache namespace` | bug,perf | ? | - |
| - | [#49899](https://github.com/sgl-project/sglang/pull/49899) `[Doc] plugins: Document and pin the plugin-facing RuntimeContext subset` | infra | ? | - |
| - | [#49900](https://github.com/sgl-project/sglang/issues/49900) `[Bug][Performance][DeepSeek-V4.1] Decode step with one running request is ~12 ms slower than with two: _w8a8_b` | nvidia,perf,quant | ? | - |
| - | [#49901](https://github.com/sgl-project/sglang/issues/49901) `[Bug] Cross-Tenant MCP Session Reuse via Incomplete Connection Pool Keys` |  | ? | - |
| - | [#49903](https://github.com/sgl-project/sglang/issues/49903) `[Bug] Cross-Client Token Leak in Multi-Tokenizer Mode via Duplicate rid State Merging` |  | ? | - |
| - | [#49904](https://github.com/sgl-project/sglang/pull/49904) `Perf [AMD] all-reduce tuner for graph and eager mode` | perf,rocm | ? | - |
| - | [#49910](https://github.com/sgl-project/sglang/pull/49910) `[Fix] function_call: Default DeepSeek tool strictness to false` | bug | ? | - |
| - | [#49911](https://github.com/sgl-project/sglang/pull/49911) `[Fix] openai: Accept ECMA regex patterns in non-strict tools` | bug | ? | - |
| - | [#49914](https://github.com/sgl-project/sglang/pull/49914) `[Perf] server_args: Keep transformers out of the import path` | perf | ? | - |
| - | [#49916](https://github.com/sgl-project/sglang/issues/49916) `[Feature] Extend SGLang Simulator for Dynamo-compatible PD and low-memory hardware simulation` |  | ? | - |
| - | [#49920](https://github.com/sgl-project/sglang/pull/49920) `[Fix] lora: [sglang-miles] Narrow the kv_b_proj prefix-cache rule to trtllm_mla` | bug,perf | ? | - |
| - | [#49924](https://github.com/sgl-project/sglang/pull/49924) `[Fix] disaggregation: digest KV and state at the ids the transfer uses` | bug | ? | - |
| - | [#49925](https://github.com/sgl-project/sglang/pull/49925) `[Fix] Falcon-H1: run the Mamba2 extend as a graph break in breakable prefill graphs` | bug | ? | - |
| - | [#49926](https://github.com/sgl-project/sglang/pull/49926) `[Fix] mamba: Never autotune the SSD chunk scan into a config that computes a wrong result` | bug,perf | ? | - |
| - | [#49928](https://github.com/sgl-project/sglang/pull/49928) `[Feat] kv-cache: NVFP4 KV cache for hybrid SWA models` | nvidia,perf,quant | ? | - |
| - | [#49932](https://github.com/sgl-project/sglang/pull/49932) `[Fix] lora: [sglang-miles] Route MLA cached-prefix rows to their own kv_b_proj adapters` | bug | ? | - |
| - | [#49933](https://github.com/sgl-project/sglang/pull/49933) `[Perf] multimodal: Vectorize the placeholder-token scan in pad_mm_token_pairs` | infra,perf | ? | - |
| - | [#49934](https://github.com/sgl-project/sglang/pull/49934) `[Perf] rust-server: Bound queued compressed-body memory in request decompression` | infra,perf | ? | - |
| - | [#49935](https://github.com/sgl-project/sglang/pull/49935) `[Fix] gptq_marlin: Derive the MoE w13 scale layout from hidden size` | bug,quant | ? | - |
| - | [#49937](https://github.com/sgl-project/sglang/pull/49937) `[Fix] speculative: Publish adaptive tier capture settings` | bug | ? | - |
| - | [#49938](https://github.com/sgl-project/sglang/pull/49938) `[Fix] graph: Restore attention variant on capture exceptions` | bug | ? | - |
| - | [#49940](https://github.com/sgl-project/sglang/pull/49940) `[Fix] [AMD] diffusion: Preserve graph capture with layerwise offload` | bug,infra,perf,rocm | ? | - |
| - | [#49944](https://github.com/sgl-project/sglang/issues/49944) `[Tracking] Unified Memory Roadmap` |  | ? | - |
| - | [#49946](https://github.com/sgl-project/sglang/pull/49946) `[CI] [AMD] vlm: Restore MiniCPM-o MMMU coverage` | infra,rocm | ? | - |
| - | [#49952](https://github.com/sgl-project/sglang/pull/49952) `[Feat] jinaocr: Add model support` |  | ? | - |
| - | [#49953](https://github.com/sgl-project/sglang/issues/49953) `[Feature] Support jina-ocr-v1 with FastMTP speculative decoding` |  | ? | - |
| - | [#49956](https://github.com/sgl-project/sglang/pull/49956) `[Fix] [AMD] ci: Fix runner preflight and allocation cleanup` | bug,infra,rocm | ? | - |
| - | [#49957](https://github.com/sgl-project/sglang/pull/49957) `[CI] [AMD] nightly: Preserve and report test failures` | infra,rocm | ? | - |
| - | [#49962](https://github.com/sgl-project/sglang/pull/49962) `[Fix] function_call: Fix DeepSeekV3Detector streaming and error isolation` | bug | ? | - |
| - | [#49963](https://github.com/sgl-project/sglang/pull/49963) `[Fix] [AMD] compat: Repair fixture and Torch fallback compatibility` | bug,infra,perf,rocm | ? | - |
| - | [#49965](https://github.com/sgl-project/sglang/pull/49965) `[CI] [AMD] images: Align build source and record runtime provenance` | infra,rocm | ? | - |
| - | [#49968](https://github.com/sgl-project/sglang/issues/49968) `[Roadmap] Q4 2026 MultiHardware Roadmap` |  | ? | - |
| - | [#49969](https://github.com/sgl-project/sglang/pull/49969) `[Perf] dsa: Scheduled MQA logits for the prefill indexer` | perf | ? | - |
| - | [#49974](https://github.com/sgl-project/sglang/pull/49974) `[Perf] radix-cache: keep the full device-eviction queue across walks` | perf | ? | - |
| - | [#49976](https://github.com/sgl-project/sglang/pull/49976) `[Fix] jit: Report JIT CUDA home in check_env (refs #49209)` | bug,nvidia | ? | - |
| - | [#49977](https://github.com/sgl-project/sglang/pull/49977) `[Fix] gdn: Replay exact prefill buckets for quantized GDN on SM100/SM103 (refs #49295)` | bug,nvidia,quant | ? | - |
| - | [#49978](https://github.com/sgl-project/sglang/pull/49978) `[Perf] dsv4: Keep SM90 full top-k decode on select_decode (refs #49336)` | nvidia,perf | ? | - |
| - | [#49979](https://github.com/sgl-project/sglang/pull/49979) `[Perf] flash-attn: Add opt-in switch to skip FP8 two-level accumulation at hdim256 (refs #49541)` | nvidia,perf,quant | ? | - |
| - | [#49981](https://github.com/sgl-project/sglang/pull/49981) `replace image` |  | ? | - |
| - | [#49982](https://github.com/sgl-project/sglang/pull/49982) `[Fix] openai: Skip added tokens when probing whether a tokenizer is byte-level` | bug | ? | - |
| - | [#49985](https://github.com/sgl-project/sglang/issues/49985) `[Feature] Steering vector support: applying activation vectors, not just reading them` |  | ? | - |
| - | [#49988](https://github.com/sgl-project/sglang/pull/49988) `Feat/vertical merge eep mooncake` | infra,nvidia,perf,rocm | ? | - |
| - | [#49989](https://github.com/sgl-project/sglang/pull/49989) `[Feat] [Intel] xpu: Use XPU Kernels for DSV4.1 Full Top-k and Candidate Indexing` | nvidia,perf | ? | - |
| - | [#49991](https://github.com/sgl-project/sglang/pull/49991) `[Perf] gdn: use window-sized ReplaySSM factors for direct spec decode` | perf | ? | - |
| - | [#49995](https://github.com/sgl-project/sglang/pull/49995) `[Refactor] [NPU] operators: Migrate sgl-kernel-npu calls to public operators entry points` | infra,perf | ? | - |
| - | [#50000](https://github.com/sgl-project/sglang/pull/50000) `[WIP] Kimi K3.1 Optimization` | perf | ? | - |
| - | [#50001](https://github.com/sgl-project/sglang/pull/50001) `[Fix] diffusion: honor explicit GPU IDs in monolithic workers` | bug,perf | ? | - |
| - | [#50010](https://github.com/sgl-project/sglang/issues/50010) `[Feature] Share CUDA graph eager preparation across capture shapes` | nvidia | ? | - |
| - | [#50014](https://github.com/sgl-project/sglang/pull/50014) `[Perf] cuda-graph: share eager preparation across capture shapes` | nvidia,perf | ? | - |
| - | [#50015](https://github.com/sgl-project/sglang/issues/50015) `[Bug] Multi-GB cudaHostRegister fails intermittently on fragmented hosts: GUP FOLL_LONGTERM order-10 exhaustio` |  | ? | - |
| - | [#50017](https://github.com/sgl-project/sglang/pull/50017) `[Feat] attention: Add ag_delay_reduce DCP backend for MLA and Triton GQA` | perf,rocm | ? | - |
| - | [#50020](https://github.com/sgl-project/sglang/pull/50020) `[Fix] [XPU] bailing: Do not force the CUDA rope kernel in DsV3MLA on XPU` | bug,nvidia,perf | ? | - |
| - | [#50021](https://github.com/sgl-project/sglang/pull/50021) `[Fix] nemotron: Apply the NemotronH defaults to Nemotron 3 Nano Omni` | bug,infra | ? | - |
| P1 | [#50024](https://github.com/sgl-project/sglang/pull/50024) `[Perf] [AMD] Qwen3.8-Flash-Next: Pack the FP8 GDN input projections on ROCm` | infra,perf,quant,rocm | ? | - |
| - | [#50025](https://github.com/sgl-project/sglang/pull/50025) `[Feat] Engram: Serve native tables from Mooncake MNNVL EGM` |  | ? | - |
| - | [#50026](https://github.com/sgl-project/sglang/pull/50026) `[Fix] diffusion: Restrict served post-processing model paths to an operator allowlist` | bug,perf | ? | - |
| - | [#50028](https://github.com/sgl-project/sglang/pull/50028) `[Chore] rust: Bump sglang-api-types to 0.1.1` | infra | ? | - |
| - | [#50029](https://github.com/sgl-project/sglang/pull/50029) `[Doc] cookbook: add reported H200 Qwen3.8-27B benchmarks` | nvidia,perf | ? | - |
| - | [#50030](https://github.com/sgl-project/sglang/issues/50030) `[Bug] --enable-hisparse fails at start-up for GLM-5.3-Flash: 'HybridLinearKVPool' object has no attribute 'reg` |  | ? | - |
| - | [#50031](https://github.com/sgl-project/sglang/pull/50031) `[Fix] multimodal: Honor encoder GPU preprocessing setting for video decoding` | bug | ? | - |
| - | [#50032](https://github.com/sgl-project/sglang/pull/50032) `[Perf] scheduler: Cut per-step host work in the batch-1 speculative decode loop` | infra,perf | ? | - |
| - | [#50035](https://github.com/sgl-project/sglang/pull/50035) `[Doc] cookbook: add reported DeepSeek-V4.1 B200/B300 benchmarks` | nvidia,perf | ? | - |
| - | [#50037](https://github.com/sgl-project/sglang/issues/50037) `[Bug] Qwen3.5 long-context prefill can produce NaNs in the Blackwell CuTe DSL GDN inverse kernel` | nvidia,perf | ? | - |
| - | [#50038](https://github.com/sgl-project/sglang/pull/50038) `[Fix] [NVIDIA] GDN: Prevent NaNs in Qwen3.5 long-context prefill` | bug,infra,nvidia,perf | ? | - |
| - | [#50042](https://github.com/sgl-project/sglang/pull/50042) `[Feat] grpc: Add opt-in api.v1 cancellation retirement receipts` | infra | ? | - |
| - | [#50043](https://github.com/sgl-project/sglang/pull/50043) `[Doc] docs: Fix indentation, spelling and formatting issues` | bug,quant | ? | - |
| - | [#50045](https://github.com/sgl-project/sglang/issues/50045) `SGLang 1.0 Release Tracker` | infra | ? | - |
| - | [#50046](https://github.com/sgl-project/sglang/pull/50046) `[Perf] hisparse: Keep long requests resident in HBM, add an elastic device pool and faster swap-in` | perf | ? | - |
| - | [#50047](https://github.com/sgl-project/sglang/pull/50047) `[Perf] hisparse: Remove the per-step host syncs from the scheduler-side swap-in bookkeeping` | perf | ? | - |
| - | [#50048](https://github.com/sgl-project/sglang/pull/50048) `[Feat] [XPU] Qwen3.8-flash-next: Use native QSA, PLE and HyperConnection kernels` | infra,nvidia,perf | ? | - |
| - | [#50049](https://github.com/sgl-project/sglang/pull/50049) `[Perf] dspark: Fold the static verify epilogue's commits into the accept tail and trim the verify-to-draft glu` | infra,perf | ? | - |
| - | [#50050](https://github.com/sgl-project/sglang/pull/50050) `[Perf] [AMD] muse-spark: Optimize prefill performance` | perf,rocm | ? | - |
| - | [#50051](https://github.com/sgl-project/sglang/pull/50051) `[Perf] scheduler: Send a finished request's last output before its prefix-cache insert and free its prompt ids` | infra,perf | ? | - |
| P1 | [#50054](https://github.com/sgl-project/sglang/pull/50054) `[AMD] Fix cross-layer KV sharing on ROCm: consumers zero the provider's cache` | bug,infra,perf,rocm | ? | - |
| - | [#50057](https://github.com/sgl-project/sglang/issues/50057) `tuning_block_wise_kernel.py cannot tune the [32, 32] block recipe (empty search space) and times candidates wi` | perf | ? | - |
| - | [#50058](https://github.com/sgl-project/sglang/pull/50058) `[Feat] [PPU] moe: Add Triton autotune configs for T-HEAD SAIL (PPU-ZW810E / ZW-M890P)` | perf,rocm | ? | - |
| - | [#50060](https://github.com/sgl-project/sglang/pull/50060) `[Feat] MLA: Enable combined PCP and DCP for DeepSeek dense MLA` |  | ? | - |
| - | [#50061](https://github.com/sgl-project/sglang/pull/50061) `[Perf] [NVIDIA] speculative: Fuse penalties, logit bias and temperature softmax in verify sampling` | nvidia,perf | ? | - |
| - | [#50062](https://github.com/sgl-project/sglang/pull/50062) `Default linear_attn_backend to intel_xpu for Qwen3.5-family GDN models on XPU` | nvidia | ? | - |
| - | [#50063](https://github.com/sgl-project/sglang/pull/50063) `[Fix] lang: Preserve `num_api_spec_tokens` in `SglFunction.bind` and init `SglExpr` base in `SglImage`/`SglVid` | bug | ? | - |
| - | [#50064](https://github.com/sgl-project/sglang/pull/50064) `[Perf] [NVIDIA] dsv4: Vectorize RoPE loads in SM100 decode attention` | nvidia,perf | ? | - |
| - | [#50065](https://github.com/sgl-project/sglang/pull/50065) `[Feat] muse_spark: Support expert TP (`--ep-size 1`) for NVFP4 checkpoints` | infra,quant | ? | - |
| - | [#50066](https://github.com/sgl-project/sglang/pull/50066) `[Feat] debug_utils: Tag non-intrusive dumps with speculative draft/ta…` |  | ? | - |
| - | [#50067](https://github.com/sgl-project/sglang/pull/50067) `[Perf] rust-server: Stream the request body through the DP relay` | infra,perf | ? | - |
| - | [#50068](https://github.com/sgl-project/sglang/pull/50068) `[Fix] [MUSA] vision: define flash_attn_func for the fa3 mm attention …` | bug,nvidia | ? | - |
| - | [#50069](https://github.com/sgl-project/sglang/pull/50069) `Perf [AMD] all-reduce: pick the kernel from a tune table` | perf,rocm | ? | - |
| - | [#50070](https://github.com/sgl-project/sglang/issues/50070) `[Bug] --grammar-backend llguidance/outlines with --reasoning-parser aborts structured output: no allocate_voca` |  | ? | - |
| - | [#50071](https://github.com/sgl-project/sglang/pull/50071) `[Fix] constrained: Add mask hooks to llguidance and outlines backends` | bug | ? | - |
| - | [#50072](https://github.com/sgl-project/sglang/pull/50072) `[Fix] [PPU] deep_gemm: do not fail sglang import when deep_gemm layout helpers are missing` | bug | ? | - |
| - | [#50073](https://github.com/sgl-project/sglang/issues/50073) `[Bug] collective_rpc unreliable` |  | ? | - |
| - | [#50074](https://github.com/sgl-project/sglang/pull/50074) `[Fix] moe: scale the KT routed output once when the top-k already folds the factor` | bug,quant | ? | - |
| - | [#50075](https://github.com/sgl-project/sglang/pull/50075) `[Fix] hisparse: Admit decode prompts against the logical pool` | bug | ? | - |
| - | [#50077](https://github.com/sgl-project/sglang/pull/50077) `[Perf] [AMD] diffusion: split large-K bf16 linears on gfx1151` | perf,rocm | ? | - |
| - | [#50078](https://github.com/sgl-project/sglang/pull/50078) `[Feat] [AMD] deterministic: Allow the dsa attention backend for GLM-5.3 on gfx950` | perf,rocm | ? | - |
| - | [#50079](https://github.com/sgl-project/sglang/pull/50079) `[Fix] [PPU] deep_gemm: adapt to T-HEAD SAIL DeepGEMM API surface` | bug | ? | - |
| - | [#50080](https://github.com/sgl-project/sglang/pull/50080) `[Fix] [AMD] deterministic: Run MXFP4 MoE experts through AITER's deterministic fused_moe` | bug,perf,quant,rocm | ? | - |
| - | [#50082](https://github.com/sgl-project/sglang/pull/50082) `[Fix] [PPU] flashmla: size MLA split buffers for SAIL and reject dense FP8` | bug,nvidia,quant | ? | - |
| P1 | [#50083](https://github.com/sgl-project/sglang/issues/50083) `[Tracking] Deterministic inference for GLM-5.3 on AMD MI350X / MI355X` | rocm | ? | - |
| - | [#50084](https://github.com/sgl-project/sglang/pull/50084) `[Perf] [NVIDIA] dflash: Batch native context KV writes across draft layers` | nvidia,perf | ? | - |
| - | [#50086](https://github.com/sgl-project/sglang/pull/50086) `[Feat] [PPU] quantization: add MXFP4 downcast kernels for T-HEAD SAIL` | perf,quant | ? | - |
| - | [#50087](https://github.com/sgl-project/sglang/issues/50087) `[Feature] Non-intrusive dumps cannot distinguish draft vs target model under DSPARK (both are TARGET_VERIFY)` |  | ? | - |
| - | [#50088](https://github.com/sgl-project/sglang/pull/50088) `[Fix] scheduler: Count the unprefilled part of a chunked request in total_tokens load` | bug,infra | ? | - |
| - | [#50089](https://github.com/sgl-project/sglang/pull/50089) `[Feat] [PPU] moe: add SAIL variant of the EP-MoE scatter kernel` | perf | ? | - |
| - | [#50090](https://github.com/sgl-project/sglang/pull/50090) `[Feat] [PPU] moe: add DeepGEMM MoE runner for T-HEAD SAIL` |  | ? | - |
| - | [#50091](https://github.com/sgl-project/sglang/issues/50091) `[Bug] [PPU] DeepSeek-V4.1 (fp4 experts) cannot be served on T-HEAD SAIL with main` | quant | ? | - |
| - | [#50092](https://github.com/sgl-project/sglang/pull/50092) `[Fix] health: Avoid startswith on a non-string request rid` | bug | ? | - |
| - | [#50093](https://github.com/sgl-project/sglang/pull/50093) `[Perf] [NVIDIA] diffusion/convrot: Fuse INT8 projection and rounded SwiGLU on SM120` | nvidia,perf,quant | ? | - |
| - | [#50094](https://github.com/sgl-project/sglang/pull/50094) `[Perf] [NVIDIA] mhc: allow the SM120 decode band on the compensated bf16x3 projection` | nvidia,perf | ? | - |
| - | [#50095](https://github.com/sgl-project/sglang/pull/50095) `[Fix] tuning_block_wise_kernel: Tune [32, 32] block recipes on CUDA` | bug,nvidia,perf | ? | - |
| P1 | [#50099](https://github.com/sgl-project/sglang/pull/50099) `[Perf] [AMD] deterministic: Allow AITER MLA decode on gfx950 with a fixed KV split count` | perf,rocm | ? | - |
| - | [#50100](https://github.com/sgl-project/sglang/issues/50100) `[Bug] Host validation accepts unsupported shapes in sigmoid_gate_topk_renorm, causing Triton static_assert fai` | rocm | ? | - |
| - | [#50103](https://github.com/sgl-project/sglang/issues/50103) `[Bug] Qwen3-VL on Hopper: the default prefill_decode_interval=22 lowers request throughput on long-prompt and ` | nvidia,perf | ? | - |
| - | [#50104](https://github.com/sgl-project/sglang/pull/50104) `AdaFlash 适配 SGLang NPU` | perf | ? | - |
| - | [#50106](https://github.com/sgl-project/sglang/pull/50106) `[Feat] cli: Export Cookbook commands for every config-driven LLM/VLM page` | infra,rocm | ? | - |
| - | [#50109](https://github.com/sgl-project/sglang/pull/50109) `[Feat] [AMD] attention: Enable AITER full and sliding-window unified memory` | perf,rocm | ? | - |
| - | [#50110](https://github.com/sgl-project/sglang/pull/50110) `[Fix] moe: Validate sigmoid gate padded axes before compilation` | bug,perf | ? | - |
| - | [#50111](https://github.com/sgl-project/sglang/pull/50111) `[Feat] HiCache: Support page_unified for DeepSeek V4/V4.1 and DSA pools` | infra | ? | - |
| - | [#50113](https://github.com/sgl-project/sglang/pull/50113) `[Perf] [AMD] smallm_moe_gfx950: MXFP4 kernels at 128 columns per rank` | perf,quant,rocm | ? | - |
| - | [#50116](https://github.com/sgl-project/sglang/pull/50116) `[Fix] mem_cache: Fix explicit HND initialization` | bug,infra | ? | - |
| - | [#50119](https://github.com/sgl-project/sglang/issues/50119) `[Bug] GLM-5.3 low/high reasoning_effort emits <\|assistant\|> after final answer and continues generating` |  | ? | - |
| - | [#50120](https://github.com/sgl-project/sglang/pull/50120) `[Perf] MiniMax-H3: overlap SubBlock attention with Ulysses communication` | infra,perf | ? | - |
| - | [#50121](https://github.com/sgl-project/sglang/pull/50121) `[Fix] openai: Accept MCP tools without descriptions` | bug | ? | - |
| - | [#50125](https://github.com/sgl-project/sglang/pull/50125) `[Fix] router: set TCP_NODELAY on accepted client sockets` | bug | ? | - |
| - | [#50127](https://github.com/sgl-project/sglang/pull/50127) `[Fix] openai: Answer /v1/models/{model} for the LoRA adapters /v1/models lists` | bug | ? | - |
| - | [#50128](https://github.com/sgl-project/sglang/pull/50128) `[Fix] responses: Treat "stream": null as a non-streaming request` | bug | ? | - |
| - | [#50129](https://github.com/sgl-project/sglang/pull/50129) `[Fix] [AMD] nightly: Detect skipped AMD nightly test jobs` | bug,rocm | ? | - |
| - | [#50130](https://github.com/sgl-project/sglang/issues/50130) `[Bug] hicache: short Mooncake zero-copy reads are accepted as full cache hits` | perf | ? | - |
| - | [#50131](https://github.com/sgl-project/sglang/issues/50131) `[Bug] responses: truncated or malformed tool call arguments are silently rewritten to {}` | risk | ? | - |
| - | [#50132](https://github.com/sgl-project/sglang/issues/50132) `[Bug] router: non-idempotent POSTs are replayed after connection close even when the worker may have consumed ` |  | ? | - |
| - | [#50133](https://github.com/sgl-project/sglang/pull/50133) `[Feat] KVShard: enable chunk wise allgather in kv cache sharding` | perf | ? | - |
| - | [#50138](https://github.com/sgl-project/sglang/issues/50138) `[Bug] --enable-deterministic-inference: Mamba-1 logprobs of a request depend on whether it is decoded alone or` |  | ? | - |
| - | [#50139](https://github.com/sgl-project/sglang/issues/50139) `[Bug] Session turn on a hybrid (Mamba/GDN) model keeps its state slot after admission is refused and later run` | perf | ? | - |
| - | [#50140](https://github.com/sgl-project/sglang/pull/50140) `[Feat] profiler: Emit the forward step span as an NVTX range` |  | ? | - |
| - | [#50141](https://github.com/sgl-project/sglang/pull/50141) `[Fix] lang: Fix OpenAI backend speculative pattern matching and select token usage` | bug | ? | - |
| - | [#50142](https://github.com/sgl-project/sglang/pull/50142) `[Fix] api-key: fall back to SGLANG_API_KEY / SGLANG_ADMIN_API_KEY env vars` | bug | ? | - |
| - | [#50143](https://github.com/sgl-project/sglang/pull/50143) `[Fix] scheduler: return a refused session turn's Mamba state slot` | bug,perf | ? | - |
| - | [#50145](https://github.com/sgl-project/sglang/pull/50145) `[Fix] scheduler: Make collective_rpc reliable with DP attention` | bug | ? | - |
| - | [#50148](https://github.com/sgl-project/sglang/pull/50148) `[Fix] batch_invariant_ops: Do not choose the matmul kernel by a.is_contiguous()` | bug,perf | ? | - |
| - | [#50149](https://github.com/sgl-project/sglang/issues/50149) `[Bug] dLLM with CUDA graphs: the first forward after an idle /flush_cache hits an illegal memory access and th` | bug,nvidia,risk | ? | - |
| - | [#50150](https://github.com/sgl-project/sglang/pull/50150) `[Feat] platforms: Let OOT platforms provide breakable graph backends (3/3)` | infra,perf | ? | - |
| - | [#50151](https://github.com/sgl-project/sglang/pull/50151) `[Perf] rust-server: Bound the crash recorder's memory and lock hold time` | bug,perf | ? | - |
| - | [#50152](https://github.com/sgl-project/sglang/pull/50152) `[Fix] function-call: Preserve field names when removing schema identifiers` | bug | ? | - |
| - | [#50153](https://github.com/sgl-project/sglang/pull/50153) `[Feat] simulator: Support harness-native activation` | infra | ? | - |
| - | [#50154](https://github.com/sgl-project/sglang/pull/50154) `[Feat] hicache: Publish KV events for completed L3 storage backups` | perf | ? | - |
| - | [#50155](https://github.com/sgl-project/sglang/pull/50155) `[Feat] sampling: Return sampling logprobs without the sampling mask` |  | ? | - |
| - | [#50160](https://github.com/sgl-project/sglang/pull/50160) `[Perf] [Apple] activation: Add a Metal SiLU-and-mul for the Torch MPS path` | perf | ? | - |
| - | [#50162](https://github.com/sgl-project/sglang/pull/50162) `[Test] entrypoints: Cover multi-worker API-key authentication` |  | ? | - |
| - | [#50163](https://github.com/sgl-project/sglang/pull/50163) `[Fix] scheduler: Deliver Engine.collective_rpc to every rank under DP attention` | bug | ? | - |
| - | [#50164](https://github.com/sgl-project/sglang/pull/50164) `[Perf] sampling: Keep bounded atomic stop regex windows finite` | perf | ? | - |
| - | [#50165](https://github.com/sgl-project/sglang/pull/50165) `[Fix] moe: Make simulated expert routing work on in-kernel routers` | bug,perf | ? | - |
| - | [#50166](https://github.com/sgl-project/sglang/pull/50166) `[Fix] [AMD] top-k: Avoid shared split workspace races` | bug,perf,rocm | ? | - |
| - | [#50167](https://github.com/sgl-project/sglang/pull/50167) `[Fix] router: gate the closed-connection POST replay behind a flag` | bug | ? | - |
| - | [#50168](https://github.com/sgl-project/sglang/pull/50168) `[Chore] deps: Bump OpenAI SDK to 2.8.0 in non-default pyprojects` | infra | ? | - |
| - | [#50171](https://github.com/sgl-project/sglang/issues/50171) `[Feat] docker: add backwards-compatible ENTRYPOINT to engine images` | infra | ? | - |
| - | [#50172](https://github.com/sgl-project/sglang/pull/50172) `[Feat] http_server: Compress response bodies for clients that accept zstd` |  | ? | - |
| - | [#50174](https://github.com/sgl-project/sglang/pull/50174) `Share an external DeepSeek-V4 target with the DSpark draft` |  | ? | - |
| - | [#50179](https://github.com/sgl-project/sglang/pull/50179) `[Fix] embedding: Normalize FP16 pooled embeddings in float32` | bug | ? | - |
| - | [#50180](https://github.com/sgl-project/sglang/pull/50180) `[Feat] dp-controller: Keep a routing key on one DP rank (--load-balance-method follow_routing_key)` |  | ? | - |
| - | [#50186](https://github.com/sgl-project/sglang/pull/50186) `[Feat] inkling2: Support Inkling-2-Small` | infra,nvidia,perf,quant | ? | - |
| - | [#50187](https://github.com/sgl-project/sglang/pull/50187) `[Feat] [AMD] model: Add Inkling-2-Small MI35x support` | nvidia,perf,rocm | ? | - |
| - | [#50188](https://github.com/sgl-project/sglang/pull/50188) `[Fix] weight-sync: [sglang-miles] Size the delta-apply pool by the cgroup CPU quota` | bug | ? | - |
| - | [#50191](https://github.com/sgl-project/sglang/pull/50191) `[Refactor] distributed: One PP relay for the HiCache, bootstrap and grammar PP syncs` | perf | ? | - |
| - | [#50192](https://github.com/sgl-project/sglang/pull/50192) `[Fix] lora: fix race between batch acquire and unload` | bug,risk | ? | - |
| - | [#50194](https://github.com/sgl-project/sglang/pull/50194) `[Fix] [NVIDIA] gemm: order the split-K epilogue kernel's cluster hand-offs as FlashInfer #7443 does, and let c` | bug,nvidia,perf | ? | - |
| - | [#50195](https://github.com/sgl-project/sglang/pull/50195) `[Fix] [NVIDIA] moe: keep the tuned autotune key for deferred-finalize FP4 TRT-LLM MoE calls` | bug,nvidia,perf,quant | ? | - |
| - | [#50200](https://github.com/sgl-project/sglang/pull/50200) `Reject remote media URLs resolving to non-global addresses` | perf | ? | - |
| - | [#50201](https://github.com/sgl-project/sglang/pull/50201) `[Fix] server: require POST for state-changing endpoints` | bug,rocm | ? | - |
| - | [#50202](https://github.com/sgl-project/sglang/pull/50202) `[Fix] multimodal: Prevent temporary ID recycling and shared-storage overcounting in estimate_cache_size_bytes` | bug | ? | - |
| - | [#50205](https://github.com/sgl-project/sglang/pull/50205) `[Feat] [NPU] deepseek-v4.1: Support Ascend A3 W8A8 inference and DSpark` | perf,quant | ? | - |
| - | [#50206](https://github.com/sgl-project/sglang/issues/50206) `[Bug] loader: Target GDS option leaks into a different draft loader` |  | ? | - |
| - | [#50207](https://github.com/sgl-project/sglang/pull/50207) `[Fix] loader: Isolate target GDS options from draft loaders` | bug | ? | - |
| - | [#50208](https://github.com/sgl-project/sglang/pull/50208) `[CI] [AMD] deps: Cache rebuilt AITER wheels per commit and arch` | infra,perf,rocm | ? | - |
| - | [#50209](https://github.com/sgl-project/sglang/pull/50209) `[Perf] [NVIDIA] attention: Use FlashMLA head64 for small sparse queries` | nvidia,perf | ? | - |
| - | [#50210](https://github.com/sgl-project/sglang/pull/50210) `[Fix] speculative: Validate draft window options at startup` | bug | ? | - |
| - | [#50211](https://github.com/sgl-project/sglang/pull/50211) `[Fix] dsa: Reject mixed TRTLLM FP8 KV backends` | bug,quant | ? | - |
| - | [#50212](https://github.com/sgl-project/sglang/pull/50212) `[Fix] jit_kernel: keep interior pointers into VMM host memory` | bug,perf | ? | - |
| - | [#50213](https://github.com/sgl-project/sglang/pull/50213) `[Feat] scheduler: Keep a reserve of KV and state slots for cached prefixes (--prefill-cache-reserve)` | infra,perf | ? | - |
| - | [#50214](https://github.com/sgl-project/sglang/pull/50214) `[Fix] [MUSA] fla: split the TRACK_STATE constexpr out of the runtime …` | bug,perf | ? | - |
| - | [#50216](https://github.com/sgl-project/sglang/pull/50216) `[Feat] sgl-kv-indexer: peer-L1 KVCM bindings and contract tests (stacked on #44460)` | infra | ? | - |
| - | [#50217](https://github.com/sgl-project/sglang/pull/50217) `[Feat] linker: pair async prefetch lookups with request release (stacked on #48820)` | infra,perf | ? | - |
| - | [#50220](https://github.com/sgl-project/sglang/pull/50220) `[Test] [AMD] sana-video2: Skip the BF16 softmax attention test when the build is not CUDA` | infra,nvidia,perf,rocm | ? | - |
| - | [#50221](https://github.com/sgl-project/sglang/issues/50221) `[Bug] one_batch crashes with --enable-dp-attention: int object has no attribute startswith` | bug | ? | - |
| - | [#50222](https://github.com/sgl-project/sglang/pull/50222) `[Fix] one_batch: Fix crash under DP attention from non-string rid` | bug | ? | - |
| - | [#50224](https://github.com/sgl-project/sglang/pull/50224) `[Fix] cpu: guard sgl_kernel imports behind try/except on GPU-less hosts` | bug,perf | ? | - |
| - | [#50225](https://github.com/sgl-project/sglang/pull/50225) `[Fix] lang: Send one output-length parameter from the OpenAI backend` | bug | ? | - |
| - | [#50226](https://github.com/sgl-project/sglang/pull/50226) `[Feat] cuda-graph: Support full prefill CUDA graphs for hybrid GDN models` | nvidia | ? | - |
| - | [#50227](https://github.com/sgl-project/sglang/pull/50227) `[Fix] cpu: wire --device cpu to the CPU-engine platform selection` | bug | ? | - |
| - | [#50228](https://github.com/sgl-project/sglang/pull/50228) `[Perf] [NVIDIA] gemma4: run the fused all-reduce sites for decode batches inside the decode CUDA graphs` | infra,nvidia,perf | ? | - |
| - | [#50229](https://github.com/sgl-project/sglang/pull/50229) `[Fix] weights: Stop reporting success after a TP update failure` | bug,infra | ? | - |
| - | [#50230](https://github.com/sgl-project/sglang/pull/50230) `[Fix] lora: Reject partial TP adapter loads and preserve cleanup IDs` | bug | ? | - |
| - | [#50232](https://github.com/sgl-project/sglang/pull/50232) `[Feat] muse_spark: support pipeline-parallel disaggregated DFLASH prefill` | perf | ? | - |
| - | [#50233](https://github.com/sgl-project/sglang/pull/50233) `[Feat] mem_cache: FlashStates integration for hybrid models: unit eviction, GreedyDual-Size, miss attribution,` | perf | ? | - |
| - | [#50235](https://github.com/sgl-project/sglang/pull/50235) `[Doc] hyperparameter-tuning: explain decode stalls from long prefills` | perf | ? | - |
| - | [#50236](https://github.com/sgl-project/sglang/pull/50236) `[Fix] mem_cache: Clamp the buffer_only anchor-lock cap by the model context length` | bug,infra,perf | ? | - |
| - | [#50238](https://github.com/sgl-project/sglang/pull/50238) `[Feat] [AMD] FLy: Support entropy-gated deferred verification for draft-model speculative decoding` | infra,perf,rocm | ? | - |
| - | [#50239](https://github.com/sgl-project/sglang/pull/50239) `[Feat] sgl-router: Add shape_aware policy and --dp-rank-policy` |  | ? | - |
| - | [#50240](https://github.com/sgl-project/sglang/pull/50240) `[Perf] scheduler: Avoid redundant tree work in dfs-weight scheduling` | perf | ? | - |
| - | [#50241](https://github.com/sgl-project/sglang/issues/50241) `[Tracking] Deterministic inference on AMD Instinct MI350X / MI355X (gfx950)` | rocm | ? | - |
| - | [#50242](https://github.com/sgl-project/sglang/pull/50242) `[Feat] sgl-router: Add runtime worker management API` |  | ? | - |
| - | [#50243](https://github.com/sgl-project/sglang/pull/50243) `[Feat] diffusion: Integrate FlashInfer Ulysses for Wan and MiniMax H3` | nvidia,perf | ? | - |
| - | [#50244](https://github.com/sgl-project/sglang/pull/50244) `[Perf] DFLASH: Verify top-k sampled batches on the all-gathered top-k support (opt-in)` | infra,perf | ? | - |
| - | [#50245](https://github.com/sgl-project/sglang/pull/50245) `[Fix] [NPU] gdn: Transpose [V, K] SSM states around chunk_gated_delta_rule_npu in TritonGDNKernel.extend` | bug | ? | - |
| - | [#50246](https://github.com/sgl-project/sglang/pull/50246) `[Refactor] transcription: Render speech-LM ASR prompts on the server with data-driven adapters` |  | ? | - |
| - | [#50247](https://github.com/sgl-project/sglang/pull/50247) `[Feat] diffusion: Accept a prebuilt AdaLN cache for MiniMax-H3 image` | perf | ? | - |
| - | [#50248](https://github.com/sgl-project/sglang/pull/50248) `[Perf] [NVIDIA] dsv4: Select V4.1 prefill index top-k with the fused ragged kernel` | nvidia,perf | ? | - |
| - | [#50249](https://github.com/sgl-project/sglang/issues/50249) `[Bug] [Intel] XPU: GDN chunk prefill 2.6x slower and wrong recompute_w_u output for K != V since #47944` | nvidia,perf | ? | - |
| - | [#50250](https://github.com/sgl-project/sglang/pull/50250) `[Feat] distributed: add torch fallback for variable-size collectives` | infra | ? | - |
| - | [#50251](https://github.com/sgl-project/sglang/pull/50251) `[Perf] [NVIDIA] fused_moe: add tuned Triton MoE configs for A100 80GB PCIe` | nvidia,perf,rocm | ? | - |
| - | [#50253](https://github.com/sgl-project/sglang/pull/50253) `[Feat] gdn: add opt-in cross-round DFLASH ReplaySSM commits` | perf | ? | - |
| - | [#50255](https://github.com/sgl-project/sglang/pull/50255) `[Fix] [Intel] attention: Restore 2D block I/O in the XPU FLA GDN kernels` | bug,nvidia,perf | ? | - |
| - | [#50256](https://github.com/sgl-project/sglang/pull/50256) `[Feat] diffusion: Add AdaLN tensor-parallel folding for MiniMax-H3` | perf | ? | - |
| - | [#50257](https://github.com/sgl-project/sglang/pull/50257) `[CI] chore: add CI permissions for amd-pedghazi` | infra,rocm | ? | - |
| - | [#50259](https://github.com/sgl-project/sglang/pull/50259) `[Perf] [NVIDIA] diffusion: Tune MiniMax-H3 online FP8 GEMM dispatch` | nvidia,perf,quant | ? | - |
| - | [#50261](https://github.com/sgl-project/sglang/pull/50261) `[Perf] sampler: Sum the captured probabilities without re-masking them` | perf | ? | - |
| - | [#50262](https://github.com/sgl-project/sglang/pull/50262) `[Perf] pooler: Avoid per-request GPU scalar reads in cross-encoder pooling` | perf | ? | - |
| - | [#50264](https://github.com/sgl-project/sglang/pull/50264) `[Fix][CPU] graph: Warm up eager model in prefill capture and register intel amx handler` | bug | ? | - |
| P0 | [#50265](https://github.com/sgl-project/sglang/pull/50265) `[Perf] [AMD] aiter: FP8 ASM prefill for GQA ratios the kernel lacks (e.g. 6) via KV-head repeat` | perf,quant,rocm | main | - |
| - | [#50269](https://github.com/sgl-project/sglang/pull/50269) `[Doc] [Intel] minimax-h3: add arch pro b70 recipe` |  | ? | - |
| - | [#50270](https://github.com/sgl-project/sglang/pull/50270) `[Feat] spec: support DMTP speculative decoding` |  | ? | - |
| - | [#50271](https://github.com/sgl-project/sglang/pull/50271) `[Perf] [AMD] multimodal_gen: opt-in Triton matmul for large bf16 linears on gfx1151` | perf,rocm | ? | - |
| - | [#50272](https://github.com/sgl-project/sglang/pull/50272) `[Fix] DSV4: count folded encoder-SWA replay rows in the prefill-graph DP vote` | bug | ? | - |
| - | [#50273](https://github.com/sgl-project/sglang/pull/50273) `[Fix] vision: Compute SDPA masks on GPU during graph capture` | bug | ? | - |
| - | [#50275](https://github.com/sgl-project/sglang/pull/50275) `[Feat] [MUSA] docker: Upgrade to Python 3.12 and torch 2.13` | infra,perf | ? | - |
| - | [#50276](https://github.com/sgl-project/sglang/pull/50276) `[Feat] [NVIDIA] dsa: Support GLM-5 family DCP with MTP on Hopper` | nvidia,perf | ? | - |
| - | [#50277](https://github.com/sgl-project/sglang/pull/50277) `[Fix] minicpmv: Set loader attributes such as shared_experts_config on the inner model` | bug,infra | ? | - |
| - | [#50278](https://github.com/sgl-project/sglang/pull/50278) `[Perf] rust-processor: Decode byte-level token pieces without table scans` | perf | ? | - |
| - | [#50279](https://github.com/sgl-project/sglang/pull/50279) `[Perf] watermark: Record decode contexts without dynamic CUDA indexing` | nvidia,perf | ? | - |
| - | [#50281](https://github.com/sgl-project/sglang/pull/50281) `[Perf] cuda_graph: Run one eager warmup per breakable prefill graph shape` | perf | ? | - |
| - | [#50282](https://github.com/sgl-project/sglang/pull/50282) `[Fix] kimi-k3: Keep streaming tool calls past malformed XTML` | bug | ? | - |
| - | [#50283](https://github.com/sgl-project/sglang/pull/50283) `[Perf] tokenizer: Skip TokenizersBackend retries when the checkpoint declares that class` | perf | ? | - |
| - | [#50284](https://github.com/sgl-project/sglang/pull/50284) `[Feat] processor: Stream Kimi-K3 tool-call arguments incrementally` |  | ? | - |
| - | [#50285](https://github.com/sgl-project/sglang/pull/50285) `[Fix] processor: Match SGLang's Kimi-K3 tool-call ids, grammars and K3 response format` | bug,infra | ? | - |
| - | [#50286](https://github.com/sgl-project/sglang/pull/50286) `[Fix] tensor_bridge: preserve lazy CPU view values when importing into MLX` | bug | ? | - |
| - | [#50287](https://github.com/sgl-project/sglang/pull/50287) `[Fix] DynamicGradMode: preserve context state across policy changes` | bug | ? | - |
| - | [#50288](https://github.com/sgl-project/sglang/pull/50288) `[Fix] layernorm: Follow live parameter dtype` | bug | ? | - |
| - | [#50290](https://github.com/sgl-project/sglang/pull/50290) `[Perf] rust-server: Avoid JSON roundtrips in streamed chat` | perf | ? | - |
| - | [#50291](https://github.com/sgl-project/sglang/pull/50291) `[Fix] ipc: Preserve unsupported values through the MessagePack fallback` | bug | ? | - |
| - | [#50292](https://github.com/sgl-project/sglang/pull/50292) `[Fix] openai: Keep tools callable under tool_choice=auto with a JSON response format` | bug | ? | - |
| - | [#50293](https://github.com/sgl-project/sglang/pull/50293) `[Perf] minimax_m3: Prebuild MSA-v1 JIT extensions in parallel during weight loading` | perf | ? | - |
| - | [#50294](https://github.com/sgl-project/sglang/pull/50294) `ci(npu): run PR test suite on Ascend CI runner labels [test-only]` | infra | ? | - |
| - | [#50295](https://github.com/sgl-project/sglang/pull/50295) `[Test] [NPU] rl: Phase 2 RL test coverage for routed experts, attention consistency, deterministic inference` |  | ? | - |
| - | [#50296](https://github.com/sgl-project/sglang/pull/50296) `[Perf] responses: Encode Harmony reasoning replay state only at completion` | perf | ? | - |
| - | [#50297](https://github.com/sgl-project/sglang/pull/50297) `[CI] [AMD] pr-test: Balance shards using measured runtimes` | infra,rocm | ? | - |
| - | [#50298](https://github.com/sgl-project/sglang/pull/50298) `[CI] [AMD] tests: Reuse the default OpenAI server across API cases` | infra,rocm | ? | - |
| - | [#50299](https://github.com/sgl-project/sglang/pull/50299) `[Fix] speculative: Reject unsupported DFLASH and DSpark step counts` | bug | ? | - |
| - | [#50301](https://github.com/sgl-project/sglang/pull/50301) `[Fix] diffusion: Reject unsupported ComfyUI model patches and transformer_blocks access early` | bug,perf | ? | - |
| - | [#50302](https://github.com/sgl-project/sglang/pull/50302) `[Fix] image: Honor patch limits for extreme aspect ratios` | bug | ? | - |
| - | [#50303](https://github.com/sgl-project/sglang/pull/50303) `[Fix] rotary: Apply CPU offsets once in the native fallback` | bug | ? | - |
| - | [#50304](https://github.com/sgl-project/sglang/pull/50304) `[Perf] hicache: Avoid unnecessary Mooncake lease renewals in Linker prefetch` | infra,perf | ? | - |
| - | [#50305](https://github.com/sgl-project/sglang/pull/50305) `ci(npu): run the NPU PR stages on the sglang fed runner labels` | infra | ? | - |
| - | [#50312](https://github.com/sgl-project/sglang/pull/50312) `[Fix] preprocessing: Account for retained buffers in cache budgets` | bug,perf | ? | - |
| - | [#50314](https://github.com/sgl-project/sglang/pull/50314) `[Perf] [NVIDIA] gdn: Use tuned chunk-H stages for long H20 prefill` | nvidia,perf | ? | - |
| - | [#50316](https://github.com/sgl-project/sglang/pull/50316) `[Fix] tokenizer: Register <\|assistant\|> as stop token ID for GLM-5.3` | bug | ? | - |
| - | [#50317](https://github.com/sgl-project/sglang/pull/50317) `[Feat] moe: Support tensor parallelism for Paged Experts` | infra | ? | - |
| - | [#50319](https://github.com/sgl-project/sglang/pull/50319) `[Fix] modelopt: reject incompatible mixed-precision shared-expert fusion` | bug,nvidia,perf,quant | ? | - |
| - | [#50320](https://github.com/sgl-project/sglang/pull/50320) `[Perf] all_reduce_fusion: Compile the cluster-size variants in parallel` | perf | ? | - |
| - | [#50322](https://github.com/sgl-project/sglang/pull/50322) `[Perf] engram: Extend all-to-all lookup to prefill CP` | perf | ? | - |
| - | [#50326](https://github.com/sgl-project/sglang/pull/50326) `[Perf] multimodal: Batch multi-span items across requests in one encoder call` | perf | ? | - |
| P0 | [#50327](https://github.com/sgl-project/sglang/pull/50327) `[Fix] [AMD] kvcache: Write V with its own head size in reshape_and_cache_flash` | bug,perf,rocm | main | - |
| - | [#50328](https://github.com/sgl-project/sglang/pull/50328) `[Fix] scheduler: Credit releasable private KV in priority preemption` | bug | ? | - |
| - | [#50329](https://github.com/sgl-project/sglang/pull/50329) `[Fix] gateway: Honor separate prefill and decode policies in gRPC PD routing` | bug | ? | - |
| - | [#50330](https://github.com/sgl-project/sglang/pull/50330) `[CI] [NPU] diffusion: Add MindIE-SD dependencies and RainFusion E2E coverage` | infra,perf | ? | - |
| - | [#50331](https://github.com/sgl-project/sglang/pull/50331) `[Feat] [Intel] diffusion: Keep sage_v3_bf16_blocks at BF16 in the DeepSymm ring` | perf | ? | - |
| - | [#50332](https://github.com/sgl-project/sglang/pull/50332) `[Feat] [Intel] diffusion: Load AutoRound MXFP8 (mx_fp W8A8) checkpoints on XPU` | nvidia,perf,quant | ? | - |
| - | [#50333](https://github.com/sgl-project/sglang/pull/50333) `[Fix] MMMU: Fail when a subject fails to load; parse options without eval` | bug | ? | - |
| - | [#50334](https://github.com/sgl-project/sglang/pull/50334) `[Perf] minimax_m3: Default prefill CUDA graphs to 8192 tokens` | nvidia,perf | ? | - |
| - | [#50335](https://github.com/sgl-project/sglang/pull/50335) `[Perf] [AMD] kimi-k3: Prefill-only FP8 copies of the dense BF16 linears` | perf,quant,rocm | ? | - |
| - | [#50336](https://github.com/sgl-project/sglang/issues/50336) `[RFC] Optimizing Large-Scale MoE Inference with Multi-GPU Partial Expert Offload` | perf,quant | ? | - |
| P1 | [#50337](https://github.com/sgl-project/sglang/pull/50337) `[Perf] [AMD] kimi-k3: Default SGLANG_K3_TARGET_DENSE_FP8 to wide on gfx950` | perf,rocm | ? | - |
| - | [#50338](https://github.com/sgl-project/sglang/pull/50338) `[Perf] minimax_m3: Default MXFP8 dense GEMMs to prebuilt CUTLASS outside decode servers` | nvidia,perf,quant | ? | - |
| - | [#50339](https://github.com/sgl-project/sglang/pull/50339) `[Feat] dsa: Run prims_ts over a 352 B/token NVFP4 KV cache` | nvidia,perf,quant | ? | - |
| - | [#50340](https://github.com/sgl-project/sglang/pull/50340) `[Fix] [AMD] all_reduce_mhc_hip: Import AITER CustomAllreduce only for type checking` | bug,infra,perf,rocm | ? | - |
| - | [#50341](https://github.com/sgl-project/sglang/pull/50341) `[Fix] flexkv: preserve MTP and DSpark draft state across cache replay` | bug,perf | ? | - |
| - | [#50342](https://github.com/sgl-project/sglang/pull/50342) `[Perf] model_loader: Prefetch checkpoint shards into the page cache by default` | perf | ? | - |
| - | [#50343](https://github.com/sgl-project/sglang/pull/50343) `[Fix] inkling: misc fixes` | bug,perf | ? | - |
| - | [#50344](https://github.com/sgl-project/sglang/pull/50344) `[Perf] pooler: Avoid rebuilding pooled hidden states before scoring` | perf | ? | - |
| - | [#50346](https://github.com/sgl-project/sglang/pull/50346) `[Perf] gdn: Fuse QKV layout conversion and QK L2 normalization` | perf | ? | - |
| - | [#50347](https://github.com/sgl-project/sglang/pull/50347) `ci(npu): concurrent NPU PR suite on Ascend CI runner labels [test-only]` | infra | ? | - |
| - | [#50349](https://github.com/sgl-project/sglang/pull/50349) `[Fix] multimodal: Fix single-frame partial video duration and preserve zero config values in MiMoProcessor` | bug | ? | - |
| - | [#50350](https://github.com/sgl-project/sglang/pull/50350) `[Feat] scheduler: Allow priority preemption under unified memory` |  | ? | - |
| - | [#50351](https://github.com/sgl-project/sglang/issues/50351) `[Bug] Download cache paths ignore TMPDIR` | perf | ? | - |
| - | [#50352](https://github.com/sgl-project/sglang/pull/50352) `[Perf] [NVIDIA] fp8: Add Triton block-fp8 GEMM configs for RTX PRO 6000 Server Edition` | nvidia,perf,quant,rocm | ? | - |
| - | [#50354](https://github.com/sgl-project/sglang/pull/50354) `[Feat] [AMD] tlx: Add the vendored gfx950 TLX GEMM and Muse MoE kernels on stock Triton via uTLX` | infra,perf,quant,rocm | ? | - |
| - | [#50355](https://github.com/sgl-project/sglang/pull/50355) `[Fix] sgl-router: Accept inline system messages in /v1/messages` | bug | ? | - |
| - | [#50356](https://github.com/sgl-project/sglang/pull/50356) `[Feat] [ARM] attention: Add Arm backend for compiled CPU decode` |  | ? | - |
| - | [#50359](https://github.com/sgl-project/sglang/pull/50359) `[Feat] [XPU] spec/uno: Support UNO speculative decoding on Intel XPU` | nvidia,perf | ? | - |
| - | [#50360](https://github.com/sgl-project/sglang/pull/50360) `[Fix] utils: Respect TMPDIR for download caches` | bug | ? | - |
| - | [#50361](https://github.com/sgl-project/sglang/pull/50361) `[Fix] utils: Handle videos with unavailable frame counts` | bug | ? | - |
| - | [#50362](https://github.com/sgl-project/sglang/pull/50362) `[Fix] openai: Give the multimodal processor the rendered chat prompt, not a decode of its ids` | bug | ? | - |
| - | [#50365](https://github.com/sgl-project/sglang/pull/50365) `[Fix] kda: Keep the exact intra-chunk diagonal for short prefills without a gate lower bound` | bug,perf | ? | - |
| - | [#50366](https://github.com/sgl-project/sglang/pull/50366) `[Fix] openai: Treat explicit null on defaulted request fields as omitted` | bug | ? | - |
| - | [#50367](https://github.com/sgl-project/sglang/pull/50367) `[Perf] [AMD] muse-spark: Add in-tree aiter BF16 GEMM rows for gfx950 TP8` | perf,rocm | ? | - |
| - | [#50375](https://github.com/sgl-project/sglang/pull/50375) `[Fix] scheduler: Avoid cancellation in dynamic chunk-size prediction` | bug | ? | - |
| - | [#50376](https://github.com/sgl-project/sglang/pull/50376) `[Fix] model_loader: Return replaced weights to the device after each post-load hook` | bug,quant | ? | - |
| - | [#50377](https://github.com/sgl-project/sglang/issues/50377) `[Bug]  qwen3_coder / granite_toolcall_parser: NaN/Infinity in array and object parameters give non-JSON argume` | bug,risk | ? | - |
| - | [#50378](https://github.com/sgl-project/sglang/pull/50378) `[CI] diffusion: Name the exact LoRA weight file in server test cases` | infra,perf | ? | - |
| - | [#50379](https://github.com/sgl-project/sglang/pull/50379) `[Fix] marlin: Load dense group scales and zero points at group boundaries` | bug,perf,quant | ? | - |
| - | [#50380](https://github.com/sgl-project/sglang/pull/50380) `[CI] Build and publish sglang-kernel cu134 wheels against torch 2.15.0` | infra,perf | ? | - |
| - | [#50381](https://github.com/sgl-project/sglang/pull/50381) `[CI] sgl-deep-gemm: Build and publish cu134 wheels against torch 2.15.0` | infra | ? | - |
| - | [#50382](https://github.com/sgl-project/sglang/pull/50382) `Build and publish sgl-deep-ep cu134 wheels against torch 2.15.0` | infra | ? | - |
| - | [#50383](https://github.com/sgl-project/sglang/pull/50383) `[CI] whl-release: Build sgl-flash-mla cu134 wheels against torch 2.15.0` | infra | ? | - |
| - | [#50384](https://github.com/sgl-project/sglang/pull/50384) `[Deps] Upgrade the CUDA PyTorch stack to 2.15 with CUDA 13.4 (cu134) wheels` | infra,nvidia | ? | - |
| - | [#50385](https://github.com/sgl-project/sglang/pull/50385) `[Feat] dp-controller: Add --load-balance-method prefix_aware to keep multi-turn sessions on their cached DP ra` |  | ? | - |
| - | [#50386](https://github.com/sgl-project/sglang/issues/50386) `[Bug] [AMD] INT8 W8A8 models fail on ROCm: `NameError: int8_scaled_mm` for compressed-tensors, `w8a8_int8` rej` | quant,rocm | ? | - |
| - | [#50395](https://github.com/sgl-project/sglang/issues/50395) `[Bug] NGRAM speculative decoding is not deterministic with --enable-deterministic-inference` |  | ? | - |

### sgl-amd-mono — Merged / closed (22 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#26](https://github.com/sgl-project/sgl-amd-mono/pull/26) `[Feat] [MI355X] muse_spark: Whole-layer monokernels for Muse Spark` | rocm | main | - |
| P0 | [#65](https://github.com/sgl-project/sgl-amd-mono/pull/65) `[Fix] deepseek_v41: Pass input_ids to SGLang's Engram so image rows stay in its gate` | bug | main | - |
| P0 | [#71](https://github.com/sgl-project/sgl-amd-mono/pull/71) `[Feat] [MI355X] glm53_flash: Serve MTP verify steps on the monokernel` | rocm | main | - |
| - | [#83](https://github.com/sgl-project/sgl-amd-mono/pull/83) `[Feat] [MI355X] qwen38_a95b_mxfp4: Run each decoder layer's tail as one K2 launch` | quant,rocm | ? | - |
| P0 | [#91](https://github.com/sgl-project/sgl-amd-mono/pull/91) `[Perf] [MI355X] deepseek_v41: Push gathered rows in whole 128 B lines` | perf,rocm | main | - |
| P0 | [#94](https://github.com/sgl-project/sgl-amd-mono/pull/94) `[Fix] glm53_flash: Read the KDA layer cache from the linear-attention backend` | bug,perf | main | - |
| P0 | [#97](https://github.com/sgl-project/sgl-amd-mono/pull/97) `[Fix] [MI355X] glm53_flash: Stop the sparse-attention fault on rows past 262,144 tokens` | bug,rocm | main | - |
| P0 | [#98](https://github.com/sgl-project/sgl-amd-mono/pull/98) `[Feat] [MI355X] glm53_flash: Run verify steps of up to 16 rows on the monokernel` | rocm | main | - |
| P0 | [#100](https://github.com/sgl-project/sgl-amd-mono/pull/100) `[Perf] [MI355X] glm53_flash: Score a verify request's index tiles once for its rows` | perf,rocm | main | - |
| - | [#107](https://github.com/sgl-project/sgl-amd-mono/pull/107) `[CI] ci: Run the PR review guideline's checks on dedicated MI355X nodes, per PR and nightly` | infra,rocm | ? | - |
| P0 | [#108](https://github.com/sgl-project/sgl-amd-mono/pull/108) `[Fix] [MI355X] kimi_k3: Size the warmup bank for the block-write row` | bug,rocm | main | - |
| P0 | [#110](https://github.com/sgl-project/sgl-amd-mono/pull/110) `[Fix] [MI355X] glm53: Keep uv's output tile inside the declared LDS` | bug,rocm | main | - |
| P1 | [#111](https://github.com/sgl-project/sgl-amd-mono/pull/111) `[Perf] [MI355X] kimi_k31: Make the routed experts' top-k, sort and mxfp8 quant in the wide launch` | perf,quant,rocm | ? | - |
| P1 | [#112](https://github.com/sgl-project/sgl-amd-mono/pull/112) `[Fix] [MI355X] kimi_k31: Follow SGLang's column-tail row cap in the wide launch's exit` | bug,rocm | ? | - |
| P1 | [#113](https://github.com/sgl-project/sgl-amd-mono/pull/113) `[Fix] [MI355X] kimi_k3/kimi_k31: Find a KDA layer's state through the backend's state_layer` | bug,rocm | ? | - |
| - | [#114](https://github.com/sgl-project/sgl-amd-mono/pull/114) `[Refactor] [MI355X] kimi_k31: Drop the wide launch's debug checks and A/B switches` | rocm | ? | - |
| P0 | [#116](https://github.com/sgl-project/sgl-amd-mono/pull/116) `[Perf] [MI355X] kimi_k31: Feed aiter's BM16 presort from the wide launch (aux16)` | perf,rocm | main | - |
| P1 | [#118](https://github.com/sgl-project/sgl-amd-mono/pull/118) `[Fix] deepseek_v41: Run the DSpark draft sampler and simulated accept on current SGLang` | bug | ? | - |
| - | [#119](https://github.com/sgl-project/sgl-amd-mono/pull/119) `[CI] ci: Add the CI maintainers as code owners of the workflows and scripts/ci` | infra | ? | - |
| - | [#121](https://github.com/sgl-project/sgl-amd-mono/pull/121) `[Fix] kimi_k3: Import require_mlp_sync from dp_attention on current SGLang` | bug | ? | - |
| - | [#124](https://github.com/sgl-project/sgl-amd-mono/pull/124) `[Fix] test: Import get_tokenizer and patch require_mlp_sync where current SGLang defines them` | bug | ? | - |
| - | [#130](https://github.com/sgl-project/sgl-amd-mono/pull/130) `[CI] ci: Let the run-ci label run the PR test on fork PRs` | infra | ? | - |

### sgl-amd-mono — Open / submitted (13 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#87](https://github.com/sgl-project/sgl-amd-mono/pull/87) `[Perf] [MI355X] deepseek_v41: Pipeline routed FFN-down FP4 weight loads through double-buffered LDS at TP2` | perf,quant,rocm | main | - |
| P0 | [#101](https://github.com/sgl-project/sgl-amd-mono/pull/101) `[Feat] common: Check each compiled kernel's residency and scratch where a runner builds it` | perf | main | - |
| - | [#109](https://github.com/sgl-project/sgl-amd-mono/pull/109) `[CI] ci: Pin the PR test's two runners to Crusoe v3-060 and v3-123` | infra | ? | - |
| P0 | [#115](https://github.com/sgl-project/sgl-amd-mono/pull/115) `[Perf] [MI355X] deepseek_v41: Cheaper attention and seam hand-offs, a lighter wo_b all-reduce, fewer index lau` | perf,rocm | main | - |
| P0 | [#117](https://github.com/sgl-project/sgl-amd-mono/pull/117) `[Perf] [MI355X] deepseek_v41: Run TP4 decode and verify steps of 49-256 rows on vLLM's asm layer kernels` | perf,rocm | kevin/dsv41-flags-engram-pv-tp8 | - |
| P1 | [#120](https://github.com/sgl-project/sgl-amd-mono/pull/120) `[Fix] deepseek_v41: Build the one-launch top-k against SGLang's top-k modes` | bug,infra | ? | - |
| P0 | [#122](https://github.com/sgl-project/sgl-amd-mono/pull/122) `[Fix] kimi_k3: Refuse a MoE front that is not bf16, such as SGLang's static FP8 front` | bug,perf,quant | main | - |
| - | [#127](https://github.com/sgl-project/sgl-amd-mono/pull/127) `[Feat] [MI355X] kimi_k3: Read the MoE front from bf16 copies kept at load when SGLang's is static FP8` | quant,rocm | ? | - |
| P1 | [#128](https://github.com/sgl-project/sgl-amd-mono/pull/128) `[Perf] [MI355X] deepseek_v41: Per-row MoE at TP8 and TP4, flagless wo_a/wo_b and q hand-offs, warmed kernargs,` | perf,rocm | ? | - |
| P1 | [#129](https://github.com/sgl-project/sgl-amd-mono/pull/129) `[Feat] [MI355X] glm53: Serve GLM-5.3 at TP2 (32 heads a rank), steps of up to 4 rows` | rocm | ? | - |
| P1 | [#132](https://github.com/sgl-project/sgl-amd-mono/pull/132) `[Feat] [MI355X] kimi_k3: Support FP8 attention and bf16 ReplaySSM state safely` | quant,rocm | ? | - |
| P0 | [#133](https://github.com/sgl-project/sgl-amd-mono/pull/133) `[Feat] [MI355X] glm53: Run verify steps of up to 16 rows on the monokernel` | rocm | main | - |
| P0 | [#134](https://github.com/sgl-project/sgl-amd-mono/pull/134) `[Fix] kimi_k31: Reject non-float32 SSM state for the wide monokernel` | bug | main | - |

### ATOM — Merged / closed (145 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#1400](https://github.com/ROCm/ATOM/issues/1400) `[Issue]: DeepSeek-V4-Flash Memory access fault under 64/128 concurrency with 3000+ requests` |  | ? | - |
| P1 | [#2364](https://github.com/ROCm/ATOM/pull/2364) `feat(sp): add Ulysses sequence parallelism and optimize M3 prefill communication` | infra,perf | ? | - |
| - | [#2453](https://github.com/ROCm/ATOM/pull/2453) `[1/3 entrypoint refactor] [feat(mesh)]: unify multi-API ingress for HTTP and ext-proc` | infra | ? | - |
| P0 | [#2489](https://github.com/ROCm/ATOM/pull/2489) `[gfx1250] Add ATOM_MLA_ABSORB_BF16: keep MLA-absorb weights in BF16` | rocm | main | - |
| - | [#2581](https://github.com/ROCm/ATOM/pull/2581) `feat(kimi-k3): DFlash GQA speculative draft model` | infra | ? | - |
| - | [#2582](https://github.com/ROCm/ATOM/pull/2582) `feat(spec-decode): probability-ratio rejection sampling behind draft_probs` | infra | ? | - |
| - | [#2598](https://github.com/ROCm/ATOM/pull/2598) `DeepSeek-V4.1-Flash: LMCache tier offload through the MP server (vLLM plugin)` | infra | ? | - |
| P0 | [#2655](https://github.com/ROCm/ATOM/pull/2655) `fix(qwen4-exp): register the QSA FP8 scale planes for KV offload` | bug,infra,quant | lingzha/qwen38-lmcache | - |
| P1 | [#2663](https://github.com/ROCm/ATOM/pull/2663) `feat(spec): capture the Qwen3.8 MTP draft steps in CUDA graphs (MRoPE)` | infra,nvidia | ? | - |
| - | [#2668](https://github.com/ROCm/ATOM/pull/2668) `fix(offload): refresh state images in LMCache's LRU on every tier hit and keep the index consistent` | bug,infra | ? | - |
| P0 | [#2691](https://github.com/ROCm/ATOM/pull/2691) `fix(mxfp4): pad an MLP pair's K inside the parallel linears; refuse an unaligned K at load` | bug,perf,quant | main | - |
| P1 | [#2707](https://github.com/ROCm/ATOM/pull/2707) `perf(qwen3.5): Triton top-k router + pad the 513-row MoE router weight to 528` | infra,perf,rocm | ? | - |
| - | [#2709](https://github.com/ROCm/ATOM/pull/2709) `feat(kimi-k3): PP8 P/D prefill 1/4 — PAGE-backed state checkpoints under PP` | infra | ? | - |
| P1 | [#2715](https://github.com/ROCm/ATOM/pull/2715) `[MLA] Plan a padded sparse MTP verify's work over the real tokens only` |  | ? | - |
| - | [#2721](https://github.com/ROCm/ATOM/pull/2721) `[MiniMax-M3.1] P/D from a PP4 prefill into a TP4 decode (1/2: KV transfer)` | infra | ? | - |
| - | [#2752](https://github.com/ROCm/ATOM/pull/2752) `[Offload] Support M3 PAGE layouts in Mooncake Store` | infra | ? | - |
| - | [#2755](https://github.com/ROCm/ATOM/pull/2755) `feat(dp): prefix-spread DP routing with native Mooncake Store recovery` | infra | ? | - |
| - | [#2762](https://github.com/ROCm/ATOM/pull/2762) `review-pr: port the automated PR-review pipeline from aiter as rocm-atom-bot (P0)` | infra,rocm | ? | - |
| P1 | [#2771](https://github.com/ROCm/ATOM/pull/2771) `perf(qwen4_exp): keep the PLE n-gram table in page-locked host memory, read over UVA` | infra,perf | ? | - |
| - | [#2808](https://github.com/ROCm/ATOM/pull/2808) `feat(deepseek_v41): fuse DSpark context-KV main_norm + group32 quantize_fp8` | perf,quant | ? | - |
| - | [#2809](https://github.com/ROCm/ATOM/pull/2809) `feat(indexer): migrate V4 and V4.1 FP4 scoring to the OPUS config API` | infra,quant | ? | - |
| - | [#2831](https://github.com/ROCm/ATOM/pull/2831) `feat(dsv41): fuse wo_a->wo_b mxfp8 quant into the batched GEMM epilogue` | perf,quant | ? | - |
| P1 | [#2847](https://github.com/ROCm/ATOM/pull/2847) `perf(qwen4_exp): Qwen3.8-Flash-Next TP prefill follow-ups: drafter FlyDSL QSA, row-sharded indexer selection, ` | infra,perf,rocm | ? | - |
| P1 | [#2864](https://github.com/ROCm/ATOM/issues/2864) `V4.1 compatibility: API completion, beta endpoints, and image support` |  | ? | - |
| P0 | [#2869](https://github.com/ROCm/ATOM/pull/2869) `[Qwen3.5] Fix NaN decoding from stale PAGE checkpoint bytes reused as KV` | bug,risk | alizaidy/gfx1250-qwen-support | - |
| P1 | [#2932](https://github.com/ROCm/ATOM/pull/2932) `fix(engram): serialize UVA registration across DP ranks and register in 1 GiB chunks` | bug,infra | ? | - |
| P1 | [#2933](https://github.com/ROCm/ATOM/pull/2933) `fix(dsv41): quantize the fused shared-expert activation for native MX w2` | bug,infra,perf,quant | ? | - |
| P1 | [#2938](https://github.com/ROCm/ATOM/pull/2938) `perf(kimi-k3): read a strided AttnRes block residual without copying it` | perf | ? | - |
| P1 | [#2962](https://github.com/ROCm/ATOM/pull/2962) `[MiniMax-M3.1] MXFP4 index cache and MXFP4 KV cache (--index-cache-dtype fp4, --kv-cache-dtype fp4)` | infra,perf,quant | ? | - |
| P1 | [#2985](https://github.com/ROCm/ATOM/pull/2985) `fix(ci): one local-model completeness check for SGLang/vLLM accuracy; new prefill CP flags; wait for SGLang wa` | bug,infra,risk | ? | - |
| P1 | [#2986](https://github.com/ROCm/ATOM/pull/2986) `fix(ci): run DeepSeek-V3.2-FP8 DP/EP on SGLang with ATOM_FUSE_SHARED_EXPERT=0` | bug,infra,perf,quant | ? | - |
| - | [#2987](https://github.com/ROCm/ATOM/pull/2987) `[ATOMesh][CI] Enable Kimi K3 WideEP DPA16/EP16 with MoRI EP and add MoRI cases into nightly runs` | infra | ? | - |
| - | [#2993](https://github.com/ROCm/ATOM/pull/2993) `fix(qwen38): mono draft fallback without a RoPE cache; QSA RoPE at ATOM's MRoPE positions` | bug,infra,perf | ? | - |
| P1 | [#3020](https://github.com/ROCm/ATOM/pull/3020) `perf(dsv41): fold the shared-expert add into the MoE TP all-reduce via HIP Lamport kernel` | infra,perf,rocm | ? | - |
| P1 | [#3023](https://github.com/ROCm/ATOM/pull/3023) `[fix] Kimi-K3.1 DSpark under PP: share the target's embedding on the last stage` | bug,infra | ? | - |
| P1 | [#3027](https://github.com/ROCm/ATOM/pull/3027) `fix(offload): key multimodal prompts by media, one LMCache engine id per server; a native MP restore has its o` | bug,infra | ? | - |
| P0 | [#3029](https://github.com/ROCm/ATOM/issues/3029) `vLLM plugin + ATOM offload: multimodal LMCache keys ignore the media, and two servers on one host share an eng` |  | ? | - |
| P0 | [#3034](https://github.com/ROCm/ATOM/pull/3034) `feat(minimax-m3): enable native 1x32 MXFP8 preshuffle GEMM` | infra,quant | main | - |
| - | [#3036](https://github.com/ROCm/ATOM/pull/3036) `feat(api): add DeepSeek's beta FIM and assistant-prefix completion` | infra | ? | - |
| P1 | [#3038](https://github.com/ROCm/ATOM/pull/3038) `[MiniMax-M3.1] P/D from a PP4 prefill into a TP4 decode (2/2: DSpark)` | infra | ? | - |
| P0 | [#3048](https://github.com/ROCm/ATOM/pull/3048) `[DCP] Add a `mailbox` decode merge backend on aiter's FlyDSL `dcp_lse_combine`` | infra,rocm | main | - |
| P0 | [#3051](https://github.com/ROCm/ATOM/issues/3051) `[Kimi-K3.1][DCP8] Long decodes collapse into repeated token 0 (`!!!!`) and later lose the prompt under TP8 + D` |  | ? | - |
| P1 | [#3052](https://github.com/ROCm/ATOM/pull/3052) `fix(attention): accept optional explicit FlyDSL plans` | bug,infra,rocm | ? | - |
| P1 | [#3059](https://github.com/ROCm/ATOM/pull/3059) `[Lumen-RL] Pause and resume generation; preempt before the KV pool or the weights change` | bug | ? | - |
| - | [#3060](https://github.com/ROCm/ATOM/pull/3060) `fix(qwen3): tie the LM head to the embedding's Parameter` | bug | ? | - |
| P1 | [#3061](https://github.com/ROCm/ATOM/pull/3061) `feat(api): hold Kimi-K3 tool calls to their schemas with the structured-output grammar` |  | ? | - |
| P1 | [#3062](https://github.com/ROCm/ATOM/pull/3062) `fix(ci): read the SGLang benchmark matrix from a file in the summary job` | bug,infra,perf | ? | - |
| P0 | [#3063](https://github.com/ROCm/ATOM/pull/3063) `fix(kimi-k3.1): include DSA index keys in offload` | bug,infra | main | - |
| P1 | [#3071](https://github.com/ROCm/ATOM/pull/3071) `ci: remove Atomesh TW weekly schedule` | infra | ? | - |
| P1 | [#3072](https://github.com/ROCm/ATOM/pull/3072) `fix(config): key the compile cache on max_num_batched_tokens and kv_cache_dtype` | bug,infra,perf | ? | - |
| P1 | [#3073](https://github.com/ROCm/ATOM/pull/3073) `fix(compile): format Inductor's implicit-fallback log text only when emitted` | bug,infra | ? | - |
| P1 | [#3075](https://github.com/ROCm/ATOM/pull/3075) `fix(moe): drop the missing-route clear from comm-fused MoE` | bug,infra,perf | ? | - |
| P1 | [#3076](https://github.com/ROCm/ATOM/pull/3076) `fix(moe): preserve invalid DP rows when reassigning shared experts` | bug,infra | ? | - |
| P1 | [#3078](https://github.com/ROCm/ATOM/issues/3078) `[Issue]: Scheduled regression reruns skip labelled benchmark variants and can suppress the [Perf Regression] i` | bug,perf | ? | - |
| - | [#3080](https://github.com/ROCm/ATOM/pull/3080) `[gfx1250][GDN] Prefill chain: conv1d, fused KKT+inverse, chunk_h, chunk_o closer to roofline` | perf,rocm | ? | - |
| - | [#3083](https://github.com/ROCm/ATOM/pull/3083) `feat(sampler): opt in to independent per-row sampling noise` |  | ? | - |
| - | [#3090](https://github.com/ROCm/ATOM/pull/3090) `feat(api): strict function tools on /beta/chat/completions (BETA-03)` | infra | ? | - |
| P1 | [#3091](https://github.com/ROCm/ATOM/pull/3091) `[DeepSeek-V4.1] High-interactivity monokernel decode for DeepSeek-V4.1-Flash on MI355X (TP4, DSpark)` | infra,rocm | ? | - |
| - | [#3092](https://github.com/ROCm/ATOM/issues/3092) `ATOM main broken by aiter PR#6952: pa_mqa_logits_mxfp4_plan removed` | quant,rocm | ? | - |
| P0 | [#3098](https://github.com/ROCm/ATOM/pull/3098) `fix(dspark): allocate k draft KV positions for block drafters, not k-1` | bug | main | - |
| - | [#3105](https://github.com/ROCm/ATOM/pull/3105) `Fix delayed P/D KV completion reporting during empty engine steps` | bug,infra | ? | - |
| - | [#3106](https://github.com/ROCm/ATOM/pull/3106) `fix(scheduler): stop bounding the delayer's fill probe by prompt length` | bug | ? | - |
| P0 | [#3108](https://github.com/ROCm/ATOM/pull/3108) `fix(attention): drop the FlyDSL paged-decode API probe` | bug,rocm | main | - |
| - | [#3109](https://github.com/ROCm/ATOM/pull/3109) `[DSV4.1][gfx1250] Single-launch decode step (FlyDSL)` | rocm | ? | - |
| - | [#3110](https://github.com/ROCm/ATOM/pull/3110) `[DSV4.1] Quantize the MXFP8 query 8 heads a program in the rope/window seam` | infra,quant | ? | - |
| - | [#3111](https://github.com/ROCm/ATOM/pull/3111) `fix(api): check and load Chat images in the server (IMAGE-03/04)` | bug,infra | ? | - |
| - | [#3113](https://github.com/ROCm/ATOM/pull/3113) `fix(tbo): release completed job before workers idle` | bug,infra | ? | - |
| - | [#3115](https://github.com/ROCm/ATOM/pull/3115) `feat(api): image input on /v1/responses and /v1/messages (IMAGE-02/06)` | infra | ? | - |
| - | [#3117](https://github.com/ROCm/ATOM/pull/3117) `Kimi-K3 plugin: LMCache MP offload with the KDA state riding the PAGE object` |  | ? | - |
| - | [#3121](https://github.com/ROCm/ATOM/pull/3121) `[CI][dashboard] AgentX / Non-AgentX dashboard with an InferenceX-style AgentX view` | infra | ? | - |
| - | [#3128](https://github.com/ROCm/ATOM/pull/3128) `perf(dsv41): widen the indexer block-maxima grid and use 128-wide candidate tiles` | infra,perf | ? | - |
| - | [#3132](https://github.com/ROCm/ATOM/pull/3132) `perf(dsv41): add the shared expert output in the MegaMoE combine on the mori v2 EP path` | infra,perf | ? | - |
| - | [#3136](https://github.com/ROCm/ATOM/pull/3136) `refactor(tbo): stage, publish and finish attention metadata once per micro-batch` | infra | ? | - |
| - | [#3137](https://github.com/ROCm/ATOM/pull/3137) `vllm-atom: GLM-5.3-Flash prefix caching and MTP on the plugin backend` | infra | ? | - |
| - | [#3141](https://github.com/ROCm/ATOM/pull/3141) `feat(mesh): routing decision observability 1/2 — decision metrics on the router port` | infra | ? | - |
| - | [#3142](https://github.com/ROCm/ATOM/pull/3142) `feat(mesh): routing decision observability 2/2 — sampled decision log, dispatched DP rank` |  | ? | - |
| - | [#3147](https://github.com/ROCm/ATOM/pull/3147) `feat(pd): bound decode admission by pending receive KV bytes` | infra | ? | - |
| - | [#3148](https://github.com/ROCm/ATOM/issues/3148) `Qwen3.8 mono: target and draft programs don't write the QSA RoPE position cache` | perf | ? | - |
| - | [#3153](https://github.com/ROCm/ATOM/pull/3153) `Add defense-in-depth guards for self-hosted runner jobs` |  | ? | - |
| - | [#3154](https://github.com/ROCm/ATOM/pull/3154) `ci: add ATOM test result gates` | infra | ? | - |
| - | [#3155](https://github.com/ROCm/ATOM/pull/3155) `fix(k3-offload): fence the in-process state store on the slot->PAGE copy` | bug | ? | - |
| - | [#3157](https://github.com/ROCm/ATOM/issues/3157) `Warm routed AITER plugin ops before capture_cudagraph(): decode-only ops are never reached by warmup_model()` | rocm | ? | - |
| - | [#3160](https://github.com/ROCm/ATOM/issues/3160) `Qwen3.8 QSA prefill: 'context_lens must contain N entries' at concurrency > 6 since #3136` |  | ? | - |
| P1 | [#3167](https://github.com/ROCm/ATOM/pull/3167) `fix(qwen4_exp): page QSA through the scheduled requests' block-table rows` | bug,infra | ? | - |
| - | [#3168](https://github.com/ROCm/ATOM/pull/3168) `docs(readme): add the ATOM Meets Mooncake blog to News` |  | ? | - |
| - | [#3169](https://github.com/ROCm/ATOM/pull/3169) `fix(v4): run V4's TBO comm stream at high priority` | bug,infra | ? | - |
| - | [#3170](https://github.com/ROCm/ATOM/pull/3170) `docs(readme): add the FlyDSL mono kernels blog to News` | perf,rocm | ? | - |
| - | [#3171](https://github.com/ROCm/ATOM/pull/3171) `fix(runner): reconcile KV block counts across TP and PCP-group workers` | bug,infra | ? | - |
| - | [#3177](https://github.com/ROCm/ATOM/issues/3177) `DSV4.1-Flash crash on gfx1250: hidden_states is None in postprocess after V4.1 single-launch step` | bug,rocm | ? | - |
| - | [#3181](https://github.com/ROCm/ATOM/pull/3181) `docker: bump Mooncake to kvcache-ai/Mooncake@206d634 (THP-backed RDMA Store segments)` | infra | ? | - |
| - | [#3182](https://github.com/ROCm/ATOM/pull/3182) `test(dspark): pass the block pass to _stage_anchors in the served-step test` |  | ? | - |
| P0 | [#3184](https://github.com/ROCm/ATOM/pull/3184) `fix(qwen38): mono target and draft programs write the QSA RoPE position cache` | bug,perf | main | - |
| - | [#3185](https://github.com/ROCm/ATOM/pull/3185) `[DSV4.1][gfx1250] Fix the crash on a single-launch served step: no hidden states for the drafter's ids (#3177)` | bug,infra,rocm | ? | - |
| P1 | [#3189](https://github.com/ROCm/ATOM/pull/3189) `fix(plugin): start DeepSeek-V4.1 on the vLLM plugin again after #3136` | bug | ? | - |
| P0 | [#3192](https://github.com/ROCm/ATOM/issues/3192) `[Qwen3.8 mono] With FlyDSL 0.5.0, every MonoKernel.launch re-traces the whole program, so decode is ~300x slow` | perf,rocm | ? | - |
| - | [#3204](https://github.com/ROCm/ATOM/pull/3204) `docs(recipes): refresh the DeepSeek-V4.1-Flash agentic recipe settings` |  | ? | - |
| - | [#3216](https://github.com/ROCm/ATOM/pull/3216) `dp_routing follow-up: prefix_spread single lookup walk + radix re-merge, dp_routing package` |  | ? | - |
| - | [#3217](https://github.com/ROCm/ATOM/pull/3217) `scheduler: re-rank waiting only on a load event; preempt and parked partials queue behind settled offload resu` | infra | ? | - |
| - | [#3218](https://github.com/ROCm/ATOM/pull/3218) `ci: run the agentic benchmarks on the pitt MI350X pool` | infra,perf,rocm | ? | - |
| P0 | [#3226](https://github.com/ROCm/ATOM/pull/3226) `fix(mono): launch the Qwen3.8 and DeepSeek-V4.1 hi programs through their compiled functions` | bug | main | - |
| - | [#3229](https://github.com/ROCm/ATOM/pull/3229) `prefix_spread: trim/evict counters and the budget trade-off (follow-up to #3216)` | infra | ? | - |
| - | [#3230](https://github.com/ROCm/ATOM/pull/3230) `ci(vllm): benchmark the PR CI models at the SGLang concurrencies, drop GLM-5.2-MXFP4-MTP` | infra,perf,quant | ? | - |
| - | [#3232](https://github.com/ROCm/ATOM/pull/3232) `ci(mesh): skip the mocker benchmark and empty accuracy runs on PRs, fix the mocker cargo cache` | bug,infra,perf,risk | ? | - |
| - | [#3233](https://github.com/ROCm/ATOM/pull/3233) `docs(recipes): match the DeepSeek-V4.1-Flash agentic recipe to the InferenceX config` | infra | ? | - |
| P1 | [#3237](https://github.com/ROCm/ATOM/pull/3237) `fix(qwen38): use aiter's FlyDSL QSA prefill scorer instead of the vendored copy` | bug,rocm | ? | - |
| P1 | [#3240](https://github.com/ROCm/ATOM/issues/3240) `Kimi-K3.1 prefill: a 16K chunk as fast as SGLang's (1164 ms vs 837 ms)` |  | ? | - |
| - | [#3241](https://github.com/ROCm/ATOM/issues/3241) `Bring ROCm/ATOM#3042 and #3099 into whx/k31-perf for recipe F8` | perf,rocm | ? | - |
| - | [#3242](https://github.com/ROCm/ATOM/issues/3242) `Kimi-K3.1 16K prefill benchmark harness` | perf | ? | - |
| - | [#3243](https://github.com/ROCm/ATOM/issues/3243) `Kimi-K3.1 DCP sparse prefill at its native 96 heads` |  | ? | - |
| - | [#3244](https://github.com/ROCm/ATOM/issues/3244) `Split Kimi-K3.1's KDA in_proj GEMM at prefill sizes` |  | ? | - |
| - | [#3245](https://github.com/ROCm/ATOM/issues/3245) `Plan the DCP sparse MLA prefill work once per forward` |  | ? | - |
| - | [#3246](https://github.com/ROCm/ATOM/issues/3246) `Row-sharded MoE tail for Kimi-K3.1 prefill` |  | ? | - |
| - | [#3247](https://github.com/ROCm/ATOM/issues/3247) `Head-major all-to-all for the DCP sparse prefill output` |  | ? | - |
| - | [#3248](https://github.com/ROCm/ATOM/issues/3248) `Row-sharded attention residual before each Kimi-K3.1 MoE` |  | ? | - |
| - | [#3249](https://github.com/ROCm/ATOM/issues/3249) `Kimi-K3.1 AgentX c16 end to end at the integration tip` |  | ? | - |
| - | [#3250](https://github.com/ROCm/ATOM/issues/3250) `Preallocated block-residual bank for Kimi-K3.1` |  | ? | - |
| - | [#3253](https://github.com/ROCm/ATOM/pull/3253) `Bring ROCm/ATOM#3042 and ROCm/ATOM#3099 into whx/k31-perf for recipe F8` | perf,rocm | ? | - |
| - | [#3264](https://github.com/ROCm/ATOM/pull/3264) `Add a Kimi-K3.1 16K prefill profiling harness with a per-layer trace parser` |  | ? | - |
| - | [#3268](https://github.com/ROCm/ATOM/pull/3268) `Split Kimi-K3.1's KDA in_proj GEMM at prefill sizes` |  | ? | - |
| - | [#3270](https://github.com/ROCm/ATOM/pull/3270) `Read ReplaySSM's KDA beta in place instead of copying it` |  | ? | - |
| - | [#3272](https://github.com/ROCm/ATOM/pull/3272) `Run Kimi-K3.1 DCP sparse prefill at its native 96 gathered heads` |  | ? | - |
| - | [#3273](https://github.com/ROCm/ATOM/pull/3273) `Add a column-sharded latent tail op for Kimi-K3.1 decode` |  | ? | - |
| - | [#3277](https://github.com/ROCm/ATOM/pull/3277) `feat(kv_events): serve each DP rank's publisher at /kv_event_sources` |  | ? | - |
| - | [#3278](https://github.com/ROCm/ATOM/pull/3278) `Describe Kimi-K3.1's split KDA in_proj in its comments` |  | ? | - |
| - | [#3280](https://github.com/ROCm/ATOM/pull/3280) `Add a Kimi-K3.1 decode profiling harness with a per-layer trace parser` |  | ? | - |
| - | [#3281](https://github.com/ROCm/ATOM/pull/3281) `Row-shard Kimi-K3.1's latent MoE tail on large prefill steps` |  | ? | - |
| - | [#3282](https://github.com/ROCm/ATOM/pull/3282) `Plan Kimi-K3.1 DCP sparse prefill MLA work once a forward` |  | ? | - |
| - | [#3283](https://github.com/ROCm/ATOM/pull/3283) `Fuse Kimi-K3 KDA decode conv1d, f_b_proj and ReplaySSM into one kernel` | perf | ? | - |
| P0 | [#3284](https://github.com/ROCm/ATOM/pull/3284) `Store a flushing ReplaySSM step's k / g records after every V slice replays them` |  | whx/k31-perf | - |
| - | [#3285](https://github.com/ROCm/ATOM/issues/3285) `DSV4.1-Flash DEP4 crash: hipErrorInvalidValue in DSPark compute_draft_kv on gfx1250` | bug,rocm | ? | - |
| - | [#3286](https://github.com/ROCm/ATOM/pull/3286) `Send the Kimi-K3.1 DCP sparse prefill output to the all-to-all head-major` |  | ? | - |
| P1 | [#3287](https://github.com/ROCm/ATOM/pull/3287) `Row-shard Kimi-K3.1's latent MoE tail only from 8192 tokens` |  | ? | - |
| - | [#3288](https://github.com/ROCm/ATOM/pull/3288) `Row-shard Kimi-K3.1's attention residual before each MoE on large prefill steps` |  | ? | - |
| - | [#3291](https://github.com/ROCm/ATOM/pull/3291) `Gather the DCP decode top-k candidates on the last dim` |  | ? | - |
| - | [#3292](https://github.com/ROCm/ATOM/pull/3292) `review-pr: make a failed review's notice prove it landed` |  | ? | - |
| - | [#3294](https://github.com/ROCm/ATOM/pull/3294) `Add a long-prompt logprob A/B tool for Kimi-K3.1 prefill changes` | bug | ? | - |
| - | [#3295](https://github.com/ROCm/ATOM/pull/3295) `ci: ignore review bot files for heavy test gates` | infra | ? | - |
| - | [#3303](https://github.com/ROCm/ATOM/pull/3303) `Allocate Kimi-K3.1's block-residual bank once per forward` |  | ? | - |
| - | [#3314](https://github.com/ROCm/ATOM/pull/3314) `Send the DCP sparse prefill output all-to-all in FP8 behind ATOM_DCP_PREFILL_A2A_FP8` | quant | ? | - |
| - | [#3317](https://github.com/ROCm/ATOM/pull/3317) `Leave the row-sharded MoE layers' zero addends unwritten` |  | ? | - |
| P1 | [#3319](https://github.com/ROCm/ATOM/pull/3319) `Overlap the DSA indexer's top-k exchange with the q path` | bug,perf | ? | - |
| - | [#3320](https://github.com/ROCm/ATOM/pull/3320) `Run Kimi-K3.1's MoE front linears as one BF16 GEMM` |  | ? | - |
| - | [#3327](https://github.com/ROCm/ATOM/pull/3327) `Hoist the DCP indexer FP4 staging's OPUS scale index into the metadata builder` | quant | ? | - |
| - | [#3329](https://github.com/ROCm/ATOM/pull/3329) `Reduce Kimi-K3.1's latent and shared MoE partials with one all-reduce` |  | ? | - |
| - | [#3331](https://github.com/ROCm/ATOM/pull/3331) `Run Kimi-K3.1's ReplaySSM KDA decode and verify through the fused op` | perf | ? | - |

### ATOM — Open / submitted (96 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#2842](https://github.com/ROCm/ATOM/pull/2842) `fix(state checkpoints): keep block 0 a zero null page and zero released PAGE units` | bug,infra | main | - |
| P0 | [#2980](https://github.com/ROCm/ATOM/pull/2980) `feat(k3-mono): read FP8 dense projections in place` | quant | main | - |
| P1 | [#3046](https://github.com/ROCm/ATOM/pull/3046) `[API] Offloaded chat preparation reuses a session's earlier turns (ATOM_API_OFFLOAD_TOKENIZE_CACHE_MB)` |  | ? | - |
| P1 | [#3047](https://github.com/ROCm/ATOM/issues/3047) `[Perf Regression] 23 config(s) regressed @ 64412f10` | bug,perf | ? | - |
| P1 | [#3049](https://github.com/ROCm/ATOM/pull/3049) `perf(minimax-m3): quantize the dense MLP activation in the SwiGLU kernel` | perf,quant | ? | - |
| P1 | [#3053](https://github.com/ROCm/ATOM/pull/3053) `feat(kimi-k3): fuse o_proj's E8M0 activation quant into the KDA gated norm` | perf,quant | ? | - |
| P1 | [#3054](https://github.com/ROCm/ATOM/pull/3054) `feat(kimi-k3): fold the consumer's E8M0 activation quant into the attention residual` | quant | ? | - |
| P1 | [#3064](https://github.com/ROCm/ATOM/pull/3064) `[MiniMax-M3.1] Windowed DSpark draft KV (1/4): the scheduler's window pool` |  | ? | - |
| P1 | [#3065](https://github.com/ROCm/ATOM/pull/3065) `[MiniMax-M3.1] Windowed DSpark draft KV (2/4): the block pass reads and writes through a windowed table` |  | ? | - |
| P1 | [#3066](https://github.com/ROCm/ATOM/pull/3066) `[MiniMax-M3.1] Windowed DSpark draft KV (3/4): send only the consumer's window over Mooncake P/D` |  | ? | - |
| - | [#3081](https://github.com/ROCm/ATOM/pull/3081) `[DO NOT MERGE] [gfx1250][GDN] Prefill chain: conv1d, fused KKT+inverse, chunk_h, chunk_o closer to roofline` | perf,rocm | ? | - |
| - | [#3082](https://github.com/ROCm/ATOM/pull/3082) `Share the DeepSeek-V4 target with SGLang's DSpark draft` |  | ? | - |
| - | [#3084](https://github.com/ROCm/ATOM/pull/3084) `[SP] Fuse the MiniMax-M3 QKV GEMM with the Ulysses exchange via AITER gemm_fusion` | bug,perf,rocm | ? | - |
| - | [#3085](https://github.com/ROCm/ATOM/pull/3085) `[Qwen3.5 MTP] Draft argmax under the presence penalty + FP8 draft LM head (stacked on #3045)` | quant | ? | - |
| - | [#3086](https://github.com/ROCm/ATOM/pull/3086) `[Engine] ATOM_EARLY_PREFILL_SCHEDULE on independent DP ranks (measured slower on Qwen3.5 DP4; flag stays off)` | perf | ? | - |
| - | [#3087](https://github.com/ROCm/ATOM/pull/3087) `refactor(mono): set FlyDSL's target arch through FLYDSL_GPU_ARCH only` | infra,rocm | ? | - |
| - | [#3088](https://github.com/ROCm/ATOM/pull/3088) `[Docs] Add contributing guide, area contacts and review guide` |  | ? | - |
| P1 | [#3089](https://github.com/ROCm/ATOM/issues/3089) `[Perf Regression] 11 config(s) regressed @ 6d22f7db` | bug,perf | ? | - |
| - | [#3093](https://github.com/ROCm/ATOM/pull/3093) `[Qwen3.5 MTP] Decode-step trims: host token split, one-shot split reduce, one-kernel verify epilogue, Gluon sa` | perf,rocm | ? | - |
| P0 | [#3094](https://github.com/ROCm/ATOM/issues/3094) `[Perf Regression] 13 config(s) regressed @ 6d22f7db` | bug,perf | ? | - |
| P0 | [#3095](https://github.com/ROCm/ATOM/issues/3095) `[Issue]: [DeepSeek-V4] TP ranks select MoE experts from their own replicated router logits and can disagree on` | rocm | ? | - |
| - | [#3096](https://github.com/ROCm/ATOM/issues/3096) `[Perf Regression] 7 config(s) regressed @ 6d22f7db` | bug,perf | ? | - |
| - | [#3100](https://github.com/ROCm/ATOM/pull/3100) `[kv_transfer] lmcache_mp: pass optional LMCache ATOM adapter arguments` | infra | ? | - |
| - | [#3101](https://github.com/ROCm/ATOM/pull/3101) `[feature] add leapquant gdn ` | quant | ? | - |
| P1 | [#3102](https://github.com/ROCm/ATOM/pull/3102) `feat(dsv41): DeepSeek-V4.1-Flash on MI308X (gfx942)` | infra,rocm | ? | - |
| - | [#3114](https://github.com/ROCm/ATOM/pull/3114) `feat(gemm_fusion): route MiniMax-M3 SP QKV through aiter.sp_qkv_fused (on #3084)` | perf,rocm | ? | - |
| P0 | [#3120](https://github.com/ROCm/ATOM/issues/3120) `GLM-5.3-Flash with bf16 KV: aiter MLA decode misreads KV stored past 4 GiB of a layer's cache` | perf,rocm | ? | - |
| - | [#3123](https://github.com/ROCm/ATOM/issues/3123) `[Bug] Qwen3.8-Flash-Next (qwen4_exp) image prompts crash on a prefix-cache hit inside or past an image` | bug,perf | ? | - |
| - | [#3124](https://github.com/ROCm/ATOM/pull/3124) `fix(api): keep structured-output extras optional at startup` | bug | ? | - |
| - | [#3125](https://github.com/ROCm/ATOM/pull/3125) `[kv_transfer] lmcache_mp: name prompts by LMCache chunk hashes, not tokens` | infra | ? | - |
| - | [#3127](https://github.com/ROCm/ATOM/pull/3127) `perf(dsv41): fuse the quantized-pool compress tail into one Triton kernel` | infra,perf,quant,rocm | ? | - |
| - | [#3134](https://github.com/ROCm/ATOM/pull/3134) `perf(dspark): fused Markov chain for larger batches; bonus sampling on a side stream` | infra,perf | ? | - |
| - | [#3139](https://github.com/ROCm/ATOM/pull/3139) `perf(dspark): vocab-split probabilistic verification` | infra,perf | ? | - |
| - | [#3144](https://github.com/ROCm/ATOM/pull/3144) `[GFX1250][MOE]iod weight preshuffle` | rocm | ? | - |
| - | [#3145](https://github.com/ROCm/ATOM/pull/3145) `[MI355X] feat(diffusion): Wan2.1 VAE with conv3d dispatched to AITER FlyDSL` | perf,rocm | ? | - |
| - | [#3149](https://github.com/ROCm/ATOM/issues/3149) `[ROCm Product Quality Control]: Weekly Kimi Vendor Verifier (KVV) accuracy regression testing on AMD ATOM` | bug,risk,rocm | ? | - |
| - | [#3151](https://github.com/ROCm/ATOM/pull/3151) `[Config] Resolve parallel mapping before worker initialization` | infra | ? | - |
| P1 | [#3156](https://github.com/ROCm/ATOM/pull/3156) `feat(dsv41): run gfx942 post seams on AITER's ASM mHC seam` | rocm | ? | - |
| P1 | [#3159](https://github.com/ROCm/ATOM/pull/3159) `fix(api): take Kimi-K3 chat prompt ids from its tokenizer's segment encoder` | bug | ? | - |
| P1 | [#3164](https://github.com/ROCm/ATOM/pull/3164) `[DSV4.1] Fuse the FP8 shared expert into the MXFP4 MoE under ATOM_FUSE_MXFP8_SHARED_INTO_MXFP4` | perf,quant | ? | - |
| P0 | [#3175](https://github.com/ROCm/ATOM/issues/3175) `[Perf Regression] 3 config(s) regressed @ 724f7bf4` | bug,perf | ? | - |
| - | [#3176](https://github.com/ROCm/ATOM/pull/3176) `[DSV4.1][gfx1250] Extend single-launch decode to C16 with FP8 KV / FP4 index caches` | quant,rocm | ? | - |
| - | [#3178](https://github.com/ROCm/ATOM/pull/3178) `[Qwen3.5] FHMoE: the shared expert inside the gfx1250 grouped MoE (flag off; stacked on #3093)` | rocm | ? | - |
| - | [#3186](https://github.com/ROCm/ATOM/pull/3186) `feat(dsv41): EPLB on the layers before the decoder` | infra | ? | - |
| P0 | [#3187](https://github.com/ROCm/ATOM/pull/3187) `[MoE] MegaMoE: let AITER pick small/large/staged routes from the DP-group max rows; single-stream shared exper` | rocm | main | - |
| - | [#3188](https://github.com/ROCm/ATOM/pull/3188) `perf(engram): tune quantized UVA lookup geometry on gfx1250` | perf,quant,rocm | ? | - |
| - | [#3190](https://github.com/ROCm/ATOM/issues/3190) `vLLM plugin refactor: design` |  | ? | - |
| - | [#3193](https://github.com/ROCm/ATOM/pull/3193) `perf(dcp): merge decode partials with aiter's fused DCP merge when the group has one` | perf,rocm | ? | - |
| - | [#3194](https://github.com/ROCm/ATOM/pull/3194) `[Offload] umbp_store: KV offload over a Mori UMBP standalone server` | infra | ? | - |
| P1 | [#3195](https://github.com/ROCm/ATOM/pull/3195) `[MiniMax-M3.1] One-launch decode router (GEMV + top-4 gate + MoE sort) on gfx950` | rocm | ? | - |
| - | [#3196](https://github.com/ROCm/ATOM/pull/3196) `fix(scheduler): a DP prefill rank whose cost sets the step's target prefills its chunk whole` | bug | ? | - |
| - | [#3197](https://github.com/ROCm/ATOM/pull/3197) `fix(graphs): a token-graph recording keeps no argument its region takes live` | bug | ? | - |
| - | [#3198](https://github.com/ROCm/ATOM/pull/3198) `[MiniMax-M3.1] Fuse SwiGLU-OAI with the MXFP8 quant of down_proj input` | perf,quant | ? | - |
| - | [#3199](https://github.com/ROCm/ATOM/pull/3199) `[MiniMax-M3.1] Fused all-reduce + Gemma RMSNorm writes qkv_proj's MXFP8 input` | perf,quant | ? | - |
| - | [#3200](https://github.com/ROCm/ATOM/pull/3200) `fix(models): the Qwen3.5 MTP drafter loads on a dense target` | bug | ? | - |
| - | [#3201](https://github.com/ROCm/ATOM/pull/3201) `fix(kv): an abort before decode's pull retires prefill's send claim` | bug | ? | - |
| - | [#3203](https://github.com/ROCm/ATOM/pull/3203) `fix(pd): a P/D producer reports its first token from the forward that samples it` | bug | ? | - |
| - | [#3205](https://github.com/ROCm/ATOM/pull/3205) `feat(minimax-m3): M3.1 decode router sharing a launch with the shared expert SwiGLU (1..128 rows)` |  | ? | - |
| - | [#3206](https://github.com/ROCm/ATOM/pull/3206) `[WIP]feat(mesh): session affinity 1/2 — a configurable session table, dp_sticky on it` | infra | ? | - |
| - | [#3207](https://github.com/ROCm/ATOM/pull/3207) `feat(minimax-m3): fold the M3.1 shared expert output into the routed GEMM2` |  | ? | - |
| - | [#3214](https://github.com/ROCm/ATOM/pull/3214) `feat(minimax-m3): run the M3.1 shared gate_up GEMM inside the router launch` |  | ? | - |
| P1 | [#3219](https://github.com/ROCm/ATOM/pull/3219) `fix(mla): pass the Triton decode only the sequences that own rows of q` | bug,rocm | ? | - |
| - | [#3220](https://github.com/ROCm/ATOM/pull/3220) `feat(mla): packed FP4 KV cache (MXFP4 / NVFP4) for the gfx1250 Triton decode` | perf,quant,rocm | ? | - |
| - | [#3222](https://github.com/ROCm/ATOM/issues/3222) `--kv_cache_dtype fp4 not supported on public main (required by DSV4.1-Flash DEP4 recipe)` | bug,quant | ? | - |
| - | [#3224](https://github.com/ROCm/ATOM/pull/3224) `perf(dspark): probabilistic verify reads the target logits rows in place` | infra,perf | ? | - |
| - | [#3227](https://github.com/ROCm/ATOM/issues/3227) `offload: two known gaps from #3027 (vLLM plugin media keys unsalted; Kimi-K3 chunk-aligned resend gets no tier` |  | ? | - |
| - | [#3228](https://github.com/ROCm/ATOM/pull/3228) `feat(moe): add DSv4.1 two-node EP16 MegaMoE` | infra | ? | - |
| - | [#3231](https://github.com/ROCm/ATOM/issues/3231) `[RFC] Decouple LMCache MP mode from ATOM` |  | ? | - |
| - | [#3235](https://github.com/ROCm/ATOM/pull/3235) `[Spec decode] --spec-decode-kv-cache-dtype: bf16/fp8 KV for a draft that has its own pool` | infra,perf,quant | ? | - |
| - | [#3236](https://github.com/ROCm/ATOM/pull/3236) `feat(model_loader): keep loaded weights on the GPU across server restarts (ATOM_PRELOAD)` |  | ? | - |
| - | [#3239](https://github.com/ROCm/ATOM/issues/3239) `[Perf Regression] 17 config(s) regressed @ 47e0c707` | bug,perf | ? | - |
| - | [#3251](https://github.com/ROCm/ATOM/pull/3251) `feat(minimax-m3): read DSpark taps from the next layer all-reduce` |  | ? | - |
| - | [#3255](https://github.com/ROCm/ATOM/pull/3255) `docs(recipes): Qwen3.5 AgentX recipe for the MXFP4 InferenceX submission` | quant | ? | - |
| - | [#3258](https://github.com/ROCm/ATOM/pull/3258) `perf(kda): reuse Conv1D state and input registers for decode` | perf | ? | - |
| - | [#3259](https://github.com/ROCm/ATOM/issues/3259) `[RFC] Pluggable KV pool backend: MORI-UMBP owns the L1 (HBM) pool so DP ranks share it` |  | ? | - |
| - | [#3260](https://github.com/ROCm/ATOM/issues/3260) `MiniMax-M3.1 MXFP4 KV: route sparse PA decode through run_pa_decode and drop the segment plan loop` | quant | ? | - |
| - | [#3261](https://github.com/ROCm/ATOM/issues/3261) `MhaKvPool: take only the KV layout (drop kv_dtype); the layout reports the transfer unit` |  | ? | - |
| - | [#3262](https://github.com/ROCm/ATOM/issues/3262) `Per-model fp4 KV support hook instead of _check_fp4_kv in shared config.py` | quant | ? | - |
| - | [#3263](https://github.com/ROCm/ATOM/issues/3263) `MiniMax-M3 skip-index layers: one fused writer for every KV dtype` | perf | ? | - |
| - | [#3267](https://github.com/ROCm/ATOM/pull/3267) `feat(kv): pluggable KV pool backend, with MORI-UMBP owning the L1 (HBM) pool` |  | ? | - |
| - | [#3271](https://github.com/ROCm/ATOM/pull/3271) `fix(engram): keep UVA rows in GTT host memory, one copy per NUMA node` | bug,infra | ? | - |
| - | [#3298](https://github.com/ROCm/ATOM/pull/3298) `test: cover PR welcome CI label table` | infra | ? | - |
| - | [#3304](https://github.com/ROCm/ATOM/pull/3304) `[draft] vp spec sampling` |  | ? | - |
| - | [#3308](https://github.com/ROCm/ATOM/pull/3308) `[MiniMax-M3.1] Mono decode: MXFP8 shared expert, a4w4 routed experts, indexer CP, NVFP4 pages` | infra,quant | ? | - |
| - | [#3311](https://github.com/ROCm/ATOM/pull/3311) `Cut Kimi-K3.1's DCP sparse prefill overhead in its DSA layers` |  | ? | - |
| - | [#3312](https://github.com/ROCm/ATOM/pull/3312) `Speed up Kimi-K3.1 prefill around its KDA in_proj and latent MoE collectives` | perf | ? | - |
| - | [#3315](https://github.com/ROCm/ATOM/pull/3315) `fix(dsv41 mono): check the hi programs in every FP4 index layout they serve` | bug,quant | ? | - |
| P0 | [#3316](https://github.com/ROCm/ATOM/pull/3316) `feat(dsv41 mono): serve the hi monokernel decode at TP2` |  | main | - |
| - | [#3321](https://github.com/ROCm/ATOM/pull/3321) `feat(dsa mono): serve an FP4 index cache` | infra,perf,quant | ? | - |
| P1 | [#3322](https://github.com/ROCm/ATOM/issues/3322) `[Perf Regression] 20 config(s) regressed @ 5b744ee3` | bug,perf | ? | - |
| - | [#3323](https://github.com/ROCm/ATOM/pull/3323) `Ready-suffix priority and cold-partial slice for Store restores (split from #3097)` | infra | ? | - |
| - | [#3325](https://github.com/ROCm/ATOM/pull/3325) `[Qwen3.5 MTP] Speculative rejection sampling for MTP drafts (flag off; stacked on #3093)` |  | ? | - |
| - | [#3326](https://github.com/ROCm/ATOM/pull/3326) `[Qwen3.5 recipe] mkcfg.py: SUBMISSION_RULESET binds the client to a ruleset's published seeds` |  | ? | - |
| - | [#3330](https://github.com/ROCm/ATOM/pull/3330) `KDA ReplaySSM: optional HIP decode / verify step (ATOM_REPLAYSSM_KDA_HIP)` | rocm | ? | - |
| - | [#3332](https://github.com/ROCm/ATOM/pull/3332) `Kimi-K3: KDA prefill on the state pool in place (FlashKDA paged state cache)` | perf | ? | - |
| P0 | [#3333](https://github.com/ROCm/ATOM/pull/3333) `fix(dspark): pass aiter's new _UAParams fields in the Kimi-K3 DSpark GQA draft` | bug,infra,rocm | main | - |

### ATOM — Closed unmerged (1 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#3040](https://github.com/ROCm/ATOM/pull/3040) `fix(dspark): allocate the draft block's last KV row (lookahead mtp_k, not mtp_k - 1)` | bug | main | - |

### tokenspeed — Merged / closed (292 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P1 | [#1373](https://github.com/lightseekorg/tokenspeed/issues/1373) `nccl weight transfer reports success without transferring: /update_weights returns 200 and loads uninitialised` | nvidia | ? | - |
| - | [#2517](https://github.com/lightseekorg/tokenspeed/issues/2517) `min_new_tokens is accepted by SamplingParams.verify() but never enforced` |  | ? | - |
| - | [#2575](https://github.com/lightseekorg/tokenspeed/issues/2575) `[Feature] Muse Spark Open: speculative decoding with its DFlash2 draft` |  | ? | - |
| - | [#2576](https://github.com/lightseekorg/tokenspeed/issues/2576) `[Bug] Triton FP8 channel MoE misses its FP64 check on SM90 above 512 tokens` | nvidia,quant,rocm | ? | - |
| - | [#2662](https://github.com/lightseekorg/tokenspeed/pull/2662) `feat(monokernel): opt-in decode monokernels on gfx950 for Qwen3.8-Flash-Next-Quark-MXFP4` | quant,rocm | ? | - |
| - | [#2717](https://github.com/lightseekorg/tokenspeed/pull/2717) `perf(pd): overlap the prefill role's planning with its forward` | perf | ? | - |
| - | [#2758](https://github.com/lightseekorg/tokenspeed/issues/2758) `[Feature] EAGLE-4 / EAGLE-Harness on AMD MI355X (gfx950): summary and open items` | rocm | ? | - |
| - | [#2763](https://github.com/lightseekorg/tokenspeed/pull/2763) `perf(kernel): size FP8 QSA decode grids by wave count with the N16 head tile` | perf,quant | ? | - |
| - | [#2770](https://github.com/lightseekorg/tokenspeed/pull/2770) `perf(kernel): stream QSA FP8 decode tiles through a staged-id cp.async ring` | perf,quant | ? | - |
| P0 | [#2775](https://github.com/lightseekorg/tokenspeed/pull/2775) `perf(amd): reduce packed FP8 MoE alignment overhead` | perf,quant,rocm | main | - |
| - | [#2777](https://github.com/lightseekorg/tokenspeed/pull/2777) `perf(qwen3.5): fold the routed MoE finalize into the shared-expert gate add` | perf | ? | - |
| - | [#2778](https://github.com/lightseekorg/tokenspeed/pull/2778) `perf(kernel): pipeline the GDN replay commit through a cp.async state ring` | perf | ? | - |
| P0 | [#2779](https://github.com/lightseekorg/tokenspeed/pull/2779) `perf(sampling): reduce top-k work for greedy rows` | perf | main | - |
| - | [#2794](https://github.com/lightseekorg/tokenspeed/issues/2794) `[Feature] support embedding model` |  | ? | - |
| - | [#2809](https://github.com/lightseekorg/tokenspeed/pull/2809) `feat(amd): run the EAGLE-Harness tree and policy kernels on gfx950 with Triton` | perf,rocm | ? | - |
| - | [#2812](https://github.com/lightseekorg/tokenspeed/pull/2812) `fix(cache): wait for Host load-backs in every cache accessor and per captured prefill-graph segment` | bug,perf | ? | - |
| P0 | [#2868](https://github.com/lightseekorg/tokenspeed/pull/2868) `fix(amd): keep ROCr's InterceptQueue out of serving processes` | bug,rocm | main | - |
| P1 | [#2871](https://github.com/lightseekorg/tokenspeed/pull/2871) `perf(kvp): gather MLA prefix history with a fused all-gather on GB300` | nvidia,perf | ? | - |
| - | [#2892](https://github.com/lightseekorg/tokenspeed/pull/2892) `feat(spec): verify sampled DFlash2 drafts by rejection sampling on triton` | rocm | ? | - |
| P1 | [#2893](https://github.com/lightseekorg/tokenspeed/pull/2893) `perf(spec): drop redundant launches from each DFLASH decode step` | perf | ? | - |
| P1 | [#2895](https://github.com/lightseekorg/tokenspeed/pull/2895) `fix(amd): stop gfx950 mha prefill and extend from compiling while serving` | bug,rocm | ? | - |
| P1 | [#2896](https://github.com/lightseekorg/tokenspeed/pull/2896) `perf(amd): speed up gfx950 mha extend over long cached prefixes` | perf,rocm | ? | - |
| P0 | [#2897](https://github.com/lightseekorg/tokenspeed/pull/2897) `fix(amd): make gfx950 mha attention over fp8 caches accurate and faster` | bug,perf,quant,rocm | main | - |
| P1 | [#2898](https://github.com/lightseekorg/tokenspeed/pull/2898) `perf(amd): balance gfx950 mha verify splits by request length` | perf,rocm | ? | - |
| P1 | [#2899](https://github.com/lightseekorg/tokenspeed/pull/2899) `perf(amd): pick gfx950 MoE, router and dense GEMMs by row count` | perf,rocm | ? | - |
| P1 | [#2900](https://github.com/lightseekorg/tokenspeed/pull/2900) `perf(muse): cut copies and RCCL fallbacks from Muse Spark communication` | perf,rocm | ? | - |
| P1 | [#2901](https://github.com/lightseekorg/tokenspeed/pull/2901) `perf(amd): reduce Muse expert TP8 routes on their token owners` | perf,rocm | ? | - |
| P1 | [#2902](https://github.com/lightseekorg/tokenspeed/pull/2902) `perf(amd): split Muse expert TP8 prefill down projection by columns` | perf,rocm | ? | - |
| P1 | [#2903](https://github.com/lightseekorg/tokenspeed/pull/2903) `perf(amd): fuse the Muse expert TP8 decode route all-reduce and norm` | perf,rocm | ? | - |
| - | [#2916](https://github.com/lightseekorg/tokenspeed/pull/2916) `feat(attn): add Qwen FP8 attention projections support` | quant | ? | - |
| - | [#2921](https://github.com/lightseekorg/tokenspeed/issues/2921) `[Feature] Intel GPU (XPU) platform support — Data Center GPU D-series` | nvidia | ? | - |
| P1 | [#2925](https://github.com/lightseekorg/tokenspeed/pull/2925) `perf(kernel): end FP8 QSA prefix loops at the last valid tile` | perf,quant | ? | - |
| - | [#2926](https://github.com/lightseekorg/tokenspeed/pull/2926) `perf(gdn): capture Qwen4-Exp GDN layers inside prefill graphs` | perf | ? | - |
| P1 | [#2933](https://github.com/lightseekorg/tokenspeed/pull/2933) `perf(qsa): run large FP8 prefill calls on a BF16 KV scratch` | perf,quant | ? | - |
| P0 | [#2941](https://github.com/lightseekorg/tokenspeed/pull/2941) `fix(amd): run short prefill requests through the regular tile path on gfx950` | bug,rocm | main | - |
| P0 | [#2942](https://github.com/lightseekorg/tokenspeed/pull/2942) `perf(gfx950): stop recompiling MHA prefill kernels per batch size` | perf,rocm | main | - |
| P1 | [#2956](https://github.com/lightseekorg/tokenspeed/pull/2956) `fix(pd): keep KV pages until PD transfers stop` | bug | ? | - |
| P1 | [#2957](https://github.com/lightseekorg/tokenspeed/pull/2957) `fix(amd): wait for every wave's stores to reach L2 before a release` | bug,infra,rocm | ? | - |
| - | [#2961](https://github.com/lightseekorg/tokenspeed/pull/2961) `feat(scheduler): opt-in prefill chunk yield on the P role` |  | ? | - |
| P0 | [#2962](https://github.com/lightseekorg/tokenspeed/pull/2962) `perf(layernorm): run GemmaRMSNorm through fused Triton kernels on AMD` | perf,rocm | main | - |
| - | [#2966](https://github.com/lightseekorg/tokenspeed/pull/2966) `fix(scheduler): register every KV-event boundary a restored request republishes` | bug | ? | - |
| - | [#2972](https://github.com/lightseekorg/tokenspeed/pull/2972) `perf(mha): draft tree lanes: run the lane prefix as one Triton decode per request, with batch-shaped key split` | perf,rocm | ? | - |
| P0 | [#2973](https://github.com/lightseekorg/tokenspeed/pull/2973) `fix(kernel): address MLA token offsets past 2**31 elements in int64` | bug,perf | main | - |
| - | [#2980](https://github.com/lightseekorg/tokenspeed/pull/2980) `perf(spec): replay the Eagle drafter's prefill work from CUDA graphs` | nvidia,perf | ? | - |
| - | [#2981](https://github.com/lightseekorg/tokenspeed/pull/2981) `feat(scheduler): drop short prompt-end checkpoints on prefill servers` |  | ? | - |
| - | [#2982](https://github.com/lightseekorg/tokenspeed/pull/2982) `feat(scheduler): demote superseded in-forward State checkpoints` |  | ? | - |
| - | [#2985](https://github.com/lightseekorg/tokenspeed/pull/2985) `perf(cache): size the compact Host parent to whole KV pages` | perf | ? | - |
| - | [#2993](https://github.com/lightseekorg/tokenspeed/pull/2993) `perf(kda): verify speculative windows with a CuTe DSL kernel on Blackwell` | nvidia,perf | ? | - |
| - | [#3006](https://github.com/lightseekorg/tokenspeed/pull/3006) `refactor(kernel): centralize optional-package probes in tokenspeed_kernel._optional` | perf | ? | - |
| - | [#3007](https://github.com/lightseekorg/tokenspeed/pull/3007) `refactor(layers): table-driven rope scaling construction in get_rope` |  | ? | - |
| P1 | [#3010](https://github.com/lightseekorg/tokenspeed/pull/3010) `perf(dsv41): speed up the decode attention projections` | perf | ? | - |
| P1 | [#3016](https://github.com/lightseekorg/tokenspeed/pull/3016) `perf(moe): stage MegaMoE inputs several tokens per program, with PDL` | perf | ? | - |
| P1 | [#3018](https://github.com/lightseekorg/tokenspeed/pull/3018) `fix(glm53-flash): dequantize an FP8 indexer wk into the fused projection` | bug,perf,quant | ? | - |
| P1 | [#3019](https://github.com/lightseekorg/tokenspeed/pull/3019) `fix(moe): keep the SM90 FP8 per-channel MoE on exact tiles above 512 tokens` | bug,nvidia,quant | ? | - |
| - | [#3028](https://github.com/lightseekorg/tokenspeed/pull/3028) `perf(moe): run the DSV4.1 shared expert inside the MegaMoE launch` | perf | ? | - |
| - | [#3057](https://github.com/lightseekorg/tokenspeed/pull/3057) `feat(scheduler): add a prefill/decode interval` |  | ? | - |
| - | [#3058](https://github.com/lightseekorg/tokenspeed/pull/3058) `feat(runtime): add --prefill-decode-interval` |  | ? | - |
| - | [#3061](https://github.com/lightseekorg/tokenspeed/pull/3061) `docs(recipes): update muse spark amd recipe` | rocm | ? | - |
| P1 | [#3063](https://github.com/lightseekorg/tokenspeed/pull/3063) `feat(mla): add native MLA prefill kernel` | perf | ? | - |
| - | [#3064](https://github.com/lightseekorg/tokenspeed/pull/3064) `fix(npu): honor selected devices in EPD transfer runtime` | bug | ? | - |
| - | [#3065](https://github.com/lightseekorg/tokenspeed/pull/3065) `fix(cache): compact a lone request's packed-group blocks when eviction alone cannot fund its admission` | bug,perf | ? | - |
| P1 | [#3067](https://github.com/lightseekorg/tokenspeed/pull/3067) `perf(dsv41): gather Engram host rows straight into wkv's MXFP8 input` | perf,quant | ? | - |
| P0 | [#3069](https://github.com/lightseekorg/tokenspeed/pull/3069) `fix(mla): align DSpark KV dtype and fix workspace overflow` | bug,risk | main | - |
| P1 | [#3070](https://github.com/lightseekorg/tokenspeed/pull/3070) `perf(kernel): run small-weight decode BF16 GEMMs on pinned FlashInfer TGV tiles` | infra,nvidia,perf | ? | - |
| - | [#3071](https://github.com/lightseekorg/tokenspeed/pull/3071) `fix(scheduler): publish hybrid KV cache events from Full/history residency` | bug,perf | ? | - |
| - | [#3073](https://github.com/lightseekorg/tokenspeed/pull/3073) `fix(cuda): exclude compiler stubs from runtime library lookup` | bug,nvidia | ? | - |
| - | [#3074](https://github.com/lightseekorg/tokenspeed/pull/3074) `fix(cache): export private P/D partial-prefix destinations` | bug,perf | ? | - |
| P1 | [#3075](https://github.com/lightseekorg/tokenspeed/pull/3075) `perf(dsv41): clean only the live tiles of each indexer score row` | perf | ? | - |
| P1 | [#3078](https://github.com/lightseekorg/tokenspeed/pull/3078) `perf(dsv41): upload block-table row spans and rebuild them on the device` | perf | ? | - |
| - | [#3081](https://github.com/lightseekorg/tokenspeed/pull/3081) `perf(runtime): pad every state group's stopped rows in one launch` | perf | ? | - |
| P1 | [#3083](https://github.com/lightseekorg/tokenspeed/pull/3083) `perf(kimi-k31): trim four launches from each DSA layer's decode prologue` | perf | ? | - |
| - | [#3084](https://github.com/lightseekorg/tokenspeed/pull/3084) `fix(test): expect the gfx950 DSA prefill adapters to forward the warmup flag` | bug,rocm | ? | - |
| - | [#3085](https://github.com/lightseekorg/tokenspeed/pull/3085) `fix(test): parse the cached Muse Spark checkpoint with its own quantization format` | bug,quant | ? | - |
| - | [#3086](https://github.com/lightseekorg/tokenspeed/pull/3086) `feat(moe): add distributed weight data parallel prefill` |  | ? | - |
| - | [#3087](https://github.com/lightseekorg/tokenspeed/pull/3087) `ci(amd): change gfx950 test / bench runner labels` | bug,infra,perf,rocm | ? | - |
| - | [#3089](https://github.com/lightseekorg/tokenspeed/pull/3089) `Revert "ci(amd): change gfx950 test / bench runner labels"` | bug,infra,perf,rocm | ? | - |
| - | [#3090](https://github.com/lightseekorg/tokenspeed/pull/3090) `build: release tokenspeed-mla 2.0.8` | infra,perf | ? | - |
| - | [#3092](https://github.com/lightseekorg/tokenspeed/pull/3092) `build: require tokenspeed-mla 2.0.8` | infra,perf | ? | - |
| - | [#3093](https://github.com/lightseekorg/tokenspeed/pull/3093) `feat(rl): support rl` |  | ? | - |
| - | [#3094](https://github.com/lightseekorg/tokenspeed/pull/3094) `test(dsv41): give the mega-MoE stand-in a shared_expert_fused field` | perf | ? | - |
| P1 | [#3097](https://github.com/lightseekorg/tokenspeed/pull/3097) `perf(mla): unroll fixed FP8 decode MMA loops` | perf,quant | ? | - |
| - | [#3098](https://github.com/lightseekorg/tokenspeed/pull/3098) `feat(lm-head): support tensor parallel heads across attention DP groups` |  | ? | - |
| - | [#3099](https://github.com/lightseekorg/tokenspeed/pull/3099) `chore: upgrade FlashInfer to 0.7.3` | nvidia | ? | - |
| - | [#3100](https://github.com/lightseekorg/tokenspeed/pull/3100) `feat(numerics): add blockwise logprob subtraction modes` |  | ? | - |
| - | [#3101](https://github.com/lightseekorg/tokenspeed/pull/3101) `perf: build forward block tables from live windows` | infra,perf | ? | - |
| P1 | [#3102](https://github.com/lightseekorg/tokenspeed/pull/3102) `perf: fuse V4.1 decode attention with FP8 output` | perf,quant | ? | - |
| - | [#3104](https://github.com/lightseekorg/tokenspeed/pull/3104) `fix(runtime): separate input token bounds from output vocabulary` | bug | ? | - |
| - | [#3105](https://github.com/lightseekorg/tokenspeed/pull/3105) `fix(pd): isolate registrations and drain cancelled transfers` | bug | ? | - |
| - | [#3106](https://github.com/lightseekorg/tokenspeed/pull/3106) `feat(runtime): receive complete WeightStore snapshots` |  | ? | - |
| - | [#3107](https://github.com/lightseekorg/tokenspeed/pull/3107) `feat: allow model profiles to construct attention configurations` |  | ? | - |
| - | [#3108](https://github.com/lightseekorg/tokenspeed/pull/3108) `build: release tokenspeed-mla 2.0.9` | infra,perf | ? | - |
| - | [#3109](https://github.com/lightseekorg/tokenspeed/pull/3109) `build: require tokenspeed-mla 2.0.9` | infra,perf | ? | - |
| - | [#3110](https://github.com/lightseekorg/tokenspeed/pull/3110) `fix(pd): transfer the complete replayable cache tail` | bug,perf | ? | - |
| - | [#3111](https://github.com/lightseekorg/tokenspeed/pull/3111) `feat(kimi-k31): replay prefill CUDA graphs on the aggregated role by default` | nvidia | ? | - |
| - | [#3112](https://github.com/lightseekorg/tokenspeed/pull/3112) `fix(ci): satisfy Clippy for the PD cancellation check` | bug,infra | ? | - |
| - | [#3113](https://github.com/lightseekorg/tokenspeed/pull/3113) `docs(readme): add Kimi K3.1 Pro day-0 news entry` |  | ? | - |
| - | [#3114](https://github.com/lightseekorg/tokenspeed/pull/3114) `fix: adapt the FlashInfer adapters and callers to 0.7.3` | bug,nvidia | ? | - |
| - | [#3115](https://github.com/lightseekorg/tokenspeed/pull/3115) `perf(mha): target verify: fold the verify rows per request in the Triton MHA decode` | perf,rocm | ? | - |
| P0 | [#3118](https://github.com/lightseekorg/tokenspeed/pull/3118) `fix: close warmup gaps and gate gfx950 inline asm` | bug,rocm | main | - |
| - | [#3119](https://github.com/lightseekorg/tokenspeed/pull/3119) `perf(amd): pipeline the gfx950 sliding-window split decode and expose it to fused kernels` | perf,rocm | ? | - |
| P0 | [#3120](https://github.com/lightseekorg/tokenspeed/pull/3120) `perf(amd): fuse muse spark's decode layer boundaries into fewer launches` | perf,rocm | efric/muse-area/attention | - |
| P0 | [#3121](https://github.com/lightseekorg/tokenspeed/pull/3121) `perf(amd): stream gfx950 mxfp4 moe decode weights at few rows` | perf,quant,rocm | main | - |
| P1 | [#3122](https://github.com/lightseekorg/tokenspeed/pull/3122) `perf(spec): shorten the dflash2 draft step and keep sampling vocab-sharded` | perf | ? | - |
| - | [#3123](https://github.com/lightseekorg/tokenspeed/pull/3123) `docs(recipes): set muse spark's mi355x cap and prefill/decode interval by concurrency` | rocm | ? | - |
| - | [#3126](https://github.com/lightseekorg/tokenspeed/pull/3126) `perf(dsv41): batch prefill indexer requests into one call` | perf | ? | - |
| - | [#3127](https://github.com/lightseekorg/tokenspeed/pull/3127) `perf(inkling): store ShortConv hidden checkpoints on the KV planes` | perf | ? | - |
| - | [#3128](https://github.com/lightseekorg/tokenspeed/pull/3128) `docs(cache): list the short prompt-end drop among the in-forward skips` | perf | ? | - |
| - | [#3129](https://github.com/lightseekorg/tokenspeed/pull/3129) `fix(test): pass the drafter prefill graph flag in the DFlash2 sampling tests` | bug | ? | - |
| - | [#3130](https://github.com/lightseekorg/tokenspeed/pull/3130) `fix(kimi-k25): derive the absorbed MLA weights under dummy loading` | bug | ? | - |
| - | [#3131](https://github.com/lightseekorg/tokenspeed/pull/3131) `refactor(models): load Llama, Qwen3 and Qwen3-MoE weights through BaseCausalLM` |  | ? | - |
| - | [#3132](https://github.com/lightseekorg/tokenspeed/pull/3132) `fix(server): start in-forward checkpoints on older scheduler wheels` | bug | ? | - |
| - | [#3133](https://github.com/lightseekorg/tokenspeed/pull/3133) `fix(test): avoid a racy DMA writeback negative control` | bug | ? | - |
| - | [#3135](https://github.com/lightseekorg/tokenspeed/pull/3135) `perf(dsv41): batch prefill attention requests into one call` | perf | ? | - |
| - | [#3139](https://github.com/lightseekorg/tokenspeed/pull/3139) `perf(dsv41): fuse prefill attention FP8 output, DeepGEMM front GEMMs` | perf,quant | ? | - |
| - | [#3140](https://github.com/lightseekorg/tokenspeed/issues/3140) `[Bug] DeepSeek V4 Triton attention overflows token row offsets` | risk,rocm | ? | - |
| P0 | [#3141](https://github.com/lightseekorg/tokenspeed/pull/3141) `fix(dsv4): prevent Triton token row offset overflow` | bug,risk,rocm | main | - |
| - | [#3144](https://github.com/lightseekorg/tokenspeed/pull/3144) `fix(test): pass rows_aligned in the Qwen4 exp delta-layer replay test` | bug | ? | - |
| - | [#3145](https://github.com/lightseekorg/tokenspeed/pull/3145) `fix(test): pass the query shard device in the drafter prefill graph test` | bug | ? | - |
| - | [#3146](https://github.com/lightseekorg/tokenspeed/pull/3146) `perf(beam): run the fused SSMax Q/K norm at TP2 and TP4` | perf | ? | - |
| - | [#3147](https://github.com/lightseekorg/tokenspeed/pull/3147) `perf(kda): fuse the gate and convolution producers into one-token verify` | perf | ? | - |
| - | [#3148](https://github.com/lightseekorg/tokenspeed/pull/3148) `build: release tokenspeed-scheduler 0.1.50` | infra,perf | ? | - |
| - | [#3149](https://github.com/lightseekorg/tokenspeed/pull/3149) `fix(test): pass fused_decode_groups in the V4.1 batched-prefill tests` | bug,perf | ? | - |
| - | [#3150](https://github.com/lightseekorg/tokenspeed/pull/3150) `ci(release): add an optional free-text suffix to manual nightlies` | infra | ? | - |
| - | [#3151](https://github.com/lightseekorg/tokenspeed/pull/3151) `perf(kernel): prefer the BF16x3 FP32 GEMM for split weights` | perf | ? | - |
| - | [#3152](https://github.com/lightseekorg/tokenspeed/pull/3152) `fix(npu): accept Gluon constexpr helpers during import` | bug,rocm | ? | - |
| - | [#3153](https://github.com/lightseekorg/tokenspeed/pull/3153) `test: isolate prompt logprob order from CPU GEMM rounding` |  | ? | - |
| - | [#3155](https://github.com/lightseekorg/tokenspeed/pull/3155) `refactor(amd): split extern intrinsics into per-category libraries` | rocm | ? | - |
| - | [#3156](https://github.com/lightseekorg/tokenspeed/pull/3156) `test(qsa): dequantize the stand-in attention's cache once` | perf,quant | ? | - |
| - | [#3157](https://github.com/lightseekorg/tokenspeed/pull/3157) `fix(test): avoid a racy kernel writeback negative control` | bug,perf | ? | - |
| - | [#3158](https://github.com/lightseekorg/tokenspeed/pull/3158) `perf(beam): run the BF16 Q/K/V and output gate projections as one GEMM` | perf | ? | - |
| - | [#3159](https://github.com/lightseekorg/tokenspeed/pull/3159) `ci(release): name manual nightlies with a release candidate number` | infra | ? | - |
| - | [#3163](https://github.com/lightseekorg/tokenspeed/pull/3163) `test(qsa): run the BF16 scratch test's attention stand-ins on the GPU` |  | ? | - |
| - | [#3164](https://github.com/lightseekorg/tokenspeed/pull/3164) `docs(release): scope the release-candidate ordering note` | infra | ? | - |
| - | [#3166](https://github.com/lightseekorg/tokenspeed/pull/3166) `build(deps): upgrade tokenspeed-scheduler to 0.1.50` | infra,perf | ? | - |
| - | [#3167](https://github.com/lightseekorg/tokenspeed/pull/3167) `refactor(models): load Qwen3.5 through the shared causal-LM loader` |  | ? | - |
| - | [#3168](https://github.com/lightseekorg/tokenspeed/pull/3168) `feat(dev): reload edited forward code into a running engine` |  | ? | - |
| - | [#3169](https://github.com/lightseekorg/tokenspeed/pull/3169) `test(runtime): separate input and output vocabulary coverage` |  | ? | - |
| - | [#3170](https://github.com/lightseekorg/tokenspeed/pull/3170) `test(runtime): consolidate logprob order resolution coverage` |  | ? | - |
| - | [#3171](https://github.com/lightseekorg/tokenspeed/pull/3171) `docs(cache): link the PD landing contract` | perf | ? | - |
| - | [#3173](https://github.com/lightseekorg/tokenspeed/pull/3173) `perf(qsa): add native FP8 CuTe prefill on SM107` | nvidia,perf,quant | ? | - |
| - | [#3174](https://github.com/lightseekorg/tokenspeed/pull/3174) `ci: clean up inactive branches every six hours` | infra | ? | - |
| - | [#3175](https://github.com/lightseekorg/tokenspeed/pull/3175) `refactor(models): load Qwen3-Omni through the shared causal-LM loader` |  | ? | - |
| - | [#3176](https://github.com/lightseekorg/tokenspeed/pull/3176) `fix(qwen4-exp): keep an FP8 checkpoint's PLE table in FP8 by default` | bug,quant | ? | - |
| - | [#3177](https://github.com/lightseekorg/tokenspeed/pull/3177) `ci(amd): update MI450 simulator nightly` | infra,rocm | ? | - |
| - | [#3178](https://github.com/lightseekorg/tokenspeed/pull/3178) `feat(model): mask DeepSeek V4.1 control tokens` |  | ? | - |
| - | [#3179](https://github.com/lightseekorg/tokenspeed/pull/3179) `feat(scheduler): add opt-in short-prefill ordering` |  | ? | - |
| - | [#3182](https://github.com/lightseekorg/tokenspeed/pull/3182) `feat(engine): report reasoning token usage` |  | ? | - |
| - | [#3183](https://github.com/lightseekorg/tokenspeed/pull/3183) `perf(hc): pipeline wide gated residual mixing` | perf | ? | - |
| - | [#3186](https://github.com/lightseekorg/tokenspeed/pull/3186) `feat(scheduler): add prefill gate to coordinate delayed prefill across attention-DP ranks` |  | ? | - |
| - | [#3187](https://github.com/lightseekorg/tokenspeed/pull/3187) `build: release tokenspeed-scheduler 0.1.51` | infra,perf | ? | - |
| - | [#3188](https://github.com/lightseekorg/tokenspeed/pull/3188) `build: require tokenspeed-scheduler 0.1.51` | infra,perf | ? | - |
| - | [#3190](https://github.com/lightseekorg/tokenspeed/pull/3190) `perf(kimi-k3): walk the B4-8 decode experts' static schedule and claim FC2 jobs` | perf | ? | - |
| - | [#3192](https://github.com/lightseekorg/tokenspeed/pull/3192) `refactor(models): run Qwen3 and Qwen3-MoE on the shared decoder layer` |  | ? | - |
| - | [#3193](https://github.com/lightseekorg/tokenspeed/pull/3193) `ci: skip kernel unit tests for runtime-only pull requests` | infra,perf | ? | - |
| - | [#3194](https://github.com/lightseekorg/tokenspeed/pull/3194) `ci(amd): reuse preinstalled ROCm stacks` | infra,rocm | ? | - |
| - | [#3195](https://github.com/lightseekorg/tokenspeed/pull/3195) `ci(amd): remove Kimi-K3 model workflows` | infra,rocm | ? | - |
| - | [#3196](https://github.com/lightseekorg/tokenspeed/pull/3196) `ci(amd): add Kimi-K3.1 Pro workflows` | infra,rocm | ? | - |
| - | [#3198](https://github.com/lightseekorg/tokenspeed/pull/3198) `fix(kimi-k3): cap the decode experts grids at the device's SM count` | bug | ? | - |
| - | [#3199](https://github.com/lightseekorg/tokenspeed/pull/3199) `perf(kimi-k3): release the B5-8 decode experts early and prefetch the next weights into L2` | infra,perf | ? | - |
| - | [#3200](https://github.com/lightseekorg/tokenspeed/pull/3200) `feat(sampling): vendor sonic-sampler's kernels as the sonic backend` | perf | ? | - |
| - | [#3201](https://github.com/lightseekorg/tokenspeed/pull/3201) `ci: run only the kernel test files whose op families a pull request changes` | bug,infra,perf | ? | - |
| - | [#3202](https://github.com/lightseekorg/tokenspeed/pull/3202) `test: match grouped FP8 projection hardware support` | quant | ? | - |
| - | [#3204](https://github.com/lightseekorg/tokenspeed/pull/3204) `perf(pd): pull the remote prefill behind the forward and zero only unfilled pages on a D-role landing` | perf | ? | - |
| - | [#3205](https://github.com/lightseekorg/tokenspeed/pull/3205) `refactor(models): run MiniMax-M3 on the shared decoder layer` |  | ? | - |
| - | [#3206](https://github.com/lightseekorg/tokenspeed/pull/3206) `perf(dsa): fuse the Kimi-K3.1 decode indexer tail and its index query quantization` | perf,quant | ? | - |
| - | [#3207](https://github.com/lightseekorg/tokenspeed/pull/3207) `perf(kimi-k3): fuse large attention-DP input projections with vendored front programs` | perf | ? | - |
| - | [#3208](https://github.com/lightseekorg/tokenspeed/pull/3208) `feat(moe): support Qwen4 MXFP4 MegaMoE with DeepGEMM` | quant | ? | - |
| - | [#3209](https://github.com/lightseekorg/tokenspeed/pull/3209) `ci: skip a model's tasks when a pull request changes only other models` | bug,infra | ? | - |
| - | [#3210](https://github.com/lightseekorg/tokenspeed/pull/3210) `ci: run only the runtime test files that a test or model change reaches` | bug,infra | ? | - |
| - | [#3211](https://github.com/lightseekorg/tokenspeed/pull/3211) `build: release tokenspeed-scheduler 0.1.52` | infra,perf | ? | - |
| - | [#3213](https://github.com/lightseekorg/tokenspeed/pull/3213) `build: require tokenspeed-scheduler 0.1.52` | infra,perf | ? | - |
| - | [#3214](https://github.com/lightseekorg/tokenspeed/pull/3214) `perf(kda): start the o-projection with the gated norm and reject strided verify records` | perf | ? | - |
| - | [#3225](https://github.com/lightseekorg/tokenspeed/pull/3225) `fix(metrics): split running batch from in-flight requests` | bug | ? | - |
| - | [#3226](https://github.com/lightseekorg/tokenspeed/pull/3226) `refactor(models): build the DeepSeek-V3 decoder layer on BaseDecoderLayer` | infra | ? | - |
| - | [#3228](https://github.com/lightseekorg/tokenspeed/pull/3228) `feat(sampling): sample vocab-sharded logits with sonic under TP` |  | ? | - |
| - | [#3229](https://github.com/lightseekorg/tokenspeed/pull/3229) `refactor(models): share one forward and MLP builder across the Qwen3.5 decoder layers` |  | ? | - |
| - | [#3230](https://github.com/lightseekorg/tokenspeed/pull/3230) `fix(runtime): read HF metadata from the local cache in offline mode` | bug,perf | ? | - |
| - | [#3232](https://github.com/lightseekorg/tokenspeed/pull/3232) `fix(kernel): return empty NVFP4 quantization and CuTe DSL GEMM outputs for zero rows` | bug,perf,quant | ? | - |
| - | [#3233](https://github.com/lightseekorg/tokenspeed/pull/3233) `feat(monokernel): Muse Spark single-request decode monokernels on gfx950` | rocm | ? | - |
| - | [#3234](https://github.com/lightseekorg/tokenspeed/pull/3234) `perf(kimi-k3): run the decode input projection on a warp split-K up to 16 rows` | perf | ? | - |
| - | [#3235](https://github.com/lightseekorg/tokenspeed/pull/3235) `feat(sampling): verify sampled drafts against their recorded q in sonic` |  | ? | - |
| - | [#3236](https://github.com/lightseekorg/tokenspeed/pull/3236) `fix(runtime): resolve a separate draft repository at its own revision` | bug | ? | - |
| - | [#3238](https://github.com/lightseekorg/tokenspeed/pull/3238) `perf(kimi-k31): project the indexer keys in the decode chain's input projection` | perf | ? | - |
| - | [#3239](https://github.com/lightseekorg/tokenspeed/pull/3239) `refactor(models): build the K3 DSpark draft layer on DFlashDecoderLayer's construction hooks` | infra | ? | - |
| - | [#3240](https://github.com/lightseekorg/tokenspeed/pull/3240) `build: release tokenspeed-scheduler 0.1.53` | infra,perf | ? | - |
| - | [#3241](https://github.com/lightseekorg/tokenspeed/pull/3241) `ci: run every model task when a pull request changes a speculative-decoding model module` | bug,infra | ? | - |
| - | [#3242](https://github.com/lightseekorg/tokenspeed/pull/3242) `refactor(drafter): share the draft input, buffers and run between Eagle and Mtp` |  | ? | - |
| - | [#3243](https://github.com/lightseekorg/tokenspeed/pull/3243) `build: require tokenspeed-scheduler 0.1.53` | infra,perf | ? | - |
| - | [#3244](https://github.com/lightseekorg/tokenspeed/pull/3244) `fix(communication): check the device before importing Iris in the residual-norm predicate` | bug | ? | - |
| - | [#3245](https://github.com/lightseekorg/tokenspeed/pull/3245) `feat(sampling): sample speculative drafts from the draft head's vocabulary shard` |  | ? | - |
| - | [#3246](https://github.com/lightseekorg/tokenspeed/pull/3246) `test(engine): agree fake PD transfer retirement across ranks` |  | ? | - |
| P0 | [#3247](https://github.com/lightseekorg/tokenspeed/pull/3247) `fix(dsv41): keep cache gather output offsets 64-bit` | bug,perf | main | - |
| - | [#3248](https://github.com/lightseekorg/tokenspeed/issues/3248) `Please help to enable Triton PRs so I can add Windows support.` | rocm | ? | - |
| - | [#3249](https://github.com/lightseekorg/tokenspeed/pull/3249) `test(qsa): isolate the int32 prefill fallback runner` |  | ? | - |
| - | [#3252](https://github.com/lightseekorg/tokenspeed/pull/3252) `fix(dsv41): compute the remaining cache and query copy offsets in int64` | bug,perf | ? | - |
| - | [#3253](https://github.com/lightseekorg/tokenspeed/pull/3253) `feat(sampling): support synthetic acceptance on the sonic backend` |  | ? | - |
| - | [#3254](https://github.com/lightseekorg/tokenspeed/pull/3254) `test(logits): pass the sampler's shard support to keep_sampled_logits_vocab_sharded` |  | ? | - |
| - | [#3256](https://github.com/lightseekorg/tokenspeed/pull/3256) `build: release tokenspeed-scheduler 0.1.54` | infra,perf | ? | - |
| - | [#3257](https://github.com/lightseekorg/tokenspeed/pull/3257) `build: require tokenspeed-scheduler 0.1.54` | infra,perf | ? | - |
| - | [#3258](https://github.com/lightseekorg/tokenspeed/pull/3258) `fix(pd): isolate failed peers and reject expired transfers` | bug | ? | - |
| - | [#3259](https://github.com/lightseekorg/tokenspeed/pull/3259) `build(deps): update tokenspeed-smg and gRPC dependency pins` | infra,perf | ? | - |
| - | [#3260](https://github.com/lightseekorg/tokenspeed/pull/3260) `fix(mla): wait for the TMEM correction-record load before releasing its stage` | bug | ? | - |
| - | [#3261](https://github.com/lightseekorg/tokenspeed/pull/3261) `fix(kernel): acquire the cluster mailboxes at cluster scope` | bug,perf | ? | - |
| - | [#3262](https://github.com/lightseekorg/tokenspeed/pull/3262) `feat(cache): expose shared-prefix publication and group ownership` | perf | ? | - |
| P1 | [#3263](https://github.com/lightseekorg/tokenspeed/pull/3263) `perf(scheduler): keep the active LCM block count in the block tables` | perf | ? | - |
| - | [#3264](https://github.com/lightseekorg/tokenspeed/pull/3264) `refactor(runtime): externalize the WeightStore receiver` |  | ? | - |
| - | [#3265](https://github.com/lightseekorg/tokenspeed/pull/3265) `feat: trace request lifecycles, first output latency and prefix cache hits` | perf | ? | - |
| - | [#3266](https://github.com/lightseekorg/tokenspeed/pull/3266) `ts-control: report decode admission wait instead of a negative prefill_ms on decode nodes` |  | ? | - |
| - | [#3267](https://github.com/lightseekorg/tokenspeed/pull/3267) `fix(prefill): support eager history-dependent embeddings` | bug | ? | - |
| - | [#3268](https://github.com/lightseekorg/tokenspeed/pull/3268) `refactor(amd): replace inline-asm waits, votes and scans with LLVM intrinsics` | rocm | ? | - |
| - | [#3269](https://github.com/lightseekorg/tokenspeed/pull/3269) `perf(kimi-k31): run the DSA decode front in one cluster launch` | perf | ? | - |
| - | [#3271](https://github.com/lightseekorg/tokenspeed/pull/3271) `fix(engine): honor --stream-interval under speculative decoding` | bug | ? | - |
| - | [#3272](https://github.com/lightseekorg/tokenspeed/pull/3272) `fix(moe): keep NVFP4 MoE tuning off clustered persistent trtllm-gen kernels` | bug,perf,quant | ? | - |
| - | [#3273](https://github.com/lightseekorg/tokenspeed/pull/3273) `docs: add news entry for DWDP and WideEP support for Kimi K3` |  | ? | - |
| - | [#3275](https://github.com/lightseekorg/tokenspeed/pull/3275) `perf(k3.1): reduce-scatter the decode MoE shared rows in the two-shot` | perf | ? | - |
| - | [#3276](https://github.com/lightseekorg/tokenspeed/pull/3276) `perf(dspark): shard the K3 draft's context projection and fuse its KV writes` | perf | ? | - |
| - | [#3277](https://github.com/lightseekorg/tokenspeed/pull/3277) `perf(metadata): skip full tiles before padding tails` | perf | ? | - |
| - | [#3278](https://github.com/lightseekorg/tokenspeed/pull/3278) `perf(muse-spark): let the mailbox consumers store this rank's block` | perf | ? | - |
| - | [#3279](https://github.com/lightseekorg/tokenspeed/pull/3279) `perf(kda): fold the output norm and the window's producers into the verify kernels` | perf | ? | - |
| - | [#3282](https://github.com/lightseekorg/tokenspeed/pull/3282) `feat(sampling): draw sonic rows without top-k, top-p or min-p from the whole vocabulary` |  | ? | - |
| - | [#3283](https://github.com/lightseekorg/tokenspeed/pull/3283) `perf(gemm): admit and pin FlashInfer CuTe DSL bf16 projections on SM107` | infra,nvidia,perf | ? | - |
| - | [#3284](https://github.com/lightseekorg/tokenspeed/pull/3284) `perf(kimi-k31): project and gate the DSA layers' MLA values in one CuTe DSL kernel` | perf | ? | - |
| - | [#3285](https://github.com/lightseekorg/tokenspeed/pull/3285) `fix(sampling): keep the token crossing top_p in sonic's nucleus` | bug | ? | - |
| - | [#3286](https://github.com/lightseekorg/tokenspeed/pull/3286) `perf(muse-spark): all-reduce the MoE tail inside the routed-sum kernel` | perf | ? | - |
| - | [#3287](https://github.com/lightseekorg/tokenspeed/pull/3287) `fix(metadata): use shared Triton block-table expansion on NPU` | bug,rocm | ? | - |
| - | [#3288](https://github.com/lightseekorg/tokenspeed/pull/3288) `docs: highlight Kimi K3 AgentX throughput in news` | perf | ? | - |
| - | [#3289](https://github.com/lightseekorg/tokenspeed/pull/3289) `ci: cache tokenspeed-engine builds` | infra,perf | ? | - |
| - | [#3292](https://github.com/lightseekorg/tokenspeed/pull/3292) `ci: keep unit-test Triton caches local to each job` | infra,rocm | ? | - |
| - | [#3293](https://github.com/lightseekorg/tokenspeed/pull/3293) `ci: allow 90 minutes for AMD kernel tests` | infra,perf,rocm | ? | - |
| - | [#3294](https://github.com/lightseekorg/tokenspeed/pull/3294) `ci: avoid serving builds in MI450 simulator tests` | infra | ? | - |
| - | [#3295](https://github.com/lightseekorg/tokenspeed/pull/3295) `fix(control): finish prefill streams after transfer failures` | bug | ? | - |
| - | [#3296](https://github.com/lightseekorg/tokenspeed/pull/3296) `ci: add tokenspeed-engine wheel releases` | infra,perf | ? | - |
| - | [#3300](https://github.com/lightseekorg/tokenspeed/pull/3300) `ci: support dated tokenspeed-engine post and rc releases` | infra,perf | ? | - |
| - | [#3301](https://github.com/lightseekorg/tokenspeed/pull/3301) `ci: publish tokenspeed-engine pip indexes` | infra,perf | ? | - |
| - | [#3302](https://github.com/lightseekorg/tokenspeed/pull/3302) `fix(scheduler): publish completed pages only when something can reuse them` | bug | ? | - |
| - | [#3303](https://github.com/lightseekorg/tokenspeed/pull/3303) `feat(dflash): support dflash for PD` |  | ? | - |
| - | [#3305](https://github.com/lightseekorg/tokenspeed/pull/3305) `fix(runtime): refresh stop criteria when request IDs are reused` | bug | ? | - |
| - | [#3306](https://github.com/lightseekorg/tokenspeed/pull/3306) `fix(host): notify launcher before blocking rank cleanup` | bug | ? | - |
| - | [#3307](https://github.com/lightseekorg/tokenspeed/pull/3307) `perf(dspark): run each greedy Markov step in one launch` | perf | ? | - |
| - | [#3308](https://github.com/lightseekorg/tokenspeed/pull/3308) `bugfix(pd): refresh cached routes and registrations after prefill restart` |  | ? | - |
| - | [#3309](https://github.com/lightseekorg/tokenspeed/pull/3309) `fix(distributed): use the current CUDA stream for PyNCCL operations` | bug,nvidia | ? | - |
| - | [#3310](https://github.com/lightseekorg/tokenspeed/pull/3310) `fix(packaging): move GPU memory saver to tokenspeed-kernel 0.1.5` | bug,perf | ? | - |
| - | [#3311](https://github.com/lightseekorg/tokenspeed/pull/3311) `test(spec): declare query_sharded on the drafter graph test backend` |  | ? | - |
| - | [#3313](https://github.com/lightseekorg/tokenspeed/pull/3313) `feat(profile): show the control plane and the C++ scheduler on /start_profile traces` |  | ? | - |
| - | [#3315](https://github.com/lightseekorg/tokenspeed/pull/3315) `feat(sampling): verify draft trees on sonic` |  | ? | - |
| - | [#3316](https://github.com/lightseekorg/tokenspeed/pull/3316) `test(prefill-graph): declare query_sharded on the dummy batch's draft backend` |  | ? | - |
| - | [#3318](https://github.com/lightseekorg/tokenspeed/pull/3318) `test: initialize mapping in distributed KV-scale update fixture` | quant | ? | - |
| - | [#3319](https://github.com/lightseekorg/tokenspeed/pull/3319) `perf(moe): tune Kimi-K3 decode experts past 128 rows on tile 32` | perf | ? | - |
| - | [#3320](https://github.com/lightseekorg/tokenspeed/pull/3320) `test: isolate DSV4.1 copy offsets and update index expectations` |  | ? | - |
| - | [#3325](https://github.com/lightseekorg/tokenspeed/pull/3325) `perf(scheduler): reduce full-cache CPU overhead while preserving RAII ownership` | perf | ? | - |
| - | [#3327](https://github.com/lightseekorg/tokenspeed/pull/3327) `perf(kimi-k31): select a DSA decode round's top-k beside the query absorption` | perf | ? | - |
| - | [#3332](https://github.com/lightseekorg/tokenspeed/pull/3332) `perf(spec): record a hot-token draft head's q over each rank's vocabulary columns` | perf | ? | - |
| - | [#3334](https://github.com/lightseekorg/tokenspeed/pull/3334) `ci(l3): require complete native validation evidence` | infra | ? | - |
| - | [#3335](https://github.com/lightseekorg/tokenspeed/pull/3335) `build: release tokenspeed-mla 2.0.10` | infra,perf | ? | - |
| - | [#3336](https://github.com/lightseekorg/tokenspeed/pull/3336) `build: require tokenspeed-mla 2.0.10` | infra,perf | ? | - |
| - | [#3338](https://github.com/lightseekorg/tokenspeed/pull/3338) `perf(muse-spark): run the BF16 expert layers through MoELayer` | perf | ? | - |
| - | [#3341](https://github.com/lightseekorg/tokenspeed/pull/3341) `fix(comm): release Lamport peer handles before scratch storage` | bug,infra | ? | - |
| - | [#3344](https://github.com/lightseekorg/tokenspeed/pull/3344) `feat(npu): add opt-in top-p sampling candidate cap` |  | ? | - |
| - | [#3348](https://github.com/lightseekorg/tokenspeed/pull/3348) `fix(qsa): report unavailable native top-k` | bug | ? | - |
| - | [#3349](https://github.com/lightseekorg/tokenspeed/pull/3349) `fix(prefill-graph): hold a break's frozen-dataclass tensors weakly when it has scalars` | bug | ? | - |
| - | [#3350](https://github.com/lightseekorg/tokenspeed/pull/3350) `feat(npu): extend DSA DCP8 decode and verify geometries` |  | ? | - |
| - | [#3352](https://github.com/lightseekorg/tokenspeed/pull/3352) `feat(cache): support sliding-window token sinks` | perf | ? | - |
| - | [#3354](https://github.com/lightseekorg/tokenspeed/pull/3354) `fix(sampling): synchronize radix histogram writers before block completion` | bug | ? | - |
| - | [#3356](https://github.com/lightseekorg/tokenspeed/pull/3356) `perf(engine): reduce logprob copies and codec overhead` | perf | ? | - |
| - | [#3357](https://github.com/lightseekorg/tokenspeed/pull/3357) `fix(npu): warm kernels on the serving stream and keep MoE weights rel…` | bug,perf | ? | - |
| - | [#3358](https://github.com/lightseekorg/tokenspeed/pull/3358) `perf(spec): replay the drafter's decode steps from graphs in prefill rounds` | perf | ? | - |
| - | [#3365](https://github.com/lightseekorg/tokenspeed/pull/3365) `fix(dspark): write context KV over every verify row in the draft's pages` | bug | ? | - |
| - | [#3366](https://github.com/lightseekorg/tokenspeed/pull/3366) `ci(monokernel): run the monokernel cross-GPU unit tests on two GPUs` | infra | ? | - |
| - | [#3367](https://github.com/lightseekorg/tokenspeed/pull/3367) `test(runtime): give the autotune executor doubles a serving stream` | perf | ? | - |
| - | [#3369](https://github.com/lightseekorg/tokenspeed/pull/3369) `fix(control): iterate over ranks in serving test` | bug | ? | - |
| - | [#3370](https://github.com/lightseekorg/tokenspeed/pull/3370) `perf(runtime): join a stream fork's branch once` | perf | ? | - |
| - | [#3371](https://github.com/lightseekorg/tokenspeed/pull/3371) `feat(model): day 0 support for Inkling 2 Small` |  | ? | - |
| - | [#3373](https://github.com/lightseekorg/tokenspeed/pull/3373) `test: initialize device in Mooncake weight-update runner fixture` |  | ? | - |
| - | [#3376](https://github.com/lightseekorg/tokenspeed/pull/3376) `fix(kernel): repair FP32 projection linkage and NVIDIA test guards` | bug,nvidia,perf | ? | - |
| P0 | [#3377](https://github.com/lightseekorg/tokenspeed/pull/3377) `fix(scheduler): stop reallocating a block table's ParentRefs on every append` | bug | main | - |
| - | [#3378](https://github.com/lightseekorg/tokenspeed/pull/3378) `fix(kimi): answer stores_capture_taps from the multimodal wrappers` | bug | ? | - |
| - | [#3379](https://github.com/lightseekorg/tokenspeed/pull/3379) `fix(dsa): preserve top-k candidates after a partial init window` | bug | ? | - |
| - | [#3380](https://github.com/lightseekorg/tokenspeed/pull/3380) `test(dspark): pass the anchor policy when sizing the context-write router` |  | ? | - |
| - | [#3382](https://github.com/lightseekorg/tokenspeed/pull/3382) `fix(ci): a parallel kernel test run that the changed-paths selection empties passes` | bug,infra,perf | ? | - |
| - | [#3383](https://github.com/lightseekorg/tokenspeed/pull/3383) `fix(npu): isolate block-scaled MoE GPU imports on Ascend` | bug,quant | ? | - |
| - | [#3384](https://github.com/lightseekorg/tokenspeed/pull/3384) `perf(k3-decode): rank the routing candidates with every thread at every row count` | perf | ? | - |
| - | [#3385](https://github.com/lightseekorg/tokenspeed/pull/3385) `fix(scheduler): pass cache group ID in SWA sink tests` | bug,perf | ? | - |
| - | [#3387](https://github.com/lightseekorg/tokenspeed/pull/3387) `perf(mla): floor the split-KV reducer capacity at 8 splits` | perf | ? | - |
| - | [#3390](https://github.com/lightseekorg/tokenspeed/pull/3390) `fix(loader): support shared writable mappings for host weights` | bug | ? | - |
| - | [#3391](https://github.com/lightseekorg/tokenspeed/pull/3391) `feat(runtime): support opt-in quantized weight discard` | quant | ? | - |
| - | [#3392](https://github.com/lightseekorg/tokenspeed/pull/3392) `feat(host): switch log timestamps to local time behind an env var` |  | ? | - |
| - | [#3393](https://github.com/lightseekorg/tokenspeed/pull/3393) `fix(kernel): restore the AMD kernel unit tests broken since the Inkling 2 Small kernels` | bug,perf,rocm | ? | - |
| - | [#3396](https://github.com/lightseekorg/tokenspeed/pull/3396) `docs(recipes): capture multi-request inline prefill for Kimi K3.1` |  | ? | - |
| - | [#3398](https://github.com/lightseekorg/tokenspeed/pull/3398) `fix(inkling2): minor fixes` | bug | ? | - |
| - | [#3401](https://github.com/lightseekorg/tokenspeed/pull/3401) `build: release tokenspeed-mla 2.0.11` | infra,perf | ? | - |
| - | [#3402](https://github.com/lightseekorg/tokenspeed/pull/3402) `build: require tokenspeed-mla 2.0.11` | infra,perf | ? | - |
| - | [#3403](https://github.com/lightseekorg/tokenspeed/pull/3403) `chore(deps): update tokenspeed-smg pin to 1.16.0.post20261113` | infra,perf | ? | - |

### tokenspeed — Open / submitted (35 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#3088](https://github.com/lightseekorg/tokenspeed/pull/3088) `fix(ci): allow pinned CUTLASS DSL companion in cu129 installs` | bug,infra,nvidia | ? | - |
| - | [#3095](https://github.com/lightseekorg/tokenspeed/pull/3095) `fix(streaming): flush output when a decode step crosses the interval` | bug | ? | - |
| P0 | [#3125](https://github.com/lightseekorg/tokenspeed/pull/3125) `perf(scheduler): keep slid-out sliding-window pages and evict them first` | perf | main | - |
| - | [#3142](https://github.com/lightseekorg/tokenspeed/issues/3142) `[Bug] Failed weight updates leave inference enabled without memory saver` |  | ? | - |
| - | [#3143](https://github.com/lightseekorg/tokenspeed/pull/3143) `fix(runtime): guard weight validity without memory saver` | bug | ? | - |
| - | [#3180](https://github.com/lightseekorg/tokenspeed/pull/3180) `refactor(qcp): separate query shard layout from per-forward tensor inputs` |  | ? | - |
| - | [#3181](https://github.com/lightseekorg/tokenspeed/pull/3181) `fix(dsa): require host row-start support during initialization` | bug | ? | - |
| - | [#3189](https://github.com/lightseekorg/tokenspeed/pull/3189) `refactor(npu): clarify MLA and DSA execution and resource boundaries` |  | ? | - |
| - | [#3191](https://github.com/lightseekorg/tokenspeed/pull/3191) `feat(scheduler): KV cache events carry the groups that hold a boundary` | perf | ? | - |
| P0 | [#3203](https://github.com/lightseekorg/tokenspeed/pull/3203) `perf(attention): skip Triton decode reduction for a single KV split` | perf,rocm | main | - |
| - | [#3218](https://github.com/lightseekorg/tokenspeed/pull/3218) `feat(pd): let a prefill compute before its decode allocation (opt-in)` |  | ? | - |
| P1 | [#3219](https://github.com/lightseekorg/tokenspeed/pull/3219) `feat(sampling): speculative sampling on the triton backend` | rocm | ? | - |
| - | [#3220](https://github.com/lightseekorg/tokenspeed/pull/3220) `feat(ple): share host embedding tables across local ranks` |  | ? | - |
| P1 | [#3224](https://github.com/lightseekorg/tokenspeed/pull/3224) `perf(engram): sort and dedup large MXFP8 host-table gathers` | perf,quant | ? | - |
| - | [#3227](https://github.com/lightseekorg/tokenspeed/pull/3227) `fix(client): end the stream when the client aborts a request` | bug | ? | - |
| P0 | [#3231](https://github.com/lightseekorg/tokenspeed/pull/3231) `feat(mha): serve an FP8 E4M3 KV cache through the portable Triton MHA kernels on AMD, draft trees included` | perf,quant,rocm | main | - |
| - | [#3237](https://github.com/lightseekorg/tokenspeed/pull/3237) `perf(mla): remove extra V.contiguous() buffer during prefill` | perf | ? | - |
| P1 | [#3251](https://github.com/lightseekorg/tokenspeed/pull/3251) `feat(kernel): opt-in online autotune of gfx950 BF16 GEMV routing` | perf,rocm | ? | - |
| - | [#3255](https://github.com/lightseekorg/tokenspeed/pull/3255) `feat(scheduler): fill the budget a holding prefill chunk leaves` |  | ? | - |
| - | [#3312](https://github.com/lightseekorg/tokenspeed/pull/3312) `perf(gdn): optimized FlashInfer backend when ReplaySSM chain is disabled` | nvidia,perf | ? | - |
| - | [#3321](https://github.com/lightseekorg/tokenspeed/pull/3321) `perf(sampling): draw each request's coins in one call per row` | perf | ? | - |
| - | [#3322](https://github.com/lightseekorg/tokenspeed/pull/3322) `perf(control): remember the JSON schemas already found to be JSON` | perf | ? | - |
| - | [#3328](https://github.com/lightseekorg/tokenspeed/issues/3328) `[Feature] Bound fatal rank shutdown when synchronous logging blocks` |  | ? | - |
| - | [#3329](https://github.com/lightseekorg/tokenspeed/pull/3329) `feat(cache): validate deployment Host memory budgets` | perf | ? | - |
| - | [#3330](https://github.com/lightseekorg/tokenspeed/pull/3330) `feat(metrics): expose L3 operation ages and alert rules` |  | ? | - |
| - | [#3331](https://github.com/lightseekorg/tokenspeed/pull/3331) `fix(l3): preserve retirement guarantees across failed shutdowns` | bug | ? | - |
| - | [#3333](https://github.com/lightseekorg/tokenspeed/pull/3333) `feat(hc): add FP8 gated residual mixing with prequantized fusion` | perf,quant | ? | - |
| - | [#3337](https://github.com/lightseekorg/tokenspeed/pull/3337) `test(l3): add opt-in cross-instance model serving gate` |  | ? | - |
| - | [#3347](https://github.com/lightseekorg/tokenspeed/pull/3347) `feat(ascend): serve a speculative verify window in MHA decode` |  | ? | - |
| - | [#3351](https://github.com/lightseekorg/tokenspeed/pull/3351) `perf(dsv41): enable independent encoder and decoder prefill graphs` | perf | ? | - |
| - | [#3360](https://github.com/lightseekorg/tokenspeed/pull/3360) `feat(benchmark): simulate fixed-state model forwards` | perf | ? | - |
| P1 | [#3363](https://github.com/lightseekorg/tokenspeed/pull/3363) `perf(rdna4): faster low-batch Qwen3.8-27B Quark MXFP4 decode` | perf,quant,rocm | ? | - |
| - | [#3375](https://github.com/lightseekorg/tokenspeed/pull/3375) `fix(ci): keep stale Ascend NPU reruns from superseding fresh checks` | bug,infra | ? | - |
| - | [#3381](https://github.com/lightseekorg/tokenspeed/pull/3381) `perf(ple): optimize rank-local host gather and verify state writes` | perf | ? | - |
| - | [#3394](https://github.com/lightseekorg/tokenspeed/pull/3394) `feat(pd): let a prefill compute before its decode allocation (opt-in)` |  | ? | - |

### tokenspeed — Closed unmerged (2 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| P0 | [#2927](https://github.com/lightseekorg/tokenspeed/pull/2927) `perf(qsa): share K across ragged prefill rows in block scoring` | perf | main | - |
| P0 | [#3048](https://github.com/lightseekorg/tokenspeed/pull/3048) `perf(amd): reuse stage 1's route grouping in the mxfp4 route-tile stage 2` | perf,quant,rocm | efric/muse-moe/01-stage1-k-tiles | - |
