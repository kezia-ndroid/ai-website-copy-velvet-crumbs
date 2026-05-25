# AI Website Copy Generator — Velvet Crumbs Cafe
### Prompt Engineering Task | Future Interns 2026

## Business Chosen

**Velvet Crumbs Cafe**
Location: Kottayam, Kerala, India
Type: Local cafe — coffee, bakes, Kerala breakfast, coworking-friendly
Target Audience: Students, working professionals, families, and locals

## What This Project Does

This project uses structured AI prompts to generate
conversion-focused website copy for Velvet Crumbs Cafe —
a real local business in Kottayam, Kerala.

The copy covers:
- Homepage headline, sub-headline, and intro
- Services page with 6 detailed descriptions
- 4 CTA sections (primary, trust-builder, urgency, footer)
- Tone-adapted, location-specific language throughout

## Tools Used

| Tool     | Purpose                          |
|----------|----------------------------------|
| Claude   | Primary copy generation          |
| ChatGPT  | Prompt testing and variations    |
| Gemini   | Tone adaptation experiments      |
| GitHub   | Version control and portfolio    |

## Repository Structure

ai-website-copy-velvet-crumbs/
├── README.md
├── prompts/
│   ├── 01_homepage_prompt.txt
│   ├── 02_services_prompt.txt
│   ├── 03_cta_prompt.txt
│   └── 04_tone_adapter_prompt.txt
├── outputs/
│   ├── homepage_copy.md
│   ├── services_copy.md
│   └── cta_sections.md

## Prompt Logic

Each prompt is structured around 5 elements:

1. ROLE — Tell the AI who it is
   "You are a professional copywriter for local businesses."

2. CONTEXT — Name, location, business type
   "Write copy for Velvet Crumbs, a cafe in Kottayam, Kerala."

3. OUTPUT — Exactly what sections to produce
   "Include: headline, sub-headline, intro paragraph."

4. TONE — How it should feel
   "Warm, friendly, local. Avoid generic phrases."

5. FORMAT — How to structure the response
   "Output: Headline / Sub-headline / Intro"

This 5-part structure makes every prompt reusable —
just swap the business name, location, and tone.


## Prompt 1 — Homepage Copy

You are a professional copywriter for local businesses.
Write homepage copy for "Velvet Crumbs", a cafe in Kottayam, Kerala.

Include:
- A headline (under 8 words, punchy and warm)
- A sub-headline (who it's for + key benefit)
- A 3-sentence intro paragraph

Tone: Warm, friendly, local.
Avoid: Clichés like "best cafe" or "quality service".
Format: Headline / Sub-headline / Intro paragraph

## Prompt 2 — Services Page

Write service descriptions for "Velvet Crumbs" cafe
in Kottayam, Kerala.

Services: Filter Coffee, Cold Brew, Fresh Pastries,
Kerala Breakfast, Work-Friendly Space, Private Bookings.

For each service:
- Service name
- 2 sentences: what it is + why customers love it
- One emotional hook at the end

Tone: Cozy, proud, local. Avoid generic food-blog language.


## Prompt 3 — CTA Sections

Write 3 call-to-action sections for "Velvet Crumbs"
cafe in Kottayam, Kerala.

CTA 1 — Primary: persuade visitors to visit or book
CTA 2 — Trust builder: 4 bullet points why locals love us
CTA 3 — Urgency/location: mention proximity to
         Kottayam Railway Station + a morning offer

Tone: Friendly, confident. No pressure tactics.


## Prompt 4 — Tone Adapter (Reusable for Any Business)

Rewrite the following website copy for [BUSINESS NAME]
in [LOCATION].

Adapt tone to: [friendly / professional / confident]
Target audience: [students / families / professionals]
Key selling point: [what makes this business unique]


## Sample Output — Homepage

Headline:
Every Crumb Tells a Story.

Sub-headline:
Kottayam's most-loved cafe — where slow mornings,
handmade pastries, and real Kerala coffee come together.

Intro:
At Velvet Crumbs, we believe the best conversations
happen over a good cup. Walk in as a stranger, leave
as a regular. That's the Velvet Crumbs promise.

## How to Reuse for Other Businesses

1. Open any prompt file in /prompts/
2. Replace business name, location, and tone
3. Paste into Claude, ChatGPT, or Gemini
4. Save the output in /outputs/
5. Repeat for each section

This system can generate a full website copy set
for any local business in under 10 minutes.

## Author
Created by: Kezia K Babu
Program: Future Interns — Prompt Engineering Task 2026
LinkedIn: https://www.linkedin.com/in/kezia-k-babu
