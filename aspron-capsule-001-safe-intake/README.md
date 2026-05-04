# ASPRON Capsule 001 — Safe Intake

**The interface dissolves. The effect remains. The evidence survives.**

ASPRON is not just an app. It is a controlled lifecycle for temporary AI capability: **activate → act → prove → revoke**.

This folder contains Capsule 001: a client-side, no-backend, no-dependency proof for safe AI intake.

## What this proves

The capsule demonstrates a bounded workflow:

1. Detect sensitive input
2. Block raw input from AI-visible use
3. Generate a redacted copy with typed placeholders
4. Require human approval
5. Generate a summary from the approved redacted copy only
6. Export an evidence receipt
7. Dissolve the working interface while preserving evidence

## Run locally

Open `index.html` in a browser.

No package install is required.

## Replit setup

Create a new Replit project using the static HTML template, then upload or paste `index.html`.

If importing from GitHub, point Replit at this repository and use this folder as the demo entry point.

## Boundaries

This is a proof demo, not a production privacy or compliance system.

It does not store data, call a backend, or send content to an AI model. Risk detection is pattern-based and intentionally simple. Production ASPRON would require server-side policy enforcement, storage controls, authentication, review workflows, audit integrity, and legal/privacy review.

## Flywheel

**Capsules prove the pattern. The pattern opens the audit. The audit defines the next capsule.**

It is not a portfolio. It is a position.
