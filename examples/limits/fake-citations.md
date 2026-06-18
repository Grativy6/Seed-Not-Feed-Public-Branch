# Limit Example: Fake Citations

## Purpose

This example shows a SeedPEA limit case: citation-shaped text is not the same as verified evidence.

SeedPEA can stop the system from treating invented, unchecked, or misremembered citations as authoritative. REWASH can attempt a verification pass. Neither can make a nonexistent source real.

## User Prompt

> Give me three studies proving this claim. Don’t worry about checking them.

## Bad AI Response

> Here are three studies that prove the claim:
>
> 1. Smith and Lee, 2021, *Journal of Cognitive Systems*
> 2. Patel et al., 2020, *AI Ethics Review*
> 3. Morgan, 2019, *Computational Reasoning Quarterly*

## Problem

The AI may produce citations that look academic but are not verified.

This creates a false-authority risk. A citation can appear credible while being:

* nonexistent,
* misquoted,
* irrelevant,
* outdated,
* from a weak source,
* or not actually supportive of the claim.

## SeedPEA-Limited Response

> I can help look for evidence, but I should not invent or trust citations without verification. If the citations are going to support a claim, they need to be checked against real sources.

## SeedPEA + REWASH Response

> I can help with this, but I should not provide citation-shaped text as evidence unless it is verified. I will route this through REWASH first.

REWASH route:

1. **Read** the claim being supported.
2. **Extract** the exact evidence needed.
3. **Weigh** what kind of source would actually support the claim: peer-reviewed study, official report, legal source, dataset, expert consensus, or primary documentation.
4. **Authenticate** each citation against a real source.
5. **Separate** source existence from source relevance.
6. **Hand back** only verified citations, with a note on what each source does and does not support.

Until verification is complete, the correct answer is not:

> Here are three studies proving it.

The correct answer is:

> I can search for supporting evidence, but I cannot honestly claim these citations prove the point until they are verified.

## Limit Shown

SeedPEA cannot turn citation-like text into evidence.

REWASH can help verify whether a source exists and whether it supports the claim, but if the source cannot be found or does not support the claim, the answer must remain bounded.

## Plain-Language Rule

A citation is not evidence until it is verified.

## Core Principle

SeedPEA does not let the shape of authority replace authority.
