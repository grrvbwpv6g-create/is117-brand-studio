# THE EDIT

**Effortless confidence through simple, versatile everyday style.**

THE EDIT is a minimalist white T-shirt brand concept for young professionals. Its modernist direction pairs a neutral palette, clean sans-serif typography, and an original wordmark to present the everyday tee as a polished, adaptable wardrobe choice.

> This is a classroom storefront prototype. Product details are fictional; the demo bag does not place orders, collect payment, or persist between page loads.

## Live website

[Visit THE EDIT](https://grrvbwpv6g-create.github.io/is117-brand-studio/)

- [Storefront](https://grrvbwpv6g-create.github.io/is117-brand-studio/)
- [Live style guide](https://grrvbwpv6g-create.github.io/is117-brand-studio/styleguide.html)
- [Design studio](https://grrvbwpv6g-create.github.io/is117-brand-studio/studio.html)

## Brand identity

- **Audience:** Young professionals looking for a simple shirt they can style for everyday and smart-casual occasions.
- **Promise:** THE EDIT helps young professionals feel polished and confident through simple, versatile everyday style.
- **Character:** Refined, confident, and sophisticated.
- **Visual direction:** Modernist—neutral colors, clear hierarchy, structured layouts, and readable typography.
- **Voice:** Confident, sophisticated, and minimalist.

The audience is a design hypothesis, not a result of customer research. Read the project’s decisions and evidence in [SPEC.md](SPEC.md), and see the short AI-drafted learning record in [LEARNING.md](LEARNING.md).

## Website features

- Responsive white T-shirt storefront with the THE EDIT wordmark and brand messaging.
- Size selection for S, M, L, and XL, with helpful feedback if a visitor tries to add an item without choosing a size.
- Working demo bag that shows selected sizes, quantities, and an item count; it can also be emptied. The bag resets on reload.
- Optional Casual and Smart Casual preferences that reveal corresponding styling suggestions.
- Live style guide covering the shared logo, palette, typography, spacing, components, and voice.
- Design studio introducing how modernist and postmodernist choices can give the same product different meanings.

## Responsive design and testing

The storefront and supporting pages adapt to narrow screens. The mobile layout stacks the product content and constrains its grid items and headline sizing to prevent horizontal overflow. A Playwright browser test checks that pages fit a 375-pixel viewport; additional browser checks cover core storefront interactions, keyboard use, page integrity, and automated accessibility rules.

Run the complete project check with:

```sh
npm run check
```

It includes formatting, lint, server tests, and Chromium-based Playwright tests. The latest local check completed successfully.

## BRAND-001

The completed BRAND-001 work was merged in [pull request #2](https://github.com/grrvbwpv6g-create/is117-brand-studio/pull/2).

## Run locally

Requirements: Node.js **22.16 or later on the 22 LTS line**, or **24 or later**, and npm.

```sh
git clone git@github.com:grrvbwpv6g-create/is117-brand-studio.git
cd is117-brand-studio
npm ci
npm run dev
```

Open the local address printed by the server (normally `http://127.0.0.1:5173`). Keep the development server running while browsing; saved files under `public/` refresh automatically. Press **Ctrl+C** in that terminal to stop it.

To run checks locally:

```sh
npm run check
```

## AI assistance

AI assistance supported brand exploration, copy and design suggestions, implementation, troubleshooting, and testing. The student selected THE EDIT and its modernist direction and reviewed the resulting project. See [LEARNING.md](LEARNING.md) for the concise record of contributions and assistance.
