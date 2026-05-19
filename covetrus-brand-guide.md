# Covetrus Brand Guide
> This file is designed to be used as a reference for AI tools (Claude, Copilot, etc.), developers, designers, and anyone creating Covetrus-branded content. Attach it to a Claude Project, paste it into a system prompt, or reference it in any AI tool to ensure brand-consistent outputs.

---

## 1. Brand Identity

**Company Name:** Covetrus
**Industry:** Veterinary health technology and services
**Mission:** To advance the world of veterinary medicine by empowering practitioners with the technology, products, and solutions they need to thrive.
**Tone:** Professional, trustworthy, forward-thinking, warm, and science-backed. Covetrus speaks with confidence but never arrogance. We are a partner to veterinary professionals, not a vendor.

**Brand Philosophy:** Our brand is one of the most valuable assets we have. Every time someone encounters our name, our work, or our content, whether in a product, a proposal, a social post, or an AI-generated output, they form an impression of who we are. Consistency is what turns those individual moments into a recognizable, trustworthy identity.

**Sub-brands:** Covetrus operates a family of brands including VetSuite, vRxPro, GreatPet Care, Pulse, and Prop Brands. Each has its own identity but operates within the Covetrus brand system.

---

## 2. Logo

The Covetrus master brand logo is the foundation, but our portfolio includes a family of point solution logos that extend the brand across our products and services. Each point solution logo has been designed to work within the Covetrus brand system while carrying its own identity.

All logo versions are stored in our central asset library on SharePoint. Always pull logo files from this source to ensure you are using the most current, approved version. Do not recreate, alter, or source logos from anywhere else.

### Logo Variants
| Variant | File | Usage |
|---|---|---|
| Full Wordmark – RGB | `Covetrus_RGB.svg` | Primary use on white/light backgrounds |
| Full Wordmark – Knockout (KO) | `Covetrus_RGB_KO.svg` | Use on dark or colored backgrounds |
| Full Wordmark – Black | `Covetrus_Black.svg` | Single-color print, light backgrounds |
| Full Wordmark – White | `Covetrus_White.svg` | Use on dark backgrounds, single-color white contexts |
| Icon/Bug – RGB | `Covetrus_Bug_RGB.svg` | Small spaces, app icons, favicons, social avatars |
| Icon/Bug – Knockout (KO) | `Covetrus_Bug_RGB_KO.svg` | Icon use on dark backgrounds |
| Icon/Bug – Black | `Covetrus_Bug_Black.svg` | Single-color print, light backgrounds |
| Icon/Bug – White | `Covetrus_Bug_White.svg` | Icon use on dark backgrounds, single-color white |

### Logo Do's
- Use SVG for all web, app, and screen contexts
- Use PNG when transparency is needed (presentations, overlays)
- Use JPG for PowerPoint slides and email signatures
- Use the KO/White variants on dark or colored backgrounds
- Maintain clear space equal to the height of the "C" on all sides

### Logo Don'ts
- Do not modify colors, rotate, skew or distort elements
- Do not add shadows, outlines, gradients or effects
- Do not move or modify the ® or ™ symbols
- Do not move or rearrange elements
- Do not create new logos without involving the creative team

### Partnership Logo Guidelines

When locking up the Covetrus logo with a partner or co-branded mark, follow the rules below to keep the relationship between the two brands clear, balanced, and consistent.

**External Partner Lockup:**
- The Covetrus logo should always be on the left side and the partner logo on the right.
- There should be a thin line between the two logos that is the height of the Covetrus logo.
- The line should be grey, hex `#6E6E6E`.

**Internal Covetrus Product Lockup:**
- For internal Covetrus product lockups where two of our own brands are featured together, use a plus sign between the logos (also hex `#6E6E6E`) instead of a vertical line.

---

## 3. Color Palette

Color is one of the most immediate and powerful expressions of our brand. Used consistently, our palette builds recognition over time. Primary colors carry the weight of the brand and should do the most work across our touchpoints. Secondary and accent colors exist to support, not compete.

All color combinations used for text, UI elements, and critical information must meet WCAG 2.1 AA contrast standards at minimum.

### Primary Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Vet Blue | `#021660` | rgb(2, 22, 96) | Primary brand color. Use for headings, primary text, buttons, nav, and dominant UI elements. |
| Care Red | `#ED3030` | rgb(237, 48, 48) | Use for alerts, badges, emphasis, and energy/urgency. |
| Tech Teal | `#27BDBE` | rgb(39, 189, 190) | Use for highlights, links, CTAs, icons, and progress indicators. |

