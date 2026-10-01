# PFUSA Logo Decision Record

**Decision date:** 01 October 2026\
**Project:** Prayer Force USA (PFUSA)\
**Status:** LOCKED --- reopen only by explicit branding decision

## Purpose

This record preserves the durable branding decisions made during the
PFUSA incense-logo review and implementation. It is intended to prevent
approved assets from being inadvertently regenerated, altered, replaced,
or superseded during future site work.

## Approved Primary Incense Logo

**Candidate A is the approved PFUSA incense logo.**

Protected master:

`brand-assets/logo-milestones/PFUSA_Incense_Logo_Candidate-A_Preferred.png`

Production copy:

`assets/pfusa-incense-logo-candidate-a.png`

Candidate A should not be regenerated, redrawn, stretched, restyled, or
otherwise modified as part of routine site work. When the approved logo
is needed, use the approved source asset rather than recreating it.

## Immediate Predecessor

Candidate A's immediate predecessor was retired because part of its
geometry --- particularly the upper extension of the P in combination
with the censer/flame composition --- created unintended visual
ambiguity.

During review, the predecessor was **not identified as containing a
recognizable occult or Satanic symbol**. The concern was visual
association or ambiguity, not identification of an actual occult emblem.

Candidate A removed that ambiguity while retaining the intended
censer/prayer concept.

## Favicon / Micro-Mark

Approved production favicon:

`favicon.png`

The favicon is a **32 × 32 simplified incense micro-mark**. It was
intentionally developed from Candidate A's visual DNA rather than
produced by simply shrinking the full Candidate A artwork.

The micro-mark and the full Candidate A logo serve different size/use
cases. Do not replace the micro-mark with a mechanically reduced full
logo without an explicit branding decision.

## Prelaunch / Countdown Artwork

Approved production composite:

`prelaunch/prelaunch-background-candidateA-approved.png`

The approved composite is **v5**.

V5 was selected after side-by-side comparison with later experiments
intended to restore more navy background and further blend Candidate A's
black field. Those later experiments were not selected. V5 remains the
approved production artwork.

The prelaunch artwork should not be regenerated or casually
recomposited. Any future change should begin from the approved source
assets and should preserve Candidate A rather than modifying the logo
itself.

## Confirmation Pages

Candidate A is confirmed live on:

-   `/check-your-email/`
-   `/thank-you/`

Both pages use:

`assets/pfusa-incense-logo-candidate-a.png`

The prior page-art asset:

`assets/incense-logo.png`

is no longer referenced by active HTML as of this decision record. It
should not be reintroduced into active pages without an intentional
branding decision.

## Favicon vs. Page-Art Troubleshooting Note

An apparent favicon inconsistency during this work was ultimately traced
to a different issue: the unwanted predecessor incense logo was an
`<img>` displayed within the Check Your Email and Thank You pages.

The approved root `favicon.png` was separately verified as the intended
32 × 32 micro-mark.

This distinction should be remembered during future troubleshooting:

-   **Browser/tab icon:** `favicon.png`
-   **Full Candidate A page logo:**
    `assets/pfusa-incense-logo-candidate-a.png`

Do not assume a visible logo on a confirmation page is the favicon.

## Relevant Git Milestones

-   `205cea5` --- `Milestone: PFUSA incense logo Candidate A preferred`
-   `3ddf65d` --- `Update favicon to PFUSA incense micro-mark`
-   `3e7ea53` --- `Milestone: approve Candidate A prelaunch artwork`
-   `afc15e3` --- `Milestone: use Candidate A on confirmation pages`

These commits provide rollback/history points for the approved branding
work.

## Locked Decision

The following are approved and **LOCKED**:

1.  Candidate A as the PFUSA incense logo.
2.  `brand-assets/logo-milestones/PFUSA_Incense_Logo_Candidate-A_Preferred.png`
    as the protected Candidate A master.
3.  `assets/pfusa-incense-logo-candidate-a.png` as the production
    full-logo copy.
4.  `favicon.png` as the approved 32 × 32 incense micro-mark.
5.  `prelaunch/prelaunch-background-candidateA-approved.png` (v5) as the
    approved prelaunch/countdown composite.
6.  Candidate A usage on the Check Your Email and Thank You pages.

These assets should remain unchanged unless the PFUSA branding decision
is explicitly reopened.

## Working Principle for Future Changes

**Approved brand images are assets, not prompts.**

When an approved image already exists, future development should
reference, copy, place, crop, or mechanically composite that exact asset
as appropriate. Image generation or stylistic reinterpretation should
not be used as a substitute for the approved source unless explicitly
requested.
