# DigitalTrack Brand Guide For AI Agents

This file translates the materials in this folder into a practical reference for AI agents, designers, writers, and automation workflows.

## Purpose

Use this file as the primary brand-context source when generating:

- website copy
- ads
- social posts
- presentations
- sales collateral
- email signatures
- business cards
- design briefs
- implementation notes for designers or developers

## Source Quality

The folder contains a mix of real brand assets and template leftovers.

Confirmed or high-confidence sources reviewed:

- `Brand Guideline/PNG/06.PNG`
- `Brand Guideline/PNG/07.PNG`
- `Brand Guideline/PNG/08.PNG`
- `Brand Guideline/PNG/09 copy.PN.PNG`
- `Brand Guideline/PNG/10.PNG`
- `Brand Guideline/PNG/12.PNG`
- `Brand Guideline/PNG/13.PNG`
- `DT rack card content.docx`
- `Montserrat/`
- `Logo source file/`
- `biz cards and rack cards/Business card and Rack card design canva .txt`

Likely template or unreliable sources:

- `Brand Guideline/PNG/3.PNG` vision page contains lorem ipsum
- `Brand Guideline/PNG/04.PNG` mission page contains lorem ipsum
- `Brand Guideline/PNG/05.PNG` brand values page contains German template words
- `Brand Guideline/PNG/13.PNG` business card mockup uses sample person details

Rule: do not invent brand strategy from placeholder pages.

## Brand Core

- Brand name: `DigitalTrack`
- Descriptor/tagline in current lockup: `Digital Marketing`
- Category: digital marketing services
- Brand posture: practical, growth-focused, local-business oriented
- Audience in current materials: restaurants, food trucks, caterers, plumbers, contractors, home services, nonprofits, outreach organizations
- Language support: English and Spanish materials already exist, so bilingual adaptation is on-brand

## Service Positioning

Current materials consistently position DigitalTrack around these services:

- Reputation Management
- Social Media Management
- SMS/Email Marketing
- Lead Generation
- Local SEO

When writing copy, keep the value proposition concrete:

- grow visibility
- attract qualified leads
- improve reviews and trust
- stay connected with customers
- help local businesses get found

## Visual Identity

### Logo

Confirmed from the guideline:

- The main logo is a horizontal wordmark: `digitalTrack`
- `digital` is dark gray
- `Track` is bright cyan
- A thin cyan line and circle element sits under the wordmark and visually connects to the descriptor
- The descriptor `Digital Marketing` appears below the wordmark in a lighter, spaced style

Approved logo variants shown in the guide:

- full-color on light background
- reversed white logo on cyan or dark background
- grayscale / one-color style

### Logo Rules

Use these as hard constraints:

- do not distort the logo
- do not rotate the logo
- do not change element positions inside the lockup
- do not recolor the logo with off-brand colors
- preserve generous whitespace around the logo

The guide mentions exclusion zones but does not clearly define a measurable ratio in the reviewed export. Agents should preserve visible breathing room and avoid crowding the logo.

### Minimum Size

Confirmed from the guide:

- digital minimum width: `90px`
- print minimum width: `1.25in`
- no maximum size is defined

### Reference Proportion

One guide page shows the master logo at approximately:

- width: `9.83in`
- height: `2.75in`

Treat this as a reference example, not a mandatory output size.

## Color Palette

Confirmed from the guideline:

- Primary cyan: `#40D6E4`
  - RGB: `64, 214, 228`
  - CMYK: `58, 0, 15, 0`
- Dark gray: `#606165`
  - RGB: `96, 97, 101`
  - CMYK: `62, 54, 49, 22`
- Black: `#000000`
  - RGB: `0, 0, 0`
  - CMYK: `75, 68, 67, 90`
- White: `#FFFFFF`
  - CMYK: `0, 0, 0, 0`

Note: the guide's white RGB entry appears to show `25,255,255`, which is almost certainly a typo. Use standard white `255,255,255`.

## Typography

Working typeface recommendation:

- Primary font: `Montserrat`

Confidence level: medium-high.

Why:

- a full `Montserrat` package is included in this folder
- the brand materials visually align with a geometric sans approach
- no stronger competing type spec was found in the reviewed exports

Agent instruction:

- use Montserrat for headings, UI labels, and body copy unless a later official source overrides it
- keep typography clean, modern, and legible
- avoid decorative or script fonts

## Writing Guidance

When generating copy for DigitalTrack, prefer:

- direct language
- service clarity
- business outcomes
- local-business relevance
- credibility and trust
- accessible bilingual-ready structure

Tone should feel:

- clear
- competent
- modern
- helpful
- results-oriented

Avoid:

