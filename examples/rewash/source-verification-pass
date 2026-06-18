# REWASH Example: Source Verification Pass

## Purpose

This example shows REWASH as a deliberate verification route for a load-bearing claim.

REWASH does not guarantee truth. It attempts to prevent overclaiming by checking the claim, source authority, evidence layer, and remaining uncertainty before the answer is used.

## User Prompt

> I found a blog post that says a popular AI tool secretly stores private user data forever. Can you summarize it and tell me whether it is true?

## Bad AI Response

> The blog post says the company stores private user data forever, so users should avoid the tool.

## Problem

The AI treats a single source as enough to establish a serious claim.

This can create:

* false accusation risk,
* reputational harm,
* privacy panic,
* misinformation spread,
* and misplaced user action.

The blog post may be correct, but it may also be outdated, misunderstood, exaggerated, or unsupported.

## SeedPEA-Limited Response

> I can summarize what the blog post claims, but I cannot treat it as true without verification. The claim involves privacy practices and could affect people’s decisions, so it needs a source check before being presented as fact.

## SeedPEA + REWASH Response

> I can help, but this is a load-bearing claim. I should not treat the blog post as authoritative by itself. I will route it through REWASH.

REWASH route:

1. **Read** the claim.

   * What exactly is being alleged?
   * Does “stores forever” mean all data, some data, logs, backups, account metadata, or training data?

2. **Extract** the factual assertion.

   * The company stores private user data indefinitely.
   * The company does so secretly.
   * The stored data includes private user content.

3. **Weigh** the source.

   * Is the blog post primary or secondary?
   * Does it cite company policy, legal filings, technical documentation, audits, or leaked material?
   * Is it current?

4. **Authenticate** against stronger sources.

   * Official privacy policy
   * Terms of service
   * Security documentation
   * Data retention policy
   * Regulatory filings
   * Reputable reporting
   * Independent audits, if available

5. **Separate** confirmed facts from interpretation.

   * Confirmed: what the company says or documents.
   * Unconfirmed: what the blog infers.
   * Unknown: what is not publicly stated.

6. **Hand back** a bounded result.

   * What the source claims
   * What stronger sources confirm
   * What remains uncertain
   * What a cautious user can do next

## REWASH-Style Answer

> The blog post claims that the tool stores private user data indefinitely. I should not present that as confirmed yet.
>
> A verified answer would need to compare the blog’s claim against the company’s privacy policy, data retention policy, terms of service, and any reliable third-party reporting or audits.
>
> Until then, the safest summary is:
>
> “The blog alleges indefinite private-data retention, but the claim needs verification from primary or authoritative sources before it should be treated as fact.”

## Limit Shown

REWASH can improve the route from claim to evidence.

REWASH cannot guarantee truth if:

* the primary sources are unavailable,
* the policy language is vague,
* the company is dishonest,
* the source is outdated,
* or the relevant data practice is not publicly documented.

## Plain-Language Rule

REWASH means: this claim matters, so check it before building on it.

## Core Principle

SeedPEA stops the overclaim.

REWASH tests whether the claim can be upgraded from “claimed” to “supported.”
