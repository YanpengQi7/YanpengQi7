<h1 align="center">Hi, I'm Yanpeng 👋</h1>

<p align="center">
  <b>SDE building production AI systems — RAG pipelines, agent workflows, and full-stack products.</b><br/>
  <b>Eval-first: I measure my AI systems, then I measure the evals themselves.</b><br/>
  <sub>Based in Greater Seattle · Turning ambiguous problems into reliable, <i>verified</i> systems — and publishing what the numbers actually say.</sub>
</p>

<p align="center">
  <a href="https://yanpengqi.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-yanpengqi.com-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://yanpengqi.com/blog"><img alt="Blog" src="https://img.shields.io/badge/Blog-Read-1F6FEB?style=for-the-badge&logo=readthedocs&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/yanpeng-qi"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/YanpengQi7/awesome-ai-application-engineer"><img alt="AI Engineer Roadmap" src="https://img.shields.io/badge/AI%20Engineer-Roadmap-6E56CF?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://yanpengqi.com/cv"><img alt="CV" src="https://img.shields.io/badge/CV-View-2EA44F?style=for-the-badge&logo=readdotcv&logoColor=white"></a>
</p>

---

### 🛠️ Tech I reach for

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-000?style=flat-square&logo=vercel&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-6E56CF?style=flat-square"/>
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

---

### 🚀 Featured Project

#### 🛡️ [AI Reliability Copilot](https://github.com/YanpengQi7/ai-reliability-copilot) &nbsp; [![Demo](https://img.shields.io/badge/Live-Demo-success?style=flat-square)](https://ai-reliability-copilot.vercel.app)

Turns a production incident — alerts, logs, on-call notes — into a structured **9-section reliability report** (severity, ranked root-cause hypotheses, mitigation with rollback, postmortem). Ships as a web app, an **MCP server**, and a **CLI**.

But the product isn't the point — **the eval pipeline is**: every prompt change is scored by an LLM-as-judge across a fixed scenario suite, with repeats and error bars. I treat my own AI like a system under test, and I publish what the numbers say even when it's unflattering:

> 📉 **Found that prompt v1 / v2 / v3 differences were statistical noise**, not improvement — the within-cell std was larger than every between-version delta. Caught myself before shipping a "+0.16 quality win" that was sampling noise.
>
> 🔬 **Cross-checked the judge against an independent model** (DeepSeek-judges-DeepSeek vs. Claude Sonnet 4.6). The same-family judge inflates overall scores by **+0.24 / 5 (~5%)** — concentrated in the *soft* dimensions (actionability, completeness), **zero on safety** (90% exact agreement). I had *guessed* 10–20%; measuring showed I'd overestimated.

`Next.js 16` · `TypeScript` · `Vercel AI SDK` · `DeepSeek` · `Supabase / pgvector` · `MCP` · `Cross-model eval`

---

### 🧰 More Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 [mcp-recall](https://github.com/YanpengQi7/mcp-recall)

Local-first **structured memory** for Claude Code over MCP — hybrid retrieval (vector KNN + BM25 fused with **Reciprocal Rank Fusion**), local embeddings, recency-decay ranking, dedup guard. No API keys; nothing leaves the machine.

`MCP` · `sqlite-vec` · `Hybrid Retrieval` · `Local Embeddings`

</td>
<td width="50%" valign="top">

#### 📚 [Awesome AI Application Engineer](https://github.com/YanpengQi7/awesome-ai-application-engineer)

A practical AI application engineering roadmap — LLM basics → Prompt, RAG, Agent, MCP, evaluation, production — with hands-on tutorials, checklists, templates, and real RAG bad cases.

`LLM` · `RAG` · `Agent` · `MCP` · `Evaluation` · `Production`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔍 [SRE Investigator](https://github.com/YanpengQi7/sre-investigator)

MCP-agnostic SRE skill for Claude Code — discovers whatever MCP tools are exposed, classifies them by capability, queries read-only evidence, and **keeps evidence separate from inference**.

`Claude Code Skill` · `MCP` · `Prompt design`

</td>
<td width="50%" valign="top">

#### 🗺️ [ServiceAtlas](https://github.com/YanpengQi7/serviceatlas)

AI SRE knowledge compiler — turns a codebase into source-grounded runbooks, dependency / blast-radius maps, observability-gap reports, and PR reliability-impact analysis.

`Python` · `LLM` · `Reliability` · `Runbooks`

</td>
</tr>
</table>

---

### 📊 GitHub Stats

<p align="center">
  <img alt="GitHub metrics" src="https://raw.githubusercontent.com/YanpengQi7/YanpengQi7/main/github-metrics.svg"/>
</p>

<sub align="center">Self-hosted via <a href="https://github.com/lowlighter/metrics">lowlighter/metrics</a> — refreshed daily by GitHub Actions, served straight from this repo (no rate-limited third-party instance).</sub>

---

### ✍️ Recent Writing

- 📖 [RAG quality is mostly retrieval design](https://yanpengqi.com/blog/rag-quality-is-mostly-retrieval-design)
- 📖 [Agent systems need evals before they need more tools](https://yanpengqi.com/blog/agent-systems-need-evals-before-they-need-more-tools)
- 📖 [Model routing is a product decision, not just an optimization](https://yanpengqi.com/blog/model-routing-is-a-product-decision-not-just-an-optimization)
- 📖 [Capacity planning for AI products starts with traffic shape](https://yanpengqi.com/blog/capacity-planning-for-ai-products-starts-with-traffic-shape)

---

### 🌱 Now

- Building **eval-first AI tooling** — repeatable scenarios > manual inspection, and **validating the judges themselves** (cross-model bias measurement)
- Maintaining **Awesome AI Application Engineer** — a practical roadmap for Chinese developers learning production LLM apps
- Exploring **MCP** as a substrate for SRE / on-call workflows
- Open to chat about: production LLM systems, RAG quality, agent evals, MCP, AI infra

📬 Reach me at **[yanpengqi.com](https://yanpengqi.com)** · [LinkedIn](https://www.linkedin.com/in/yanpeng-qi)

<sub><i>"AI systems should be grounded in real data, observable when the model is wrong, and evaluated with repeatable scenarios."</i></sub>
