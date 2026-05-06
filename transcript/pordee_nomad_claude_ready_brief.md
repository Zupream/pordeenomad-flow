# Claude-ready Brief — PordeeNomad Meeting Update

## Source
Meeting recording: **PordeeNomad Meeting Update — 2026-04-03 15:50 GMT+07**  
Duration: ~40:42 minutes  
Language: Thai  
Note: This brief is based on Thai ASR/VTT. Some names/terms may need verification.

---

## Purpose of Meeting
The meeting aligned the team on the revised commission and platform-fee model for the marketplace/affiliate structure. The main shift is to separate:

1. **Seller-defined affiliate commission** — seller inputs the percentage paid to affiliates/agents.
2. **Platform-defined fee deduction** — platform deducts a fixed percentage from seller sales/revenue and allocates it internally to planned payout pools and operating fees.

---

## High-level Decision
Use a model similar to TikTok Shop:

- Seller can set the affiliate/agent commission percentage by themselves.
  - Example: seller inputs 5%, 10%, 15%, 20%.
  - The affiliate/agent receives according to the percentage the seller set.
- Separately, the platform deducts a platform fee from the seller.
  - Working example discussed: **10% platform deduction**.
  - This is separate from the affiliate commission.

---

## Proposed Platform Fee Breakdown

Working example: if a seller sells a product for 100 THB, the platform deducts 10 THB.

### 10% Platform Deduction Structure

| Category | % | Internal Use |
|---|---:|---|
| Shop Growth / Marketing Plan Support Fee | 5% | Used for royalty, team management, sales sharing, and special bonus pools |
| Infrastructure Fee | 2% | Used for internal management and training/seminars |
| Platform Fee / GP | 3% | Used as platform operating budget / marketplace GP |

### Internal breakdown of the 5% Shop Growth / Marketing Plan Support Fee

| Item | % | Notes |
|---|---:|---|
| Royalty / Licensing fee | 2% | Calculated using existing model |
| Team management fee | 1% | Per-person: 1% of downline (3 levels) affiliate commission × tier% |
| Sales sharing | 1% | Pool from total company sales |
| Special/quarterly/other bonus | 1% | Pool from total company sales, used for promotional rewards |

Important UX/business note:
- Seller does not necessarily need to see all internal details.
- The seller-facing explanation can show the 10% platform fee as high-level categories, e.g. 5% growth support, 2% infrastructure, 3% platform fee.
- Detailed internal allocation can remain for admin/business logic.

---

## Item 1 — Seller-defined Affiliate Commission

### Decision
Seller inputs the affiliate commission percentage themselves.

### Examples
- Seller inputs 5% → affiliate receives 5%.
- Seller inputs 10% → affiliate receives 10%.
- Seller inputs 15% → affiliate receives 15%.
- Seller inputs 20% → affiliate receives 20%.

### Clarification
This is separate from:
- platform fee,
- team management fee,
- royalty/licensing,
- sales sharing,
- special bonus pool.

---

## Item 2 — Royalty / Licensing Fee: 2%

### Decision
Continue calculating this using the existing model.

### Example discussed
If a team/member generates 100 THB of income:

- War/starting rank receives 10% of 100 = 10 THB.
- Gold receives 30% of 10 = 3 THB.
- Platinum receives 50% of 3 = 1.50 THB.

The team confirmed this item is clear and can continue with the same logic.

---

## Item 3 — Team Management Fee: 1%

### Pool source
- 1% from **affiliate commission of downline levels 1, 2, and 3 combined** (not from sales).
- **Calculated per person** — each qualifying partner calculates from their own downline's commissions, 3 levels deep.

### Eligibility / qualification
A person must have:
- personal sales of at least 1,000 THB/month, and
- affiliate/agent commission income of at least 1,000 THB/month.

### Payout concept (updated)
Each qualifying partner's team management fee is calculated individually:
1. Sum all affiliate commissions of their downline levels 1, 2, and 3.
2. Calculate 1% of that total sum.
3. Multiply by the partner's own tier percentage.

Example:
- Partner is Gold tier.
- Downline level 1 commissions (10 people) = 50,000 THB.
- Downline level 2 commissions (20 people) = 30,000 THB.
- Downline level 3 commissions (20 people) = 20,000 THB.
- Total downline commissions = 100,000 THB.
- 1% pool = 1,000 THB.
- Gold (10%) = 1,000 × 10% = **100 THB**.

Tier percentages:
  - Starter: 0% (not eligible).
  - Silver: 5% of pool.
  - Gold: 10% of pool.
  - Platinum: 15% of pool.
  - Wisdom: 20% of pool.

### Key clarifications
- The calculation covers **exactly 3 levels deep** (direct downline + 2 more levels).
- **Every qualifying partner** receives team management fee calculated from their own downline.
- The pool source is affiliate commission income of downline members, not their sales amounts.
- Overpay risk is mitigated because the source is only 1% and is capped by actual commission income generated.

---

## Item 4 — Sales Sharing: 1%

### Pool source
- 1% from **total company sales**.

### Eligibility discussed
A person must have:
- personal sales of at least 1,000 THB/month, and
- affiliate/agent commission income of at least 10,000 THB/month.

### Payout concept
The platform separates a pool from total company sales, then allocates by rank.

