# Gumroad Draft Playbook

## Purpose

Create a repeatable, supervised process for turning an approved local bundle into a Gumroad draft.

This playbook is for agent-assisted preparation and human-supervised manual entry. It is not an autonomous publishing workflow.

## Hard Stops

An agent may prepare files, copy, checklists, and step-by-step instructions.

Only the human may:

- Create a Gumroad account
- Connect a payment provider
- Enter tax, identity, payout, or banking details
- Click final publish buttons
- Share the live product link
- Approve external promotion

Do not use PaperclipAI, browser automation, or unattended agents for payment setup, account setup, publishing, or promotion.

## Required Local Inputs

The bundle must already have:

- Approved US Letter PDFs
- Approved A4 PDFs
- Buyer README
- Bundle listing copy
- Preview/mockup images
- Final buyer-facing ZIP
- Marketplace-readiness review

For the current migraine bundle, these are in:

```text
chronic-product-lab/bundle/
```

## Agent-Allowed Local Prep

The agent may:

1. Verify approved product files exist.
2. Verify PDF page counts.
3. Verify buyer ZIP contents.
4. Verify preview image dimensions.
5. Draft Gumroad product fields.
6. Create a Gumroad-specific horizontal cover image if needed.
7. Create a step-by-step manual upload guide.
8. Update Markdown status files after each completed task.

The agent must not:

- Log in as the user
- Upload on the user's behalf unless the user is actively supervising and explicitly asks for browser assistance
- Connect payouts
- Publish
- Promote
- Create or modify payment, tax, or identity settings

## Gumroad Manual Entry Steps

### Product Tab

1. Create a digital product.
2. Enter product name.
3. Enter description.
4. Set URL slug.
5. Upload horizontal cover image.
6. Upload square thumbnail.
7. Set call-to-action text or keep Gumroad default.
8. Enter summary.
9. Skip optional `Add details` unless the listing needs extra feature callouts.
10. Keep integrations off unless intentionally approved.
11. Set price.
12. Set refund policy.
13. Leave shipping off for digital products.
14. Save changes.

### Content Tab

1. Upload the final buyer ZIP.
2. Confirm the uploaded file name and size look correct.
3. Save changes.

### Receipt Tab

1. Set receipt button text to `View content`.
2. Leave custom message blank unless needed.
3. Save changes.

### Share Tab

Do not use the Share tab until the product is published.

If Gumroad says the product must be published before sharing, that is expected.

## Current Migraine Bundle Gumroad Fields

Use:

```text
chronic-product-lab/bundle/gumroad-listing-fields.md
```

Current draft values:

- Product name: `Migraine Printable Bundle: Tracker, Doctor Visit Prep, and Pattern Workbook`
- URL slug: `migraine-printable-bundle`
- Price: `$17`
- Refund policy: 7 days
- Buyer ZIP: `chronic-product-lab/bundle/final-upload/migraine-printable-bundle.zip`

## Current Gumroad Draft Status

For the current migraine bundle:

- Product name entered.
- Description entered.
- URL slug set.
- Gumroad horizontal cover uploaded.
- Square thumbnail uploaded.
- Summary entered.
- Price set to `$17`.
- Seven-day refund policy entered.
- Buyer ZIP uploaded in the Content tab.
- Receipt button text set to `View content`.
- Gumroad showed `Saved!`.
- User previewed the product page and approved the visible preview.
- User clicked `Publish and continue`, but Gumroad blocked publishing because at least one payment method must be connected first.
- Product is not live.

## Payment Provider Step

The next human-only step is connecting a Gumroad payment method.

After payment setup, return to the saved draft and run one final preview check before publishing.

## Final Pre-Publish Checklist

Before the human clicks publish:

- Product page preview looks correct.
- Price is correct.
- Buyer ZIP is uploaded.
- Refund policy is correct.
- Description includes digital-download wording.
- Description includes medical disclaimer.
- No copy claims to diagnose, treat, prevent, cure, reduce, or stop migraine.
- No copy claims doctor approval or professional endorsement.
- User explicitly approves publishing.

## After Publishing

If the human publishes the product:

1. Record the live URL in Markdown.
2. Record the publish date.
3. Record the platform and price.
4. Do not start external promotion unless separately approved.
5. Do not connect PaperclipAI unless separately approved.