### Accent Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Action Blue | `#0055E7` | rgb(0, 85, 231) | Interactive accent. Use for links, hover states, and digital call-to-action elements. |
| Medium Blue | `#75C1FF` | rgb(117, 193, 255) | Secondary blue accent. Use for icons, highlights, and supporting UI elements. |
| GreatPet Green | `#008556` | rgb(0, 133, 86) | Brand extension accent. Use for GreatPet-related content, success states, and positive indicators. |

### Color Spectrums (Full Tint-to-Shade Ranges)

**Vet Blue:** `#F3FBFF`, `#E8F7FF`, `#B3E0FF`, `#75C1FF`, `#46A2FB`, `#1474E5`, `#0055E7`, `#11338A`, **`#021660`**, `#02114B`

**Tech Teal:** `#ECFCFC`, `#D7F5F2`, `#B1ECE6`, `#7CDCD9`, **`#27BDBE`**, `#05A5A5`, `#0F7785`, `#0B4A53`, `#0C3238`

**Care Red:** `#FFF5F5`, `#FCD9D9`, `#F9ABAB`, `#FF8585`, **`#ED3030`**, `#C01E2C`, `#A40E20`, `#750A17`, `#4F0615`

**GreatPet Green:** `#EAF6F3`, `#CCF2D9`, `#96E6B2`, `#6ED299`, `#41B87F`, `#159F6C`, **`#008556`**, `#015C43`, `#133A33`

**Neutral:** `#FFFFFF`, `#F7F7F7`, `#F1F1F1`, `#E8E8E8`, `#D9D9D9`, `#CACACA`, `#A9A9A9`, `#919090`, `#6E6E6E`, `#484848`, `#2C2C2C`, `#191919`

### CSS Variables (for software/UI use)
```css
:root {
  --color-vet-blue: #021660;
  --color-tech-teal: #27BDBE;
  --color-care-red: #ED3030;
  --color-action-blue: #0055E7;
  --color-medium-blue: #75C1FF;
  --color-greatpet-green: #008556;
  --color-black: #191919;
  --color-gray-light: #F7F7F7;
  --color-gray-mid: #6B7280;
}
```

---

## 4. Typography

Our primary typeface is Mulish. We made a deliberate shift to Mulish because it is purpose-built for digital environments, optimized for screen rendering, highly legible at small sizes, and designed with accessibility in mind. Its clean, open letterforms perform consistently across interfaces, documents, and AI-generated content.

For environments where Mulish cannot be rendered, most notably Microsoft Outlook and email clients, use Arial as the standard fallback. Arial shares Mulish's clean, sans-serif character and maintains a professional, readable appearance across all platforms and devices.

Do not substitute decorative, serif, or system-default fonts like Calibri or Times New Roman, as these are inconsistent with our brand aesthetic.

### Font Stack
| Role | Font | File | Weight(s) |
|---|---|---|---|
| All text | `Mulish` (variable) | `Mulish-VariableFont_wght.ttf` | 200–900 (full range) |
| Fallback | `Arial` | System font | Regular, Bold |
| Monospace / Code | System monospace | — | 400, 500 |

### Type Scale (Desktop)
| Level | Size | Weight | Line Height | Usage |
|---|---|---|---|---|
| H1 | 48px / 3rem | 900 | 1.1 | Page heroes, major section titles |
| H2 | 36px / 2.25rem | 800 | 1.2 | Section headings |
| H3 | 24px / 1.5rem | 700 | 1.3 | Card titles, subsections |
| H4 | 18px / 1.125rem | 700 | 1.4 | Labels, minor headings |
| Body | 16px / 1rem | 400 | 1.6 | All paragraph text |
| Small | 14px / 0.875rem | 400 | 1.5 | Captions, footnotes, metadata |
| Label / Tag | 12px / 0.75rem | 800 | 1.4 | Uppercase tags, eyebrow text |

### Typography Rules
- **All text** uses Mulish. There is no secondary typeface — use weight variation to create hierarchy.
- **Headlines** should be set in Vet Blue (`#021660`) on light backgrounds, or White on dark backgrounds.
- **Body text** should be Near Black (`#191919`) on light backgrounds for maximum readability.
- **Never** use Tech Teal or Care Red for body text — reserve them for interactive elements or very short emphasis.
- Line length (measure) should be kept between 60–80 characters for body text.
- Do not justify body text. Use left-align for all body copy.
- Use uppercase + weight 800 for labels, tags, and eyebrow text only. Never uppercase body copy.
- Typography applied well creates clarity. Applied poorly, it creates friction. Respect the type hierarchy, use weights intentionally, and never sacrifice legibility for style.

---

