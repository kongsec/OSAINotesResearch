# OSAI Training Vault — by Kongsec

> Complete offensive AI security notes aligned with OffSec's AI-300 (OSAI) certification.  
> Beginner to advanced. Real scenarios. Working payloads. Tools included.

**Live →** [kongsec.github.io/osai-vault](https://kongsec.github.io/osai-vault)

---

## What's Inside

22 modules covering the full OSAI curriculum — from AI/ML fundamentals to 48-hour exam prep.

| # | Module | Level |
|---|--------|-------|
| 00 | Overview & Adversary Mindset | Beginner |
| 01 | AI/ML Fundamentals for Attackers | Beginner |
| 02 | LLM Architecture Deep Dive | Beginner |
| 03 | AI Attack Surface Map | Beginner |
| 04 | Prompt Injection | Intermediate |
| 05 | Jailbreaking Techniques | Intermediate |
| 06 | Data Exfiltration via LLM | Intermediate |
| 07 | Insecure Output Handling | Intermediate |
| 08 | RAG Pipeline Attacks | Advanced |
| 09 | Agent & Tool Hijacking | Advanced |
| 10 | Multi-Agent Exploitation | Advanced |
| 11 | Model Extraction | Advanced |
| 12 | Data Poisoning | Advanced |
| 13 | AI Supply Chain Attacks | Advanced |
| 14 | AI Infra Recon | Infrastructure |
| 15 | API & Endpoint Attacks | Infrastructure |
| 16 | Model Serving Exploits | Infrastructure |
| 17 | Case Studies & CVEs | Real World |
| 18 | Red Team Scenarios | Real World |
| 19 | OWASP LLM Top 10 | Real World |
| 20 | Tools Arsenal | Resources |
| 21 | Labs & Practice | Resources |
| 22 | Exam Prep | Resources |

---

## Coverage

- **OWASP LLM Top 10 (2025)** — full mapping
- **MITRE ATLAS** — tactic/technique mapping per module
- **CVEs covered** — CVE-2023-43654 (ShellTorch), HuggingFace pickle RCE, and more
- **Real incidents** — Bing Chat, Slack AI, ChatGPT plugins, Samsung leak, GitHub Copilot
- **Working payloads** — prompt injection tiers, jailbreak techniques, RAG poisoning, agent hijacking
- **Tools** — Garak, PyRIT, promptfoo, modelscan, ART, Vigil, LLMFuzzer

---

## Deploy

Single-file HTML. No dependencies. No build step.

```
repo/
└── index.html   ← rename osai_kongsec.html to this
```

Enable GitHub Pages → Settings → Pages → Branch: `main` → `/root`

Done. Accessible at `https://kongsec.github.io/<repo-name>`

---

## Frameworks Referenced

- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [OffSec AI-300](https://www.offsec.com/courses/ai-300/)

---

## Disclaimer

For authorized security research and educational use only.  
All techniques are documented for defensive awareness and certified offensive security training.

---

`kongsec` · offensive security research
