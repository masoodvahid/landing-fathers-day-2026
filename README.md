# B.B. Simon — Father's Day Landing Page

A single-file, dependency-free landing page for the Father's Day **20%–50% off** sale.
Minimalistic luxury design: near-black background, brand gold + crystal-shimmer accents.

## Preview
Open `index.html` in any browser. No build step, no install.

## What to customize (all in `index.html`)

| What | Where | Notes |
|------|-------|-------|
| **Logo** | `<a class="logo">` in the header (search `TODO: replace this wordmark`) | Swap the text wordmark for `<img src="assets/logo.svg" alt="B.B. Simon" height="34">` |
| **Brand colors** | `:root { ... }` at the top of the `<style>` block | Update `--gold`, `--ink`, etc. with your exact brand hex codes |
| **Discount tiers** | `<section id="tiers">` (search `EDIT THESE TIERS`) | ⚠️ Discount is **by product category**. Placeholders: Belts 20%, Wallets 30%, Handbags 40%, Accessories 50%. Replace category names + percentages with your exact rule. |
| **Promo code** | `DAD2026` in the `code-pill` | Or remove the pill if the discount is automatic |
| **Sale end date** | `SALE_END` in the `<script>` | Drives the countdown timer |
| **Shop links** | `href="https://bbsimononline.com"` | Point CTAs at the right store/collection URL |

## Outstanding items
- [ ] Confirm the **exact per-category percentages** (placeholders in place; the attached rule image didn't transfer into the build environment).
- [ ] Provide the **logo file** and **exact brand hex codes** to replace the placeholders.
