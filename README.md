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
| [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | 59,500 | [→ reports/security/nuclei.md](reports/security/nuclei.md) |
| [rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) | 59,000 | [→ reports/security/metasploit-framework.md](reports/security/metasploit-framework.md) |
| [nmap/nmap](https://github.com/nmap/nmap) | 58,500 | [→ reports/security/nmap.md](reports/security/nmap.md) |
| [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap) | 58,000 | [→ reports/security/sqlmap.md](reports/security/sqlmap.md) |
| [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | 51,000 | [→ reports/security/ghidra.md](reports/security/ghidra.md) |

### AI / ML Infrastructure

> *The frameworks training the world's models. What trains the framework?*

| Repo | Stars | Report |
|------|-------|--------|
| [pytorch/pytorch](https://github.com/pytorch/pytorch) | 49,500 | [→ reports/ai-ml/pytorch.md](reports/ai-ml/pytorch.md) |
| [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) | 49,000 | [→ reports/ai-ml/tensorflow.md](reports/ai-ml/tensorflow.md) |
| [huggingface/transformers](https://github.com/huggingface/transformers) | 48,500 | [→ reports/ai-ml/transformers.md](reports/ai-ml/transformers.md) |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 41,500 | [→ reports/ai-ml/langchain.md](reports/ai-ml/langchain.md) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 42,000 | [→ reports/ai-ml/vllm.md](reports/ai-ml/vllm.md) |

### Infrastructure

> *The substrate beneath the cloud. Invisible until it isn't.*

| Repo | Stars | Report |
|------|-------|--------|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | 29,500 | [→ reports/infrastructure/kubernetes.md](reports/infrastructure/kubernetes.md) |
| [hashicorp/terraform](https://github.com/hashicorp/terraform) | 28,500 | [→ reports/infrastructure/terraform.md](reports/infrastructure/terraform.md) |
| [grafana/grafana](https://github.com/grafana/grafana) | 27,000 | [→ reports/infrastructure/grafana.md](reports/infrastructure/grafana.md) |
| [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 26,500 | [→ reports/infrastructure/elasticsearch.md](reports/infrastructure/elasticsearch.md) |

### NPM / Web

> *The dependencies nobody audits because everyone depends on them.*

| Repo | Stars | Report |
|------|-------|--------|
| [facebook/react](https://github.com/facebook/react) | 39,000 | [→ reports/npm-web/react.md](reports/npm-web/react.md) |
| [axios/axios](https://github.com/axios/axios) | 34,000 | [→ reports/npm-web/axios.md](reports/npm-web/axios.md) |
| [vercel/next.js](https://github.com/vercel/next.js) | 18,000 | [→ reports/npm-web/nextjs.md](reports/npm-web/nextjs.md) |

### Trending / AI Agents

> *The repos shipping fastest. Speed and rigor are inversely correlated — until they aren't.*

| Repo | Stars | Report |
|------|-------|--------|
| [ollama/ollama](https://github.com/ollama/ollama) | 13,500 | [→ reports/trending/ollama.md](reports/trending/ollama.md) |
| [supabase/supabase](https://github.com/supabase/supabase) | 12,000 | [→ reports/trending/supabase.md](reports/trending/supabase.md) |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 14,500 | [→ reports/trending/autogpt.md](reports/trending/autogpt.md) |

---

## Report Anatomy <kbd>REDACTED</kbd>

Each report opens with the verdict. One sentence. The complete payload.

Everything after it is evidence.

```
███████████ ███ ████████ █████ ███ ███████. ███ ████████. ████████ ███████████ ███████ ██ █████████.
███████████ ███ ████████ █████ ███ ███████. ███ ████████. ████████ ███████████ ███████ ██ █████████.
███████████ ███ ████████ █████ ███ ███████. ███ ████████. ████████ ███████████ ███████ ██ █████████.
███████████ ███ ████████ █████ ███ ███████. ███ ████████. ████████ ███████████ ███████ ██ █████████.
███████████ ███ ████████ █████ ███ ███████. ███ ████████. ████████ ███████████ ███████ ██ █████████.
```

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
