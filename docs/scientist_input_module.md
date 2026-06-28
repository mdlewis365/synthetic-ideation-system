# Scientist Input Module

## Overview

The Scientist Input Module is the SIS user-facing workflow for defining an invention vector.

## Required Fields

- Exploration Vector: the core direction of the invention search.
- Target Exploration Domain: the technical or scientific area for exploration.
- Objective Framing: what the user is trying to discover, design, invert, or formulate.
- Allowed Approaches: methods or concept families the user permits.
- Reject If: disallowed assumptions, obvious paths, or unacceptable concept types.

SIS validates that these required fields are present before starting a job.

## Optional Controls

- Search Forcing Function
- Required Structural Lens
- Discovery Mode
- Causal Necessity Condition
- Prior-Art Collapse Pattern

These controls shape the invention-vector process. They are public-facing configuration fields, not a disclosure of private prompt logic.

## Model and Mode Selection

The user selects an allowed model and an Invention Mode before initializing the vector. SIS validates the model selection and uses the selected mode in private prompt assembly.

## What Is Not Included

This file does not include private prompt templates, JavaScript implementation details, backend routes, function names, model-routing internals, credentials, or logs.
