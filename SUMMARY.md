# WE_GO_MARS Documentation Summary

This repository assembles research, planning guidance, and program surveys focused on radiation shielding for human Mars missions. Use this summary to navigate the major references and understand how the pieces fit together.

## Mission and Scope

- **Radiation Shielding Specification** – Core architecture assumptions, mission phases, and protection principles: [`specs/radiation-shielding/README.md`](specs/radiation-shielding/README.md)
- **Root Research Overview** – Literature synthesis covering shielding strategies, environmental data, and risk posture: [`README.md`](README.md)
- **Dosimetry Architecture** – Measurement objectives, instrumentation layers, and calibration workflows: [`specs/dosimetry/README.md`](specs/dosimetry/README.md)

## Mission Planning Playbooks

- **NASA Planning Workflow** – Lifecycle phases, systems engineering flow, and verification artifacts: [`specs/radiation-shielding/PLANNING.md`](specs/radiation-shielding/PLANNING.md)
- **ESA Planning Workflow** – ECSS processes, concurrent engineering, and partner coordination: [`specs/radiation-shielding/ESA_PLANNING.md`](specs/radiation-shielding/ESA_PLANNING.md)
- **Grand Challenges** – Cross-agency showstoppers framing technology roadmaps: [`specs/radiation-shielding/GRAND_CHALLENGES.md`](specs/radiation-shielding/GRAND_CHALLENGES.md)

## Procurement and Program Landscapes

- **NASA Solicitations** – Historical and current calls (NextSTEP, HERO, SBIR, RadWorks): [`specs/radiation-shielding/NASA_SOLICITATIONS.md`](specs/radiation-shielding/NASA_SOLICITATIONS.md)
- **ESA Tenders** – GSTP, Discovery & Preparation, OSIP, and E3P opportunities: [`specs/radiation-shielding/ESA_TENDERS.md`](specs/radiation-shielding/ESA_TENDERS.md)
- **Agency Snapshots**
  - CNSA programs: [`specs/radiation-shielding/CNSA_PROGRAMS.md`](specs/radiation-shielding/CNSA_PROGRAMS.md)
  - Roscosmos programs: [`specs/radiation-shielding/ROSCOSMOS_PROGRAMS.md`](specs/radiation-shielding/ROSCOSMOS_PROGRAMS.md)
  - JAXA programs: [`specs/radiation-shielding/JAXA_PROGRAMS.md`](specs/radiation-shielding/JAXA_PROGRAMS.md)
  - CSA programs: [`specs/radiation-shielding/CSA_PROGRAMS.md`](specs/radiation-shielding/CSA_PROGRAMS.md)
  - ISRO programs: [`specs/radiation-shielding/ISRO_PROGRAMS.md`](specs/radiation-shielding/ISRO_PROGRAMS.md)
- **Commercial Focus** – SpaceX Mars architecture and shielding approach: [`specs/radiation-shielding/SPACEX_PROGRAMS.md`](specs/radiation-shielding/SPACEX_PROGRAMS.md)

## Tools and Evaluation

- **AI Benchmark Concept** – Radiation Shielding Reasoning Benchmark (RSRB) structure and sample items: [`specs/radiation-shielding/AI_BENCHMARK.md`](specs/radiation-shielding/AI_BENCHMARK.md)

## Historical Lessons

- **Radiation Events in Mars Missions** – Case studies of radiation-induced anomalies and measurements: [`specs/radiation-shielding/MARS_MISSION_LESSONS.md`](specs/radiation-shielding/MARS_MISSION_LESSONS.md)

## System Engineering Reference