## 5. Photography

Select a brand to find authorized and approved lifestyle images for that area of business. Photography is organized by sub-brand: Covetrus, VetSuite, vRxPro, GreatPet Care, Prop Brands, and Pulse.

### Photography Style
- Imagery should feature real veterinary professionals in authentic working environments.
- Avoid overly staged or stock-photo aesthetics.
- Color grade should be warm-neutral — avoid cold blue tones.
- Animals (pets and livestock) should appear healthy and well cared for.
- People of diverse backgrounds, ages, and specialties should be represented.

### Legal & Compliance Guardrails — Images & Photography
All images used in Covetrus materials must be:
- Licensed by a third party for our use, **or**
- Property of Covetrus, **or**
- Authorized for use with a signed permission agreement on file

Always confirm image rights before use. Images must be appropriate for the product and audience.

---

## 6. Icons

32 icons are available in 4 colorways. Each icon is downloadable as SVG or PNG. Use SVG wherever possible for crisp rendering at any size; PNG is appropriate for presentations and email signatures.

### Icon Style
- Use **line icons** (stroke-based) at 1.5–2px stroke weight.
- Icons use two-color combinations: a primary color and an accent color.
- Four approved icon colorways:
  1. Black (`#191919`) + Medium Blue (`#75C1FF`) — light backgrounds
  2. Black (`#191919`) + Tech Teal (`#27BDBE`) — light backgrounds
  3. White (`#FFFFFF`) + Medium Blue (`#75C1FF`) — dark backgrounds
  4. White (`#FFFFFF`) + Tech Teal (`#27BDBE`) — dark backgrounds
- Do not mix filled and outline icons in the same UI context.

---

## 7. Voice, Tone & Legal Language Guide

How we write is as much a part of our brand as how we look. This section covers our voice and tone across B2B and B2C audiences, our do's and don'ts, trademark and registration mark usage, and the legal and compliance guardrails every piece of creative must follow. **When in doubt on anything in this section, stop, and ask Legal or Creative before proceeding.**

### Our Voice

Covetrus has one voice, but the way we use it shifts depending on who we are talking to. Our voice is always:

- **Professional but warm** — Credible without being cold, knowledgeable without being condescending.
- **Solutions-oriented** — We lead with how we help, not what we sell.
- **Honest and grounded** — We never overstate, we substantiate what we claim, and we treat our audience as the capable professionals they are.
- **Human** — We write for real people, in language they actually use.

### Tone by Audience

#### B2B — Veterinary Professionals
Our B2B audience — DVMs, practice managers, and veterinary staff — are busy, smart, and skeptical of marketing that oversells. But before they are professionals, they are people who chose this work for a reason. Most entered veterinary medicine out of a deep love for animals and a desire to make a difference in the lives of the pets and people who depend on them. They are driven by purpose, not just process, and the best creative we make speaks to both.

Our tone is professional, credible, and supportive, but it is also human. We acknowledge the weight of what veterinary teams carry: the long hours, the emotional demands, the business pressures that can pull focus away from why they started. We are a partner to the practice and to the people within it. We never pitch at them. We speak directly, avoid jargon, and never use urgency tactics that imply pressure. When our work reminds veterinary professionals that Covetrus exists to give them more time, more confidence, and more capacity to do the work they love, that is when we are at our best.

##### B2B — Language & Claims
**Don't use:**
- "Your online pharmacy"
- "Improves your patient compliance"
- "Boosts practice revenue"
- "The only product you'll ever need"
- "Improves the health of veterinarians"
- "Comparable to…"

**Use instead:**
- "Your online storefront" / "your practice-branded online storefront"
- "Can help support patient compliance"
- "Helps practices keep more revenue in-house"
- Focus on specific, substantiated benefits
- Do not use human health benefit references at all
- Only use with supporting data on file — confirm with Legal

##### B2B — Unsubstantiated Superlatives
The following words are prohibited unless a supporting citation is on file and confirmed with Legal before use:
- "Best"
- "Trusted" / "Trust"
- "Superior"
- "Unsurpassed"
- "Always" / "Never" (in a claims context)
- "Better" — permitted only when supported by a direct comparison with data on file

**Cushion language rule:** When making product or outcome claims, always use softening language — "can," "may," "help," or "designed to" — unless the claim is directly substantiated with a cited data source.

##### B2B — Exchange-of-Value Language
The following words can implicate anti-bribery policy and business courtesy violations. Do not use in any marketing materials unless the program has been explicitly pre-approved by Compliance or Legal:
- "Deal"
- "Gift"
- "Benefits"
- "Get" (in the context of receiving something of value)

