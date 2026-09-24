<!-- ===================== HERO ===================== -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0D1117,55:1F1206,100:F97316&text=Jazeer%20Ahammed&fontColor=FFFFFF&fontSize=52&fontAlignY=36&desc=Founder%20%C2%B7%20Platform%20Architect%20%C2%B7%20Building%20trust%20infrastructure%20for%20AI%20agents&descSize=16&descAlignY=58&animation=fadeIn" alt="Jazeer Ahammed" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1400&color=F97316&center=true&vCenter=true&width=760&height=40&lines=Founder+%40+DgVerse+%E2%80%94+building+HelixID;Replacing+API+keys+with+verifiable+agent+identity;Open+standards%3A+W3C+VCs+%C2%B7+DIDs+%C2%B7+OAuth+2.1;10%2B+years+of+platform%2C+cloud+%26+DevSecOps" alt="Typing SVG" />

<br/>

[![HelixID](https://img.shields.io/badge/HelixID-open%20source-F97316?style=for-the-badge&labelColor=0D1117)](https://github.com/helixid)
[![Docs](https://img.shields.io/badge/docs-helixid.dev-F97316?style=for-the-badge&labelColor=0D1117&logo=readthedocs&logoColor=white)](https://docs.helixid.dev)
[![DgVerse](https://img.shields.io/badge/DgVerse-company-0D1117?style=for-the-badge&labelColor=F97316)](https://www.dgverse.in/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jazeer)
[![X](https://img.shields.io/badge/@iamjazeer-0D1117?style=for-the-badge&logo=x&logoColor=white)](https://x.com/iamjazeer)

</div>

<br/>

## ⚡ TL;DR

```yaml
whoami:
  name:     Jazeer Ahammed
  building: HelixID — the identity & authorization layer for AI agents
  day_job:  Platform / Cloud Architect — 10+ years, sysadmin → DevOps lead
  thesis:   "Agents will act for us. Trust has to be verifiable, scoped and revocable — not an API key in an env var."
  ships:    [platforms, identity infra, open standards]
```

<br/>

## 🚀 What I'm Building

<table>
<tr>
<td width="50%" valign="top">

### 🧬 [HelixID](https://github.com/helixid)
**Auth for AI agents, built on open standards.**

Replaces static API keys with identity that is **verifiable, scoped, revocable and auditable** — using W3C Verifiable Credentials and DIDs.

- Multi-hop delegation with auditable cross-org trust
- Designed to sit alongside OAuth 2.1 / OIDC and SPIFFE — not replace them
- DLT-agnostic core: `did:key` / `did:web` by default, ledger anchoring optional
- TypeScript + Python SDKs · Apache 2.0

`open source` · `active development`

</td>
<td width="50%" valign="top">

### 🏢 [DgVerse](https://www.dgverse.in/)
**The trust layer for digital credentials and AI agents.**

The company behind HelixID. Before it, we shipped a **production verifiable-credential SaaS** on Hedera — issuance, QR verification and API integrations.

- W3C VC/DID with selective disclosure
- Hybrid NFT / soulbound credential path
- Infra, CI/CD, observability & security owned end-to-end

`founder` · `since 2023`

</td>
</tr>
</table>

<details>
<summary><b>🔍 How HelixID works — the 5-layer trust stack</b></summary>
<br/>

```mermaid
flowchart LR
    A([🤖 AI Agent]) --> B[1 · Identity<br/>DID]
    B --> C[2 · Authority<br/>scoped VC]
    C --> D[3 · Enforcement<br/>effective scopes]
    D --> E[4 · Audit<br/>tamper-evident log]
    E --> F[5 · Revocation<br/>status list]
    F --> G([✅ Service])
    style A fill:#0D1117,stroke:#F97316,color:#fff
    style G fill:#F97316,stroke:#F97316,color:#fff
```

Authority is the intersection of a platform ceiling and a user-consented grant — so an agent can never hold more power than both sides agreed to. Verification needs no live call to the issuer to vouch for each request.

</details>

<br/>

## 📈 Platform Track Record

<div align="center">

| | Impact |
|:--:|:--|
| ☸️ | Built & run a **high-availability, multi-region AKS platform** |
| 💰 | Cut cloud spend **35% year-on-year** through FinOps & right-sizing |
| 🛡️ | **30% fewer failed deployments** — blue/green, canary, GitOps |
| 👥 | Lead an **8-engineer DevOps team** across CI/CD, IaC and security |
| ⚙️ | Terraform provisioning that turned days into hours (**~80% faster**) |

</div>

<br/>

## 🧰 Stack

<div align="center">

**Cloud · IaC · Containers**

<img src="https://skillicons.dev/icons?i=aws,azure,gcp,linux,terraform,ansible,docker,kubernetes,githubactions&theme=dark" alt="Cloud and infrastructure stack" />

**Observability · Data**

<img src="https://skillicons.dev/icons?i=prometheus,grafana,elasticsearch,postgres&theme=dark" alt="Observability stack" />

**Code**

<img src="https://skillicons.dev/icons?i=ts,nodejs,python,bash&theme=dark" alt="Languages" />

<br/><br/>

![Istio](https://img.shields.io/badge/Istio-0D1117?style=flat-square&logo=istio&logoColor=466BB0)
![Cilium](https://img.shields.io/badge/Cilium-0D1117?style=flat-square&logo=cilium&logoColor=F8C517)
![Argo CD](https://img.shields.io/badge/Argo%20CD-0D1117?style=flat-square&logo=argo&logoColor=EF7B4D)
![Helm](https://img.shields.io/badge/Helm-0D1117?style=flat-square&logo=helm&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-0D1117?style=flat-square&logo=grafana&logoColor=F46800)
![Thanos](https://img.shields.io/badge/Thanos-0D1117?style=flat-square)
![Hedera](https://img.shields.io/badge/Hedera-0D1117?style=flat-square&logo=hedera&logoColor=white)
![W3C VC](https://img.shields.io/badge/W3C%20VC-F97316?style=flat-square)
![DID](https://img.shields.io/badge/DIDs-F97316?style=flat-square)
![OAuth 2.1](https://img.shields.io/badge/OAuth%202.1%20%2F%20OIDC-F97316?style=flat-square)
![SPIFFE](https://img.shields.io/badge/SPIFFE-F97316?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-F97316?style=flat-square)

</div>

<br/>

## 🧭 How I Operate

- **Architecture first, then execution.** Every design gets judged on trade-offs and business impact, not novelty.
- **Claims must survive an engineer checking them.** If a benchmark or a feature needs an asterisk, the asterisk goes on the slide.
- **Boring infrastructure wins.** Reliable, observable and cheap beats clever.
- **Own the pager.** Take the 3am page, write the postmortem, share the credit.

<br/>

## 📊 Activity

<!--
  STATS_HOST: these are shared public instances. As of Sep 2026 the popular
  github-readme-stats.vercel.app (503) and github-readme-activity-graph (402) are down,
  so this uses github-profile-summary-cards + streak-stats. If a card breaks, self-host
  github-readme-stats on Vercel and swap the base URL.
-->

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jazeer888&theme=github_dark" alt="GitHub contribution summary" />

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=jazeer888&theme=github_dark" alt="GitHub stats" />
<img height="170" src="https://streak-stats.demolab.com/?user=jazeer888&hide_border=true&background=0D1117&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=9BA1A6&dates=6E7681&currStreakNum=FFFFFF&sideNums=FFFFFF&stroke=30363D" alt="GitHub streak" />

</div>

<br/>

<!-- ===================== CTA ===================== -->
<div align="center">

## 🤝 Let's Build

**Working on agent infrastructure, MCP tooling, or cross-org trust?**<br/>
I'm looking for **design partners** for HelixID and I'm always up for a conversation on platform engineering.

[![Star HelixID](https://img.shields.io/badge/⭐%20Star%20HelixID-F97316?style=for-the-badge&labelColor=0D1117)](https://github.com/helixid/helixid)
[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jazeer)
[![X](https://img.shields.io/badge/Follow-0D1117?style=for-the-badge&logo=x&logoColor=white)](https://x.com/iamjazeer)

<img src="https://komarev.com/ghpvc/?username=jazeer888&style=flat-square&color=F97316&label=profile+views" alt="Profile views" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:F97316,45:1F1206,100:0D1117" alt="" />

</div>
