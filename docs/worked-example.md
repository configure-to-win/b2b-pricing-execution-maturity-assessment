# Worked example

> Illustrative example - not customer data, benchmark data, advice or a recommended policy.

## Scenario

Northstar Industrial Supply is a fictional mid-sized distributor of industrial equipment, spare parts and service packages. Its quotes may combine vendor-supplied products, local services, several currencies and customer-specific price agreements.

Sales uses a shared quoting system, but pricing information still comes from several sources. Finance maintains calculation guidance, and non-standard deals can require commercial approval.

## Example answers

| ID | Dimension | Current | Target | Rationale |
| --- | --- | ---: | ---: | --- |
| Q01 | Pricing data foundation | 1 | 3 | Source owners exist, but teams still use exported price files and manual freshness checks. |
| Q02 | Pricing data foundation | 1 | 3 | The correct version often depends on the product specialist. |
| Q03 | Customer-specific and contracted pricing | 1 | 3 | Agreements are recorded for major accounts but not always available in the quote context. |
| Q04 | Customer-specific and contracted pricing | 0 | 3 | Deviations from the existing agreement are usually reviewed manually. |
| Q05 | Calculations and deal economics | 2 | 3 | Margin and discount formulas are documented in a shared template. |
| Q06 | Calculations and deal economics | 2 | 3 | Sales and finance usually align, but rebate treatment still varies. |
| Q07 | Price execution | 2 | 3 | A standard process exists, but users can select a different value manually. |
| Q08 | Price execution | 1 | 3 | Override reasons are not captured consistently. |
| Q09 | Exception and approval governance | 2 | 3 | Discount and margin triggers are documented. |
| Q10 | Exception and approval governance | 2 | 3 | Routing is repeatable but substitutes and reapproval are not consistently applied. |
| Q11 | Traceability and performance visibility | 1 | 3 | Some calculation and approval history is retained, but it is fragmented. |
| Q12 | Traceability and performance visibility | 1 | 3 | Management reporting focuses on quote status rather than recurring pricing exceptions. |

## Example dimension profile

| Dimension | Current average | Current level | Target average | Target level | Gap |
| --- | ---: | --- | ---: | --- | ---: |
| Pricing data foundation | 1.00 | Emerging | 3.00 | Advanced | 2.00 |
| Customer-specific and contracted pricing | 0.50 | Reactive | 3.00 | Advanced | 2.50 |
| Calculations and deal economics | 2.00 | Established | 3.00 | Advanced | 1.00 |
| Price execution | 1.50 | Emerging | 3.00 | Advanced | 1.50 |
| Exception and approval governance | 2.00 | Established | 3.00 | Advanced | 1.00 |
| Traceability and performance visibility | 1.00 | Emerging | 3.00 | Advanced | 2.00 |

No overall average or maturity level is calculated.

## Example priorities

Using current averages and the published tie-break:

1. Customer-specific and contracted pricing
2. Pricing data foundation

The second priority ties with Traceability and performance visibility at 1.00. Pricing data foundation appears first because the fixed dimension order is used to resolve equal scores.

## Example actions

| Priority | Action | Owner | Evidence of completion |
| ---: | --- | --- | --- |
| 1 | Create a controlled contracted-price register with account, product, currency, effective dates and approval source. | Commercial operations | Approved register and three traced quote examples. |
| 2 | Define owners and freshness checks for list, cost, floor and currency sources used before quoting. | Pricing operations | Source register, update calendar and freshness report. |
| 3 | Define override reason codes and retain the selected reference and user-entered value. | Sales operations | Override specification and sampled decision traces. |

These actions are fictional. A real team should consider risk, quote volume, dependencies, effort and expected operational value before approving work.

## Why the full scan still matters

The example profile identifies pricing execution gaps. It does not show whether the largest quote-performance problem is data search, quote creation, errors, approvals, release delay or management visibility.

The full Quote Performance Scan adds those broader process dimensions and provides the separate overall benchmark.
