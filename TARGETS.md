# THE NEXT 80 SUBJECTS

**Ranked by the gap between reputation and substrate truth.**

Every repo below was selected on the same axiom: the more trust a system has accumulated, the more interesting its confession.

---

## Selection Logic

The first 20 subjects mapped the obvious terrain — the tools everyone uses and nobody reads. The next 80 go deeper: into the protocols beneath the protocols, the agent frameworks being deployed before anyone understands them, the crypto contracts holding billions with 500 lines of Solidity, and the compilers that compile the compilers.

The forensic lens does not change. The targets get harder.

---

## Category 01 — AI Agents & Orchestration (10)

> *The fastest-moving category in software. Ship velocity and security rigor are inversely correlated. These repos are the blast radius.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 21 | [microsoft/autogen](https://github.com/microsoft/autogen) | ~35k | Multi-agent trust boundaries — when an agent delegates to another agent, who validates the output? |
| 22 | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | ~27k | Role-based agent permissions with no enforcement substrate beneath the abstraction. |
| 23 | [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | ~23k | Microsoft's enterprise AI glue layer — the attack surface of every Fortune 500 AI integration. |
| 24 | [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | ~26k | Agents writing code that gets executed — the supply chain attack writes itself. |
| 25 | [joaomdmoura/crewAI-examples](https://github.com/joaomdmoura/crewAI-examples) | ~5k | Examples become templates become production. The assumption baked into the example is the assumption baked into the system. |
| 26 | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | ~8k | Validation as the last line of defense in agent pipelines — what happens when the schema is wrong? |
| 27 | [BerriAI/litellm](https://github.com/BerriAI/litellm) | ~17k | Universal LLM proxy — a single abstraction layer routing secrets and prompts to every major provider. |
| 28 | [letta-ai/letta](https://github.com/letta-ai/letta) | ~14k | Stateful memory agents — persistent state is persistent attack surface. |
| 29 | [composiohq/composio](https://github.com/composiohq/composio) | ~12k | Tool-use substrate for agents — the integration layer that touches OAuth tokens, APIs, and filesystems. |
| 30 | [e2b-dev/e2b](https://github.com/e2b-dev/e2b) | ~7k | Code execution sandboxes for AI agents — the boundary between the model's suggestion and the host OS. |

---

## Category 02 — LLM Infrastructure & Serving (8)

> *The metal beneath the model. These repos decide whether a prompt becomes a response or a production incident.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 31 | [ggerganov/llama.cpp](https://github.com/ggml-org/llama.cpp) | ~73k | C++ inference at the edge — memory management, no garbage collector, quantization math nobody re-derives. |
| 32 | [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) | ~37k | Distributed training orchestration — the assumptions baked into ZeRO that every large model inherits. |
| 33 | [ray-project/ray](https://github.com/ray-project/ray) | ~35k | Distributed compute substrate — the scheduling primitives beneath half of ML infra. |
| 34 | [openai/triton](https://github.com/triton-lang/triton) | ~14k | GPU kernel compiler — the layer between PyTorch and CUDA that nobody audits because nobody understands it. |
| 35 | [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | ~37k | The backbone of the LMSYS Chatbot Arena — how benchmarks get gamed starts here. |
| 36 | [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | ~8k | Multi-cloud LLM job orchestration — the IAM credentials are the target. |
| 37 | [guidance-ai/guidance](https://github.com/guidance-ai/guidance) | ~19k | Structured generation control — constrained decoding as a new attack surface category. |
| 38 | [unslothai/unsloth](https://github.com/unslothai/unsloth) | ~25k | Fine-tuning acceleration — the assumption that the dataset is clean is load-bearing. |

---

## Category 03 — Security: Offensive (5)

> *Five more tools that made offense cheap. The democratization of capability is a forensic event.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 39 | [bettercap/bettercap](https://github.com/bettercap/bettercap) | ~17k | Network attack Swiss Army knife — what the codebase reveals about the author's threat model. |
| 40 | [tcpdump/tcpdump](https://github.com/the-tcpdump-group/tcpdump) | ~2.5k | 40 years of packet parsing — the CVE history is a geological record of assumptions. |
| 41 | [gentilkiwi/mimikatz](https://github.com/gentilkiwi/mimikatz) | ~19k | The credential extractor that redefined red teaming — every Windows security assumption in one binary. |
| 42 | [pwndbg/pwndbg](https://github.com/pwndbg/pwndbg) | ~8k | Exploit development environment — the tools that write the exploits have their own attack surface. |
| 43 | [hashcat/hashcat](https://github.com/hashcat/hashcat) | ~22k | Password recovery at GPU scale — the assumptions about entropy that the codebase makes explicit. |

---

## Category 04 — Security: Defensive (5)

> *The blue team's substrate. The tools that are supposed to catch everything.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 44 | [hashicorp/vault](https://github.com/hashicorp/vault) | ~31k | The secrets manager that holds the keys to every other system — its own key management assumptions are the confession. |
| 45 | [getsentry/sentry](https://github.com/getsentry/sentry) | ~39k | Error monitoring at scale — the irony of a system that catches other systems' errors having its own. |
| 46 | [falcosecurity/falco](https://github.com/falcosecurity/falco) | ~7k | Runtime security via eBPF — the kernel observer that can itself be observed. |
| 47 | [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | ~24k | Vulnerability scanning — the scanner's own dependency chain is the attack vector. |
| 48 | [openssl/openssl](https://github.com/openssl/openssl) | ~25k | The cryptographic substrate of the internet — Heartbleed is the ghost that never leaves this repo. |

---

## Category 05 — Databases & Storage (8)

> *Where the data actually lives. The graveyard of every access control assumption.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 49 | [redis/redis](https://github.com/redis/redis) | ~67k | In-memory by design, persistent by accident — the gap between intended and actual durability guarantees. |
| 50 | [postgres/postgres](https://github.com/postgres/postgres) | ~16k | 35 years of SQL — the execution planner's assumptions are load-bearing for every ORM built on top. |
| 51 | [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) | ~30k | Distributed SQL with serializable isolation claims — the CAP theorem confession is always in the edge cases. |
| 52 | [clickhouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | ~38k | Columnar analytics at scale — the performance claims are the attack surface. |
| 53 | [qdrant/qdrant](https://github.com/qdrant/qdrant) | ~21k | Vector database — the HNSW index approximation assumptions every RAG system inherits. |
| 54 | [chroma-core/chroma](https://github.com/chroma-core/chroma) | ~16k | The default vector DB for LangChain demos becoming production systems — default configs as permanent state. |
| 55 | [apache/cassandra](https://github.com/apache/cassandra) | ~8.5k | Eventual consistency by design — the "eventually" is the ghost in every distributed system built on it. |
| 56 | [milvus-io/milvus](https://github.com/milvus-io/milvus) | ~32k | Enterprise vector DB — the dependency chain between Go, Python, and C++ is the fault line. |

---

## Category 06 — Developer Toolchain (8)

> *The tools that build the tools that build the internet. Meta-layer forensics.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 57 | [microsoft/TypeScript](https://github.com/microsoft/TypeScript) | ~101k | The type system that 40% of npm depends on — what the compiler assumes about soundness. |
| 58 | [vitejs/vite](https://github.com/vitejs/vite) | ~68k | The build tool that replaced webpack by being fast — speed and correctness are in tension, and the debt is in Rollup interop. |
| 59 | [oven-sh/bun](https://github.com/oven-sh/bun) | ~74k | JavaScript runtime rewritten in Zig — compatibility claims vs. substrate reality. |
| 60 | [denoland/deno](https://github.com/denoland/deno) | ~100k | Node's security model, inverted — the permission system is the thesis, the escape hatches are the confession. |
| 61 | [webpack/webpack](https://github.com/webpack/webpack) | ~65k | 10 years of bundler assumptions — the module resolution logic is a fossil record. |
| 62 | [rust-lang/rust](https://github.com/rust-lang/rust) | ~99k | Memory safety via ownership — the unsafe blocks are the geological record of where the model breaks down. |
| 63 | [llvm/llvm-project](https://github.com/llvm/llvm-project) | ~29k | The compiler that compiles the compilers — IR optimizations as a source of undefined behavior archaeology. |
| 64 | [docker/buildx](https://github.com/docker/buildx) | ~3.5k | Multi-platform build orchestration — the cache poisoning surface nobody thinks about. |

---

## Category 07 — Web Frontend (7)

> *The browser-facing layer. Where billions of users meet billions of lines of assumption.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 65 | [vuejs/core](https://github.com/vuejs/core) | ~47k | Reactivity via Proxy — the difference between the mental model and the actual scheduler is the bug report backlog. |
| 66 | [sveltejs/svelte](https://github.com/sveltejs/svelte) | ~80k | Compile-time reactivity — the compiler output is what ships, and most developers never read it. |
| 67 | [angular/angular](https://github.com/angular/angular) | ~96k | Zone.js as the change detection substrate — the performance assumptions baked into enterprise Angular apps. |
| 68 | [trpc/trpc](https://github.com/trpc/trpc) | ~35k | Type-safe APIs — the gap between TypeScript types and runtime validation. |
| 69 | [prisma/prisma](https://github.com/prisma/prisma) | ~40k | ORM that generates SQL — the query planner does not know what Prisma promised. |
| 70 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | ~78k | Copy-paste component library — the trust model is "you own the code," which means you own the debt. |
| 71 | [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | ~84k | Utility-first CSS — the PostCSS plugin chain is the actual execution environment nobody reads. |

---

## Category 08 — Blockchain & Crypto (7)

> *Immutable systems where the ghost cannot be patched. The confession is permanent.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 72 | [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) | ~47k | The reference EVM implementation — every EIP's assumption becomes consensus law. |
| 73 | [bitcoin/bitcoin](https://github.com/bitcoin/bitcoin) | ~80k | 15 years of hardened C++ — the script interpreter assumptions are load-bearing for $1T of value. |
| 74 | [solana-labs/solana](https://github.com/solana-labs/solana) | ~13k | High-throughput consensus — the performance is the design, and the design is the attack surface. |
| 75 | [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) | ~25k | The standard library that every smart contract inherits — one assumption flaw, infinite blast radius. |
| 76 | [Uniswap/v3-core](https://github.com/Uniswap/v3-core) | ~4.5k | Concentrated liquidity AMM — the math is correct, the oracle manipulation assumptions are not. |
| 77 | [foundry-rs/foundry](https://github.com/foundry-rs/foundry) | ~8k | Smart contract testing framework — the testing tool's assumptions become the contract's untested assumptions. |
| 78 | [gakonst/ethers-rs](https://github.com/alloy-rs/alloy) | ~3k | Rust Ethereum primitives — the type system encoding of EVM semantics vs. actual EVM behavior. |

---

## Category 09 — Communication & Protocol (5)

> *The channels. Where data moves and identity claims propagate.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 79 | [matrix-org/synapse](https://github.com/matrix-org/synapse) | ~12k | Federated messaging — the trust model between homeservers is the attack surface for the entire network. |
| 80 | [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) | ~26k | The gold standard for encrypted messaging — the gap between protocol correctness and implementation correctness. |
| 81 | [nicowillis/ntfy](https://github.com/binwiederhier/ntfy) | ~19k | Push notification server self-hosted — authentication as an afterthought in the default config. |
| 82 | [caddyserver/caddy](https://github.com/caddyserver/caddy) | ~58k | Automatic HTTPS web server — the certificate management assumptions, the JSON config attack surface. |
| 83 | [cloudflare/quiche](https://github.com/cloudflare/quiche) | ~9.5k | QUIC and HTTP/3 implementation — the protocol that replaces TCP has its own assumption inventory. |

---

## Category 10 — Systems & Low-Level (7)

> *The bedrock. The assumptions here propagate upward through every layer.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 84 | [torvalds/linux](https://github.com/torvalds/linux) | ~185k | The kernel — not the whole thing, but the eBPF verifier and the scheduler. Two subsystems that touch everything. |
| 85 | [moby/moby](https://github.com/moby/moby) | ~68k | Docker's engine — the namespace and cgroup isolation primitives that container security rests on. |
| 86 | [containerd/containerd](https://github.com/containerd/containerd) | ~17k | The container runtime beneath Kubernetes — the OCI spec assumptions made concrete. |
| 87 | [cilium/cilium](https://github.com/cilium/cilium) | ~20k | eBPF-based networking — kernel-level packet processing with no garbage collector and all of the consequences. |
| 88 | [WebAssembly/wabt](https://github.com/WebAssembly/wabt) | ~7k | The WebAssembly binary toolkit — the spec interpreter is what browser implementations diverge from. |
| 89 | [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) | ~15k | Production Wasm runtime — the sandbox escape surface is the spec gap. |
| 90 | [openzfs/zfs](https://github.com/openzfs/zfs) | ~10k | Copy-on-write filesystem — the data integrity guarantees and the edge cases where they don't hold. |

---

## Category 11 — Data & Analytics (5)

> *The pipelines. Where raw events become decisions. The transformation is the vulnerability.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 91 | [apache/kafka](https://github.com/apache/kafka) | ~28k | Distributed log — the offset management assumptions every stream processing system inherits. |
| 92 | [apache/airflow](https://github.com/apache/airflow) | ~37k | Workflow orchestration — DAG serialization, the pickle attack surface, the default credential storage. |
| 93 | [apache/spark](https://github.com/apache/spark) | ~39k | Distributed data processing — the RDD lineage assumptions and what happens when they're wrong at scale. |
| 94 | [dbt-labs/dbt-core](https://github.com/dbt-labs/dbt-core) | ~10k | SQL transformation layer — the assumption that your warehouse's SQL dialect matches dbt's model. |
| 95 | [great-expectations/great_expectations](https://github.com/great-expectations/great_expectations) | ~10k | Data quality validation — the system that validates data has no external validator. |

---

## Category 12 — Cloud Native & GitOps (5)

> *The operators. The systems that manage systems. Recursive attack surfaces.*

| # | Repo | Stars | Forensic Angle |
|---|------|-------|----------------|
| 96 | [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | ~18k | GitOps delivery — git as the source of truth, and the RBAC model that wraps it. |
| 97 | [fluxcd/flux2](https://github.com/fluxcd/flux2) | ~6.5k | Continuous delivery operator — the reconciliation loop assumptions and what happens when state diverges. |
| 98 | [istio/istio](https://github.com/istio/istio) | ~36k | Service mesh — mTLS as an assumption, the Envoy sidecar as the enforcement point, the config as the attack surface. |
| 99 | [open-telemetry/opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) | ~4.5k | Observability pipeline — the system that sees everything is itself invisible to most security reviews. |
| 100 | [prometheus/prometheus](https://github.com/prometheus/prometheus) | ~55k | The monitoring system that became the default — the TSDB compaction assumptions, the scrape model's trust boundary. |

---

---

*The forensic lens does not change with the target. Every codebase has a confession. The only variable is how long it takes to ask the right question.*
