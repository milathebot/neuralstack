# Overclock — Ideation to Launch Action Plan
**Version 1 | May 2026**
**8-week sprint to first 200+ tins sold at Superteam Canada / Toronto Solana event**

Two parallel tracks: **Physical product** and **On-chain layer**. They merge at launch.

---

## The Product

**Overclock** — Pressed focus mints, 30-tablet flip-top tin, chocolate-espresso, sugar-free
**Stack:** Xylitol 60% / Mannitol 10% / Dutch Cocoa 8% / Coffee Extract 3% / Ceremonial Matcha 3% / Lion's Mane dual-extract 2% / Vanilla 2% / Chocolate Flavor 1.5% / Sea Salt 0.5% / Stevia Reb M 0.3% / Calcium Stearate 1%
**Price:** $10–14 retail / $6–8 wholesale
**Per tin:** ~75mg natural caffeine / ~50mg L-theanine / ~600mg lion's mane
**Terminology:** Hand-pressed. Never cold-pressed (Neuro Gum patent).

---

## The Genesis cNFT

Each Genesis cNFT (001–1,000) records:
- Mint number (001–1,000)
- Mint date
- Event/location
- Tin SKU
- **Perks:** 10% Lifetime Discount / Early Access / Token-Gated Drops / Genesis Channel Access
- **Non-transferable / Non-tradable** — stays in holder's wallet forever

On-chain: Underdog Protocol. Solana mainnet. Mint wallet funded with ~0.5 SOL (covers 10,000+ mints).

---

## Budget: ~$2,395–3,195

**Compress to ~$2,000–2,200:**
- Skip optional label review ($300–500 saved)
- Skip Ledger hardware wallet for now ($200 saved)
- Use Shopify Lite ($5/mo) not full Shopify
- Negotiate tablet press on AliExpress ($180–220 vs $300+)

**Realistic budget: ~$2,000–2,200**

---

## Critical Path (what breaks everything)

1. **York Region Public Health says no to home production** → Plan B: commercial kitchen (FoodShare / Kitchen24, +$500–1,000)
2. **Tablet press doesn't arrive** → Order from Amazon CA even at premium, don't wait on AliExpress for v1
3. **Tins don't arrive** → Order unbranded fallback Week 2
4. **Formula doesn't taste good** → Mint-flavor fallback (peppermint-forward)
5. **Solana Pay / cNFT fails at event** → Fallback: collect wallet addresses on paper, mint cNFTs in batch post-event
6. **Event gets cancelled** → Telegram community + online launch as Plan B

---

## Week 0 — This week

**Goal:** Confirm foundations before spending money or time.

- [ ] **1. Confirm event date.** DM Superteam Canada — get the exact date. Everything backwards-plans from this.
- [ ] **2. Call York Region Public Health (1-800-361-5653).** Describe product: "pressed compressed candy / breath mints, sugar alcohol base with cocoa powder, matcha powder, lion's mane mushroom powder, all dry ingredients, no cooking, ambient compression, sealed metal tins." Ask: "Does this qualify as low-risk food under O. Reg. 493/17?" Get answer in writing via follow-up email.
- [ ] **3. Trademark + domain + handle check.** CIPO at ised-isde.canada.ca/cipo (Nice Class 30). Check overclockmints.com, overclock.gg, overclock.snacks, overclock.fyi, overclock.foods. Check @OverclockMints on IG/X.
- [ ] **4. Register the business.** Sole proprietorship through ServiceOntario, ~$60. "Overclock" or "Overclock Foods" as operating name. Unlocks bank account, dealer name on label, insurance.
- [ ] **5. Set up operational stack:**
  - Business bank account (Big 5, walk-in with MBL)
  - Phantom or Backpack wallet (software wallet for v1, Ledger later)
  - Coinbase or Kraken account for SOL/USDC → CAD off-ramping
  - Underdog Protocol account (cNFT minting)
  - Shopify Lite trial ($5/mo)
  - → Output: all accounts live, wallet address logged.

**Time:** ~5 hours. **Cost:** ~$60.

---

## Week 1 — Prototype + On-chain scaffolding

**Goal:** Press first 50 tablets. cNFT mint flow on devnet.

