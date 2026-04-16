# Cross-Reference: The Project's Nervous System

## What This Is

A machine-readable and human-readable index of every key concept and which files define, reference, or depend on it. When a concept evolves in one file, use this to find every other file that needs updating.

**How to use:**
1. A concept changes in file X → Check this document → Find every file that defines, references, or should reference it → Update all of them
2. Writing a new file → Check this document → Add it to every concept it touches
3. Reading any file → Check this document → Understand where it fits in the larger web

## Concept Index

---

### Survivorship Chain

**Definition**: `framework/00-core-logic.md`
**Also defines**: `framework/reflection-survivorship-and-agency.md` (passive vs chosen survival)
**References**: `README.md`, `framework/00-core-logic.md` (self)
**Implicitly uses**: `motivation/motivation-journey-map.md`, `risk/risk-analysis.md` (Risk 2), `assessment/assessment-design.md`, `motivation/cost-of-inaction.md`
**SHOULD reference but doesn't**: `cost-of-inaction.md`, `motivation-journey-map.md`, `risk/risk-analysis.md`

**If this concept changes**: Update `00-core-logic.md` → then `README.md` → then check `motivation-journey-map.md` (does the "default journey" still align?), `cost-of-inaction.md` (same argument), `risk/risk-analysis.md` (Risk 2 about parent resistance is the survivorship chain in action)

---

### Galaxy of Spirits ⭐ THE CORE

**Definition**: `framework/galaxy-of-spirits.md`
**References**: `00-core-logic.md`, `README.md` (priority order), `framework/ai-ecosystem-vision.md` (parent tool), `CONNECTOR-MAP.md`
**Implicitly uses**: `cost-of-inaction.md` ("100 children" is spirit-collection concept), `risk/risk-analysis.md`
**SHOULD reference but doesn't**: `cost-of-inaction.md`, `reflection-survivorship-and-agency.md`

**If this concept changes**: This is the most important document. If its definition evolves (e.g., what counts as a "spirit"), update `README.md` priority order, `00-core-logic.md` (proof section), `ai-ecosystem-vision.md` (Galaxy of Spirits Library tool). Also update `galaxy-of-problems.md` (the two galaxies are paired).

---

### 主体性 (Agency)

**Definition**: `motivation/zhutixing-model.md` (progression model), `framework/00-philosophy.md` (measurable outcome)
**References**: All stage files (`01-stage-seedling.md` through `05-stage-architect.md`), `motivation/motivation-architecture.md`, `assessment/assessment-design.md`, `README.md`
**Implicitly uses**: `reflection-survivorship-and-agency.md`, `healing-the-13-year-old.md`, `motivation/ai-integration.md`
**SHOULD reference but doesn't**: `reflection-survivorship-and-agency.md` (entire document about recovering agency), `healing-the-13-year-old.md` (co-pilot is 主体性 at any age), `ai-integration.md` (guiding question is about agency)

**⚠️ INCONSISTENCY**: `zhutixing-model.md` defines 5 stages (ages 2-18), but `lifelong-galaxy.md` extends to 9 stages including adults. The 主体性 model should be unified with lifelong stages 6-9.

**If this concept changes**: Update `zhutixing-model.md` → `00-philosophy.md` → all stage files → `motivation-architecture.md` → `assessment/assessment-design.md`. Check `lifelong-galaxy.md` for consistency (adult stages).

---

### Co-Pilot Principle

**Definition**: `framework/healing-the-13-year-old.md` (parent-as-co-pilot table), `framework/lifelong-galaxy.md` (co-pilot arrangement)
**References**: `CONNECTOR-MAP.md`, `framework/resource-requirements-ai-facilitation.md` (human-irreducible)
**Implicitly uses**: `01-stage-seedling.md`, `ai-ecosystem-vision.md`
**SHOULD reference but doesn't**: `01-stage-seedling.md` (the co-pilot model IS the seedling approach), `ai-ecosystem-vision.md` (you + AI = co-pilot)

**If this concept changes**: Update `healing-the-13-year-old.md` → `lifelong-galaxy.md` → `resource-requirements-ai-facilitation.md` → `01-stage-seedling.md` (what does co-piloting look like at age 2?)

---

### 80/20 Principle

**Definition**: `motivation/motivation-architecture.md` (80% motivation / 20% scaffolding)
**Also defines**: `framework/03-stage-builder.md` (80% design effort)
**References**: `05-stage-architect.md` (80/20 in exam season), `mapping/methodology.md`
**Implicitly uses**: `04-stage-investigator.md` (80/20 in journal review), `resource-requirements-ai-facilitation.md`
**SHOULD reference but doesn't**: `04-stage-investigator.md` (has 80/20 section but doesn't cite motivation-architecture.md)

