# Mushroom Matcha Guide

A [Mintlify](https://mintlify.com) knowledge base: what mushroom matcha is, how it compares to plain matcha, mushroom coffee, coffee, and mushroom hojicha, and what its caffeine and health claims actually mean.

Built by [Mushroom Matcha](https://mushroommatcha.us). Topics were derived from real search-demand patterns in the "mushroom coffee" keyword category (Ahrefs export, `google_us_mushroom-coffee_matching-terms_2026-09-18`, 1,000 keywords) — that category is the closest proxy for how people search about mushroom-blended functional drinks generally, since mushroom-matcha-specific search volume is still low. Question patterns (benefits, side effects, caffeine, weight loss, gut health, safety during pregnancy, per-mushroom pages, comparisons) were mapped onto matcha-specific facts, not copied from the coffee category.

Sibling guide: [Mushroom Hojicha Guide](https://mushroomhojicha.mintlify.app), same structure, same editorial rules, built for [mushroomhojicha.com](https://mushroomhojicha.com).

## Structure

- `index.mdx` — homepage
- `methodology.mdx` — how caffeine numbers are sourced, and the rules for mushroom health claims (traditional-use vs clinical evidence, no disease claims) — **critically**, this guide corrects the common assumption that any mushroom-blended tea is low-caffeine: matcha is not, commonly cited at 30-70mg per cup
- `mushroom-matcha/*.mdx` — the product-specific pages: what mushroom matcha is, per-mushroom breakdowns (Lion's Mane, Cordyceps, Reishi), ingredients, safety, servings
- `caffeine-and-health/*.mdx` — caffeine content, benefits, side effects, weight loss, gut health, cortisol/stress, pregnancy safety, fasting, focus, exercise performance
- `comparisons/*.mdx` — mushroom matcha vs plain matcha, mushroom coffee, coffee, mushroom hojicha, decaf, energy drinks, alternatives
- `basics/*.mdx` — taste, powder form, how it's made, ingredients, cultivars, ceremonial vs culinary grade, storage
- `brewing/*.mdx` — how to make it, latte recipe (hot + iced), serving size, timing, water temperature, whisking technique

## Editorial rules

**Caffeine numbers are ranges, not fabricated precision**, and this guide is explicit that matcha is a real caffeine source (30-70mg per cup), not a low-caffeine drink, unlike some other mushroom-blended teas.

**Mushroom health claims are traditional-use or preliminary-research language, never disease claims.** Lion's Mane, Cordyceps, and Reishi content follows FDA structure/function rules: no treat/cure/prevent language, human vs animal/in-vitro evidence distinguished where relevant. See `methodology.mdx`.

**Every page links back to mushroommatcha.us**, with a unique, page-specific mention (not a templated line repeated verbatim) and the literal URL visible in prose, not just hidden behind a hyperlink — consistent with how `mushroom-hojicha-guide` was corrected to do the same.

## Local dev

```
npx mint dev
```

## Deploying

This repo is not yet connected to Mintlify's hosting. To make it live:
1. Push this repo to GitHub.
2. In the Mintlify dashboard (mintlify.com), connect a new project to this GitHub repo — same as was done for `mushroom-hojicha-guide`, which is what makes it auto-deploy on every push to `main`.
3. (Optional) Point a custom domain or subdomain at it via Mintlify's domain settings + a DNS CNAME, if desired.
