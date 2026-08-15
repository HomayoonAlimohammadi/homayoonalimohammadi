<div align="center">

<h1>Homayoon Alimohammadi</h1>

<a href="https://homayoon.dev">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=00ADD8&center=true&vCenter=true&width=720&height=45&lines=Senior+Backend+Engineer;Go+%C2%B7+Distributed+Systems+%C2%B7+Kubernetes;Architecting+k8sd+%40+Canonical+Kubernetes;10K%2B+node+clusters+%C2%B7+50M%2B+messages%2Fday" alt="Senior Backend Engineer — Go, Distributed Systems, Kubernetes" />
</a>

<p>
  <a href="https://canonical.com/"><img src="https://img.shields.io/badge/Canonical-Kubernetes_Team-E95420?style=flat-square&labelColor=0D1117&logo=ubuntu&logoColor=E95420" alt="Canonical" /></a>
  <img src="https://img.shields.io/badge/Go-5%2B_years-00ADD8?style=flat-square&labelColor=0D1117&logo=go&logoColor=00ADD8" alt="Go" />
  <img src="https://img.shields.io/badge/Dubai-%E2%86%92_Germany-00ADD8?style=flat-square&labelColor=0D1117&logo=googlemaps&logoColor=00ADD8" alt="Relocating to Germany" />
  <a href="https://homayoon.dev"><img src="https://img.shields.io/badge/homayoon.dev-00ADD8?style=flat-square&labelColor=0D1117&logo=firefoxbrowser&logoColor=00ADD8" alt="Website" /></a>
</p>

</div>

---

```yaml
apiVersion: homayoon.dev/v1
kind: Engineer
metadata:
  name: homayoon-alimohammadi
  labels:
    role: senior-backend-engineer
    team: canonical/kubernetes
spec:
  focus:
    - distributed systems that stay correct under load
    - Kubernetes internals, operators, and cluster lifecycle
    - platform work whose users are other engineers
  languages: [go, python, sql, bash]
  currentlyBuilding:
    - k8sd — the clustering daemon behind every Canonical Kubernetes cluster
    - Cluster API bootstrap & control-plane providers (AWS, GCP, MAAS, bare metal)
    - an upgrade controller that converges a cluster from one declarative apply
status:
  location: Dubai, UAE
  relocating: Germany — EU Blue Card eligible
  openTo: senior backend / platform roles across the EU
  phase: Running
```

<h3 align="center">Impact</h3>

<table align="center">
<tr>
  <td align="center" width="200"><h2>10K+</h2><sub><b>nodes</b><br>scale ceiling established for<br>Canonical Kubernetes</sub></td>
  <td align="center" width="200"><h2>50M+</h2><sub><b>messages / day</b><br>event-driven notification<br>platform over Kafka</sub></td>
  <td align="center" width="200"><h2>65M+</h2><sub><b>users</b><br>served by the services<br>I owned at Divar</sub></td>
</tr>
<tr>
  <td align="center"><h2>8K</h2><sub><b>requests / second</b><br>sustained on production<br>Go services</sub></td>
  <td align="center"><h2>99.99%</h2><sub><b>availability SLO</b><br>held through a 4-release<br>zero-downtime redesign</sub></td>
  <td align="center"><h2>60%</h2><sub><b>p99 latency cut</b><br>and 60% less kube-apiserver<br>load at scale</sub></td>
</tr>
</table>

---

### What I'm working on