**If this concept changes**: Update `motivation-architecture.md` → `03-stage-builder.md` → `05-stage-architect.md` → `mapping/methodology.md` → `04-stage-investigator.md`

---

### Journaling / Presencing

**Definition**: `motivation/motivation-architecture.md` (journaling as instrument, Presencing inspiration)
**References**: `03-stage-builder.md` (Builder's Journal), `04-stage-investigator.md` (Investigator's Log), `05-stage-architect.md` (Weekly Reflection), `resource-requirements-ai-facilitation.md` (AI journaling analysis)
**Implicitly uses**: `01-stage-seedling.md` (parent observation log), `02-stage-explorer.md` (investigation journals), `assessment/assessment-design.md`
**SHOULD reference but doesn't**: `01-stage-seedling.md`, `02-stage-explorer.md`, `assessment/assessment-design.md`

**If this concept changes**: Update `motivation-architecture.md` → all stage files (check for consistency) → `resource-requirements-ai-facilitation.md` (AI analysis section) → `assessment/assessment-design.md` (journal analysis for assessment)

---

### AI Integration Philosophy

**Definition**: `motivation/ai-integration.md` (stage-by-stage philosophy)
**Also defines**: `framework/resource-requirements-ai-facilitation.md` (what AI handles vs human), `framework/ai-ecosystem-vision.md` (open-source ecosystem)
**Reference each other correctly**: All three cross-reference each other
**Implicitly uses**: `assessment/gaokao-readiness.md` (AI-assisted weak area identification)
**SHOULD reference but doesn't**: `gaokao-readiness.md`

**⚠️ Nuance**: `ai-ecosystem-vision.md` says "60-80% of every resource requirement" as a simplification. `resource-requirements-ai-facilitation.md` has the stage-by-stage breakdown (Seedling ~80%, Investigator ~60%, etc.). Keep the vision doc's simplification but link to the detail doc.

**If this concept changes**: These three docs are well-linked. Check `gaokao-readiness.md` when AI exam prep concepts change.

---

### Motivation Journey Map

**Definition**: `motivation/motivation-journey-map.md` (decline and counter-attack by age)
**References**: `cost-of-inaction.md`, `resource-requirements-ai-facilitation.md` (cross-referenced)
**Should cross-reference**: `zhutixing-model.md` (both are age-based progression models), `00-core-logic.md` (explains how the chain destroys motivation)

**If this concept changes**: Update `motivation-journey-map.md` → check `zhutixing-model.md` for alignment → check `00-core-logic.md` → check `resource-requirements-ai-facilitation.md` (stage-by-stage resources map to the journey stages)

---

### Cost of Inaction

**Definition**: `motivation/cost-of-inaction.md` (what the traditional system destroys)
**References**: `motivation-journey-map.md` (cited as trajectory)
**Should reference**: `00-core-logic.md` (same survivorship chain argument), `galaxy-of-spirits.md` (the "100 children" counterfactual is the spirit-collection concept)
**Implicitly uses**: Risk analysis themes

**If this concept changes**: Update `cost-of-inaction.md` → check `00-core-logic.md` (same argument) → check `galaxy-of-spirits.md` (spirit collection as proof against the cost) → check `risk/risk-analysis.md`

---

### Test-to-Problem Transformation

**Definition**: `mapping/methodology.md` (formula + 5 steps + 5 patterns)
**Subject-specific mappings**: `mapping/math-mapping.md`, `mapping/yuwen-mapping.md`, `mapping/science-mapping.md`
**References**: `00-philosophy.md`, `README.md`, `assessment/gaokao-readiness.md`
**Subject maps reference**: `methodology.md` but don't cross-reference each other

**If this concept changes**: Update `methodology.md` → verify `math-mapping.md`, `yuwen-mapping.md`, `science-mapping.md` still follow the formula → check `00-philosophy.md` → check `gaokao-readiness.md`

---

### Assessment Design

**Definition**: `assessment/assessment-design.md` (non-zero-sum), `assessment/gaokao-readiness.md` (exam competitiveness)
**References**: `risk/risk-analysis.md` (Risk 1 mitigation), `README.md`
**SHOULD cross-reference**: Each other (complementary), `motivation-architecture.md` (assessment tied to motivation)

**If this concept changes**: Update `assessment-design.md` ↔ `gaokao-readiness.md` (check both) → check `risk/risk-analysis.md` → check `README.md`

---

### Risk Analysis

