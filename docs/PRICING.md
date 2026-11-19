# Vytrix pricing recommendation (DRAFT, not approved)

All figures are drafts for the owner's decision. Competitor figures are approximate, from a short web check in November 2026, and must not be quoted externally.

## Licence relationship

Vytrix is under the [Zyvor Production License v1.0](../LICENSE): non-production use is free, production use needs a paid commercial license. The price below is the price of that production licence. Free tier is unchanged (evaluation, development, testing, research, education). See also [COMMERCIAL-LICENSE.md](COMMERCIAL-LICENSE.md).

## Today (published)

INR 899 incl. GST (about US$10), a **one-time** perpetual Supporter grant per payer (Cashfree / Razorpay), per `COMMERCIAL-LICENSE.md` and the price book. It is not per Mac per year.

## Method

Zyvor price book: INR incl. 18% GST is authoritative; USD = INR / 1.18 / 84, rounded; adoption pricing; per-unit meter (here per Mac per year, as for Velora, Elvora and Gryvia-Apple).

## Recommendation

| Tier | Meter | INR incl. GST | USD (derived) | Notes |
|---|---|---:|---:|---|
| Free | non-production | 0 | 0 | Unchanged |
| Individual production | per Mac / year | **1,999** | **20** (1,999/1.18/84 = 20.2) | One person or entity, own Macs |
| Team / fleet production | per Mac / year | **3,499** | **35** (3,499/1.18/84 = 35.3) | Includes Fleet Pro; minimum 5 Macs (INR 17,495, about US$176/yr) |
| Large fleet (50+ Macs) | by quote | sales@zyvor.dev | | Volume band per the price book (-10/-15/-20%) |

## Market check (approximate)

- iStat Menus 7: about US$12 one-time (family pack about US$15); Setapp bundle lists it from about US$15 per month. Single-machine consumer utility, no fleet features.
- TG Pro: price not confirmed in this check; a one-time consumer licence in the low tens of dollars is the usual reference.
- Stats: free, open source.
- Netdata: about US$4.50 per node per month billed annually (about US$54/yr); core agent is open source.
- Datadog Infrastructure Pro: about US$15 per host per month list (about US$180/yr); free tier up to 5 hosts.
- Internal anchors: Velora Pro INR 7,299/Mac/yr (about US$86), Gryvia-Apple Solo INR 4,999/yr, Elvora US$199/Mac/yr, Nivora INR 999 one-time.

## Rationale

INR 899 one-time under-prices a production licence: it sits at iStat Menus consumer level, yields one payment per customer for a product that keeps shipping, and undercuts the INR 4,999 to 7,299 range of sibling Mac products. An annual per-Mac meter matches the rest of the Mac line and the price book. INR 1,999 (about US$20) per Mac per year stays a low-friction adoption price, well under Netdata and Datadog per-host rates, and roughly 1.7x today's one-time price recouped each year. Fleet Pro (central history, alerts, SSO, Prometheus) justifies INR 3,499 (about US$35) per Mac, still below Netdata's US$54 and far below Datadog's US$180, with a 5-Mac minimum so tiny fleets use the individual tier. Anyone who already paid INR 899 keeps their perpetual grant for the version current at payment and later versions, unless the owner decides otherwise.

## Open decisions

- Annual per-Mac meter versus keeping a one-time price; treatment of existing INR 899 payers.
- Whether individuals running Vytrix on a few of their own Macs pay per Mac or once per person.
- Update Cashfree/Razorpay forms and `zyvor-pricing` (`data/prices.csv`, licence column for Vytrix) only after approval.
