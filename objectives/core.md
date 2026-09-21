---
schemaVersion: treeseed.objective/v1
id: sdk-core
projectId: sdk
title: TreeSeed SDK Core Objective
outcome: TreeSeed SDK provides the programmatic platform substrate for TreeSeed content, control-plane state, graph-first context, workflow orchestration, reconciliation, hosting, package workflows, shared contracts, and TreeDX integration while preserving its package boundary.
status: active
---

TreeSeed SDK exists to provide the programmatic platform substrate for TreeSeed content, control-plane state, graph-first context, workflow orchestration, reconciliation, hosting, package workflows, shared contracts, and TreeDX integration.

This core objective is the starting direction for the TreeSeed SDK Knowledge Hub. It should influence every package-local workday, research note, implementation proposal, generated artifact, approval request, and release-readiness summary.

SDK owns portable primitives and shared contracts. It must not import from package implementations above it, own UI routes, run provider execution, serve the backend API, or encode TreeDX internals as product semantics.

Agents working in this project should keep outputs grounded in the package README, package-local source evidence, and the TreeSeed package ownership map. When a task would cross into another package's authority, the agent should describe the boundary and route the work to the correct project instead of mutating outside this hub.