**Definition**: `risk/risk-analysis.md` (8 major risks + mitigations)
**References**: `05-stage-architect.md` (cited), `gaokao-readiness.md` (cited)
**Should reference**: `cost-of-inaction.md` (cost argument supports risk assessment), `ai-ecosystem-vision.md` (equity solution)

**Risk-to-Document Mapping**:
- Risk 1 (高考 disadvantage) → `gaokao-readiness.md`, `mapping/` docs
- Risk 2 (Parent resistance) → `cost-of-inaction.md`, Galaxy of Spirits
- Risk 3 (Teacher capability) → `ai-integration.md`, `resource-requirements-ai-facilitation.md`
- Risk 4 (Motivation ≠ exam) → `motivation-journey-map.md`, `assessment/gaokao-readiness.md`
- Risk 5 (Island school) → `assessment/assessment-design.md`
- Risk 6 (AI dependency) → `ai-integration.md`
- Risk 7 (Equity) → `ai-ecosystem-vision.md` (open-source solves this)
- Risk 8 (Extraordinary people) → `resource-requirements-ai-facilitation.md` (AI handles scale)

---

### Lifelong Galaxy (Stages 6-9)

**Definition**: `framework/lifelong-galaxy.md` (Rediscoverer through Elder-Witness)
**References**: `CONNECTOR-MAP.md`, `README.md` (updated)
**Should reference**: `zhutixing-model.md` (agency progression should extend to stages 6-9), `reflection-survivorship-and-agency.md` (Stage 6 IS the survivorship shift)

**If this concept changes**: Update `lifelong-galaxy.md` → `README.md` → check `zhutixing-model.md` for 主体性 progression consistency → check `reflection-survivorship-and-agency.md` (the personal shift IS Stage 6)

---

### Galaxy of Problems

**Definition**: `framework/galaxy-of-problems.md` (universe of real-world problems)
**References**: `00-core-logic.md` (framework map), `galaxy-of-spirits.md` (needs Galaxy of Spirits), `ai-ecosystem-vision.md` (Galaxy Explorer tool)
**Implicitly uses**: `mapping/methodology.md`, all stage files

**Pairing**: Galaxy of Problems = WHERE you explore. Galaxy of Spirits = WHY you explore. Always mention them together.

---

## Orchestration Rules

### Rule 1: When a Concept Changes in One File

```
1. Identify the concept (use this document)
2. Find all files that DEFINE it → update definition consistency
3. Find all files that REFERENCE it → update cross-references
4. Find all files that IMPLICITLY USE it → add explicit links
5. Find all files that SHOULD reference it → add links
6. Check for INCONSISTENCIES across all related files
7. Update this CROSS-REFERENCE.md if the relationship changes
```

### Rule 2: When Writing a New File

```
1. Identify which concepts the file touches
2. Add the file to each concept's list in this document
3. Check existing files that SHOULD reference the new file
4. Add forward-links from existing files to the new file
5. Add the new file to the appropriate folder and update this document
```

### Rule 3: Consistency Check Triggers

Run a full consistency check when:
- A new concept is introduced (does it contradict existing concepts?)
- A stage number or age range changes (affects 10+ files)
- A percentage or metric changes (e.g., AI coverage numbers)
- A priority order changes (README, core-logic, galaxy-of-spirits must agree)
- A new document is created

### Rule 4: Priority Alignment

These three files MUST agree on the top priority. If they disagree, fix immediately:
- `README.md` (public-facing)
- `framework/00-core-logic.md` (internal philosophy)
- `framework/galaxy-of-spirits.md` (the living document)

Current alignment: All three agree Galaxy of Spirits is the most important.

### Rule 5: The Cheatsheet Is Derived

`cheatsheet.md` is a working summary. It is DERIVED from other documents, not authoritative. When in doubt, the source documents take precedence. Check `cheatsheet.md` against the source documents whenever it's used.

**⚠️ KNOWN ISSUE**: `cheatsheet.md` still says 5 stages. Source of truth is `lifelong-galaxy.md` (9 stages). Fix `cheatsheet.md` when cheatsheet is next updated.

---

## Inconsistencies to Fix

