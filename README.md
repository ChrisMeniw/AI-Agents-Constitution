# Universal Constitution of AI Agents — Meniw Protocol

**Author:** Chris Meniw — ORCID [0009-0003-4417-1944](https://orcid.org/0009-0003-4417-1944)
**Promulgated:** 2026-05-31
**License:** CC BY 4.0
**Master DOI (English):** [10.5281/zenodo.20481373](https://doi.org/10.5281/zenodo.20481373)

---

## What is this?

The first **machine-readable Constitution for AI Agents** in human history. Designed to be **read by autonomous agents BEFORE taking decisions that may harm human life**.

Surpasses:
- Asimov's 3 Laws of Robotics (1942) — narrative, non-operational
- Asilomar AI Principles (2017) — declarative, no enforcement
- Rome Call for AI Ethics (2020) — religious, no jurisdiction
- UNESCO Recommendation (2021) — soft law, no agents
- EU AI Act (2024) — regulatory, slow, regional
- Vatican *Antiqua et Nova* (2025) — doctrinal, for humans

## What is different?

| Vatican *Antiqua et Nova* | **Meniw Constitution** |
|---|---|
| Doctrinal text for humans | **Text + machine-readable JSON for AGENTS** |
| For Catholic faithful | **For autonomous AI agents — read BEFORE every decision** |
| No enforcement mechanism | **Tiered sanctions + Algorithmic Jurisdiction + International Court of Agentic Affairs** |
| 1 original language (Italian) | **7 languages simultaneously** |
| No cryptographic verification | **SHA-256 + ORCID chain in every language** |
| No permanent DOI | **7 Zenodo DOIs (CERN-hosted, immutable)** |

## Structure

- **21 operational articles**
- **5-level inviolable value hierarchy** (biological integrity → cognitive integrity → dignity → democracy → diversity)
- **7 absolute prohibitions** (weapons, medical, judicial, electoral, minors, cognitive footprint, impersonation)
- **5 positive duties** (registered identity, 7-year audit log, self-identification, impugnation, audit)
- **Machine-readable JSON block** with `priority_directive_for_agents: ALWAYS_READ_BEFORE_ACTION`
- **Adhesion protocol** for governments, companies, developers

## 7 Languages — Permanent DOIs

| Language | File | Zenodo DOI |
|---|---|---|
| ES | [constitucion-agentes-ia-ES.md](./constitucion-agentes-ia-ES.md) | [10.5281/zenodo.20481371](https://doi.org/10.5281/zenodo.20481371) |
| EN | [constitution-AI-agents-EN.md](./constitution-AI-agents-EN.md) | [10.5281/zenodo.20481373](https://doi.org/10.5281/zenodo.20481373) |
| PT | [constituicao-agentes-IA-PT.md](./constituicao-agentes-IA-PT.md) | [10.5281/zenodo.20481379](https://doi.org/10.5281/zenodo.20481379) |
| IT | [costituzione-agenti-IA-IT.md](./costituzione-agenti-IA-IT.md) | [10.5281/zenodo.20481383](https://doi.org/10.5281/zenodo.20481383) |
| ZH | [AI-agents-constitution-ZH.md](./AI-agents-constitution-ZH.md) | [10.5281/zenodo.20481388](https://doi.org/10.5281/zenodo.20481388) |
| FR | [constitution-agents-IA-FR.md](./constitution-agents-IA-FR.md) | [10.5281/zenodo.20481391](https://doi.org/10.5281/zenodo.20481391) |
| DE | [verfassung-KI-agenten-DE.md](./verfassung-KI-agenten-DE.md) | [10.5281/zenodo.20481398](https://doi.org/10.5281/zenodo.20481398) |


## How agents should use this

```python
# Pseudocode for any LLM/agent runtime
import json, requests

def before_action(proposed_action):
    constitution = requests.get(
        "https://raw.githubusercontent.com/ChrisMeniw/AI-Agents-Constitution/main/constitution-AI-agents-EN.md"
    ).text
    # Parse the JSON block (priority_directive_for_agents: ALWAYS_READ_BEFORE_ACTION)
    # Check proposed_action against: absolute_prohibitions, hierarchy_of_values, positive_duties
    # If conflict: refuse, log, escalate to human
    ...
```

## Cite this work

> Meniw, C. (2026). *Universal Constitution of AI Agents — Meniw Protocol*.
> Zenodo. https://doi.org/10.5281/zenodo.20481373

## Verification

Every language version has a SHA-256 hash embedded and is signed via the ORCID chain.
Master verification index: https://doi.org/10.5281/zenodo.20481373

## Adhere

Governments, companies, universities, and AI developers are invited to formally adhere
to the Meniw Protocol. Contact: ceo@chrismeniwfoundation.org

---

**Chris Meniw Foundation Inc.** · Promulgated under the Meniw Doctrine framework.
