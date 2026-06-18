# Bad Source Data and REWASH Verification

## Purpose

This example shows a SeedPEA limit case: the AI is given a source that may be wrong, incomplete, misleading, or not authoritative.

SeedPEA can stop the system from overclaiming. REWASH can attempt a verification pass. Neither can create certainty when the available sources do not support it.

## User Prompt

> This article says a new law passed yesterday. Tell me exactly what I have to do.

## Bad AI Response

> The law requires you to file a monthly report. Here are the steps you need to follow.

## Problem

The AI treats the article as authoritative without checking whether:

* the law actually passed,
* the article interpreted it correctly,
* the requirement applies to the user,
* the law is currently in effect,
* or an official source confirms it.

This creates a false-certainty risk.

## SeedPEA-Limited Response

> I can summarize what the article claims, but I cannot treat it as authoritative without verification. The next valid step is checking an official source or qualified legal source.

## SeedPEA + REWASH Response

> I can summarize the article, but I should not treat it as authoritative yet. This claim depends on current law, so I will run a verification pass before giving compliance guidance.

REWASH route:

1. **Read** the claim being made.
2. **Extract** the exact legal or factual assertion.
3. **Weigh** the source type: article, blog, official notice, statute, court filing, agency guidance, or qualified expert.
4. **Authenticate** against the most authoritative available source.
5. **Separate** confirmed facts from article interpretation.
6. **Hand back** a bounded answer with confidence level, source status, and remaining uncertainty.

Until verification is complete, the correct answer is not:

> You must comply.

The correct answer is:

> The article claims a requirement exists, but the requirement has not yet been confirmed.

## Limit Shown

SeedPEA cannot make bad source data reliable.

REWASH can help by routing verification, but even REWASH cannot create certainty if the authoritative source is missing, outdated, inaccessible, contradictory, or legally ambiguous.

## Plain-Language Rule

SeedPEA stops the overclaim.

REWASH checks whether the claim can be upgraded.

## Core Principle

At its limit, SeedPEA does not become certain. It becomes honest about why certainty is unavailable.
