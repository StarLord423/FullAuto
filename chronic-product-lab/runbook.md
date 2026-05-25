# Local Runbook

## Recommended Architecture

Use a supervised assembly line:

```text
Human selects product
  -> Researcher produces research package
  -> Product Builder creates printable content and layout
  -> Critic grades it
  -> Human approves or sends revision notes
  -> Only approved products become bundle or marketplace candidates
```

PaperclipAI can run this later, but during the MVP it must not autonomously publish, promote, email, post, or create accounts.

## Current State

The first migraine mini-catalog is locally validated:

- Migraine Daily Symptom Tracker
- Migraine Doctor Visit Prep Pack
- Migraine Pattern Workbook

The local bundle package exists at:

```text
chronic-product-lab/bundle/
```

The bundle includes approved US Letter and A4 PDFs, a bundle README, draft listing copy, mockup/preview requirements, seven completed preview images, a marketplace-readiness review, and a final buyer-facing upload ZIP.

## Manual Quality Gate

The product passes only if:

- Total average score is 8/10 or higher.
- Medical safety is 10/10.
- Condition specificity is 8/10 or higher.
- "Not generic AI output" is 8/10 or higher.

Automatic fail:

- Any diagnosis or treatment claim.
- Any prevention, cure, or guaranteed-outcome claim.
- Any fake professional endorsement.
- Any copied competitor language.
- Any page that is hard to print or read.
- Any product that could apply equally to any chronic illness by changing the title.

## Next Practical Step

Choose a local-only marketplace prep task, such as drafting platform-specific listing fields without publishing or deciding a test price.

Do not add Etsy, Gumroad, Pinterest, SendGrid, VPS automation, or PaperclipAI until the user explicitly approves that phase.

## Task Closeout Rule

Every task ends with a documentation pass:

1. Update relevant Markdown files.
2. Remove obsolete status or next-step notes.
3. Check that referenced files exist.
4. Check that safety and publishing guardrails still match the latest approval state.
