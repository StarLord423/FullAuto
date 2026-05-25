# Chronic Product Lab

Local MVP for testing whether AI-assisted chronic illness printables are good enough to sell.

This is intentionally not an Etsy/Gumroad/Pinterest automation yet. The goal is to produce, review, approve, and package high-quality files locally before connecting any marketplace or scheduler.

## Current Status

Condition: Migraine / Chronic Migraine

Validated products:

1. Migraine Daily Symptom Tracker - passed Critic review and received human approval for local validation.
2. Migraine Doctor Visit Prep Pack - passed Critic review and received human approval for local validation.
3. Migraine Pattern Workbook - passed Critic review and received human approval for local validation.

Bundle status:

- Local bundle folder created at `bundle/`.
- Approved US Letter and A4 PDFs copied into the bundle.
- Bundle README, draft listing copy, and mockup/preview requirements created.
- Bundle listing mockups and preview images created in `bundle/mockups/`.
- Marketplace-readiness review created at `bundle/marketplace-readiness-review.md`.
- Buyer-facing upload ZIP created at `bundle/final-upload/migraine-printable-bundle.zip`.
- Gumroad listing fields drafted at `bundle/gumroad-listing-fields.md`.
- Gumroad product published at `https://3010107719883.gumroad.com/l/migraine-printable-bundle`.
- User reviewed the mockups and said they liked them.
- No PaperclipAI integration or external promotion has been approved.

## Workflow

1. Fill in the product brief.
2. Run the Researcher prompt.
3. Run the Product Builder prompt.
4. Generate the printable as HTML first.
5. Export to PDF manually or through a local converter.
6. Run the Critic prompt.
7. Revise until the scorecard passes.
8. Record human approval before adding a product to any bundle or marketplace candidate set.

## Folder Layout

```text
chronic-product-lab/
  agents/
  bundle/
    mockups/
  migraine/
    01-daily-symptom-tracker/
    02-doctor-visit-prep/
    03-trigger-workbook/
  paperclip/
  runbook.md
```

## Guardrails

- Do not claim to diagnose, treat, prevent, or reduce symptoms.
- Do not claim doctor approval unless a real qualified professional reviewed it.
- Do not invent credentials.
- Do not copy competitor wording or layouts.
- Always include a medical disclaimer.
- Keep outputs migraine-specific, not generic wellness planner filler.
