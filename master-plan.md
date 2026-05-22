# Overclock — Master Plan
**Version 8 | May 2026**

---

## SITUATION

Overclock is a functional mint brand targeting gamers, coders, and Web3 builders in Canada.

**Product:** Pressed focus mints — 30-tablet flip-top tin, chocolate-espresso, sugar-free
**Price:** $6–8 wholesale / $10–14 retail
**Margin:** ~70% at events, 50–57% wholesale
**Budget to launch:** $2,000–2,200 (200 tins + cNFT system + Shopify + insurance)

**On-chain:** Genesis cNFT (001–1,000) via Underdog Protocol on Solana. Non-transferable, non-tradable. Wallet-gated perks: 10% lifetime discount, early access, token-gated drops, Genesis channel access.

**Format reference:** Altoids / Neuro Mints
**Terminology:** "Hand-pressed" or "pressed" — never "cold-pressed" (Neuro Gum patent)

---

## THE FORMULA (per 1g tablet)

| Ingredient | % | Notes |
|------------|---|-------|
| Xylitol | 60% | Sugar-free sweetener base |
| Mannitol | 10% | Sugar alcohol, clean taste |
| Dutch-processed cocoa | 8% | Chocolate base + theobromine |
| Coffee extract | 3% | Natural caffeine source |
| Ceremonial matcha | 3% | L-theanine + gentle caffeine |
| Lion's mane dual-extract | 2% | Fruiting body mushroom |
| Vanilla | 2% | Flavor carrier |
| Natural chocolate flavor | 1.5% | Flavor blend |
| Sea salt | 0.5% | Flavor amplification |
| Stevia reb M | 0.3% | Zero-calorie sweetener |
| Calcium stearate | 1% | Tablet binding agent |

**Per tin (~30 tablets):** ~75mg natural caffeine, ~50mg L-theanine, ~600mg lion's mane
**Dietary:** Sugar-free / vegan / gluten-free

---

## PHASE 1 — DIY PROTOTYPE (Weeks 1–4)

**Goal: Have a physical product to test.**

### 1.1 — Source Ingredients
- [ ] Source from Costco, Bulk Barn, and online:
  - Costco: Dutch-processed cocoa powder, vanilla extract, sea salt
  - Bulk Barn: xylitol (compressible/granular), mannitol if available
  - Online: ceremonial matcha (Jade Leaf, Encha, Aki Matcha), lion's mane dual-extract (Real Mushrooms or Nootropics Depot, ~$25–40/100g), calcium stearate food-grade (NOW Foods), stevia reb M, natural chocolate flavor powder, decaf coffee extract powder
- Est. cost: ~$100–150 for initial run (200+ tins worth)

### 1.2 — Buy Tablet Press
- [ ] Buy TDP-0 tablet press + 10mm round dies on Amazon CA (7–10 day delivery) or AliExpress (2–3 weeks, cheaper)
  - Amazon CA: ~$300
  - AliExpress: ~$180–220
  - This is the hand-press — standard mechanical compression, not cold-pressed

### 1.3 — First Test Batch (DIY Hand-Press)
- [ ] Make first 50 tablets:
  1. Mix dry ingredients in correct proportions by weight, sieve through fine mesh
  2. Press into 10mm round tablets using TDP-0 hand press
  3. Test-press 5 tablets first — check hardness and ejection
  4. Adjust compression pressure as needed
  5. Press 50, store in airtight container
