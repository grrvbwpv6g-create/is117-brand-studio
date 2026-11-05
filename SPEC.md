# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Baseline tested; initial brand decisions agreed.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Brand identity established; modernist storefront and live style guide implemented. Design comparison and final validation pending.
- Next small decision: Compare modernist and postmodernist hero previews.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

| Tiny card                             | Primary audience                                                           | Secondary audience                                           |
| ------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Person in a concrete situation        | Young professionals ages 22–35 getting dressed for work or a casual outing | College students ages 18–24 choosing everyday campus outfits |
| Goal or meaning they seek             | Look polished, stylish, and confident                                      | Feel comfortable and look presentable on campus              |
| Concern before choosing               | Whether a plain white T-shirt can suit professional and casual styling     | Whether the shirt is practical and affordable                |
| What the page should help them decide | Whether this T-shirt fits their preferred polished, versatile style        | Whether this T-shirt suits their everyday wardrobe           |
| Evidence or assumption                | Assumption; not validated                                                  | Assumption; not validated                                    |

## Early brand brief

| Decision                                 | Agreement                                                                                                                          |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Brand name                               | THE EDIT                                                                                                                           |
| One-sentence promise                     | THE EDIT helps young professionals feel polished and confident through simple, versatile everyday style.                           |
| Primary archetype: the brand's character | The Ruler — confident, refined, and sophisticated                                                                                  |
| Three voice traits                       | Confident, Sophisticated, Minimalist                                                                                               |
| One example line in this voice           | Confidence begins with simplicity.                                                                                                 |
| Learner's predicted audience effect      | Young professionals may perceive THE EDIT as polished, professional, and easy to style. This is a prediction, not a tested result. |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                                                                                                                       |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Headline: "Confidence Begins With Simplicity." Support: "A white T-shirt for effortless everyday styling." Action: "Explore the Tee". Identical in both previews.                                                                                                                                                                                           |     |
| Modernist preview, reference, and annotations     | Modernist hero preview created in public/studio.html and styled in public/studio.css. Uses neutral colors, bold sans-serif typography, generous whitespace, and structured alignment. Intended effect: communicate simplicity, confidence, and sophistication. External design reference and detailed annotations still pending.                            |
| Postmodernist preview, reference, and annotations | Postmodernist hero preview created in public/studio.html and styled in public/studio.css. Uses bright yellow-green, oversized uppercase typography, a thick black border, and a rotated layout. Intended effect: create an energetic, expressive, and unconventional shopping experience. External design reference and detailed annotations still pending. |
| Chosen direction and reason                       | Modernist. I chose this direction because its clean layout, neutral colors, bold typography, and organized spacing support THE EDIT's confident and sophisticated brand identity. The postmodernist alternative is visually energetic but less consistent with the professional, timeless image I want to communicate to young professionals.               |
| Original SVG logo                                 | Not chosen yet                                                                                                                                                                                                                                                                                                                                              |
| Monochrome and small-size variants                | Monochrome black wordmark created. White-background preview verified. Small-size and reversed white versions still need testing.                                                                                                                                                                                                                            |
| Original SVG logo                                 | Created public/the-edit-logo.svg — an original bold uppercase THE EDIT wordmark with wide letter spacing and a minimalist design. Verified that it displays correctly in Safari.                                                                                                                                                                            |
| Shared palette, typography, spacing, and assets   | Not chosen yet                                                                                                                                                                                                                                                                                                                                              |

### Design references

- Modernist reference: The Metropolitan Museum of Art,
  "The Bauhaus, 1919–1933."
  https://www.metmuseum.org/toah/hd/bauh/hd_bauh.htm
  Inspiration: Functional design, simplified forms, and
  clear visual organization. THE EDIT applies these ideas
  through neutral colors, structured alignment, and
  readable sans-serif typography.
- Postmodernist reference: David Carson, experimental
  graphic design and typography.
  https://www.davidcarsondesign.com/
  Inspiration: Expressive typography, unconventional
  composition, and breaking traditional grid structures.
  THE EDIT's Postmodernist preview explores these ideas
  through oversized uppercase text, bold color contrast,
  and a slightly rotated layout.
- Comparison: Both previews use the same product, headline,
  description, and action so that the visual design can be
  compared fairly.

### Design annotations

**Modernist preview**

1. Neutral colors create a clean, sophisticated appearance.
2. Bold sans-serif typography makes the product headline easy to read.
3. Generous whitespace and structured alignment help customers focus on the T-shirt.

**Postmodernist preview**

1. Bright yellow-green creates strong visual contrast and attracts attention.
2. Oversized uppercase typography gives the design an expressive personality.
3. The rotated layout and thick black border challenge traditional, orderly composition.

**Final choice:** Modernism fits THE EDIT's young professional audience and its promise of effortless confidence better than the more experimental Postmodernist direction.

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                | Actual copy or interaction                                                                                             | Visitor benefit / factual support                                                                                 |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Unity                    | Implemented: Added a message connecting customers through a shared appreciation for simple, confident everyday style.  | Helps visitors understand THE EDIT's brand identity without making unsupported claims about a customer community. |
| Commitment & Consistency | Implemented: Added an optional Casual or Smart Casual style preference dropdown with personalized styling suggestions. | Helps visitors explore how the white T-shirt fits their personal style without pressure or misleading claims.     |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files           | Issue / PR      | Actual checks and observations            |
| --------- | --------------- | --------------- | ----------------------------------------- |
| BRAND-001 | Not changed yet | Not created yet | Not run yet; learner observations pending |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