**Comparison claims:** All comparison charts and competitive claims must be supported by evidence or data. Provide the citation and source to the Creative and C&C teams. Do not publish comparison claims without substantiation on file.

#### B2C — Pet Parents & Horse Owners
Our B2C audience leads with emotion, but that emotion looks very different depending on who we are talking to. Understanding the distinction between our companion animal and equine audiences is not a small detail. It is fundamental to writing copy that earns credibility and trust.

##### B2C — Pharmacy & Storefront Language
**Don't use:**
- "Your veterinarian's online pharmacy"
- "Our online pharmacy"

**Use instead:**
- "Your veterinarian's online storefront"
- "Your practice-branded online storefront"

##### B2C — Prohibited Words for Products
The following words may not be used in product copy unless they are sourced directly from manufacturer language and a citation is included:
- Trusted
- Treat
- Relieve
- Best
- All
- Stock up

#### Companion Animal — Pet Parents
Pet parents love their animals deeply. Their pets are family, and when it comes to their health and care, they want the best. Our tone is warm, clear, and reassuring. We use accessible language, meet pet parents where they are, and never talk down to them.

But B2C communication for Covetrus carries a unique responsibility: in most cases, we are not speaking as Covetrus, we are speaking on behalf of the veterinarian. The vet is the trusted voice in the pet parent relationship, and our role is to support and extend that trust, not replace or compete with it. Every piece of B2C communication should feel like it is coming from the practice, reinforcing the bond between pet parent and their veterinary team, and making it easier for them to follow through on the care their vet has recommended.

In other cases, Covetrus is the vet's partner in the background, powering the experience, the storefront, the reminders, and the tools, without stepping in front of the relationship. In these moments our job is to be seamless, reliable, and entirely in service of the practice and the pet parent they are caring for.

##### Referring to Pets — Canine & Feline
"Pet" is our primary term. The following may be used for variety and tone:

**OK to use:**
- Dog / cat
- Pup / puppy / kitten (when age-relevant)
- Best friend
- Furry family member
- Four-legged family member
- Canine / feline companion
- Loyal companion
- Pronouns: they / them

**Never use:**
- "It" when referring to a pet
- "Fur baby"
- "Doggo"
- "Pupper"
- Other overly cutesy terms

#### Equine — Horse Owners
The equine audience is its own world, and it demands its own voice. Horse owners range from competitive sport and performance riders to recreational owners, breeders, and farm operators. What they share, regardless of discipline or background, is a deep and serious relationship with their horse. This is not casual pet ownership. It is a lifestyle, a livelihood, and in many cases an identity.

This audience is knowledgeable, no-nonsense, and highly attuned to anything that feels inauthentic. They respect expertise and practicality. They do not respond to overly emotional, consumer-brand language, and they will immediately distrust copy that feels like it was written for a dog food commercial. Earn their respect by speaking to them as the experienced, informed horse people they are.

The same principle applies here as with companion animal B2C — in most cases we are speaking on behalf of the veterinarian, or as their partner behind the experience. The equine vet relationship is built on deep professional trust, and our communications must always honor and reinforce that.

##### Referring to Horses
"Horse" is our primary term. The following may be used for variety:

**OK to use:**
- Equine companion
- Four-legged family member
- Pronouns: they / them — avoid where possible and use "your horse" instead

**Never use:**
- "It" when referring to a horse
- Referring to horses as "pets"

### Trademark & Registration Mark Usage

Trademark and registration marks are not a formality, they are a legal protection for our brand and our business. Using them correctly is everyone's responsibility.

- **® (Registered)** — used for marks that are officially registered with the USPTO. This is a legal designation and may only be used for registered marks.
- **™ (Trademark)** — used for marks that are claimed as trademarks but may not yet be registered.

**The rule:** Always use the correct mark at **first mention** of a product or brand name in any marketing material, print or digital. Subsequent mentions within the same piece do not require the mark.

#### Correct Usage by Brand & Product

**Covetrus Brands & Platforms:**
- Covetrus®
- VetSuite®
- Covetrus® Pulse®
- Pulse®
- Covetrus® vRxPro®
- vRxPro®
- Covetrus® Compounding
- Covetrus® Payments
- Covetrus® Pulse® and Zoetis Diagnostics
- Covetrus® Supply
- Covetrus® Brand Products
- Equipment
- Covetrus® CarePlans
- Covetrus® Comms
- Covetrus® GreatPetCare®
- GreatPetCare®
- New Build Services
- Financial Services

**Compounding Products:**
- ezPress Tablets
- Soft Chew
- MiniTab™
- MiniMelt™
- FlexTab™
- AccuClick Pen
- Oti-Pack®
- Flavored MiniTab™
- Flavored Tablets

