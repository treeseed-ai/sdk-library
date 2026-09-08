---
schemaVersion: treeseed.knowledge-page/v1
id: core-objective
bookId: sdk-core
slug: core-objective
title: SDK Core Objective
summary: Define and maintain the stable contracts, clients, and integration
  surfaces that let TreeSeed components coordinate safely and reproducibly.
status: published
visibility: team
order: 0
contributors: []
relatedBookIds: []
relatedKnowledgeIds: []
relatedNoteIds: []
relatedQuestionIds: []
relatedObjectiveIds: []
relatedProposalIds: []
relatedDecisionIds: []
guaranteeIds: []
audiences:
  primary:
    - TreeSeed agents
    - TreeSeed maintainers
  secondary:
    - TreeSeed integrators
  excluded: []
capabilityIds: []
routePatterns: []
resourceTypes: []
actionIds: []
keywords: []
documentationUrls: []
---

The SDK project defines the shared contracts and supported client surfaces used across TreeSeed. Its core objective is to keep those interfaces explicit, typed, versioned, reproducible, and safe for independent package and service evolution.

Work in this project should preserve compatibility where promised, expose authoritative execution and knowledge provenance, and keep cross-project coordination independent of any single repository while retaining exact team, project, agent, and immutable-reference identity.

