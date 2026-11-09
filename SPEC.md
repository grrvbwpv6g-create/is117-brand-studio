# Brand Studio decisions

This is the durable record of learner decisions and project evidence. Audience cards are hypotheses, not customer research. See [LEARNING.md](LEARNING.md) for the short record of learner explanations and help received.

## Current stage

- Stage: BRAND-001 implementation completed; the learner chose to keep the modernist THE EDIT design.
- Current feature: `BRAND-001` — THE EDIT branded storefront and live style guide.
- Status: Storefront, live style guide, design comparison, responsive improvements, and local automated checks are documented below. BRAND-001 was merged in [pull request #2](https://github.com/grrvbwpv6g-create/is117-brand-studio/pull/2).
- Live website: [THE EDIT](https://grrvbwpv6g-create.github.io/is117-brand-studio/).
- Remaining verification: The latest mobile CSS changes have passed the local check; a GitHub Actions run against those latest changes is not yet confirmed. The learner tested keyboard focus movement and one dropdown selection in Safari; broader keyboard coverage, including every button and the demo bag, is not claimed.

## Product boundary

THE EDIT is a fictional white T-shirt storefront prototype. It offers size selection, styling suggestions, and a temporary demo bag; it does not place orders, collect payment or personal information, or persist the bag after reload. Product facts are fictional; no claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales are made.

## Audience hypotheses

| Tiny card                             | Primary audience                                                           | Secondary audience                                           |
| ------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Person in a concrete situation        | Young professionals ages 22–35 getting dressed for work or a casual outing | College students ages 18–24 choosing everyday campus outfits |
| Goal or meaning they seek             | Look polished, stylish, and confident                                      | Feel comfortable and look presentable on campus              |
| Concern before choosing               | Whether a plain white T-shirt can suit professional and casual styling     | Whether the shirt is practical and affordable                |
| What the page should help them decide | Whether this T-shirt fits their preferred polished, versatile style        | Whether this T-shirt suits their everyday wardrobe           |
| Evidence or assumption                | Assumption; not validated by customer research                             | Assumption; not validated by customer research               |

## Brand brief

| Decision                            | Agreement                                                                                                                          |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Brand name                          | THE EDIT                                                                                                                           |
| One-sentence promise                | THE EDIT helps young professionals feel polished and confident through simple, versatile everyday style.                           |
| Primary archetype (brand character) | The Ruler — confident, refined, and sophisticated                                                                                  |
| Three voice traits                  | Confident, Sophisticated, Minimalist                                                                                               |
| Example line                        | “Confidence begins with simplicity.”                                                                                               |
| Learner's predicted audience effect | Young professionals may perceive THE EDIT as polished, professional, and easy to style. This is a prediction, not a tested result. |

## Visual decision

Two design directions in [public/studio.html](public/studio.html) compare the same product, headline, supporting copy, and action. The live comparison is exploratory and does not change the chosen modernist storefront.

| Item                                          | Agreement or implementation                                                                                                                                                                                                                                                                                                                                                    |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Shared headline / support / action            | “Confidence Begins With Simplicity.” / “A white T-shirt for effortless everyday styling.” / “Explore the Tee”.                                                                                                                                                                                                                                                                 |
| Modernist direction                           | Neutral colors, bold sans-serif typography, generous whitespace, and structured alignment. The coded direction is intended to emphasize simplicity, confidence, and sophistication.                                                                                                                                                                                            |
| Postmodernist direction                       | Bright yellow-green, oversized uppercase typography, a thick black border, and rotated/asymmetrical placement; intended as an energetic, expressive contrast.                                                                                                                                                                                                                  |
| Chosen direction and reason                   | Modernist. The learner chose its clean layout, neutral colors, bold typography, and organized spacing to support THE EDIT's confident and sophisticated identity for young professionals; the more experimental direction felt less consistent with the desired professional, timeless image.                                                                                  |
| Design references recorded for the comparison | The Metropolitan Museum of Art, “The Bauhaus, 1919–1933”: https://www.metmuseum.org/toah/hd/bauh/hd_bauh.htm . David Carson, experimental graphic design and typography: https://www.davidcarsondesign.com/ . These links are the references recorded in the project; the comparison applies simplified forms/organization and expressive typography/composition respectively. |
| Original SVG logo                             | [public/the-edit-logo.svg](public/the-edit-logo.svg), an original uppercase THE EDIT wordmark with wide letter spacing. Used in the storefront and style guide.                                                                                                                                                                                                                |
| Logo presentations                            | The style guide shows the wordmark at a small size and with a monochrome black treatment; the same SVG source is used. The recorded Safari check verified the logo display. No trademark clearance is claimed.                                                                                                                                                                 |
| Shared styling                                | The storefront and style guide load [public/styles.css](public/styles.css) and use the same wordmark asset. The studio comparison has its own page-specific styling.                                                                                                                                                                                                           |

### Design annotations

These are the design intentions recorded for the two coded directions, not customer research:

**Modernist**

1. Neutral colors and whitespace support a clean, sophisticated presentation.
2. Bold sans-serif type gives the headline a clear hierarchy.
3. Structured alignment organizes the product and message.

**Postmodernist**

1. Bright yellow-green and strong contrast attract attention.
2. Oversized uppercase type gives the direction an expressive character.
3. Rotated placement and a heavy border interrupt a conventional grid.

**Final direction:** Modernist, for the reasons in the learner's recorded choice above.

## Storefront, style guide, and interactions

- The [storefront](public/index.html) applies THE EDIT identity to the white T-shirt, navigation, product description, and demo-shopping interaction.
- The [live style guide](public/styleguide.html) documents the wordmark, neutral palette, typography, spacing, components, and voice using the same shared stylesheet and logo asset. Some instructional labels remain on the guide; this record describes the implementation, not a claim that every starter prompt has been removed.
- The [design studio](public/studio.html) includes a modernist/postmodernist comparison using matching product copy and action.
- Visitors can choose S, M, L, or XL. Submitting without a size displays an error and does not add an item.
- The in-memory demo bag tracks selected sizes and quantities, can be emptied, and resets when the page reloads.
- The optional Casual or Smart Casual dropdown changes its styling suggestion. It is an invitation to explore a preference, not a purchase commitment.

## Ethical persuasion

| Principle                                         | Actual page element and mechanism                                                                                                                 | Visitor benefit and limits                                                                                                                                                                |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Unity                                             | The storefront's brand-unity message invites visitors who value simple, confident everyday style to recognize the brand's intended point of view. | Communicates identity without claiming that customers form a proven community or inventing customer endorsements.                                                                         |
| Commitment & Consistency (lightweight, voluntary) | The visitor may choose Casual or Smart Casual and then receives a suggestion matching that selected preference.                                   | The suggestion follows the visitor's optional choice and helps explore personal styling. It does not imply a purchase commitment, and the feature is not evidence of improved conversion. |

## BRAND-001 — THE EDIT branded storefront and live style guide

**Scope delivered:** Apply the selected THE EDIT identity to the storefront and shared live style guide, retain the functional size selector and demo bag, and provide two contrasting design explorations. No checkout or customer accounts were added.

**Keep decision:** The learner selected the modernist direction and chose to keep the improved spacing and responsive layout. The completed BRAND-001 work is linked in merged [pull request #2](https://github.com/grrvbwpv6g-create/is117-brand-studio/pull/2).

## Evidence

Automated checks confirm only their stated assertions. They do not establish audience demand, factual claims beyond the code, comprehensive personal keyboard use, or full accessibility.

| Spec ID   | Files and live project                                                                                                                                                                                                                                       | Issue / PR                                                                     | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | [Storefront](public/index.html), [shared CSS](public/styles.css), [style guide](public/styleguide.html), [design studio](public/studio.html), [tests](tests/browser/studio.spec.js); [live website](https://grrvbwpv6g-create.github.io/is117-brand-studio/) | Merged [PR #2](https://github.com/grrvbwpv6g-create/is117-brand-studio/pull/2) | `CI=true npm run check` passed locally on macOS: formatting and lint passed, 7 server tests passed, and 10 Playwright tests passed. The browser suite includes automated keyboard interaction coverage and 375×812 no-overflow assertions for all three pages. In a separate personal Safari check on Mac, the learner reports using Tab to move between elements and seeing a visible focus outline, then opening the Choose a Style dropdown with Spacebar and selecting Casual using Down Arrow and Enter. This does not claim that every button or the demo bag was keyboard-tested. Earlier GitHub Actions diagnostics measured 392px document width at 375px and identified `.product-visual` and its product-section contents extending to the right. Responsive CSS now gives the mobile product grid a zero-minimum track, lets `.product-visual` and `.product-information` shrink (`min-width: 0`), and lowers the mobile heading's minimum size from 4.2rem to 3rem. The updated local suite passes; GitHub Actions has not yet been confirmed against this latest CSS. The learner's Safari observations of keyboard behavior and spacing are distinct from the automated overflow diagnostic. |

## Later

No follow-up feature is selected. If work resumes after BRAND-001, choose one small visitor-focused improvement and record it under a new spec ID.

## T-shirt Research — November 9, 2026

### 1. Three Clothing Website Comparisons

**Research date:** November 9, 2026

| Source | Observation / What to Check | What It Suggests for THE EDIT |
|---|---|---|
| [UNIQLO](https://www.uniqlo.com/us/en/) | UNIQLO presents everyday basics with practical product information, including fit, materials, and pricing. | THE EDIT should make its T-shirt easy to understand with clear product information and simple navigation. |
| [Everlane](https://www.everlane.com/) | Everlane emphasizes wardrobe essentials, versatile styling, and product materials. | THE EDIT can emphasize how a simple white T-shirt works with different outfits, without making unsupported quality claims. |
| [COS](https://www.cos.com/en-us/) | COS presents modern clothing with attention to garment shapes, fits, and design details. | THE EDIT can use a refined visual direction and clearly describe the T-shirt's fit. |

**Research limitation:** These observations describe the brands' general presentation. Specific visual details and product claims should be checked against the live pages. Brand-character interpretations are my own.

### 2. Two Brand Positions

**Position A — Premium Minimalist Essential**

THE EDIT focuses on a simple white T-shirt for young professionals who want versatile everyday clothing. The brand emphasizes confidence, simplicity, and a sophisticated appearance.

**Position B — Affordable Everyday Basic**

THE EDIT focuses on college students who want comfortable, practical clothing at accessible prices. The brand emphasizes convenience, casual styling, and affordability.

**My decision:** I chose Position A because it matches THE EDIT's existing brand promise, "Effortless Confidence," and its Modernist design direction.

**Assumption:** Premium describes the intended brand presentation, not verified fabric quality or a confirmed pricing advantage.

### 3. Two Audience Persona Hypotheses

**Persona A — Young Professional**

- Age: 25 (hypothetical)
- Needs versatile clothing for everyday activities and casual professional settings.
- Values simple styling and a polished appearance.
- May be concerned about fit, comfort, and versatility.

**Persona B — College Student**

- Age: 21 (hypothetical)
- Needs comfortable clothing for classes and everyday activities.
- May prioritize affordability and casual styling.
- May be concerned about price, comfort, and durability.

**Selected primary audience:** Young professionals.

I chose young professionals because THE EDIT's sophisticated visual identity, minimalist approach, and confident messaging align with this audience hypothesis. College students remain a possible secondary audience.

**Assumption:** These personas represent potential customers, not findings from customer interviews or surveys.

### 4. Look, Brand Character, and Honest Persuasion

**Visual direction:** Modernist design with neutral colors, clean typography, simple layouts, and balanced spacing.

**Brand archetype:** Ruler.

**Brand voice:** Confident, Sophisticated, Minimalist.

**Brand promise:** Effortless Confidence.

**Headline:** Confidence Begins With Simplicity.

**Supporting text:** A white T-shirt for effortless everyday styling.

**Call to action:** Explore the Tee.

The visual design supports the brand by creating a clean and organized shopping experience. The Ruler archetype communicates confidence through a controlled and polished presentation.

THE EDIT should persuade customers through clear product information, realistic styling examples, and straightforward messaging. It should avoid fake reviews, misleading discounts, false scarcity, and unsupported claims about product quality or sustainability.

### 5. Research Decision

I will keep young professionals as THE EDIT's primary audience and maintain the Modernist design direction established in my previous Brand Studio work.

UNIQLO suggests the importance of practical product information. Everlane suggests emphasizing versatile everyday styling. COS suggests presenting clothing with a refined design and clear fit descriptions.

I want THE EDIT to combine a sophisticated appearance with simple, understandable product information.

### 6. Peer Review and Feedback

**Review partner:** Classmate — name to be added.

**Incoming feedback issues:** Pending classmate review.

**My review of my classmate's project:** Pending availability of their repository.

**Feedback decision:** To be documented after receiving actual feedback.

**Changes and verification:** To be documented after reviewing the issues and deciding whether to implement, investigate, defer, or decline each suggestion.

### 7. Change Note and Open Question

**Current change:** Added comparative clothing-site research, two brand positions, two audience hypotheses, and the selected primary audience to the existing Brand Studio documentation.

**Open question:** Does THE EDIT's current homepage clearly communicate that it is intended primarily for young professionals?

**Next step:** Request peer feedback, document the decision in GitHub Issues, link any accepted changes to commits or pull requests, verify the results, and request reviewer confirmation before closing resolved issues.

**AI assistance:** ChatGPT assisted with organizing and drafting the research. I am responsible for checking website observations, evaluating peer feedback, verifying changes, and making the final project decisions.
