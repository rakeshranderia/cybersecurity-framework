# Cybersecurity Framework

Cybersecurity works best when it is treated as a business risk and resilience discipline, not simply a collection of technical controls.

This repository brings together the frameworks, controls and practical approaches I use when thinking about cybersecurity strategy, governance, risk and resilience.

It is intended as a practical reference rather than a prescriptive security model.

---

## My Approach

I tend to approach cybersecurity with a few principles in mind:

- **Start with risk** — understand what matters before deciding which controls to implement.
- **Keep security connected to the business** — controls need to protect the organisation without unnecessarily preventing people from doing their jobs.
- **Use frameworks as tools, not outcomes** — certification or maturity scores are useful, but they are not the end goal.
- **Build in layers** — identity, endpoints, infrastructure, data, monitoring and recovery all contribute to the overall security posture.
- **Test what you implement** — a documented control is not necessarily an effective control.
- **Keep improving** — threats, technology and the organisation will continue to change.

The objective is ultimately straightforward:

**Understand the risk, implement proportionate controls, test whether they work and keep improving them.**

---

## Security Frameworks

Different frameworks provide different perspectives on the same underlying challenge.

This repository considers several that I have worked with or used as reference points:

| Framework | Primary Focus |
|---|---|
| **ISO 27001** | Information Security Management System |
| **Essential Eight** | Practical cyber resilience controls |
| **NIST CSF** | Cybersecurity risk management |
| **SOC 2** | Security and trust service controls |
| **PSPF** | Australian Government protective security |
| **APRA CPS 234** | Information security for APRA-regulated entities |

I don't see these as competing frameworks.

Depending on the organisation, they can be used together to provide different levels of governance, control guidance and assurance.

---

## Core Security Domains

A cybersecurity program needs to consider more than perimeter security or endpoint protection.

I generally look across the following areas:

1. **Governance & Strategy**
2. **Risk Management**
3. **Identity & Access Management**
4. **Infrastructure & Network Security**
5. **Endpoint Security**
6. **Application Security**
7. **Data Protection**
8. **Security Monitoring & Detection**
9. **Incident Response**
10. **Business Continuity & Disaster Recovery**
11. **Third-Party & Supply Chain Risk**
12. **Security Awareness & Culture**

These areas are interconnected.

For example, strong preventative controls still need detection and response capability, while good incident response has limited value if the organisation cannot recover its critical services.

---

## Security Maturity

Maturity models are useful for understanding where capability currently sits and where investment may be required.

A simple five-stage view is:

| Level | Description |
|---|---|
| **1 — Initial** | Limited, reactive and largely undocumented |
| **2 — Developing** | Basic controls established but inconsistent |
| **3 — Defined** | Documented and consistently implemented |
| **4 — Managed** | Measured, monitored and actively managed |
| **5 — Optimised** | Continuously improving and risk-driven |

I don't believe every organisation needs to achieve the highest maturity level in every security domain.

The appropriate target depends on factors such as:

- Business risk
- Regulatory obligations
- Information sensitivity
- Threat exposure
- Operational requirements
- Cost
- Organisational priorities

The more useful question is not:

**"How do we reach Level 5 everywhere?"**

It is:

**"Where does the organisation need greater maturity, and why?"**

---

## Cybersecurity Risk Management

Cybersecurity risk should be visible as an organisational risk rather than existing solely inside the technology function.

A practical process is:

1. **Identify** — understand critical systems, information, assets and dependencies.
2. **Assess** — evaluate threats, vulnerabilities, likelihood and potential impact.
3. **Prioritise** — focus effort on risks with the greatest potential business consequence.
4. **Treat** — mitigate, transfer, accept or avoid risk based on organisational appetite.
5. **Monitor** — review changes in risk and whether controls remain effective.
6. **Report** — provide executives and the Board with visibility of material risks and decisions.

### Risk Considerations

Assessments may need to consider:

- Confidentiality, integrity and availability
- Critical business processes
- Regulatory obligations
- Third-party dependencies
- Data sensitivity
- Threat landscape
- Business impact
- Recovery requirements

One of the important responsibilities of technology leadership is translating these issues into language that allows business leaders to make informed decisions.

---

## Essential Eight

The Australian Cyber Security Centre's Essential Eight provides a practical baseline for improving cyber resilience.

The eight mitigation strategies are:

| Control | Objective |
|---|---|
| **Application Control** | Prevent unauthorised applications from executing |
| **Patch Applications** | Reduce vulnerabilities in applications |
| **Configure Microsoft Office Macro Settings** | Reduce malicious macro execution |
| **User Application Hardening** | Reduce browser and application attack surfaces |
| **Restrict Administrative Privileges** | Limit opportunities for privilege escalation |
| **Patch Operating Systems** | Reduce operating system vulnerabilities |
| **Multi-Factor Authentication** | Reduce the risk of compromised credentials |
| **Regular Backups** | Enable recovery from destructive attacks |

In practice, implementing the controls is only part of the work.

An ongoing Essential Eight program also needs:

- Ownership
- Maturity assessment
- Risk-based prioritisation
- Exception management
- Monitoring
- Testing
- Reporting

This turns the Essential Eight from a checklist into an operational security capability.

---

## ISO 27001

ISO/IEC 27001 provides a structured approach to establishing, implementing, maintaining and continually improving an Information Security Management System.

I find the value of ISO 27001 is broader than certification.

A functioning ISMS creates a repeatable way to connect:

**Risk → Controls → Ownership → Evidence → Review → Improvement**

### Governance

- Information security policy
- Roles and responsibilities
- Leadership accountability
- Security objectives

### Risk Management

- Information security risk assessment
- Risk treatment
- Risk acceptance
- Control effectiveness

### Operational Controls

- Access management
- Asset management
- Supplier security
- Incident management
- Business continuity
- Security awareness

### Assurance

- Internal audits
- Management reviews
- Control testing
- Corrective actions
- Continual improvement

Certification can provide useful external assurance.

The greater value, however, comes when the ISMS becomes part of normal technology and risk management rather than something maintained primarily for an annual audit.

---

## Architecture

Cybersecurity is most effective when controls work together rather than operating as isolated products.

The architecture section provides a high-level view across:

**Identity → Endpoints → Infrastructure → Cloud → Data → Monitoring → Response → Recovery**

[View Cybersecurity Architecture](architecture/cybersecurity-architecture.md)

---

## From Framework to Practice

Frameworks become more useful when they are applied to real organisational problems.

In my Technology Leadership repository, I've documented an example of using ISO 27001:2022 transition work as part of a broader security maturity program covering governance, Essential Eight, SOC 2, data protection, detection, resilience and executive reporting.

[Read: Building Cybersecurity Maturity](https://github.com/rakeshranderia/technology-leadership/blob/main/cybersecurity/security-maturity.md)

That case study focuses less on the individual controls and more on how they were brought together as an ongoing security program.

---

## Perspective

One of the lessons I've taken from leading cybersecurity programs is that **more security does not automatically mean better security**.

Controls need to address meaningful risk.

They need to work operationally.

They need clear ownership.

And they need to be tested.

A security program becomes sustainable when cybersecurity is no longer treated as a separate technology activity and instead becomes part of the way the organisation manages **risk, data, resilience and change**.