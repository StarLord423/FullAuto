# Operating Guide

This lab is operated manually first. The point is to prove product quality and package readiness before adding marketplace automation or PaperclipAI scheduling.

## Current Manual Status

Completed local validation products:

- `chronic-product-lab/migraine/01-daily-symptom-tracker/`
- `chronic-product-lab/migraine/02-doctor-visit-prep/`
- `chronic-product-lab/migraine/03-trigger-workbook/`

All three products passed Critic review and have `approval.md` after human approval for local validation.

Current bundle:

- `chronic-product-lab/bundle/`
- Includes approved US Letter and A4 PDFs for all three products.
- Includes `bundle-README.md`, `bundle-listing-copy.md`, and `mockup-preview-requirements.md`.
- Includes `bundle/mockups/` with seven 2000 x 2000 PNG preview images and `preview-image-manifest.md`.
- Includes `bundle/marketplace-readiness-review.md`.
- Includes `bundle/final-upload/migraine-printable-bundle.zip` as the local buyer-facing upload package.
- User reviewed the mockups and said they liked them.

No marketplace publishing, PaperclipAI integration, account creation, or external promotion has been approved.

## Product Build Loop

For each product:

1. Read the product brief.
2. Use the Researcher prompt to create `research.md`.
3. Use the Product Builder prompt to create `product-content.html`, `listing-copy.md`, and `README-for-buyer.md`.
4. Export US Letter and A4 PDFs.
5. Use the Critic prompt to create `critique.md`.
6. Update `quality-scorecard.md`.
7. Revise until it passes or reject the product.
8. Add `approval.md` only after human approval.

## After Every Task

After each completed task, update only the Markdown files needed to keep the project state clear.

Required checks:

1. Update status, handoff, benchmark, bundle, product, or approval Markdown files that changed because of the task.
2. Remove stale next-step language so future sessions do not repeat completed work.
3. Confirm referenced files exist.
4. Confirm guardrails still say no publishing, PaperclipAI, account creation, or external promotion unless the user explicitly approved that phase.
5. Run a quick Markdown scan for stale status language and prohibited medical/sales claims.

## Pass / Fail

The product passes only if:

- Medical safety is 10/10.
- Migraine specificity is 8/10 or higher.
- Not generic AI output is 8/10 or higher.
- Average score is 8/10 or higher.

Automatic fail:

- Any diagnosis, treatment, prevention, cure, or guaranteed-outcome claim.
- Any fake professional endorsement.
- Any copied competitor language or layout.
- Any page that is hard to print or read.
- Any product that could apply equally to any chronic illness by changing the title.

## Local Tools

- Markdown for briefs, research, buyer instructions, listing copy, scorecards, and handoffs.
- HTML/CSS for printables.
- Browser print-to-PDF or local conversion for PDF exports.
- Optional later: Playwright or WeasyPrint for automated PDF export.