| # | Issue | Files Involved | Priority | Status |
|---|---|---|---|---|
| 1 | `cheatsheet.md` says 5 stages; `lifelong-galaxy.md` and `README.md` say 9 | `cheatsheet.md` | HIGH | ✅ FIXED (2026-04-16) |
| 2 | `zhutixing-model.md` defines 5 agency stages; `lifelong-galaxy.md` extends to 9 | `zhutixing-model.md`, `lifelong-galaxy.md` | HIGH | ✅ FIXED (2026-04-16) — Stages 6-9 added with note linking to lifelong-galaxy.md |
| 3 | `ai-ecosystem-vision.md` simplifies AI coverage as 60-80%; detail is stage-dependent | `ai-ecosystem-vision.md`, `resource-requirements-ai-facilitation.md` | MEDIUM | ⚠️ PENDING |
| 4 | Missing cross-links between `cost-of-inaction.md` and `00-core-logic.md` | Multiple | MEDIUM | ⚠️ PENDING |
| 5 | Stage files don't consistently link to `ai-integration.md` | All stage files | LOW | ⚠️ PENDING |
| 6 | Stage files don't consistently link to `assessment/assessment-design.md` | All stage files | LOW | ⚠️ PENDING |
| 7 | Stage files don't consistently link to `motivation/motivation-architecture.md` | All stage files | LOW | ⚠️ PENDING |
| 8 | `motivation-journey-map.md` and `zhutixing-model.md` should cross-reference | `motivation-journey-map.md`, `zhutixing-model.md` | MEDIUM | ⚠️ PENDING |
| 9 | `assessment/gaokao-readiness.md` doesn't link to `ai-integration.md` | `gaokao-readiness.md` | LOW | ⚠️ PENDING |
| 10 | Presencing/Theory U cited in `motivation-architecture.md` but not in `lifelong-galaxy.md` | `lifelong-galaxy.md`, `motivation-architecture.md` | LOW | ⚠️ PENDING |

---

## File Dependency Tree

```
                    [THE CORE LOGIC: Why This Exists]
                           00-core-logic.md
                                  │
                    ┌──────────────┼──────────────┐
                    │              │              │
              [THE PHILOSOPY]  [THE EVIDENCE]  [THE HEALING]
              00-philosophy.md  galaxy-of-    healing-the-13-
                              spirits.md     year-old.md
                    │              │              │
         ┌──────────┼──────────┐   │              │
         │          │          │   │              │
    [AGENCY]   [MOTIVATION]  [AI] │         [CO-PILOT]
   zhutixing-  motivation-  ai-   │         principle
    model.md  architecture.md integration.md
         │          │
         └────┬─────┘
              │
         [MOTIVATION JOURNEY MAP]
         motivation-journey-map.md
              │
    ┌─────────┼─────────┬──────────┬───────────┐
    │         │         │          │           │
 [STAGE 1] [STAGE 2] [STAGE 3] [STAGE 4] [STAGE 5]
 seedling  explorer  builder   investigator architect
   .md       .md      .md        .md          .md
    │         │         │          │           │
    └─────────┴────┬────┴──────────┴───────────┘
                   │
            [ASSESSMENT]
          assessment-design.md
          gaokao-readiness.md
                   │
            [RISK ANALYSIS]
            risk-analysis.md
                   │
            [AI ECOSYSTEM]
        ai-ecosystem-vision.md
   resource-requirements-ai-facilitation.md

[LIFELONG GALAXY: Stages 6-9]
   lifelong-galaxy.md
   ↳ Should connect: zhutixing-model.md, reflection-survivorship-and-agency.md

[CONNECTOR MAP]
   CONNECTOR-MAP.md
   ↳ Bridges THIS PROJECT to PERSONAL TRANSFORMATION FOLDERS
   ↳ Lives OUTSIDE the dependency tree (connects to the outside world)

[MAPPING: Test → Problem]
   mapping/methodology.md
   ↳ Subject maps: math-mapping.md, yuwen-mapping.md, science-mapping.md
   ↳ Feeds into: all stage files, gaokao-readiness.md
```

---

## Change Log

| Date | Change | Files Updated | By |
|---|---|---|---|
| 2026-04-16 | Created CROSS-REFERENCE.md — full cross-reference map of all 36 files | — | Claude |
| 2026-04-16 | Updated README.md with core logic, 9 stages, full file tree, AI vision | README.md | Claude |
| 2026-04-16 | Fixed CONNECTOR-MAP.md (partial) — bi-directional bridge design | CONNECTOR-MAP.md | Claude |
| 2026-04-16 | Added stage-by-stage AI map to resource-requirements-ai-facilitation.md | resource-requirements-ai-facilitation.md | Claude |
| 2026-04-16 | Added cross-reference system — concept index, orchestration rules, dependency tree, inconsistencies tracker | CROSS-REFERENCE.md | Claude |
| 2026-04-16 | ✅ FIXED: cheatsheet.md updated to 9 stages, decisions updated, priorities updated | cheatsheet.md | FIXED |
| 2026-04-16 | ✅ FIXED: zhutixing-model.md extended to Stages 6-9 (Rediscoverer through Elder-Witness), linked to lifelong-galaxy.md | zhutixing-model.md | FIXED |