### Physical product track
- [ ] **6. Order tablet press.** TDP-0 single-station hand press, Amazon CA or AliExpress, $200–$300. Include 8–10mm round die. 7–10 day delivery. Order from Amazon CA if time-constrained.
- [ ] **7. Order ingredients:**
  - Costco: Dutch-processed cocoa powder, vanilla extract, sea salt
  - Bulk Barn: xylitol (compressible/granular), mannitol if available
  - Online (Amazon CA / specialty): ceremonial matcha (Jade Leaf, Encha, Aki Matcha), lion's mane dual-extract (Real Mushrooms or Nootropics Depot, ~$25–40/100g), calcium stearate food-grade (NOW Foods), stevia reb M, natural chocolate flavor powder, decaf coffee extract powder
  - Kitchen scale with 0.1g precision (~$30 if needed)
  - → Output: all ingredients in kitchen.
- [ ] **8. Order prototype tins.** 5–10 unbranded flip-top tins from Amazon CA (~$1–2 each) for taste testing. → Output: tins in hand.

### On-chain track
- [ ] **9. Design Genesis cNFT metadata schema:**
  - Mint number (001–1,000)
  - Mint date
  - Event/location
  - Tin SKU
  - Perk traits: "10% Lifetime Discount", "Early Access", "Token-Gated Drops", "Genesis Channel Access"
  - Image: prototype design now, final Week 3
  - Non-transferable, non-tradable
  - → Output: JSON schema doc.
- [ ] **10. Build mint flow on Solana devnet.** Underdog Protocol API: mint cNFT to wallet address. Test: QR scan → Phantom → pay devnet SOL → backend confirms → cNFT minted. → Output: working devnet demo.
- [ ] **11. Set up cNFT-tracking database.** Postgres. Tables: `genesis_holders` (wallet, mint number, mint date, email, event), `purchases` (wallet, order ID, amount, discount applied). → Output: DB schema deployed.

**Time:** ~15 hours. **Cost:** ~$400–500.

---

## Week 2 — Press first batch + validate formula

**Goal:** 50 prototype tablets. 10 honest testers. Refined formula.

### Physical product track
- [ ] **12. Press first 50 tablets** (once press arrives):
  - Mix dry ingredients per formula, sieve through fine mesh
  - Test-press 5 tablets, check hardness and ejection
  - Adjust compression pressure
  - Press 50, store in airtight container
  - → Output: 50 prototype tablets.
- [ ] **13. Self-test 2–3 days.** Note: dominant flavor, off-notes, aftertaste, mouthfeel, dissolve time, sweetness. → Output: tasting note doc.
- [ ] **14. Distribute to 8–10 honest testers** (Solana devs, coders, gamer friends). Give 3–5 tablets each. Ask: flavor (1–10), texture (1–10), would-pay-$12-for-30 (Y/N), one thing to change. → Output: 8–10 written reviews.
- [ ] **15. Get food handler certificate.** TrainCan or CIFS online, ~$50, ~4 hours, valid 5 years. → Output: cert in hand.
- [ ] **16. Quote liability insurance.** PolicyMe, Zensurance, or local broker — ~$1M general commercial liability for home-based food maker, ~$400–600/year. Get quote in writing, don't bind yet. → Output: written quote.

### On-chain track
- [ ] **17. Move cNFT mint flow to Solana mainnet.** Same code, switch RPC endpoint, fund mint wallet with ~0.5 SOL. Test one real mint to a friend's wallet. → Output: working mainnet mint, verified on Solscan.
- [ ] **18. Build Solana Pay checkout flow:**
  - Event QR: Generate payment QR, displayed at booth. On payment confirmation, capture buyer's wallet address, trigger cNFT mint.
  - Online: Standalone Solana Pay flow (Shopify integration comes Week 4–5).
  - → Output: working event checkout demo.
- [ ] **19. Document perk redemption mechanism:**
  - Online: wallet connects at checkout → backend checks cNFT ownership → applies 10% if yes
  - Event: buyer shows Phantom wallet → check holder list → apply discount
  - Token-gated drops: Lit Protocol or tokenproof checks cNFT ownership
  - → Output: redemption flow doc.

**Time:** ~15–20 hours. **Cost:** ~$50 cert + ~$30 cNFT testing.

---

## Week 3 — Iterate formula + finalize design + build community

**Goal:** Formula locked. Branded tins ordered. Telegram channels live. Genesis collection deployed.

