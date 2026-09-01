# Cybersecurity Framework

Cybersecurity works best when it is treated as a business risk and resilience discipline, not simply a collection of technical controls.

This repository brings together practical approaches to cybersecurity strategy, governance, risk, resilience and assurance.

It is intended as a reference and working framework rather than a prescriptive security model or compliance claim.

## Approach

A few principles underpin the material in this repository:

- **Start with risk** — understand what matters before deciding which controls to implement.
- **Keep security connected to the business** — controls should protect the organisation without unnecessarily preventing people from doing their jobs.
- **Use frameworks as tools, not outcomes** — certifications and maturity scores support assurance, but they are not the end goal.
- **Build security in layers** — identity, endpoints, infrastructure, applications, data, monitoring and recovery all contribute to security posture.
- **Test what you implement** — a documented control is not necessarily an effective control.
- **Keep improving** — threats, technology and organisational priorities continue to change.

The objective is straightforward:

**Understand the risk → Implement proportionate controls → Test effectiveness → Improve**

## Frameworks

Different frameworks provide different perspectives on the same underlying security and resilience challenge.

| Framework | Primary focus |
|---|---|
| **ISO 27001** | Information Security Management System |
| **Essential Eight** | Practical cyber-resilience controls |
| **NIST CSF** | Cybersecurity risk management |
| **SOC 2** | Security and trust-service controls |
| **PSPF** | Australian Government protective security |
| **APRA CPS 230** | Operational risk and resilience |
| **APRA CPS 234** | Information security for APRA-regulated entities |

These frameworks are not necessarily competing approaches. Depending on the organisation, they can be used together to support governance, control design, maturity assessment and assurance.

See the [`frameworks/`](frameworks/) directory.

## Core Security Domains

A cybersecurity program needs to consider more than perimeter or endpoint security.

Key domains include:

1. Governance & Strategy
2. Risk Management
3. Identity & Access Management
4. Infrastructure & Network Security
5. Endpoint Security
6. Application Security
7. Data Protection
8. Security Monitoring & Detection
9. Incident Response
10. Business Continuity & Disaster Recovery
11. Third-Party & Supply Chain Risk
12. Security Awareness & Culture

These areas are interconnected. Preventative controls still require detection and response, while incident response has limited value if critical services cannot be recovered.

## Risk & Maturity

Cybersecurity risk should be visible as an organisational risk rather than existing solely inside the technology function.

A practical risk cycle is:

**Identify → Assess → Prioritise → Treat → Monitor → Report**

Maturity should also be proportionate.

Not every organisation needs the highest maturity level in every security domain. Appropriate targets depend on:

- business risk;
- regulatory obligations;
- information sensitivity;
- threat exposure;
- operational requirements;
- cost;
- organisational priorities.

The more useful question is:

**Where does the organisation need greater maturity, and why?**

## Governance & Resilience

The [`governance/`](governance/) section contains practical material covering:

- business continuity and disaster recovery;
- incident response;
- security metrics and reporting;
- third-party and supply-chain risk.

The aim is to connect technical security capability with governance, ownership, evidence and organisational resilience.

## Architecture

Cybersecurity is most effective when controls operate together rather than as isolated products.

The architecture section considers security across:

**Identity → Endpoints → Infrastructure → Cloud → Data → Monitoring → Response → Recovery**

[View Cybersecurity Architecture](architecture/cybersecurity-architecture.md)

## From Framework to Practice

Frameworks become useful when they are applied to real organisational problems.

A related case study in the Technology Leadership repository documents the use of ISO 27001:2022 transition work as part of a broader cybersecurity maturity program covering governance, Essential Eight, SOC 2, data protection, detection, resilience and executive reporting.

[Read: Building Cybersecurity Maturity](https://github.com/rakeshranderia/technology-leadership/blob/main/cybersecurity/security-maturity.md)

## Roadmap

Future development of this repository is tracked in:

[`roadmap/cybersecurity-roadmap.md`](roadmap/cybersecurity-roadmap.md)

## Perspective

**More security does not automatically mean better security.**

Controls need to address meaningful risk, work operationally, have clear ownership and be tested.

A security program becomes sustainable when cybersecurity is no longer treated as a separate technology activity and instead becomes part of how the organisation manages **risk, data, resilience and change**.