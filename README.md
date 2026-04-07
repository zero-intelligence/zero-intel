```diff
+ ███████╗███████╗██████╗  ██████╗
+ ╚══███╔╝██╔════╝██╔══██╗██╔═══██╗
+   ███╔╝ █████╗  ██████╔╝██║   ██║
+  ███╔╝  ██╔══╝  ██╔══██╗██║   ██║
+ ███████╗███████╗██║  ██║╚██████╔╝
+ ╚══════╝╚══════╝╚═╝  ╚═╝ ╚═════╝
+ ██╗███╗   ██╗████████╗███████╗██╗
+ ██║████╗  ██║╚══██╔══╝██╔════╝██║
+ ██║██╔██╗ ██║   ██║   █████╗  ██║
+ ██║██║╚██╗██║   ██║   ██╔══╝  ██║
+ ██║██║ ╚████║   ██║   ███████╗███████╗
+ ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚══════╝
+ 
```


**Every codebase has a confession. Most people never ask it the right question.**

---

This is not a security audit. Security audits tell you what is broken.

This tells you *why* it was always going to break.

The ghost is never in the line that fails. The ghost is in the assumption that was never questioned.

---

## The 20 Subjects

Ranked by strategic value, architectural complexity, and the gap between reputation and substrate.

### Security Tools

> *We turned the forensic lens on the forensic tools.*

