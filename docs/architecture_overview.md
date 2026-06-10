# Architecture Overview

## 1. System Purpose

The Synthetic Ideation System, or SIS, is a governed, user-directed
invention-vector system for generating structured technical concepts.

SIS is built around a Scientist Input Module that helps a user define an
invention objective, constrain the exploration space, select an Invention Mode,
select a language model, and initialize a governed generation process.

The purpose of SIS is to support disciplined invention work rather than
unstructured brainstorming. It helps turn a technical problem space into a
structured invention or concept output that can be reviewed by a human
researcher, engineer, or collaborator.

SIS is a research and development project by Michael Lewis / Synthetic OS Labs.

## 2. Design Philosophy

SIS is designed around governed ideation, structured workflows, traceability,
and feasibility awareness.

The system emphasizes:

- User-directed invention: the user defines the invention vector and selects the
  Invention Mode.
- Structured input: required fields establish the exploration domain,
  objective, allowed approaches, and rejection boundaries.
- Configurable control: optional invention-control fields allow the user to
  shape how the exploration should be constrained.
- Governed generation: submissions are validated before generation begins.
- Human review: SIS produces structured invention or concept outputs for review;
  it does not replace engineering validation, safety review, or patent analysis.

## 3. High-Level Workflow

At a public architecture level, SIS follows this workflow:

1. Authorized scientist access is required.
2. The user opens the Scientist Input Module.
3. The user enters required fields:
   - Exploration Vector
   - Target Exploration Domain
   - Objective Framing
   - Allowed Approaches
   - Reject If
4. The user may configure optional invention-control fields:
   - Search Forcing Function
   - Required Structural Lens
   - Discovery Mode
   - Causal Necessity Condition
   - Prior-Art Collapse Pattern
5. The user selects a Language Model.
6. The user selects an Invention Mode.
7. The user initializes the vector.
8. SIS validates the required inputs.
9. SIS assembles private internal generation instructions.
10. SIS validates the selected model against allowed model options.
11. SIS starts an asynchronous generation job.
12. SIS returns a job identifier and produces a structured governed
    invention/concept output for human review.

Publicly documented Invention Modes include:

- Mechanism Discovery
- System Architecture
- Process Innovation
- Algorithmic Method
- Hybrid System Development
- Constraint-Inversion

This public description intentionally avoids proprietary prompt content,
internal evaluator logic, scoring rules, model-routing details, and private
governance mechanisms.

## 4. Conceptual Components

### Scientist Input Module

The Scientist Input Module is the user-facing entry point for SIS. It collects
the invention-vector fields, optional invention-control fields, selected
language model, and selected Invention Mode.

### Required Scientist Inputs

Required Scientist Inputs define the minimum information needed to initialize a
governed invention vector:

- Exploration Vector
- Target Exploration Domain
- Objective Framing
- Allowed Approaches
- Reject If

These fields establish the direction, domain, framing, permissible approaches,
and rejection boundaries for the concept generation process.

### Optional Invention-Control Fields

Optional invention-control fields allow the user to further constrain or shape
the exploration:

- Search Forcing Function
- Required Structural Lens
- Discovery Mode
- Causal Necessity Condition
- Prior-Art Collapse Pattern

These controls are public-safe descriptions of user-configurable inputs. They do
not disclose private prompt logic or internal evaluator mechanisms.

### User-Selected Invention Mode

The user selects the Invention Mode. SIS does not autonomously choose the mode.

The selected mode provides high-level direction for the type of invention work
being requested, such as mechanism discovery, system architecture, process
innovation, algorithmic method development, hybrid system development, or
constraint-inversion exploration.

### Private Prompt Assembly Layer

After the user initializes the vector, SIS assembles a private internal master
prompt from the validated submission. This layer is part of the private SIS
implementation and is not documented in this repository beyond its high-level
role.

Proprietary prompts, prompt-construction methods, and internal instruction
content are intentionally excluded from the public repository.

### Model Selection and Validation Layer

The user selects a language model from available options. SIS validates that the
selected model is allowed before starting the generation job.

This overview does not disclose model-routing internals, private configuration,
provider-specific operational details, or any credentials.

### Job Execution Layer

SIS starts an asynchronous generation job after the submission and model
selection pass validation. The system returns a job identifier for output
handling.

This public overview does not disclose backend route names, function names,
lock names, storage internals, operational logs, or implementation-specific job
management details.

### Output/Reporting Layer

The output/reporting layer produces a structured governed invention or concept
summary for human review. Public-safe outputs may include a concept description,
technical framing, intended use, constraints, risks, and follow-up questions.

SIS outputs are intended to support further review, not to guarantee novelty,
patentability, feasibility, safety, or engineering readiness.

### Governance and Traceability Layer

The governance and traceability layer supports disciplined use of the SIS
workflow. At a public level, this means preserving alignment between the
submitted invention vector, selected mode, validated inputs, and structured
output.

Private governance mechanisms, internal evaluator logic, scoring rules, and
implementation details are intentionally not disclosed.

## 5. Public Repository Scope

This public repository contains only documentation, sanitized examples, and
public-safe architectural notes for the Synthetic Ideation System.

The following materials are intentionally excluded:

- Proprietary engine code
- Proprietary prompts
- Prompt-construction implementation details
- Internal evaluator logic
- Scoring rules
- Synthetic OS integrations
- Carter integrations
- Private governance mechanisms
- Backend route names, function names, or source-code details
- Model-routing internals
- Operational logs
- API keys, secrets, environment variables, private configuration, or database
  schemas

This repository is intended to communicate the public concept and architecture
of SIS without disclosing implementation details that would allow someone to
clone the full internal SIS/SOS system.

## 6. Example Use Cases

Public-safe example use cases include:

- Exploring technical product concepts
- Generating early-stage research directions
- Framing possible invention pathways at a high level
- Structuring invention-focused brainstorming sessions
- Producing concept summaries for later engineering review
- Framing research questions for mechanism, architecture, process, algorithmic,
  hybrid-system, or constraint-inversion exploration

## 7. Non-Goals

This public repository is not:

- The full SIS engine
- A replacement for engineering validation
- A patentability or prior-art search system
- A guarantee of novelty, patentability, safety, or feasibility
- A disclosure of proprietary Synthetic OS internals
- A disclosure of Carter/Synthetic OS source code or private governance logic

SIS can support structured invention-vector generation, but technical claims
still require appropriate review, validation, and domain expertise.

## 8. Development Status

SIS is an active research and development project. Public documentation may
evolve as the project matures, while proprietary implementation details remain
private.

## 9. Author

Created by Michael Lewis / Synthetic OS Labs.
