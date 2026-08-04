# AxonRing Deployment Checklist

**Purpose:** Step-by-step actions to take the fixed content live on axonring.com (or your current domain).  
**Estimated effort:** 1–3 days depending on platform (Shopify, custom, Webflow, etc.).

---

## Phase 0 — Preparation (Do First)

- [ ] **Backup current site**  
  Export theme / full site backup and note current product SKUs, prices, and inventory.

- [ ] **Decide platform approach**  
  - Option A: Replace homepage + product pages in existing CMS  
  - Option B: Point domain to new static/HTML pages temporarily  
  - Option C: Full redesign using the provided HTML as design reference

- [ ] **Confirm final pricing & SKUs**  
  Executive $249 · Prestige $349 (or adjust). Remove all Ultra / Elite / ECG / display models from catalog.

- [ ] **Prepare support email**  
  Ensure support@… (or current address) is monitored and staff know the new honest product description.

---

## Phase 1 — Content Removal (Critical)

- [ ] **Delete or unpublish** every product card / page that claims:  
  ECG · micro-display · blood pressure · continuous HR / SpO2 · GPS · “no battery + sensors” combination

- [ ] **Search & destroy old claims** site-wide:  
  Search for: “ECG”, “micro-display”, “blood pressure”, “tap to pay Visa”, “Apple Pay”, “50,000+”, “4.9★”, “98% satisfied”, “GPS”, “gesture control”, “AI health coach”

- [ ] **Remove inflated social proof**  
  Delete fake review counts, star ratings, and generic testimonials that cannot be verified.

---

## Phase 2 — Core Pages

- [ ] **Homepage**  
  Replace with content from `pages/home.html` (or paste copy from `copy/hero-and-features.md` + `copy/what-it-does-not.md`).

- [ ] **Product pages**  
  - Create / update **Executive** → use `pages/product-executive.html` language  
  - Create / update **Prestige** → use `pages/product-prestige.html` language  
  - Ensure both pages contain the “Does not” block

- [ ] **Specs page**  
  Publish `/specs` using `pages/specs.html` or `copy/technical-specs.md`

- [ ] **Compare page**  
  Publish `/compare` using `pages/compare.html` or `copy/comparison-table.md`

- [ ] **Sizing page**  
  Publish `/sizing` using `pages/sizing.html` + `policies/sizing-and-fulfillment.md`

- [ ] **Reviews page**  
  Publish `/reviews` using `pages/reviews.html` (placeholder until real reviews arrive)

---

## Phase 3 — Policies & Checkout

- [ ] **Returns & Warranty**  
  Update Returns / FAQ / Policy page with language from `policies/returns-warranty.md`

- [ ] **Checkout language**  
  Add the short honest disclaimers from `policies/checkout-terms.md` above the pay button and in order-confirmation emails

- [ ] **Sizing flow**  
  Configure order process so a free sizing kit is the first shipment and size confirmation is required before the final ring ships (see `policies/sizing-and-fulfillment.md`)

- [ ] **Legal product description**  
  Add the legal-safe product description from `policies/checkout-terms.md` to Terms of Service or product footnotes

---

## Phase 4 — Navigation & Internal Links

- [ ] Update main navigation: Home · Shop · Specs · Compare · Sizing · Reviews · Support
- [ ] Add footer links to Specs, Compare, Returns, Sizing
- [ ] Ensure every product page links to “What it does not do” and Specs
- [ ] Update any email templates, abandoned-cart sequences, and post-purchase emails with the new honest language

---

## Phase 5 — Technical & SEO

- [ ] Update meta titles and descriptions (remove health-tracking keywords that no longer apply)
- [ ] Redirect old product URLs (Ultra, Elite, etc.) to the new homepage or collection page
- [ ] Update sitemap and submit to Google Search Console
- [ ] Check mobile rendering of the new homepage and product pages
- [ ] Test free sizing kit flow end-to-end (order → kit ships → size confirm → ring ships)

---

## Phase 6 — Post-Launch Verification (Same Day)

- [ ] Browse the live homepage as a new visitor — confirm no contradictory claims remain
- [ ] Place a test order and verify sizing-kit messaging appears
- [ ] Check that “What it does not do” is visible without scrolling on homepage and product pages
- [ ] Confirm support team can answer: “Does it track heart rate?” and “Can it pay at terminals?” with the correct honest answers
- [ ] Monitor for 48 hours for any customer confusion and adjust FAQ if needed

---

## Phase 7 — Ongoing (First 30 Days After Launch)

- [ ] Collect real customer photos and short quotes (see `copy/social-proof.md`)
- [ ] Publish first verified reviews on the Reviews page
- [ ] Review return reasons — if any still mention “expected health tracking”, strengthen the “Does not” messaging
- [ ] Consider adding a short explainer video or GIF showing a real tap-to-share interaction

---

**Done when:** A new visitor can read the homepage and product pages and accurately understand that AxonRing is a passive NFC ring with no battery, no health sensors, and no terminal payments — before they click “Buy”.
