# Contributing to the B2B Pricing Execution Maturity Assessment

Thank you for helping improve the **B2B Pricing Execution Maturity Assessment**.

The repository should remain a vendor-neutral practical resource for discussing and improving pricing execution during complex B2B quoting.

## Before contributing

Review:

- [README](README.md)
- [Methodology](docs/methodology.md)
- [Definitions](docs/definitions.md)
- [Limitations](docs/limitations.md)

## Contribution principles

### Preserve the assessment boundary

The workbook provides six dimension-level profiles. Do not introduce:

- an average or sum across all six dimensions;
- an overall pricing maturity or Quote Performance Score;
- an industry or participant benchmark;
- a product or vendor recommendation;
- a claim that every organisation should reach Intelligent maturity.

### Keep the content vendor-neutral

Questions, definitions and controls must not depend on one CPQ, CRM, ERP or pricing platform. Product references may be used only as clearly labelled examples outside the controlled assessment model.

### Do not introduce universal commercial policy

Do not prescribe a universal floor price, margin, discount, approval threshold, SLA or target maturity level. These decisions depend on the organisation, quote population and risk context.

### Keep examples fictional

Examples must not contain customer data, confidential prices, personal data, vendor-confidential implementation details or unsupported benchmark data.

### Keep all representations aligned

Changes to a question, dimension, response label, threshold or recommendation may affect:

- `template/b2b-pricing-execution-maturity-assessment.xlsx`;
- `data/assessment-questions.csv`;
- `data/assessment-model.json`;
- the PDF preview;
- README and documentation;
- the worked example and changelog.

Update every affected representation in the same contribution.

## Report an issue

Include where possible:

```text
Workbook version:
Worksheet or file:
Question, dimension or field:
Expected behaviour:
Observed behaviour:
Steps to reproduce:
Excel or LibreOffice version:
Additional context:
```

Do not attach confidential quote, customer, price, contract, vendor or employee data.

## Propose a methodology change

Explain:

1. the decision problem the change addresses;
2. why the existing model is insufficient;
3. affected questions, dimensions, thresholds or recommendations;
4. whether previous results remain comparable;
5. how blank handling and incomplete dimensions were tested;
6. how the Excel, CSV, JSON, PDF and documentation remain aligned.

## Documentation style

- Use concise headings and plain international English.
- Use British English spelling where practical.
- Explain purpose and boundaries before implementation detail.
- Distinguish observed evidence from assumptions and target states.
- Avoid promotional claims, universal best practices and unsupported outcomes.
- Refer to **Configure to WIN** as the publisher.

## Workbook compatibility

Avoid VBA, macros, external data connections, proprietary add-ins and formulas that require non-standard extensions. Prefer stable Excel and LibreOffice-compatible formulas and explicit validation lists.

## Versioning

Record changes to controlled terms, assessment statements, formulas, thresholds, workbook structure or recommendations in `CHANGELOG.md`. Use an appropriate version increment for changes that affect previous results or machine-readable consumers.

## License

By contributing, you agree that your original contribution may be distributed under the repository license in [LICENSE.md](LICENSE.md). Do not submit material that you do not have the right to contribute.

The official online resource is:

https://configure.win/resources/pricing-maturity-assessment
