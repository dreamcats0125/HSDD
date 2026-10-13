# Asset Naming and Versioning Standard

Version: 1.0

Status: Active

---

# Purpose

This document defines naming and versioning rules for all HSDD assets.

The objective is to ensure:

- Consistency
- Searchability
- Traceability
- Long-term maintainability

across all repositories and systems.

---

# Naming Principles

File names should be:

- Clear
- Predictable
- Searchable
- Human readable

Avoid:

- Spaces
- Ambiguous abbreviations
- Temporary names
- Generic filenames

Examples:

✅ Good

Enterprise-Identity-v1.1.md

Corporate-Governance-v1.0.md

Spatial-Culture-v1.0.md

---

❌ Avoid

Final.doc

NewFile.md

Test.md

Untitled.md

---

# Standard Format

```text
[Asset-Name]-v[Major].[Minor].md
```

Example:

```text
Enterprise-Identity-v1.1.md

Corporate-Culture-v1.0.md

Operations-Handbook-v1.0.md
```

---

# Asset Categories

## Identity

Prefix:

```text
Identity-
```

Examples:

```text
Identity-Framework-v1.0.md
```

---

## Governance

Prefix:

```text
Governance-
```

Examples:

```text
Governance-Model-v1.0.md
```

---

## Operations

Prefix:

```text
Operations-
```

Examples:

```text
Operations-Handbook-v1.0.md
```

---

## Style

Prefix:

```text
Style-
```

Examples:

```text
Style-Language-v1.0.md

Style-System-v1.0.md
```

---

## Spatial

Prefix:

```text
Spatial-
```

Examples:

```text
Spatial-Culture-v1.0.md

Spatial-Pattern-v1.0.md
```

---

## Narrative

Prefix:

```text
Narrative-
```

Examples:

```text
Narrative-Matrix-v1.0.md
```

---

## Media

Prefix:

```text
Media-
```

Examples:

```text
Media-Framework-v1.0.md
```

---

## Body

Prefix:

```text
Body-
```

Examples:

```text
Body-Data-v1.0.md

Body-Framework-v1.0.md
```

---

## Protocol

Prefix:

```text
Protocol-
```

Examples:

```text
Protocol-Shadow-Revenue-v1.0.md
```

---

# Body Asset Naming

Virtual body assets follow a vector-based convention.

---

## Pose Vector

```text
PV-[Owner]-[Index]
```

Examples:

```text
PV-MIN-001
PV-MIN-002
```

---

## Motion Grammar

```text
MG-[Owner]-[Index]
```

Examples:

```text
MG-MIN-001
```

---

## Emotion Vector

```text
EV-[Owner]-[Index]
```

Examples:

```text
EV-MIN-001
```

---

## Style Vector

```text
SL-[Owner]-[Index]
```

Examples:

```text
SL-MIN-001
```

---

# Versioning Rules

HSDD uses semantic versioning.

Format:

```text
vMajor.Minor
```

---

## Major Version

Structural changes.

Examples:

```text
v1.0 → v2.0
```

When:

- Architecture changes
- Scope changes
- Governance changes

---

## Minor Version

Content updates.

Examples:

```text
v1.0 → v1.1
v1.1 → v1.2
```

When:

- New sections added
- Existing sections refined
- Clarifications made

---

# Asset Status

Each asset should contain:

```text
Status: Draft
Status: Active
Status: Review
Status: Deprecated
Status: Archived
```

---

# Asset Lifecycle

```text
Draft
    ↓
Review
    ↓
Active
    ↓
Deprecated
    ↓
Archived
```

---

# Repository Rule

Official assets must never overwrite previous major versions.

Examples:

✅

Enterprise-Identity-v1.0.md

Enterprise-Identity-v1.1.md

Enterprise-Identity-v2.0.md

---

❌

Enterprise-Identity.md

(without version history)

---

# Objective

The objective of naming is not organization.

The objective is continuity.

A document should remain understandable,
traceable,
and maintainable
years after its creation.

---

# Revision History

v1.0

- Initial naming standard
- Asset classification model
- Body vector naming model
- HSDD versioning rules