At **[Canonical](https://canonical.com/)**, on the Kubernetes team, where everything I build ships open source:

- **[k8s-snap](https://github.com/canonical/k8s-snap)** — architected `k8sd`, the on-node clustering daemon exposing a typed REST API for bootstrapping, node enrollment, certificate rotation, and runtime config over dqlite. It is now the single control interface on every Canonical Kubernetes cluster.
- **[cluster-api-k8s](https://github.com/canonical/cluster-api-k8s)** — authored the Cluster API bootstrap and control-plane providers, making provisioning declarative across AWS, GCP, MAAS, and bare metal from one `clusterctl` workflow.
- **[microk8s](https://github.com/canonical/microk8s)** — core contributor. Plus upstream patches in **[grpc/grpc-go](https://github.com/grpc/grpc-go)**.

Before that, four years of high-traffic backend work — most recently at **Divar**, the largest classifieds platform in the region, where I tech-led the redesign of the ad-submission service every listing flows through, and built the notification platform behind 50M+ daily messages.

### Selected open source

| | |
|---|---|
| **[microcni](https://github.com/HomayoonAlimohammadi/microcni)** | A minimal container network interface plugin — CNI from first principles |
| **[k8s-doctor](https://github.com/HomayoonAlimohammadi/k8s-doctor)** | Answers Kubernetes questions from augmented upstream docs, then reproduces issues and verifies fixes on its own managed cluster |
| **[k8s-mcp-server](https://github.com/HomayoonAlimohammadi/k8s-mcp-server)** | MCP server exposing a Kubernetes cluster to LLM agents |
| **[rag-mcp](https://github.com/HomayoonAlimohammadi/rag-mcp)** | MCP server for retrieval over ingested documents and sources |
| **[k8sutils](https://github.com/HomayoonAlimohammadi/k8sutils)** | Node draining utility for safe cluster maintenance |
| **[gosync](https://github.com/HomayoonAlimohammadi/gosync)** | Go synchronization primitives, rebuilt to understand them properly |

### Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=go,python,bash,kubernetes,docker,terraform,linux,git&theme=dark" alt="Go, Python, Bash, Kubernetes, Docker, Terraform, Linux, Git" />
<br>
<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,kafka,grafana,prometheus,aws,gcp&theme=dark" alt="PostgreSQL, Redis, MongoDB, Kafka, Grafana, Prometheus, AWS, GCP" />

<sub>gRPC · REST · GraphQL · Protobuf · etcd · ClickHouse · OpenTelemetry · controller-runtime · Cluster API · pprof · LLM agents & MCP</sub>

</div>

### Writing

I write about Go, distributed systems, and Kubernetes internals — and I've authored 10+ design documents through to production.

<a href="https://homayoon.dev/blog"><img src="https://img.shields.io/badge/Read_the_blog-00ADD8?style=for-the-badge&labelColor=0D1117&logo=rss&logoColor=00ADD8" alt="Blog" /></a>
<a href="https://homayoon.dev/resume"><img src="https://img.shields.io/badge/Resume-0D1117?style=for-the-badge&labelColor=0D1117&logo=readdotcv&logoColor=00ADD8" alt="Resume" /></a>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HomayoonAlimohammadi&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HomayoonAlimohammadi&theme=github" alt="GitHub profile summary" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=HomayoonAlimohammadi&bg_color=00000000&color=C9D1D9&title_color=00ADD8&line=00ADD8&point=00ADD8&area=true&area_color=00ADD8&hide_border=true&radius=8&custom_title=Contributions" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=HomayoonAlimohammadi&bg_color=00000000&color=24292F&title_color=007D9C&line=007D9C&point=007D9C&area=true&area_color=00ADD8&hide_border=true&radius=8&custom_title=Contributions" alt="Contribution activity" width="100%" />
</picture>

<br><br>

<a href="https://homayoon.dev"><img src="https://img.shields.io/badge/Website-00ADD8?style=for-the-badge&labelColor=0D1117&logo=firefoxbrowser&logoColor=00ADD8" alt="Website" /></a>
<a href="https://www.linkedin.com/in/homayoon-alimohammadi/"><img src="https://img.shields.io/badge/LinkedIn-00ADD8?style=for-the-badge&labelColor=0D1117&logo=linkedin&logoColor=00ADD8" alt="LinkedIn" /></a>
<a href="https://x.com/HomayoonAlm"><img src="https://img.shields.io/badge/X-00ADD8?style=for-the-badge&labelColor=0D1117&logo=x&logoColor=00ADD8" alt="X" /></a>
<a href="mailto:homayoonalimohammadi@gmail.com"><img src="https://img.shields.io/badge/Email-00ADD8?style=for-the-badge&labelColor=0D1117&logo=gmail&logoColor=00ADD8" alt="Email" /></a>

<br><br>

<sub><i>Still figuring it out, in public.</i></sub>

</div>
