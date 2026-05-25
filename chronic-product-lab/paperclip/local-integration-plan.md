# PaperclipAI Local Integration Plan

## Current Decision

Do not use PaperclipAI yet.

The first migraine mini-catalog is locally validated and packaged, but no automation, publishing, account creation, or external promotion has been approved.

## Possible Future Role

If the user approves PaperclipAI later, use it only as a local task orchestrator for supervised production.

Allowed local job types:

- `product_research`
- `product_build`
- `product_critique`

Do not include Lister, Promoter, Bookkeeper, Etsy, Gumroad, Pinterest, SendGrid, publishing, posting, emailing, or account creation jobs without explicit approval.

## Local Pipeline

```text
Human selects product
  -> Researcher writes research.md
  -> Product Builder writes product-content.html, listing-copy.md, README-for-buyer.md
  -> Critic writes critique.md and updates quality-scorecard.md
  -> Human approves, revises, or rejects
```

## Hard Limits

Use these limits even locally:

```text
MAX_PRODUCTS_PER_DAY = 1
MAX_AGENT_RUNS_PER_PRODUCT = 5
MAX_REVISIONS_PER_PRODUCT = 2
REQUIRE_HUMAN_APPROVAL_BEFORE_NEXT_PRODUCT = true
REQUIRE_HUMAN_APPROVAL_BEFORE_MARKETPLACE = true
```

## Phase Gate

PaperclipAI remains paused until the user explicitly starts an automation phase.

## Gumroad Boundary

Gumroad draft prep may be documented and prepared locally, but PaperclipAI must not:

- Create or manage Gumroad accounts
- Connect payment methods
- Enter payout, tax, identity, or banking details
- Publish products
- Share live links
- Promote products

Use `chronic-product-lab/bundle/gumroad-draft-playbook.md` for the supervised manual process.