- vague hype
- startup jargon
- abstract mission language not supported by source material
- enterprise-only tone unless the specific audience requires it

## Offer And CTA Patterns

Current collateral suggests these messaging patterns:

- free consultation CTA
- QR-driven booking flow
- industry-specific positioning by vertical
- benefit-led copy before technical detail

Useful CTA examples:

- Book a free consultation
- Grow your visibility
- Get more qualified leads
- Improve your online reputation

## Bilingual / Localization Guidance

Because English and Spanish rack card content already exists:

- Spanish adaptations are brand-consistent
- keep service names understandable, not overly literal
- preserve the same business outcome emphasis in both languages

## Asset Notes

Useful source assets in this folder:

- `Logo source file/digital track with tagline(1).ai`
- `Logo source file/DT circle logo.svg`
- `Logo source file/black.PNG`
- `Logo source file/blue.PNG`
- `Logo source file/grey.PNG`
- `Logo source file/white.PNG`
- `Kit/Brand identity kit.PDF`

Sensitive or private items:

- Canva edit links in the `biz cards and rack cards/*.txt` files
- personal contact details in business card content
- raw PSD and AI files

Do not put sensitive links or personal details into public repos by default.

## Known Uncertainties

Agents should treat these as unresolved until verified:

- formal mission statement
- formal vision statement
- final approved brand values list
- exact typography hierarchy beyond Montserrat as the working family
- whether `Digital Marketing` is a fixed tagline in all contexts or just the current lockup descriptor
- whether `info@digitaltrack.c` in the extracted business card content is a typo for another email address
- whether `www. digitaltrack.co` in the extracted business card content contains spacing or copy issues

## Safe Agent Defaults

If an agent must make decisions without asking:

- use the full-color logo on white when possible
- use white logo on cyan or dark background when contrast requires it
- use `#40D6E4` and `#606165` as the main brand pair
- use Montserrat
- write for local service-business growth, trust, visibility, and lead generation
- keep layouts clean, modern, and uncluttered

## Recommended GitHub Setup

Best practice: keep the detailed brand source in its own private repo or private docs folder, then point agents to it from lightweight instruction files.

Recommended private repo structure:

```text
digitaltrack-brand-private/
  AGENTS.md
  CLAUDE.md
  docs/
    brand/
      DIGITALTRACK_BRAND_AGENT.md
      logo-usage.md
      messaging.md
  assets/
    logos/
    fonts/
  references/
    sanitized-guideline-pages/
```

### What To Store

Safe to store in a private repo:

- this agent brand file
- exported logo files
- font references if license allows
- sanitized brand guideline images or PDFs
- approved messaging blocks
- reusable prompts and design instructions

Store carefully or exclude:

- raw Canva edit links
- personal phone numbers and emails unless required
- oversized working PSD or AI files if the repo is meant mainly for agent context
- anything you may later want to share publicly

## AGENTS.md And CLAUDE.md

Yes, both can help, but they should stay short.

Use them as entrypoints, not as the full brand document.

Recommended pattern:

- `AGENTS.md` for Codex/OpenAI-style repo instructions
- `CLAUDE.md` for Claude Code or Claude Desktop workflows
- both files should point to the same detailed brand source file

Suggested `AGENTS.md` content:

```md
# Agent Instructions

Before writing copy, creating designs, or changing brand-facing UI, read:

- `docs/brand/DIGITALTRACK_BRAND_AGENT.md`

Hard rules:

- Do not invent mission, vision, or values from template pages.
- Use DigitalTrack colors and logo rules from the brand doc.
- Prefer Montserrat unless a newer official source overrides it.
- Keep tone practical, local-business focused, and results-oriented.
```

Suggested `CLAUDE.md` content:

```md
# Claude Project Notes

Brand reference:

- `docs/brand/DIGITALTRACK_BRAND_AGENT.md`

When generating brand-facing work:

- follow the confirmed logo and color rules
- use Montserrat as the working typeface
- keep messaging concrete and outcome-focused
- avoid using placeholder mission, vision, or sample contact details
```

## Maintenance Workflow

When new brand material is approved:

1. update this file first
2. mark each new rule as `confirmed` or `inferred`
3. keep AGENTS/CLAUDE files short and stable
4. remove template leftovers from source folders if they keep causing confusion

## Summary For Agents

DigitalTrack is a practical digital marketing brand focused on helping local businesses grow through reputation management, social media, SMS/email marketing, lead generation, and local SEO. The confirmed visual system centers on a gray-and-cyan logo, clean modern typography, and restrained use of color. Use Montserrat, keep layouts clean, preserve the logo lockup, and do not treat placeholder vision or mission pages as official brand strategy.
