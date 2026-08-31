# B2B Pricing Execution Maturity Assessment

A free, vendor-neutral Excel workbook for assessing six dimensions of pricing execution maturity in B2B quoting and identifying practical improvement priorities.

The assessment is a focused module of the Configure to WIN Quote Performance Scan. It produces a dimension-level pricing execution profile; it does not calculate an overall maturity score, provide an industry benchmark or recommend a product or vendor.

## Get the assessment

- [Download the latest versioned release](https://github.com/configure-to-win/b2b-pricing-execution-maturity-assessment/releases/latest)
- [Open the Excel workbook](template/b2b-pricing-execution-maturity-assessment.xlsx)
- [View the assessment and methodology](https://configure.win/resources/pricing-maturity-assessment)
- [Complete the full Quote Performance Scan](https://configure.win/quote-performance-scan)
- [Review the shareable maturity matrix](preview/pricing-execution-maturity-matrix.pdf)

## What the workbook assesses

The workbook evaluates twelve statements across six pricing dimensions:

1. **Pricing data foundation** - availability, ownership and version control of list, cost, floor and currency data.
2. **Customer-specific and contracted pricing** - availability of account- and product-specific agreements and explicit price-deviation calculations.
3. **Calculations and deal economics** - consistent calculation of discounts, margins, rebates and incentives.
4. **Price execution** - consistent application of the applicable price and controlled manual overrides.
5. **Exception and approval governance** - explicit approval conditions, authority and routing.
6. **Traceability and performance visibility** - reconstruction of inputs, calculations, rules and decisions, plus visibility into recurring exceptions and leakage.

Each dimension contains two equally weighted statements. Users select a current state and may add an optional target state.

## Response scale

| Value | Response |
| ---: | --- |
| 0 | Ad hoc or manual |
| 1 | Partly defined |
| 2 | Documented but inconsistent |
| 3 | System-supported and governed |
| 4 | Measured and continuously improved |

Dimension averages map to five maturity levels:

| Average | Level |
| ---: | --- |
| 0.00-0.79 | Reactive |
| 0.80-1.59 | Emerging |
| 1.60-2.39 | Established |
| 2.40-3.19 | Advanced |
| 3.20-4.00 | Intelligent |

See [Methodology](docs/methodology.md) and [Scoring and priorities](docs/scoring-and-priorities.md) for the complete rules.

## What the workbook produces

- a current maturity level for each completed dimension;
- an optional target level and gap for each completed dimension;
- the two weakest dimensions after all current-state questions are complete;
- a recommended next control based on the dimension and current level;
- an improvement register with owners, target dates, status and evidence;
- a current-versus-target maturity profile;
- a bridge from pricing execution topics to the broader Quote Performance Scan.

The workbook deliberately does **not** produce:

- a score or average across all six dimensions;
- an overall pricing maturity level;
- a Quote Performance Score;
- an industry or market benchmark;
- a comparison with other users;
- a product, vendor or implementation-architecture recommendation.

## Workbook contents

| Worksheet | Purpose |
| --- | --- |
| **Start here** | Explains purpose, scope, response options, instructions, version and official resources. |
| **Quick assessment** | Captures the twelve current-state responses, optional targets and supporting evidence. |
| **Maturity profile** | Shows six dimension averages, levels, gaps, priority rank and recommended next controls. |
| **Maturity matrix** | Describes each dimension from Reactive through Intelligent and suggests useful evidence. |
| **Improvement priorities** | Supports action planning, ownership, target dates, status and evidence. |
| **Quote Performance bridge** | Explains how each pricing dimension relates to the broader quote process. |
| **Methodology** | Documents calculations, thresholds, blank handling, priority logic and limitations. |
| **Definitions** | Provides vendor-neutral definitions of the controlled terminology. |
| **Worked example** | Demonstrates the assessment using fictional industrial-distributor data. |

## Recommended workflow

1. Agree which B2B quote process, team and commercial scope are being assessed.
2. Complete all twelve current-state statements in **Quick assessment**.
3. Add target-state responses only where a future control state has been agreed.
4. Review the six dimension results and the two first improvement priorities.
5. Add evidence and assign improvement actions, owners and target dates.
6. Use the **Maturity matrix** to discuss what a realistic next level means for each dimension.
7. Complete the full Quote Performance Scan to assess how pricing interacts with quote creation, accuracy, cycle time, approvals, release and commercial visibility.

Detailed instructions are available in the [Workbook guide](docs/workbook-guide.md).

## Repository contents

- `template/` - the release workbook;
- `preview/` - a shareable PDF of the maturity matrix;
- `data/assessment-questions.csv` - the twelve statements in a portable tabular format;
- `data/assessment-model.json` - the dimensions, scale, thresholds, priority logic and limitations;
- `docs/` - methodology, scoring, definitions, worked example, bridge and limitations.

The CSV and JSON files support review, citation and reuse of the published assessment model. They are not a separate benchmark or scoring service.

## Documentation

- [Workbook guide](docs/workbook-guide.md)
- [Methodology](docs/methodology.md)
- [Scoring and priorities](docs/scoring-and-priorities.md)
- [Maturity matrix](docs/maturity-matrix.md)
- [Quote Performance bridge](docs/quote-performance-bridge.md)
- [Definitions](docs/definitions.md)
- [Worked example](docs/worked-example.md)
- [Limitations](docs/limitations.md)

## Important limitations

This is a structured self-assessment, not an independent audit. Results describe only the responses entered for the selected scope. The workbook does not assess willingness-to-pay, packaging strategy, market price optimisation or the suitability of a specific software product.

Review [Limitations](docs/limitations.md) before using the output in an investment, governance or implementation decision.

## Version

Current release: **1.0.0**.

See [CHANGELOG.md](CHANGELOG.md) for release history.

## License

The workbook and original documentation are licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.md).

Preferred attribution:

> B2B Pricing Execution Maturity Assessment by Configure to WIN  
> https://configure.win/resources/pricing-maturity-assessment  
> Licensed under CC BY 4.0.
