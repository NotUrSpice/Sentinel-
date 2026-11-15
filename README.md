<div align="center">

# SENTINEL

### From isolated threat reports to coordinated digital protection

**One intelligence network. Two interfaces.**

[![Ideathon](https://img.shields.io/badge/IEDC-DotSlash%20Ideathon%202026-2563EB?style=for-the-badge)](https://github.com/NotUrSpice/Sentinel-)
[![Achievement](https://img.shields.io/badge/Achievement-2nd%20Place-F4B400?style=for-the-badge)](https://github.com/NotUrSpice/Sentinel-)

*An evidence-linked digital threat-intelligence and decision-support concept.*

</div>

---

## Overview

Digital fraud rarely stays confined to a single phone number, payment identifier, or phishing link. A victim may report a phone number, a bank may flag a suspicious account, and another user may submit a malicious URL—while all three signals are connected to the same campaign.

**Sentinel** proposes a shared threat-intelligence layer that connects these fragmented signals, helps identify coordinated campaigns, and supports timely, evidence-based responses.

The concept is built around **one intelligence core and two interfaces**:

- **Citizen Gateway — “Am I at risk?”** Gives individuals an accessible way to check a phone number, UPI/payment identifier, URL, or message and receive a risk indication with practical safety guidance.
- **Institutional Command Center — “What should we stop first?”** Helps authorized institutions review connected campaigns, inspect supporting evidence, and prioritize interventions when investigative resources are limited.

Sentinel is designed to connect and explain signals—not to declare people guilty or autonomously enforce decisions.

## The problem

Threat indicators are often handled in isolation:

- A citizen reports a suspicious phone number.
- A bank flags a potentially fraudulent payment account.
- A user reports a phishing link.
- Different organizations may not have a unified view of how these indicators relate.

Looking at each identifier independently can miss the wider campaign. Sentinel reframes the question from *“Is this identifier suspicious?”* to:

> **“What is it connected to—and what should we act on first?”**

## Proposed solution

Sentinel combines a **threat graph** with a **risk and prioritization engine**.

At a conceptual level, the system brings together permitted signals from sources such as citizen reports, public threat feeds, and authorized institutional data. It links related identifiers and activity into campaign-level views, while preserving the provenance and confidence of each signal.

### Core components

| Component | Purpose |
|---|---|
| Threat Graph | Connects related phone numbers, payment identifiers, URLs, domains, accounts, reports, and other permitted signals. |
| Risk Engine | Assesses the strength of the available evidence linking an identifier or activity to a potentially harmful campaign. |
| Citizen Gateway | Presents accessible risk information and recommended safety steps. |
| Institutional Command Center | Supports campaign review, evidence inspection, and intervention prioritization. |
| Evidence & Provenance Layer | Retains source references, timestamps, confidence, and the basis for graph connections. |

## How it works

1. **Submit a signal** — A citizen or an authorized source provides a phone number, payment identifier, URL, message, report, or other permitted signal.
2. **Evaluate available evidence** — Sentinel checks the signal against available reports, graph connections, and trusted inputs.
3. **Connect related activity** — Related identifiers can be grouped into a wider campaign view rather than treated as unrelated incidents.
4. **Communicate risk** — The Citizen Gateway presents a risk category and clear next steps. The institutional interface exposes supporting evidence for authorized review.
5. **Prioritize review** — Where resources are limited, the system can help institutions compare campaigns using evidence confidence, expected harm, reach, growth, and actionability.
6. **Improve the evidence base** — Verified and corrected information can improve subsequent analysis.

## Two interfaces

### 1. Citizen Gateway

Designed around the question **“Am I at risk?”**

Proposed user journey:

- Submit or forward a phone number, UPI/payment identifier, URL, or suspicious message.
- Receive a risk indication such as **High Risk**, **Suspicious**, or **No Known Risk**.
- Get clear safety guidance—for example, avoid transferring money and verify through an independent, trusted channel.
- Optionally submit a report that may contribute to the wider evidence base.

A “No Known Risk” result means that sufficient risk evidence was not identified; it is **not a guarantee of safety**.

### 2. Institutional Command Center

Designed around the question **“What should we stop first?”**

Proposed capabilities:

- View related indicators as connected campaigns.
- Inspect the evidence behind a graph connection.
- Review source, timestamp, confidence, and provenance.
- Compare campaign activity and potential harm.
- Prioritize cases for authorized human review.

## Operations research perspective

Sentinel's prioritization concept recognizes that investigative capacity is limited. A team may have more campaigns to review than available investigator-hours.

Rather than relying only on a first-in-first-out queue, the proposed system considers factors such as:

- Expected harm and severity.
- Campaign reach and growth velocity.
- Confidence in the evidence linking activity to a harmful campaign.
- Actionability and expected effectiveness of intervention.
- Available investigator-hours and verification capacity.

This separates **threat-association confidence** (how strongly evidence connects activity to a campaign) from **intervention priority** (which campaign may warrant attention first).

## Responsible design and governance

Sentinel is a decision-support concept. Its governance boundaries are central to the design.

- **No automated accusations:** Sentinel does not declare a person to be a criminal.
- **Human authority:** High-consequence actions remain with the relevant authorized institution and its established processes.
- **Evidence-linked outputs:** Signals and graph connections should be traceable to their sources, timestamps, and confidence.
- **Privacy-aware data handling:** Data access and sharing should be limited to permitted purposes and necessary information.
- **Correction and review:** Disputed or outdated indicators should be reviewable and correctable.
- **Clear accountability:** Sentinel remains responsible for the quality, security, provenance, and honest presentation of its intelligence; institutions remain responsible for actions they independently authorize.

> Sentinel connects and explains. Authorized institutions verify and decide.

**Important:** The ideathon materials describe a proposed governance framework, not a legal opinion. Any real deployment would require qualified legal, privacy, cybersecurity, and sector-specific review.

## Prototype scope

The ideathon presentation describes a concept whose prototype uses **synthetic/public data**. Real institutional signals, production integrations, and operational interventions would require appropriate partnerships, permissions, security controls, and governance.

This repository documents the project concept. Features described as proposed should not be interpreted as production-ready or already deployed.

## Future scope

Potential next steps include:

- Building a working, source-attributed threat-graph prototype using synthetic data.
- Developing the Citizen Gateway and Institutional Command Center as separate interfaces.
- Evaluating graph-linking and risk-calibration approaches.
- Prototyping transparent campaign-prioritization methods.
- Adding review, correction, expiry, and audit workflows.
- Exploring institution-led pilots subject to formal approvals and safeguards.

## Recognition

**2nd Place — IEDC DotSlash Ideathon 2026**

## Team

**Anjana · Akshay · Kailas · Madhav**

## Repository

[github.com/NotUrSpice/Sentinel-](https://github.com/NotUrSpice/Sentinel-)

---

<div align="center">

*Sentinel — One intelligence network. Two interfaces.*

</div>
