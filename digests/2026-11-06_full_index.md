# Complete index — 2026-10-30 → 2026-11-06

Every cached item, unfiltered and unranked, for completeness. The curated digest is the separate file.

### aiter — Merged / closed (194 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#4188](https://github.com/ROCm/aiter/pull/4188) `[FlyDSL] gfx1201 (RDNA4) FlyDSL BF16 attention optimizations & FP8 attention implementation` | perf,quant,rocm | main | - |
| - | [#5114](https://github.com/ROCm/aiter/issues/5114) `[gfx950] fp8_mqa_logits: the >=2 GiB gl.store fallback fails to compile and aborts the process` | rocm | ? | - |
| - | [#5194](https://github.com/ROCm/aiter/pull/5194) `Cache the MLA split count, not the split indptr tensor` | perf | main | - |
| - | [#5461](https://github.com/ROCm/aiter/pull/5461) `[FlyDSL] [CI] One stage and two-stage ring all-reduce kernels for PCIe interconnects` | infra,perf,rocm | main | - |
| - | [#5505](https://github.com/ROCm/aiter/pull/5505) `[Triton/Gluon] Fix the hardcoded die and CU counts in the Triton kernels` | bug,perf,rocm | main | - |
| - | [#5518](https://github.com/ROCm/aiter/pull/5518) `[FlyDSL] [gfx950] Add explicit page strides and 64-bit rebase for FP4 MQA logits` | quant,rocm | main | - |
| - | [#5577](https://github.com/ROCm/aiter/pull/5577) `[Triton/Gluon] Add FP8 Flash Attention v2 kernel (gfx942/gfx950)` | infra,perf,quant,rocm | main | - |
| - | [#5578](https://github.com/ROCm/aiter/pull/5578) `[Triton/Gluon] Add MXFP8 Flash Attention v2 (gfx950 / CDNA4)` | quant,rocm | main | - |
| - | [#5815](https://github.com/ROCm/aiter/pull/5815) `[FlyDSL] [CI] Add FlyDSL fused intranode all-to-all for Ulysses sequence-parallel attention` | infra,perf,rocm | main | - |
| - | [#5913](https://github.com/ROCm/aiter/pull/5913) `[FlyDSL] feat(2stageGR) Two-stage Hyper-Connection Gated Residual kernel` | perf,rocm | main | - |
| - | [#5938](https://github.com/ROCm/aiter/pull/5938) `[JIT] fix(jit): keep detached-head advice local to third-party clone` | bug | main | - |
| - | [#5969](https://github.com/ROCm/aiter/pull/5969) `[CK] [FlyDSL] Introduce FP8 a8w8 gemm kernel with fp32 blockscale to uplift the MI355 blockwise gemm perf` | perf,quant,rocm | main | - |
| - | [#5970](https://github.com/ROCm/aiter/pull/5970) `[CI] [JIT] [kernel] Add an opt-in hipBLASLt grouped GEMM backend for SonicMoE` | infra,perf,rocm | main | - |
| - | [#5988](https://github.com/ROCm/aiter/pull/5988) `[ASM] [HIP] [CK] Add gfx950 Q256 fused MXFP4 prefill pipeline` | perf,quant,rocm | main | - |
| - | [#6024](https://github.com/ROCm/aiter/pull/6024) `[Triton/Gluon] [Perf] fused_reduce_act_mul_and_mxfp4_quant: wider launch tile, add round_to_input_dtype and tr` | perf,quant,rocm | main | - |
| - | [#6140](https://github.com/ROCm/aiter/pull/6140) `[HIP] [FlyDSL] [CI] Add aiter.paged_mqa_logits with a tuned Gluon/FlyDSL table` | infra,perf,rocm | main | - |
| - | [#6158](https://github.com/ROCm/aiter/pull/6158) `[Triton/Gluon] [Config] MoE and MLA configs for gfx1101, gfx1150 and gfx1151: sparse_mla_dsv4_train, sonicmoe` | rocm | main | - |
| - | [#6171](https://github.com/ROCm/aiter/pull/6171) `[ASM] [HIP] [JIT] [Perf] [Hardware][MI300X] Delayed mHC seam for gfx942 (mhc_fused_post_pre_delayed)` | perf,rocm | main | - |
| - | [#6185](https://github.com/ROCm/aiter/pull/6185) `[HIP] [CI] [JIT] Add aiter.mqa_logits with a tuned Triton/FlyDSL table` | infra,perf,rocm | main | - |
| - | [#6219](https://github.com/ROCm/aiter/pull/6219) `[Triton/Gluon] moe_gemm_a8w8: fnuz FP8 and MXFP8 on gfx942` | infra,quant,rocm | main | - |
| - | [#6244](https://github.com/ROCm/aiter/pull/6244) `[Triton/Gluon] Gluon PA decode: allow query_length > 4 on the single-KV-head PS path` | rocm | main | - |
| - | [#6270](https://github.com/ROCm/aiter/pull/6270) `[HIP] [JIT] [Feature] Custom allreduce: fused residual add and row-selective RMSNorm` | infra,perf,rocm | main | - |
| - | [#6427](https://github.com/ROCm/aiter/pull/6427) `[FlyDSL] Glm5 2 qkv proj opt for gfx950` | infra,rocm | main | - |
| - | [#6430](https://github.com/ROCm/aiter/pull/6430) `[Triton/Gluon] [FlyDSL] [CI] [MoE] MegaMoE gfx1250: stage1/stage2 switches, mori combine path, current mori EP` | infra,rocm | main | - |
| - | [#6458](https://github.com/ROCm/aiter/pull/6458) `[Triton/Gluon] [Kernel] Add dual-layout H16 MXFP4 quantization` | perf,quant,rocm | main | - |
| - | [#6464](https://github.com/ROCm/aiter/pull/6464) `[FLYDSL] Fea/mxfp4 flydsl a8w4 opt & replace` | infra,quant,rocm | main | - |
| - | [#6476](https://github.com/ROCm/aiter/pull/6476) `[Triton/Gluon] [Kernel] Add MXFP4 dequant H16 requantization` | perf,quant,rocm | main | - |
| - | [#6484](https://github.com/ROCm/aiter/pull/6484) `[Feature][MoE] fused_moe: skip moe_sorting when the caller registers a BM=16 presort` | infra,perf | main | - |
| - | [#6496](https://github.com/ROCm/aiter/pull/6496) `[FlyDSL] [gfx950] Add gdn fused prefill kernel` | perf,rocm | main | - |
| - | [#6545](https://github.com/ROCm/aiter/pull/6545) `[Triton/Gluon] Enable and tune pipelined unshuffled MLA decode on gfx1250` | perf,rocm | main | - |
| - | [#6552](https://github.com/ROCm/aiter/pull/6552) `[CK] [FlyDSL] gfx942 a16wmix a16w16: honour swiglu_limit for BF16 SiLU and SwiGLU` | rocm | main | - |
| - | [#6557](https://github.com/ROCm/aiter/pull/6557) `[FlyDSL] [gfx1250] Tune DeepSeek-R1 FP4 MoE tiles for high-batch decode` | perf,quant,rocm | main | - |
| - | [#6560](https://github.com/ROCm/aiter/pull/6560) `[Triton/Gluon] MHAv4 split-KV` | rocm | main | - |
| - | [#6564](https://github.com/ROCm/aiter/pull/6564) `[HIP] [FlyDSL] perf(mega_moe): fuse the gfx1250 compact dispatch and GEMM1 into one stage-1 kernel` | perf,rocm | main | - |
| - | [#6575](https://github.com/ROCm/aiter/pull/6575) `[Triton/Gluon] [ASM] [HIP] MHAv4 per-row block-sparse geometry, LSE and ragged KV on gfx950` | rocm | main | - |
| - | [#6578](https://github.com/ROCm/aiter/pull/6578) `[ASM] Fix KV addressing, mask scratch and empty splits in gfx950 BF16 32-head MLA` | bug,rocm | main | - |
| - | [#6645](https://github.com/ROCm/aiter/pull/6645) `[FlyDSL] Use HIP to query XCC count and share it with FlyDSL PA` | infra,rocm | main | - |
| - | [#6662](https://github.com/ROCm/aiter/pull/6662) `[HIP] [FlyDSL] Add gfx1250 implicit-GEMM conv3d` | rocm | main | - |
| - | [#6678](https://github.com/ROCm/aiter/pull/6678) `[Triton/Gluon] Add fused_reduce_add_rmsnorm` | infra,perf,rocm | main | - |
| - | [#6692](https://github.com/ROCm/aiter/pull/6692) `[CK] [Bugfix] FMoE tuner: use all sources for shapes FlyDSL v2 cannot tune` | perf,rocm | main | - |
| - | [#6727](https://github.com/ROCm/aiter/pull/6727) `[Triton/Gluon] Add Split-K Variant of A8W8 BMM with Fused Reduce Quant` | infra,perf,quant,rocm | main | - |
| - | [#6734](https://github.com/ROCm/aiter/pull/6734) `[HIP] Fuse a 32-point Hadamard rotation into the MXFP4 per-1x32 quant and AR + RMSNorm epilogue` | infra,perf,quant,rocm | main | - |
| - | [#6767](https://github.com/ROCm/aiter/pull/6767) `[Triton/Gluon] [HIP] [OPUS] [AITERKER-209] Add gfx1250-strict architecture plumbing` | rocm | main | - |
| - | [#6770](https://github.com/ROCm/aiter/pull/6770) `[Triton/Gluon] fav3_sage: RDNA3 (gfx1100) support: FP16 V and a tuned gfx1100 table` | perf,rocm | main | - |
| - | [#6831](https://github.com/ROCm/aiter/pull/6831) `[HIP] [Perf] Pipeline CSR segments in unsplit OPUS sparse prefill` | infra,perf,rocm | main | - |
| - | [#6844](https://github.com/ROCm/aiter/pull/6844) `[JIT] Build every listed CU count of each GPU_ARCHS arch` | infra | main | - |
| - | [#6854](https://github.com/ROCm/aiter/pull/6854) `[Triton/Gluon] [Bugfix] Fix uneven split-K bug in fused a8w8 blockscale GEMMs` | bug,perf,quant,rocm | main | - |
| - | [#6865](https://github.com/ROCm/aiter/pull/6865) `review-pr: add HK20 (submodule upstream check) and A4 (new-feature re…` |  | main | - |
| - | [#6879](https://github.com/ROCm/aiter/pull/6879) `[HIP] [BugFix] Clamp pos in fused_qk_rope_concat_and_cache_mla_seg_kernel` | perf,rocm | main | - |
| - | [#6881](https://github.com/ROCm/aiter/pull/6881) `[FlyDSL] [CI] MegaMoEV2: fuse Dispatch, GEMM1, GEMM2 and Combine into one kernel` | infra,perf,rocm | main | - |
| - | [#6884](https://github.com/ROCm/aiter/pull/6884) `[Triton/Gluon] Support a bf16 recurrent state in the fused GDN decode kernel` | perf,rocm | main | - |
| - | [#6886](https://github.com/ROCm/aiter/pull/6886) `[Test] Use the device fp8 range in test_fused_kv_norm_rope_group_quant` | perf,quant | main | - |
| - | [#6889](https://github.com/ROCm/aiter/pull/6889) `[Triton/Gluon] Window-aware split-KV for sliding-window verify on gfx950` | rocm | main | - |
| - | [#6925](https://github.com/ROCm/aiter/pull/6925) `[Triton/Gluon] Allow a strided feature dim in conv_state for single-token conv1d update` | rocm | main | - |
| - | [#6956](https://github.com/ROCm/aiter/pull/6956) `[FlyDSL] [JIT] Build the GEMM, conv, chunk_gdn_h and FP8 FMHA AOT caches by replaying the runtime` | infra,quant,rocm | main | - |
| - | [#6970](https://github.com/ROCm/aiter/pull/6970) `[HIP] [CK] [JIT] [Tuner] Rank accuracy-qualified kernels by package energy` | perf,risk,rocm | main | - |
| - | [#6979](https://github.com/ROCm/aiter/pull/6979) `[Triton/Gluon] [Config] Add gfx1151 RMSNorm large-M/small-N config` | rocm | main | - |
| - | [#6982](https://github.com/ROCm/aiter/pull/6982) `[Triton/Gluon] [Config] Add gfx1151 fused_sigmoid_mul config` | perf,rocm | main | - |
| - | [#6983](https://github.com/ROCm/aiter/pull/6983) `[Triton/Gluon] [gfx950] unified_attention: split-KV 3D configs for head_size <= 128 keyed on max_seqlen_q` | rocm | main | - |
| - | [#6985](https://github.com/ROCm/aiter/pull/6985) `[Triton/Gluon] [Config] Add gfx1151 batched_gemm_a16w16 configs` | rocm | main | - |
| - | [#6990](https://github.com/ROCm/aiter/pull/6990) `[CK] [Bugfix] Align batch prefill full-attention dispatch` |  | main | - |
| - | [#6996](https://github.com/ROCm/aiter/pull/6996) `[ASM] [HIP] gfx1250 mha bwd d192 d128 kernel integration` | perf,rocm | main | - |
| - | [#7018](https://github.com/ROCm/aiter/pull/7018) `[Config] [Perf] Tune DeepSeek-V4 M1/M2/M8/M64 FP8 GEMMs on gfx1250` | perf,quant,rocm | main | - |
| - | [#7029](https://github.com/ROCm/aiter/pull/7029) `[CI] Triton nightly test` | infra,rocm | main | - |
| - | [#7034](https://github.com/ROCm/aiter/pull/7034) `[Triton/Gluon] KDA cleanup` | rocm | main | - |
| - | [#7047](https://github.com/ROCm/aiter/pull/7047) `[Triton/Gluon] Mask OOB e8m0 scales on the ragged-K path of batched_gemm_afp4wfp4` | quant,rocm | main | - |
| - | [#7048](https://github.com/ROCm/aiter/pull/7048) `[Triton/Gluon] Add arch_info.is_sw_emulated_fp4_avail() and enable gemm_afp4wfp4 on gfx1101` | rocm | main | - |
| - | [#7056](https://github.com/ROCm/aiter/pull/7056) `[FlyDSL] pa_decode: MXFP4 K/V in the shared PA tile kernel (gfx950, query_length 1)` | perf,quant,rocm | main | - |
| - | [#7057](https://github.com/ROCm/aiter/pull/7057) `[HIP] fused_qknorm_idxrqknorm: write MXFP4 index-K and main KV caches, emit an fp8 main Q` | perf,quant,rocm | main | - |
| - | [#7060](https://github.com/ROCm/aiter/pull/7060) `[FlyDSL] MiniMax-M3 index score: MXFP4 index-cache decode scorer` | perf,quant,rocm | main | - |
| - | [#7061](https://github.com/ROCm/aiter/pull/7061) `[FlyDSL] MiniMax-M3 index score: MXFP4 index-cache prefill scorer` | perf,quant,rocm | main | - |
| - | [#7074](https://github.com/ROCm/aiter/pull/7074) `bench_mega_moe: fix kernel table on multi-stream graphs, add --fused_shared_experts` | bug,infra,perf | main | - |
| - | [#7075](https://github.com/ROCm/aiter/pull/7075) `[Config] Add MI350P TP1 a4w4 GEMM tuning for Qwen3.8-27B-Quark-AWQ-MXFP4` | perf,quant,rocm | main | - |
| - | [#7079](https://github.com/ROCm/aiter/pull/7079) `[FlyDSL] Merge gfx1250 PA decode partitions in the tile kernel and speed up dense decode` | perf,rocm | main | - |
| - | [#7080](https://github.com/ROCm/aiter/pull/7080) `[HIP] Speed up gfx1250 two-stage AR RMSNorm FP8 amax reduction` | perf,quant,rocm | main | - |
| - | [#7092](https://github.com/ROCm/aiter/pull/7092) `[FlyDSL] pa_decode: zero V rows past the context before PV` | rocm | main | - |
| - | [#7097](https://github.com/ROCm/aiter/pull/7097) `MHAv4: temporarily disable `rotated_fp8_quantization_matches_reference` on gfx942` | infra,quant,rocm | main | - |
| - | [#7099](https://github.com/ROCm/aiter/issues/7099) `ROCm 10.1 (clang 24): 8-wave cktile blockscale GEMMs no longer inlined, 7-15x slower` | perf,quant,rocm | ? | - |
| - | [#7101](https://github.com/ROCm/aiter/pull/7101) `[HIP] [Bugfix] Accept generic torch.Stream in torch_to_c_types` | infra,rocm | main | - |
| - | [#7103](https://github.com/ROCm/aiter/pull/7103) `[JIT] Add -mllvm -ignore-tti-inline-compatible=true for the 10.1 LLVM compiler to avoid some performance loss ` | perf,rocm | main | - |
| - | [#7104](https://github.com/ROCm/aiter/pull/7104) `[FlyDSL] moe_reduce: guard against -1 topk_ids padding sentinel` | rocm | main | - |
| - | [#7110](https://github.com/ROCm/aiter/pull/7110) `[ASM] Fix for num_local_tokens` | bug | main | - |
| - | [#7121](https://github.com/ROCm/aiter/pull/7121) `[Triton/Gluon] : Change RotatingBuffersBench API and update any existing benchmarks` | bug,perf,rocm | main | - |
| - | [#7124](https://github.com/ROCm/aiter/pull/7124) `[ASM] [HIP] [OPUS] Add gfx950 MLA v4.1 a8w4 prefill kernels for an NVFP4 prefix KV` | perf,quant,rocm | main | - |
| - | [#7126](https://github.com/ROCm/aiter/pull/7126) `[Triton/Gluon] [FlyDSL] [CI] [Bugfix] Never share scratch buffers whose zero fill was recorded into a graph` | infra,rocm | main | - |
| - | [#7127](https://github.com/ROCm/aiter/pull/7127) `[FlyDSL] Tune DSv4.1 EP8 A8W4 MegaMoE` | infra,perf,rocm | main | - |
| - | [#7130](https://github.com/ROCm/aiter/pull/7130) `[FlyDSL][MoE] Fix gfx1250 HERD decode routing and extend it past 512 experts` | bug,rocm | main | - |
| - | [#7131](https://github.com/ROCm/aiter/pull/7131) `[HIP] [JIT] [gfx1250] Add Mega-MHC kernels for DeepSeek-V4.1 (fused MXFP8, row-major scales)` | perf,quant,rocm | main | - |
| - | [#7134](https://github.com/ROCm/aiter/pull/7134) `[HIP] [Perf] Route gfx950 E=128..255 decode at M>=17 to multi-phase MoE sorting` | perf,rocm | main | - |
| - | [#7142](https://github.com/ROCm/aiter/pull/7142) `[HIP] [FlyDSL] [GFX1250] Kimi-K3 DSpark PTPC/blockscale and f_b_proj GEMM rows` | quant,rocm | main | - |
| - | [#7147](https://github.com/ROCm/aiter/pull/7147) `[FlyDSL] [Bugfix] Fix PA decode scaling and merge alignment` | bug,rocm | zhiding512/gfx1250-pa-merge-partitions | - |
| - | [#7149](https://github.com/ROCm/aiter/pull/7149) `[HIP] fix(custom_ar): make 6-rank custom collectives correct` | bug,infra,rocm | main | - |
| - | [#7155](https://github.com/ROCm/aiter/pull/7155) `[HIP] feat(custom_ar): read captured gfx1250 inputs in place on the IPC transport` | rocm | main | - |
| - | [#7159](https://github.com/ROCm/aiter/pull/7159) `[OPUS] Fix CU lookup compatibility and gfx1250 kernel queries` | bug,perf,rocm | main | - |
| - | [#7160](https://github.com/ROCm/aiter/pull/7160) `[ASM] [HIP] gfx1250 mha bwd: hd64 kernels and hd128 border mask` | perf,rocm | main | - |
| - | [#7162](https://github.com/ROCm/aiter/pull/7162) `[Triton/Gluon] [Config] [Tune] [gfx950] Add gfx950 Llama blockscale GEMM configurations (gfx950)` | perf,quant,rocm | main | - |
| - | [#7163](https://github.com/ROCm/aiter/pull/7163) `[CI] Drop the Aiter Test Gate requirement for CI-only changes` | bug,infra,rocm | main | - |
| - | [#7171](https://github.com/ROCm/aiter/pull/7171) `[Triton/Gluon] Add fused bf16 BMM + cat + FP8 quant + head pad for MLA decode` | perf,quant,rocm | main | - |
| - | [#7173](https://github.com/ROCm/aiter/pull/7173) `[ASM] [HIP] Mha v4: gfx950 hd256 mxfp4/6 kernels with per-batch seqlens_k` | perf,quant,rocm | main | - |
| - | [#7174](https://github.com/ROCm/aiter/pull/7174) `[Triton/Gluon] bench_sage: route head dim 256 to the hd256 mxfp4/6 producers` | perf,quant,rocm | main | - |
| - | [#7182](https://github.com/ROCm/aiter/pull/7182) `[Bugfix] MLA decode: merge only the splits gfx950 bf16 gqa32 stage 1 writes` | rocm | main | - |
| - | [#7185](https://github.com/ROCm/aiter/pull/7185) `[OPUS] [JIT] Fall back to regular COs when A0 strict is unsupported by the HIP runtime` | rocm | main | - |
| - | [#7191](https://github.com/ROCm/aiter/pull/7191) `[FlyDSL] Rename gfx1250 TDM kernel prefix from a8w4 to mxfp4` | perf,quant,rocm | main | - |
| - | [#7194](https://github.com/ROCm/aiter/issues/7194) `[Triton] batched_gemm_afp4wfp4 outputs NaN for shape B=2 M=256 N=3584 K=2112 on gfx950` | bug,risk,rocm | ? | - |
| - | [#7197](https://github.com/ROCm/aiter/pull/7197) `[FlyDSL] pa_decode: peel the last KV tile so only it carries the V tail mask` | rocm | main | - |
| - | [#7204](https://github.com/ROCm/aiter/pull/7204) `[Config] [Tuning] Qwen3.8-Flash-Next TP4 prefill BF16 GEMMs on MI308X (gfx942, 80 CU)` | perf,rocm | main | - |
| - | [#7205](https://github.com/ROCm/aiter/pull/7205) `[FlyDSL] Make PA planner batch and capacity runtime values` | rocm | main | - |
| - | [#7208](https://github.com/ROCm/aiter/pull/7208) `[Misc] Package aiter skills as a Claude Code plugin; drop FlyDSL duplicates` | rocm | create-pr-skill | - |
| - | [#7209](https://github.com/ROCm/aiter/pull/7209) `[Config] [gfx1250] Tune MiniMax-M3 TP4 BF16, indexer-CP QKV and MoE token 1024` | perf,rocm | main | - |
| - | [#7213](https://github.com/ROCm/aiter/pull/7213) `[FlyDSL] Tdm new interface refactor: make_tdm_atom -> make_tiled_tdm_atom` | rocm | main | - |
| - | [#7214](https://github.com/ROCm/aiter/pull/7214) `[FlyDSL] FMHA gfx1250: per-tensor fp8 descales for the a8w8 kernel` | perf,quant,rocm | main | - |
| - | [#7215](https://github.com/ROCm/aiter/pull/7215) `[ASM] [HIP] feat(fmha_bwd): gfx950 sliding window attention backward kernels` | perf,rocm | main | - |
| - | [#7219](https://github.com/ROCm/aiter/pull/7219) `[Perf] Avoid torch Stream construction across grouped MoE launches` | perf,rocm | main | - |
| - | [#7224](https://github.com/ROCm/aiter/pull/7224) `[Config] Add Beam FP8 fused MoE configs for gfx950` | perf,quant,rocm | main | - |
| - | [#7229](https://github.com/ROCm/aiter/pull/7229) `[CI] Run the selected Triton tests on each merge to main` | infra,rocm | main | - |
| - | [#7234](https://github.com/ROCm/aiter/pull/7234) `[Config] [gfx1250] Tune DeepSeek-V4.1-Flash dense FP8 GEMM tiles for intermediate-M decode` | perf,quant,rocm | main | - |
| - | [#7235](https://github.com/ROCm/aiter/pull/7235) `[Config] Mistral Large 4 gfx950 tuned tables (TP8 + TP4)` | perf,rocm | main | - |
| - | [#7241](https://github.com/ROCm/aiter/issues/7241) `FlyDSL int32 overflow in grouped_gemm_mxfp4 arena_handle on gfx1250 EP4 DSR1` | bug,quant,risk,rocm | ? | - |
| - | [#7246](https://github.com/ROCm/aiter/pull/7246) `[Config] [Perf] Tune gfx1250 DSv4.1 BF16 LM-head and router GEMMs` | perf,rocm | main | - |
| - | [#7247](https://github.com/ROCm/aiter/pull/7247) `[Config] [Tune] [gfx1250] DeepSeek-V4.1-Flash BF16 and MX32 FP8 GEMM rows (complements #7246)` | perf,quant,rocm | main | - |
| - | [#7250](https://github.com/ROCm/aiter/pull/7250) `[CI] Update triton-nightly-watchers.txt with new users` | infra,rocm | main | - |
| - | [#7253](https://github.com/ROCm/aiter/pull/7253) `[Triton/Gluon] [gfx1250] unified_attention 2D: bound gathered page ids by the sequence` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#7257](https://github.com/ROCm/aiter/pull/7257) `[Triton/Gluon] MHA prefill: use the gfx1151 attn_fwd config on gfx1150` | infra,rocm | main | - |
| - | [#7258](https://github.com/ROCm/aiter/pull/7258) `[FlyDSL] QuickAllReduce INT4: E5M2 group scale so groups above 480 no longer clip` | quant,rocm | main | - |
| - | [#7265](https://github.com/ROCm/aiter/pull/7265) `[HIP] perf(custom_ar): gfx1250 LL all-gather for messages up to 4 MiB a rank` | perf,rocm | main | - |
| - | [#7271](https://github.com/ROCm/aiter/pull/7271) `[FlyDSL] Add flyc.compile to skills. and cache HERD host launches` | perf,rocm | main | - |
| - | [#7272](https://github.com/ROCm/aiter/pull/7272) `[FlyDSL] optimize dsv4 flash perf` | perf,rocm | main | - |
| - | [#7273](https://github.com/ROCm/aiter/issues/7273) `[Issue]: Missing rocm 10.x support` | rocm | ? | - |
| - | [#7287](https://github.com/ROCm/aiter/issues/7287) `[Perf][gfx950][MXFP4] gemm_a4w4 selects a slower path for narrow-N dense GEMM shapes` | perf,quant,rocm | ? | - |
| - | [#7290](https://github.com/ROCm/aiter/pull/7290) `[CI] CI: auto-update split test times` | infra | main | - |
| - | [#7294](https://github.com/ROCm/aiter/pull/7294) `[FlyDSL] [CI] [MoE] gemm2: bound atomic rows by the sort's valid token count` | infra,rocm | main | - |
| - | [#7296](https://github.com/ROCm/aiter/pull/7296) `[FlyDSL] optimize dsv4.1, k3, m3 moe perf for gfx1250` | perf,rocm | main | - |
| - | [#7299](https://github.com/ROCm/aiter/pull/7299) `[FlyDSL] Fix grouped GEMM C ABI overflow for large EP buffers` | bug,risk,rocm | main | - |
| - | [#7302](https://github.com/ROCm/aiter/pull/7302) `[HIP] [Bugfix] Skip empty inputs in custom all-gather` | rocm | main | - |
| - | [#7303](https://github.com/ROCm/aiter/pull/7303) `review-pr: publish the card as a PR review with findings anchored inline` |  | main | - |
| - | [#7309](https://github.com/ROCm/aiter/pull/7309) `[HIP] [FlyDSL] optimize dsv41 perf for decode shape` | perf,rocm | main | - |
| - | [#7311](https://github.com/ROCm/aiter/pull/7311) `[Triton/Gluon] fix: remove exact-M RMSNorm forward specialization` | bug,rocm | main | - |
| - | [#7314](https://github.com/ROCm/aiter/pull/7314) `[ASM] [HIP] [OPUS] Add gfx1250 MLA v4.1 a8w8 sparse prefill kernels` | perf,quant,rocm | main | - |
| - | [#7315](https://github.com/ROCm/aiter/pull/7315) `[FlyDSL] [gfx1250] mega_moe S1F: reachable stage-1 hook, plan precompile, tuned defaults (on by default)` | perf,rocm | main | - |
| - | [#7316](https://github.com/ROCm/aiter/pull/7316) `[CI] Reuse FlyDSL AOT cache and reduce A8W8 GEMM test overhead` | infra,perf,quant,rocm | main | - |
| - | [#7317](https://github.com/ROCm/aiter/pull/7317) `[HIP] [CK] [FlyDSL] [GEMM][gfx950] Tune narrow-N MXFP4 with CSV-selected preshuffle kernels` | perf,quant,rocm | main | - |
| - | [#7318](https://github.com/ROCm/aiter/pull/7318) `mrope cache-quant test: covering default set, full matrix behind --full` | perf,quant | main | - |
| - | [#7321](https://github.com/ROCm/aiter/pull/7321) `[CI] [MLA] test_mla_v4_nm: make the script perf sweep opt-in` | infra,perf | main | - |
| - | [#7323](https://github.com/ROCm/aiter/pull/7323) `[Test] Shrink the default shapes of test_topk_per_row.py` |  | main | - |
| - | [#7330](https://github.com/ROCm/aiter/pull/7330) `[CI] Scope test_moe_2stage.py to representative tokens in standard CI` | infra | main | - |
| - | [#7331](https://github.com/ROCm/aiter/pull/7331) `[FlyDSL] [CI] Conv3d: default to representative Wan correctness, move full matrix to perf mode` | bug,infra,perf,rocm | main | - |
| - | [#7340](https://github.com/ROCm/aiter/pull/7340) `[CI] [Build] Pin FlyDSL to v0.4.2` | infra,rocm | main | - |
| - | [#7347](https://github.com/ROCm/aiter/pull/7347) `[Triton/Gluon] [Config] Tune gfx950 gemm_a8w8 for Llama 3.1 8B FP8 decode.` | perf,quant,rocm | main | - |
| - | [#7348](https://github.com/ROCm/aiter/pull/7348) `[Triton/Gluon] [gfx1250] unified attention: 128-token tile for 8-heads-per-KV bf16 prefill` | rocm | shaoclee/bench_ua_perm | - |
| - | [#7356](https://github.com/ROCm/aiter/issues/7356) `[Issue]: AITER_AR_1STAGE_MAX_KB is compared as bytes, not KiB, in the fused all-reduce one-stage limit` | perf,rocm | ? | - |
| - | [#7357](https://github.com/ROCm/aiter/pull/7357) `[Bugfix] Clarify fused all-reduce limit units with MAX_BYTES` | perf | main | - |
| - | [#7358](https://github.com/ROCm/aiter/issues/7358) `[Issue]: gfx950 Opus MoE sort auto dispatch keeps E=384 small-token decode on the slower one-shot kernel` | perf,rocm | ? | - |
| - | [#7359](https://github.com/ROCm/aiter/pull/7359) `[HIP] [Perf] Route gfx950 Opus MoE sort auto dispatch to multi-phase for E=384 decode` | perf,rocm | main | - |
| - | [#7363](https://github.com/ROCm/aiter/pull/7363) `[FlyDSL] [MoE] Reuse stage2 scatter/reduce scratch in _flydsl_v2_stage2_wrapper` | rocm | main | - |
| - | [#7365](https://github.com/ROCm/aiter/pull/7365) `[FlyDSL] [AMD][DSV4] fix: drop expert -1 pad routes in the fused TP route/psumkernel` | bug,perf,rocm | main | - |
| - | [#7366](https://github.com/ROCm/aiter/pull/7366) `[Config] [gfx1250] Tune DeepSeek-V4.1-Flash MX32 FP8 GEMMs at large decode M` | perf,quant,rocm | main | - |
| - | [#7373](https://github.com/ROCm/aiter/pull/7373) `[HIP] [Bugfix] sample_kernels: partial-vector and prologue-tail defects` | rocm | main | - |
| - | [#7375](https://github.com/ROCm/aiter/pull/7375) `[ASM] [HIP] [FlyDSL] [gfx1250] asm mha fp8 fwd: add D192x128 per-tensor varlen kernel` | perf,quant,rocm | main | - |
| - | [#7376](https://github.com/ROCm/aiter/pull/7376) `[HIP] [Bugfix] Skip grouped top-k launches with zero tokens` | rocm | main | - |
| - | [#7379](https://github.com/ROCm/aiter/pull/7379) `[FlyDSL] [AOT] Build gfx1250-strict wheels from the gfx1250 kernel family` | infra,perf,rocm | main | - |
| - | [#7383](https://github.com/ROCm/aiter/pull/7383) `Add gfx950 a8w8 blockscale GEMM tunings for Qwen3-14B-FP8` | perf,quant,rocm | main | - |
| - | [#7384](https://github.com/ROCm/aiter/pull/7384) `[FlyDSL] gfx1250 PA decode: BF16 wave-pair pipeline at D64, drop redundant D128 checks` | rocm | main | - |
| - | [#7390](https://github.com/ROCm/aiter/pull/7390) `[ASM] [HIP] [JIT] Fold gfx1250 MLA v4.1 sparse prefill split-K in-kernel with workgroup clusters` | perf,rocm | main | - |
| - | [#7392](https://github.com/ROCm/aiter/pull/7392) `[CI] ci: avoid build runner for disabled wheel jobs` | infra | main | - |
| - | [#7395](https://github.com/ROCm/aiter/pull/7395) `[ASM] [HIP] [JIT] Clamp bf16 MLA decode kv_indices and move gfx950 kernels to opus/gfx950/` | perf,rocm | main | - |
| - | [#7411](https://github.com/ROCm/aiter/pull/7411) `[Config] MiniMax-M3 MXFP8: tune N=1280 K=6144 (DSpark context KV projection)` | perf,quant | main | - |
| - | [#7418](https://github.com/ROCm/aiter/pull/7418) `[HIP] [MLA] Store per-request qo lengths before the v1_2 planner reads them` | rocm | main | - |
| - | [#7424](https://github.com/ROCm/aiter/pull/7424) `[FlyDSL] Move _e8m0_byte_to_f32 into mxfp4_gemm_common` | quant,rocm | main | - |
| - | [#7428](https://github.com/ROCm/aiter/pull/7428) `[CI] Build release wheels for ROCm 7.14, 10.0 and 10.1 (Drop 7.0 and 7.1)` | infra,rocm | main | - |
| - | [#7429](https://github.com/ROCm/aiter/pull/7429) `[Triton/Gluon] [GFX950] Add custom sparse MLA kernel for tensor scale fp8 kv cache` | perf,quant,rocm | main | - |
| - | [#7433](https://github.com/ROCm/aiter/pull/7433) `[HIP] [FlyDSL] [Bugfix] Size the custom allreduce pool from per-op AR/AG/RS max-size env vars` | rocm | main | - |
| - | [#7434](https://github.com/ROCm/aiter/pull/7434) `[OPUS] [FlyDSL] [AOT] Cover the full gfx1250 kernel family for gfx1250-strict wheels` | perf,rocm | main | - |
| - | [#7438](https://github.com/ROCm/aiter/pull/7438) `[CI] Fix flash attention Windows smoke checkout` | bug,infra | main | - |
| - | [#7439](https://github.com/ROCm/aiter/pull/7439) `[HIP] [FlyDSL] tune bmm and mxfp8 together ,update related tuned csv` | perf,quant,rocm | main | - |
| - | [#7441](https://github.com/ROCm/aiter/pull/7441) `[Config] Add gfx950 a4w4 GEMM configs for Qwen3.8-2.4T GDN in_proj_qkvz at TP8` | quant,rocm | main | - |
| - | [#7452](https://github.com/ROCm/aiter/pull/7452) `[HIP] fea: impl lamport allreduce on gfx9` | rocm | main | - |
| - | [#7464](https://github.com/ROCm/aiter/pull/7464) `[HIP] [MLA] Align gfx942 QH64 FP8 page-size planning` | quant,rocm | main | - |
| - | [#7468](https://github.com/ROCm/aiter/pull/7468) `[WIP][FlyDSL] MoE fused quant for prefill: token-multidest with route counts, compact-scale two-pass` | perf,quant,rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#7472](https://github.com/ROCm/aiter/pull/7472) `[Triton/Gluon] unified_attention: keep 3D split-KV padding rows from storing segment stats` | infra,rocm | main | - |
| - | [#7475](https://github.com/ROCm/aiter/pull/7475) `[FlyDSL] [Perf] Tune flydsl_attn_res loads and grid choice for gfx942` | perf,rocm | flydsl-attn-res | - |
| - | [#7477](https://github.com/ROCm/aiter/pull/7477) `[Config] Tune Preshuffled A8W8 GEMM for DSR1 Shapes on gfx1250` | perf,quant,rocm | main | - |
| - | [#7482](https://github.com/ROCm/aiter/pull/7482) `[CI] Make PR Self-Review verdicts evidence-driven instead of event-driven` | infra | main | - |
| - | [#7485](https://github.com/ROCm/aiter/pull/7485) `[Config] Add Kimi-K3.1 Pro gfx950 BF16 GEMM tuned rows to kimik3 tables` | perf,rocm | main | - |
| - | [#7487](https://github.com/ROCm/aiter/pull/7487) `[HIP] [JIT] gfx1250 mha: fix the CK JIT builds and route the Python backward to asm` | bug,rocm | main | - |
| - | [#7490](https://github.com/ROCm/aiter/pull/7490) `[Release v0.1.28] Re-cut post1 from main through #7429` | infra | release/v0.1.28 | - |
| - | [#7491](https://github.com/ROCm/aiter/pull/7491) `[HIP] [JIT] Guard Mega-MHC gfx1250 sources by build target` | infra,rocm | main | - |
| - | [#7494](https://github.com/ROCm/aiter/pull/7494) `[Triton/Gluon] [FlyDSL] [MoE] Kimi-K3 HERD on gfx1250: K+1 sigmoid top-k and one route+psum kernel` | perf,rocm | main | - |
| - | [#7495](https://github.com/ROCm/aiter/pull/7495) `Zan/dsv41 decoding exp` |  | zan/dsv41-decoding | - |
| - | [#7498](https://github.com/ROCm/aiter/pull/7498) `[Config] configs: add MiniMax-M3.1 gfx950 GEMM tuning` | perf,rocm | main | - |
| - | [#7505](https://github.com/ROCm/aiter/pull/7505) `[OPUS] [gfx1250] Clear HIP sticky error after A0 strict-CO probe failure (#7185 follow-up)` | rocm | main | - |
| - | [#7507](https://github.com/ROCm/aiter/pull/7507) `[Config] [gfx1250] Tune MiniMax-M3 DP4/EP4 dense GEMMs` | perf,rocm | main | - |
| - | [#7535](https://github.com/ROCm/aiter/issues/7535) `[Issue]: FlyDSL AOT replay aborts on ROCm 10: ROCR_VISIBLE_DEVICES=-1 is rejected` | rocm | ? | - |
| - | [#7541](https://github.com/ROCm/aiter/pull/7541) `[CI] Skip Flash Attention CI on draft PRs` | infra | main | - |
| - | [#7551](https://github.com/ROCm/aiter/pull/7551) `[FlyDSL] [AOT] Hide the GPUs from replays with empty device lists, not -1` | rocm | main | - |

### aiter — Open / submitted (271 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#7180](https://github.com/ROCm/aiter/pull/7180) `[CI] Cache compiled objects across builds with ccache (2h16m -> ~6m)` | infra,perf | main | - |
| - | [#7181](https://github.com/ROCm/aiter/pull/7181) `[HIP] [JIT] [Perf] Speed up gfx950 mHC decode with Gram statistics` | perf,rocm | main | - |
| - | [#7183](https://github.com/ROCm/aiter/pull/7183) `[HIP] [JIT] Add gfx950 prefill FP8 MQA logits` | quant,rocm | main | - |
| - | [#7184](https://github.com/ROCm/aiter/pull/7184) `[HIP] [JIT] Add gfx950 paged FP8 MQA logits` | quant,rocm | main | - |
| - | [#7186](https://github.com/ROCm/aiter/pull/7186) `[Triton/Gluon] [Kernel] Gluon MHA kernel for gfx1250 (fp16/fp8)` | perf,quant,rocm | main | - |
| - | [#7187](https://github.com/ROCm/aiter/pull/7187) `mla file for 1250` |  | main | - |
| - | [#7188](https://github.com/ROCm/aiter/pull/7188) `Tune gfx1250 A4W4 MoE prefill TDM GEMM, retune E96 and add E1 config` | perf,quant,rocm | dev/yadai_prefill_clean | - |
| - | [#7189](https://github.com/ROCm/aiter/pull/7189) `tuned values for k3` | perf | main | - |
| - | [#7192](https://github.com/ROCm/aiter/pull/7192) `[Triton/Gluon] [GFX950] Mha v4 production` | rocm | main | - |
| - | [#7195](https://github.com/ROCm/aiter/pull/7195) `[DO NOT MERGE] [CI] Add a manual gfx1201 DevLab Dispatch smoke test.` | infra,rocm | main | - |
| - | [#7196](https://github.com/ROCm/aiter/pull/7196) `[FlyDSL] MegaMoEV2: opt-in Stage2 + combine over SDMA with an 8-wave GEMM2` | rocm | main | - |
| - | [#7198](https://github.com/ROCm/aiter/pull/7198) `[HIP] tune(qwen3.5-397b mxfp4): lm_head, small-M FP8 projection and MoE rows for TP4/TP2 (+ TP4 MXFP4 MoE shap` | perf,quant,rocm | main | - |
| - | [#7199](https://github.com/ROCm/aiter/pull/7199) `perf(flydsl pa_decode): let the head-256 FP8 pipe take three and four M-tiles (48/64 query rows)` | perf,quant,rocm | main | - |
| - | [#7200](https://github.com/ROCm/aiter/pull/7200) `[Triton/Gluon] [FlyDSL] [CI] [MoE] MegaMoE gfx1250 internal CI mirror of #6430` | infra,rocm | main | - |
| - | [#7201](https://github.com/ROCm/aiter/pull/7201) `[Triton/Gluon] [Bugfix] gfx1250 Gluon unified attention 2D: zero V rows past the sequence end` | infra,rocm | main | - |
| - | [#7202](https://github.com/ROCm/aiter/pull/7202) `[Triton/Gluon] [Bugfix] gfx1250 a8w4 MoE decode: store the output tile from registers, not LDS + TDM store` | rocm | main | - |
| - | [#7203](https://github.com/ROCm/aiter/pull/7203) `[Triton/Gluon] [Bugfix] gfx1250 unified attention 2D: store decode outputs from registers` | infra,rocm | main | - |
| - | [#7206](https://github.com/ROCm/aiter/pull/7206) `[FlyDSL] feat(flydsl pa_decode): expose can_use_flydsl_pa_decode, the host-side acceptance check` | rocm | main | - |
| - | [#7207](https://github.com/ROCm/aiter/pull/7207) `[Build] [Misc] Add create-pr skill for review-ready aiter PRs` | infra,rocm | main | - |
| - | [#7210](https://github.com/ROCm/aiter/pull/7210) `[Perf] Reduce fused MoE dispatcher keyword matching overhead` | perf | main | - |
| - | [#7211](https://github.com/ROCm/aiter/pull/7211) `[Triton/Gluon] [Perf] Use complete split-loop bounds and tune gfx950 GEMM` | perf,rocm | main | - |
| - | [#7212](https://github.com/ROCm/aiter/pull/7212) `[gfx1250] Extend fused all-reduce RMSNorm to MiniMax-M3 shapes` | perf,rocm | main | - |
| - | [#7216](https://github.com/ROCm/aiter/pull/7216) `[Docs] Persist FlyDSL kernel caches across containers` | perf,rocm | main | - |
| - | [#7217](https://github.com/ROCm/aiter/pull/7217) `[JIT] [Perf] Avoid allocating dummy dispatch tensors for inference collectives` | perf | main | - |
| - | [#7218](https://github.com/ROCm/aiter/pull/7218) `[Config] Add tuned GEMM and fused-MoE configs for MI350P (gfx950, 128 CUs)` | perf,rocm | main | - |
| - | [#7220](https://github.com/ROCm/aiter/pull/7220) `fix the _fold_seqlen_indptr perf error` | bug,perf | main | - |
| - | [#7222](https://github.com/ROCm/aiter/pull/7222) `[FlyDSL] [Fix] Guard dropped expert IDs in fused MoE route and remap` | bug,perf,rocm | main | - |
| - | [#7223](https://github.com/ROCm/aiter/pull/7223) `[FlyDSL] [Perf] Keep FP4 quantization K-splits before selecting compact scales` | perf,quant,rocm | main | - |
| - | [#7225](https://github.com/ROCm/aiter/pull/7225) `[Triton/Gluon] KDA packed decode: accept the fused conv1d weight` | perf,rocm | main | - |
| - | [#7226](https://github.com/ROCm/aiter/pull/7226) `[Docs] FlyDSL review guidance: live-GPU test gates, test quality, Copilot checks, aiter FlyDSL notes` | rocm | main | - |
| - | [#7227](https://github.com/ROCm/aiter/pull/7227) `review-pr: correct FlyDSL D10/D10b and add D13/D14 from review outcomes` | rocm | main | - |
| - | [#7228](https://github.com/ROCm/aiter/pull/7228) `[Triton/Gluon] Fused a16w16 GEMM with a separate tile and split-K per output` | perf,rocm | main | - |
| - | [#7230](https://github.com/ROCm/aiter/pull/7230) `[HIP] [Tuning] [gfx950] Add MiniMax-M3 MXFP4 MoE configs for TP8 (E=128, top-4, inter_dim 384)` | perf,quant,rocm | main | - |
| - | [#7231](https://github.com/ROCm/aiter/pull/7231) `[Triton/Gluon] [Perf] Tune the act_mul_and_fp8_group_quant launch on gfx942` | infra,perf,quant,rocm | main | - |
| - | [#7232](https://github.com/ROCm/aiter/pull/7232) `[Triton/Gluon] [Feature] MHA: add out_dtype to the Triton forward entry point` | infra,rocm | main | - |
| - | [#7233](https://github.com/ROCm/aiter/pull/7233) `[Config] [Perf] Add gfx942 a8w8 blockscale B-preshuffle rows for Qwen3.8-27B` | perf,quant,rocm | main | - |
| - | [#7238](https://github.com/ROCm/aiter/pull/7238) `[FlyDSL] [AITER] FlyDSL a8w8 256x256 nb4/nb2 persistent kernel improvement` | perf,quant,rocm | main | - |
| - | [#7239](https://github.com/ROCm/aiter/pull/7239) `[Triton/Gluon] Pipelining for fused GDN decode kernel, add ba partials reduction` | perf,rocm | main | - |
| - | [#7240](https://github.com/ROCm/aiter/issues/7240) `RFC: Versioned Kernel Provider Interface for AITER` | infra,perf,rocm | ? | - |
| - | [#7242](https://github.com/ROCm/aiter/pull/7242) `[Triton/Gluon] [gfx950] Read DeepSeek-V4.1 KV records in sparse MLA` | rocm | main | - |
| - | [#7243](https://github.com/ROCm/aiter/pull/7243) `[Build] Reuse preshuffle_on ck2stages modules for non-fp4 MoE and add PREBUILD_KERNELS=4` | infra,quant | main | - |
| - | [#7244](https://github.com/ROCm/aiter/pull/7244) `[Triton/Gluon] [Feature] unified_attention: support causal=False for bidirectional draft verify` | rocm | main | - |
| - | [#7245](https://github.com/ROCm/aiter/pull/7245) `[HIP] [Perf] MLA: Run 96-head FP8 decode natively at qlen 7–8 under round-robin CP` | perf,quant,rocm | main | - |
| - | [#7248](https://github.com/ROCm/aiter/pull/7248) `[FlyDSL] [Perf] Avoid empty Tensor construction for omitted MoE operands` | perf,rocm | main | - |
| - | [#7249](https://github.com/ROCm/aiter/pull/7249) `[Triton/Gluon] [Config] Add gfx1151 gemm_a16w4 configs` | quant,rocm | main | - |
| - | [#7251](https://github.com/ROCm/aiter/pull/7251) `[FlyDSL] [Fix] Honor omitted valid-route counts in EP routing` | bug,rocm | main | - |
| - | [#7252](https://github.com/ROCm/aiter/pull/7252) `[FlyDSL] [Perf] Reduce scan barriers in gfx1250 fused TP routing` | perf,rocm | main | - |
| - | [#7254](https://github.com/ROCm/aiter/pull/7254) `[Config] Add MI350P (gfx950, 128 CU) a8w8 blockscale GEMM configs for Gemma-4-31B FP8-block` | quant,rocm | main | - |
| - | [#7255](https://github.com/ROCm/aiter/pull/7255) `[Triton/Gluon] [Config] [gfx950] unified_attention: num_stages 2 for the head-512 fp8 prefill tile` | quant,rocm | main | - |
| - | [#7256](https://github.com/ROCm/aiter/pull/7256) `[Triton/Gluon] [gfx1250] fused_rmsnorm_add: row kernel, gemma_norm, move to fusions` | infra,perf,rocm | main | - |
| - | [#7259](https://github.com/ROCm/aiter/pull/7259) `[Config] [Perf] [gfx950] MiniMax-M3 MoE tuned rows: TP2 a4w4 prefill re-tune, TP8 a16w4 inter 384` | perf,quant,rocm | main | - |
| - | [#7260](https://github.com/ROCm/aiter/pull/7260) `[Triton/Gluon] [Config] Add gfx1150 gemm_a16w4 configs` | quant,rocm | main | - |
| - | [#7261](https://github.com/ROCm/aiter/pull/7261) `[FlyDSL] [Perf] Cache immutable grouped MoE integer config parsing` | perf,rocm | main | - |
| - | [#7262](https://github.com/ROCm/aiter/pull/7262) `[FlyDSL] [Perf] Avoid allocating an unread MoE quantizer placeholder` | perf,quant,rocm | main | - |
| - | [#7263](https://github.com/ROCm/aiter/pull/7263) `[FlyDSL] [Fix] Use legal buffer access widths for vec8 MoE gather-reduce` | bug,rocm | main | - |
| - | [#7264](https://github.com/ROCm/aiter/pull/7264) `[FlyDSL] [JIT] optimize mega moe tp for small token` | perf,rocm | main | - |
| - | [#7266](https://github.com/ROCm/aiter/pull/7266) `[Triton] ep_sort_routing: barrier before the last-CTA ticket (scratch race on gfx1250)` | bug,risk,rocm | main | - |
| - | [#7267](https://github.com/ROCm/aiter/pull/7267) `[Triton/Gluon] [gfx1250] a4w4 MoE configs for Qwen3.5-35B-A3B at EP4` | quant,rocm | main | - |
| - | [#7268](https://github.com/ROCm/aiter/pull/7268) `[Triton] ep_sort_routing: grid size at run time, no compile per prefill shape` | rocm | satya/ep_sort_routing_barrier | - |
| - | [#7269](https://github.com/ROCm/aiter/pull/7269) `[FlyDSL] Generalize gfx1250 BF16 wave query tiles` | rocm | main | - |
| - | [#7270](https://github.com/ROCm/aiter/pull/7270) `[Triton/Gluon] [Config] gfx1151: tune gemm_a8w8_preshuffled configs` | perf,quant,rocm | main | - |
| - | [#7274](https://github.com/ROCm/aiter/pull/7274) `[FlyDSL] [Test] Honor the requested grouped MoE activation format` | rocm | main | - |
| - | [#7275](https://github.com/ROCm/aiter/pull/7275) `[FlyDSL] [Perf] Use wave32 ballots for small persistent expert lookup` | perf,rocm | main | - |
| - | [#7277](https://github.com/ROCm/aiter/pull/7277) `[Triton/Gluon] MHA fp8 prefill: run the fp16 kernel on archs with software-emulated fp8` | perf,quant,rocm | main | - |
| - | [#7278](https://github.com/ROCm/aiter/issues/7278) `[Issue]: Triton MHA prefill attn_fwd (flash_attn_triton_amd) computes q/k/v/out row offsets in int32, which ov` | nvidia,risk,rocm | ? | - |
| - | [#7280](https://github.com/ROCm/aiter/pull/7280) `[Perf] mha: flash_attn_varlen_fp8_pertensor_func writes into a caller's output buffer` | nvidia,perf,quant | main | - |
| - | [#7281](https://github.com/ROCm/aiter/pull/7281) `[Triton/Gluon] Mask OOB e8m0 scales on the ragged-K path of fused_gemm_afp4wfp4_mul_add and split_cat` | perf,quant,rocm | main | - |
| - | [#7282](https://github.com/ROCm/aiter/pull/7282) `[Triton] gfx1150: add gemm_a8w8_preshuffled configs (int8)` | quant,rocm | main | - |
| - | [#7283](https://github.com/ROCm/aiter/pull/7283) `[HIP] [Bugfix] Reject non-contiguous mixes and out in mhc_post` | rocm | main | - |
| - | [#7284](https://github.com/ROCm/aiter/pull/7284) `[FlyDSL] [MoE] Support expert parallel for MXMOE a4w4 GEMM1 with layout-v2 GEMM2` | quant,rocm | main | - |
| - | [#7285](https://github.com/ROCm/aiter/pull/7285) `Validate the timed output in ordinary MXMOE coupled search` |  | main | - |
| - | [#7286](https://github.com/ROCm/aiter/pull/7286) `Fail the MXMOE shape on a fatal GPU error in pruned and full search` |  | main | - |
| - | [#7288](https://github.com/ROCm/aiter/pull/7288) `[Triton/Gluon] [gfx1250] gemm_a16w16: register-store epilogue option and GPT-OSS large-M / TP2 configs` | rocm | main | - |
| - | [#7289](https://github.com/ROCm/aiter/pull/7289) `[Triton/Gluon] [gfx1250] gemm_a16w16: GPT-OSS decode buckets retuned with rotating weights; LM-head files` | perf,rocm | main | - |
| - | [#7291](https://github.com/ROCm/aiter/pull/7291) `[ASM] [gfx1250] asm mha bf16 fwd: allow D64 without a sink` | rocm | main | - |
| - | [#7293](https://github.com/ROCm/aiter/pull/7293) `[Triton] gfx1150: add fused_gemm_a16w16_mul_add config (2.08x vs main)` | perf,rocm | main | - |
| - | [#7295](https://github.com/ROCm/aiter/pull/7295) `[Config] Dev/qwen38 flash moe` |  | main | - |
| - | [#7297](https://github.com/ROCm/aiter/pull/7297) `[FlyDSL] Megamoe Ep Internode Impl` | rocm | main | - |
| - | [#7298](https://github.com/ROCm/aiter/pull/7298) `[Fix] Build DeepSeek RoPE caches on the default device, not hard-coded cuda` | bug,infra,nvidia | main | - |
| - | [#7300](https://github.com/ROCm/aiter/pull/7300) `[Config] feat(minimax-m3.1): add TP4 tuned gfx950 GEMM configs` | perf,rocm | main | - |
| - | [#7301](https://github.com/ROCm/aiter/pull/7301) `[Triton/Gluon] : Add RotatingBufferBench support for sage, hstu, deep, na3d_flash attn` | nvidia,perf,rocm | main | - |
| - | [#7304](https://github.com/ROCm/aiter/pull/7304) `[CI] Rebalance slow op tests across shards` | infra | main | - |
| - | [#7307](https://github.com/ROCm/aiter/pull/7307) `[Triton] Add channel_rmsnorm: RMS norm over dim 1 + activation (Wan VAE norm + SiLU)` | rocm | main | - |
| - | [#7312](https://github.com/ROCm/aiter/pull/7312) `[Triton] Add fused_qk_norm_rope_across_heads: cross-head Q/K RMSNorm + RoPE (Wan)` | perf,rocm | main | - |
| - | [#7319](https://github.com/ROCm/aiter/pull/7319) `[FlyDSL] Support independent output layouts in gfx1250 PA decode` | rocm | main | - |
| - | [#7320](https://github.com/ROCm/aiter/pull/7320) `[Triton] Add conv2d_depthwise with a fused bias, activation or GLU (SANA, Stable Cascade)` | perf,rocm | main | - |
| - | [#7322](https://github.com/ROCm/aiter/pull/7322) `[Build] Ci/test marker classification` | infra | main | - |
| - | [#7324](https://github.com/ROCm/aiter/pull/7324) `gfx1250 gemm2+combine per rank scatter` | rocm | main | - |
| - | [#7325](https://github.com/ROCm/aiter/pull/7325) `[Config] [gfx950] Gemma 4 26B-A4B BF16 fused-MoE tuned configs for MI350P (128 CUs)` | perf,rocm | main | - |
| - | [#7326](https://github.com/ROCm/aiter/pull/7326) `[FlyDSL] QuickAllReduce INT4/INT6: fp32 divisor and adaptive group scales` | infra,quant,rocm | main | - |
| - | [#7327](https://github.com/ROCm/aiter/pull/7327) `[Triton] fused_nhwc_to_nchw_add: channels-last to NCHW plus residual in one pass (gfx1150, gfx1151, gfx1201)` | perf,rocm | main | - |
| - | [#7328](https://github.com/ROCm/aiter/pull/7328) `[Triton/Gluon] [CI] [DO NOT MERGE] bump triton from 7cb7b059 to 65ee8992` | infra,rocm | main | - |
| - | [#7329](https://github.com/ROCm/aiter/pull/7329) `[CI] [DO NOT MERGE] bump triton from 7cb7b059 to 65ee8992` | infra,rocm | main | - |
| - | [#7332](https://github.com/ROCm/aiter/pull/7332) `[FlyDSL] [GFX1250] [MoE] Retune gfx1250 DSv4.1 EP4 a4w4 grouped MoE rows for d…` | perf,quant,rocm | main | - |
| - | [#7333](https://github.com/ROCm/aiter/issues/7333) `[Perf] Gemma 4 26B-A4B BF16 on MI350P: CK MoE stage-2 kernel at ~30% of peak, stalled on memory waits (MoE 1.1` | nvidia,perf | ? | - |
| - | [#7335](https://github.com/ROCm/aiter/pull/7335) `[DRAFT] tune(qwen3.5-397b): FlyDSL rows for the 528-row padded MoE router (re-tune before ready)` | perf,rocm | qichu/qwen35-397b-mxfp4-tuned-configs | - |
| - | [#7337](https://github.com/ROCm/aiter/pull/7337) `[HIP] [Perf] Route large gfx942 MoE sorts to multi-phase` | perf,rocm | main | - |
| - | [#7338](https://github.com/ROCm/aiter/pull/7338) `[Perf] MoE routing top-k: readlane/DPP instead of ds_bpermute` | perf | main | - |
| - | [#7339](https://github.com/ROCm/aiter/pull/7339) `[Triton] Add conv2d_nearest_up2x_3x3: nearest x2 upsample + 3x3 conv without the upsampled tensor (gfx1150, gf` | rocm | main | - |
| - | [#7341](https://github.com/ROCm/aiter/pull/7341) `[CI] Run full test_moe_2stage.py matrix nightly/on-demand` | infra | main | - |
| - | [#7342](https://github.com/ROCm/aiter/pull/7342) `[Triton/Gluon] [CI] [DO NOT MERGE] : Migrating Triton tests and standard tests to mi325 DPX runners` | infra,rocm | main | - |
| - | [#7343](https://github.com/ROCm/aiter/pull/7343) `[FlyDSL] [Perf] fn-resident mHC pre GEMM for gfx950 prefill` | perf,rocm | main | - |
| - | [#7345](https://github.com/ROCm/aiter/pull/7345) `[FlyDSL] perf(mega_moe): gfx1250 decode megakernel - dispatch, GEMM1, GEMM2 and combine in one launch` | perf,rocm | main | - |
| - | [#7346](https://github.com/ROCm/aiter/pull/7346) `[FlyDSL] dist: public SP APIs: PCP graph_capture, head exchange, all_to_all, MegaMoE setup errors` | bug,infra,rocm | main | - |
| - | [#7349](https://github.com/ROCm/aiter/pull/7349) `[FlyDSL] Fix LDS race in MoE sorting p23 kernel` | bug,perf,risk,rocm | main | - |
| - | [#7350](https://github.com/ROCm/aiter/issues/7350) `[Issue]: FlyDSL fused_compress_attn corrupts the first compressed entry of each sequence (negative-history sta` | perf,risk,rocm | ? | - |
| - | [#7351](https://github.com/ROCm/aiter/pull/7351) `[FlyDSL] [Bugfix] Fix first-entry corruption in fused_compress_attn` | bug,perf,risk,rocm | main | - |
| - | [#7352](https://github.com/ROCm/aiter/issues/7352) `[Issue]: FlyDSL MoE sorting p23_kernel reuses cumsum LDS without a barrier (unmasked read/reuse race)` | bug,risk,rocm | ? | - |
| - | [#7353](https://github.com/ROCm/aiter/pull/7353) `[FlyDSL] [Bugfix] Synchronize MoE sorting before reusing cumsum LDS` | rocm | main | - |
| - | [#7354](https://github.com/ROCm/aiter/issues/7354) `[Issue]: FlyDSL MoE sorting shares one cached multiphase workspace across calls, so concurrently replayed grap` | risk,rocm | ? | - |
| - | [#7355](https://github.com/ROCm/aiter/pull/7355) `[FlyDSL] [Bugfix] MoE sorting: allocate the multiphase workspace per call` | rocm | main | - |
| - | [#7360](https://github.com/ROCm/aiter/pull/7360) `[Triton/Gluon] [Perf] [KDA] Optimize the gfx950 FlashKDA prefill for GLM-5.3-Flash` | perf,rocm | main | - |
| - | [#7361](https://github.com/ROCm/aiter/pull/7361) `[HIP] [CK] [Draft][aiter] Clamp FP8 per_Token / per_Tensor SiLU before SiLU at any swiglu_limit` | quant,rocm | main | - |
| - | [#7362](https://github.com/ROCm/aiter/pull/7362) `[Triton/Gluon] (TDM/WMMA) grouped GEMM for gfx1250` | rocm | main | - |
| - | [#7364](https://github.com/ROCm/aiter/pull/7364) `[Triton/Gluon] [gfx1250] Add WG cluster stream-k GEMM `gemm_a16w16_streamk`` | rocm | main | - |
| - | [#7368](https://github.com/ROCm/aiter/pull/7368) `Decouple MoE public names from backends (#7150 batch 1)` |  | main | - |
| - | [#7369](https://github.com/ROCm/aiter/pull/7369) `[Triton/Gluon] [Config] Add gfx1201 RMSNorm large-M/small-N config` | rocm | main | - |
| - | [#7371](https://github.com/ROCm/aiter/pull/7371) `[ASM] [HIP] perf(pa): update gfx950 unified MTP code objects` | perf,rocm | main | - |
| - | [#7372](https://github.com/ROCm/aiter/pull/7372) `[HIP] [FlyDSL] conv3d gfx950: kernel-only timing in tuner and tables, memoize fp32 bias` | perf,rocm | main | - |
| - | [#7374](https://github.com/ROCm/aiter/pull/7374) `[HIP] [JIT] Add gfx950 K-pool indexer cache writers` | perf,rocm | main | - |
| - | [#7377](https://github.com/ROCm/aiter/pull/7377) `Qsa index scorer/stage2` |  | main | - |
| - | [#7378](https://github.com/ROCm/aiter/pull/7378) `[Triton] [Config] Add gfx1201 gemm_a16w16 config` | rocm | main | - |
| - | [#7380](https://github.com/ROCm/aiter/pull/7380) `[Triton] gfx950 unified attention: do not specialize on num_seqs (+ reduce_segments)` | rocm | main | - |
| - | [#7381](https://github.com/ROCm/aiter/pull/7381) `[Config] [Tune] GLM-5.3 a8w8 blockscale GEMM rows for gfx950` | perf,quant,rocm | main | - |
| - | [#7382](https://github.com/ROCm/aiter/pull/7382) `[Triton] [Config] Add gfx1201 gemm_a16w16_gated config` | rocm | main | - |
| - | [#7385](https://github.com/ROCm/aiter/pull/7385) `[CI] ci: cache CK submodule checkout` | infra,perf | main | - |
| - | [#7386](https://github.com/ROCm/aiter/pull/7386) `[Bugfix] Allow gfx942 FlyDSL a16w4 and a16wi4 MoE tuning` | perf,quant,rocm | main | - |
| - | [#7387](https://github.com/ROCm/aiter/pull/7387) `[HIP] [OPUS] Add OPUS GEMM BlockScale_Mxfp8 GEMM for M <=1024 Shape.` | quant,rocm | main | - |
| - | [#7388](https://github.com/ROCm/aiter/pull/7388) `[FlyDSL] [Misc] pa_decode: key the tile kernel on FlyDSL dtypes and drop the batch-first plan grid` | perf,rocm | main | - |
| - | [#7389](https://github.com/ROCm/aiter/pull/7389) `[Config] [Perf] Tune DeepSeek V4.1 EP16 A4W4 for routed and shared experts` | perf,quant | main | - |
| - | [#7391](https://github.com/ROCm/aiter/pull/7391) ` [Triton/Gluon] gfx950 a16w16: Stream-K for compute-bound shapes (draft)` | rocm | llirSched_integration | - |
| - | [#7393](https://github.com/ROCm/aiter/issues/7393) `[MLA] gfx942 persistent a8w8 decode returns output / kv_scale at q_len 3 and 4` | quant,rocm | ? | - |
| - | [#7394](https://github.com/ROCm/aiter/pull/7394) `MHAv4 gfx942 parity ` | rocm | main | - |
| - | [#7396](https://github.com/ROCm/aiter/pull/7396) `[HIP][Triton/Gluon] gfx1250 decode all-reduce + RMSNorm (+ FP8 quant) in one kernel` | perf,quant,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7399](https://github.com/ROCm/aiter/pull/7399) `[ASM] [HIP] gfx942 mha bwd: hd192 / hd192_128 pssk kernels (fp16 / bf16, batch / varlen), 64-bit odo addressin` | perf,rocm | main | - |
| - | [#7401](https://github.com/ROCm/aiter/pull/7401) `feat(flydsl): fuse sparse PA output quantization` | perf,quant,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7403](https://github.com/ROCm/aiter/pull/7403) `[Triton/Gluon] [gfx1250] Add a16w16 MoE GEMM` | rocm | main | - |
| - | [#7406](https://github.com/ROCm/aiter/pull/7406) `[Triton/Gluon] Step-5 CSA paged MQA logits kernel for gfx942` | infra,perf,rocm | main | - |
| - | [#7407](https://github.com/ROCm/aiter/pull/7407) `[ASM] [HIP] [CI] Add gfx1250 MLA v4.1 a8w4 fused sparse prefill kernel` | infra,perf,rocm | main | - |
| - | [#7408](https://github.com/ROCm/aiter/pull/7408) `[WIP] perf(gfx1250): integrate MiniMax-M3 fusion stack` | perf,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7409](https://github.com/ROCm/aiter/pull/7409) `[FlyDSL] gfx942 a16wi4: faster int4 MoE dequant via v_perm_b32` | perf,quant,rocm | main | - |
| - | [#7410](https://github.com/ROCm/aiter/pull/7410) `[FlyDSL] perf: integrate APRE M256 kernels into gfx1250 MegaMoE S1F` | perf,rocm | main | - |
| - | [#7412](https://github.com/ROCm/aiter/pull/7412) `[FlyDSL] FP8 MQA logits improvements for gfx950` | quant,rocm | main | - |
| - | [#7413](https://github.com/ROCm/aiter/pull/7413) `[Triton/Gluon] [Feature] FlashKDA: store the recurrent state at interior chunk boundaries` | rocm | main | - |
| - | [#7414](https://github.com/ROCm/aiter/pull/7414) `[Config] [Tuning][gfx950] Retune MiniMax-M3.1 TP4 A16W4 decode rows (E=128, top-4) for 8/16/32/64/128 tokens` | perf,quant,rocm | main | - |
| - | [#7415](https://github.com/ROCm/aiter/pull/7415) `[HIP] [OPUS] [JIT] [MLA] gfx950 fp8 flat-row MTP decode: host planner, stage 1 and bf16 merge` | quant,rocm | main | - |
| - | [#7416](https://github.com/ROCm/aiter/pull/7416) `[Triton/Gluon] [Kernel] Add fused_mixed_sample: tiled exponential-race sampling with greedy override` | bug,infra,perf,risk,rocm | main | - |
| - | [#7417](https://github.com/ROCm/aiter/pull/7417) `[Triton/Gluon] fixed a moe bug related to swiglu on gfx1250` | rocm | main | - |
| - | [#7419](https://github.com/ROCm/aiter/pull/7419) `[FlyDSL] [gfx1250] Fix a K-split race in the fused EP psum-quant kernel, and enable the fusion off the grouped` | bug,perf,quant,risk,rocm | main | - |
| - | [#7420](https://github.com/ROCm/aiter/pull/7420) `[gfx1250] Qwen3.5-35B-A3B DP: retuned Gluon a16w16 configs + bf16 GEMM CSV` | perf,rocm | main | - |
| - | [#7421](https://github.com/ROCm/aiter/pull/7421) `[Triton/Gluon] [GFX12] A8K4V8 Attention` | rocm | main | - |
| - | [#7422](https://github.com/ROCm/aiter/pull/7422) `[FlyDSL] Add opt-in geometry-only PA decode partition preparation` | rocm | main | - |
| - | [#7423](https://github.com/ROCm/aiter/pull/7423) `[FlyDSL] [PA] Avoid unused arrival counters and direct-output scratch` | rocm | main | - |
| - | [#7425](https://github.com/ROCm/aiter/pull/7425) `[Triton/Gluon] [Config] Add gfx950 preshuffled AFP4WFP4 GEMM configs for Qwen3.8-27B MXFP4 on MI350P` | quant,rocm | main | - |
| - | [#7427](https://github.com/ROCm/aiter/pull/7427) `[HIP] [Perf] Tune large-row BF16-to-FP8 quant on gfx1250` | perf,quant,rocm | main | - |
| - | [#7430](https://github.com/ROCm/aiter/pull/7430) `[HIP] [FlyDSL] [Feature] [Perf] DeepSeek V4.1: MXFP8 dual RMSNorm with fused KV RoPE quant, and FlyDSL rope_qu` | perf,quant,rocm | main | - |
| - | [#7431](https://github.com/ROCm/aiter/pull/7431) `[FlyDSL][gfx1250] Optimize grouped MXFP4 native prefill GEMM scheduling` | perf,quant,rocm | main | - |
| - | [#7432](https://github.com/ROCm/aiter/pull/7432) `[HIP] perf(custom_ar): gfx1250 LL two-shot all-reduce for 1 MiB+ messages` | perf,rocm | main | - |
| - | [#7436](https://github.com/ROCm/aiter/pull/7436) `[HIP] [FlyDSL] SwiGLU-step activation and exact FP8 block scales in gfx942 MoE` | quant,rocm | main | - |
| - | [#7444](https://github.com/ROCm/aiter/pull/7444) `[FlyDSL] QuickAllReduceInt4: reduce-scatter and all-gather modes for sequence parallelism` | rocm | main | - |
| - | [#7445](https://github.com/ROCm/aiter/pull/7445) `perf(custom-ar): drop the gfx1250 fused AR final barrier` | perf,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7447](https://github.com/ROCm/aiter/pull/7447) `[FlyDSL] Generalize gfx1250 FP8 PA to two and three query tiles` | quant,rocm | main | - |
| - | [#7448](https://github.com/ROCm/aiter/pull/7448) `[Triton/Gluon] [Config] [gfx950] unified_attention: bf16 head-512 large-prefill tile (Gemma-4 global layers)` | rocm | main | - |
| - | [#7449](https://github.com/ROCm/aiter/pull/7449) `[Perf] Let the consumer finish a gfx1250 PTPC split-K GEMM` | perf,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7453](https://github.com/ROCm/aiter/pull/7453) `[CK] [MoE] Build the a16w16 CK 2-stage MoE instances without scale code` | infra,quant | main | - |
| - | [#7454](https://github.com/ROCm/aiter/pull/7454) `[Triton/Gluon] Allow pa_decode_gluon query length 8` | rocm | main | - |
| - | [#7455](https://github.com/ROCm/aiter/pull/7455) `[Triton/Gluon] Sparse attention block mask to LUT optimization` | infra,perf,rocm | main | - |
| - | [#7456](https://github.com/ROCm/aiter/pull/7456) `[Config] gfx1250: grouped-MoE tiles for Kimi-K2 Thinking TP8` | rocm | main | - |
| - | [#7457](https://github.com/ROCm/aiter/pull/7457) `[Config] Add gfx950 BF16 GEMM tunings for Gemma-4-26B-A4B` | perf,rocm | main | - |
| - | [#7458](https://github.com/ROCm/aiter/pull/7458) `[Triton/Gluon] Add RoPE and KV-cache write to the fused bf16 BMM MLA decode kernel` | perf,rocm | main | - |
| - | [#7461](https://github.com/ROCm/aiter/pull/7461) `[Triton/Gluon] gfx942 MXFP4-KV sparse paged-attention decode` | quant,rocm | main | - |
| - | [#7462](https://github.com/ROCm/aiter/pull/7462) `[ASM] [HIP] Optimize gfx950 MXFP6 GEMMs for Ideogram DiT shapes` | perf,quant,rocm | main | - |
| - | [#7463](https://github.com/ROCm/aiter/pull/7463) `[HIP] Split MXFP6 GEMM launches whose output exceeds 2 GiB` | quant,rocm | main | - |
| - | [#7465](https://github.com/ROCm/aiter/pull/7465) `[RFC #7240] Kernel provider interface: configuration, priority, provenance, observability` | perf | main | - |
| - | [#7466](https://github.com/ROCm/aiter/pull/7466) `[CI] Run the provider interface tests as a CPU-only gate on every PR` | infra | main | - |
| - | [#7467](https://github.com/ROCm/aiter/pull/7467) `[Triton/Gluon] [Config] gfx1151 batched_gemm_a16w16: B-specific configs for the #6986 kernel (stacked on #6986` | perf,rocm | main | - |
| - | [#7469](https://github.com/ROCm/aiter/pull/7469) `[FlyDSL] PCIe-optimized Ulysses all-to-all` | infra,perf,rocm | main | - |
| - | [#7470](https://github.com/ROCm/aiter/pull/7470) `[Triton/Gluon] [Perf] Add optional gfx942 small-M MoE sorter` | infra,perf,rocm | main | - |
| - | [#7471](https://github.com/ROCm/aiter/pull/7471) `[Triton] fp8_mqa_logits: add a deterministic option` | rocm | main | - |
| - | [#7473](https://github.com/ROCm/aiter/pull/7473) `[MHA] Stop flash_attn_varlen_func from dropping sequences with seqlen_q <= min_seqlen_q` | infra,nvidia,rocm | main | - |
| - | [#7474](https://github.com/ROCm/aiter/pull/7474) `[MHA] Fix flash_attn_varlen_func with block_table (paged KV)` | bug,infra,nvidia,rocm | main | - |
| - | [#7476](https://github.com/ROCm/aiter/pull/7476) `[Triton/Gluon] [Perf] Tune MLA decode launch configuration for BF16 KV on gfx1201` | perf,rocm | main | - |
| - | [#7478](https://github.com/ROCm/aiter/pull/7478) `[Config] Add Gemma-4-E4B bf16 GEMM configs for gfx950 (MI350P, 128 CUs)` | rocm | main | - |
| - | [#7479](https://github.com/ROCm/aiter/pull/7479) `[Config] [Perf] Retune Llama-3.1-405B BF16 GEMM config for gfx950` | perf,rocm | main | - |
| - | [#7480](https://github.com/ROCm/aiter/pull/7480) `[HIP] [Tuner] Sample package power by CUDA graph replay` | nvidia,perf,rocm | main | - |
| - | [#7481](https://github.com/ROCm/aiter/pull/7481) `[Config] [MoE] Kimi-K3 A8W4: retune the token 8/16 decode rows for DFlash verify batches` | perf | main | - |
| - | [#7484](https://github.com/ROCm/aiter/pull/7484) `[JIT] Route three ops through the provider interface, and let a compiled op report its signature` |  | main | - |
| - | [#7486](https://github.com/ROCm/aiter/pull/7486) `[FlyDSL] [MoE] a16wmix gemm2 reduce epilog: skip sort pad sentinels (slot == topk)` | rocm | main | - |
| - | [#7488](https://github.com/ROCm/aiter/pull/7488) `[Triton/Gluon] [Perf] gfx1250 all-reduce: fold a residual add into the reduce` | perf,rocm | main | - |
| - | [#7489](https://github.com/ROCm/aiter/pull/7489) `[Triton/Gluon] fused_clamp_act_mul: accept rows of whole quant groups` | perf,quant,rocm | main | - |
| - | [#7492](https://github.com/ROCm/aiter/pull/7492) `[Triton] [Config] gfx1201 gemm_a16w16: shape-specific configs (stacked on #7378)` | rocm | main | - |
| - | [#7493](https://github.com/ROCm/aiter/pull/7493) `[Tuner] Raise a GPU fault from the power-sampling pass` | perf | main | - |
| - | [#7496](https://github.com/ROCm/aiter/pull/7496) `[FlyDSL] EP intranode dispatch: skip negative / out-of-range expert ids` | rocm | main | - |
| - | [#7497](https://github.com/ROCm/aiter/pull/7497) `[FlyDSL] [MoE] Intra-node EP dispatch/combine without the mori runtime: HIP IPC symmetric buffers, token-major` | rocm | main | - |
| - | [#7499](https://github.com/ROCm/aiter/pull/7499) `[HIP] fea: impl gfx1250 lamport ar+rms` | rocm | main | - |
| - | [#7500](https://github.com/ROCm/aiter/pull/7500) `[FlyDSL] [MoE] Support row-strided MXFP4 activations` | quant,rocm | main | - |
| - | [#7501](https://github.com/ROCm/aiter/pull/7501) `[FlyDSL] [MoE] [gfx1250] give each MX combine chunk its own scale line` | quant,rocm | main | - |
| - | [#7502](https://github.com/ROCm/aiter/pull/7502) `[Triton] [Config] Add gfx1201 batched_gemm_a16w16 configs` | rocm | main | - |
| - | [#7503](https://github.com/ROCm/aiter/pull/7503) `[HIP] [FlyDSL] Conv3d gfx1250 Optimization` | perf,rocm | main | - |
| - | [#7504](https://github.com/ROCm/aiter/issues/7504) `[FlyDSL] moe_reduce: masked reduction does not bound-check topk_ids against expert_mask size` | rocm | ? | - |
| - | [#7506](https://github.com/ROCm/aiter/pull/7506) `[Triton/Gluon] gfx950 fp8 varlen MHA forward for MLA prefill` | quant,rocm | main | - |
| - | [#7508](https://github.com/ROCm/aiter/pull/7508) `[CI] [DO NOT MERGE] [TEST] Try amd runtime on AITER toolkit runner` | infra,rocm | main | - |
| - | [#7509](https://github.com/ROCm/aiter/pull/7509) `[OPUS] [Bugfix] Fix LDS race in gfx942 A8W8 blockscale B-preshuffle GEMM` | bug,quant,risk,rocm | main | - |
| - | [#7510](https://github.com/ROCm/aiter/pull/7510) `[Triton/Gluon] [gfx942] Read the fp8_dsv32_mla cache in fnuz on gfx942` | infra,perf,rocm | main | - |
| - | [#7511](https://github.com/ROCm/aiter/pull/7511) `[Triton] [Config] Add gfx1201 fused_sigmoid_mul config` | perf,rocm | main | - |
| - | [#7512](https://github.com/ROCm/aiter/issues/7512) `gfx1250 Gluon unified attention 2D: LDS-staged TDM store writes a stale output tile on decode` | bug,rocm | ? | - |
| - | [#7513](https://github.com/ROCm/aiter/pull/7513) `[Triton/Gluon] [Config] gfx950: tune gemm_a16w16 for kimik3/glm5/qwen3.5 model shapes` | perf,rocm | main | - |
| - | [#7514](https://github.com/ROCm/aiter/pull/7514) `[OPUS] Tune gfx1250 a16w16 GEMMs for Kimi K2 on 96 CUs` | perf,rocm | main | - |
| - | [#7515](https://github.com/ROCm/aiter/pull/7515) `[Config] [Tuning] Add Kimi-K3 gfx950 BF16 decode rows for qkv_a+gate a…` | perf,rocm | main | - |
| - | [#7516](https://github.com/ROCm/aiter/pull/7516) `[Triton/Gluon] [Config] Add gfx942 FP8 head-dim-256 MHA config` | quant,rocm | main | - |
| - | [#7517](https://github.com/ROCm/aiter/pull/7517) `[Triton/Gluon] fp8_mqa_logits: optional caller-owned logits buffer` | rocm | main | - |
| - | [#7518](https://github.com/ROCm/aiter/pull/7518) `[Triton/Gluon] Cast strides to int64 in MHA prefill attn_fwd to prevent overflow` | risk,rocm | main | - |
| - | [#7519](https://github.com/ROCm/aiter/issues/7519) `[Issue]: two-stage DSv4 compressor ignores overlap and writes a wrong KV cache for cr=4 layers` | perf | ? | - |
| - | [#7520](https://github.com/ROCm/aiter/issues/7520) `[Issue]: two-stage DSv4 compressor does not validate compress_scratch (wrong dtype silently changes results, s` | bug,risk | ? | - |
| - | [#7521](https://github.com/ROCm/aiter/issues/7521) `[Issue]: use_fp4_cache is accepted but ignored; the launcher always writes FP8 records` | quant | ? | - |
| - | [#7522](https://github.com/ROCm/aiter/pull/7522) `[Triton/Gluon] Honor overlap in the two-stage DeepSeek-V4 compressor` | perf,rocm | main | - |
| - | [#7523](https://github.com/ROCm/aiter/pull/7523) `[Triton/Gluon] Validate the two-stage DeepSeek-V4 compressor scratch buffer` | rocm | main | - |
| - | [#7524](https://github.com/ROCm/aiter/pull/7524) `[Triton/Gluon] Reject use_fp4_cache in the DeepSeek-V4 compressor` | rocm | main | - |
| - | [#7525](https://github.com/ROCm/aiter/pull/7525) `validate-kernel-pr: read the identity gate after fetch.sh's stderr redirect` | perf | main | - |
| - | [#7526](https://github.com/ROCm/aiter/pull/7526) `[OPUS] [Build] Extract C++ code in generators to jinja template files` | infra | main | - |
| - | [#7527](https://github.com/ROCm/aiter/issues/7527) `[Issue]: aiter.ops.triton.quant cannot be imported on a GPU-less host (get_arch re-raises the probe error)` | quant,rocm | ? | - |
| - | [#7528](https://github.com/ROCm/aiter/pull/7528) `[Triton/Gluon] Keep a failed arch probe from breaking GPU-less imports` | rocm | main | - |
| - | [#7529](https://github.com/ROCm/aiter/pull/7529) `[FlyDSL] [CI] Add a fused Kimi-K3 KDA target-verify kernel on gfx942 and gfx950` | infra,perf,rocm | main | - |
| - | [#7530](https://github.com/ROCm/aiter/pull/7530) `[Triton/Gluon] [Kernel] Add a Triton fallback for paged_mxfp4_mqa_logits on archs without the Gluon kernel` | perf,quant,rocm | main | - |
| - | [#7531](https://github.com/ROCm/aiter/pull/7531) `[FlyDSL] [gfx1250] mega_moe S1F: snap decode steps to a stage-1 tile (opt-in, AITER_S1F_SNAP_ALIGN)` | rocm | main | - |
| - | [#7532](https://github.com/ROCm/aiter/pull/7532) `[Triton/Gluon] [Hardware] Enable gemm_a16wfp4 and gemm_a8wfp4 on software-emulated FP4 (gfx1101)` | quant,rocm | main | - |
| - | [#7533](https://github.com/ROCm/aiter/pull/7533) `[Triton/Gluon] [Hardware] Enable batched and fused FP4 GEMMs on software-emulated FP4 (gfx1101)` | perf,quant,rocm | main | - |
| - | [#7534](https://github.com/ROCm/aiter/issues/7534) `[Issue]: module_moe_sorting_opus does not build for gfx1250 (DPP row_bcast in dpp_inclusive_scan_wave)` | infra,rocm | ? | - |
| - | [#7536](https://github.com/ROCm/aiter/issues/7536) `[Issue]: grouped MoE GEMM tests require an AOT entry for moe_fused_route_quant_scatter that run_aot does not b` | infra,perf,quant | ? | - |
| - | [#7537](https://github.com/ROCm/aiter/pull/7537) `[FlyDSL] FP4 row-group MQA logits: opt-in |s| epilogue and 16-key tile maxima` | quant,rocm | main | - |
| - | [#7538](https://github.com/ROCm/aiter/pull/7538) `[JIT] feat(mxfp4): own per-model A4W4 GEMM configs behind a public API` | quant | main | - |
| - | [#7539](https://github.com/ROCm/aiter/pull/7539) `[Triton] [Gluon] Clamp gfx950 unified attention block-table prefetch in all modes` | rocm | main | - |
| - | [#7540](https://github.com/ROCm/aiter/pull/7540) `[HIP] Fix/7534 moe sorting opus gfx1250` | bug,rocm | main | - |
| - | [#7542](https://github.com/ROCm/aiter/pull/7542) `[CK] [FlyDSL] Dev/ms ep32 support` | rocm | main | - |
| - | [#7543](https://github.com/ROCm/aiter/pull/7543) `perf(flydsl): fold the gfx1250 TP MoE route into the activation quant` | perf,quant,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7544](https://github.com/ROCm/aiter/pull/7544) `[Triton/Gluon] Pipeline scale loads and use explicit FMA in fused_gemm_a8w8_blockscale_a16w16` | perf,quant,rocm | main | - |
| - | [#7545](https://github.com/ROCm/aiter/pull/7545) `[FlyDSL] Optimize gfx1250 MiniMax-M3 paged attention and planning` | perf,rocm | main | - |
| - | [#7546](https://github.com/ROCm/aiter/pull/7546) `[HIP] [FlyDSL] [CI] Add tunable HGEMM K-stagger and B streaming loads` | infra,rocm | main | - |
| - | [#7547](https://github.com/ROCm/aiter/pull/7547) `perf(flydsl): route the gfx1250 TP prefill MoE in one launch` | perf,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7548](https://github.com/ROCm/aiter/pull/7548) `[HIP] [FlyDSL] Port gfx1250 TDM HGEMM and source tuning space` | perf,rocm | main | - |
| - | [#7549](https://github.com/ROCm/aiter/pull/7549) `perf(mha): pack the gfx1250 varlen ASM LSE only when it is returned` | perf,rocm | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#7550](https://github.com/ROCm/aiter/pull/7550) `[FlyDSL] fused_compress_attn: zero padding kv in Phase 1` | perf,rocm | main | - |
| - | [#7552](https://github.com/ROCm/aiter/pull/7552) `[HIP] getPaddedM: fall back to the M=16 row for M<16 when no power-of-two row is tuned` | perf,rocm | main | - |
| - | [#7553](https://github.com/ROCm/aiter/pull/7553) `Jruan/gfx1250 fdsl fmha paged` | rocm | main | - |
| - | [#7554](https://github.com/ROCm/aiter/pull/7554) `[Triton/Gluon] [Bugfix] gemm_afp4wfp4: mask K-tail scales with 0, not 127` | quant,rocm | main | - |
| - | [#7555](https://github.com/ROCm/aiter/pull/7555) `[HIP] perf: gfx1250 LL all-gather lines carry 12 bytes and one flag` | perf,rocm | main | - |
| - | [#7556](https://github.com/ROCm/aiter/pull/7556) `[FlyDSL][QSA] Sparse prefill attention on gfx950: union and packed-direct ports, strided K/V, routing` | rocm | main | - |
| - | [#7558](https://github.com/ROCm/aiter/pull/7558) `[fused_moe] Keep Swiglu MXFP4 A4W4 off a numerically-broken shape` | perf,quant | main | - |
| - | [#7559](https://github.com/ROCm/aiter/pull/7559) `[ASM] [HIP] [gfx1250] asm mha bf16 hd256: batch and varlen forward` | rocm | main | - |
| - | [#7560](https://github.com/ROCm/aiter/pull/7560) `[CI] Add area contacts and review guide; document merge rules and review timeline` | infra | main | - |
| - | [#7561](https://github.com/ROCm/aiter/pull/7561) `[FlyDSL] [AOT] Fix mm out_dtype replay on torch 2.9.1` | bug,rocm | main | - |
| - | [#7563](https://github.com/ROCm/aiter/pull/7563) `review-pr: route the design judgment instead of making it (Step 7.8)` |  | main | - |
| - | [#7564](https://github.com/ROCm/aiter/pull/7564) `[Triton/Gluon] gfx950: add opt-in ping-pong Gluon kernel for MXFP4 GEMM` | perf,quant,rocm | main | - |
| - | [#7565](https://github.com/ROCm/aiter/pull/7565) `[MOE] Rotate the SwiGLU output between the two GEMMs` |  | main | - |
| - | [#7566](https://github.com/ROCm/aiter/pull/7566) `[Triton][gfx950] Split-KV for sliding-window decode; 128-key tile for shuffled full attention` | rocm | main | - |
| - | [#7567](https://github.com/ROCm/aiter/pull/7567) `[FlyDSL] [Bugfix] Fix MoE XCD swizzle on grids not divisible by 8` | bug,rocm | main | - |
| - | [#7568](https://github.com/ROCm/aiter/pull/7568) `[CI] Install the amd-mori 1.2.5 release for the multi-GPU tests` | infra,rocm | main | - |
| - | [#7569](https://github.com/ROCm/aiter/pull/7569) `[HIP] [MLA] Saturate the fp8 rope output of fused_qk_rope_concat_and_cache_mla` | perf,quant,rocm | main | - |
| - | [#7570](https://github.com/ROCm/aiter/pull/7570) `[HIP] [MLA] Add a wide split-K reduce for decode and verify with few units and many splits` | rocm | main | - |
| - | [#7571](https://github.com/ROCm/aiter/pull/7571) `[Docs] Update ruff version in contribution guidelines to match CI` | infra | main | - |
| - | [#7572](https://github.com/ROCm/aiter/pull/7572) `[FlyDSL] [MoE] comm-fused MoE: launch clear_missing_routes over the whole route scratch` | perf,rocm | main | - |
| - | [#7573](https://github.com/ROCm/aiter/pull/7573) `[HIP] gfx1250 Mega-MHC: XCD-local and clustered split tiles, sublayer TDM, res_preshuffle helpers` | rocm | main | - |
| - | [#7574](https://github.com/ROCm/aiter/pull/7574) `[ASM] Fix LDS race between V reads and R re-layout in gfx950 BF16 QH3…` | bug,risk,rocm | main | - |
| - | [#7575](https://github.com/ROCm/aiter/pull/7575) `Add FlyDSL V4.1 CSA main compressor` | rocm | main | - |
| - | [#7576](https://github.com/ROCm/aiter/pull/7576) `[HIP] [Bugfix] sample: Map exponential's top uniform bucket to a positive sample` | rocm | main | - |
| - | [#7577](https://github.com/ROCm/aiter/pull/7577) `[Triton] [Config] Add gfx1201 gemm_a16w4 configs` | quant,rocm | main | - |
| - | [#7578](https://github.com/ROCm/aiter/pull/7578) `[FlyDSL] Speed up paged-attention decode on gfx950` | perf,rocm | main | - |
| - | [#7579](https://github.com/ROCm/aiter/pull/7579) `[FlyDSL] gfx1250 PA decode: wider softmax steps and leaner prologue for MiniMax-M3 shapes` | rocm | main | - |
| - | [#7580](https://github.com/ROCm/aiter/pull/7580) `[Tune] GLM-5 MQA logits: retune with clean_logits=False, add GLM-5.3-Flash rows` | perf | main | - |
| - | [#7581](https://github.com/ROCm/aiter/pull/7581) `[Config] [Perf] Retune DeepSeek-V4.1-Flash EP4 MXFP4 (a4w4) fused-MoE rows for gfx950` | perf,quant,rocm | main | - |
| - | [#7582](https://github.com/ROCm/aiter/pull/7582) `[Config] [Perf] Add DeepSeek-V4.1-Flash EP8 MXFP4 (a4w4) fused-MoE rows for gfx950` | perf,quant,rocm | main | - |

### vLLM — Merged / closed (794 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#23943](https://github.com/vllm-project/vllm/issues/23943) `[Feature]: Any plans to add nvidia/parakeet-tdt-0.6b-v3 to vllm?` | nvidia | ? | - |
| - | [#30075](https://github.com/vllm-project/vllm/issues/30075) `[Feature]: Default eplb num_redundant_experts to the lowest valid value if unspecified` |  | ? | - |
| - | [#30614](https://github.com/vllm-project/vllm/pull/30614) `[Feature] Default EPLB num_redundant_experts to minimum valid value` |  | main | - |
| - | [#31856](https://github.com/vllm-project/vllm/issues/31856) `[Bug]: Text degeneration / repetition loops with MiniMax-M2.1-NVFP4 on v0.14.0rc1.dev308` | quant | ? | - |
| - | [#35508](https://github.com/vllm-project/vllm/pull/35508) `[Responses] Normalize OpenResponses input items to match openai-python SDK requirements` | infra | main | - |
| - | [#36821](https://github.com/vllm-project/vllm/issues/36821) `[Bug]: No sm_121 (Blackwell) support on aarch64 — NVIDIA DGX Spark / Acer GN100` | bug,nvidia | ? | - |
| - | [#37162](https://github.com/vllm-project/vllm/issues/37162) `[Feature] Fuse per-group FP8 dynamic quant onto Triton attention kernel` | perf,quant,rocm | ? | - |
| - | [#37185](https://github.com/vllm-project/vllm/issues/37185) `[Bug]: The 2-bit model repeatedly outputs !!!!, while Transformers works correctly.` | bug | ? | - |
| - | [#37261](https://github.com/vllm-project/vllm/issues/37261) `[Bug]: KeyError when use lmcache layerwise mode in vllm 0.14.0` | bug | ? | - |
| - | [#38991](https://github.com/vllm-project/vllm/issues/38991) `[Bug]: runai_safetensors_weights_iterator yields tensors in nondeterministic order, breaking FP8 inference on ` | quant | ? | - |
| - | [#39479](https://github.com/vllm-project/vllm/issues/39479) `[torch.compile] config hashing refactor follow-ups` |  | ? | - |
| - | [#41469](https://github.com/vllm-project/vllm/issues/41469) `[Bug]: AttributeError: '_C' object has no attribute 'awq_dequantize' on Intel Arc B580 XPU (AWQ inference fail` | bug,nvidia,quant | ? | - |
| - | [#41565](https://github.com/vllm-project/vllm/issues/41565) `[Bug]: TurboQuant _continuation_prefill workspace allocation fails at long context — v0.20.0 regression` | bug,quant | ? | - |
| - | [#42286](https://github.com/vllm-project/vllm/issues/42286) `[New Model]: ZAYA1-8B` |  | ? | - |
| - | [#42837](https://github.com/vllm-project/vllm/pull/42837) `[feature] shuffle safetensor weight files` |  | main | - |
| - | [#43090](https://github.com/vllm-project/vllm/issues/43090) `[CI Failure]: Language Models Tests (Hybrid) 1 - granite-4.0-tiny-preview prefix caching regression` | bug,infra | ? | - |
| - | [#43750](https://github.com/vllm-project/vllm/issues/43750) `[Bug]: [XPU] compressed-tensors WNA16 MoE selector ignores XPU platform, crashes on Marlin path` | bug,nvidia,quant | ? | - |
| - | [#44245](https://github.com/vllm-project/vllm/issues/44245) `fix(lora): _load_lora_config retry uses deterministic backoff without jitter — thundering herd risk` | bug | ? | - |
| - | [#44734](https://github.com/vllm-project/vllm/issues/44734) `CUDA device-side assert with nvidia/Qwen3.6-35B-A3B-NVFP4 + MTP on nightly f91fb2f` | nvidia,quant | ? | - |
| - | [#45154](https://github.com/vllm-project/vllm/issues/45154) `[Rust Frontend][RFC]: Elastic Expert Parallel support` |  | ? | - |
| - | [#45531](https://github.com/vllm-project/vllm/issues/45531) `[Bug]: minimax M3MXFP8 with mtp can not start success` | bug,quant | ? | - |
| - | [#45661](https://github.com/vllm-project/vllm/issues/45661) `[Bug]: NotImplementedError: No NvFp4 MoE backend supports the deployment configuration.` | bug,quant | ? | - |
| - | [#46311](https://github.com/vllm-project/vllm/issues/46311) `[Bug]: INCConfig doesn't support hybrid INT4+FP8 AutoRound checkpoints — weight_scale_inv params not loaded, m` | quant,risk | ? | - |
| - | [#46328](https://github.com/vllm-project/vllm/issues/46328) `[Bug]: glm-5-fp8 zcode str object has no attribute items` | bug,quant | ? | - |
| - | [#46335](https://github.com/vllm-project/vllm/pull/46335) `[Doc] Fix %% rendering in CLI reference for --safetensors-load-strategy` | bug | main | - |
| - | [#46358](https://github.com/vllm-project/vllm/issues/46358) `[RFC]: Unify Context Parallelism in vLLM (PCP ⊥ DCP)` |  | ? | - |
| - | [#46370](https://github.com/vllm-project/vllm/pull/46370) `[Feature] Initial support for fault tolerant ep using scale-down` | infra,quant | main | - |
| - | [#46625](https://github.com/vllm-project/vllm/issues/46625) `Qwen3-VL-8B-FP8 on RTX 5080 (Blackwell SM120) - engine init OK but generate() hangs silently` | bug,nvidia,quant,risk | ? | - |
| - | [#46679](https://github.com/vllm-project/vllm/issues/46679) `[Bug]: GLM5.2 RuntimeError: The expanded size of the tensor (10210) must match the existing size (16384) at no` | bug | ? | - |
| - | [#46707](https://github.com/vllm-project/vllm/issues/46707) `[RFC]: Support for Domino speculative decoding in vLLM` |  | ? | - |
| - | [#46715](https://github.com/vllm-project/vllm/issues/46715) `[Bug]: When the startup parameter "--max-model-len  auto --enable-chunked-prefill -- enable-prefix-caching --m` | bug,infra,quant | ? | - |
| - | [#46726](https://github.com/vllm-project/vllm/issues/46726) `[Bug]: sparse-MLA indexer error with  GLM 5.2 NVFP4 on RTX 6000 Pro SM120` | bug,nvidia,quant | ? | - |
| - | [#46743](https://github.com/vllm-project/vllm/issues/46743) `[Feature]: migrate NVSHMEM patches for RoCE from llm-d to vllm image` |  | ? | - |
| - | [#47020](https://github.com/vllm-project/vllm/issues/47020) `Backport workflow-hardening fix (excessive-permissions) to 5 release branches` | bug,infra | ? | - |
| - | [#47022](https://github.com/vllm-project/vllm/issues/47022) `[New Model]: Couqi XTTS_v2 multilanguage text-to-speech` |  | ? | - |
| - | [#47026](https://github.com/vllm-project/vllm/issues/47026) `[Bug]: Gemma4ForConditionalGeneration + runtime LoRA greedy decode diverges from HuggingFace transformers on t` | bug | ? | - |
| - | [#47047](https://github.com/vllm-project/vllm/issues/47047) `Gemma-4-26B-A4B-NVFP4 + MTP4 is slower on v0.23.0 than v0.21.0 on RTX PRO 6000 Blackwell` | nvidia,perf,quant | ? | - |
| - | [#47051](https://github.com/vllm-project/vllm/issues/47051) `[Bug]:  GPT-OSS models silently ignore unsupported content types (input_file, etc.)` | bug,risk | ? | - |
| - | [#47069](https://github.com/vllm-project/vllm/issues/47069) `[Bug]: Concurrent temperature=0 non-determinism in vLLM, FLASH_ATTN batch-invariant path on Hopper` | bug,nvidia | ? | - |
| - | [#47095](https://github.com/vllm-project/vllm/issues/47095) `[RFC]: Extension points for backends whose physical layout isn't a permutation of the logical layout (weights,` | perf,quant | ? | - |
| - | [#47129](https://github.com/vllm-project/vllm/issues/47129) `[Bug]: DiffusionGemma fails to start with RuntimeError in _compiled_sample_step during torch.compile (matmul s` | bug,perf | ? | - |
| - | [#47223](https://github.com/vllm-project/vllm/issues/47223) `[Installation]: old nccl version in docker container` | infra,nvidia | ? | - |
| - | [#47275](https://github.com/vllm-project/vllm/issues/47275) `[Bug]: Gemma4 MoE (26B-A4B) aborts with "nanobind::builtin_exception: Expected an MLIR object (got OpResultLis` | nvidia | ? | - |
| - | [#47280](https://github.com/vllm-project/vllm/issues/47280) `[RFC]: Implement return indexer topk for sparse attention.` |  | ? | - |
| - | [#47326](https://github.com/vllm-project/vllm/issues/47326) `[Bug]: Incoherent output depending on tensor-parallel-size during inference on Leanstral (Mistral Small 4 fami` | bug | ? | - |
| - | [#47339](https://github.com/vllm-project/vllm/issues/47339) `Respect explicit VLLM_TARGET_DEVICE=tpu on macOS` |  | ? | - |
| - | [#47349](https://github.com/vllm-project/vllm/issues/47349) `[Bug]: fp8 KV cache + prefix caching truncates generation (ignore_eos bypassed) on Qwen3.5-NVFP4` | perf,quant,risk | ? | - |
| - | [#47351](https://github.com/vllm-project/vllm/issues/47351) `[RFC]: Sparse-attention-based self-speculative decoding (StreamingLLM, then Vegas)` |  | ? | - |
| - | [#47415](https://github.com/vllm-project/vllm/issues/47415) `WorkerProc initialization failure swallows root cause traceback (raise e from None)` |  | ? | - |
| - | [#47424](https://github.com/vllm-project/vllm/issues/47424) `[Bug]: DiffusionGemma output unstable (v0.24.0)` | bug,perf | ? | - |
| - | [#47473](https://github.com/vllm-project/vllm/issues/47473) `[Bug]: Gemma4 (probably other models with missing v_proj) breaks with mixed quantization` | bug,quant | ? | - |
| - | [#47486](https://github.com/vllm-project/vllm/issues/47486) `[Bug]: SpeculativeConfig silently overrides the user's explicit speculative method (model_type and path-substr` | risk | ? | - |
| - | [#47528](https://github.com/vllm-project/vllm/issues/47528) `[Bug]: DeepSeek-V4-Pro (DeepseekV4ForCausalLM, scale_fmt=ue8m0 / FP4 MoE) produces garbled / degenerate output` | bug,quant | ? | - |
| - | [#47548](https://github.com/vllm-project/vllm/issues/47548) `[Bug]: Combination of sleep mode and speculative decoding cause crash (ROCm / MI250)` | bug,rocm | ? | - |
| - | [#47561](https://github.com/vllm-project/vllm/issues/47561) `CUDA illegal memory access during speculator prefill CUDA graph capture on H100` | bug,nvidia,risk | ? | - |
| - | [#47570](https://github.com/vllm-project/vllm/issues/47570) `[Bug]: wrong cutlass Arch import` | bug,nvidia | ? | - |
| - | [#47746](https://github.com/vllm-project/vllm/issues/47746) `[Bug]: AnthropicContentBlock missing per-type field validation for tool_use blocks` | bug | ? | - |
| - | [#47763](https://github.com/vllm-project/vllm/issues/47763) `[Performance]: MiniMax-M3 verify-as-decode re-streams the sparse KV from HBM once per draft token` | perf | ? | - |
| - | [#47768](https://github.com/vllm-project/vllm/issues/47768) `[RFC]: vLLM gRPC server API for downstream integrations` |  | ? | - |
| - | [#47783](https://github.com/vllm-project/vllm/issues/47783) `[Bug]: DSV4 sparse MLA emits garbage (gsm8k ~0%) with the packed KV layout from #44577` | bug,risk | ? | - |
| - | [#47788](https://github.com/vllm-project/vllm/issues/47788) `[Bug]: Qwen3-Omni use_audio_in_video via --mm-processor-kwargs is broken in online serving: engine crash at st` | bug,risk | ? | - |
| - | [#47847](https://github.com/vllm-project/vllm/issues/47847) `[Bug]: disable_flashinfer_q_quantization + fp8 KV + spec decode silently corrupts sliding-window models on SM1` | nvidia,quant,risk | ? | - |
| - | [#47918](https://github.com/vllm-project/vllm/issues/47918) `[Bug]: V1 + Ray distributed executor + LoRA — execute_model returns NoneType on NVIDIA GPU` | nvidia | ? | - |
| - | [#48898](https://github.com/vllm-project/vllm/issues/48898) `[Bug]: NVFP4 garbage output under torch.compile when per-rank K is not 32-aligned (TP8 on SM120): padded block` | nvidia,quant,risk | ? | - |
| - | [#48951](https://github.com/vllm-project/vllm/pull/48951) `[Rust Frontend] Fix bad_words handling in /v1/completions` | bug | main | - |
| - | [#49216](https://github.com/vllm-project/vllm/issues/49216) `[Bug]: Tools streaming internal error when `VLLM_ENFORCE_STRICT_TOOL_CALLING=false` and `tool_choice=required`` | bug | ? | - |
| - | [#49859](https://github.com/vllm-project/vllm/issues/49859) `[Bug]: v0.26.0 EngineCore fails to start on SM90+ — _warmup_ll_bf16_router_gemm hits AttributeError: module 'c` | nvidia | ? | - |
| - | [#50237](https://github.com/vllm-project/vllm/issues/50237) `[Bug]: ROCm mixed KV-cache layouts abort speculative decoding with AssertionError` | perf,rocm | ? | - |
| - | [#50682](https://github.com/vllm-project/vllm/issues/50682) `[ROCm][AMD] Kimi-K3 Gap and Roadmap Tracking` | rocm | ? | - |
| - | [#50699](https://github.com/vllm-project/vllm/issues/50699) `[Bug]: DiffusionGemma: runtime CUDA OOM under concurrent decode (fp32 canvas×vocab temporaries)` | nvidia,perf | ? | - |
| - | [#51808](https://github.com/vllm-project/vllm/pull/51808) `[Online quantization] Support activation quant key override for online MXFP4 linear/MOE quant methods` | nvidia,quant | main | - |
| - | [#51953](https://github.com/vllm-project/vllm/pull/51953) `[Bugfix][MRV2] Fix DiffusionGemma runtime OOM via tiled logits projection` | bug,perf | main | - |
| - | [#52415](https://github.com/vllm-project/vllm/issues/52415) `[Bug] XPU qnorm/rope kernel: overlapping stores in one program corrupt the KV cache nondeterministically` | nvidia,perf,risk | ? | - |
| - | [#52778](https://github.com/vllm-project/vllm/issues/52778) `CustomAllreduce admits cross-node TP=2 groups and dies in cudaIpcOpenMemHandle (custom_all_reduce.cuh:143 'inv` | nvidia,quant | ? | - |
| - | [#52875](https://github.com/vllm-project/vllm/pull/52875) `[Perf][Frontend] Render plain completion stream deltas from a template` | perf | main | - |
| - | [#53369](https://github.com/vllm-project/vllm/pull/53369) `[Bugfix][Frontend] Match default MM LoRA for OpenAI input_audio parts` | bug | main | - |
| - | [#54109](https://github.com/vllm-project/vllm/pull/54109) `[MoE][DeepEPV2] Add PaddedStandard activation format` | infra,nvidia,quant,rocm | main | - |
| - | [#54206](https://github.com/vllm-project/vllm/issues/54206) `[Bug]: Quark FSE compatibility check matches `shared_expert_gate`, silently disabling fused shared experts on ` | perf,quant,risk,rocm | ? | - |
| - | [#54307](https://github.com/vllm-project/vllm/pull/54307) `[KV Connector] Support heterogeneous TP sharing for hybrid KV cache in Mooncake Store` | perf | main | - |
| - | [#54377](https://github.com/vllm-project/vllm/issues/54377) `[Model] Cohere Transcribe fails to initialize on Turing (fp16): expected scalar type Float but found Half in R` |  | ? | - |
| - | [#54399](https://github.com/vllm-project/vllm/pull/54399) `[Bugfix][Model] Fix CohereASR FP16 attention bias dtype` | bug | main | - |
| - | [#54437](https://github.com/vllm-project/vllm/issues/54437) `[Bug]: structured output can sample unconstrained tokens when the draft hand-off goes stale (spec decode + asy` |  | ? | - |
| - | [#54625](https://github.com/vllm-project/vllm/pull/54625) `[Core] Add cache-aware admission ordering` | perf | main | - |
| - | [#54644](https://github.com/vllm-project/vllm/issues/54644) `[RFC]: Preemption victim-selection extension point (least-computed-first as the first built-in)` |  | ? | - |
| - | [#55688](https://github.com/vllm-project/vllm/pull/55688) `[Mamba] Unify FI ReplaySSM STP/MTP/Prefix Caching Lifecycle` | infra,perf | main | - |
| - | [#55775](https://github.com/vllm-project/vllm/issues/55775) `[Bug]: MTP + FlashInfer long-context CUDA IMA / Xid 31 still on v0.27.1 (Qwen3.8-27B-NVFP4, RTX 5090, max-num-` | nvidia,quant | ? | - |
| - | [#55835](https://github.com/vllm-project/vllm/pull/55835) `[Bugfix][Distributed] Keep cross-node MNNVL groups off CUDA IPC all-reduce` | bug,nvidia | main | - |
| - | [#56076](https://github.com/vllm-project/vllm/pull/56076) `[KV Offload] Refactor cpu offloading - calculate gpu pointers and introduce fs ABC` |  | main | - |
| - | [#56102](https://github.com/vllm-project/vllm/pull/56102) `[Bugfix][Kernel] Fix cooperative top-k dispatch on SM110` | bug,nvidia,perf | main | - |
| - | [#56155](https://github.com/vllm-project/vllm/pull/56155) `[Core][Attention] Resolve per-layer KV dtype in attention runtime` | nvidia,perf,quant,rocm | main | - |
| - | [#56277](https://github.com/vllm-project/vllm/pull/56277) `[MM] Mistral vision Encoder CG support ` | nvidia,perf | main | - |
| - | [#56307](https://github.com/vllm-project/vllm/pull/56307) `[ROCm][Kernel] New "hip" GDN backend for gfx1151` | infra,perf,rocm | main | - |
| - | [#56450](https://github.com/vllm-project/vllm/pull/56450) `[ROCm][Perf] Encoder prefill attention on gfx1151: split-D head dims, alignment hint, launch config` | perf,rocm | main | - |
| - | [#56492](https://github.com/vllm-project/vllm/pull/56492) `[Core] Extensible KV cache` | infra,nvidia,perf | main | - |
| - | [#56606](https://github.com/vllm-project/vllm/pull/56606) `[Bugfix][Quantization] Fix online MoE weight conversion `KeyError: 'weight_scale'` with Humming` | bug,quant | main | - |
| - | [#56851](https://github.com/vllm-project/vllm/issues/56851) `[RFC]: Request level text and derender output on `/inference/v1/generate`` |  | ? | - |
| - | [#56996](https://github.com/vllm-project/vllm/pull/56996) `[Perf][Attention] Source Triton metadata builder geometry from kv_cache_spec` | bug,perf,rocm | main | - |
| - | [#57042](https://github.com/vllm-project/vllm/pull/57042) `[Kernel] Accumulate ranks in absolute order in 2-stage custom all-reduce` | perf | main | - |
| - | [#57167](https://github.com/vllm-project/vllm/pull/57167) `[Bugfix][MoE] Reject non-contiguous routing tensors` | bug | main | - |
| - | [#57245](https://github.com/vllm-project/vllm/pull/57245) `[LoRA] Add DeepSeek V4.1 language-model adapter support` | nvidia | main | - |
| - | [#57474](https://github.com/vllm-project/vllm/pull/57474) `[Perf][KV Offload] Publish async lookup results per request group` | perf | main | - |
| - | [#57519](https://github.com/vllm-project/vllm/pull/57519) `[Bugfix][Benchmark] Fail streams that end in a server error event` | bug,perf | main | - |
| - | [#57678](https://github.com/vllm-project/vllm/pull/57678) `[Model Loader] One post-load hook signature; the loader runs every module's hook` | infra,quant | main | - |
| - | [#57684](https://github.com/vllm-project/vllm/issues/57684) `[Question] Support path for platform plugins that cannot install Triton (MRV2 requires it)` | rocm | ? | - |
| - | [#57770](https://github.com/vllm-project/vllm/pull/57770) `[Perf][Spec Decode] Split-vocabulary Triton argmax for the DSpark greedy draft` | perf,rocm | main | - |
| - | [#57851](https://github.com/vllm-project/vllm/pull/57851) `[Bugfix][LoRA] Handle leading missing packed groups` | bug | main | - |
| - | [#58618](https://github.com/vllm-project/vllm/pull/58618) `[Bugfix][KV Offload] Anchor the partial-tail lookup on the full-attention prefix` | bug,infra | main | - |
| - | [#58726](https://github.com/vllm-project/vllm/issues/58726) `[Performance]: Weight loading is slow on GB10 (DGX Spark): per-tensor H2D copies straight from safetensors mma` | perf,quant | ? | - |
| - | [#58868](https://github.com/vllm-project/vllm/pull/58868) `[Perf][Model Loader] Fault in mmap'd weight pages before host-to-device copies on integrated GPUs` | perf | main | - |
| - | [#59041](https://github.com/vllm-project/vllm/pull/59041) `[CI][Test] Use file:// rendezvous in the Ray multi-GPU test harness` | infra | main | - |
| - | [#59124](https://github.com/vllm-project/vllm/pull/59124) `[ROCm][Perf][MLA] Add opt-in FlyDSL FP8 prefill attention for AITER MLA` | perf,quant,rocm | main | - |
| - | [#59203](https://github.com/vllm-project/vllm/issues/59203) `[Bug][v0.32.0 release] No working block size on the release tag (both 64 and 128 fail); fix tracked in #60762` | bug,infra | ? | - |
| - | [#59383](https://github.com/vllm-project/vllm/pull/59383) `[Bugfix][KV Offload] Return lazily offloaded GPU blocks to the eviction end` | bug,perf | main | - |
| - | [#59526](https://github.com/vllm-project/vllm/pull/59526) `[CI] Run pip-compile pre-commit hooks only when requirements change` | bug,infra | main | - |
| - | [#59722](https://github.com/vllm-project/vllm/issues/59722) `[Bug]: Rust vllm-bench openai-chat counts token-less streams as successful` | perf | ? | - |
| - | [#59736](https://github.com/vllm-project/vllm/pull/59736) `[Bugfix][Rust Frontend] Fail token-less streams in vllm-bench openai-chat` | bug,perf | main | - |
| - | [#59747](https://github.com/vllm-project/vllm/pull/59747) `[Bugfix][NIXL] Reject push handshakes between different P/D block sizes` | bug | main | - |
| - | [#59802](https://github.com/vllm-project/vllm/pull/59802) `[ROCm][DSv4.1][Perf] Overlap the mHC gate projection with attention and FFN` | perf,rocm | main | - |
| - | [#59844](https://github.com/vllm-project/vllm/pull/59844) `[Bugfix][DeepEP] Upgrade to 2.1 and retain per-context GIN completion ordering` | bug,infra,nvidia | main | - |
| - | [#59958](https://github.com/vllm-project/vllm/pull/59958) `[Qwen4Exp] PLE disk offload` | infra | main | - |
| - | [#59961](https://github.com/vllm-project/vllm/pull/59961) `[Bugfix][DSv3.2] Carry the shared indexer top-k across pipeline stages` | bug,infra | main | - |
| - | [#59998](https://github.com/vllm-project/vllm/issues/59998) `[Bug]: FlashInfer with LHBNC on A100 asserts at startup` | nvidia | ? | - |
| - | [#59999](https://github.com/vllm-project/vllm/pull/59999) `[Bugfix] FlashInfer: declare only KV layouts it can address` | bug,nvidia | main | - |
| - | [#60010](https://github.com/vllm-project/vllm/pull/60010) `[Bugfix][Benchmark] Clean up sweep workers after the server exits` | bug,perf | main | - |
| - | [#60102](https://github.com/vllm-project/vllm/pull/60102) `[ROCm][DSv4.1][Perf] Route gfx942 sparse MLA prefill to AITER pa_prefill_sparse` | perf,rocm | main | - |
| - | [#60177](https://github.com/vllm-project/vllm/pull/60177) `[Bugfix][Benchmark] Preserve Rust SSE payloads across chunks and comments` | bug,perf | main | - |
| - | [#60181](https://github.com/vllm-project/vllm/pull/60181) `[Bugfix][NIXL] Fix host-buffer h2d sync overwriting received KV` | bug | main | - |
| - | [#60213](https://github.com/vllm-project/vllm/pull/60213) `[Metrics][Frontend] Expose request render duration metric` |  | main | - |
| - | [#60218](https://github.com/vllm-project/vllm/pull/60218) `[hw-agnostic] Opt-in infrastructure for OOT plugins` | infra | main | - |
| - | [#60252](https://github.com/vllm-project/vllm/pull/60252) `[Bugfix][Spec Decode] Keep SW draft block a divisor of the primary block` | bug | main | - |
| - | [#60258](https://github.com/vllm-project/vllm/issues/60258) `[ROCm][CI] ci_base images built from ROCm 10.0 nightly wheels have a non-reproducible ~9.5 GiB top layer` | infra,rocm | ? | - |
| - | [#60314](https://github.com/vllm-project/vllm/pull/60314) `[Model] Support data-parallel multimodal encoder for Gemma-4` |  | main | - |
| - | [#60339](https://github.com/vllm-project/vllm/pull/60339) `[Spec Decode][MRV2] Suffix decoding speculator for Model Runner V2` |  | main | - |
| - | [#60372](https://github.com/vllm-project/vllm/pull/60372) `[Kernel] Integrate FA4 SM90 FP8 MMA for Gemma-4 full attention` | infra,nvidia,perf,quant | main | - |
| - | [#60408](https://github.com/vllm-project/vllm/issues/60408) `[Bug][ROCm] gfx950: ROCM_AITER_UNIFIED_ATTN decode regressed in v0.31.0 (-19%, and MTP decode decays with cont` | rocm | ? | - |
| - | [#60418](https://github.com/vllm-project/vllm/pull/60418) `[ROCm] [RDNA] [Perf] Add tuned configs for TRITON_ATTN kernel and swap places of TRITON_ATTN and ROCM_ATTN in ` | perf,rocm | main | - |
| - | [#60438](https://github.com/vllm-project/vllm/pull/60438) `[Bugfix] Fall back from DeepGEMM when nvcc is older than 12.9` | bug,nvidia | main | - |
| - | [#60479](https://github.com/vllm-project/vllm/pull/60479) `[Bugfix] Keep GPTQ linear layers batch invariant` | bug,quant | main | - |
| - | [#60487](https://github.com/vllm-project/vllm/pull/60487) `[Bugfix][ROCm] Count attention sinks once in AITER FA chunked-context extend` | bug,rocm | main | - |
| - | [#60543](https://github.com/vllm-project/vllm/pull/60543) `[Bugfix][DSv4.1] Autotune the sparse indexer's wq_b GEMM` | bug,perf | main | - |
| - | [#60618](https://github.com/vllm-project/vllm/pull/60618) `[Perf][Kernel] Single-launch fused scoring+top-k kernel for sparse-indexer prefill, without materializing logi` | infra,perf,rocm | main | - |
| - | [#60762](https://github.com/vllm-project/vllm/pull/60762) `[Bugfix][DSv4.1] Declare 64-token kernel blocks for SM120 sparse backends` | bug,infra,nvidia,perf,quant,rocm | main | - |
| - | [#60791](https://github.com/vllm-project/vllm/issues/60791) `[Bug]: MiniMax-M3: PP startup, NIXL+PP prefill, NIXL/offload+HMA+DSpark, offload+PP, Mooncake recompute loop, ` |  | ? | - |
| - | [#60824](https://github.com/vllm-project/vllm/pull/60824) `[ZenCPU] Add zen5 CPU tests reusing the pushed zen image` | infra | main | - |
| - | [#60867](https://github.com/vllm-project/vllm/pull/60867) `[KV Connector][ROCm] MoRIIO: hybrid READ for several attention groups and shared-group speculative methods` | rocm | main | - |
| - | [#60873](https://github.com/vllm-project/vllm/pull/60873) `[Bugfix] Fix depyf incompatibility with Inductor's set_sys_modules` | bug | main | - |
| - | [#60882](https://github.com/vllm-project/vllm/pull/60882) `[Perf][ToolParser] Scan required-tool streaming deltas incrementally` | perf | main | - |
| - | [#60895](https://github.com/vllm-project/vllm/pull/60895) `[Perf][GLM-5.3-Flash] DeepGEMM FP8 MegaMoE with fused shared experts` | perf,quant | main | - |
| - | [#60919](https://github.com/vllm-project/vllm/pull/60919) `[JIT][ROCm] Fully warmup GLM-5.3-Flash` | rocm | main | - |
| - | [#60977](https://github.com/vllm-project/vllm/issues/60977) `[Bug]: EmbeddingGemma 2 rejects dimensions=768 despite returning 768-dimensional embeddings` |  | ? | - |
| - | [#60978](https://github.com/vllm-project/vllm/pull/60978) `[Bugfix][Pooling] Use embedding_dim for pooling output size` | bug | main | - |
| - | [#60989](https://github.com/vllm-project/vllm/pull/60989) `[MRV2][Spec Decode] Refactor AR speculators and enable CUDA Graph for draft model` | nvidia | main | - |
| - | [#61162](https://github.com/vllm-project/vllm/pull/61162) `[Bugfix][MRV2][LoRA] Disable KV-sharing fast prefill for LoRA batches` | bug,nvidia | main | - |
| - | [#61194](https://github.com/vllm-project/vllm/pull/61194) `[Bugfix][Watermarking] Skip incomplete opening contexts` | bug,infra | main | - |
| - | [#61219](https://github.com/vllm-project/vllm/pull/61219) `[Bugfix][Spec Decode] V2 rejection sampler: return logprob_token_ids scores` | bug | main | - |
| - | [#61267](https://github.com/vllm-project/vllm/pull/61267) `[Bugfix][LoRA] respect `attention_k_eq_v=True` QKK LoRA layers` | bug | main | - |
| - | [#61292](https://github.com/vllm-project/vllm/pull/61292) `[KV Connector][Mooncake] Start async lookup when a request arrives via on_new_request` |  | main | - |
| - | [#61319](https://github.com/vllm-project/vllm/issues/61319) `[Bug]:  Greedy (temperature=0) decoding is not reproducible across repeated calls on the same engine for Liqui` | bug,quant | ? | - |
| - | [#61361](https://github.com/vllm-project/vllm/pull/61361) `[MORI] Add MORI EP V2 support` | nvidia,rocm | main | - |
| - | [#61380](https://github.com/vllm-project/vllm/pull/61380) `[Bugfix] Resolve HF paths when loading sharded state` | bug | main | - |
| - | [#61435](https://github.com/vllm-project/vllm/pull/61435) `[ROCm][Perf][Kimi-K3] Specialized decode on MI355X: K1/K2 + MLA M1a/M1b (FlyDSL, TP8, DCP1/DCP8)` | infra,perf,rocm | main | - |
| - | [#61463](https://github.com/vllm-project/vllm/pull/61463) `[Bugfix][Kernel] Sync cluster before DSMEM stores in ll_bf16 split-K router GEMM` | bug,perf | main | - |
| - | [#61542](https://github.com/vllm-project/vllm/pull/61542) `[Bugfix][Tool Parser] Preserve whitespace in HYV4 argument names` | bug | main | - |
| - | [#61593](https://github.com/vllm-project/vllm/pull/61593) `[CPU] Enable gelu_tanh activation support for Gemma4 MoE` |  | main | - |
| - | [#61609](https://github.com/vllm-project/vllm/pull/61609) `[Attention][DCP] Support DCP on the FlashMLA sparse bf16 KV path` | nvidia | main | - |
| - | [#61614](https://github.com/vllm-project/vllm/pull/61614) `[Perf][GLM-5.3-Flash] Update FlashKDA pin, consume row-strided QKV directly` | infra,perf | main | - |
| - | [#61641](https://github.com/vllm-project/vllm/pull/61641) `[Perf][Kernel] Convert two FP8 values per cvt in the FP8 quant kernels` | nvidia,perf,quant | main | - |
| - | [#61658](https://github.com/vllm-project/vllm/issues/61658) `[Bug]: tiering async lookup serves stale absent verdicts across instances sharing a secondary tier` | bug | ? | - |
| - | [#61680](https://github.com/vllm-project/vllm/pull/61680) `[Perf][HiSparse] Segment host KV pool backing files` | perf | main | - |
| - | [#61755](https://github.com/vllm-project/vllm/pull/61755) `[Bugfix][Kernel] Fill K-padded output in silu_and_mul_nvfp4_quant` | bug,perf,quant | main | - |
| - | [#61764](https://github.com/vllm-project/vllm/pull/61764) `[Bugfix][EC Connector] Allocate producer control ports at startup` | bug | main | - |
| - | [#61770](https://github.com/vllm-project/vllm/pull/61770) `[Bugfix][ROCm][Qwen4Exp] Remap Quark layer names for the MTP draft model` | bug,rocm | main | - |
| - | [#61794](https://github.com/vllm-project/vllm/pull/61794) `[Test][UMBP][6/10] Add embedded runtime and MORI integration coverage` | infra,rocm | main | - |
| - | [#61795](https://github.com/vllm-project/vllm/pull/61795) `[UMBP][7/10] Add standalone mode backed by a node-local server` | infra,rocm | main | - |
| - | [#61821](https://github.com/vllm-project/vllm/pull/61821) `[Perf][Kernel] Add the bias in the SM120 NVFP4 CUTLASS GEMM epilogue` | nvidia,perf,quant | main | - |
| - | [#61837](https://github.com/vllm-project/vllm/pull/61837) `[ROCm][Model] Step-5-Preview support on ROCm` | infra,nvidia,rocm | main | - |
| - | [#61853](https://github.com/vllm-project/vllm/issues/61853) `[Bug]: enable_lora on Jamba (ai21labs/Jamba-tiny-dev) causes a CUDA illegal memory access followed by an uncau` | bug,nvidia,risk | ? | - |
| - | [#61866](https://github.com/vllm-project/vllm/issues/61866) `[ROCm][Perf] gfx950 spec-decode verify attention is up to 48x slower with AITER <= v0.1.25; bump to a release ` | infra,perf,rocm | ? | - |
| - | [#61881](https://github.com/vllm-project/vllm/issues/61881) `[Refactor]: Split MRV2 CUDA graph capture planning by batch type` | nvidia | ? | - |
| - | [#61950](https://github.com/vllm-project/vllm/pull/61950) `[Bugfix][ROCm] Fix Kimi K3 online quantization with padded projections` | bug,quant,rocm | main | - |
| - | [#61971](https://github.com/vllm-project/vllm/pull/61971) `[Perf][DSv4.1] Bump FlashMLA to pass int64 positions to MegaAttn` | infra,nvidia,perf | main | - |
| - | [#61973](https://github.com/vllm-project/vllm/pull/61973) `[Bugfix] Preserve batch audio handler error status codes` | bug | main | - |
| - | [#61995](https://github.com/vllm-project/vllm/pull/61995) `[CPU][MRv2] Enable MRv2 for non-triton CPU backends` | infra,rocm | main | - |
| - | [#62007](https://github.com/vllm-project/vllm/pull/62007) `[ROCm][DI][CI]  Add DeepSeek-V3 NIXL accuracy steps` | infra,risk,rocm | main | - |
| - | [#62057](https://github.com/vllm-project/vllm/pull/62057) `[ROCm][Model] Add Beam 1.0 support on ROCm ` | infra,nvidia,rocm | main | - |
| - | [#62097](https://github.com/vllm-project/vllm/pull/62097) `[Bugfix][LoRA] Account for CLIP CLS rows in LLaVA-NeXT-Video tower mappings` | bug | main | - |
| - | [#62111](https://github.com/vllm-project/vllm/pull/62111) `[Bugfix] Fix multi-layer MTP module selection for Qwen3.5 and Qwen3-Next` | bug,infra | main | - |
| - | [#62172](https://github.com/vllm-project/vllm/pull/62172) `[Perf][Kernel] Let cooperative_topk read the BF16 indexer logits` | perf | main | - |
| - | [#62192](https://github.com/vllm-project/vllm/pull/62192) `[Kernel] Batch invariance: pin FlashInfer FP8 bmm and W4A16 NVFP4 kernels` | infra,nvidia,perf,quant | main | - |
| - | [#62203](https://github.com/vllm-project/vllm/pull/62203) `[Perf][ToolParser] Scan Kimi K3 streaming tool calls incrementally` | perf | main | - |
| - | [#62217](https://github.com/vllm-project/vllm/issues/62217) `[Bug][HiSparse]: Two admitted async KV loads stall the scheduler on host blocks` |  | ? | - |
| - | [#62234](https://github.com/vllm-project/vllm/pull/62234) `[Bugfix][Spec Decode] Align speculator hidden norm in GLM-4.5/4.6 MoE and GLM-OCR MTP with GLM5Next to recycle` | bug,infra | main | - |
| - | [#62264](https://github.com/vllm-project/vllm/issues/62264) `[Bug]: --attention-backend b12x fails at startup without --block-size (impl checks block size before the platf` |  | ? | - |
| - | [#62270](https://github.com/vllm-project/vllm/pull/62270) `[ROCm][Perf][MiniMax-M3] Enable the fp8 indexer cache on gfx942` | infra,perf,quant,rocm | main | - |
| - | [#62275](https://github.com/vllm-project/vllm/pull/62275) `[Bugfix] Disable CUTLASS FP4 MoE backend on sm_110` | bug,nvidia,quant | main | - |
| - | [#62367](https://github.com/vllm-project/vllm/pull/62367) `[Feature] Support batch invariance for ShortConv (LFM2) models` | infra | main | - |
| - | [#62424](https://github.com/vllm-project/vllm/pull/62424) `[Rust Frontend] Add native GLM-5.3 / GLM-5.3-Flash chat rendering` | infra | main | - |
| - | [#62470](https://github.com/vllm-project/vllm/pull/62470) `[Bugfix][LoRA] Scale embedding LoRA deltas by the base layer's embed_scale` | bug,quant | main | - |
| - | [#62517](https://github.com/vllm-project/vllm/pull/62517) `[Bugfix][Parser] DeepSeek V4.1: don't leak a `<｜DSML｜ tool_calls>` opener into content` | bug | main | - |
| - | [#62560](https://github.com/vllm-project/vllm/pull/62560) `[Core][MRV2] Warm up the sampler after CUDA graph capture to stop memory growth under load` | nvidia | main | - |
| - | [#62565](https://github.com/vllm-project/vllm/pull/62565) `[ROCm][Perf] Fix Kimi-K2.6 int4 MoE prefill regression on Triton 3.8 (gfx950 tuned config)` | bug,perf,quant,rocm | main | - |
| - | [#62606](https://github.com/vllm-project/vllm/issues/62606) `[Bug][ROCm]: ROCM_AITER_UNIFIED_ATTN gives wrong output on gfx950 when a layer's KV cache is 2–4 GiB` | perf,risk,rocm | ? | - |
| - | [#62613](https://github.com/vllm-project/vllm/pull/62613) `[KV Offload] Emit self-describing events for recurrent state groups` |  | main | - |
| - | [#62623](https://github.com/vllm-project/vllm/pull/62623) `[XPU][Test] Skip attention fusion splitting_ops check on XPU` | nvidia,perf | main | - |
| - | [#62632](https://github.com/vllm-project/vllm/pull/62632) `[Perf][Kernel][DSv4.1] Copy-based Q zero-pad for large eager mega-attention steps` | perf | main | - |
| - | [#62633](https://github.com/vllm-project/vllm/pull/62633) `[Perf][Kernel][DSv4.1] Swap-AB CuTe DSL decode attention for small TP2/TP4 steps` | infra,perf | main | - |
| - | [#62647](https://github.com/vllm-project/vllm/pull/62647) `[Bugfix][Frontend] Materialize DeepSeek V4.1 content iterators before deepcopy` | bug | main | - |
| - | [#62674](https://github.com/vllm-project/vllm/pull/62674) `[Bugfix] Retry incomplete HTTP response bodies` | bug | main | - |
| - | [#62702](https://github.com/vllm-project/vllm/pull/62702) `[Perf][Core] Keep prompt token ids as int32 buffers` | perf | main | - |
| - | [#62716](https://github.com/vllm-project/vllm/pull/62716) `[ROCm][Build][1/5] Speed up ROCm build: generate the paged attention instantiations from one variant list` | infra,perf,rocm | main | - |
| - | [#62717](https://github.com/vllm-project/vllm/pull/62717) `[ROCm][Build][2/5] Speed up ROCm build: split the topk softplus-sqrt instantiations per dtype` | infra,perf,rocm | main | - |
| - | [#62725](https://github.com/vllm-project/vllm/pull/62725) `[ROCm][Bugfix] Serve gfx942 MLA verify past 4 tokens with a Triton kernel` | bug,perf,rocm | main | - |
| - | [#62729](https://github.com/vllm-project/vllm/pull/62729) `[Bugfix] Honor add_generation_prompt and continue_final_message in the DeepSeek V4.1 tokenizer` | bug | main | - |
| - | [#62750](https://github.com/vllm-project/vllm/pull/62750) `[Quantization] Block Hadamard input rotation for linear layers: online `mxfp4_hadamard32` and Quark online-rot` | quant,rocm | main | - |
| - | [#62753](https://github.com/vllm-project/vllm/pull/62753) `[Bugfix][Benchmark] Count tool call deltas as generated tokens in openai-responses` | bug,perf | main | - |
| - | [#62759](https://github.com/vllm-project/vllm/pull/62759) `[Quant] LUT-B MoE with MXFP8 activations: native Rubin kernel + emulation` | infra,perf,quant | main | - |
| - | [#62802](https://github.com/vllm-project/vllm/pull/62802) `[EPD] Support DeepSeek-V4.1 image metadata-only inputs` |  | main | - |
| - | [#62836](https://github.com/vllm-project/vllm/pull/62836) `[Bugfix] Fix GPTQ checkpoint loading for PLaMo3` | bug,quant | main | - |
| - | [#62881](https://github.com/vllm-project/vllm/pull/62881) `[Bugfix][Test] Rotate KV into RHT domain in the INT4 unified attn test` | bug,infra,quant | main | - |
| - | [#62956](https://github.com/vllm-project/vllm/pull/62956) `[Perf][glm5next] Add SM121 TP=2 skinny-GEMM plans for GLM-5.3-Flash` | nvidia,perf | main | - |
| - | [#62966](https://github.com/vllm-project/vllm/pull/62966) `[Core] Add watermark_config.enforce to override request opt-outs in EngineCore` | infra | main | - |
| - | [#62967](https://github.com/vllm-project/vllm/pull/62967) `[Bugfix][gRPC] Drain in-flight RPCs and engine work within --shutdown-timeout` | bug | main | - |
| - | [#62979](https://github.com/vllm-project/vllm/pull/62979) `[Bugfix][HiSparse] Reserve in-flight imports' host pages at admission` | bug,perf | main | - |
| - | [#63005](https://github.com/vllm-project/vllm/pull/63005) `[Perf][Frontend] Build run-batch TypeAdapters once instead of per request` | infra,perf | main | - |
| - | [#63011](https://github.com/vllm-project/vllm/issues/63011) `[Bug]: b12x attention backend advertises head_dim 64, but every head_dim 64 model crashes at the first forward` | bug | ? | - |
| - | [#63012](https://github.com/vllm-project/vllm/pull/63012) `[Bugfix][Attention] Stop advertising head_dim 64 in the b12x backend` | bug | main | - |
| - | [#63027](https://github.com/vllm-project/vllm/pull/63027) `[ROCm][Perf][DSv4.1] Mono: tuned K1/K2 for the TP2 compress-ratio-2 layers on MI355X` | perf,rocm | main | - |
| - | [#63049](https://github.com/vllm-project/vllm/issues/63049) `[Bug]: TritonW4A16 GEMM faults on ROCm once M × N or M × K passes 2^31` | quant,rocm | ? | - |
| - | [#63054](https://github.com/vllm-project/vllm/pull/63054) `[Bugfix][ROCm] Use 64-bit row offsets in the Triton W4A16 GEMM` | bug,quant,rocm | main | - |
| - | [#63076](https://github.com/vllm-project/vllm/pull/63076) `[ROCm][Perf] Triton sigmoid+bias top-k when MoE grouping eliminates nothing` | perf,rocm | main | - |
| - | [#63098](https://github.com/vllm-project/vllm/pull/63098) `[Feature][DSv4.1] Enable PCP with PP or DP` | infra,perf | main | - |
| - | [#63103](https://github.com/vllm-project/vllm/pull/63103) `[Frontend] Stream derender on /inference/v1/generate` |  | main | - |
| - | [#63116](https://github.com/vllm-project/vllm/pull/63116) `[Bugfix][ROCm] Size AITER MLA persistent metadata for every decode query length` | bug,rocm | main | - |
| - | [#63117](https://github.com/vllm-project/vllm/pull/63117) `[Bugfix][ROCm] Take the AITER MLA KV cache dtype from the group's spec` | bug,perf,rocm | main | - |
| - | [#63123](https://github.com/vllm-project/vllm/pull/63123) `[Bugfix][Distributed] Gate FlashInfer all-reduce on 16-byte row widths ` | bug,infra,nvidia | main | - |
| - | [#63130](https://github.com/vllm-project/vllm/issues/63130) `[Bug]: Strict serde rejection of duplicate field `reasoning` breaks agent harnesses that echo both `reasoning`` | bug | ? | - |
| - | [#63137](https://github.com/vllm-project/vllm/pull/63137) `[Rust Frontend] Accept duplicate reasoning aliases in chat messages` |  | main | - |
| - | [#63162](https://github.com/vllm-project/vllm/issues/63162) `[Bug]: `return_tokens_as_token_ids` is ignored on derender paths` | bug | ? | - |
| - | [#63170](https://github.com/vllm-project/vllm/issues/63170) `[Bug]: GLM-5.x (DSA) under pipeline parallelism: reuse layers at a stage start read stale top-k indices` | bug | ? | - |
| - | [#63173](https://github.com/vllm-project/vllm/pull/63173) `[Bugfix][Frontend] Honor token ID logprob overrides on derender paths` | bug | main | - |
| - | [#63174](https://github.com/vllm-project/vllm/pull/63174) `[Bugfix] Skip redundant weight tensor clones for loaders that yield owned tensors` | bug,infra,rocm | main | - |
| - | [#63189](https://github.com/vllm-project/vllm/pull/63189) `[Bugfix][Frontend] Handle buffered JSON embedding responses in run-batch` | bug | main | - |
| - | [#63204](https://github.com/vllm-project/vllm/pull/63204) `[Refactor][ROCm][MoE] Let each AiterExperts subclass own its AITER call args` | quant,rocm | main | - |
| - | [#63205](https://github.com/vllm-project/vllm/pull/63205) `[Model Runner V2][Spec Decode] Speculator config classes and custom speculators` | perf | main | - |
| - | [#63219](https://github.com/vllm-project/vllm/pull/63219) `[Bugfix][Spec Decode] Per-request draft retention for structured output under PP` | bug,infra | main | - |
| - | [#63231](https://github.com/vllm-project/vllm/pull/63231) `[Core] Change default --block-size from 16 to 64` | bug,nvidia,rocm | main | - |
| - | [#63232](https://github.com/vllm-project/vllm/pull/63232) `[Perf][FlashAttention] FA4: pass no FP8 descale for a unit per-tensor scale` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#63247](https://github.com/vllm-project/vllm/pull/63247) `[Compile] Make the compile cache device-neutral with compile_on_one_rank` | infra,perf | main | - |
| - | [#63249](https://github.com/vllm-project/vllm/pull/63249) `[Bugfix][KV Offload] Preserve stored event prefix order` | bug | main | - |
| - | [#63297](https://github.com/vllm-project/vllm/pull/63297) `[ROCm][Kimi-K3] Keep KDA prefill checkpoints with the gluon backend` | rocm | main | - |
| - | [#63302](https://github.com/vllm-project/vllm/pull/63302) `[Frontend] Validate JSON body and request_ids in /inference/v1/abort_requests` |  | main | - |
| - | [#63304](https://github.com/vllm-project/vllm/pull/63304) `[Frontend] Remove dead helpers and sync type annotations in entrypoints and config` |  | main | - |
| - | [#63348](https://github.com/vllm-project/vllm/pull/63348) `[Docs] Add Qwen3-4B and tidy Qwen entries in batch invariance tested models` |  | main | - |
| - | [#63349](https://github.com/vllm-project/vllm/pull/63349) `[MOE oracle][Refactor][1/N] Deduplicate the MoE oracle selection and backend code` | nvidia | main | - |
| - | [#63363](https://github.com/vllm-project/vllm/issues/63363) `[RFC]: Keep per-request token lists out of EngineCore garbage collection` | risk | ? | - |
| - | [#63364](https://github.com/vllm-project/vllm/pull/63364) `[ROCm][Build][4/5] Speed up ROCm build: instantiate the int4 skinny GEMM per output width` | infra,perf,quant,rocm | main | - |
| - | [#63367](https://github.com/vllm-project/vllm/pull/63367) `[ROCm][DSv4.1] Shard the Engram gate so TP ranks gather only the value slice` | rocm | main | - |
| - | [#63406](https://github.com/vllm-project/vllm/pull/63406) `[Core][CUDA Graph] Separate prefill (token) and decode (request) CUDA graph capture sizes` | nvidia | main | - |
| - | [#63414](https://github.com/vllm-project/vllm/issues/63414) `[Bug]: compile_mm_encoder is engine-fatal for RADIO/NaViT encoders (Nemotron Parse 3.5)` |  | ? | - |
| - | [#63415](https://github.com/vllm-project/vllm/pull/63415) `[Bugfix][Model] Make compile_mm_encoder work for RADIO/NaViT encoders` | bug | main | - |
| - | [#63416](https://github.com/vllm-project/vllm/pull/63416) `[KV Connector][NIXL] Pair KV regions by layer for every transfer` |  | main | - |
| - | [#63419](https://github.com/vllm-project/vllm/pull/63419) `[ROCm] Migrate Aiter sigmoid to topk_gating` | rocm | main | - |
| - | [#63420](https://github.com/vllm-project/vllm/pull/63420) `[Mooncake] Support selective leases for prefix lookups` |  | main | - |
| - | [#63426](https://github.com/vllm-project/vllm/pull/63426) `[ROCm][CI] Print the native backtrace of a fault in AMD CI pytest runs` | infra,rocm | main | - |
| - | [#63434](https://github.com/vllm-project/vllm/pull/63434) `[Bugfix][Frontend] Pass the caller's prompt_token_ids to the chat derender parser` | bug | main | - |
| - | [#63440](https://github.com/vllm-project/vllm/pull/63440) `[ROCm][Perf][Muse Spark] FlyDSL decode monokernel for DSpark verify steps on MI355X (--monokernel)` | infra,nvidia,perf,rocm | main | - |
| - | [#63467](https://github.com/vllm-project/vllm/issues/63467) `[Bug]: Wrong token ids from fastokens' split cache before 0.3.4 (Rust frontend, VLLM_USE_FASTOKENS)` | perf | ? | - |
| - | [#63482](https://github.com/vllm-project/vllm/pull/63482) `[Bugfix] [Tokenizer] Preserve Hub model identity when loading tokenizer snapshots` | bug | main | - |
| - | [#63488](https://github.com/vllm-project/vllm/pull/63488) `[Bugfix] Restore engine memory budget after IPC fallback` | bug | main | - |
| - | [#63514](https://github.com/vllm-project/vllm/issues/63514) `[Bug]: `hadacore_transform` gives wrong results for odd row counts (INT4 per-token-head KV cache): garbage K/V` | bug,perf,quant,risk | ? | - |
| - | [#63587](https://github.com/vllm-project/vllm/issues/63587) `[Bug]: DFlash draft acceptance drops to ~0 on 0.32.0 with FULL CUDA graphs (in-graph draft metadata, #60692)` | nvidia | ? | - |
| - | [#63606](https://github.com/vllm-project/vllm/pull/63606) `[Bugfix][Frontend] Use the default template of multi-template processors` | bug | main | - |
| - | [#63614](https://github.com/vllm-project/vllm/pull/63614) `[Bugfix][Kernel] hadacore: fix skipped wait_group on partial-chunk warp for odd row counts (#63514)` | bug,nvidia,perf | main | - |
| - | [#63641](https://github.com/vllm-project/vllm/pull/63641) `[XPU][Test] Use current platform device in test_compile_ranges` | infra,nvidia | main | - |
| - | [#63672](https://github.com/vllm-project/vllm/pull/63672) `[Fast Start] Support online FP8 and CUTLASS NVFP4 weight-cache restarts` | infra,nvidia,perf,quant | main | - |
| - | [#63692](https://github.com/vllm-project/vllm/pull/63692) `[Fast Start] Stop preload groups when a daemon rank exits` | infra | main | - |
| - | [#63695](https://github.com/vllm-project/vllm/pull/63695) `[KV Offload] Carry request context on raw stored events` |  | main | - |
| - | [#63696](https://github.com/vllm-project/vllm/pull/63696) `[KV Offload] Describe complete stores from request context` |  | main | - |
| - | [#63711](https://github.com/vllm-project/vllm/pull/63711) `[CPU][Zen] Enable Laguna MoE on Zen CPU via grouped W8A16 (DA8W8)` | quant | main | - |
| - | [#63730](https://github.com/vllm-project/vllm/pull/63730) `[ROCm][Perf] Kimi-K3 prefill GEMMs on AITER tuned kernels` | perf,rocm | main | - |
| - | [#63732](https://github.com/vllm-project/vllm/issues/63732) `[Bug]: Gemma 4 + online --quantization fp8: image requests crash since v0.23.0 (FP8-cast pixel values reach qu` | bug,quant | ? | - |
| - | [#63742](https://github.com/vllm-project/vllm/pull/63742) `[Perf][Mamba] Use the shared checkpoint exporter for Mamba2 and drop ssd_checkpoint` | perf | main | - |
| - | [#63752](https://github.com/vllm-project/vllm/pull/63752) `[Bugfix][Model Loader] Reject stacked weights that received only some shards` | bug | main | - |
| - | [#63754](https://github.com/vllm-project/vllm/pull/63754) `[Fast Start] Support ModelOpt CUTLASS FP8 weight-cache restarts` | infra,nvidia,perf,quant | main | - |
| - | [#63759](https://github.com/vllm-project/vllm/issues/63759) `[Bug]: Qwen3.5: int32 token-offset overflows in three Triton kernels give wrong outputs or illegal memory acce` | bug,perf,risk,rocm | ? | - |
| - | [#63761](https://github.com/vllm-project/vllm/pull/63761) `[Bugfix] Fix int32 token offset overflows in Qwen3.5 attention and GDN prefill kernels` | bug,infra,perf,risk | main | - |
| - | [#63774](https://github.com/vllm-project/vllm/pull/63774) `[ROCm] Bump AITER to v0.1.27` | infra,rocm | main | - |
| - | [#63801](https://github.com/vllm-project/vllm/pull/63801) `[Perf][HiSparse] Prefetch speculative groups with bounded copy workers` | infra,perf | main | - |
| - | [#63835](https://github.com/vllm-project/vllm/pull/63835) `[ROCm][Perf][Bugfix] wvSplitK: launch tiles of their own for gfx1151 and gfx1150; fix bigType for A_CHUNK 16` | bug,perf,rocm | main | - |
| - | [#63842](https://github.com/vllm-project/vllm/pull/63842) `[Perf][Frontend] Compute prompt block hashes in the Rust frontend` | infra,perf | main | - |
| - | [#63870](https://github.com/vllm-project/vllm/pull/63870) `[Rust Frontend][gRPC] Separate liveness from inference readiness` |  | main | - |
| - | [#63885](https://github.com/vllm-project/vllm/pull/63885) `[ROCm][Perf][DSv4.1] Build the SWA decode metadata in one launch ` | infra,perf,rocm | main | - |
| - | [#63886](https://github.com/vllm-project/vllm/pull/63886) `[Spec Decode][DSpark] Batch-sharded sequential block` |  | main | - |
| - | [#63888](https://github.com/vllm-project/vllm/pull/63888) `[ROCm][Perf][DSv4.1] Skip the top-k -1 fill on the rows vLLM's decode top-k writes` | perf,rocm | main | - |
| - | [#63891](https://github.com/vllm-project/vllm/pull/63891) `[ROCm][Perf][DSv4.1] Run DSpark's fused Markov sampling on gfx950 with --monokernel` | infra,perf,rocm | main | - |
| - | [#63892](https://github.com/vllm-project/vllm/pull/63892) `[ROCm][Perf][DSv4.1] Mono: batch TP4 K2's X8 copies, load its push's peer bases late` | perf,rocm | main | - |
| - | [#63900](https://github.com/vllm-project/vllm/pull/63900) `[KV Offload] Remove unused touch from CachePolicy and OffloadingManager` |  | main | - |
| - | [#63901](https://github.com/vllm-project/vllm/pull/63901) `[Rust Frontend][1/3] Map developer messages to system for templates without the developer role` |  | main | - |
| - | [#63902](https://github.com/vllm-project/vllm/pull/63902) `[Rust Frontend] Add the stateless Responses API (streaming and non-streaming)` |  | main | - |
| - | [#63921](https://github.com/vllm-project/vllm/pull/63921) `[Perf][DSv4.1] Extend the latency_specialized decode on NVIDIA` | infra,nvidia,perf | main | - |
| - | [#63922](https://github.com/vllm-project/vllm/pull/63922) `[Bugfix] Skip more weight formats in the tokenizer/processor snapshot` | bug | main | - |
| - | [#63925](https://github.com/vllm-project/vllm/issues/63925) `[Bug]: Tokenizer/processor snapshot (#60825) downloads model weights it doesn't ignore (`*.ot`, `*.tflite`, ..` |  | ? | - |
| - | [#63927](https://github.com/vllm-project/vllm/pull/63927) `[Perf][KV Offload] Keep offload event metadata out of the cyclic GC` | perf | main | - |
| - | [#63944](https://github.com/vllm-project/vllm/issues/63944) `[Bug]: int8_per_token_head scale-view fill overwrites Gated DeltaNet state in hybrid models` | quant | ? | - |
| - | [#63948](https://github.com/vllm-project/vllm/issues/63948) `[Bug]: KV offload P2P tier: reset_cache() fails an assert on a prefill node with stores waiting for the decode` |  | ? | - |
| - | [#63949](https://github.com/vllm-project/vllm/pull/63949) `[ROCm][CI] Untrusted base builds wait for main's images instead of rebuilding them` | infra,rocm | main | - |
| - | [#63956](https://github.com/vllm-project/vllm/pull/63956) `[Perf][DSA] Token-sharded sparse-MLA prefill under TP; remove indexer row sharding` | infra,nvidia,perf,rocm | main | - |
| - | [#63971](https://github.com/vllm-project/vllm/pull/63971) `[Bugfix][Mooncake] Let decodes reuse divergent local hybrid prefix hits` | bug | main | - |
| - | [#63974](https://github.com/vllm-project/vllm/pull/63974) `[Bugfix][Rust Frontend] Match Python text-part joining for HF templates` | bug | main | - |
| - | [#63977](https://github.com/vllm-project/vllm/pull/63977) `[XPU] upgrade to torch 2.15` | infra,nvidia | main | - |
| - | [#63983](https://github.com/vllm-project/vllm/issues/63983) `[Bug]: FunctionGemma tool parser drops every non-string argument (numbers, booleans, arrays, objects)` | bug | ? | - |
| - | [#63988](https://github.com/vllm-project/vllm/pull/63988) `[Bugfix][KV Offload] Drain unfetched P2P stores before cache reset` | bug,infra,perf | main | - |
| - | [#63992](https://github.com/vllm-project/vllm/pull/63992) `[Bugfix][Tool Parser] Parse bare FunctionGemma arguments and stream them as valid JSON` | bug | main | - |
| - | [#64004](https://github.com/vllm-project/vllm/pull/64004) `[ROCm][Kimi-K3][Perf] Cut gfx942 MXFP4-to-int4 requant time under pure TP` | perf,quant,rocm | main | - |
| - | [#64016](https://github.com/vllm-project/vllm/pull/64016) `[Model] Add Unlimited-OCR-2 DASH attention support` | infra,nvidia | main | - |
| - | [#64028](https://github.com/vllm-project/vllm/pull/64028) `[CI/Build] Publish nightly EFA image to DockerHub` | infra | main | - |
| - | [#64029](https://github.com/vllm-project/vllm/pull/64029) `[ROCm][Perf][Kimi-K3] Specialized decode K2: sentinel all-reduces, pre-AR loads, tagged x rows` | perf,rocm | main | - |
| - | [#64059](https://github.com/vllm-project/vllm/pull/64059) `[Bugfix] Fix DFlash draft acceptance of 0 with FULL CUDA graphs` | bug,nvidia | main | - |
| - | [#64065](https://github.com/vllm-project/vllm/pull/64065) `[Bugfix][XPU] Add record_logical_topk_ready to XPUMLASparseImpl` | bug,infra,nvidia | main | - |
| - | [#64071](https://github.com/vllm-project/vllm/pull/64071) `[EPD] Metadata-only image and video inputs for GLM-5.3-Flash` |  | main | - |
| - | [#64076](https://github.com/vllm-project/vllm/pull/64076) `[Refactor] Remove dead code multiple places` | nvidia,perf | main | - |
| - | [#64077](https://github.com/vllm-project/vllm/pull/64077) `[Perf] Muse Spark Open Specialized Decode: Optimized GB300 Decode (1.5x)` | infra,nvidia,perf | main | - |
| - | [#64094](https://github.com/vllm-project/vllm/pull/64094) `[ROCm][DSv4.1][Perf]  Enable prefix-cache SWA replay on gfx950` | perf,rocm | main | - |
| - | [#64095](https://github.com/vllm-project/vllm/pull/64095) `[Core][MLA] Cross-layer KV cache sharing for attention layers` | perf | main | - |
| - | [#64096](https://github.com/vllm-project/vllm/pull/64096) `[KV Connector][Spec Decode] Support lookahead block hashes in KV connectors` | perf | main | - |
| - | [#64106](https://github.com/vllm-project/vllm/issues/64106) `[Bug]: Kimi-K3 on MI355X: --kv-cache-dtype fp8 silently breaks accuracy (GSM8K 0.975 -> 0.305)` | perf,quant,risk,rocm | ? | - |
| - | [#64110](https://github.com/vllm-project/vllm/pull/64110) `[Qwen4Exp] Remove FlashAttention dependency and standardize QSA naming` |  | main | - |
| - | [#64119](https://github.com/vllm-project/vllm/pull/64119) `[Fast Start] Support ModelOpt CUTLASS block FP8 cache restarts` | infra,nvidia,perf,quant | main | - |
| - | [#64129](https://github.com/vllm-project/vllm/pull/64129) `[Perf][DCP] Sparse indexer: key only significant bits in the DCP top-k merge` | perf | main | - |
| - | [#64132](https://github.com/vllm-project/vllm/pull/64132) `[ROCm][CI] Bake the fast-exit plugin into the test image and fix the ray-compat pin strip` | bug,infra,rocm | main | - |
| - | [#64138](https://github.com/vllm-project/vllm/pull/64138) `[Perf][DSA] Read BF16 logits directly in persistent top-k` | bug,perf | main | - |
| - | [#64164](https://github.com/vllm-project/vllm/pull/64164) `[Bugfix][Metrics] Keep Ray metrics usable without Ray Serve` | bug | main | - |
| - | [#64168](https://github.com/vllm-project/vllm/pull/64168) `[Bugfix] Fix Gemma 4 vision crash with online FP8 quantization` | bug,infra,nvidia,quant | main | - |
| - | [#64174](https://github.com/vllm-project/vllm/pull/64174) `[CI] Enroll four Nightly steps and three AMD mirrors in automatic sharding` | infra,rocm | main | - |
| - | [#64178](https://github.com/vllm-project/vllm/issues/64178) `[Docs] Case 4 equations render as literal LaTeX on published Hybrid KV Cache Manager page` | perf | ? | - |
| - | [#64179](https://github.com/vllm-project/vllm/pull/64179) `[Model] Enable --mm-encoder-tp-mode data for MiMo-V2.6` | infra | main | - |
| - | [#64181](https://github.com/vllm-project/vllm/pull/64181) `[CI] Enroll three standalone AMD steps in automatic sharding` | infra,rocm | main | - |
| - | [#64182](https://github.com/vllm-project/vllm/pull/64182) `[Feature][Quantization] Support AWQ/GPTQ Marlin cache restarts` | infra,perf,quant | main | - |
| - | [#64187](https://github.com/vllm-project/vllm/pull/64187) `[Perf][Model Loader] Make the EP weight filter EPLB-aware` | infra,perf | main | - |
| - | [#64188](https://github.com/vllm-project/vllm/pull/64188) `[Doc] Fix Case 4 math rendering in hybrid KV cache manager` | bug,perf | main | - |
| - | [#64215](https://github.com/vllm-project/vllm/pull/64215) `[Model] Add NVIDIA Canary (nvidia/canary-1b-v2) speech-to-text support` | nvidia | main | - |
| - | [#64218](https://github.com/vllm-project/vllm/pull/64218) `[Rust Frontend] Support return_weight_versions` |  | main | - |
| - | [#64219](https://github.com/vllm-project/vllm/pull/64219) `[Rust Frontend] Report completion_tokens_details only when reasoning tokens are counted` |  | main | - |
| - | [#64220](https://github.com/vllm-project/vllm/pull/64220) `[Rust Frontend] Report prompt logprobs on streamed completions echo like Python` |  | main | - |
| - | [#64222](https://github.com/vllm-project/vllm/pull/64222) `[Rust Frontend] Support --root-path` |  | main | - |
| - | [#64223](https://github.com/vllm-project/vllm/pull/64223) `[Rust Frontend] Support --max-log-len` |  | main | - |
| - | [#64226](https://github.com/vllm-project/vllm/issues/64226) `[Bug]: Rust vllm-bench saves ramp-up runs as fixed-rate results` | perf | ? | - |
| - | [#64232](https://github.com/vllm-project/vllm/pull/64232) `[Rust Frontend] Log one structured access log event per HTTP response` |  | main | - |
| - | [#64241](https://github.com/vllm-project/vllm/pull/64241) `[CI] Pin existing dependency hashes and enforce immutable references` | infra,rocm | main | - |
| - | [#64265](https://github.com/vllm-project/vllm/pull/64265) `[Rust Frontend] Run utility calls to completion when the caller is cancelled` |  | main | - |
| - | [#64269](https://github.com/vllm-project/vllm/pull/64269) `[Pooling] Speed up ColBERT reranking with batched token heads` | perf | main | - |
| - | [#64272](https://github.com/vllm-project/vllm/pull/64272) `[CI] Enroll 13 jobs in automatic sharding` | infra | main | - |
| - | [#64274](https://github.com/vllm-project/vllm/pull/64274) `[Rust Frontend] Reject chat templates for native renderers` |  | main | - |
| - | [#64285](https://github.com/vllm-project/vllm/pull/64285) `[XPU][CI] Enable streaming input e2e test on XPU` | infra,nvidia | main | - |
| - | [#64294](https://github.com/vllm-project/vllm/pull/64294) `[Bugfix][Rust Frontend][ZMQ] Run ZMQ transport I/O on the dedicated runtime` | bug | main | - |
| - | [#64299](https://github.com/vllm-project/vllm/pull/64299) `[Bugfix][KV Offload][P2P] Settle buffered terminal messages after disconnect` | bug | main | - |
| - | [#64300](https://github.com/vllm-project/vllm/pull/64300) `[Bugfix][KV Offload][P2P] Avoid leaking failed IDs for finished requests` | bug | main | - |
| - | [#64308](https://github.com/vllm-project/vllm/pull/64308) `[Rust][Benchmark] Record ramp-up runs in the result JSON and filename` | perf | main | - |
| - | [#64312](https://github.com/vllm-project/vllm/pull/64312) `[Quantization] Support CSF-compressed NVFP4 block scales in ModelOpt` | quant | main | - |
| - | [#64317](https://github.com/vllm-project/vllm/pull/64317) `[ROCm][Perf] Keep 32-bit buffer addressing for per-token-head KV and AITER cross-attention fallback` | perf,quant,rocm | main | - |
| - | [#64327](https://github.com/vllm-project/vllm/issues/64327) `[Bug][HiSparse] GLM-5.3 TP8 B200: unspecified launch failure with MNNVL all-reduce (#61989) once KV spills to ` | bug,nvidia | ? | - |
| - | [#64330](https://github.com/vllm-project/vllm/pull/64330) `[Bugfix][ROCm][MoRIIO] Wait for MoRIIO WRITE mode completions in short chunks` | bug,rocm | main | - |
| - | [#64336](https://github.com/vllm-project/vllm/pull/64336) `[RL][Model Loader] Direct weight reload: write checkpoint tensors into the live model` |  | main | - |
| - | [#64338](https://github.com/vllm-project/vllm/pull/64338) `[Bugfix] Flashinfer attention warmup deadlock under PP>1` | bug,nvidia,risk | main | - |
| - | [#64342](https://github.com/vllm-project/vllm/pull/64342) `[CI] Fix mypy multimodels tests folder` | bug,infra,nvidia | main | - |
| - | [#64352](https://github.com/vllm-project/vllm/pull/64352) `[Model Loader] Direct reload: reset MoE expert padding at begin` | infra,quant | main | - |
| - | [#64355](https://github.com/vllm-project/vllm/pull/64355) `[CI] Enroll five steps and four AMD mirrors in automatic sharding` | infra,rocm | main | - |
| - | [#64357](https://github.com/vllm-project/vllm/pull/64357) `[Model Loader] Run the model-level post-load hook once at the end of every load and reload` | infra | main | - |
| - | [#64368](https://github.com/vllm-project/vllm/pull/64368) `[Spec Decode][ROCm] draft_lm_head_quantization for DSpark drafters` | quant,rocm | main | - |
| - | [#64391](https://github.com/vllm-project/vllm/issues/64391) `[Bug]: Security concern: `/invocations` endpoint is enabled by default and bypasses API key authentication` | bug | ? | - |
| - | [#64396](https://github.com/vllm-project/vllm/pull/64396) `[CI][XPU] Extend batch-invariance tests in Intel CI` | infra,nvidia | main | - |
| - | [#64417](https://github.com/vllm-project/vllm/pull/64417) `[Perf] Skip custom-op dispatch for FlashInfer dense GEMMs in eager` | nvidia,perf,quant | main | - |
| - | [#64431](https://github.com/vllm-project/vllm/issues/64431) `[Bug]: DeepSeek V4.1 Python renderer ignores add_generation_prompt and continue_final_message` |  | ? | - |
| - | [#64433](https://github.com/vllm-project/vllm/issues/64433) `[Bug]: vllm-rs render drops tools for tool_choice "none" and rejects empty content, unlike the Python frontend` |  | ? | - |
| - | [#64442](https://github.com/vllm-project/vllm/pull/64442) `[Perf][DSpark][DSv4.1] Fuse the Markov sampling loop on NVIDIA by inverse CDF` | infra,nvidia,perf | main | - |
| - | [#64444](https://github.com/vllm-project/vllm/pull/64444) `[Bugfix][KV Offload] Publish successful stores to lookup state` | bug | main | - |
| - | [#64448](https://github.com/vllm-project/vllm/pull/64448) `[ROCm][MiniMax-M3.1] NVFP4 indexer: decode CP for DSpark 7` | infra,quant,rocm | main | - |
| - | [#64449](https://github.com/vllm-project/vllm/pull/64449) `[Bugfix][Rust Frontend] Send the DP rendezvous in coordinated-DP INIT` | bug | main | - |
| - | [#64450](https://github.com/vllm-project/vllm/pull/64450) `[Rust Frontend] Let the handshake owner serve a range of DP ranks` |  | bz/rust-dp-rendezvous-init | - |
| - | [#64451](https://github.com/vllm-project/vllm/pull/64451) `[Rust Frontend] Support hybrid and external DP LB in `vllm-rs serve`` |  | bz/rust-handshake-owner-dp-range | - |
| - | [#64457](https://github.com/vllm-project/vllm/pull/64457) `[Bugfix][Core] Keep offline DP ranks' collectives aligned with async scheduling` | bug | main | - |
| - | [#64467](https://github.com/vllm-project/vllm/pull/64467) `[Perf][MoE] Use 32-row tiles in prepare_megamoe_inputs from 1024 tokens` | perf | main | - |
| - | [#64471](https://github.com/vllm-project/vllm/pull/64471) `[Bugfix][Rust Frontend] Accept empty message content like the Python frontend` | bug | main | - |
| - | [#64472](https://github.com/vllm-project/vllm/pull/64472) `[Bugfix][Core] Keep KV cache zeroing for mixed-precision UniformTypeKVCacheSpecs groups` | bug,infra,perf | main | - |
| - | [#64475](https://github.com/vllm-project/vllm/pull/64475) `[MiniMax-M3.1][P/D] NIXL KV-head re-sharding for per-head-contiguous NVFP4 pages` | perf,quant | main | - |
| - | [#64478](https://github.com/vllm-project/vllm/pull/64478) `[XPU][UT] Temporarily Skip CUDA-IPC weight cache test` | nvidia,perf,rocm | main | - |
| - | [#64479](https://github.com/vllm-project/vllm/pull/64479) `[XPU][Perf] Reuse GDN metadata across KV cache groups on XPU` | nvidia,perf | main | - |
| - | [#64487](https://github.com/vllm-project/vllm/pull/64487) `[MM] Support mm_device_do_normalize for gemma3.` |  | main | - |
| - | [#64492](https://github.com/vllm-project/vllm/pull/64492) `[Bugfix][Rust Frontend] Accept assistant turns without content like Python` | bug | main | - |
| - | [#64494](https://github.com/vllm-project/vllm/pull/64494) `[Kernel] Add size-gated PDL to silu_and_mul_nvfp4_quant` | perf,quant | main | - |
| - | [#64495](https://github.com/vllm-project/vllm/pull/64495) `[Bugfix] Preserve multimodal processor-cache hits during request eviction` | bug,perf | main | - |
| - | [#64509](https://github.com/vllm-project/vllm/pull/64509) `[Perf][Qwen3.5] (NVIDIA-only) Fused norm+quant and gate+quant` | infra,nvidia,perf,quant | main | - |
| - | [#64510](https://github.com/vllm-project/vllm/pull/64510) `[Perf] Enable native small-head kernels in SM90 sparse FlashMLA` | nvidia,perf | main | - |
| - | [#64512](https://github.com/vllm-project/vllm/pull/64512) `[Rust Frontend] Export UMBP connector transfer metrics like Python` |  | main | - |
| - | [#64513](https://github.com/vllm-project/vllm/pull/64513) `[Rust Frontend] Report the generate response envelope like Python` |  | main | - |
| - | [#64514](https://github.com/vllm-project/vllm/pull/64514) `[Rust Frontend] Support VLLM_SKIP_MODEL_NAME_VALIDATION` |  | main | - |
| - | [#64517](https://github.com/vllm-project/vllm/issues/64517) `[Bug]: Muse, MiniCPM5 and Poolside V1 tool parsers JSON-decode string parameters not declared as plain "type":` |  | ? | - |
| - | [#64518](https://github.com/vllm-project/vllm/pull/64518) `[Bugfix][Tool Parser] Keep raw text for string parameters with union/enum/$ref schemas (Muse, MiniCPM5, Poolsi` | bug | main | - |
| - | [#64526](https://github.com/vllm-project/vllm/pull/64526) `[Rust Frontend] Support return_prompt_text` |  | main | - |
| - | [#64529](https://github.com/vllm-project/vllm/pull/64529) `[CI] Bump Transformers version to 5.22.0` | infra | main | - |
| - | [#64538](https://github.com/vllm-project/vllm/issues/64538) `[Bug]: Rust vllm-bench silently ignores --dataset-path with synthetic datasets (benchmarks random prompts inst` | bug,perf,risk | ? | - |
| - | [#64546](https://github.com/vllm-project/vllm/issues/64546) `Muse tool parser JSON-decodes Optional[str] parameters, so "10001" becomes 10001` |  | ? | - |
| - | [#64551](https://github.com/vllm-project/vllm/pull/64551) `[Bugfix][Rust Frontend] Reject --dataset-path with synthetic vllm-bench datasets` | bug,perf | main | - |
| - | [#64553](https://github.com/vllm-project/vllm/pull/64553) `[Kernel] Add CUDA routing kernel for Muse Spark Open` | infra,nvidia,perf | main | - |
| - | [#64557](https://github.com/vllm-project/vllm/pull/64557) `[Bugfix][Rust Frontend] Count tool call deltas as generated tokens in vllm-bench openai-responses` | bug,perf | main | - |
| - | [#64558](https://github.com/vllm-project/vllm/pull/64558) `[Bugfix][KV Offload] Count each key once per request toward store_threshold` | bug | main | - |
| - | [#64559](https://github.com/vllm-project/vllm/pull/64559) `[HiSparse] Remove dead code, unused custom-op arguments, and a stale connector check` | perf | main | - |
| - | [#64561](https://github.com/vllm-project/vllm/pull/64561) `[CI] Shard Spec Decode AL MTP automatically and split its Gemma4 test by dataset` | infra | main | - |
| - | [#64562](https://github.com/vllm-project/vllm/pull/64562) `[HiSparse][Core] Move HiSparse hot-page stride alignment into its spec` | perf | main | - |
| - | [#64567](https://github.com/vllm-project/vllm/pull/64567) `[ROCm][Bugfix] Skip AITER tuned GEMM when M*N >= 2^31 on gfx950` | bug,perf,rocm | main | - |
| - | [#64569](https://github.com/vllm-project/vllm/pull/64569) `[CI] Enroll 6 steps and 10 AMD mirrors in automatic sharding` | infra,rocm | main | - |
| - | [#64570](https://github.com/vllm-project/vllm/issues/64570) `[Bug]: EngineCore dies with KeyError in punica `convert_mapping` when a LoRA name is unloaded and loaded again` |  | ? | - |
| - | [#64575](https://github.com/vllm-project/vllm/pull/64575) `[Frontend] Reject Anthropic-defined tools by type in /v1/messages` |  | main | - |
| - | [#64576](https://github.com/vllm-project/vllm/pull/64576) `[CI][MoE] Start every MoE kernel test file from a clean GPU state` | infra,perf | main | - |
| - | [#64577](https://github.com/vllm-project/vllm/pull/64577) `[ROCm][CI] Prebuild mamba-ssm and causal-conv1d into the CI test image` | infra,rocm | main | - |
| - | [#64579](https://github.com/vllm-project/vllm/pull/64579) `[NIXL] Bump NIXL version to 1.5.2` | infra | main | - |
| - | [#64580](https://github.com/vllm-project/vllm/pull/64580) `[Kernel][DSA] Restore FP32 indexer MQA logits for non-DeepSeek models and add `indexer_logits_dtype`` | infra,perf | main | - |
| - | [#64583](https://github.com/vllm-project/vllm/pull/64583) `[Bugfix][Kimi-K3] Fall back from the latent-MoE tail fusion under sleep mode` | bug,perf | main | - |
| - | [#64585](https://github.com/vllm-project/vllm/pull/64585) `[NIXL][CI/Build] Bump NIXL to 1.5.2 and drop source build for Rubin` | infra,nvidia | main | - |
| - | [#64589](https://github.com/vllm-project/vllm/pull/64589) `[Docs] Add DeepSeek-V4.1-Flash MI325X AgentX preset` | infra,rocm | main | - |
| - | [#64590](https://github.com/vllm-project/vllm/pull/64590) `[CI] Enroll the remaining LM Eval jobs in automatic sharding (30 jobs)` | infra | main | - |
| - | [#64591](https://github.com/vllm-project/vllm/pull/64591) `[CI] Enroll the remaining Kernels jobs in automatic sharding (30 jobs)` | infra,perf | main | - |
| - | [#64592](https://github.com/vllm-project/vllm/pull/64592) `[CI] Enroll the remaining Spec Decode jobs in automatic sharding (21 jobs)` | infra | main | - |
| - | [#64593](https://github.com/vllm-project/vllm/pull/64593) `[CI] Enroll the remaining Distributed, EP and fault-tolerance jobs in automatic sharding (25 jobs)` | infra | main | - |
| - | [#64594](https://github.com/vllm-project/vllm/pull/64594) `[CI] Enroll the remaining Models (basic, multimodal, language) jobs in automatic sharding (22 jobs)` | infra | main | - |
| - | [#64595](https://github.com/vllm-project/vllm/pull/64595) `[CI] Enroll the remaining Compile, PyTorch, CUDA and ABI jobs in automatic sharding (29 jobs)` | infra,nvidia | main | - |
| - | [#64596](https://github.com/vllm-project/vllm/pull/64596) `[CI] Enroll the remaining Misc and Samplers jobs in automatic sharding (17 jobs)` | infra | main | - |
| - | [#64597](https://github.com/vllm-project/vllm/pull/64597) `[CI] Enroll the remaining Engine and Basic Correctness jobs in automatic sharding (17 jobs)` | bug,infra | main | - |
| - | [#64598](https://github.com/vllm-project/vllm/pull/64598) `[CI] Enroll the remaining quantization and benchmarks jobs in automatic sharding (4 jobs)` | infra,perf,quant | main | - |
| - | [#64599](https://github.com/vllm-project/vllm/pull/64599) `[CI] Enroll the remaining Rust frontend and OpenAI API correctness jobs in automatic sharding (6 jobs)` | bug,infra | main | - |
| - | [#64602](https://github.com/vllm-project/vllm/pull/64602) `[CI] Remove the retired A100 queue's steps; keep their live AMD mirrors standalone` | infra,rocm | main | - |
| - | [#64606](https://github.com/vllm-project/vllm/pull/64606) `[CI] Enroll 8 jobs in automatic sharding` | infra | main | - |
| - | [#64607](https://github.com/vllm-project/vllm/pull/64607) `[Recipe] Qwen3.5-397B-A17B: add the B200 NVFP4 TP2 agentic preset` | infra,nvidia,quant | main | - |
| - | [#64610](https://github.com/vllm-project/vllm/pull/64610) `[ROCm][CI] Update ROCm AITER nightly staging index` | infra,rocm | main | - |
| - | [#64612](https://github.com/vllm-project/vllm/pull/64612) `[GLM5.3 Perf] Switching dlfash fp8 kv cache draft model, 2.85 GB memory saved per rank` | perf,quant | main | - |
| - | [#64614](https://github.com/vllm-project/vllm/pull/64614) `[Bugfix][ROCm] Use 64-bit row offsets in the RDNA hybrid W4A16 GEMM` | bug,quant,rocm | main | - |
| - | [#64615](https://github.com/vllm-project/vllm/pull/64615) `[Bugfix][Frontend] Leave GLM-4.7 array and object tool arguments unpinned` | bug | main | - |
| - | [#64616](https://github.com/vllm-project/vllm/pull/64616) `[Bugfix][LoRA] Fix KeyError crash when a LoRA name is reloaded with requests in flight` | bug | main | - |
| - | [#64617](https://github.com/vllm-project/vllm/pull/64617) `[Recipe] Kimi-K3: add B300 AgentX aggregated Mooncake preset` | infra | main | - |
| - | [#64618](https://github.com/vllm-project/vllm/pull/64618) `[Multimodal] Cache PyNvVideoCodec decoder caps` | perf | main | - |
| - | [#64619](https://github.com/vllm-project/vllm/pull/64619) `[CI][Kimi-K3] Add enable_adaptive_verification to the KDA checkpoint test stub` | infra | main | - |
| - | [#64626](https://github.com/vllm-project/vllm/pull/64626) `[Bugfix][Rust Frontend] Don't count content-free chunks as streamed outputs in vllm-bench chat` | bug,perf | main | - |
| - | [#64630](https://github.com/vllm-project/vllm/pull/64630) `[Bugfix][SleepMode] Exact-size, reusable pinned CPU backup for level-1 sleep` | bug,infra | main | - |
| - | [#64633](https://github.com/vllm-project/vllm/pull/64633) `[XPU] Use GitHub release page index URL for vllm-xpu-kernels` | infra,nvidia,perf | main | - |
| - | [#64635](https://github.com/vllm-project/vllm/pull/64635) `[CI] Continue automatic PyTorch Fullgraph sharding` | infra | main | - |
| - | [#64638](https://github.com/vllm-project/vllm/pull/64638) `[Perf] Fuse all-gather and norm for Muse Spark hybrid MoE` | nvidia,perf | main | - |
| - | [#64639](https://github.com/vllm-project/vllm/issues/64639) `[Bug]: 0.30.0 kimi-k3 PD分离  使用MLA-Block5草稿模型版本接收率基本为0` | bug | ? | - |
| - | [#64644](https://github.com/vllm-project/vllm/pull/64644) `[CI] Fix mypy errors in test_glm5next.py` | bug,infra | main | - |
| - | [#64650](https://github.com/vllm-project/vllm/pull/64650) `[Perf][Qwen3.8] Add SM103 skinny GEMM plans for TP=1` | nvidia,perf | main | - |
| - | [#64651](https://github.com/vllm-project/vllm/pull/64651) `[XPU][CI] add EPD test into intel CI` | infra,nvidia | main | - |
| - | [#64653](https://github.com/vllm-project/vllm/pull/64653) `[Perf][LoRA][MoE] Use the shrink/expand kernels for MoE-LoRA batches of up to 64 tokens` | perf | main | - |
| - | [#64655](https://github.com/vllm-project/vllm/pull/64655) `[CI][ROCm] Check skinny-GEMM guard dispatch without torch.profiler` | infra,rocm | main | - |
| - | [#64656](https://github.com/vllm-project/vllm/pull/64656) `[Test][UMBP] Restore a Mamba2 hybrid end to end through UMBP` | infra,rocm | main | - |
| - | [#64657](https://github.com/vllm-project/vllm/pull/64657) `[Test][UMBP] Cover TP=2 restore through per-rank MORI pools` | infra,rocm | main | - |
| - | [#64658](https://github.com/vllm-project/vllm/pull/64658) `[Test][UMBP] Cover end-to-end restore while the embedded DRAM pool is evicting` | infra,rocm | main | - |
| - | [#64659](https://github.com/vllm-project/vllm/pull/64659) `[Perf][MiniMax-M3] Sequence parallelism and GEMM-RS for TP + MegaMoE` | perf | main | - |
| - | [#64665](https://github.com/vllm-project/vllm/pull/64665) `[Doc] Kimi-K3: move the GB300 AgentX presets to the Oct 26 points with KV-balanced decode` | infra,nvidia | main | - |
| - | [#64666](https://github.com/vllm-project/vllm/pull/64666) `[Docs] Fix dead links to moved llm-d, Dynamo, TPU, Ray and Tensorizer pages` | bug | main | - |
| - | [#64673](https://github.com/vllm-project/vllm/pull/64673) `[Perf][Parser] Skip tool-argument conversions after a replaced value` | perf | main | - |
| - | [#64674](https://github.com/vllm-project/vllm/pull/64674) `[Perf][Frontend] Decode streamed custom-tool input incrementally` | perf | main | - |
| - | [#64675](https://github.com/vllm-project/vllm/pull/64675) `[Bugfix][Parser] Parse closed Qwen3 tool parameters once while streaming` | bug | main | - |
| - | [#64677](https://github.com/vllm-project/vllm/pull/64677) `[Bugfix][UMBP] Copy every KV cache layout's per-head runs` | bug,infra,perf,rocm | main | - |
| - | [#64681](https://github.com/vllm-project/vllm/pull/64681) `[Bugfix][LoRA] Give Mamba-1 LoRA layers every row of the batch` | bug,infra | main | - |
| - | [#64686](https://github.com/vllm-project/vllm/pull/64686) `[Bugfix][KV Offload][P2P] Clean up both roles on request finish` | bug | main | - |
| - | [#64689](https://github.com/vllm-project/vllm/pull/64689) `[Feature][MoE] Allow a shared routed-expert row restorer` |  | main | - |
| - | [#64691](https://github.com/vllm-project/vllm/pull/64691) `[RL] NCCL weight transfer: release cached memory after a weight update` | infra,nvidia | main | - |
| - | [#64692](https://github.com/vllm-project/vllm/pull/64692) `[Model Loader] Refill weight-derived tensors in place on every post-load rerun` | infra,nvidia,quant | main | - |
| - | [#64695](https://github.com/vllm-project/vllm/pull/64695) `[Rust Frontend] Generate through an `Llm` trait` |  | main | - |
| - | [#64697](https://github.com/vllm-project/vllm/pull/64697) `[Rust Frontend] Support --skip-tokenizer-init` |  | main | - |
| - | [#64708](https://github.com/vllm-project/vllm/pull/64708) `[ROCm][CI] Drop LD_PRELOAD from the subprocess env in test_amd_ci_fast_exit` | infra,rocm | main | - |
| - | [#64723](https://github.com/vllm-project/vllm/pull/64723) `[Perf][Qwen3.5] (NVIDIA path) Fused AR+norm+quant` | infra,nvidia,perf,quant | main | - |
| - | [#64727](https://github.com/vllm-project/vllm/pull/64727) `[ROCm][CI] Fix AITER MXFP4 padding tests failing instead of skipping on MI300` | bug,infra,quant,rocm | main | - |
| - | [#64728](https://github.com/vllm-project/vllm/pull/64728) `[Bugfix] Stop offline beam search at the context limit` | bug | main | - |
| - | [#64733](https://github.com/vllm-project/vllm/pull/64733) `[MiniMax-M3.1][PP] m31-pp-opt: NIXL pull from PP prefill stages and the Q8KV4 prefill workspace on SM10x` |  | m31-pp-opt | - |
| - | [#64734](https://github.com/vllm-project/vllm/pull/64734) `[ROCm][CI] Raise the MI355 DeepSeek-V3.2 GSM8K startup wait to 1800s` | infra,rocm | main | - |
| - | [#64740](https://github.com/vllm-project/vllm/pull/64740) `[ROCm][CI] Run MI355 MoE Kernels on a full MI355 instead of DPX` | infra,perf,rocm | main | - |
| - | [#64743](https://github.com/vllm-project/vllm/pull/64743) `[Bugfix][Mistral] Carry token ids in stream state for byte-fallback tokens` | bug,perf | main | - |
| - | [#64751](https://github.com/vllm-project/vllm/pull/64751) `[Bugfix][Spec Decode] Honor draft moe/attention backend overrides for MRV2 standalone draft model` | bug | main | - |
| - | [#64757](https://github.com/vllm-project/vllm/pull/64757) `[Bugfix][Frontend] Report prompt_tokens_details in batched chat completions` | bug | main | - |
| - | [#64758](https://github.com/vllm-project/vllm/issues/64758) `[Bug]: Kimi-K3 outputs turn into `!!!!` (token 0) streams under load (FlashKDA spreads one NaN across requests` | bug,nvidia,risk | ? | - |
| - | [#64759](https://github.com/vllm-project/vllm/pull/64759) `[Bugfix][Kimi-K3] Pin FlashKDA and FlashMLA with NaN fixes` | bug,infra,nvidia,risk | main | - |
| - | [#64760](https://github.com/vllm-project/vllm/pull/64760) `[GLM 5.3 Perf] Sorted-A TMA for FP8 MoE down projection on H200, 6.0%~ 7.6% E2E Throughput Improvement` | nvidia,perf,quant | main | - |
| - | [#64762](https://github.com/vllm-project/vllm/pull/64762) `[CI] Use test models from the vllm-project Hub org` | infra,nvidia | main | - |
| - | [#64763](https://github.com/vllm-project/vllm/pull/64763) `[ROCm][HY4] Use breakable graphs without torch.compile` | infra,rocm | main | - |
| - | [#64778](https://github.com/vllm-project/vllm/issues/64778) `[Bug]: Non-streaming `/v1/chat/completions/derender` and `/v1/completions/derender` report `usage.prompt_token` | bug | ? | - |
| - | [#64779](https://github.com/vllm-project/vllm/pull/64779) `[Deps] Upgrade to huggingface_hub 2` | infra,rocm | main | - |
| - | [#64781](https://github.com/vllm-project/vllm/pull/64781) `[Bugfix] Read generate usage.prompt_tokens in non-streaming derender` | bug | main | - |
| - | [#64782](https://github.com/vllm-project/vllm/pull/64782) `[Bugfix][CUDA] Use CUDA memory accounting for integrated GPUs on WSL` | bug,nvidia | main | - |
| - | [#64788](https://github.com/vllm-project/vllm/pull/64788) `[CI] Enroll Spec Decode AL DSpark and UMBP Connector Integration in automatic sharding` | infra | main | - |
| - | [#64792](https://github.com/vllm-project/vllm/pull/64792) `[Docs][ROCm] Mistral Large 4 recipe: adds TP4 and lowest-latency presets ` | infra,perf,rocm | main | - |
| - | [#64797](https://github.com/vllm-project/vllm/pull/64797) `[Recipes Tool][CPU] Remove obsolete TP/DP NUMA binding workaround` |  | main | - |
| - | [#64802](https://github.com/vllm-project/vllm/pull/64802) `[Bugfix] Update humming-kernels version to 0.1.19` | bug,infra,perf | main | - |
| - | [#64804](https://github.com/vllm-project/vllm/pull/64804) `[Docs][ROCm] Add DeepSeek-V4.1-Flash MI355X TP8 concurrency-1 AgentX preset` | infra,rocm | main | - |
| - | [#64805](https://github.com/vllm-project/vllm/pull/64805) `[Docs][ROCm] Add MiniMax-M3.1-Flash MI355X TP4 AgentX preset` | infra,rocm | main | - |
| - | [#64806](https://github.com/vllm-project/vllm/pull/64806) `[Bugfix][Attention] Bound SM100 decode indexer logits with query-row chunks` | bug,nvidia,perf | main | - |
| - | [#64814](https://github.com/vllm-project/vllm/issues/64814) `[Bug]: Withdrawn` |  | ? | - |
| - | [#64815](https://github.com/vllm-project/vllm/pull/64815) `[Perf][MXFP8] Keep DeepSeek-V4.1 fusions on the torch._scaled_mm kernel` | infra,nvidia,perf,quant | main | - |
| - | [#64816](https://github.com/vllm-project/vllm/pull/64816) `[Perf][DSv4.1] Vectorize first-layer HC expansion copy` | perf | main | - |
| - | [#64819](https://github.com/vllm-project/vllm/pull/64819) `[Bugfix][KV Offload][P2P] Disconnect a peer whose registration fails` | bug | main | - |
| - | [#64820](https://github.com/vllm-project/vllm/pull/64820) `[Kernel] Qwen4Exp: compute HyperConnection and PLE gate row offsets in int64` | infra,perf | main | - |
| - | [#64821](https://github.com/vllm-project/vllm/pull/64821) `[Doc] MiniMax-M3.1-Flash: add GB300 InferenceX AgentX presets` | infra,nvidia | main | - |
| - | [#64826](https://github.com/vllm-project/vllm/pull/64826) `[CI] Run Distributed Features examples once and shard its pytest commands` | infra | main | - |
| - | [#64830](https://github.com/vllm-project/vllm/pull/64830) `[Config] Move V2-only checks into V1 model runner unsupported features` |  | main | - |
| - | [#64831](https://github.com/vllm-project/vllm/pull/64831) `[Bugfix][Benchmark] Fix bench mm-processor crash with HF datasets` | bug,perf | main | - |
| - | [#64833](https://github.com/vllm-project/vllm/pull/64833) `[ROCm][Step5] Require CDNA3 or newer for the sparse attention layers` | rocm | main | - |
| - | [#64836](https://github.com/vllm-project/vllm/pull/64836) `[ROCm][Step5] Exercise the real CSA decode and engine paths in tests` | rocm | main | - |
| - | [#64838](https://github.com/vllm-project/vllm/pull/64838) `[Mamba] Postpone --mamba-cache-mode removal to v0.34.0` | perf | main | - |
| - | [#64839](https://github.com/vllm-project/vllm/pull/64839) `[ROCm][CI] Add a build.sh prebuild mode for maintainer-approved stack builds` | infra,rocm | main | - |
| - | [#64841](https://github.com/vllm-project/vllm/pull/64841) `[ModelRunner V2] Reduce peak memory of chunked prompt logprobs` |  | main | - |
| - | [#64845](https://github.com/vllm-project/vllm/issues/64845) `[Bug]: EmbeddingGemma 2 rejects `dimensions` by default although the model supports Matryoshka (128/256/512/76` |  | ? | - |
| - | [#64852](https://github.com/vllm-project/vllm/pull/64852) `[Perf][MiniMax-M3] (NVIDIA-only) Fused norm+quant MXFP8` | nvidia,perf,quant | main | - |
| - | [#64856](https://github.com/vllm-project/vllm/pull/64856) `[Bugfix][MiniMax-M3.1] Reserve MSA Q8KV4 prefill workspace` | bug,nvidia | main | - |
| - | [#64869](https://github.com/vllm-project/vllm/pull/64869) `[Misc] Allow weights mapper to transform weights` |  | main | - |
| - | [#64880](https://github.com/vllm-project/vllm/pull/64880) `[Bugfix][LoRA] Apply DeepSeek-V4 compressor and wo_a adapters` | bug,nvidia | main | - |
| - | [#64885](https://github.com/vllm-project/vllm/pull/64885) `[Bugfix][Pooling] Enable Matryoshka dimensions for EmbeddingGemma 2` | bug,infra | main | - |
| - | [#64886](https://github.com/vllm-project/vllm/pull/64886) `[Bugfix][ROCm][Kimi-K3] Refresh derived weight copies after in-place weight writes` | bug,rocm | main | - |
| - | [#64898](https://github.com/vllm-project/vllm/pull/64898) `[Perf][Qwen4Exp] Fuse HyperConnection up projection and gate mix for long prefills` | infra,perf | main | - |
| - | [#64907](https://github.com/vllm-project/vllm/issues/64907) `[Feature]: Batch-invariant Qwen GDN with prefix caching and MTP` | perf | ? | - |
| - | [#64909](https://github.com/vllm-project/vllm/pull/64909) `[Doc] MiniMax-M3.1-Flash: update the GB200 AgentX presets` | infra,nvidia | main | - |
| - | [#64910](https://github.com/vllm-project/vllm/pull/64910) `[Doc] MiniMax-M3.1-Flash: update the GB300 AgentX presets` | infra,nvidia | main | - |
| - | [#64914](https://github.com/vllm-project/vllm/pull/64914) `[MRV2] Cap torch.topk rows in chunked prompt logprobs` |  | main | - |
| - | [#64916](https://github.com/vllm-project/vllm/pull/64916) `[Spec Decode][Perf] Fuse DFlash2 candidate edge scoring into a Triton kernel` | perf,rocm | main | - |
| - | [#64920](https://github.com/vllm-project/vllm/pull/64920) `[Model] Muse Glimmer: reuse in-tree RMSNorm / GemmaRMSNorm` |  | main | - |
| - | [#64935](https://github.com/vllm-project/vllm/pull/64935) `[Bugfix][Frontend] Report reasoning tokens in batched chat completions` | bug,infra | main | - |
| - | [#64937](https://github.com/vllm-project/vllm/pull/64937) `[Bugfix][Benchmark] Count reasoning_content deltas as streamed outputs in chat` | bug,perf | main | - |
| - | [#64939](https://github.com/vllm-project/vllm/issues/64939) `[Bug]: Rust vllm-bench ignores --output-len for the sharegpt and hf datasets` | perf | ? | - |
| - | [#64944](https://github.com/vllm-project/vllm/pull/64944) `[Model] Nemotron-3.5-Transcribe: pack the audio tower's valid frames for MMEncoderAttention` |  | main | - |
| - | [#64946](https://github.com/vllm-project/vllm/pull/64946) `[Rust][Benchmark] Map --output-len to the sharegpt and hf datasets` | perf | main | - |
| - | [#64953](https://github.com/vllm-project/vllm/issues/64953) `[Bug]:  `seed=-1` passes config validation and kills engine init inside `np.random.seed` ("Seed must be betwee` | bug | ? | - |
| - | [#64955](https://github.com/vllm-project/vllm/pull/64955) `[Perf][MoE] Fuse padding skipping in grouped and Muse prepared routing` | infra,perf | main | - |
| - | [#64958](https://github.com/vllm-project/vllm/pull/64958) `[ROCm][Kimi-K3] Support Mooncake consumers with specialized decode` | rocm | main | - |
| - | [#64971](https://github.com/vllm-project/vllm/pull/64971) `[Bugfix][Frontend] Fix tool_reference results on DeepSeek V4.1 and /v1/messages` | bug | main | - |
| - | [#64974](https://github.com/vllm-project/vllm/pull/64974) `[Refactor][DSv4.1] Remove duplicated code` | nvidia | main | - |
| - | [#64984](https://github.com/vllm-project/vllm/pull/64984) `[Bugfix][MM] Keep FlashInfer cu_seqlens halves aligned in Qwen3-VL encoder CUDA graph replay` | bug,nvidia | main | - |
| - | [#64985](https://github.com/vllm-project/vllm/issues/64985) `[Bug]: KV-sharing fast prefill hangs under async scheduling (non-blocking D2H copy of query_start_loc_cpu)` | bug | ? | - |
| - | [#64986](https://github.com/vllm-project/vllm/pull/64986) `[Bugfix][Attention] Fix KV-sharing fast prefill hang from unsynchronized host offsets` | bug | main | - |
| - | [#64989](https://github.com/vllm-project/vllm/pull/64989) `[Bugfix][HiSparse] Release temporary device KV bindings after graph profiling` | bug,infra,nvidia | main | - |
| - | [#64993](https://github.com/vllm-project/vllm/pull/64993) `[Test][KV Offload] Update stale partial-tail scheduler expectations` |  | main | - |
| - | [#64999](https://github.com/vllm-project/vllm/pull/64999) `[Bugfix][GDN] Restore in_proj_ba overlap on CUDA` | bug,infra,nvidia,perf | main | - |
| - | [#65000](https://github.com/vllm-project/vllm/pull/65000) `[Kernel] Batch invariance: combine the NVFP4 linear kernel overrides (follow-up to #62192)` | perf,quant | main | - |
| - | [#65001](https://github.com/vllm-project/vllm/pull/65001) `[Rust Frontend] Support --log-error-stack` |  | main | - |
| - | [#65005](https://github.com/vllm-project/vllm/pull/65005) `[Docs][Model] Add Parakeet TDT transcription support via plugin` |  | main | - |
| - | [#65008](https://github.com/vllm-project/vllm/pull/65008) `[CI] Lower gpu_memory_utilization in test_gemma4_lora` | infra | main | - |
| - | [#65030](https://github.com/vllm-project/vllm/pull/65030) `[Perf][Model] DeepSeek V4/V4.1 Vision: encode a call's images in packed passes` | perf | main | - |
| - | [#65033](https://github.com/vllm-project/vllm/pull/65033) `[Mamba][MRV2] Plan Triton ReplaySSM decode on the GPU and support Model Runner V2` | rocm | main | - |
| - | [#65035](https://github.com/vllm-project/vllm/issues/65035) `[Bug]: Anthropic Messages stream reports the whole prompt as input_tokens in message_start` | rocm | ? | - |
| - | [#65036](https://github.com/vllm-project/vllm/pull/65036) `[Bugfix][Frontend] Report the prompt cache split in the first streamed usage` | bug,perf | main | - |
| - | [#65041](https://github.com/vllm-project/vllm/pull/65041) `[Bugfix][MRV2][Spec Decode] Keep P/D prompt tails on FULL graphs with adaptive verification` | bug,nvidia | main | - |
| - | [#65044](https://github.com/vllm-project/vllm/pull/65044) `[Doc] Move the Ascend content of the recipes to vllm-ascend overlays` | infra | main | - |
| - | [#65045](https://github.com/vllm-project/vllm/pull/65045) `[Model] Remove redundant Muse Spark configuration overrides` |  | main | - |
| - | [#65046](https://github.com/vllm-project/vllm/pull/65046) `[Bugfix][DSv4] Skip empty compressed indexer prefill chunks` | bug | main | - |
| - | [#65047](https://github.com/vllm-project/vllm/pull/65047) `[XPU] update triton-xpu 3.9.0 shim layer` | infra,nvidia,rocm | main | - |
| - | [#65050](https://github.com/vllm-project/vllm/pull/65050) `[Kernel] Enable CuteDSL GDN prefill on SM110` | nvidia,perf | main | - |
| - | [#65051](https://github.com/vllm-project/vllm/pull/65051) `[Bugfix][LoRA] Skip MoE-LoRA shrink/expand when no LoRA is active` | bug | main | - |
| - | [#65055](https://github.com/vllm-project/vllm/issues/65055) `[Performance]: MoE top-k gating PDL launch (#59737) slows CUDA graph replay on pre-Hopper GPUs` | nvidia,perf | ? | - |
| - | [#65059](https://github.com/vllm-project/vllm/pull/65059) `[Bugfix][Kernel] Only set PDL launch attr for MoE top-k gating on SM90+` | bug,nvidia,perf | main | - |
| - | [#65060](https://github.com/vllm-project/vllm/pull/65060) `[Bugfix][KV Connector] Fix KV role detection for MultiConnector with nested connectors` | bug | main | - |
| - | [#65071](https://github.com/vllm-project/vllm/issues/65071) `[Bug]: CustomDataset converts numeric-string prompts to integers before tokenization` |  | ? | - |
| - | [#65075](https://github.com/vllm-project/vllm/issues/65075) `[Bug]: Bi-encoder scoring token limits fail with MistralTokenizer` |  | ? | - |
| - | [#65076](https://github.com/vllm-project/vllm/pull/65076) `[KVConnector][Mooncake] Add per-GPU device names for MooncakeStoreConnector` |  | main | - |
| - | [#65080](https://github.com/vllm-project/vllm/pull/65080) `[Bugfix][ROCm] Muse Spark: merge the two process_weights_after_loading hooks` | bug,rocm | main | - |
| - | [#65081](https://github.com/vllm-project/vllm/issues/65081) `[CI Failure]: pre-commit mypy on main - process_weights_after_loading redefined in vllm/models/muse_spark/amd/` | infra,rocm | ? | - |
| - | [#65083](https://github.com/vllm-project/vllm/pull/65083) `[Bugfix][Benchmark] Keep numeric-string prompts as strings in CustomDataset` | bug,perf | main | - |
| - | [#65087](https://github.com/vllm-project/vllm/pull/65087) `[ROCm][Perf][MiniMax-M3.1] Four-wave decode top-k for the NVFP4 indexer` | perf,quant,rocm | main | - |
| - | [#65088](https://github.com/vllm-project/vllm/pull/65088) `[Bugfix][Model] Fix Ling3 SwiGLU clamping` | bug | main | - |
| - | [#65091](https://github.com/vllm-project/vllm/pull/65091) `[Bugfix][CI/Build] Use compilation config to control breakable cuda graph` | bug,infra,nvidia | main | - |
| - | [#65093](https://github.com/vllm-project/vllm/pull/65093) `[Bugfix][Pooling] Fix scoring token limits with MistralTokenizer` | bug | main | - |
| - | [#65095](https://github.com/vllm-project/vllm/issues/65095) `[Bug]: The message API doesn't support min_tokens for now` | bug | ? | - |
| - | [#65097](https://github.com/vllm-project/vllm/pull/65097) `[XPU][CI]Increase memory for Quantization test and deselect timeout case in v1/shutdown` | infra,nvidia,quant | main | - |
| - | [#65100](https://github.com/vllm-project/vllm/pull/65100) `[Perf][Spec Decode] Skip vocab blocks with no target token in the resample kernel` | perf | main | - |
| - | [#65118](https://github.com/vllm-project/vllm/pull/65118) `[Bugfix][Mistral] Keep skip_special_tokens for MistralTokenizer in Responses / legacy parser path` | bug | main | - |
| - | [#65124](https://github.com/vllm-project/vllm/pull/65124) `[Bugfix][KV Offload][P2P] Abort inbound loads when draining for a cache reset` | bug,perf | main | - |
| - | [#65125](https://github.com/vllm-project/vllm/pull/65125) `[Bugfix][Spec Decode] Muse Spark DSpark: initialize _context_kv_proj so the draft loads` | bug | main | - |
| - | [#65127](https://github.com/vllm-project/vllm/pull/65127) `[Bugfix] Validate global model seed range` | bug | main | - |
| - | [#65140](https://github.com/vllm-project/vllm/pull/65140) `[ROCm][CI] Fix Muse Spark RoPE cache leak between tests` | bug,infra,perf,rocm | main | - |
| - | [#65144](https://github.com/vllm-project/vllm/pull/65144) `[Bugfix][Rust Frontend] Include error sources in HTTP 400 messages` | bug | main | - |
| - | [#65152](https://github.com/vllm-project/vllm/pull/65152) `[Kernel] Enable Step5 SwiGLU in TRTLLM MoE` | nvidia,perf,quant | main | - |
| - | [#65153](https://github.com/vllm-project/vllm/pull/65153) `[Bugfix][Step5] Size the KV block to the CSA tail ring` | bug | main | - |
| - | [#65157](https://github.com/vllm-project/vllm/pull/65157) `[Docs] Fix accidental cross-references in docstrings` | bug,infra | main | - |
| - | [#65160](https://github.com/vllm-project/vllm/pull/65160) `[Feature][MooncakeStore] Add automatic deployment cache prefixes` | infra,perf | main | - |
| - | [#65162](https://github.com/vllm-project/vllm/pull/65162) `[Build] Fetch `triton_kernels` from a source tarball instead of a `git clone` (avoiding +400 MB pull)` | infra | main | - |
| - | [#65166](https://github.com/vllm-project/vllm/pull/65166) `[Perf][Frontend] Validate plain embedding inputs before the full union` | perf | main | - |
| - | [#65171](https://github.com/vllm-project/vllm/issues/65171) `[Bug][Transformers Backend] HunyuanOCR fails with attention head dimension mismatch (128 vs 192)` |  | ? | - |
| - | [#65174](https://github.com/vllm-project/vllm/pull/65174) `[Bugfix][Kimi-VL] Set pad_token_id explicitly in KimiVLConfig` | bug | main | - |
| - | [#65175](https://github.com/vllm-project/vllm/pull/65175) `[Spec Decode] Support XPress + Acceptance Estimator` |  | main | - |
| - | [#65178](https://github.com/vllm-project/vllm/pull/65178) `[Perf][DCP] Sparse indexer: read the rank-major DCP top-k gather in place` | perf | main | - |
| - | [#65179](https://github.com/vllm-project/vllm/issues/65179) `CATHLEENANNTICO ` |  | ? | - |
| - | [#65184](https://github.com/vllm-project/vllm/pull/65184) `[ROCm][CI] Gate MoRI EPv2 modular-kernel cases on the production EPv2 checks` | infra,perf,rocm | main | - |
| - | [#65185](https://github.com/vllm-project/vllm/pull/65185) `[Compile] Fix compile warning topk `csrc/topk_histogram_4096_overflow.cuh`` | bug,risk | main | - |
| - | [#65190](https://github.com/vllm-project/vllm/issues/65190) `[ROCm][Bug] Muse Spark long-context c40 on MI350X: serial prefill and ~0 decode when the working set exceeds G` | rocm | ? | - |
| - | [#65198](https://github.com/vllm-project/vllm/pull/65198) `[GLM 5.3 Perf] Align draft model kv cache dtype align with target, 50% GPU Memory saved for each draft model` | perf | main | - |
| - | [#65199](https://github.com/vllm-project/vllm/pull/65199) `[Docs] List the Nemotron-3-Diarization plugin` |  | main | - |
| - | [#65201](https://github.com/vllm-project/vllm/pull/65201) `[Bugfix][HiSparse] Avoid the MNNVL FlashInfer all-reduce with HiSparse` | bug,nvidia | main | - |
| - | [#65204](https://github.com/vllm-project/vllm/issues/65204) `[Bug]: Extensible KV cache + KV offload connector fails to start: granule alignment rounds reserved blocks to ` | bug,perf,quant | ? | - |
| - | [#65205](https://github.com/vllm-project/vllm/issues/65205) `[Bug]: Muse Spark (NVIDIA path): 46 private fp32 RoPE tables of 1M rows cost 11.5 GiB per GPU` | nvidia | ? | - |
| - | [#65206](https://github.com/vllm-project/vllm/pull/65206) `[Bugfix][Model] Share one RoPE cache across Muse Spark NVIDIA layers` | bug,infra,nvidia,perf | main | - |
| - | [#65211](https://github.com/vllm-project/vllm/pull/65211) `[CI] Enroll 6 jobs in automatic sharding` | infra | main | - |
| - | [#65214](https://github.com/vllm-project/vllm/pull/65214) `[HiSparse] Support the extensible KV cache` | nvidia,perf | main | - |
| - | [#65216](https://github.com/vllm-project/vllm/pull/65216) `[Frontend] Add granite_toolcall_parser for Granite 4.2 tool calling` |  | main | - |
| - | [#65225](https://github.com/vllm-project/vllm/pull/65225) `[Bugfix] Pad extensible KV cache segments instead of rounding the block count` | bug,perf | main | - |
| - | [#65226](https://github.com/vllm-project/vllm/pull/65226) `[Bugfix][Multimodal] Pad MiniMax-M3 encoder graph cu_seqlens with zero-length sequences` | bug,nvidia | main | - |
| - | [#65229](https://github.com/vllm-project/vllm/pull/65229) `[Bugfix][Spec Decode] Avoid catastrophic cancellation in the acceptance estimator` | bug | main | - |
| - | [#65230](https://github.com/vllm-project/vllm/pull/65230) `[Quantization] Remove QuTLASS and fp_quant, run QuIP NVFP4 on Humming` | infra,nvidia,perf,quant | main | - |
| - | [#65234](https://github.com/vllm-project/vllm/pull/65234) `[CI] Shard Multimodal Models (Extended Generation 1) automatically, with spawned engines` | infra | main | - |
| - | [#65235](https://github.com/vllm-project/vllm/pull/65235) `[RL][Model Loader] Load plan: plan_loads and TraceTensor` |  | main | - |
| - | [#65237](https://github.com/vllm-project/vllm/pull/65237) `[Bugfix][KV Offload] Keep lazy SimpleCPUOffload stores at the GPU eviction end` | bug,perf | main | - |
| - | [#65238](https://github.com/vllm-project/vllm/pull/65238) `[CI/Build] Add batch-invariance auto-label rule` | infra | main | - |
| - | [#65245](https://github.com/vllm-project/vllm/pull/65245) `[Bugfix][Benchmark] Skip the client-side chat template on chat backends` | bug,perf | main | - |
| - | [#65249](https://github.com/vllm-project/vllm/pull/65249) `[ROCm][DSv4.1] Enable prefix-cache SWA replay on gfx942` | perf,rocm | main | - |
| - | [#65253](https://github.com/vllm-project/vllm/pull/65253) `[Bugfix][Benchmark] Preserve inactive expert IDs in synthetic forward routing` | bug,infra,perf | main | - |
| - | [#65258](https://github.com/vllm-project/vllm/pull/65258) `[Doc] MiniMax-M3.1-Flash: drop DEP4 c96 and c128 from the GB300 AgentX presets` | infra,nvidia | main | - |
| - | [#65267](https://github.com/vllm-project/vllm/pull/65267) `[Perf][ROCm][MiniMax-M3.1] Add opt-in parallel decode top-k` | infra,perf,rocm | main | - |
| - | [#65271](https://github.com/vllm-project/vllm/pull/65271) `[Bugfix][Scheduler] Don't split a multimodal item when a prefix cache hit ends inside it` | bug,perf | main | - |
| - | [#65273](https://github.com/vllm-project/vllm/issues/65273) `[Bug]: Step3 tool parser does not coerce nullable or object/array parameters` | bug | ? | - |
| - | [#65274](https://github.com/vllm-project/vllm/pull/65274) `[Bugfix] Step3 tool parser: coerce nullable and object/array parameters by schema` | bug | main | - |
| - | [#65276](https://github.com/vllm-project/vllm/pull/65276) `[ROCm][CI] Cache a PR's ROCm base image for main with `/ci rocm cache`` | infra,perf,rocm | main | - |
| - | [#65277](https://github.com/vllm-project/vllm/issues/65277) `[Feature]: Rust frontend does not export `vllm:cache_config_info`` |  | ? | - |
| - | [#65279](https://github.com/vllm-project/vllm/pull/65279) `[Bugfix][KV Offload] Preserve SWA null-page offsets after store retry` | bug | main | - |
| - | [#65281](https://github.com/vllm-project/vllm/pull/65281) `[Model Loader] Direct reload: lay the checkpoint out where a relocated weight now starts` |  | main | - |
| - | [#65284](https://github.com/vllm-project/vllm/pull/65284) `[Rust][Benchmark] Keep transport failures visible in measured requests` | perf | main | - |
| - | [#65285](https://github.com/vllm-project/vllm/pull/65285) `[Perf][Core] Cache parked async KV loads' admission reservations` | perf | main | - |
| - | [#65289](https://github.com/vllm-project/vllm/pull/65289) `[Feature][AuxOutput] Replay ordinary raw indexer selections (rl/aux-output)` |  | rl/aux-output | - |
| - | [#65291](https://github.com/vllm-project/vllm/pull/65291) `[Tools] Import vllm-state-transition-verifier` |  | vllm-state-transition-verifier | - |
| - | [#65292](https://github.com/vllm-project/vllm/pull/65292) `[Doc] Point to the vllm-state-transition-verifier branch from the NCCL weight transfer docs` | nvidia | main | - |
| - | [#65293](https://github.com/vllm-project/vllm/pull/65293) `[Rust Frontend] Choose chat content format by probing the template` |  | main | - |
| - | [#65294](https://github.com/vllm-project/vllm/pull/65294) `[Rust Frontend] Keep developer messages in place for templates without the role` |  | bz/rust-content-format-probe | - |
| - | [#65296](https://github.com/vllm-project/vllm/pull/65296) `[Model Loader] DeepSeek-V4 ROCm: keep the preshuffle scales out of the module's parameters` | quant,rocm | main | - |
| - | [#65300](https://github.com/vllm-project/vllm/pull/65300) `[Perf][Core] Keep per-request token and block id lists out of the cyclic GC` | perf | main | - |
| - | [#65302](https://github.com/vllm-project/vllm/pull/65302) `[Model] Add ZAYA1 support` |  | main | - |
| - | [#65319](https://github.com/vllm-project/vllm/pull/65319) `[Core][KV Connector] Start capped async KV loads while the batch is full` |  | main | - |
| - | [#65322](https://github.com/vllm-project/vllm/pull/65322) `[ROCm][Perf] W4A16: retune int4 skinny GEMM decode tuples for gfx115x` | perf,quant,rocm | main | - |
| - | [#65324](https://github.com/vllm-project/vllm/issues/65324) `[Bug]: Requests queued during level-2 sleep run before `reload_weights` and return wrong output with HTTP 200` | risk | ? | - |
| - | [#65331](https://github.com/vllm-project/vllm/pull/65331) `[Bugfix][KV Connector] Mooncake store: register the committed blocks of an extensible KV cache` | bug,perf | main | - |
| - | [#65350](https://github.com/vllm-project/vllm/pull/65350) `[Bugfix][Spec Decode] Use vllm.config.replace for the MRV1 DFlash draft config` | bug | main | - |
| - | [#65363](https://github.com/vllm-project/vllm/pull/65363) `[Bugfix][Multimodal] Handle media cache eviction during reads` | bug,perf | main | - |
| - | [#65369](https://github.com/vllm-project/vllm/pull/65369) `[Rust Frontend] Stop binding --data-parallel-rank to VLLM_DP_RANK` |  | main | - |
| - | [#65370](https://github.com/vllm-project/vllm/pull/65370) `[Rust Frontend] Accept Python underscore and dotted flag forms under vllm-rs serve` |  | main | - |
| - | [#65371](https://github.com/vllm-project/vllm/pull/65371) `[Rust Frontend] Coerce replayed tool-call arguments that are not an object` |  | main | - |
| - | [#65372](https://github.com/vllm-project/vllm/pull/65372) `[Rust Frontend] Accept FastAPI boolean spellings on dev route query parameters` |  | main | - |
| - | [#65374](https://github.com/vllm-project/vllm/pull/65374) `[Rust Frontend] Omit unset usage prompt_tokens_details and message annotations like Python` |  | main | - |
| - | [#65375](https://github.com/vllm-project/vllm/pull/65375) `[Rust Frontend] Drop incomplete tool-call markup at the end of output like Python` |  | main | - |
| - | [#65376](https://github.com/vllm-project/vllm/pull/65376) `[Rust Frontend] Return 501 for /generative_scoring and the opt-in Cohere v2 chat routes` |  | main | - |
| - | [#65377](https://github.com/vllm-project/vllm/pull/65377) `[Rust Frontend] Drop tool calls under tool_choice=none for split tool parsers` |  | main | - |
| - | [#65378](https://github.com/vllm-project/vllm/issues/65378) `[Bug]: Extensible KV cache undersizes the KV cache on integrated (UMA) GPUs, down to 0 blocks: free memory rea` | perf,quant | ? | - |
| - | [#65386](https://github.com/vllm-project/vllm/pull/65386) `Minimax m3.1 dspark drafter monokernel` | infra | main | - |
| - | [#65388](https://github.com/vllm-project/vllm/issues/65388) `[Bug]: Scale-out `/render` drops `max_tokens: 16` (the `/v1/completions` default) from `sampling_params`, so `` | bug,quant | ? | - |
| - | [#65389](https://github.com/vllm-project/vllm/pull/65389) `[Bugfix] Keep default max_tokens in rendered sampling_params` | bug | main | - |
| - | [#65399](https://github.com/vllm-project/vllm/pull/65399) `[Bugfix][Scheduler] Respect disabled chunked prefill for multimodal requests` | bug | main | - |
| - | [#65412](https://github.com/vllm-project/vllm/pull/65412) `[Bugfix] Granite4Vision: strip padding tiles for list pixel_values` | bug | main | - |
| - | [#65413](https://github.com/vllm-project/vllm/pull/65413) `[Bugfix] Size the extensible KV cache from UMA-corrected free memory` | bug,nvidia,perf | main | - |
| - | [#65416](https://github.com/vllm-project/vllm/pull/65416) `[XPU] fix case test_p2p_lifecycle_e2e.py and test_mm_prefix_lm.py` | bug,nvidia | main | - |
| - | [#65417](https://github.com/vllm-project/vllm/pull/65417) `[MyPy][8b/N] Fix and enforce remaining tests/models subdirectories` | bug | main | - |
| - | [#65418](https://github.com/vllm-project/vllm/pull/65418) `[Bugfix][ROCm] Raise the extensible KV cache margin floor to 3 GiB` | bug,perf,rocm | main | - |
| - | [#65423](https://github.com/vllm-project/vllm/pull/65423) `[Perf][Startup] Keep openai out of import vllm.config via lazy ToolServer import` | perf | main | - |
| - | [#65425](https://github.com/vllm-project/vllm/pull/65425) `[ROCm][CI] Restore the Torch Stable ABI Audit mirror with a locked audit tool` | infra,rocm | main | - |
| - | [#65428](https://github.com/vllm-project/vllm/pull/65428) `[Bugfix][CI] Keep the chat template on NixlConnector PD + SD acceptance prompts` | bug,infra | main | - |
| - | [#65432](https://github.com/vllm-project/vllm/pull/65432) `[ROCm][Perf][MiniMax-M3.1] Score DSpark 7 decode locally below 3 requests instead of via indexer CP` | perf,rocm | main | - |
| - | [#65438](https://github.com/vllm-project/vllm/pull/65438) `[Model] Optimize Muse Spark GEMM and communication-norm fusion` | perf | main | - |
| - | [#65439](https://github.com/vllm-project/vllm/pull/65439) `[CI][Tests] Remove timing dependence from Engram prefetch synchronization test` | infra | main | - |
| - | [#65441](https://github.com/vllm-project/vllm/pull/65441) `[CI][Model] Fill the model info cache once in the model init and tensor schema tests` | infra,perf | main | - |
| - | [#65442](https://github.com/vllm-project/vllm/pull/65442) `[CI][Test] Skip unavailable models before spawning a test process` | infra | main | - |
| - | [#65443](https://github.com/vllm-project/vllm/pull/65443) `[CI][Test] Skip multi-node-only pipeline-parallel cases at collection` | infra | main | - |
| - | [#65445](https://github.com/vllm-project/vllm/pull/65445) `[Model] Canary: require `language` and test translation` |  | main | - |
| - | [#65449](https://github.com/vllm-project/vllm/pull/65449) `[Bugfix][Spec Decode] Initialize Mistral EAGLE weight-loader state` | bug | main | - |
| - | [#65451](https://github.com/vllm-project/vllm/issues/65451) `[Bug]: GLM-5.3 at max_model_len=1M crashes at startup on B300 (illegal memory access in TRT-LLM FMHA) since #6` | bug,risk | ? | - |
| - | [#65452](https://github.com/vllm-project/vllm/pull/65452) `[Misc] Add LiteTopK acknowledgement to fused_mqa_topk` | perf | main | - |
| - | [#65455](https://github.com/vllm-project/vllm/pull/65455) `[KV Offload] Adapt to the new KVCR key adapter API` | infra | main | - |
| - | [#65457](https://github.com/vllm-project/vllm/pull/65457) `[Bugfix] Keep the extensible tensor's PyCapsule_New prototype private` | bug | main | - |
| - | [#65459](https://github.com/vllm-project/vllm/pull/65459) `[Bugfix][Frontend] Support min_tokens in the Anthropic Messages API` | bug | main | - |
| - | [#65460](https://github.com/vllm-project/vllm/pull/65460) `[CI] Enroll 1 step in automatic sharding: UMBP Connector TP2 Integration` | infra | main | - |
| - | [#65465](https://github.com/vllm-project/vllm/issues/65465) `[Bug][Spec Decode][Structured Output] Reverting #54442 reopens grammar-invalid proposal acceptance in async sc` |  | ? | - |
| - | [#65466](https://github.com/vllm-project/vllm/pull/65466) `[Core] Handle new requests and aborts while waiting for model output` |  | main | - |
| - | [#65467](https://github.com/vllm-project/vllm/pull/65467) `[Recipe] Kimi-K3: refresh B300 AgentX preset to InferenceX #4381 head` | infra | main | - |
| - | [#65473](https://github.com/vllm-project/vllm/pull/65473) `[CI] Run test_depyf_integration in a spawned process` | infra | main | - |
| - | [#65478](https://github.com/vllm-project/vllm/pull/65478) `[ROCm][Perf][MiniMax-M3.1] Fuse the FFN-side MXFP8 activation quant into the post-attention norm and swiglu` | perf,quant,rocm | main | - |
| - | [#65481](https://github.com/vllm-project/vllm/pull/65481) `[ROCm][Perf][MiniMax-M3.1] Pick the NVFP4 sparse decode splits per XCD, not per CU` | infra,perf,quant,rocm | main | - |
| - | [#65482](https://github.com/vllm-project/vllm/pull/65482) `[CI] Enroll RL Entrypoints in automatic sharding` | infra | main | - |
| - | [#65484](https://github.com/vllm-project/vllm/pull/65484) `[CI] Shard Quantization Kernels automatically instead of by hand` | infra,perf,quant | main | - |
| - | [#65488](https://github.com/vllm-project/vllm/pull/65488) `[Perf][Spec Decode] Pad DFlash draft inputs on extra programs of the same launch` | perf | main | - |
| - | [#65494](https://github.com/vllm-project/vllm/pull/65494) `[Build] Update DeepGEMM pin to latest main` | infra | main | - |
| - | [#65495](https://github.com/vllm-project/vllm/pull/65495) `[CI][Test] Validate manual NVFP4 fusion in NVIDIA Qwen mixed-precision test` | infra,nvidia,perf,quant | main | - |
| - | [#65496](https://github.com/vllm-project/vllm/pull/65496) `[Bugfix][MiniMax-M3] Don't emit MXFP8 from the input norm under sequence parallelism` | bug,quant | main | - |
| - | [#65498](https://github.com/vllm-project/vllm/pull/65498) `[Perf][MoE] Skip the combine staging copy in flashinfer_nvlink_one_sided` | nvidia,perf | main | - |
| - | [#65504](https://github.com/vllm-project/vllm/pull/65504) `[Step5] Allow MegaMoE with pipeline parallelism` |  | main | - |
| - | [#65514](https://github.com/vllm-project/vllm/pull/65514) `[CI] Run PyTorch Compilation root tests in one pytest, with test_config.py's forked tests spawned` | infra | main | - |
| - | [#65518](https://github.com/vllm-project/vllm/pull/65518) `[Build] Bump vllm-flash-attn to compress fatbins with --compress-mode=size` | infra,nvidia | main | - |
| - | [#65522](https://github.com/vllm-project/vllm/pull/65522) `[Bugfix] Keep the HiSparse FlashInfer all-reduce backend on lazy workspace creation` | bug,nvidia | main | - |
| - | [#65528](https://github.com/vllm-project/vllm/pull/65528) `[Spec Decode] Clean up AR speculator decode path` |  | main | - |
| - | [#65529](https://github.com/vllm-project/vllm/pull/65529) `[Recipe] Kimi-K3: add B200 AgentX aggregated Mooncake preset` | infra,nvidia | main | - |
| - | [#65530](https://github.com/vllm-project/vllm/pull/65530) `[ROCm][Perf][MiniMax-M3.1] Retune the MXFP8 dot_scaled GEMM tiles for M=17-256` | perf,quant,rocm | main | - |
| - | [#65537](https://github.com/vllm-project/vllm/pull/65537) `[MiniMax-M3] Support sequence parallelism with pipeline parallelism` |  | main | - |
| - | [#65539](https://github.com/vllm-project/vllm/pull/65539) `[Bugfix][Distributed] Fix PP rank derivation when prefill context parallelism is enabled` | bug,infra | main | - |
| - | [#65540](https://github.com/vllm-project/vllm/pull/65540) `[Build] Marlin: drop SM12x-specific cubins and rely on compute_80 PTX` | infra,quant | main | - |
| - | [#65542](https://github.com/vllm-project/vllm/pull/65542) `[Kernel] Marlin: remove 8-bit (INT8/FP8) activation support, rely on Humming` | infra,nvidia,perf,quant | main | - |
| - | [#65547](https://github.com/vllm-project/vllm/pull/65547) `[Bugfix][Frontend] Accept an empty tools array like OpenAI` | bug,infra | main | - |
| - | [#65551](https://github.com/vllm-project/vllm/issues/65551) `[Bug] AssertionError in sanity_check_mm_encoder_outputs on Ascend 300I A2 (vllm-ascend): multimodal embeddings` |  | ? | - |
| - | [#65552](https://github.com/vllm-project/vllm/pull/65552) `[CI][DSv4.1] Give the MXFP8 linear test stub a params_dtype` | infra,quant | main | - |
| - | [#65553](https://github.com/vllm-project/vllm/pull/65553) `[GLM 5.3 Perf] Enable fp8 kv cache for glm 5.3 flash draft model dspark, 960MB GPU memory saved each rank` | perf,quant | main | - |
| - | [#65554](https://github.com/vllm-project/vllm/pull/65554) `[Bugfix] Fix startup illegal memory access from unaligned extensible KV cache segments` | bug,perf,risk | main | - |
| - | [#65557](https://github.com/vllm-project/vllm/pull/65557) `[Doc] Add vllm-iluvatar core Gpu to the Vllm support list` |  | main | - |
| - | [#65567](https://github.com/vllm-project/vllm/pull/65567) `[CI] Run H100 fusion config sweeps and batch invariance nightly only` | infra,nvidia,perf | main | - |
| - | [#65573](https://github.com/vllm-project/vllm/issues/65573) `[Feature]: Support `mm_device_do_normalize` for Gemma 4` |  | ? | - |
| - | [#65577](https://github.com/vllm-project/vllm/pull/65577) `[MM] Support mm_device_do_normalize for Gemma 4` |  | main | - |
| - | [#65579](https://github.com/vllm-project/vllm/pull/65579) `[Bugfix][Multimodal] Fix tensor conversion in audio parsing and hashing` | bug,nvidia | main | - |
| - | [#65585](https://github.com/vllm-project/vllm/pull/65585) `[CI] Enroll the MI300 Batch Invariance (Distributed) mirror in automatic sharding` | infra,rocm | main | - |
| - | [#65593](https://github.com/vllm-project/vllm/pull/65593) `[Bugfix][EC Connector] Make control-plane ZMQ heartbeats take effect` | bug | main | - |
| - | [#65598](https://github.com/vllm-project/vllm/pull/65598) `[Bugfix][Attention] Keep FlashInfer TRTLLM prefill query offsets in a persistent buffer` | bug,nvidia | main | - |
| - | [#65599](https://github.com/vllm-project/vllm/pull/65599) `[ROCm][Step5] Use one warp for CSA prefill sparse attention on CDNA3/CDNA4` | rocm | main | - |
| - | [#65619](https://github.com/vllm-project/vllm/pull/65619) `[Perf][Qwen4Exp] Share the QSA top-k buffer across layers` | perf | main | - |
| - | [#65620](https://github.com/vllm-project/vllm/pull/65620) `[Doc] Document multimodal requirements for the Transformers modeling …` | infra | main | - |
| - | [#65621](https://github.com/vllm-project/vllm/pull/65621) `[Rust Frontend] Accept refusal content parts in assistant messages` |  | main | - |
| - | [#65622](https://github.com/vllm-project/vllm/pull/65622) `[Rust Frontend] Count vllm:watermark_requests from the engine-reported flag` |  | main | - |
| - | [#65623](https://github.com/vllm-project/vllm/pull/65623) `[Rust Frontend] Pass assistant and tool content parts to HF templates like Python` |  | main | - |
| - | [#65624](https://github.com/vllm-project/vllm/pull/65624) `[Rust Frontend] Support echo with truncate_prompt_tokens` | risk | main | - |
| - | [#65625](https://github.com/vllm-project/vllm/pull/65625) `[Rust Frontend] Support n > 1 choices` |  | main | - |
| - | [#65631](https://github.com/vllm-project/vllm/pull/65631) `[Bugfix][KV Offload] Keep whole-chunk max_load_tokens caps with sliding window groups` | bug | main | - |
| - | [#65635](https://github.com/vllm-project/vllm/pull/65635) `[Rust Frontend] Export vllm:cache_config_info like Python` |  | main | - |
| - | [#65636](https://github.com/vllm-project/vllm/pull/65636) `[Rust Frontend] Report system_fingerprint from the engine's config hash` |  | main | - |
| - | [#65641](https://github.com/vllm-project/vllm/pull/65641) `[ROCm][CI] Skip the GPU coredump in MonoKernel fault-injection tests` | infra,rocm | main | - |
| - | [#65652](https://github.com/vllm-project/vllm/pull/65652) `[torch.compile] Replace config `compute_hash` with `compile_factors`` | nvidia | main | - |
| - | [#65669](https://github.com/vllm-project/vllm/pull/65669) `[CPU][Zen] Update zentorch to 2.14.0.2` | infra | main | - |
| - | [#65679](https://github.com/vllm-project/vllm/pull/65679) `[Bugfix] Require fastokens >= 0.3.5 for VLLM_USE_FASTOKENS` | bug,infra | main | - |
| - | [#65682](https://github.com/vllm-project/vllm/issues/65682) `[RFC]: Bounded load/save admission for Mooncake Store` |  | ? | - |
| - | [#65684](https://github.com/vllm-project/vllm/pull/65684) `[Recipe] Add Kimi K3.1 Pro recipes` | infra | main | - |
| - | [#65688](https://github.com/vllm-project/vllm/pull/65688) `[Recipe] Kimi-K3.1-Pro: pin Docker images, drop pip, add Rubin VR200` | infra | main | - |
| - | [#65689](https://github.com/vllm-project/vllm/pull/65689) `[Bugfix][Multimodal] Don't validate model-built dummy inputs against mm limits` | bug | main | - |
| - | [#65692](https://github.com/vllm-project/vllm/pull/65692) `[Perf][Qwen4Exp] Route the PLE shard copy through copy_weight_` | perf | main | - |
| - | [#65697](https://github.com/vllm-project/vllm/pull/65697) `[Bugfix][Frontend] Count prompts over max_model_len in Anthropic count_tokens` | bug | main | - |
| - | [#65710](https://github.com/vllm-project/vllm/pull/65710) `[Bugfix][Structured Output] Handle EOS in speculative Guidance batches` | bug | main | - |
| - | [#65722](https://github.com/vllm-project/vllm/pull/65722) `[Bugfix][ROCm] Stop AITER FA from skipping 1-token prompts in prefill/extend` | bug,rocm | main | - |
| - | [#65725](https://github.com/vllm-project/vllm/pull/65725) `[Recipe] Kimi-K3.1-Pro: add TPU serving via vllm-torchtpu` | infra | main | - |
| - | [#65745](https://github.com/vllm-project/vllm/pull/65745) `[Model] Add Ricursive Ripple-65B support` | infra | main | - |
| - | [#65750](https://github.com/vllm-project/vllm/pull/65750) `[CI] Pass --models=llama3.2 so Rust Frontend Tool Use gets a shard plan` | infra | main | - |
| - | [#65752](https://github.com/vllm-project/vllm/issues/65752) `[Bug]: `/v1/responses` omits `completed_at` / `error` and sends `text: null`, so strict OpenAI-compatible clie` |  | ? | - |
| - | [#65753](https://github.com/vllm-project/vllm/pull/65753) `[CI] Consolidate per-version model labels into vendor/family labels` | infra | main | - |
| - | [#65761](https://github.com/vllm-project/vllm/pull/65761) `[Bugfix][Multimodal] Encoder CUDA graph: cap each graph's frame slots at its token budget` | bug,nvidia | main | - |
| - | [#65762](https://github.com/vllm-project/vllm/pull/65762) `[CI] Let ci-selector decide csrc/ changes on CUDA` | bug,infra,nvidia | main | - |
| - | [#65763](https://github.com/vllm-project/vllm/pull/65763) `[CI][Kernels] Make the MiniMax-M3 decode top-k test deterministic` | infra,perf | main | - |
| - | [#65773](https://github.com/vllm-project/vllm/pull/65773) `[Core] Cheapen the spin while waiting for model output` |  | main | - |
| - | [#65776](https://github.com/vllm-project/vllm/pull/65776) `[CI Failure] Move Multimodal Models (Extended Pooling) to h200_35gb` | infra | main | - |
| - | [#65778](https://github.com/vllm-project/vllm/pull/65778) `[Bugfix][Multimodal] Fix FlashInfer ViT attention for GLM-4.1V, GLM-OCR and GLM-5.3-Flash` | bug,nvidia | main | - |
| - | [#65805](https://github.com/vllm-project/vllm/pull/65805) `[XPU] skipp unsupported test cases in CI` | infra,nvidia | main | - |
| - | [#65806](https://github.com/vllm-project/vllm/pull/65806) `[Bugfix][MiniMax-M3] Initialize the shard record in the indexer QKV layer` | bug | main | - |
| - | [#65810](https://github.com/vllm-project/vllm/pull/65810) `[CI] Drop the removed input_dtype arg from the Zen DA8W4 test` | infra | main | - |
| - | [#65811](https://github.com/vllm-project/vllm/issues/65811) `[Bug]: Qwen3.5-122B + LoRA crashes at startup: _inject_lora_into_fused_moe asserts TritonExperts, but FlashInf` | bug,nvidia,perf | ? | - |
| - | [#65812](https://github.com/vllm-project/vllm/pull/65812) `[Bugfix] Honor checkpoint FP8 KV scales in Qwen4Exp QSA` | bug,quant | main | - |
| - | [#65816](https://github.com/vllm-project/vllm/pull/65816) `[Bugfix][DeepSeek-V4] Share the target embedding with the MTP drafter under PP` | bug | main | - |
| - | [#65817](https://github.com/vllm-project/vllm/pull/65817) `[Recipe] Add ERNIE-5.5-Flash recipe` | infra | main | - |
| - | [#65825](https://github.com/vllm-project/vllm/pull/65825) `[Bugfix][LoRA] Align GPT-OSS MXFP4 LoRA TP shards with base weights` | bug,quant | main | - |
| - | [#65826](https://github.com/vllm-project/vllm/pull/65826) `[Model] Add LFM3-Text` |  | main | - |
| - | [#65827](https://github.com/vllm-project/vllm/pull/65827) `[Model] Add LFM3-VL` |  | main | - |
| - | [#65828](https://github.com/vllm-project/vllm/pull/65828) `[Model] Add LFM3-Audio` |  | main | - |
| - | [#65831](https://github.com/vllm-project/vllm/pull/65831) `[Perf][Core] Reduce per-block CPU cost of KV block allocation and caching` | perf | main | - |
| - | [#65834](https://github.com/vllm-project/vllm/pull/65834) `[Docs] Fix missing MLA verify parameter types in API docs` | bug | main | - |
| - | [#65850](https://github.com/vllm-project/vllm/pull/65850) `[Rust Frontend] Add the max_lora label to vllm:lora_requests_info` |  | main | - |
| - | [#65851](https://github.com/vllm-project/vllm/pull/65851) `[Rust Frontend] Keep whitespace in HY tool-call argument names` |  | main | - |
| - | [#65852](https://github.com/vllm-project/vllm/pull/65852) `[Rust Frontend] Return FastAPI-style JSON 400 errors for bad dev route query strings` |  | main | - |
| - | [#65853](https://github.com/vllm-project/vllm/pull/65853) `[Rust Frontend] Support namespace tools in the Responses API` |  | main | - |
| - | [#65854](https://github.com/vllm-project/vllm/pull/65854) `[Rust Frontend] Accept an empty tools array like OpenAI` |  | main | - |
| - | [#65863](https://github.com/vllm-project/vllm/pull/65863) `[Rust Frontend] Echo prompt-cache and safety_identifier fields in Responses` | perf | main | - |
| - | [#65867](https://github.com/vllm-project/vllm/pull/65867) `[Perf][Frontend] Write run-batch JSON responses without parsing them back` | perf | main | - |
| - | [#65875](https://github.com/vllm-project/vllm/pull/65875) `[Bugfix][CI] Fix duplicate max_num_seqs in Llama Nemotron VL pooling test` | bug,infra | main | - |
| - | [#65883](https://github.com/vllm-project/vllm/pull/65883) `[Perf][MiniMax-M3] Don't sync when building sparse-attention prefill metadata` | perf | main | - |
| - | [#65889](https://github.com/vllm-project/vllm/pull/65889) `[CI] Limit ROCm Docker Hub login to image publishing` | infra,rocm | main | - |
| - | [#65895](https://github.com/vllm-project/vllm/pull/65895) `[CI] Use a repository-scoped Docker Hub secret for release publishing` | infra | main | - |
| - | [#65908](https://github.com/vllm-project/vllm/pull/65908) `[ROCm][CI] Fix flaky layer 0 bound in test_dsv4_mono_layers` | bug,infra,rocm | main | - |
| - | [#65910](https://github.com/vllm-project/vllm/pull/65910) `[CI][Step5] Pin the starting block size in the CSA tail ring test` | infra | main | - |
| - | [#65912](https://github.com/vllm-project/vllm/pull/65912) `[ROCm][CI] Fix flaky streaming checks in test_translation_validation` | bug,infra,rocm | main | - |
| - | [#65914](https://github.com/vllm-project/vllm/pull/65914) `[Model Loader] One finish for every update path; drop refresh_derived_weights` |  | main | - |
| - | [#65916](https://github.com/vllm-project/vllm/pull/65916) `[ROCm][CI] Shard Spec Decode AL MTP with pytest-shard after the Gemma4 dataset split` | infra,rocm | main | - |
| - | [#65930](https://github.com/vllm-project/vllm/pull/65930) `[Dependency] Upgrade FlashInfer to 0.7.3` | infra,nvidia | main | - |
| - | [#65937](https://github.com/vllm-project/vllm/pull/65937) `[ROCm] Bump AITER to v0.1.28.post1` | infra,rocm | main | - |
| - | [#65954](https://github.com/vllm-project/vllm/pull/65954) `[Bugfix][Frontend] Accept Anthropic thinking.type=between_tools on the Messages API` | bug | main | - |
| - | [#65968](https://github.com/vllm-project/vllm/pull/65968) `[Docs][ROCm] Fix stale AMD recipe images for GLM-5 and GLM-5.1` | bug,infra,rocm | main | - |
| - | [#65971](https://github.com/vllm-project/vllm/pull/65971) `[ROCm][Kernel] Follow-ups to the gfx942 MLA Triton verify kernel` | perf,rocm | main | - |
| - | [#65977](https://github.com/vllm-project/vllm/pull/65977) `[Misc] Add NIXL team to nixl label` | infra | main | - |
| - | [#65986](https://github.com/vllm-project/vllm/pull/65986) `[Recipes] Update DeepSeek-V4.1-Flash AgentX presets for GB200 and B200` | infra,nvidia | main | - |
| - | [#65988](https://github.com/vllm-project/vllm/pull/65988) `[ROCm][CI] Let /ci rocm cache start its main build on AMD CI` | infra,perf,rocm | main | - |
| - | [#65989](https://github.com/vllm-project/vllm/pull/65989) `[Bugfix][Gemma4] Read per-layer embeddings on later pipeline stages` | bug | main | - |
| - | [#66005](https://github.com/vllm-project/vllm/pull/66005) `[CI][Frontend] Pin the derender n2 parity cases to top-1 sampling` | infra | main | - |
| - | [#66006](https://github.com/vllm-project/vllm/issues/66006) `[Bug]: With `HF_HUB_OFFLINE=1`, a Hub-ID speculative draft model logs `ERROR ... Error retrieving safetensors:` |  | ? | - |
| - | [#66012](https://github.com/vllm-project/vllm/pull/66012) `[Bugfix] Do not retry safetensors metadata lookup in offline mode` | bug | main | - |
| - | [#66016](https://github.com/vllm-project/vllm/pull/66016) `[Build][Bugfix] Never fall back from an x.yf CUDA arch to a lower minor` | bug,infra,nvidia | main | - |
| - | [#66017](https://github.com/vllm-project/vllm/pull/66017) `[Bugfix][Qwen3-Omni] Size the video encoder budget from the processor's video limits` | bug | main | - |
| - | [#66019](https://github.com/vllm-project/vllm/pull/66019) `[CI][KV Offload] Pin GPU block size in test_p2p_cache_reset_with_absent_decoder` | infra | main | - |
| - | [#66029](https://github.com/vllm-project/vllm/pull/66029) `[XPU] increase gpu_memory_utilization for test_granite4_vision.py` | nvidia | main | - |
| - | [#66039](https://github.com/vllm-project/vllm/pull/66039) `[XPU][CI] Correct deselected file path in entrypoints/scale_out test` | infra,nvidia | main | - |
| - | [#66044](https://github.com/vllm-project/vllm/pull/66044) `[Doc][Bugfix] Fix strict docs build broken by unresolved autorefs` | bug,infra,nvidia | main | - |
| - | [#66046](https://github.com/vllm-project/vllm/pull/66046) `[ROCm][CI] Skip the unlimited OCR tests until the ROCm CK OCR2 DASH updates land` | infra,rocm | main | - |
| - | [#66062](https://github.com/vllm-project/vllm/pull/66062) `[Doc][Bugfix] Fix strict docs build broken by subclassing mocked torch classes` | bug,infra | main | - |
| - | [#66064](https://github.com/vllm-project/vllm/pull/66064) `[Perf][GDN] Fuse prefill state gather/scatter with the shared Triton kernels` | infra,perf,rocm | main | - |
| - | [#66079](https://github.com/vllm-project/vllm/pull/66079) `[CI][Bugfix] Fix EmbeddingGemma2 encoder contract test after Gemma-4 DP encoder` | bug,infra | main | - |
| - | [#66097](https://github.com/vllm-project/vllm/pull/66097) `[Model] Use the upstream config for Qwen3-ASR` |  | main | - |
| - | [#66111](https://github.com/vllm-project/vllm/pull/66111) `[CI] Reuse the HF reference across use_prompt_embeds` | infra | main | - |

### vLLM — Open / submitted (1061 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#64620](https://github.com/vllm-project/vllm/pull/64620) `[MoE] Load fused expert weights with one weight_loader call per shard` | perf | main | - |
| - | [#64621](https://github.com/vllm-project/vllm/pull/64621) `[Perf][GDN] Use FlashInfer's regular prefill route for short batches` | nvidia,perf | main | - |
| - | [#64622](https://github.com/vllm-project/vllm/pull/64622) `[Startup] Skip the CUDA graph memory profile when its estimate is disabled` | nvidia | main | - |
| - | [#64623](https://github.com/vllm-project/vllm/pull/64623) `[Core] Don't let a second SIGTERM interrupt EngineCore and worker teardown` |  | main | - |
| - | [#64624](https://github.com/vllm-project/vllm/pull/64624) `[Hybrid] Round the attention block size up to prefix_match_unit` |  | main | - |
| - | [#64629](https://github.com/vllm-project/vllm/pull/64629) `[MoE] Autotune FlashInfer MegaMoE live-token workspaces at startup` | nvidia,perf | main | - |
| - | [#64631](https://github.com/vllm-project/vllm/pull/64631) `[Attention] Shard MiniMax M3.1's NVFP4 index cache with indexer CP` | nvidia,perf,quant | main | - |
| - | [#64632](https://github.com/vllm-project/vllm/issues/64632) `[Tracking] Muse Spark Open Improvement` | rocm | ? | - |
| - | [#64634](https://github.com/vllm-project/vllm/pull/64634) `[MM][CG] Support ViT full CUDA graph for Intern-S1` | nvidia | main | - |
| - | [#64636](https://github.com/vllm-project/vllm/pull/64636) `[Perf][Qwen4Exp] Add SM80 TP=8 skinny GEMM plans` | perf | main | - |
| - | [#64640](https://github.com/vllm-project/vllm/pull/64640) `[ROCm][MoE] Add opt-in AITER FlyDSL clamped MXFP4 BF16 experts` | infra,quant,rocm | main | - |
| - | [#64641](https://github.com/vllm-project/vllm/pull/64641) `[Fast Start] Add weights mirror support for daemon2daemon` |  | main | - |
| - | [#64642](https://github.com/vllm-project/vllm/pull/64642) `[Bugfix][ROCm][DSv4.1] Inject Engram at a PP stage that starts at an Engram layer` | bug,infra,rocm | main | - |
| - | [#64643](https://github.com/vllm-project/vllm/pull/64643) `[Feature][ROCm][DSv4.1] Relay KV-sharing state across ROCm pipeline stages` | infra,rocm | main | - |
| - | [#64645](https://github.com/vllm-project/vllm/issues/64645) `[Feature]: Support LiquidAI LFM3 models` |  | ? | - |
| - | [#64646](https://github.com/vllm-project/vllm/pull/64646) `[Benchmark] Add small-M NVFP4 linear benchmark across vLLM kernels` | perf,quant | main | - |
| - | [#64648](https://github.com/vllm-project/vllm/issues/64648) `[RFC]: Direct layerwise and chunk-wise KV WRITE with Mooncake` |  | ? | - |
| - | [#64649](https://github.com/vllm-project/vllm/pull/64649) `[Bugfix][Scheduler] Cap the async-load spec margin at max_model_len` | bug | main | - |
| - | [#64652](https://github.com/vllm-project/vllm/issues/64652) `[Bug]: EAGLE3 draft acceptance collapses after the first position with --block-size > 128 (MiniMax-M3, GB200)` | nvidia | ? | - |
| - | [#64654](https://github.com/vllm-project/vllm/issues/64654) `[Feature]: Add ID-only request logging while preserving lifecycle events` |  | ? | - |
| - | [#64660](https://github.com/vllm-project/vllm/pull/64660) `[Bugfix][Rust Frontend] Serve SageMaker /ping and mark /invocations unsupported` | bug | main | - |
| - | [#64661](https://github.com/vllm-project/vllm/pull/64661) `[Bugfix][NIXL] Preserve packed-row aliases during region dedup` | bug | main | - |
| - | [#64662](https://github.com/vllm-project/vllm/pull/64662) `[ROCm][Perf] Add MI325X FP8 fused MoE configs for Qwen3.8-Flash-Next` | perf,quant,rocm | main | - |
| - | [#64663](https://github.com/vllm-project/vllm/pull/64663) `[Doc] Named and required tool_choice need a tool parser` |  | main | - |
| - | [#64664](https://github.com/vllm-project/vllm/issues/64664) `[Bug][ROCm] vLLM fails to detect AMD GPU in WSL when AMDSMI cannot initialize` | rocm | ? | - |
| - | [#64667](https://github.com/vllm-project/vllm/pull/64667) `[Frontend] Add --enable-log-request-ids-only` |  | main | - |
| - | [#64668](https://github.com/vllm-project/vllm/pull/64668) `[1/2][MRV2] Remove the dependency of MRV2 DBO from MRV1` | infra,nvidia | main | - |
| - | [#64669](https://github.com/vllm-project/vllm/issues/64669) `[Bug]: Qwen GDN models fail to start with CPU weight offloading without UVA` |  | ? | - |
| - | [#64670](https://github.com/vllm-project/vllm/pull/64670) `[Bugfix] Move offloaded A_log and dt_bias to the GPU in the Qwen GDN warmup` | bug | main | - |
| - | [#64671](https://github.com/vllm-project/vllm/pull/64671) `[CPU] Add Gloo DP/EP follow-up for wide expert parallelism` | infra | main | - |
| - | [#64672](https://github.com/vllm-project/vllm/pull/64672) `[Model] Add Raon-1-mini support` |  | main | - |
| - | [#64676](https://github.com/vllm-project/vllm/pull/64676) `[Bugfix][UMBP] Reject DRAM watermarks that keep MORI from evicting` | bug,infra,rocm | main | - |
| - | [#64678](https://github.com/vllm-project/vllm/pull/64678) `[Bugfix][KV Offload][P2P] Fail a dead peer's sibling ports on the same host at once (opt-in)` | bug | main | - |
| - | [#64679](https://github.com/vllm-project/vllm/issues/64679) `[Bug]: fuse_rope_kvcache breaks draft_model/EAGLE spec decode when the drafter's attention shape differs from ` | perf,rocm | ? | - |
| - | [#64680](https://github.com/vllm-project/vllm/issues/64680) `[Bug]: ROCM_AITER_FA crashes with draft_model/EAGLE drafters in extend_forward (None prefix in merge_attn_stat` | bug,rocm | ? | - |
| - | [#64682](https://github.com/vllm-project/vllm/pull/64682) `[Security] Bound decoded image copies before preprocessing` |  | main | - |
| - | [#64683](https://github.com/vllm-project/vllm/pull/64683) `[Model] Add Apriel Voice support` | infra | main | - |
| - | [#64684](https://github.com/vllm-project/vllm/pull/64684) `[Security] Bound Ovis2.5 processed media allocations` | infra | main | - |
| - | [#64685](https://github.com/vllm-project/vllm/pull/64685) `[Rust Frontend] gRPC Render service with streaming Derender; multimodal, LoRA, logprobs and stop strings for r` |  | main | - |
| - | [#64687](https://github.com/vllm-project/vllm/pull/64687) `[Models][XPU] Port eager Qwen3.5 models and fuse MoE decode` | infra,nvidia,perf | main | - |
| - | [#64693](https://github.com/vllm-project/vllm/pull/64693) `[ROCm][MoRIIO] Support PP for prefill instance in PD disaggregated serving with MoRI WRITE mode` | rocm | main | - |
| - | [#64694](https://github.com/vllm-project/vllm/pull/64694) `[CI] Run Anthropic contract tests on CPU` | infra | main | - |
| - | [#64696](https://github.com/vllm-project/vllm/issues/64696) `[Bug]: `npcache` silently serves stale weights after the source `.bin` checkpoint changes` | bug,risk | ? | - |
| - | [#64698](https://github.com/vllm-project/vllm/pull/64698) `[Doc] Clarify --base-url must not include /v1 suffix in benchmark CLI` | perf | main | - |
| - | [#64699](https://github.com/vllm-project/vllm/pull/64699) `[Feature][MRV2] Enable Qwen3.5 GDN ReplaySSM standard decode` | perf | main | - |
| - | [#64701](https://github.com/vllm-project/vllm/pull/64701) `[Perf][MRV2] Trim the FULL graph output copy and the draft-token gather` | nvidia,perf | main | - |
| - | [#64702](https://github.com/vllm-project/vllm/pull/64702) `[CI] Release GPU and distributed state at every test-file boundary` | infra | main | - |
| - | [#64703](https://github.com/vllm-project/vllm/pull/64703) `[Bugfix][Benchmark] Reject incomplete completion streams` | bug,perf | main | - |
| - | [#64704](https://github.com/vllm-project/vllm/issues/64704) `[Bug]: PyTorch `.bin` checkpoints can silently lose a distinct `lm_head` when embeddings are configured as tie` | bug,risk | ? | - |
| - | [#64705](https://github.com/vllm-project/vllm/pull/64705) `[XPU][UT] use fp32 when hf_runner on XPU` | nvidia | main | - |
| - | [#64706](https://github.com/vllm-project/vllm/pull/64706) `[Kernel] Port fused_deepseek_v4_qnorm_rope_kv_insert to CuTe DSL` | infra,perf | main | - |
| - | [#64710](https://github.com/vllm-project/vllm/pull/64710) `[Rust Frontend] Bump the Rust toolchain to 1.100.0-beta.7` | infra | main | - |
| - | [#64711](https://github.com/vllm-project/vllm/pull/64711) `[Rust Frontend] Replace assert!(matches!(..)) with std assert_matches!` |  | bz/rust-toolchain-1.100 | - |
| - | [#64713](https://github.com/vllm-project/vllm/issues/64713) `[Feature]: Add an NVIDIA RTX PRO 6000 Blackwell deployment recipe for DeepSeek-V4-Flash-Vision-Exp` | nvidia | ? | - |
| - | [#64714](https://github.com/vllm-project/vllm/issues/64714) `[Bug]: `MessageQueue.shutdown()` cannot wake a reader blocked on an overflow payload` | bug,risk | ? | - |
| - | [#64715](https://github.com/vllm-project/vllm/pull/64715) `[ROCm][UMBP] Support UMBP standalone mode for DeepSeek-V4.1-Flash` | rocm | main | - |
| - | [#64716](https://github.com/vllm-project/vllm/pull/64716) `[Bugfix] Rebuild npcache when source checkpoint shards are updated` | bug | main | - |
| - | [#64718](https://github.com/vllm-project/vllm/pull/64718) `[2/2][MRV2] Abort sibling microbatches when one fails` | infra,nvidia | main | - |
| - | [#64719](https://github.com/vllm-project/vllm/pull/64719) `[CI] Narrow CUDA image cache inputs and reuse published ancestors` | infra,nvidia,perf | main | - |
| - | [#64720](https://github.com/vllm-project/vllm/pull/64720) `[ROCm][Perf][Qwen3.8] Keep dense mono K2 on during MTP verify.` | infra,perf,rocm | main | - |
| - | [#64721](https://github.com/vllm-project/vllm/pull/64721) `[Feature][Frontend] Accept forwarded multimodal features with reused prompt token ids` |  | main | - |
| - | [#64722](https://github.com/vllm-project/vllm/pull/64722) `[ROCm][MoRIIO] Support DCP for decode instance in PD disaggregated serving with MoRI WRITE mode` | rocm | main | - |
| - | [#64724](https://github.com/vllm-project/vllm/pull/64724) `[Perf] Fused SynthID-Text sampling with bucketed tournament layers` | perf | main | - |
| - | [#64725](https://github.com/vllm-project/vllm/issues/64725) `[RFC]: Integrating LeapQuant into vLLM — INT8 Quantization of GDN/KDA Linear Attention Recurrent States` | quant,rocm | ? | - |
| - | [#64726](https://github.com/vllm-project/vllm/pull/64726) `[Tests][MRV2] Test padded tokens get PAD slots` |  | main | - |
| - | [#64729](https://github.com/vllm-project/vllm/pull/64729) `[Rust Frontend] Let the server run over any `Llm`` |  | main | - |
| - | [#64730](https://github.com/vllm-project/vllm/pull/64730) `[Bugfix] Support PyTorch bin checkpoints in checkpoint_has_lm_head` | bug | main | - |
| - | [#64731](https://github.com/vllm-project/vllm/pull/64731) `[Perf][Kernel] Faster full-warp MoE top-k selection with redux.sync` | perf | main | - |
| - | [#64735](https://github.com/vllm-project/vllm/pull/64735) `[Refactor] Simplify GLM sparse indexer decode grouping with gather` | infra | main | - |
| - | [#64736](https://github.com/vllm-project/vllm/pull/64736) `[WIP] Rust engine http client backup` |  | main | - |
| - | [#64737](https://github.com/vllm-project/vllm/pull/64737) `[ROCm][Bugfix] Fix AITER shared-expert fusion routing for gate-less MoE (DeepSeek-V2-Lite)` | bug,perf,rocm | main | - |
| - | [#64738](https://github.com/vllm-project/vllm/pull/64738) `[Feature][Quantization] Support compressed-tensors FP8 Marlin cache restarts` | infra,nvidia,perf,quant | main | - |
| - | [#64739](https://github.com/vllm-project/vllm/pull/64739) `[Model Loader] Find safetensors shards listed in a subdirectory` |  | main | - |
| - | [#64741](https://github.com/vllm-project/vllm/pull/64741) `[Tests][MoE] Test bias and router weight are applied before the cast` |  | main | - |
| - | [#64742](https://github.com/vllm-project/vllm/pull/64742) `[Bugfix][Rust Frontend] Fix cancellation during request submission` | bug | main | - |
| - | [#64744](https://github.com/vllm-project/vllm/pull/64744) `[ROCm][Bugfix] W4A16 dense prefill cache: count cached allocator blocks as free in the budget check` | bug,perf,quant,rocm | main | - |
| - | [#64746](https://github.com/vllm-project/vllm/pull/64746) `[Perf][LoRA][MoE] Use problem-sized shrink/expand configs for MoE-LoRA batches of up to 256 tokens` | perf | main | - |
| - | [#64747](https://github.com/vllm-project/vllm/pull/64747) `[Kernel][LoRA][MoE] Keep the MoE-LoRA shrink/expand intermediate in fp32 and round the output once` | perf | main | - |
| - | [#64748](https://github.com/vllm-project/vllm/pull/64748) `[Perf][LoRA][MoE] Remove the small-batch fused MoE-LoRA kernel` | perf | main | - |
| - | [#64749](https://github.com/vllm-project/vllm/pull/64749) `[Bugfix] Fix DSA fusion budgets, RoPE capacity and NUMA startup` | bug,infra,perf | main | - |
| - | [#64750](https://github.com/vllm-project/vllm/pull/64750) `[Bugfix][Tool Parser] LFM2: constrain forced tool_choice to the native format and parse hyphenated tool names` | bug | main | - |
| - | [#64752](https://github.com/vllm-project/vllm/pull/64752) `[ROCm] Skip RTLD_GLOBAL libtorch_cpu.so promotion when HSA_TOOLS_LIB is set` | rocm | main | - |
| - | [#64753](https://github.com/vllm-project/vllm/pull/64753) `[Quantization][MoE] Keep CSF-compressed NVFP4 expert scales resident on B12X` | quant | main | - |
| - | [#64754](https://github.com/vllm-project/vllm/pull/64754) `[Perf][KV Offload] Speed up CPU-only Tiering startup` | perf | main | - |
| - | [#64756](https://github.com/vllm-project/vllm/pull/64756) `[KVConnector][MoRIIO] Keep the handshake listener alive on bad messages` | rocm | main | - |
| - | [#64761](https://github.com/vllm-project/vllm/issues/64761) `[Bug]: cu134 nightly image has conflicting PyTorch/Triton dependency metadata (aarch64)` | rocm | ? | - |
| - | [#64764](https://github.com/vllm-project/vllm/pull/64764) `[Perf][LoRA] Compute kernel metadata on the CPU to remove per-step GPU syncs` | perf | main | - |
| - | [#64765](https://github.com/vllm-project/vllm/pull/64765) `[Misc] Use the b12x package shipped with flashinfer-python` | infra,nvidia | main | - |
| - | [#64766](https://github.com/vllm-project/vllm/pull/64766) `[Bugfix][Kernel] Plan b12x NVFP4 W4A16 linear token counts at load time` | bug,perf,quant | main | - |
| - | [#64767](https://github.com/vllm-project/vllm/pull/64767) `[Quantization] Load ModelOpt NVFP4 W4A16 token embeddings in mixed-precision checkpoints` | infra,quant | main | - |
| - | [#64768](https://github.com/vllm-project/vllm/pull/64768) `[Bugfix][Rust Frontend] Fill files missing from a cached Hub snapshot instead of treating them as absent` | bug | main | - |
| - | [#64769](https://github.com/vllm-project/vllm/pull/64769) `[Recipe] Add RedHatAI checkpoints and speculators for Qwen3` | infra | main | - |
| - | [#64770](https://github.com/vllm-project/vllm/pull/64770) `[Recipe] Add RedHatAI Qwen3.8 checkpoint variants` | infra | main | - |
| - | [#64771](https://github.com/vllm-project/vllm/pull/64771) `[Recipe] Add RedHatAI QwQ and Qwen3-VL recipe support` | infra | main | - |
| - | [#64772](https://github.com/vllm-project/vllm/pull/64772) `[Recipe] Add RedHatAI Llama 3 FP8 variants` | infra,quant | main | - |
| - | [#64773](https://github.com/vllm-project/vllm/pull/64773) `[Recipe] Add RedHatAI GLM variants and DSpark preview` | infra | main | - |
| - | [#64774](https://github.com/vllm-project/vllm/pull/64774) `[Recipe] Add RedHatAI speculative decoders for Gemma 4 and GPT-OSS` | infra | main | - |
| - | [#64775](https://github.com/vllm-project/vllm/pull/64775) `[Recipe] Add RedHatAI quantized variants for additional models` | infra,quant | main | - |
| - | [#64776](https://github.com/vllm-project/vllm/issues/64776) `[RFC]: Single Batch Overlap (down GEMM ↔ combine) for DeepEP LL` | nvidia,perf | ? | - |
| - | [#64777](https://github.com/vllm-project/vllm/pull/64777) `[Bugfix][Spec Decode] Use the target's kernel block sizes for EAGLE draft attention` | bug,perf | main | - |
| - | [#64780](https://github.com/vllm-project/vllm/issues/64780) `[RFC]: DBO support for FlashInfer NVLink all-to-all backends (single-node H200/B200 first)` | nvidia | ? | - |
| - | [#64783](https://github.com/vllm-project/vllm/pull/64783) `[Attention] Support `fp8_ds_mla` in Triton MLA on Ampere` | infra,rocm | main | - |
| - | [#64784](https://github.com/vllm-project/vllm/pull/64784) `[ROCm][CI] Fix GPU memory startup flakes in PP and sleep mode tests` | bug,infra,nvidia,rocm | main | - |
| - | [#64785](https://github.com/vllm-project/vllm/pull/64785) `[ROCm][KV Connector] Add MoRIIO transfer stats and Prometheus metrics` | rocm | main | - |
| - | [#64786](https://github.com/vllm-project/vllm/pull/64786) `[Bugfix][Distributed] Wake MessageQueue readers on shutdown` | bug | main | - |
| - | [#64787](https://github.com/vllm-project/vllm/pull/64787) `[MoE][DBO] Support DBO with the FlashInfer NVLink two-sided all2all` | nvidia | main | - |
| - | [#64789](https://github.com/vllm-project/vllm/issues/64789) `[Bug]: Responses API rejects `input_text` content for Mistral Large 4 with --tokenizer-mode mistral` | bug | ? | - |
| - | [#64790](https://github.com/vllm-project/vllm/issues/64790) `[Bug]: In-tree LMCache integration can't be imported with lmcache >= 0.5.6` |  | ? | - |
| - | [#64791](https://github.com/vllm-project/vllm/issues/64791) `[Performance][ROCm]: set HSA_SCRATCH_SINGLE_LIMIT in the ROCm image: per-dispatch scratch allocation costs ~13` | perf,rocm | ? | - |
| - | [#64793](https://github.com/vllm-project/vllm/issues/64793) `[Bug]: Responses API rejects `developer` role for Mistral Large 4 with --tokenizer-mode mistral` | bug | ? | - |
| - | [#64794](https://github.com/vllm-project/vllm/pull/64794) `[ROCm][DSv4.1] Read V4.1 KV records in Mono decode on gfx950` | infra,rocm | main | - |
| - | [#64795](https://github.com/vllm-project/vllm/pull/64795) `[CI] Say which steps stay out of automatic sharding, and why` | infra | main | - |
| - | [#64796](https://github.com/vllm-project/vllm/pull/64796) `[CI][Do not merge yet] Turn automatic sharding on by default` | infra,nvidia | main | - |
| - | [#64799](https://github.com/vllm-project/vllm/pull/64799) `[CI][Do not merge] Staging: flag combinations for default-on sharding` | infra,nvidia | main | - |
| - | [#64801](https://github.com/vllm-project/vllm/issues/64801) `[Feature]: Accept the global DP rank in X-data-parallel-rank under hybrid/external LB` |  | ? | - |
| - | [#64808](https://github.com/vllm-project/vllm/issues/64808) `[Bug]: Gemma-4 MTP halves prefix-cache hits with `--prefix-cache-retention-interval`` | bug,perf | ? | - |
| - | [#64809](https://github.com/vllm-project/vllm/issues/64809) `[Bug]: `raw_logprobs` are computed after the structured-output grammar mask` | bug | ? | - |
| - | [#64810](https://github.com/vllm-project/vllm/issues/64810) `[Feature]: Anthropic-defined tools (web_search, bash, text_editor, ...) in /v1/messages` |  | ? | - |
| - | [#64813](https://github.com/vllm-project/vllm/pull/64813) `[Bugfix][Docker] Preserve source-built Triton in downstream uv installs` | bug,infra,nvidia,rocm | main | - |
| - | [#64817](https://github.com/vllm-project/vllm/pull/64817) `[Perf][Kimi] Run one packed prefill convolution` | infra,perf | main | - |
| - | [#64818](https://github.com/vllm-project/vllm/pull/64818) `[XPU] Use xccl2 backend for XPU distributed communication` | nvidia | main | - |
| - | [#64822](https://github.com/vllm-project/vllm/pull/64822) `[Perf][Model] Muse vision encoders: no GPU<->CPU syncs, build Glimmer's vision prep once per call` | infra,perf | main | - |
| - | [#64823](https://github.com/vllm-project/vllm/pull/64823) `[ROCm][Perf][GLM-5.3-Flash] mxfp4_mla: native gfx950 kernel for prefill and mixed steps (on #64323)` | infra,perf,quant,rocm | main | - |
| - | [#64824](https://github.com/vllm-project/vllm/issues/64824) `[Feature]: Close the remaining DeepGEMM (and other kernel-library) runtime-JIT gaps in kernel warmup` | perf | ? | - |
| - | [#64825](https://github.com/vllm-project/vllm/pull/64825) `[Perf] Capture prefill-sized CUDA graphs by default for Qwen3.5` | nvidia,perf | main | - |
| - | [#64827](https://github.com/vllm-project/vllm/pull/64827) `[DeepSeek-V4] Warm up DeepGEMM fp8_einsum for the o_proj` |  | main | - |
| - | [#64829](https://github.com/vllm-project/vllm/pull/64829) `[CPU][Perf] Speed up GDN speculative-decode recurrent update` | perf | main | - |
| - | [#64832](https://github.com/vllm-project/vllm/pull/64832) `[Model] Add SenseNova Loop support` | infra,perf | main | - |
| - | [#64834](https://github.com/vllm-project/vllm/pull/64834) `[CI][XPU] Use supported block sizes in UCX backend tests` | infra,nvidia | main | - |
| - | [#64837](https://github.com/vllm-project/vllm/pull/64837) `[Tests] Handle Triton async compile cleanup callback` | rocm | main | - |
| - | [#64840](https://github.com/vllm-project/vllm/pull/64840) `[Bugfix] Size the default GDN recurrent beta by value heads` | bug | main | - |
| - | [#64842](https://github.com/vllm-project/vllm/pull/64842) `[Bugfix][NixlPush] Supervise the push writer thread (W2)` | bug | main | - |
| - | [#64843](https://github.com/vllm-project/vllm/pull/64843) `[Bugfix][Core] Widen EAGLE periodic SWA tails so a diverging sibling keeps its prefix-cache hit` | bug,perf | main | - |
| - | [#64844](https://github.com/vllm-project/vllm/pull/64844) `[Spec Decode][MRV2] Speculative round contract for custom speculators` | nvidia,perf | main | - |
| - | [#64846](https://github.com/vllm-project/vllm/pull/64846) `[Perf] Launch the Qwen GDN decode and Triton fused-MoE kernels with PDL` | perf,rocm | main | - |
| - | [#64847](https://github.com/vllm-project/vllm/pull/64847) `[XPU] Add tests for DCP and cache op` | infra,nvidia,perf | main | - |
| - | [#64848](https://github.com/vllm-project/vllm/pull/64848) `[Test] Check supported-models docs against model registry` |  | main | - |
| - | [#64849](https://github.com/vllm-project/vllm/pull/64849) `[Test] Add unit tests for math_utils helpers` |  | main | - |
| - | [#64850](https://github.com/vllm-project/vllm/pull/64850) `[Test] Add tests for collection_utils helpers` |  | main | - |
| - | [#64851](https://github.com/vllm-project/vllm/pull/64851) `[Frontend][Responses] Accept input_audio content parts in user messages (#47659)` |  | main | - |
| - | [#64853](https://github.com/vllm-project/vllm/issues/64853) `[Feature]: Allow `reset_prefix_cache` to clear cached prefixes without preempting running requests` |  | ? | - |
| - | [#64854](https://github.com/vllm-project/vllm/pull/64854) `[Kernel][Fusion] Fuse tanh-GELU gated activation with static FP8 quant` | perf,quant | main | - |
| - | [#64855](https://github.com/vllm-project/vllm/issues/64855) `[Bug] Sparse-attention indexer: native padded decode (`requires_padding`) gives wrong logits/top-k on ragged s` | rocm | ? | - |
| - | [#64857](https://github.com/vllm-project/vllm/pull/64857) `[ROCm][Perf] gfx942 sparse MLA decode: load e8m0 scales once per 64 columns, BLOCK_K 16` | perf,quant,rocm | main | - |
| - | [#64858](https://github.com/vllm-project/vllm/pull/64858) `[Frontend] support anthropic-defined client tools on /v1/messages` |  | main | - |
| - | [#64859](https://github.com/vllm-project/vllm/issues/64859) `[Bug]: Bidirectional NIXL: prefill-side request hangs in WAITING_FOR_REMOTE_KVS after its first D->P pull` | bug | ? | - |
| - | [#64860](https://github.com/vllm-project/vllm/pull/64860) `[Bugfix][NIXL] Fix bidirectional P-side hang after the first D->P pull` | bug | main | - |
| - | [#64861](https://github.com/vllm-project/vllm/pull/64861) `[Bugfix] Require mistral-common 1.13.1 for `developer` role support` | bug,infra | main | - |
| - | [#64862](https://github.com/vllm-project/vllm/pull/64862) `[Rust Frontend] Support beam search (use_beam_search, length_penalty)` | infra | main | - |
| - | [#64863](https://github.com/vllm-project/vllm/pull/64863) `[CPU] Move CPU-backend-only op wrappers into vllm/_cpu_ops.py` | infra,perf | main | - |
| - | [#64865](https://github.com/vllm-project/vllm/pull/64865) `[Feature][Core] Reset prefix cache without preempting running requests` | perf | main | - |
| - | [#64866](https://github.com/vllm-project/vllm/issues/64866) `[Feature]: [CI] Restore Ascend interface compatibility checks with locked test dependencies` | infra | ? | - |
| - | [#64867](https://github.com/vllm-project/vllm/pull/64867) `[Model][Doc] Add RTX PRO 6000 Blackwell support for DeepSeek-V4-Flash-Vision-Exp` | infra,nvidia | main | - |
| - | [#64870](https://github.com/vllm-project/vllm/pull/64870) `[Feat][BI][2/N] add batch-invariant DeepSeek V4 support (compressor)` | infra | main | - |
| - | [#64871](https://github.com/vllm-project/vllm/pull/64871) `[KV Connector][Mooncake] Share one transfer planner between the protocol directions` |  | main | - |
| - | [#64872](https://github.com/vllm-project/vllm/pull/64872) `[Kernel] Let --linear-backend deep_gemm override the DeepGemm model a…` | perf | main | - |
| - | [#64873](https://github.com/vllm-project/vllm/pull/64873) `[Config] Hash MambaConfig in the compile cache identity` | perf | main | - |
| - | [#64874](https://github.com/vllm-project/vllm/issues/64874) `[Bug]: [ROCm][GLM-5.3-Flash]: "Workspace is locked" AssertionError in rocm_fp8_paged_mqa_logits under high dec` | bug,rocm | ? | - |
| - | [#64875](https://github.com/vllm-project/vllm/pull/64875) `[Bugfix][Prefix] Skip EAGLE block drop for KV-shared drafters + widen periodic SWA tail` | bug,perf | main | - |
| - | [#64876](https://github.com/vllm-project/vllm/pull/64876) `[CI] Fix mHC numerical test portability across GPU architectures` | bug,infra | main | - |
| - | [#64877](https://github.com/vllm-project/vllm/pull/64877) `[Frontend] Accept managed global DP ranks in request headers` |  | main | - |
| - | [#64878](https://github.com/vllm-project/vllm/pull/64878) `[Bugfix][MRV2] Preserve MTP query lengths in idle DP batches` | bug,infra | main | - |
| - | [#64879](https://github.com/vllm-project/vllm/pull/64879) `[Frontend] Return Anthropic-format errors for request validation on /v1/messages` |  | main | - |
| - | [#64881](https://github.com/vllm-project/vllm/pull/64881) `[Kernel][XPU] Tensor-descriptor Q loads in Triton MLA decode attention` | nvidia,perf,rocm | main | - |
| - | [#64882](https://github.com/vllm-project/vllm/issues/64882) `[Bug]: Multimodal video loaders ignore --media-io-kwargs num_frames` | bug | ? | - |
| - | [#64883](https://github.com/vllm-project/vllm/pull/64883) `[ROCm][Perf][DSv4.1] Mono: tuned K2 FFN seam at TP4 / TP8` | perf,rocm | main | - |
| - | [#64884](https://github.com/vllm-project/vllm/pull/64884) `[Feat][BI][3/N] add batch-invariant DeepSeek V4 support (mHC)` |  | main | - |
| - | [#64887](https://github.com/vllm-project/vllm/pull/64887) `[Bugfix][DSA] Disable native padded decode on ragged spec-decode batches (#64855)` | bug | main | - |
| - | [#64888](https://github.com/vllm-project/vllm/pull/64888) `[Bugfix][ROCm] Fix AITER FA extend_forward zero-chunk and drafter KV workspace (#64680)` | bug,rocm | main | - |
| - | [#64889](https://github.com/vllm-project/vllm/pull/64889) `[Bugfix][Compile] Support distinct attention geometries in RopeKVCacheFusionPass (#64679)` | bug,perf | main | - |
| - | [#64890](https://github.com/vllm-project/vllm/pull/64890) `[Perf][Attention] Cache TritonAttentionImpl K/V cache views per tensor (#64572)` | perf | main | - |
| - | [#64891](https://github.com/vllm-project/vllm/pull/64891) `[Security] Gate NIXL remote-decode pulls on bidirectional transfer` | infra | main | - |
| - | [#64892](https://github.com/vllm-project/vllm/pull/64892) `[Perf][DSv4.1] Overlap mHC coefficients behind the fused all-reduce on SM90` | nvidia,perf | main | - |
| - | [#64893](https://github.com/vllm-project/vllm/pull/64893) `[Perf][DSv4.1] DeepSeek-V4.1-Flash specialized decode on Hopper (H200 TP4)` | infra,nvidia,perf | main | - |
| - | [#64894](https://github.com/vllm-project/vllm/pull/64894) `[Bugfix][ROCm] Fall back to torch.cuda in RocmPlatform when AMDSMI cannot init (#64664)` | bug,nvidia,rocm | main | - |
| - | [#64895](https://github.com/vllm-project/vllm/pull/64895) `[Bugfix][KV Connector][Mooncake] Coalesce in-flight lease heartbeats` | bug | main | - |
| - | [#64896](https://github.com/vllm-project/vllm/pull/64896) `[Bugfix][DSA] Skip sparse indexer prefill work for empty chunks` | bug,infra | main | - |
| - | [#64897](https://github.com/vllm-project/vllm/pull/64897) `[Bugfix][Spec Decode][XPU] greedy_argmax: treat NaN as -inf on the torch fallback` | bug,nvidia,risk | main | - |
| - | [#64899](https://github.com/vllm-project/vllm/pull/64899) `[Bugfix][Multimodal] Honour explicit num_frames in Qwen-VL video loaders` | bug | main | - |
| - | [#64900](https://github.com/vllm-project/vllm/pull/64900) `Allow reset_prefix_cache to clear cached prefixes without preempting running requests` | perf | main | - |
| - | [#64901](https://github.com/vllm-project/vllm/pull/64901) `[Model] DeepSeek-V4.1: zero frozen FP8 Engram tables in place in the dummy loader` | quant | main | - |
| - | [#64902](https://github.com/vllm-project/vllm/pull/64902) `[MoE] Release cached allocator blocks before mapping MegaMoE symmetric memory` | infra | main | - |
| - | [#64903](https://github.com/vllm-project/vllm/pull/64903) `[Bugfix][MoE] Avoid double router weighting in TRTLLM FP8 experts` | bug,nvidia,quant | main | - |
| - | [#64904](https://github.com/vllm-project/vllm/pull/64904) `[Bugfix][Structured Output] Preserve raw scores before grammar masking` | bug | main | - |
| - | [#64905](https://github.com/vllm-project/vllm/pull/64905) `[Perf][MoE] Let GateLinear's low-latency router GEMM serve bf16-output routers` | perf | main | - |
| - | [#64906](https://github.com/vllm-project/vllm/pull/64906) `[Perf][MoE] Keep fp32 activation scales on the Triton FP8 experts and re-enable their fused SiLU+quant path` | perf,quant,rocm | main | - |
| - | [#64908](https://github.com/vllm-project/vllm/pull/64908) `[Misc] Remove dead torch < 2.11 version checks and workarounds` | infra,nvidia,quant | main | - |
| - | [#64917](https://github.com/vllm-project/vllm/pull/64917) `[ROCm][Perf][DSv4.1] Balance the FP8 paged decode indexer across rows` | perf,quant,rocm | main | - |
| - | [#64918](https://github.com/vllm-project/vllm/pull/64918) `[Security] Require trust for remote prefill cache accounting` | perf | main | - |
| - | [#64921](https://github.com/vllm-project/vllm/pull/64921) `[Bugfix][Model] DeepSeek-V4.1: keep decoder replay off when its cut cannot be replayed` | bug,infra | main | - |
| - | [#64922](https://github.com/vllm-project/vllm/pull/64922) `[Bugfix][Model] DeepSeek-V4.1: keep load permutations and Engram peer handles out of the sleep weights pool` | bug | main | - |
| - | [#64923](https://github.com/vllm-project/vllm/pull/64923) `[Bugfix][V2 runner] Keep idle-DP dummy requests within max_model_len` | bug | main | - |
| - | [#64924](https://github.com/vllm-project/vllm/pull/64924) `[KV Connector] Remove the in-tree LMCache integration package` |  | main | - |
| - | [#64925](https://github.com/vllm-project/vllm/pull/64925) `[XPU][Qwen4Exp] Run the QSA side-cache ops and indexer prepare on XPU` | nvidia,perf | main | - |
| - | [#64926](https://github.com/vllm-project/vllm/pull/64926) `[XPU][Qwen4Exp] Run QSA block selection on XPU` | nvidia | main | - |
| - | [#64927](https://github.com/vllm-project/vllm/pull/64927) `[Core][Scheduler] Add an opt-in time-bounded prefill hold` |  | main | - |
| - | [#64928](https://github.com/vllm-project/vllm/pull/64928) `[ROCm][Multimodal] FP8 ViT attention: opt-in AITER asm path (head_dim padded to 128); single-writer scale file` | nvidia,quant,rocm | main | - |
| - | [#64929](https://github.com/vllm-project/vllm/pull/64929) `[ROCm] Add VLLM_ROCM_USE_AITER_QUICK_REDUCE to keep INT4 QuickReduce on the HIP kernel` | perf,quant,rocm | main | - |
| - | [#64930](https://github.com/vllm-project/vllm/pull/64930) `[ROCm][DBO] QuickReduce and SDMA INT4 all-reduce for pure-TP microbatches` | quant,rocm | main | - |
| - | [#64931](https://github.com/vllm-project/vllm/pull/64931) `[Bugfix][Benchmark] Fix timeline export at rounded minute boundaries` | bug,perf | main | - |
| - | [#64932](https://github.com/vllm-project/vllm/pull/64932) `[Bugfix][MoE] Fix MiniMax-M3.1 NVFP4 experts failing to load on Hopper` | bug,infra,nvidia,quant | main | - |
| - | [#64933](https://github.com/vllm-project/vllm/pull/64933) `[Bugfix] Spawn workers when CUDA forward compatibility is enabled` | bug,infra,nvidia | main | - |
| - | [#64936](https://github.com/vllm-project/vllm/issues/64936) `[Bug]: NCCL weight sync: packed transfer fails to unpack misaligned tensors (pack_tensors has no alignment)` | bug,nvidia | ? | - |
| - | [#64938](https://github.com/vllm-project/vllm/issues/64938) `[Bug]: [RFE] Decode context parallelism: fail-fast with the valid DCP set, or support `--decode-context-parall` | bug | ? | - |
| - | [#64940](https://github.com/vllm-project/vllm/issues/64940) `[Bug]: Responses API 500s on assistant message with empty content list` | bug | ? | - |
| - | [#64941](https://github.com/vllm-project/vllm/pull/64941) `[Frontend][Responses] Reject empty assistant message content with 400 instead of 500` |  | main | - |
| - | [#64942](https://github.com/vllm-project/vllm/pull/64942) `[Perf][Attention] Add bounded FP8 page expansion for native prefill` | nvidia,perf,quant | main | - |
| - | [#64943](https://github.com/vllm-project/vllm/pull/64943) `[Bugfix] Show topology-compatible DCP values in configuration errors` | bug | main | - |
| - | [#64945](https://github.com/vllm-project/vllm/pull/64945) `[Bugfix][KVConnector] Fix Mooncake save offset stalls with evicted SWA blocks` | bug | main | - |
| - | [#64947](https://github.com/vllm-project/vllm/pull/64947) `[Bugfix] Include MoE routes in adaptive verification cost profiling` | bug | main | - |
| - | [#64948](https://github.com/vllm-project/vllm/pull/64948) `[Spec Decode] Avoid redundant EAGLE3 auxiliary concatenation with fc_norm` |  | main | - |
| - | [#64949](https://github.com/vllm-project/vllm/pull/64949) `[Bugfix][Kernel] Synchronize Marlin MoE shared-buffer reuse` | bug,perf,quant | main | - |
| - | [#64950](https://github.com/vllm-project/vllm/pull/64950) `[Spec Decode] Add an independent first-draft graph ceiling` | infra,nvidia | main | - |
| - | [#64951](https://github.com/vllm-project/vllm/pull/64951) `[Bugfix][Spec Decode] Preserve windowed draft AOT guard after cache promotion` | bug,infra,perf | main | - |
| - | [#64952](https://github.com/vllm-project/vllm/issues/64952) `[Feature]: Add pipeline parallelism support for Qwen3.8-Flash-Next (Qwen4Exp)` |  | ? | - |
| - | [#64954](https://github.com/vllm-project/vllm/issues/64954) `[Bug]: `--attention-backend TORCH_SDPA` passes config validation, then dies with "Backend TORCH_SDPA must be r` | bug | ? | - |
| - | [#64956](https://github.com/vllm-project/vllm/issues/64956) `[Bug]: kv_cache_dtype="turboquant_3bit_nc" crashes on Phi-2 (head_size=80) — supports_head_size() claims "any ` | bug,quant | ? | - |
| - | [#64957](https://github.com/vllm-project/vllm/pull/64957) `feat(compilation): add MoE FlashInfer fusion pass for kMoEFinalizeARResidualRMSNorm (#40544)` | nvidia,perf | main | - |
| - | [#64961](https://github.com/vllm-project/vllm/pull/64961) `[Bugfix][Frontend] Convert Responses content parts to chat parts` | bug | main | - |
| - | [#64962](https://github.com/vllm-project/vllm/pull/64962) `[Bugfix][Tool Parser] Fix hunyuan_a13b streaming arguments with braces and deep nesting` | bug | main | - |
| - | [#64963](https://github.com/vllm-project/vllm/pull/64963) `[Bugfix] Preserve cross-encoder pair boundaries during explicit truncation` | bug,risk | main | - |
| - | [#64964](https://github.com/vllm-project/vllm/pull/64964) `[Security] Keep prefill truncation state internal to each request` | risk | main | - |
| - | [#64965](https://github.com/vllm-project/vllm/pull/64965) `[Bugfix][Attention] Reject TORCH_SDPA for decoder attention` | bug | main | - |
| - | [#64966](https://github.com/vllm-project/vllm/pull/64966) `[Doc] Document streaming cancellation and KV cache reclamation in online server` | perf | main | - |
| - | [#64967](https://github.com/vllm-project/vllm/pull/64967) `[Quantization][Attention] Enforce power-of-two head size validation in TurboQuant attention` | quant | main | - |
| - | [#64969](https://github.com/vllm-project/vllm/pull/64969) `[ROCm][Perf] Run fp8 DCP cprr MLA verify at 96 native heads when AITER supports it` | perf,quant,rocm | main | - |
| - | [#64970](https://github.com/vllm-project/vllm/pull/64970) `[Bugfix][GDN] Preserve Torch exp precision in fused prefill` | bug,infra,nvidia,perf | main | - |
| - | [#64972](https://github.com/vllm-project/vllm/issues/64972) `[Bug]: CudaPlatform.log_warnings() aborts startup on an unqueryable NVML device even when CUDA_VISIBLE_DEVICES` |  | ? | - |
| - | [#64973](https://github.com/vllm-project/vllm/issues/64973) `[RFC]: Hybrid KV Backend: Eliminating Disk Restore Pipeline Bubbles Without CPU Memory Bloat` |  | ? | - |
| - | [#64975](https://github.com/vllm-project/vllm/pull/64975) `[Core][Perf] Evict superseded Mamba align states first` | perf | main | - |
| - | [#64976](https://github.com/vllm-project/vllm/pull/64976) `[Bugfix][Kernel] Honor batched and strided SwiGLU clamp inputs` | bug,infra,perf | main | - |
| - | [#64978](https://github.com/vllm-project/vllm/pull/64978) `[Perf][MoE] Skip the token-count load on the low-latency fused-MoE path` | perf | main | - |
| - | [#64979](https://github.com/vllm-project/vllm/pull/64979) `[Perf] Add SM90 skinny GEMM plans for dense Qwen3 and Llama-3.1 decode (TP=1)` | nvidia,perf | main | - |
| - | [#64980](https://github.com/vllm-project/vllm/pull/64980) `[Perf] W8A16 skinny GEMM for block-FP8 linear layers at 1-4 tokens on Hopper` | nvidia,perf,quant | main | - |
| - | [#64981](https://github.com/vllm-project/vllm/pull/64981) `[Perf] Enable PDL for Inductor-generated Triton kernels in 'interactivity' performance mode` | perf,rocm | main | - |
| - | [#64982](https://github.com/vllm-project/vllm/pull/64982) `[Perf] Skinny GEMM: eager fast path and SM90 plans for the Qwen3.5 MoE BF16 projections` | nvidia,perf | main | - |
| - | [#64983](https://github.com/vllm-project/vllm/pull/64983) `[Perf][MoE] Grouped W8A16 skinny GEMM for block-FP8 routed experts at small token counts (SM90)` | nvidia,perf,quant | main | - |
| - | [#64987](https://github.com/vllm-project/vllm/pull/64987) `[Misc] Skip other ranks' weights before weights transforms` | quant | main | - |
| - | [#64991](https://github.com/vllm-project/vllm/pull/64991) `[Bugfix][Core] Abort requests still running at the --shutdown-timeout drain deadline` | bug | main | - |
| - | [#64994](https://github.com/vllm-project/vllm/pull/64994) `[Perf][DCP] Up-project the MLA decode output before the A2A merge` | infra,perf | main | - |
| - | [#64995](https://github.com/vllm-project/vllm/pull/64995) `[Docs] Add drain shutdown section to Kubernetes deployment guide` |  | main | - |
| - | [#64996](https://github.com/vllm-project/vllm/pull/64996) `[Kernel] Honor ND group FP8 input contract` | perf,quant | main | - |
| - | [#64997](https://github.com/vllm-project/vllm/issues/64997) `[Frontend]: Render requests: keep mm_metadata in the response when the tensors are omitted` |  | ? | - |
| - | [#64998](https://github.com/vllm-project/vllm/pull/64998) `[Rust Frontend] add `/v1/messages` support` |  | main | - |
| - | [#65003](https://github.com/vllm-project/vllm/pull/65003) `[WIP][Quantization] Triton kernels for ModelOpt IQ2_XXS / Q8_0 block weights on SM75+` | infra,perf,quant,rocm | main | - |
| - | [#65004](https://github.com/vllm-project/vllm/pull/65004) `[Perf][Sampler] Histogram-bracket top-p for large p-only batches` | perf | main | - |
| - | [#65006](https://github.com/vllm-project/vllm/pull/65006) `[Model] Nemotron-H: serve FP8 linears as W8A16 with bf16_activations` | quant | main | - |
| - | [#65007](https://github.com/vllm-project/vllm/pull/65007) `[Perf][Spec Decode] Vocab-parallel DSpark Markov sampling and vocab-sharded verification over TP` | infra,perf | main | - |
| - | [#65009](https://github.com/vllm-project/vllm/pull/65009) `[Bugfix][Distributed] Unpack misaligned packed tensors` | bug | main | - |
| - | [#65010](https://github.com/vllm-project/vllm/pull/65010) `[CPU][MRV2] Reuse cross-group metadata in the builders, as on GPU` |  | main | - |
| - | [#65011](https://github.com/vllm-project/vllm/pull/65011) `[Feature][Parser] Stream strict nested string arguments in Qwen XML` | infra | main | - |
| - | [#65012](https://github.com/vllm-project/vllm/pull/65012) `[Bugfix][Kernel] Check pointer alignment before vectorizing activation kernels` | bug,perf | main | - |
| - | [#65013](https://github.com/vllm-project/vllm/pull/65013) `[Perf][DSv4.1] Skip Q computation in replay KV prewrite` | infra,perf | main | - |
| - | [#65014](https://github.com/vllm-project/vllm/issues/65014) `[Feature]: Update tilelang to 0.1.15` |  | ? | - |
| - | [#65015](https://github.com/vllm-project/vllm/pull/65015) `[Bugfix][Tool Parser] Keep granite4 streamed text between tool calls` | bug | main | - |
| - | [#65016](https://github.com/vllm-project/vllm/pull/65016) `[Multimodal] Faster multimodal input path under concurrent image traffic (parallel preprocessing + sizable shm` | perf | main | - |
| - | [#65018](https://github.com/vllm-project/vllm/pull/65018) `[Feature][Frontend] Add metadata value to mm_payload on render requests` |  | main | - |
| - | [#65019](https://github.com/vllm-project/vllm/pull/65019) `[Bugfix][Parser] DeepSeek V4.1: treat DSML markers as structure only from the DSML token` | bug | main | - |
| - | [#65020](https://github.com/vllm-project/vllm/pull/65020) `[Bugfix] Tolerate NVML device query failures in startup diagnostics` | bug,infra,nvidia | main | - |
| - | [#65021](https://github.com/vllm-project/vllm/pull/65021) `[Doc][ROCm] Add verified MI300X/MI325X entries to Qwen3.8-27B recipe` | infra,rocm | main | - |
| - | [#65022](https://github.com/vllm-project/vllm/pull/65022) `[ROCm][Bugfix] Keep AITER MLA split metadata alive for CUDA graph replay` | bug,nvidia,rocm | main | - |
| - | [#65024](https://github.com/vllm-project/vllm/pull/65024) `[Security] Restrict EC NIXL reads to configured producer peers` | infra | main | - |
| - | [#65026](https://github.com/vllm-project/vllm/pull/65026) `[Feature][Kernel] Add opt-in CuTe DSL compile and AOT caches` | infra,perf | main | - |
| - | [#65027](https://github.com/vllm-project/vllm/pull/65027) `[Model] Support Nemotron Lightning structured decisions` |  | main | - |
| - | [#65028](https://github.com/vllm-project/vllm/pull/65028) `[Perf][Rust Frontend] Serialize SSE chunks before building the event` | perf | main | - |
| - | [#65029](https://github.com/vllm-project/vllm/pull/65029) `[Bugfix][Frontend] Report the line of a run-batch request rejected by request validators` | bug | main | - |
| - | [#65034](https://github.com/vllm-project/vllm/issues/65034) `[Bug]: Quark `exclude` entries written as weight names (e.g. `mtp.fc.weight`) are silently never matched, brea` | bug,quant,risk,rocm | ? | - |
| - | [#65037](https://github.com/vllm-project/vllm/pull/65037) `[Perf][Frontend] Append Responses streaming text in place` | perf | main | - |
| - | [#65038](https://github.com/vllm-project/vllm/pull/65038) `feat(metrics): add per-step copy-on-write KV block counter` |  | main | - |
| - | [#65039](https://github.com/vllm-project/vllm/pull/65039) `[Doc] Use the dash-separated CLI flag names in scoring and tool-calling docs` |  | main | - |
| - | [#65040](https://github.com/vllm-project/vllm/pull/65040) `[Doc] Use the dash-separated CLI flag names in the remaining docs` |  | main | - |
| - | [#65042](https://github.com/vllm-project/vllm/issues/65042) `[Doc]: Docs use CLI flag names that `vllm serve` does not register` |  | ? | - |
| - | [#65043](https://github.com/vllm-project/vllm/pull/65043) `[Doc] Add Apple Silicon (Metal) weight compatibility note to the Apple install page` |  | main | - |
| - | [#65048](https://github.com/vllm-project/vllm/issues/65048) `[CI Failure]: MI300 MoE Kernels Multi-GPU - MoriEPv2 combine block_num 304 exceeds xdb_flag_slots 256 in test_` | infra,perf,rocm | ? | - |
| - | [#65049](https://github.com/vllm-project/vllm/pull/65049) `[ModelRunner V2] Accumulate chunked prompt logprobs on the host` |  | main | - |
| - | [#65052](https://github.com/vllm-project/vllm/pull/65052) `[BI] Add the batch-invariant CUDA op library` | infra,nvidia | main | - |
| - | [#65053](https://github.com/vllm-project/vllm/pull/65053) `[BI][DSv4.1] Make dense projections, norms and logprobs batch invariant` | infra,nvidia | main | - |
| - | [#65054](https://github.com/vllm-project/vllm/issues/65054) `[Feature]: GDN prefill on SM110 (Jetson Thor): use the CuteDSL and FlashInfer kernels` | nvidia,perf | ? | - |
| - | [#65056](https://github.com/vllm-project/vllm/issues/65056) `[RFC]: Selected input-row hidden-state export for full-vocabulary OPD teachers` | quant | ? | - |
| - | [#65057](https://github.com/vllm-project/vllm/pull/65057) `[Frontend][Reference only] Expose min_tokens and ignore_eos in Messages API` |  | main | - |
| - | [#65058](https://github.com/vllm-project/vllm/pull/65058) `[Bugfix][Kernel] Fix two block-FP8 linear crashes on SM12x` | bug,nvidia,perf,quant | main | - |
| - | [#65061](https://github.com/vllm-project/vllm/pull/65061) `[BI][DSv4.1] Make FlashMLA sparse attention and the indexer batch invariant` | infra,nvidia | main | - |
| - | [#65062](https://github.com/vllm-project/vllm/pull/65062) `[Bugfix][Test] Qwen4Exp QSA: run the fp8 kernel tests the way the layer does below sm_89` | bug,perf,quant | main | - |
| - | [#65063](https://github.com/vllm-project/vllm/pull/65063) `[Bugfix][P/D] Reject P/D kv_transfer_params with several prompts` | bug | main | - |
| - | [#65064](https://github.com/vllm-project/vllm/pull/65064) `[BI][DSv4.1] Make SWA bounded replay exact under batch invariance` | infra,nvidia,perf | main | - |
| - | [#65065](https://github.com/vllm-project/vllm/pull/65065) `[BI] Make DeepSeek MoE and the EP exchange batch invariant` | bug,infra,nvidia,perf,quant | main | - |
| - | [#65066](https://github.com/vllm-project/vllm/pull/65066) `[BI][DSv4.1] Run mHC on fixed-split TileLang kernels under batch invariance` | infra,nvidia,perf,quant | main | - |
| - | [#65067](https://github.com/vllm-project/vllm/pull/65067) `[BI][DSv4.1] Support DSpark speculative decoding under batch invariance` | infra,nvidia,perf,quant | main | - |
| - | [#65068](https://github.com/vllm-project/vllm/pull/65068) `[BI][DSv4.1] Add opt-in tensor-core GEMM tiers under batch invariance` | infra,nvidia,perf,quant | main | - |
| - | [#65069](https://github.com/vllm-project/vllm/pull/65069) `[BI][DSv4.1] Add opt-in Mega kernels under batch invariance` | infra,nvidia,perf,quant | main | - |
| - | [#65070](https://github.com/vllm-project/vllm/issues/65070) `[Bug]:  CPU WNA16 MoE cannot load poolside/Laguna-XS-2.1-INT4` | bug,quant | ? | - |
| - | [#65072](https://github.com/vllm-project/vllm/issues/65072) `[Bug]: ASRDataset uses channel count as duration when filtering stereo audio bytes` |  | ? | - |
| - | [#65073](https://github.com/vllm-project/vllm/issues/65073) `[Bug]: Duplicate MCP server names advertise tools from a different execution server` |  | ? | - |
| - | [#65074](https://github.com/vllm-project/vllm/issues/65074) `[Bug]: MCP tool discovery drops tools after the first tools/list page` |  | ? | - |
| - | [#65077](https://github.com/vllm-project/vllm/pull/65077) `[Perf][Quantization] Honor FP8 activations for Humming linear on SM100/SM110` | infra,nvidia,perf,quant | main | - |
| - | [#65078](https://github.com/vllm-project/vllm/pull/65078) `[ROCm][Perf][Qwen3.8] Dense mono decode on 128-CU gfx950 (MI350P)` | infra,perf,rocm | main | - |
| - | [#65079](https://github.com/vllm-project/vllm/pull/65079) `[Bugfix][EC] Reuse runner cache hits before remote admission` | bug,perf | main | - |
| - | [#65082](https://github.com/vllm-project/vllm/pull/65082) `[Perf][KV Offload] Vectorize direct-layout descriptor fill across layers` | perf | main | - |
| - | [#65084](https://github.com/vllm-project/vllm/pull/65084) `[Multimodal] Refactor encoder cuda graph to support share graph buffer reuse` | nvidia,rocm | main | - |
| - | [#65085](https://github.com/vllm-project/vllm/pull/65085) `[Bugfix][Benchmark] Derive forward benchmark batch budget from cases` | bug,perf | main | - |
| - | [#65086](https://github.com/vllm-project/vllm/pull/65086) `[Perf][Core] Optimize sliding-window prefix cache lookup with stride jumping` | perf | main | - |
| - | [#65089](https://github.com/vllm-project/vllm/pull/65089) `[Attention] Opt in to startup sizing of the FlashInfer workspace` | nvidia | main | - |
| - | [#65090](https://github.com/vllm-project/vllm/pull/65090) `[Bugfix][MCP] Keep first server's tools on duplicate server name` | bug | main | - |
| - | [#65092](https://github.com/vllm-project/vllm/pull/65092) `[Bugfix][ROCm] Reserve kpool decode indexer logits in workspace during profiling` | bug,rocm | main | - |
| - | [#65094](https://github.com/vllm-project/vllm/pull/65094) `[Bugfix][NIXL] Reject P/D pairs whose KV cache groups scale differently` | bug,perf,quant | main | - |
| - | [#65096](https://github.com/vllm-project/vllm/issues/65096) `[Bug]: Unbounded startup wait holds --data-parallel-rpc-port; crashed frontend leaves orphaned processes holdi` | bug | ? | - |
| - | [#65098](https://github.com/vllm-project/vllm/pull/65098) `[ROCm][Disagg][CI] Give Wide-EP headless nodes the MoRIIO KV config` | infra,rocm | main | - |
| - | [#65099](https://github.com/vllm-project/vllm/pull/65099) `[Feat] Add HALOps as an opt-in MXFP8 GEMM backend for Blackwell` | infra,nvidia,quant | main | - |
| - | [#65101](https://github.com/vllm-project/vllm/pull/65101) `[Kernel] Exact top-p cutoffs and kept log-sum-exps for bf16 logits` | infra,perf | main | - |
| - | [#65102](https://github.com/vllm-project/vllm/pull/65102) `[Perf][Spec Decode] Apply top-p cutoffs as target logits load in verification` | infra,perf | main | - |
| - | [#65103](https://github.com/vllm-project/vllm/pull/65103) `[Perf][Spec Decode] Take the target log-sum-exp from the top-p cutoff kernel` | infra,perf | main | - |
| - | [#65105](https://github.com/vllm-project/vllm/issues/65105) `[Bug]: [ROCm] AITER MLA `paged_kv_indices` sized max_num_seqs x max_model_len (4 GiB per builder) pins a cache` | infra,rocm | ? | - |
| - | [#65106](https://github.com/vllm-project/vllm/issues/65106) `[Bug]: [ROCm][Kimi-K3] DBO: MoE workspace locked smaller than the DP-gathered batch, first request fails` | rocm | ? | - |
| - | [#65107](https://github.com/vllm-project/vllm/pull/65107) `[CI/Build] Mirror release and nightly images to the vllm/vllm, vllm/vllm-rocm and vllm/vllm-xpu DockerHub alia` | infra,nvidia,rocm | main | - |
| - | [#65108](https://github.com/vllm-project/vllm/pull/65108) `[Bugfix][LoRA] Fix GPT-OSS triton_kernels 3.8 MoE LoRA row order` | bug | main | - |
| - | [#65110](https://github.com/vllm-project/vllm/pull/65110) `[Perf][HY4] Speed up the iHC pre reduction with M-blocked and split-K paths` | perf | main | - |
| - | [#65111](https://github.com/vllm-project/vllm/pull/65111) `[Bugfix][Model] Inkling: skip EP-alignment padding experts when loading expert weights` | bug | main | - |
| - | [#65112](https://github.com/vllm-project/vllm/issues/65112) `test_process_checkpoint: no coverage path for hybrid GDN models` |  | ? | - |
| - | [#65113](https://github.com/vllm-project/vllm/pull/65113) `[Test] Support hybrid GDN models in test_process_checkpoint` |  | main | - |
| - | [#65114](https://github.com/vllm-project/vllm/issues/65114) `[Bug]: vllm-rs chat render and native render select opposite thinking modes when a thinking toggle is combined` |  | ? | - |
| - | [#65115](https://github.com/vllm-project/vllm/issues/65115) `[Bug]: DeepSeek render parity — native appends EOS for continue_final_message, vllm-rs does not` |  | ? | - |
| - | [#65116](https://github.com/vllm-project/vllm/issues/65116) `[Bug]: DeepSeek tool-schema JSON omits "description": null in vllm-rs (native includes it)` |  | ? | - |
| - | [#65117](https://github.com/vllm-project/vllm/pull/65117) `[Feature] Add MXFP8 expert online quantization to DeepGEMM MegaMoE` | quant | main | - |
| - | [#65119](https://github.com/vllm-project/vllm/issues/65119) `[RFC]: DBO for the MTP/EAGLE drafter forward in Model Runner V2` |  | ? | - |
| - | [#65120](https://github.com/vllm-project/vllm/issues/65120) `[RFC]: DBO for the decoder of multimodal MoE models in Model Runner V2` |  | ? | - |
| - | [#65121](https://github.com/vllm-project/vllm/issues/65121) `[RFC]: DBO with the allgather_reducescatter all2all backend on CUDA` | nvidia | ? | - |
| - | [#65122](https://github.com/vllm-project/vllm/issues/65122) `[RFC]: Zero-copy DeepEP low-latency combine, safe under DBO` | nvidia,perf | ? | - |
| - | [#65123](https://github.com/vllm-project/vllm/pull/65123) `[Bugfix][EC] Republish runner cache hits after CPU-tier eviction` | bug,perf | main | - |
| - | [#65126](https://github.com/vllm-project/vllm/pull/65126) `[Bugfix][Frontend] Reject API keys for the Python gRPC server` | bug | main | - |
| - | [#65128](https://github.com/vllm-project/vllm/pull/65128) `[MORI][DBO] Dual batch overlap with MoRI EPv2 (native and AsyncLL), and DBO fixes` | nvidia,perf,rocm | main | - |
| - | [#65129](https://github.com/vllm-project/vllm/pull/65129) `[Bugfix][DSv4.1] Preserve BF16 Engram checkpoint tables` | bug | main | - |
| - | [#65130](https://github.com/vllm-project/vllm/pull/65130) `[Model Runner V2][Spec Decode] Draft token heads for block-diffusion speculators` | perf | main | - |
| - | [#65131](https://github.com/vllm-project/vllm/issues/65131) `[Bug]: Sync KV load-failure recovery triggers num_output_placeholders assertion on v0.29.0 and v0.32.0` | bug | ? | - |
| - | [#65132](https://github.com/vllm-project/vllm/pull/65132) `[ROCm][Perf] Build AITER MLA full-graph decode metadata in one kernel` | infra,perf,rocm | main | - |
| - | [#65133](https://github.com/vllm-project/vllm/pull/65133) `[Bugfix] shm_broadcast: unblock writer in acquire_write when shutdown` | bug | main | - |
| - | [#65134](https://github.com/vllm-project/vllm/pull/65134) `[ROCm][Perf] Add fused MoE config for Gemma 4 26B-A4B on MI350P` | perf,rocm | main | - |
| - | [#65135](https://github.com/vllm-project/vllm/issues/65135) `[Bug]: MessageQueue.shutdown() does not unblock writers blocked in acquire_write` | bug | ? | - |
| - | [#65136](https://github.com/vllm-project/vllm/pull/65136) `[Feature][NIXL] Add prefix cache reset to the toy proxy` | infra,perf | main | - |
| - | [#65137](https://github.com/vllm-project/vllm/pull/65137) `[Bugfix][KV Connector] Keep same-host NIXL on NVLink with the extensible KV cache` | bug,perf | main | - |
| - | [#65139](https://github.com/vllm-project/vllm/issues/65139) `[Bug]: b12x attention — CUDA illegal memory access at the first MTP verify step (cold-JIT `PagedForwardKernel`` | bug,nvidia,perf,quant,risk | ? | - |
| - | [#65141](https://github.com/vllm-project/vllm/issues/65141) `[Bug]: Second `vllm serve --grpc` on the same port starts fine and steals traffic` |  | ? | - |
| - | [#65142](https://github.com/vllm-project/vllm/pull/65142) `[Bugfix][Frontend] Don't let the gRPC server share a port that's already in use` | bug | main | - |
| - | [#65143](https://github.com/vllm-project/vllm/pull/65143) `[Metrics][Quantization] Let quantization configs report weight bytes for MFU` | perf,quant | main | - |
| - | [#65145](https://github.com/vllm-project/vllm/pull/65145) `[CI] Bake hash-locked KV connectors into the CI image and re-enable their jobs` | infra | main | - |
| - | [#65146](https://github.com/vllm-project/vllm/pull/65146) `[ROCm][Perf][DeepSeek-V4.1] Fused mega-attention prefill kernel for MI355X` | infra,nvidia,perf,rocm | main | - |
| - | [#65147](https://github.com/vllm-project/vllm/pull/65147) `[Bugfix][MRV2][Spec Decode] Count NaNs in logits per request, not per logits row` | bug | main | - |
| - | [#65148](https://github.com/vllm-project/vllm/pull/65148) `[Bugfix] Warm up FlashInfer kernels on an autotune cache hit` | bug,nvidia,perf | main | - |
| - | [#65149](https://github.com/vllm-project/vllm/pull/65149) `[Quantization][Fusion] Extend manual activation fusion to more NVFP4 linear backends` | infra,nvidia,perf,quant | main | - |
| - | [#65150](https://github.com/vllm-project/vllm/pull/65150) `[Bugfix][Rust Frontend] Preserve null DeepSeek tool descriptions` | bug | main | - |
| - | [#65151](https://github.com/vllm-project/vllm/issues/65151) `[Feature][ROCm]: Configurable HIP host wait policy for WSL GPU workers` | rocm | ? | - |
| - | [#65154](https://github.com/vllm-project/vllm/pull/65154) `[Bugfix][XPU] Make layer_norm batch invariant under VLLM_BATCH_INVARIANT` | bug,nvidia | main | - |
| - | [#65155](https://github.com/vllm-project/vllm/issues/65155) `[Bug]: Rust frontend: clients that connect during --shutdown-timeout hang instead of being refused` | bug,perf | ? | - |
| - | [#65156](https://github.com/vllm-project/vllm/pull/65156) `[Bugfix][Frontend] Close the parent's listening sockets after launching the Rust frontend` | bug | main | - |
| - | [#65158](https://github.com/vllm-project/vllm/pull/65158) `[CI] Add check-docstring-style pre-commit hook and use single backticks in docstrings` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#65159](https://github.com/vllm-project/vllm/pull/65159) `[Bugfix][Scheduler] Drain in-flight stale output on sync KV load-failure recovery (#65131)` | bug | main | - |
| - | [#65161](https://github.com/vllm-project/vllm/issues/65161) `[Performance]: With EAGLE and the OffloadingConnector, a prefix-cache hit loads its dropped last block from th` | perf | ? | - |
| - | [#65163](https://github.com/vllm-project/vllm/pull/65163) `[Bugfix][Frontend] Stop accepting gRPC connections when shutdown starts` | bug | main | - |
| - | [#65164](https://github.com/vllm-project/vllm/pull/65164) `[Fusion] Residual stream for allreduce manual fusion` | infra,perf | main | - |
| - | [#65165](https://github.com/vllm-project/vllm/pull/65165) `[Quantization] Extend int8_per_channel_weight_only to LinearBase.` | quant | main | - |
| - | [#65167](https://github.com/vllm-project/vllm/pull/65167) `[V1]_Support_multimodal_decoder_DBO_inputs` |  | main | - |
| - | [#65168](https://github.com/vllm-project/vllm/pull/65168) `[Fast start] Pluggable shared stores for daemon warmup caches` | infra | main | - |
| - | [#65169](https://github.com/vllm-project/vllm/pull/65169) `[Bugfix][Reasoning] kimi_k3: return the reply as content when the think channel is skipped` | bug | main | - |
| - | [#65172](https://github.com/vllm-project/vllm/issues/65172) `[RFC]: Holemiss: Selective Recovery of Partially Lost LLM Cache State` | perf | ? | - |
| - | [#65173](https://github.com/vllm-project/vllm/issues/65173) `[Bug] DeepSeek V4.1 Flash selects the last optional tool parameter based on JSON Schema property order, contra` | bug | ? | - |
| - | [#65176](https://github.com/vllm-project/vllm/pull/65176) `[Bugfix][Spec Decode] Keep the rejection-sampling residual nonzero in fp32` | bug | main | - |
| - | [#65177](https://github.com/vllm-project/vllm/pull/65177) `[Bugfix][Quantization] Index INT8 MoE per-channel weight scales independently of act quant - #58570` | bug,quant | main | - |
| - | [#65180](https://github.com/vllm-project/vllm/pull/65180) `[Rust Frontend] Implement the scale-out render routes on the main server` | quant | main | - |
| - | [#65181](https://github.com/vllm-project/vllm/pull/65181) `[Bugfix][Quantization] Respect non-gated shard count in FP4 Marlin` | bug,quant | main | - |
| - | [#65182](https://github.com/vllm-project/vllm/pull/65182) `[Perf][MRV2][Mamba2] Fuse aligned metadata CUDA graph inputs` | nvidia,perf | main | - |
| - | [#65186](https://github.com/vllm-project/vllm/pull/65186) `[Perf][GDN] Export Triton prefill checkpoints into the paged state cache` | infra,perf,rocm | main | - |
| - | [#65188](https://github.com/vllm-project/vllm/pull/65188) `[ROCm][Perf] Qwen3.8-Flash-Next specialized decode at 1-128 rows on MI355X (--monokernel)` | infra,perf,rocm | main | - |
| - | [#65189](https://github.com/vllm-project/vllm/pull/65189) `[Kernel][MoE] MXFP8 W8A8 MoE on FlashInfer CUTLASS` | nvidia,perf,quant | main | - |
| - | [#65191](https://github.com/vllm-project/vllm/pull/65191) `[CPU][Test] Add INT8 W4A8 smoke tests for Arm CPUs` | infra,quant | main | - |
| - | [#65192](https://github.com/vllm-project/vllm/pull/65192) `[Bugfix][Distributed] Fall back from FlashInfer PCIe IPC all-reduce without peer access` | bug,nvidia | main | - |
| - | [#65193](https://github.com/vllm-project/vllm/issues/65193) `[Bug][Quantization] MXFP8 linear kernel selection ignores the requested activation scheme — weight-only (W8A16` | perf,quant,risk | ? | - |
| - | [#65194](https://github.com/vllm-project/vllm/pull/65194) `[ROCm][MiniMax-M3] MXFP4 mode for the fused norm / RoPE / KV insert` | perf,quant,rocm | main | - |
| - | [#65195](https://github.com/vllm-project/vllm/pull/65195) `[ROCm][MiniMax-M3] Prebuild the NVFP4 FlyDSL kernels at startup` | perf,quant,rocm | main | - |
| - | [#65196](https://github.com/vllm-project/vllm/pull/65196) `[ROCm] MiniMax-M3: allow the AMD monokernel decode on MiniMax-M3.1` | infra,rocm | main | - |
| - | [#65197](https://github.com/vllm-project/vllm/pull/65197) `[KV Offload] Rename the filtered group index to config_group_idx` |  | main | - |
| - | [#65200](https://github.com/vllm-project/vllm/pull/65200) `[WIP][FT] Pause healthy engines for recovery` |  | main | - |
| - | [#65202](https://github.com/vllm-project/vllm/pull/65202) `[ROCm][RDNA] Add gfx1170 and gfx1171 support` | infra,rocm | main | - |
| - | [#65203](https://github.com/vllm-project/vllm/pull/65203) `[Attention] Sync FA with upstream (54b044c8)` | infra | main | - |
| - | [#65207](https://github.com/vllm-project/vllm/pull/65207) `[ROCm][MoE] Accumulate the shared-expert output in AITER's stage 2; fold routed scaling into top-k` | quant,rocm | main | - |
| - | [#65208](https://github.com/vllm-project/vllm/pull/65208) `[Kernel] Add opt-in NVFP4 activations for long prefills to b12x NVFP4 W4A16 linears` | perf,quant | main | - |
| - | [#65209](https://github.com/vllm-project/vllm/issues/65209) `[RFC]: Group-wide LoRA admission and residency for distributed MoE serving` |  | ? | - |
| - | [#65213](https://github.com/vllm-project/vllm/pull/65213) `[Bugfix][Frontend] Send an error event when a streamed Responses request fails` | bug | main | - |
| - | [#65215](https://github.com/vllm-project/vllm/pull/65215) `[Docs] Generate the quantization scheme table from source` | quant | main | - |
| - | [#65217](https://github.com/vllm-project/vllm/pull/65217) `[Spec Decode][MRV2] Add prefill_context_kv_only for P/D prefill instances` |  | main | - |
| - | [#65218](https://github.com/vllm-project/vllm/issues/65218) `[Bug]: NixlConnector silently corrupts NVFP4 KV cache when the prefill block size is smaller than decode's` | perf,quant,risk | ? | - |
| - | [#65219](https://github.com/vllm-project/vllm/pull/65219) `[Bugfix][NIXL] Reject NVFP4 KV cache when the prefill block size is smaller than decode's` | bug,perf,quant | main | - |
| - | [#65220](https://github.com/vllm-project/vllm/pull/65220) `[Feature][Distributed] Default supported shared-memory queues to futex waits` | infra | main | - |
| - | [#65221](https://github.com/vllm-project/vllm/pull/65221) `[Feature][Model Loader] Expose fastsafetensors transfer-mode selection` | infra | main | - |
| - | [#65222](https://github.com/vllm-project/vllm/pull/65222) `[Perf][Attention] Serve PrefixLM prefill with FlashAttention-2 in the Triton backend` | perf,rocm | main | - |
| - | [#65223](https://github.com/vllm-project/vllm/issues/65223) `[RFC]: TokenGate integration into vLLM` |  | ? | - |
| - | [#65224](https://github.com/vllm-project/vllm/pull/65224) `[ROCm][Perf][GLM-5.3-Flash] Split decodes off the AITER FlashKDA prefill on gfx950` | perf,rocm | main | - |
| - | [#65227](https://github.com/vllm-project/vllm/pull/65227) `[Perf][Multimodal] Encoder CUDA graphs: one replay per batch, finer grid up to one max budget` | nvidia,perf,rocm | main | - |
| - | [#65228](https://github.com/vllm-project/vllm/pull/65228) `[Attention] Prefer 128-token KV blocks for FA4 on Blackwell` | infra,nvidia | main | - |
| - | [#65231](https://github.com/vllm-project/vllm/pull/65231) `[ROCm][Perf] Fuse in_proj_qkvz + in_proj_ba into AITER dual-splitk GEMM kernel (Qwen3.8-27B)` | perf,rocm | main | - |
| - | [#65232](https://github.com/vllm-project/vllm/pull/65232) `[KV Connector] Spec-driven TP slicing for NIXL KV transfers` | nvidia | main | - |
| - | [#65233](https://github.com/vllm-project/vllm/pull/65233) `[Bugfix][MoE] Use the prepared b12x API for compact N64 W4A8 MXFP4 experts` | bug,quant | main | - |
| - | [#65236](https://github.com/vllm-project/vllm/pull/65236) `[Spec Decode] Support draft_lm_head_quantization for DFlash` | quant | main | - |
| - | [#65239](https://github.com/vllm-project/vllm/pull/65239) `[Doc][KV Offload] Document KV cache layout support for OffloadingConnector` | perf | main | - |
| - | [#65240](https://github.com/vllm-project/vllm/pull/65240) `[Quantization][MoE] Keep MXFP4 expert scales compressed on B12X` | infra,quant | main | - |
| - | [#65241](https://github.com/vllm-project/vllm/pull/65241) `[Bugfix][Kernel] Add __syncwarp before the lane-0 stores in the fused KDA decode block reductions` | bug,perf | main | - |
| - | [#65242](https://github.com/vllm-project/vllm/issues/65242) `[Bug]: Hermes streaming tool parser leaks keys that follow "arguments" into the streamed arguments string; non` | bug | ? | - |
| - | [#65243](https://github.com/vllm-project/vllm/pull/65243) `[ROCm][Perf][DSv4.1] Skip the redundant output copy in MoRI finalize` | perf,rocm | main | - |
| - | [#65244](https://github.com/vllm-project/vllm/pull/65244) `[Doc] Add startup-cache-image agent skill` | perf | main | - |
| - | [#65246](https://github.com/vllm-project/vllm/pull/65246) `[CI/Build] Rebuild lmcache against the image's torch` | infra | main | - |
| - | [#65247](https://github.com/vllm-project/vllm/pull/65247) `[Bugfix][Frontend] Stop Hermes streaming tool parser leaking keys that follow "arguments"` | bug | main | - |
| - | [#65248](https://github.com/vllm-project/vllm/pull/65248) `[ROCm][Perf][Attention] AITER gluon attention backend for Qwen3.8-27B` | perf,rocm | main | - |
| - | [#65250](https://github.com/vllm-project/vllm/issues/65250) `[Performance]: extract_hidden_states loses ~38% throughput to a decode draft that is almost never accepted` | perf | ? | - |
| - | [#65251](https://github.com/vllm-project/vllm/pull/65251) `[ROCm] Move AITER MXFP4 linear op registration into _aiter_ops` | quant,rocm | main | - |
| - | [#65254](https://github.com/vllm-project/vllm/pull/65254) `[MoE][RL] MegaMoE NVFP4: load each scale on its own, combine after loading` | quant | main | - |
| - | [#65255](https://github.com/vllm-project/vllm/issues/65255) `[RFC]: Out-of-tree KV-export connectors that hand a vLLM prefill to MLX (EXO) decode on Apple Silicon` |  | ? | - |
| - | [#65256](https://github.com/vllm-project/vllm/pull/65256) `[Quantization] Keep E8M0 scale bytes when loading into uint8 params` | infra,quant | main | - |
| - | [#65257](https://github.com/vllm-project/vllm/pull/65257) `[ROCm] Split-K bf16x3 router GEMV for fp32 router gates at 33-2047 tokens` | rocm | main | - |
| - | [#65259](https://github.com/vllm-project/vllm/pull/65259) `[RL][Model Loader] Make expert scale, Inkling and Mamba v2 sharded loaders copy_-only` | infra,quant | main | - |
| - | [#65260](https://github.com/vllm-project/vllm/pull/65260) `[Bugfix][KV Connector] Forward num_threads to non-UCX NIXL backends` | bug | main | - |
| - | [#65262](https://github.com/vllm-project/vllm/pull/65262) `[Feature][KV Connector][Mooncake] Export store usage metrics for MooncakeStoreConnector` |  | main | - |
| - | [#65263](https://github.com/vllm-project/vllm/pull/65263) `[Bugfix][Core] Fix Gemma-4 MTP prefix-cache hit loss when lookahead block hashes are off` | bug,perf | main | - |
| - | [#65264](https://github.com/vllm-project/vllm/issues/65264) `[Bug]: Mamba align prefix cache keys a partial-hit state copy at a block boundary that no chunk wrote when an ` | bug,perf | ? | - |
| - | [#65265](https://github.com/vllm-project/vllm/issues/65265) `[Bug]: --max-num-queued-tokens is enforced per API server, not across API servers` |  | ? | - |
| - | [#65266](https://github.com/vllm-project/vllm/pull/65266) `[Bugfix][Frontend] Share the max_num_queued_tokens count across API servers` | bug | main | - |
| - | [#65268](https://github.com/vllm-project/vllm/pull/65268) `[Feature] Segment attention layout for one-pass multi-candidate scoring` | perf | main | - |
| - | [#65269](https://github.com/vllm-project/vllm/pull/65269) `[Bugfix][Frontend] Decode each streaming-input chunk after its own prompt` | bug | main | - |
| - | [#65270](https://github.com/vllm-project/vllm/pull/65270) `[MRV2][Spec Decode] Fix mixed draft-model warmup token budget` | bug | main | - |
| - | [#65272](https://github.com/vllm-project/vllm/pull/65272) `[Quantization] Support ModelOpt INT8_PB_WO (per-block INT8 weight-only) linear layers` | quant | main | - |
| - | [#65275](https://github.com/vllm-project/vllm/pull/65275) `[Bugfix][MRV2] Use promised max_query_len for encoder-only FULL CUDA graphs` | bug,nvidia | main | - |
| - | [#65278](https://github.com/vllm-project/vllm/issues/65278) `[Bug]: GLM-5.3 (DSA sparse MLA) is not batch invariant under `VLLM_BATCH_INVARIANT=1`; today it is refused at ` | bug,perf,quant | ? | - |
| - | [#65280](https://github.com/vllm-project/vllm/pull/65280) `[XPU] Support Extensible KV cache` | nvidia,perf | main | - |
| - | [#65282](https://github.com/vllm-project/vllm/pull/65282) `[Core] Priority scheduling: preempt lower-priority requests for KV cache space` | perf | main | - |
| - | [#65283](https://github.com/vllm-project/vllm/pull/65283) `[Core] Priority scheduling: hold lower-priority prefill for first tokens` |  | main | - |
| - | [#65286](https://github.com/vllm-project/vllm/pull/65286) `[Bugfix][Core] Release libgomp workers before every fork` | bug,infra | main | - |
| - | [#65288](https://github.com/vllm-project/vllm/pull/65288) `[Bugfix][Quantization] Honor activation scheme in MXFP8 linear selection` | bug,infra,quant | main | - |
| - | [#65290](https://github.com/vllm-project/vllm/pull/65290) `[MoE] Add a generic fused gate router and backend interface` | infra,perf | main | - |
| - | [#65297](https://github.com/vllm-project/vllm/pull/65297) `[Perf] SM90 FP8 scaled_mm: 64x256 tiles for M just above a multiple of 256` | nvidia,perf,quant | main | - |
| - | [#65298](https://github.com/vllm-project/vllm/pull/65298) `[Benchmark][MoE] Add eager and graph top-k chain measurements` | infra,perf | main | - |
| - | [#65299](https://github.com/vllm-project/vllm/pull/65299) `[Bugfix][MoE] Keep grouped top-k weights independent of batch size` | bug | main | - |
| - | [#65301](https://github.com/vllm-project/vllm/pull/65301) `[Bugfix][Rust Frontend] Fail incomplete and errored streams in vllm-bench` | bug,perf | main | - |
| - | [#65303](https://github.com/vllm-project/vllm/pull/65303) `[Bugfix][Parser] Preserve token IDs in non-streaming engine parsing` | bug | main | - |
| - | [#65304](https://github.com/vllm-project/vllm/pull/65304) `[Model] Add GRT (Geometric Rotation Transformer) model support` |  | main | - |
| - | [#65305](https://github.com/vllm-project/vllm/pull/65305) `[Feature][PCP] Support DeepSeek V4 with FlashMLA on NVIDIA` | infra,nvidia | main | - |
| - | [#65306](https://github.com/vllm-project/vllm/pull/65306) `[Perf][GLM-5.3-Flash] Add SM90 skinny GEMM plans for the BF16 decode projections` | infra,nvidia,perf | main | - |
| - | [#65307](https://github.com/vllm-project/vllm/pull/65307) `[Bugfix][Elastic EP] Keep FlashInfer autotuning working on stateless groups` | bug,nvidia,perf | main | - |
| - | [#65310](https://github.com/vllm-project/vllm/pull/65310) `[ROCm][MiniMax-M3] LM-path speedups: fused norm + FP8 quant, dense short MSA prefill, JIT warm-ups` | perf,quant,rocm | main | - |
| - | [#65311](https://github.com/vllm-project/vllm/pull/65311) `[ROCm][Multimodal][MiniMax-M3] Sequence-parallel vision encoder for single-image batches` | nvidia,rocm | main | - |
| - | [#65312](https://github.com/vllm-project/vllm/issues/65312) `High-concurrency MTP on GLM-5.3 (H20 x8, batch 256): static K loses 10x; per-batch-size K table recovers it` |  | ? | - |
| - | [#65313](https://github.com/vllm-project/vllm/pull/65313) `[CI/Build] Make Python 3.14 the default for images and CI` | infra,rocm | main | - |
| - | [#65314](https://github.com/vllm-project/vllm/pull/65314) `[Bugfix][CPU]-Support-grouped-INT8-WNA16-MoE` | bug,quant | main | - |
| - | [#65316](https://github.com/vllm-project/vllm/pull/65316) `[Bugfix][Frontend] Put required properties first in strict tool grammars` | bug | main | - |
| - | [#65317](https://github.com/vllm-project/vllm/pull/65317) `[Bugfix][Metrics] Count preemptions in the scheduler, not on resume` | bug | main | - |
| - | [#65318](https://github.com/vllm-project/vllm/pull/65318) `[Bugfix][MRV2] Reserve MoE workspace before graph capture` | bug | main | - |
| - | [#65320](https://github.com/vllm-project/vllm/pull/65320) `[Bugfix][CPU] Use supports_fused_gdn_convs() for every GDN conv path (fixes macOS)` | bug,perf | main | - |
| - | [#65323](https://github.com/vllm-project/vllm/pull/65323) `[XPU][UT] Preserve RoPE buffer dtype for HF reference in the privacy-filter model test on XPU` | nvidia | main | - |
| - | [#65325](https://github.com/vllm-project/vllm/issues/65325) `[Bug]: Requests queued during level-2 sleep run before `reload_weights` and return wrong output with HTTP 200` | risk | ? | - |
| - | [#65326](https://github.com/vllm-project/vllm/pull/65326) `[Bugfix][Core] Fail requests queued during level-2 sleep when a wake resumes before the weights are restored` | bug | main | - |
| - | [#65327](https://github.com/vllm-project/vllm/issues/65327) `[Core]: DRY BlockPool.get_new_blocks with caching + metrics on/off variable factored out of the loop` |  | ? | - |
| - | [#65328](https://github.com/vllm-project/vllm/issues/65328) `[Bug]: shared streaming helper synthesizes delta_token_ids that serving never sends, changing engine behavior` | bug | ? | - |
| - | [#65329](https://github.com/vllm-project/vllm/pull/65329) `[model] Support FireRedFireRedASR2-AED` |  | main | - |
| - | [#65330](https://github.com/vllm-project/vllm/pull/65330) `[Core] DRYup KV cache block allocation loop` | perf | main | - |
| - | [#65332](https://github.com/vllm-project/vllm/issues/65332) `[Bug]: Large `n` (parallel sampling) in /v1/chat/completions causes severe cross-request latency` | bug,perf | ? | - |
| - | [#65334](https://github.com/vllm-project/vllm/pull/65334) `[Kernel] Calibrate the NVFP4 W4A16 Marlin/CuTe-DSL choice per layer shape on sm_12x` | infra,perf,quant | main | - |
| - | [#65335](https://github.com/vllm-project/vllm/pull/65335) `[Bugfix][KV Offload] Preserve full specs in scheduler cache projection` | bug,infra,perf | main | - |
| - | [#65336](https://github.com/vllm-project/vllm/pull/65336) `[KV Connector][NIXL] Pull KV from pipeline-parallel prefill stages, with the hybrid KV cache manager` | perf | main | - |
| - | [#65337](https://github.com/vllm-project/vllm/issues/65337) `[Bug]: GDN metadata builder hits CUDA device-side assert when adaptive verification trims a mixed prefill+spec` | bug,nvidia | ? | - |
| - | [#65338](https://github.com/vllm-project/vllm/pull/65338) `[Bugfix][Kernel] Align packed GDN decode with speculative recurrence` | bug,perf | main | - |
| - | [#65339](https://github.com/vllm-project/vllm/pull/65339) `[Perf][Core] Reserve step budget for waiting requests with cached KV` | perf | main | - |
| - | [#65340](https://github.com/vllm-project/vllm/pull/65340) `[Bugfix][GDN] Size repeat_interleave from the device token total` | bug | main | - |
| - | [#65342](https://github.com/vllm-project/vllm/issues/65342) `[Bug]: collective_rpc timeout does not bound enqueue wait on a full broadcast ring` |  | ? | - |
| - | [#65343](https://github.com/vllm-project/vllm/pull/65343) `[Bugfix][Core] Bound local RPC ring-slot wait by deadline` | bug | main | - |
| - | [#65344](https://github.com/vllm-project/vllm/pull/65344) `[Perf][Kernel] Add opt-in BF16 gated projection fusion for SM89 prefills` | perf | main | - |
| - | [#65345](https://github.com/vllm-project/vllm/pull/65345) `[Security] Use weights_only=True for EPLB all_gather_object collectives` |  | main | - |
| - | [#65346](https://github.com/vllm-project/vllm/pull/65346) `[Bugfix][Tool Parser] ernie45: keep content when no complete tool call is found` | bug | main | - |
| - | [#65347](https://github.com/vllm-project/vllm/pull/65347) `[Test][Model Loader] Direct weight reload equals a cold start, bitwise` | infra | main | - |
| - | [#65348](https://github.com/vllm-project/vllm/issues/65348) `[Feature]: Rust frontend: allow fetching multimodal media from private/internal hosts` |  | ? | - |
| - | [#65349](https://github.com/vllm-project/vllm/pull/65349) `[Perf] Warm up JIT kernels that only long prefills, eager drafters and constrained decoding reach` | perf | main | - |
| - | [#65351](https://github.com/vllm-project/vllm/pull/65351) `[Multimodal][CG] Share encoder CUDA graph capture buffers across token budgets` | nvidia,rocm | main | - |
| - | [#65352](https://github.com/vllm-project/vllm/pull/65352) `[Bugfix][Multimodal] Fix DP vision encoder hang: type an empty rank's output with the vision tower's output dt` | bug | main | - |
| - | [#65353](https://github.com/vllm-project/vllm/pull/65353) `[Bugfix][Model Loader] Reload fixes: gpt-oss streamed MXFP4 TP split, w2_bias, FlashInfer bmm scales` | bug,nvidia,quant | main | - |
| - | [#65354](https://github.com/vllm-project/vllm/pull/65354) `[Quantization] OSCAR KV cache presets for the TurboQuant backend` | infra,perf,quant | main | - |
| - | [#65355](https://github.com/vllm-project/vllm/pull/65355) `[Bugfix][Frontend] Bound parallel sampling by server limits` | bug | main | - |
| - | [#65356](https://github.com/vllm-project/vllm/pull/65356) `[Bugfix] Fix DeepSeek-V4.1-Flash boot failure on SM120 (RTX PRO 6000 Blackwell): allow 64-page block size for ` | bug,nvidia | main | - |
| - | [#65357](https://github.com/vllm-project/vllm/issues/65357) `[Bug] Empty/missing string content on a developer message returns 500 (and leaks internal _image_indices) inst` |  | ? | - |
| - | [#65358](https://github.com/vllm-project/vllm/issues/65358) `[Feature request] DeepGEMM MegaMoE: support SM120 (Blackwell workstation) GPUs` | nvidia | ? | - |
| - | [#65359](https://github.com/vllm-project/vllm/issues/65359) `[Proposal][Perf] Wire flashinfer's PcieIpcAllGatherWorkspace into CudaCommunicator.all_gather for latency-boun` | nvidia,perf | ? | - |
| - | [#65360](https://github.com/vllm-project/vllm/issues/65360) `[Bug]: /inference/v1/generate usage omits reasoning_tokens in derender mode` | bug | ? | - |
| - | [#65361](https://github.com/vllm-project/vllm/pull/65361) `[Feature][LoRA] Coordinate MoE adapter admission and residency` | infra,nvidia | main | - |
| - | [#65362](https://github.com/vllm-project/vllm/pull/65362) `[Test] Let simulate_tool_streaming stream explicit per-chunk token ids` |  | main | - |
| - | [#65364](https://github.com/vllm-project/vllm/issues/65364) `[Bug]: [CPU] DeepSeek-V4 fails at the first decode step with KeyError: 'c1a'` | bug,quant | ? | - |
| - | [#65365](https://github.com/vllm-project/vllm/pull/65365) `[Bugfix][CPU] DeepSeek-V4: return all layer types from the CPU tile scheduler` | bug,infra | main | - |
| - | [#65366](https://github.com/vllm-project/vllm/pull/65366) `[Bugfix] Return 400 for empty DeepSeek V4.1 developer messages` | bug,infra | main | - |
| - | [#65367](https://github.com/vllm-project/vllm/pull/65367) `[Bugfix][Tool Parser] xlam, hunyuan_a13b: keep tool calls whose arguments are not an object` | bug | main | - |
| - | [#65368](https://github.com/vllm-project/vllm/pull/65368) `[Bugfix][Parser] chat_parsing: keep large integers exact for number parameters` | bug | main | - |
| - | [#65373](https://github.com/vllm-project/vllm/pull/65373) `Share DeepSeek V4.1 CPU KV across TP ranks` | perf | main | - |
| - | [#65379](https://github.com/vllm-project/vllm/pull/65379) `[Model] Add native CTC word timestamps for Nemotron 3.5 Transcribe` | infra | main | - |
| - | [#65380](https://github.com/vllm-project/vllm/pull/65380) `[Frontend][v0.30.0][Reference only] Backport Messages min_tokens and ignore_eos` |  | releases/v0.30.0 | - |
| - | [#65381](https://github.com/vllm-project/vllm/pull/65381) `[Feature][HiSparse] Add backend hooks for private host allocation` |  | main | - |
| - | [#65382](https://github.com/vllm-project/vllm/pull/65382) `[Docs] Update SPEED-Bench preparation script documentation` | perf | main | - |
| - | [#65383](https://github.com/vllm-project/vllm/pull/65383) `[Bugfix] Report reasoning_tokens in /inference/v1/generate derender usage` | bug | main | - |
| - | [#65384](https://github.com/vllm-project/vllm/issues/65384) `[RFC]: Decouple Physical PCP Topology from Per-Forward Attention Layout and Draft Execution Policy` |  | ? | - |
| - | [#65385](https://github.com/vllm-project/vllm/issues/65385) `[Bug]: GDN Triton/FLA prefill gives wrong, non-deterministic results on Hopper (H20) with triton 3.6: `chunk_s` | bug,nvidia,perf,rocm | ? | - |
| - | [#65387](https://github.com/vllm-project/vllm/issues/65387) `[Bug]: TP workers wedge permanently in Triton kernel launch (GDN layer_norm_fwd) with idle GPUs; Qwen3.5 + MTP` | perf,rocm | ? | - |
| - | [#65390](https://github.com/vllm-project/vllm/issues/65390) `[ROCm] A text-only model needs torchvision, and you find out 15 minutes into JIT compilation` | rocm | ? | - |
| - | [#65391](https://github.com/vllm-project/vllm/issues/65391) `[Bug]: Resolve Triton kernel block sizes per platform instead of hardcoding them` | bug,perf,rocm | ? | - |
| - | [#65393](https://github.com/vllm-project/vllm/pull/65393) `[ROCm][Quantization] Add FP8 block GEMM configs for gfx1100 (AMD_Radeon_Graphics)` | quant,rocm | main | - |
| - | [#65394](https://github.com/vllm-project/vllm/pull/65394) `[Bugfix][Quantization] Honor the activation scheme in MXFP8 linear kernel selection` | bug,nvidia,perf,quant | main | - |
| - | [#65395](https://github.com/vllm-project/vllm/pull/65395) `[Perf][Attention] Cache FlexAttention K/V cache views per tensor` | perf | main | - |
| - | [#65396](https://github.com/vllm-project/vllm/pull/65396) `[Perf][Mamba] Cache the conv_state transpose view per state-cache tensor` | perf | main | - |
| - | [#65397](https://github.com/vllm-project/vllm/pull/65397) `[Rust Frontend] End reasoning at a tool-call opener like Python` |  | main | - |
| - | [#65398](https://github.com/vllm-project/vllm/pull/65398) `[Quantization] Add mxfp4_hadamard32_moe online quantization` | infra,quant,rocm | main | - |
| - | [#65400](https://github.com/vllm-project/vllm/pull/65400) `[Recipe] Kimi-K3, MiniMax-M3.1-Flash: add Rubin VR200 support` | infra | main | - |
| - | [#65401](https://github.com/vllm-project/vllm/issues/65401) `[Bug]: get_top_k_tokens applies scaling and soft capping in the wrong order` | bug | ? | - |
| - | [#65402](https://github.com/vllm-project/vllm/pull/65402) `[Bugfix][MRv1][Spec Decode] Count NaNs in logits per request, not per logits row` | bug | main | - |
| - | [#65403](https://github.com/vllm-project/vllm/pull/65403) `[Perf][Sparse MLA][GLM-5.3] Index-group workspace savings and opt-in masked-MHA prefill on quantized KV` | nvidia,perf,quant,rocm | main | - |
| - | [#65404](https://github.com/vllm-project/vllm/pull/65404) `[CI] Recheck test coverage after shell script edits` | infra | main | - |
| - | [#65405](https://github.com/vllm-project/vllm/issues/65405) `[Bug]: MoE w2_bias is added tp_size times under tensor parallelism` |  | ? | - |
| - | [#65406](https://github.com/vllm-project/vllm/pull/65406) `[Bugfix][MoE] Count the expert down-projection bias once under TP` | bug | main | - |
| - | [#65407](https://github.com/vllm-project/vllm/pull/65407) `[Bugfix][ROCm][Qwen4Exp] Bind the opaque SP wrappers in the PLE layer` | bug,rocm | main | - |
| - | [#65408](https://github.com/vllm-project/vllm/pull/65408) `[WIP][Kernel] Fuse SiLU and FlashInfer SM90 block-FP8 quantization` | infra,nvidia,perf,quant | main | - |
| - | [#65409](https://github.com/vllm-project/vllm/pull/65409) `[Model] Deprecate PaliGemma support.` |  | main | - |
| - | [#65410](https://github.com/vllm-project/vllm/pull/65410) `[ROCm][Step5] Use native fnuz FP8 MFMA in CSA prefill indexer scores` | quant,rocm | main | - |
| - | [#65411](https://github.com/vllm-project/vllm/issues/65411) `[Bug]: /v1/messages renders consecutive assistant messages as separate turns` | rocm | ? | - |
| - | [#65414](https://github.com/vllm-project/vllm/pull/65414) `[Bugfix][Frontend] Combine consecutive assistant messages in Anthropic requests` | bug | main | - |
| - | [#65415](https://github.com/vllm-project/vllm/pull/65415) `fix(logits_processor): apply soft capping before scaling in get_top_k…` | bug | main | - |
| - | [#65419](https://github.com/vllm-project/vllm/pull/65419) `[ROCm][Perf][Attention] AITER Gluon paged attention reduce + output gate fusion (Qwen3.8-27B)` | perf,rocm | main | - |
| - | [#65420](https://github.com/vllm-project/vllm/pull/65420) `[Perf][GLM-5.3] Fuse MXFP4 MoE input quantization with route. 20% TTFT improvement` | nvidia,perf,quant | main | - |
| - | [#65421](https://github.com/vllm-project/vllm/pull/65421) `[ROCm][Perf][DSv4.1] Asm decode layers for 17-256-row decode steps (gfx950, TP4)` | infra,perf,rocm | main | - |
| - | [#65422](https://github.com/vllm-project/vllm/pull/65422) `[Bugfix][Structured Output] Allow integer multipleOf with xgrammar` | bug | main | - |
| - | [#65424](https://github.com/vllm-project/vllm/issues/65424) `[Feature]: Add opt-in in-flight request deduplication for chat completions` |  | ? | - |
| - | [#65426](https://github.com/vllm-project/vllm/pull/65426) `[Bugfix][Realtime] Ignore a final commit when no transcription is running` | bug | main | - |
| - | [#65427](https://github.com/vllm-project/vllm/pull/65427) `[ROCm][Kernel] Pick the split of `top_k_per_row_decode` per row on the device` | perf,rocm | main | - |
| - | [#65429](https://github.com/vllm-project/vllm/pull/65429) `[Kernel][Attention] Segment sliding windows in split-K; split-K for non-causal speculative rows (supersedes #6` | perf | main | - |
| - | [#65430](https://github.com/vllm-project/vllm/issues/65430) `[Bug][Spec Decode][Structured Output] Reverting #54442 reopens grammar-invalid proposal acceptance in async sc` |  | ? | - |
| - | [#65431](https://github.com/vllm-project/vllm/pull/65431) `[Model] Gemma 4: native packed vision tower on MMEncoderAttention` | nvidia | main | - |
| - | [#65433](https://github.com/vllm-project/vllm/pull/65433) `[Perf][MiniMax-M3] Raise the fused MoE finalize + all-reduce cap from 32 to 128 tokens` | infra,perf | main | - |
| - | [#65434](https://github.com/vllm-project/vllm/pull/65434) `[Perf][MiniMax-M3] Two-shot fused MoE finalize + all-reduce + norm + MXFP8 up to 512 tokens` | infra,perf,quant | main | - |
| - | [#65435](https://github.com/vllm-project/vllm/pull/65435) `[Perf][MiniMax-M3] Quantize the routed MoE input while the router GEMM runs` | infra,nvidia,perf,quant | main | - |
| - | [#65436](https://github.com/vllm-project/vllm/pull/65436) `[Perf][Sampling] Gather vocab-parallel logits into their final layout in one pass` | infra,perf | main | - |
| - | [#65437](https://github.com/vllm-project/vllm/pull/65437) `[Bugfix][Core] Clear stale block-table row tails on shrinking add_row/move_row` | bug | main | - |
| - | [#65440](https://github.com/vllm-project/vllm/issues/65440) `[Feature]: CUDA 12 wheels for v0.33.x (torch 2.14.0 has cu126 only), and three stale CUDA gates that break CUD` | nvidia | ? | - |
| - | [#65444](https://github.com/vllm-project/vllm/pull/65444) `[Perf] Make detokenizer output-text appends O(1) per token` | perf | main | - |
| - | [#65446](https://github.com/vllm-project/vllm/pull/65446) `[torch.compile] Only flag `_buffers.update` in the cudagraph buffer assignment check` | nvidia | main | - |
| - | [#65447](https://github.com/vllm-project/vllm/issues/65447) `[Feature]: Replace CUTLASS MXFP4 W4A4 MoE (CutlassExpertsMxfp4) with FlashInfer kernels on Blackwell` | nvidia,perf,quant | ? | - |
| - | [#65448](https://github.com/vllm-project/vllm/pull/65448) `[KV Connector][Spec Decode] Support lookahead block hashes in remaining KV connectors` | perf | main | - |
| - | [#65453](https://github.com/vllm-project/vllm/pull/65453) `[Bugfix][Multimodal] Register `cu_seqlens` replay padding for GLM-4.1V/Kimi-K2.5 encoder CUDA graphs` | bug,nvidia | main | - |
| - | [#65454](https://github.com/vllm-project/vllm/pull/65454) `[hw-agnostic] Linear layers for the Transformers backend` |  | main | - |
| - | [#65456](https://github.com/vllm-project/vllm/issues/65456) `[CI Failure][ROCm]: MI355 spec decode tests OOM with the extensible KV cache` | infra,perf,rocm | ? | - |
| - | [#65458](https://github.com/vllm-project/vllm/pull/65458) `[Perf] Bypass the dispatcher for all vLLM custom ops in eager mode` | nvidia,perf,quant,rocm | main | - |
| - | [#65461](https://github.com/vllm-project/vllm/pull/65461) `[ROCm][Perf][DSv4.1] Mono: merge K2(l) and K1(l + 1) into one launch at TP8` | infra,perf,rocm | main | - |
| - | [#65462](https://github.com/vllm-project/vllm/pull/65462) `[Rust Frontend] Export cache configuration metrics` | perf | main | - |
| - | [#65463](https://github.com/vllm-project/vllm/pull/65463) `[Bugfix][KV Cache] Re-fit `--max-model-len auto` after the extensible KV cache shrinks` | bug,perf | main | - |
| - | [#65464](https://github.com/vllm-project/vllm/pull/65464) `[Refactor] Migrate FlashInfer NVLink two-sided to MoEEpCommunication` | nvidia | main | - |
| - | [#65468](https://github.com/vllm-project/vllm/issues/65468) `[Bug][Spec Decode] DSD K=0: draft-KV retention cost under batch-size ladders + tier-edge release design (with ` | infra | ? | - |
| - | [#65469](https://github.com/vllm-project/vllm/pull/65469) `fixing up the MCP Tool discovery` |  | main | - |
| - | [#65470](https://github.com/vllm-project/vllm/pull/65470) `[Perf][Model] Qwen4Exp QSA: compact grid for indexer prefill scoring` | infra,perf | main | - |
| - | [#65471](https://github.com/vllm-project/vllm/pull/65471) `[Perf][Model] Qwen4Exp QSA: SM120 launch config for indexer prefill scoring` | infra,nvidia,perf | main | - |
| - | [#65472](https://github.com/vllm-project/vllm/pull/65472) `[Docs] Document hybrid NIXL startup requirements` | infra | main | - |
| - | [#65474](https://github.com/vllm-project/vllm/pull/65474) `[ROCm][Perf][Qwen4Exp] Tune QSA sparse GQA and indexer on gfx942 and gfx950` | perf,rocm | main | - |
| - | [#65475](https://github.com/vllm-project/vllm/pull/65475) `[Bugfix][ROCm][Qwen4Exp] Bind the opaque SP wrapper in the MTP draft` | bug,rocm | main | - |
| - | [#65477](https://github.com/vllm-project/vllm/pull/65477) `[Bugfix][Env] Lowercase VLLM_FLOAT32_MATMUL_PRECISION before torch sees it` | bug | main | - |
| - | [#65479](https://github.com/vllm-project/vllm/pull/65479) `[ROCm][MiniMax-M3.1] MXFP8 linear on AITER's tuned FlyDSL GEMM` | perf,quant,rocm | main | - |
| - | [#65480](https://github.com/vllm-project/vllm/pull/65480) `[ROCm][Perf] Use the Triton fp32 router GEMM up to 128 tokens for small routers on gfx950` | perf,rocm | main | - |
| - | [#65483](https://github.com/vllm-project/vllm/pull/65483) `[Perf][MiniMax-M3.1-Flash] Specialized decode on B200 and B300` | infra,nvidia,perf | main | - |
| - | [#65485](https://github.com/vllm-project/vllm/pull/65485) `[Build] Prune docs and CI config from the sdist` | infra | main | - |
| - | [#65486](https://github.com/vllm-project/vllm/pull/65486) `[Build] Only build FA2 by default when targeting SM8x/SM12x` | infra,nvidia | main | - |
| - | [#65487](https://github.com/vllm-project/vllm/pull/65487) `[Bugfix][Distributed] Copy misaligned packed weight-transfer entries on unpack` | bug | main | - |
| - | [#65489](https://github.com/vllm-project/vllm/pull/65489) `[Perf][Spec Decode] Rejection sample can skip loads in all-greedy case` | perf | main | - |
| - | [#65490](https://github.com/vllm-project/vllm/pull/65490) `[Bugfix][Perf] Exclude draft-only buckets from min_num_layers in KV cache grouping` | bug,perf | main | - |
| - | [#65491](https://github.com/vllm-project/vllm/pull/65491) `[Bugfix] Omit inactive CP checkpointing kwargs in FlashInfer GDN prefill` | bug,nvidia | main | - |
| - | [#65492](https://github.com/vllm-project/vllm/pull/65492) `[Perf] Pre-warm float32 greedy-with-penalties sampler and GDN RMSNorm buckets` | perf | main | - |
| - | [#65493](https://github.com/vllm-project/vllm/pull/65493) `[Benchmark] Add --random-mm-video-encode-fps to random-mm` | perf | main | - |
| - | [#65497](https://github.com/vllm-project/vllm/pull/65497) `[Perf][Kernel] Fuse RMSNorm + block FP8 quant for fp32 (Gemma-style) norm weights` | perf,quant | main | - |
| - | [#65499](https://github.com/vllm-project/vllm/pull/65499) `[Benchmark] Add synthetic audio support to random-mm` | perf | main | - |
| - | [#65501](https://github.com/vllm-project/vllm/pull/65501) `[Bugfix][KV Connector][Mooncake] Fix transfer address overflow on Intel XPU` | bug,nvidia,risk | main | - |
| - | [#65502](https://github.com/vllm-project/vllm/issues/65502) `[RFC]: First-class, trusted forwarded prompt token IDs on the chat, Messages, and Responses routes` |  | ? | - |
| - | [#65503](https://github.com/vllm-project/vllm/issues/65503) `[Feature]: vllm.Render for completions, Anthropic Messages, and Responses, with raw-JSON input and optional cl` |  | ? | - |
| - | [#65505](https://github.com/vllm-project/vllm/pull/65505) `[Perf][Kernel][Attention] Binary-search mm_prefix spans in Triton unified attention` | perf,rocm | main | - |
| - | [#65506](https://github.com/vllm-project/vllm/pull/65506) `[Bugfix][Frontend] Stop API workers and coordinator on parent loss` | bug,infra | main | - |
| - | [#65507](https://github.com/vllm-project/vllm/pull/65507) `[KVConnector] Enable LMCache MP connector for the extensible kv cache` | perf | main | - |
| - | [#65508](https://github.com/vllm-project/vllm/pull/65508) `[ROCm][Perf][MiniMax-M3.1] Emit the o_proj MXFP8 input from the NVFP4 sparse decode kernel` | perf,quant,rocm | main | - |
| - | [#65509](https://github.com/vllm-project/vllm/pull/65509) `[ROCm][Perf] Capture the routed MoE chain before the shared-expert aux branch for small decode batches` | perf,rocm | main | - |
| - | [#65510](https://github.com/vllm-project/vllm/pull/65510) `[Mamba] Store ReplaySSM ring trackers in the Mamba page; put the dt ring last` | infra | main | - |
| - | [#65511](https://github.com/vllm-project/vllm/pull/65511) `[Build][CUDA] Raise CUDA compiler version gates for cooperative_topk (12.8) and DeepGEMM (12.9)` | infra,nvidia | main | - |
| - | [#65512](https://github.com/vllm-project/vllm/pull/65512) `[WIP][ROCm][Perf][DeepSeek-V4.1] Mega-attention prefill kernel for gfx942` | infra,nvidia,perf,rocm | main | - |
| - | [#65513](https://github.com/vllm-project/vllm/issues/65513) `[Performance]: Gemma 4 full-attention layers run the Triton kernel for the whole prefill whenever the batch ca` | perf,rocm | ? | - |
| - | [#65515](https://github.com/vllm-project/vllm/issues/65515) `[Performance]: Large CPU->GPU KV offload loads stall the worker thread inside cuMemcpyBatchAsync` | perf | ? | - |
| - | [#65517](https://github.com/vllm-project/vllm/pull/65517) `[Bugfix][ROCm][MoE] Fix tkw1 rejecting count-free expert metadata, rename AITER QuantMethod` | bug,quant,rocm | main | - |
| - | [#65519](https://github.com/vllm-project/vllm/pull/65519) `[Perf][KV Offload] Bound copy descriptors submitted per step for CPU->GPU loads` | perf | main | - |
| - | [#65520](https://github.com/vllm-project/vllm/pull/65520) `[Model] Nemotron-3.5-Transcribe: support ReplaySSM` |  | main | - |
| - | [#65521](https://github.com/vllm-project/vllm/pull/65521) `[Perf][mHC] use FlashInfer mega mHC for MHCFusedPostPreOp (GLM-5.3-Fl…` | nvidia,perf | main | - |
| - | [#65523](https://github.com/vllm-project/vllm/issues/65523) `[Bug]:  MiMo-V2.6 video timestamps ignore real frame times (every clip is labelled 00:00–00:30)` | bug | ? | - |
| - | [#65524](https://github.com/vllm-project/vllm/pull/65524) `[Perf][DSv4.1] Replay one row for far prefill chunks` | nvidia,perf | main | - |
| - | [#65525](https://github.com/vllm-project/vllm/pull/65525) `[ROCm][UMBP][Muse Spark] Support UMBP for Muse Spark Open, keeping the decode monokernel` | rocm | main | - |
| - | [#65526](https://github.com/vllm-project/vllm/pull/65526) `[Model Loader] Refill derived tensors with refill_derived (mHC broadcast, Muse Spark ROCm router planes, Flash` | nvidia,rocm | main | - |
| - | [#65527](https://github.com/vllm-project/vllm/pull/65527) `[Bugfix][SM120] Admit SM120 to the flattened device-query-lens path` | bug,nvidia | main | - |
| - | [#65531](https://github.com/vllm-project/vllm/issues/65531) `[Bug]: Precomputed image or video embeddings crash the engine when the encoder CUDA graph is on` | bug,nvidia | ? | - |
| - | [#65532](https://github.com/vllm-project/vllm/pull/65532) `[Bugfix] Fix Cohere/Cohere2 compute_logits when LoRA is enabled` | bug | main | - |
| - | [#65533](https://github.com/vllm-project/vllm/issues/65533) `[Bug]: GLM-4.7-AWQ on Blackwell (sm_120) produces degenerate/looping output on v0.25.1 but correct on v0.14.0 ` | bug,nvidia,perf,quant | ? | - |
| - | [#65534](https://github.com/vllm-project/vllm/pull/65534) `[Core][MM] Make the multimodal encoder cache size configurable ` | perf | main | - |
| - | [#65535](https://github.com/vllm-project/vllm/pull/65535) `[Bugfix][Multimodal] Skip the encoder CUDA graph for precomputed embeddings` | bug,nvidia | main | - |
| - | [#65536](https://github.com/vllm-project/vllm/pull/65536) `[Bugfix][Quantization] Normalize Quark exclude entries with parameter suffixes (#65034)` | bug,quant,rocm | main | - |
| - | [#65538](https://github.com/vllm-project/vllm/pull/65538) `[Bugfix] Reject empty/missing content on developer/system messages (400) instead of renderer crash (500)` | bug | main | - |
| - | [#65541](https://github.com/vllm-project/vllm/pull/65541) `[Rust][Benchmark] Align vllm-bench result files and requests with Python` | perf | main | - |
| - | [#65543](https://github.com/vllm-project/vllm/issues/65543) `[RFC]: Scheduler-owned persistent state for streaming RNN-T ASR (model starts as a plugin)` |  | ? | - |
| - | [#65544](https://github.com/vllm-project/vllm/pull/65544) `[Core] Scheduler-owned persistent state for streaming models` | infra,nvidia,perf | main | - |
| - | [#65545](https://github.com/vllm-project/vllm/issues/65545) `[RFC]: Lifecycle hooks for endpoint plugins (readiness and graceful drain), with an out-of-tree Riva-compatibl` |  | ? | - |
| - | [#65546](https://github.com/vllm-project/vllm/pull/65546) `[Frontend] Optional lifecycle hooks for endpoint plugins` | infra | main | - |
| - | [#65548](https://github.com/vllm-project/vllm/issues/65548) `[RFC]: Source Identity and Semantic Metadata for KV Cache Events` | perf | ? | - |
| - | [#65549](https://github.com/vllm-project/vllm/pull/65549) `[Core][MRv2] Build ModelState through an overridable runner method` | infra | main | - |
| - | [#65550](https://github.com/vllm-project/vllm/issues/65550) `[Bug]: After a full-prompt KV connector load, the recomputed last token's sliding window reads the null block` | bug | ? | - |
| - | [#65555](https://github.com/vllm-project/vllm/pull/65555) `[ROCm][DSv4.1] Score the sparse-indexer prefill on ShardQ token slices` | rocm | main | - |
| - | [#65556](https://github.com/vllm-project/vllm/pull/65556) `[Bugfix] Llama4 pythonic parser: strip <|python_end|> even without <|python_start|>` | bug | main | - |
| - | [#65558](https://github.com/vllm-project/vllm/pull/65558) `[Kernel] Marlin: deprecate VLLM_MARLIN_USE_ATOMIC_ADD and drop the bf16 sm90 build` | infra,nvidia,perf,quant | main | - |
| - | [#65559](https://github.com/vllm-project/vllm/pull/65559) `[ROCm][KV Offload] SimpleCPUOffload: batch copies on SDMA with hipMemcpyFlagExtPreferCE (HIP 7.16+)` | nvidia,rocm | main | - |
| - | [#65560](https://github.com/vllm-project/vllm/issues/65560) `[Tracking] Replace Marlin with Humming across NVIDIA architectures` | nvidia,quant | ? | - |
| - | [#65561](https://github.com/vllm-project/vllm/pull/65561) `[Bugfix][KV Offload] SimpleCPUOffload: requeue a finished request's CPU prefix, free CPU blocks tail first` | bug | main | - |
| - | [#65562](https://github.com/vllm-project/vllm/pull/65562) `[Bugfix] Keep KV-cache scale defaults under dummy loading` | bug,perf,quant | main | - |
| - | [#65563](https://github.com/vllm-project/vllm/pull/65563) `[Bugfix][MoRIIO] Route decode requests by their own DP rank` | bug,rocm | main | - |
| - | [#65564](https://github.com/vllm-project/vllm/issues/65564) `[Bug]: Qwen3.5-9B forced named tool choice is ~11x slower on A100 with v0.27.1 than v0.31.0` | bug,perf | ? | - |
| - | [#65565](https://github.com/vllm-project/vllm/pull/65565) `[Refactor][Worker] Expose platform executor and PP orchestration hooks` | infra | main | - |
| - | [#65566](https://github.com/vllm-project/vllm/pull/65566) `[XPU] Qwen3.5 specialized decode: mono decode kernels (`--monokernel`)` | infra,nvidia,perf | main | - |
| - | [#65568](https://github.com/vllm-project/vllm/issues/65568) `[Bug]: Kimi K3 latent-MoE tail fusion fails at startup when NVLS multicast is unavailable (multi-GPU Confident` | perf | ? | - |
| - | [#65569](https://github.com/vllm-project/vllm/issues/65569) `[Performance]: Batch-invariant mode on Hopper/Blackwell routes Linear layers to Triton although cuBLAS is alre` | nvidia,perf,rocm | ? | - |
| - | [#65570](https://github.com/vllm-project/vllm/pull/65570) `[Perf][Spec Decode] Reduce padded n-gram verification in MRV2` | nvidia,perf | main | - |
| - | [#65571](https://github.com/vllm-project/vllm/pull/65571) `[Perf][Frontend] Reduce sampled-logprob return-path overhead` | infra,perf | main | - |
| - | [#65572](https://github.com/vllm-project/vllm/pull/65572) `[Bugfix][Spec Decode] Fall back from InstantTensor for PP-local draft models` | bug,infra | main | - |
| - | [#65574](https://github.com/vllm-project/vllm/pull/65574) `[Perf][Frontend] Reduce chat SSE serialization and Harmony polling` | infra,perf | main | - |
| - | [#65575](https://github.com/vllm-project/vllm/pull/65575) `[KV Connector][Mooncake] Fail pulls from a lost prefill worker` |  | main | - |
| - | [#65576](https://github.com/vllm-project/vllm/pull/65576) `[docker] Install AWS EFA in the main image; build DeepEP-EFA separately` | infra,nvidia | main | - |
| - | [#65578](https://github.com/vllm-project/vllm/pull/65578) `[Perf][Kernel] Fuse bias add + GELU + NVFP4 quant for BERT-style FFNs` | infra,perf,quant | main | - |
| - | [#65580](https://github.com/vllm-project/vllm/pull/65580) `[Bugfix] Retain sliding window block for recomputed token on full remote KV load` | bug,perf | main | - |
| - | [#65581](https://github.com/vllm-project/vllm/pull/65581) `[Bugfix] Respect actual video fps and frame indices in MiMo-v2.6 timestamp generation` | bug | main | - |
| - | [#65582](https://github.com/vllm-project/vllm/pull/65582) `[Bugfix] Gracefully fallback to non-fused latent-MoE tail when NVLS multicast is unavailable` | bug,perf | main | - |
| - | [#65583](https://github.com/vllm-project/vllm/pull/65583) `[Bugfix][Benchmark] Fix bench throughput crash with BlazeEdit HF datasets` | bug,perf | main | - |
| - | [#65584](https://github.com/vllm-project/vllm/pull/65584) `[Bugfix][KV Connector] Backoff last prompt token for sliding window in P/D (#65550)` | bug | main | - |
| - | [#65587](https://github.com/vllm-project/vllm/issues/65587) `[Bug]: VLLM_BATCH_INVARIANT=1 is not batch-invariant for Gemma-2-9B on H100 (FlashAttention sliding-window pat` | bug,nvidia | ? | - |
| - | [#65588](https://github.com/vllm-project/vllm/pull/65588) `[Spec Decode] Measure the Dynamic SD table instead of writing it by hand` | perf | main | - |
| - | [#65589](https://github.com/vllm-project/vllm/pull/65589) `[Perf][Startup] Don't import vllm.parser from vllm.v1.structured_output` | perf | main | - |
| - | [#65590](https://github.com/vllm-project/vllm/pull/65590) `[Perf][Startup] Compile per_block_cast_to_fp8 on first use` | perf | main | - |
| - | [#65591](https://github.com/vllm-project/vllm/pull/65591) `[Model][CUDA] Gemma 4 native vision tower on H100: bound eager tower memory, fix Triton test` | bug,nvidia,rocm | main | - |
| - | [#65592](https://github.com/vllm-project/vllm/issues/65592) `[Bug]: /inference/v1/generate with "max_tokens": null bypasses default/override/platform output-token caps` |  | ? | - |
| - | [#65594](https://github.com/vllm-project/vllm/pull/65594) `[Bugfix][Frontend] Handle non-string HTTPException details` | bug | main | - |
| - | [#65595](https://github.com/vllm-project/vllm/pull/65595) `[ROCm][DSv4.1] Share Engram host tables across DP ranks with HIP VMM` | rocm | main | - |
| - | [#65596](https://github.com/vllm-project/vllm/pull/65596) `[Model][Perf] Gemma 4: torch.compile for the native vision tower` | nvidia,perf | main | - |
| - | [#65597](https://github.com/vllm-project/vllm/pull/65597) `[ROCm][UMBP] Add waiting-request prefetch to UMBPStoreConnector` | rocm | main | - |
| - | [#65600](https://github.com/vllm-project/vllm/pull/65600) `[XPU][UT] Patch stream-capture check in SM90 sparse MLA plan test` | nvidia | main | - |
| - | [#65601](https://github.com/vllm-project/vllm/pull/65601) `[KV Events] Expose chunk size in BlockStored events` | perf | main | - |
| - | [#65602](https://github.com/vllm-project/vllm/pull/65602) `[Bugfix] Fix MiniMax-M3 attention warmup deadlock under PP>1 (#60791)` | bug,risk | main | - |
| - | [#65604](https://github.com/vllm-project/vllm/pull/65604) `[Perf][Core] Bound FIFO eviction cost for duplicate prefixes` | perf | main | - |
| - | [#65605](https://github.com/vllm-project/vllm/pull/65605) `[Frontend] Add generative box answers for multimodal models on /v1/systemone` |  | main | - |
| - | [#65606](https://github.com/vllm-project/vllm/pull/65606) `[Perf][Model] Shard large QSA prefill query rows on SM90 TP4/TP8` | infra,nvidia,perf | main | - |
| - | [#65607](https://github.com/vllm-project/vllm/pull/65607) `[Perf][HiSparse] Batch the coordinator's per-page residency bookkeeping` | perf | main | - |
| - | [#65608](https://github.com/vllm-project/vllm/pull/65608) `[Bugfix][Structured Output] Honor request stop tokens in Guidance` | bug | main | - |
| - | [#65609](https://github.com/vllm-project/vllm/pull/65609) `[Recipes] Add Kimi-K2.6 overlay placement anchors and dynamic client model` | infra | main | - |
| - | [#65611](https://github.com/vllm-project/vllm/issues/65611) `[Bug]: gpt-oss-20b + nebius/EAGLE3-gpt-oss-20b gives corrupted greedy output at num_speculative_tokens >= 5 on` | risk,rocm | ? | - |
| - | [#65612](https://github.com/vllm-project/vllm/pull/65612) `[Doc] Add 2x RTX 3090 (Ampere, sm86) AWQ INT4 recipe for Qwen3.8-27B` | infra,quant | main | - |
| - | [#65613](https://github.com/vllm-project/vllm/pull/65613) `[KV Transfer] Integrate layerwise transfer into MooncakeConnector` |  | main | - |
| - | [#65614](https://github.com/vllm-project/vllm/pull/65614) `[Frontend] Align hybrid LB mode in server CLI with create_engine_config for headless nodes` |  | main | - |
| - | [#65615](https://github.com/vllm-project/vllm/pull/65615) `[Bugfix][Multimodal] Molmo2: snap NTSC frame rates in fps sampling` | bug | main | - |
| - | [#65616](https://github.com/vllm-project/vllm/pull/65616) `[Bugfix] Serialize YAML list items that are mappings as JSON in --config` | bug,infra | main | - |
| - | [#65617](https://github.com/vllm-project/vllm/pull/65617) `[Bugfix] Skip optional vision import for text-only warmup` | bug | main | - |
| - | [#65618](https://github.com/vllm-project/vllm/issues/65618) `[Bug]: DSpark draft for DeepSeek-V4 models has no `packed_modules_mapping` → fused layers ignore `ignored_laye` | bug,perf,quant,rocm | ? | - |
| - | [#65626](https://github.com/vllm-project/vllm/issues/65626) `[Bug]: OffloadingConnector KV events drop the request's extra_keys (cache_salt), so a KV-event consumer can't ` |  | ? | - |
| - | [#65627](https://github.com/vllm-project/vllm/pull/65627) `[Bugfix][Attention] Keep FA sliding window active under batch invariance` | bug | main | - |
| - | [#65628](https://github.com/vllm-project/vllm/pull/65628) `[ROCm][Perf][Qwen4Exp] Opt-in exact AITER IPC and INT4 QuickReduce collectives for the --enable-hc-sp layers` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#65629](https://github.com/vllm-project/vllm/pull/65629) `[Rust Frontend][Perf] Reduce per-request output channel memory` | perf | main | - |
| - | [#65630](https://github.com/vllm-project/vllm/pull/65630) `[Perf][Quantization] Batch the Marlin MoE scale and zero-point conversion over experts` | perf,quant | main | - |
| - | [#65632](https://github.com/vllm-project/vllm/issues/65632) `[Bug]: vLLM Kimi k3 KVV AMD GPU product quality issue (DeepSWE & BEAM)` | bug,rocm | ? | - |
| - | [#65633](https://github.com/vllm-project/vllm/pull/65633) `[CI] Re-enable Ascend CI` | infra | main | - |
| - | [#65634](https://github.com/vllm-project/vllm/pull/65634) `[Feature] Add POST /set_log_level to change logger levels at runtime` | bug | main | - |
| - | [#65637](https://github.com/vllm-project/vllm/pull/65637) `[Core] SubGPU pipelining: run micro-batches on green-context SM pools (Model Runner V2)` | nvidia | main | - |
| - | [#65638](https://github.com/vllm-project/vllm/pull/65638) `[ROCm][MiniMax-M3] Mono decode on the NVFP4 KV and index caches` | quant,rocm | main | - |
| - | [#65639](https://github.com/vllm-project/vllm/pull/65639) `[KVConnector][NIXL] Add stream-ordered same-host CUDA IPC pulls` | nvidia | main | - |
| - | [#65640](https://github.com/vllm-project/vllm/pull/65640) `[Bugfix][KV Offload] Refresh streaming request keys after preemption` | bug | main | - |
| - | [#65642](https://github.com/vllm-project/vllm/pull/65642) `[Qwen4Exp] Clean up hybrid cache spec plumbing` | perf | main | - |
| - | [#65643](https://github.com/vllm-project/vllm/pull/65643) `[Refactor][PCP] Separate physical topology from attention execution layout` | infra | main | - |
| - | [#65644](https://github.com/vllm-project/vllm/issues/65644) `[Bug]: Streaming final usage chunk intermittently omits metrics.speculative_decoding while spec-decode Prometh` | bug,quant | ? | - |
| - | [#65645](https://github.com/vllm-project/vllm/pull/65645) `[ROCm][MiniMax-M3] Default to breakable CUDA graphs tests on ROCM` | nvidia,rocm | main | - |
| - | [#65647](https://github.com/vllm-project/vllm/pull/65647) `[Bugfix][Spec Decode] Add packed_modules_mapping to DeepSeek-V4 DSpark models` | bug | main | - |
| - | [#65649](https://github.com/vllm-project/vllm/pull/65649) `[Perf][Sampling] Use FlashInfer top-k selection for top-k/top-p masking` | nvidia,perf | main | - |
| - | [#65650](https://github.com/vllm-project/vllm/issues/65650) `[RFC]: Using Backend-Owned KV Cache Runtime Shapes` | perf,quant | ? | - |
| - | [#65651](https://github.com/vllm-project/vllm/pull/65651) `[Bugfix][Tool Parser] llama4_json: parse parallel tool calls without ";" separator` | bug,infra | main | - |
| - | [#65653](https://github.com/vllm-project/vllm/issues/65653) `[Feature]: Support simultaneous Tool Calling and Structured Output via Grammar Union / Prefix Tree` |  | ? | - |
| - | [#65654](https://github.com/vllm-project/vllm/pull/65654) `[Frontend] Support repetition_detection in Responses and Messages to stop repetitive generation` |  | main | - |
| - | [#65655](https://github.com/vllm-project/vllm/pull/65655) `[Core][DP][WIP] Add a cross-DP prefill delayer scheduling policy` | rocm | main | - |
| - | [#65656](https://github.com/vllm-project/vllm/pull/65656) `[Perf][DSV4.1] Accelerate candidate prefill and decode with CuTe` | infra,perf | main | - |
| - | [#65657](https://github.com/vllm-project/vllm/pull/65657) `[Mamba] Add FlashInfer GDN ReplaySSM STP, MTP, and prefix caching` | infra,nvidia | main | - |
| - | [#65658](https://github.com/vllm-project/vllm/pull/65658) `[ROCm][PP] Stage hand-off on SDMA copy engines (--pp-sdma-handoff)` | infra,rocm | main | - |
| - | [#65659](https://github.com/vllm-project/vllm/pull/65659) `[Bugfix][Multimodal] Normalize audio layout before resampling` | bug | main | - |
| - | [#65660](https://github.com/vllm-project/vllm/pull/65660) `WIP: [Mamba] Add separate CuTeDSL ReplaySSM checkpoints` | infra,perf | main | - |
| - | [#65661](https://github.com/vllm-project/vllm/pull/65661) `[Bugfix][CPU] Support Mamba2 internal prefill checkpoints on CPU` | bug,infra | main | - |
| - | [#65662](https://github.com/vllm-project/vllm/issues/65662) `[Bug]: v0.33.0 GitHub Release incorrectly points to v0.33.0rc3 tag` | bug,infra | ? | - |
| - | [#65663](https://github.com/vllm-project/vllm/pull/65663) `[Bugfix][KV] Avoid partial ExampleConnector snapshots` | bug | main | - |
| - | [#65664](https://github.com/vllm-project/vllm/pull/65664) `[Bugfix][Kimi-K3] Fall back from the latent-MoE tail fusion without NVLS multicast` | bug,perf | main | - |
| - | [#65665](https://github.com/vllm-project/vllm/pull/65665) `[hw-agnostic] Triton attention backend for the Transformers backend` | rocm | main | - |
| - | [#65666](https://github.com/vllm-project/vllm/pull/65666) `[Kernel][LoRA][MoE] Skip zero intermediate rank tiles in fused MoE LoRA expand` | perf | main | - |
| - | [#65667](https://github.com/vllm-project/vllm/pull/65667) `[Bugfix][MRV2]  Read routed experts from unkeyed full blocks` | bug,infra | main | - |
| - | [#65670](https://github.com/vllm-project/vllm/pull/65670) `[Feature][Frontend] Add completion-order output to run-batch` |  | main | - |
| - | [#65671](https://github.com/vllm-project/vllm/pull/65671) `[Bugfix][Mooncake] Settle decoder pull preparation failures` | bug | main | - |
| - | [#65672](https://github.com/vllm-project/vllm/pull/65672) `[Bugfix][Mooncake] Make early prefill abort cleanup idempotent` | bug | main | - |
| - | [#65673](https://github.com/vllm-project/vllm/pull/65673) `[Perf][MoE] Fuse paired Humming routing alignment on SM90` | infra,nvidia,perf | main | - |
| - | [#65675](https://github.com/vllm-project/vllm/pull/65675) `[Perf] Tune FlashInfer MNNVL all-reduce cutoffs for single-node TP4/TP8 on SM90` | nvidia,perf | main | - |
| - | [#65676](https://github.com/vllm-project/vllm/pull/65676) `[Quantization] Prefer Humming over Marlin for int4 g128 on SM12x` | quant | main | - |
| - | [#65677](https://github.com/vllm-project/vllm/issues/65677) `[Feature]: CPU : support heterogeneous memory (DDR + HBM) NUMA node via hwloc` |  | ? | - |
| - | [#65678](https://github.com/vllm-project/vllm/pull/65678) `[CPU] Support heterogeneous memory (DDR + HBM) NUMA nodes via hwloc` |  | main | - |
| - | [#65680](https://github.com/vllm-project/vllm/issues/65680) `[Bug]: Kimi-K3 hybrid model (24 full-attn + 69 linear-attn) degenerates into repeated @ tokens on long prompts` | nvidia | ? | - |
| - | [#65681](https://github.com/vllm-project/vllm/pull/65681) `[KV Offload][2/N] Add ON_OVERWRITE stores and the lazy store mode` |  | main | - |
| - | [#65683](https://github.com/vllm-project/vllm/pull/65683) `[Bugfix][KV Offload] Size the lazy walk target for sliding-window allocations` | bug,perf | main | - |
| - | [#65685](https://github.com/vllm-project/vllm/pull/65685) `[Model] Kimi K3.1 Pro (split 4/5: ROCm, P/D, indexer top-k)` | infra,nvidia,perf,rocm | main | - |
| - | [#65687](https://github.com/vllm-project/vllm/pull/65687) `[Recipe] Add Qwen recipes with IAXL KVShrink support` | infra | main | - |
| - | [#65690](https://github.com/vllm-project/vllm/pull/65690) `[ROCm][MORI IO]Moriio handshake failure ` | rocm | main | - |
| - | [#65691](https://github.com/vllm-project/vllm/pull/65691) `[Perf][Spec Decode] Fused logits gather for the DSpark draft head of opted-in models` | infra,perf | main | - |
| - | [#65693](https://github.com/vllm-project/vllm/issues/65693) `[Bug]: /v1/messages streaming reports a tool call cut short by EOS as stop_reason tool_use` |  | ? | - |
| - | [#65694](https://github.com/vllm-project/vllm/pull/65694) `[Core][KV Connector] Add VLLM_KV_SCRAMBLE_BLOCKS to test and benchmark with a fragmented KV pool` | perf | main | - |
| - | [#65695](https://github.com/vllm-project/vllm/pull/65695) `[Bugfix][Frontend] Report a tool call cut short by EOS as end_turn in Anthropic streaming` | bug | main | - |
| - | [#65696](https://github.com/vllm-project/vllm/pull/65696) `Experiment OCTAVE KV on GFX1151` | infra,rocm | main | - |
| - | [#65698](https://github.com/vllm-project/vllm/pull/65698) `[Build] Compile DeepGEMM's extension through the compiler launcher` | infra | main | - |
| - | [#65699](https://github.com/vllm-project/vllm/pull/65699) `[Bugfix] Infer the per-layer attention module count from KV cache layer names` | bug,perf | main | - |
| - | [#65700](https://github.com/vllm-project/vllm/pull/65700) `[Kernel][Triton] Allow an fp8_e5m2 KV cache on SM80-SM88` | perf,quant,rocm | main | - |
| - | [#65701](https://github.com/vllm-project/vllm/pull/65701) `[Bugfix][Benchmark] Fix multichannel ASR audio duration filtering` | bug,perf | main | - |
| - | [#65702](https://github.com/vllm-project/vllm/pull/65702) `[Perf][KV Connector] Mooncake store: build and parse lookup candidates in bulk` | infra,perf | main | - |
| - | [#65703](https://github.com/vllm-project/vllm/pull/65703) `[Doc][ROCm] Qwen3.5-122B-A10B recipe: move AMD to v0.33.0, retire the UNIFIED_ATTN warning` | infra,rocm | main | - |
| - | [#65704](https://github.com/vllm-project/vllm/pull/65704) `[Bugfix][GLM-5.3] Build the MTP eh_proj low-latency GEMM plan` | bug,infra,perf | main | - |
| - | [#65705](https://github.com/vllm-project/vllm/pull/65705) `[Bugfix][Gemma4] Don't add empty thought block to past model turns in tool_chat_template_gemma4.jinja` | bug | main | - |
| - | [#65706](https://github.com/vllm-project/vllm/pull/65706) `[Perf][GLM-5.3] Use FlashInfer's warp split-K BF16 GEMM for the SM107 low-latency table` | nvidia,perf | main | - |
| - | [#65707](https://github.com/vllm-project/vllm/issues/65707) `[RFC]: [Draft] Split FusedMoEQuantConfig into static schema and runtime state` | perf,quant | ? | - |
| - | [#65708](https://github.com/vllm-project/vllm/pull/65708) `[Triton] Enable tunable BLOCK_SIZEs based on current plarform` | rocm | main | - |
| - | [#65711](https://github.com/vllm-project/vllm/pull/65711) `[ROCm][Perf] Use tuned AITER Triton `gemm_a8w8` for per-tensor FP8 decode GEMMs on gfx950` | perf,quant,rocm | main | - |
| - | [#65712](https://github.com/vllm-project/vllm/pull/65712) `[Bugfix][MoRIIO] Expire write_done notifications no request matches` | bug,rocm | main | - |
| - | [#65713](https://github.com/vllm-project/vllm/pull/65713) `[Perf][Model Loader] Route sharded_state, reload and Engram table copies through copy_weight_` | perf | main | - |
| - | [#65714](https://github.com/vllm-project/vllm/issues/65714) `[RFC]: A KV compatibility identity, enforced on NIXL and P2P transfers and readable by routers` | quant | ? | - |
| - | [#65715](https://github.com/vllm-project/vllm/pull/65715) `[ROCm][Perf][Kimi-K3] Add HipCustomCommunicator, a communicator to support complex fusions. ` | infra,nvidia,perf,rocm | main | - |
| - | [#65716](https://github.com/vllm-project/vllm/pull/65716) `More gfx1250 models, di, and perf fixes ` | infra,perf,quant,rocm | main | - |
| - | [#65717](https://github.com/vllm-project/vllm/pull/65717) `[ROCm][Perf][MLA] Fold the decode RoPE + KV-cache write into the AITER fused decode query` | perf,rocm | main | - |
| - | [#65718](https://github.com/vllm-project/vllm/pull/65718) `[ROCm] Guard FlashInfer import and add portable rsqrt fallback in Flint` | nvidia,rocm | main | - |
| - | [#65719](https://github.com/vllm-project/vllm/pull/65719) `[Bugfix][CPU] Use the C++ GDN conv in speculative decoding on AVX-512BF16 CPUs` | bug | main | - |
| - | [#65720](https://github.com/vllm-project/vllm/pull/65720) `[Bugfix][CPU] Compute beta in float32 in the GDN decode kernel` | bug,perf | main | - |
| - | [#65721](https://github.com/vllm-project/vllm/issues/65721) `[Bug]: NixlConnector drops kv_connector_extra_config.num_threads for non-UCX backends` |  | ? | - |
| - | [#65723](https://github.com/vllm-project/vllm/pull/65723) `[Kernel] Add per-phase linear activation precision to quantization_config` | perf,quant | main | - |
| - | [#65724](https://github.com/vllm-project/vllm/pull/65724) `[MM] Support mm_device_do_normalize for Gemma 4 Unified` |  | main | - |
| - | [#65726](https://github.com/vllm-project/vllm/issues/65726) `[Bug]: /v1/completions top_logprobs overwrites the sampled token's entry when candidates decode to the same st` |  | ? | - |
| - | [#65727](https://github.com/vllm-project/vllm/pull/65727) `[MoE][FlashInfer] Opt-in transport (CFT/Lamport) selection for NVLink one-sided all-to-all` | nvidia | main | - |
| - | [#65728](https://github.com/vllm-project/vllm/pull/65728) `[Bugfix][Perf] Cache FABRIC handle fallback in cumem allocator` | bug,perf | main | - |
| - | [#65729](https://github.com/vllm-project/vllm/pull/65729) `[Refactor][Spec Decode] Use the DFlash parent helper for Muse DSpark context KV init` | bug | main | - |
| - | [#65730](https://github.com/vllm-project/vllm/pull/65730) `[Bugfix] Make beam search with structured outputs reachable` | bug,infra | main | - |
| - | [#65731](https://github.com/vllm-project/vllm/pull/65731) `[Perf] Let a grammar hand beam search its allowed tokens directly` | perf | main | - |
| - | [#65732](https://github.com/vllm-project/vllm/pull/65732) `[Quantization] Support tensor parallelism for block-diagonal compressed-tensors Hadamard transforms` | quant | main | - |
| - | [#65733](https://github.com/vllm-project/vllm/pull/65733) `[CI] Make DSpark sharded-sampling test deterministic under torch.compile` | infra | main | - |
| - | [#65734](https://github.com/vllm-project/vllm/issues/65734) `[Bug][ROCm]: Dense attention output allocated with torch.empty — CUDA-graph padding rows poison the dynamic pe` | nvidia,quant,risk,rocm | ? | - |
| - | [#65735](https://github.com/vllm-project/vllm/pull/65735) `[Model] Add transcription to the Transformers modeling backend` |  | main | - |
| - | [#65737](https://github.com/vllm-project/vllm/pull/65737) `[Bugfix][Kernel] Use 64-bit row offsets in the persistent and cooperative top-k kernels` | bug,perf | main | - |
| - | [#65738](https://github.com/vllm-project/vllm/pull/65738) `[Spec Decode] Remove the one-chunk cap on adaptive verification` |  | main | - |
| - | [#65739](https://github.com/vllm-project/vllm/pull/65739) `[Feature][Attention] Add NIXL GPU Device API for MLA DCP A2A` | infra | main | - |
| - | [#65740](https://github.com/vllm-project/vllm/pull/65740) `[CI] Enable mypy for tests/v1/core and tests/v1/engine` | infra,perf | main | - |
| - | [#65741](https://github.com/vllm-project/vllm/pull/65741) `[Bugfix][Frontend] Keep the sampled token's entry in /v1/completions top_logprobs` | bug | main | - |
| - | [#65742](https://github.com/vllm-project/vllm/pull/65742) `[ROCm][Perf][DSv4.1] Use the single-kernel DSv4 top-k on ROCm` | perf,rocm | main | - |
| - | [#65743](https://github.com/vllm-project/vllm/pull/65743) `[Refactor] Remove dead code kernels` | perf,quant | main | - |
| - | [#65744](https://github.com/vllm-project/vllm/pull/65744) `[Bugfix][Frontend] Normalize Chat Completions tools and tool_choice validation` | bug | main | - |
| - | [#65746](https://github.com/vllm-project/vllm/pull/65746) `[GLM 5.3 Perf] Expand fp8 moe tma for sm100, 1.03~1.60x kernel performance improvement` | nvidia,perf,quant | main | - |
| - | [#65747](https://github.com/vllm-project/vllm/pull/65747) `[ROCm][Perf][Muse Spark] fp8 (e4m3) KV cache for the decode monokernel` | perf,quant,rocm | main | - |
| - | [#65748](https://github.com/vllm-project/vllm/pull/65748) `[ROCm][Perf][Muse Spark] Decode monokernel TP4 EP4` | perf,rocm | main | - |
| - | [#65749](https://github.com/vllm-project/vllm/pull/65749) `[ROCm][Perf][DSv4.1] Split-K BF16 router GEMM for gfx950 decode batches` | infra,perf,rocm | main | - |
| - | [#65751](https://github.com/vllm-project/vllm/issues/65751) `[Performance]: DFlash drafts the full block under dynamic speculative decoding, so a small runtime K still pay` | perf | ? | - |
| - | [#65754](https://github.com/vllm-project/vllm/pull/65754) `[ROCm][RDNA][MoE] Add hybrid W4A16 MoE backend for gfx115x (HIP decode + Triton prefill)` | infra,quant,rocm | main | - |
| - | [#65755](https://github.com/vllm-project/vllm/pull/65755) `[Bugfix][Step5] Fix FP32 residual truncation at pipeline boundaries` | bug,risk | main | - |
| - | [#65756](https://github.com/vllm-project/vllm/pull/65756) `[Bugfix] Ship vllm/utils/numa_wrapper.sh in the wheel` | bug,infra | main | - |
| - | [#65757](https://github.com/vllm-project/vllm/pull/65757) `[Rust Frontend] Check tokenizer ids against the Python frontend` |  | main | - |
| - | [#65758](https://github.com/vllm-project/vllm/pull/65758) `Quant config refactor 2` | infra,nvidia,quant | main | - |
| - | [#65759](https://github.com/vllm-project/vllm/pull/65759) `Quant config refactor 3` | infra,nvidia,quant,rocm | main | - |
| - | [#65760](https://github.com/vllm-project/vllm/pull/65760) `Fused MoE quant config refactor` | infra,perf,quant | main | - |
| - | [#65764](https://github.com/vllm-project/vllm/pull/65764) `[Model] Add LoRA support for Reflection Beam` |  | main | - |
| - | [#65765](https://github.com/vllm-project/vllm/pull/65765) `[CI/Build][NVIDIA] Move Rubin nightly images to CUDA 13.5` | infra,nvidia | main | - |
| - | [#65766](https://github.com/vllm-project/vllm/pull/65766) `[DeepSeek-V4] Support sequence parallelism with pipeline parallelism for MegaMoE` |  | main | - |
| - | [#65767](https://github.com/vllm-project/vllm/pull/65767) `[ROCm][Perf] Add Gluon MXFP8 prefill kernels on gfx950` | perf,quant,rocm | main | - |
| - | [#65768](https://github.com/vllm-project/vllm/pull/65768) `[Perf][Rust][Benchmark] Reuse allowed tokens in multi-turn generation` | perf | main | - |
| - | [#65769](https://github.com/vllm-project/vllm/issues/65769) `[Bug]: CuMemAllocator.discard retains the CPU backup of asleep allocations` |  | ? | - |
| - | [#65770](https://github.com/vllm-project/vllm/issues/65770) `[Bug]: gpt-oss chat completions return 500 when a prior tool call name contains special-token text` |  | ? | - |
| - | [#65771](https://github.com/vllm-project/vllm/pull/65771) `[Bugfix][Frontend] Encode special-token text as plain text in gpt-oss legacy tool-call headers` | bug | main | - |
| - | [#65772](https://github.com/vllm-project/vllm/pull/65772) `[Bugfix][SleepMode] Release CPU backups when discarding asleep allocations` | bug,infra | main | - |
| - | [#65774](https://github.com/vllm-project/vllm/issues/65774) `[Bug]: qwen3_coder: a repeated parameter breaks the streamed tool call arguments` |  | ? | - |
| - | [#65775](https://github.com/vllm-project/vllm/pull/65775) `[Bugfix][Parser] Keep the first value of a repeated Qwen3 tool parameter` | bug | main | - |
| - | [#65777](https://github.com/vllm-project/vllm/pull/65777) `[Frontend][Realtime] Add server-side turn detection (server_vad / semantic_vad) to /v1/realtime` | infra | main | - |
| - | [#65779](https://github.com/vllm-project/vllm/pull/65779) `[Frontend] Stream diarized_json transcriptions as segment events` |  | main | - |
| - | [#65780](https://github.com/vllm-project/vllm/pull/65780) `[Frontend] Support output logprobs for gpt-oss in the Responses API (…` |  | main | - |
| - | [#65781](https://github.com/vllm-project/vllm/pull/65781) `[Bugfix][Frontend] Align DeepSeek V4.1 thinking precedence with Rust` | bug,infra | main | - |
| - | [#65782](https://github.com/vllm-project/vllm/issues/65782) `[RFC]: SM90 DeepGEMM MegaMoE for DeepSeek V4` | nvidia | ? | - |
| - | [#65783](https://github.com/vllm-project/vllm/pull/65783) `[Bugfix][MM] Do not offer cuDNN FP8 ViT attention on SM 12x` | bug,nvidia,quant | main | - |
| - | [#65784](https://github.com/vllm-project/vllm/pull/65784) `[Bugfix][Tool Parser] Stream all tool calls completed in one delta (ernie45, jamba, granite-20b-fc)` | bug | main | - |
| - | [#65785](https://github.com/vllm-project/vllm/pull/65785) `[ROCm][Kimi-K3][Perf] Support BF16 MLA projections in specialized decode` | perf,rocm | main | - |
| - | [#65786](https://github.com/vllm-project/vllm/pull/65786) `[Bugfix][KV Offload] Preserve block extra keys across async request cleanup` | bug,infra | main | - |
| - | [#65787](https://github.com/vllm-project/vllm/pull/65787) `[Bugfix][Mooncake] Reclaim unclaimed transfer placeholders` | bug | main | - |
| - | [#65788](https://github.com/vllm-project/vllm/pull/65788) `[XPU][UT] Enable v1/attention tests on XPU` | nvidia | main | - |
| - | [#65789](https://github.com/vllm-project/vllm/pull/65789) `[Bugfix][MoE] Pad block-FP8 weight scales for the HPC MoE backend` | bug,quant | main | - |
| - | [#65790](https://github.com/vllm-project/vllm/pull/65790) `[Perf][MoE] Let DeepGEMM MoE fall back to Triton for small M on Hopper` | nvidia,perf,rocm | main | - |
| - | [#65791](https://github.com/vllm-project/vllm/pull/65791) `[Perf] Vectorize silu_and_mul_per_block_quant for large inputs` | perf,quant | main | - |
| - | [#65792](https://github.com/vllm-project/vllm/pull/65792) `[BugFix][DP] Hash the parallel config before engine init for DP validation` | bug | main | - |
| - | [#65793](https://github.com/vllm-project/vllm/issues/65793) `[Bug]: DeepSeek-V4.1-Flash: some DP ranks of a multi-node DP/EP decode engine produce degenerate output (rank-` |  | ? | - |
| - | [#65794](https://github.com/vllm-project/vllm/pull/65794) `[Perf][MoE] Triton FP8 MoE: per-layer activation scale format and always-fused SiLU+quant` | perf,quant,rocm | main | - |
| - | [#65795](https://github.com/vllm-project/vllm/pull/65795) `[Core] Stop re-queuing waiting requests that max_loras blocks` |  | main | - |
| - | [#65796](https://github.com/vllm-project/vllm/pull/65796) `[Benchmark] Compare MXFP4 MoE backends at GLM-5.3 shapes` | perf,quant | main | - |
| - | [#65797](https://github.com/vllm-project/vllm/issues/65797) `[RFC]: Token-id parity with the Python frontend as a tested contract for the Rust frontend` |  | ? | - |
| - | [#65799](https://github.com/vllm-project/vllm/pull/65799) `[RL][Model Loader] Direct reload: check that an update loaded every parameter` |  | main | - |
| - | [#65802](https://github.com/vllm-project/vllm/pull/65802) `[Model Loader] Direct reload of online-quantized modules` | quant | main | - |
| - | [#65804](https://github.com/vllm-project/vllm/pull/65804) `[Spec Decode] Treat standalone draft model prefill as decode` |  | main | - |
| - | [#65807](https://github.com/vllm-project/vllm/issues/65807) `[Bug]: cyankiwi/Qwen3.8-27B-AWQ-INT4输出混乱` | bug,quant | ? | - |
| - | [#65808](https://github.com/vllm-project/vllm/pull/65808) `[Bugfix] Fix DP ViT all-gather dtype mismatch when the first parameter is fp32` | bug | main | - |
| - | [#65809](https://github.com/vllm-project/vllm/pull/65809) `[RL][Model Loader] Load plan: stacked (transformers v5) routed experts as per-expert views` | infra | main | - |
| - | [#65813](https://github.com/vllm-project/vllm/issues/65813) `[RFC]: Add a Tree Speculative Decoding Framework` |  | ? | - |
| - | [#65814](https://github.com/vllm-project/vllm/pull/65814) `[KV Events] Add opt-in inline event source attribution` | infra | main | - |
| - | [#65815](https://github.com/vllm-project/vllm/pull/65815) `[Quantization] Add a KV-cache KL benchmark that reads the quantized cache` | perf,quant | main | - |
| - | [#65818](https://github.com/vllm-project/vllm/pull/65818) `[Bugfix] Fix Granite 4.1 Vision deepstack handoff between pipeline stages` | bug | main | - |
| - | [#65820](https://github.com/vllm-project/vllm/pull/65820) `[Bugfix][Attention] Zero-init dense attention output buffers to prevent CUDA-graph padding corruption (#65734)` | bug,nvidia,risk | main | - |
| - | [#65821](https://github.com/vllm-project/vllm/issues/65821) `[Bug]: FP8 KV cache with `kv_cache_dtype_skip_layers` crashes FA3: "scheduler_metadata must have shape (metada` | bug,nvidia,perf,quant | ? | - |
| - | [#65822](https://github.com/vllm-project/vllm/pull/65822) `[Perf][KV Connector][ROCm] MoRIIO WRITE: skip blocks the decoder prefix cache already holds` | perf,rocm | main | - |
| - | [#65829](https://github.com/vllm-project/vllm/pull/65829) `[Model] Add LFM3-Omni` |  | main | - |
| - | [#65830](https://github.com/vllm-project/vllm/pull/65830) `[Bugfix][Attention] Prevent overlapping query tile writes in Triton unified attention` | bug,rocm | main | - |
| - | [#65832](https://github.com/vllm-project/vllm/pull/65832) `[ROCm][DSV4.1] Honor the multi-stream GEMM token threshold in the CSA attention path` | infra,rocm | main | - |
| - | [#65833](https://github.com/vllm-project/vllm/pull/65833) `[ROCm] Run SiluAndMulWithClamp through AITER's fused clamped SwiGLU` | perf,rocm | main | - |
| - | [#65835](https://github.com/vllm-project/vllm/pull/65835) `[Bugfix][Model] Gemma 4: support checkpoints without a vision tower` | bug | main | - |
| - | [#65836](https://github.com/vllm-project/vllm/pull/65836) `[Spec Decode][Qwen4Exp] Enable local argmax reduction for NVIDIA MTP` | nvidia | main | - |
| - | [#65837](https://github.com/vllm-project/vllm/pull/65837) `[ROCm][DSV4.1] Quantize the shared query once with AITER's fused dual RMSNorm` | perf,quant,rocm | main | - |
| - | [#65838](https://github.com/vllm-project/vllm/pull/65838) `[Perf][MiniMax-M3] Port cross-layer index top-k sharing to the NVIDIA path` | infra,nvidia,perf | main | - |
| - | [#65839](https://github.com/vllm-project/vllm/pull/65839) `[Bugfix][Core] Compare all attention fields in SlidingWindowMLASpec.merge` | bug,perf | main | - |
| - | [#65840](https://github.com/vllm-project/vllm/pull/65840) `[XPU][Kimi-K3] Run KDA metadata tests on XPU` | nvidia | main | - |
| - | [#65841](https://github.com/vllm-project/vllm/issues/65841) `[Feature]: Support n > 1 sampling, multimodal processor kwargs, and output_mode: derender in vllm.Inference` |  | ? | - |
| - | [#65842](https://github.com/vllm-project/vllm/pull/65842) `[Bugfix][MoE] Only divide shared expert output in FP16 for models that compensate` | bug | main | - |
| - | [#65843](https://github.com/vllm-project/vllm/pull/65843) `[Perf][Qwen4Exp] Add opt-in SM120 GDN norm/MXFP8 decode fusion` | infra,nvidia,perf,quant | main | - |
| - | [#65848](https://github.com/vllm-project/vllm/pull/65848) `[Model] Add Ling VL video, YaRN, and vision DP support` | infra | main | - |
| - | [#65855](https://github.com/vllm-project/vllm/pull/65855) `[Test] Cover small-router unquantized linear batch invariance` | quant | main | - |
| - | [#65856](https://github.com/vllm-project/vllm/issues/65856) `[Bug]: Draft-model speculative decoding exceeds the token budget during warmup` | bug | ? | - |
| - | [#65858](https://github.com/vllm-project/vllm/pull/65858) `[ROCm][Perf][MiniMax-M3] Fuse prefill all-reduce + GemmaRMSNorm via FlyDSL QuickReduce` | infra,perf,rocm | main | - |
| - | [#65859](https://github.com/vllm-project/vllm/pull/65859) `support qwen3.8-flash-next pp` |  | main | - |
| - | [#65860](https://github.com/vllm-project/vllm/pull/65860) `[Bugfix] Account for draft slots in GPU warmup batch sizing` | bug | main | - |
| - | [#65862](https://github.com/vllm-project/vllm/pull/65862) `[Recipe] Kimi-K3: add MI355X Mooncake disaggregated prefill/decode guide` | infra,rocm | main | - |
| - | [#65864](https://github.com/vllm-project/vllm/pull/65864) `[Rust Frontend] Return routed experts on non-streaming chat and completions` |  | main | - |
| - | [#65865](https://github.com/vllm-project/vllm/pull/65865) `[Recipe] Update Zhenwu Kimi-K3.1-Pro settings` | infra | main | - |
| - | [#65866](https://github.com/vllm-project/vllm/pull/65866) `[Bugfix] Move model inspection RPC out of LLM.__repr__` | bug | main | - |
| - | [#65868](https://github.com/vllm-project/vllm/issues/65868) `[Bug]: MRV2 extensible KV cache commits all KV before encoder CUDA graph capture, so cudagraph_mm_encoder OOMs` | nvidia,perf | ? | - |
| - | [#65869](https://github.com/vllm-project/vllm/pull/65869) `[XPU][CI] fix the wrong test name in intel CI` | bug,infra,nvidia | main | - |
| - | [#65870](https://github.com/vllm-project/vllm/pull/65870) `[Kernel] Route MXFP8 linears to FlashInfer b12x on SM12x` | nvidia,perf,quant | main | - |
| - | [#65871](https://github.com/vllm-project/vllm/pull/65871) `[Bugfix][Attention] Fix V masking for non-causal sliding-window attention` | bug | main | - |
| - | [#65873](https://github.com/vllm-project/vllm/issues/65873) `[Bug]: Nemotron-3.5-Super-VL-120B-A12B-NVFP4 native MTP fails to load: "start (0) + length (5376) exceeds dime` | bug,quant | ? | - |
| - | [#65874](https://github.com/vllm-project/vllm/pull/65874) `[Kernel][Perf] Fused GDN MTP: Support DSpark K=8 and use idle SMs at small batch sizes` | perf | main | - |
| - | [#65876](https://github.com/vllm-project/vllm/pull/65876) `[KV Offload] Prefetch secondary lookups on request admission` |  | main | - |
| - | [#65877](https://github.com/vllm-project/vllm/pull/65877) `[Misc] Separate Mooncake PD and Store connectors into sibling packages` | infra | main | - |
| - | [#65880](https://github.com/vllm-project/vllm/pull/65880) `[Perf][Model Runner V2] Skip no-op staged-write flush of BlockTables.num_blocks` | perf | main | - |
| - | [#65881](https://github.com/vllm-project/vllm/pull/65881) `[CI] Let ci-selector decide CMakeLists.txt changes on CUDA` | bug,infra,nvidia | main | - |
| - | [#65882](https://github.com/vllm-project/vllm/pull/65882) `[EPD] Support native gRPC workers in the Python proxy` | infra | main | - |
| - | [#65884](https://github.com/vllm-project/vllm/pull/65884) `[Perf] Cut eager host overhead of collectives, MoE and router custom ops` | infra,perf | main | - |
| - | [#65885](https://github.com/vllm-project/vllm/pull/65885) `[Perf] Cache per-call host work in MXFP8 linear, NVFP4 KV views, NVFP4 MoE and router GEMM` | infra,nvidia,perf,quant | main | - |
| - | [#65886](https://github.com/vllm-project/vllm/issues/65886) `[Feature]: Add gc-moe as an option for moe-backend` |  | ? | - |
| - | [#65887](https://github.com/vllm-project/vllm/pull/65887) `fix(mamba): stop a mid-block resume at the block boundary` | bug | main | - |
| - | [#65888](https://github.com/vllm-project/vllm/pull/65888) `[HiSparse] Alternative to #55398: promote P/D imports into GPU pages without NIXL changes` | bug,perf | main | - |
| - | [#65890](https://github.com/vllm-project/vllm/pull/65890) `[Model Loader] streamingly load weights files.` | perf | main | - |
| - | [#65891](https://github.com/vllm-project/vllm/pull/65891) `[Bugfix] Fix FA3 crash with kv_cache_dtype_skip_layers under an FP8 KV cache` | bug,nvidia,perf,quant | main | - |
| - | [#65892](https://github.com/vllm-project/vllm/pull/65892) `[Bugfix][Frontend] Truncate singleton-batch prompt embeddings correctly` | bug,risk | main | - |
| - | [#65893](https://github.com/vllm-project/vllm/pull/65893) `[Benchmark][KV Offload] Add multi-turn KV offloading benchmark script` | perf | main | - |
| - | [#65894](https://github.com/vllm-project/vllm/pull/65894) `[Docs] Prepare PaddleOCR-VL recipe for the Ascend owner overlay` | infra | main | - |
| - | [#65896](https://github.com/vllm-project/vllm/pull/65896) `[Perf][PP] Opt-in PP transport on CUDA copy engines (NVLink only)` | infra,nvidia,perf | main | - |
| - | [#65897](https://github.com/vllm-project/vllm/pull/65897) `[ROCm][Bugfix] DeepSeek-V4: B-preshuffle the FP8 linears in their kernel so weight reloads redo it` | bug,infra,perf,quant,rocm | main | - |
| - | [#65898](https://github.com/vllm-project/vllm/pull/65898) `[ROCm][MiniMax-M3] gfx942 MXFP4 indexer: fixes, fused decode, fast prefill` | perf,quant,rocm | main | - |
| - | [#65899](https://github.com/vllm-project/vllm/pull/65899) `[ROCm][MiniMax-M3] Serve --kv-cache-dtype mxfp4 on gfx942` | perf,quant,rocm | main | - |
| - | [#65900](https://github.com/vllm-project/vllm/pull/65900) `fix(sampler): fall back to the native sampler when FlashInfer cannot JIT-build` | bug,infra,nvidia | main | - |
| - | [#65901](https://github.com/vllm-project/vllm/pull/65901) `[Perf] Add opt-in FlashInfer multimodal encoder autotuning` | infra,nvidia,perf | main | - |
| - | [#65902](https://github.com/vllm-project/vllm/pull/65902) `[Perf][Mamba] Launch checkpoint export only for rows with a checkpoint` | perf | main | - |
| - | [#65903](https://github.com/vllm-project/vllm/pull/65903) `[Kernel][Perf] Add Blackwell BF16 tuned configs for Qwen2.5-1.5B to the batch-invariant matmul table` | nvidia,perf | main | - |
| - | [#65904](https://github.com/vllm-project/vllm/pull/65904) `[Model] Move MiniMax-M3 to `AutoWeightsLoader` and add `orig_to_new_transform`` | quant | main | - |
| - | [#65905](https://github.com/vllm-project/vllm/pull/65905) `[HiSparse][DSv4.1] Host-back the C1/C2 compressed caches on SM90` | nvidia,perf | main | - |
| - | [#65906](https://github.com/vllm-project/vllm/issues/65906) `[Bug]: Qwen3.5-122B-A10B-FP8 GSM8K accuracy decreases at commit 0fae39a` | bug,quant,risk | ? | - |
| - | [#65907](https://github.com/vllm-project/vllm/issues/65907) `[Bug]: v0.33.0: DeepSeek-V4.1 + DSpark speculative decoding OOMs at startup with `--gpu-memory-utilization=0.9` | bug,nvidia,quant | ? | - |
| - | [#65909](https://github.com/vllm-project/vllm/pull/65909) `[watermarking] Support block verification with dual_key_gumbel watermarking` |  | main | - |
| - | [#65911](https://github.com/vllm-project/vllm/pull/65911) `[ROCm][Perf] W4A16: serve 6-8 decode rows with the HIP skinny GEMM on gfx1151` | infra,perf,quant,rocm | main | - |
| - | [#65913](https://github.com/vllm-project/vllm/issues/65913) `[RFC]: Deprecate and remove the torchao reload decorator in favor of reload_weights` | quant | ? | - |
| - | [#65915](https://github.com/vllm-project/vllm/pull/65915) `[Rust Frontend] Support --override-generation-config` |  | main | - |
| - | [#65917](https://github.com/vllm-project/vllm/pull/65917) `[Perf][KV Connector] Remove superseded prompt-end Mamba checkpoints` | perf | main | - |
| - | [#65918](https://github.com/vllm-project/vllm/pull/65918) `[Quark] Rotate MXFP4 MoE activations before both GEMMs` | quant,rocm | main | - |
| - | [#65919](https://github.com/vllm-project/vllm/issues/65919) `[Bug]: benchmark_moe.py fails with Ray 2.59 on ROCm: it replaces HIP_VISIBLE_DEVICES with ROCR_VISIBLE_DEVICES` | perf,rocm | ? | - |
| - | [#65920](https://github.com/vllm-project/vllm/pull/65920) `[Perf] [NVIDIA] attention: Improve the DSA prefill kernel with LiteTopK (FP8, GLM-5.x / DeepSeek) on SM100` | infra,nvidia,perf,quant | main | - |
| - | [#65921](https://github.com/vllm-project/vllm/pull/65921) `[HiSparse] Alternative to #55398: land P/D imports in resident pages through a generic transfer view` | perf | main | - |
| - | [#65922](https://github.com/vllm-project/vllm/pull/65922) `[Bugfix][NIXL] Fix NVFP4 KV corruption with different block sizes` | bug,infra,nvidia,quant,risk | main | - |
| - | [#65923](https://github.com/vllm-project/vllm/pull/65923) `[ROCm][MORI IO]Moriio hybrid load failure` | perf,rocm | main | - |
| - | [#65925](https://github.com/vllm-project/vllm/issues/65925) `[Bug]: DeepSeek-V4.1 with DSpark adaptive verification crashes at startup on MI355X (TP8) with a GPU memory ac` | bug,rocm | ? | - |
| - | [#65926](https://github.com/vllm-project/vllm/pull/65926) `[Bugfix][DSv4.1] Use int64 row offsets in the K-cache gather kernels` | bug,perf | main | - |
| - | [#65927](https://github.com/vllm-project/vllm/pull/65927) `[Bugfix] Prune broken chunk_scaled_dot_kkt autotune configs on Hopper` | bug,nvidia,perf | main | - |
| - | [#65928](https://github.com/vllm-project/vllm/pull/65928) `[Perf] Add encoder CUDA graph support for Cohere Transcribe` | infra,nvidia,perf | main | - |
| - | [#65929](https://github.com/vllm-project/vllm/pull/65929) `[Bugfix][CPU] Validate hash-MoE tid2eid expert ids at the op boundary` | bug | main | - |
| - | [#65931](https://github.com/vllm-project/vllm/pull/65931) `[Kernel][Perf] Add H100 BF16 tuned configs for Qwen2.5-7B to the batch-invariant matmul table` | nvidia,perf | main | - |
| - | [#65932](https://github.com/vllm-project/vllm/pull/65932) `[Bugfix][Frontend] Pool HF fast tokenizers in BaseRenderer so concurrent truncation stays per request` | bug,risk | main | - |
| - | [#65933](https://github.com/vllm-project/vllm/pull/65933) `[Bugfix][Structured Output] Retry a failed cached xgrammar compile without the cache` | bug,perf | main | - |
| - | [#65934](https://github.com/vllm-project/vllm/issues/65934) `[Bug]: [InferHunt] olmo3 tool parser silently drops HTML-like plain text in streaming responses` | risk | ? | - |
| - | [#65935](https://github.com/vllm-project/vllm/pull/65935) `[Bugfix][ROCm] benchmark_moe: keep HIP_VISIBLE_DEVICES for Ray` | bug,perf,rocm | main | - |
| - | [#65936](https://github.com/vllm-project/vllm/pull/65936) `[Bugfix][Tool Parser] Olmo3: stream plain text that starts with "<"` | bug | main | - |
| - | [#65938](https://github.com/vllm-project/vllm/issues/65938) `[Bug][KV Connector] Permanent stall: parked async KV loads exhaust the GPU pool and none can allocate its tail` |  | ? | - |
| - | [#65939](https://github.com/vllm-project/vllm/pull/65939) `[Bugfix][Mooncake] Bound store prefix lookups with a circuit breaker` | bug,infra | main | - |
| - | [#65940](https://github.com/vllm-project/vllm/pull/65940) `[ROCm][CI] Run the MI355 BF16 AR-RMS fusion E2E matrices nightly with a per-PR subset` | infra,perf,rocm | main | - |
| - | [#65941](https://github.com/vllm-project/vllm/pull/65941) `[MM] Nemotron VL: resize images and video frames on the GPU with CV-CUDA` | infra,nvidia | main | - |
| - | [#65942](https://github.com/vllm-project/vllm/issues/65942) `[doc] three core functions document a return value they cannot produce (moe_unpermute, CacheOnlyModel.forward,` |  | ? | - |
| - | [#65943](https://github.com/vllm-project/vllm/pull/65943) `[KVConnector] Reuse the Mooncake PD TransferEngine in the store connector` |  | main | - |
| - | [#65944](https://github.com/vllm-project/vllm/issues/65944) `[Bug]: ModelOpt FP8 KV-cache scales are not loaded into MLA attention (DeepSeek-V2/V3, GLM-4.7-Flash, A.X-K1, ` | perf,quant | ? | - |
| - | [#65945](https://github.com/vllm-project/vllm/issues/65945) `[Bug]: GPT-J silently ignores FP8 KV-cache scales from compressed-tensors (LLM Compressor) checkpoints` | perf,quant,risk | ? | - |
| - | [#65946](https://github.com/vllm-project/vllm/issues/65946) `[Bug]: Kimi-Linear ignores checkpoint FP8 KV-cache scales (compressed-tensors and ModelOpt): its MLA layer get` | perf,quant | ? | - |
| - | [#65947](https://github.com/vllm-project/vllm/pull/65947) `[DeepSeek-V3.2] Support sequence parallelism with pipeline parallelism` | bug | main | - |
| - | [#65948](https://github.com/vllm-project/vllm/pull/65948) `[Bugfix] Load ModelOpt FP8 KV-cache scales into MLA attention` | bug,perf,quant | main | - |
| - | [#65949](https://github.com/vllm-project/vllm/pull/65949) `[Bugfix] Map compressed-tensors KV-cache scale names for GPT-J` | bug,perf,quant | main | - |
| - | [#65950](https://github.com/vllm-project/vllm/pull/65950) `[Bugfix] Load FP8 KV-cache scales for Kimi-Linear's MLA layer` | bug,perf,quant | main | - |
| - | [#65951](https://github.com/vllm-project/vllm/pull/65951) `[Bugfix][Quantization] Handle dict-valued Quark `algo_config` in `maybe_update_config`` | bug,quant,rocm | main | - |
| - | [#65952](https://github.com/vllm-project/vllm/issues/65952) `[Bug]: [ROCm] GLM-5.3 TP8 hangs with MTP and CPU KV offload` | bug,rocm | ? | - |
| - | [#65953](https://github.com/vllm-project/vllm/pull/65953) `[Feat][KV Offload] Add Hybrid KV Backend with bounded SSD streaming` | nvidia | main | - |
| - | [#65955](https://github.com/vllm-project/vllm/pull/65955) `[Quantization] Avoid importing humming when resolving quantization configs` | quant | main | - |
| - | [#65956](https://github.com/vllm-project/vllm/pull/65956) `[KV Offload][OBJ] Pass the accelerated option to the NIXL OBJ backend to enable S3 over RDMA` |  | main | - |
| - | [#65957](https://github.com/vllm-project/vllm/pull/65957) `[ROCm][CI] Cache only a ROCm stack the PR's CI pushed itself` | infra,perf,rocm | main | - |
| - | [#65958](https://github.com/vllm-project/vllm/pull/65958) `[Recipe] Kimi-K3.1-Pro: add MI325X (gfx942) single-node TP8 with DCP8` | infra,rocm | main | - |
| - | [#65959](https://github.com/vllm-project/vllm/issues/65959) `[RFC]: Switch Rust regex engine for response parsing` |  | ? | - |
| - | [#65961](https://github.com/vllm-project/vllm/pull/65961) `[Spec Decode][Watermarking] Allow watermarking with greedy drafts` |  | main | - |
| - | [#65962](https://github.com/vllm-project/vllm/pull/65962) `[Docs] Clarify prefix-caching determinism expectations` |  | main | - |
| - | [#65963](https://github.com/vllm-project/vllm/pull/65963) `[ROCm][RDNA4] Snap the gfx1201 TRITON_ATTN decode split-K threshold to a capture size` | rocm | main | - |
| - | [#65964](https://github.com/vllm-project/vllm/pull/65964) `[Bugfix][Frontend] Accept typed tool choice and tool models in ChatCompletionRequest` | bug | main | - |
| - | [#65965](https://github.com/vllm-project/vllm/pull/65965) `[Bugfix] Fix KV scale names on stacked models and the `--mm-encoder-only` shared root check` | bug,quant | main | - |
| - | [#65966](https://github.com/vllm-project/vllm/issues/65966) `[doc] out-of-tree quantization example imports FusedMoE, which the fused_moe package no longer exports` | perf,quant | ? | - |
| - | [#65967](https://github.com/vllm-project/vllm/issues/65967) `[RFC]: Compute-free prefix KV lookup-and-pin for router-driven peer KV reuse` | infra | ? | - |
| - | [#65969](https://github.com/vllm-project/vllm/issues/65969) `[RFC][HiSparse] Selective shared KV offloading for DeepSeek V4.1` |  | ? | - |
| - | [#65970](https://github.com/vllm-project/vllm/pull/65970) `[WIP][HiSparse] Selective KV offload for DeepSeek V4.1` | perf | main | - |
| - | [#65972](https://github.com/vllm-project/vllm/pull/65972) `[Perf][MoE] Route DP padding rows like real rows in monolithic MoE kernels` | nvidia,perf | main | - |
| - | [#65973](https://github.com/vllm-project/vllm/issues/65973) `[Performance]: Hybrid models with prefix caching prefill chunks above the default cudagraph capture ceiling ea` | perf | ? | - |
| - | [#65974](https://github.com/vllm-project/vllm/pull/65974) `[MoE][NVIDIA] Support SM107 in flashinfer_moe_ep_cutedsl for NVFP4 experts for FI 0.7.3` | nvidia,quant | main | - |
| - | [#65975](https://github.com/vllm-project/vllm/pull/65975) `[Perf][Quantization] Use fast SiLU intrinsics in Humming MoE activations` | perf,quant | main | - |
| - | [#65976](https://github.com/vllm-project/vllm/pull/65976) `[Frontend] Reject Anthropic max_tokens=0 prewarm with an actionable error` |  | main | - |
| - | [#65978](https://github.com/vllm-project/vllm/issues/65978) `[Feature]: Unify activation-scheme handling across linear oracles (generalize the activation override + add a ` | quant | ? | - |
| - | [#65979](https://github.com/vllm-project/vllm/pull/65979) `[CI] Enroll Language Models (Extended Generation) in automatic sharding; spawn in test_gemma's dummy-loader te` | infra | main | - |
| - | [#65980](https://github.com/vllm-project/vllm/pull/65980) `[Bugfix][Quantization] Select batch-invariant MXFP8/MXFP4 linear kernels under VLLM_BATCH_INVARIANT` | bug,infra,perf,quant | main | - |
| - | [#65981](https://github.com/vllm-project/vllm/pull/65981) `[RFC][Prototype] Snapshot post-processed model weights to skip checkpoint loading on restart` |  | main | - |
| - | [#65982](https://github.com/vllm-project/vllm/pull/65982) `[Bugfix][Attention] Use 4 warps when the 16-row prefill tile still misses shared memory` | bug | main | - |
| - | [#65983](https://github.com/vllm-project/vllm/pull/65983) `[Bugfix][Model] Build the tied embedding on the last PP rank for ERNIE 4.5 MoE and Falcon-H1` | bug,infra | main | - |
| - | [#65984](https://github.com/vllm-project/vllm/pull/65984) `[Bugfix][Spec Decode] Fix standalone draft models with pipeline parallelism in Model Runner V2` | bug,infra | main | - |
| - | [#65985](https://github.com/vllm-project/vllm/pull/65985) `[ROCm][Muse Spark] DSpark draft layers as one persistent FlyDSL launch (--monokernel)` | infra,rocm | main | - |
| - | [#65987](https://github.com/vllm-project/vllm/pull/65987) `[Bugfix] Make fused MoE expert weights contiguous before GPU copy in Llama-4` | bug,perf | main | - |
| - | [#65990](https://github.com/vllm-project/vllm/pull/65990) `[Doc] Add a new-model checklist to the parser agent guide` |  | main | - |
| - | [#65991](https://github.com/vllm-project/vllm/pull/65991) `[Spec Decode] Add option to disable extract_hidden_states decode drafts` |  | main | - |
| - | [#65992](https://github.com/vllm-project/vllm/pull/65992) `[ROCm][DSv4.1][Perf] Run the fused mHC seams as AITER's single-launch HIP Mega-MHC` | perf,rocm | main | - |
| - | [#65993](https://github.com/vllm-project/vllm/pull/65993) `[Rust Frontend] Multimodal and LoRA in the engine-free renderer` |  | main | - |
| - | [#65994](https://github.com/vllm-project/vllm/pull/65994) `[Rust Frontend][gRPC] Add the Render service with RenderChat` |  | main | - |
| - | [#65995](https://github.com/vllm-project/vllm/pull/65995) `[Bugfix][ROCm] Support AITER's preload() in FlyDSL INT4 QuickReduce init` | bug,quant,rocm | main | - |
| - | [#65996](https://github.com/vllm-project/vllm/pull/65996) `[Bugfix][MRV2] Build multimodal prefix-LM attention ranges on every PP stage` | bug,infra | main | - |
| - | [#65997](https://github.com/vllm-project/vllm/pull/65997) `[Bugfix][Mamba] Support speculative decoding in Mamba-1 layers` | bug | main | - |
| - | [#65998](https://github.com/vllm-project/vllm/pull/65998) `[ROCm] Pass the (B, next_n) context lengths to AITER paged MQA logits` | rocm | main | - |
| - | [#65999](https://github.com/vllm-project/vllm/pull/65999) `[Bugfix][Model] Pass Solar skip connection states to the next pipeline stage` | bug | main | - |
| - | [#66000](https://github.com/vllm-project/vllm/pull/66000) `[Bugfix][Step5][Spec Decode] Skip VllmConfig re-validation for the MTP draft config` | bug | main | - |
| - | [#66001](https://github.com/vllm-project/vllm/pull/66001) `[ROCm][Perf][MoE] Run the router GEMM before the shared-expert fork` | perf,rocm | main | - |
| - | [#66002](https://github.com/vllm-project/vllm/pull/66002) `[RL][Model Loader] Direct reload: models opt in; refuse known-silent paths` | perf,risk | main | - |
| - | [#66003](https://github.com/vllm-project/vllm/pull/66003) `[ROCm][Perf] AITER FA: build the extend metadata without a host sync` | infra,perf,rocm | main | - |
| - | [#66004](https://github.com/vllm-project/vllm/pull/66004) `[Bugfix][Frontend] Muse reasoning parser: deliver the visible text when a reply ends behind a stray recipient ` | bug,risk | main | - |
| - | [#66007](https://github.com/vllm-project/vllm/pull/66007) `[Bugfix][Model] Fix GraniteMoeHybrid loading and running only its own layers under pipeline parallelism` | bug | main | - |
| - | [#66008](https://github.com/vllm-project/vllm/pull/66008) `[Bugfix][MoRIIO] Let decode renew READ block leases on prefill` | bug,rocm | main | - |
| - | [#66009](https://github.com/vllm-project/vllm/issues/66009) `[Bug]: NixlConnector consumer reads remote KV after the producer lease expired and the blocks were recycled (s` | bug,risk | ? | - |
| - | [#66010](https://github.com/vllm-project/vllm/pull/66010) `[Sleep Mode] Level 2 discards only parameters` | bug | main | - |
| - | [#66011](https://github.com/vllm-project/vllm/pull/66011) `[Bugfix][NIXL] Decline remote prefill reads after the producer's KV lease expired` | bug | main | - |
| - | [#66013](https://github.com/vllm-project/vllm/pull/66013) `[Bugfix][EPLB] Fix startup hangs with a pipeline stage that has no MoE layers` | bug,infra | main | - |
| - | [#66015](https://github.com/vllm-project/vllm/pull/66015) `[Bugfix][MoE] Stop DeepGEMM's MLOPart helper once MegaMoE caches its SM map` | bug | main | - |
| - | [#66018](https://github.com/vllm-project/vllm/pull/66018) `[Attention][MiniMax-M3] Add FlashInfer MSA backend for SM90 and SM120/SM121` | nvidia | main | - |
| - | [#66020](https://github.com/vllm-project/vllm/pull/66020) `[Bugfix] Added CUDA graph capturing enabled flag management in MRV2` | bug,nvidia | main | - |
| - | [#66021](https://github.com/vllm-project/vllm/pull/66021) `[Perf][RL] Validate sparse weight patches in one pass` | perf | main | - |
| - | [#66023](https://github.com/vllm-project/vllm/issues/66023) `[Feature]: Tighter integration with Compressed-Tensors by consolidating and converting targets to vLLM` | quant | ? | - |
| - | [#66024](https://github.com/vllm-project/vllm/issues/66024) `[CI Failure]: Entrypoints Integration - test_derender_parity.py::test_inline_derender_parity[n2]` | infra | ? | - |
| - | [#66025](https://github.com/vllm-project/vllm/pull/66025) `[Bugfix][DSv4.1] Run decoder replay on a PP stage that starts at the cut` | bug | main | - |
| - | [#66026](https://github.com/vllm-project/vllm/pull/66026) `[Bugfix][Spec Decode] Don't specialize MRV2 _gather_draft_sampled_kernel on num_logits` | bug | main | - |
| - | [#66027](https://github.com/vllm-project/vllm/pull/66027) `[Attention][DCP] Sparse MLA DCP optimizations: packed top-k merge, direct A2A, DCP ShardQ (Kimi K3.1 split 5/5` | infra,nvidia,perf,rocm | main | - |
| - | [#66028](https://github.com/vllm-project/vllm/pull/66028) `[Rust Frontend] Kimi K3.1 chat renderer (Kimi K3.1 split 2/5)` |  | main | - |
| - | [#66030](https://github.com/vllm-project/vllm/pull/66030) `[Model] Kimi K3.1: model files and NVIDIA specialized decode (Kimi K3.1 split 1/5)` | infra,nvidia,perf | main | - |
| - | [#66031](https://github.com/vllm-project/vllm/pull/66031) `[ROCm] Add AITER CK DASH attention for Unlimited-OCR-2` | infra,rocm | main | - |
| - | [#66032](https://github.com/vllm-project/vllm/pull/66032) `[ROCm][CI] Run `/ci rocm cache` on the ci pipeline instead of AMD CI` | infra,perf,rocm | main | - |
| - | [#66034](https://github.com/vllm-project/vllm/pull/66034) `[XPU][CI]Migrate Distributed Torchrun + Shutdown to intel_gpu_k8s` | infra,nvidia | main | - |
| - | [#66035](https://github.com/vllm-project/vllm/pull/66035) `[HiSparse] Flush hot-buffer stats on the metrics logging timescale` |  | main | - |
| - | [#66036](https://github.com/vllm-project/vllm/pull/66036) `[ROCm][DSv4/4.1] Enable Tensor scale FP8 KV Cache for Sparse MLA` | perf,quant,rocm | main | - |
| - | [#66037](https://github.com/vllm-project/vllm/pull/66037) `[Core][Kimi K3.1] KV cache and attention changes to serve Kimi K3.1 at TP8 (Kimi K3.1 split 3/5)` | bug,nvidia,perf | main | - |
| - | [#66038](https://github.com/vllm-project/vllm/pull/66038) `[Perf][DSv4.1] Reuse the gathered compressed KV across consumers in FlashMLA prefill` | nvidia,perf | main | - |
| - | [#66040](https://github.com/vllm-project/vllm/pull/66040) `[Kernel] Deferred RecoverSSM verify kernels for FP32-state KDA layers` | perf | main | - |
| - | [#66041](https://github.com/vllm-project/vllm/pull/66041) `[Perf][DSA] Keep ShardQ projections sequence-sharded under SP` | perf | main | - |
| - | [#66043](https://github.com/vllm-project/vllm/pull/66043) `[Bugfix][Worker] Apply the startup plan on every rank or on none` | bug | main | - |
| - | [#66045](https://github.com/vllm-project/vllm/pull/66045) `[Bugfix][Model Loader] Stop the EP weight filter from skipping a draft model's experts` | bug,infra | main | - |
| - | [#66047](https://github.com/vllm-project/vllm/pull/66047) `[ROCm][Perf][DSv4.1] Shard the sparse-indexer decode rows across TP` | perf,rocm | main | - |
| - | [#66048](https://github.com/vllm-project/vllm/pull/66048) `Fix/spec decode insert resampled race` | bug,risk | main | - |
| - | [#66049](https://github.com/vllm-project/vllm/pull/66049) `[Bugfix][Core] Reject negative block counts in the free-block pool APIs` | bug,perf | main | - |
| - | [#66050](https://github.com/vllm-project/vllm/pull/66050) `[Model] Enable audio-conditioned hidden-state extraction for Ming ASR` | infra | main | - |
| - | [#66051](https://github.com/vllm-project/vllm/pull/66051) `[ROCm][Muse Spark] DSpark Markov sampling with one launch a round (--monokernel)` | infra,rocm | main | - |
| - | [#66052](https://github.com/vllm-project/vllm/pull/66052) `[Bugfix][DSA] Stage ShardQ indexer indices in fresh host memory each step` | bug | main | - |
| - | [#66053](https://github.com/vllm-project/vllm/pull/66053) `[Rust Frontend] Add the Poolside tool parser` |  | main | - |
| - | [#66054](https://github.com/vllm-project/vllm/pull/66054) `[Perf][MiniMax-M3] Shard large batches by token and fuse the MoE finalize into the reduce-scatter` | infra,perf | main | - |
| - | [#66055](https://github.com/vllm-project/vllm/issues/66055) `[Bug]: thinking_token_budget turns off reasoning when an earlier message mentions <think>` |  | ? | - |
| - | [#66056](https://github.com/vllm-project/vllm/pull/66056) `[Bugfix][Reasoning] Don't count a start marker quoted in an earlier message against thinking_token_budget` | bug | main | - |
| - | [#66057](https://github.com/vllm-project/vllm/pull/66057) `[Bugfix][Gemma4] Honor videos_kwargs.max_soft_tokens for video frames` | bug | main | - |
| - | [#66059](https://github.com/vllm-project/vllm/pull/66059) `[Fast start] Support D2D scaling for multi-node serving` | infra | main | - |
| - | [#66060](https://github.com/vllm-project/vllm/pull/66060) `[RL][Model Loader] Load plan: per-family plan == load_weights tests` |  | main | - |
| - | [#66061](https://github.com/vllm-project/vllm/pull/66061) `[Feature][Model] Add NCP-OLMo support for pure HF checkpoints` | infra | main | - |
| - | [#66063](https://github.com/vllm-project/vllm/pull/66063) `[Bugfix][Spec Decode] Fix draft models using the target's pipeline stage under PP` | bug,infra | main | - |
| - | [#66065](https://github.com/vllm-project/vllm/pull/66065) `[Model] Support CrisperWhisper 2.0` |  | main | - |
| - | [#66066](https://github.com/vllm-project/vllm/pull/66066) `[XPU] Allow StatelessGroupCoordinator and elastic EPLB on XPU/xccl` | infra,nvidia | main | - |
| - | [#66067](https://github.com/vllm-project/vllm/pull/66067) `[Refactor][Multimodal] Share encoder CUDA graph code via mixins` | nvidia | main | - |
| - | [#66068](https://github.com/vllm-project/vllm/pull/66068) `[ROCm][Quantization] Add tuned W8A8 block-FP8 Triton GEMM configs for MI355X` | perf,quant,rocm | main | - |
| - | [#66069](https://github.com/vllm-project/vllm/pull/66069) `[Spec Decode][Model Loader] LiLiCorr: load draft updates split across load_weights calls` |  | main | - |
| - | [#66070](https://github.com/vllm-project/vllm/issues/66070) `[Bug]: Qwen3.5 vision RoPE angle precision differs from HF (public 9B reproduction, mixed FP32 workaround resu` | bug,quant | ? | - |
| - | [#66071](https://github.com/vllm-project/vllm/pull/66071) ` [Model][DSv4.1] Token-shard sparse-MLA prefill under TP (ShardQ)` | infra | main | - |
| - | [#66072](https://github.com/vllm-project/vllm/pull/66072) `docs: fix broken FusedMoE imports in quantization guide` | bug,perf,quant | main | - |
| - | [#66073](https://github.com/vllm-project/vllm/pull/66073) `[Multimodal] Add keyframe-aware sampling to PyNvVideoCodec backend` |  | main | - |
| - | [#66074](https://github.com/vllm-project/vllm/issues/66074) `[Bug]: MXFP4 linear layers on Hopper (default Humming kernel) silently round or zero weights whose E8M0 scale ` | nvidia,perf,quant,risk | ? | - |
| - | [#66075](https://github.com/vllm-project/vllm/pull/66075) `[Test][Core] Regression tests for EAGLE prefix caching with multiple attention groups and mixed block sizes` | bug,perf | main | - |
| - | [#66076](https://github.com/vllm-project/vllm/pull/66076) `[Kernel] Add GC-MoE backend with fused shared experts for DeepSeek-V4.1` | perf | main | - |
| - | [#66077](https://github.com/vllm-project/vllm/pull/66077) `[Quantization][Kernel] Unify MXFP6 linear activation scheme gate and propagate per-layer target overrides` | perf,quant | main | - |
| - | [#66078](https://github.com/vllm-project/vllm/pull/66078) `[Feature][Rust Frontend] Support parallel sampling in gRPC GenerateStream` |  | main | - |
| - | [#66080](https://github.com/vllm-project/vllm/pull/66080) `[Bugfix][DeepGEMM] Match relax warmup M values to the vendored SM100 heuristic` | bug,nvidia | main | - |
| - | [#66081](https://github.com/vllm-project/vllm/pull/66081) `[Bugfix][Spec Decode] Fix non-deferred structured-output draft retrieval` | bug | main | - |
| - | [#66082](https://github.com/vllm-project/vllm/pull/66082) `[Perf][ROCm][ROCM_ATTN] Run large fp8 decode batches on the AITER asm paged attention` | perf,quant,rocm | main | - |
| - | [#66083](https://github.com/vllm-project/vllm/pull/66083) `[Bugfix] Handle OOV multimodal prompt logprobs` | bug | main | - |
| - | [#66084](https://github.com/vllm-project/vllm/pull/66084) `[ROCm][Spec Decode] Support draft_lm_head_quantization on RDNA (int4 drafter head, 18% faster MTP decode)` | perf,quant,rocm | main | - |
| - | [#66085](https://github.com/vllm-project/vllm/issues/66085) `[Performance]: Avoid extra logits passes for temperature-only sampling` | perf | ? | - |
| - | [#66086](https://github.com/vllm-project/vllm/pull/66086) `[Perf][MRV2] Avoid extra passes for temperature-only sampling` | infra,perf | main | - |
| - | [#66087](https://github.com/vllm-project/vllm/pull/66087) `[Bugfix][EPLB] Fix startup failure with MoE layers on multiple pipeline stages` | bug,infra | main | - |
| - | [#66088](https://github.com/vllm-project/vllm/pull/66088) `[Bugfix] Make GLM-5.3 sparse MLA batch invariant under VLLM_BATCH_INVARIANT` | bug | main | - |
| - | [#66089](https://github.com/vllm-project/vllm/pull/66089) `[ROCm][CI] Bound DeepSeek V4 MoE output by per-token error` | infra,quant,rocm | main | - |
| - | [#66090](https://github.com/vllm-project/vllm/pull/66090) `[Bugfix] Stop advertising fp8_e5m2 where the KV writer stores e4m3` | bug,quant,rocm | main | - |
| - | [#66091](https://github.com/vllm-project/vllm/pull/66091) `[Bugfix] Partition HF3FS external cache keys by multimodal and LoRA identity` | bug,perf | main | - |
| - | [#66092](https://github.com/vllm-project/vllm/pull/66092) `[Doc] Raise the bar for in-tree kernel translation units` | perf | main | - |
| - | [#66093](https://github.com/vllm-project/vllm/issues/66093) `[Feature]: Carry the HTTP EPD multimodal handoff on the Rust gRPC frontend` |  | ? | - |
| - | [#66094](https://github.com/vllm-project/vllm/pull/66094) `[Frontend][gRPC] Carry the HTTP EPD handoff on the Rust frontend` |  | main | - |
| - | [#66095](https://github.com/vllm-project/vllm/pull/66095) `[Build] Rewrite CUDA arch selection per target and preserve plain arch coverage` | infra,nvidia | main | - |
| - | [#66096](https://github.com/vllm-project/vllm/pull/66096) `[Doc] Correct docstrings that promise a return value` |  | main | - |
| - | [#66098](https://github.com/vllm-project/vllm/pull/66098) `[Bugfix][Frontend] Reject legacy functions/function_call in Chat Completions` | bug | main | - |
| - | [#66099](https://github.com/vllm-project/vllm/pull/66099) `[Kernel][MiniMax-M3] Drop tl.make_block_ptr from the Hopper sparse prefill` | nvidia,perf | main | - |
| - | [#66100](https://github.com/vllm-project/vllm/pull/66100) `[CPU][Refactor] Move CPU ops wrappers to vllm/_cpu_ops.py` | infra,perf | main | - |
| - | [#66101](https://github.com/vllm-project/vllm/issues/66101) `[Spec Decode] Broaden NVFP4 draft LM-head validation beyond GB10: Memra results and Blackwell/model matrix` | nvidia,quant | ? | - |
| - | [#66102](https://github.com/vllm-project/vllm/pull/66102) `feat: Add apply_router_weight_on_input support for CPU MoE expert classes` |  | main | - |
| - | [#66103](https://github.com/vllm-project/vllm/pull/66103) `[Rust Frontend] Join text parts in the renderer for DeepSeek V3.2 and /v1/responses` |  | main | - |
| - | [#66104](https://github.com/vllm-project/vllm/pull/66104) `[Rust Frontend] Export vllm:request_render_duration_seconds` |  | main | - |
| - | [#66105](https://github.com/vllm-project/vllm/pull/66105) `[Rust Frontend] Export SimpleCPUOffload KV connector metrics` |  | main | - |
| - | [#66106](https://github.com/vllm-project/vllm/pull/66106) `[Rust Frontend] Support tool_reference content parts` |  | main | - |
| - | [#66107](https://github.com/vllm-project/vllm/pull/66107) `[Rust Frontend] Accept `spaces_between_special_tokens` as a no-op` |  | main | - |
| - | [#66108](https://github.com/vllm-project/vllm/pull/66108) `[Core] Reject the guidance backend for unsupported tokenizers in EngineCore` |  | main | - |
| - | [#66109](https://github.com/vllm-project/vllm/issues/66109) `[Bug]: Marlin NVFP4 zeroes E4M3 subnormal block scales with float16 activations, although its float16 path dec` | quant | ? | - |
| - | [#66110](https://github.com/vllm-project/vllm/pull/66110) `[Bugfix] Keep small NVFP4 block scales in Marlin with float16 activations` | bug,quant | main | - |
| - | [#66112](https://github.com/vllm-project/vllm/pull/66112) `[Bugfix][Quantization] Avoid Humming's fused-E8M0 path for MXFP4 layers it would round` | bug,perf,quant | main | - |
| - | [#66113](https://github.com/vllm-project/vllm/issues/66113) `[Bug]: Ministral-3 / Devstral-Small-2 FP8 with `--config-format hf`: vision tower and projector are built as F` | quant | ? | - |
| - | [#66114](https://github.com/vllm-project/vllm/pull/66114) `[Bugfix] Keep modules listed in FP8 modules_to_not_convert unquantized` | bug,quant | main | - |
| - | [#66115](https://github.com/vllm-project/vllm/issues/66115) `[Bug]: LFM2, LFM2-MoE, Jamba, Zamba2, Step3, Bailing MoE and PLaMo3 build `Attention` without `quant_config`, ` | infra,perf,quant | ? | - |
| - | [#66116](https://github.com/vllm-project/vllm/pull/66116) `[Bugfix] Pass quant_config to Attention in hybrid and MoE models` | bug,quant | main | - |
| - | [#66117](https://github.com/vllm-project/vllm/pull/66117) `[Bugfix][Frontend] Reject translation on models that cannot translate` | bug | main | - |
| - | [#66118](https://github.com/vllm-project/vllm/pull/66118) `[RL][Model Loader] Load FP8 indexer wk and MLA projections independently, as FP8 or BF16, in any scale layout` | infra,quant | main | - |
| - | [#66119](https://github.com/vllm-project/vllm/pull/66119) `[Rust Frontend] Support --log-level and --logging-config` |  | main | - |
| - | [#66120](https://github.com/vllm-project/vllm/issues/66120) `[Bug]: MiniMax-M3 sparse attention layers drop checkpoint FP8 KV-cache scales and run with scale 1.0` | perf,quant | ? | - |
| - | [#66121](https://github.com/vllm-project/vllm/pull/66121) `feat: CPU WNA16 MoE INT8 weight-only support for mixed INT4/INT8 models (issue #65070)` | quant | main | - |
| - | [#66122](https://github.com/vllm-project/vllm/issues/66122) `[Feature]: Integrate FlashTopK fused indexer top-k for DSA prefill on Hopper (SM90)` | nvidia,perf | ? | - |
| - | [#66123](https://github.com/vllm-project/vllm/pull/66123) `[Bugfix] Preserve embedding size overrides` | bug | main | - |
| - | [#66124](https://github.com/vllm-project/vllm/issues/66124) `[Bug]: `enable_weights_track` refuses correct weight-only NVFP4 checkpoints (input scales that no export write` | perf,quant | ? | - |
| - | [#66125](https://github.com/vllm-project/vllm/pull/66125) `[XPU] skip test_online_hadamard_target_wraps_resolved_method UT` | nvidia | main | - |
| - | [#66126](https://github.com/vllm-project/vllm/pull/66126) `[Perf][Kernel] CUTLASS FP8 scaled_mm: smaller tiles for narrow-N decode GEMMs on SM90 and SM100` | nvidia,perf,quant | main | - |
| - | [#66128](https://github.com/vllm-project/vllm/pull/66128) `[ROCm][Perf][DSv4.1] Score adaptive-verification decode steps as varlen sequences in the MXFP4 indexer` | perf,quant,rocm | main | - |
| - | [#66129](https://github.com/vllm-project/vllm/issues/66129) `[Bug]: compressed-tensors loads checkpoint FP8 k/v scales into layers kept in BF16 by kv_cache_dtype_skip_laye` | bug,nvidia,quant | ? | - |
| - | [#66130](https://github.com/vllm-project/vllm/pull/66130) `[ROCm] Add a FlyDSL MXFP4 linear backend for RDNA4` | infra,quant,rocm | main | - |
| - | [#66131](https://github.com/vllm-project/vllm/issues/66131) `[Bug][KV Connector] Local hybrid hit can exceed draft-attention coverage` |  | ? | - |
| - | [#66132](https://github.com/vllm-project/vllm/pull/66132) `[Bugfix][KV Connector] Reconcile local hits when draft attention lags` | bug,infra,perf | main | - |
| - | [#66133](https://github.com/vllm-project/vllm/pull/66133) `[ROCm][Perf] W4A16: fix the gfx1151 bf16 tile cliff at decode-sized M (up to +44% decode throughput)` | bug,perf,quant,rocm | main | - |
| - | [#66134](https://github.com/vllm-project/vllm/issues/66134) `[RFC]: Text sessions on /v1/realtime with streaming-input prefill` |  | ? | - |
| - | [#66135](https://github.com/vllm-project/vllm/pull/66135) `[Bugfix][Parser] DeepSeek DSML: keep a closer inside a tool-argument value` | bug | main | - |

### sglang — Merged / closed (721 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#29738](https://github.com/sgl-project/sglang/issues/29738) `[Bug] NameError: name 'deep_gemm' is not defined in tf32_hc_prenorm_gemm when SGLANG_ENABLE_JIT_DEEPGEMM=0` |  | ? | - |
| - | [#29857](https://github.com/sgl-project/sglang/issues/29857) `[Bug] v0.5.14: With EAGLE/MTP on, KV pool profiler leaves ~50 GB VRAM idle on hybrid GDN model (Qwen3.6-27B NV` | quant | ? | - |
| - | [#30314](https://github.com/sgl-project/sglang/issues/30314) `[Bug] Scheduler event loop blocks on Mamba eviction under large-context requests, causing server hang and proc` | bug | ? | - |
| - | [#30550](https://github.com/sgl-project/sglang/issues/30550) `[Bug] [MLX] SchedulerProfilerManager._start_profile returns success=False under mocked Metal capture` |  | ? | - |
| - | [#30719](https://github.com/sgl-project/sglang/pull/30719) `[Perf] [Intel] diffusion: Adding AMX optimizations on CPU platform` | infra,perf | main | - |
| - | [#30760](https://github.com/sgl-project/sglang/issues/30760) `[Bug] HiCache prefetch all_reduce deadlock with TP=4, no PP — mismatched call count in check_prefetch_progress` | risk | ? | - |
| - | [#30980](https://github.com/sgl-project/sglang/pull/30980) `[Feat] [XPU] graph: Add full prefill graph` | infra,nvidia | main | - |
| - | [#31206](https://github.com/sgl-project/sglang/issues/31206) `[Bug] sgl-router (PD): open circuit breaker still dispatches to decode, producing a permanent fake-dead prefil` |  | ? | - |
| - | [#31261](https://github.com/sgl-project/sglang/issues/31261) `[Feature] Support Deterministic Inference for Qwen3_5ForConditionalGeneration` |  | ? | - |
| - | [#31763](https://github.com/sgl-project/sglang/issues/31763) `How should I configure the service to make the model return tool calls that comply with the OpenAI standard in` |  | ? | - |
| - | [#32124](https://github.com/sgl-project/sglang/issues/32124) `[Feature] Skip redundant DeepGEMM all-M warmup when a compatible JIT cache is restored` | perf | ? | - |
| - | [#32286](https://github.com/sgl-project/sglang/issues/32286) `[Bug] MiniMax-M3 tool-call parser: top-level `oneOf` parameters schema not resolved (numbers become strings, a` |  | ? | - |
| - | [#32441](https://github.com/sgl-project/sglang/issues/32441) `[Bug] [MLX] test_batched_decode_matches_solo asserts bitwise solo/batched token equality, which no batch-shape` |  | ? | - |
| - | [#33185](https://github.com/sgl-project/sglang/issues/33185) `[Bug] DeepSeek-V4-Flash-0731: reasoning_effort mapped one level off — `high` is a no-op and vendor `max` is un` |  | ? | - |
| - | [#33226](https://github.com/sgl-project/sglang/pull/33226) `[Feat] cp: Support FlashInfer prefill context parallelism` | nvidia | main | - |
| - | [#34212](https://github.com/sgl-project/sglang/pull/34212) `[Fix] [AMD] DSP: skip unused QuickAllReduce allocation for DCP groups` | bug,infra,rocm | main | - |
| - | [#34259](https://github.com/sgl-project/sglang/issues/34259) `[Bug] Kimi-K3 - cross prompt reasoning leakage` |  | ? | - |
| - | [#34513](https://github.com/sgl-project/sglang/issues/34513) `[RFC] Agent-aware session affinity without routing keys: a router policy` |  | ? | - |
| - | [#34740](https://github.com/sgl-project/sglang/issues/34740) `[Bug] SGLANG_SIMULATE_ACC_LEN silently degrades detokenization to O(n²) — `predict.fill_(100)` emits a byte-fa` | risk | ? | - |
| - | [#35270](https://github.com/sgl-project/sglang/issues/35270) `[Bug] Radix cache `evictable_size()` double-counts shared pages, killing the scheduler at idle` | perf | ? | - |
| - | [#35433](https://github.com/sgl-project/sglang/issues/35433) `[Bug] DeepSeek-V4 returns an empty response when the final message has role=system` |  | ? | - |
| - | [#35772](https://github.com/sgl-project/sglang/issues/35772) `[Bug] Qwen3-VL vision features diverge from Transformers/vLLM in v0.5.17 on fine-grained grounding` |  | ? | - |
| - | [#35785](https://github.com/sgl-project/sglang/issues/35785) `Triton version mismatch` | rocm | ? | - |
| - | [#35792](https://github.com/sgl-project/sglang/pull/35792) `[Fix] compressed-tensors: Honor .linear-wrapped ignore entries on fused shards` | bug,infra,perf,quant | main | - |
| - | [#36059](https://github.com/sgl-project/sglang/pull/36059) `[Perf] dsv4: Add native H16 CuTe sparse prefill backend` | infra,perf | main | - |
| - | [#36081](https://github.com/sgl-project/sglang/issues/36081) `[Bug] DSV4F0731+DSPARK ERROR IN SGLANG 0.5.18` |  | ? | - |
| - | [#36140](https://github.com/sgl-project/sglang/issues/36140) `[Bug] DFLASH speculative decoding is not supported under PD disaggregation: spec_info None crash, then watchdo` | bug | ? | - |
| - | [#36179](https://github.com/sgl-project/sglang/issues/36179) `[Bug] When using hicache to enable L2/L3 storage in DeepSeek V4, token loop repetition occurs very frequently` |  | ? | - |
| - | [#36226](https://github.com/sgl-project/sglang/issues/36226) `[Performance] Multiple potential avoidable scheduler, sampling, and streaming overheads identified` | perf | ? | - |
| - | [#36545](https://github.com/sgl-project/sglang/issues/36545) `Qwen3.8-Flash-Next QSA crashes with FP8 KV cache (BF16 q vs FP8 k dtype assertion)` | bug,perf,quant | ? | - |
| - | [#36633](https://github.com/sgl-project/sglang/issues/36633) `[CPU] FP8 KV store: keep fused decode path, stop using Python index_put` | perf,quant | ? | - |
| - | [#36807](https://github.com/sgl-project/sglang/issues/36807) `[Bug] fast_topk_v2 can silently return wrong top-k sets when a radix threshold bucket exceeds its 4096-entry c` | risk | ? | - |
| - | [#36829](https://github.com/sgl-project/sglang/issues/36829) `GLM-5.3-Flash (glm5_next, mHC) EAGLE3/MTP: fused_eh_norm width mismatch with mHC-flattened aux hidden; accepta` | perf | ? | - |
| - | [#36894](https://github.com/sgl-project/sglang/issues/36894) `[Bug] /unload_lora_adapter permanently deadlocks the scheduler after parallel-sampling traffic (n > 1)` | risk | ? | - |
| - | [#36906](https://github.com/sgl-project/sglang/issues/36906) `[Bug] GLM-5.3-Flash crashes at startup under pipeline parallelism — KeyError: 'residual'` | bug | ? | - |
| - | [#36935](https://github.com/sgl-project/sglang/issues/36935) `[Prefix Cache / Hybrid] Branch reuse silently collapses under LRU pressure when (kv_pool_tokens / chunked_pref` | perf,risk | ? | - |
| - | [#37052](https://github.com/sgl-project/sglang/issues/37052) `[Bug] Qwen3.8-Flash-Next + NEXTN full decode graph: repeated dual-rank invalid-probability asserts on GB10` |  | ? | - |
| - | [#37089](https://github.com/sgl-project/sglang/issues/37089) `[Bug] Qwen3.8-Flash-Next W4A16 on A100 TP4: Marlin MoE invalid thread config; Triton MoE then hits QSA FA-CuTe` | quant,rocm | ? | - |
| - | [#37097](https://github.com/sgl-project/sglang/issues/37097) `[Bug] Pretokenized image requests can crash GLM MRoPE with a stale retokenized mask` | bug | ? | - |
| - | [#37150](https://github.com/sgl-project/sglang/issues/37150) `[Feature] Tuning / per-GPU config for DSv4 top-k v2 cluster launch plan (kClusterFloor / kNumPersistentCluster` | perf | ? | - |
| - | [#37183](https://github.com/sgl-project/sglang/issues/37183) `AMD MI308X SGLang GLM-5.3-Flash ValueError: The checkpoint you are trying to load has model type `glm5_next` b` | rocm | ? | - |
| - | [#37186](https://github.com/sgl-project/sglang/issues/37186) `[Bug] Qwen3.5 visual encoder weights dropped by PP layer-range filter in load_weights` |  | ? | - |
| - | [#37215](https://github.com/sgl-project/sglang/issues/37215) `[Bug] --dp 8 intermittently fails with TCPStore EADDRINUSE on single-node 8×H800` |  | ? | - |
| - | [#37216](https://github.com/sgl-project/sglang/issues/37216) `[Bug] remote_instance weight loading fails with --pp-size 2 — TransferEngine info keyed by tp_rank` |  | ? | - |
| - | [#37238](https://github.com/sgl-project/sglang/issues/37238) `Does SGLang have a demo for running the VBench dataset accuracy evaluation on Wan2.2?` | perf,risk | ? | - |
| - | [#37263](https://github.com/sgl-project/sglang/issues/37263) `[Bug] /v1/responses silently drops prompt_cache_key instead of applying it to radix-cache identity` | perf,risk | ? | - |
| - | [#37283](https://github.com/sgl-project/sglang/issues/37283) `[Bug] A non-object entry in a tool-call array discards the valid calls beside it` |  | ? | - |
| - | [#37326](https://github.com/sgl-project/sglang/issues/37326) `[Bug] NEXTN/MTP draft acceptance decays to ~0 over server uptime on qwen4_exp (Qwen3.8-Flash-Next), fully rest` |  | ? | - |
| - | [#37342](https://github.com/sgl-project/sglang/issues/37342) `[Bug] DeepSeek-V4-Flash-0731 fails to load on v0.5.17/v0.5.18: AssertionError: Hidden size mismatch in the mxf` | quant | ? | - |
| - | [#37349](https://github.com/sgl-project/sglang/issues/37349) `[Guide] Setup and Troubleshooting for SGLang on V100` |  | ? | - |
| - | [#37367](https://github.com/sgl-project/sglang/pull/37367) `[Perf] [AMD] moe: Resolve MoRI dispatch from the AITER activation contract` | infra,perf,rocm | main | - |
| - | [#37368](https://github.com/sgl-project/sglang/issues/37368) `[Bug] NVFP4 online MoE loading can use overwritten RunAI streamer tensors` | quant | ? | - |
| - | [#37369](https://github.com/sgl-project/sglang/issues/37369) `[Bug] GLM-5.3-Flash RunAI streaming can corrupt fused MLA weights` | perf,risk | ? | - |
| - | [#37389](https://github.com/sgl-project/sglang/issues/37389) `[RFC][Feature] Extract an In-Process Route Planner from experimental/sgl-router's PD Workflow` | infra | ? | - |
| - | [#37405](https://github.com/sgl-project/sglang/issues/37405) `[RFC] Incremental test cleanup, CI taxonomy, and shared diffusion dispatch` | infra,perf | ? | - |
| - | [#37419](https://github.com/sgl-project/sglang/issues/37419) `[Feature] Avoid raw media input prefixes in multimodal error logs` |  | ? | - |
| - | [#37421](https://github.com/sgl-project/sglang/issues/37421) `CI: tests flaking on ubuntu-latest` | infra | ? | - |
| - | [#37457](https://github.com/sgl-project/sglang/issues/37457) `[Bug] Startup logs and server_info expose API keys in resolved server arguments` |  | ? | - |
| - | [#37475](https://github.com/sgl-project/sglang/issues/37475) `[Bug] DFlash target_layer_ids fallback guesses wrong tap layers; count collision fails silently` | risk | ? | - |
| - | [#37478](https://github.com/sgl-project/sglang/issues/37478) `[ROCm] IndexerKPool calls aiter fp8_mqa_logits unbounded; >2 GiB logits abort every TP rank (#36960 does not c` | rocm | ? | - |
| - | [#37526](https://github.com/sgl-project/sglang/issues/37526) `[CI] Test Escape Report: /rerun-test did not enforce registered test __main__ validation` | infra,nvidia | ? | - |
| - | [#37548](https://github.com/sgl-project/sglang/issues/37548) `[GLM-5.3-Flash] NextN/MTP crashes on the first request: Glm5NextForConditionalGenerationNextN inherits DeepSee` | bug | ? | - |
| - | [#37553](https://github.com/sgl-project/sglang/issues/37553) `custom_mask grows unbounded via torch.cat in EAGLE/DFlash speculative decoding` |  | ? | - |
| - | [#37579](https://github.com/sgl-project/sglang/issues/37579) `[Bug] GLM-V (glm4v processor): stray multimodal placeholder strings in message text cause 500 "Mismatch: More ` |  | ? | - |
| - | [#37590](https://github.com/sgl-project/sglang/issues/37590) `[Bug] DP-attention scheduler crashes (NoneType len) when attn_tp_size>1 and attn_cp_size>1: request-broadcast ` | bug | ? | - |
| - | [#37597](https://github.com/sgl-project/sglang/pull/37597) `[Feat] [CPU] glm_ocr: Add model support` | infra,perf | main | - |
| - | [#37608](https://github.com/sgl-project/sglang/issues/37608) `[Bug] --tool-call-parser auto selects glm45 instead of spark25 for Spark-X2.5` |  | ? | - |
| - | [#37639](https://github.com/sgl-project/sglang/issues/37639) `[Bug] Spark2.5 attention output gate hardcodes sigmoid, ignores config gate_attn_act_mode` |  | ? | - |
| - | [#37640](https://github.com/sgl-project/sglang/issues/37640) `[Bug] sgl_kernel ships infllm_ops as a cp310-tagged extension inside an abi3 wheel: unimportable on Python != ` |  | ? | - |
| - | [#37645](https://github.com/sgl-project/sglang/issues/37645) `[Bug] glm45 reasoning parser returns the whole answer as reasoning_content (content empty) when the model skip` |  | ? | - |
| - | [#37646](https://github.com/sgl-project/sglang/issues/37646) `[Bug] --enable-flashinfer-pure-allreduce is not available on 0.5.18` | nvidia | ? | - |
| - | [#37648](https://github.com/sgl-project/sglang/issues/37648) `[Bug][ROCm] GLM-5.3-MXFP4 TP8 + EAGLE GPU memory fault under high-concurrency long-context load` | quant,risk,rocm | ? | - |
| - | [#37650](https://github.com/sgl-project/sglang/issues/37650) `[Bug] `HarmonyParser` never flushes` |  | ? | - |
| - | [#37652](https://github.com/sgl-project/sglang/issues/37652) `[Bug] `force_nonempty_content`: the answer stays stranded in reasoning_content when there's a single trailing ` |  | ? | - |
| - | [#37707](https://github.com/sgl-project/sglang/issues/37707) `[Bug]  pattern + minLength: xgrammar silently drops the length bound` | risk | ? | - |
| - | [#37710](https://github.com/sgl-project/sglang/issues/37710) `[Feature] KVCache can support dtype:int` |  | ? | - |
| - | [#37711](https://github.com/sgl-project/sglang/issues/37711) `[Bug] Ollama endpoints: /api/chat 500s on every request; /api/generate 500s when the client sends no num_predi` |  | ? | - |
| - | [#37755](https://github.com/sgl-project/sglang/issues/37755) `[Bug] MiMo-V2.5-Pro-W8A8 load weight failed via modelslim` | quant | ? | - |
| - | [#37765](https://github.com/sgl-project/sglang/issues/37765) `[PD] Make request role and state-transfer shape explicit` |  | ? | - |
| - | [#37772](https://github.com/sgl-project/sglang/issues/37772) `[Feature] LoRA adapter support for Dspark speculative decoding draft models` |  | ? | - |
| - | [#37792](https://github.com/sgl-project/sglang/issues/37792) `[Feature] Serve Qwen3.8-Flash-Next (176B / 6B-active MoE) at 2.57 bpw on one 24 GB GPU with 32 GB host RAM` |  | ? | - |
| - | [#37838](https://github.com/sgl-project/sglang/issues/37838) `[Feature] DeepSeek-V4 trtllm attention backend: support PD disaggregation (uniform-FP8 KV layout in the PD han` | quant | ? | - |
| - | [#37845](https://github.com/sgl-project/sglang/issues/37845) `[Bug] Multi-part text content is rejected for system and assistant messages` |  | ? | - |
| - | [#37846](https://github.com/sgl-project/sglang/issues/37846) `[Bug]  Null optional config sections are treated as populated` |  | ? | - |
| - | [#37848](https://github.com/sgl-project/sglang/issues/37848) `[Bug] Missing layer prefixes bypass per-module quantization setting` | quant | ? | - |
| - | [#37852](https://github.com/sgl-project/sglang/issues/37852) `[Bug] sglang:kv_cache_memory_usage_gb reports 0 for DeepSeek-V4 pools` |  | ? | - |
| - | [#37892](https://github.com/sgl-project/sglang/issues/37892) `[Bug] DeepSeek-V4 long-context prefill: illegal memory access in the DSA indexer top-k kernel (`topk_v1.cuh:34` | bug,perf,risk | ? | - |
| - | [#37904](https://github.com/sgl-project/sglang/issues/37904) `[PDMux] scheduler event loop deadlocks in decode_stream.synchronize() when a mixed decode+split-prefill batch ` | risk | ? | - |
| - | [#37912](https://github.com/sgl-project/sglang/issues/37912) `[Bug] [Rust gateway] reasoning_effort: support full OpenAI 7-tier set (blocked on smg release)` | infra | ? | - |
| - | [#37931](https://github.com/sgl-project/sglang/issues/37931) `[Bug] DeepSeek-V4-Flash-Vision-Exp on 2x DGX Spark: scheduler OOM-killed during weight load (cookbook cell dgx` | quant | ? | - |
| - | [#37936](https://github.com/sgl-project/sglang/issues/37936) `Reproducible EAGLE `vectorized_gather_kernel` OOB with concurrent constrained tool request → NCCL abort / Xid ` | nvidia | ? | - |
| - | [#37976](https://github.com/sgl-project/sglang/pull/37976) `[Feat] trace: propagate per-request context to mooncake store RPC for end-to-end request tracing` | infra,perf | main | - |
| - | [#38013](https://github.com/sgl-project/sglang/issues/38013) `[Bug]` |  | ? | - |
| - | [#38022](https://github.com/sgl-project/sglang/issues/38022) `[Bug] A single malformed multimodal request takes down the whole engine, and client retries spread it node-by-` |  | ? | - |
| - | [#38029](https://github.com/sgl-project/sglang/issues/38029) `[Bug] EAGLE DSA draft backend misses KVIndexTranslator in FP8 MHA prefix reads` | quant | ? | - |
| - | [#38073](https://github.com/sgl-project/sglang/issues/38073) `[NVFP4 MoE Marlin fallback] w13/w2_blockscale_swizzled dead copies waste ~3.5 GiB per GPU (SM80–SM90x)` | nvidia,quant | ? | - |
| - | [#38074](https://github.com/sgl-project/sglang/issues/38074) `[NVFP4 MoE Marlin fallback] prepare_moe_nvfp4_layer_for_marlin leaks ~0.66 GiB/layer; old params retained by a` | quant | ? | - |
| - | [#38099](https://github.com/sgl-project/sglang/issues/38099) `[Bug] NIXL staging reuses the send buffer too early and repeats completed sends` |  | ? | - |
| - | [#38129](https://github.com/sgl-project/sglang/issues/38129) `[Bug] NGRAM cached requests miss newly inserted longer contexts` |  | ? | - |
| - | [#38143](https://github.com/sgl-project/sglang/issues/38143) `[Bug] MiniMax-M3 W4A16 (compressed-tensors) on 2x DGX Spark (sm_121, TP=2): serves but every token is id 0 — a` | quant,rocm | ? | - |
| - | [#38167](https://github.com/sgl-project/sglang/issues/38167) `[Bug][Diffusion] MiniMax-H3: 1344x768 fails deterministically with "CUDA driver error: device not ready" on 12` | nvidia,perf | ? | - |
| - | [#38196](https://github.com/sgl-project/sglang/issues/38196) `[Bug] [NPU] ascend attention backend silently corrupts output with page_size 16 (128 OK, 1 rejected per #25169` | risk | ? | - |
| - | [#38207](https://github.com/sgl-project/sglang/issues/38207) `[Bug] GLM-5.3 DPC crashes` | bug | ? | - |
| - | [#38236](https://github.com/sgl-project/sglang/issues/38236) `[Bug] DeepseekV4ForCausalLM hook rejects `--speculative-algorithm NEXTN` because the NEXTN->EAGLE alias is res` |  | ? | - |
| - | [#38440](https://github.com/sgl-project/sglang/pull/38440) `[Feat] [NPU] DSpark: DeepSeek-V4 support DSpark compact mode` | infra,perf,quant | main | - |
| - | [#38565](https://github.com/sgl-project/sglang/pull/38565) `[Fix] sampling: deterministic top-p / top-k renorm when tp_size > 1 (TP rank divergence in DFlash/DSpark)` | bug,infra,perf | main | - |
| - | [#38719](https://github.com/sgl-project/sglang/pull/38719) `[Fix] moe: Preserve FP32 router precision across model gates` | bug,infra | main | - |
| - | [#38900](https://github.com/sgl-project/sglang/pull/38900) `[Fix] qwen4: Release loader parameter snapshot before quantization post-processing` | bug,infra,quant | main | - |
| - | [#38943](https://github.com/sgl-project/sglang/pull/38943) `[Feat] dcp: Support breakable prefill CUDA graphs under decode context parallelism` | infra,nvidia | main | - |
| - | [#39173](https://github.com/sgl-project/sglang/issues/39173) `[Bug] DeepSeek-V4.1-Flash + Engram: profiled SPS table (compact ragged verify) dies in CUDA-graph capture with` | nvidia | ? | - |
| - | [#39682](https://github.com/sgl-project/sglang/pull/39682) `[Feat] diffusion/model: support HiDream-O1-Image` | infra,perf | main | - |
| - | [#39793](https://github.com/sgl-project/sglang/pull/39793) `[Feat] xing4_0: Add model support` | infra,perf | main | - |
| - | [#39799](https://github.com/sgl-project/sglang/pull/39799) `[Fix] mem-cache: Budget the non-DSA EAGLE draft KV pool at its DCP-widened size` | bug,infra,perf | main | - |
| - | [#39880](https://github.com/sgl-project/sglang/pull/39880) `[Feat] hicache: Add the fast_file local storage backend` | infra | main | - |
| - | [#39947](https://github.com/sgl-project/sglang/pull/39947) `[Feat] [NPU] DSpark: Support dsv4 dspark on ascend 950` | infra,perf | main | - |
| - | [#40107](https://github.com/sgl-project/sglang/pull/40107) `[Fix] disaggregation: Preserve sampler customized_info across PD` | bug,infra | main | - |
| - | [#40139](https://github.com/sgl-project/sglang/pull/40139) `[Fix] [Intel] cpu-kernel: Fix rope for VLA model` | bug,infra,perf | main | - |
| - | [#40421](https://github.com/sgl-project/sglang/pull/40421) `[Perf] [NVIDIA] deepseek-v4.1: Reuse dequantized compressed KV in PD CP prefill (7/N)` | infra,nvidia,perf,quant | main | - |
| - | [#40708](https://github.com/sgl-project/sglang/pull/40708) `[Perf] [AMD] qwen3.5: Route 512-expert softmax MoE routing through aiter topk_gating` | infra,perf,rocm | main | - |
| - | [#40746](https://github.com/sgl-project/sglang/pull/40746) `[Fix] [NPU] mtp: fix darft fias-v2 branch when fias v2 on` | bug,infra | main | - |
| - | [#40825](https://github.com/sgl-project/sglang/pull/40825) `[Feat] [NPU] kimi-k3: Support DCP with shared compact communication` | infra,nvidia,perf | main | - |
| - | [#40832](https://github.com/sgl-project/sglang/pull/40832) `[Test] [CPU] UT: Fix the mapping between the TP and the given NUMA nodes.` | bug,infra | main | - |
| - | [#40890](https://github.com/sgl-project/sglang/pull/40890) `[Perf] [NPU] mimo: fold attention_value_scale into o_proj weights` | infra,perf | main | - |
| - | [#40914](https://github.com/sgl-project/sglang/pull/40914) `[Refactor] memory-pool: Build draft sidecar host pools from buffer info` | infra,perf,rocm | main | - |
| - | [#40916](https://github.com/sgl-project/sglang/pull/40916) `[Refactor] memory-pool: Build QSA indexer host pools from buffer info` | infra,rocm | main | - |
| - | [#41108](https://github.com/sgl-project/sglang/pull/41108) `[Perf] mimo-v2: Optimize router GEMM with the HPC-Ops bf16xfp32 kernel` | infra,perf | main | - |
| - | [#41204](https://github.com/sgl-project/sglang/pull/41204) `[Fix] processor: Restore BOS/EOS flags for processor-owned tokenizers` | bug,infra | main | - |
| - | [#41294](https://github.com/sgl-project/sglang/pull/41294) `[Perf] [NVIDIA] dsv41: Use the fused low-ratio compressor on Hopper` | infra,nvidia,perf | main | - |
| - | [#41301](https://github.com/sgl-project/sglang/pull/41301) `[Perf] [NVIDIA] quantization: Add tuned W8A8 block-FP8 GEMM configs for H20` | infra,nvidia,perf,quant | main | - |
| - | [#41504](https://github.com/sgl-project/sglang/pull/41504) `[Chore] [NPU] common: Update references from A5 to arch35 or Ascend 950 across multiple modules` | infra,perf | main | - |
| - | [#41532](https://github.com/sgl-project/sglang/pull/41532) `[Feat] [XPU] quant: Add MXFP8 W8A8 compressed-tensors` | infra,nvidia,quant | main | - |
| - | [#41639](https://github.com/sgl-project/sglang/pull/41639) `[Feat] [AMD] moe: Add native GLM MXFP4 Triton Gluon backend` | infra,perf,quant,rocm | main | - |
| - | [#41768](https://github.com/sgl-project/sglang/pull/41768) `[Fix] multimodal: Keep every image, video and audio of a request when n > 1` | bug,infra | main | - |
| - | [#41771](https://github.com/sgl-project/sglang/pull/41771) `[Fix] dp-controller: Keep one input_embeds request from killing a DP server under total_tokens` | bug,infra | main | - |
| - | [#41880](https://github.com/sgl-project/sglang/pull/41880) `[Perf] [AMD] Qwen3.8: AITER FlyDSL hc_mix for Qwen3.8 hyper-connections on gfx950` | infra,perf,rocm | main | - |
| - | [#41916](https://github.com/sgl-project/sglang/pull/41916) `[Fix] sampling: Make top-k/top-p filtering consistent across sampling paths` | bug,quant | main | - |
| - | [#42198](https://github.com/sgl-project/sglang/pull/42198) `[Perf] [AMD] custom-all-reduce: Select the fused AR+RMSNorm 1-stage kernel by token count and read volume` | infra,perf,rocm | main | - |
| - | [#42248](https://github.com/sgl-project/sglang/pull/42248) `[Perf] srt: Native tensor output and prefill scoring optimizations` | infra,perf | main | - |
| - | [#42654](https://github.com/sgl-project/sglang/pull/42654) `[Perf] moe: Enable deferred finalize for NVFP4 on the routed TRT-LLM runner` | infra,perf,quant,rocm | main | - |
| - | [#42718](https://github.com/sgl-project/sglang/pull/42718) `[Fix] dsv41: Run DSpark compact verify by mapping packed verify tokens to their requests` | bug,infra,perf | main | - |
| - | [#42725](https://github.com/sgl-project/sglang/pull/42725) `[Fix] [Intel] attention: Allow page_size=1 on the Intel XPU backend` | bug,infra,nvidia | main | - |
| - | [#42968](https://github.com/sgl-project/sglang/pull/42968) `[Perf] DeepSeek-V4.1: Support indexer TP shard` | infra,perf | main | - |
| - | [#43110](https://github.com/sgl-project/sglang/pull/43110) `[Fix] hicache: Resolve derived sidecars over every source transfer` | bug,infra,perf | main | - |
| - | [#43194](https://github.com/sgl-project/sglang/pull/43194) `[Fix] diffusion: Cosmos3 Bug fixes` | bug,infra,perf,quant | main | - |
| - | [#43204](https://github.com/sgl-project/sglang/issues/43204) ``AssertionError: Can not alloc mamba cache` kills the engine when every cached mamba state is locked` | perf | ? | - |
| - | [#43428](https://github.com/sgl-project/sglang/issues/43428) `[Feature] Add native SmolLM3 support` |  | ? | - |
| - | [#43786](https://github.com/sgl-project/sglang/pull/43786) `[Perf] DeepSeek-V4: Fuse inverse RoPE into wo_a FP8 quantization` | infra,perf,quant | main | - |
| - | [#43788](https://github.com/sgl-project/sglang/pull/43788) `[Fix] [AMD] deterministic: Bypass AITER GEMM and MoE in deterministic mode on gfx950` | bug,infra,quant,rocm | main | - |
| - | [#43864](https://github.com/sgl-project/sglang/issues/43864) `[Bug] gemma-4-31B-it: audio request crashes the scheduler;      /get_model_info misreports has_audio_understan` | bug | ? | - |
| - | [#43865](https://github.com/sgl-project/sglang/pull/43865) `[Fix] tokenizer_manager: Prevent scheduler crash and has_audio_understanding misreport for audio-declaring mod` | bug,infra | main | - |
| - | [#43866](https://github.com/sgl-project/sglang/pull/43866) `[Fix] multimodal: Return 400 for images Pillow refuses as decompression bombs` | bug,infra,perf | main | - |
| - | [#43875](https://github.com/sgl-project/sglang/issues/43875) `[Bug] [diffusion] OpenAI API hardening and runtime utils/pipeline bugs` | perf | ? | - |
| - | [#43896](https://github.com/sgl-project/sglang/pull/43896) `[Refactor] scheduler: Write every request finish state through Req methods` | infra,perf | main | - |
| - | [#43897](https://github.com/sgl-project/sglang/pull/43897) `[Refactor] scheduler: Finish queue-popped aborts in place` | infra,perf | main | - |
| - | [#43898](https://github.com/sgl-project/sglang/pull/43898) `[Refactor] scheduler: Remove PD multiplexing` | infra,perf,rocm | main | - |
| - | [#43899](https://github.com/sgl-project/sglang/pull/43899) `[Refactor] scheduler: Track running requests in an owner list` | infra | main | - |
| - | [#43900](https://github.com/sgl-project/sglang/pull/43900) `[Refactor] scheduler: Route every step launch through one hook and count in-flight steps` | infra,perf | main | - |
| - | [#43901](https://github.com/sgl-project/sglang/pull/43901) `[Refactor] scheduler: List every request holder and check no request is in two` | infra,perf | main | - |
| - | [#43902](https://github.com/sgl-project/sglang/pull/43902) `[Refactor] scheduler: Move deferred responses into an object and rename the PD prefill inflight queue to the t` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#43903](https://github.com/sgl-project/sglang/pull/43903) `[Refactor] scheduler: Hold a launched prefill in one list until its next holder takes it` | infra | main | - |
| - | [#43904](https://github.com/sgl-project/sglang/pull/43904) `[Refactor] scheduler: Check request ownership once at step launch` | infra | main | - |
| - | [#43905](https://github.com/sgl-project/sglang/pull/43905) `[Fix] scheduler: Abort held decode requests, and read live requests from the lists` | bug,infra | main | - |
| - | [#43906](https://github.com/sgl-project/sglang/pull/43906) `[Fix] scheduler: Tell a step's middle chunk from the batch's chunked request, not a per-request counter` | bug,infra | main | - |
| - | [#43907](https://github.com/sgl-project/sglang/pull/43907) `[Refactor] scheduler: Share one interface across request lists and abort through each list` | infra | main | - |
| - | [#43908](https://github.com/sgl-project/sglang/pull/43908) `[Refactor] scheduler: Hold wrapped requests in request lists and abort through each list` | infra | main | - |
| - | [#43909](https://github.com/sgl-project/sglang/pull/43909) `[Fix] scheduler: Record weight version events on every request list` | bug,infra | main | - |
| - | [#43910](https://github.com/sgl-project/sglang/pull/43910) `[Refactor] scheduler: Hold the waiting queue and the chunked slot in request lists` | infra | main | - |
| - | [#43911](https://github.com/sgl-project/sglang/pull/43911) `[Fix] hisparse: Release HiSparse rows on the KV checksum mismatch and chunked abort exits` | bug,infra | main | - |
| - | [#44148](https://github.com/sgl-project/sglang/pull/44148) `[Feat] moe: Allow SiTU on the CuTe DSL NVFP4 MoE (Kimi-K3 W4A16)` | infra,nvidia,quant | main | - |
| - | [#44168](https://github.com/sgl-project/sglang/pull/44168) `[Perf] [NVIDIA] sampling: Enable Cake softmax on SM100` | infra,nvidia,perf | main | - |
| - | [#44197](https://github.com/sgl-project/sglang/pull/44197) `[Fix] [AMD] mamba: Import the causal conv1d kernels for Mamba2 layers on ROCm` | bug,perf,rocm | main | - |
| - | [#44253](https://github.com/sgl-project/sglang/pull/44253) `[Feat] simulator: migrate the estimator SDK to AISimulate` | infra | main | - |
| - | [#44268](https://github.com/sgl-project/sglang/pull/44268) `[Fix] moe: Fix --enable-fused-moe-sum-all-reduce outside CUDA and with LoRA hooks` | bug,infra,nvidia,perf | main | - |
| - | [#44302](https://github.com/sgl-project/sglang/pull/44302) `[Perf] [AMD] Qwen3.8: Enable fused GDN packing for ratio-3 heads` | infra,perf,rocm | main | - |
| - | [#44394](https://github.com/sgl-project/sglang/pull/44394) `[Feat] [CPU] cpu-graph: Add prefill torch compile graph and dynamic graph support` | infra,perf | main | - |
| - | [#44398](https://github.com/sgl-project/sglang/pull/44398) `[Test] [NPU] kimi_k3: enable L2 host HiCache for 32p gpqa accuracy test with host hit-rate bench` | infra,perf,risk | main | - |
| - | [#44399](https://github.com/sgl-project/sglang/pull/44399) `[Feat] gemma4: per-layer attention backend` | infra | main | - |
| - | [#44435](https://github.com/sgl-project/sglang/pull/44435) `[Feat] [NPU] scheduler: align cross-request ViT batching with CUDA and fix NPU graph buffer ownership` | bug,infra,nvidia | main | - |
| - | [#44437](https://github.com/sgl-project/sglang/pull/44437) `[Fix] mem_cache: Move FP4 MLA block scales with their KV in `move_kv_cache`` | bug,infra,quant | main | - |
| - | [#44438](https://github.com/sgl-project/sglang/pull/44438) `[Fix] deterministic: Validate the per-phase attention backends` | bug,infra | main | - |
| - | [#44442](https://github.com/sgl-project/sglang/pull/44442) `[Feat] [NPU] GLM-4.1V: Add ModelSlim W8A8S support with multimodal serving optimizations` | infra,perf,quant | main | - |
| - | [#44457](https://github.com/sgl-project/sglang/pull/44457) `[Perf] attention: Skip the triton MLA K rescale when k_scale is 1.0` | infra,perf,rocm | main | - |
| - | [#44459](https://github.com/sgl-project/sglang/pull/44459) `[Perf] [AMD] mla: Fuse RoPE, concat and KV-cache write for MLA decode on gfx1250` | infra,perf,rocm | main | - |
| - | [#44489](https://github.com/sgl-project/sglang/pull/44489) `[Perf] [AMD] deterministic: Allow AITER decode attention on gfx950` | infra,perf,rocm | main | - |
| - | [#44491](https://github.com/sgl-project/sglang/pull/44491) `[Perf] qwen3: Fuse SiLU*mul with the NVFP4 quantization of down_proj in Qwen2MLP` | infra,perf,quant | main | - |
| - | [#44494](https://github.com/sgl-project/sglang/pull/44494) `[Fix] metrics: Handle CPU monitor clock resets after restore` | bug,infra | main | - |
| - | [#44503](https://github.com/sgl-project/sglang/pull/44503) `[Refactor] sparse-mla: Expose arithmetic and DSA metadata hooks` | infra,rocm | main | - |
| - | [#44506](https://github.com/sgl-project/sglang/pull/44506) `[Fix] [NPU] glm-ocr: Fix M-RoPE section for GLM-OCR on Ascend and add A3 validation` | bug,infra | main | - |
| - | [#44538](https://github.com/sgl-project/sglang/pull/44538) `[CI] [AMD] spur: Run AMD CI suites on MI35x nodes scheduled through Spur` | infra,rocm | main | - |
| - | [#44574](https://github.com/sgl-project/sglang/pull/44574) `[Fix] multimodal: Keep shared-memory feature transport for multi-node pipeline parallelism` | bug,infra | main | - |
| - | [#44718](https://github.com/sgl-project/sglang/pull/44718) `[Feat] [AMD] mamba: Store hicache checkpoints without a GPU slot` | infra,perf,rocm | main | - |
| - | [#44725](https://github.com/sgl-project/sglang/pull/44725) `[Fix] minimax_h3: Support out-of-tree platforms` | bug,infra,perf | main | - |
| - | [#44750](https://github.com/sgl-project/sglang/pull/44750) `[Fix] nemotron-h: Allow explicit CuTe DSL W4A16 MoE` | bug,infra,quant | main | - |
| - | [#44825](https://github.com/sgl-project/sglang/pull/44825) `[Doc] blogs: Sync LMSYS SGLang blog cards` |  | main | - |
| - | [#44967](https://github.com/sgl-project/sglang/pull/44967) `[Test] [NPU] kimi_k3: add 128k prefill/decode perf acceptance cases on 4-node mix` | infra,perf | main | - |
| - | [#44974](https://github.com/sgl-project/sglang/pull/44974) `[Fix] moe: Avoid stale prefix reads in ep_scatter` | bug,infra,perf | main | - |
| - | [#44990](https://github.com/sgl-project/sglang/pull/44990) `[Refactor] memory-pool: Describe DeepSeek V4 device pools with buffer info` | infra,rocm | main | - |
| - | [#45019](https://github.com/sgl-project/sglang/pull/45019) `[Refactor] memory-pool: Build DSA indexer host pools from buffer info` | infra,rocm | main | - |
| - | [#45020](https://github.com/sgl-project/sglang/pull/45020) `[Refactor] memory-pool: Build unified page-envelope host pools from buffer info` | infra,rocm | main | - |
| - | [#45065](https://github.com/sgl-project/sglang/pull/45065) `[Fix] diffusion: Exit the worker after an unrecoverable device error` | bug,infra,perf | main | - |
| - | [#45089](https://github.com/sgl-project/sglang/pull/45089) `[Perf] [NVIDIA] fused_moe: Add H20 configs for GLM-5.3-Flash TP8/TP4` | infra,nvidia,perf | main | - |
| - | [#45129](https://github.com/sgl-project/sglang/pull/45129) `[Fix] Anthropic: accept thinking.display="updates"` | bug,infra | main | - |
| - | [#45149](https://github.com/sgl-project/sglang/pull/45149) `[Feat] [MLU] platform: Add initial support for Cambricon MLUs` | infra,perf | main | - |
| - | [#45174](https://github.com/sgl-project/sglang/pull/45174) `[Fix] Minimax-M3: Deterministic tie-breaking in the CUDA radix decode top-k` | bug,infra,nvidia,perf | main | - |
| - | [#45200](https://github.com/sgl-project/sglang/pull/45200) `[Fix] humming: Free replaced MoE weights after each sublayer transform` | bug,infra | main | - |
| - | [#45202](https://github.com/sgl-project/sglang/pull/45202) `[Perf] [AMD] Kimi-K3: prepare the attention interface for mono fusion` | infra,perf,rocm | main | - |
| - | [#45248](https://github.com/sgl-project/sglang/pull/45248) `[Refactor] kda: Import recurrent_kda from the canonical flashinfer namespace` | nvidia | main | - |
| - | [#45293](https://github.com/sgl-project/sglang/pull/45293) `[CI] [NPU] tests: Add GSM8K PR gate for DSV4-Flash W8A8 8P GPQA` | infra,quant | main | - |
| - | [#45302](https://github.com/sgl-project/sglang/pull/45302) `[Fix] [NPU] DSA: Correct DSA Models Sparse offload index-cache budgeting` | bug,infra,perf | main | - |
| - | [#45328](https://github.com/sgl-project/sglang/pull/45328) `[Perf] pd: Publish decode KV destinations without host syncs under overlap` | infra,perf | main | - |
| - | [#45332](https://github.com/sgl-project/sglang/pull/45332) `[Fix] [AMD] quark: Load MXFP4 MoE checkpoints on gfx95 and gfx1250 without SGLANG_USE_AITER` | bug,infra,quant,rocm | main | - |
| - | [#45360](https://github.com/sgl-project/sglang/pull/45360) `[Doc] cookbook: add Muse Spark unified memory control` |  | main | - |
| - | [#45377](https://github.com/sgl-project/sglang/pull/45377) `[CI] [Intel] disaggregation: Run XPU P/D nightly on Mooncake and NIXL` | infra,nvidia | main | - |
| - | [#45406](https://github.com/sgl-project/sglang/pull/45406) `[Feat] [NVIDIA] megakernels: Expose hybrid runtime and DSpark verification views` | infra,nvidia,perf | main | - |
| - | [#45443](https://github.com/sgl-project/sglang/pull/45443) `[Fix] [AMD] imports: Skip import-time device probes when no GPU is visible` | bug,perf,rocm | main | - |
| - | [#45466](https://github.com/sgl-project/sglang/pull/45466) `[Fix] constrained: Do not cache grammar poll timeouts as invalid grammars` | bug,infra,perf | main | - |
| - | [#45486](https://github.com/sgl-project/sglang/pull/45486) `[Fix] [AMD] MoE: Preserve CT FP8 Triton layout and reduction dimensions` | bug,infra,perf,quant,rocm | main | - |
| - | [#45496](https://github.com/sgl-project/sglang/pull/45496) `[Fix] data_parallel_controller: Fix active ranks update and simplify round-robin dispatch` | bug | main | - |
| - | [#45550](https://github.com/sgl-project/sglang/pull/45550) `[Fix] [NPU] diffusion: :bug: Auto-select FA for MXFP8 attention` | bug,infra,perf,quant | main | - |
| - | [#45600](https://github.com/sgl-project/sglang/pull/45600) `[Feat] linker: Add prefetch mode for the Mooncake external linker` | infra,perf | main | - |
| - | [#45601](https://github.com/sgl-project/sglang/pull/45601) `[Perf] [AMD] deterministic: Allow AITER prefill attention on gfx950` | infra,perf,rocm | main | - |
| - | [#45683](https://github.com/sgl-project/sglang/pull/45683) `[Feat] muse-spark: Infer hardware launch defaults and simplify cookbook recipes` |  | main | - |
| - | [#45717](https://github.com/sgl-project/sglang/pull/45717) `[Feat] [Intel] CPU-core-binding: Support Compute Building Block for next Gen Xeon` | infra,perf | main | - |
| - | [#45770](https://github.com/sgl-project/sglang/issues/45770) `[Bug] EPD encoder allocates unused pinned embedding pools on nonzero TP ranks` | infra | ? | - |
| - | [#45772](https://github.com/sgl-project/sglang/pull/45772) `[Fix] encoder: allocate embedding cache resources only on rank 0` | bug,infra,perf | main | - |
| - | [#45785](https://github.com/sgl-project/sglang/pull/45785) `[Fix] scheduler: Publish KV metrics when idle` | bug,infra | main | - |
| - | [#45798](https://github.com/sgl-project/sglang/pull/45798) `[Fix] llava: Load LLaVA-1.5 CLIP tower` | bug,infra | main | - |
| - | [#45828](https://github.com/sgl-project/sglang/pull/45828) `[Perf] fp8: Hopper small-M GEMV, fused KDA output quant, CUDA grouped top-k, partial-block tails` | infra,nvidia,perf,quant | main | - |
| - | [#45834](https://github.com/sgl-project/sglang/pull/45834) `[Fix] diffusion: LoRA merge cache key identity and eviction` | bug,infra,perf | main | - |
| - | [#45839](https://github.com/sgl-project/sglang/pull/45839) `[Fix] HiCache: bind captured KDA waits to live load events` | bug,infra,perf | main | - |
| - | [#45876](https://github.com/sgl-project/sglang/pull/45876) `[Perf] DFLASH: route draft bf16 GEMMs through tuned dispatch on GB300` | nvidia,perf,quant | main | - |
| - | [#45883](https://github.com/sgl-project/sglang/pull/45883) `[Feat] rust/grpc: Honor --grpc-response-timeout-secs in the Rust server` | infra | main | - |
| - | [#45885](https://github.com/sgl-project/sglang/pull/45885) `[Feat] nemotron3-embed: Support Nemotron-3-Embed embedding models` | infra | main | - |
| - | [#45945](https://github.com/sgl-project/sglang/pull/45945) `[Feat] comm: Gated background transfers` | infra | main | - |
| - | [#45953](https://github.com/sgl-project/sglang/issues/45953) `[Bug] Glm47MoeDetector.detect_and_parse drops tool calls when the function name is followed by a newline (non-` |  | ? | - |
| - | [#45972](https://github.com/sgl-project/sglang/pull/45972) `[Fix] kimi_k3: Use uuid tool_call_id instead of history-count id` | bug,infra | main | - |
| - | [#45981](https://github.com/sgl-project/sglang/pull/45981) `[CI] lora: Simplify LoRA tests and add a lora rerun group` | infra,nvidia | main | - |
| - | [#46018](https://github.com/sgl-project/sglang/pull/46018) `[Fix] humming: adapt integration to kernels 0.1.18` | bug,infra,perf | main | - |
| - | [#46028](https://github.com/sgl-project/sglang/pull/46028) `[Perf] cosmos3: Accelerate conditioning hashing with GPU BLAKE3` | infra,perf | main | - |
| - | [#46053](https://github.com/sgl-project/sglang/pull/46053) `[Fix] function_call: Normalize GLM non-streaming tool names` | bug,infra | main | - |
| - | [#46082](https://github.com/sgl-project/sglang/pull/46082) `[Perf] trtllm_mha: Split full-attention decode KV across CTAs at large batch (opt-in)` | infra,nvidia,perf | main | - |
| - | [#46088](https://github.com/sgl-project/sglang/pull/46088) `[Perf] dsv41: Fuse decode mHC post, combine and RMSNorm into one kernel` | infra,perf | main | - |
| - | [#46166](https://github.com/sgl-project/sglang/pull/46166) `[Perf] http: Serialize /v1/embeddings responses with model_json_response` | infra,perf | main | - |
| - | [#46175](https://github.com/sgl-project/sglang/pull/46175) `[CI] rust: Publish sglang-api-types on crates.io` | infra | main | - |
| - | [#46225](https://github.com/sgl-project/sglang/pull/46225) `[Fix] attention: Zero padded KDA/GDN recurrent outputs` | bug,infra,perf | main | - |
| - | [#46251](https://github.com/sgl-project/sglang/pull/46251) `[Perf] sgl-router: Encode tiktoken models with fastokens under --tokenizer-backend fast` | infra,perf | main | - |
| - | [#46255](https://github.com/sgl-project/sglang/pull/46255) `[Fix] diffusion: LoRA alpha reload, auto-mode skip, critic coverage` | bug,infra,perf | main | - |
| - | [#46274](https://github.com/sgl-project/sglang/pull/46274) `[Fix] diffusion: Keep each request's rollout trajectory and conditioning under dynamic batching` | bug,infra,perf | main | - |
| - | [#46277](https://github.com/sgl-project/sglang/pull/46277) `[Perf] diffusion: Wan-Animate-2 decode clamp, LTX-2 Bongmath closed form, rollout log-prob/CPU-copy, validator` | bug,infra,perf,risk | main | - |
| - | [#46278](https://github.com/sgl-project/sglang/pull/46278) `[Feat] [NPU] dspark: Integrate native sampling and verification kernels` | infra,perf | main | - |
| - | [#46291](https://github.com/sgl-project/sglang/pull/46291) `[Feat] rust-server: multimodal (image) preprocessing through sglang-processor` | infra | main | - |
| - | [#46325](https://github.com/sgl-project/sglang/pull/46325) `[Perf] [AMD] deterministic: Use a fixed-order two-stage all-reduce for large inputs` | infra,perf,rocm | main | - |
| - | [#46327](https://github.com/sgl-project/sglang/pull/46327) `[Perf] [AMD] unquant: Pad gfx115x linear and lm_head weight rows to avoid cache aliasing` | infra,perf,quant,rocm | main | - |
| - | [#46328](https://github.com/sgl-project/sglang/pull/46328) `[Perf] diffusion: opt-in Wan UMT5 padding trim (SGLANG_DIFFUSION_WAN_TEXT_PADDING)` | infra,perf | main | - |
| - | [#46334](https://github.com/sgl-project/sglang/pull/46334) `[Fix] scheduler: Publish KV events while the engine is paused` | bug,infra | main | - |
| - | [#46373](https://github.com/sgl-project/sglang/pull/46373) `[Fix] disaggregation: Send decode transfer destinations to prefill only after the in-flight forward` | bug,infra | main | - |
| - | [#46394](https://github.com/sgl-project/sglang/pull/46394) `[CI] [Intel] ci/xpu: Rename rolling Docker tag and add release-cut results CSV` | infra,nvidia | main | - |
| - | [#46395](https://github.com/sgl-project/sglang/pull/46395) `[Feat] disagg: Write PD decode KV to the linker and skip pages the prefill already stored` | infra,perf | main | - |
| - | [#46443](https://github.com/sgl-project/sglang/pull/46443) `[Fix] diffusion: Fix rollout conditioning and scalar weight checksums` | bug,infra,perf | main | - |
| - | [#46444](https://github.com/sgl-project/sglang/issues/46444) `[Bug] diffusion: Rollout conditioning misalignment and scalar weight checksum failure` | perf | ? | - |
| - | [#46454](https://github.com/sgl-project/sglang/pull/46454) `[Perf] diffusion: HunyuanImage-3 prefix K/V cache, opt-in FA3 attention and think-prompt support` | infra,nvidia,perf | main | - |
| - | [#46456](https://github.com/sgl-project/sglang/pull/46456) `[Perf] paged-experts: exact size pinning` | infra,perf | main | - |
| - | [#46476](https://github.com/sgl-project/sglang/issues/46476) `[Bug] DSpark draft query width is incorrect on FA3/FA4 when `sample_from_anchor=False`` | nvidia | ? | - |
| - | [#46478](https://github.com/sgl-project/sglang/pull/46478) `[Fix] attention: Use ModelRunner query width for DSpark FlashAttention drafts` | bug,infra | main | - |
| - | [#46485](https://github.com/sgl-project/sglang/pull/46485) `[Feat] observability: Add scheduler_iterations_total metric` | infra | main | - |
| - | [#46519](https://github.com/sgl-project/sglang/pull/46519) `[Chore] [XPU] deps: Pin sglang-kernel-xpu by version using uv` | infra,nvidia,perf | main | - |
| - | [#46580](https://github.com/sgl-project/sglang/pull/46580) `[Feat] diffusion/model: add the BRIA Fibo 2.0 transformer and text conditioning` | infra,perf | main | - |
| - | [#46597](https://github.com/sgl-project/sglang/pull/46597) `[Perf] [NVIDIA] minimax-sparse: Run the decode indexer CP on Hopper at TP4 and TP8` | infra,nvidia,perf | main | - |
| - | [#46601](https://github.com/sgl-project/sglang/pull/46601) `[Fix] diffusion: LingBot QKV sharing, causal RoPE on no-cache path, uneven split guard` | bug,infra,perf | main | - |
| - | [#46606](https://github.com/sgl-project/sglang/pull/46606) `[Fix] cache: Roll back host slots when allocation raises` | bug,infra,perf | main | - |
| - | [#46623](https://github.com/sgl-project/sglang/pull/46623) `[Feat] xpu: Consolidate simple XPU enablements` | infra,nvidia,perf | main | - |
| - | [#46627](https://github.com/sgl-project/sglang/pull/46627) `[Test] minimax-m3.1: Add nightly e2e tests on H200 and B300` | infra,nvidia | main | - |
| - | [#46637](https://github.com/sgl-project/sglang/pull/46637) `[Feat] rust/grpc: Report the node's Rust listeners in api.v1 discovery` | infra | main | - |
| - | [#46654](https://github.com/sgl-project/sglang/pull/46654) `[Fix] scheduler: Skip --prefill-decode-interval when nothing is decoding` | bug,infra | main | - |
| - | [#46662](https://github.com/sgl-project/sglang/pull/46662) `[Doc] [AMD] GLM-5.3: Enable MTP on MI355X and add the agentic recipe with the AMD monokernel` | rocm | main | - |
| - | [#46666](https://github.com/sgl-project/sglang/issues/46666) `[Bug] DeepSeek-V4.1 DSpark with SGLANG_ENABLE_DP_SPEC_PREFILL_COORDINATION: decoder-tail run_idle cuts verify ` |  | ? | - |
| - | [#46676](https://github.com/sgl-project/sglang/pull/46676) `[Fix] dsv4: Keep a coordinated verify rank out of the decoder-tail idle replay` | bug,infra | main | - |
| - | [#46677](https://github.com/sgl-project/sglang/pull/46677) `[Perf] [AMD] dsv4.1: Wire up 32x32-block fp8 wo_a GEMM` | infra,perf,quant,rocm | main | - |
| - | [#46685](https://github.com/sgl-project/sglang/pull/46685) `[CI] [AMD] monokernels: Bump the sgl-amd-mono pin daily` | infra,rocm | main | - |
| - | [#46690](https://github.com/sgl-project/sglang/pull/46690) `[Feat] [AMD] minimax: gfx950 sparse attention, NVFP4 KV and DSpark verify kernels` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#46691](https://github.com/sgl-project/sglang/pull/46691) `[Feat] [AMD] minimax: gfx950 MoE, router GEMV, block-fp8 GEMM and fp8 producer kernels` | infra,perf,quant,rocm | main | - |
| - | [#46692](https://github.com/sgl-project/sglang/pull/46692) `[Feat] [AMD] distributed: JIT quick all-reduce for TP4 on gfx950` | infra,perf,rocm | main | - |
| - | [#46720](https://github.com/sgl-project/sglang/pull/46720) `[Fix] cuda-graph: Keep attention metadata and SP workspaces alive across graph variants of a batch size` | bug,infra,nvidia | main | - |
| - | [#46721](https://github.com/sgl-project/sglang/pull/46721) `[Test] cuda-graph: Add a standalone CUDA-graph lifetime validation tool and its skill` | nvidia | main | - |
| - | [#46724](https://github.com/sgl-project/sglang/pull/46724) `[Perf] [NVIDIA] muse-spark-open: Fuse MoE finalize with the 2shot_push all-reduce` | nvidia,perf | main | - |
| - | [#46738](https://github.com/sgl-project/sglang/pull/46738) `[Perf] kda: Write convolution output directly into contiguous QKV planes` | infra,perf | main | - |
| - | [#46759](https://github.com/sgl-project/sglang/pull/46759) `[CI] [NPU] nightly: add rerun suites for three 2-NPU cases` | infra | main | - |
| - | [#46800](https://github.com/sgl-project/sglang/pull/46800) `[Fix] [AMD] quark: Keep MXFP8 shared experts out of the MXFP4 fused slot on dense-first models` | bug,infra,perf,quant,rocm | main | - |
| - | [#46816](https://github.com/sgl-project/sglang/pull/46816) `[Fix] [Intel] gemma4: Bidirectional image attention on the intel_xpu backend` | bug,infra,nvidia | main | - |
| - | [#46827](https://github.com/sgl-project/sglang/pull/46827) `[Feat] unified-memory: Evict Full and SWA KV from one shared LRU order (joint_lru)` | infra,perf | main | - |
| - | [#46833](https://github.com/sgl-project/sglang/pull/46833) `[Fix] [AMD] aiter: Use the layer's softmax scale in MHA prefill and decode` | bug,infra,quant,rocm | main | - |
| - | [#46857](https://github.com/sgl-project/sglang/pull/46857) `[Perf] GLM-5.3: Restore TP decode fusion and graph sizing with CP prefill` | infra,perf | main | - |
| - | [#46860](https://github.com/sgl-project/sglang/pull/46860) `[Refactor] diffusion: normalize diffusers output layout in one place` | infra,perf | main | - |
| - | [#46871](https://github.com/sgl-project/sglang/pull/46871) `[Fix] diffusion: keep tied vocab tables on device under layerwise offload` | bug,infra,perf | main | - |
| - | [#46883](https://github.com/sgl-project/sglang/pull/46883) `[Chore] [AMD] docker: Build uTLX into the gfx950 rocm10 images` | infra,rocm | main | - |
| - | [#46884](https://github.com/sgl-project/sglang/pull/46884) `[Perf] hicache: Publish prefill read-done when offload copies are fenced on the forward stream` | infra,perf | main | - |
| - | [#46890](https://github.com/sgl-project/sglang/pull/46890) `[Feat] dsa: Extend interleave-CP breakable prefill graphs to GlmMoeDs…` | infra,perf | main | - |
| - | [#46892](https://github.com/sgl-project/sglang/pull/46892) `[Feat] docker: Update the EFA images to EFA installer 1.51.0` | infra | main | - |
| - | [#46898](https://github.com/sgl-project/sglang/pull/46898) `[Perf] disaggregation: Stop device admission in a decode transfer pass at the first refusal` | infra,perf | main | - |
| - | [#46905](https://github.com/sgl-project/sglang/pull/46905) `[Perf] Hunyuan3D: Speed up shape export with GPU-side grid generation` | infra,perf | main | - |
| - | [#46907](https://github.com/sgl-project/sglang/pull/46907) `[Fix] minimax-h3: Swap the fc1 halves of the Acc LoRA in build_minimax_h3_pdd_weights` | bug,infra,perf | main | - |
| - | [#46908](https://github.com/sgl-project/sglang/pull/46908) `[Perf] [NVIDIA] qwen3: Reuse fused QK-norm/RoPE kernel for decode` | infra,nvidia,perf | main | - |
| - | [#46921](https://github.com/sgl-project/sglang/pull/46921) `[Feat] [NPU] attention: Support modelslim MLA FP8 KVCache` | infra,quant | main | - |
| - | [#46922](https://github.com/sgl-project/sglang/pull/46922) `[Test] cpu: Re-enable the subblock sparse attention test` | infra | main | - |
| - | [#46928](https://github.com/sgl-project/sglang/pull/46928) `[Fix] [AMD] aiter: Fix garbage decode output with unified attention at page size 1 under CUDA graph` | bug,infra,nvidia,risk,rocm | main | - |
| - | [#46930](https://github.com/sgl-project/sglang/pull/46930) `[Perf] hicache: Wait once per write_back eviction walk, not once per victim` | infra,perf | main | - |
| - | [#46936](https://github.com/sgl-project/sglang/pull/46936) `[Feat] hicache: Store MXFP8 KV pages in L3 as payload + scales objects` | infra,quant | main | - |
| - | [#46937](https://github.com/sgl-project/sglang/pull/46937) `[Fix] anthropic: Preserve cache_salt for Messages requests` | bug,infra | main | - |
| - | [#46947](https://github.com/sgl-project/sglang/pull/46947) `[CI] [AMD] diffusion/flux3: Make exact-quality VAE convolutions deterministic on ROCm` | infra,perf,rocm | main | - |
| - | [#46956](https://github.com/sgl-project/sglang/pull/46956) `[Perf] Hunyuan3D: Skip redundant OBJ exports when generating GLB` | infra,perf | main | - |
| - | [#46961](https://github.com/sgl-project/sglang/pull/46961) `[Feat] rust-server: Report cached tokens by cache tier in native /generate meta_info` | infra,perf | main | - |
| - | [#46963](https://github.com/sgl-project/sglang/pull/46963) `[Feat] rust-server: Report the scheduler's per-request stats in native /generate meta_info` | infra | main | - |
| - | [#46964](https://github.com/sgl-project/sglang/pull/46964) `[Feat] diffusion: Support Hy-Nomas INT8 DiT and FP8 VAE checkpoints` | infra,perf,quant | main | - |
| - | [#47023](https://github.com/sgl-project/sglang/pull/47023) `[Test] [NPU] deepseek_v4_flash: Switch FP8 4P GPQA test from EAGLE to DSPARK and add acceptance-rate test` | infra,quant | main | - |
| - | [#47029](https://github.com/sgl-project/sglang/pull/47029) `[Fix] attention: Compute extend attention KV offsets in int64` | bug,infra,perf | main | - |
| - | [#47030](https://github.com/sgl-project/sglang/pull/47030) `[Fix] [AMD] aiter: Use the layer's KV scales in the legacy target-verify attention` | bug,infra,quant,rocm | main | - |
| - | [#47042](https://github.com/sgl-project/sglang/pull/47042) `[Perf] [AMD] aiter: Bucket decode paged-attention partitions by sequence length` | infra,perf,rocm | main | - |
| - | [#47053](https://github.com/sgl-project/sglang/pull/47053) `[Doc] kimi-k3: Convert the cookbook page's pipe tables to JSX tables` |  | main | - |
| - | [#47054](https://github.com/sgl-project/sglang/pull/47054) `[Test] [AMD] fp8-grid: Compare the GEMM to aiter within one bf16 rounding, not bitwise` | infra,quant,rocm | main | - |
| - | [#47056](https://github.com/sgl-project/sglang/pull/47056) `[CI] [Intel] xpu-eval: Add sgl-eval to XPU test deps and move all GSM8K tests to it` | infra,nvidia | main | - |
| - | [#47062](https://github.com/sgl-project/sglang/pull/47062) `[Perf] [AMD] attention: Use the AITER FAv3 varlen kernel on gfx942 as well` | perf,rocm | main | - |
| - | [#47064](https://github.com/sgl-project/sglang/pull/47064) `[Perf] [AMD] kda: Narrow the Kimi-K3 TP8 KDA recurrent tile for small batches on gfx950` | infra,perf,rocm | main | - |
| - | [#47066](https://github.com/sgl-project/sglang/pull/47066) `[Fix] kernels: Hash tensors over 8 GiB in gpu_tensor_hash` | bug,infra,perf | main | - |
| - | [#47070](https://github.com/sgl-project/sglang/pull/47070) `[Perf] [NVIDIA] moe: Add H20 block-FP8 Triton configs for Qwen3-30B-A3B` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47084](https://github.com/sgl-project/sglang/pull/47084) `[Fix] environ: Register the batch-invariant matmul fallback flag in Envs` | bug | main | - |
| - | [#47085](https://github.com/sgl-project/sglang/pull/47085) `[Feat] RL: Report prompt KV weight versions in generation metadata` |  | main | - |
| - | [#47086](https://github.com/sgl-project/sglang/pull/47086) `[Feat] kv-canary: Pass through canary info when the KV-canary is enabled` | perf | main | - |
| - | [#47087](https://github.com/sgl-project/sglang/pull/47087) `[Feat] RL: Hash raw received weights by name in check_weights` | infra | main | - |
| - | [#47099](https://github.com/sgl-project/sglang/pull/47099) `[Feat] platforms: Let platforms default unset profile request fields` | infra | main | - |
| - | [#47106](https://github.com/sgl-project/sglang/pull/47106) `[Perf] rust-server: Flatten egress logprob columns only for rows that carry them` | infra,perf | main | - |
| - | [#47112](https://github.com/sgl-project/sglang/pull/47112) `[Feat] rust-server: Give the native /generate hook the request, its headers and its outcome` |  | main | - |
| - | [#47113](https://github.com/sgl-project/sglang/pull/47113) `[Fix] rust-server: Fix the metrics flush race and the default-priority label` | bug,risk | main | - |
| - | [#47118](https://github.com/sgl-project/sglang/pull/47118) `[CI] [AMD] diffusion/ming: Skip the CUDA-only fused RMSNorm test on ROCm` | infra,nvidia,perf,rocm | main | - |
| - | [#47119](https://github.com/sgl-project/sglang/pull/47119) `[Feat] sgl-router: Render MiniMax-M3 and M3.1 through sglang-processor` | infra | main | - |
| - | [#47120](https://github.com/sgl-project/sglang/pull/47120) `[Fix] multimodal: Preserve strong identities across VLM caches` | bug,infra,perf | main | - |
| - | [#47121](https://github.com/sgl-project/sglang/pull/47121) `[Perf] diffusion: Wan-Animate-2 1.7x faster denoising via exact FA3 in-context attention, opt-in FP8 reference` | infra,nvidia,perf,quant | main | - |
| - | [#47130](https://github.com/sgl-project/sglang/pull/47130) `[Fix] bench: Size the one-batch KV-capacity skip by the heaviest attention-DP rank for ragged batches` | bug,infra,perf | main | - |
| - | [#47135](https://github.com/sgl-project/sglang/pull/47135) `[Feat] lora: upsert on /load_lora_adapter` |  | sglang-miles | - |
| - | [#47149](https://github.com/sgl-project/sglang/pull/47149) `[Perf] dsv4: Fix amax8_varlen and mega MoE pre-dispatch grids for 1024-thread SMs` | bug,perf | main | - |
| - | [#47150](https://github.com/sgl-project/sglang/pull/47150) `[CI] [AMD] pr-test: Move test_quark_mxfp4 from the MI35x 1-GPU PR stage to nightly` | infra,quant,rocm | main | - |
| - | [#47152](https://github.com/sgl-project/sglang/pull/47152) `[CI] [AMD] pr-test: Move the Kimi-K2.5 MXFP4 BCG test to nightly` | infra,quant,rocm | main | - |
| - | [#47159](https://github.com/sgl-project/sglang/pull/47159) `[Feat] observability: Report a TTFT phase breakdown in response meta_info` | infra | main | - |
| - | [#47160](https://github.com/sgl-project/sglang/pull/47160) `[Fix] rust-server: Let an HTTP layer start a native /generate request's timing` | bug | main | - |
| - | [#47173](https://github.com/sgl-project/sglang/pull/47173) `[Refactor] [NPU] graph: Remove the NPU graph runner` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47177](https://github.com/sgl-project/sglang/pull/47177) `[Perf] pd: Copy the last chunk's state page indices to the host without a scheduler sync` | infra,perf | main | - |
| - | [#47180](https://github.com/sgl-project/sglang/pull/47180) `[Perf] [AMD] dsa: Replicate the DCP query projection on the owned route` | infra,perf,rocm | main | - |
| - | [#47186](https://github.com/sgl-project/sglang/pull/47186) `[Fix] diffusion: Preserve FP32 product rounding in Anima RoPE` | bug,infra,perf | main | - |
| - | [#47187](https://github.com/sgl-project/sglang/pull/47187) `[Doc] minimax-m3: Route GB300 decode to trtllm_mha in the cookbook recipe (prefill stays fa4)` | nvidia | main | - |
| - | [#47196](https://github.com/sgl-project/sglang/pull/47196) `[Feat] unlimited-ocr-v2: Add Unlimited-OCR v2 model support` | infra,perf | main | - |
| - | [#47200](https://github.com/sgl-project/sglang/pull/47200) `[Perf] [NVIDIA] speculative-decoding: Add generic CUDA runtime fast paths` | infra,nvidia,perf,quant | main | - |
| - | [#47201](https://github.com/sgl-project/sglang/pull/47201) `[Perf] [NVIDIA] speculative-decoding: Bind generic provider strategies` | infra,nvidia,perf,quant | main | - |
| - | [#47208](https://github.com/sgl-project/sglang/pull/47208) `[CI] [PPU] slash-command: Register PPU with shared opt-in CI tiers` | infra | main | - |
| - | [#47211](https://github.com/sgl-project/sglang/pull/47211) `[Refactor] [NPU] quant: Refactor shared quantization utilities and DSpark weight mapping` | infra,perf,quant | main | - |
| - | [#47216](https://github.com/sgl-project/sglang/pull/47216) `[Fix] [NPU] dspark: Avoid double-counting verify KV lengths in graph replay` | bug,infra | main | - |
| - | [#47229](https://github.com/sgl-project/sglang/pull/47229) `[Fix] kernels: Support OOT fused ops under torch.compile` | bug,infra,perf | main | - |
| - | [#47234](https://github.com/sgl-project/sglang/pull/47234) `[Feat] attention: Add OOT linear-attention backend registration` | infra | main | - |
| - | [#47235](https://github.com/sgl-project/sglang/pull/47235) `[Fix] multimodal: Share typed identities for Kimi prepared inputs` | bug,infra | main | - |
| - | [#47236](https://github.com/sgl-project/sglang/pull/47236) `[Perf] [AMD] moe/topk: Use the Triton softmax top-k router for Qwen3-Next (hidden 2048)` | infra,perf,rocm | main | - |
| - | [#47240](https://github.com/sgl-project/sglang/pull/47240) `[Fix] diffusion: Check cancellation at stage and sampling boundaries` | bug,infra,perf | main | - |
| - | [#47255](https://github.com/sgl-project/sglang/pull/47255) `[Fix] disaggregation: Bind NIXL transfer workers to the rank's device` | bug,infra | main | - |
| - | [#47260](https://github.com/sgl-project/sglang/pull/47260) `[Perf] detokenizer: Send per-request decode inputs once and keep them in the detokenizer` | infra,perf | main | - |
| - | [#47261](https://github.com/sgl-project/sglang/pull/47261) `[Fix] attention: Keep fused RoPE KV writes off DCP layouts` | bug,infra,perf | main | - |
| - | [#47270](https://github.com/sgl-project/sglang/pull/47270) `[Fix] diffusion: recover LTX eager performance without disabling fusion` | bug,infra,perf | main | - |
| - | [#47283](https://github.com/sgl-project/sglang/pull/47283) `[Fix] [AMD] deepseek-v4: Respect AITER selection for Q-LoRA quantization` | bug,infra,quant,rocm | main | - |
| - | [#47289](https://github.com/sgl-project/sglang/issues/47289) `[RFC] Add per-step TBO admission policy and fallback diagnostics` |  | ? | - |
| - | [#47292](https://github.com/sgl-project/sglang/pull/47292) `[Perf] diffusion: Fuse SANA-Video depthwise convolution and GLU on SM120` | infra,nvidia,perf | main | - |
| - | [#47295](https://github.com/sgl-project/sglang/pull/47295) `[Perf] cuda-graph: Upload each deduplicated executable on a private stream before its first launch` | infra,nvidia,perf | main | - |
| - | [#47297](https://github.com/sgl-project/sglang/issues/47297) `[Bug] diffusion: LingBot-Video-MoE crashes in text encoding under default layerwise offload (tied vocab table ` | bug,perf | ? | - |
| - | [#47300](https://github.com/sgl-project/sglang/pull/47300) `[Fix] TensorMatcher: keep symbol device/dtype options; use kDLGPU aliases` | bug,infra,nvidia,perf,quant | main | - |
| - | [#47301](https://github.com/sgl-project/sglang/pull/47301) `[Fix] diffusion: select Blackwell subtile attention by execution mode and quality` | bug,infra,nvidia,perf | main | - |
| - | [#47306](https://github.com/sgl-project/sglang/pull/47306) `[Perf] allreduce: enable FlashInfer AllReduce Fusion auto-enable for Kimi-K3` | infra,nvidia,perf | main | - |
| - | [#47319](https://github.com/sgl-project/sglang/pull/47319) `[Fix] rust-server: Serve /v1/loads from every listener under multi-node DP attention` | bug,infra | main | - |
| - | [#47320](https://github.com/sgl-project/sglang/pull/47320) `RL: Read byte ranges of output store fields into caller memory` |  | sglang-miles | - |
| - | [#47321](https://github.com/sgl-project/sglang/pull/47321) `[Fix] rust-server: End an /abort_request-ed request on the scheduler's abort finish reason, as Python does` | bug,infra | main | - |
| - | [#47331](https://github.com/sgl-project/sglang/pull/47331) `[Doc] [AMD] cookbook: Add DCP4 to the GLM-5.2 MI355X MXFP4 high-throughput recipe` | perf,quant,rocm | main | - |
| - | [#47333](https://github.com/sgl-project/sglang/pull/47333) `[Fix] Spec: Fall back to eager when the ragged-verify tier exceeds the captured grid` | bug,infra | main | - |
| - | [#47337](https://github.com/sgl-project/sglang/pull/47337) `[Fix] model_loader: Neutral UE8M0 block scales for dummy weights` | bug,infra,quant | main | - |
| - | [#47353](https://github.com/sgl-project/sglang/pull/47353) `[Feat] fpm: Retain captured intervals and support multiple FpmTiming listeners` | infra | main | - |
| - | [#47354](https://github.com/sgl-project/sglang/pull/47354) `[Perf] [NVIDIA] glm5: Route small-M BF16 GEMMs to FlashInfer warp split-K with PDL on SM107` | infra,nvidia,perf,quant | main | - |
| - | [#47355](https://github.com/sgl-project/sglang/pull/47355) `[Refactor] multimodal: [sglang-miles] Register token-space strategies through a registry function trainers can` |  | sglang-miles | - |
| - | [#47358](https://github.com/sgl-project/sglang/pull/47358) `[Refactor] multimodal: [sglang-miles] Let token-space strategies declare media decoding and the video device` |  | rockdu-dev-mm-v2-miles/10-registry-sync | - |
| - | [#47362](https://github.com/sgl-project/sglang/pull/47362) `[CI] [AMD] aiter: Update ROCm AITER pin to 26f4f1fb2 (gfx1250 only)` | infra,rocm | main | - |
| - | [#47365](https://github.com/sgl-project/sglang/pull/47365) `[CI] [NPU] coverage: Refresh the coverage baseline every 2 days and raise the publish gate to 40%` | infra | main | - |
| - | [#47366](https://github.com/sgl-project/sglang/pull/47366) `[Fix] disaggregation: Keep output ids during a PD rebootstrap instead of popping and replaying the last one` | bug,infra | main | - |
| - | [#47367](https://github.com/sgl-project/sglang/pull/47367) `[Feat] [NPU] attention: support mixed-chunk on the ascend attention backend` | infra | main | - |
| - | [#47373](https://github.com/sgl-project/sglang/pull/47373) `[Perf] [NPU] attention: Support mlaprolog for kimik3` | infra,perf | main | - |
| - | [#47378](https://github.com/sgl-project/sglang/pull/47378) `[Feat] diffusion: Support Pika-Labs/Pika-H3-Flex (MiniMax-H3 + 6-step LoRA)` | infra,perf | main | - |
| - | [#47380](https://github.com/sgl-project/sglang/pull/47380) `[Doc] [NPU] docs: Rename NPU hardware to A2/A3 Series products` | quant | main | - |
| - | [#47381](https://github.com/sgl-project/sglang/pull/47381) `[Fix] scheduler: Retire the beam group of an aborted chunked leader` | bug,infra | main | - |
| - | [#47382](https://github.com/sgl-project/sglang/issues/47382) `[Doc][NPU] Various missing clarifications, prerequisites and validation steps in Ascend NPU documentation` |  | ? | - |
| - | [#47387](https://github.com/sgl-project/sglang/pull/47387) `[Perf] [NVIDIA] dsv41: Balance the SM90 paged decode indexer's tiles across the GPU so one long context no lon` | infra,nvidia,perf | main | - |
| - | [#47394](https://github.com/sgl-project/sglang/pull/47394) `[Doc] [AMD] cookbook: Update Muse Spark Open MI355X AgentX recipe to the 1027 image` | rocm | main | - |
| - | [#47395](https://github.com/sgl-project/sglang/pull/47395) `[Fix] [AMD] scripts: Run and correctly test Dockerfile-only PRs (CI filter + AITER rebuild)` | bug,infra,rocm | main | - |
| - | [#47408](https://github.com/sgl-project/sglang/pull/47408) `[Fix] [AMD] quark: Fix the EP>1 crash in the Quark MXFP4 W4A16 MoE path and restrict it to gfx1151` | bug,infra,quant,rocm | main | - |
| - | [#47411](https://github.com/sgl-project/sglang/pull/47411) `[Feat] diffusion: Native Gemma-4-Unified text encoder for LTX-2.5` | infra,perf | main | - |
| - | [#47415](https://github.com/sgl-project/sglang/pull/47415) `[Perf] detokenizer: Send each step's output ids as one flat column with row offsets` | infra,perf | main | - |
| - | [#47419](https://github.com/sgl-project/sglang/pull/47419) `[Chore] release: Bump docs install version to 0.5.23` | infra,rocm | main | - |
| - | [#47422](https://github.com/sgl-project/sglang/pull/47422) `[Doc] [AMD] cookbook: Update muse-spark recipe 1030` | rocm | main | - |
| - | [#47424](https://github.com/sgl-project/sglang/pull/47424) `[Test] managers: Give the chunked-abort test scheduler an output_streamer` |  | main | - |
| - | [#47429](https://github.com/sgl-project/sglang/pull/47429) `[Doc] [NPU] docs: clarify installation and quickstart docs for Ascend NPUs` |  | main | - |
| - | [#47442](https://github.com/sgl-project/sglang/pull/47442) `[Fix] diffusion: Build the Cosmos 3 RoPE table on GPU so CPU offload gives the same output` | bug,infra,perf | main | - |
| - | [#47444](https://github.com/sgl-project/sglang/issues/47444) `[Bug] NemotronHConfig rejects transformers 5 layer types `linear_attention` / `full_attention` in config.json` |  | ? | - |
| - | [#47445](https://github.com/sgl-project/sglang/pull/47445) `[Fix] ipc: Make multimodal payloads, hidden states and weight-update dtypes round-trip under msgpack IPC` | bug,infra | main | - |
| - | [#47452](https://github.com/sgl-project/sglang/pull/47452) `[Perf] kimi-k3: Allow residual bank shards with NCCL` | infra,nvidia,perf | main | - |
| - | [#47458](https://github.com/sgl-project/sglang/pull/47458) `[Fix] nemotron: Accept transformers 5 layer types in NemotronHConfig` | bug | main | - |
| - | [#47464](https://github.com/sgl-project/sglang/pull/47464) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main ea8b3439` |  | main | - |
| - | [#47465](https://github.com/sgl-project/sglang/pull/47465) `[Perf] diffusion: Hold a Qwen-Image-2.1 Q/K norm + RoPE row with a half-warp` | infra,perf | main | - |
| - | [#47466](https://github.com/sgl-project/sglang/pull/47466) `[Perf] diffusion: Skip the cross-request cache for Qwen3-VL vision features` | infra,perf | main | - |
| - | [#47467](https://github.com/sgl-project/sglang/pull/47467) `[Perf] diffusion: Replay Qwen-Image-2.1's text-only encoder from CUDA graphs` | infra,nvidia,perf | main | - |
| - | [#47474](https://github.com/sgl-project/sglang/pull/47474) `[Fix] diffusion/bcg: Warm up LTX-2 two-stage at the output resolution` | bug,infra,perf | main | - |
| - | [#47476](https://github.com/sgl-project/sglang/pull/47476) `[Feat] paged-experts: size the resident experts automatically` | infra | main | - |
| - | [#47483](https://github.com/sgl-project/sglang/pull/47483) `[Chore] [AMD] mono-kernel: Bump sgl-amd-mono for Qwen3.8-Flash-Next` | infra,perf,rocm | main | - |
| - | [#47488](https://github.com/sgl-project/sglang/pull/47488) `[Fix] diffusion: Fail fast on offline runtime failures` | bug,infra,perf | main | - |
| - | [#47489](https://github.com/sgl-project/sglang/pull/47489) `[Feat] rust-server: Drain on SIGTERM like the Python server` | infra | oss-sync-7ef70da4f4 | - |
| - | [#47494](https://github.com/sgl-project/sglang/pull/47494) `[Perf] dspark: Refresh Mamba tracking once per verification step` | infra,perf | main | - |
| - | [#47503](https://github.com/sgl-project/sglang/pull/47503) `[Perf] rmsnorm: One SM100-tuned JIT template for plain, fused residual-add and fp8 per-tensor quant` | infra,nvidia,perf,quant | main | - |
| - | [#47504](https://github.com/sgl-project/sglang/pull/47504) `[CI] [AMD] mi355x: Clean up interrupted nightly jobs and reduce runner disk usage` | infra,rocm | main | - |
| - | [#47512](https://github.com/sgl-project/sglang/pull/47512) `[Perf] sampling: JIT softmax and argmax for the sampler and speculative verify` | infra,perf | main | - |
| - | [#47515](https://github.com/sgl-project/sglang/issues/47515) `[Bug] diffusion: Nomas KV budget ignores freed cached memory, and SP divisibility is checked too late` | perf | ? | - |
| - | [#47516](https://github.com/sgl-project/sglang/pull/47516) `[Fix] diffusion: Nomas KV budget counts freed cached memory, reject SP-indivisible segments up front` | bug,infra,perf | main | - |
| - | [#47520](https://github.com/sgl-project/sglang/pull/47520) `[Doc] [AMD] cookbook: Add Qwen3.8-Flash-Next MI355X AgentX recipe` | rocm | main | - |
| - | [#47521](https://github.com/sgl-project/sglang/pull/47521) `[Fix] scheduler: Abort retracted requests whose KV the recompute cannot rebuild` | bug,infra | main | - |
| - | [#47522](https://github.com/sgl-project/sglang/pull/47522) `[CI] codespell: Ignore miniTE blog name` | infra | main | - |
| - | [#47526](https://github.com/sgl-project/sglang/pull/47526) `[Perf] Kimi-K3: Enable the fused KDA decode at 6 and 3 heads per rank` | infra,perf | main | - |
| - | [#47532](https://github.com/sgl-project/sglang/pull/47532) `[Feat] rust-server: Reach every attention-DP rank with aborts and publish the listener map` | infra | main | - |
| - | [#47537](https://github.com/sgl-project/sglang/pull/47537) `[Fix] rust-server: Give the mixed-logprob frame test's payload flat output ids with row offsets` | bug,infra | main | - |
| - | [#47539](https://github.com/sgl-project/sglang/pull/47539) `[Doc] cookbook: Use latest image for Muse Spark Open deployment` |  | main | - |
| - | [#47540](https://github.com/sgl-project/sglang/pull/47540) `[Fix] spec: Seed the DSpark MLA draft weights in the verify-rows test` | bug | main | - |
| - | [#47542](https://github.com/sgl-project/sglang/pull/47542) `[Perf] unified-memory: Bind the SWA tail's new pages without a host sync in alloc_extend_swa_tail` | infra,perf | main | - |
| - | [#47543](https://github.com/sgl-project/sglang/pull/47543) `[Fix] hicache: mlock pinned host buffers so page aging never scans them` | bug,infra | main | - |
| - | [#47544](https://github.com/sgl-project/sglang/pull/47544) `[Refactor] disaggregation: Commit the PD handoff token through the shared per-token commit` | infra,quant | main | - |
| - | [#47545](https://github.com/sgl-project/sglang/pull/47545) `[Fix] request_logger: Redact client watermark keys in request logs when watermarking is off` | bug,infra | main | - |
| - | [#47546](https://github.com/sgl-project/sglang/pull/47546) `[Fix] tokenizer_manager: Do not dispatch a request whose abort was already sent` | bug,infra | main | - |
| - | [#47549](https://github.com/sgl-project/sglang/pull/47549) `[CI] chore: add CI permissions and diffusion CODEOWNERS for JackZeng0208` | infra,perf | main | - |
| - | [#47550](https://github.com/sgl-project/sglang/pull/47550) `[Perf] model_executor: Write small forward metadata with fill kernels behind SGLANG_ENABLE_MLP_SYNC_METADATA_F` | infra,perf | main | - |
| - | [#47551](https://github.com/sgl-project/sglang/pull/47551) `[CI] tests: Rendezvous the tile-sharding gloo test through a file store` | infra,perf | main | - |
| - | [#47552](https://github.com/sgl-project/sglang/pull/47552) `[Perf] R3: Keep the routed-expert host cache only on the output rank (1/3)` | infra,perf | main | - |
| - | [#47553](https://github.com/sgl-project/sglang/pull/47553) `[Perf] R3: Skip routed-expert capture on ranks that send no rows (2/3)` | infra,perf | main | - |
| - | [#47556](https://github.com/sgl-project/sglang/pull/47556) `[Test] rust-server: Drop request-fake members the output streamer no longer reads` |  | main | - |
| - | [#47557](https://github.com/sgl-project/sglang/pull/47557) `[Fix] hicache: Withhold only protected bytes from page-cache credit` | bug,infra,perf | main | - |
| - | [#47560](https://github.com/sgl-project/sglang/pull/47560) `[Doc] cookbook: Add Qwen3.8-Flash-Next B300 NVFP4 AgentX recipes` | quant | main | - |
| - | [#47563](https://github.com/sgl-project/sglang/pull/47563) `[CI] health: Retry transient GitHub API failures` | infra | main | - |
| - | [#47565](https://github.com/sgl-project/sglang/pull/47565) `[Perf] diffusion: Pipeline Ulysses attention over head groups down to three waves` | infra,perf | main | - |
| - | [#47566](https://github.com/sgl-project/sglang/pull/47566) `[Perf] minimax-h3: Skip attention for the packing's alignment rows in the Ulysses pipeline` | infra,perf | main | - |
| - | [#47567](https://github.com/sgl-project/sglang/pull/47567) `[Perf] [ROCM] diffusion: Pipeline MiniMax-H3's Ulysses exchange over head groups on RCCL` | bug,infra,perf,rocm | main | - |
| - | [#47568](https://github.com/sgl-project/sglang/pull/47568) `[Perf] [ROCM] diffusion: Encode the MP4 while the VAE decodes on ROCm too` | infra,perf,rocm | main | - |
| - | [#47569](https://github.com/sgl-project/sglang/pull/47569) `[Perf] [ROCM] diffusion: Bit-exact fast QK RMSNorm and fused RoPE for MiniMax-H3` | infra,perf,rocm | main | - |
| - | [#47570](https://github.com/sgl-project/sglang/pull/47570) `[Perf] [ROCM] diffusion: Skip dead math-SDPA work in the MiniMax-H3 VAE decoder on gfx950` | infra,perf,rocm | main | - |
| - | [#47571](https://github.com/sgl-project/sglang/pull/47571) `[Fix] diffusion: Server warmup reaches every data-parallel replica` | bug,infra,perf | main | - |
| - | [#47574](https://github.com/sgl-project/sglang/pull/47574) `[Feat] [NPU] eplb: Enable dynamic expert load balancing on Ascend` | infra | main | - |
| - | [#47577](https://github.com/sgl-project/sglang/pull/47577) `[Fix] megamoe: Allocate the symmetric buffers before KV cache sizing` | bug,infra,perf | main | - |
| - | [#47582](https://github.com/sgl-project/sglang/pull/47582) `[Fix] diffusion: LTX-2.5 two-stage defaults to its 1920x1088 canvas` | bug,infra,perf | main | - |
| - | [#47583](https://github.com/sgl-project/sglang/pull/47583) `[Fix] diffusion: MiniMax-H3 warms up at the short edge --warmup-resolutions names` | bug,infra,perf | main | - |
| - | [#47586](https://github.com/sgl-project/sglang/pull/47586) `[Perf] diffusion: keep GQA and MOSS-Image attention on cuDNN SDPA on Blackwell` | infra,nvidia,perf | main | - |
| - | [#47587](https://github.com/sgl-project/sglang/pull/47587) `[Doc] diffusion: Set measured cookbook defaults for MiniMax-H3, FastH3 Omni, MOSS-Image and Qwen-Image-2.1` | infra,perf | main | - |
| - | [#47592](https://github.com/sgl-project/sglang/pull/47592) `[CI] ci: Preload `sglang.test.test_utils` in CPU fork workers` | infra | main | - |
| - | [#47598](https://github.com/sgl-project/sglang/issues/47598) `[Bug] rust-server: attention-DP listeners on one CPU mask pin their frontends to the same cores` | infra | ? | - |
| - | [#47599](https://github.com/sgl-project/sglang/pull/47599) `[Fix] rust-server: Give each attention-DP listener its own frontend cores` | bug,infra | main | - |
| - | [#47601](https://github.com/sgl-project/sglang/pull/47601) `[Test] model_loader: Cover unindexed Mistral shard filtering` | infra | main | - |
| - | [#47602](https://github.com/sgl-project/sglang/issues/47602) `[Test] Cover unindexed Mistral safetensors filtering` |  | ? | - |
| - | [#47603](https://github.com/sgl-project/sglang/pull/47603) `[CI] test: Drop tests that never run in CI` | infra,perf | main | - |
| - | [#47605](https://github.com/sgl-project/sglang/pull/47605) `[Feat] diffusion: LRU eviction for LoRA merge cache` | infra,perf | main | - |
| - | [#47611](https://github.com/sgl-project/sglang/pull/47611) `[Test] [Ascend] npu: Add GLM-5.2 2P2D gpqa cases and unify evalscope retry loop` | infra | main | - |
| - | [#47612](https://github.com/sgl-project/sglang/pull/47612) `[MiniMax-M3] Keep the fused q/k/v + index GEMM writable by online weight updates` | perf | sglang-miles | - |
| - | [#47613](https://github.com/sgl-project/sglang/issues/47613) `[Bug] PP disaggregated decode produces garbage (runs of token 0) when pp_async_batch_depth > pp_size / 2` | risk | ? | - |
| - | [#47614](https://github.com/sgl-project/sglang/pull/47614) `[Fix] PP: record received proxy tensors on the forward stream` | bug,infra | main | - |
| - | [#47615](https://github.com/sgl-project/sglang/pull/47615) `[Doc] [AMD] cookbook: Add GLM-5.2 MI355X AgentX recipe` | rocm | main | - |
| - | [#47619](https://github.com/sgl-project/sglang/pull/47619) `[CI] ci: Re-tier CUDA tests across base, extra, nightly, and weekly by importance` | infra,nvidia,perf,quant | main | - |
| - | [#47623](https://github.com/sgl-project/sglang/pull/47623) `[Doc] cookbook: Update MiniMax-M3.1-Flash AgentX launches` |  | main | - |
| - | [#47625](https://github.com/sgl-project/sglang/pull/47625) `[CI] diffusion: Fix image preprocessing test dependency environment` | bug,infra,perf | main | - |
| - | [#47630](https://github.com/sgl-project/sglang/pull/47630) `[Fix] hicache: Set host_only_checkpoint in the sidecar restore test` | bug,infra | main | - |
| - | [#47632](https://github.com/sgl-project/sglang/pull/47632) `[Perf] [AMD] attention: Forward decode graph variants through wrapper backends` | infra,perf,rocm | main | - |
| - | [#47638](https://github.com/sgl-project/sglang/pull/47638) `[Fix] disaggregation: Send aux_item_lens next to aux_ptrs in PD registration` | bug | main | - |
| - | [#47641](https://github.com/sgl-project/sglang/pull/47641) `[Perf] [NVIDIA] moe: One-warp-per-token CUDA MoE router for sigmoid, sqrtsoftplus and softmax routing` | infra,nvidia,perf,quant | main | - |
| - | [#47643](https://github.com/sgl-project/sglang/pull/47643) `[Perf] [NVIDIA] mega_moe: Count EPLB load in-kernel` | nvidia,perf | main | - |
| - | [#47646](https://github.com/sgl-project/sglang/pull/47646) `[Fix] kernels/jit: Correct the PDLTriggerSecondary comment on what griddepcontrol.wait covers` | bug,perf | main | - |
| - | [#47651](https://github.com/sgl-project/sglang/pull/47651) `[Perf] kda: Batch strided FlashInfer prefill input copies` | infra,nvidia,perf | main | - |
| - | [#47652](https://github.com/sgl-project/sglang/pull/47652) `[Fix] disaggregation: Ignore a late STAGING_REQ for an already-scattered staging chunk` | bug | main | - |
| - | [#47653](https://github.com/sgl-project/sglang/pull/47653) `[Perf] kimi-k3: Seed a validated FlashInfer prefill MoE tactic` | infra,nvidia,perf | main | - |
| - | [#47662](https://github.com/sgl-project/sglang/pull/47662) `[Fix] reasoning: Reject reasoning_effort outside the enum for M3` | bug | main | - |
| - | [#47670](https://github.com/sgl-project/sglang/pull/47670) `[Fix] mem_cache: Keep K/V in separate allocations under torch.compile` | bug,infra | main | - |
| - | [#47675](https://github.com/sgl-project/sglang/pull/47675) `[Refactor] memory-pool: Build MiniMax K-only index host pools from buffer info` | infra,rocm | main | - |
| - | [#47676](https://github.com/sgl-project/sglang/pull/47676) `[Perf] [NVIDIA] dsv4: Route padded decode replays through the metadata glue graph` | infra,nvidia,perf | main | - |
| - | [#47678](https://github.com/sgl-project/sglang/pull/47678) `[Perf] [NVIDIA] dflash: Fill decode-prep length buffers in bulk` | nvidia,perf | main | - |
| - | [#47680](https://github.com/sgl-project/sglang/pull/47680) `[Fix] mem_cache: Skip Mamba checkpoint donation when slots are exhausted` | bug,infra,perf | main | - |
| - | [#47683](https://github.com/sgl-project/sglang/pull/47683) `[Perf] [NVIDIA] gemm: Tiny GEMM as SIMT + mma.sync templates with batch-size dispatch` | infra,nvidia,perf | main | - |
| - | [#47684](https://github.com/sgl-project/sglang/pull/47684) `[Perf] attention: Round the DeepSeek-V4.1 dense indexer logits tiles to whole SM waves` | infra,perf | main | - |
| - | [#47686](https://github.com/sgl-project/sglang/pull/47686) `[Perf] diffusion: Nomas camera attention reads each frame's value directly when camera_chunk_size is 1` | infra,perf | main | - |
| - | [#47687](https://github.com/sgl-project/sglang/pull/47687) `[CI] moe: Give the NVFP4 non-gated Marlin MoE test bf16-sized headroom` | infra,quant | main | - |
| - | [#47691](https://github.com/sgl-project/sglang/pull/47691) `[Fix] rust-server: Validate gathered listener ranks and address families` | bug,infra | main | - |
| - | [#47699](https://github.com/sgl-project/sglang/pull/47699) `[Doc] cookbook: Add MiniMax-M3.1-Flash GB300 PD AgentX points` | nvidia | main | - |
| - | [#47704](https://github.com/sgl-project/sglang/pull/47704) `[Fix] disaggregation: Match the whole bootstrap address when evicting a dead prefill's connections` | bug | main | - |
| - | [#47705](https://github.com/sgl-project/sglang/pull/47705) `[Refactor] memory-pool: Rename index key format to layout` | infra,rocm | main | - |
| - | [#47710](https://github.com/sgl-project/sglang/issues/47710) `[Bug] SM120: fused-A GEMM eligibility accepts K % 256 but the auto-selected CuTe DSL kernel asserts K % 1024 (` | bug,nvidia,perf | ? | - |
| - | [#47712](https://github.com/sgl-project/sglang/pull/47712) `[Fix] [NVIDIA] fused-a-gemm: Check the selected backend's K alignment before taking the fused path` | bug,infra,nvidia,perf | main | - |
| - | [#47714](https://github.com/sgl-project/sglang/pull/47714) `[Refactor] memory-pool: Build QSA indexer host pools as hybrid sidecars` | infra,rocm | main | - |
| - | [#47716](https://github.com/sgl-project/sglang/pull/47716) `[Fix] scheduler: Decide early result processing before scheduling the next batch` | bug,infra | main | - |
| - | [#47723](https://github.com/sgl-project/sglang/pull/47723) `[Doc] skills: Update the CI skills for the tier layout and current pipeline` | infra | main | - |
| - | [#47724](https://github.com/sgl-project/sglang/pull/47724) `[Perf] diffusion: qknorm_complex_rope keeps two Q/K rows in flight per half-warp` | infra,perf | main | - |
| - | [#47725](https://github.com/sgl-project/sglang/pull/47725) `[Fix] disaggregation: Initialize the bootstrap server loop and runner before the server thread starts` | bug | main | - |
| - | [#47727](https://github.com/sgl-project/sglang/pull/47727) `[Fix] disaggregation: Call finalize_bootstrap outside the assert statement` | bug | main | - |
| - | [#47728](https://github.com/sgl-project/sglang/pull/47728) `[Fix] dspark: Stage each request's own SWA ring slot at batch size 1` | bug,perf | main | - |
| - | [#47731](https://github.com/sgl-project/sglang/pull/47731) `[Perf] imports: Keep light modules off HF patches, model configs, and the scheduler` | infra,nvidia,perf,rocm | main | - |
| - | [#47732](https://github.com/sgl-project/sglang/pull/47732) `[Fix] kv_events: Offset ipc endpoints per DP rank and finish shutdown when the queue is full` | bug | main | - |
| - | [#47735](https://github.com/sgl-project/sglang/pull/47735) `[Refactor] unlimited-ocr: Reduce scheduler coupling` | infra,perf | main | - |
| - | [#47736](https://github.com/sgl-project/sglang/pull/47736) `[Fix] tests: Initialize DCP replay backend capability` | bug,infra | main | - |
| - | [#47737](https://github.com/sgl-project/sglang/pull/47737) `[Fix] disaggregation: Use the shared ZMQ context for staging prefetch sockets` | bug | main | - |
| - | [#47742](https://github.com/sgl-project/sglang/pull/47742) `[Fix] kimi-k3: Honor initial expert placement in fused routing` | bug,infra,perf | main | - |
| - | [#47743](https://github.com/sgl-project/sglang/pull/47743) `[Perf] mla: Use masked K concatenation for padded head counts` | infra,perf | main | - |
| - | [#47744](https://github.com/sgl-project/sglang/pull/47744) `[Fix] linear: Keep replicated outputs out of TP symmetric memory` | bug,infra | main | - |
| - | [#47749](https://github.com/sgl-project/sglang/pull/47749) `[CI] [Intel] ci/xpu: Move remaining XPU CI installs to uv and set SGLANG_IS_IN_CI` | infra,nvidia | main | - |
| - | [#47758](https://github.com/sgl-project/sglang/pull/47758) `[Fix] disagg: Give the decode queue test scheduler a tree_cache` | bug,infra | main | - |
| - | [#47782](https://github.com/sgl-project/sglang/pull/47782) `[Refactor] kernels: Centralize GPU architecture queries in sglang.kernels.arch` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47784](https://github.com/sgl-project/sglang/pull/47784) `[Perf] [NVIDIA] moe: Rewrite moe_finalize_fuse_shared as a JIT kernel with all top-k gathers in flight` | infra,nvidia,perf | main | - |
| - | [#47785](https://github.com/sgl-project/sglang/pull/47785) `[Perf] [NVIDIA] qwen3: Fuse prefill QK norm and RoPE with contiguous Q` | infra,nvidia,perf | main | - |
| - | [#47789](https://github.com/sgl-project/sglang/pull/47789) `[CI] nightly: Disable the MiniMax-M3.1-Flash H200 test while it times out` | infra,nvidia | main | - |
| - | [#47804](https://github.com/sgl-project/sglang/pull/47804) `[Refactor] environ: Rename the SGLANG_Q35MF_* runtime switches to SGLANG_OPT_* names` | nvidia,perf | main | - |
| - | [#47810](https://github.com/sgl-project/sglang/pull/47810) `[Feat] deepseek-recipe: Expose convert and encode_conversation on DeepSeekRecipe` | infra | main | - |
| - | [#47815](https://github.com/sgl-project/sglang/pull/47815) `[Perf] attention: Use live KV lengths for SM12x FA4 graph replay` | infra,nvidia,perf | main | - |
| - | [#47821](https://github.com/sgl-project/sglang/pull/47821) `[Fix] [NPU] MOE: Skip MoE padded-row kernel launches for empty tensors in case of crashing on NPU` | bug,infra,perf | main | - |
| - | [#47823](https://github.com/sgl-project/sglang/pull/47823) `[CI] [NPU] workflow: Gate pr-test-npu-finish on pr-gate and drop nightly PR trigger` | infra | main | - |
| - | [#47825](https://github.com/sgl-project/sglang/pull/47825) `[CI] disaggregation: Fail a PD test launch fast when an H20 runner is short of GPUs` | infra | main | - |
| - | [#47829](https://github.com/sgl-project/sglang/pull/47829) `[Fix] test: Stub _confidence_budget_prepare in the scheduler running-reqs test` | bug,infra | main | - |
| - | [#47835](https://github.com/sgl-project/sglang/pull/47835) `[Test] diffusion: align warmup and LoRA fixtures with runtime contracts` | infra,perf | main | - |
| - | [#47836](https://github.com/sgl-project/sglang/issues/47836) `[CI] test_linear_parallel_groups.py fails on main: replicated rows now skip TP symmetric memory` | infra | ? | - |
| - | [#47837](https://github.com/sgl-project/sglang/pull/47837) `[Test] linear: Expect replicated rows to skip TP symmetric memory` |  | main | - |
| - | [#47844](https://github.com/sgl-project/sglang/pull/47844) `[Doc] [AMD] cookbook: Verify MiniMax-M3.1-Flash High-Throughput on MI355X` | perf,rocm | main | - |
| - | [#47852](https://github.com/sgl-project/sglang/pull/47852) `[Perf] diffusion: Fuse MiniMax-H3 encoder SiLU and padding` | infra,perf | main | - |
| - | [#47853](https://github.com/sgl-project/sglang/pull/47853) `[Feat] halops: Add HALOps as an opt-in MXFP8 GEMM backend for Blackwell and support mxfp8 megamoe` | infra,nvidia,quant | main | - |
| - | [#47858](https://github.com/sgl-project/sglang/pull/47858) `[Fix] graph: Restore XPU logger and Inkling backend mock dtype` | bug,nvidia | main | - |
| - | [#47860](https://github.com/sgl-project/sglang/pull/47860) `[Fix] spec: Give the mocked draft decode backend a cache_loc_dtype in the inkling test` | bug,infra | main | - |
| - | [#47861](https://github.com/sgl-project/sglang/pull/47861) `[Doc] cookbook: add Unlimited-OCR-2 NVIDIA platform recipes` | nvidia | main | - |
| - | [#47866](https://github.com/sgl-project/sglang/pull/47866) `[Fix] KDA: Compile the CuTe DSL decode kernel for the caller's dt_bias dtype` | bug,infra,perf | main | - |
| - | [#47875](https://github.com/sgl-project/sglang/pull/47875) `[Chore] owner: update` |  | main | - |
| - | [#47892](https://github.com/sgl-project/sglang/pull/47892) `[Fix] quantization: Store --quantization-param-path KV scales the way checkpoint KV scales are stored` | bug,infra,quant | main | - |
| - | [#47894](https://github.com/sgl-project/sglang/pull/47894) `[Chore] [NVIDIA] deps: Bump sgl-deep-gemm to 0.2.5.post3` | infra,nvidia | main | - |
| - | [#47898](https://github.com/sgl-project/sglang/pull/47898) `[Perf] [NVIDIA] fused-a-gemm: Relax the CuTe DSL kernel's K alignment from 1024 to 256` | infra,nvidia,perf | main | - |
| - | [#47900](https://github.com/sgl-project/sglang/pull/47900) `[Doc] cookbook: Align navigation groups with model publishers` |  | main | - |
| - | [#47902](https://github.com/sgl-project/sglang/pull/47902) `[Test] [NPU] DeepSeek_v4_pro: Add 16p mix in128k out1k performance and gpqa testcase, DeepSeek_v4_flash:Enable` | infra,perf | main | - |
| - | [#47907](https://github.com/sgl-project/sglang/pull/47907) `[Perf] diffusion: Avoid upscaling native H3 references by default` | infra,perf | main | - |
| - | [#47915](https://github.com/sgl-project/sglang/pull/47915) `[Fix] kernels: Port rmsnorm and softmax bench off the removed get_jit_cuda_arch` | bug,infra,perf | main | - |
| - | [#47924](https://github.com/sgl-project/sglang/pull/47924) `[Fix] [NPU] attention: Pack valid MLA prefix tokens for mixed batches` | bug,infra | main | - |
| - | [#47926](https://github.com/sgl-project/sglang/pull/47926) `[Fix] [AMD] qwen3: Guard dtype alignment when fused decode omits KV` | bug,perf,rocm | sglang-miles | - |
| - | [#47928](https://github.com/sgl-project/sglang/pull/47928) `[Refactor] memory-pool: Assemble HiCache host pools from buffer info` | infra,nvidia,rocm | main | - |
| - | [#47929](https://github.com/sgl-project/sglang/pull/47929) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main c5e8b9b3 and revert #47560` |  | main | - |
| - | [#47935](https://github.com/sgl-project/sglang/pull/47935) `[Perf] dsv41: Keep MXFP4 Engram tables packed and decode E2M1 in the gather` | infra,perf,quant | main | - |
| - | [#47940](https://github.com/sgl-project/sglang/pull/47940) `[Chore] [AMD] rccl: pin rccl to d2e0de35` | infra,rocm | main | - |
| - | [#47944](https://github.com/sgl-project/sglang/pull/47944) `[Fix] attention: Migrate FLA Triton kernels off tl.make_block_ptr` | bug,infra,perf,rocm | main | - |
| - | [#47949](https://github.com/sgl-project/sglang/pull/47949) `[Perf] [NVIDIA] dsv41: Split small-batch decode mHC post-combine-norm rows over a CTA cluster` | nvidia,perf | main | - |
| - | [#47951](https://github.com/sgl-project/sglang/pull/47951) `[Doc] [AMD] cookbook: Qwen3.8-Flash-Next MI355X, add the monokernel command for concurrency 1-8` | rocm | main | - |
| - | [#47954](https://github.com/sgl-project/sglang/pull/47954) `[Refactor] rust-server: Make the advertised listener host an overridable classmethod` |  | main | - |
| - | [#47955](https://github.com/sgl-project/sglang/pull/47955) `[Perf] srt: Record per request whether an extend row completes its prompt` | infra,perf | main | - |
| - | [#47957](https://github.com/sgl-project/sglang/pull/47957) `[CI] quant: Lower the Mixtral AWQ MMLU threshold to 0.62 to clear its run-to-run spread` | infra,quant | main | - |
| - | [#47960](https://github.com/sgl-project/sglang/pull/47960) `[Perf] [NVIDIA] dsv4/topk_v2: Exactness modes (fast / exact / deterministic) and an exact cluster path` | infra,nvidia,perf | main | - |
| - | [#47962](https://github.com/sgl-project/sglang/pull/47962) `[CI] diffusion: Refresh the LTX-2 two-stage runtime VRAM baseline for the cached prompt K/V` | infra,perf | main | - |
| - | [#47963](https://github.com/sgl-project/sglang/pull/47963) `[Fix] rust-server: Park the idle scheduler on its request ring only with --sleep-on-idle` | bug,infra | main | - |
| - | [#47969](https://github.com/sgl-project/sglang/pull/47969) `[CI] [AMD] pr-test: Run the MI35x 1-GPU stage after MI300 stage-b; move test_flydsl_v4nm_decode to nightly` | infra,rocm | main | - |
| - | [#47971](https://github.com/sgl-project/sglang/pull/47971) `[CI] [AMD] diffusion/minimax-h3: Skip the group-attend contract test on ROCm` | infra,perf,rocm | main | - |
| - | [#47976](https://github.com/sgl-project/sglang/pull/47976) `[Perf] [NVIDIA] moe: Localize DeepGEMM Mega MoE weights across locality domains` | nvidia,perf | main | - |
| - | [#47989](https://github.com/sgl-project/sglang/pull/47989) `[CI] test: Relax bs=1 perf limits for CI hosts with slower CPUs` | infra,perf | main | - |
| - | [#47990](https://github.com/sgl-project/sglang/pull/47990) `[Refactor] imports: Import names from where they are defined; remove re-export shims` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47992](https://github.com/sgl-project/sglang/pull/47992) `[CI] lint: Reject importing a name through a module that only re-imports it` | infra | main | - |
| - | [#47993](https://github.com/sgl-project/sglang/pull/47993) `[Perf] [NVIDIA] qwen3: Reuse the table QK-norm/RoPE kernel for MRoPE decode` | nvidia,perf | main | - |
| - | [#47994](https://github.com/sgl-project/sglang/pull/47994) `[Fix] moe: Revert the JIT rewrite of `moe_finalize_fuse_shared` (#47784)` | bug,perf | main | - |
| - | [#47997](https://github.com/sgl-project/sglang/pull/47997) `[Doc] blogs: Sync LMSYS SGLang blog cards` |  | main | - |
| - | [#48001](https://github.com/sgl-project/sglang/pull/48001) `[Fix] spec: Write routed DFLASH and DSPARK context KV into the draft's own rows` | bug | main | - |
| - | [#48002](https://github.com/sgl-project/sglang/pull/48002) `[Fix] server_args: Refuse a sharded-padded CP KV layout with unified memory` | bug,perf | main | - |
| - | [#48003](https://github.com/sgl-project/sglang/pull/48003) `[Refactor] hicache: Move shared host backing and build unified host pools from layout views` | infra | main | - |
| - | [#48004](https://github.com/sgl-project/sglang/pull/48004) `[Refactor] mem_cache: Own state and fixed payloads in the KV storage plan and size from them` | perf | main | - |
| - | [#48005](https://github.com/sgl-project/sglang/pull/48005) `[Refactor] mem_cache: Plan draft KV bands by retention lifetime` | infra,perf | main | - |
| - | [#48028](https://github.com/sgl-project/sglang/pull/48028) `[Fix] batch-invariant: restore torch.bmm when set_batch_invariant_mode exits` | bug,infra | main | - |
| - | [#48032](https://github.com/sgl-project/sglang/pull/48032) `[CI] [AMD] nightly-disagg: Run MI355X disagg nightly at 04:00 UTC (12:00 UTC+8)` | infra,rocm | main | - |
| - | [#48037](https://github.com/sgl-project/sglang/pull/48037) `[Perf] disaggregation: Cache host-staged decode admission accounting across a transfer pass` | infra,perf | main | - |
| - | [#48039](https://github.com/sgl-project/sglang/issues/48039) `[Bug] 'HashTopK' object has no attribute 'topk_config' during breakable prefill CUDA graph capture` | nvidia | ? | - |
| - | [#48041](https://github.com/sgl-project/sglang/pull/48041) `[Fix] moe: Skip hash layers before topk_config in prefill routing paths` | bug,infra | main | - |
| - | [#48051](https://github.com/sgl-project/sglang/pull/48051) `[Doc] qwen: Use TRT-LLM MHA for the B300 Qwen3-VL-4B recipe` |  | main | - |
| - | [#48053](https://github.com/sgl-project/sglang/pull/48053) `[CI] runners: Move H100 tests with no H100-specific dependency to 1-gpu-small` | infra,nvidia,perf,quant | main | - |
| - | [#48054](https://github.com/sgl-project/sglang/pull/48054) `Revert "[Feat] diffusion/model: add the BRIA Fibo 2.0 transformer and text conditioning (#46580)"` | perf | main | - |
| - | [#48055](https://github.com/sgl-project/sglang/pull/48055) `Revert "[Perf] kimi-k3: Seed a validated FlashInfer prefill MoE tactic (#47653)"` | nvidia,perf | main | - |
| - | [#48061](https://github.com/sgl-project/sglang/pull/48061) `[Fix] batch-invariant: restore the dispatcher state when a scope exits` | bug | main | - |
| - | [#48066](https://github.com/sgl-project/sglang/pull/48066) `[Feat] sgl-router: Add an opt-in fips feature backed by aws-lc-rs` | infra | main | - |
| - | [#48067](https://github.com/sgl-project/sglang/pull/48067) `[CI] [AMD] miles: Pass CI and the SGLang source path to nightly suites` | infra,rocm | main | - |
| - | [#48070](https://github.com/sgl-project/sglang/pull/48070) `[Doc] cookbook: Add MiniMax-M3.1-Flash GB300 MonoKernel and DEP16 AgentX points` | nvidia | main | - |
| - | [#48075](https://github.com/sgl-project/sglang/pull/48075) `[Perf] Hunyuan3D: Reduce redundant QEM quadric accumulation` | infra,perf | main | - |
| - | [#48082](https://github.com/sgl-project/sglang/pull/48082) `[Perf] paged-experts: load experts without a staging copy` | infra,perf | main | - |
| - | [#48087](https://github.com/sgl-project/sglang/pull/48087) `[Perf] imports: Keep the detokenizer off TokenizerManager and the tokenizer off schedule_batch` | infra,perf | main | - |
| - | [#48092](https://github.com/sgl-project/sglang/pull/48092) `[Fix] test: Import ResolvedView from model_override_base in test_model_overrides` | bug,infra | main | - |
| - | [#48099](https://github.com/sgl-project/sglang/pull/48099) `[Perf] [NVIDIA] moe: Release localized Mega MoE originals so KV capacity matches non-localized` | infra,nvidia,perf | main | - |
| - | [#48104](https://github.com/sgl-project/sglang/pull/48104) `[Doc] [XPU] Cookbook: Update the XPU Docker version to 0.5.23` | infra,nvidia | main | - |
| - | [#48109](https://github.com/sgl-project/sglang/pull/48109) `[Fix] moe: Match padded-row indices to token-count dtype` | bug,infra | main | - |
| - | [#48111](https://github.com/sgl-project/sglang/pull/48111) `[Perf] spec: Default `SGLANG_SPEC_TP_SYNC` to `init`` | infra,perf | main | - |
| - | [#48119](https://github.com/sgl-project/sglang/pull/48119) `[Refactor] tokenizer: Fold `TokenizerWorker` into `TokenizerManager`` | infra | main | - |
| - | [#48121](https://github.com/sgl-project/sglang/pull/48121) `[Test] mooncake: bind metadata server to loopback in tests` |  | main | - |
| - | [#48123](https://github.com/sgl-project/sglang/pull/48123) `[Feat] RL: Store output store replay fields as layer blocks at layer splits` |  | sglang-miles | - |
| - | [#48125](https://github.com/sgl-project/sglang/pull/48125) `[Feat] unified_cache: Support MiniMax-M3.1 in the direct external linker` | infra | main | - |
| - | [#48131](https://github.com/sgl-project/sglang/pull/48131) `[CI] [AMD] nightly-disagg: Keep all MI355X CI settings in the repo and clean up after failed jobs` | infra,rocm | main | - |
| - | [#48134](https://github.com/sgl-project/sglang/pull/48134) `[CI] [AMD] ci: Follow #47619 on AMD and fix two never-run registrations` | bug,infra,perf,rocm | main | - |
| - | [#48141](https://github.com/sgl-project/sglang/issues/48141) `[Bug] MiniMax H3 cookbook silently downscales 1440p video requests to 768p` | risk | ? | - |
| - | [#48160](https://github.com/sgl-project/sglang/pull/48160) `[Test] [NPU] deepseek_v4: Replace 8K perf case with 128K 1P1D case and add L2 host hit-rate checks` | perf | main | - |
| - | [#48166](https://github.com/sgl-project/sglang/pull/48166) `[Perf] [NVIDIA] moe: Add L4 Triton fused MoE configs for Qwen3-30B-A3B` | infra,nvidia,perf,rocm | main | - |
| - | [#48174](https://github.com/sgl-project/sglang/pull/48174) `[Perf] [NVIDIA] moe: Re-land the JIT moe_finalize_fuse_shared with the shared row read after the PDL wait` | infra,nvidia,perf | main | - |
| - | [#48176](https://github.com/sgl-project/sglang/pull/48176) `[CI] rerun-test: Retry diffusion reruns like the multimodal-gen CI` | infra,perf | main | - |
| - | [#48192](https://github.com/sgl-project/sglang/pull/48192) `[Chore] mooncake: bump mooncake version to 0.3.14` | infra | main | - |
| - | [#48221](https://github.com/sgl-project/sglang/issues/48221) `[CI] Arm64: test_moe.py fails with missing sgl_kernel.fused_experts_cpu on main` | infra,perf | ? | - |
| - | [#48223](https://github.com/sgl-project/sglang/pull/48223) `[Fix] test: Import sgl_kernel in the Arm64 MoE test` | bug | main | - |
| - | [#48229](https://github.com/sgl-project/sglang/pull/48229) `[Perf] dsv4: Expand the low-ratio indexer page table in one Triton kernel` | perf,rocm | main | - |
| - | [#48230](https://github.com/sgl-project/sglang/issues/48230) `[Bug] PD + Mooncake: different DSA backends on prefill and decode silently corrupt the decode KV ("Requested a` | risk | ? | - |
| - | [#48231](https://github.com/sgl-project/sglang/pull/48231) `[Fix] disaggregation: Reject a decode peer whose KV page stride differs at Mooncake registration` | bug,infra | main | - |
| - | [#48243](https://github.com/sgl-project/sglang/pull/48243) `[Perf] dsv4: dequantize several KV tokens per program in the V4.1 paged dequant` | perf,quant | main | - |
| - | [#48244](https://github.com/sgl-project/sglang/pull/48244) `[Fix] dspark: Expand [N, H] staged embeds in the DeepSeek-V4 DSpark draft forward` | bug | main | - |
| - | [#48245](https://github.com/sgl-project/sglang/pull/48245) `[Perf] dsv4: four chunks per thread in mega MoE pre-dispatch for prefill-sized batches` | perf | main | - |
| - | [#48246](https://github.com/sgl-project/sglang/pull/48246) `[Perf] deep_select: use the 3-CTA tier for non-paged bf16 top-512 too` | perf | main | - |
| - | [#48256](https://github.com/sgl-project/sglang/pull/48256) `[CI] diffusion: Add the B200 baseline override for b200-cirrascale2` | infra,nvidia,perf | main | - |
| - | [#48264](https://github.com/sgl-project/sglang/pull/48264) `[Feat] beam: support LoRA for BF16 and FP8` | infra,quant | main | - |
| - | [#48265](https://github.com/sgl-project/sglang/pull/48265) `[CI] [AMD] miles: Split the MI30x 4-GPU nightly into two jobs` | infra,rocm | main | - |
| - | [#48266](https://github.com/sgl-project/sglang/pull/48266) `[Chore] [NVIDIA] deep_select: List SM107 as supported` | nvidia,perf | main | - |
| - | [#48277](https://github.com/sgl-project/sglang/pull/48277) `[Doc] cookbook: Add TPU v7 to Muse Spark Open` |  | main | - |
| - | [#48278](https://github.com/sgl-project/sglang/pull/48278) `[Test] dspark: Register the simulated-bonus test for CUDA CI` | infra,nvidia | main | - |
| - | [#48279](https://github.com/sgl-project/sglang/pull/48279) `[Chore] [NVIDIA] docker: Move cu134 container to torch 2.15 official release` | infra,nvidia | main | - |
| - | [#48282](https://github.com/sgl-project/sglang/pull/48282) `[Fix] test: Import sgl_kernel in the Xeon thread-binding test` | bug,infra | main | - |
| - | [#48283](https://github.com/sgl-project/sglang/pull/48283) `[Refactor] scheduler: Retire every queued abort through one RequestRetirer entry` | infra | main | - |
| - | [#48284](https://github.com/sgl-project/sglang/pull/48284) `[Fix] model_loader: Use the local CUDA device in the fastsafetensors loader` | bug,infra,nvidia | main | - |
| - | [#48290](https://github.com/sgl-project/sglang/pull/48290) `[Test] [NPU] kimi_k3: run the decode perf case via the aisbench prefix mode` | perf | main | - |
| - | [#48292](https://github.com/sgl-project/sglang/pull/48292) `[Fix] disaggregation: Reject the KV checksum with DeepSeek-V4 and on a HiSparse decode` | bug | main | - |
| - | [#48298](https://github.com/sgl-project/sglang/pull/48298) `[Fix] spec: Draw `SGLANG_SIMULATE_ACC_LEN` once per step from the server seed` | bug,infra,perf | main | - |
| - | [#48301](https://github.com/sgl-project/sglang/pull/48301) `[Test] kv_canary: Drop min_p from the canary-info e2e sampling params` |  | main | - |
| - | [#48323](https://github.com/sgl-project/sglang/pull/48323) `[CI] [AMD] miles: Skip MI30x tests whose kernels exceed gfx942 LDS` | infra,perf,rocm | main | - |
| - | [#48325](https://github.com/sgl-project/sglang/pull/48325) `[Feat] docker: Install AWS EFA in the main image; drop the EFA image variant` | infra | main | - |
| - | [#48327](https://github.com/sgl-project/sglang/pull/48327) `[Refactor] scheduler: Release in-step finishes through the request retirer` | infra | main | - |
| - | [#48328](https://github.com/sgl-project/sglang/pull/48328) `[Fix] mamba: Give a lazy boundary snapshot its own slot instead of overwriting the keep slot` | bug,infra,perf | main | - |
| - | [#48339](https://github.com/sgl-project/sglang/pull/48339) `[CI] [NPU] nightly-4-npu-a3: Rebalance partitions, bound retries, retire GLM-5.2 16p accuracy` | infra,risk | main | - |
| - | [#48343](https://github.com/sgl-project/sglang/pull/48343) `[Fix] openai: Tool schema ids, explicit include_usage=false, and Kimi-K3 prompt fidelity` | bug,infra | main | - |
| - | [#48344](https://github.com/sgl-project/sglang/issues/48344) `[RFC] mem_cache: Cross-branch KV page splicing and cursor fork/rewind for hybrid models (Qwen3.5 / GDN)` |  | ? | - |
| - | [#48352](https://github.com/sgl-project/sglang/pull/48352) `[Chore] [NPU] deps: Bump kernel and hybrid memory packages` | infra,perf | main | - |
| - | [#48357](https://github.com/sgl-project/sglang/pull/48357) `[Fix] kimi-k3: Resolve strict tool $refs into the root parameters schema` | bug,infra | main | - |
| - | [#48366](https://github.com/sgl-project/sglang/pull/48366) `[Refactor] kernels/diffusion/tests: Prune new dead code and make silently skipped tests run` | infra,nvidia,perf,quant,risk,rocm | main | - |
| - | [#48380](https://github.com/sgl-project/sglang/pull/48380) `[Doc] agent-skills: Add JIT kernel performance guide and document more header-library helpers` | infra,perf | main | - |
| - | [#48391](https://github.com/sgl-project/sglang/pull/48391) `[Test] cli: Add cookbook command snapshot and serve direct-launch tests` |  | main | - |
| - | [#48392](https://github.com/sgl-project/sglang/pull/48392) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main 57116fff` |  | main | - |
| - | [#48399](https://github.com/sgl-project/sglang/pull/48399) `[Refactor] env: Dispatch on the GPU architecture instead of env vars that restate it` | infra,perf,quant,rocm | main | - |
| - | [#48401](https://github.com/sgl-project/sglang/pull/48401) `[Test] [Intel] jit: Stub tvm_ffi paths in test_jit_cache when tvm_ffi is absent` | infra | main | - |
| - | [#48413](https://github.com/sgl-project/sglang/pull/48413) `[Doc] cookbook: Add Kimi-K3.1-Pro deployment recipes` |  | main | - |
| - | [#48415](https://github.com/sgl-project/sglang/pull/48415) `[Feat] model: Add basic Kimi-K3.1 support (NV, AMD)` | infra,perf,quant,rocm | main | - |
| - | [#48417](https://github.com/sgl-project/sglang/pull/48417) `[Doc] popular-models: Feature Kimi-K3.1-Pro first` |  | main | - |
| - | [#48421](https://github.com/sgl-project/sglang/pull/48421) `[Fix] HiCache: Reject partial L3 prefetch allocation for hybrid models` | bug,infra,perf | main | - |
| - | [#48424](https://github.com/sgl-project/sglang/pull/48424) `[Perf] deepseek_v4: bump sgl-deep-gemm to 0.2.6, FlashInfer-layout scales from DeepGEMM producers, current MQA` | infra,nvidia,perf,quant | main | - |
| - | [#48429](https://github.com/sgl-project/sglang/pull/48429) `[Doc] cookbook: Run the Kimi-K3.1-Pro MI35x PD Docker commands on the host network with RDMA` | infra | main | - |
| - | [#48432](https://github.com/sgl-project/sglang/pull/48432) `[Doc] [AMD] cookbook: Qwen3.8-Flash-Next MI355X, add the HiCache commands for concurrency 24-80` | rocm | main | - |
| - | [#48433](https://github.com/sgl-project/sglang/pull/48433) `[Feat] weight_update: Let platforms serve weight transports through /plugin_weight_update` | infra | main | - |
| - | [#48435](https://github.com/sgl-project/sglang/pull/48435) `[Doc] kimi-k3.1: Point the cookbook install branch at kimi-k3.1-day-0` |  | main | - |
| - | [#48437](https://github.com/sgl-project/sglang/pull/48437) `[Perf] [AMD] dsa: Split-K HIP sparse MLA for decode/verify` | perf,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48439](https://github.com/sgl-project/sglang/pull/48439) `[Perf] [AMD] dflash: Row-shard the draft's target-hidden fc in prefill chunks` | perf,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48440](https://github.com/sgl-project/sglang/pull/48440) `[Perf] [AMD] moe: Run the small-batch sort + stage-1 quant up to 1024 pairs on Kimi-K3` | perf,quant,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48443](https://github.com/sgl-project/sglang/pull/48443) `[CI] test: Give test_vision_chunked_prefill's llava preprocessing more time` | infra | main | - |
| - | [#48450](https://github.com/sgl-project/sglang/pull/48450) `[Fix] mem_cache: Order lazy unified-pool page reuse after the latest forward` | bug,infra | main | - |
| - | [#48452](https://github.com/sgl-project/sglang/pull/48452) `[Fix] disaggregation: Publish a yielded optimistic prefill's KV under a write-through cache` | bug,infra,perf | main | - |
| - | [#48464](https://github.com/sgl-project/sglang/pull/48464) `[Test] Remove unit tests added in Kimi-K3.1 PR` |  | kimi-k3.1-day-0 | - |
| - | [#48467](https://github.com/sgl-project/sglang/pull/48467) `[Fix] [NVIDIA] deepseek-v4: Pass a caller-owned multi-CTA counter buffer to the trtllm sparse MLA kernel` | bug,nvidia,perf | main | - |
| - | [#48480](https://github.com/sgl-project/sglang/pull/48480) `[Fix] kimi-k3: Make tool_choice required and none grammars end the turn` | bug,infra | main | - |
| - | [#48481](https://github.com/sgl-project/sglang/pull/48481) `[Fix] kimi-k3: Validate message-level tools and let a forced call override JSON response_format` | bug,infra | main | - |
| - | [#48485](https://github.com/sgl-project/sglang/pull/48485) `[Fix] [AMD] mooncake: Bump Mooncake to pick up the HIP IPC sub-allocation fix` | bug,infra,rocm | main | - |
| - | [#48490](https://github.com/sgl-project/sglang/pull/48490) `[Perf] [AMD] kimi-k3: Row-sharded MoE front, o_proj and stream for gfx950 prefill` | perf,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48491](https://github.com/sgl-project/sglang/pull/48491) `[Refactor] scheduler: Release every PD disaggregation exit through RequestRetirer` | infra,perf | main | - |
| - | [#48499](https://github.com/sgl-project/sglang/pull/48499) `[Test] [NPU] deepseek_v4_flash: Update 128K AisBench performance test and AisBench` | infra,perf | main | - |
| - | [#48501](https://github.com/sgl-project/sglang/pull/48501) `[Feat] dsa: Kernel prerequisites for a DCP-sharded indexer` | infra,perf | main | - |
| - | [#48522](https://github.com/sgl-project/sglang/pull/48522) `[Fix] hicache: Stop L3 prefetch at the match key limit` | bug,infra | main | - |
| - | [#48525](https://github.com/sgl-project/sglang/pull/48525) `[Chore] flashmla: bump sgl-flash-mla to 1.0.2` | infra,nvidia | main | - |
| - | [#48535](https://github.com/sgl-project/sglang/pull/48535) `[CI] lint: Import ForwardMode from its defining module in the KV translate test` | infra | main | - |
| - | [#48546](https://github.com/sgl-project/sglang/pull/48546) `[Doc] cookbook: Add ERNIE-5.5-Flash deployment recipes` | infra | main | - |
| - | [#48547](https://github.com/sgl-project/sglang/pull/48547) `[Feat] model: Support ERNIE 5.5 Flash` | infra,perf,quant | main | - |
| - | [#48551](https://github.com/sgl-project/sglang/pull/48551) `[Doc] cookbook: Update Kimi-K3.1-Pro GB300 AgentX launches` | nvidia | main | - |
| - | [#48571](https://github.com/sgl-project/sglang/pull/48571) `[Fix] mamba: Make the lazy full-pool KL test hold across GPUs` | bug,infra,perf | main | - |
| - | [#48573](https://github.com/sgl-project/sglang/pull/48573) `[Chore] [AMD] aiter: promote gfx1250 pin to 07ff5f318` | infra,rocm | main | - |
| - | [#48588](https://github.com/sgl-project/sglang/pull/48588) `[Feat] dsa: Exact multicast top-k merge for DCP decode` | perf | main | - |
| - | [#48603](https://github.com/sgl-project/sglang/issues/48603) `[Bug] EPLB statistics include empty draft records during speculative decoding` |  | ? | - |
| - | [#48604](https://github.com/sgl-project/sglang/pull/48604) `[CI] [NPU] npu: Switch precision test selection to lb-actions/precision-test` | infra,perf | main | - |
| - | [#48606](https://github.com/sgl-project/sglang/pull/48606) `[Refactor] scheduler: Release retracted, paused and chunked-aborted requests through RequestRetirer` | infra | main | - |
| - | [#48614](https://github.com/sgl-project/sglang/pull/48614) `[CI] chore: add CI permissions for QiuMike (weight_cache codeowner)` | infra | main | - |
| - | [#48617](https://github.com/sgl-project/sglang/pull/48617) `[CI] runners: Move base-b H100 tests to 1-gpu-small, extra-a, or nightly` | infra,nvidia | main | - |
| - | [#48619](https://github.com/sgl-project/sglang/pull/48619) `[CI] test: Give TestLlavaServer's llava preprocessing more time` | infra | main | - |
| - | [#48622](https://github.com/sgl-project/sglang/pull/48622) `[Perf] deepseek_v4: call the current DeepGEMM paged MQA API for DSv4.1 decode` | perf | main | - |
| - | [#48634](https://github.com/sgl-project/sglang/pull/48634) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main 2ad2c9f9` |  | main | - |
| - | [#48637](https://github.com/sgl-project/sglang/pull/48637) `Revert "[Feat] docker: Install AWS EFA in the main image; drop the EFA image variant"` | infra | main | - |
| - | [#48640](https://github.com/sgl-project/sglang/pull/48640) `[Test] [NPU] qwen3.6-27b: fail fast on collapsed spec acceptance` |  | main | - |
| - | [#48654](https://github.com/sgl-project/sglang/pull/48654) `[Fix] scheduler: Match arrival prefixes on every PP stage` | bug,infra | main | - |
| - | [#48668](https://github.com/sgl-project/sglang/pull/48668) `[Fix] sgl-router: Keep a worker's cached chain visible when another worker holds its prefix` | bug,infra | main | - |
| - | [#48677](https://github.com/sgl-project/sglang/issues/48677) `[CI] attention/unittests/mla/test_flashinfer.py fails on main: FlashInfer MLA EAGLE draft CUDA-graph outputs m` | infra,nvidia | ? | - |
| - | [#48692](https://github.com/sgl-project/sglang/pull/48692) `[CI] [AMD] spur: Take HF_TOKEN from the runner environment` | infra,rocm | main | - |
| - | [#48693](https://github.com/sgl-project/sglang/pull/48693) `[Fix] hicache: Do not count staged-prefetch deferrals while KV awaits a PD transfer` | bug,infra | main | - |
| - | [#48708](https://github.com/sgl-project/sglang/pull/48708) `[Chore] CODEOWNERS: Update code owners` |  | main | - |
| - | [#48713](https://github.com/sgl-project/sglang/pull/48713) `[Feat] kimi-k3.1: Let shared-expert TP span interleave prefill CP` |  | main | - |
| - | [#48714](https://github.com/sgl-project/sglang/pull/48714) `[Feat] kimi-k3.1: Opt-in trtllm DSA backend` |  | main | - |
| - | [#48718](https://github.com/sgl-project/sglang/pull/48718) `[Test] Remove the unit tests that #48504 ports from the Kimi-K3.1 branch` | quant | kimi-k3.1-day-0 | - |
| - | [#48719](https://github.com/sgl-project/sglang/pull/48719) `[Fix] docker: update NVIDIA megakernel pin for Qwen3.5 follow-up kernels` | bug,infra,nvidia,perf | main | - |
| - | [#48721](https://github.com/sgl-project/sglang/pull/48721) `[Feat] kimi-k3.1: DSA decode context parallelism runtime` | infra | main | - |
| - | [#48722](https://github.com/sgl-project/sglang/pull/48722) `[CI] [AMD] nightly-disagg: Install the checkout's runtime deps over the image` | infra,rocm | main | - |
| - | [#48723](https://github.com/sgl-project/sglang/pull/48723) `[Perf] mega_moe: reserve 18 SMs for MegaMoE in sm107 decode and target-verify` | nvidia,perf | main | - |
| - | [#48726](https://github.com/sgl-project/sglang/pull/48726) `[CI] [AMD] miles: Skip MI30x FP8 and DeepSeek-V4 tests that cannot run on gfx942` | infra,quant,rocm | main | - |
| - | [#48732](https://github.com/sgl-project/sglang/pull/48732) `[Fix] gemm: Keep Kimi-K3's tiny GEMM shapes on SIMT at every batch size` | bug,perf | main | - |
| - | [#48734](https://github.com/sgl-project/sglang/pull/48734) `[Fix] spec: Make per-step draft `out_cache_loc` contiguous for KV writes` | bug,infra | main | - |
| - | [#48737](https://github.com/sgl-project/sglang/pull/48737) `[Chore] ci: Cut deprecation warnings and TBO debug logs from CI output` | infra,perf | main | - |
| - | [#48738](https://github.com/sgl-project/sglang/pull/48738) `[CI] rerun-test: Tag each test command with its registered CI stage` | infra | main | - |
| - | [#48751](https://github.com/sgl-project/sglang/pull/48751) `[Fix] eplb: Keep draft forwards out of the target expert window` | bug | main | - |
| - | [#48752](https://github.com/sgl-project/sglang/pull/48752) `[Fix] rust-server: Publish 127.0.0.1 for an IPv6 loopback SGLANG_HOST_IP on an IPv4 wildcard bind` | bug | main | - |
| - | [#48755](https://github.com/sgl-project/sglang/pull/48755) `[Chore] utils: Guard `srt.utils` imports and remove dead code` | infra | main | - |
| - | [#48756](https://github.com/sgl-project/sglang/pull/48756) `[CI] spec: Shrink the radix workload in the EAGLE retract stress tests` | infra | main | - |
| - | [#48758](https://github.com/sgl-project/sglang/pull/48758) `[Refactor] utils: Move domain-dependent modules out of `srt.utils`` | infra,perf | main | - |
| - | [#48761](https://github.com/sgl-project/sglang/pull/48761) `[Perf] mhc: halve the DeepGEMM prenorm slices when the grid overflows one wave` | perf,risk | main | - |
| - | [#48781](https://github.com/sgl-project/sglang/pull/48781) `[Refactor] utils: Split `common.py` into topic modules and owner packages` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#48789](https://github.com/sgl-project/sglang/pull/48789) `[Chore] sgl-kernel: Remove the vendored FlashMLA build and wrappers` | infra,nvidia,perf | main | - |
| - | [#48799](https://github.com/sgl-project/sglang/pull/48799) `[CI] [NPU] coverage: publish baseline to OBS only and fail loud on missing data` | infra | main | - |
| - | [#48808](https://github.com/sgl-project/sglang/issues/48808) `[CI] multimodal-gen-test-1-gpu (llada_image) fails on main: 'NoneType' object has no attribute 'takes_deferred` | infra | ? | - |
| - | [#48809](https://github.com/sgl-project/sglang/pull/48809) `[Fix] overlap: Skip deferred-relay flush when future_map is None` | bug,perf | main | - |
| - | [#48816](https://github.com/sgl-project/sglang/pull/48816) `[CI] sgl-router: Stop label events from cancelling and restarting the router tiers` | infra | main | - |
| - | [#48827](https://github.com/sgl-project/sglang/pull/48827) `[Refactor] utils: Keep sglang.srt and sglang.kernels off sglang.utils` | infra,perf,quant | main | - |
| - | [#48828](https://github.com/sgl-project/sglang/pull/48828) `[Refactor] radix-cache: Keep only the read pool names in the Rust `PoolName`` | infra,perf | main | - |
| - | [#48829](https://github.com/sgl-project/sglang/pull/48829) `[Chore] deps: Drop flash-attn-4 from default dependencies` | infra,nvidia,perf,rocm | main | - |
| - | [#48853](https://github.com/sgl-project/sglang/pull/48853) `[Chore] flash-attn: Remove the kernels-hub FA3 loader and the kernels dependency` | infra,nvidia,perf | main | - |
| - | [#48856](https://github.com/sgl-project/sglang/pull/48856) `[HiCache] Linker: Drop the shared PCP namespace from the Mooncake direct linker` |  | kimi-k3.1-day-0 | - |
| - | [#48857](https://github.com/sgl-project/sglang/pull/48857) `[Doc] cookbook: Refresh SemiAnalysis AgentX launches to InferenceX main ce35bc93` |  | main | - |
| - | [#48868](https://github.com/sgl-project/sglang/pull/48868) `[Feat] kimi-k3.1: Sync the prefill-CP review fixes from the port PRs` | perf | kimi-k3.1-day-0 | - |

### sglang — Open / submitted (1096 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#47356](https://github.com/sgl-project/sglang/pull/47356) `[Perf] sampling: Avoid full-prompt copies in custom thinking budget logit processor` | perf | main | - |
| - | [#47357](https://github.com/sgl-project/sglang/issues/47357) `Llama KV scale loader replaces tensor scales with floats and leaves host mirrors stale` | quant | ? | - |
| - | [#47359](https://github.com/sgl-project/sglang/pull/47359) `[Feature][Spec Decode] Add DSpine adjacent-causal-injection drafts` | perf | main | - |
| - | [#47363](https://github.com/sgl-project/sglang/pull/47363) `[DSV4] Use the shared memory budget for dense prefill` | perf | main | - |
| - | [#47364](https://github.com/sgl-project/sglang/pull/47364) `[DeepSeek-V4.1] Extend remaining fusion batch limits to 1024 rows` | perf | main | - |
| - | [#47368](https://github.com/sgl-project/sglang/pull/47368) `[Fix] model-loader: Preserve KV cache scale tensors` | bug,perf,quant | main | - |
| - | [#47370](https://github.com/sgl-project/sglang/pull/47370) `[Doc] [XPU] Cookbook: Update to the cookbook for models supported by Intel Arc Pro B-Series GPUs` | nvidia | main | - |
| - | [#47371](https://github.com/sgl-project/sglang/pull/47371) `[AMD] muse-spark: ROCm day0` | nvidia,perf,quant,rocm | main | - |
| - | [#47372](https://github.com/sgl-project/sglang/pull/47372) `[Fix] function_call: Preserve JSON array tool calls across inter-call whitespace` | bug | main | - |
| - | [#47375](https://github.com/sgl-project/sglang/pull/47375) `[Fix] hicache: Allow fallback for namespaced cgroup paths` | bug | release/v0.5.23 | - |
| - | [#47377](https://github.com/sgl-project/sglang/pull/47377) `[CI] [NPU] unit: Fix two stale NPU unit test assertions` | bug,infra | main | - |
| - | [#47379](https://github.com/sgl-project/sglang/pull/47379) `[Fix] disaggregation: invalidate Mooncake and Mori PD peers before role switches` | bug | main | - |
| - | [#47383](https://github.com/sgl-project/sglang/pull/47383) `[Feat] [NPU] attention: Add native LIM and CopySFA KV offload` | perf | main | - |
| - | [#47384](https://github.com/sgl-project/sglang/pull/47384) `[Doc] deployment: Add a Slurm Apptainer serving example` |  | main | - |
| - | [#47385](https://github.com/sgl-project/sglang/pull/47385) `[Doc] ascend: add NPU graph mode optimization guide` | perf | main | - |
| - | [#47386](https://github.com/sgl-project/sglang/pull/47386) `[Doc] cookbook: add Ascend NPU deployment for Qwen3` |  | main | - |
| - | [#47388](https://github.com/sgl-project/sglang/pull/47388) `[Test] ngram: Add shared code-edit benchmarks for SGLang and TensorRT-LLM` | perf | main | - |
| - | [#47389](https://github.com/sgl-project/sglang/pull/47389) `[Feat] diffusion/pi05: Support action expert training` | perf | main | - |
| - | [#47390](https://github.com/sgl-project/sglang/pull/47390) `[Fix] scheduler: Process NGRAM grammar results before planning` | bug | main | - |
| - | [#47391](https://github.com/sgl-project/sglang/pull/47391) `[Fix] cuda-graph: Keep an aligned top bucket and size draft graphs by their capture width` | bug,nvidia | main | - |
| - | [#47392](https://github.com/sgl-project/sglang/pull/47392) `[Fix] session: Keep recurrent state aligned with kept tokens` | bug | main | - |
| - | [#47397](https://github.com/sgl-project/sglang/issues/47397) `SGLANG_JIT_DEEPGEMM_FAST_WARMUP on DeepSeek-V4.1: 3-5x faster cold start, no runtime degradation detectable at` | perf | ? | - |
| - | [#47398](https://github.com/sgl-project/sglang/pull/47398) `[Feat] [AMD] gpt-oss: Mixed W4A8 MoE on gfx1250, Gluon below a token count and FlyDSL above` | infra,rocm | main | - |
| - | [#47399](https://github.com/sgl-project/sglang/issues/47399) `[Bug] [NPU] 图模式下走Fia v2算子，torch_npu.npu_fused_infer_attention_score_v2函数入参错误` | perf | ? | - |
| - | [#47400](https://github.com/sgl-project/sglang/pull/47400) `[Fix] multimodal: keep images of input_ids chat requests; locate them by placeholder ID` | bug | main | - |
| - | [#47401](https://github.com/sgl-project/sglang/pull/47401) `[Feat] dcp: Support GQA DCP with HiCache L2` | perf | main | - |
| - | [#47402](https://github.com/sgl-project/sglang/pull/47402) `[Fix] qwen-vl: keep the client's input_ids for image requests on sglang-miles` | bug | sglang-miles | - |
| - | [#47404](https://github.com/sgl-project/sglang/pull/47404) `[Fix] moe: Reuse one FlashInfer MXFP4 CUTLASS MoE workspace per stream` | bug,nvidia,quant | main | - |
| - | [#47405](https://github.com/sgl-project/sglang/pull/47405) `[Perf] disaggregation: Send replicated KV heads from one prefill rank` | perf | main | - |
| - | [#47406](https://github.com/sgl-project/sglang/pull/47406) `[Fix] deepseek-v4.1: Fix bounded replay with CP and DSpark` | bug | main | - |
| - | [#47407](https://github.com/sgl-project/sglang/pull/47407) `[Fix] benchmark: Skip malformed custom JSONL records` | bug,perf | main | - |
| - | [#47409](https://github.com/sgl-project/sglang/issues/47409) `[Bug] Attention-DP ranks are indistinguishable to routers and dashboards: `KvMetrics.data_parallel_rank` is al` |  | ? | - |
| - | [#47410](https://github.com/sgl-project/sglang/pull/47410) `[Perf] deterministic: Launch a fixed number of Triton decode blocks for large split budgets` | perf,rocm | main | - |
| - | [#47412](https://github.com/sgl-project/sglang/pull/47412) `[Fix] [AMD] deterministic: Run block-FP8 linears through Triton on ROCm` | bug,quant,rocm | main | - |
| - | [#47413](https://github.com/sgl-project/sglang/pull/47413) `[Fix] deterministic: Batch-invariant Kimi Delta Attention` | bug,perf | main | - |
| - | [#47414](https://github.com/sgl-project/sglang/pull/47414) `[Fix] [AMD] deterministic: Run FP8 MoE experts through the Triton runner on ROCm` | bug,quant,rocm | main | - |
| - | [#47416](https://github.com/sgl-project/sglang/pull/47416) `[Fix] metrics: Correct MFU/MBU bandwidth overcounting and GraniteMoE AutoTokenizer fallback` | bug,infra,perf | main | - |
| - | [#47418](https://github.com/sgl-project/sglang/pull/47418) `[Perf] [AMD] DFlash: FP8 KV and tuned launch for draft SWA verify` | perf,quant,rocm | main | - |
| - | [#47420](https://github.com/sgl-project/sglang/issues/47420) `[Bug] benchmark: --dataset-name random silently requires the ShareGPT download; fails on offline/restricted ne` | perf,risk | ? | - |
| - | [#47421](https://github.com/sgl-project/sglang/pull/47421) `[Feat] [CPU] Model: Enable DeepSeek V4.1 Flash on xeon cpu` | perf | main | - |
| - | [#47423](https://github.com/sgl-project/sglang/pull/47423) `[Feat] dflash: Serve SpecForge KDA drafts through the target KDA layer` | infra | main | - |
| - | [#47425](https://github.com/sgl-project/sglang/pull/47425) `[Feat] observability: Support tracing only the first N decode steps per request` |  | main | - |
| - | [#47426](https://github.com/sgl-project/sglang/pull/47426) `[Perf] disaggregation: Keep prefill KV-send index readback off the scheduler under CP and KV sharding` | perf | main | - |
| - | [#47427](https://github.com/sgl-project/sglang/pull/47427) `[Fix] openai: Reject unk_token_id and colliding IDs in serving_rerank._get_yes_no_token_ids` | bug | main | - |
| - | [#47428](https://github.com/sgl-project/sglang/issues/47428) `[Bug] S3 model URI overrides explicit remote_instance + modelexpress with runai_streamer` |  | ? | - |
| - | [#47430](https://github.com/sgl-project/sglang/pull/47430) `[Perf] [AMD] aiter: FP8 Q for EAGLE target_verify and draft_extend attention with an FP8 KV cache` | perf,quant,rocm | main | - |
| - | [#47431](https://github.com/sgl-project/sglang/pull/47431) `[Fix] [AMD] quark: Match exclude entries that name a parameter (.weight) by module` | bug,rocm | main | - |
| - | [#47432](https://github.com/sgl-project/sglang/pull/47432) `[Perf] [AMD] aiter/spec: Remove two host syncs from extend metadata and spec M-RoPE positions` | perf,rocm | main | - |
| - | [#47433](https://github.com/sgl-project/sglang/pull/47433) `[Perf] [AMD] gdn: ReplaySSM verify uses one pipeline stage at every batch size on gfx950` | perf,rocm | main | - |
| - | [#47434](https://github.com/sgl-project/sglang/pull/47434) `[Fix] spec: Greedy requests keep the argmax prefill draft under rejection sampling` | bug | main | - |
| - | [#47435](https://github.com/sgl-project/sglang/pull/47435) `[fix] prefill CUDA graph fallback returning a runner instead of GraphCapture` | bug,nvidia | main | - |
| - | [#47436](https://github.com/sgl-project/sglang/pull/47436) `[Fix] model-loader: Honor explicit weight loaders for object-store models and drafts` | bug | main | - |
| - | [#47437](https://github.com/sgl-project/sglang/pull/47437) `[Perf] [AMD] aiter: Run the DSpark MHA draft on non-causal unified_attention` | perf,rocm | main | - |
| - | [#47438](https://github.com/sgl-project/sglang/pull/47438) `[Refactor] [NPU] dsv4: Migrate to the released CANN transformer operators` | infra,perf | main | - |
| - | [#47439](https://github.com/sgl-project/sglang/pull/47439) `[Fix] [AMD] Keep QK-norm RoPE shuffles within logical warps` | bug,perf,rocm | main | - |
| - | [#47440](https://github.com/sgl-project/sglang/pull/47440) `[DSV4] Fix CUDA Cluster top-k tie overflow exactness` | bug,nvidia,perf,risk | main | - |
| - | [#47441](https://github.com/sgl-project/sglang/pull/47441) `[Docs] [AMD] Add MiMo-V2.6 MI355X INT4 QuickReduce recipe` | quant,rocm | main | - |
| - | [#47443](https://github.com/sgl-project/sglang/pull/47443) `[Fix] diffusion: Honor the requested profiler step count` | bug,perf | main | - |
| - | [#47446](https://github.com/sgl-project/sglang/pull/47446) `[Fix] logging: Bound token-ID decoding in partial request logs` | bug,infra | main | - |
| - | [#47447](https://github.com/sgl-project/sglang/pull/47447) `[Perf] [AMD] kimi-k3: Fuse attention o_proj's GEMM with its attention-TP sum via mori` | perf,rocm | main | - |
| - | [#47448](https://github.com/sgl-project/sglang/pull/47448) `feat(simulator): add AFD support to sglang-simulator` | infra | main | - |
| - | [#47449](https://github.com/sgl-project/sglang/pull/47449) `[Feat] scheduler: Add max-queued-tokens for request management` |  | main | - |
| - | [#47450](https://github.com/sgl-project/sglang/pull/47450) `[Feat] tracing: Attribute prefix checkpoint CPU time to requests` |  | main | - |
| - | [#47451](https://github.com/sgl-project/sglang/pull/47451) `[Test] kda: Cover contiguous QKV graph inputs and asymmetric fallback` | infra,perf | main | - |
| - | [#47453](https://github.com/sgl-project/sglang/pull/47453) `[AMD] Write the Kimi-K3 shared-down GEMM through AITER when out is set` | rocm | main | - |
| - | [#47454](https://github.com/sgl-project/sglang/pull/47454) `[Fix] function_call: Preserve MiniCPM5 boundaries inside CDATA` | bug | main | - |
| - | [#47455](https://github.com/sgl-project/sglang/pull/47455) `[Perf] HiSparse: Reduce redundant DSA index-K memory to increase decode capacity` | infra,perf | main | - |
| - | [#47456](https://github.com/sgl-project/sglang/pull/47456) `[Fix] scheduler: Bind request receivers to their selected transport` | bug | main | - |
| - | [#47457](https://github.com/sgl-project/sglang/pull/47457) `[Fix] deepseek_v41: track image work after cancellation` | bug | main | - |
| - | [#47460](https://github.com/sgl-project/sglang/pull/47460) `[Feat][DSV4.1][engram]: Sharing Engram via RDMA to reduce PD DRAM redundancy` |  | main | - |
| - | [#47461](https://github.com/sgl-project/sglang/issues/47461) `stop_regex: a non-literal match is left in the returned text, and no_stop_trim has no effect for regex stops` |  | ? | - |
| - | [#47462](https://github.com/sgl-project/sglang/pull/47462) `[Refactor] pd: Extract MoriTransport behind the common Transport interface` |  | main | - |
| - | [#47463](https://github.com/sgl-project/sglang/pull/47463) `[Fix] stop_regex: Record the matched span, not the pattern source` | bug | main | - |
| - | [#47468](https://github.com/sgl-project/sglang/pull/47468) `[Fix] diffusion: Align Pika H3 Flex inference numerics` | bug,infra,perf | main | - |
| - | [#47469](https://github.com/sgl-project/sglang/pull/47469) `[Perf] [NVIDIA] attention: Add opt-in LiteTopK prefill indexer top-k for DSA (FP8) and DeepSeek-V4.1 (FP4) on ` | infra,nvidia,perf,quant | main | - |
| - | [#47470](https://github.com/sgl-project/sglang/pull/47470) `[Fix] observability: Assign correct dp_rank under attention-dp for KV metrics and Prometheus` | bug | main | - |
| - | [#47471](https://github.com/sgl-project/sglang/pull/47471) `[Fix] benchmark: Add offline guidance for random datasets` | bug,perf | main | - |
| - | [#47472](https://github.com/sgl-project/sglang/pull/47472) `[Perf] disaggregation: Batch prefill KV-send page-id readback across a batch` | perf | main | - |
| - | [#47473](https://github.com/sgl-project/sglang/pull/47473) `[Test] diffusion/disaggregation: Cover aligned transfer staging` | perf | codex/diffusion-stage-deployment | - |
| - | [#47475](https://github.com/sgl-project/sglang/pull/47475) `[Fix] profiler: Init profile-by-stage counters when num_steps is not given` | bug | main | - |
| - | [#47477](https://github.com/sgl-project/sglang/pull/47477) `[Perf] [AMD] attention: Attend AITER varlen's live prefix as one segment` | perf,rocm | main | - |
| - | [#47478](https://github.com/sgl-project/sglang/pull/47478) `[Feat] dsv41-engram: Share Engram tables across P/D using EGM` |  | main | - |
| - | [#47480](https://github.com/sgl-project/sglang/pull/47480) `[Fix] sglang-miles: Clear the multimodal embedding cache on flush_cache and weight updates` | bug,perf | rockdu-dev-mm-v2/sglang-miles | - |
| - | [#47481](https://github.com/sgl-project/sglang/issues/47481) `[Performance] Reproducible cache hit-rate dip during L2/L3 capacity pressure with HiCache + Mooncake` | perf | ? | - |
| - | [#47482](https://github.com/sgl-project/sglang/pull/47482) `[Fix] disaggregation: Settle the in-flight decode result before a PD decode retraction` | bug | main | - |
| - | [#47484](https://github.com/sgl-project/sglang/pull/47484) `[Fix] disaggregation: Back up separate draft KV pools in PD CPU retraction` | bug,infra | main | - |
| - | [#47485](https://github.com/sgl-project/sglang/pull/47485) `[Perf] [AMD] lm_head: Opt-in aiter tgemm for the bf16 lm_head on gfx950` | perf,rocm | main | - |
| - | [#47486](https://github.com/sgl-project/sglang/pull/47486) `[AMD] Route MiMo V2.6 target verify through AITER MegaMoE` | rocm | main | - |
| - | [#47490](https://github.com/sgl-project/sglang/issues/47490) `[Bug] EAGLE draft extend crashes with negative dimension under DP attention + FlashInfer A2A + prefill CUDA gr` | bug,nvidia | ? | - |
| - | [#47491](https://github.com/sgl-project/sglang/pull/47491) `[Fix] [AMD] scheduler: Keep the scheduler's GPU work on the forward stream under monokernel` | bug,infra,rocm | main | - |
| - | [#47493](https://github.com/sgl-project/sglang/pull/47493) `[Fix] dp-attention: Trim MLP-sync pad rows from extend outputs before the draft extend` | bug,infra | main | - |
| - | [#47495](https://github.com/sgl-project/sglang/pull/47495) `[Fix] lang: Normalize stop in RuntimeEndpoint._handle_dtype_to_regex` | bug | main | - |
| - | [#47496](https://github.com/sgl-project/sglang/pull/47496) `[Fix] stop: Store the matched regex span, not the pattern` | bug | main | - |
| - | [#47497](https://github.com/sgl-project/sglang/pull/47497) `[Fix] profile: Allow profile_by_stage without num_steps` | bug | main | - |
| - | [#47498](https://github.com/sgl-project/sglang/pull/47498) `[Fix] nemotron: Accept transformers 5 layer type names` | bug | main | - |
| - | [#47500](https://github.com/sgl-project/sglang/pull/47500) `[Feat] nemotron_parse: Support Nemotron 3.5 Parse` |  | main | - |
| - | [#47501](https://github.com/sgl-project/sglang/issues/47501) `[Bug] Qwen3.8-Flash-Next-FP8 TP4/EP4 decode ~5% slower on GB200 since #45917 (FP8 TRT-LLM MoE leaves in-kernel` | nvidia,perf,quant | ? | - |
| - | [#47502](https://github.com/sgl-project/sglang/pull/47502) `[Fix] moe: Keep FP8 TRT-LLM in-kernel routing for padding-only TopK bounds` | bug,perf,quant | main | - |
| - | [#47505](https://github.com/sgl-project/sglang/issues/47505) `[Bug] rust-server: gather_server_endpoints runs on elastic-EP joiners over a WORLD group the serving ranks nev` |  | ? | - |
| - | [#47506](https://github.com/sgl-project/sglang/pull/47506) `[Fix] rust-server: Skip server endpoint collective on elastic-EP joiners` | bug | main | - |
| - | [#47507](https://github.com/sgl-project/sglang/pull/47507) `[Feat] lmcache: Enable external KV reuse on PD prefill servers` | perf | main | - |
| - | [#47508](https://github.com/sgl-project/sglang/issues/47508) `[Bug][ROCm] Kimi-K3 fused KDA input-projection buffers are replaced on weight reload` | perf,rocm | ? | - |
| - | [#47509](https://github.com/sgl-project/sglang/issues/47509) `[Bug] rust-server: gather_server_endpoints can advertise a loopback or unroutable address to other nodes, and ` |  | ? | - |
| - | [#47511](https://github.com/sgl-project/sglang/issues/47511) `[Bug] rust-server: /internal/peer serves a relayed control request without checking it was meant for this DP r` |  | ? | - |
| - | [#47513](https://github.com/sgl-project/sglang/pull/47513) `[Perf] attention: Support attention sinks in the split-KV EAGLE verify kernel (gpt-oss)` | perf | main | - |
| - | [#47514](https://github.com/sgl-project/sglang/pull/47514) `[KVCR] Guard mode for the dense direct linker (stacked on #45650)` | perf | main | - |
| - | [#47517](https://github.com/sgl-project/sglang/pull/47517) `[Perf] [NVIDIA] muse-spark-open: Fuse all-gather + Norm + Quant` | nvidia,perf,quant | main | - |
| - | [#47518](https://github.com/sgl-project/sglang/pull/47518) `[Feat] lmcache: Decide external KV loads from measured costs` | perf | main | - |
| - | [#47519](https://github.com/sgl-project/sglang/pull/47519) `[Fix] rust-server: Refuse a relayed control request meant for another DP rank` | bug,perf | main | - |
| - | [#47524](https://github.com/sgl-project/sglang/pull/47524) `[Fix] moe: Use flashinfer_trtllm_routed when routed experts are returned` | bug,nvidia | main | - |
| - | [#47525](https://github.com/sgl-project/sglang/pull/47525) `[Perf] moe: Batch the TRT-LLM BF16 expert layout and index Qwen3.5 expert loading` | perf,quant | main | - |
| - | [#47527](https://github.com/sgl-project/sglang/pull/47527) `[Fix] Kimi-K3: Rebuild derived weights in place on weight updates` | bug | main | - |
| - | [#47528](https://github.com/sgl-project/sglang/pull/47528) `[Fix] multimodal: [sglang-miles] Pass caller token IDs to the Qwen-VL legacy loader` | bug | sglang-miles | - |
| - | [#47529](https://github.com/sgl-project/sglang/pull/47529) `[Fix] RL: Fix crash when returning routed experts under DCP or KV sharding` | bug,infra | main | - |
| - | [#47530](https://github.com/sgl-project/sglang/pull/47530) `[Fix] Kimi-K3: Refresh --dcp-replicate-q-proj weights on weight update` | bug | main | - |
| - | [#47531](https://github.com/sgl-project/sglang/pull/47531) `[Perf] Kimi-K3: Index parameters per decoder layer in load_weights` | perf | main | - |
| - | [#47534](https://github.com/sgl-project/sglang/pull/47534) `[Fix] rust-server: Derive advertised host towards dist_init_addr and reject loopback on multi-node` | bug | main | - |
| - | [#47535](https://github.com/sgl-project/sglang/pull/47535) `[KVCR] Hybrid-pool (FULL+MAMBA) direct linker (stacked on #47514)` | perf | main | - |
| - | [#47536](https://github.com/sgl-project/sglang/pull/47536) `[Perf] RL: Keep routed-expert rows only for MoE layers` | infra,perf | main | - |
| - | [#47538](https://github.com/sgl-project/sglang/pull/47538) `[Feat] http_server: Dispatch SageMaker /invocations to completions and embeddings by request body` | infra | main | - |
| - | [#47554](https://github.com/sgl-project/sglang/pull/47554) `[Perf] R3: Gather DeepEP routed-expert ids once per forward (3/3)` | infra,nvidia,perf | main | - |
| - | [#47558](https://github.com/sgl-project/sglang/pull/47558) `[Fix] lmcache: Order stores after forward-stream KV writes` | bug,perf | main | - |
| - | [#47559](https://github.com/sgl-project/sglang/pull/47559) `[Fix] openai: Prevent infinite loop in split_audio_energy_aware when max_clip_s <= search window` | bug | main | - |
| - | [#47561](https://github.com/sgl-project/sglang/pull/47561) `[Perf] [NVIDIA] muse-spark: Build the routed-MoE routing metadata on router stream` | infra,nvidia,perf | main | - |
| - | [#47562](https://github.com/sgl-project/sglang/issues/47562) `[AITER-Upgrade] PR readiness gfx1250 (MI45x)` | rocm | ? | - |
| - | [#47564](https://github.com/sgl-project/sglang/pull/47564) `[Test] server_args: Align Muse Spark platform mocks` |  | main | - |
| - | [#47572](https://github.com/sgl-project/sglang/pull/47572) `[Fix+Doc] minimax-m3: declare MiniMax2 routing and switch the GB300 MXFP8 recipe MoE runner to flashinfer_trtl` | bug,infra,nvidia,quant | main | - |
| - | [#47576](https://github.com/sgl-project/sglang/pull/47576) `[Perf] cp: Upload zigzag CP metadata with one pinned non-blocking copy` | infra,perf | main | - |
| - | [#47578](https://github.com/sgl-project/sglang/pull/47578) `[Perf] kv-shard: Batch PageInterleave allocator pops and frees per batch` | perf | main | - |
| - | [#47579](https://github.com/sgl-project/sglang/pull/47579) `Fix #47399: Correct next_tokens parameter in NPU graph decode mode` | bug | main | - |
| - | [#47580](https://github.com/sgl-project/sglang/pull/47580) `Fix #47213: Prevent decode checkpoint reuse in deterministic mode` | bug | main | - |
| - | [#47581](https://github.com/sgl-project/sglang/pull/47581) ` [Perf] [NPU] dspark: Integrate argmax and verify scheduler kernels` | infra,perf | main | - |
| - | [#47584](https://github.com/sgl-project/sglang/pull/47584) `[Fix] [AMD] hicache: Book explicitly sized host pools against one host memory snapshot` | bug,infra,rocm | main | - |
| - | [#47585](https://github.com/sgl-project/sglang/pull/47585) `[Fix] [AMD] quark: Widen the Quark MXFP4 W4A16 MoE gate to consumer RDNA and fail clearly without aiter` | bug,infra,quant,rocm | main | - |
| - | [#47588](https://github.com/sgl-project/sglang/pull/47588) `[Feat] sail: support DeepGEMM GEMM/MoE backends [4/N]` | infra,perf,quant | main | - |
| - | [#47589](https://github.com/sgl-project/sglang/pull/47589) `[Perf] [NVIDIA] kernels: Add Blackwell SM100 CuTe DSL NVFP4 DualGEMM+SwiGLU, PDL-safe GEMM, Grouped GEMM, and ` | nvidia,perf,quant | main | - |
| - | [#47590](https://github.com/sgl-project/sglang/pull/47590) `fix(dspark): honor speculative accept threshold in rejection sampling` | bug,perf | main | - |
| - | [#47591](https://github.com/sgl-project/sglang/pull/47591) `[Perf] [AMD] aiter: Query native head support for DCP MLA verify` | perf,rocm | main | - |
| - | [#47593](https://github.com/sgl-project/sglang/pull/47593) `[Fix] scheduler/MiniMax-M3.1-Flash: Bound a chunked prefill continuation by the allocatable KV` | bug | main | - |
| - | [#47594](https://github.com/sgl-project/sglang/issues/47594) `[Test] Add CPU unit coverage for MTP weight filtering` |  | ? | - |
| - | [#47595](https://github.com/sgl-project/sglang/pull/47595) `[Fix] eplb: Exclude draft statistics and reuse compatible TP groups` | bug | main | - |
| - | [#47600](https://github.com/sgl-project/sglang/pull/47600) `feat: add NCCL EP as optional moe-a2a-backend (low-latency decode)` | infra,nvidia,perf | main | - |
| - | [#47604](https://github.com/sgl-project/sglang/pull/47604) `[Feat] pp: Replay breakable prefill graphs on PP stages with zigzag prefill CP` |  | main | - |
| - | [#47606](https://github.com/sgl-project/sglang/pull/47606) `[Fix] function_call: Drain tool calls stranded in the buffer when the stream ends` | bug | main | - |
| - | [#47607](https://github.com/sgl-project/sglang/issues/47607) `[Test] Cover model-loader extra config validation` |  | ? | - |
| - | [#47608](https://github.com/sgl-project/sglang/pull/47608) `[Test] model_loader: Cover extra config validation` |  | main | - |
| - | [#47610](https://github.com/sgl-project/sglang/pull/47610) `[Fix] pd: Pair MiniMax sparse state by layer id under PP` | bug | main | - |
| - | [#47616](https://github.com/sgl-project/sglang/pull/47616) `[Feat] cache: add concurrent Mooncake linker prefetch control` | perf | main | - |
| - | [#47617](https://github.com/sgl-project/sglang/pull/47617) `[Fix] hicache: storage workers survive, fail loud when dead, stop without querying the backlog` | bug,infra,perf | main | - |
| - | [#47618](https://github.com/sgl-project/sglang/pull/47618) `[Fix] pd: Agree on PP prefill release and abort-vs-error outcome via PP0 decision` | bug,infra | main | - |
| - | [#47620](https://github.com/sgl-project/sglang/pull/47620) `[Fix] hicache: vote the prefetch timeout once per tick, not per admission poll` | bug,infra,perf | main | - |
| - | [#47621](https://github.com/sgl-project/sglang/pull/47621) `[Fix] hicache: buffer_only cuts an oversized storage hit to the prefix that fits` | bug,infra,perf | main | - |
| - | [#47622](https://github.com/sgl-project/sglang/pull/47622) `[Fix] openai: Return required and named tool calls without a tool-call parser` | bug | main | - |
| - | [#47624](https://github.com/sgl-project/sglang/issues/47624) `[RFC] NPU RL Test Consolidation: File Ownership, Coverage Docstrings, and CI Integration (Ascend)` | infra | ? | - |
| - | [#47626](https://github.com/sgl-project/sglang/pull/47626) `[Fix] hicache: settle storage backups at the agreed written prefix and retry the tail` | bug,infra,perf | main | - |
| - | [#47627](https://github.com/sgl-project/sglang/pull/47627) `[Perf] [NVIDIA] dspark: Stage DSv4.1 long-context target verify metadata beside the draft` | nvidia,perf | main | - |
| - | [#47628](https://github.com/sgl-project/sglang/pull/47628) `[Fix] lang: Prevent StreamExecutor deadlock after worker thread error` | bug,risk | main | - |
| - | [#47629](https://github.com/sgl-project/sglang/pull/47629) `[Fix] [NPU] moe: honor simple TopK scoring and routing scale` | bug,quant | main | - |
| - | [#47631](https://github.com/sgl-project/sglang/pull/47631) `[Fix] profiler: keep trace files inside output_dir` | bug | main | - |
| - | [#47633](https://github.com/sgl-project/sglang/pull/47633) `[Feat] minimax-m3: Serve M3.1 NVFP4 MoE with DeepEP low-latency NVFP4 dispatch and CuteDSL masked GEMM` | nvidia,perf,quant | main | - |
| - | [#47634](https://github.com/sgl-project/sglang/pull/47634) `[Fix] [NPU] attention: Slice MLA latent K after TP all-gather` | bug | main | - |
| - | [#47635](https://github.com/sgl-project/sglang/pull/47635) `[NPU] HiSparse: support DeepSeek V4 sparse KV offload on Ascend` |  | main | - |
| - | [#47636](https://github.com/sgl-project/sglang/pull/47636) `[Perf] [NVIDIA] muse-spark: TF32 cluster split-K GEMM for the decode router logits` | nvidia,perf | main | - |
| - | [#47637](https://github.com/sgl-project/sglang/pull/47637) `[Fix] [NPU] gptq: Correct linear zero-point offset sign` | bug,quant | main | - |
| - | [#47639](https://github.com/sgl-project/sglang/pull/47639) `[Fix] [NPU] awq: Preserve weight dtype in linear fallback` | bug,quant | main | - |
| - | [#47640](https://github.com/sgl-project/sglang/pull/47640) `[Refactor] [Ascend] dsa: Align index K cache and scale layout with GPU` | perf,quant | main | - |
| - | [#47642](https://github.com/sgl-project/sglang/pull/47642) `[Quant/GGUF] Fix iq3xs_grid: 146 words must be 0x3c not 0x3e` | bug,perf,quant | main | - |
| - | [#47644](https://github.com/sgl-project/sglang/pull/47644) `[Fix] dflash: Stage the draft sampler only for batches its buffers hold` | bug | main | - |
| - | [#47645](https://github.com/sgl-project/sglang/pull/47645) `[Fix] [AMD] aiter: Plan the DCP asm verify shard with the draft tokens under CUDA graph replay` | bug,infra,nvidia,rocm | main | - |
| - | [#47647](https://github.com/sgl-project/sglang/pull/47647) `[Perf] [NPU] dsv4: Avoid unused packed indexer cache allocation` | perf | main | - |
| - | [#47649](https://github.com/sgl-project/sglang/pull/47649) `[Fix] scoring: Return token_logprobs for setwise CausalLM scoring` | bug | main | - |
| - | [#47650](https://github.com/sgl-project/sglang/pull/47650) `[Perf] hicache: Space out write_back eviction waits with a bounded reserve` | perf | main | - |
| - | [#47654](https://github.com/sgl-project/sglang/pull/47654) `[Fix] [NPU] sparse-kv: Preserve shared prefixes in physical host slots` | bug | main | - |
| - | [#47655](https://github.com/sgl-project/sglang/pull/47655) `[Fix] [AMD] utils: Cap integrated-device available memory by the device total` | bug,rocm | main | - |
| - | [#47656](https://github.com/sgl-project/sglang/pull/47656) `[Fix] [NPU] moe: Honor SwiGLU clamp for BF16 and INT8 experts` | bug,quant | main | - |
| - | [#47657](https://github.com/sgl-project/sglang/issues/47657) `[Feature] Per-node HTTP frontend for data-parallel groups spanning nodes, addressed by global `X-Data-Parallel` |  | ? | - |
| - | [#47658](https://github.com/sgl-project/sglang/pull/47658) `[Perf] SM120: honour SGLANG_OPT_DEEPGEMM_HC_PRENORM for the DeepSeek-V4.1 compensated mhc projection` | infra,nvidia,perf | main | - |
| - | [#47659](https://github.com/sgl-project/sglang/pull/47659) `[Fix] [NPU] MLA: preserve NZ cache data during CPU retraction` | bug,perf | main | - |
| - | [#47660](https://github.com/sgl-project/sglang/pull/47660) `[Feat] [NPU] DSV4.1: Support DeepSeek-V4.1 on Ascend A5` | perf | main | - |
| - | [#47661](https://github.com/sgl-project/sglang/pull/47661) `[Fix] openai: honor LoRA adapters in /v1/responses` | bug | main | - |
| - | [#47663](https://github.com/sgl-project/sglang/pull/47663) `[Perf] [NPU] dsv4: Reuse CPU query lengths for prefill metadata` | perf | main | - |
| - | [#47664](https://github.com/sgl-project/sglang/pull/47664) `[Fix] [Intel] moe: Route dropped slots at weight 0` | bug,quant | main | - |
| - | [#47665](https://github.com/sgl-project/sglang/pull/47665) `[Perf] [NPU] dsv4: Generate compression positions with stepped arange` | perf | main | - |
| - | [#47666](https://github.com/sgl-project/sglang/pull/47666) `[WIP][Perf]dsv41: Accelerate SM90 compact FP4 candidate scoring with CUDA ` | nvidia,perf,quant | main | - |
| - | [#47667](https://github.com/sgl-project/sglang/pull/47667) `[Perf] minimax-m3: Overlap the MegaMoE shared expert with the routed launch` | perf | main | - |
| - | [#47668](https://github.com/sgl-project/sglang/pull/47668) `[Feat] diffusion/model: Support Efficient-Large-Model/Open-H3-Regenerate-2K (MiniMax-H3 2K draft refiner)` | perf | main | - |
| - | [#47669](https://github.com/sgl-project/sglang/pull/47669) `[Perf] cosmos3: support nvenc convert image to videos` | infra,perf | main | - |
| - | [#47671](https://github.com/sgl-project/sglang/pull/47671) `[Perf] speculative: Vectorize full verify attention mask construction in NGRAMWorker` | perf | main | - |
| - | [#47672](https://github.com/sgl-project/sglang/pull/47672) `[Perf] [NVIDIA] dsv4: avoid CP compressor input reorder with rank-major reads` | nvidia,perf | main | - |
| - | [#47673](https://github.com/sgl-project/sglang/pull/47673) `[Feat] qwen4-exp: Add node-sharded Mooncake Engram storage` |  | main | - |
| - | [#47674](https://github.com/sgl-project/sglang/pull/47674) `[Feat] multimodal: GLM-5.3 token-space strategy for images (sglang-miles)` |  | sglang-miles | - |
| - | [#47677](https://github.com/sgl-project/sglang/pull/47677) `[Perf] [NVIDIA] dspark: Stage draft DP-MoE token counts through persistent buffers` | nvidia,perf | main | - |
| - | [#47681](https://github.com/sgl-project/sglang/pull/47681) `[KVCR] Hint salted lookups with the published event hash (stacked on #45650)` | perf | main | - |
| - | [#47682](https://github.com/sgl-project/sglang/pull/47682) `[KVCR] Carry kv_hint_sources through the DP controller (stacked on #45650)` | perf | main | - |
| - | [#47685](https://github.com/sgl-project/sglang/pull/47685) `[Perf] [NVIDIA] dflash: Top up decode KV pages for the whole batch on allocation steps` | nvidia,perf | main | - |
| - | [#47688](https://github.com/sgl-project/sglang/pull/47688) `[Fix] [Intel] attention: Round the local-attention chunk clamp up to a whole page` | bug | main | - |
| - | [#47689](https://github.com/sgl-project/sglang/pull/47689) `[Fix] moe: Correctly route fused shared experts and normalize routed topk in grouped_topk` | bug,perf | main | - |
| - | [#47690](https://github.com/sgl-project/sglang/pull/47690) `[Feat] [NVIDIA] quant: Enable CompressedTensorsWNA16TritonMoE on Turing sm_75 GPUs` | nvidia,quant | main | - |
| - | [#47692](https://github.com/sgl-project/sglang/pull/47692) `[Perf] moe: skip inactive expert routes in Triton EP without a2a` | perf,rocm | main | - |
| - | [#47693](https://github.com/sgl-project/sglang/pull/47693) `[Fix] multi-tokenizer: Broadcast a non-owner's abort to the owning worker` | bug | main | - |
| - | [#47694](https://github.com/sgl-project/sglang/pull/47694) `[Fix] dspark: Stop compact verify from counting padding rows as accepted drafts` | bug | main | - |
| - | [#47695](https://github.com/sgl-project/sglang/pull/47695) `[Feat] [AMD] quark: Quark int4 W4A16 on ROCm, and gfx1151 kernels for Strix Halo decode and prefill` | infra,perf,quant,rocm | main | - |
| - | [#47696](https://github.com/sgl-project/sglang/pull/47696) `[Perf] diffusion: Run a single packed FA3 sequence through the batch kernel` | infra,nvidia,perf | main | - |
| - | [#47697](https://github.com/sgl-project/sglang/pull/47697) `[Perf] diffusion/pi05: Optimize prefix encoding and action denoising` | perf | main | - |
| - | [#47698](https://github.com/sgl-project/sglang/pull/47698) `[Perf] eplb: Replace per-item tensor ops with list packing in deepseek_vec.pack_groups` | perf | main | - |
| - | [#47700](https://github.com/sgl-project/sglang/pull/47700) `Fix PP disaggregated decode race condition (#47613)` | bug,risk | main | - |
| - | [#47701](https://github.com/sgl-project/sglang/pull/47701) `[Feat] activevln: Add differentiable actor and SRT weight export` | perf | main | - |
| - | [#47702](https://github.com/sgl-project/sglang/pull/47702) `[Fix] server-args: Treat YAML null as unset in --config files` | bug | main | - |
| - | [#47703](https://github.com/sgl-project/sglang/pull/47703) `[Fix] trtllm_mha: Pack a graph-built page table for eager reads` | bug,nvidia | dflash-draft-sampler-batch-overflow | - |
| - | [#47706](https://github.com/sgl-project/sglang/pull/47706) `[Perf] rerank: Score Qwen3-VL reranker candidates concurrently` | perf | main | - |
| - | [#47707](https://github.com/sgl-project/sglang/pull/47707) `[Doc] docs: Fix commands that the CLI rejects` | bug | main | - |
| - | [#47708](https://github.com/sgl-project/sglang/pull/47708) `[Fix] rerank: Request exact yes/no logprobs for the Qwen3-VL reranker` | bug | main | - |
| - | [#47709](https://github.com/sgl-project/sglang/pull/47709) `[Doc] environ: Correct default values in the env var reference` |  | main | - |
| - | [#47711](https://github.com/sgl-project/sglang/pull/47711) `[Fix] multi-tokenizer: Record an abort that arrives before any worker holds the rid` | bug | main | - |
| - | [#47713](https://github.com/sgl-project/sglang/pull/47713) `[Perf] [NPU] dsv4: Reuse verify sequence lengths` | perf | main | - |
| - | [#47718](https://github.com/sgl-project/sglang/pull/47718) `[Perf] [NPU] Release temporary DeepSeek-V4 RoPE tables` | infra,perf | main | - |
| - | [#47719](https://github.com/sgl-project/sglang/pull/47719) `[Fix] [AMD] kernels: Fix ROCm 7.0 mHC compilation and FP32 GEMM` | bug,perf,rocm | main | - |
| - | [#47720](https://github.com/sgl-project/sglang/pull/47720) `[Perf] [NPU] Bound DeepSeek-V4 prefill query intermediates` | perf | main | - |
| - | [#47721](https://github.com/sgl-project/sglang/pull/47721) `[Perf] [NPU] Bound DeepSeek-V4 RoPE tables by serving context` | perf | main | - |
| - | [#47722](https://github.com/sgl-project/sglang/pull/47722) `[Feat] observability: Add request-level frontend wall-time histograms` |  | main | - |
| - | [#47726](https://github.com/sgl-project/sglang/pull/47726) `[Chore] rust: Pin the sgl-model-gateway toolchain to 1.92` | infra | main | - |
| - | [#47729](https://github.com/sgl-project/sglang/pull/47729) `[Feat] qwen3.5: Support native sequence classification` |  | main | - |
| - | [#47733](https://github.com/sgl-project/sglang/pull/47733) `[Fix] connector: Fix directory mutation and pattern filtering in `pull_files_from_db`` | bug | main | - |
| - | [#47734](https://github.com/sgl-project/sglang/issues/47734) `[Perf] sglang-kernel FA3 picks MmaPV_is_RS=false for hdim 128 non-causal on H200 (1.5-3% slower than flash-att` | infra,nvidia,perf | ? | - |
| - | [#47738](https://github.com/sgl-project/sglang/pull/47738) `[Perf] [AMD] fla: autotune the GDN chunk_fwd_kernel_o on ROCm` | perf,rocm | main | - |
| - | [#47739](https://github.com/sgl-project/sglang/pull/47739) `[Fix] speculative: Validate adaptive policy options before startup` | bug | main | - |
| - | [#47740](https://github.com/sgl-project/sglang/pull/47740) `[Perf] [NPU] dsv4: bound decode SWA storage by request slots` | perf | main | - |
| - | [#47745](https://github.com/sgl-project/sglang/pull/47745) `[Fix] diffusion: Harden component loaders: trust_remote_code gating, Ming overrides, meta-init upscaler` | bug,perf | main | - |
| - | [#47746](https://github.com/sgl-project/sglang/pull/47746) `[Fix] diffusion: SenseNova-U1: keep think tokens in attention, fix 4.x import and vision_model init` | bug,infra,perf | main | - |
| - | [#47748](https://github.com/sgl-project/sglang/pull/47748) `[Fix] dsv4: Add an opt-in deterministic sparse top-k for DeepSeek-V4.1` | bug,perf | main | - |
| - | [#47750](https://github.com/sgl-project/sglang/pull/47750) `[Fix] score: Validate logical item and MIS hidden-state row counts` | bug,infra | main | - |
| - | [#47751](https://github.com/sgl-project/sglang/pull/47751) `[Feat] speculative: Support synchronous STANDALONE PD handoff` |  | main | - |
| - | [#47752](https://github.com/sgl-project/sglang/pull/47752) `[Fix] session: Keep refused and OOM-aborted streaming turns out of the session` | bug,perf | main | - |
| - | [#47753](https://github.com/sgl-project/sglang/pull/47753) `[Fix] function_call: Stream prose that arrives in the same delta as the first tool call` | bug | main | - |
| - | [#47756](https://github.com/sgl-project/sglang/pull/47756) `[Fix] [AMD] diffusion: install amd-smi so FLUX.3 serves on ROCm on gfx1151` | bug,infra,perf,rocm | main | - |
| - | [#47757](https://github.com/sgl-project/sglang/pull/47757) `[Fix] disagg: Isolate malformed NIXL prefill bootstrap metadata` | bug | main | - |
| - | [#47759](https://github.com/sgl-project/sglang/issues/47759) `[Bug] Video input data still leak into logs at --log-requests-level 0/1` |  | ? | - |
| - | [#47760](https://github.com/sgl-project/sglang/pull/47760) `[Fix] Log: Skip leaked user input fields (e.g. video_config._question) via nested field skip support` | bug | main | - |
| - | [#47761](https://github.com/sgl-project/sglang/pull/47761) `[Perf] dsa: Use larger FP8 KV tiles for high query parallelism` | perf,quant | main | - |
| - | [#47762](https://github.com/sgl-project/sglang/pull/47762) `[Fix] diffusion: make VMoBA backend loadable and respect softmax_scale` | bug,perf | main | - |
| - | [#47763](https://github.com/sgl-project/sglang/issues/47763) `[RFC] Agent harness x SGLang: keep multi-turn agent prefixes cacheable` |  | ? | - |
| - | [#47764](https://github.com/sgl-project/sglang/issues/47764) `[Feature] attention: FlashInfer backend rejects ragged verify in CUDA graph` | nvidia | ? | - |
| - | [#47765](https://github.com/sgl-project/sglang/pull/47765) `[Perf] dflash: Fuse the simulated-acceptance overwrite into one kernel` | perf | main | - |
| - | [#47766](https://github.com/sgl-project/sglang/pull/47766) `[Fix] router: Forward disagg_prefill_dp_rank on DP-aware prefill PD requests` | bug | main | - |
| - | [#47767](https://github.com/sgl-project/sglang/pull/47767) `[Feat] mem_cache: Add native CUDA VMM fabric custom mem pool for MNNVL PD` | nvidia | main | - |
| - | [#47768](https://github.com/sgl-project/sglang/pull/47768) `[Perf] hicache: Extend prefix_keys in place across storage batches` | perf | main | - |
| - | [#47769](https://github.com/sgl-project/sglang/pull/47769) `[Feat] multimodal: Add bounded GPU feature publication admission` |  | main | - |
| - | [#47770](https://github.com/sgl-project/sglang/pull/47770) `[Perf] DFlash: Use CUDA graphs for draft and idle verify under DP attention` | nvidia,perf | trtllm-mha-pack-eager-page-table | - |
| - | [#47771](https://github.com/sgl-project/sglang/pull/47771) `[Fix] attention: Read sliding-window KV at its SWA slots in torch_native` | bug | main | - |
| - | [#47772](https://github.com/sgl-project/sglang/pull/47772) `[Fix] PD: Record decode handoff time for non-streaming metrics` | bug | main | - |
| - | [#47773](https://github.com/sgl-project/sglang/pull/47773) `[Fix] spec: Keep softmax batch-independent under deterministic inference` | bug,perf | main | - |
| - | [#47774](https://github.com/sgl-project/sglang/pull/47774) `[Perf] [AMD] fla/gdn: Faster GDN long-prompt prefill on gfx95 (chunk kernels, two-stream chunk scan, no host s` | perf,rocm | main | - |
| - | [#47778](https://github.com/sgl-project/sglang/pull/47778) `[Perf] [AMD] frontend: Encode long Qwen3.5-family chat prompts in parallel` | perf,rocm | main | - |
| - | [#47779](https://github.com/sgl-project/sglang/pull/47779) `[Perf] [AMD] qwen3_5: One wavefront per head and an in-place gate for the fused Q/K norm + RoPE + gate kernel` | perf,rocm | main | - |
| - | [#47780](https://github.com/sgl-project/sglang/pull/47780) `[Perf] [AMD] scheduler: Prefill the partial chunk of a long prompt first` | perf,rocm | main | - |
| - | [#47781](https://github.com/sgl-project/sglang/pull/47781) `[Fix] llguidance: Preserve token state on decode reentry` | bug | main | - |
| - | [#47783](https://github.com/sgl-project/sglang/issues/47783) `<!-- ccr-overview-v2 -->` |  | ? | - |
| - | [#47786](https://github.com/sgl-project/sglang/pull/47786) `[Feat] multimodal: Share CPU preprocessing artifacts across tokenizer workers` |  | main | - |
| - | [#47787](https://github.com/sgl-project/sglang/pull/47787) `[Perf] [NVIDIA] attention: Reuse the flashinfer MLA decode tactic for trtllm_mla eager decode` | nvidia,perf | main | - |
| - | [#47790](https://github.com/sgl-project/sglang/pull/47790) `[Feat] decisions: `--decision-config`, per-type default temperatures for ordinary chat models` |  | main | - |
| - | [#47792](https://github.com/sgl-project/sglang/pull/47792) `[Fix] frontend: Preserve routing keys when slicing generation requests` | bug | main | - |
| - | [#47793](https://github.com/sgl-project/sglang/pull/47793) `[Test] deterministic: Isolate backend arguments and fix sampling coverage` | bug | main | - |
| - | [#47794](https://github.com/sgl-project/sglang/pull/47794) `[Fix] quantization: Pad gated NVFP4 CUTLASS MoE projections` | bug,nvidia,quant | main | - |
| - | [#47795](https://github.com/sgl-project/sglang/pull/47795) `[Test] sampling: Cover hash boundaries and seeded batch invariance` |  | main | - |
| - | [#47796](https://github.com/sgl-project/sglang/pull/47796) `[Doc] metrics: Explain scheduler load and queueing signals` |  | main | - |
| - | [#47797](https://github.com/sgl-project/sglang/issues/47797) `[RFC] Define per-request speculative decoding opt-out execution semantics` |  | ? | - |
| - | [#47798](https://github.com/sgl-project/sglang/pull/47798) `[CI] cp: Disable the CP8 TP-decode B300 server test while it fails` | infra | main | - |
| - | [#47799](https://github.com/sgl-project/sglang/pull/47799) `[Fix] models: Phi-3-4k ignores its 2047-token sliding window (output breaks past 2k tokens)` | bug | main | - |
| - | [#47800](https://github.com/sgl-project/sglang/pull/47800) `[Fix] batch-invariant: deterministic mode runs fp32 matmuls in TF32 (Gemma 3 breaks past 2k tokens)` | bug | main | - |
| - | [#47801](https://github.com/sgl-project/sglang/issues/47801) `[Bug] [AMD] diffusion: Qwen-Image 2.1 VAE decode is not deterministic at 1024x1024 on ROCm (math SDPA in the R` | infra,perf,rocm | ? | - |
| - | [#47802](https://github.com/sgl-project/sglang/pull/47802) `[Fix] attention: Triton decode reads wrong KV head for GQA groups > 16 not divisible by 16 (GLM-4-32B breaks)` | bug,perf,rocm | main | - |
| - | [#47803](https://github.com/sgl-project/sglang/pull/47803) `[Perf] [Apple] layernorm: Add a Metal RMSNorm for the Torch MPS path` | perf | main | - |
| - | [#47805](https://github.com/sgl-project/sglang/pull/47805) `[Perf] diffusion: Use O(1) free-list sets in BuddyAllocator and deque in DisaggMetrics` | perf | main | - |
| - | [#47806](https://github.com/sgl-project/sglang/pull/47806) `[Chore] ci: Update test est_time values` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47807](https://github.com/sgl-project/sglang/pull/47807) `[Perf] [NVIDIA] serving: LayerNorm SP min tokens, DFLASH overlap, small-batch reject sampling, HiCache host si` | bug,nvidia,perf,quant | main | - |
| - | [#47808](https://github.com/sgl-project/sglang/pull/47808) `[Feat] deepseek-recipe: [sglang-miles] Expose convert and encode_conversation on DeepSeekRecipe` |  | sglang-miles | - |
| - | [#47809](https://github.com/sgl-project/sglang/pull/47809) `[Fix] attention: Honor custom masks past the causal tile in Triton extend` | bug,perf,rocm | main | - |
| - | [#47811](https://github.com/sgl-project/sglang/pull/47811) `[Fix] [NPU] kimi-k3: Split QKV/G projections for mixed ModelSlim precision` | bug | main | - |
| - | [#47813](https://github.com/sgl-project/sglang/pull/47813) `[Fix] [AMD] aiter: Decode DCP over a non-fp8 KV cache on Gluon instead of the asm kernel` | bug,perf,quant,rocm | main | - |
| - | [#47814](https://github.com/sgl-project/sglang/pull/47814) `[Fix] [AMD] aiter: Refuse an MLA draft model under DCP with a clear error` | bug,perf,rocm | main | - |
| - | [#47816](https://github.com/sgl-project/sglang/pull/47816) `[Fix] sampling: Allow seeded min-p sampling in the torch sampler` | bug | main | - |
| - | [#47817](https://github.com/sgl-project/sglang/pull/47817) `[Perf] moe: Skip compiled TopK postprocess when metadata is absent` | perf | main | - |
| - | [#47818](https://github.com/sgl-project/sglang/pull/47818) `[Feat] HttpServerEngineAdapter: forward memory-release tags and expose pause/continue_generation` | infra | main | - |
| - | [#47819](https://github.com/sgl-project/sglang/pull/47819) `[Perf] deepseek-v4: Avoid unused Torch hc_pre wrapper in capture mode` | perf | main | - |
| - | [#47820](https://github.com/sgl-project/sglang/pull/47820) `[Fix] diffusion: Ensure deterministic VAE decode on ROCm for Qwen-Image 2.1` | bug,perf,rocm | main | - |
| - | [#47824](https://github.com/sgl-project/sglang/pull/47824) `[Fix] [Intel] gemma4: Enable GPTQ INT4 inference on CPU` | bug,perf,quant | main | - |
| - | [#47827](https://github.com/sgl-project/sglang/issues/47827) `[Bug] Simulator Replay startup eagerly imports optional AIConfigurator dependency` |  | ? | - |
| - | [#47828](https://github.com/sgl-project/sglang/pull/47828) `[Fix] simulator: Lazily import optional AIConfigurator dependency` | bug,infra | main | - |
| - | [#47830](https://github.com/sgl-project/sglang/issues/47830) `[Bug] Hybrid Mamba model + EAGLE: KV-cache sizing error says to raise --mem-fraction-static when the Mamba sta` | perf | ? | - |
| - | [#47831](https://github.com/sgl-project/sglang/pull/47831) `[Feat] diffusion: support BRIA Fibo 2.0 generation and editing` | perf | main | - |
| - | [#47833](https://github.com/sgl-project/sglang/pull/47833) `[Perf] R3: Add --routed-experts-dtype int16 to halve the routed-expert host cache` | infra,perf | main | - |
| - | [#47834](https://github.com/sgl-project/sglang/issues/47834) `[NPU] Investigate fused masked attention for pi0.5 VLA inference` | perf | ? | - |
| - | [#47838](https://github.com/sgl-project/sglang/pull/47838) `[Fix] http_server: Start HTTP workers with lazy CUDA module loading` | bug,nvidia | main | - |
| - | [#47839](https://github.com/sgl-project/sglang/pull/47839) `[Perf] [AMD] mori/Qwen3.5: Send replicated KV heads as pages across P/D attention TP mismatch` | perf,rocm | main | - |
| - | [#47840](https://github.com/sgl-project/sglang/pull/47840) `[Fix] disaggregation: fix HiSparse spec PD transfer on PP>1 prefill` | bug | main | - |
| - | [#47841](https://github.com/sgl-project/sglang/pull/47841) `[Fix] transcription: Serve /v1/audio/transcriptions for Qwen3-Omni and Gemma 4` | bug | main | - |
| - | [#47842](https://github.com/sgl-project/sglang/pull/47842) `[Fix] diffusion: Enable Cosmos 3 Edge and Nano fused QK-norm/RoPE on SM 120` | bug,infra,perf | main | - |
| - | [#47843](https://github.com/sgl-project/sglang/pull/47843) `[muse_spark] serve LoRA on the text layers only` |  | backup/sglang-miles-muse-spark-open-20261019 | - |
| - | [#47845](https://github.com/sgl-project/sglang/pull/47845) `[Fix] mem_cache: report Mamba state cache when it exhausts the KV budget` | bug,perf | main | - |
| - | [#47846](https://github.com/sgl-project/sglang/pull/47846) `[Fix] hicache: Bound CPU collective waits and watch idle event polling` | bug,infra | main | - |
| - | [#47848](https://github.com/sgl-project/sglang/pull/47848) `[Fix] [Apple] mlx: Initialize Mamba checkpoint grid for auxiliary radix cache` | bug,perf | main | - |
| - | [#47849](https://github.com/sgl-project/sglang/pull/47849) `[Perf] kimi-k3: Reduce latent-up weight memory on TP8 decode workers` | perf | main | - |
| - | [#47850](https://github.com/sgl-project/sglang/pull/47850) `[Fix] mem_cache: broadcast packed draft layers in the MLA dedup linker` | bug,perf | main | - |
| - | [#47851](https://github.com/sgl-project/sglang/pull/47851) `[Perf] [NVIDIA] mla: Serve mixed-batch decode rows with the absorbed decode kernel` | nvidia,perf | main | - |
| - | [#47854](https://github.com/sgl-project/sglang/pull/47854) `[Feat] benchmark: add rerank benchmark client` | perf | main | - |
| - | [#47855](https://github.com/sgl-project/sglang/pull/47855) `[Feat] [CPU] model: Support Ling models on CPU` |  | main | - |
| - | [#47856](https://github.com/sgl-project/sglang/pull/47856) `[Fix] [NPU] diffusion: :bug: Fix profiler patches and daemon trace parsing` | bug,perf | main | - |
| - | [#47857](https://github.com/sgl-project/sglang/pull/47857) `[Feat] [NPU] attention: enable mixed-chunk for pure MLA on the ascend backend` | infra | main | - |
| - | [#47859](https://github.com/sgl-project/sglang/pull/47859) `[Feat] moe: Add Mooncake Elastic EP scale-up support` | infra,quant | main | - |
| - | [#47862](https://github.com/sgl-project/sglang/pull/47862) `[Feat] [AMD] aiter: One folder of in-tree aiter tuned rows for every model` | infra,perf,rocm | main | - |
| - | [#47863](https://github.com/sgl-project/sglang/pull/47863) `[Fix] Apply user stop strings only to the final answer, not the reasoning section` | bug | main | - |
| - | [#47864](https://github.com/sgl-project/sglang/pull/47864) `[Fix] tool-call: enforce parallel_tool_calls=false for tool_choice=auto` | bug | main | - |
| - | [#47867](https://github.com/sgl-project/sglang/pull/47867) `[Feat] [AMD] hicache: Add --hicache-mamba-size-gb to pin the HiCache Mamba host pool size` | infra,rocm | main | - |
| - | [#47868](https://github.com/sgl-project/sglang/issues/47868) `[Bug] SMG PowerOfTwoPolicy does not track in-flight requests in regular HTTP routing` |  | ? | - |
| - | [#47869](https://github.com/sgl-project/sglang/pull/47869) `[Perf] diffusion: Fuse LTX video VAE normalization and padding` | infra,perf | main | - |
| - | [#47870](https://github.com/sgl-project/sglang/pull/47870) `[Fix] [AMD] ct-fp8-moe: Mark the pre-shuffled CT FP8 MoE weights is_shuffled` | bug,infra,quant,rocm | main | - |
| - | [#47871](https://github.com/sgl-project/sglang/pull/47871) `[Fix] gateway: Track in-flight requests for every policy in regular HTTP routing` | bug | main | - |
| - | [#47872](https://github.com/sgl-project/sglang/pull/47872) `[Perf] [AMD] dsa: Opt-in single-pass Triton top-k for long-context decode rows` | infra,perf,rocm | main | - |
| - | [#47873](https://github.com/sgl-project/sglang/pull/47873) `[Fix] engram: create the shared host table without os.memfd_create` | bug | main | - |
| - | [#47874](https://github.com/sgl-project/sglang/pull/47874) `[Fix] SMG: Track in-flight requests for P2C in regular HTTP routing` | bug | main | - |
| - | [#47876](https://github.com/sgl-project/sglang/pull/47876) `[Feat] mamba: Support strided destination conv-state pools in the conv-window scatter` | infra,perf | main | - |
| - | [#47877](https://github.com/sgl-project/sglang/pull/47877) `[Feat] metrics: expose detokenizer worker processing time` |  | main | - |
| - | [#47878](https://github.com/sgl-project/sglang/pull/47878) `[Perf] attention: Run dense causal prefill when QSA block selection is exhaustive` | perf | main | - |
| - | [#47879](https://github.com/sgl-project/sglang/pull/47879) `[Refactor] [NPU] dsv4: consume registered sgl-kernel-npu Transformer APIs` | perf | main | - |
| - | [#47882](https://github.com/sgl-project/sglang/pull/47882) `[Feat] qwen4_exp: Support the MXFP8 PLE table of compressed-tensors checkpoints` | infra,quant | main | - |
| - | [#47883](https://github.com/sgl-project/sglang/pull/47883) `[Fix] speculative: Align all spec workers on the scheduler-facing forward_batch_generation signature` | bug | main | - |
| - | [#47884](https://github.com/sgl-project/sglang/pull/47884) `[Fix] multimodal: Prevent circular boundary wraparound in BaseMultimodalProcessor.get_mm_items_offset` | bug | main | - |
| - | [#47885](https://github.com/sgl-project/sglang/pull/47885) `[NPU] Prototype opt-in fused masked attention for pi0.5` | perf | main | - |
| - | [#47886](https://github.com/sgl-project/sglang/pull/47886) `[Fix] [AMD] w8a8_fp8: Load and run per-channel FP8 DeepSeek-V4 checkpoints on ROCm` | bug,quant,rocm | main | - |
| - | [#47887](https://github.com/sgl-project/sglang/pull/47887) `[Fix] config: Keep --decrypted-draft-config-file across the config registry reload` | bug | main | - |
| - | [#47888](https://github.com/sgl-project/sglang/pull/47888) `[Perf] [AMD] dsv4: Token-parallel prefill on ROCm (opt-in)` | perf,rocm | main | - |
| - | [#47889](https://github.com/sgl-project/sglang/pull/47889) `[Perf] cosmos3: optimize Sim-Bimanual kv cache management` | infra,perf | main | - |
| - | [#47890](https://github.com/sgl-project/sglang/pull/47890) `[Feat] RL: Publish runner weights over MoRI-IO for peer weight writes` | rocm | sglang-miles | - |
| - | [#47891](https://github.com/sgl-project/sglang/pull/47891) `[Feat] [XPU] graph: add context-aware support for XPU graph` | infra,nvidia | main | - |
| - | [#47893](https://github.com/sgl-project/sglang/pull/47893) `[Perf] [NVIDIA] glm5_next: Run the fused KDA decode kernel at 8 and 16 heads per rank` | infra,nvidia,perf | main | - |
| - | [#47895](https://github.com/sgl-project/sglang/pull/47895) `[Fix] [NVIDIA] qwen: Bound serving allocations and handle empty and grayscale inputs` | bug,nvidia,perf | main | - |
| - | [#47896](https://github.com/sgl-project/sglang/issues/47896) `[Bug] Qwen3.5 GatedDeltaNet: finalize_fused_in_proj builds the fused in_proj weight on CPU under --cpu-offload` | perf | ? | - |
| - | [#47897](https://github.com/sgl-project/sglang/pull/47897) `[Perf] [AMD] dsa: In-tree gfx950 paged MQA logits for decode / MTP-verify rows` | infra,perf,rocm | main | - |
| - | [#47899](https://github.com/sgl-project/sglang/pull/47899) `[Fix] qwen3.5: Keep CPU-offloaded GDN input projections separate` | bug,infra | main | - |
| - | [#47901](https://github.com/sgl-project/sglang/pull/47901) `[Feature] multimodal: Cache token-space media features per item before loading` | perf | rockdu-dev-mm-v2/10-strategy-media-declarations | - |
| - | [#47903](https://github.com/sgl-project/sglang/pull/47903) `[Feature] multimodal: [sglang-miles] Cache token-space media features per item before loading` | perf | sglang-miles | - |
| - | [#47904](https://github.com/sgl-project/sglang/pull/47904) `[Fix] moe: Refuse mxfp8 trtllm-gen MoE runner on consumer Blackwell` | bug,nvidia,perf,quant | main | - |
| - | [#47905](https://github.com/sgl-project/sglang/pull/47905) `[Feat] [NVIDIA] attention: add SM100 Q8KV8 sparse MLA kernel as the q8kv8_sm100 DSA backend` | nvidia,perf | main | - |
| - | [#47906](https://github.com/sgl-project/sglang/pull/47906) `[Perf] [AMD] minimax-sparse: Persist Triton autotune results across server restarts` | perf,rocm | main | - |
| - | [#47908](https://github.com/sgl-project/sglang/pull/47908) `[Fix] [AMD] quark: Match aiter's column-major scale layout in the MXFP4 quant fake` | bug,infra,quant,rocm | main | - |
| - | [#47909](https://github.com/sgl-project/sglang/pull/47909) `[Perf] [AMD] triton: Scale KV cache writes out of place and drop the extend K/V clones` | perf,quant,rocm | main | - |
| - | [#47910](https://github.com/sgl-project/sglang/pull/47910) `[Perf] [AMD] aiter: Split the fused-QKV q slice into heads without a copy in batch prefill` | perf,rocm | main | - |
| - | [#47911](https://github.com/sgl-project/sglang/pull/47911) `[Fix] [AMD] aiter: Skip the unused decode workspace on the vectorized_5d KV layout` | bug,infra,rocm | main | - |
| - | [#47912](https://github.com/sgl-project/sglang/pull/47912) `[Perf] [AMD] mxfp8: Split K in the gfx950 dot_scaled GEMM for underfilled decode grids` | perf,quant,rocm | main | - |
| - | [#47913](https://github.com/sgl-project/sglang/pull/47913) `[Perf] [NVIDIA] trtllm_mla: Build fp8 chunked-prefill Q/K/V in one launch` | infra,nvidia,perf,quant | main | - |
| - | [#47914](https://github.com/sgl-project/sglang/pull/47914) `[Perf] radix_cache: page-stride prefix matching and bigram boundary preservation` | perf | main | - |
| - | [#47916](https://github.com/sgl-project/sglang/issues/47916) `[Bug] [mamba/hybrid] MambaPool.copy_from gathers all source temporal states into one temporary (n x state_size` | nvidia | ? | - |
| - | [#47917](https://github.com/sgl-project/sglang/pull/47917) `[Feat] [NPU] longcat: Support Longcat2.0 for arch22 NPU` |  | main | - |
| - | [#47918](https://github.com/sgl-project/sglang/pull/47918) `[Fix] qwen2.5-vl: use per-frame cu_seqlens for video full attention` | bug | main | - |
| - | [#47919](https://github.com/sgl-project/sglang/pull/47919) `[PD] Support decode KV restore with Linker prefetch` | perf | main | - |
| - | [#47920](https://github.com/sgl-project/sglang/pull/47920) `[Fix] Support Qwen prefill CP with whole-expert EP and optimize NIXL KV transfers` | bug,perf | main | - |
| - | [#47921](https://github.com/sgl-project/sglang/pull/47921) `[Feat] [Apple] mps: Serve Unlimited-OCR v2 BF16 on the Torch MPS runtime` | perf,quant | main | - |
| - | [#47922](https://github.com/sgl-project/sglang/pull/47922) `[Fix] eplb: Skip draft recording and reuse NPU TP groups` | bug | main | - |
| - | [#47923](https://github.com/sgl-project/sglang/pull/47923) `[Feat] [AMD] tokenizer: Install fastokens in the ROCm image` | infra,rocm | main | - |
| - | [#47925](https://github.com/sgl-project/sglang/pull/47925) `ci run` | infra | main | - |
| - | [#47930](https://github.com/sgl-project/sglang/pull/47930) `[Feat] [NVIDIA] megakernel: Support prefill and extend steps` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47932](https://github.com/sgl-project/sglang/issues/47932) `[Bug] expert_distribution_recorder records all-zero counts under `flashinfer_trtllm` (BYPASSED TopK skips the ` | nvidia | ? | - |
| - | [#47934](https://github.com/sgl-project/sglang/pull/47934) `[Fix] [NPU] dsv4: transfer A3 C4 state using peer-local rows` | bug | main | - |
| - | [#47936](https://github.com/sgl-project/sglang/pull/47936) `[Fix] spec: Record spec-v2 tensors by device type, not is_cuda` | bug | main | - |
| - | [#47937](https://github.com/sgl-project/sglang/pull/47937) `[Fix] [NPU] dsv4: preserve empty PD state components across PP stages` | bug | main | - |
| - | [#47938](https://github.com/sgl-project/sglang/pull/47938) `[Fix] [AMD] dsv4: transfer unified C4 state by request-local rows` | bug,rocm | main | - |
| - | [#47939](https://github.com/sgl-project/sglang/pull/47939) `[Fix] attention: Restore block pointers on Triton 3.9 for FLA kernels (cherry-pick #45470)` | bug,perf,rocm | amd_march | - |
| - | [#47941](https://github.com/sgl-project/sglang/pull/47941) `[Fix] sampler: Avoid a host read in the torch top-k / top-p / min-p sampler` | bug,infra | main | - |
| - | [#47942](https://github.com/sgl-project/sglang/pull/47942) `[WIP][Feat] [NPU] Support Jet-Nemotron inference on Ascend NPU` | perf | main | - |
| - | [#47943](https://github.com/sgl-project/sglang/pull/47943) `[Fix] ZeroMQ broadcast: make blocking send wait for queue space` | bug | main | - |
| - | [#47945](https://github.com/sgl-project/sglang/pull/47945) `[Test] Add CPU unit coverage for MTP weight filtering` |  | main | - |
| - | [#47946](https://github.com/sgl-project/sglang/pull/47946) `[CI] [AMD] ci: Name AMD suites, jobs and runners as CUDA does` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#47947](https://github.com/sgl-project/sglang/pull/47947) `[Fix] sampling: Apply additive penalties before repetition scaling` | bug | main | - |
| - | [#47948](https://github.com/sgl-project/sglang/pull/47948) `[Perf] diffusion: Fuse LTX-2.3 vocoder resampling and SnakeBeta` | infra,perf | main | - |
| - | [#47950](https://github.com/sgl-project/sglang/pull/47950) `[Perf] parser: Avoid O(N^2) buffer copies and scans in BaseReasoningFormatDetector streaming` | perf | main | - |
| - | [#47952](https://github.com/sgl-project/sglang/pull/47952) `[CI] mscclpp: Introduce CI for MSCCL++ all-reduce on the single-node 8-GPU H200 runner` | infra,nvidia | main | - |
| - | [#47953](https://github.com/sgl-project/sglang/pull/47953) `[Perf] diffusion: Cache FLUX.2 Klein reference K/V across steps` | infra,perf | main | - |
| - | [#47956](https://github.com/sgl-project/sglang/pull/47956) `[Feat] xpu: Consolidate simple XPU enablements` | infra,nvidia,perf,quant | main | - |
| - | [#47958](https://github.com/sgl-project/sglang/pull/47958) `[Fix] diffusion: Apply RoPE to the FLUX.2-dev negative CFG branch` | bug,perf | main | - |
| - | [#47959](https://github.com/sgl-project/sglang/pull/47959) `[Chore] sgl-router: decouple preprocessing from app state` | infra | main | - |
| - | [#47961](https://github.com/sgl-project/sglang/pull/47961) `[Feat] [Intel] disaggregation: Support Intel XPU in the EPD multimodal encoder path` | infra,nvidia | main | - |
| - | [#47964](https://github.com/sgl-project/sglang/pull/47964) `[Feat] [AMD] custom-all-reduce: Run the JIT custom all-reduce v2 on ROCm` | infra,perf,rocm | main | - |
| - | [#47965](https://github.com/sgl-project/sglang/pull/47965) `[Feat] spec: add per-request speculative decoding opt-out with mixed-batch support (#47797)` |  | main | - |
| - | [#47966](https://github.com/sgl-project/sglang/pull/47966) `[Feat] spec: support adaptive speculative decoding for STANDALONE worker` |  | main | - |
| - | [#47967](https://github.com/sgl-project/sglang/pull/47967) `[Fix] [XPU] sampling: Make deterministic top-k renorm reproducible on XPU` | bug,nvidia | main | - |
| - | [#47968](https://github.com/sgl-project/sglang/pull/47968) `[Refactor] multimodal: Share the CUDA VMM chunk copy and let the transport pick its pool class` | infra,nvidia | main | - |
| - | [#47970](https://github.com/sgl-project/sglang/pull/47970) `[Test] cp: Re-enable the CP8 TP-decode server test with measured logprob bounds` |  | main | - |
| - | [#47972](https://github.com/sgl-project/sglang/pull/47972) `[CI] [AMD] amd-ci: Pass optional HF proxy env into the CI container` | infra,rocm | main | - |
| - | [#47973](https://github.com/sgl-project/sglang/pull/47973) `[Fix] attention: Use int64 token offsets in layernorm_gated and fused_qk_rmsnorm_rope_gate` | bug,perf | main | - |
| - | [#47974](https://github.com/sgl-project/sglang/pull/47974) `[Fix] debug_utils: Stop grafter tests hanging on a reused port` | bug | main | - |
| - | [#47975](https://github.com/sgl-project/sglang/pull/47975) `[Feat] embedding: Accept chat-style messages on /v1/embeddings` |  | main | - |
| - | [#47977](https://github.com/sgl-project/sglang/pull/47977) `[Feat] mm: Add --disable-multimodal to serve a multimodal model text-only` | infra | main | - |
| - | [#47978](https://github.com/sgl-project/sglang/pull/47978) `[Chore] sgl-router: move tokenizer prompt logic out of policies` | infra | main | - |
| - | [#47980](https://github.com/sgl-project/sglang/pull/47980) `[Test] cp: Add a diagnostic for the CP8 TP-decode logprob gap (do not merge)` |  | main | - |
| - | [#47981](https://github.com/sgl-project/sglang/pull/47981) `[Feat] [NVIDIA] weight-sync: Add GPU-delta in-place weight updates` | nvidia | main | - |
| - | [#47982](https://github.com/sgl-project/sglang/pull/47982) `[Feat] dflash: Shared context K/V drafts with a one-layer draft KV pool` |  | main | - |
| - | [#47983](https://github.com/sgl-project/sglang/pull/47983) `[Perf] [AMD] diffusion: Fuse the FLUX.2 adaLN modulate and drop the Ulysses QKV copies` | perf,rocm | main | - |
| - | [#47984](https://github.com/sgl-project/sglang/pull/47984) `[Fix] mem_cache: Chunk MambaPool temporal state copy to avoid OOM spike` | bug,infra | main | - |
| - | [#47985](https://github.com/sgl-project/sglang/pull/47985) `[Perf] muse-spark: Overlap non-NVFP4 pre-expert norm with routing` | perf,quant | main | - |
| - | [#47986](https://github.com/sgl-project/sglang/pull/47986) `[Fix] function_call: Reject complete invalid Qwen JSON tool calls` | bug | main | - |
| - | [#47987](https://github.com/sgl-project/sglang/pull/47987) `[Fix] unified-memory: Realize the reclaim certificate that relief opens on the tri-pool` | bug | main | - |
| - | [#47988](https://github.com/sgl-project/sglang/pull/47988) `[Feat] cp: Radix cache for padded CP KV layouts` | perf | main | - |
| - | [#47991](https://github.com/sgl-project/sglang/pull/47991) `[Feat] speculative: Build adaptive spec states within an opt-in memory budget` | infra | main | - |
| - | [#47995](https://github.com/sgl-project/sglang/pull/47995) `[Feat] cp: Hierarchical cache for padded CP KV layouts` | perf | yonghao/cp-sharded-kv-radix | - |
| - | [#47999](https://github.com/sgl-project/sglang/pull/47999) `[CI] [NVIDIA] docker: Publish the CUDA 13.4 nightly image for x86_64 as well as aarch64` | infra,nvidia | main | - |
| - | [#48000](https://github.com/sgl-project/sglang/pull/48000) `[Doc] cookbook: Install MiniMax-M3.1-Flash from main and move GB / Hopper to nightly images` | nvidia | main | - |
| - | [#48006](https://github.com/sgl-project/sglang/pull/48006) `[Refactor] mem_cache: Name each unified window sub-pool by its own window length` | nvidia,perf | cheng/hot-fix/unified-kv-release-after-forward | - |
| - | [#48007](https://github.com/sgl-project/sglang/pull/48007) `[Refactor] mem_cache: Address prefix-tree window slots, cursors and evictions by sub-pool name` | perf | cheng/refactor/unified-kv-layout-planner | - |
| - | [#48008](https://github.com/sgl-project/sglang/pull/48008) `[Refactor] mem_cache: Gate unified page reuse and moves on one per-band page ledger` | nvidia,perf | cheng/refactor/unified-kv-move-safety | - |
| - | [#48009](https://github.com/sgl-project/sglang/pull/48009) `[Refactor] disaggregation: Track unified PD transfers per row and reuse their pages only once quiescent` | perf | cheng/refactor/unified-kv-window-rails | - |
| - | [#48010](https://github.com/sgl-project/sglang/pull/48010) `[Refactor] mem_cache: Give unified request rows one lifecycle state and one reset` | perf | cheng/refactor/unified-kv-page-ledger | - |
| - | [#48011](https://github.com/sgl-project/sglang/pull/48011) `[Refactor] mem_cache: Add a layout planner and request demand for the unified chain` | perf | cheng/refactor/unified-kv-planner-reclaim | - |
| - | [#48012](https://github.com/sgl-project/sglang/pull/48012) `[Refactor] mem_cache: Plan, admit and reclaim unified memory through one layout search` | nvidia,perf | cheng/refactor/unified-kv-float-placement | - |
| - | [#48013](https://github.com/sgl-project/sglang/pull/48013) `[Refactor] mem_cache: Give each window sub-pool its own host pool, PD entry and metrics` | perf | cheng/refactor/unified-kv-window-names | - |
| - | [#48014](https://github.com/sgl-project/sglang/pull/48014) `[Feat] attention: Serve several window sub-pools per runner in the Triton backend` | nvidia,perf,rocm | cheng/refactor/unified-kv-pd-window-entries | - |
| - | [#48027](https://github.com/sgl-project/sglang/pull/48027) `[Perf] entrypoints: Avoid O(N^2) request body chunk concatenation in RequestDecompressionMiddleware` | perf | main | - |
| - | [#48030](https://github.com/sgl-project/sglang/pull/48030) `[Refactor] [NPU] graph: Enable breakable prefill graphs on Ascend NPU` |  | main | - |
| - | [#48031](https://github.com/sgl-project/sglang/pull/48031) `Npu/hicache sparse copy` |  | main | - |
| - | [#48033](https://github.com/sgl-project/sglang/pull/48033) `[Feat] embedding: Add Cohere-compatible /v2/embed API` |  | main | - |
| - | [#48034](https://github.com/sgl-project/sglang/pull/48034) `[Fix] function_call: Parse null and exponent numbers in Gemma4 tool calls` | bug | main | - |
| - | [#48035](https://github.com/sgl-project/sglang/pull/48035) `[Perf] mem_cache: Fuse INT8 Mamba checkpoint quantization and restore` | perf,quant | main | - |
| - | [#48036](https://github.com/sgl-project/sglang/pull/48036) `[Perf] diffusion: Parallelize heavy component loading` | perf | main | - |
| - | [#48038](https://github.com/sgl-project/sglang/pull/48038) `[Perf] [NVIDIA] eplb: Rebalance the DSpark draft MoE as its own placement family` | nvidia,perf | main | - |
| - | [#48040](https://github.com/sgl-project/sglang/pull/48040) `[Fix] minimax-m2: Keep values of nullable parameters and survive non-finite numbers` | bug | main | - |
| - | [#48042](https://github.com/sgl-project/sglang/pull/48042) `[Perf] [AMD] hicache: make the block_quota of the all-layer D2H backup copy configurable` | infra,perf,rocm | main | - |
| - | [#48043](https://github.com/sgl-project/sglang/pull/48043) `[Perf] [AMD] qwen3: Fuse the 1x128 FP8 input quant into RMSNorm and SiLU-and-mul for block-FP8 linears on gfx9` | infra,perf,quant,rocm | main | - |
| - | [#48044](https://github.com/sgl-project/sglang/pull/48044) `[Perf] [AMD] qwen3-next: Fuse the full-attention Q/K GemmaRMSNorm and partial RoPE into one Triton kernel on g` | infra,perf,rocm | main | - |
| - | [#48045](https://github.com/sgl-project/sglang/pull/48045) `feat: port Muse Spark Open support to sglang-miles` | nvidia,perf,rocm | sglang-miles | - |
| - | [#48046](https://github.com/sgl-project/sglang/pull/48046) `[Refactor] docker: Share the NVIDIA megakernel commit pin` | infra,nvidia | main | - |
| - | [#48047](https://github.com/sgl-project/sglang/pull/48047) `[Perf] hicache: add an optional minimum batch size for write_back eviction` | infra,perf | main | - |
| - | [#48048](https://github.com/sgl-project/sglang/pull/48048) `[Fix] model_loader: Bound CPU checkpoint retention in multithreaded PT loading` | bug | main | - |
| - | [#48049](https://github.com/sgl-project/sglang/pull/48049) `[Fix] mem_cache: Fix HiCache load-back rollback and pin handoff` | bug,infra,perf | main | - |
| - | [#48050](https://github.com/sgl-project/sglang/pull/48050) `[Perf] [NPU] embeddings: Fuse token remapping and vocabulary mask` | perf | main | - |
| - | [#48052](https://github.com/sgl-project/sglang/pull/48052) `[HiCache] Storage touch hook and prompt_cache_options.ttl retention hint` | perf | main | - |
| - | [#48059](https://github.com/sgl-project/sglang/pull/48059) `[Feat] [Intel] diffusion: SageAttention V3 for XPU self-attention` | nvidia,perf | main | - |
| - | [#48060](https://github.com/sgl-project/sglang/pull/48060) `[Feat] [Intel] diffusion: online MXFP8 on XPU` | nvidia,perf,quant | main | - |
| - | [#48063](https://github.com/sgl-project/sglang/pull/48063) `[Fix] tokenizer_manager: Leave room for max_new_tokens and reserved tokens when auto-truncating` | bug,risk | main | - |
| - | [#48064](https://github.com/sgl-project/sglang/pull/48064) `[Perf] [AMD] dsv4: aiter sparse prefill, fp8 wo_a and mxfp8_128 GEMM` | infra,perf,quant,rocm | main | - |
| - | [#48065](https://github.com/sgl-project/sglang/pull/48065) `[Fix] [AMD] dsv4: Fix the mHC weight orientation across layer boundaries` | bug,infra,rocm | main | - |
| - | [#48068](https://github.com/sgl-project/sglang/pull/48068) `[Perf] [AMD] dsv4: Route the DSV4 GEMMs through AITER` | perf,rocm | main | - |
| - | [#48069](https://github.com/sgl-project/sglang/pull/48069) `[Perf] [AMD] dsv4: Unified-KV attention kernels` | perf,rocm | main | - |
| - | [#48071](https://github.com/sgl-project/sglang/pull/48071) `[Fix] [NPU] lora: Handle constexpr tuple offsets on older Triton` | bug,perf,rocm | main | - |
| - | [#48072](https://github.com/sgl-project/sglang/pull/48072) `[Perf] [NVIDIA] dp-attention: Route the padding rows of the TP-MoE gather to no expert` | nvidia,perf | main | - |
| - | [#48073](https://github.com/sgl-project/sglang/pull/48073) `[Fix] qwen4-exp: Honor FP8 exclusions for PLE tables` | bug,quant | main | - |
| - | [#48074](https://github.com/sgl-project/sglang/pull/48074) `[Feat] [Intel] video_decoder: Decode video on the XPU media engine via torchcodec-xpu` | infra,nvidia | main | - |
| - | [#48076](https://github.com/sgl-project/sglang/pull/48076) `[Feat] scheduler: Add the UniBoost schedule policy` |  | main | - |
| - | [#48077](https://github.com/sgl-project/sglang/pull/48077) `[Feat] scheduler: Adapt the UniBoost gamma online from the response-time tail` |  | main | - |
| - | [#48078](https://github.com/sgl-project/sglang/pull/48078) `[Feat] scheduler: Bound UniBoost waits of requests that share a prefix` |  | main | - |
| - | [#48079](https://github.com/sgl-project/sglang/pull/48079) `[Feat] scheduler: UniBoost decode time-slicing for first-token-starved waiters` | rocm | main | - |
| - | [#48080](https://github.com/sgl-project/sglang/issues/48080) `[Feature]  Model registry: eager import of all model modules hides failures (one bad dependency → 0 models reg` |  | ? | - |
| - | [#48081](https://github.com/sgl-project/sglang/pull/48081) `[Fix] disaggregation: fix HiSparse staged-spec crash under DP-attention padding` | bug | main | - |
| - | [#48083](https://github.com/sgl-project/sglang/pull/48083) `[Fix] [AMD] attention: Default deterministic inference to Triton on HIP` | bug,rocm | main | - |
| - | [#48084](https://github.com/sgl-project/sglang/pull/48084) `[Fix] sampling: Make penalizer execution order deterministic` | bug | main | - |
| - | [#48085](https://github.com/sgl-project/sglang/pull/48085) `[Fix] lora: Skip unsupported embeddings when targeting all modules` | bug | main | - |
| - | [#48086](https://github.com/sgl-project/sglang/pull/48086) `[Fix] benchmark: Support Gemma 4 in the CSGMV LoRA tuner` | bug,perf | main | - |
| - | [#48088](https://github.com/sgl-project/sglang/pull/48088) `[Fix] Mooncake: Resolve per-worker MNNVL physical GPU` | bug,infra | main | - |
| - | [#48089](https://github.com/sgl-project/sglang/pull/48089) `[Fix] [AMD] modelopt: Support ModelOpt FP8 Nemotron models on gfx950` | bug,quant,rocm | main | - |
| - | [#48090](https://github.com/sgl-project/sglang/pull/48090) `[Perf] [AMD] spec: Skip the vocabulary-wide sort in MTP rejection-sampling verify` | infra,perf,rocm | main | - |
| - | [#48091](https://github.com/sgl-project/sglang/pull/48091) `[Perf] [NVIDIA] mxfp4: Bound SM90 preprocessing memory` | nvidia,perf,quant | main | - |
| - | [#48093](https://github.com/sgl-project/sglang/pull/48093) `[Perf] [AMD] dsv4: Cut HIP prefill and verify host overhead` | infra,perf,rocm | main | - |
| - | [#48094](https://github.com/sgl-project/sglang/pull/48094) `[Perf] [AMD] dsv4: Fuse the next RMSNorm into mhc_post_pre` | perf,rocm | main | - |
| - | [#48095](https://github.com/sgl-project/sglang/pull/48095) `[Perf] [AMD] dspark: Speed up the DSPARK draft step` | infra,perf,rocm | main | - |
| - | [#48096](https://github.com/sgl-project/sglang/pull/48096) `[Perf] radix-cache: Preserve long device prefixes during partial eviction` | perf | main | - |
| - | [#48097](https://github.com/sgl-project/sglang/pull/48097) `[Feat] [AMD] moe: Run AITER MegaMoEGfx1250 with the mori dispatch` | infra,rocm | main | - |
| - | [#48098](https://github.com/sgl-project/sglang/pull/48098) `[Feat] pd: Place prefill sessions by projected per-rank token load` |  | main | - |
| - | [#48100](https://github.com/sgl-project/sglang/pull/48100) `[Fix] scheduler: Clear setwise pooling positions when a request is aborted` | bug | main | - |
| - | [#48101](https://github.com/sgl-project/sglang/pull/48101) `[Test] [NPU] HiCache: Reduce host memory allocation` |  | main | - |
| - | [#48102](https://github.com/sgl-project/sglang/pull/48102) `[Fix] [NPU] Support bounded encoder-decoder SDPA graphs` | bug | release/v0.5.22 | - |
| - | [#48103](https://github.com/sgl-project/sglang/pull/48103) `[NPU] a5: fix vl models bug` | bug | main | - |
| - | [#48106](https://github.com/sgl-project/sglang/pull/48106) `[Feat] mem_cache: Elastic hybrid-SWA KV pools (kvcached VMM), with an Intel XPU path` | nvidia,perf | main | - |
| - | [#48107](https://github.com/sgl-project/sglang/pull/48107) `[Fix] modelopt-nvfp4: Resolve the automatic MoE runner once so the weight prep matches the kernel path` | bug,nvidia,perf,quant | main | - |
| - | [#48108](https://github.com/sgl-project/sglang/issues/48108) `[Bug] ModelOpt NVFP4 MoE crashes at warmup with AttributeError 'g1_scale_c' under the default --moe-runner-bac` | bug,nvidia,quant | ? | - |
| - | [#48110](https://github.com/sgl-project/sglang/pull/48110) `[Doc] [NVIDIA] qwen3: Add 16 GB consumer GPU (SM89) config tip to the cookbook` | nvidia | main | - |
| - | [#48112](https://github.com/sgl-project/sglang/pull/48112) `[Fix] mem_cache: Agree on one TreeCore backend across ranks sharing a prefix tree` | bug,perf | main | - |
| - | [#48113](https://github.com/sgl-project/sglang/pull/48113) `[Perf] [NVIDIA] gemm: Enable KDA FP8 skinny GEMM for K=3072, N=5120 at M=2/4/8` | nvidia,perf,quant | main | - |
| - | [#48114](https://github.com/sgl-project/sglang/pull/48114) `[Fix] kv-events: Retry replay batches under backpressure` | bug | main | - |
| - | [#48115](https://github.com/sgl-project/sglang/pull/48115) `[Perf] disaggregation: Avoid O(N^2) watermark maintenance in StagingAllocator.free` | perf | main | - |
| - | [#48116](https://github.com/sgl-project/sglang/pull/48116) `[Fix] function_call: Type the named tool_choice item schema as an object` | bug | main | - |
| - | [#48117](https://github.com/sgl-project/sglang/pull/48117) `[Fix] spec: Prune the draft branch instead of crashing when the grammar rejects a token` | bug,infra | main | - |
| - | [#48118](https://github.com/sgl-project/sglang/pull/48118) `[Perf] [AMD] gdn: Add an aiter backend for linear-chain target verify` | infra,perf,rocm | main | - |
| - | [#48120](https://github.com/sgl-project/sglang/pull/48120) `[Feat] disaggregation: Gate Mooncake session recovery on one real transfer trial` |  | main | - |
| - | [#48122](https://github.com/sgl-project/sglang/pull/48122) `[Perf] diffusion: Cache MiniMax-H3 reference and keyframe rows per image` | infra,perf | main | - |
| - | [#48124](https://github.com/sgl-project/sglang/pull/48124) `[Test] attention: Guard Muse Spark fused KV store writes` | perf | main | - |
| - | [#48126](https://github.com/sgl-project/sglang/pull/48126) `[Feat] [NPU] attention: Support Modelslim GQA mxfp8 kvcache for 950 NPU` | quant | main | - |
| - | [#48127](https://github.com/sgl-project/sglang/issues/48127) `[Bug] RadixArk/Muse-Glimmer-NVFP4 fails at load since #45632 (MXFP8 lm_head), and on Hopper also at DeepGEMM w` | nvidia,quant | ? | - |
| - | [#48128](https://github.com/sgl-project/sglang/pull/48128) `[Fix] quantization: Load Muse-Glimmer-NVFP4's MXFP8 lm_head, and run its MXFP8 dense layers as block-FP8 off B` | bug,infra,nvidia,quant | main | - |
| - | [#48130](https://github.com/sgl-project/sglang/pull/48130) `[Fix] fp8_utils: Import DeepGEMM lazily in transform_scale_ue8m0` | bug,quant | main | - |
| - | [#48132](https://github.com/sgl-project/sglang/pull/48132) `[Perf] qsa: Pass output_size to repeat_interleave in the graph speculative layout` | perf | main | - |
| - | [#48133](https://github.com/sgl-project/sglang/pull/48133) `[Fix] hicache: Correct DCP L2 transfer-byte accounting` | bug | main | - |
| - | [#48136](https://github.com/sgl-project/sglang/pull/48136) `[Refactor] memory-pool: Report device pool roles in buffer info` | infra,rocm | main | - |
| - | [#48137](https://github.com/sgl-project/sglang/pull/48137) `[Refactor] memory-pool: Bind HiCache entries to device pools by name` | infra,rocm | device-pool-info-roles | - |
| - | [#48138](https://github.com/sgl-project/sglang/pull/48138) `[Refactor] memory-pool: Move the NVFP4 host budget into its host module` | infra,nvidia,quant,rocm | device-pools-by-name | - |
| - | [#48139](https://github.com/sgl-project/sglang/pull/48139) `[Fix] models: Set k/v_scale_float when loading KV cache scales from file` | bug,perf,quant | main | - |
| - | [#48140](https://github.com/sgl-project/sglang/pull/48140) `[Fix] deepgemm: Handle missing CUDA toolkit during availability checks` | bug,nvidia | main | - |
| - | [#48142](https://github.com/sgl-project/sglang/pull/48142) `[Fix] moe: Preserve expert recording with TRT-LLM routing` | bug | main | - |
| - | [#48143](https://github.com/sgl-project/sglang/pull/48143) `[Fix] qwen3_coder: Keep non-finite numbers out of number parameters` | bug | main | - |
| - | [#48144](https://github.com/sgl-project/sglang/issues/48144) `[RFC] KV Cache Optimization for Cosmos3-Nano-Sim-Bimanual` | perf | ? | - |
| - | [#48145](https://github.com/sgl-project/sglang/issues/48145) `[Bug] Mooncake HiCache backup fails for Qwen3.8-Flash-Next-FP8` | quant | ? | - |
| - | [#48146](https://github.com/sgl-project/sglang/pull/48146) `[Perf] [AMD] dsv41: Run the HIP sparse prefill on the FP8 KV cache` | perf,quant,rocm | main | - |
| - | [#48148](https://github.com/sgl-project/sglang/pull/48148) `[Fix] [AMD] dsv4: Let breakable prefill graphs capture without the SWA tail` | bug,rocm | main | - |
| - | [#48149](https://github.com/sgl-project/sglang/pull/48149) `[Fix] dwdp: Retry local VMM allocation after CUDA OOM` | bug,nvidia | main | - |
| - | [#48150](https://github.com/sgl-project/sglang/issues/48150) `[Bug] fused_marlin_moe is not run-to-run deterministic on sm_90+ (atomic adds, moe_align_block_size token orde` | perf,quant | ? | - |
| - | [#48151](https://github.com/sgl-project/sglang/pull/48151) `[Fix] function_call: Infer number for schemas that allow integer or number` | bug | main | - |
| - | [#48152](https://github.com/sgl-project/sglang/pull/48152) `[Perf] [AMD] DeepSeek-V4.1: Shard the HIP prefill indexer rows across attention TP` | infra,perf,rocm | main | - |
| - | [#48153](https://github.com/sgl-project/sglang/pull/48153) `[Fix] qwen3.5: Fix encode server initialization bug.` | bug | main | - |
| - | [#48154](https://github.com/sgl-project/sglang/pull/48154) `[Perf] [AMD] mla: Use the gfx950 aiter RoPE, RMSNorm and MLA KV-row paths on gfx1250` | infra,perf,rocm | main | - |
| - | [#48156](https://github.com/sgl-project/sglang/pull/48156) `[Perf] hicache: Reduce host compaction copies by filling holes from boundary pages` | perf | main | - |
| - | [#48157](https://github.com/sgl-project/sglang/pull/48157) `[Perf] [XPU] mamba: Fuse the Mamba-1 prefill selective scan into one Triton kernel` | nvidia,perf,rocm | main | - |
| - | [#48159](https://github.com/sgl-project/sglang/pull/48159) `[Feat] diffusion: Support dynamic LoRA on GGUF transformers` | perf,quant | main | - |
| - | [#48161](https://github.com/sgl-project/sglang/pull/48161) `[Fix] lora: Support Qwen3.5 GDN packed projections` | bug | main | - |
| - | [#48162](https://github.com/sgl-project/sglang/pull/48162) `[Feat] [AMD] dsv4: FP4 indexer with natural layout and OPUS MQA logits` | perf,quant,rocm | main | - |
| - | [#48163](https://github.com/sgl-project/sglang/pull/48163) `[Fix] hicache: Register the whole host-pool allocation with Mooncake` | bug | main | - |
| - | [#48164](https://github.com/sgl-project/sglang/pull/48164) `[Fix] kimi-k3: Reuse the attention-residual bank across forward passes` | bug | main | - |
| - | [#48165](https://github.com/sgl-project/sglang/pull/48165) `[Perf] quantization: Speed up Hopper group32 FP8 quantization with FP32 scales` | infra,nvidia,perf,quant | main | - |
| - | [#48167](https://github.com/sgl-project/sglang/pull/48167) `[Feat] hicache: Register draft Mamba state pool` |  | main | - |
| - | [#48168](https://github.com/sgl-project/sglang/pull/48168) `[Test] [NPU] rl: Add sleep/wake scheduler unit and 1-NPU smoke tests` |  | main | - |
| - | [#48169](https://github.com/sgl-project/sglang/pull/48169) `[Test] [NPU] rl: Add pause/resume scheduler idempotency and 1-NPU smoke tests` |  | main | - |
| - | [#48171](https://github.com/sgl-project/sglang/pull/48171) `[Perf] diffusion: Share convrot_int8 input quantization across LTX-2 projections` | perf,quant | main | - |
| - | [#48172](https://github.com/sgl-project/sglang/issues/48172) `[Bug] --tool-call-parser auto finds no parser on Qwen2.5-0.5B, Qwen3 2507 and Ling-mini-2.0, so tool calls com` |  | ? | - |
| - | [#48173](https://github.com/sgl-project/sglang/pull/48173) `[Feat] [AMD] diffusion: Add MXFP6 and A6W4 online GEMM quantization` | perf,quant,rocm | main | - |
| - | [#48175](https://github.com/sgl-project/sglang/pull/48175) `[Fix] anthropic: don't reject adaptive thinking when there is no reasoning parser` | bug | main | - |
| - | [#48178](https://github.com/sgl-project/sglang/pull/48178) `[Fix] kimi-k3: Verify DFLASH on cutedsl_mla under DCP` | bug | main | - |
| - | [#48180](https://github.com/sgl-project/sglang/pull/48180) `[Fix] openai: Keep one BOS on text-only multimodal prompts` | bug | main | - |
| - | [#48181](https://github.com/sgl-project/sglang/pull/48181) `[Fix] rust-server: Parse JSON tool calls for named and required choices` | bug | main | - |
| - | [#48187](https://github.com/sgl-project/sglang/pull/48187) `[Fix] spec: Apply the multi-layer boundary-KV fix to non-hybrid chain MTP drafts` | bug | main | - |
| - | [#48188](https://github.com/sgl-project/sglang/pull/48188) `[Fix] spec: Keep chain MTP prefill hidden states under DP attention` | bug | main | - |
| - | [#48189](https://github.com/sgl-project/sglang/pull/48189) `[Feat] [NVIDIA] deepseek-v4: add opt-in row-wise MoE pipelines` | infra,nvidia | main | - |
| - | [#48190](https://github.com/sgl-project/sglang/pull/48190) `[CI] [AMD] rerun-test: Add `--amd` to rerun tests on their AMD runners` | infra,rocm | main | - |
| - | [#48191](https://github.com/sgl-project/sglang/pull/48191) `[Feat] diffusion/realtime: Add a client-side benchmark for realtime video sessions` | perf | main | - |
| - | [#48193](https://github.com/sgl-project/sglang/pull/48193) `[Fix] deps: add websockets so /v1/realtime works without extras` | bug,infra | main | - |
| - | [#48194](https://github.com/sgl-project/sglang/pull/48194) `[Fix] [AMD] kimi-k3: Restore the KDA in-proj fusion for quantized che…` | bug,perf,quant,rocm | main | - |
| - | [#48195](https://github.com/sgl-project/sglang/pull/48195) `[Feat] serving: Add --max-payload-size flag to raise the HTTP request payload limit` |  | main | - |
| - | [#48196](https://github.com/sgl-project/sglang/issues/48196) `[CI] diffusion: Wan VAE decode time spikes on the 1-gpu-5090 sm* runners` | infra,perf | ? | - |
| - | [#48197](https://github.com/sgl-project/sglang/pull/48197) `[AMD][Kimi-K3] Route radix4 on bf16 with the cached bias, drop the pe…` | rocm | main | - |
| - | [#48198](https://github.com/sgl-project/sglang/pull/48198) `[Fix] tokenizer: Isolate per-request failures and skip cancelled requests in AsyncDynamicBatchTokenizer` | bug | main | - |
| - | [#48200](https://github.com/sgl-project/sglang/pull/48200) `[Doc] diffusion: Document IMAGEIO_FFMPEG_EXE for faster MP4 encoding` | perf | main | - |
| - | [#48201](https://github.com/sgl-project/sglang/pull/48201) `[Fix] [AMD] layernorm: call vLLM fused_add_rms_norm in place` | bug,perf,rocm | main | - |
| - | [#48202](https://github.com/sgl-project/sglang/pull/48202) `[Refactor] dwdp: Route DWDP through a device-neutral VMM backend` |  | main | - |
| - | [#48203](https://github.com/sgl-project/sglang/pull/48203) `[Feat] [Intel] dwdp: Add a Level Zero VMM backend for DWDP on XPU` | nvidia,quant | main | - |
| - | [#48205](https://github.com/sgl-project/sglang/pull/48205) `[Perf] disaggregation: Add the just_in_time decode allocation policy` | perf | main | - |
| - | [#48206](https://github.com/sgl-project/sglang/issues/48206) `[CI] PD: Mooncake 'Memory region not registered by any active device(s)' fails a whole class on the 8-gpu-h20 ` | infra | ? | - |
| - | [#48207](https://github.com/sgl-project/sglang/pull/48207) `[Fix] routed-experts: reset routed_experts_start_len when a request is rejected at intake` | bug,infra | main | - |
| - | [#48208](https://github.com/sgl-project/sglang/pull/48208) `[Perf] speculative: batched top logprobs when every request asks the same k` | perf | main | - |
| - | [#48209](https://github.com/sgl-project/sglang/pull/48209) `[Perf] hicache: Skip satisfied Full host eviction heaps` | perf | main | - |
| - | [#48210](https://github.com/sgl-project/sglang/pull/48210) `[Feat] [Intel] sensenova: Run SenseNova-U1.5-8B-MoT on Arc Pro B60` | perf | main | - |
| - | [#48211](https://github.com/sgl-project/sglang/pull/48211) `[Fix] openai: do not render a null tool-level defer_loading` | bug | main | - |
| - | [#48212](https://github.com/sgl-project/sglang/pull/48212) `[Perf] openai: cache per-token text and bytes for logprob outputs` | perf,quant | main | - |
| - | [#48213](https://github.com/sgl-project/sglang/pull/48213) `[Fix] PD: Recover NIXL peers on the prefill across decode restarts and re-registrations` | bug | main | - |
| - | [#48214](https://github.com/sgl-project/sglang/pull/48214) `[Doc] cookbook: Capture prefill CUDA graphs up to 16384 tokens in the GLM-5.3-Flash B300 FP8 Low Latency recip` | nvidia,perf,quant | main | - |
| - | [#48215](https://github.com/sgl-project/sglang/issues/48215) `[Feature] diffusion: TP=2 support for GGUF with dynamic LoRA` | perf,quant | ? | - |
| - | [#48216](https://github.com/sgl-project/sglang/pull/48216) `[CI] proto: Publish protobuf module to Buf Schema Registry` | infra | main | - |
| - | [#48217](https://github.com/sgl-project/sglang/pull/48217) `[Refactor] custom-ar-v2: Single-word push epoch and consume-style pull semaphores` | infra,perf | main | - |
| - | [#48218](https://github.com/sgl-project/sglang/pull/48218) `[Perf] diffusion: Enable image-prefix sequence parallelism for ERNIE-Image` | infra,perf | main | - |
| - | [#48219](https://github.com/sgl-project/sglang/pull/48219) `[Fix] [AMD] moe: Keep is_shuffled on AITER-shuffled unquantized MoE weights` | bug,quant,rocm | main | - |
| - | [#48220](https://github.com/sgl-project/sglang/pull/48220) `[Fix] [NVIDIA] cosmos:Multi node execution fixes` | bug,nvidia,perf | main | - |
| - | [#48222](https://github.com/sgl-project/sglang/pull/48222) `[Feat] scheduler: Hardware governor that scales prefill knobs from GPU telemetry` | quant | main | - |
| - | [#48224](https://github.com/sgl-project/sglang/pull/48224) `[Perf] overlap: Stash the speculative relay in one launch` | perf | main | - |
| - | [#48225](https://github.com/sgl-project/sglang/issues/48225) `Add pinned model-file checksum verification to SGLang Diffusion loading` | infra,perf | ? | - |
| - | [#48226](https://github.com/sgl-project/sglang/pull/48226) `[Fix] scheduler: let a client abort yield to the stop or length cap of its step` | bug | main | - |
| - | [#48227](https://github.com/sgl-project/sglang/pull/48227) `[Feat] model-loader: cap the bytes the multithreaded loader keeps in flight` |  | main | - |
| - | [#48228](https://github.com/sgl-project/sglang/pull/48228) `[Fix] scheduler: use OpenAI's context-length wording when a prompt exceeds the KV pool` | bug | main | - |
| - | [#48232](https://github.com/sgl-project/sglang/issues/48232) `[RFC] Engine-free render service for sglang-processor over gRPC (Lower/Respond), including Messages and Respon` |  | ? | - |
| - | [#48233](https://github.com/sgl-project/sglang/pull/48233) `[Fix] [NVIDIA] deterministic: fix MLA backend selection on SM100` | bug,nvidia | main | - |
| - | [#48234](https://github.com/sgl-project/sglang/pull/48234) `[Fix] deepseek_v2: keep q_b_proj on one GEMM under deterministic inference` | bug | main | - |
| - | [#48235](https://github.com/sgl-project/sglang/pull/48235) `[Test] [NVIDIA] flash-attn: batch-invariance test for FA4 absorbed MLA` | nvidia | main | - |
| - | [#48236](https://github.com/sgl-project/sglang/pull/48236) `[Fix] moe: disable deferred finalize under deterministic inference` | bug | main | - |
| - | [#48237](https://github.com/sgl-project/sglang/pull/48237) `[Fix] [NVIDIA] deterministic: enable DeepGEMM BF16 deterministic mode when getter is absent` | bug,nvidia | main | - |
| - | [#48238](https://github.com/sgl-project/sglang/pull/48238) `[Fix] [NVIDIA] moe: keep DeepGEMM standard MoE layout on compact under deterministic inference` | bug,nvidia | main | - |
| - | [#48239](https://github.com/sgl-project/sglang/pull/48239) `[Perf] eager-runner: size the input registry by the prefill limit` | perf | main | - |
| - | [#48240](https://github.com/sgl-project/sglang/pull/48240) `[Perf] hybrid: drop residual host syncs from GDN extend` | perf | main | - |
| - | [#48241](https://github.com/sgl-project/sglang/pull/48241) `[Feat] weight-sync: let one serialized payload serve every TP rank` |  | sglang-miles | - |
| - | [#48242](https://github.com/sgl-project/sglang/pull/48242) `[Perf] [NVIDIA] fp8-gemm: 64x256 tiles for M just above a multiple of 256 on SM90` | nvidia,perf,quant | main | - |
| - | [#48247](https://github.com/sgl-project/sglang/pull/48247) `[Fix] http_server: skip the sglang launcher re-import in spawned uvicorn workers` | bug | main | - |
| - | [#48248](https://github.com/sgl-project/sglang/pull/48248) `[Feat] metrics: count prefill tokens lost to a missing cache component state` | perf | main | - |
| - | [#48249](https://github.com/sgl-project/sglang/pull/48249) `[Perf] qwen4: pin the offloaded PLE table at its exact size` | infra,perf | main | - |
| - | [#48250](https://github.com/sgl-project/sglang/pull/48250) `[Perf] [NVIDIA] qsa: JIT CUDA kernel for the indexer decode scoring` | nvidia,perf | main | - |
| - | [#48251](https://github.com/sgl-project/sglang/pull/48251) `[Perf] qsa: 64 CTAs per row for the mid-batch indexer decode` | perf | main | - |
| - | [#48252](https://github.com/sgl-project/sglang/pull/48252) `[Feat] qwen4: --ple-offload-token-embedding keeps embed_tokens in host memory` |  | main | - |
| - | [#48253](https://github.com/sgl-project/sglang/pull/48253) `[Fix] scheduler: keep auto-truncated prompts schedulable` | bug,risk | main | - |
| - | [#48254](https://github.com/sgl-project/sglang/pull/48254) `[Fix] routed-experts: return no tokens in the abort echo of a request whose routing is gone` | bug | main | - |
| - | [#48255](https://github.com/sgl-project/sglang/pull/48255) `[Feat] routed-experts: routed_experts_start_len=-1 returns one row per generated token` |  | main | - |
| - | [#48257](https://github.com/sgl-project/sglang/pull/48257) `[CI] diffusion: Skip the FLUX.3 disagg test when the gated model is unreachable` | infra,perf | main | - |
| - | [#48258](https://github.com/sgl-project/sglang/pull/48258) `[Perf] flashinfer: release the shared workspace when no backend uses it` | infra,nvidia,perf | main | - |
| - | [#48259](https://github.com/sgl-project/sglang/pull/48259) `[Fix] hicache: carry routed-experts rows through the host tier` | bug,perf | main | - |
| - | [#48260](https://github.com/sgl-project/sglang/issues/48260) `[Bug] DSA models crash on first prefill with --cpu-offload-gb: breakable prefill CUDA graph replays the DSA in` | bug,nvidia | ? | - |
| - | [#48261](https://github.com/sgl-project/sglang/pull/48261) `[Fix] hicache: Carry captured routing rows with KV between device and host` | bug,perf | main | - |
| - | [#48262](https://github.com/sgl-project/sglang/pull/48262) `[Perf] [NVIDIA] moe: Fused NVFP4 SwiGLU MoE kernel for SM120` | nvidia,perf,quant | main | - |
| - | [#48263](https://github.com/sgl-project/sglang/pull/48263) `[Perf] [NVIDIA] nvfp4: Fuse SiLU-and-mul with the next linear layer's NVFP4 activation quant` | nvidia,perf,quant | main | - |
| - | [#48267](https://github.com/sgl-project/sglang/pull/48267) `[Fix] deps: Use oss-harmony for offline GPT-OSS serving` | bug,infra | main | - |
| - | [#48268](https://github.com/sgl-project/sglang/pull/48268) `[Fix] moe: Make Marlin MoE deterministic under --enable-deterministic-inference` | bug,quant | main | - |
| - | [#48269](https://github.com/sgl-project/sglang/pull/48269) `[Feat] diffusion: Support dynamic full-matrix LoKr for single-GPU Z-Image` | perf | main | - |
| - | [#48270](https://github.com/sgl-project/sglang/pull/48270) `[Feat] scheduler: log host-device syncs by stage and call site` |  | main | - |
| - | [#48271](https://github.com/sgl-project/sglang/pull/48271) `[Perf] qsa: drop the per-layer RoPE cache length check in the indexer` | perf | main | - |
| - | [#48272](https://github.com/sgl-project/sglang/pull/48272) `[Fix] mem_cache: report the CUDA error when host registration fails` | bug,nvidia | main | - |
| - | [#48273](https://github.com/sgl-project/sglang/pull/48273) `[Fix] models: Pass HF sliding windows to RadixAttention without the query` | bug | main | - |
| - | [#48274](https://github.com/sgl-project/sglang/pull/48274) `[Perf] qsa: scale the indexer prefill scores inside the relative scoring kernel` | perf,quant | main | - |
| - | [#48275](https://github.com/sgl-project/sglang/pull/48275) `[Feat] hicache: debug check that load-backs restore the backed-up rows` |  | main | - |
| - | [#48276](https://github.com/sgl-project/sglang/pull/48276) `[Feat] weights: let a custom weight loader reject a tensor update cleanly` |  | main | - |
| - | [#48280](https://github.com/sgl-project/sglang/pull/48280) `[Fix] utils: Handle post-match KMP transition in TokenSequenceMatcher.advance` | bug | main | - |
| - | [#48281](https://github.com/sgl-project/sglang/pull/48281) `[Perf] diffusion/helios: Keep timestep conditioning compact` | infra,perf | main | - |
| - | [#48285](https://github.com/sgl-project/sglang/pull/48285) `[Feature] multimodal: [sglang-miles] Share the token-space item feature cache on disk` | perf | rockdu-dev-mm-v2-miles/12-item-feature-cache | - |
| - | [#48286](https://github.com/sgl-project/sglang/pull/48286) `[Feature] multimodal: [sglang-miles] Item feature cache key sanity check` | perf | rockdu-dev-mm-v2-miles/13-disk-item-feature-cache | - |
| - | [#48287](https://github.com/sgl-project/sglang/pull/48287) `[Feature] multimodal: Share the token-space item feature cache on disk` | perf | rockdu-dev-mm-v2/11-item-feature-cache | - |
| - | [#48288](https://github.com/sgl-project/sglang/pull/48288) `[Feature] multimodal: Item feature cache key sanity check` | perf | rockdu-dev-mm-v2/12-disk-item-feature-cache | - |
| - | [#48289](https://github.com/sgl-project/sglang/pull/48289) `[Fix] [NPU] memory-saver: Drain device before sleep unmap and preserve runtime tensor attrs` | bug | main | - |
| - | [#48291](https://github.com/sgl-project/sglang/pull/48291) `[Fix] model_loader: Stop checkpoint prefetch on interrupted weight loading` | bug | main | - |
| - | [#48293](https://github.com/sgl-project/sglang/pull/48293) `[Fix] hicache: Include Mamba slot side states in Mooncake storage` | bug | main | - |
| - | [#48294](https://github.com/sgl-project/sglang/pull/48294) `[Perf] gemm: Opt-in table of pinned bit-identical cuBLASLt algorithms for BF16 linears` | infra,perf,quant | main | - |
| - | [#48295](https://github.com/sgl-project/sglang/pull/48295) `[Feat] modelopt: Quantize block-FP8 MTP draft experts to NVFP4 for MIXED_PRECISION checkpoints` | quant | main | - |
| - | [#48296](https://github.com/sgl-project/sglang/pull/48296) `[Perf] [NVIDIA] qsa: split-K sparse decode kernel for fp8 KV` | nvidia,perf,quant | main | - |
| - | [#48297](https://github.com/sgl-project/sglang/pull/48297) `[Fix] responses: Recover malformed Harmony tool headers` | bug | main | - |
| - | [#48299](https://github.com/sgl-project/sglang/pull/48299) `[Fix] modelopt: Keep NVFP4 MoE experts intact across partial weight updates` | bug,nvidia,quant | main | - |
| - | [#48300](https://github.com/sgl-project/sglang/issues/48300) `[Feature][RFC] Preserve measured cache-write usage across PD handoff` | perf | ? | - |
| - | [#48302](https://github.com/sgl-project/sglang/pull/48302) `[Fix] [AMD] dsa: One decode graph variant on every attention-DP rank, one verify graph` | bug,infra,rocm | main | - |
| - | [#48303](https://github.com/sgl-project/sglang/pull/48303) `[Perf] [AMD] GLM5.3: Speed up KDA causal-conv and mHC pre prefill on gfx950` | perf,rocm | main | - |
| - | [#48304](https://github.com/sgl-project/sglang/pull/48304) `[Feature] multimodal: [sglang-miles] Write item feature cache entries behind the request` | perf | rockdu-dev-mm-v2-miles/14-item-feature-cache-check | - |
| - | [#48305](https://github.com/sgl-project/sglang/pull/48305) `[Feature] multimodal: [sglang-miles] Write each item feature cache key once` | perf | rockdu-dev-mm-v2-miles/15-item-feature-cache-write-behind | - |
| - | [#48306](https://github.com/sgl-project/sglang/pull/48306) `[Feature] multimodal: Write item feature cache entries behind the request` | perf | rockdu-dev-mm-v2/13-item-feature-cache-check | - |
| - | [#48307](https://github.com/sgl-project/sglang/pull/48307) `[Feature] multimodal: Write each item feature cache key once` | perf | rockdu-dev-mm-v2/14-item-feature-cache-write-behind | - |
| - | [#48308](https://github.com/sgl-project/sglang/pull/48308) `[Feat] [Intel] Model-enabling: Enable Nemotron-H models on Xeon CPU` | infra,perf,quant | main | - |
| - | [#48309](https://github.com/sgl-project/sglang/pull/48309) `[Perf] memory: Expand single-GPU decode graph coverage` | perf | main | - |
| - | [#48310](https://github.com/sgl-project/sglang/pull/48310) `[Perf] streaming: Coalesce queued tokenizer output notifications` | perf | main | - |
| - | [#48311](https://github.com/sgl-project/sglang/issues/48311) `[CI] diffusion: perf checks depend on which runner a job lands on, and in-job retries can't fix a slow host` | bug,infra,perf | ? | - |
| - | [#48312](https://github.com/sgl-project/sglang/pull/48312) `[Perf] logprobs: Pack readback and cache cumulative stream encoding` | perf | main | - |
| - | [#48313](https://github.com/sgl-project/sglang/pull/48313) `[Perf] [NVIDIA] fused_moe: Add H20 down-projection (TMA) configs for GLM-5.3-Flash TP8/TP4` | nvidia,perf | main | - |
| - | [#48314](https://github.com/sgl-project/sglang/pull/48314) `[Perf] [NVIDIA] fused_moe: Add H20-3e configs for GLM-5.3-Flash TP8/TP4` | nvidia,perf | main | - |
| - | [#48315](https://github.com/sgl-project/sglang/pull/48315) `[Test] elastic-ep: Register NIXL EP CI coverage` | infra | main | - |
| - | [#48316](https://github.com/sgl-project/sglang/pull/48316) `[Fix] offload: Keep DSA indexer parameters resident on GPU under CPU offload` | bug | main | - |
| - | [#48317](https://github.com/sgl-project/sglang/pull/48317) `[CI] [AMD] ci: Register CUDA base/extra tests on AMD (parity experiment, do not merge)` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#48318](https://github.com/sgl-project/sglang/pull/48318) `[Fix] mem_cache: Saturate FP8 KV values before casting` | bug,quant | main | - |
| - | [#48319](https://github.com/sgl-project/sglang/pull/48319) `[Feat] lora: MoE LoRA base-GEMM providers for quantized experts (Marlin MXFP4 W4A16; CuTeDSL block-scaled MXFP` | nvidia,perf,quant | main | - |
| - | [#48320](https://github.com/sgl-project/sglang/pull/48320) `[Perf] [NVIDIA] fp8_fa_sm120: Run cross-attention when K/V length differs from Q` | nvidia,perf | main | - |
| - | [#48321](https://github.com/sgl-project/sglang/pull/48321) `[Perf] [NVIDIA] convrot_int8: Use three stages and a 128x256 tile for large M on SM120` | nvidia,perf | main | - |
| - | [#48322](https://github.com/sgl-project/sglang/pull/48322) `[Feat] [Intel] diffusion: DeepSymm IPC ring attention on XPU` | nvidia,perf | main | - |
| - | [#48326](https://github.com/sgl-project/sglang/pull/48326) `[Fix] metrics: Correct FLOPs estimate for hybrid Mamba/attention/MLP models` | bug | main | - |
| - | [#48329](https://github.com/sgl-project/sglang/pull/48329) `[Fix] scheduler: Support logprobs in mixed chunked prefill` | bug | main | - |
| - | [#48330](https://github.com/sgl-project/sglang/pull/48330) `[Benchmark] Add random video dataset support` | perf | main | - |
| - | [#48331](https://github.com/sgl-project/sglang/pull/48331) `[Benchmark] Add random audio dataset support` | perf | main | - |
| - | [#48332](https://github.com/sgl-project/sglang/pull/48332) `[Fix] HiSparse: use receiver draft layout for PP KV transfer` | bug | main | - |
| - | [#48333](https://github.com/sgl-project/sglang/pull/48333) `[Perf] HiSparse: elide unused shared-layer indexer key buffers` | perf | main | - |
| - | [#48334](https://github.com/sgl-project/sglang/pull/48334) `[Fix] HiSparse: check logical capacity for speculative decode` | bug | main | - |
| - | [#48335](https://github.com/sgl-project/sglang/pull/48335) `[Fix] HiSparse: use logical PD budgets and abort unsupported retraction` | bug | main | - |
| - | [#48336](https://github.com/sgl-project/sglang/issues/48336) `[Bug] GLM-5.3-Flash + glm47 tool grammar: enable_thinking=false bans </think>, so generation always runs to ma` |  | ? | - |
| - | [#48337](https://github.com/sgl-project/sglang/pull/48337) `[Fix] dsv32: Keep developer messages when dropping earlier reasoning` | bug | main | - |
| - | [#48338](https://github.com/sgl-project/sglang/pull/48338) `[Fix] observability: Serialize kv_hints in exported request metrics` | bug | main | - |
| - | [#48340](https://github.com/sgl-project/sglang/pull/48340) `[Feat] hicache: Add a direct_kernel IO backend on page_row for MLA/DSA pools` | nvidia,perf | main | - |
| - | [#48342](https://github.com/sgl-project/sglang/pull/48342) `[Fix] parser: Detect the plain-JSON tool-call format for tool-call-parser=auto` | bug | main | - |
| - | [#48345](https://github.com/sgl-project/sglang/pull/48345) `[Fix] diffusion/realtime: Report generate loop errors with no leading message line` | bug,perf | main | - |
| - | [#48346](https://github.com/sgl-project/sglang/issues/48346) `[Feature] dp-attention: the per-step H2D transfer of global_num_tokens_gpu is overwritten before anything read` |  | ? | - |
| - | [#48347](https://github.com/sgl-project/sglang/pull/48347) `[Fix] offloader: Enforce the CPU offload storage budget` | bug | main | - |
| - | [#48348](https://github.com/sgl-project/sglang/issues/48348) `[Feature] [NPU] kimi-k3.1: Add model support and route DSA attention path on Ascend` |  | ? | - |
| - | [#48349](https://github.com/sgl-project/sglang/pull/48349) `Enable Hy3-FP8 on xpu` | nvidia,quant | main | - |
| - | [#48350](https://github.com/sgl-project/sglang/pull/48350) `[Perf] flashinfer_cutedsl: Use swap-AB MoE on Blackwell` | nvidia,perf,quant | main | - |
| - | [#48351](https://github.com/sgl-project/sglang/pull/48351) `[Perf] [AMD] dsv41: Compile the HIP FP4 prefill schedule kernels before serving` | perf,quant,rocm | main | - |
| - | [#48353](https://github.com/sgl-project/sglang/pull/48353) `[Fix] [XPU] compressed-tensors: Support W8A8 int8 on XPU and quantize Whisper MLP linears.` | bug,infra,nvidia,perf,quant | main | - |
| - | [#48355](https://github.com/sgl-project/sglang/pull/48355) `[Fix] glm47: Let the tool grammar survive templates that ignore enable_thinking` | bug | main | - |
| - | [#48356](https://github.com/sgl-project/sglang/issues/48356) `[Bug] disaggregation: Qwen EAGLE PD decode can produce corrupted output after retraction` | risk | ? | - |
| - | [#48364](https://github.com/sgl-project/sglang/pull/48364) `[Feat] [CPU] model: Support Intern-S2-Mobius models on CPU` | infra,perf | main | - |
| - | [#48365](https://github.com/sgl-project/sglang/pull/48365) `[Perf] lightonocr: remap multimodal item offsets via bisect without dict/sort` | perf | main | - |
| - | [#48367](https://github.com/sgl-project/sglang/pull/48367) `[Perf] speculative: Fuse the draft proposal's Gumbel-max sample into one pass` | perf | main | - |
| - | [#48368](https://github.com/sgl-project/sglang/pull/48368) `[Fix] srt: Make DWDP, device timer, and AMX tests platform-safe` | bug,perf | main | - |
| - | [#48369](https://github.com/sgl-project/sglang/pull/48369) `[Intel][XPU] GDN fork stride fixes and device-agnostic tests` | nvidia,perf | main | - |
| - | [#48370](https://github.com/sgl-project/sglang/pull/48370) `[Perf] gemma3: Fuse q_norm and k_norm into gemma_rmsnorm for rank above 2` | infra,perf | main | - |
| - | [#48371](https://github.com/sgl-project/sglang/pull/48371) `[Feat] sail: support PLA recurrent linear attention fast paths [5/N]` | infra,perf,quant | main | - |
| - | [#48372](https://github.com/sgl-project/sglang/pull/48372) `[Fix] scheduler, multimodal: Fix embedding over-length hang, cap CPU pool, fix ST6 reference` | bug | main | - |
| - | [#48373](https://github.com/sgl-project/sglang/pull/48373) `[Perf] [Intel] kv-canary: Add an on-device XPU fallback for plan/verify/write` | nvidia,perf | main | - |
| - | [#48374](https://github.com/sgl-project/sglang/pull/48374) `[Fix] [Intel] xpu: Fix int8 rounding, static Triton launcher crash and XPU test settings` | bug,nvidia,perf,quant,rocm | main | - |
| - | [#48375](https://github.com/sgl-project/sglang/pull/48375) `[Feat] PD: Publish spec_kv_layout so DSpark/DFlash prefill and decode must match` | infra | main | - |
| - | [#48376](https://github.com/sgl-project/sglang/pull/48376) `[Feat] qsa: host offload of the QSA K/V with a per-request GPU hot cache (1/N)` | perf | main | - |
| - | [#48377](https://github.com/sgl-project/sglang/pull/48377) `[Perf] qsa: CUDA-graph-safe fused resolve for the QSA K/V host offload (2/N)` | nvidia,perf | main | - |
| - | [#48378](https://github.com/sgl-project/sglang/pull/48378) `[Feat] qsa: host offload of the MTP draft model's QSA K/V (3/N)` |  | main | - |
| - | [#48379](https://github.com/sgl-project/sglang/pull/48379) `[Perf] qsa: copy only the context rows a prefill reads under the QSA K/V offload` | perf | main | - |
| - | [#48381](https://github.com/sgl-project/sglang/pull/48381) `[Perf] [NVIDIA] quantization: Add tuned W8A8 block-FP8 GEMM configs for RTX 4090` | nvidia,perf,quant | main | - |
| - | [#48382](https://github.com/sgl-project/sglang/pull/48382) `[Fix] [AMD] disaggregation: Pair MoRI DSA state across PP prefill stages` | bug,infra,rocm | main | - |
| - | [#48383](https://github.com/sgl-project/sglang/pull/48383) `[Perf] diffusion: reuse bit-exact RoPE in HiDream-O1-Image` | infra,perf | main | - |
| - | [#48384](https://github.com/sgl-project/sglang/pull/48384) `[Fix] disaggregation: Preserve Qwen EAGLE state across retraction` | bug | main | - |
| - | [#48385](https://github.com/sgl-project/sglang/pull/48385) `[Fix] multimodal: keep placeholder token ids at multimodal positions of input_ids` | bug | main | - |
| - | [#48386](https://github.com/sgl-project/sglang/pull/48386) `[Perf] model_executor: Reuse device positions for text-only MRoPE` | perf | main | - |
| - | [#48387](https://github.com/sgl-project/sglang/pull/48387) `[Feat] routers: forward decode output before prefill HTTP completion` |  | main | - |
| - | [#48388](https://github.com/sgl-project/sglang/pull/48388) `[Feat] sampling: --sampling-banned-token-ids masks token ids for the target and EAGLE draft` |  | main | - |
| - | [#48389](https://github.com/sgl-project/sglang/pull/48389) `[Feat][NPU] mem-cache: support GLM DSA cache layer-split on Ascend` | perf | main | - |
| - | [#48390](https://github.com/sgl-project/sglang/pull/48390) `[Feat] bailing: add TP-only FP8 and native Ling3 serving support` | infra,quant | main | - |
| - | [#48393](https://github.com/sgl-project/sglang/pull/48393) `[Fix] kimi-k3: Cap cached_tokens at prompt_tokens in the Rust processor` | bug | main | - |
| - | [#48394](https://github.com/sgl-project/sglang/pull/48394) `[Perf] diffusion: Fuse Anima gated residuals during BCG capture` | infra,perf | main | - |
| - | [#48395](https://github.com/sgl-project/sglang/pull/48395) `[Feat] kimi-k3: Support DeepEP v2 with native MXFP4 experts` | nvidia,quant | main | - |
| - | [#48396](https://github.com/sgl-project/sglang/pull/48396) `[Feat] [AMD] kv-shard: Support GLM DSA KV cache sharding on ROCm` | perf,rocm | main | - |
| - | [#48397](https://github.com/sgl-project/sglang/pull/48397) `[Fix] [AMD] moe: Stop dropping FP32 partials in GLM Gluon TP8 32K MoE` | bug,infra,perf,rocm | main | - |
| - | [#48398](https://github.com/sgl-project/sglang/pull/48398) `[Perf] gdn: read strided q/k/v in the Triton chunked prefill and skip the dead output zero fill` | perf,rocm | main | - |
| - | [#48400](https://github.com/sgl-project/sglang/pull/48400) `[Chore] [AMD] wip: triton3.9 for rocm10/10.1 gfx1250` | rocm | main | - |
| - | [#48402](https://github.com/sgl-project/sglang/pull/48402) `[Fix] scheduler: Respect earlier EOS in speculative stop handling` | bug | main | - |
| - | [#48403](https://github.com/sgl-project/sglang/issues/48403) `[Bug] EPLB crashes with per_pass/per_token recorder modes` | bug | ? | - |
| - | [#48404](https://github.com/sgl-project/sglang/pull/48404) `[Fix] eplb: reject incompatible recorder modes` | bug,infra | main | - |
| - | [#48405](https://github.com/sgl-project/sglang/pull/48405) `[Perf] [AMD] kvcache: Fuse fp8 quantization into the vectorized_5d KV-cache write` | infra,perf,quant,rocm | main | - |
| - | [#48406](https://github.com/sgl-project/sglang/pull/48406) `[Perf] [AMD] qwen3: Let the fused QK-norm + RoPE + KV write serve the vectorized_5d layout` | infra,perf,rocm | main | - |
| - | [#48407](https://github.com/sgl-project/sglang/pull/48407) `[Perf] dsa: Use the packed prefill top-k for DSA models on CUDA` | nvidia,perf | main | - |
| - | [#48408](https://github.com/sgl-project/sglang/issues/48408) `[Feature] Add an opt-in bounded matching window for LPM scheduling` |  | ? | - |
| - | [#48409](https://github.com/sgl-project/sglang/pull/48409) `[Feat] scheduler: add an opt-in bounded matching window for LPM` | infra | main | - |
| - | [#48410](https://github.com/sgl-project/sglang/pull/48410) `[CI] arm64: Publish Arm CPU Docker images` | infra | main | - |
| - | [#48411](https://github.com/sgl-project/sglang/issues/48411) `[CI] Xeon: SPR socket0 server tests OOM-killed during KV allocation on sglang-spr08/18/19` | infra | ? | - |
| - | [#48412](https://github.com/sgl-project/sglang/pull/48412) `[Feat] pp: Relay routed experts through pipeline-parallel stages` |  | main | - |
| - | [#48414](https://github.com/sgl-project/sglang/pull/48414) `[Feat] model: Add Kimi-K3.1 support` | infra,nvidia,perf,quant | main | - |
| - | [#48416](https://github.com/sgl-project/sglang/pull/48416) `TTFT：only prefill` |  | main | - |
| - | [#48418](https://github.com/sgl-project/sglang/pull/48418) `[Fix] diffusion: Count reclaimable page cache as available inside a cgroup cap` | bug,infra,perf | main | - |
| - | [#48419](https://github.com/sgl-project/sglang/pull/48419) `[Fix] scheduler: Keep prefill batches homogeneous by input form` | bug | main | - |
| - | [#48420](https://github.com/sgl-project/sglang/pull/48420) `[Feat] [NPU] kimi-k3.1: Add model support and route DSA attention path on Ascend` |  | main | - |
| - | [#48422](https://github.com/sgl-project/sglang/pull/48422) `[Fix] cp: Embed the full sequence when a CP hook returns no embeddings` | bug | main | - |
| - | [#48423](https://github.com/sgl-project/sglang/pull/48423) `[Perf] weight_checker: Avoid per-chunk host syncs and redundant FP32 casts in compare_weights` | perf | main | - |
| - | [#48425](https://github.com/sgl-project/sglang/pull/48425) `[Fix] deterministic: replay hybrid Mamba prefix instead of restoring donated state` | bug | main | - |
| - | [#48426](https://github.com/sgl-project/sglang/pull/48426) `[Fix] deterministic: Size the MQA-logits chunks without free memory` | bug | main | - |
| - | [#48427](https://github.com/sgl-project/sglang/pull/48427) `[Feat] [AMD] model: Add Kimi-K3.1 MI35x support` | infra,perf,quant,rocm | kimi-k3.1-day-0 | - |
| - | [#48428](https://github.com/sgl-project/sglang/pull/48428) `[Fix] batch_invariant_ops: Cap the mean kernel's grid so large outputs launch on ROCm` | bug,perf,rocm | main | - |
| - | [#48431](https://github.com/sgl-project/sglang/pull/48431) `[Feat] hicache: Share request-end Mamba backups` | infra,perf | main | - |
| - | [#48434](https://github.com/sgl-project/sglang/pull/48434) `[Fix] [AMD] aiter: Quantize q with its own scale in the fp8 prefills over a gathered cache` | bug,infra,perf,quant,rocm | main | - |
| - | [#48436](https://github.com/sgl-project/sglang/pull/48436) `[Fix] [Intel] diffusion: Skip XPU component prefetch that would not fit` | bug,nvidia,perf | main | - |
| - | [#48438](https://github.com/sgl-project/sglang/pull/48438) `[Test] [AMD] aiter: Run the HD128 ASM prefill test on gfx950 with a routed pool` | infra,rocm | main | - |
| - | [#48441](https://github.com/sgl-project/sglang/pull/48441) `[Perf] dp-attention: Skip the dead H2D copy of global_num_tokens_gpu` | perf | main | - |
| - | [#48442](https://github.com/sgl-project/sglang/pull/48442) `[Perf] diffusion: Accelerate exact SANA-Video RoPE on SM103` | infra,nvidia,perf | main | - |
| - | [#48444](https://github.com/sgl-project/sglang/pull/48444) `[Perf] [NVIDIA] gdn: deferred-fold ReplaySSM target verify on FlashInfer u-cache kernels` | nvidia,perf | qwen38-fn-rubin | - |
| - | [#48445](https://github.com/sgl-project/sglang/pull/48445) `[Feat] diffusion: Add --model-checksum to verify model files before loading` | perf | main | - |
| - | [#48446](https://github.com/sgl-project/sglang/pull/48446) `[Fix] io_struct: Give each request its own sampling_params dict during normalization` | bug | main | - |
| - | [#48447](https://github.com/sgl-project/sglang/pull/48447) `[Fix] dp-attention: Carry a rank's ShutdownReq to its DP peers through the MLP-sync gather` | bug | main | - |
| - | [#48448](https://github.com/sgl-project/sglang/pull/48448) `[CI] server_args: Isolate two tests from process state and host hardware` | infra | main | - |
| - | [#48449](https://github.com/sgl-project/sglang/pull/48449) `[Refactor] scheduler: Run a prefill batch's KV calls from one overridable _flush_prefill` |  | main | - |
| - | [#48451](https://github.com/sgl-project/sglang/pull/48451) `[Perf] pd: Poll the prefill result wait per attention-DP shard and pump HiCache storage events in it` | infra,perf | main | - |
| - | [#48453](https://github.com/sgl-project/sglang/pull/48453) `[Test] load-snapshot: Pin the Python server mode in TestZmqReaderOwner` | infra | main | - |
| - | [#48454](https://github.com/sgl-project/sglang/pull/48454) `[Doc] cookbook: Refresh Qwen3.8-Flash-Next GB300 AgentX points` | nvidia | main | - |
| - | [#48455](https://github.com/sgl-project/sglang/pull/48455) `[Feat] rust-server: Log requests like the Python server` |  | main | - |
| - | [#48456](https://github.com/sgl-project/sglang/pull/48456) `[Fix] [NVIDIA] dsv41: Restore decode accuracy by running the side-stream mHC mix in BF16x3 on Blackwell` | bug,nvidia,perf,risk | main | - |
| - | [#48457](https://github.com/sgl-project/sglang/pull/48457) `[Feat] rust-server: Write --crash-dump-folder dumps from the Rust frontend` | bug,infra | oss-sync-700891a42b | - |
| - | [#48458](https://github.com/sgl-project/sglang/pull/48458) `[Fix] disaggregation: Keep non-final KV sends inside the protected prefix` | bug,infra | main | - |
| - | [#48460](https://github.com/sgl-project/sglang/issues/48460) `Importing sglang replaces `triton.next_power_of_2` with a host-only function, breaking other Triton kernels in` | perf,rocm | ? | - |
| - | [#48461](https://github.com/sgl-project/sglang/issues/48461) ``HybridLinearKVPool` ignores `v_head_dim` for the full-attention MHA pool (hybrid linear-attention models with` |  | ? | - |
| - | [#48462](https://github.com/sgl-project/sglang/issues/48462) `Allow models outside sglang's architecture list to use the MLA KV cache (detect MLA from config, not architect` | perf | ? | - |
| - | [#48463](https://github.com/sgl-project/sglang/issues/48463) `Feature request: overlap scheduling for externally registered linear-attention models using the mamba radix ca` | perf | ? | - |
| - | [#48465](https://github.com/sgl-project/sglang/issues/48465) `[Feature] Metric for time to first answer token (after reasoning)` |  | ? | - |
| - | [#48466](https://github.com/sgl-project/sglang/pull/48466) `[Feat] observability: add time to first answer token histogram` |  | main | - |
| - | [#48468](https://github.com/sgl-project/sglang/pull/48468) `[Chore] [NVIDIA] deps: Bump FlashInfer to 0.7.3 and migrate the NVLink one-sided all-to-all to flashinfer.moe_` | infra,nvidia,perf | main | - |
| - | [#48469](https://github.com/sgl-project/sglang/pull/48469) `[Feat] kimi-k31: Support PCP KV sharding with HiCache and DFlash` | perf | kimi-k3.1-day-0 | - |
| - | [#48470](https://github.com/sgl-project/sglang/pull/48470) `[Perf] diffusion: Tune LingBot MoE TMA for B300 SXM6 AC` | infra,perf | main | - |
| - | [#48471](https://github.com/sgl-project/sglang/pull/48471) `[Fix] mem_cache: Pass v_head_dim to the hybrid linear full-attention pool` | bug | main | - |
| - | [#48472](https://github.com/sgl-project/sglang/issues/48472) `Feature request: public single-iteration step API for an in-process `Scheduler`` |  | ? | - |
| - | [#48473](https://github.com/sgl-project/sglang/issues/48473) `Feature request: in-process output sink instead of the detokenizer/tokenizer sockets` |  | ? | - |
| - | [#48474](https://github.com/sgl-project/sglang/issues/48474) `Decouple per-request sampling seeds from `enable_deterministic_inference`'s kernel overrides; allow ignoring t` | perf | ? | - |
| - | [#48475](https://github.com/sgl-project/sglang/issues/48475) `Feature request: extension points for externally defined models (registration of runtime classes, attention lo` | perf | ? | - |
| - | [#48476](https://github.com/sgl-project/sglang/issues/48476) `Support data-parallel attention/replicas inside one existing torch distributed world (in-process scheduler)` |  | ? | - |
| - | [#48477](https://github.com/sgl-project/sglang/pull/48477) `[Feat] decision: Serve pplx-decider v1.2 checkpoints on /v1/systemone` |  | main | - |
| - | [#48478](https://github.com/sgl-project/sglang/pull/48478) `[CI] [AMD] test: Use an ungated Llama-3.1-8B mirror in stage-a basic sanity` | infra,rocm | main | - |
| - | [#48479](https://github.com/sgl-project/sglang/pull/48479) `[CI] [AMD] nightly: Add Kimi-K3.1-Pro nightly test` | infra,rocm | main | - |
| - | [#48482](https://github.com/sgl-project/sglang/issues/48482) `Feature request: per-request time stats in scheduler outputs without enable_metrics` |  | ? | - |
| - | [#48483](https://github.com/sgl-project/sglang/issues/48483) `[Bug] [AMD] moe: GLM Gluon EP>1 32K prefill reads codes past the 2-GiB buffer-op window` | rocm | ? | - |
| - | [#48486](https://github.com/sgl-project/sglang/pull/48486) `[Fix] parser: Keep DeepSeek recipe output when a length finish splits a UTF-8 character` | bug | main | - |
| - | [#48487](https://github.com/sgl-project/sglang/pull/48487) `[Fix] sampler: skip the token-id all-reduce when the TP sync group has one rank` | bug,infra | main | - |
| - | [#48488](https://github.com/sgl-project/sglang/pull/48488) `[Doc] [NPU] ascend: Add a knowledge base for SGLang deployment on Ascend NPUs` | quant | main | - |
| - | [#48489](https://github.com/sgl-project/sglang/pull/48489) `[Fix] function_call: infer argument types from full JSON schema in step3/minicpm5` | bug | main | - |
| - | [#48492](https://github.com/sgl-project/sglang/pull/48492) `[Fix] rust-server: Let DP rank 0's drain wait for every attention-DP listener` | bug | main | - |
| - | [#48494](https://github.com/sgl-project/sglang/pull/48494) `[Fix] cuda-graph: Refuse the metadata glue graph when the attention backend plans on the host` | bug,nvidia,perf | main | - |
| - | [#48495](https://github.com/sgl-project/sglang/pull/48495) `[Fix] detokenizer: Freeze GC in the output router` | bug | main | - |
| - | [#48496](https://github.com/sgl-project/sglang/pull/48496) `[Perf] mem_cache: Order recycled unified-page writers after the forward instead of the current stream` | infra,perf | main | - |
| - | [#48498](https://github.com/sgl-project/sglang/pull/48498) `[Perf] pp: Send decode activations before CPU result processing` | perf | main | - |
| - | [#48500](https://github.com/sgl-project/sglang/pull/48500) `[Fix] deepseek_v4: floor amax before the division in the V4.1 fp8 KV scale` | bug,perf,quant | main | - |
| - | [#48502](https://github.com/sgl-project/sglang/issues/48502) `[Bug] DeepSeek-V4.1-Flash: every inference request crashes with IndexError at logits_processor.py:692 on sglan` | bug | ? | - |
| - | [#48503](https://github.com/sgl-project/sglang/pull/48503) `[Doc] diffusion: Correct Wan video requests and document padding tradeoffs` | perf | main | - |
| - | [#48504](https://github.com/sgl-project/sglang/pull/48504) `[Feat] kimi-k3.1: Prefill Context Parallelism Support` | perf,quant | main | - |
| - | [#48505](https://github.com/sgl-project/sglang/pull/48505) `[Perf] [AMD] dsa: Route the DCP prefill by its wire bytes` | infra,perf,rocm | main | - |
| - | [#48506](https://github.com/sgl-project/sglang/issues/48506) `[Bug] [NVIDIA] test/manual/ep/test_flashinfer_dispatcher.py: Every test errors on main, and the test needs a r` | nvidia | ? | - |
| - | [#48507](https://github.com/sgl-project/sglang/pull/48507) `[Fix] multimodal: Cap receive-time CUDA VMM feature copies per GPU and stage the rest in pinned host memory` | bug,infra,nvidia | main | - |
| - | [#48508](https://github.com/sgl-project/sglang/pull/48508) `[Perf] tokenizer_manager: Keep the crash-dump request history pickled so the cyclic GC never scans it` | bug,infra,perf | main | - |
| - | [#48509](https://github.com/sgl-project/sglang/pull/48509) `[Fix] responses: Align protocol for logprobs, background/stream, and input validation` | bug | main | - |
| - | [#48510](https://github.com/sgl-project/sglang/pull/48510) `[Feat] [NVIDIA] kimi_k3: Add in-tree TP8 specialized decode with DCP and HiCache` | infra,nvidia,perf | main | - |
| - | [#48511](https://github.com/sgl-project/sglang/pull/48511) `[Test] rust-server: Cover the embedded Rust frontend in a two-node TP engine` |  | main | - |
| - | [#48512](https://github.com/sgl-project/sglang/pull/48512) `[Feat] rust-server: Refuse ignored flags, enforce API keys, exit on a failed warmup, declare the SSE charset` | perf | oss-sync-65c40d1f0e | - |
| - | [#48513](https://github.com/sgl-project/sglang/pull/48513) `[Feat] rust-server: Export extension metric families and hand media admission timing to the MM processor` | infra | main | - |
| - | [#48515](https://github.com/sgl-project/sglang/pull/48515) `[Fix] rust-server: Freeze the scheduler's garbage collector after the startup warmup` | bug,risk | oss-sync-219fe11113 | - |
| - | [#48517](https://github.com/sgl-project/sglang/pull/48517) `[Fix] modelopt: Load serialized NVFP4 experts of hybrid FP8+NVFP4 checkpoints under modelopt_fp4` | bug,quant | main | - |
| - | [#48518](https://github.com/sgl-project/sglang/pull/48518) `[Fix] server-args: Redact the access keys from /server_info, logs, launch_command and crash dumps` | bug | oss-sync-c677a14dcf | - |
| - | [#48519](https://github.com/sgl-project/sglang/issues/48519) `[RFC] scheduler: UniBoost, a starvation-bounded schedule policy (#48076-#48079)` |  | ? | - |
| - | [#48520](https://github.com/sgl-project/sglang/pull/48520) `[Feat] pd: Add input-only prefix retention on decode` | perf | main | - |
| - | [#48521](https://github.com/sgl-project/sglang/pull/48521) `[Fix] qwen3_coder: Preserve streamed text and tool argument order` | bug | main | - |
| - | [#48523](https://github.com/sgl-project/sglang/pull/48523) `[Feat] rust-server: Decompress x-body-compressed request bodies` | infra | oss-sync-5f33eae5cc | - |
| - | [#48524](https://github.com/sgl-project/sglang/pull/48524) `[Feat] Humming: Unify MoE input processing` |  | main | - |
| - | [#48526](https://github.com/sgl-project/sglang/pull/48526) `[Fix] dsa: Cap the MQA-logits budget by host memory on integrated GPUs` | bug | main | - |
| - | [#48527](https://github.com/sgl-project/sglang/pull/48527) `[Doc] [NPU] qwen3.8-flash-next: Add Ascend A2 deployment tutorial` |  | main | - |
| - | [#48529](https://github.com/sgl-project/sglang/pull/48529) `[Feat] disaggregation: Support Qwen3.5 and Qwen3.8 MTP with NIXL CPU buffers` |  | main | - |
| - | [#48531](https://github.com/sgl-project/sglang/pull/48531) `[Perf] [NVIDIA] fp8: Let the Hopper block GEMV take K=6144 for MiniMax M3.1` | infra,nvidia,perf,quant | main | - |
| - | [#48533](https://github.com/sgl-project/sglang/pull/48533) `[Fix] kda: Allocate FlashInfer prefill-graph checkpoints in the SSM state dtype` | bug,nvidia,perf | main | - |
| - | [#48534](https://github.com/sgl-project/sglang/pull/48534) `Let DeprecatedChoiceToFlagAction accept the caller's SUPPRESS default` |  | main | - |
| - | [#48536](https://github.com/sgl-project/sglang/pull/48536) `[Perf] [AMD] quantization: Fuse SiLU-and-mul with the dynamic per-tensor fp8 quant of dense MLPs on gfx95` | infra,perf,quant,rocm | main | - |
| - | [#48537](https://github.com/sgl-project/sglang/pull/48537) `[Fix] [NPU] mooncake: register device allocation spans` | bug | main | - |
| - | [#48538](https://github.com/sgl-project/sglang/pull/48538) `[Fix] hicache: validate MLA rows before packing draft caches` | bug | main | - |
| - | [#48539](https://github.com/sgl-project/sglang/pull/48539) `[Perf] scheduler: price host cache reloads in prefill LPM` | perf | main | - |
| - | [#48540](https://github.com/sgl-project/sglang/pull/48540) `[Perf] [NPU] moe: tile local prefill expert activations` | perf | main | - |
| - | [#48541](https://github.com/sgl-project/sglang/pull/48541) `[Feat] pd: add token-aware decode session placement` |  | main | - |
| - | [#48542](https://github.com/sgl-project/sglang/pull/48542) `[Perf] pd: overlap prefill rank publication and transfer retirement` | perf | main | - |
| - | [#48543](https://github.com/sgl-project/sglang/pull/48543) `[Feat] [NPU] hicache: add exact-size ACL pinned host allocation` | infra | main | - |
| - | [#48545](https://github.com/sgl-project/sglang/pull/48545) `[Fix] [CPU] cpu-graph: Preserve return_logprob and request metadata in dynamic prefill` | bug,infra | main | - |
| - | [#48548](https://github.com/sgl-project/sglang/pull/48548) `[Fix] moe_topk_sum: fold rows past CUDA's 65535 gridDim.y into gridDim.z` | bug,nvidia,perf,quant | main | - |
| - | [#48549](https://github.com/sgl-project/sglang/pull/48549) `[Fix] spec: Select only tokens with probability in chain rejection sampling's final draw` | bug,perf | main | - |
| - | [#48550](https://github.com/sgl-project/sglang/pull/48550) `[Perf] radix-tree: Cap Rust tree-core match keys with a memoryview instead of a slice` | perf | main | - |
| - | [#48552](https://github.com/sgl-project/sglang/pull/48552) `[Feat] EPLB: Speed up EPLB balanced packing with a bounded min-heap` | perf | main | - |
| - | [#48554](https://github.com/sgl-project/sglang/pull/48554) `[Fix] [NVIDIA] custom-allreduce: Scope a zero NVLink fabric cluster UUID to its own node` | bug,infra,nvidia | main | - |
| - | [#48555](https://github.com/sgl-project/sglang/pull/48555) `[Perf] [NPU] cache: enable compact DSA indexers for PD and HiCache` | perf | main | - |
| - | [#48556](https://github.com/sgl-project/sglang/pull/48556) `[Fix] moe: Fix illegal memory access in the W4A16/W8A16 Triton MoE kernel (unmasked K tail)` | bug,perf,quant,risk,rocm | main | - |
| - | [#48557](https://github.com/sgl-project/sglang/issues/48557) `[Bug] `/v1/responses` streaming returns HTTP 200 + `response.failed` for context-length-exceeded requests, whi` |  | ? | - |
| - | [#48558](https://github.com/sgl-project/sglang/pull/48558) `[Feat] mem_cache: Support INT8 Mamba checkpoints in HiCache L1/L2` | perf,quant | main | - |
| - | [#48559](https://github.com/sgl-project/sglang/pull/48559) `[Perf] rerank: Cache compiled Jinja templates` | perf | main | - |
| - | [#48560](https://github.com/sgl-project/sglang/pull/48560) `[Feat] [NPU] dsa: complete A2 packed INT8 KV integration` | quant | main | - |
| - | [#48561](https://github.com/sgl-project/sglang/issues/48561) `[Bug] DeepSeek V4.1: natural EOS with unclosed reasoning produces a successful empty answer` |  | ? | - |
| - | [#48562](https://github.com/sgl-project/sglang/pull/48562) `[Feat] [NPU] dsa: add graph-safe A2 INT8 indexer support` | quant | main | - |
| - | [#48563](https://github.com/sgl-project/sglang/pull/48563) `[Perf] [NVIDIA] gemma4: fuse the TP all-reduce with the layer epilogue and FP8 quant on NVLink multicast` | infra,nvidia,perf,quant | main | - |
| - | [#48564](https://github.com/sgl-project/sglang/pull/48564) `[Fix] metrics: Add MLA/MoE-aware FLOPs and fix forward_overlap device gate in the MFU estimator` | bug,perf | main | - |
| - | [#48565](https://github.com/sgl-project/sglang/pull/48565) `[Fix] benchmark: Correct single-turn token counts and native stream failures` | bug,perf | main | - |
| - | [#48566](https://github.com/sgl-project/sglang/pull/48566) `[Feat] EPLB: Build only the local rank EPLB static dispatch map` | infra | main | - |
| - | [#48567](https://github.com/sgl-project/sglang/pull/48567) `[Fix] tp_worker: Seed each attention-DP group with its own random stream` | bug | main | - |
| - | [#48568](https://github.com/sgl-project/sglang/pull/48568) `[Fix] runtime: Sync FlashInfer autotune tactics across attention-DP groups` | bug,nvidia,perf | main | - |
| - | [#48569](https://github.com/sgl-project/sglang/pull/48569) `[Test] [NPU] return-aux-hidden-states: Add NPU e2e testTest npu return aux hidden states` |  | main | - |
| - | [#48570](https://github.com/sgl-project/sglang/pull/48570) `[Fix] glm5: support interleave CP prefill BCG row boundaries` | bug | main | - |
| - | [#48572](https://github.com/sgl-project/sglang/pull/48572) `[Feat] rust-server: Report the serving DP rank in /generate meta_info` |  | oss-sync-50c14dcd23 | - |
| - | [#48574](https://github.com/sgl-project/sglang/pull/48574) `[Fix] [NPU] deepep: support Normal BF16 with quantized LowLatency` | bug,nvidia,perf,quant | main | - |
| - | [#48575](https://github.com/sgl-project/sglang/pull/48575) `[Feat] [NPU] runtime: prewarm the native pinned-host allocator` | infra | main | - |
| - | [#48576](https://github.com/sgl-project/sglang/pull/48576) `[Feat] hicache: trace per-request storage prefetch phases` | perf | main | - |
| - | [#48577](https://github.com/sgl-project/sglang/pull/48577) `[Feat] hicache: expose pending work and backup outcome metrics` | perf | main | - |
| - | [#48578](https://github.com/sgl-project/sglang/pull/48578) `[Feat] [Intel] glm4: Enable GLM4-series CPU inference` | infra,perf | main | - |
| - | [#48579](https://github.com/sgl-project/sglang/pull/48579) `[Perf] io_struct: Validate an input_embeds body against one union member` | infra,perf | main | - |
| - | [#48580](https://github.com/sgl-project/sglang/issues/48580) `[Feature] Add per-request skip_detokenize option to sglang.api.v1.GenerateRequest` |  | ? | - |
| - | [#48581](https://github.com/sgl-project/sglang/issues/48581) `[Feature] Honor chat-template stop strings when ChatCompletionRequest carries input_ids` |  | ? | - |
| - | [#48582](https://github.com/sgl-project/sglang/issues/48582) `[RFC] Integrate MindIE-SD as an Acceleration Library for SGLang Diffusion` | perf | ? | - |
| - | [#48583](https://github.com/sgl-project/sglang/pull/48583) `[Feat] [Intel] xpu_kernel: update sglang-kernel-xpu to 0.6.0` | infra,nvidia,perf | main | - |
| - | [#48584](https://github.com/sgl-project/sglang/pull/48584) `[Perf] kimi-k3.1: TP-shard the decode MoE front and latent-up tail` | infra,perf | main | - |
| - | [#48585](https://github.com/sgl-project/sglang/pull/48585) `[Perf] gdn: reduce MIS output and QK preparation overhead` | infra,perf | main | - |
| - | [#48586](https://github.com/sgl-project/sglang/pull/48586) `[Perf] kimi-k3: Fuse the decode MoE routing for 1-256 rows into one kernel` | infra,perf,quant | main | - |
| - | [#48587](https://github.com/sgl-project/sglang/pull/48587) `[Fix] responses: Kick-start the stream generator so validation errors answer a real HTTP 400` | bug | main | - |
| - | [#48589](https://github.com/sgl-project/sglang/pull/48589) `[Perf] [NPU] gdn: Enable direct state-pool I/O for prefill` | perf | main | - |
| - | [#48590](https://github.com/sgl-project/sglang/pull/48590) `[Feat] disaggregation: Add optional KVServe compression to Mooncake P/D` |  | main | - |
| - | [#48591](https://github.com/sgl-project/sglang/pull/48591) `[Perf] speculative: Support zero-copy QLEN_MASK in FlashAttentionBackend for NGRAMWorker` | perf | main | - |
| - | [#48592](https://github.com/sgl-project/sglang/pull/48592) `[Feat] speculative: Insert bounded prompt tail on extend in NGRAMWorker` |  | main | - |
| - | [#48593](https://github.com/sgl-project/sglang/issues/48593) `[Bug] Full prefill CUDA graph capture fails for hybrid linear attention models (IndexError in HybridLinearAttn` | nvidia | ? | - |
| - | [#48594](https://github.com/sgl-project/sglang/pull/48594) `[Fix] flashattention: Resolve window KV pool for frozen-KV MTP draft (illegal memory access on Gemma-4)` | bug,risk | main | - |
| - | [#48596](https://github.com/sgl-project/sglang/pull/48596) `[Fix] Return HTTP 400 for /v1/responses streams rejected before the first chunk` | bug | main | - |
| - | [#48597](https://github.com/sgl-project/sglang/pull/48597) `[Fix] pd: harden rebootstrap submission and count pending retries` | bug | main | - |
| - | [#48598](https://github.com/sgl-project/sglang/pull/48598) `[Fix] dsa: align FlashMLA metadata with prefill graph query rows` | bug,nvidia | main | - |
| - | [#48599](https://github.com/sgl-project/sglang/pull/48599) `[Feat] hicache: report resident L2 hit origins` | perf | main | - |
| - | [#48600](https://github.com/sgl-project/sglang/pull/48600) `[Feat] [Intel] HiCache: Support unified-memory HiCache on XPU` | nvidia | main | - |
| - | [#48601](https://github.com/sgl-project/sglang/issues/48601) `[Bug] Decode HiCache returns HTTP 500 when a shorter prefix has no Mamba checkpoint` |  | ? | - |
| - | [#48602](https://github.com/sgl-project/sglang/pull/48602) `[Perf] dsa: Add an opt-in FlashInfer Prims-TS sparse MLA backend` | nvidia,perf | main | - |
| - | [#48605](https://github.com/sgl-project/sglang/pull/48605) `[Perf] moe/paged-experts: decide block-wide and skip empty page-ins` | perf,quant | main | - |
| - | [#48607](https://github.com/sgl-project/sglang/pull/48607) `[Feat] moe: Add platform-scoped expert executor providers` |  | main | - |
| - | [#48608](https://github.com/sgl-project/sglang/pull/48608) `[Fix] lora: Skip unmatched weights during non-strict buffer loading in LoRAMemoryPool` | bug | main | - |
| - | [#48609](https://github.com/sgl-project/sglang/pull/48609) `[Fix] [XPU] xpu-graph: Support read-done events and retain capture inputs in graph backend` | bug,infra,nvidia | main | - |
| - | [#48610](https://github.com/sgl-project/sglang/pull/48610) `fix(expert_distribution): skip reset/append when _disable_all is True` | bug | main | - |
| - | [#48611](https://github.com/sgl-project/sglang/pull/48611) `[Fix] hicache: Keep buffer-mode PP stages on PP0's drain and staging steps` | bug,perf | main | - |
| - | [#48612](https://github.com/sgl-project/sglang/pull/48612) `[Perf] [NPU] DeepSeek-V4: remove blocking H2D copies and fuse DSPARK verify compressor-position metadata into ` | perf,rocm | main | - |
| - | [#48613](https://github.com/sgl-project/sglang/pull/48613) `[Perf] kda: Run the fused CuTe DSpARK verify kernel on a BF16 SSM state` | perf | main | - |
| - | [#48615](https://github.com/sgl-project/sglang/pull/48615) `[Fix] diffusion: Keep explicit cuDNN attention inside LTX breakable CUDA graphs` | bug,infra,nvidia,perf | main | - |
| - | [#48616](https://github.com/sgl-project/sglang/pull/48616) `[Fix] gemm: Order the CuTe DSL kernels' TMEM release after the epilogue's tcgen05.ld` | bug,infra,perf | main | - |
| - | [#48618](https://github.com/sgl-project/sglang/issues/48618) `[Bug]` |  | ? | - |
| - | [#48620](https://github.com/sgl-project/sglang/pull/48620) `[Fix] [AMD] JIT: Port per-token group FP8 quantization v2 to ROCm` | bug,perf,quant,rocm | main | - |
| - | [#48621](https://github.com/sgl-project/sglang/pull/48621) `[Fix] dspark: Count scheduler ranks in SPS profiler` | bug,infra | main | - |
| - | [#48623](https://github.com/sgl-project/sglang/issues/48623) `[Perf] radix cache: each eviction rebuilds a heap over all evictable leaves` | perf | ? | - |
| - | [#48624](https://github.com/sgl-project/sglang/pull/48624) `[Feat] scheduler: Add waitable request retirement receipts` |  | main | - |
| - | [#48625](https://github.com/sgl-project/sglang/pull/48625) `[Perf] [AMD] qsa: Share compressed-key reads across the four verify rows of a request on gfx950` | perf,rocm | main | - |
| - | [#48626](https://github.com/sgl-project/sglang/issues/48626) `[Tracking] Predictable long-context agent serving: APIs, cache usage, and resource lifetime` | perf | ? | - |
| - | [#48627](https://github.com/sgl-project/sglang/pull/48627) `[Fix] scheduler: Support return_logprob with mixed chunked prefill` | bug | main | - |
| - | [#48628](https://github.com/sgl-project/sglang/pull/48628) `[Fix] scheduler: Count buffer-mode prefetch hits in shortest-prefill-first` | bug,perf | main | - |
| - | [#48629](https://github.com/sgl-project/sglang/pull/48629) `[Perf] models: use fused apply_qk_norm in Exaone, HunYuan-V3, AfMoE, and BailingMoE` | perf | main | - |
| - | [#48630](https://github.com/sgl-project/sglang/pull/48630) `[Feat] scheduler: Correlate prefill admission scans with DP forward rounds` |  | main | - |
| - | [#48631](https://github.com/sgl-project/sglang/pull/48631) `[Fix] [NPU] loader: Preserve packed NZ weights in presharded checkpoints` | bug | main | - |
| - | [#48632](https://github.com/sgl-project/sglang/pull/48632) `[Fix] mooncake: Surface transfer thread device binding failures to sender polls` | bug | main | - |
| - | [#48633](https://github.com/sgl-project/sglang/pull/48633) `[Perf] [NPU] allocator: Share the Triton bound for one-block KV extends` | perf,rocm | main | - |
| - | [#48635](https://github.com/sgl-project/sglang/issues/48635) `[Bug] AttributeError: 'QwenImagePipelineConfig' object has no attribute 'sample_sigmas'。` |  | ? | - |
| - | [#48636](https://github.com/sgl-project/sglang/pull/48636) `[Feat] model: Add Ripple-65B Preview (ricursiveAI/Ripple-65B-Preview) support` |  | main | - |
| - | [#48638](https://github.com/sgl-project/sglang/pull/48638) `[Perf] [NVIDIA] moe: Add an opt-in persistent MXFP4 decode MoE kernel for Kimi-K3.1` | infra,nvidia,perf,quant | main | - |
| - | [#48641](https://github.com/sgl-project/sglang/pull/48641) `[Perf] [AMD] dsv4: Keep the exact decoder SWA tail in HIP breakable prefill graphs` | perf,rocm | main | - |
| - | [#48642](https://github.com/sgl-project/sglang/pull/48642) `[Feat] paged-experts: keep experts on disk so later starts skip loading them` | infra | main | - |
| - | [#48643](https://github.com/sgl-project/sglang/pull/48643) `[Fix] modelslim: don't mutate the caller's quantization config` | bug,quant | main | - |
| - | [#48645](https://github.com/sgl-project/sglang/pull/48645) `[Fix] GLM: fold reasoning_effort onto the template's levels for tool grammars` | bug | release/v0.5.23 | - |
| - | [#48646](https://github.com/sgl-project/sglang/pull/48646) `[Fix] [XPU] diffusion/z-image: Fix missing QK norm + RoPE fusion path for B=1 (already used for B>1)` | bug,infra,nvidia,perf | main | - |
| - | [#48647](https://github.com/sgl-project/sglang/pull/48647) `[Perf] dLLM: Skip denoising for FDFO prompt-only batches` | perf | main | - |
| - | [#48648](https://github.com/sgl-project/sglang/pull/48648) `[Perf] [AMD] Qwen4-Exp/HC: Fuse decode-sized hyper-connection norm and inject into FlyDSL mix` | perf,rocm | main | - |
| - | [#48649](https://github.com/sgl-project/sglang/pull/48649) `[Perf] [AMD] qsa: Faster decode MQA logits on ROCm (padded Q, group-strided launch)` | perf,rocm | main | - |
| - | [#48650](https://github.com/sgl-project/sglang/pull/48650) `[Bug] Fix Qwen-Image-2.1 config resolution for underscore directory names` | bug,perf | main | - |
| - | [#48651](https://github.com/sgl-project/sglang/pull/48651) `[Perf] [AMD] diffusion: Quantize MXFP4 activations with the AITER HIP kernel` | perf,quant,rocm | main | - |
| - | [#48652](https://github.com/sgl-project/sglang/pull/48652) `[Fix] hisparse: Use host-backed logical capacity for request limits` | bug | main | - |
| - | [#48653](https://github.com/sgl-project/sglang/pull/48653) `[Feat] platforms: Add tensor IPC extension points` |  | main | - |
| - | [#48656](https://github.com/sgl-project/sglang/pull/48656) `[Feat] comfyui: Load FastH3 and Qwen-Image 2.1 Turbo single files` | infra,perf | main | - |
| - | [#48657](https://github.com/sgl-project/sglang/pull/48657) `[Fix] rl: One tensor weight payload per engine rank under pipeline parallelism` | bug | main | - |
| - | [#48658](https://github.com/sgl-project/sglang/pull/48658) `[Feat] model-loader: ModelExpress weight release, resume and reload hooks` | infra | main | - |
| - | [#48659](https://github.com/sgl-project/sglang/pull/48659) `[Fix] tbo: Preserve child offsets and auxiliary hidden states` | bug | main | - |
| - | [#48660](https://github.com/sgl-project/sglang/issues/48660) `[Bug] TBO can change deterministic prefill outputs and drop speculative auxiliary hidden states` | bug | ? | - |
| - | [#48661](https://github.com/sgl-project/sglang/pull/48661) `[Fix] [Intel] docker/xpu: Install the Intel GPU stack from the versioned intel-omix channel` | bug,infra,nvidia | main | - |
| - | [#48662](https://github.com/sgl-project/sglang/pull/48662) `[Feat] cli: Export Cookbook commands to _commands.json` | infra | main | - |
| - | [#48663](https://github.com/sgl-project/sglang/pull/48663) `[Perf] [AMD] DeepSeek-V4.1: Token-sharded prefill attention under attention TP` | perf,rocm | main | - |
| - | [#48664](https://github.com/sgl-project/sglang/pull/48664) `[Test][NPU] overlap-schedule validation: GLM5/Kimi/DSV4 case reconfig + TEMP nightly scoping` | perf | main | - |
| - | [#48665](https://github.com/sgl-project/sglang/pull/48665) `[Perf] [NPU] chunked-prefill: KV cache pruning for extra-long context` | perf | main | - |
| - | [#48666](https://github.com/sgl-project/sglang/pull/48666) `[Fix] tbo: Capture routed experts at each child's parent rows` | bug,infra | main | - |
| - | [#48667](https://github.com/sgl-project/sglang/pull/48667) `[Fix] hicache: validate decode L3 hits and preserve transferred Mamba state` | bug,perf | main | - |
| - | [#48669](https://github.com/sgl-project/sglang/pull/48669) `[Doc] kernels: correct the documented output dtype parameter name` | perf | main | - |
| - | [#48670](https://github.com/sgl-project/sglang/pull/48670) `[Doc] srt: restore docstring parameter names the signatures no longer take` |  | main | - |
| - | [#48671](https://github.com/sgl-project/sglang/pull/48671) `[Fix] openai: Honor chat-template stop strings for pre-tokenized input_ids` | bug | main | - |
| - | [#48672](https://github.com/sgl-project/sglang/pull/48672) `[Perf] AMD Follower of allreduce auto-tuner from PR 34838 by qunatised QRs` | perf,rocm | main | - |
| - | [#48673](https://github.com/sgl-project/sglang/pull/48673) `[Fix] parser: Fail a DeepSeek-V4/V4.1 thinking turn that stops before </think>` | bug | main | - |
| - | [#48674](https://github.com/sgl-project/sglang/pull/48674) `[Doc] golang: point the Basic Usage TOC entry at the heading that exists` |  | main | - |
| - | [#48675](https://github.com/sgl-project/sglang/pull/48675) `[Feat] dllm: Expose cumulative request-level forward metrics` |  | main | - |
| - | [#48676](https://github.com/sgl-project/sglang/pull/48676) `[Feat] fireredasr2: Add FireRedASR2-LLM speech recognition support` |  | main | - |
| - | [#48678](https://github.com/sgl-project/sglang/pull/48678) `[Feat] docker: Install AWS EFA in the main image; drop the EFA image variant` | infra | main | - |
| - | [#48679](https://github.com/sgl-project/sglang/pull/48679) `[Feat] scheduler: Include per-request time stats in scheduler outputs without enable_metrics` |  | main | - |
| - | [#48680](https://github.com/sgl-project/sglang/pull/48680) `[Fix] cuda_graph: Disable full prefill CUDA graph for hybrid linear attention models (#48593)` | bug,nvidia | main | - |
| - | [#48681](https://github.com/sgl-project/sglang/pull/48681) `[Fix] utils: Wake waiting readers when a waiting writer is cancelled in `RWLock`` | bug | main | - |
| - | [#48682](https://github.com/sgl-project/sglang/pull/48682) `[Fix] Add opt-in FP32 GDN prefix-cache snapshots` | bug,perf | main | - |
| - | [#48683](https://github.com/sgl-project/sglang/pull/48683) `Fix duplicated words in comments and docstrings` | bug,perf | main | - |
| - | [#48684](https://github.com/sgl-project/sglang/pull/48684) `[Doc] diffusion/realtime: Document the session protocol shared by all realtime pipelines` | perf | main | - |
| - | [#48685](https://github.com/sgl-project/sglang/pull/48685) `[Fix] diffusion/realtime: Keep the session open when a client sends a text frame` | bug,perf | main | - |
| - | [#48686](https://github.com/sgl-project/sglang/pull/48686) `[Fix] diffusion/realtime: Close the connection with 1011 when generation fails` | bug,perf | main | - |
| - | [#48687](https://github.com/sgl-project/sglang/pull/48687) `[Fix] diffusion/realtime: Tell clients why a request or event was rejected` | bug,perf | main | - |
| - | [#48688](https://github.com/sgl-project/sglang/pull/48688) `[Perf] longcat-image: Reuse timestep conditioning for serial CFG` | infra,perf | main | - |
| - | [#48689](https://github.com/sgl-project/sglang/pull/48689) `[Feat] qwen4-exp: accept HMM devices for the file-backed PLE table` | infra | main | - |
| - | [#48690](https://github.com/sgl-project/sglang/pull/48690) `[Perf] [AMD] KDA: Build extend chunk indices from host seq lens (SGLANG_ROCM_NO_EXTEND_SYNC)` | infra,perf,rocm | main | - |
| - | [#48691](https://github.com/sgl-project/sglang/pull/48691) `[Fix] routed-experts: Read DP-local rows for NIXL and other EP backends` | bug | main | - |
| - | [#48696](https://github.com/sgl-project/sglang/pull/48696) `[Fix] paged-experts: use libc when Python omits memfd_create` | bug | main | - |
| - | [#48697](https://github.com/sgl-project/sglang/pull/48697) `[Fix] openai: recover Responses API logprob bytes from token ids` | bug | main | - |
| - | [#48698](https://github.com/sgl-project/sglang/pull/48698) `[Fix] openai: Report the raw byte for SentencePiece byte-fallback pieces in chat logprobs` | bug | main | - |
| - | [#48699](https://github.com/sgl-project/sglang/pull/48699) `[CI] [AMD] disaggregation: Send aux data over TCP in the PP disaggregation test` | infra,rocm | main | - |
| - | [#48700](https://github.com/sgl-project/sglang/pull/48700) `[Fix] [AMD] aiter: Reserve the decode workspace in the automatic mem_fraction_static` | bug,infra,rocm | main | - |
| - | [#48701](https://github.com/sgl-project/sglang/pull/48701) `[Perf] [AMD] kimi-k3: Run KDA target verify through AITER's fused FlyDSL kernel` | perf,quant,rocm | main | - |
| - | [#48702](https://github.com/sgl-project/sglang/pull/48702) `[Fix] openai: honor chat template stop strings for input_ids requests` | bug | main | - |
| - | [#48703](https://github.com/sgl-project/sglang/issues/48703) `[Doc] sglang-diffusion guide subclasses ImageSamplingParams, which does not exist (the base class is SamplingP` | perf | ? | - |
| - | [#48704](https://github.com/sgl-project/sglang/pull/48704) `[CI] [AMD] basic_perf: Relax the MI300X p95 limit for embeddings batch size 10` | infra,rocm | main | - |
| - | [#48705](https://github.com/sgl-project/sglang/issues/48705) `[Tracking] Multimodal parity between the Rust and Python frontends` |  | ? | - |
| - | [#48706](https://github.com/sgl-project/sglang/issues/48706) `[Bug] GLM-4.7-Flash ignores ModelOpt FP8 KV-cache scales (self_attn.k_proj.k_scale / v_proj.v_scale)` | perf,quant | ? | - |
| - | [#48707](https://github.com/sgl-project/sglang/issues/48707) `[Bug] DeepSeek MLA FP8 KV cache: k/v_scale corrupt decode (ModelOpt names) or are dropped (compressed-tensors)` | perf,quant,risk | ? | - |
| - | [#48709](https://github.com/sgl-project/sglang/pull/48709) `[Feat] kimi-k3.1: Prefill context parallelism (CP-TP group sharing)` |  | main | - |
| - | [#48710](https://github.com/sgl-project/sglang/pull/48710) `[Feat] kimi-k3.1: MegaMoE, breakable prefill graphs and DFlash under prefill CP` |  | k31-pcp/1-core | - |
| - | [#48711](https://github.com/sgl-project/sglang/pull/48711) `[Perf] kimi-k3.1: Fuse MegaMoE padding masks, DSA indexer Q prep and CP row copies` | perf,quant | k31-pcp/2-megamoe-bcg | - |
| - | [#48712](https://github.com/sgl-project/sglang/pull/48712) `[Feat] cuda-graph: Kimi-K3.1 breakable prefill graphs with PP x prefill CP` | infra,nvidia | k31-pcp/3-fused-kernels | - |
| - | [#48716](https://github.com/sgl-project/sglang/pull/48716) `[Fix] deepseek_v2/glm4_moe_lite/nextn: Handle checkpoint KV-cache scales for MLA attention and NVFP4 draft mod` | bug,perf,quant | main | - |
| - | [#48720](https://github.com/sgl-project/sglang/issues/48720) `Kimi-K3.1 Issue Tracker` |  | ? | - |
| - | [#48724](https://github.com/sgl-project/sglang/pull/48724) `[CI] ci: Stop the suite and exit when a timed-out test process cannot be killed` | infra | main | - |
| - | [#48725](https://github.com/sgl-project/sglang/issues/48725) `[Bug] NextN/MTP drafts of ModelOpt NVFP4 checkpoints get no KV-cache scales, so the draft's FP8 KV cache runs ` | perf,quant | ? | - |
| - | [#48728](https://github.com/sgl-project/sglang/pull/48728) `[Fix] attention: Order the fp8 paged MQA logits kernel's TMEM dealloc after every math warp's tcgen05.ld` | bug,perf,quant | main | - |
| - | [#48729](https://github.com/sgl-project/sglang/pull/48729) `[Fix] dsv4: Keep trtllm-gen sparse MLA from reading lengths the launch right before it wrote` | bug,perf | main | - |
| - | [#48731](https://github.com/sgl-project/sglang/pull/48731) `[Perf] [NVIDIA] dsv41: Gather 8 local Engram rows per program on SM103 and SM107` | nvidia,perf | main | - |
| - | [#48733](https://github.com/sgl-project/sglang/pull/48733) `[Perf] [NVIDIA] dsv41: Index-Q RoPE + fp4 pack runs one thread per fp4 block for prefill-sized calls` | nvidia,perf,quant | main | - |
| - | [#48735](https://github.com/sgl-project/sglang/pull/48735) `[Fix] diffusion/pi05: Honor request seeds for action noise` | bug,perf | main | - |
| - | [#48739](https://github.com/sgl-project/sglang/pull/48739) `[Feat] kimi-k3.1: DSPARK and DFLASH under decode context parallelism` | infra | main | - |
| - | [#48740](https://github.com/sgl-project/sglang/pull/48740) `[Perf] kimi-k3.1: Faster DCP decode reduce (push-combine, V pre-projection, direct exchange)` | bug,perf | main | - |
| - | [#48741](https://github.com/sgl-project/sglang/pull/48741) `[Feat] kimi-k3.1: PD disaggregation under decode context parallelism` |  | main | - |
| - | [#48742](https://github.com/sgl-project/sglang/pull/48742) `[Feat] [NVIDIA] speculative: add an optional recurrent checkpoint commit hook` | nvidia,perf | main | - |
| - | [#48743](https://github.com/sgl-project/sglang/pull/48743) `[Perf] fla: let fused_recurrent_kda update the state pool in place` | perf | main | - |
| - | [#48744](https://github.com/sgl-project/sglang/pull/48744) `[Fix] test: Propagate deterministic prefix logprob failures` | bug | main | - |
| - | [#48745](https://github.com/sgl-project/sglang/pull/48745) `[Fix] kda: Align unfused safe-gate diagonal normalization anchor` | bug,perf | main | - |
| - | [#48746](https://github.com/sgl-project/sglang/pull/48746) `[Feat] model_config: Allow external models to opt into MLA caching` |  | main | - |
| - | [#48747](https://github.com/sgl-project/sglang/issues/48747) `[Bug] FlashInfer and Triton apply checkpoint KV-cache scales to a BF16 KV cache, so decode output is garbage (` | nvidia,perf,quant,risk,rocm | ? | - |
| - | [#48748](https://github.com/sgl-project/sglang/pull/48748) `[Fix] attention: do not apply KV-cache scales to a BF16 KV cache in FlashInfer and Triton` | bug,nvidia,perf,quant,rocm | main | - |
| - | [#48749](https://github.com/sgl-project/sglang/issues/48749) `[Bug] Checkpoint FP8 KV-cache scales are ignored: attention built without quant_config (GLM-4.5, Llama 4, Qwen` | perf,quant | ? | - |
| - | [#48750](https://github.com/sgl-project/sglang/pull/48750) `[Fix] models: load FP8 KV-cache scales for GLM-4.5, Llama 4, HunYuan, HY3, EXAONE-MoE, LFM2 and the Qwen3 fami` | bug,perf,quant | main | - |
| - | [#48753](https://github.com/sgl-project/sglang/pull/48753) `[Feat] rust-server: Refuse more ignored settings, add a launch-time GenerateValidator, and catalogue the Pytho` | perf | oss-sync-5c6b779350 | - |
| - | [#48754](https://github.com/sgl-project/sglang/pull/48754) `[Refactor] kimi-k3.1: Move the DCP prefill KV gather out of the DSA backend` |  | kimi-k3.1-day-0 | - |
| - | [#48757](https://github.com/sgl-project/sglang/pull/48757) `[Fix] scheduler: Abort beam groups on a retract pause and close three request-drop gaps` | bug,infra | main | - |
| - | [#48759](https://github.com/sgl-project/sglang/pull/48759) `[Fix] qwen4_exp: decode the fp8 PLE table on SM80` | bug,quant | main | - |
| - | [#48760](https://github.com/sgl-project/sglang/pull/48760) `[Perf] rotary_embedding: Short-circuit absent modality token scans in M-RoPE get_rope_index` | perf | main | - |
| - | [#48762](https://github.com/sgl-project/sglang/pull/48762) `[Refactor] scheduler: Run every state check through SchedulerInvariantChecker.run` | infra | main | - |
| - | [#48763](https://github.com/sgl-project/sglang/pull/48763) `[Feat] dflash: Serve MoE FFN drafts for DFlash and DSpark` | infra | main | - |
| - | [#48764](https://github.com/sgl-project/sglang/pull/48764) `[Fix] cache: Register UMBP GPU buffers with device metadata` | bug,perf | main | - |
| - | [#48765](https://github.com/sgl-project/sglang/pull/48765) `[Fix] anthropic: Report Kimi prompt usage at stream start` | bug | kimi-k3.1-day-0 | - |
| - | [#48766](https://github.com/sgl-project/sglang/issues/48766) `[Feature] Support SID-based generative retrieval with constrained decoding and optimized beam search` | perf | ? | - |
| - | [#48767](https://github.com/sgl-project/sglang/pull/48767) `[Perf] [AMD] diffusion: Mount the Wan FFN linear+GELU site on gfx1250 with a bit-exact GELU` | infra,perf,rocm | main | - |
| - | [#48768](https://github.com/sgl-project/sglang/pull/48768) `[Perf] [AMD] diffusion: Let aiter RMSNorm read strided Q/K rows instead of copying them` | infra,perf,rocm | main | - |
| - | [#48769](https://github.com/sgl-project/sglang/pull/48769) `[Perf] [AMD] diffusion: Build the ROCm batched-Conv2D VAE input in one Triton pass` | infra,perf,rocm | main | - |
| - | [#48770](https://github.com/sgl-project/sglang/pull/48770) `[Perf] [AMD] DeepSeek-V4.1: Exchange only the indexer selection part attention reads under the HIP row shard` | bug,perf,rocm | main | - |
| - | [#48771](https://github.com/sgl-project/sglang/pull/48771) `[Perf] [AMD] DeepSeek-V4.1: Opt-in SDMA exchange for the HIP indexer row shard` | bug,perf,rocm | main | - |
| - | [#48772](https://github.com/sgl-project/sglang/pull/48772) `[Perf] [AMD] DeepSeek-V4.1: Faster HIP dense prefill indexer (row-group scoring, |s| epilogue, tile-gated top-` | perf,rocm | main | - |
| - | [#48773](https://github.com/sgl-project/sglang/pull/48773) `[Fix] [AMD] topk v2: Fix split-launch short rows on a +0-bin tie overflow` | bug,infra,perf,risk,rocm | main | - |
| - | [#48774](https://github.com/sgl-project/sglang/pull/48774) `[Perf] attention: Parallelize MLA chunked-prefix KV index construction` | perf | main | - |
| - | [#48775](https://github.com/sgl-project/sglang/pull/48775) `[Feat] kimi-k3: Stream tool-call arguments incrementally and fix forced-call grammars` | bug | main | - |
| - | [#48776](https://github.com/sgl-project/sglang/pull/48776) `[Feat] kimi-k3: Read the `thinking` object and map reasoning effort onto K3 tiers` |  | main | - |
| - | [#48777](https://github.com/sgl-project/sglang/pull/48777) `[Feat] kimi-k3: Shape chat responses to the K3 wire format` |  | main | - |
| - | [#48778](https://github.com/sgl-project/sglang/pull/48778) `[Fix] multimodal: Fail bad client media with a client error` | bug | main | - |
| - | [#48779](https://github.com/sgl-project/sglang/pull/48779) `[Feat] scheduler: Size pipeline-parallel prefill chunks by pending load` | perf | main | - |
| - | [#48780](https://github.com/sgl-project/sglang/pull/48780) `[Feature] Add bitsandbytes support for Qwen3-VL / Qwen3-VL-MoE` |  | main | - |
| - | [#48782](https://github.com/sgl-project/sglang/pull/48782) `[Fix] hicache: Wait for overlapping write-through acknowledgements` | bug,perf | main | - |
| - | [#48783](https://github.com/sgl-project/sglang/pull/48783) `[Perf] [NVIDIA] bf16-gemm: SM107 split-K and cute_ext tactics` | nvidia,perf,quant | main | - |
| - | [#48784](https://github.com/sgl-project/sglang/pull/48784) `[Perf] [NVIDIA] eplb: Vectorize the static per-rank dispatch map` | nvidia,perf | main | - |
| - | [#48785](https://github.com/sgl-project/sglang/pull/48785) `[Feat] spec/dflash: keep an all-sliding-window DFLASH draft's KV on the target's SWA slots` | nvidia | main | - |
| - | [#48786](https://github.com/sgl-project/sglang/pull/48786) `[Feat] HiCache: add tma copy kernel for unified layout` | infra,perf | main | - |
| - | [#48787](https://github.com/sgl-project/sglang/pull/48787) `[Perf] [XPU] fp8: Run FP8 dense layers weight-only (W8A16) through sgl_kernel.fp8_linear` | infra,nvidia,perf,quant | main | - |
| - | [#48788](https://github.com/sgl-project/sglang/pull/48788) `[Fix] kimi-k3: Rebuild derived weights in place on weight updates` | bug | main | - |
| - | [#48790](https://github.com/sgl-project/sglang/pull/48790) `[Fix] [Intel] ci/xeon: Build image from the checked-out revision` | bug,infra | main | - |
| - | [#48791](https://github.com/sgl-project/sglang/issues/48791) `[Bug] Reasoning parser splits on first occurrence of closing think tag: quoted </think> inside reasoning trunc` | risk | ? | - |
| - | [#48792](https://github.com/sgl-project/sglang/pull/48792) `[Perf] [XPU] vae-layernorm-silu: add Xpu triton path to replace torch` | nvidia,perf,rocm | main | - |
| - | [#48793](https://github.com/sgl-project/sglang/issues/48793) `[Bug] Model gateway silently drops `cache_salt` on chat completions` | risk | ? | - |
| - | [#48794](https://github.com/sgl-project/sglang/pull/48794) `[Fix] quantization: Pad the Marlin N tile for compressed-tensors WNA16` | bug,quant | main | - |
| - | [#48795](https://github.com/sgl-project/sglang/pull/48795) `[Fix] responses: Merge a commentary preamble with its tool calls when replaying history` | bug | main | - |
| - | [#48796](https://github.com/sgl-project/sglang/pull/48796) `[Feat] cp: Add Qwen3.5/Qwen3.8 prefill with Symm and MegaMoE` | infra,nvidia,perf | main | - |
| - | [#48797](https://github.com/sgl-project/sglang/pull/48797) `[Test] server-info: Pin the Python frontend in two /server_info unit tests` | infra | oss-sync-f1de93624a | - |
| - | [#48798](https://github.com/sgl-project/sglang/pull/48798) `[Feat] rust-server: Let the launching process list the ports its node's Rust listeners bind` | infra | oss-sync-f1de93624a | - |
| - | [#48800](https://github.com/sgl-project/sglang/pull/48800) `[Feat] request_logger: Summarize media inputs per modality in request logs` |  | main | - |
| - | [#48801](https://github.com/sgl-project/sglang/pull/48801) `[Feat] sgl-router: Log per-request image, video and audio counts in the access log` |  | main | - |
| - | [#48802](https://github.com/sgl-project/sglang/issues/48802) `[Bug] Decode HiCache restore returns HTTP 500 under host-cache pressure with GLM-5.3-Flash` | perf | ? | - |
| - | [#48806](https://github.com/sgl-project/sglang/pull/48806) `[Perf] [AMD] GLM5.3: Allow an FP8 E4M3 KV cache for Triton sparse attention on gfx950` | perf,quant,rocm | main | - |
| - | [#48807](https://github.com/sgl-project/sglang/pull/48807) `[Test] npu/glm5.3: Add 2P2D PCP EPLB GPQA accuracy test` | risk | main | - |
| - | [#48810](https://github.com/sgl-project/sglang/pull/48810) `[Fix] [AMD] mxfp4: Keep MoE weight layout and dispatch consistent with the selected runner` | bug,infra,quant,rocm | main | - |
| - | [#48811](https://github.com/sgl-project/sglang/pull/48811) `[Fix] disaggregation: Fail a prefill KV transfer whose decode never completes it` | bug | main | - |
| - | [#48812](https://github.com/sgl-project/sglang/pull/48812) `[Fix] weight_checker: Compare weights on the live weight's device` | bug,infra | main | - |
| - | [#48813](https://github.com/sgl-project/sglang/pull/48813) `[Fix] disaggregation: Advance a Mamba request's unpublished KV under a write-through cache` | bug,perf | main | - |
| - | [#48814](https://github.com/sgl-project/sglang/pull/48814) `[Feat] simulator: Route native staged execution through SimOpus` | infra | main | - |
| - | [#48815](https://github.com/sgl-project/sglang/pull/48815) `[Fix] rust-server: Keep the DP control fan-out off an inherited HTTP proxy` | bug | oss-sync-219fe11113 | - |
| - | [#48818](https://github.com/sgl-project/sglang/pull/48818) `[Feat] rust-server: Let an embedding package register scheduler state fields for /server_info` |  | oss-sync-f1de93624a | - |
| - | [#48819](https://github.com/sgl-project/sglang/issues/48819) `[Bug] SAIL/PPU memory capacity query incorrectly invokes nvidia-smi and warns about NVIDIA drivers` | nvidia | ? | - |
| - | [#48820](https://github.com/sgl-project/sglang/pull/48820) `[Feat] linker: Support async lookup in prefetch mode` | perf | main | - |
| - | [#48822](https://github.com/sgl-project/sglang/issues/48822) `[RFC] Add NPU RLHF Lifecycle Tests` |  | ? | - |
| - | [#48823](https://github.com/sgl-project/sglang/pull/48823) `[Feat] linker: Support lmcache external linker` | perf | main | - |
| - | [#48824](https://github.com/sgl-project/sglang/pull/48824) `[Fix] dp-attention: Preserve original forward mode in prefill graph replay` | bug | main | - |
| - | [#48825](https://github.com/sgl-project/sglang/pull/48825) `[Fix] [SAIL] utils: Use device properties for memory capacity` | bug | main | - |
| - | [#48826](https://github.com/sgl-project/sglang/pull/48826) `[Feat] speculative: Report completed adaptive round execution by tier` |  | main | - |
| - | [#48830](https://github.com/sgl-project/sglang/pull/48830) `[CI] [AMD] spur: Run 1-, 2- and 4-GPU suites on part of a node` | infra,rocm | main | - |
| - | [#48831](https://github.com/sgl-project/sglang/pull/48831) `[Perf] dspark: Prepare the DSpark draft attention metadata through the glue graph under every verify mode` | perf | main | - |
| - | [#48832](https://github.com/sgl-project/sglang/pull/48832) `[Perf] dsv4: Run compact target verify's ratio 1 and 2 compressors through the fused kernels` | perf | qiaolin/dsv41-compact-draft-glue | - |
| - | [#48833](https://github.com/sgl-project/sglang/pull/48833) `[Perf] dspark: Build the compact verify window and stage its padded layout in one launch each` | infra,perf | qiaolin/dsv41-compact-fused-low-ratio-compress | - |
| - | [#48834](https://github.com/sgl-project/sglang/pull/48834) `[Fix] grpc: preserve Prometheus metric names` | bug | main | - |
| - | [#48835](https://github.com/sgl-project/sglang/pull/48835) `[Fix] [NPU] eplb: Preserve A5 expert storage during migration` | bug | main | - |
| - | [#48836](https://github.com/sgl-project/sglang/pull/48836) `[Fix] [SAIL] utils: Query device memory without nvidia-smi` | bug,nvidia | main | - |
| - | [#48837](https://github.com/sgl-project/sglang/issues/48837) `[Bug] PD decode server fails to start with CUDA OOM on hybrid mamba models: mamba memory budget ignores decode` | nvidia | ? | - |
| - | [#48838](https://github.com/sgl-project/sglang/pull/48838) `[Fix] mem_cache: charge PD decode pre-allocated slots in the mamba memory budget` | bug | main | - |
| - | [#48840](https://github.com/sgl-project/sglang/pull/48840) `[Fix] hisparse: disambiguate __ffsll for HIP's dual overloads` | bug,perf,rocm | main | - |
| - | [#48841](https://github.com/sgl-project/sglang/pull/48841) `[Perf] kimi_k3: Compile only reachable attention-residual variants` | perf | main | - |
| - | [#48842](https://github.com/sgl-project/sglang/pull/48842) `[Feat] dflash: Support sliding-window draft KV pools for NIXL PD` |  | main | - |
| - | [#48843](https://github.com/sgl-project/sglang/pull/48843) `[Fix] distributed: Isolate local SHM writer ports by rank` | bug | main | - |
| - | [#48844](https://github.com/sgl-project/sglang/pull/48844) `[Fix] benchmark: Flush one-batch benchmark output` | bug,perf | main | - |
| - | [#48845](https://github.com/sgl-project/sglang/pull/48845) `[Fix] sgl-model-gateway: Preserve cache_salt on chat completions` | bug | main | - |
| - | [#48846](https://github.com/sgl-project/sglang/pull/48846) `[Feat] hisparse: reject unvalidated speculative algorithms by name` |  | main | - |
| - | [#48847](https://github.com/sgl-project/sglang/pull/48847) `[Perf] [XPU] graph: Support full prefill graph for GDN/Mamba and Gemma models` | nvidia,perf | main | - |
| - | [#48848](https://github.com/sgl-project/sglang/pull/48848) `[Fix] HiCache: Wait for decode prefetch before publishing prefix length` | bug | main | - |
| - | [#48850](https://github.com/sgl-project/sglang/pull/48850) `[Fix] deepseek_v4: Capture decoder-tail graphs at startup, never on a step a DP rank skips` | bug | main | - |
| - | [#48851](https://github.com/sgl-project/sglang/pull/48851) `[Chore] [AMD] monokernels: Pin sgl-amd-mono at 7a4a552d` | infra,rocm | main | - |
| - | [#48852](https://github.com/sgl-project/sglang/pull/48852) `[Fix] mem_cache: Release a request's unified KV only after its last forward retires` | bug,infra,perf | main | - |
| - | [#48854](https://github.com/sgl-project/sglang/pull/48854) `[CI] [AMD] ci: Run 16 kernel tests per PR on AMD, as CUDA does` | infra,nvidia,perf,quant,rocm | main | - |
| - | [#48855](https://github.com/sgl-project/sglang/pull/48855) `[Perf]cosmos3: Explore opt-in BF16 DiT CUDA Graphs` | nvidia,perf | main | - |
| - | [#48858](https://github.com/sgl-project/sglang/pull/48858) `[Feat] simulator: Simulate prefill-decode disaggregation with modelled KV transfer` | infra | main | - |
| - | [#48859](https://github.com/sgl-project/sglang/pull/48859) `[Feat] kimi_k3: Add opt-in FlashInfer fused KDA decode consumer` | nvidia,perf | main | - |
| - | [#48860](https://github.com/sgl-project/sglang/pull/48860) `[Fix] cuda_graph: Retain capture inputs for full graph replay` | bug | main | - |
| - | [#48861](https://github.com/sgl-project/sglang/pull/48861) `[Perf] [CPU] graph: Move SWA index translation into Intel AMX attention kernels and prune masked prefix loads` | perf | main | - |
| - | [#48862](https://github.com/sgl-project/sglang/pull/48862) `[Fix] [AMD] all-reduce: Check quick reduce before custom AR so ROCM_QUICK_REDUCE_QUANTIZATION takes effect` | bug,quant,rocm | main | - |
| - | [#48863](https://github.com/sgl-project/sglang/pull/48863) `[Perf] [AMD] dsa: Use a spill-free BF16 tile for the triton sparse-MLA split-K decode on gfx950` | perf,rocm | main | - |
| - | [#48864](https://github.com/sgl-project/sglang/pull/48864) `[Perf] [AMD] kda: Row-streamed chunked verify for ReplaySSM ring mode on gfx950` | perf,rocm | main | - |
| - | [#48865](https://github.com/sgl-project/sglang/pull/48865) `[Perf] [AMD] deepseek-v4.1: Reuse the low-ratio identity extend fill across the layers of a ratio` | perf,rocm | main | - |
| - | [#48866](https://github.com/sgl-project/sglang/pull/48866) `[Perf] [AMD] deepseek-v4: Fill a run of identity prefill requests in one batched write` | perf,rocm | main | - |
| - | [#48867](https://github.com/sgl-project/sglang/pull/48867) `[Perf] kimi_k3: Batch expert weight transfers during initial loading` | perf | main | - |
| - | [#48869](https://github.com/sgl-project/sglang/pull/48869) `[Perf] kimi_k3: Overlap kernel compilation with checkpoint loading` | perf | main | - |
| - | [#48870](https://github.com/sgl-project/sglang/pull/48870) `[Perf] utils: Avoid per-element list allocation in flatten_hidden for flat float rows` | perf | main | - |
| - | [#48871](https://github.com/sgl-project/sglang/pull/48871) `[Fix] modelopt_fp4: Skip swizzled NVFP4 MoE blockscales on Marlin paths` | bug,nvidia,quant | main | - |
| - | [#48872](https://github.com/sgl-project/sglang/pull/48872) `[Fix] disaggregation: Make the KV checksum digest each state component's own transfer payload` | bug | main | - |
| - | [#48874](https://github.com/sgl-project/sglang/pull/48874) `[Fix] mooncake: Handle Ascend DSV4 PP KV layouts` | bug,infra,nvidia,perf,quant,rocm | main | - |
| - | [#48875](https://github.com/sgl-project/sglang/pull/48875) `[Perf] [AMD] GLM-5.3-Flash: Replay breakable prefill graphs with cached prefixes and HIP KDA` | perf,rocm | main | - |
| - | [#48876](https://github.com/sgl-project/sglang/pull/48876) `[Perf] qwen2.5-vl: Avoid empty vision windows` | perf | main | - |
| - | [#48877](https://github.com/sgl-project/sglang/pull/48877) `[Feat] kimi-k3.1: HiCache under decode context parallelism` |  | main | - |
| - | [#48878](https://github.com/sgl-project/sglang/pull/48878) `[Perf] [AMD] kimi-k3: Write the fp8-Q asm verify query in the fused Q/cache launch` | perf,quant,rocm | main | - |
| - | [#48879](https://github.com/sgl-project/sglang/pull/48879) `[Doc] cookbook: Fix Qwen3.8-Flash-Next thinking-mode description` | bug | main | - |
| - | [#48881](https://github.com/sgl-project/sglang/pull/48881) `[Perf] multimodal: Avoid CPU thread-pool fanout in SHM copy` | perf | main | - |
| - | [#48882](https://github.com/sgl-project/sglang/pull/48882) `[Fix] [NPU] dsa: Allow DSA DCP with PD disaggregation` | bug,infra | main | - |
| - | [#48883](https://github.com/sgl-project/sglang/pull/48883) `[Fix] disaggregation: Make CommonKVReceiver._clear() idempotent under early allocation` | bug | main | - |
| - | [#48884](https://github.com/sgl-project/sglang/pull/48884) `[Fix] multimodal: Preserve processor options when splitting requests` | bug | main | - |
| - | [#48887](https://github.com/sgl-project/sglang/pull/48887) `[Fix] sampling: Validate parallel sample counts before batch expansion` | bug | main | - |
| - | [#48888](https://github.com/sgl-project/sglang/pull/48888) `[Test] [NVIDIA] ep: Rewrite the FlashInfer dispatcher test for FlashInfer 0.7.3` | nvidia | main | - |
| - | [#48889](https://github.com/sgl-project/sglang/pull/48889) `[Fix] disaggregation: Preserve in-flight staging count when reopening a bootstrap room` | bug | main | - |
| - | [#48890](https://github.com/sgl-project/sglang/pull/48890) `[WIP] [Diffusion] Add LoRA merge mode disabled` | perf | main | - |
| - | [#48891](https://github.com/sgl-project/sglang/pull/48891) `[Perf] [SM100] attention: optimize sparse MLA prefill for small heads` | infra,nvidia,perf | main | - |
| - | [#48892](https://github.com/sgl-project/sglang/issues/48892) `[CI] multimodal-gen-test-2-gpu (test_kandinsky6_sr_decode_parallel spatial-2) fails on main: Tensor-likes are ` | infra | ? | - |
| - | [#48893](https://github.com/sgl-project/sglang/pull/48893) `[Perf] [AMD] aiter: FP8 MLA prefix prefill on gfx1250 via the FlyDSL a8w8 FMHA` | perf,quant,rocm | main | - |
| - | [#48894](https://github.com/sgl-project/sglang/pull/48894) `[Test] [NPU] kimi_k3: tune the 128k decode prefix case to repeat_rate=0.99 / request_rate=0` | perf | main | - |
| - | [#48895](https://github.com/sgl-project/sglang/pull/48895) `[Perf] [NVIDIA] dsa/dcp: Fused DCP8 indexer top-k for decode` | infra,nvidia,perf | main | - |
| - | [#48896](https://github.com/sgl-project/sglang/pull/48896) `[Doc] blogs: Sync LMSYS SGLang blog cards` |  | main | - |
| - | [#48897](https://github.com/sgl-project/sglang/pull/48897) `[Perf] [AMD] aiter: Opt unified verify out of the host seq_lens mirror for spec-v2 overlap` | perf,rocm | main | - |
| - | [#48898](https://github.com/sgl-project/sglang/pull/48898) `[Feat] [NVIDIA] DSA: Add FlashInfer GVR V2 top-k backend` | nvidia,perf | main | - |
| - | [#48899](https://github.com/sgl-project/sglang/pull/48899) `[Feat] hisparse: support DFLASH speculative decoding` |  | main | - |
| - | [#48900](https://github.com/sgl-project/sglang/pull/48900) `[Feat] diffusion: Route named layers to a second online quantization format` | perf,quant | main | - |
| - | [#48901](https://github.com/sgl-project/sglang/pull/48901) `[Fix] speculative: Preserve repetition penalties in DFLASH and DSPARK` | bug | main | - |
| - | [#48902](https://github.com/sgl-project/sglang/pull/48902) `[Feat] [AMD] kimi-k3.1: PD over MoRI between same-size DCP roles` | infra,rocm | kimi-k3.1-day-0-amd | - |
| - | [#48903](https://github.com/sgl-project/sglang/pull/48903) `[Test] kandinsky6-sr: Check spatial-shard decode exactly in fp32 and with a calibrated bf16 outlier budget` | infra,perf | main | - |
| - | [#48904](https://github.com/sgl-project/sglang/issues/48904) `[Bug] Qwen3, Qwen3-VL, Qwen3-VL-MoE, Qwen3-Omni-MoE, Qwen3-ASR and Qwen3 rerankers ignore checkpoint FP8 KV-ca` | perf,quant | ? | - |
| - | [#48906](https://github.com/sgl-project/sglang/issues/48906) `[Bug] NVFP4 Marlin path (default on SM80-SM90) decodes E4M3 subnormal block scales as 0 with bfloat16 activati` | nvidia,quant | ? | - |
| - | [#48907](https://github.com/sgl-project/sglang/pull/48907) `[Fix] marlin: Decode E4M3 subnormal NVFP4 block scales exactly with bfloat16 activations` | bug,nvidia,perf,quant | main | - |
| - | [#48908](https://github.com/sgl-project/sglang/pull/48908) `[Perf] [NVIDIA] deepseek_v4: Token-shard SM90 sparse-MLA prefill under attention TP` | nvidia,perf | main | - |
| - | [#48909](https://github.com/sgl-project/sglang/pull/48909) `[Feat] [Ascend] Add A3 MegaMoE support for SwiGLU/SiTU and BF16/INT experts` |  | main | - |
| - | [#48910](https://github.com/sgl-project/sglang/pull/48910) `[Perf] [XPU] minimax-h3: Use bit-exact fused XPU kernels in the DiT` | nvidia,perf | main | - |
| - | [#48911](https://github.com/sgl-project/sglang/issues/48911) `[Bug] More model loaders drop checkpoint FP8 KV-cache scales (Qwen1.5/2-MoE, Qwen2.5-VL, Qwen3-Next, AFMoE, Ge` | perf,quant | ? | - |
| - | [#48912](https://github.com/sgl-project/sglang/pull/48912) `[Fix] models: map checkpoint KV-cache scale names in more model loaders` | bug,perf,quant | main | - |
| - | [#48913](https://github.com/sgl-project/sglang/issues/48913) `[Bug] Gemma 4 and Gemma 3n KV-shared layers read the FP8 KV cache with scale 1.0 instead of the writing layer'` | perf,quant | ? | - |
| - | [#48914](https://github.com/sgl-project/sglang/pull/48914) `[Fix] gemma: KV-shared layers use the KV-cache scales of the layer whose cache they read` | bug,perf,quant | main | - |
| - | [#48915](https://github.com/sgl-project/sglang/pull/48915) `[Fix] spec: load FP8 KV-cache scales in the DFlash and LLaMA EAGLE-3 draft loaders` | bug,perf,quant | main | - |
| - | [#48916](https://github.com/sgl-project/sglang/pull/48916) `[Fix] parser: split reasoning on last think end token` | bug | main | - |
| - | [#48917](https://github.com/sgl-project/sglang/issues/48917) `[Bug] TorchNativeLlamaForCausalLM / TorchNativePhi3ForCausalLM load no checkpoint tensors and no KV-cache scal` | perf,quant | ? | - |
| - | [#48918](https://github.com/sgl-project/sglang/pull/48918) `[Fix] torch_native_llama: load checkpoint tensors and KV-cache scales` | bug,perf,quant | main | - |
| - | [#48919](https://github.com/sgl-project/sglang/issues/48919) `[Bug] NVFP4 W4A4 linear keeps the largest weight global scale of fused q/k/v and gate/up layers without a chec` | perf,quant | ? | - |
| - | [#48920](https://github.com/sgl-project/sglang/pull/48920) `[Fix] quantization: check fused NVFP4 global scales in the W4A4 linear post-load step` | bug,nvidia,perf,quant | main | - |
| - | [#48921](https://github.com/sgl-project/sglang/pull/48921) `[Perf] mlp: Extend dense SwiGLU/block-FP8 quant fusion to SM90, prefill and TP>1` | nvidia,perf,quant | main | - |
| - | [#48922](https://github.com/sgl-project/sglang/issues/48922) `[Bug] SM120 DeepSeek-V4.1: low-ratio indexer decode dies with schedule_meta=None (fp8_fp4_paged_mqa_logits arg` | nvidia | ? | - |
| - | [#48923](https://github.com/sgl-project/sglang/pull/48923) `[Feat] [Ascend] Integrate A5 MXFP experts with MegaMoE` |  | megamoe_glm_support | - |

### sgl-amd-mono — Merged / closed (16 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#26](https://github.com/sgl-project/sgl-amd-mono/pull/26) `[Feat] [MI355X] muse_spark: Whole-layer monokernels for Muse Spark` | rocm | main | - |
| - | [#29](https://github.com/sgl-project/sgl-amd-mono/pull/29) `[Feat] [MI355X] qwen38_flash_next: Add the Qwen3.8-Flash-Next 180B monokernel` | rocm | main | - |
| - | [#65](https://github.com/sgl-project/sgl-amd-mono/pull/65) `[Fix] deepseek_v41: Pass input_ids to SGLang's Engram so image rows stay in its gate` | bug | main | - |
| - | [#71](https://github.com/sgl-project/sgl-amd-mono/pull/71) `[Feat] [MI355X] glm53_flash: Serve MTP verify steps on the monokernel` | rocm | main | - |
| - | [#75](https://github.com/sgl-project/sgl-amd-mono/pull/75) `[Feat] [MI355X] glm53: The NextN draft steps on their own launches` | rocm | main | - |
| - | [#85](https://github.com/sgl-project/sgl-amd-mono/pull/85) `[Perf] [MI355X] glm53: Shared layer and MoE hand-offs, NextN entry, K-split front, indexer launch, MoE expert ` | perf,rocm | main | - |
| - | [#86](https://github.com/sgl-project/sgl-amd-mono/pull/86) `[Perf] [MI355X] glm53: Long-context indexer: two-row scoring from 4 rows, keys straight into registers, the sc` | perf,rocm | main | - |
| - | [#91](https://github.com/sgl-project/sgl-amd-mono/pull/91) `[Perf] [MI355X] deepseek_v41: Push gathered rows in whole 128 B lines` | perf,rocm | main | - |
| - | [#94](https://github.com/sgl-project/sgl-amd-mono/pull/94) `[Fix] glm53_flash: Read the KDA layer cache from the linear-attention backend` | bug,perf | main | - |
| - | [#95](https://github.com/sgl-project/sgl-amd-mono/pull/95) `[Perf] [MI355X] deepseek_v41: DSpark step glue in fewer launches, Markov draft sampling, faster K1 and K2` | perf,rocm | main | - |
| - | [#96](https://github.com/sgl-project/sgl-amd-mono/pull/96) `[Chore] maintainer: updates` |  | main | - |
| - | [#97](https://github.com/sgl-project/sgl-amd-mono/pull/97) `[Fix] [MI355X] glm53_flash: Stop the sparse-attention fault on rows past 262,144 tokens` | bug,rocm | main | - |
| - | [#102](https://github.com/sgl-project/sgl-amd-mono/pull/102) `[Feat] [MI355X] kimi_k31: Wide-row layer launch for Kimi-K3.1 verify steps` | rocm | main | - |
| - | [#103](https://github.com/sgl-project/sgl-amd-mono/pull/103) `[Feat] [MI355X] kimi_k3/kimi_k31: Kimi-K3's gfx950 launches, and Kimi-K3.1 steps of up to 8 rows on them` | rocm | main | - |
| - | [#104](https://github.com/sgl-project/sgl-amd-mono/pull/104) `[Fix] tests: Run the unit and Kimi-K3 kernel tests on current SGLang` | bug,perf | main | - |
| - | [#105](https://github.com/sgl-project/sgl-amd-mono/pull/105) `[Refactor] [MI355X] kimi_k3/kimi_k31: One serving form, no copied helpers, every wide width a bucket` | rocm | main | - |

### sgl-amd-mono — Open / submitted (16 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#87](https://github.com/sgl-project/sgl-amd-mono/pull/87) `[Perf] [MI355X] deepseek_v41: Pipeline routed FFN-down FP4 weight loads through double-buffered LDS at TP2` | perf,quant,rocm | main | - |
| - | [#88](https://github.com/sgl-project/sgl-amd-mono/pull/88) `[Feat] [MI355X] qwen38_a95b_mxfp4: Serve NEXTN verify steps with K2` | quant,rocm | main | - |
| - | [#89](https://github.com/sgl-project/sgl-amd-mono/pull/89) `[Feat] [MI355X] qwen38_a95b_mxfp4: Run the GDN front of decode steps as one K1 launch` | quant,rocm | main | - |
| - | [#90](https://github.com/sgl-project/sgl-amd-mono/pull/90) `[Feat] [MI355X] qwen38_a95b_mxfp4: Run the fused shared expert of sgl-project/sglang#41899` | perf,quant,rocm | main | - |
| - | [#92](https://github.com/sgl-project/sgl-amd-mono/pull/92) `[Feat] [MI355X] qwen38_a95b_mxfp4: Run the MXFP4 GDN projections of sgl-project/sglang#43839` | quant,rocm | main | - |
| - | [#93](https://github.com/sgl-project/sgl-amd-mono/pull/93) `[Feat] [MI355X] qwen38_flash_next: Serve TP2 decode of the MXFP4 model` | quant,rocm | main | - |
| - | [#98](https://github.com/sgl-project/sgl-amd-mono/pull/98) `[Feat] [MI355X] glm53_flash: Run verify steps of up to 16 rows on the monokernel` | rocm | main | - |
| - | [#99](https://github.com/sgl-project/sgl-amd-mono/pull/99) `Mvarjoka/kimi k3` |  | billishyahao/kimi_k3 | - |
| - | [#100](https://github.com/sgl-project/sgl-amd-mono/pull/100) `[Perf] [MI355X] glm53_flash: Score a verify request's index tiles once for its rows` | perf,rocm | main | - |
| - | [#101](https://github.com/sgl-project/sgl-amd-mono/pull/101) `[Feat] common: Check each compiled kernel's residency and scratch where a runner builds it` | perf | main | - |
| - | [#106](https://github.com/sgl-project/sgl-amd-mono/pull/106) `[Perf] [MI355X] deepseek_v41: One launch per reuse layer, the index sources' compressor in K1, the Engram proj` | perf,rocm | main | - |
| - | [#107](https://github.com/sgl-project/sgl-amd-mono/pull/107) `[CI] ci: Run the PR review guideline's checks on dedicated MI355X nodes` | infra,rocm | main | - |
| - | [#108](https://github.com/sgl-project/sgl-amd-mono/pull/108) `[Fix] [MI355X] kimi_k3: Size the warmup bank for the block-write row` | bug,rocm | main | - |
| - | [#109](https://github.com/sgl-project/sgl-amd-mono/pull/109) `[CI] ci: Pin the PR test's two runners to Crusoe v3-060 and v3-123` | infra | main | - |
| - | [#110](https://github.com/sgl-project/sgl-amd-mono/pull/110) `[Fix] [MI355X] glm53: Keep uv's output tile inside the declared LDS` | bug,rocm | main | - |
| - | [#111](https://github.com/sgl-project/sgl-amd-mono/pull/111) `[Perf] [MI355X] kimi_k31: Make the routed experts' top-k, sort and mxfp8 quant in the wide launch` | perf,quant,rocm | main | - |

### ATOM — Merged / closed (99 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#2322](https://github.com/ROCm/ATOM/issues/2322) `[CI] Approving a PR restarts the CI pipeline` | infra | ? | - |
| - | [#2364](https://github.com/ROCm/ATOM/pull/2364) `feat(sp): add Ulysses sequence parallelism and optimize M3 prefill communication` | infra,perf | main | - |
| - | [#2365](https://github.com/ROCm/ATOM/pull/2365) `[feature] support pp>1 for Kimi-K3` | infra | main | - |
| - | [#2374](https://github.com/ROCm/ATOM/pull/2374) `ci: avoid restarting tests on PR approval` | infra | main | - |
| - | [#2453](https://github.com/ROCm/ATOM/pull/2453) `[1/3 entrypoint refactor] [feat(mesh)]: unify multi-API ingress for HTTP and ext-proc` | infra | main | - |
| - | [#2471](https://github.com/ROCm/ATOM/pull/2471) `feat(observability): add decode-step engine stats` | infra | main | - |
| - | [#2489](https://github.com/ROCm/ATOM/pull/2489) `[gfx1250] Add ATOM_MLA_ABSORB_BF16: keep MLA-absorb weights in BF16` | rocm | main | - |
| - | [#2570](https://github.com/ROCm/ATOM/pull/2570) `[ATOMesh][MoRIIO] Enable Kimi K3 and update the MoRI IO changes to support Kimi KDA state for KV.` | bug,rocm | main | - |
| - | [#2610](https://github.com/ROCm/ATOM/pull/2610) `perf(qwen): integrate Mono decode and optimized TP1 MTP3 serving` | infra,perf | main | - |
| - | [#2653](https://github.com/ROCm/ATOM/pull/2653) `perf(sglang): aiter FlyDSL QSA sparse attention for Qwen3.8-Flash-Next eager prefill` | infra,perf,rocm | main | - |
| - | [#2655](https://github.com/ROCm/ATOM/pull/2655) `fix(qwen4-exp): register the QSA FP8 scale planes for KV offload` | bug,infra,quant | lingzha/qwen38-lmcache | - |
| - | [#2663](https://github.com/ROCm/ATOM/pull/2663) `feat(spec): capture the Qwen3.8 MTP draft steps in CUDA graphs (MRoPE)` | infra,nvidia | main | - |
| - | [#2665](https://github.com/ROCm/ATOM/pull/2665) `perf(moe): Triton softmax top-k routing, bit-identical to AITER` | perf,rocm | main | - |
| - | [#2691](https://github.com/ROCm/ATOM/pull/2691) `fix(mxfp4): pad an MLP pair's K inside the parallel linears; refuse an unaligned K at load` | bug,perf,quant | main | - |
| - | [#2707](https://github.com/ROCm/ATOM/pull/2707) `perf(qwen3.5): Triton top-k router + pad the 513-row MoE router weight to 528` | infra,perf,rocm | main | - |
| - | [#2722](https://github.com/ROCm/ATOM/pull/2722) `perf(v4): Split the prefill sparse indexer by query row across TP` | infra,perf | main | - |
| - | [#2727](https://github.com/ROCm/ATOM/pull/2727) `fix(dp): preserve prefill alignment with capped pending probes` | bug,infra | main | - |
| - | [#2738](https://github.com/ROCm/ATOM/pull/2738) `perf(qwen3.5): merge the GDN in_proj_ba into in_proj_qkvz for per-token FP8` | infra,perf,quant | main | - |
| - | [#2739](https://github.com/ROCm/ATOM/pull/2739) `perf(norm): optional per-token FP8 quant folded into GemmaRMSNorm` | infra,perf,quant | zhiwei/qwen35-gdn-inproj-merge | - |
| - | [#2757](https://github.com/ROCm/ATOM/pull/2757) `[SGL ATOM]Upgrade SGLang to 0.5.22 and publish ROCm 7 and 10 images` | infra,rocm | main | - |
| - | [#2759](https://github.com/ROCm/ATOM/pull/2759) `[Offload] Address M3 Store review follow-ups` |  | mengqing/mooncake-store-m3-page | - |
| - | [#2761](https://github.com/ROCm/ATOM/pull/2761) `perf(attention): leave gluon scratch to aiter; state the sparse prefill plan precondition` | infra,perf,rocm | main | - |
| - | [#2765](https://github.com/ROCm/ATOM/pull/2765) `feat(moe): build MegaMoE from an aiter MegaMoERecipe (with the stage1/stage2 switches)` | infra,rocm | main | - |
| - | [#2779](https://github.com/ROCm/ATOM/pull/2779) `fix(sglang): run MI308 Qwen3.5-35B PTPC on the untuned MoE path` | bug,infra,perf,rocm | main | - |
| - | [#2785](https://github.com/ROCm/ATOM/pull/2785) `fix(plugin): build SGLang DP-attention ParallelConfig per rank` | bug,infra | main | - |
| - | [#2810](https://github.com/ROCm/ATOM/pull/2810) `[gfx1250] DeepSeek-V4.1: HIP Mega-MHC with row-major fused MXFP8` | infra,perf,quant,rocm | main | - |
| - | [#2817](https://github.com/ROCm/ATOM/pull/2817) `[ATOMesh][DI][CI] Enable WideEP with MoRI V1LL with DSV3 & Kimi K2.5 MXFP4` | infra,quant | main | - |
| - | [#2834](https://github.com/ROCm/ATOM/pull/2834) `perf(qwen4_exp): sequence-parallel HC residual streams for Qwen3.8-Flash-Next TP prefill` | perf | main | - |
| - | [#2835](https://github.com/ROCm/ATOM/pull/2835) `fix(plugin): fix Kimi-K3's KDA autotune key in the plugin, not the vLLM image` | bug,infra,perf | main | - |
| - | [#2836](https://github.com/ROCm/ATOM/pull/2836) `fix(metrics): make per-request context gauges opt-in via CLI` | bug,infra | main | - |
| - | [#2837](https://github.com/ROCm/ATOM/pull/2837) `fix(runtime): propagate MP failures and return unhealthy status` | bug,infra | main | - |
| - | [#2841](https://github.com/ROCm/ATOM/pull/2841) `fix(k3-mono): read o_norm as native fp32, accept bf16 latent projections` | bug | main | - |
| - | [#2844](https://github.com/ROCm/ATOM/pull/2844) `fix(api): align reasoning controls and frontend protocol contracts` | bug,infra | main | - |
| - | [#2849](https://github.com/ROCm/ATOM/pull/2849) `fix(kimi-k3): hold tool_choice="required" to the tools channel on the GPU` | bug,infra | main | - |
| - | [#2856](https://github.com/ROCm/ATOM/pull/2856) `feat(api): return Chat token logprobs with DSpark support` | infra | main | - |
| - | [#2859](https://github.com/ROCm/ATOM/pull/2859) `[DSV4.1] Head-blocked query RoPE in the fused rope/window seam` | infra,perf | main | - |
| - | [#2862](https://github.com/ROCm/ATOM/pull/2862) `feat(api): constrain JSON output and expose deployment capabilities` | infra | main | - |
| - | [#2867](https://github.com/ROCm/ATOM/pull/2867) `[Recipe] Qwen3.5 MLPerf Endpoints: 4xTP1 c16 node (TP=1), shared expert side stream for it` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2868](https://github.com/ROCm/ATOM/pull/2868) `[Qwen3.5] c2048 DEP4: stop prefix-resumed requests decoding garbage (GDN prefill eager in DP prefill graphs, d` | risk | alizaidy/gfx1250-qwen-support | - |
| - | [#2869](https://github.com/ROCm/ATOM/pull/2869) `[Qwen3.5] Fix NaN decoding from stale PAGE checkpoint bytes reused as KV` | bug,risk | alizaidy/gfx1250-qwen-support | - |
| - | [#2870](https://github.com/ROCm/ATOM/pull/2870) `[MHA] Unified-attention prefill: run the kernel over the scheduled rows only` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2871](https://github.com/ROCm/ATOM/pull/2871) `feat(mono): shared DSA indexer mono launch; Kimi-K3 mono to 64 rows, plain decode and ReplaySSM` | infra | main | - |
| - | [#2872](https://github.com/ROCm/ATOM/pull/2872) `[gfx1250] Enable Qwen3.5 LMCache offload and bound GPU checkpoints` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2874](https://github.com/ROCm/ATOM/pull/2874) `[Qwen3.5] fp8 KV cache with unified attention on gfx1250` | perf,quant,rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2878](https://github.com/ROCm/ATOM/pull/2878) `[gfx1250] Qwen3.5: fixes for the Triton MoE experts over MegaMoE` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2884](https://github.com/ROCm/ATOM/pull/2884) `[State] GPU budget for PAGE state checkpoint images that keeps each conversation's resume points` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2888](https://github.com/ROCm/ATOM/pull/2888) `[Qwen3.5] Tokenize prompts in worker processes (ATOM_TOKENIZE_PROCESSES), opt-in pre-engine timing` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2889](https://github.com/ROCm/ATOM/pull/2889) `[Qwen3.5] Fused QK-norm + MRoPE + KV write for an fp8 cache under unified attention` | perf,quant | alizaidy/gfx1250-qwen-support | - |
| - | [#2890](https://github.com/ROCm/ATOM/pull/2890) `[Recipe] Qwen3.5 MLPerf agentic: reproduction recipe, official-run trajectories, client knobs, LM head mode` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2893](https://github.com/ROCm/ATOM/pull/2893) `fix(moe): mask cudagraph pad rows under pure TP again` | bug,infra | main | - |
| - | [#2895](https://github.com/ROCm/ATOM/pull/2895) `fix(sglang): keep DSV4 MTP draft on the same SWA ring` | bug,infra | main | - |
| - | [#2897](https://github.com/ROCm/ATOM/pull/2897) `feat(dp): opt-in adaptive prefill admission (--prefill-admit-policy adaptive)` | infra | main | - |
| - | [#2898](https://github.com/ROCm/ATOM/pull/2898) `fix(engram): mlock in-place UVA page runs while registered (on by default, best effort)` | bug,infra | main | - |
| - | [#2902](https://github.com/ROCm/ATOM/pull/2902) `[Kimi-K3] Chunk image prefills: emit embedding_spans and cache_seed` | infra | main | - |
| - | [#2905](https://github.com/ROCm/ATOM/pull/2905) `fix(moe): restore TP MoE num_local_tokens` | bug,infra | main | - |
| - | [#2906](https://github.com/ROCm/ATOM/pull/2906) `[kv_transfer] lmcache_mp: lookup thread, transfer thread, same-step saves` | infra | main | - |
| - | [#2910](https://github.com/ROCm/ATOM/pull/2910) `[Kimi-K3] Return the reply as content when the model skips its think channel` | infra | main | - |
| - | [#2912](https://github.com/ROCm/ATOM/pull/2912) `perf(api-server): stop keeping finished sequences, keep prompt rendering and tokenizing off the event loop` | infra,perf | main | - |
| - | [#2913](https://github.com/ROCm/ATOM/pull/2913) `feat(api-server): --api-server-count N, front-end worker processes for the OpenAI server` | infra | main | - |
| - | [#2916](https://github.com/ROCm/ATOM/pull/2916) `[Sampler] Speculative verify at TP > 1: sample top-k from per-shard candidates (ATOM_TOPK_CANDIDATE_HEAD)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2917](https://github.com/ROCm/ATOM/pull/2917) `[Sampling] presence_penalty on decode and speculative-verify rows` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2918](https://github.com/ROCm/ATOM/pull/2918) `[Qwen3.5] MoE: opt-in 128-column expert padding (ATOM_QWEN_MOE_PAD_ALIGN_128)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2919](https://github.com/ROCm/ATOM/pull/2919) `[MoE] ATOM_MOE_TRITON_TOPK: aiter's Triton top-8 for plain renormalized routing` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2920](https://github.com/ROCm/ATOM/pull/2920) `[Observability] ATOM_REQ_TIMELINE: per-request TTFT marks and engine-step / rank-0 forward phase marks` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2921](https://github.com/ROCm/ATOM/pull/2921) `[Qwen3.5] Prefill tail option (ATOM_PREFILL_TAIL_SKIPS_HOLD_TOKENS) and an fp8-KV-tolerant recipe prefix check` | quant | alizaidy/gfx1250-qwen-support | - |
| - | [#2923](https://github.com/ROCm/ATOM/pull/2923) `[Attention] One-launch zeroing of released PAGE units and dead conv columns; prefill batch ids from cu_seqlens` | infra | alizaidy/gfx1250-qwen-support | - |
| - | [#2924](https://github.com/ROCm/ATOM/pull/2924) `[Qwen3.5] Decode small-kernel fusions: MoE tail in the combine, gated shared-expert GEMM, MTP drafter prologue` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2929](https://github.com/ROCm/ATOM/pull/2929) `[Sampler] Top-k / top-p sampling from the bf16 logits in two kernels (ATOM_FUSED_TOPK_TOPP_SAMPLE)` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2930](https://github.com/ROCm/ATOM/pull/2930) `[DP] Place new sticky sessions by attention load (ATOM_DP_PLACE_BY_CONTEXT)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2934](https://github.com/ROCm/ATOM/pull/2934) `[GDN] Exact mid-step state checkpoints, and checkpoint steps that stay in the prefill token graph` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#2935](https://github.com/ROCm/ATOM/pull/2935) `[Qwen3.5] gfx1250 chunk_h: pick BV from the longest walk and the total work` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2936](https://github.com/ROCm/ATOM/pull/2936) `fix(loader): resolve OpenMP symbol through torch` | bug,infra | main | - |
| - | [#2944](https://github.com/ROCm/ATOM/pull/2944) `[Fix][API] Kimi-K3: render history tool-call arguments verbatim, reject malformed tool requests with 400` | bug | main | - |
| - | [#2951](https://github.com/ROCm/ATOM/pull/2951) `fix(dsv41): add 5, 6, 7, 12 to the default decoder request graph sizes` | bug,infra | main | - |
| - | [#2954](https://github.com/ROCm/ATOM/pull/2954) `fix(ci): stub triton.language.extra in the DP gather CPU test` | bug,infra,rocm | main | - |
| - | [#2957](https://github.com/ROCm/ATOM/pull/2957) `fix(loader): keep loader threads at one OpenMP thread on torch 2.11` | bug | main | - |
| - | [#2969](https://github.com/ROCm/ATOM/pull/2969) `[Qwen3.5] Step glue: fused post-verify top-k and sampling (flags, default off)` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2986](https://github.com/ROCm/ATOM/pull/2986) `fix(ci): run DeepSeek-V3.2-FP8 DP/EP on SGLang with ATOM_FUSE_SHARED_EXPERT=0` | bug,infra,perf,quant | main | - |
| - | [#2987](https://github.com/ROCm/ATOM/pull/2987) `[ATOMesh][CI] Enable Kimi K3 WideEP DPA16/EP16 with MoRI EP and add MoRI cases into nightly runs` | infra | main | - |
| - | [#2992](https://github.com/ROCm/ATOM/pull/2992) `fix(attention): build MiniMax-M3 sparse decode metadata over the padded batch` | bug,infra | main | - |
| - | [#2993](https://github.com/ROCm/ATOM/pull/2993) `fix(qwen38): mono draft fallback without a RoPE cache; QSA RoPE at ATOM's MRoPE positions` | bug,infra,perf | main | - |
| - | [#3000](https://github.com/ROCm/ATOM/pull/3000) `[DP] Replicated experts under DP attention, independent DP ranks` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3001](https://github.com/ROCm/ATOM/pull/3001) `[TokenGraph] Full attention writes the next segment's buffer: no replay copy` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3002](https://github.com/ROCm/ATOM/pull/3002) `[Kimi-K3] Keep image alpha for processors that fill transparent backgrounds` | infra | main | - |
| - | [#3003](https://github.com/ROCm/ATOM/pull/3003) `kimik3.1 day0` | infra | main | - |
| - | [#3007](https://github.com/ROCm/ATOM/pull/3007) `[gfx1250][GDN] Persistent Gluon conv1d for prefill` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#3009](https://github.com/ROCm/ATOM/pull/3009) `[gfx1250][GDN] Fuse KKT + gating into the Gluon inverse/WY kernel` | perf,rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#3011](https://github.com/ROCm/ATOM/pull/3011) `[gfx1250][GDN] chunk_o: K32 q.h panels, V in the H tile, native exp` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#3013](https://github.com/ROCm/ATOM/pull/3013) `[gfx1250][GDN] chunk_h: last-gate lookup, per-size tiles, cleanup` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#3017](https://github.com/ROCm/ATOM/pull/3017) `Early prefill schedule: dispatch the next prefill while the decode runs (ATOM_EARLY_PREFILL_SCHEDULE)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3018](https://github.com/ROCm/ATOM/pull/3018) `[API] Prepare chat completions in the tokenize workers; cheaper SSE streaming (opt-in)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3019](https://github.com/ROCm/ATOM/pull/3019) `[Qwen3.5] mlperf_endpoints_qwen35: 128 GiB GDN state checkpoint budget, METRICS_ISL client knob` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3024](https://github.com/ROCm/ATOM/issues/3024) `--kv-cache-dtype (hyphenated) is documented but not registered; only --kv_cache_dtype parses` | perf | ? | - |
| - | [#3029](https://github.com/ROCm/ATOM/issues/3029) `vLLM plugin + ATOM offload: multimodal LMCache keys ignore the media, and two servers on one host share an eng` |  | ? | - |
| - | [#3034](https://github.com/ROCm/ATOM/pull/3034) `feat(minimax-m3): enable native 1x32 MXFP8 preshuffle GEMM` | infra,quant | main | - |
| - | [#3035](https://github.com/ROCm/ATOM/pull/3035) `Remove atom_overview_draft.md` |  | main | - |
| - | [#3036](https://github.com/ROCm/ATOM/pull/3036) `feat(api): add DeepSeek's beta FIM and assistant-prefix completion` | infra | main | - |
| - | [#3060](https://github.com/ROCm/ATOM/pull/3060) `fix(qwen3): tie the LM head to the embedding's Parameter` | bug | main | - |
| - | [#3072](https://github.com/ROCm/ATOM/pull/3072) `fix(config): key the compile cache on max_num_batched_tokens and kv_cache_dtype` | bug,infra,perf | main | - |

### ATOM — Open / submitted (152 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#2832](https://github.com/ROCm/ATOM/issues/2832) `[Perf Regression] 15 config(s) regressed @ 66796d40` | bug,perf | ? | - |
| - | [#2838](https://github.com/ROCm/ATOM/pull/2838) `[MiniMax M3.1] Add PP4-to-DCP4 Mooncake KV transfer and target/DSpark attention` |  | mengqing/m31-pp4-tp4-nvfp4-integration | - |
| - | [#2840](https://github.com/ROCm/ATOM/pull/2840) `feat(dsv41): add gfx1250 mono backend and separate architecture implementations` | rocm | main | - |
| - | [#2842](https://github.com/ROCm/ATOM/pull/2842) `fix(state checkpoints): keep block 0 a zero null page and zero released PAGE units` | bug,infra | main | - |
| - | [#2843](https://github.com/ROCm/ATOM/pull/2843) `fix(attention): keep MTP-5 decode on FlyDSL pa_decode past the gluon query-length limit` | bug,infra,rocm | main | - |
| - | [#2845](https://github.com/ROCm/ATOM/pull/2845) `perf(flydsl pa_decode): head-256 batch-1/2 plan ceiling and 48-row pipe for MTP-5 verify (opt-in)` | infra,perf,rocm | main | - |
| - | [#2846](https://github.com/ROCm/ATOM/pull/2846) `[PD] Unify KV staging/landing and add MiniMax PP-to-TP support` |  | mengqing/m31-pp4-tp4-nvfp4-integration | - |
| - | [#2847](https://github.com/ROCm/ATOM/pull/2847) `perf(qwen4_exp): Qwen3.8-Flash-Next TP prefill follow-ups: drafter FlyDSL QSA, row-sharded indexer selection, ` | perf,rocm | main | - |
| - | [#2848](https://github.com/ROCm/ATOM/pull/2848) `feat(eplb): add DeepInfer hot expert selection` |  | main | - |
| - | [#2850](https://github.com/ROCm/ATOM/pull/2850) `[MiniMax-M3.1] Windowed DSpark draft KV (4/4): keep the draft KV to its sliding window, behind ATOM_DSPARK_DRA` |  | Jasen/m31-draft-window-pd | - |
| - | [#2851](https://github.com/ROCm/ATOM/pull/2851) `perf(qwen3.5): compute the GDN gate inside the ReplaySSM kernel` | infra,perf | main | - |
| - | [#2852](https://github.com/ROCm/ATOM/pull/2852) `perf(qwen3.5): prefill all-reduce + norm via INT4 quick-reduce for 2k-8k-token steps` | infra,perf,quant | main | - |
| - | [#2853](https://github.com/ROCm/ATOM/pull/2853) `Qwen3.5 MTP: capture draft mid-steps (MRoPE opt-in) and reuse their staging buffers, on top of #2663` | infra | main | - |
| - | [#2854](https://github.com/ROCm/ATOM/pull/2854) `Qwen3.5 MTP: gather the fc output with aiter's custom all-gather instead of RCCL` | infra,rocm | main | - |
| - | [#2855](https://github.com/ROCm/ATOM/pull/2855) `perf(attn): unified attention for prefix-hit FP8 prefill + start-up warm-up` | infra,perf,quant | main | - |
| - | [#2858](https://github.com/ROCm/ATOM/pull/2858) `Fix standalone Inductor/Triton cache persistence across container restarts` | bug,perf,rocm | main | - |
| - | [#2860](https://github.com/ROCm/ATOM/pull/2860) `feat(v41): replay the decoder graph on over-band prefills (opt-in)` |  | main | - |
| - | [#2861](https://github.com/ROCm/ATOM/issues/2861) `Qwen3.8 PLE host table: share one page-locked copy across the DP ranks of a node` |  | ? | - |
| - | [#2863](https://github.com/ROCm/ATOM/issues/2863) `Move RapidServe's _CU_POOL_FRACTIONS from RapidServeModelRunner to atom/config.py` |  | ? | - |
| - | [#2864](https://github.com/ROCm/ATOM/issues/2864) `V4.1 compatibility: API completion, beta endpoints, and image support` |  | ? | - |
| - | [#2865](https://github.com/ROCm/ATOM/issues/2865) `Qwen3.5 image prompt: prefix-cache hit covering image tokens crashes merge_multimodal_embeddings (shape mismat` | bug,perf | ? | - |
| - | [#2866](https://github.com/ROCm/ATOM/issues/2866) `Qwen3-Next-80B-A3B-Instruct-FP8 (TP1, cudagraph): HIP illegal memory access after 193/200 GSM8K requests; --en` | bug,quant,risk,rocm | ? | - |
| - | [#2873](https://github.com/ROCm/ATOM/pull/2873) `[Perf] Use finer gfx1250 index-score chunks for small decode grids` | perf,rocm | main | - |
| - | [#2875](https://github.com/ROCm/ATOM/issues/2875) `[Perf Regression] 16 config(s) regressed @ 43eed2fd` | bug,perf | ? | - |
| - | [#2876](https://github.com/ROCm/ATOM/pull/2876) `[MiniMax-M3.1] Run the DSpark draft's MXFP8 linears on AITER's preshuffled GEMM` | quant,rocm | main | - |
| - | [#2877](https://github.com/ROCm/ATOM/pull/2877) `[DSV4.1][gfx1250] Fuse probabilistic Markov chain reductions` | perf,rocm | main | - |
| - | [#2879](https://github.com/ROCm/ATOM/issues/2879) `[Perf Regression] 49 config(s) regressed @ d246797d` | bug,perf | ? | - |
| - | [#2880](https://github.com/ROCm/ATOM/pull/2880) `[gfx1250] Triton MoE over MegaMoE: SwiGLU clamp default 0.0 and dispatch guards` | rocm | main | - |
| - | [#2881](https://github.com/ROCm/ATOM/pull/2881) `[gfx1250] GemmaRMSNorm: aiter Gluon fused_rmsnorm_add in place of the HIP kernel` | perf,rocm | main | - |
| - | [#2882](https://github.com/ROCm/ATOM/pull/2882) `[gfx1250] Add opt-in peer exchange for DP4 target logits` | bug,rocm | main | - |
| - | [#2886](https://github.com/ROCm/ATOM/pull/2886) `feat(minimax-m3): mono decode on gfx1250 (MI455X)` | rocm | main | - |
| - | [#2887](https://github.com/ROCm/ATOM/pull/2887) `optimize dsv4 flash opt` | perf | main | - |
| - | [#2892](https://github.com/ROCm/ATOM/issues/2892) `Qwen3.8-Flash-Next-Quark-MXFP4 with -dp 2 (TP1, MTP 3): ModelRunner dies in PLE compute_ngram_ids (ngram_conte` | quant,rocm | ? | - |
| - | [#2894](https://github.com/ROCm/ATOM/pull/2894) `feat(kimi-k3): add gfx1250 monokernel` | rocm | main | - |
| - | [#2896](https://github.com/ROCm/ATOM/pull/2896) `fix(rtpllm): upstream Qwen4Exp plugin integration contracts` | bug | main | - |
| - | [#2899](https://github.com/ROCm/ATOM/pull/2899) `[MLA] Opt-in FP8 prefill attention on gfx1250: ASM or FlyDSL` | quant,rocm | main | - |
| - | [#2900](https://github.com/ROCm/ATOM/pull/2900) `feat(moe): route FlyDSL MXFP4 decode through aiter HERD on gfx1250 (Kimi-K3 image branch)` | quant,rocm | k3-455-tp8-1029 | - |
| - | [#2901](https://github.com/ROCm/ATOM/pull/2901) `feat(docker): move the ROCm 10 line from 10.0.0 to 10.1.0 (HIP 7.16)` | infra,rocm | main | - |
| - | [#2903](https://github.com/ROCm/ATOM/pull/2903) `[DSV4.1][Perf] Fuse Q RoPE/quant, sparse attention and output cast through AITER` | perf,quant,rocm | main | - |
| - | [#2904](https://github.com/ROCm/ATOM/pull/2904) `feat(minimax-m3): record prefill as token graphs` |  | main | - |
| - | [#2908](https://github.com/ROCm/ATOM/pull/2908) `feat(dsv41): add gfx1250 mono backend, enabled by default for 1/2/8-request decode` | rocm | main | - |
| - | [#2909](https://github.com/ROCm/ATOM/pull/2909) `feat(dsv41): carry the mHC residual in Mega-MHC's res_preshuffle layout through decode` |  | main | - |
| - | [#2911](https://github.com/ROCm/ATOM/issues/2911) `[Issue]: ATOM_TORCH_PROFILER_DIR is ignored when the server is started without --torch-profiler-dir` |  | ? | - |
| - | [#2914](https://github.com/ROCm/ATOM/pull/2914) `perf(spec-decode): fuse the unfiltered per-row-noise draw into two launches (ATOM_SPEC_BONUS_FUSED)` | perf | main | - |
| - | [#2915](https://github.com/ROCm/ATOM/pull/2915) `perf(mla): ATOM_MLA_MIN_HEADS=12 skips the zero padding to 16 query heads in FP8 decode` | perf,quant | main | - |
| - | [#2922](https://github.com/ROCm/ATOM/pull/2922) `[ATOMesh] Add Kimi-K2.6-MXFP4 1P1D TP8 + 2P1D TP8 Mooncake disagg` | quant | main | - |
| - | [#2925](https://github.com/ROCm/ATOM/pull/2925) `fix(engine): honor ATOM_TORCH_PROFILER_DIR` | bug | main | - |
| - | [#2926](https://github.com/ROCm/ATOM/issues/2926) `[Issue]: Compile cache is shared by models that differ only in layer count or widths, so the second model load` | perf | ? | - |
| - | [#2927](https://github.com/ROCm/ATOM/pull/2927) `fix(config): key the compile cache on the HF model architecture` | bug,perf | main | - |
| - | [#2928](https://github.com/ROCm/ATOM/issues/2928) `[Issue]: Native sampler shares one exponential-noise row across all unfiltered stochastic rows of a batch (ord` |  | ? | - |
| - | [#2931](https://github.com/ROCm/ATOM/issues/2931) `[Perf Regression] 13 config(s) regressed @ 974414f1` | bug,perf | ? | - |
| - | [#2932](https://github.com/ROCm/ATOM/pull/2932) `fix(engram): serialize UVA registration across DP ranks and register in 1 GiB chunks` | bug | main | - |
| - | [#2933](https://github.com/ROCm/ATOM/pull/2933) `fix(dsv41): quantize the fused shared-expert activation for native MX w2` | bug,perf,quant | main | - |
| - | [#2938](https://github.com/ROCm/ATOM/pull/2938) `perf(kimi-k3): read a strided AttnRes block residual without copying it` | perf | main | - |
| - | [#2939](https://github.com/ROCm/ATOM/pull/2939) `[MoE] ATOM_MEGA_COMBINE_WIRE applies to decode steps too` |  | main | - |
| - | [#2940](https://github.com/ROCm/ATOM/pull/2940) `[mono] Merge the DCP decode partials in-kernel: Kimi-K3 in K2, GLM-5.2 in its layer kernel` | infra,perf | main | - |
| - | [#2941](https://github.com/ROCm/ATOM/pull/2941) `[WIP]feat(pd): bound decode admission by pending receive KV bytes and free decode KV` |  | mengqing/m31-mxfp4-feature-stack | - |
| - | [#2942](https://github.com/ROCm/ATOM/pull/2942) `feat(kimi-k3): record prefill as token graphs` |  | main | - |
| - | [#2943](https://github.com/ROCm/ATOM/pull/2943) `feat: unify token constraints and support min_tokens` |  | main | - |
| - | [#2945](https://github.com/ROCm/ATOM/pull/2945) `feat(k3-mono): run on an fp16 KDA recurrent state pool` |  | main | - |
| - | [#2947](https://github.com/ROCm/ATOM/pull/2947) `Qsa index scorer/stage2` |  | main | - |
| - | [#2949](https://github.com/ROCm/ATOM/pull/2949) `perf(minimax-m3): consume sparse PA prequant output` | perf,quant | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#2950](https://github.com/ROCm/ATOM/issues/2950) `[Perf Regression] 15 config(s) regressed @ 974414f1` | bug,perf | ? | - |
| - | [#2952](https://github.com/ROCm/ATOM/pull/2952) `[WIP] perf(minimax-m3): integrate MI455 fusion stack` | perf | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#2953](https://github.com/ROCm/ATOM/pull/2953) `perf(kimi-k3): one-launch q/k norm + rope + paged K/V write for the DFlash draft (ATOM_K3_DRAFT_QKROPE)` | perf | main | - |
| - | [#2955](https://github.com/ROCm/ATOM/issues/2955) `[Perf Regression] 3 config(s) regressed @ ce260d2e` | bug,perf | ? | - |
| - | [#2958](https://github.com/ROCm/ATOM/pull/2958) `Enable DSpark adaptive ragged verification` |  | main | - |
| - | [#2959](https://github.com/ROCm/ATOM/pull/2959) `[Kimi-K3] Midstep KDA state checkpoints from the FlashKDA recurrence` |  | main | - |
| - | [#2960](https://github.com/ROCm/ATOM/pull/2960) `[Kimi-K3] Prefill token graphs: the KDA/MLA backend takes a padded prefill` |  | main | - |
| - | [#2961](https://github.com/ROCm/ATOM/pull/2961) `perf(mla): opt-in opus flat-row decode for DCP8/DCP1 MTP (ATOM_OPUS_MLA)` | perf | main | - |
| - | [#2962](https://github.com/ROCm/ATOM/pull/2962) `[MiniMax-M3.1] MXFP4 index cache; reject M3 --kv-cache-dtype fp4` | infra,perf,quant | main | - |
| - | [#2963](https://github.com/ROCm/ATOM/pull/2963) `[GDN] Write the linear-attention output into the graph buffer (no replay copy)` |  | main | - |
| - | [#2966](https://github.com/ROCm/ATOM/pull/2966) `[DO NOT MERGE] [Qwen3.5][GDN] Gates inside the KKT kernel (ATOM_GDN_KKT_GATING)` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2967](https://github.com/ROCm/ATOM/pull/2967) `[DO NOT MERGE] [Qwen3.5][GDN] Gluon inverse/WY kernel for gfx1250 (ATOM_GDN_GLUON_INVERSE)` | perf,rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2968](https://github.com/ROCm/ATOM/pull/2968) `[DO NOT MERGE] [Qwen3.5][GDN] chunk_h paired TDM loads + chunk_o in-wave gated norm (gfx1250)` | rocm | alizaidy/gfx1250-qwen-support | - |
| - | [#2970](https://github.com/ROCm/ATOM/pull/2970) `[Qwen3.5] Fused TP4 decode MoE half in one persistent kernel (draft, flag off)` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#2971](https://github.com/ROCm/ATOM/pull/2971) `perf(minimax-m3): fill underoccupied gfx1250 prefill index grids` | perf,rocm | main | - |
| - | [#2973](https://github.com/ROCm/ATOM/pull/2973) `[GFX1250][K3][LMCache] Enable LMCache MP for K3 TP8DCP8 on GFX1250` | rocm | main | - |
| - | [#2974](https://github.com/ROCm/ATOM/issues/2974) `Reasoning markers inside a tool-call argument are read as channel markers` |  | ? | - |
| - | [#2975](https://github.com/ROCm/ATOM/pull/2975) `perf(dspark): one-launch draft KV addressing (context slots and the unsharded block metadata)` | perf | main | - |
| - | [#2976](https://github.com/ROCm/ATOM/pull/2976) `perf(kimi-k3): no k copy before the DFlash draft's context k-norm` | perf | main | - |
| - | [#2979](https://github.com/ROCm/ATOM/pull/2979) `perf(minimax-m3): tune long-context decode topk tiles` | perf | main | - |
| - | [#2980](https://github.com/ROCm/ATOM/pull/2980) `feat(k3-mono): read FP8 dense projections in place` | quant | main | - |
| - | [#2981](https://github.com/ROCm/ATOM/pull/2981) `Codex/deepinfer dp scheduler` |  | main | - |
| - | [#2982](https://github.com/ROCm/ATOM/pull/2982) `perf(minimax-m3): raise decode score memory throughput` | perf | main | - |
| - | [#2983](https://github.com/ROCm/ATOM/issues/2983) `Qwen3.8 Mono: PLE host table (`MonoPleEmbedding`) has no release_weight_memory / sync_weight hooks` | infra | ? | - |
| - | [#2985](https://github.com/ROCm/ATOM/pull/2985) `fix(ci): one local-model completeness check for SGLang/vLLM accuracy; new prefill CP flags; wait for SGLang wa` | bug,infra,risk | main | - |
| - | [#2988](https://github.com/ROCm/ATOM/pull/2988) `perf(minimax-m3): reduce split-K QKV and gate/up partials in their consumers` | perf | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#2989](https://github.com/ROCm/ATOM/pull/2989) `[DSV4.1] Use contiguous KV sources and add OPUS/ASM A8W4 attention` |  | main | - |
| - | [#2990](https://github.com/ROCm/ATOM/pull/2990) `[Kimi-K3] Video inputs with chunked prefill and bounded vision passes` |  | main | - |
| - | [#2991](https://github.com/ROCm/ATOM/issues/2991) `[Perf Regression] 1 config(s) regressed @ 16ebac2e` | bug,perf | ? | - |
| - | [#2994](https://github.com/ROCm/ATOM/pull/2994) `feat(kimi-k3): fuse o_proj's E8M0 activation quant into the MLA out gate` | perf,quant | main | - |
| - | [#2995](https://github.com/ROCm/ATOM/pull/2995) `feat(kimi-k3): fuse down_proj's E8M0 activation quant into SiTUv2` | perf,quant | qichu/k3-e8m0-fused-quant | - |
| - | [#2996](https://github.com/ROCm/ATOM/pull/2996) `perf(kimi-k3): quantize the shared qkv_a / g_proj input once` | perf,quant | main | - |
| - | [#2997](https://github.com/ROCm/ATOM/pull/2997) `feat(mesh): defer ATOM Decode placement until Prefill handoff` |  | main | - |
| - | [#2998](https://github.com/ROCm/ATOM/pull/2998) `[DSV4.1] Bucket decoder tails by DP final-prefill request count` |  | main | - |
| - | [#3006](https://github.com/ROCm/ATOM/pull/3006) `perf(kimi-k3): mono MLA post / prep folds into K2 (ATOM_MONO_MLA_POST, ATOM_MONO_MLA_PREP)` | perf | main | - |
| - | [#3008](https://github.com/ROCm/ATOM/pull/3008) `[DO NOT MERGE] [gfx1250][GDN] Persistent Gluon conv1d for prefill` | rocm | main | - |
| - | [#3010](https://github.com/ROCm/ATOM/pull/3010) `[DO NOT MERGE] [gfx1250][GDN] Fuse KKT + gating into the Gluon inverse/WY kernel` | perf,rocm | main | - |
| - | [#3012](https://github.com/ROCm/ATOM/pull/3012) `[DO NOT MERGE] [gfx1250][GDN] chunk_o: K32 q.h panels, V in the H tile, native exp` | rocm | main | - |
| - | [#3014](https://github.com/ROCm/ATOM/pull/3014) `[DO NOT MERGE] [gfx1250][GDN] chunk_h: last-gate lookup, per-size tiles, cleanup` | rocm | main | - |
| - | [#3015](https://github.com/ROCm/ATOM/pull/3015) `fix(dflash): keep the per-tensor unit scale out of the draft's KVCacheTensor` | bug,quant | main | - |
| - | [#3016](https://github.com/ROCm/ATOM/pull/3016) `[Qwen3.5 MTP] TP4 drafter small-kernel fusions + the drafter MoE in the fused MoE-half kernel (stacked on #297` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#3020](https://github.com/ROCm/ATOM/pull/3020) `perf(dsv41): fold the shared-expert add into the MoE TP all-reduce` | perf | main | - |
| - | [#3021](https://github.com/ROCm/ATOM/pull/3021) `perf(dsv41): take the fused shared-expert act + quant at TP4 and TP8` | perf,quant | main | - |
| - | [#3022](https://github.com/ROCm/ATOM/pull/3022) `perf(dsv41): quantize the shared expert's input in the FFN mHC seam` | perf,quant | main | - |
| - | [#3023](https://github.com/ROCm/ATOM/pull/3023) `[fix] Kimi-K3.1 DSpark under PP: share the target's embedding on the last stage` | bug | main | - |
| - | [#3025](https://github.com/ROCm/ATOM/issues/3025) `Qwen3.8: make the QSA field declaration kernel-free so the builder's offload tests run on CPU CI` | infra,perf | ? | - |
| - | [#3026](https://github.com/ROCm/ATOM/pull/3026) `[ATOMesh][DI][CI] Add DeepSeek-V4-Pro wide-EP MoRIIO write gsm8k` | infra,rocm | main | - |
| - | [#3027](https://github.com/ROCm/ATOM/pull/3027) `fix(offload): key multimodal prompts by media, one LMCache engine id per server, MP anchors on the chunk grid,` | bug | main | - |
| - | [#3028](https://github.com/ROCm/ATOM/issues/3028) `Plugin mode: atom_config.load_dummy is always None, so a framework's dummy load is invisible to ATOM` |  | ? | - |
| - | [#3031](https://github.com/ROCm/ATOM/pull/3031) `[Kimi-K3] docs(recipes): Kimi-K3.1 AgentX recipe on MI355X` | rocm | main | - |
| - | [#3032](https://github.com/ROCm/ATOM/issues/3032) `mono: `resident_grid_refusals` compares the raw `kv_connector` spelling, so connector aliases and `multi` sile` | risk | ? | - |
| - | [#3033](https://github.com/ROCm/ATOM/pull/3033) `vllm-atom: serve GLM-5.3-Flash on the plugin backend and gate it in plugin PR CI` | infra | main | - |
| - | [#3037](https://github.com/ROCm/ATOM/issues/3037) `[Perf Regression] 13 config(s) regressed @ 083891e9` | bug,perf | ? | - |
| - | [#3038](https://github.com/ROCm/ATOM/pull/3038) `[MiniMax-M3.1] P/D from a PP4 prefill into a TP4 decode (2/2: DSpark)` |  | Jasen/m31-pd-pp4-tp4 | - |
| - | [#3040](https://github.com/ROCm/ATOM/pull/3040) `fix(dspark): allocate the draft block's last KV row (lookahead mtp_k, not mtp_k - 1)` | bug | main | - |
| - | [#3041](https://github.com/ROCm/ATOM/pull/3041) `[Bugfix][Qwen3.5] Give image prompts embedding spans so prefix hits past an image don't crash` | bug | main | - |
| - | [#3042](https://github.com/ROCm/ATOM/pull/3042) `[Mono] Extend FP8/FP4 DSA indexers and qlen-6 verification` | quant | main | - |
| - | [#3043](https://github.com/ROCm/ATOM/pull/3043) `fix(indexer): keep the FP8 prefill indexer's logits and keys in persistent workspaces` | bug,quant | main | - |
| - | [#3044](https://github.com/ROCm/ATOM/pull/3044) `[Qwen3.5 recipe] e8m0 FP8 projections on by default for DP points` | quant | alizaidy/gfx1250-qwen-support | - |
| - | [#3045](https://github.com/ROCm/ATOM/pull/3045) `[Qwen3.5 DP] MoE-block and attention-reduce fusions for decode and prefill (stacked on #3016)` | perf | alizaidy/gfx1250-qwen-support | - |
| - | [#3046](https://github.com/ROCm/ATOM/pull/3046) `[API] Offloaded chat preparation reuses a session's earlier turns (ATOM_API_OFFLOAD_TOKENIZE_CACHE_MB)` |  | alizaidy/gfx1250-qwen-support | - |
| - | [#3047](https://github.com/ROCm/ATOM/issues/3047) `[Perf Regression] 23 config(s) regressed @ 64412f10` | bug,perf | ? | - |
| - | [#3048](https://github.com/ROCm/ATOM/pull/3048) `[DCP] Add a `mailbox` decode merge backend on aiter's FlyDSL `dcp_lse_combine`` | rocm | main | - |
| - | [#3049](https://github.com/ROCm/ATOM/pull/3049) `perf(minimax-m3): quantize the dense MLP activation in the SwiGLU kernel` | perf,quant | xiaobingsuper/m3-mi455-perf-stack | - |
| - | [#3050](https://github.com/ROCm/ATOM/pull/3050) `[MiniMax-M3.1] Sparse decode: attend only the rows its tables describe` | infra | main | - |
| - | [#3051](https://github.com/ROCm/ATOM/issues/3051) `[Kimi-K3.1][DCP8] Long decodes collapse into repeated token 0 (`!!!!`) and later lose the prompt under TP8 + D` |  | ? | - |
| - | [#3052](https://github.com/ROCm/ATOM/pull/3052) `fix(attention): accept optional explicit FlyDSL plans` | bug,rocm | main | - |
| - | [#3053](https://github.com/ROCm/ATOM/pull/3053) `feat(kimi-k3): fuse o_proj's E8M0 activation quant into the KDA gated norm` | perf,quant | qichu/k3-e8m0-fused-quant | - |
| - | [#3054](https://github.com/ROCm/ATOM/pull/3054) `feat(kimi-k3): fold the consumer's E8M0 activation quant into the attention residual` | quant | qichu/k3-e8m0-fused-quant | - |
| - | [#3055](https://github.com/ROCm/ATOM/pull/3055) `fix(indexer): score a step's FP8 prefill requests in groups that fit the key workspace` | bug,quant | Jasen/indexer-prefill-workspace | - |
| - | [#3057](https://github.com/ROCm/ATOM/pull/3057) `[V4] Reset the cache CUDA graph capture wrote before admitting requests` | infra,nvidia,perf | main | - |
| - | [#3058](https://github.com/ROCm/ATOM/pull/3058) `[Lumen-RL] Receive trained weights over RCCL as a weight sync` | rocm | main | - |
| - | [#3059](https://github.com/ROCm/ATOM/pull/3059) `[Lumen-RL] Pause and resume generation; preempt before the KV pool or the weights change` | bug | main | - |
| - | [#3061](https://github.com/ROCm/ATOM/pull/3061) `feat(api): hold Kimi-K3 tool calls to their schemas with the structured-output grammar` |  | main | - |
| - | [#3062](https://github.com/ROCm/ATOM/pull/3062) `fix(ci): read the SGLang benchmark matrix from a file in the summary job` | bug,infra,perf | main | - |
| - | [#3063](https://github.com/ROCm/ATOM/pull/3063) `fix(kimi-k3): offload the DSA index keys with the MLA rows` | bug | main | - |
| - | [#3064](https://github.com/ROCm/ATOM/pull/3064) `[MiniMax-M3.1] Windowed DSpark draft KV (1/4): the scheduler's window pool` |  | main | - |
| - | [#3065](https://github.com/ROCm/ATOM/pull/3065) `[MiniMax-M3.1] Windowed DSpark draft KV (2/4): the block pass reads and writes through a windowed table` |  | Jasen/m31-draft-window-pool | - |
| - | [#3066](https://github.com/ROCm/ATOM/pull/3066) `[MiniMax-M3.1] Windowed DSpark draft KV (3/4): send only the consumer's window over Mooncake P/D` |  | Jasen/m31-draft-window-block-pass | - |
| - | [#3068](https://github.com/ROCm/ATOM/pull/3068) `feat(kimi-k3): PP8 P/D prefill 2/4 — LMCache state tier under PP` | infra | zwan/k3-pp | - |
| - | [#3069](https://github.com/ROCm/ATOM/pull/3069) `feat(kimi-k3): PP8 P/D prefill 3/4 — KV and KDA state from a PP prefill to a DCP × TP decode` | infra | zwan/k3-pp-state-tier | - |
| - | [#3070](https://github.com/ROCm/ATOM/pull/3070) `perf(kimi-k3): PP8 P/D prefill 4/4 — MLA staging for a DCP consumer, more PP batches in flight` | infra,perf | zwan/k3-pp-dcp | - |
| - | [#3071](https://github.com/ROCm/ATOM/pull/3071) `ci: remove Atomesh TW weekly schedule` | infra | main | - |
| - | [#3073](https://github.com/ROCm/ATOM/pull/3073) `fix(compile): format Inductor's implicit-fallback log text only when emitted` | bug,infra | main | - |
| - | [#3074](https://github.com/ROCm/ATOM/pull/3074) `perf(dsv41): serve the MoE all-reduce add with aiter's Lamport one-shot kernel (stacked on #3020)` | perf,rocm | main | - |
| - | [#3075](https://github.com/ROCm/ATOM/pull/3075) `fix(moe): drop the missing-route clear from comm-fused MoE` | bug,infra,perf | main | - |
| - | [#3076](https://github.com/ROCm/ATOM/pull/3076) `fix(moe): exclude idle DP dummy tokens from expert routing` | bug | main | - |
| - | [#3077](https://github.com/ROCm/ATOM/pull/3077) `feat(benchmarks): record AITER_AR_1STAGE_MAX_BYTES in benchmark metadata` | perf,rocm | main | - |
| - | [#3078](https://github.com/ROCm/ATOM/issues/3078) `[Issue]: Scheduled regression reruns skip labelled benchmark variants and can suppress the [Perf Regression] i` | bug,perf | ? | - |
| - | [#3079](https://github.com/ROCm/ATOM/pull/3079) `fix(ci): resolve labelled benchmark variants in the regression rerun matrix` | bug,infra,perf | main | - |

### tokenspeed — Merged / closed (192 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#1373](https://github.com/lightseekorg/tokenspeed/issues/1373) `nccl weight transfer reports success without transferring: /update_weights returns 200 and loads uninitialised` | nvidia | ? | - |
| - | [#2335](https://github.com/lightseekorg/tokenspeed/pull/2335) `feat(comm): enable gfx1250 Iris across hosts in one fabric domain` | rocm | main | - |
| - | [#2351](https://github.com/lightseekorg/tokenspeed/pull/2351) `fix(l2): bound the Host memory share by the cgroup limit` | bug | main | - |
| - | [#2372](https://github.com/lightseekorg/tokenspeed/issues/2372) `RFC: Unified benchmark profiling with MFU, Estimated MBU, and annotated timelines` | perf | ? | - |
| - | [#2392](https://github.com/lightseekorg/tokenspeed/pull/2392) `fix(config): keep an EOS token id of 0 in ModelConfig.hf_eos_token_id` | bug | main | - |
| - | [#2470](https://github.com/lightseekorg/tokenspeed/pull/2470) `perf(beam): run Beam's fused kernels and BF16x3 router on SM90` | nvidia,perf | main | - |
| - | [#2516](https://github.com/lightseekorg/tokenspeed/pull/2516) `perf(moe): pick SM90 tiles for the Triton BF16 MoE by routes per expert` | nvidia,perf,rocm | main | - |
| - | [#2517](https://github.com/lightseekorg/tokenspeed/issues/2517) `min_new_tokens is accepted by SamplingParams.verify() but never enforced` |  | ? | - |
| - | [#2581](https://github.com/lightseekorg/tokenspeed/pull/2581) `feat(beam): serve the FP8 checkpoint on SM90` | nvidia,quant | main | - |
| - | [#2583](https://github.com/lightseekorg/tokenspeed/pull/2583) `feat(gdn): optimize CuTe WY verification and unify kernel dispatch` | perf | main | - |
| - | [#2650](https://github.com/lightseekorg/tokenspeed/issues/2650) `[Bug] Ascend NPU: default sampling backend needs a package the repo never ships or documents` |  | ? | - |
| - | [#2676](https://github.com/lightseekorg/tokenspeed/pull/2676) `feat(scheduler): drop State checkpoints a re-rendered next turn cannot resume at` |  | main | - |
| - | [#2686](https://github.com/lightseekorg/tokenspeed/pull/2686) `feat(dsv41): support model-wide QCP and KVP/DCP for PD serving` |  | main | - |
| - | [#2712](https://github.com/lightseekorg/tokenspeed/pull/2712) `perf(moe): fuse SM90 gated FC1 and prefetch FC2 weights` | nvidia,perf | main | - |
| - | [#2723](https://github.com/lightseekorg/tokenspeed/pull/2723) `perf(amd): pipeline gfx950 mha decode and extend kv page loads` | perf,rocm | main | - |
| - | [#2726](https://github.com/lightseekorg/tokenspeed/pull/2726) `fix(cache): share Qwen4-Exp PLE state planes under FP8 KV` | bug,perf,quant | main | - |
| - | [#2730](https://github.com/lightseekorg/tokenspeed/pull/2730) `feat: Support Autotune for cutedsl blockwise fp8 dense GEMM` | perf,quant | main | - |
| - | [#2731](https://github.com/lightseekorg/tokenspeed/pull/2731) `feat: add aligned state checkpoints and pluggable numerics envelopes` |  | main | - |
| - | [#2735](https://github.com/lightseekorg/tokenspeed/pull/2735) `perf(conv): integrate CuTe DSL K3 prefill tactics` | perf | main | - |
| - | [#2753](https://github.com/lightseekorg/tokenspeed/pull/2753) `fix(kernel): write strided output rows in the Triton rmsnorm` | bug,perf,rocm | main | - |
| - | [#2755](https://github.com/lightseekorg/tokenspeed/pull/2755) `feat(amd): tree attention cascade in the mha backend` | rocm | main | - |
| - | [#2764](https://github.com/lightseekorg/tokenspeed/pull/2764) `perf(moe): optimize small-token MegaMoE on SM100 and SM103` | nvidia,perf | main | - |
| - | [#2767](https://github.com/lightseekorg/tokenspeed/pull/2767) `feat(kernel): Gluon EAGLE-4 candidate shard top-k and tail for gfx950` | perf,rocm | main | - |
| - | [#2769](https://github.com/lightseekorg/tokenspeed/pull/2769) `perf(dsv41): avoid redundant MXFP4 MegaMoE padding` | perf,quant | main | - |
| - | [#2774](https://github.com/lightseekorg/tokenspeed/pull/2774) `fix(glm53): honor checkpoint MTP index sharing` | bug | main | - |
| - | [#2775](https://github.com/lightseekorg/tokenspeed/pull/2775) `perf(amd): reduce packed FP8 MoE alignment overhead` | perf,quant,rocm | main | - |
| - | [#2779](https://github.com/lightseekorg/tokenspeed/pull/2779) `perf(sampling): reduce top-k work for greedy rows` | perf | main | - |
| - | [#2788](https://github.com/lightseekorg/tokenspeed/pull/2788) `perf: warm Triton variants for changing request shapes` | bug,perf,rocm | main | - |
| - | [#2793](https://github.com/lightseekorg/tokenspeed/pull/2793) `fix(cuda): support CUDA 12.8 routing reduction` | bug,nvidia | main | - |
| - | [#2801](https://github.com/lightseekorg/tokenspeed/pull/2801) `feat(scheduler): bound the Prefill batch KV pages and share the works…` |  | main | - |
| - | [#2802](https://github.com/lightseekorg/tokenspeed/pull/2802) `feat(sampling): expose cumulative probability diagnostics for calibration` |  | main | - |
| - | [#2803](https://github.com/lightseekorg/tokenspeed/pull/2803) `fix(cache): avoid rounding large pinned host allocations` | bug,infra,perf | main | - |
| - | [#2805](https://github.com/lightseekorg/tokenspeed/pull/2805) `perf(cache): bound single-group Host history eviction scans` | perf | main | - |
| - | [#2808](https://github.com/lightseekorg/tokenspeed/pull/2808) `fix(scheduler): report KV events at the completed prefix boundary` | bug | main | - |
| - | [#2813](https://github.com/lightseekorg/tokenspeed/pull/2813) `fix(kernel): defer missing CUDA package errors until use` | bug,nvidia,perf | main | - |
| - | [#2814](https://github.com/lightseekorg/tokenspeed/pull/2814) `fix(autotune): expand GEMM buckets to the configured token budget` | bug,perf | main | - |
| - | [#2815](https://github.com/lightseekorg/tokenspeed/pull/2815) `perf(k3): split keys and use 64-deep WMMA in gfx1250 MLA prefill` | perf,rocm | main | - |
| - | [#2816](https://github.com/lightseekorg/tokenspeed/pull/2816) `perf(glm53): speed up gfx1250 MoE down projection and DSA decode` | perf,rocm | main | - |
| - | [#2817](https://github.com/lightseekorg/tokenspeed/pull/2817) `perf(dsv41): speed up gfx1250 decode sparse attention and Q/KV projection` | perf,rocm | main | - |
| - | [#2820](https://github.com/lightseekorg/tokenspeed/pull/2820) `fix(cache): improve shared L2 write-back eviction and placement` | bug,perf | main | - |
| - | [#2821](https://github.com/lightseekorg/tokenspeed/pull/2821) `perf(qsa): optimize CuTe streaming top-k for long prefill` | perf | main | - |
| - | [#2823](https://github.com/lightseekorg/tokenspeed/pull/2823) `test(cache): warm both write-back rows before stream checks` | perf | main | - |
| - | [#2824](https://github.com/lightseekorg/tokenspeed/pull/2824) `perf(gemm): remove logic of pre-compile` | perf | main | - |
| - | [#2825](https://github.com/lightseekorg/tokenspeed/pull/2825) `feat(moe): support Qwen3.5 NVFP4 MegaMoE` | quant | main | - |
| - | [#2827](https://github.com/lightseekorg/tokenspeed/pull/2827) `build: release tokenspeed-scheduler 0.1.46` | infra,perf | main | - |
| - | [#2828](https://github.com/lightseekorg/tokenspeed/pull/2828) `build: require tokenspeed-scheduler 0.1.46` | infra,perf | main | - |
| - | [#2829](https://github.com/lightseekorg/tokenspeed/pull/2829) `fix(qsa): guard padded MTP lengths and draft RoPE reads` | bug | main | - |
| - | [#2830](https://github.com/lightseekorg/tokenspeed/pull/2830) `refactor(cache): let each cache recipe declare its prefix granularity` | perf | main | - |
| - | [#2831](https://github.com/lightseekorg/tokenspeed/pull/2831) `perf(qsa): avoid duplicate FP8 KV gathers on Rubin` | perf,quant | main | - |
| - | [#2832](https://github.com/lightseekorg/tokenspeed/pull/2832) `feat(runtime): support weight discard with complete live updates` |  | main | - |
| - | [#2833](https://github.com/lightseekorg/tokenspeed/pull/2833) `fix(scheduler): do not wait on a capacity victim the round just scheduled` | bug | main | - |
| - | [#2834](https://github.com/lightseekorg/tokenspeed/pull/2834) `refactor(ascend): switch DSA CP prefill transport to native flash_ops adapters` |  | main | - |
| - | [#2835](https://github.com/lightseekorg/tokenspeed/pull/2835) `refactor: remove DeepSeek V4 support` |  | main | - |
| - | [#2836](https://github.com/lightseekorg/tokenspeed/pull/2836) `build: inline the Hopper/cu129 pip constraints into the installer` | infra,nvidia | main | - |
| - | [#2837](https://github.com/lightseekorg/tokenspeed/pull/2837) `refactor(runtime): remove modules and helpers left without callers` |  | main | - |
| - | [#2838](https://github.com/lightseekorg/tokenspeed/pull/2838) `fix(cudagraph): carry the default decode ladder up to --max-cudagraph-capture-size` | bug | main | - |
| - | [#2839](https://github.com/lightseekorg/tokenspeed/pull/2839) `fix(network): never advertise a loopback hostname address` | bug | main | - |
| - | [#2840](https://github.com/lightseekorg/tokenspeed/pull/2840) `fix(spec): refuse EAGLE3/DFLASH on targets that return no aux taps` | bug,perf | main | - |
| - | [#2841](https://github.com/lightseekorg/tokenspeed/pull/2841) `test(amd): check MegaMoE token-count recompiles with one config` | rocm | main | - |
| - | [#2842](https://github.com/lightseekorg/tokenspeed/pull/2842) `refactor(models): derive absorbed MLA weights through one helper` |  | main | - |
| - | [#2843](https://github.com/lightseekorg/tokenspeed/pull/2843) `cleanup(models): remove dead code from the model definitions` |  | main | - |
| - | [#2844](https://github.com/lightseekorg/tokenspeed/pull/2844) `feat(runtime): agree weight-load prerequisites on every rank before loading` |  | main | - |
| - | [#2845](https://github.com/lightseekorg/tokenspeed/pull/2845) `fix(sampling): validate sampling backend availability during ServerArgs initialization` | bug | main | - |
| - | [#2846](https://github.com/lightseekorg/tokenspeed/pull/2846) `perf(amd): loop the DSv4.1 top-k select rank sort at runtime` | perf,rocm | main | - |
| - | [#2847](https://github.com/lightseekorg/tokenspeed/pull/2847) `test(engine): wait out serving races in the weight-load tests` |  | main | - |
| - | [#2848](https://github.com/lightseekorg/tokenspeed/pull/2848) `fix(cache): preserve reusable prefixes through write-back eviction` | bug,perf | main | - |
| - | [#2849](https://github.com/lightseekorg/tokenspeed/pull/2849) `ci: move nvidia/thirdparty kernel tests from part-i to part-ii` | infra,nvidia,perf | main | - |
| - | [#2850](https://github.com/lightseekorg/tokenspeed/pull/2850) `fix(scheduler): pass the epoch bound at the Host allocation's eviction scan` | bug | main | - |
| - | [#2851](https://github.com/lightseekorg/tokenspeed/pull/2851) `perf(cache): warm restore transfers and reduce repeated planning work` | perf | main | - |
| - | [#2852](https://github.com/lightseekorg/tokenspeed/pull/2852) `perf(dsv41): reduce Triton specialization and warmup gaps` | perf,rocm | main | - |
| - | [#2853](https://github.com/lightseekorg/tokenspeed/pull/2853) `fix(moe): allocate the static all-to-all dispatch map with the placement` | bug | main | - |
| - | [#2854](https://github.com/lightseekorg/tokenspeed/pull/2854) `build: release tokenspeed-scheduler 0.1.47` | infra,perf | main | - |
| - | [#2855](https://github.com/lightseekorg/tokenspeed/pull/2855) `build: require tokenspeed-scheduler 0.1.47` | infra,perf | main | - |
| - | [#2856](https://github.com/lightseekorg/tokenspeed/pull/2856) `feat(kernel): report CuTe DSL compilations and direct @cute.jit calls while serving` | perf | main | - |
| - | [#2858](https://github.com/lightseekorg/tokenspeed/pull/2858) `perf(dsv41): retile gfx1250 indexer scoring and mHC projection` | perf,rocm | main | - |
| - | [#2859](https://github.com/lightseekorg/tokenspeed/pull/2859) `perf(epd): freeze the startup heap and align full GCs on encode ranks` | perf | main | - |
| - | [#2860](https://github.com/lightseekorg/tokenspeed/pull/2860) `ci: always arm the data-plane sync check and serve CI with it raising` | infra | main | - |
| - | [#2862](https://github.com/lightseekorg/tokenspeed/pull/2862) `refactor(cache): read the GDN SSM state dtype from server args` | perf | main | - |
| - | [#2863](https://github.com/lightseekorg/tokenspeed/pull/2863) `test(kernel-amd): cover missing gfx1250 kernels in MI450 simulation` | perf,rocm | main | - |
| - | [#2864](https://github.com/lightseekorg/tokenspeed/pull/2864) `test(kernel): drop QSA test points that repeat a compiled specialization` | perf | main | - |
| - | [#2865](https://github.com/lightseekorg/tokenspeed/pull/2865) `test(kernel): drop hyperconnection test points that rebuild the same plans` | perf | main | - |
| - | [#2866](https://github.com/lightseekorg/tokenspeed/pull/2866) `fix(cli): bracket IPv6 hosts in startup and metrics URLs` | bug | main | - |
| - | [#2867](https://github.com/lightseekorg/tokenspeed/pull/2867) `refactor(runtime): declare state instead of probing it with getattr` |  | main | - |
| - | [#2868](https://github.com/lightseekorg/tokenspeed/pull/2868) `fix(amd): keep ROCr's InterceptQueue out of serving processes` | bug,rocm | main | - |
| - | [#2869](https://github.com/lightseekorg/tokenspeed/pull/2869) `fix(cli): preserve multiple values for gateway options` | bug | main | - |
| - | [#2870](https://github.com/lightseekorg/tokenspeed/pull/2870) `chore(deps): update tokenspeed-iris to 0.0.0.post20261031` | perf | main | - |
| - | [#2871](https://github.com/lightseekorg/tokenspeed/pull/2871) `perf(kvp): gather MLA prefix history with a fused all-gather on GB300` | nvidia,perf | main | - |
| - | [#2872](https://github.com/lightseekorg/tokenspeed/pull/2872) `perf(cache): warm restore transfers and reduce repeated planning work` | perf | codex/fix-host-eviction-epoch-limit | - |
| - | [#2873](https://github.com/lightseekorg/tokenspeed/pull/2873) `style: fix sampling registry release checks` | bug,infra | main | - |
| - | [#2875](https://github.com/lightseekorg/tokenspeed/pull/2875) `fix(sampling): reject a negative temperature instead of coercing it to greedy` | bug | main | - |
| - | [#2877](https://github.com/lightseekorg/tokenspeed/pull/2877) `test(kernel): run the non-FP8 GEMM autotune capacity cases post-submit` | perf,quant | main | - |
| - | [#2879](https://github.com/lightseekorg/tokenspeed/pull/2879) `build: release tokenspeed-scheduler 0.1.48` | infra,perf | main | - |
| - | [#2880](https://github.com/lightseekorg/tokenspeed/pull/2880) `build: require tokenspeed-scheduler 0.1.48` | infra,perf | main | - |
| - | [#2881](https://github.com/lightseekorg/tokenspeed/pull/2881) `build: release tokenspeed-mla 2.0.6` | infra,perf | main | - |
| - | [#2882](https://github.com/lightseekorg/tokenspeed/pull/2882) `build: require tokenspeed-mla 2.0.6` | infra,perf | main | - |
| - | [#2883](https://github.com/lightseekorg/tokenspeed/pull/2883) `fix(kernel): cache PrimTS QSA cluster occupancy queries` | bug,perf | main | - |
| - | [#2885](https://github.com/lightseekorg/tokenspeed/pull/2885) `build: release tokenspeed-scheduler 0.1.49` | infra,perf | main | - |
| - | [#2886](https://github.com/lightseekorg/tokenspeed/pull/2886) `build: require tokenspeed-scheduler 0.1.49` | infra,perf | main | - |
| - | [#2889](https://github.com/lightseekorg/tokenspeed/pull/2889) `test(kernel): wait on the four gather children at once and draw FP8 experts on the GPU` | perf,quant | main | - |
| - | [#2890](https://github.com/lightseekorg/tokenspeed/pull/2890) `fix(communication): keep the signal barrier's CAS results unsigned` | bug | main | - |
| - | [#2891](https://github.com/lightseekorg/tokenspeed/pull/2891) `feat(muse): serve Muse Spark with a DFlash2 draft` |  | main | - |
| - | [#2894](https://github.com/lightseekorg/tokenspeed/pull/2894) `perf(amd): pack speculative verify rows in gfx950 mha decode` | perf,rocm | main | - |
| - | [#2907](https://github.com/lightseekorg/tokenspeed/pull/2907) `docs(recipes): serve Muse Spark on MI355X with a DFlash2 draft` | rocm | main | - |
| - | [#2908](https://github.com/lightseekorg/tokenspeed/pull/2908) `fix(conv): upload Inkling commit tables without a host sync` | bug | main | - |
| - | [#2910](https://github.com/lightseekorg/tokenspeed/pull/2910) `ci: split NVIDIA runtime-1gpu UT into two parts` | infra,nvidia | main | - |
| - | [#2913](https://github.com/lightseekorg/tokenspeed/pull/2913) `perf(attention): reuse idle MLA history chunk capacity` | perf | main | - |
| - | [#2914](https://github.com/lightseekorg/tokenspeed/pull/2914) `feat(spec): probabilistic drafting with block verification for DSpark and EAGLE3 chains` |  | main | - |
| - | [#2915](https://github.com/lightseekorg/tokenspeed/pull/2915) `perf(kimi-k3): run the TP8 decode MoE as one mailbox chain` | perf | main | - |
| - | [#2917](https://github.com/lightseekorg/tokenspeed/pull/2917) `ci: stop cancelling running test jobs on pushes to main` | infra | main | - |
| - | [#2918](https://github.com/lightseekorg/tokenspeed/pull/2918) `perf(dsv41): rotate the decode query tail in place, 8 heads per program` | perf | main | - |
| - | [#2920](https://github.com/lightseekorg/tokenspeed/pull/2920) `perf(control): stream committed states in place` | perf | main | - |
| - | [#2922](https://github.com/lightseekorg/tokenspeed/pull/2922) `perf(cache): unify host and device eviction planning` | perf | main | - |
| - | [#2923](https://github.com/lightseekorg/tokenspeed/pull/2923) `fix(multimodal): use device-specific streams for encoding cleanup` | bug | npu_lite_chl | - |
| - | [#2924](https://github.com/lightseekorg/tokenspeed/pull/2924) `fix(gdn): store in-forward State checkpoints in MIXED verify rounds` | bug | main | - |
| - | [#2928](https://github.com/lightseekorg/tokenspeed/pull/2928) `perf(scheduler): amortize dense block-table growth` | perf | main | - |
| - | [#2931](https://github.com/lightseekorg/tokenspeed/pull/2931) `feat(scheduler): expose native capacity and session cache hints` | perf | main | - |
| - | [#2934](https://github.com/lightseekorg/tokenspeed/issues/2934) `RFC: OTLP trace export from request lifecycle timestamps` |  | ? | - |
| - | [#2935](https://github.com/lightseekorg/tokenspeed/pull/2935) `feat(trace): export request lifecycles over OTLP/HTTP` |  | main | - |
| - | [#2936](https://github.com/lightseekorg/tokenspeed/pull/2936) `feat(logging): add asynchronous logging for rust host and python logger` |  | main | - |
| - | [#2937](https://github.com/lightseekorg/tokenspeed/pull/2937) `fix(numerics): align YaRN, DSA and logprob arithmetic` | bug | main | - |
| - | [#2938](https://github.com/lightseekorg/tokenspeed/pull/2938) `perf(cache): rank non-leaf State checkpoints by distance in a request window` | perf | main | - |
| - | [#2939](https://github.com/lightseekorg/tokenspeed/pull/2939) `test(engine): give the shutdown node stub the async logging flag` |  | main | - |
| - | [#2942](https://github.com/lightseekorg/tokenspeed/pull/2942) `perf(gfx950): stop recompiling MHA prefill kernels per batch size` | perf,rocm | main | - |
| - | [#2943](https://github.com/lightseekorg/tokenspeed/pull/2943) `fix(qsa): compute CuTe stream top-k offsets in int64` | bug | main | - |
| - | [#2944](https://github.com/lightseekorg/tokenspeed/pull/2944) `fix(amd): tighten gfx1250 fabric Iris setup` | bug,rocm | main | - |
| - | [#2945](https://github.com/lightseekorg/tokenspeed/pull/2945) `perf(dsv41): drop two per-layer copies from the decode step` | perf | main | - |
| - | [#2946](https://github.com/lightseekorg/tokenspeed/pull/2946) `refactor(scheduler): hold L3 leases, session registrations and store waits by RAII` |  | main | - |
| - | [#2948](https://github.com/lightseekorg/tokenspeed/pull/2948) `perf(engine): cut the control thread's round by a third at large batches` | perf | main | - |
| - | [#2949](https://github.com/lightseekorg/tokenspeed/pull/2949) `perf(kimi-k3): run TP8 decode layers through the mailbox chain` | perf | main | - |
| - | [#2954](https://github.com/lightseekorg/tokenspeed/pull/2954) `perf(scheduler): keep check failure paths out of line` | perf | main | - |
| - | [#2958](https://github.com/lightseekorg/tokenspeed/pull/2958) `refactor(models): share one gated MLP with per-model fused kernels` | perf | main | - |
| - | [#2959](https://github.com/lightseekorg/tokenspeed/pull/2959) `ci: raise the max_tokens of the Kimi-K3 and Muse Spark TP8/EP1 AIME26 evals` | infra | main | - |
| - | [#2962](https://github.com/lightseekorg/tokenspeed/pull/2962) `perf(layernorm): run GemmaRMSNorm through fused Triton kernels on AMD` | perf,rocm | main | - |
| - | [#2964](https://github.com/lightseekorg/tokenspeed/pull/2964) `perf(dsv41): batch native BF16 indexer scoring` | perf | main | - |
| - | [#2965](https://github.com/lightseekorg/tokenspeed/pull/2965) `perf(scheduler): cut the control round at long contexts by 17x` | perf | main | - |
| - | [#2969](https://github.com/lightseekorg/tokenspeed/pull/2969) `feat(cache): reserve owner copy-in blocks so every prompt end publishes its tail` | perf | main | - |
| - | [#2970](https://github.com/lightseekorg/tokenspeed/pull/2970) `fix(ci): run the AMD Qwen3.8 gsm8k eval without Host L2` | bug,infra,rocm | main | - |
| - | [#2971](https://github.com/lightseekorg/tokenspeed/pull/2971) `refactor(cache): count Host KV duplicate nodes instead of listing them` | perf | main | - |
| - | [#2973](https://github.com/lightseekorg/tokenspeed/pull/2973) `fix(kernel): address MLA token offsets past 2**31 elements in int64` | bug,perf | main | - |
| - | [#2975](https://github.com/lightseekorg/tokenspeed/pull/2975) `refactor(cache): keep the boundary tree in step through RAII holds` | perf | main | - |
| - | [#2978](https://github.com/lightseekorg/tokenspeed/pull/2978) `fix(launcher): guard optional pinned allocator tuning` | bug,infra,perf | main | - |
| - | [#2979](https://github.com/lightseekorg/tokenspeed/pull/2979) `docs(agents): prefer RAII in the engine's Rust code` |  | main | - |
| - | [#2983](https://github.com/lightseekorg/tokenspeed/pull/2983) `perf(kda): keep 8-row verify tiles for windows of eight or more tokens` | perf | main | - |
| - | [#2984](https://github.com/lightseekorg/tokenspeed/pull/2984) `perf(fp8): extend MXFP8 weight scales to Fp8LinearMethod` | perf,quant | main | - |
| - | [#2986](https://github.com/lightseekorg/tokenspeed/pull/2986) `refactor(models): move DSV4.1, GLM-5.3-Flash, MiniMax-M3 and Inkling MLPs onto GatedMLP` |  | main | - |
| - | [#2990](https://github.com/lightseekorg/tokenspeed/pull/2990) `fix(runtime): warm disaggregated decode workers on decode` | bug | main | - |
| - | [#2996](https://github.com/lightseekorg/tokenspeed/pull/2996) `perf(dsv41): group paged queries and prepare native scores once` | perf | main | - |
| - | [#2997](https://github.com/lightseekorg/tokenspeed/pull/2997) `refactor(moe): share one MoE block forward across DSV3, GLM-5.3-Flash and MiniMax-M3` |  | main | - |
| - | [#2999](https://github.com/lightseekorg/tokenspeed/pull/2999) `test(runtime): use a real Mapping in the attention-DP lm_head test` |  | main | - |
| - | [#3001](https://github.com/lightseekorg/tokenspeed/pull/3001) `fix(qwen4): align MTP with the target LM-head layout` | bug | main | - |
| - | [#3002](https://github.com/lightseekorg/tokenspeed/pull/3002) `perf(kernel): launch the DSV4.1 mHC and FP8 quantizer kernels with PDL` | perf,quant | main | - |
| - | [#3003](https://github.com/lightseekorg/tokenspeed/pull/3003) `fix(scheduler): guard duplicate IDs and contain submission errors` | bug | main | - |
| - | [#3004](https://github.com/lightseekorg/tokenspeed/pull/3004) `fix(qwen4): align hyper-connection residual rows with attention TP` | bug | main | - |
| - | [#3005](https://github.com/lightseekorg/tokenspeed/pull/3005) `feat(kda): add cuDNN prefill and CUDA graph support` | nvidia | main | - |
| - | [#3007](https://github.com/lightseekorg/tokenspeed/pull/3007) `refactor(layers): table-driven rope scaling construction in get_rope` |  | main | - |
| - | [#3008](https://github.com/lightseekorg/tokenspeed/pull/3008) `perf(mla): group FP8 packing across token and head rows` | perf,quant | main | - |
| - | [#3009](https://github.com/lightseekorg/tokenspeed/pull/3009) `fix(qwen4): share the complete target LM head with the draft` | bug | main | - |
| - | [#3010](https://github.com/lightseekorg/tokenspeed/pull/3010) `perf(dsv41): speed up the decode attention projections` | perf | main | - |
| - | [#3012](https://github.com/lightseekorg/tokenspeed/pull/3012) `feat(engine): expose prefill and decode metrics for Raptor` |  | main | - |
| - | [#3015](https://github.com/lightseekorg/tokenspeed/pull/3015) `feat(kimi-k31): support Kimi-K3.1` |  | main | - |
| - | [#3016](https://github.com/lightseekorg/tokenspeed/pull/3016) `perf(moe): stage MegaMoE inputs several tokens per program, with PDL` | perf | main | - |
| - | [#3017](https://github.com/lightseekorg/tokenspeed/pull/3017) `refactor(models): run gpt-oss decoder layers on CommManager` |  | main | - |
| - | [#3018](https://github.com/lightseekorg/tokenspeed/pull/3018) `fix(glm53-flash): dequantize an FP8 indexer wk into the fused projection` | bug,perf,quant | main | - |
| - | [#3020](https://github.com/lightseekorg/tokenspeed/pull/3020) `fix(runtime): check freed pinned blocks on the allocator's helper threads` | bug,infra | main | - |
| - | [#3021](https://github.com/lightseekorg/tokenspeed/pull/3021) `docs(recipes): add the Kimi K3.1 Pro recipe` |  | main | - |
| - | [#3022](https://github.com/lightseekorg/tokenspeed/pull/3022) `refactor(models): run MiniMax-M3's final norm on CommManager` |  | main | - |
| - | [#3023](https://github.com/lightseekorg/tokenspeed/pull/3023) `perf(control): walk the prompt ids only when prompt logprobs need them` | perf | main | - |
| - | [#3024](https://github.com/lightseekorg/tokenspeed/pull/3024) `chore(mla): bump version to 2.0.7` | infra | main | - |
| - | [#3025](https://github.com/lightseekorg/tokenspeed/pull/3025) `chore(deps): upgrade tokenspeed-mla to 2.0.7` | perf | main | - |
| - | [#3026](https://github.com/lightseekorg/tokenspeed/pull/3026) `perf(execution): hoist input-fill list casts and cache sampling route` | perf | main | - |
| - | [#3027](https://github.com/lightseekorg/tokenspeed/pull/3027) `perf(scheduler): expose the forward token vectors as read-only ndarray views` | perf | main | - |
| - | [#3028](https://github.com/lightseekorg/tokenspeed/pull/3028) `perf(moe): run the DSV4.1 shared expert inside the MegaMoE launch` | perf | main | - |
| - | [#3061](https://github.com/lightseekorg/tokenspeed/pull/3061) `docs(recipes): update muse spark amd recipe` | rocm | efric/muse-base/all | - |
| - | [#3063](https://github.com/lightseekorg/tokenspeed/pull/3063) `feat(mla): add native MLA prefill kernel` | perf | main | - |
| - | [#3067](https://github.com/lightseekorg/tokenspeed/pull/3067) `perf(dsv41): gather Engram host rows straight into wkv's MXFP8 input` | perf,quant | main | - |
| - | [#3069](https://github.com/lightseekorg/tokenspeed/pull/3069) `fix(mla): align DSpark KV dtype and fix workspace overflow` | bug,risk | main | - |
| - | [#3072](https://github.com/lightseekorg/tokenspeed/pull/3072) `perf(scheduler): defer KV-event registration until admission succeeds` | perf | main | - |
| - | [#3074](https://github.com/lightseekorg/tokenspeed/pull/3074) `fix(cache): export private P/D partial-prefix destinations` | bug,perf | main | - |
| - | [#3075](https://github.com/lightseekorg/tokenspeed/pull/3075) `perf(dsv41): clean only the live tiles of each indexer score row` | perf | main | - |
| - | [#3077](https://github.com/lightseekorg/tokenspeed/pull/3077) `build: pin Hopper Mooncake to 0.3.13.post20261026` | infra,nvidia | main | - |
| - | [#3078](https://github.com/lightseekorg/tokenspeed/pull/3078) `perf(dsv41): upload block-table row spans and rebuild them on the device` | perf | main | - |
| - | [#3079](https://github.com/lightseekorg/tokenspeed/pull/3079) `refactor(models): run every decoder layer on CommManager` |  | main | - |
| - | [#3083](https://github.com/lightseekorg/tokenspeed/pull/3083) `perf(kimi-k31): trim four launches from each DSA layer's decode prologue` | perf | main | - |
| - | [#3084](https://github.com/lightseekorg/tokenspeed/pull/3084) `fix(test): expect the gfx950 DSA prefill adapters to forward the warmup flag` | bug,rocm | main | - |
| - | [#3085](https://github.com/lightseekorg/tokenspeed/pull/3085) `fix(test): parse the cached Muse Spark checkpoint with its own quantization format` | bug,quant | main | - |
| - | [#3087](https://github.com/lightseekorg/tokenspeed/pull/3087) `ci(amd): change gfx950 test / bench runner labels` | bug,infra,perf,rocm | main | - |
| - | [#3089](https://github.com/lightseekorg/tokenspeed/pull/3089) `Revert "ci(amd): change gfx950 test / bench runner labels"` | bug,infra,perf,rocm | main | - |
| - | [#3090](https://github.com/lightseekorg/tokenspeed/pull/3090) `build: release tokenspeed-mla 2.0.8` | infra,perf | main | - |
| - | [#3092](https://github.com/lightseekorg/tokenspeed/pull/3092) `build: require tokenspeed-mla 2.0.8` | infra,perf | main | - |
| - | [#3094](https://github.com/lightseekorg/tokenspeed/pull/3094) `test(dsv41): give the mega-MoE stand-in a shared_expert_fused field` | perf | main | - |
| - | [#3097](https://github.com/lightseekorg/tokenspeed/pull/3097) `perf(mla): unroll fixed FP8 decode MMA loops` | perf,quant | main | - |
| - | [#3099](https://github.com/lightseekorg/tokenspeed/pull/3099) `chore: upgrade FlashInfer to 0.7.3` | nvidia | main | - |

### tokenspeed — Open / submitted (114 items)

| # | item | tags | base | claim |
| --- | --- | --- | --- | --- |
| - | [#2822](https://github.com/lightseekorg/tokenspeed/pull/2822) `test(ci/npu): add unit tests for the NPU report validation layer` | infra | main | - |
| - | [#2826](https://github.com/lightseekorg/tokenspeed/pull/2826) `fix(amd): wait for freed VRAM in MXFP4 MoE weight preprocessing` | bug,quant,rocm | main | - |
| - | [#2857](https://github.com/lightseekorg/tokenspeed/pull/2857) `perf(glm53): route gfx1250 BF16 prefill GEMMs to Gluon and sort FP8 MoE rows by expert` | perf,quant,rocm | main | - |
| - | [#2861](https://github.com/lightseekorg/tokenspeed/pull/2861) `perf(k3): cluster gfx1250 latent input, slab MoE down weights, rebalance MLA decode` | perf,rocm | main | - |
| - | [#2876](https://github.com/lightseekorg/tokenspeed/pull/2876) `feat(metrics): export prefix cache tier and Host L2 eviction metrics` | perf | main | - |
| - | [#2884](https://github.com/lightseekorg/tokenspeed/pull/2884) `feat(dsv41): enable prefill graphs with attention DP` |  | main | - |
| - | [#2887](https://github.com/lightseekorg/tokenspeed/pull/2887) `perf(dsv41): accelerate visual MoE routing` | perf | main | - |
| - | [#2888](https://github.com/lightseekorg/tokenspeed/pull/2888) `bench(dsv41): add agentic benchmark recipes` | perf | main | - |
| - | [#2892](https://github.com/lightseekorg/tokenspeed/pull/2892) `feat(spec): verify sampled DFlash2 drafts by rejection sampling on triton` | rocm | main | - |
| - | [#2893](https://github.com/lightseekorg/tokenspeed/pull/2893) `perf(spec): drop redundant launches from each DFLASH decode step` | perf | efric/muse-split/d2-dflash2-rejection-sampling | - |
| - | [#2895](https://github.com/lightseekorg/tokenspeed/pull/2895) `fix(amd): stop gfx950 mha prefill and extend from compiling while serving` | bug,rocm | main | - |
| - | [#2896](https://github.com/lightseekorg/tokenspeed/pull/2896) `perf(amd): speed up gfx950 mha extend over long cached prefixes` | perf,rocm | main | - |
| - | [#2897](https://github.com/lightseekorg/tokenspeed/pull/2897) `fix(amd): make gfx950 mha attention over fp8 caches accurate and faster` | bug,perf,quant,rocm | main | - |
| - | [#2898](https://github.com/lightseekorg/tokenspeed/pull/2898) `perf(amd): balance gfx950 mha verify splits by request length` | perf,rocm | main | - |
| - | [#2899](https://github.com/lightseekorg/tokenspeed/pull/2899) `perf(amd): pick gfx950 MoE, router and dense GEMMs by row count` | perf,rocm | main | - |
| - | [#2900](https://github.com/lightseekorg/tokenspeed/pull/2900) `perf(muse): cut copies and RCCL fallbacks from Muse Spark communication` | perf,rocm | main | - |
| - | [#2901](https://github.com/lightseekorg/tokenspeed/pull/2901) `perf(amd): reduce Muse expert TP8 routes on their token owners` | perf,rocm | main | - |
| - | [#2902](https://github.com/lightseekorg/tokenspeed/pull/2902) `perf(amd): split Muse expert TP8 prefill down projection by columns` | perf,rocm | main | - |
| - | [#2903](https://github.com/lightseekorg/tokenspeed/pull/2903) `perf(amd): fuse the Muse expert TP8 decode route all-reduce and norm` | perf,rocm | efric/muse-split/m5-muse-ep1-prefill-column-split | - |
| - | [#2911](https://github.com/lightseekorg/tokenspeed/pull/2911) `perf(metrics): flush Prometheus writes once per round` | perf | main | - |
| - | [#2912](https://github.com/lightseekorg/tokenspeed/pull/2912) `release(engine): tokenspeed-wire and tokenspeed-client 0.2.0` | infra,perf | main | - |
| - | [#2916](https://github.com/lightseekorg/tokenspeed/pull/2916) `feat(attn): add Qwen FP8 attention projections support` | quant | main | - |
| - | [#2919](https://github.com/lightseekorg/tokenspeed/pull/2919) `perf(cache): radix-sort closed-prefix candidates within an access epoch` | perf | main | - |
| - | [#2921](https://github.com/lightseekorg/tokenspeed/issues/2921) `[Feature] Intel GPU (XPU) platform support — Data Center GPU D-series` | nvidia | ? | - |
| - | [#2925](https://github.com/lightseekorg/tokenspeed/pull/2925) `perf(kernel): end FP8 QSA prefix loops at the last valid tile` | perf,quant | perf/qsa-fp8-decode-ring | - |
| - | [#2926](https://github.com/lightseekorg/tokenspeed/pull/2926) `perf(gdn): capture Qwen4-Exp GDN layers inside prefill graphs` | perf | main | - |
| - | [#2927](https://github.com/lightseekorg/tokenspeed/pull/2927) `perf(qsa): share K across ragged prefill rows in block scoring` | perf | main | - |
| - | [#2930](https://github.com/lightseekorg/tokenspeed/pull/2930) `feat(kimi3): serve K3 with Iris fusions on gfx1250` | perf,rocm | main | - |
| - | [#2933](https://github.com/lightseekorg/tokenspeed/pull/2933) `perf(qsa): run large FP8 prefill calls on a BF16 KV scratch` | perf,quant | main | - |
| - | [#2941](https://github.com/lightseekorg/tokenspeed/pull/2941) `fix(amd): run short prefill requests through the regular tile path on gfx950` | bug,rocm | main | - |
| - | [#2947](https://github.com/lightseekorg/tokenspeed/pull/2947) `perf(amd): optimize gfx1250 MHA prefill scheduling` | perf,rocm | main | - |
| - | [#2955](https://github.com/lightseekorg/tokenspeed/pull/2955) `feat(dspark): add experimental confidence verification with segmented CUDA graphs` | nvidia | main | - |
| - | [#2956](https://github.com/lightseekorg/tokenspeed/pull/2956) `fix(pd): keep KV pages until PD transfers stop` | bug | main | - |
| - | [#2957](https://github.com/lightseekorg/tokenspeed/pull/2957) `fix(amd): wait for every wave's stores to reach L2 before a release` | bug,infra,rocm | main | - |
| - | [#2960](https://github.com/lightseekorg/tokenspeed/pull/2960) `perf(cache): reuse storage reservation scratch capacity` | perf | main | - |
| - | [#2961](https://github.com/lightseekorg/tokenspeed/pull/2961) `feat(scheduler): opt-in prefill chunk yield on the P role` |  | main | - |
| - | [#2963](https://github.com/lightseekorg/tokenspeed/pull/2963) `perf(cache): reuse prepared prefix keys during storage preparation` | perf | main | - |
| - | [#2966](https://github.com/lightseekorg/tokenspeed/pull/2966) `fix(scheduler): register every KV-event boundary a restored request republishes` | bug | main | - |
| - | [#2967](https://github.com/lightseekorg/tokenspeed/pull/2967) `perf(cache): skip reclaimed slots when counting bucket loads` | perf | main | - |
| - | [#2972](https://github.com/lightseekorg/tokenspeed/pull/2972) `perf(mha): run draft-tree lane prefixes as one Triton decode per request, with batch-shaped key splits` | perf,rocm | main | - |
| - | [#2974](https://github.com/lightseekorg/tokenspeed/pull/2974) `feat(l3): integrate 3FS native USRBIO storage` |  | main | - |
| - | [#2980](https://github.com/lightseekorg/tokenspeed/pull/2980) `perf(spec): replay the Eagle drafter's prefill work from CUDA graphs` | nvidia,perf | main | - |
| - | [#2981](https://github.com/lightseekorg/tokenspeed/pull/2981) `feat(scheduler): drop short prompt-end checkpoints on prefill servers` |  | main | - |
| - | [#2982](https://github.com/lightseekorg/tokenspeed/pull/2982) `feat(scheduler): demote superseded State checkpoints (opt-in)` |  | main | - |
| - | [#2985](https://github.com/lightseekorg/tokenspeed/pull/2985) `perf(cache): size the compact Host parent to whole KV pages` | perf | main | - |
| - | [#2987](https://github.com/lightseekorg/tokenspeed/pull/2987) `fix(epd): return encode send slots with their chunks` | bug | main | - |
| - | [#2988](https://github.com/lightseekorg/tokenspeed/pull/2988) `fix(client): keep requests and control waits cancellation-safe` | bug | main | - |
| - | [#2989](https://github.com/lightseekorg/tokenspeed/pull/2989) `perf(cache): reuse DMA block rows across layers` | perf | main | - |
| - | [#2991](https://github.com/lightseekorg/tokenspeed/pull/2991) `test(scheduler): check cache contents in randomized closed loops` | perf | main | - |
| - | [#2992](https://github.com/lightseekorg/tokenspeed/pull/2992) `perf(cache): skip in-flight deduplication for empty Host store drains` | perf | main | - |
| - | [#2993](https://github.com/lightseekorg/tokenspeed/pull/2993) `perf(kda): verify speculative windows with a CuTe DSL kernel on Blackwell` | nvidia,perf | main | - |
| - | [#2994](https://github.com/lightseekorg/tokenspeed/pull/2994) `fix(cache): export the block filled into a decode-role tail hole` | bug,perf | main | - |
| - | [#2995](https://github.com/lightseekorg/tokenspeed/pull/2995) `test: add batch state isolation harness` |  | main | - |
| - | [#2998](https://github.com/lightseekorg/tokenspeed/pull/2998) `perf(cache): batch token input to prefix SHA-256` | perf | main | - |
| - | [#3000](https://github.com/lightseekorg/tokenspeed/pull/3000) `fix(npu): bind prefill execution stream only after warmup` | bug | main | - |
| - | [#3006](https://github.com/lightseekorg/tokenspeed/pull/3006) `refactor(kernel): centralize optional-package probes in tokenspeed_kernel._optional` | perf | main | - |
| - | [#3011](https://github.com/lightseekorg/tokenspeed/pull/3011) `fix(scheduler): coordinate memory release across attention DP ranks` | bug,infra | main | - |
| - | [#3013](https://github.com/lightseekorg/tokenspeed/pull/3013) `feat(kernel): add independent Hyper-Connections residual ops` | perf | main | - |
| - | [#3014](https://github.com/lightseekorg/tokenspeed/pull/3014) `fix(platform): update is_cuda checks to support AMD ROCm tensors` | bug,rocm | main | - |
| - | [#3019](https://github.com/lightseekorg/tokenspeed/pull/3019) `fix(moe): keep the SM90 FP8 per-channel MoE on exact tiles above 512 tokens` | bug,nvidia,quant | main | - |
| - | [#3029](https://github.com/lightseekorg/tokenspeed/pull/3029) `fix(amd): keep every wave of the muse spark attention tail on one stage` | bug,rocm | main | - |
| - | [#3030](https://github.com/lightseekorg/tokenspeed/pull/3030) `fix(runtime): size speculative decode state for the warmup, not the request cap` | bug | main | - |
| - | [#3031](https://github.com/lightseekorg/tokenspeed/pull/3031) `fix(amd): drain gfx950 split decode stores with a compiler-visible fence` | bug,rocm | main | - |
| - | [#3032](https://github.com/lightseekorg/tokenspeed/pull/3032) `refactor(kernel-amd): expose the gfx950 mha decode split merge and program ids` | perf,rocm | efric/muse-base/root | - |
| - | [#3033](https://github.com/lightseekorg/tokenspeed/pull/3033) `perf(amd): pipeline the gfx950 sliding-window split decode's page loads` | perf,rocm | efric/muse-attn/01-split-merge-program | - |
| - | [#3034](https://github.com/lightseekorg/tokenspeed/pull/3034) `feat(runtime): expose a layer's decode kv view to fused kernels` | perf | efric/muse-attn/02-sliding-split-pipeline | - |
| - | [#3036](https://github.com/lightseekorg/tokenspeed/pull/3036) `perf(amd): issue the few-row decode gemv's weight loads up front` | perf,rocm | efric/muse-attn/03-decode-kv-view | - |
| - | [#3037](https://github.com/lightseekorg/tokenspeed/pull/3037) `perf(amd): drop the fp32 router gemv's masked-load selects` | perf,rocm | efric/muse-comm/01-gemv-loads-up-front | - |
| - | [#3038](https://github.com/lightseekorg/tokenspeed/pull/3038) `refactor(kernel-amd): expose the gfx950 sigmoid top-k body per token` | perf,rocm | efric/muse-comm/02-router-gemv-selects | - |
| - | [#3039](https://github.com/lightseekorg/tokenspeed/pull/3039) `perf(amd): fuse muse spark's bf16-expert pre-expert gather and rmsnorm` | perf,rocm | efric/muse-comm/03-topk-body | - |
| - | [#3040](https://github.com/lightseekorg/tokenspeed/pull/3040) `perf(amd): route muse spark decode rows inside the pre-expert gather` | perf,rocm | efric/muse-comm/04-edges-gather-rmsnorm | - |
| - | [#3041](https://github.com/lightseekorg/tokenspeed/pull/3041) `refactor(kernel): expose the iris two-shot all-reduce phases as device functions` | perf | efric/muse-comm/05-router-front | - |
| - | [#3042](https://github.com/lightseekorg/tokenspeed/pull/3042) `perf(amd): run muse spark sliding decode attention through its boundary in one launch` | perf,rocm | efric/muse-comm/06-two-shot-phases | - |
| - | [#3043](https://github.com/lightseekorg/tokenspeed/pull/3043) `refactor(kernel): split muse spark's post-expert tail into shared device functions` | perf | efric/muse-comm/07-sliding-attention-tail | - |
| - | [#3044](https://github.com/lightseekorg/tokenspeed/pull/3044) `perf(amd): gather 9-16 muse spark decode rows from a column-shard gemm` | perf,rocm | efric/muse-comm/08-moetail-shared-bodies | - |
| - | [#3045](https://github.com/lightseekorg/tokenspeed/pull/3045) `perf(amd): push whole 128-byte lines from muse spark's column tail senders` | perf,rocm | efric/muse-comm/09-column-shard-tail | - |
| - | [#3046](https://github.com/lightseekorg/tokenspeed/pull/3046) `perf(amd): stage the moetail sender's rows in lds once per workgroup` | perf,rocm | efric/muse-comm/10-column-tail-whole-lines | - |
| - | [#3047](https://github.com/lightseekorg/tokenspeed/pull/3047) `perf(amd): keep the direct mxfp4 decode stage 1's k tiles in flight` | perf,quant,rocm | efric/muse-base/root | - |
| - | [#3048](https://github.com/lightseekorg/tokenspeed/pull/3048) `perf(amd): reuse stage 1's route grouping in the mxfp4 route-tile stage 2` | perf,quant,rocm | efric/muse-moe/01-stage1-k-tiles | - |
| - | [#3049](https://github.com/lightseekorg/tokenspeed/pull/3049) `perf(amd): widen the deferred mxfp4 direct decode stage 2 tile at ep1` | perf,quant,rocm | efric/muse-moe/02-route-tiles | - |
| - | [#3050](https://github.com/lightseekorg/tokenspeed/pull/3050) `perf(amd): run muse spark's 8-row mxfp4 moe decode as one weight-streaming launch` | perf,quant,rocm | efric/muse-moe/03-wide-deferred-stage2 | - |
| - | [#3051](https://github.com/lightseekorg/tokenspeed/pull/3051) `perf(amd): take the block draft's small-row dense gemms off hipBLASLt` | perf,rocm | efric/muse-base/draft | - |
| - | [#3052](https://github.com/lightseekorg/tokenspeed/pull/3052) `perf(sampling): fuse the vocab-parallel top-k around its all-gather` | perf | efric/muse-draft/01-small-row-gemms | - |
| - | [#3053](https://github.com/lightseekorg/tokenspeed/pull/3053) `perf(spec): project the block draft's context inline on a column-split fc` | perf | efric/muse-draft/02-vocab-topk-gather | - |
| - | [#3054](https://github.com/lightseekorg/tokenspeed/pull/3054) `perf(amd): fuse the block draft's all-reduce with its residual rmsnorm` | perf,rocm | efric/muse-draft/03-context-inline | - |
| - | [#3055](https://github.com/lightseekorg/tokenspeed/pull/3055) `perf(sampling): keep the target's sampled logits vocab-sharded under tp` | perf | efric/muse-draft/04-ar-rmsnorm | - |
| - | [#3056](https://github.com/lightseekorg/tokenspeed/pull/3056) `perf(amd): stream the dflash2 draft's mlp, o_proj and head weights in fp8` | perf,quant,rocm | efric/muse-draft/05-vocab-shard-sampling | - |
| - | [#3057](https://github.com/lightseekorg/tokenspeed/pull/3057) `feat(scheduler): add a prefill/decode interval` |  | main | - |
| - | [#3058](https://github.com/lightseekorg/tokenspeed/pull/3058) `feat(runtime): add --prefill-decode-interval` |  | efric/muse-sched/01-prefill-decode-interval | - |
| - | [#3060](https://github.com/lightseekorg/tokenspeed/pull/3060) `test(amd): gate inline asm in the gfx950 kernels` | perf,rocm | efric/muse-base/gate | - |
| - | [#3064](https://github.com/lightseekorg/tokenspeed/pull/3064) `fix(npu): honor selected devices in EPD transfer runtime` | bug | main | - |
| - | [#3065](https://github.com/lightseekorg/tokenspeed/pull/3065) `fix(cache): compact a lone request's packed-group blocks when eviction alone cannot fund its admission` | bug,perf | main | - |
| - | [#3066](https://github.com/lightseekorg/tokenspeed/pull/3066) `fix(ci): verify and cache FlashInfer JIT cache wheel downloads` | bug,infra,nvidia,perf | main | - |
| - | [#3068](https://github.com/lightseekorg/tokenspeed/issues/3068) `[Feature] EAGLE-4 / EAGLE-Harness performance on AMD MI355X (gfx950): optimization history and open items` | perf,rocm | ? | - |
| - | [#3070](https://github.com/lightseekorg/tokenspeed/pull/3070) `perf(kernel): run small-weight decode BF16 GEMMs on pinned FlashInfer TGV tiles` | infra,nvidia,perf | main | - |
| - | [#3071](https://github.com/lightseekorg/tokenspeed/pull/3071) `fix(scheduler): publish hybrid KV cache events from Full/history residency` | bug,perf | main | - |
| - | [#3073](https://github.com/lightseekorg/tokenspeed/pull/3073) `fix(cuda): exclude compiler stubs from runtime library lookup` | bug,nvidia | main | - |
| - | [#3076](https://github.com/lightseekorg/tokenspeed/pull/3076) `fix(host): notify data-plane state changes through a guard` | bug | main | - |
| - | [#3080](https://github.com/lightseekorg/tokenspeed/pull/3080) `feat(attention): support Gluon MLA decode context parallelism` | rocm | main | - |
| - | [#3081](https://github.com/lightseekorg/tokenspeed/pull/3081) `perf(runtime): pad every state group's stopped rows in one launch` | perf | main | - |
| - | [#3082](https://github.com/lightseekorg/tokenspeed/pull/3082) `perf(amd): Kimi-K3.1 KVP8 decode and prefill on MI350X` | perf,rocm | main | - |
| - | [#3086](https://github.com/lightseekorg/tokenspeed/pull/3086) `feat(moe): add distributed weight data parallel prefill` |  | main | - |
| - | [#3088](https://github.com/lightseekorg/tokenspeed/pull/3088) `fix(ci): allow pinned CUTLASS DSL companion in cu129 installs` | bug,infra,nvidia | main | - |
| - | [#3093](https://github.com/lightseekorg/tokenspeed/pull/3093) `feat(rl): support rl` |  | main | - |
| - | [#3095](https://github.com/lightseekorg/tokenspeed/pull/3095) `fix(streaming): flush output when a decode step crosses the interval` | bug | main | - |
| - | [#3096](https://github.com/lightseekorg/tokenspeed/pull/3096) `refactor(runtime): make vocabulary domains explicit` |  | main | - |
| - | [#3098](https://github.com/lightseekorg/tokenspeed/pull/3098) `feat(lm-head): support tensor parallel heads across attention DP groups` |  | main | - |
| - | [#3100](https://github.com/lightseekorg/tokenspeed/pull/3100) `feat(numerics): add blockwise logprob subtraction modes` |  | main | - |
| - | [#3101](https://github.com/lightseekorg/tokenspeed/pull/3101) `perf: build forward block tables from live windows` | infra,perf | main | - |
| - | [#3102](https://github.com/lightseekorg/tokenspeed/pull/3102) `perf: fuse V4.1 decode attention with FP8 output` | perf,quant | main | - |
| - | [#3104](https://github.com/lightseekorg/tokenspeed/pull/3104) `fix(runtime): separate input token bounds from output vocabulary` | bug | main | - |
| - | [#3105](https://github.com/lightseekorg/tokenspeed/pull/3105) `fix(pd): isolate registrations and drain cancelled transfers` | bug | main | - |
| - | [#3106](https://github.com/lightseekorg/tokenspeed/pull/3106) `feat(runtime): receive complete WeightStore snapshots` |  | main | - |
| - | [#3107](https://github.com/lightseekorg/tokenspeed/pull/3107) `feat: allow model profiles to construct attention configurations` |  | main | - |
