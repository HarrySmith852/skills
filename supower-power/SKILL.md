---
name: supower-power
description: Use when Codex needs to choose, sequence, or enforce Superpowers-style workflows for software development tasks, especially before brainstorming, planning, debugging, test-driven implementation, code review, verification, or finishing a development branch.
---

# Supower Power

## Overview

Choose the smallest Superpowers workflow that protects the task from sloppy execution. Use this skill to decide what process skill should run next, what gate must be satisfied, and what evidence is required before claiming progress.

## Workflow Selection

Map the user's request to the relevant workflow:

- New feature, behavior change, or creative implementation: use brainstorming first.
- Multi-step implementation from an approved design: use writing-plans, then executing-plans.
- Bug, failing test, crash, or unexpected behavior: use systematic-debugging before proposing fixes.
- Feature or bugfix implementation: use test-driven-development unless the user explicitly rules it out.
- Review request: use code-review posture and report findings before summaries.
- Review feedback from another person or agent: use receiving-code-review before changing code.
- Work appears complete: use verification-before-completion before claiming success.
- Branch is ready to merge or hand off: use finishing-a-development-branch.
- Two or more independent workstreams exist: consider dispatching-parallel-agents or subagent-driven-development.

## Operating Rules

- Invoke the process skill before taking the action it governs.
- Keep the process proportional: use the full workflow for risky or ambiguous work, and a compact version for tiny changes.
- Do not skip a required gate because the task looks simple.
- If workflows conflict, follow explicit user instructions first, then the stricter workflow rule.
- State which workflow is being used and why in one short sentence.
- Prefer evidence from files, commands, tests, or logs over intuition.

## Execution Checklist

1. Classify the task type from the user's latest request.
2. Name the workflow skill or skills that apply.
3. Check for gates: approval, written plan, failing test, review, or verification.
4. Run the next required workflow step.
5. Before final response, confirm what was done and what evidence supports it.
