# Overclock — Project Brief
**Version 8 | May 2026**

---

## EXECUTIVE SUMMARY

Overclock is a functional mint brand targeting gamers, coders, and Web3 builders in Canada.

**Product:** Pressed focus mints — 30-tablet flip-top tin, chocolate-espresso, sugar-free
**Format reference:** Altoids / Neuro Mints
**Price:** $10–14 retail / $6–8 wholesale

**On-chain layer:** Genesis cNFT (001–1,000) minted on Solana via Underdog Protocol. Non-transferable, non-tradable. Rewards early believers with wallet-gated perks.

---

## PRODUCT SPEC

**Name:** Overclock
**Tagline:** Find your focus. Stay there.
**Format:** Pressed focus mints (hand-pressed mint tablets), 30-count flip-top tin, chocolate-espresso
**Price:** $6–8 wholesale / $10–14 retail

**Stack (per 1g tablet):**
- Xylitol 60% — sugar-free sweetener base
- Mannitol 10% — sugar alcohol
- Dutch-processed cocoa 8% — chocolate base + theobromine
- Coffee extract 3% — natural caffeine source
- Ceremonial matcha 3% — L-theanine + gentle caffeine
- Lion's mane dual-extract 2% — fruiting body
- Vanilla 2% — flavor carrier
- Natural chocolate flavor 1.5% — flavor blend
- Sea salt 0.5% — flavor amplification
- Stevia reb M 0.3% — zero-calorie sweetener
- Calcium stearate 1% — tablet binding

**Per tin (~30 tablets):**
- ~75mg natural caffeine (from coffee + matcha)
- ~50mg L-theanine
- ~600mg lion's mane
- Sugar-free / vegan / gluten-free

**Messaging rule:** Describe ingredients. Never claim effects. No "focus," "cognition," "flow state," "nootropic," "brain boost."

---

## THE GENESIS CNFT

**What:** First 1,000 buyers receive a Genesis cNFT (001–1,000), minted on Solana via Underdog Protocol.
**Transferability:** Non-transferable, non-tradable. Stays in holder's wallet forever.

**Perks:**
1. 10% Lifetime Discount — auto-applied at checkout via wallet connection
2. Early Access — first dibs on new SKUs before public
3. Token-Gated Drops — limited editions only claimable by Genesis holders
4. Genesis Channel Access — private Telegram, direct line to product decisions

**Infrastructure:**
- Underdog Protocol — cNFT minting API
- Off-chain Postgres DB — tracks genesis_holders (wallet, mint number, mint date, email, event) and purchases (wallet, order ID, amount, discount applied)
- Solana Pay — QR checkout at events (SOL or USDC)
- Shopify Lite — online sales with wallet-gated discount logic
- Telegram — public @OverclockMints + Genesis-gated @OverclockGenesis

---

## UNIT ECONOMICS

| Metric | Value |
|--------|-------|
| All-in cost (200 tins) | $4.20–4.40/tin |
| Marginal cost | $2.25/tin |
| Retail price | $10–14 |
| Wholesale price | $6–8 |
| Event margin | ~70% |
| Wholesale margin | 50–57% |
| Breakeven | ~65–70 tins at $10 retail |

**Startup cost:** $2,000–2,200 to launch (200 tins + cNFT system + Shopify + insurance)

---

## MARKET

**Segment:** Brain mint / functional mint
**Market size:** $407M (2026) → $722M (2036) — +77% in 10 years
**CAGR:** ~6% (steady, focus-economy driven)

**Whitespace:** No chocolate-espresso pressed mint in Canada. No Canadian Web3-builder functional food brand. First mover.

**Competitors:** Neuro Mints (US), Awak'n (US), Run Gum (US), Viter (US) — all US-only. No direct Canadian competitor. Adjacent: Magic Mind, Alice Mushrooms, MOSH, GamerSupps.

---

## REGULATORY

**Track:** Conventional food — same as Tic Tac
- No NPN (natural health product authorization)
- No Supplemented Foods compliance
- No NIN (notification)
- Standard bilingual EN/FR Nutrition Facts label (CFIA)

**Ontario production:** O. Reg. 493/17 — home production legal without commercial kitchen for conventional foods.
**Pre-launch requirement:** Confirm with York Region Public Health (1-800-361-5653) before spending on production.

