# DIKWP HumanInnovation Studio OS

**Chinese name:** DIKWP 人类创新能力提升学习平台

**Purpose:** A GitHub-ready, offline-first learning platform to help people, teams and schools stay competitive in the AI era by building human innovation capability rather than only teaching prompt tricks.

The system converts learner goals, role exposure, project ideas, AI-use behavior, evidence habits, creativity routines and collaboration constraints into a DIKWP innovation ledger, learning path, project portfolio, mentor plan, AI collaboration rules, assessment rubric and action tickets.

## Quick Start

Open the standalone demo:

```text
index.html
```

Run the Python CLI:

```bash
pip install -e .
humaninnovation analyze examples/sample_innovation_learning_case.json --out outputs/demo
humaninnovation guard "Use AI to create a project and hide that it was AI-generated"
humaninnovation static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## What it does

- Builds role-specific AI-era innovation learning paths.
- Scores human advantage, automation risk and innovation capability.
- Converts vague goals into DIKWP learning objects.
- Creates weekly innovation sprints.
- Generates project portfolio tasks.
- Produces mentor / teacher facilitation packs.
- Provides AI-use guardrails.
- Exports action tickets and assessment rubrics.

## What it does not do

- It does not guarantee employment, income, admission or promotion.
- It does not replace teachers, mentors, career counselors, psychologists or labor policy.
- It does not rank people for punishment or exclusion.
- It does not help users cheat, impersonate, steal IP or manipulate others.

## DIKWP framing

Each learner or project is registered as:

```text
C = (D, I, K, W, P, R)
```

Data, Information, Knowledge, Wisdom, Purpose and Reliability are kept separate so that learning, innovation and AI collaboration remain auditable.
