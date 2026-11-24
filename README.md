### Gérard Zapf

**Security architect and engineer.** Zero Trust, SOC infrastructure as code and AI agent security. Currently Principal Specialist Solution Engineer for Cloudflare Zero Trust at Cloudflare.

```mermaid
%%{init: {'gitGraph': {'mainBranchName': 'security'}}}%%
gitGraph
  commit id: "init"
  branch zero-trust
  commit id: "solution design"
  commit id: "access policies"
  checkout security
  merge zero-trust
  branch soc-as-code
  commit id: "SIEM and SOAR"
  commit id: "IdP and CA as code"
  checkout security
  merge soc-as-code
  branch ci-guardrails
  commit id: "policy a repo cannot weaken"
  commit id: "job-bound tokens"
  checkout security
  merge ci-guardrails
  branch agent-security
  commit id: "brokered agents"
  commit id: "egress by risk tier"
  commit id: "injection range"
  checkout security
  commit id: "HEAD" tag: "now"
```

#### What I work on

- **Zero Trust architecture:** solution design for customers' Cloudflare Zero Trust deployments. Before that, the design of ZF's Zero Trust architectures.
- **SOC infrastructure as code:** SIEM, SOAR, identity provider and certificate authority, developed and operated with the ZF SOC team.
- **Guardrails in engineering workflows:** a central CI/CD policy that a repository cannot weaken. Deterministic checks block, models advise.
- **AI agent security:** brokered credentials for CI jobs and agents, hardened agent cells with egress by risk tier, a prompt-injection range for testing my own agents.

Most of this lives in private repositories on my self-hosted GitLab.

#### Public work

| | |
|---|---|
| [posture-simulator](https://github.com/Zapfmeister/posture-simulator) | Cloudflare Worker behind Access that serves custom device posture levels for Zero Trust policies |
| [maico-enocean-mqtt](https://github.com/Zapfmeister/maico-enocean-mqtt) | Reverse-engineered MAICO radio protocol (EnOcean), controls ventilation units from Home Assistant over MQTT |

Contributions to [GOAD](https://github.com/Orange-Cyberdefense/GOAD/pull/190), [authentik](https://github.com/goauthentik/authentik/pull/9541), [Cloudflare docs](https://github.com/cloudflare/cloudflare-docs/pull/33564) and the [Home Assistant Let's Encrypt add-on](https://github.com/home-assistant/apps/pull/701).

Talk: [Securing agentic harnesses: Control, visibility, and safe tool use](https://www.cloudflare.com/connect/2026/session/securing-agentic-harnesses-control-visibility-and-safe-tool-use), Cloudflare Connect 2026.

#### Toolbox

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=flat-square&logo=opentofu&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)
![authentik](https://img.shields.io/badge/authentik-FD4B2D?logo=authentik&logoColor=white&style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