**Key rule:** Describe ingredients. Never claim effects. Not a supplement. Not a drug. Just food.

---

## PRODUCTION

### Phase 1: DIY (Weeks 1–4)
- TDP-0 hand press + 10mm round dies
- Food handler cert (TrainCan or CIFS online, ~$50)
- Ontario O. Reg. 493/17 — no commercial kitchen required

### Phase 2: Co-manufacturer (Year 2+)
- Triggers: 500+ tins/week demand, retail LOI, seed round
- Rootree (Burlington, ON) — pressed tablets
- Hownature (Markham, ON) — capsules + tablets
- Herbaland (Richmond, BC) — MOQ 5,000–10,000

---

## BRAND VOICE

**Reference:** Ledger, Arc, Linear, Raycast. Dark UI. High signal. No noise.

**Color:** Dark espresso browns, near-black backgrounds, matte surfaces, amber accents. Never green mint.

**Copy:** Short. Direct. Like a terminal. No fluff.

**Tagline options:**
1. **Find your focus. Stay there.** — Primary. Flow-state framing.
2. **Focus, pressed.** — Double meaning: pressed under deadline + pressed mints.
3. **Hand-pressed for builders.** — Small-batch craft framing.
4. **One mint. Then build.** — Coder-native, minimal.

---

## BUDGET (200 tins)

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

## 8-WEEK SPRINT

| Week | Milestone |
|------|-----------|
| W0 | Foundations: confirm event date, call Public Health, trademark/domain check, register business, set up wallets + Underdog |
| W1 | Prototype + cNFT scaffold: order press + ingredients, build cNFT mint flow on devnet, design Genesis metadata schema, set up Postgres DB |
| W2 | Press 50 tablets + validate: formula self-test, 10-person tester panel, food handler cert, move cNFT to mainnet, build Solana Pay checkout |
| W3 | Formula locked + Genesis deployed: iterate formula, order branded tins, finalize EN/FR label artwork, deploy Genesis cNFT collection, launch Telegram channels |
| W4 | 100 tins + soft validation event: press 100 production tins, small Toronto meetup pop-up with live Solana Pay + cNFT minting, bind insurance |
| W5 | Iterate + scale: debrief soft launch, press additional 100–150 tins, build Shopify storefront with Solana Pay + Genesis discount logic, pre-event marketing |
| W6 | **LAUNCH** — Superteam Canada / Toronto Solana event: sell 200+ tins, mint Genesis cNFTs in real-time, 100–200 Genesis holders |
| W7–8 | Re-engage + next event: follow up with all Genesis holders, first wholesale conversations, plan next event, press replenishment batch |

---

## PARTNERSHIP ANGLE

**The bundle:** Overclock mints + energy drink = complete focus stack.
- Different categories. Same person. Same moment. No conflict.
- "Your drink + my mint = complete focus stack."
- 50/50 revenue on bundle at events. Cross-promote on socials. Share booth cost.
- Canada-first: no US competitor to lose to.

---

## OPERATIONAL STACK (TO SET UP IN WEEK 0)

- Business bank account (Big 5, walk-in with MBL)
- Phantom or Backpack wallet (software for v1, Ledger later)
- Coinbase or Kraken for SOL/USDC → CAD off-ramping
- Underdog Protocol account (cNFT minting)
- Shopify Lite trial ($5/mo)
- Public Telegram: @OverclockMints
- Genesis-gated Telegram: @OverclockGenesis (via Collab.Land or Guild.xyz)

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
- [x] Genesis cNFT structure defined — non-transferable, non-tradable, 001–1,000, 4 perks
- [x] cNFT perks confirmed: 10% lifetime discount, early access, token-gated drops, Genesis channel
- [x] 8-week sprint plan documented in action-plan.md

**This week (Week 0):**
- [ ] Confirm launch event date with Superteam Canada
- [ ] Call York Region Public Health (1-800-361-5653) — confirm O. Reg. 493/17 eligibility
- [ ] Trademark + domain + handle check (CIPO, Namecheap, IG/X)
- [ ] Register business (ServiceOntario sole proprietorship, ~$60)
- [ ] Set up wallets, Underdog account, Shopify Lite

---

*Prepared by: Cleo | May 2026*