**Proprietary Brands:** List coming soon.

**Manufacturer Partner Brands:** Must be formatted and spelled correctly as provided by the manufacturer, e.g., "MalAcetic" not "Malacetic." When in doubt, confirm spelling and mark status with Legal before publishing.

**Never:**
- Add ® to a mark that is not registered
- Omit ® or ™ on first mention in any external-facing material
- Use the Covetrus® logo in-line with another brand's logo without prior approval from the Intellectual Property attorney (see Partnership Logo Guidelines)

#### Pharmaceutical Drug Products
- Confirm whether each product is Registered® or Trademarked™ before publishing.
- All claims must align with package insert language, indications, adverse reactions, and contraindications.
- Important Safety Information or Brief Summary must be conveyed in legible font.
- Do not make claims that imply clinical outcomes unless reviewed and approved by Legal.

#### Print & Digital Article Content
- Articles must have an author or verified source.
- If written by a Covetrus employee, include their title and credentials (e.g., Link Welborn, DVM, Chief Veterinary Officer, North America).
- If ghostwritten, a written confirmation of ghostwriter permissions and Covetrus copyright must be on file.
- Data, claims, and medical information must be referenced with superscript and footnote, following style citation rules.

#### Sweepstakes, Giveaways & Surveys
Consult Legal on Incentive Guidelines and appropriate disclaimer language before any sweepstakes, giveaway, or survey goes to market. **Do not proceed without Legal sign-off.**

---

## 8. When in Doubt — Ask

Legal and Creative are here to help, not slow you down. If something isn't covered here, or you're not sure whether a claim, word, or asset is approved, reach out to Legal or Creative before it goes out.

**It is always faster to ask first than to fix it after.**

---

## 9. Social Media Guidelines

### Platform Tone
| Platform | Tone | Content Focus |
|---|---|---|
| LinkedIn | Professional, thought leadership | Industry insights, company news, careers |
| Instagram | Visual, warm, community-focused | Behind-the-scenes, team, pet-forward content |
| X / Twitter | Concise, timely, conversational | Industry news, quick tips, event coverage |
| Facebook | Informative, community | Product updates, educational content |

### Post Formatting
- Always include the Covetrus logo or watermark on owned creative assets.
- Use Tech Teal (`#27BDBE`) as the primary accent color in social graphics.
- Hashtags: use 3–5 maximum. Always include `#Covetrus` on owned posts.
- Emojis: acceptable on Instagram and X; use sparingly on LinkedIn (1–2 max).

---

## 10. Internal Document Standards

### Document Header
All internal documents should include:
- Document title (H1, Vet Blue)
- Author name, department, date
- Version number (e.g., v1.0)
- Status tag: `Draft`, `In Review`, or `Approved`

### Formatting Rules
- Use Mulish for all text. If unavailable, use Arial as fallback.
- Section headings in Vet Blue, body text in Near Black.
- Use tables for comparative data; avoid dense prose lists when a table is clearer.
- All internal docs should be stored in the approved document management system with proper naming conventions: `YYYY-MM-DD_Department_DocumentTitle_v1.0`.

---

## 11. Using This Guide With AI Tools

### Claude Projects (Recommended)
1. Go to [claude.ai](https://claude.ai) and create a new **Project**.
2. In the Project knowledge section, upload this file (`covetrus-brand-guide.md`).
3. Every conversation in that Project will now have full brand context.
4. Suggested system prompt addition: *"Always follow the Covetrus brand guide when generating content, UI code, or copy."*

### Other AI Tools
- **Cursor / GitHub Copilot:** Add this file to your `.cursorrules` or reference it in your system prompt for brand-consistent UI code.
- **ChatGPT:** Attach this file to a Custom GPT or paste relevant sections into the system prompt.
- **Any LLM API:** Include this file as a `system` message document block.

### Prompting Tips
When using AI to generate Covetrus content, include phrases like:
- *"Use the Covetrus brand guide"*
- *"Vet Blue (#021660) as primary color, Tech Teal (#27BDBE) for CTAs"*
- *"Tone: professional, warm, and forward-looking"*
- *"Font: Mulish for all text, Arial as fallback for email"*
- *"Voice: professional but warm, solutions-oriented, honest and grounded, human"*

---

*Last updated: May 2026 | Maintained by: Creative Team*
*Any assets intended for external release should be reviewed and approved by Creative before going out.*
*Materials that represent the company publicly should be reviewed by Legal.*
*For questions, contact the Creative team. When in doubt — ask.*
