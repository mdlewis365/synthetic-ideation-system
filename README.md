# Synthetic Ideation System

The **Synthetic Ideation System**, or **SIS**, is a governed, user-directed invention-vector system for generating structured technical concepts.

SIS is built around a **Scientist Input Module** that allows a user to define an invention objective, constrain the exploration space, select an Invention Mode, select a language model, and initialize a governed generation process.

This repository contains public-safe documentation for SIS. Proprietary engine code, private prompts, evaluator logic, scoring rules, Carter/Synthetic OS integrations, EAS internals, authentication logic, model-routing internals, and operational implementation details are intentionally excluded.

## Platform Context

SIS operates as one module within a larger private Synthetic OS Labs research environment.

That private platform provides authenticated access to multiple systems, including:

* **Carter Neural Console** — a private Carter interaction interface
* **EAS** — Engineering Assistance System
* **SIS** — Synthetic Ideation System

This repository focuses only on the public-safe SIS architecture, workflow, and documentation.

## What SIS Does

SIS supports disciplined invention work by helping a user move from a technical problem space to a structured invention or concept output.

At a high level, SIS helps organize:

* Exploration vectors
* Target exploration domains
* Objective framing
* Allowed approaches
* Rejection boundaries
* Invention-control parameters
* User-selected invention modes
* Structured concept output for human review

SIS is intended to support ideation and early-stage technical exploration. It does not replace engineering validation, safety review, patent analysis, or expert domain judgment.

## High-Level Workflow

At a public architecture level, SIS follows this workflow:

1. Authorized scientist access is required.
2. The user opens the Scientist Input Module.
3. The user enters required invention-vector fields.
4. The user may configure optional invention-control fields.
5. The user selects a language model.
6. The user selects an Invention Mode.
7. The user initializes the vector.
8. SIS validates the required inputs.
9. SIS assembles private internal generation instructions.
10. SIS validates the selected model against allowed options.
11. SIS starts an asynchronous generation job.
12. SIS produces a structured governed invention/concept output for human review.

## Required Scientist Inputs

The Scientist Input Module uses the following required fields:

* **Exploration Vector**
* **Target Exploration Domain**
* **Objective Framing**
* **Allowed Approaches**
* **Reject If**

These inputs define the invention direction, domain, objective, permissible approaches, and rejection boundaries.

## Optional Invention-Control Fields

SIS also supports optional control fields that allow the user to shape the invention-vector process:

* **Search Forcing Function**
* **Required Structural Lens**
* **Discovery Mode**
* **Causal Necessity Condition**
* **Prior-Art Collapse Pattern**

These are public-safe descriptions of user-configurable inputs. This repository does not disclose the private prompt logic or internal implementation behind these controls.

## Publicly Documented Invention Modes

The user selects the Invention Mode. SIS does not autonomously choose the mode.

Publicly documented Invention Modes include:

* **Mechanism Discovery**
* **System Architecture**
* **Process Innovation**
* **Algorithmic Method**
* **Hybrid System Development**
* **Constraint-Inversion**

## Repository Contents

This public repository may include:

* Public-safe architecture notes
* SIS platform context
* Scientist Input Module documentation
* Sanitized workflow examples
* Sanitized concept-output examples
* Screenshots or diagrams that do not expose private implementation details

## What Is Not Included

This repository does **not** include:

* Proprietary SIS engine code
* Proprietary prompts
* Prompt-construction implementation details
* Internal evaluator logic
* Scoring rules
* Private governance mechanisms
* Carter/Synthetic OS source code
* EAS implementation details
* Authentication or password-handling logic
* Backend route names or function names
* Model-routing internals
* Operational logs
* API keys, secrets, environment variables, private configuration, or database schemas

The goal of this repository is to communicate the public concept and architecture of SIS without disclosing implementation details that would allow someone to clone the full internal SIS/SOS system.

## Example Use Cases

Public-safe SIS use cases include:

* Exploring technical product concepts
* Generating early-stage research directions
* Framing possible invention pathways at a high level
* Structuring invention-focused brainstorming sessions
* Producing concept summaries for later engineering review
* Framing research questions for mechanism, architecture, process, algorithmic, hybrid-system, or constraint-inversion exploration

## Limitations

SIS outputs are structured ideation artifacts. They are not guarantees of:

* Novelty
* Patentability
* Safety
* Feasibility
* Engineering readiness
* Commercial viability

Technical claims still require appropriate review, validation, and domain expertise.

## Development Status

SIS is an active research and development project by **Michael Lewis / Synthetic OS Labs**.

Public documentation may evolve as the project matures, while proprietary implementation details remain private.

## Author

Created by **Michael Lewis / Synthetic OS Labs**.

