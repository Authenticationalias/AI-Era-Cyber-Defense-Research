# AI-Era Cyber Defense Research

A public working notebook and shared knowledge base about cyber defense in AI-enabled environments.

Research areas include **AI security, autonomous cyber defense, defensive automation, evidence provenance, threat intelligence, cyber defense measurement, bounded authorization, and cyber resilience**.

The main question is simple:

> **What is defense in the AI era?**

This repository exists to help preserve, organize, reuse, and share what is learned while studying that question. It also provides a lightweight way for outside sources, corrections, observations, counterexamples, and questions to enter an otherwise small one-person-plus-AI research loop.

## What this repository is

This is a **Public Working Repository**: a place for selected working notes, source-linked synthesis, open questions, and reusable defensive models.

It is not a standards body, certification authority, professional advisory service, vulnerability coordination service, or promise of complete/current coverage. Material here may change as stronger evidence, prior art, or real-world constraints are found.

Publication means that a note is useful enough to share publicly. It does **not** mean that every statement has been independently verified or that the maintainer endorses every source, issue, comment, or external contribution.

## Current working baseline

The current General Theory v0.1 is **organizationally closed / reopenable**: structured enough to branch into capability- and environment-specific research, while explicitly remaining revisable.

### Seven working record types

- Source
- Entity
- Evidence
- Claim
- Relation
- Decision
- Action

Derived concepts such as hypotheses, state projections, outcomes, and provenance are represented through those records and their relationships rather than fixed as separate universal object types.

### Three feedback loops

**Knowledge loop**  
Source / Evidence → Claim → validation / revision

**Decision loop**  
State projection → proposed Action → Decision

**Control loop**  
Authorized Action → execution → post-action Evidence → state / claim update → continue / rollback / escalate

The project also distinguishes:

- inherited security foundations;
- processes that AI mainly accelerates;
- pressures shaped more specifically by AI agents, tool use, context, memory, credentials, probabilistic outputs, and persistent feedback loops.

## Open questions

Examples of questions that may be useful entry points for outside input:

- How should evidence independence be measured when multiple telemetry sources share upstream dependencies?
- Which defensive actions should remain human-authorized when an AI system can generate new actions beyond fixed playbooks?
- How much attack-relevant knowledge can be reconstructed by joining public artifacts, and how should that reconstruction gain be measured?
- Which assumptions in the general model break first in low-telemetry, low-budget, or high-availability environments?

## A working research question: adversarial knowledge reconstruction

One research branch asks how much attack-relevant knowledge can be reconstructed by joining accessible public artifacts such as web assets, repositories, patch history, package metadata, documentation, and exposure data.

The earlier label **Knowledge Attack Surface** is deprecated here. The underlying phenomenon remains a research topic, but the terminology is intentionally not treated as novel or canonical.

## Why public input is useful

A small research loop can easily become narrow. Useful outside input may include:

- a relevant paper, standard, advisory, incident report, or implementation reference;
- a correction to a factual claim or source lineage;
- a terminology or prior-art conflict;
- a real-world condition where a working assumption fails;
- an observation from Personal, SMB, Enterprise, cloud, SOC/IR, OT/ICS, or AI-agent environments;
- a question that exposes a missing branch of the research.

If you have something concrete, opening an Issue is welcome. There is no support SLA or promise that every issue will receive a response or final adjudication.

## Evidence posture

Where practical, the project tries to keep these distinguishable:

- direct observations;
- authoritative or primary sources;
- third-party research;
- community signals;
- model inference;
- hypotheses;
- unknown or unresolved states.

Inference is used to decide what to investigate next, not to silently turn uncertainty into fact.

## Safety scope

This is defense-oriented research.

Public material should avoid:

- live credentials or secrets;
- personal data;
- non-public vulnerable endpoints;
- actionable reproduction details for undisclosed vulnerabilities;
- step-by-step intrusion procedures;
- current defensive-bypass recipes that would materially increase attack capability.

Potentially attack-enabling detail should remain private until appropriate remediation or responsible-disclosure conditions are satisfied, and later publication should be limited to what is necessary for defensive learning.

## Language

English is the primary public language because most cybersecurity standards, papers, GitHub research, and international practitioner discussion are easier to discover and connect in English. Japanese material may be added selectively; full bilingual mirroring is not a requirement.

## License

Unless otherwise noted, research documentation and other non-software material in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

Software, if added later, may use a separate software license.
