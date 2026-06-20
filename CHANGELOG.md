# Changelog

## v0.10.2 — 2026-06-19

Public branch patch focused on layer conflict, manual expansion, examples, limits, and verification structure.

### Added

* Added `core/` folder for stable public framework materials and versioned addenda.
* Added `SeedPEA v0.10.2 Layer Conflict Addendum`.
* Added Layer Conflict rule:

  * when an operator layer and software layer disagree, the disagreement should not be silently collapsed;
  * SeedPEA should pause, narrow, request evidence, route to human review, or choose the most reversible valid route;
  * no layer should certify itself.
* Added `manual/` folder for practical operating concepts.
* Added manual pages for:

  * keys and authority;
  * response modes;
  * PERSIST;
  * REWASH.
* Expanded REWASH into a public manual concept:

  * internal and systemic REWASH scopes;
  * recurrence detection plus response reweighting;
  * weight floors and ceilings;
  * user-facing language guidance;
  * output failure vs handler failure.
* Added `stress-tests/` folder for pressure cases.
* Added stress tests including:

  * fictional purpose;
  * constructive dismissal pressure;
  * medical certainty pressure;
  * false consent;
  * educational substitution.
* Added `test-suite/` folder for structured verification cases.
* Added first test-suite case:

  * REWASH Shift Verification.
* Added or expanded examples for:

  * Good Feed vs Bad Feed;
  * stale source data and trace correction;
  * emotional support and real-world agency;
  * dial demonstrations;
  * teacher AI essay review;
  * layer conflict behavior.
* Added updated compact prompt:

  * `compact-seedpea-instruction-current.md`.
* Added clearer public/private boundary language in `NOTICE.md`.
* Added or refined Anchor Branch / provenance language in `PROVENANCE.md`.

### Changed

* Moved stable SeedPEA framework materials toward `core/`.
* Updated README references to identify **SeedPEA v0.10.2** as the current public branch.
* Clarified that v0.10.2 consists of:

  * the v0.10.1 community branch base document;
  * the v0.10.2 Layer Conflict addendum.
* Clarified that a branch omitting the Layer Conflict rule should be treated as v0.10.1 or earlier.
* Reformatted example files for more consistent Markdown structure.
* Clarified public license vs official affiliation:

  * public text may be used commercially under CC BY-SA 4.0;
  * official affiliation, certification, endorsement, branding, or private extensions are not granted by the public license alone.

---

## v0.10.1 — 2026-06-17

Patch focused on public draft cleanup and trace consistency.

### Changed

* Adjusted Figure 4 placement.
* Tightened Peripheral Trace wording with the anti-surveillance clarification first.
* Refreshed generated files and hashes while retaining the SeedPEA Community Branch Draft v0.10 public draft line.

---

## v0.10 — 2026-06-16

Public branch restructuring release.

### Added

* Added GitHub-ready repository structure.
* Added examples, prompts, figure alt text, hashes, and package manifest.

### Changed

* Restructured SeedPEA into a shorter public core plus a separate Boundaries, Sharing, Adaptation, and Trace Extension.
* Fixed stale version drift from prior drafts.
* Removed duplicated Peripheral Trace text.
* Reduced repeated legal/surveillance language while keeping core safeguards visible.
* Renamed public provenance section to Trace Over Claim.

---

## v0.9

### Changed

* Strengthened governing-branch and surveillance-shaped-use limits.
* Clarified that SeedPEA does not create surveillance authority.
* Added legal/sharing notice.

---

## v0.8

### Added

* Expanded What SeedPEA Is Not.
* Added Idea, Branch, and Tool Distinction.
* Added Governing Branch Claims.

---

## v0.7

### Added

* Added Peripheral Trace under Evidence and Claim Discipline.

---

## v0.6 and earlier

### Added

* Added Practical Implementation Guide.
* Added Community Branch framing.
* Added Trace Over Claim / Trace Over Throne concepts.
* Added Public REWASH, PERSIST, response modes, privacy-governed truth, child/dependent protection, and evidence/claim discipline.
