# Architecture Overview

## Purpose

SIS supports disciplined invention work by turning a user's technical exploration vector into a structured concept output.

## Public Architecture

At a public-safe level, SIS includes:

- Scientist Input Module for structured invention-vector entry
- required input validation
- optional invention-control inputs
- user-selected invention mode
- user-selected allowed model
- private prompt assembly
- asynchronous Carter job execution
- structured output for human review

## Runtime Context

SIS runs inside the private Synthetic OS Labs application environment and uses Carter as the execution runtime. The public repository documents SIS only at a conceptual workflow level.

## Current Governance Boundary

The active SIS submission path is governed through structured inputs, required-field validation, selected-mode constraints, private prompt assembly, and Carter execution. Separate invention-gate helper code exists in the private codebase, but it was not found wired into the active SIS web submission path during this staging pass, so it is not described here as active runtime architecture.

## What Is Not Included

This document excludes private prompts, evaluator code, scoring rules, route names, function names, model routing, authentication internals, source code, operational logs, and raw user data.
