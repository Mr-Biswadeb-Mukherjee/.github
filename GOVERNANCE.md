# Project Governance and Usage Rules

## Purpose

This document defines the governance model and operational rules for repositories maintained under **Biswadeb Mukherjee's Lab**. Its purpose is to ensure transparency, maintain project quality, and establish clear expectations for contributors and users.

All individuals interacting with repositories within this organisation are expected to understand and follow these rules.

---

# Project Ownership

All repositories within this organisation are originally authored and maintained by:

**Mr. Biswadeb Mukherjee**
Offensive Security Researcher & Malware Engineer

Unless explicitly stated otherwise, the maintainer retains full authority over:

* project direction
* feature acceptance
* contribution approval
* issue moderation
* repository governance

---

# Intended Use

Projects published by this organisation are created for:

* cybersecurity research
* academic study
* authorised security testing
* professional security experimentation

Users are responsible for ensuring that any use of the software complies with applicable laws and authorisation requirements.

---

# Engineering and Coding Standards

To maintain high engineering quality across all repositories, the following coding rules apply to all contributors.

## File Structure and Code Size

Source files must follow disciplined engineering standards.

* Each source code file should contain **between 80 and 250 lines of code**.
* Creating unnecessary tiny files solely to fragment logic is not permitted.
* Files exceeding a reasonable size should be modularised into logical components.
* Each file should represent a **clear functional responsibility** within the project.

This rule exists to maintain readability, maintainability, and proper architectural structure.

---

## Import and Dependency Rules

The following architectural constraints must be respected:

* **Circular imports are strictly prohibited**
* Avoid immediate or runtime imports unless necessary
* Dependencies must be declared clearly and consistently
* Modules should maintain clean dependency boundaries
* Shared utilities should be placed in dedicated modules rather than duplicated

These practices ensure maintainable and predictable code behaviour.

---

## Architecture Discipline

All projects should follow sound software engineering principles.

* Maintain clear separation between logic layers
* Avoid tightly coupled modules
* Prefer modular, testable, and reusable components
* Follow language-specific best practices
* Avoid unnecessary abstractions

Repositories are expected to remain **research-grade but professionally engineered**.

---

## AI-Assisted Development Disclosure

AI tools may be used to assist development, but transparency is required.

If AI agents, coding assistants, or automated generation tools are used:

* This must be **clearly stated in the commit message**
* The contributor remains responsible for verifying the generated code
* AI-generated code must follow all repository engineering standards
* Unsafe or unverified generated code should never be committed directly

AI assistance does not replace engineering responsibility.

---

# Contribution Boundaries

Community contributions are welcome but must adhere to the following principles:

* Contributions must be technically relevant to the project
* Contributions should improve stability, documentation, or research quality
* Contributions must not introduce malicious functionality intended for unlawful use
* Contributions must follow repository coding and documentation standards

All contributions are reviewed before acceptance.

---

# Maintainer Authority

The maintainer reserves the right to manage repositories in the best interest of the project.

This includes the right to:

* accept or reject pull requests
* close or remove issues
* decline feature requests
* modify repository structure
* remove contributions that conflict with project objectives

Decisions made by the maintainer are final.

---

# Community Conduct

All interactions within issues, pull requests, and discussions should remain respectful and professional.

The following behaviours may result in moderation actions:

* harassment or abusive language
* spam or irrelevant content
* attempts to misuse project infrastructure
* intentionally disruptive behaviour

---

# Enforcement

Failure to follow the rules outlined in this document may result in actions including:

* rejection of pull requests
* closure of issues
* removal of comments or discussions
* restriction of repository participation

These measures are implemented to maintain a professional and productive research environment.

---

# Changes to This Policy

This governance document may be updated periodically to reflect changes in project management practices or organisational policies.

Users and contributors are encouraged to review this document periodically.

---

# Maintainer

**Mr. Biswadeb Mukherjee**

Offensive Security Researcher & Malware Engineer

**Website:** https://official-biswadeb941.in