### Physical product track
- [ ] **20. Iterate formula based on tester feedback.** Adjust matcha %, lion's mane %, cocoa intensity, sweetness. Press second batch of 50. Re-test with 3–5 original testers. → Output: v2 formula, locked.
- [ ] **21. Order branded tins in bulk.** 250+ flip-top metal tins, ~$0.80–$1.20 each. Sources: Uline Canada, Pacific Bag, Berlin Packaging, Alibaba (longer lead, lower cost). Get tin design + Genesis numbering done first — etched or printed serial numbers #001–#1000. Lead time 1–3 weeks, order now. → Output: tins ordered, ETA confirmed.
- [ ] **22. Finalize bilingual EN/FR label artwork:**
  - Bilingual Nutrition Facts table
  - Bilingual ingredient list with allergens
  - Net quantity, dealer name (Overclock Foods, Vaughan ON address), lot/date code
  - QR code pointing to overclock.co (or chosen domain) — wallet connection + benefits page
  - → Output: print-ready artwork.
- [ ] **23. Optional: regulatory label review.** $300–500 with Quality Smart Solutions or Source Nutraceutical. Spots check artwork before printing. → Output: cleared label artwork. (Skip to save $300–500.)
- [ ] **24. Order labels in bulk.** 250–500 custom labels via Sticker Mule, VistaPrint, or local printer, ~$0.20–$0.40 each. → Output: labels ordered.

### On-chain track
- [ ] **25. Design Genesis cNFT visual.** Minimal, on-brand — tin design with holder's number prominent. Spec: 1080x1080 PNG, on-chain metadata via Underdog. → Output: 1,000 unique numbered images (or template + dynamic numbering).
- [ ] **26. Deploy Genesis cNFT collection on mainnet.** Through Underdog: create collection, supply cap 1,000, non-transferable, non-tradable, 0% royalties. Verify on Solscan. → Output: collection live, address logged.
- [ ] **27. Launch Telegram channels:**
  - Public: @OverclockMints — announcements, drops, general community
  - Genesis-gated: @OverclockGenesis — locked behind cNFT verification via Collab.Land or Guild.xyz. Members get product feedback access, voting on next SKUs, drop alpha.
  - Seed public channel with 10–20 friends so it's not empty at launch.
  - → Output: both channels live.
- [ ] **28. Build wallet-to-discount integration for online sales.** Shopify app or custom checkout that detects connected wallets, queries Postgres for cNFT ownership, auto-applies 10% discount. Test on Shopify staging. → Output: integration working, tested.

**Time:** ~25 hours. **Cost:** ~$200–300 tins (deposit), ~$100 labels, ~$50 cNFT mint costs.

---

## Week 4 — First 100 tins + soft validation

**Goal:** Press 100 production tins. Soft-launch at small validation event.

