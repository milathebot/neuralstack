# Overclock — Underdog Protocol cNFT Setup Brief
**Version 1 | May 2026**

Underdog Protocol (underdogprotocol.com) is the no-code minting platform for Solana cNFTs. This brief gives you everything you need to deploy the Genesis mint in under 30 minutes once you have an account.

---

## WHAT WE'RE BUILDING

**Genesis Collection: Overclock Genesis Pass**

- Total supply: 1,000 NFTs
- Type: cNFT (compressed NFT on Solana)
- Transferability: Non-transferable, non-tradable (burned if sold)
- Blockchain: Solana (devnet for testing, then mainnet)

---

## STEP 1 — Create Underdog Account

1. Go to: underdogprotocol.com
2. Click "Connect Wallet" — use Phantom
3. Sign in with your Phantom wallet
4. Complete account setup (email, name, project name = "Overclock")

Once your account is created, send me the workspace/project URL.

---

## STEP 2 — Create a New Project

1. In Underdog dashboard → **New Project**
2. Project name: **Overclock**
3. Description: "Functional mint brand for gamers, coders, and Web3 builders. Toronto, Canada."
4. Project type: **Collection** (not Application)
5. Chain: **Solana**
6. Submit

---

## STEP 3 — Create the Genesis Collection

1. In your project → **New Collection**
2. Collection name: **Overclock Genesis Pass**
3. Symbol: **OGP**
4. Description:

> The Overclock Genesis Pass is the first and only access token for the Overclock community. Holders receive:
> - 10% lifetime discount on all Overclock products
> - Early access to new product drops before public
> - Token-gated limited editions reserved for Genesis holders
> - Access to the private Genesis Holders channel
>
> Genesis Passes are non-transferable and non-tradable. They remain in your wallet permanently and cannot be sold. If resold, the pass is burned and perks revoked.

5. Supply: **1,000**
6. Transferability: **Non-transferable** (check this box)
7. Royalties: **0%** (no secondary sales)
8. Image: (upload the Genesis artwork — see art brief below)
9. Submit

---

## STEP 4 — Mint Page Setup

Underdog generates a mint page automatically. But we'll want a custom one. Here's what to put on it:

**Page headline:** Overclock Genesis Pass

**Subheadline:** Own the moment. Own the mint.

**Description:**
> 1,000 Genesis Passes. Non-transferable. Non-tradable.
>
> Each pass grants lifetime perks: 10% discount, early access, token-gated drops, and Genesis community access.
>
> Mint opens [DATE TBD — fill in when event is confirmed].

**Call to action button:** "Mint Your Pass — [PRICE] SOL"

**Price:** 0.1 SOL (~$15–20 USD at current prices — adjusts automatically with SOL volatility)

**Mint limit per wallet:** 1

**Start date:** Set to when you want minting to open

---

## GENESIS PASS ARTWORK — BRIEF

**What I need from a designer (or what I can generate):**

**Format:** 800×800px PNG, transparent or dark background
**Style:** Dark espresso palette, similar to the pitch deck. Near-black background, warm amber/copper accents. Minimalist. Premium. Think Ledger/Arc/Linear energy.

**Visual concept options:**
1. A single lit match or ember on a dark surface — "ignition" energy
2. A tin silhouette with light escaping from the lid — product-as-power-source
3. A circuit-board style pattern with the letter "O" integrated — Web3-native

**Text on the image:**
- "GENESIS" (top or centered)
- "OVERCLOCK" (below genesis)
- "001/1000" style numbering (or this can be programmatic)

**Color palette:**
- Background: #0D0D0D (near-black)
- Primary: #D4A853 (warm amber/copper)
- Secondary: #8B5E3C (espresso brown)
- Accent: #F5E6C8 (cream highlight)

**Deliverable:** Final PNG + source file (Figma/Illustrator)

---

## STEP 5 — Deploy to Devnet First

Before mainnet:
1. In Underdog → set network to **Devnet** for testing
2. Mint a test NFT to your own wallet
3. Verify it appears in Phantom
4. Check that the non-transferable flag works (try transferring — it should fail)

Once devnet is clean, switch to **Mainnet** and launch for real.

---

## STEP 6 — Discord Integration

Underdog can sync minted passes to Discord roles automatically.

**Setup:**
1. Underdog → Project → Settings → Discord Integration
2. Connect your Discord server
3. Map the Genesis Pass collection to the "Genesis Holder" role
4. Set: "Auto-assign Genesis Holder role when user connects wallet and holds OGP"

This means anyone who mints automatically gets the Discord role — no manual assignment needed.

---

## MINT FLOW SUMMARY

1. User visits mint page (Underdog-generated or custom)
2. Connects Phantom wallet
3. Verifies wallet age (anti-bot: minimum 30 days old)
4. Mints 1 OGP at 0.1 SOL
5. NFT lands in Phantom immediately
6. Discord bot detects mint → auto-assigns "Genesis Holder" role
7. Genesis Holder gains access to #genesis-holders channel

---

## MINT PAGE COPY (FULL)

**Title:** Overclock Genesis Pass

**Hero:**
> 1,000 passes. Lifetime perks. One moment.

**Perks list:**
- 10% lifetime discount on every Overclock order
- Early access — new products before anyone else
- Token-gated drops — limited editions reserved for holders
- Genesis community — private Discord channel, direct line to the product team

**Fine print:**
> Non-transferable. Non-tradable. Passes remain in your wallet permanently. Abuse of perks (resale, transfer attempts) results in perk revocation.
>
> Minting open to wallets 30+ days old. One pass per wallet. While supplies last.

**CTA button:** "Mint — 0.1 SOL"

---

## IF UNDERDOG IS TOO SLOW / COMPLICATED

Underdog is the easiest no-code option. If you hit friction, alternatives:
1. **Tensor** — more complex, more features (secondary market)
2. **MagicEden** — requires more setup, good for collections with trading

For v1, Underdog is the right call. Keep it simple.