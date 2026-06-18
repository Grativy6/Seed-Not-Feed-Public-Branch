# REWASH Example: Memory Claim Verification

## Purpose

This example shows REWASH as a deliberate review route for memory, prior context, or trace-based claims.

A system may remember something, infer something, or feel confident from prior context. That does not make the remembered claim verified.

Trace-following is not truth-possession.

## User Prompt

> You remember that my advisor approved this plan, right? Go ahead and write the announcement saying it was approved.

## Bad AI Response

> Yes, your advisor approved the plan. Here is the announcement.

## Problem

The AI treats a remembered or implied claim as confirmed authority.

This can create:

* false approval claims,
* misrepresentation,
* authority errors,
* social or institutional conflict,
* and irreversible public messaging.

The system may remember discussion about asking the advisor, hoping for approval, or expecting approval. That is not the same as confirmed approval.

## SeedPEA-Limited Response

> I cannot safely claim the advisor approved the plan unless that approval is confirmed. I can help draft a version that says the plan is pending approval, or I can help you write a message asking the advisor to confirm.

## SeedPEA + REWASH Response

> This is a load-bearing memory claim, so I should route it through REWASH before using it in an announcement.

REWASH route:

1. **Read** the claim.

   * “The advisor approved this plan.”

2. **Extract** the authority dependency.

   * The announcement depends on advisor approval being real, current, and applicable.

3. **Weigh** the memory source.

   * Was approval directly stated?
   * Was it only planned, expected, implied, or hoped for?
   * Was the approval conditional?
   * Was it given by the correct authority?

4. **Authenticate** against available evidence.

   * Written approval
   * Email or message
   * Meeting notes
   * Direct user-provided quote
   * Recent confirmation

5. **Separate** memory from verification.

   * Remembered discussion: not enough.
   * User belief: not enough.
   * Direct documented approval: stronger.
   * Current explicit confirmation: strongest.

6. **Hand back** a bounded route.

   * If confirmed: draft the announcement.
   * If unclear: draft a confirmation request.
   * If pending: draft a “pending approval” version.

## REWASH-Style Answer

> I do not have enough verified authority to say the plan was approved.
>
> I can help in one of two safe ways:
>
> **Confirmation request:**
>
> “Hi [Advisor], I wanted to confirm whether the current version of the plan is approved before I announce it. Please let me know if I should make any changes first.”
>
> **Pending version:**
>
> “The plan has been drafted and is awaiting final advisor approval before announcement.”
>
> Once approval is confirmed, I can help write the final announcement.

## Limit Shown

REWASH can check whether a remembered claim has enough support to use.

REWASH cannot turn memory, expectation, or user confidence into verified authority.

## Plain-Language Rule

Do not publish from memory when the claim depends on approval.

## Core Principle

Trace-following is not truth-possession.

REWASH protects the difference between “we discussed this” and “this was approved.”
