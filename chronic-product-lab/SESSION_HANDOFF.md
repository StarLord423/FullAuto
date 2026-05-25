# Session Handoff

Use this file to continue the Chronic Product Lab in a new Codex session.

## Current Strategy

We are testing viability locally before integrating PaperclipAI, Etsy, Gumroad, Pinterest, or any autonomous publishing.

The operating model has been:

```text
Researcher -> Product Builder -> Critic -> Human approval -> Local bundle packaging -> Listing mockups
```

## Current Niche

Condition: Migraine / Chronic Migraine

Goal: Prepare a small validated migraine bundle for a supervised sales test before any external publishing or automation.

## Validated Products

Three migraine products have passed Critic review and received human approval for local validation:

| Product | Folder | Pages | Score | Included Formats |
| --- | --- | ---: | ---: | --- |
| Migraine Daily Symptom Tracker | `migraine/01-daily-symptom-tracker/` | 2 | 9.125/10 | US Letter PDF, A4 PDF |
| Migraine Doctor Visit Prep Pack | `migraine/02-doctor-visit-prep/` | 8 | 9.125/10 | US Letter PDF, A4 PDF |
| Migraine Pattern Workbook | `migraine/03-trigger-workbook/` | 10 | 9.125/10 | US Letter PDF, A4 PDF |

Each product folder contains:

- `brief.md`
- `research.md`
- `product-content.html`
- `product-us-letter.pdf`
- `product-a4.pdf`
- `listing-copy.md`
- `README-for-buyer.md`
- `critique.md`
- `quality-scorecard.md`
- `revision-notes.md`
- `approval.md`

## Bundle Status

Path A and Path C are complete.

Bundle folder:

```text
chronic-product-lab/bundle/
```

Bundle files:

- `migraine-daily-symptom-tracker-us-letter.pdf`
- `migraine-daily-symptom-tracker-a4.pdf`
- `migraine-doctor-visit-prep-pack-us-letter.pdf`
- `migraine-doctor-visit-prep-pack-a4.pdf`
- `migraine-pattern-workbook-us-letter.pdf`
- `migraine-pattern-workbook-a4.pdf`
- `bundle-README.md`
- `bundle-listing-copy.md`
- `mockup-preview-requirements.md`
- `marketplace-readiness-review.md`
- `gumroad-listing-fields.md`
- `gumroad-draft-playbook.md`

Mockup folder:

```text
chronic-product-lab/bundle/mockups/
```

Mockup files:

- `gumroad-cover-1280x720.png`
- `01-bundle-cover-preview.png`
- `02-included-files-preview.png`
- `03-daily-symptom-tracker-preview.png`
- `04-doctor-visit-prep-preview.png`
- `05-pattern-workbook-preview.png`
- `06-us-letter-a4-preview.png`
- `07-printing-use-case-preview.png`
- `preview-image-manifest.md`
- `contact-sheet.png` for local review only

Mockup status:

- All seven required preview images are 2000 x 2000 PNGs.
- Gumroad-specific horizontal cover image is 1280 x 720 PNG.
- The page previews use real renders from the approved bundle PDFs.
- The user reviewed the contact sheet and said they liked the mockups.

Marketplace-readiness status:

- `chronic-product-lab/bundle/marketplace-readiness-review.md` is complete.
- Verdict: ready for a supervised marketplace-readiness decision, but not approved for publishing.
- Buyer-facing upload ZIP is complete at `chronic-product-lab/bundle/final-upload/migraine-printable-bundle.zip`.
- User unzipped and reviewed the buyer package, then said it looks good.
- Remaining decisions: platform, price, and support/refund notes.

Gumroad status:

- User created a Gumroad account and is on `https://gumroad.com/products/new`.
- Gumroad listing fields are drafted locally at `chronic-product-lab/bundle/gumroad-listing-fields.md`.
- Recommended starting price in the draft: `$17`.
- Manual Gumroad draft has product name, description, URL slug, cover, thumbnail, summary, $17 price, seven-day refund policy, and buyer ZIP uploaded.
- Gumroad showed `Saved!` after saving changes.
- User previewed the product page and approved the visible preview.
- User clicked `Publish and continue`, but Gumroad blocked publishing because at least one payment method must be connected first.
- Product should remain unpublished until the user explicitly approves the final live listing.
- Gumroad draft process is saved in `chronic-product-lab/bundle/gumroad-draft-playbook.md`.

Final upload package:

```text
chronic-product-lab/bundle/final-upload/
```

Buyer ZIP contents:

- Six approved PDFs
- `README.md`

Seller-facing files such as listing copy, mockups, manifests, and readiness notes remain outside the buyer ZIP.

## Current Guardrails

- No medical diagnosis, treatment, prevention, cure, or outcome claims.
- No fake doctor approval or credentials.
- No marketplace publishing.
- No PaperclipAI integration.
- No account creation.
- Keep all buyer-facing language migraine-specific and medically cautious.
- Use "possible context" and "patterns" instead of guaranteed trigger claims.

## Recommended Next Step

Human-only step: connect a Gumroad payment provider if the user wants to continue toward publishing. After that, return to the saved Gumroad draft for a final preview check before publishing.

Do not publish anything or use PaperclipAI unless the user explicitly approves that phase.

## Standing Completion Rule

After every completed task, update relevant Markdown files before stopping. Keep updates minimal and factual, remove stale next-step language, verify referenced files exist, and keep the no-publishing/no-Paperclip/no-account guardrails current.

## New Session Start Prompt

```text
Read chronic-product-lab/SESSION_HANDOFF.md and chronic-product-lab/OPERATING.md.
Continue from the current local migraine bundle package.
Do not publish anything, create accounts, or use PaperclipAI.
```
