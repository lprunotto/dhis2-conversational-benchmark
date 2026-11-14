# DHIS2 Conversational Benchmark

An open-source research project for reproducible evaluation of conversational AI agents interacting with DHIS2.

## Motivation

Natural-language interfaces to health information systems must translate user requests into correct metadata selections and analytical queries. Their reliability can depend on model capabilities, tool usage, clarification strategies, and conversational state management.

This project aims to provide a reproducible environment for systematically evaluating these capabilities.

## Project objectives

- Provide a locally reproducible DHIS2 environment.
- Develop a fully synthetic, publicly distributable benchmark dataset.
- Define single-turn and multi-turn evaluation scenarios.
- Implement automated evaluation and conversational user simulation.
- Support comparisons between different LLMs and agent architectures.

## Current status

**Phase 1 — Local development environment**

The initial environment uses the public DHIS2 Sierra Leone demo database for development and infrastructure validation.

The demo database is temporary and is not the final benchmark dataset.

## Scope

This repository is independent of ICRC systems and does not require ICRC infrastructure, credentials, or proprietary source code.

## Development

See `docs/phase-1-setup.md` for environment setup instructions and `docs/phase-1-validation.md` for validation procedures.

## Roadmap

1. Reproducible DHIS2 environment
2. Synthetic benchmark dataset
3. Evaluation scenarios and ground truth
4. Conversational user simulator
5. Agent architecture and model comparisons
6. Reproducibility study and publication preparation

## License

See `LICENSE`.