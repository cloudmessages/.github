# Contributing

Thank you for contributing to CloudMessages. This initiative is complementary to CloudEvents and aims to standardise message envelopes, semantics, correlation, and lifecycle guidance for commands, queries, and their responses without over-standardising business payloads.

## How to propose changes

1. Open an issue describing the problem, motivation, and proposed outcome.
2. For normative specification changes, start with a proposal or RFC before opening a large pull request.
3. Keep changes narrowly scoped so reviewers can distinguish semantics, guidance, schemas, and examples.

## How specs evolve

Normative changes should move through the governance decision process. Minor editorial and non-normative clarifications may proceed by pull request and lazy consensus.

## Expectations for examples and SDKs

Examples should demonstrate transport-agnostic semantics and realistic correlation, request tracking, and tracing.

SDKs should remain small, readable, and aligned with the current draft specifications rather than inventing new semantics.

## Content quality bar

Keep normative and non-normative text clearly separated.

Preserve compatibility where possible and make compatibility impact explicit when it cannot be avoided.

Avoid over-standardising business payloads. CloudMessages standardises the outer envelope and processing semantics, not universal domain models or query languages.
