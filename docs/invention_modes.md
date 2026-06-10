# Invention Modes

## 1. Overview

Invention Modes define the type of invention work the user wants SIS to perform.
They provide high-level direction for how the invention vector should be
interpreted and what kind of concept output the user is requesting.

The user selects an Invention Mode before initializing the vector in the
Scientist Input Module.

## 2. User-Selected Mode Control

SIS is a governed, user-directed invention-vector system. The Invention Mode is
selected by the user as part of the Scientist Input Module workflow.

SIS does not autonomously choose the mode. The selected mode reflects the user's
intent for the session and works with the other SIS inputs to shape the
resulting invention or concept output.

## 3. Publicly Documented Modes

### Mechanism Discovery

Mechanism Discovery is used when the user wants to explore a possible
underlying mechanism, causal process, or operating principle.

This mode is appropriate when the invention direction depends on understanding
how something might work, what causal structure may be responsible for an
effect, or what mechanism could enable a new technical concept.

### System Architecture

System Architecture is used when the user wants to explore the structure of a
system.

This may include components, relationships, interfaces, dependencies,
subsystems, high-level organization, or the way different parts of a concept
could work together.

### Process Innovation

Process Innovation is used when the user wants to explore a new or improved
process, workflow, sequence of operations, or method of transformation.

This mode is useful for invention directions that focus on how something is
done, how a process can be changed, or how a sequence of steps can produce a
different technical or practical outcome.

### Algorithmic Method

Algorithmic Method is used when the user wants to explore a computational,
mathematical, procedural, or decision-making method.

This mode can apply to software concepts, analytical procedures, optimization
methods, classification approaches, control logic at a conceptual level, or
other structured methods for producing a result.

### Hybrid System Development

Hybrid System Development is used when the user wants to explore a concept that
combines multiple system types, domains, mechanisms, or architectural layers.

This mode is appropriate when the invention direction depends on integration,
cross-domain synthesis, or combining distinct technical elements into a
coherent system concept.

### Constraint-Inversion

Constraint-Inversion is used when the user wants to treat a constraint,
limitation, bottleneck, or failure condition as the source of the invention
direction.

Rather than treating the constraint only as a blocker, this mode frames the
constraint as a potential driver for a new mechanism, process, architecture, or
method.

## 4. How Modes Relate to the Invention Vector

The selected Invention Mode works together with the user's required SIS inputs:

- Exploration Vector
- Target Exploration Domain
- Objective Framing
- Allowed Approaches
- Reject If

These fields define the invention direction, domain, objective, permissible
approaches, and rejection boundaries.

Optional invention-control fields can further shape the result:

- Search Forcing Function
- Required Structural Lens
- Discovery Mode
- Causal Necessity Condition
- Prior-Art Collapse Pattern

Together, the selected mode and the invention-vector fields help structure the
generation process and the resulting concept summary.

## 5. Public Documentation Boundary

This file explains only the public meaning of each Invention Mode.

The public repository does not include private prompt logic, evaluator logic,
scoring rules, governance implementation, backend source code, route names,
JavaScript implementation details, model-routing internals, operational logs,
database details, API keys, environment variables, Carter/Synthetic OS internals,
or EAS internals.

Those proprietary SIS implementation details remain private.

## 6. Human Review

Mode selection helps structure SIS invention output, but the output still
requires human review, domain validation, and appropriate follow-up analysis.

SIS does not guarantee:

- Novelty
- Patentability
- Safety
- Feasibility
- Engineering readiness
- Commercial viability

Generated concepts should be treated as structured invention candidates or
research directions, not as validated technical conclusions.