- [ ] Self-test 2–3 days: note dominant flavor, off-notes, aftertaste, mouthfeel, dissolve time, sweetness
- [ ] Distribute to 8–10 honest testers (Solana devs, coders, gamer friends). Ask for written feedback: flavor (1–10), texture (1–10), would-pay-$12-for-30 (Y/N), one thing to change.
- **Deliverable:** 50 prototype tablets + tasting note doc + 8–10 written tester reviews
- Note: "Hand-pressed" is the accurate description. Not cold-pressed (Neuro Gum's patent).

### 1.4 — Packaging Prototype
- [ ] Design a simple tin label (Canva or Figma)
  - Overclock branding, bilingual EN/FR, Nutrition Facts table
  - Dark espresso / matte brown aesthetic (reference: Ledger, Arc, Linear)
- [ ] Order 5–10 unbranded prototype tins from Amazon CA (~$1–2 each) for taste testing
- [ ] Print labels (local Toronto print shop or Cat Printed online)
- Est. cost: ~$50–100 for first run of labels

### 1.5 — Food Handler Cert
- [ ] Get food handler certification online via TrainCan or CIFS
  - Est. cost: ~$50
  - ~4 hours, valid 5 years
  - Required for selling food at events / retail in Ontario

### 1.6 — Quote Insurance
- [ ] Get liability insurance quote from PolicyMe, Zensurance, or a local broker
  - ~$1M general commercial liability for home-based food maker
  - ~$400–600/year
  - Get quote in writing, don't bind yet

---

## PHASE 2 — SOFT LAUNCH (Weeks 3–4)

**Goal: 100 tins, community feedback, first revenue, live cNFT mint flow.**

### 2.1 — Iterate Formula
- [ ] Incorporate tester feedback: adjust matcha %, lion's mane %, cocoa intensity, sweetness
- [ ] Press second batch of 50, re-test with 3–5 original testers
- [ ] Lock v2 formula

### 2.2 — Order Branded Tins
- [ ] Order 250+ flip-top metal tins
  - Sources: Uline Canada, Pacific Bag, Berlin Packaging, Alibaba
  - ~$0.80–$1.20 each
  - Lead time 1–3 weeks — order Week 3 to have for Week 4
  - Get tin design + Genesis numbering done first — etched or printed serial numbers #001–#1000

### 2.3 — Finalize Label Artwork
- [ ] Confirm label includes:
  - Bilingual Nutrition Facts table
  - Bilingual ingredient list with allergens
  - Net quantity, dealer name (Overclock Foods, Vaughan ON address), lot/date code
  - QR code pointing to overclock.co — leads to wallet connection + benefits page
- [ ] Order 250–500 custom labels via Sticker Mule, VistaPrint, or local printer
  - ~$0.20–$0.40 each
  - Est. cost: ~$75

### 2.4 — On-Chain: Move to Mainnet
- [ ] Move cNFT mint flow from devnet to Solana mainnet
  - Same code, switch RPC endpoint
  - Fund mint wallet with ~0.5 SOL (covers 10,000+ cNFT mints)
  - Test one real mint to a friend's wallet, verify on Solscan
- [ ] Build Solana Pay checkout flow:
  - Event QR: generate payment QR, displayed at booth. On payment confirmation, capture buyer's wallet address, trigger cNFT mint
  - Online: standalone Solana Pay flow (Shopify integration in Week 5)
  - Have manual fallback: collect wallet addresses on paper, mint cNFTs in batch post-event

### 2.5 — Produce 100 Tins
- [ ] Press 100 production tablets (~3,000 tablets at 30/tin, ~30–40 hours across 5–7 evenings)
- [ ] Fill, seal, label each tin
- [ ] Package: 30-tablet flip-top tin, EN/FR labels

### 2.6 — Soft Validation Event
- [ ] Small Toronto event: crypto meetup, coffee shop pop-up, hackathon prep night, friend's launch party
- [ ] Bring 50–75 tins
- [ ] Goals: real customers, real payments (cash + Solana Pay), first Genesis cNFTs minted (#001–#075), direct feedback, photos for social
- [ ] Bind insurance before this event

---

## PHASE 3 — LAUNCH (Weeks 5–6)

**Goal: 200+ tins at Superteam Canada / Toronto Solana event. Genesis cNFTs #075–#250+.**

### 3.1 — Build Shopify Storefront
- [ ] Set up Shopify Lite ($5/mo) or basic Shopify ($39/mo)
- [ ] Integrate: Solana Pay checkout (Helio or Crossmint), wallet connection + Genesis discount logic, cNFT minting on order completion, token-gated landing page

### 3.2 — Press Final 100–150 Tins
- [ ] Debrief soft launch — what worked, what didn't
- [ ] Press additional 100–150 tins (total 200–250 for main event)

### 3.3 — Launch Genesis cNFT Collection
- [ ] Design and finalize Genesis cNFT visual (1080x1080 PNG, on-chain metadata via Underdog)
- [ ] Deploy Genesis cNFT collection on mainnet: supply cap 1,000, non-transferable, non-tradable, 0% royalties
- [ ] Verify on Solscan, log collection address

### 3.4 — Launch Telegram Channels
- [ ] Public: @OverclockMints — announcements, drops, general community
- [ ] Genesis-gated: @OverclockGenesis — locked behind cNFT verification via Collab.Land or Guild.xyz. Seed with 10–20 friends so it's not empty at launch.

### 3.5 — Pre-Event Marketing
- [ ] Twitter/X thread announcing Overclock, Solana integration, Genesis 1000
- [ ] Telegram channel post with countdown
- [ ] Direct outreach to 10–20 Solana people in Canada + UAE — first 100 Genesis holders
- [ ] Confirm event date and booth details with Superteam Canada

### 3.6 — LAUNCH DAY
**At the event:**
- [ ] 200+ tins packed and ready
- [ ] Solana Pay QR code printed/displayed (laptop + backup phone)
- [ ] Card reader for fiat (Square, ~$60 device + 2.65% fee — encourage Solana Pay)
- [ ] Cash float (~$200 in 5s and 10s)
- [ ] Genesis cNFT mint flow tested, backup on phone
- [ ] Business cards / QR codes to website and Telegram
- [ ] Photos and video — document everything
- [ ] Sell tins, mint Genesis cNFTs in real-time
- [ ] Collect emails for fiat payers or wallet-less buyers

**Day-of post-event:**
- [ ] Tweet/post launch with photos
- [ ] Welcome new Genesis holders to Telegram channel personally
- [ ] Thank Superteam Canada publicly

---

## PHASE 4 — SUSTAIN AND CONVERT (Weeks 7–8+)

**Goal: Repeat purchases, wholesale, next event, co-brand partnerships.**

### 4.1 — Re-engage Genesis Holders
- [ ] Day 1 follow-up: "Thanks for being a Genesis holder. Here's how to use your perks. Telegram is here."
- [ ] Day 5 follow-up: "Restock available + here's what's next." Drive online reorders.

### 4.2 — First Wholesale Conversations
- [ ] Reach out to 3–5 Toronto crypto-adjacent spots: Bitcoin Embassy, Cluster Cafe, Cohash co-working, hackerspaces, dev-focused cafes
- [ ] Pitch: stock Overclock at $6–8 wholesale

### 4.3 — Plan Next Event
- [ ] Next Toronto Solana meetup, Breakpoint side event, or UAE Solana event
- [ ] Genesis tins #200+ sold there

### 4.4 — Co-Brand Outreach
- [ ] Reach out to 5 Solana projects: Superteam Canada, Tensor, Backpack, MagicEden, Phantom, Cypher Capital UAE, Solana Mobile
- [ ] Pitch: "Co-branded tin for your community/event. Limited run of 100–300 tins. We handle production, you handle distribution."

### 4.5 — Replenish Inventory
- [ ] Press 100–200 more tins for next event + wholesale + online reorders

### 4.6 — Dashboard
- [ ] Set up Shopify analytics + on-chain dashboard
- [ ] Track: tins sold, Genesis cNFTs minted (current of 1,000), reorder rate, wallet retention, Telegram growth
- [ ] Weekly review

---

## UNIT ECONOMICS

| Metric | Value |
|--------|-------|
| All-in cost (200 tins) | $4.20–4.40/tin |
| Marginal cost (incremental) | $2.25/tin |
| Retail price | $10–14 |
| Wholesale price | $6–8 |
| Event margin | ~70% |
| Wholesale margin | 50–57% |
| Breakeven | ~65–70 tins at $10 retail |

---

## BUDGET

| Item | Cost |
|------|------|
| Ingredients + Packaging | $240 |
| Tablet Press + Dies | $400–600 |
| Business Registration | $60 |
| Kitchen Scale + Supplies | $50 |
| Labels + Artwork | $75 |
| Food Handler Cert | $50 |
| Insurance | $400–600 |
| cNFT Minting + Ops | $80 |
| Contingency | $200 |
| **Total** | **$2,000–2,200** |

---

## PARTNERSHIP — BUNDLE PLAY

**The pitch:** Your energy drink brand + Overclock mints = complete focus stack.

- Different categories. Same person. Same moment. No conflict.
- Bundle at events. Co-brand tin labels. 50/50 revenue split on bundle.
- Cross-promote on socials. Share booth cost.
- Canada-first: Viter, Run Gum, Neuro Mints aren't here. No US competition to lose to.

**"Your drink + my mint = complete focus stack."**

---

## REGULATORY SUMMARY

| Item | Status |
|------|--------|
| NPN | Not required — conventional food, not natural health product |
| Supplemented Foods compliance | Not required — ingredient levels below threshold |
| NIN | Not required — conventional food |
| EN/FR Nutrition Facts label | Required — standard CFIA bilingual label |
| Ontario home production | Legal under O. Reg. 493/17 (confirm with York Region Public Health before spending) |

**Messaging rule:** Describe ingredients. Never claim effects.
- Never: "focus," "cognition," "flow state," "nootropic," "brain boost"
- Always: "Contains natural caffeine from coffee and matcha," "Pressed mint tablets with lion's mane"

---

## TOOLS & RESOURCES

**Incorporation:** ServiceOntario (sole proprietorship, ~$60)
**Domain:** Namecheap, Hover, Cloudflare
**CIPO trademark search:** ised-isde.canada.ca/cipo (Nice Class 30)
**Ingredients:** Costco, Bulk Barn, Amazon CA, specialtyIngredient shops online
**Tablet press:** Amazon CA (fast) / AliExpress (cheap)
**Label design:** Canva (free) or Figma (free)
**Label printing:** Sticker Mule, VistaPrint, local Toronto printer
**Business banking:** RBC, BMO, Alterna Bank, EQ Bank
**Insurance:** PolicyMe, Zensurance, local broker
**Food handler cert:** TrainCan, CIFS (~$50, online, ~4 hours)
**Events:** Superteam Canada, Solana events, Meetup.com (Toronto tech/gaming)
**cNFT minting:** Underdog Protocol (underdogprotocol.com)
**Checkout:** Solana Pay (QR at events), Shopify + Helio/Crossmint (online)
**Telegram:** @OverclockMints (public), @OverclockGenesis (cNFT-gated via Collab.Land/Guild.xyz)

---

## WHAT'S DONE / NOT DONE

**Done:**
- [x] Name locked — Overclock
- [x] Format locked — pressed mint tablets, 30-ct flip-top tin, chocolate-espresso
- [x] Stack finalized — exact formula with percentages
- [x] Pricing set — $10–14 retail / $6–8 wholesale
- [x] Regulatory path confirmed — conventional food, no NPN
- [x] Competitors verified — Neuro Mints, Awak'n, Run Gum, Viter (all US-only)
- [x] Market data validated — $407M segment, 6% CAGR, Canada whitespace
- [x] Brand voice defined — Ledger/Arc/Linear/Raycast aesthetic, dark brown/black/matte
- [x] Genesis cNFT structure — non-transferable, non-tradable, 001–1,000, 4 perks
- [x] 8-week sprint plan documented in action-plan.md

**Week 0 (this week):**
- [ ] Confirm event date with Superteam Canada
- [ ] Call York Region Public Health (1-800-361-5653) — confirm O. Reg. 493/17 eligibility
- [ ] Trademark + domain + handle check
- [ ] Register business (ServiceOntario, ~$60)
- [ ] Set up wallets, Underdog account, Shopify Lite

**In progress:**
- [ ] Source ingredients
- [ ] Buy TDP-0 tablet press
- [ ] First prototype batch
- [ ] Food handler cert

---

*Prepared by: Cleo | May 2026*