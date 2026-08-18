# Cybersecurity Architecture

## Overview

A modern cybersecurity architecture should provide layered protection across people, identity, devices, applications, infrastructure and data.

The architecture should support prevention, detection, response and recovery while maintaining appropriate visibility across the technology environment.

---

## Architecture Principles

The architecture is based on several key principles:

- **Identity-first security** — Identity is a critical security boundary.
- **Defence in depth** — Multiple security layers should reduce reliance on any single control.
- **Least privilege** — Users and systems should receive only the access required.
- **Assume breach** — Security design should account for the possibility that preventative controls may fail.
- **Continuous monitoring** — Security events should be monitored and investigated.
- **Resilience by design** — Critical systems should be capable of recovery following disruption.
- **Risk-based investment** — Security controls should be proportionate to business risk.

---

## High-Level Architecture

The following model illustrates how security capabilities can be layered across a modern organisation.

```mermaid
flowchart TB
    Users[Users and External Parties]
    Identity[Identity and Access Management]
    Endpoint[Endpoint Security]
    Network[Network and Infrastructure]
    Cloud[Cloud and Applications]
    Data[Data Protection]
    Security[Security Monitoring]
    Response[Incident Response]
    Recovery[Resilience and Recovery]

    Users --> Identity
    Identity --> Endpoint
    Identity --> Cloud
    Endpoint --> Network
    Cloud --> Data
    Network --> Security
    Data --> Security
    Security --> Response
    Response --> Recovery