### Physical product track
- [ ] **29. Press 100 production tablets.** ~3,000 tablets total at 30/tin. Plan ~30–40 hours across 5–7 evenings. → Output: 100 production tins, ready to fill.
- [ ] **30. Fill, seal, label.** Fill each tin with 30 tablets (verify weight matches label), apply labels, close. → Output: 100 finished tins.
- [ ] **31. Soft validation event.** Toronto crypto meetup, coffee shop pop-up, hackathon prep night, friend's launch party. Bring 50–75 tins. Goals:
  - Real customers, real payments (cash + Solana Pay)
  - First Genesis cNFTs minted (#001–#075)
  - Direct feedback on tin design, taste, price
  - Photos and content for social
  - → Output: 50–75 tins sold, 50–75 Genesis cNFTs minted, written feedback.

### On-chain track
- [ ] **32. Test full event flow live.** Every Solana Pay purchase triggers cNFT mint automatically. Watch for failures. Document edge cases. Have manual fallback: collect wallet address on paper, mint after event. → Output: tested live flow, known issue list.
- [ ] **33. Bind liability insurance** before this event. ~$400–600/year. Don't skip — first time handing food to strangers is when you want coverage. → Output: active policy, COI on file.

**Time:** ~40–50 hours pressing + ~5 hours event prep + ~3 hours at event. **Cost:** ~$400–600 insurance + remaining tin/label balance.

---

## Week 5 — Iterate + scale to 200 tins for launch

**Goal:** Apply learnings, press final 100–150 tins, prepare for main event.

- [ ] **34. Debrief soft launch.** What sold? What did people say? Did cNFT mint flow work? Did anyone redeem the 10% discount? Write it down, change what needs changing. → Output: lessons doc, prioritized fix list.
- [ ] **35. Press additional 100–150 tins.** Brings total to 200–250 for main event. → Output: inventory ready.
- [ ] **36. Build the website.** Shopify Lite ($5/mo) or basic Shopify ($39/mo). Integrate:
  - Solana Pay checkout (Helio or Crossmint app, or custom)
  - Wallet connection + Genesis discount logic
  - cNFT minting on online order completion
  - Token-gated landing page visible only to Genesis holders
  - About / Story / FAQ pages
  - → Output: live storefront at overclock.co (or chosen domain).
- [ ] **37. Pre-event marketing push:**
  - Twitter/X thread announcing Overclock, Solana integration, Genesis 1000
  - Telegram channel post with countdown
  - Direct outreach to 10–20 Solana people in Canada + UAE — first 100 Genesis holders
  - Reach out to Superteam Canada for event-table coordination
  - → Output: launch buzz, target audience knows it's coming.

**Time:** ~40 hours pressing + ~15 hours website + marketing. **Cost:** ~$50 Shopify + ~$100 misc marketing/printing.

---

## Week 6 — LAUNCH

**Goal:** Sell at Superteam Canada / Toronto Solana event. Mint Genesis #075–#250+.

- [ ] **38. Day-of event prep:**
  - 200+ tins packed and ready
  - Solana Pay QR code printed/displayed (laptop + backup phone)
  - Card reader for fiat (Square, ~$60 device + 2.65% fee — encourage Solana Pay)
  - Cash float (~$200 in 5s and 10s)
  - Genesis cNFT mint flow tested, tested as backup on phone
  - Business cards / QR codes to website and Telegram
  - Photos and video — get someone to document
  - → Output: ready to sell.
- [ ] **39. At the event:**
  - Sell tins, mint Genesis cNFTs in real-time
  - Collect emails for fiat payers or wallet-less buyers (manual cNFT mint after)
  - Short pitch to every buyer, ask what they think, ask if they'd buy again
  - Get content: booth photos, cNFT photos, holder photos
  - → Output: 100–200 tins sold, 100–200 Genesis holders.
- [ ] **40. Same-day post-event:**
  - Tweet/post launch with photos
  - Welcome new Genesis holders to Telegram channel personally
  - Thank Superteam Canada publicly
  - → Output: content live, community engagement.

**Time:** Event prep ~5 hours + event day ~6–10 hours + post ~2 hours. **Cost:** ~$60–100 contingency.

---

## Week 7–8 — Sustain and convert

**Goal:** Convert launch into repeat purchases, prepare next event, plan first co-brand.

- [ ] **41. Email/Telegram follow-up to every Genesis holder:**
  - Day 1: "Thanks for being a Genesis holder. Here's how to use your perks. Telegram is here."
  - Day 5: "Restock available + here's what's next." Drive online reorders.
  - → Output: re-engagement campaign sent.
- [ ] **42. First wholesale conversation.** Reach out to 3–5 Toronto crypto-adjacent spots: Bitcoin Embassy, Cluster Cafe, Cohash co-working, hackerspaces, dev-focused cafes. Stock at $6–8 wholesale. → Output: 1–2 wholesale relationships started.
- [ ] **43. Plan next event.** Another Toronto Solana meetup, Breakpoint side event, UAE Solana event. Genesis tins #200+ sold there. → Output: next event date locked.
- [ ] **44. Reach out to 5 Solana projects for co-brand SKU.** Targets: Superteam Canada, Tensor, Backpack, MagicEden, Phantom, Cypher Capital UAE, Solana Mobile. Pitch: "Co-branded tin for your community/event. Limited run of 100–300 tins. We handle production, you handle distribution." → Output: 1–2 partnerships in early discussion.
- [ ] **45. Press 100–200 more tins** for next event + wholesale + online reorders. → Output: replenished inventory.
- [ ] **46. Set up Shopify analytics + on-chain dashboard.** Track: tins sold, Genesis cNFTs minted (current of 1,000), reorder rate, wallet retention, Telegram growth. Weekly review. → Output: dashboard live, weekly KPIs.

**Time:** ~30 hours/week across both weeks. **Cost:** ~$200–400 for ingredients + tins for reorder batch.

---

## What NOT to do for v1

- Major retailers (Whole Foods, Indigo) — not until 1,000+ tins sold and proven repeat purchase
- Custom Solana program / smart contract — Underdog + off-chain DB does everything
- NPN application — you're food, not NHP
- Fungible token / DAO / revenue share — wrong stage
- International shipping — defer to hand-carried event trips
- Hire anyone — one-person operation for 6–12 months minimum
- Overdesign the website — Shopify theme + good photos + clear Genesis pitch is enough

---

## Weekly Check-in Cadence

Every Sunday, 30 minutes:
- Did this week's tasks ship?
- What's blocked?
- What got pushed?
- What's the single most important thing for next week?

---

*Prepared by: Cleo | May 2026*