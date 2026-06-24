<!-- ════════════════════════════════════════════════════════════════════════
     BANNER — the one signature element. Your NASA photo (kept in the repo as
     nasa-Q1p7bh3SHj8-unsplash.jpg), cropped to a slim letterbox and compressed
     to WebP on the fly via images.weserv.nl (862 KB source → ~60 KB delivered).
     The original file is untouched and remains the single source.
       • shift the crop: a=attention → a=top / a=middle / a=bottom
       • if it ever fails to load: change "url=ssl:raw" to "url=raw"
═════════════════════════════════════════════════════════════════════════════ -->
<img alt="Earth at night, photographed from orbit"
     src="https://images.weserv.nl/?url=ssl:raw.githubusercontent.com/Rajneesh180/Rajneesh180/main/nasa-Q1p7bh3SHj8-unsplash.jpg&w=1500&h=300&fit=cover&a=attention&output=webp&q=82"
     width="100%"/>

# Rajneesh Chaudhary

**Backend & Distributed Systems Engineer** &nbsp;·&nbsp; CNCF contributor — Kubernetes, OpenTelemetry, Jaeger

Final-year IT @ ABV-IIITM Gwalior. I build Kubernetes-native services and cloud-native observability tooling — the kind of infrastructure that has to hold up in production.

[![Open to roles](https://img.shields.io/badge/Open%20to-SDE%20%2F%20Infra%20Roles%202026-2ea44f?style=flat-square)](#)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajneesh-chaudhary-37632a1b7)
&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-0d1117?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/rehsaan90)
&nbsp;
[![Medium](https://img.shields.io/badge/Medium-0d1117?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@rajneeshrehsaan48)

---

## Focus

- **Distributed systems & infra** — Kubernetes-native services, sandboxed execution, throughput under load
- **Cloud-native observability** — tracing internals and collector pipelines (OpenTelemetry, Jaeger)
- **GenAI systems** — retrieval and RAG pipelines built to real latency budgets

## Open Source — CNCF

Merged contributions to Kubernetes, OpenTelemetry, and Jaeger — work that ships in production across cloud-native deployments.

| Project | PR | Contribution |
|---|---|---|
| **Kubernetes** | [`#137398`](https://github.com/kubernetes/kubernetes/pull/137398) | Goroutine hot-loop fix in `client-go` `StartEventWatcher` — merged into **v1.36** |
| **Kubernetes** | [`#137999`](https://github.com/kubernetes/kubernetes/pull/137999) | Fix for kubelet cgroup-resize nil-pointer panic |
| **OpenTelemetry** | [`#46506`](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/46506) | Parse-time AST constant folding for pure OTTL functions — removes redundant per-datapoint evaluation in the collector hot path |
| **Jaeger** | _multiple_ | MaxTraceSize OOM safeguard · API v3 limit/attribute filtering · OTTL delete-matching-values |

<!-- TODO — Jaeger: replace "multiple" with the specific merged PR links, same as
     the rows above. Linked, merged PRs read as far more credible, and it lets a
     reviewer verify each one. Drop anything that was closed without merging. -->

## Experience

**SDE Intern — AlgoUniversity (YC S21)** &nbsp;·&nbsp; May–Jul 2025 &nbsp;·&nbsp; Hyderabad
- Built a cloud-native online judge on Kubernetes serving 50+ daily users
- Redis Streams evaluation pipeline — **5× throughput** over the sequential baseline
- Per-submission sandboxing with Docker + cgroups + SECCOMP; JWT / OAuth 2.0 / RBAC auth; zero-downtime CI/CD on AWS

**McKinsey Forward — Leadership Fellow** &nbsp;·&nbsp; Aug 2025 – Present &nbsp;·&nbsp; Remote
- Structured problem-solving (MECE, hypothesis-driven) applied to ambiguous engineering decisions, with Python dashboards and automation

## Selected Work

**GitLab Knowledge AI** — [repository](https://github.com/Rajneesh180/gitlab-knowledge-ai)
Production RAG over the GitLab Handbook. Dual-path **FAISS + BM25** retrieval with reciprocal rank fusion, **Llama 3.3 70B** via Groq, heading-aware chunking, and sub-200 ms retrieval with no external calls in the search path.

**API Health Monitor** — [repository](https://github.com/Rajneesh180/api-health-monitor)
Concurrent endpoint health-checker in pure Go. Retry logic, timeout propagation, and bounded-latency execution under load — zero external dependencies.

**Premium Online Judge** — [repository](https://github.com/Rajneesh180/Premium-Online-Judge)
Full-stack competitive-programming platform. Kubernetes-native, with a Redis Streams evaluation pipeline and Docker + cgroups + SECCOMP sandboxing; live contests, leaderboards, and a rating system.

## Tech

| | |
|---|---|
| **Languages** | Go · Python · C++ · TypeScript |
| **Infra & Cloud** | Kubernetes · Docker · Terraform · AWS · Linux |
| **Backend & Data** | Node.js · FastAPI · Redis · PostgreSQL · MongoDB |
| **Observability** | OpenTelemetry · Jaeger · Grafana |

## Competitive Programming

LeetCode **Knight**, 1200+ problems solved. Live profile below.

<img src="https://leetcard.jacoblin.cool/rehsaan90?theme=dark&font=JetBrains+Mono&ext=heatmap" width="460"/>

Flipkart GRiD — cleared Round 3 &nbsp;·&nbsp; AlgoUniversity Camp — top 0.5% nationally

## Thesis — Deep RL for UAV-Assisted IoT Data Collection

*UAV-Assisted Obstacle-Aware Data Collection for Resource-Constrained IoT Networks* — Supervisor: Dr. Ankur Jaiswal, ABV-IIITM Gwalior

- **Policy** — PPO agent (continuous control) over a D3QN baseline; state encodes UAV pose, residual energy, obstacle proximity, and rendezvous-visit vector
- **Coverage** — greedy dominating-set selection compresses 20 rendezvous points to 7 (**~65%**) at full node coverage
- **Routing** — visibility-graph planning yields collision-free paths (~2566 m, ~9.2% battery) around cuboid obstacles

<!-- TODO — only you can confirm these two:
     1) If PPO + set-attention is your FINAL model, name it and lead with the
        headline metric (e.g. mean mission score 0.725 across 240 rollouts).
        A concrete number beats "agent for adaptive optimisation".
     2) Verify obstacle heights vs UAV cruise altitude are consistent in the
        final sim — "obstacle-aware" only holds if obstacles intersect the
        flight path. I used neutral wording so nothing here contradicts itself;
        add exact heights once confirmed. -->

## GitHub Activity

<!-- Live — these refresh from your profile on every page load.
     Note: github-readme-stats is the shared public instance and occasionally
     rate-limits; count_private only counts private commits if you self-host it
     with a PAT (a short Vercel deploy). -->

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Rajneesh180&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rajneesh180&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Rajneesh180&bg_color=0d1117&color=00B4D8&line=0e75b6&point=ffffff&area=true&hide_border=true&custom_title=Contribution%20Activity" />

## Writing

I write on [Medium](https://medium.com/@rajneeshrehsaan48) about the engineering work and projects I'm exploring.

<a href="https://medium.com/@rajneeshrehsaan48">
  <img src="https://github-readme-medium-recent-article.vercel.app/medium/@rajneeshrehsaan48/0" width="100%"/>
</a>

<!-- This widget surfaces your MOST RECENT post. Your published mix is broad
     (project writeups alongside general essays), so I kept the framing as
     "Writing" rather than claiming a specific technical-topic list. -->

---

<sub><i>If it scales, it succeeds — build with impact, not just intent.</i></sub>
