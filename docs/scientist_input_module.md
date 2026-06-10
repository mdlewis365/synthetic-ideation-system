# Scientist Input Module

## 1. Overview

The Scientist Input Module is the public-facing SIS input workflow for defining
and initializing an invention vector.

It is the entry point where a user frames the invention objective, defines the
exploration boundaries, selects a language model, selects an Invention Mode, and
submits the vector for validation and governed generation.

## 2. Variable Vector Entry Phase

The Scientist Input Module supports the Variable Vector Entry Phase: Invention
Cycle Alignment.

In this phase, the user provides structured inputs that define:

- The invention direction
- The target exploration domain
- The objective framing
- The allowed approaches
- The rejection boundaries

These inputs help SIS treat ideation as a structured invention workflow rather
than an open-ended brainstorming session.

## 3. Required Scientist Inputs

### Exploration Vector

The Exploration Vector defines the core direction of the invention search. It
captures what the user wants SIS to explore and establishes the central
technical or conceptual trajectory for the session.

### Target Exploration Domain

The Target Exploration Domain identifies the technical, scientific, product, or
system area in which the invention vector should operate. It helps bound the
context so the generated output remains aligned with the intended domain.

### Objective Framing

Objective Framing describes the goal of the exploration. It clarifies what the
user is trying to discover, improve, design, invert, or formulate.

### Allowed Approaches

Allowed Approaches define the kinds of methods, mechanisms, design directions,
or conceptual strategies that are acceptable for the invention-vector process.
This field helps guide the exploration toward approaches the user considers
valid or useful.

### Reject If

Reject If defines boundaries for concepts that should be avoided. It can
describe disallowed assumptions, unacceptable solution types, infeasible
directions, or conditions that should cause a concept to be treated as outside
the intended exploration scope.

## 4. Optional Invention-Control Fields

Optional invention-control fields allow the user to shape the invention-vector
process more precisely. These controls are user-facing configuration fields and
do not disclose private SIS implementation details.

### Search Forcing Function

The Search Forcing Function lets the user apply an additional directional
constraint or pressure to the exploration. It can be used to encourage a
particular style of search, such as looking for overlooked mechanisms,
underexplored design paths, or unconventional technical structures.

### Required Structural Lens

The Required Structural Lens specifies a perspective that generated concepts
should account for. Examples might include architecture, mechanism, process,
constraint, interface, or system-relationship perspectives.

### Discovery Mode

Discovery Mode provides optional guidance about the character of the desired
exploration. It can help shape whether the session is oriented toward discovery,
comparison, synthesis, transformation, or another public-safe framing.

### Causal Necessity Condition

The Causal Necessity Condition describes a condition that a concept should
satisfy at the level of cause, mechanism, or dependency. It helps the user
state what must be true for a proposed concept to be meaningful or relevant.

### Prior-Art Collapse Pattern

The Prior-Art Collapse Pattern allows the user to describe a known or crowded
solution pattern that SIS should avoid simply reproducing. This helps orient
the exploration away from obvious or already familiar concept paths.

## 5. Language Model Selection

The user can select an available language model before initializing the vector.
SIS validates the selected model before generation begins.

This public documentation does not list private model-routing details,
provider-specific configuration, credentials, or operational model-selection
internals.

## 6. User-Selected Invention Mode

The user selects the Invention Mode. SIS does not autonomously choose the mode.

Publicly documented Invention Modes include:

- Mechanism Discovery
- System Architecture
- Process Innovation
- Algorithmic Method
- Hybrid System Development
- Constraint-Inversion

The selected mode provides high-level direction for the kind of invention work
the user wants SIS to perform.

## 7. Initialize Vector

Initializing the vector submits the structured SIS input for validation and
governed generation.

At a public level, this means SIS checks that the required inputs are present,
validates the selected model, and begins the governed generation process. This
document does not disclose private prompt assembly, backend implementation, or
job-execution details.

## 8. Human Review

SIS output is intended for human review and further validation.

SIS does not guarantee:

- Novelty
- Patentability
- Safety
- Feasibility
- Engineering readiness
- Commercial viability

Generated invention or concept outputs should be reviewed by appropriate
researchers, engineers, domain experts, or legal professionals before being
treated as validated technical work.

## 9. Public Documentation Boundary

This file documents only the public-safe, user-facing structure of the
Scientist Input Module.

The public repository does not include backend source code, JavaScript
implementation details, route names, function names, authentication logic,
prompt-construction logic, private prompts, evaluator logic, scoring rules,
model-routing internals, API keys, environment variables, database details,
operational logs, or Synthetic OS/Carter private implementation details.

Proprietary SIS internals remain private.