Example:
- Company sales = 1,000,000 THB.
- 1% pool = 10,000 THB.
- Rank allocation examples:
  - Gold: 10% of 10,000 = 1,000 THB.
  - Platinum: 15% of 10,000 = 1,500 THB.
  - Wisdom: 20% of 10,000 = 2,000 THB.

### Distribution within each rank
If multiple people qualify for the same rank, the rank pool is split among qualified people in that rank.

Example:
- Gold allocation = 1,000 THB.
- If 10 Gold members qualify, each gets 100 THB.

---

## Item 5 — Special / Promotional Bonus: 1%

### Pool source
- 1% from **total company sales**.

### Purpose
Used for special rewards such as:
- travel bonus,
- quarterly/6-month/yearly promotion,
- gold/reward campaigns,
- other seasonal incentives.

### Flexibility
The specific promotion can change by campaign period:
- every 3 months,
- every 6 months,
- yearly,
- or other campaign cycles.

Examples mentioned:
- Hong Kong trip,
- Japan trip,
- gold,
- other campaign rewards.

### Initial qualification idea
Initially, there was an idea to require:
- personal sales of at least 1,000 THB/month, and
- affiliate/agent commission income of at least 1,000 THB/month.

### Final direction after discussion
The team leaned toward removing the separate base “qualification” for this item, because having both “qualification” and “promotion condition” may be confusing and redundant.

Instead, define only campaign-specific conditions.

### Example campaign condition
- If a member earns affiliate/agent commission of 100,000 THB within 6 months → receives 1 Hong Kong trip seat.
- If a member earns affiliate/agent commission of 200,000 THB within 6 months → receives 2 seats.
- Maximum mentioned in the example: 2 seats.

### Communication recommendation
Communicate the target as commission income, not sales or points.

Example:
> If you earn 100,000 THB in affiliate/agent commission within 6 months, you receive 1 trip seat.

### Important legal/operational note
The team discussed avoiding conversion into “points,” because points could create additional legal/registration complexity for the platform.

---

## Important Business Rules / Assumptions

1. The 10% platform deduction is separate from seller-defined affiliate commission.
2. Seller controls affiliate commission rate.
3. Platform controls fee deduction rate and internal allocation.
4. Royalty/licensing continues using existing logic.
5. Team management fee is calculated per person: 1% of their downline's (3 levels) affiliate commission × tier percentage.
6. Sales sharing and special bonus are based on total company sales.
7. Special bonuses should be campaign-based and flexible.
8. Avoid using points unless legally reviewed.
9. For seller-facing UI, simplify explanation of platform deduction; keep internal breakdown in admin/business logic.

---

## Open Questions / Items to Verify

1. Confirm final platform deduction percentage: is 10% fixed or only an example?
2. Confirm final public-facing wording for the platform fee categories.
3. Confirm exact rank names and rank percentages:
   - Silver / entry level: 5%?
   - Gold: 10%?
   - Platinum: 15%?
   - Wisdom: 20%?
4. Confirm royalty rank names and cascade percentages.
5. ~~Confirm whether Team Management Fee should always pay all qualified members or require any additional cap.~~ **RESOLVED:** Pays all qualified members; calculated per person from their own downline 3 levels; no additional cap needed.
6. Confirm whether Sales Sharing eligibility is exactly:
   - personal sales >= 1,000 THB/month,
   - affiliate commission income >= 10,000 THB/month.
7. Confirm promotional bonus max reward cap, e.g. 2 seats.
8. Confirm whether promotion periods will be 3 months, 6 months, yearly, or configurable by admin.

---

## Next Steps from Meeting

1. Pimp/Supim will update the slides based on the clarified model.
2. Prepare and send a revised MOM (Minutes of Meeting).
3. Share the updated slide link and MOM in the group.
4. Update with P’Max before broadcasting the final update to the group.
5. Proceed to next step after slide/MOM alignment.

---

## Suggested Prompt to Give Claude

You are helping define business requirements and system logic for a marketplace + affiliate platform called PordeeNomad.

Use the following meeting decisions as source context. Please help convert this into:
1. business rules,
2. calculation formulas,
3. admin configuration requirements,
4. seller-facing UI copy,
5. affiliate/member-facing UI copy,
6. edge cases and acceptance criteria.

Key model:
- Seller defines affiliate commission percentage themselves.
- Platform separately deducts a platform fee from seller revenue/sales.
- Working platform fee example is 10%, split into:
  - 5% Shop Growth / Marketing Plan Support Fee,
  - 2% Infrastructure Fee,
  - 3% Platform Fee / GP.
- The internal 5% support fee is split into:
  - 2% Royalty / Licensing,
  - 1% Team Management,
  - 1% Sales Sharing,
  - 1% Special/Promotional Bonus.
- Royalty follows existing cascade logic.
- Team Management is calculated per person: sum affiliate commissions of downline 3 levels, take 1%, multiply by partner's tier percentage. All qualifying partners receive this from their own downline.
- Sales Sharing uses 1% of company sales and allocates by rank, then splits among qualified members in each rank.
- Special Bonus uses 1% of company sales and should be campaign-based; avoid point conversion due to legal complexity.
- Promotions should use conditions such as affiliate commission earned within a period, e.g. 100,000 THB in 6 months gets 1 trip seat.

Please structure the output for a BA/PO handoff.
