# AGENTS.md

## Purpose
This repository contains the public JDE Solutions, LLC website.

## Operating rules
- Treat public-facing business copy, pricing, service scope, contact details, legal language, and brand claims as controlled content.
- Do not change prices, service commitments, contact information, or legal/business claims unless the task explicitly requires it.
- Preserve accessibility, responsive behavior, internal navigation, and the existing static-site deployment model.
- Prefer small HTML/CSS/asset changes over introducing a framework without a clear requirement.
- Never add credentials, customer data, private analytics data, or internal-only information to this public repository.

## Validation
For changes:
- inspect affected HTML/CSS for broken links and obvious markup errors
- verify page titles/meta descriptions when content changes
- keep assets referenced with valid paths
- summarize any deployment/cache implications

## Agent workflow
- INVESTIGATE: inspect and report without modifying.
- BUILD: implement on a feature branch and prepare a reviewable diff.
- FIX: reproduce the visible defect where practical, then fix it.
- REVIEW: check content accuracy, accessibility, navigation, regressions, and accidental disclosure.

## Approval gates
Human approval is required before merging material pricing/scope changes, publishing new legal claims, or changing deployment/domain configuration.