- **Radiation Shielding System Specification** – End-to-end requirements, architecture, and verification with links to sub-specs: [`specs/radiation-shielding/SYSTEM_SPEC.md`](specs/radiation-shielding/SYSTEM_SPEC.md)
- **Subsystem Specifications:**
  - Mission Context: [`system-spec/MISSION_CONTEXT.md`](specs/radiation-shielding/system-spec/MISSION_CONTEXT.md)
  - Requirements: [`system-spec/REQUIREMENTS.md`](specs/radiation-shielding/system-spec/REQUIREMENTS.md)
  - Architecture: [`system-spec/ARCHITECTURE.md`](specs/radiation-shielding/system-spec/ARCHITECTURE.md)
  - Design Approach: [`system-spec/DESIGN_APPROACH.md`](specs/radiation-shielding/system-spec/DESIGN_APPROACH.md)
  - Analysis & Modeling: [`system-spec/ANALYSIS_MODELING.md`](specs/radiation-shielding/system-spec/ANALYSIS_MODELING.md)
  - Verification & Validation: [`system-spec/VERIFICATION_VALIDATION.md`](specs/radiation-shielding/system-spec/VERIFICATION_VALIDATION.md)
  - Risk Management: [`system-spec/RISK_MANAGEMENT.md`](specs/radiation-shielding/system-spec/RISK_MANAGEMENT.md)
  - Programmatics: [`system-spec/PROGRAMMATICS.md`](specs/radiation-shielding/system-spec/PROGRAMMATICS.md)
  - Operations & Sustainment: [`system-spec/OPERATIONS_SUSTAINMENT.md`](specs/radiation-shielding/system-spec/OPERATIONS_SUSTAINMENT.md)

## Cross-Disciplinary Question Mapping

- **Mars Mission Systems Engineering Question Map** – Imported question tree with analysis of responsible tasks and documentation coverage: [`specs/system-engineering/README.md`](specs/system-engineering/README.md)

## How to Use This Repository

1. **Plan mission concepts** by starting with the specification and planning playbooks, then layering agency-specific requirements.
2. **Assess technology readiness** using the procurement and tender dossiers to pinpoint funding streams and in-progress efforts.
3. **Map collaboration opportunities** by comparing international program notes with SpaceX’s commercial roadmap.
4. **Validate AI tools** with the benchmark outline and adapt the sample tasks to your evaluation needs.

## Quick Reference Matrix

| Area | Document | Purpose |
| --- | --- | --- |
| Core Spec | [`specs/radiation-shielding/README.md`](specs/radiation-shielding/README.md) | High-level shielding requirements |
| Measurement | [`specs/dosimetry/README.md`](specs/dosimetry/README.md) | Dosimetry systems and operations |
| NASA Planning | [`specs/radiation-shielding/PLANNING.md`](specs/radiation-shielding/PLANNING.md) | Lifecycle & systems engineering |
| ESA Planning | [`specs/radiation-shielding/ESA_PLANNING.md`](specs/radiation-shielding/ESA_PLANNING.md) | ECSS-aligned planning guidance |
| NASA Calls | [`specs/radiation-shielding/NASA_SOLICITATIONS.md`](specs/radiation-shielding/NASA_SOLICITATIONS.md) | Solicitations & funding paths |
| ESA Tenders | [`specs/radiation-shielding/ESA_TENDERS.md`](specs/radiation-shielding/ESA_TENDERS.md) | Competitive opportunities |
| Global Agencies | [`CNSA`](specs/radiation-shielding/CNSA_PROGRAMS.md) · [`Roscosmos`](specs/radiation-shielding/ROSCOSMOS_PROGRAMS.md) · [`JAXA`](specs/radiation-shielding/JAXA_PROGRAMS.md) · [`CSA`](specs/radiation-shielding/CSA_PROGRAMS.md) · [`ISRO`](specs/radiation-shielding/ISRO_PROGRAMS.md) | Strategic snapshots |
| Commercial | [`specs/radiation-shielding/SPACEX_PROGRAMS.md`](specs/radiation-shielding/SPACEX_PROGRAMS.md) | SpaceX-specific analysis |
| Challenges | [`specs/radiation-shielding/GRAND_CHALLENGES.md`](specs/radiation-shielding/GRAND_CHALLENGES.md) | Cross-cutting obstacles |
| AI Evaluation | [`specs/radiation-shielding/AI_BENCHMARK.md`](specs/radiation-shielding/AI_BENCHMARK.md) | Benchmark concept |

Use this summary as an entry point for strategic planning, technology gap analysis, and collaborative proposals surrounding Mars mission radiation protection.
