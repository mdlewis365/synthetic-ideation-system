# Platform Context

## 1. Overview

The Synthetic Ideation System, or SIS, is part of a larger private Synthetic OS
Labs research environment. Within that environment, SIS operates as one module
among multiple AI-assisted systems.

This public repository documents SIS only. It does not disclose private
application-host code, authentication implementation, internal prompts,
model-routing internals, operational logs, or proprietary Synthetic OS Labs
implementation details.

## 2. Private Application Host

The private Synthetic OS Labs application host can be understood publicly as an
authenticated gateway. At a high level, it provides authorized users with access
to different modules within the broader research environment.

The host is responsible for access-controlled entry into the environment and
for directing authorized users to the appropriate module. This public repository
does not describe backend route names, authentication logic, password handling,
session handling, private JavaScript behavior, or implementation-specific
backend details.

## 3. Module Map

At a public, high-level view, the private application environment includes
multiple modules:

- Carter Neural Console: a private general Carter interaction interface.
- Engineering Assistance System, or EAS: a private engineering assistance
  workflow.
- Synthetic Ideation System, or SIS: a governed invention-vector workflow built
  around the Scientist Input Module.

Only SIS is documented in this public repository.

## 4. SIS Boundary

This repository focuses on SIS public documentation, sanitized examples, and
public-safe architecture notes.

The SIS material here is intended to explain the public concept, workflow, and
architecture of a governed invention-vector system without exposing the private
engine, internal prompts, evaluator logic, scoring rules, governance mechanics,
or Synthetic OS Labs application internals.

## 5. What Is Not Included

This public repository does not include:

- Backend application host source code
- Login or authentication implementation
- Passwords or access-control details
- Carter Neural Console implementation
- EAS implementation
- Private SIS prompt logic
- Private governance mechanisms
- Model-routing internals
- Operational logs
- API keys, secrets, environment variables, or private configuration

These exclusions are intentional. The repository is designed to be safe for
public GitHub review while preserving the confidentiality of the larger private
Synthetic OS Labs environment.

## 6. Public Documentation Purpose

The purpose of this repository is to communicate the SIS concept, workflow, and
architecture in a portfolio-safe way for recruiters, engineers, researchers, and
potential collaborators.

The documentation is intended to show the design intent and public-facing
structure of SIS without enabling reconstruction of the private SIS/SOS
implementation.
