# NAKEBUSEN UI/UX SOP — Locs and Digital Customer Journeys

**Status:** RECOMMENDED OPERATING PROCEDURE · review 2026-10-26  
**Applies to:** NAKEBUSEN Locs • Digital — Powered by WARENA  
**Current public lockup:** NAKEBUSEN Locs • Digital / Powered by WARENA / @donfelohke · #HisGenjeness

This is an implementation and review SOP. It does not claim that the live website has passed browser testing or that customer usability research has been completed.

## 1. Non-negotiable customer facts

- Current loc-care campaign: **Eldoret Town / Karibu Mdosi**.
- Retouch & Styling — **from KES 700**.
- Sisterlocs Retie — **from KES 1,500**.
- Artificial Locs Installation — **from KES 3,500**.
- WhatsApp / phone: **0719 635 415** — [open WhatsApp](https://wa.me/254719635415).
- Email: **mela9ine@proton.me**.
- Prices are starting prices. Confirm suitability, scope, availability, final quote and appointment details directly.
- An enquiry is not a confirmed booking.
- Braiding is not in the current advertised service scope.
- Do not invent testimonials, certifications, service guarantees, customer counts or completed digital deployments.

These facts must agree across the website, social copy, WhatsApp replies and repository documentation. Where an operating detail is uncertain, ask the owner instead of inferring.

## 2. Two distinct journeys, one coherent brand

### Journey A — Locs

1. **Orient:** communicate loc-care offer and current location.
2. **Choose:** show service names and starting prices in plain language.
3. **Understand:** explain that price depends on the client's locs, requested work and materials; do not promise a duration unless confirmed.
4. **Enquire:** provide a clear WhatsApp action.
5. **Confirm with a human:** agree suitability, scope, quote, availability, time and location.
6. **Deliver and follow up:** provide agreed care/aftercare information; do not collect unnecessary personal details.

**Acceptance:** a first-time visitor can find the three services, their starting prices, location and contact path without decoding internal brand terminology.

### Journey B — Digital / WARENA

1. **Orient:** explain the practical problem category (GNU/Linux, computer setup, networking, deployment, systems configuration or support).
2. **Describe the problem:** invite a short, non-sensitive summary and relevant constraints.
3. **Discover:** ask only the minimum details needed to determine whether the request is in scope.
4. **Scope:** agree deliverables, prerequisites, exclusions, quote, timeline and access requirements before work.
5. **Deliver:** use versioned configuration where appropriate; record tests, limitations and rollback.
6. **Handover:** provide the customer with the configuration, documentation, ownership boundaries, recovery path and support terms that were agreed.

**Acceptance:** the site does not imply a service is available, deployed or guaranteed until it is confirmed. Do not request passwords, private keys, payment credentials or customer records through a public form or social message.

## 3. Information architecture

Recommended primary order:

1. **Hero:** NAKEBUSEN Locs • Digital; Powered by WARENA; concise customer benefit.
2. **Locs:** service list, starting prices, location and WhatsApp enquiry.
3. **Digital:** practical technology capabilities and scoped enquiry route.
4. **How it works:** enquiry → discussion → agreed scope/quote → confirmation.
5. **About / practice:** brief human authorship and the relationship among NAKEBUSEN, WARENA, IKAI and GENJE.
6. **Connect:** WhatsApp, email and approved public profiles.

Keep GENJE, IKAI and extended research context secondary to customer tasks. Do not remove the cultural identity; place it where interested visitors can explore it without blocking service discovery.

## 4. Copy and interface rules

- Use **“from KES …”** and explain that final quotes depend on the work.
- Prefer “Enquire on WhatsApp” over “Book now” unless the booking is actually confirmed by the system.
- Separate Locs and Digital actions; each CTA must have a meaningful destination.
- Use plain English by default. Offer a clearly labelled English/Kiswahili toggle; translation must preserve the meaning of prices, scope and booking conditions.
- Do not rely on colour alone to convey state.
- Theme control stays near the top-right, has a visible text label and a clear accessible action name.
- Use semantic HTML, visible keyboard focus, sensible heading order, descriptive links, sufficient contrast and reduced-motion support.
- Preserve the current public website policy: **text-only; no embedded graphics, video, canvas, graphic favicon, CSS image backgrounds, external fonts or required CDN** unless a separately reviewed decision changes it.
- Do not add analytics, trackers, popups or a floating booking widget without a documented need, privacy review and mobile test.

## 5. Shared visual system

Use the smallest effective system; do not build a component library for its own sake.

| Token / pattern | Current direction | Rule |
|---|---|---|
| Paper | `#F2EFEA` | Light surface |
| Ink | `#111111` | Primary text |
| Gold | `#D4AF37` | Accent; check contrast before small text |
| Clay | `#E2725B` | Secondary accent/focus; verify contrast |
| Deep green | `#033500` | Limited supporting accent |
| IKAI aqua | `#79D7D2` | Reserve for reflective-compute context |
| Typography | System sans + serif headings + monospace for technical details | No remote font dependency |
| Layout | Mobile-first, fluid spacing, readable line lengths | No clipped or overlapping controls |
| Motion | Brief and purposeful | Respect `prefers-reduced-motion` |

The palette is a design direction, not proof that every foreground/background pair passes WCAG contrast. Test actual combinations.

## 6. Research and benchmark use

Useful starting points:
- [Marini Naturals](https://www.marininaturals.com/) and [collections](https://www.marininaturals.com/collections) — regional hair-care taxonomy and plain-language product discovery.
- [Patagonia ecommerce case study — BASIC](https://www.basicagency.com/case-studies/patagonia-ecommerce-website) — hierarchy and navigation lessons.
- [Patagonia navigation redesign — Chelsea Lensing](https://www.chelsealensing.design/case-studies/navigation-redesign) — discovery patterns.
- [Safaricom Baze UX case study — Big Bold Red](https://www.bigboldred.agency/case-studies/safaricom-baze-scalable-ux-for-digital-lifestyle-ecosystem/) — distinct audiences and content discovery.
- [NN/g State of UX 2026](https://www.nngroup.com/articles/state-of-ux-2026/) — design practice and research context.
- [2026 Design Systems Report — zeroheight](https://report.zeroheight.com/2026) — design-system practice.

These are benchmarks, not templates to copy. Agency/designer case studies can be self-reported; use them for hypotheses, not guaranteed results.

### Eldoret competitor research status

Alif Locs, Flo Sisterlocks and ADECARGO Dreadlocks are initial local research leads. A business listing alone does not establish that a competitor's website or booking journey is good, bad, accessible or effective. Before drawing a comparison, capture the actual public site/social profile, access date, customer journey, prices, contact handoff, mobile behaviour and accessibility observations. Do not copy competitor wording or creative assets.

## 7. Design / content change SOP

### Before changing

- [ ] Inspect current main, open PRs and any branch already changing the same files.
- [ ] State the user problem and intended outcome.
- [ ] Identify which approved facts or copy are affected.
- [ ] Check whether the change needs owner confirmation, translation review or privacy review.
- [ ] Record baseline evidence and unknowns.

### Implement

- [ ] Create a focused feature branch.
- [ ] Prefer the smallest change that solves the observed problem.
- [ ] Keep customer-facing copy and prices consistent across language variants.
- [ ] Add/update regression checks for the actual failure.
- [ ] Avoid merging overlapping PRs blindly.

### Verify

- [ ] Test 320, 360, 390, 430 CSS px and desktop.
- [ ] Check both themes and the English/Kiswahili toggle.
- [ ] Check keyboard-only navigation, visible focus and zoom.
- [ ] Verify WhatsApp destination, phone number, email and all internal links.
- [ ] Check no horizontal page overflow, hidden CTA, sticky-header overlap or unreadable price row.
- [ ] Check browser console and external requests.
- [ ] Run repository tests and report the actual workflow URL/result.
- [ ] Verify the live page after deployment; do not equate a passing workflow with browser QA.

### Release record

Every substantive change should state: problem, decision, changed files, source/evidence, automated checks, manual/browser checks, remaining limitations, PR and commit, and deployment status.

## 8. Minimum usability tasks

Ask a person unfamiliar with the site to do these tasks without coaching:

1. Find the price for retouch and styling.
2. Find the Sisterlocs retie price.
3. Find where the current loc-care campaign operates.
4. Open the correct WhatsApp enquiry path.
5. Explain whether clicking the link confirms a booking.
6. Find the Digital service route and describe what information to send.
7. Change language and theme without losing their place.

Record task completion, errors, hesitation and participant feedback. Do not invent a completion rate from a small or hypothetical sample; state sample size and limitations.

## 9. Acceptance gates

A change is ready for review when:
- the user problem and proposed change are clear;
- public facts remain accurate;
- mobile layout and both themes have been checked at source level;
- relevant automated checks pass;
- language, keyboard and link behaviour are covered;
- evidence and limitations are stated.

A change is ready to claim as browser-verified only after real-browser evidence exists. A change is ready to claim as deployed only after the relevant Pages deployment and published URL are checked.

## 10. Relationship to the canonical corpus

The shared benchmark register and evidence standard live in the [FELOH Sovereign Corpus UI/UX SOP and case studies](https://github.com/donfelohke/feloh-corpus/blob/main/docs/research-briefs/ui-ux-sops-design-trends-case-studies.md). This document owns NAKEBUSEN-specific service journeys and operating details. The public website repository owns the implementation and test evidence.
