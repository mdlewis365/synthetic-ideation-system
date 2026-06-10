# Workflow Example

## 1. Overview

This is a simplified, sanitized example of how a user might use the Synthetic
Ideation System, or SIS, from Scientist Input Module entry through structured
concept output.

This example is public-safe documentation. It does not expose proprietary SIS
internals, private prompts, evaluator logic, scoring rules, backend
implementation details, model-routing internals, authentication details, or
Synthetic OS/Carter integrations.

## 2. Scenario

A user wants to explore a technical concept for improving energy efficiency in
small autonomous robotic systems.

The target systems are battery-powered robots that must operate for long periods
with limited onboard power, such as inspection robots, small field robots, or
mobile platforms used in constrained environments.

## 3. Scientist Input Module Entry

The user opens the Scientist Input Module and enters the required SIS inputs.

Sanitized example values:

- Exploration Vector: Adaptive energy conservation for small autonomous robots
- Target Exploration Domain: Battery-powered mobile robots, inspection robots,
  and small field robotics
- Objective Framing: Invent a mechanism that reduces energy consumption without
  requiring a larger battery
- Allowed Approaches: dynamic duty cycling, passive sensing, adaptive
  locomotion, environmental energy awareness, low-power standby modes
- Reject If: the concept depends on unrealistic battery chemistry, large
  external infrastructure, or continuous high-power computation

These required fields define the invention direction, domain, objective,
permissible approaches, and rejection boundaries for the SIS run.

## 4. Optional Invention-Control Fields

The user may also configure optional invention-control fields to further shape
the invention-vector process.

Sanitized example values:

- Search Forcing Function: Prefer mechanisms that reduce energy use by changing
  robot behavior rather than increasing battery capacity.
- Required Structural Lens: Treat the robot as a sensing, motion, compute, and
  power-management system.
- Discovery Mode: Look for a causal mechanism that links environmental
  awareness to reduced power demand.
- Causal Necessity Condition: The concept should reduce energy consumption only
  when the robot can safely lower sensing, compute, or motion activity.
- Prior-Art Collapse Pattern: Avoid simply proposing a larger battery, generic
  sleep mode, or standard low-power processor substitution.

These fields help the user shape the invention-vector process. They do not
disclose private prompt logic, scoring rules, evaluator behavior, or internal
governance mechanisms.

## 5. Language Model Selection

The user selects an available language model before initializing the vector.
SIS validates the selected model before generation begins.

This public example does not list private model-routing details, credentials,
provider-specific operational internals, or configuration details.

## 6. User-Selected Invention Mode

For this example, the user selects:

- Mechanism Discovery

The user selects Mechanism Discovery because the goal is to explore an
underlying mechanism for energy conservation rather than simply describe a
product feature.

SIS does not autonomously choose the Invention Mode. The mode is selected by the
user as part of the Scientist Input Module workflow.

## 7. Initialize Vector

After completing the required fields, optional controls, language model
selection, and Invention Mode selection, the user initializes the vector.

At a public architecture level, SIS then:

1. Validates the required inputs.
2. Assembles private internal generation instructions.
3. Validates the selected model against allowed options.
4. Starts an asynchronous generation job.
5. Returns a job identifier for output handling.

This example does not disclose backend source code, route names, function names,
lock names, job storage internals, prompt-construction logic, or other private
implementation details.

## 8. Sanitized Example Output

The following is a public-safe example of the kind of structured output SIS
might produce. It is provided as sanitized documentation, not as a validated
engineering design.

- Concept Name: Context-Aware Energy Gating for Small Autonomous Robots

- Problem Addressed: Small autonomous robots often waste energy by maintaining
  sensing, compute, and locomotion activity at levels that are higher than the
  immediate environment requires.

- Proposed Mechanism: The robot uses low-power environmental cues to determine
  when full sensing, compute, or locomotion activity is necessary. When the
  environment is stable or low-risk, the robot shifts selected subsystems into
  reduced-duty states. When uncertainty or task demand increases, the robot
  raises activity levels.

- Operating Principle: Energy demand is treated as a function of environmental
  uncertainty and task urgency. The robot conserves power by matching subsystem
  activity to the minimum level needed for safe progress, rather than operating
  all subsystems continuously at peak readiness.

- Potential Benefits:
  - Reduced average power consumption during low-risk operating periods
  - Longer mission duration without increasing battery size
  - Better alignment between sensing intensity, compute load, and motion demand
  - Potentially lower thermal load in compact robotic platforms

- Key Assumptions:
  - The robot can identify low-risk or stable operating conditions with
    low-power cues.
  - Reduced-duty operation does not compromise safety-critical perception.
  - The robot can transition between reduced and active states quickly enough
    for the intended task.
  - Mission requirements permit variable sensing, compute, or locomotion
    activity.

- Risks and Unknowns:
  - Incorrectly classifying a situation as low-risk could reduce awareness at
    the wrong time.
  - Frequent state transitions could reduce or eliminate the expected energy
    savings.
  - Some robot tasks may require continuous sensing or computation.
  - The mechanism may require careful validation across terrain, lighting,
    weather, obstacle density, and mission type.

- Human Review Notes:
  - A robotics engineer should review whether the proposed mechanism is
    compatible with the target robot's sensors, processor, motor control, and
    safety requirements.
  - A domain expert should identify which subsystems can safely enter
    reduced-duty operation.
  - Safety-critical applications should require additional validation before
    operational use.

- Suggested Next Validation Steps:
  - Define target robot class, mission profile, and power budget.
  - Identify candidate low-power environmental cues.
  - Estimate potential duty-cycle reductions for sensing, compute, and
    locomotion.
  - Compare expected energy savings against transition overhead.
  - Prototype the control concept in simulation before any field deployment.

## 9. Human Review and Limitations

SIS outputs require human review and follow-up validation.

SIS does not guarantee:

- Novelty
- Patentability
- Safety
- Feasibility
- Engineering readiness
- Commercial viability

The structured output should be treated as an invention candidate or research
direction, not as a validated technical conclusion.

## 10. Public Documentation Boundary

This example is intentionally simplified and sanitized for public GitHub
documentation.

The public repository excludes proprietary SIS engine code, prompts, evaluator
logic, scoring rules, governance internals, Carter/Synthetic OS integrations,
EAS internals, authentication details, backend implementation details,
JavaScript implementation details, model-routing internals, operational logs,
API keys, environment variables, database details, and private configuration.