| Repo | Stars | Report |
|------|-------|--------|
| [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | 27,725 | [→ reports/security/nuclei.md](reports/security/nuclei.md) |
| [rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) | 37,835 | [→ reports/security/metasploit-framework.md](reports/security/metasploit-framework.md) |
| [nmap/nmap](https://github.com/nmap/nmap) | 12,636 | [→ reports/security/nmap.md](reports/security/nmap.md) |
| [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap) | 36,985 | [→ reports/security/sqlmap.md](reports/security/sqlmap.md) |
| [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | 66,563 | [→ reports/security/ghidra.md](reports/security/ghidra.md) |

### AI / ML Infrastructure

> *The frameworks training the world's models. What trains the framework?*

| Repo | Stars | Report |
|------|-------|--------|
| [pytorch/pytorch](https://github.com/pytorch/pytorch) | 98,800 | [→ reports/ai-ml/pytorch.md](reports/ai-ml/pytorch.md) |
| [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) | 194,457 | [→ reports/ai-ml/tensorflow.md](reports/ai-ml/tensorflow.md) |
| [huggingface/transformers](https://github.com/huggingface/transformers) | 158,691 | [→ reports/ai-ml/transformers.md](reports/ai-ml/transformers.md) |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 132,000 | [→ reports/ai-ml/langchain.md](reports/ai-ml/langchain.md) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 75,004 | [→ reports/ai-ml/vllm.md](reports/ai-ml/vllm.md) |

### Infrastructure

> *The substrate beneath the cloud. Invisible until it isn't.*

| Repo | Stars | Report |
|------|-------|--------|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | 121,487 | [→ reports/infrastructure/kubernetes.md](reports/infrastructure/kubernetes.md) |
| [hashicorp/terraform](https://github.com/hashicorp/terraform) | 48,000 | [→ reports/infrastructure/terraform.md](reports/infrastructure/terraform.md) |
| [grafana/grafana](https://github.com/grafana/grafana) | 73,000 | [→ reports/infrastructure/grafana.md](reports/infrastructure/grafana.md) |
| [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 76,405 | [→ reports/infrastructure/elasticsearch.md](reports/infrastructure/elasticsearch.md) |

### NPM / Web

> *The dependencies nobody audits because everyone depends on them.*

| Repo | Stars | Report |
|------|-------|--------|
| [facebook/react](https://github.com/facebook/react) | 220,000 | [→ reports/npm-web/react.md](reports/npm-web/react.md) |
| [axios/axios](https://github.com/axios/axios) | 105,000 | [→ reports/npm-web/axios.md](reports/npm-web/axios.md) |
| [vercel/next.js](https://github.com/vercel/next.js) | 138,582 | [→ reports/npm-web/nextjs.md](reports/npm-web/nextjs.md) |

### Trending / AI Agents

> *The repos shipping fastest. Speed and rigor are inversely correlated — until they aren't.*

| Repo | Stars | Report |
|------|-------|--------|
| [ollama/ollama](https://github.com/ollama/ollama) | 166,779 | [→ reports/trending/ollama.md](reports/trending/ollama.md) |
| [supabase/supabase](https://github.com/supabase/supabase) | 100,075 | [→ reports/trending/supabase.md](reports/trending/supabase.md) |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 183,064 | [→ reports/trending/autogpt.md](reports/trending/autogpt.md) |

---

## Report Anatomy

```
 ██████╗ ██╗      █████╗ ███████╗███████╗██╗███████╗██╗███████╗██████╗
██╔════╝ ██║     ██╔══██╗██╔════╝██╔════╝██║██╔════╝██║██╔════╝██╔══██╗
██║      ██║     ███████║███████╗███████╗██║█████╗  ██║█████╗  ██║  ██║
██║      ██║     ██╔══██║╚════██║╚════██║██║██╔══╝  ██║██╔══╝  ██║  ██║
╚██████╗ ███████╗██║  ██║███████║███████║██║██║     ██║███████╗██████╔╝
 ╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═╝╚═╝     ╚═╝╚══════╝╚═════╝
```

The report structure is not published.

The methodology is not disclosed.

What runs beneath the surface has been deliberately kept off the record — not to obscure the findings, but to protect the integrity of the analysis. A known instrument can be played.

What we can say:

```
█████ ███████ ██████ ████████ ██ ████ ████████ ██████ ███████ ████ ██████████.
████████ ██ ███ ████████ ████ ██████ ███████ ██████████ ████ ██████ ███ ████.
██████ ███ ████ ███ █████████ ██████████ ████ ███████████ ████████ ████ █████.
███ ████████ ████ ██████ ████ ███ ██████ ████████████ ████ ██████████ ███████.
```

Every report opens with the verdict. One sentence. The complete payload.

Everything after it is evidence.

The ghost is never in the line that fails.
It is in the assumption that was never questioned.

---

> **What you are reading is approximately 1% of the full report.**
>
> The published version is a heavily redacted surface — architectural observations, structural patterns, and the ghost-in-the-commits made safe for public disclosure. Zero-days, exploit chains, active attack paths, and credential archaeology are withheld for security reasons and delivered exclusively to verified owners via commissioned reports.
>
> Reports are generated using large language models as the synthesis layer. The raw signals feeding that synthesis are not disclosed.
>
> The redaction is not a limitation. It is the product.

---

## Submit a Repo for Analysis

The 20 subjects above were chosen by us. The [next 80 are already targeted](TARGETS.md).

But the pipeline is not closed. If you have a target in mind — a codebase you depend on, one you're about to acquire, one you built and need an honest verdict on — submit it.

| | Free | Commission |
|--|------|------------|
| **Repo type** | Public only | Public or private |
| **Report depth** | Basic — verdict, git archaeology, structural vulnerabilities | Full — zero-days, exploit chains, complete attack path mapping |
| **Who gets it** | Published here, publicly | Delivered privately to you only |
| **Delivery** | Within 72 hours of approval | Within 48 hours of payment |
| **Price** | Free | $10,000 USD |
| **Vetting** | All requests reviewed — not every submission accepted | Ownership verified before payment is requested |

→ **[Request a free analysis](https://github.com/zero-intelligence/zero-intel/issues/new?template=01-request-public-repo.yml)**

→ **[Commission a full report ($10,000)](https://github.com/zero-intelligence/zero-intel/issues/new?template=02-request-private-repo.yml)**

→ **[Nominate a target for the pipeline](https://github.com/zero-intelligence/zero-intel/issues/new?template=04-nominate-a-target.yml)**

→ **[Challenge a published verdict](https://github.com/zero-intelligence/zero-intel/issues/new?template=03-challenge-a-verdict.yml)**

---

## What This Is Not

Not a bug bounty operation. Not a responsible disclosure repo. Not a list of CVE IDs.

A CVE gets patched. An architectural assumption gets inherited by the next generation of the codebase.

The patch fixes the symptom. We're measuring the condition.

---

## Zero Intelligence

Independent research on intelligence as a structural property of any system.

Not a domain. Not a platform. The substrate beneath both.

[zero-intelligence](https://github.com/zero-intelligence)

---

*Reports are live documents. Each analysis reflects the state of the repository at time of scan. Git history is permanent — the ghost never leaves.*
