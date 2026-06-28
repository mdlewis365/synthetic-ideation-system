# Synthetic Ideation System

Synthetic Ideation System (SIS) is a governed invention-vector workflow within the private Synthetic OS Labs environment.

This public repository is documentation only. It describes the current SIS workflow at a public-safe level without publishing the private engine, prompt logic, evaluator internals, or implementation details.

## What It Does

SIS helps a user frame structured invention work. It uses a Scientist Input Module to collect:

- exploration vector
- target exploration domain
- objective framing
- allowed approaches
- rejection boundaries
- optional invention-control fields
- user-selected invention mode
- user-selected allowed model

The result is a structured invention or concept output for human review.

## Current Implemented Workflow

1. Authorized scientist access is required.
2. The user completes the Scientist Input Module.
3. Required fields are validated.
4. The user-selected model is validated against allowed options.
5. SIS assembles private generation instructions.
6. Carter runs the job asynchronously.
7. A structured concept output is returned for review.

## Public Invention Modes

- Mechanism Discovery
- System Architecture
- Process Innovation
- Algorithmic Method
- Hybrid System Development
- Constraint-Inversion

The user selects the mode. The current public workflow does not describe SIS as autonomously selecting the invention mode.

## What Is Not Included

This repository does not include source code, private prompts, evaluator logic, scoring rules, model-routing internals, authentication logic, route names, function names, operational logs, raw user data, private examples, database schemas, secrets, or cloneable implementation details.

## Human Review

SIS outputs are invention candidates or research directions. They are not guarantees of novelty, patentability, feasibility, safety, engineering readiness, regulatory compliance, or commercial viability.
