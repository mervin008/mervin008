<h1 align="center">Mervin Jones D</h1>

<p align="center">
  <b>Cloud Security &amp; PKI Engineer</b><br/>
  Enterprise Certificate Lifecycle Management · GCP · Kubernetes<br/>
  <sub>Frankfurt, Germany</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mervinjonesd/">
    <img src="https://img.shields.io/badge/LinkedIn-0a7ea4?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://mervinjones.com/">
    <img src="https://img.shields.io/badge/Portfolio-0a7ea4?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:dmervinjones@gmail.com">
    <img src="https://img.shields.io/badge/Email-0a7ea4?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/certpilot/certpilot">
    <img src="https://img.shields.io/badge/CertPilot-d93025?style=flat-square&logo=letsencrypt&logoColor=white" alt="CertPilot" />
  </a>
</p>

---

### Everyone automates certificates. Almost nobody automates the authority that signs them.

An expiring leaf certificate breaks one service. An expiring **issuing CA** takes
down every certificate it ever signed — and no amount of certificate automation
helps you after that has happened.

That gap is what I work on. Five years of it: enterprise PKI, certificate
lifecycle management, and the cloud-native plumbing that has to survive both.

```
CA/Browser Forum maximum TLS validity

  398 days  ──────────────────────────────────────────────  today
  200 days  ────────────────────────                        March 2026
  100 days  ────────────                                    March 2027
   47 days  ────                                            March 2029
```

At 47 days, an estate of ten thousand certificates is **~670 renewals every
day**, continuously. Anything with a human in the loop stopped working long
before that.

---

### 🛠 What I do

**Enterprise PKI & CLM** — X.509 lifecycle automation, intermediate and issuing
CA rotation, Certificate Transparency log discovery, ACME (RFC 8555), zero-trust
mutual TLS

**Cloud & DevOps** — Google Cloud CAS, GKE, IAM, Terraform, Docker, Linux, CI/CD
security automation

**Cryptography, forward-looking** — Confidential Computing, encryption-in-use
architectures, and post-quantum readiness: measuring which endpoints negotiate a
PQ key exchange today rather than waiting for signatures to catch up

---

### 🚀 CertPilot

[**certpilot/certpilot**](https://github.com/certpilot/certpilot) — open-source
PKI and certificate lifecycle management, built for the team that owns the CA
hierarchy and gets paged when something expires.

Built because three problems kept showing up and no tool treated them as the
main event:

| | |
|:--|:--|
| **Finding what nobody registered** | CT logs, cloud accounts, and a host agent for the certificates behind two firewalls that no scan will ever reach |
| **Landing the renewal where it serves** | Staged rollouts in declared waves, then a handshake to prove it actually took |
| **Watching the authority** | Issuing CAs on the same clock as everything they sign |

`Go` · `Vue` · `PostgreSQL` · `gRPC` · ACME / HashiCorp Vault / self-signed gateways

<sub>🌐 [Site](https://certpilot-mauve.vercel.app/) · 📖 [API reference](https://certpilot.github.io/certpilot-docs/) · Early development, and the README says so rather than letting you find out.</sub>

---

### 🧰 Other things I've built

| | |
|:--|:--|
| [**Graphi-X**](https://github.com/mervin008/Graphi-X) | Sketch a maths problem on a canvas and get it solved. Gemini vision reads the drawing; FastAPI serves it. |
| [**mxc-ai-bot**](https://github.com/mervin008/mxc-ai-bot) | A Telegram bot with switchable LLM backends — Gemini, OpenAI, DeepSeek — with image input and per-user model selection. |
| **CertHub** | TLS certificate lifecycle dashboard over Google Cloud Certificate Authority Service. Vue SPA, FastAPI backend. *(private)* |
| **Terraform Proxmox** | A module for full-clone Proxmox VMs — sizing, networking and cloud-init in one configuration. *(private)* |

---

### ⚙️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/HashiCorp%20Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

---

<p align="center">
  <sub>
    Building what's next in PKI, certificate automation and post-quantum readiness.<br/>
    If you run PKI at real scale, I'd rather you tell me where CertPilot is wrong than star it.
  </sub>
</p>
