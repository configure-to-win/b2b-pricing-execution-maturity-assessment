# Methodology

## Purpose

The B2B Pricing Execution Maturity Assessment helps a team describe how consistently pricing data, customer agreements, calculations, execution, approvals and decision evidence are handled during B2B quoting.

It is a focused module of the Configure to WIN Quote Performance Scan. The module provides six separate dimension profiles. It does not provide a replacement Quote Performance Score or a general organisational maturity rating.

## Assessment scope

The assessment covers pricing execution inside or directly around the quote process:

1. Pricing data foundation
2. Customer-specific and contracted pricing
3. Calculations and deal economics
4. Price execution
5. Exception and approval governance
6. Traceability and performance visibility

It does not assess willingness-to-pay research, packaging strategy, market segmentation, competitor-price optimisation or the selection of a specific software architecture.

## Assessment unit

Before answering, define one coherent scope. For example:

- one B2B sales team;
- one quote type;
- one region or business unit;
- one product or service portfolio;
- one current quoting process.

Do not combine materially different processes into one answer merely to obtain a single profile. Separate assessments are more useful when business units use different data, policies or workflows.

## Statements and weighting

Each dimension contains two statements. Both statements have equal weight.

The response scale is:

| Value | Label | Interpretation |
| ---: | --- | --- |
| 0 | Ad hoc or manual | The practice depends primarily on manual work, individual knowledge or one-off decisions. |
| 1 | Partly defined | Some ownership or guidance exists, but adoption is local or incomplete. |
| 2 | Documented but inconsistent | A repeatable standard exists, but it is not applied or enforced consistently. |
| 3 | System-supported and governed | The practice is supported systematically, governed and traceable. |
| 4 | Measured and continuously improved | Outcomes and exceptions are reviewed and controls are improved using evidence. |

The label describes the selected scope, not the organisation as a whole.

## Current state

A current dimension average is calculated only when both current-state statements in that dimension have been answered:

```text
Current dimension average
= (current statement 1 value + current statement 2 value) / 2
```

If either statement is blank, the current average and level remain blank.

## Target state

Target state is optional. A target dimension average is calculated only when both target-state statements in that dimension have been answered:

```text
Target dimension average
= (target statement 1 value + target statement 2 value) / 2
```

A blank target does not affect the current profile. Targets should describe an agreed future control state, not an assumed maximum.

## Maturity thresholds

| Dimension average | Level |
| ---: | --- |
| 0.00-0.79 | Reactive |
| 0.80-1.59 | Emerging |
| 1.60-2.39 | Established |
| 2.40-3.19 | Advanced |
| 3.20-4.00 | Intelligent |

The thresholds are classification rules within this workbook. They are not market percentiles or externally validated benchmarks.

## Gap

A dimension gap is calculated only when both current and target averages exist:

```text
Dimension gap = target dimension average - current dimension average
```

A gap is a planning input. It is not proof of financial impact, urgency or implementation effort.

## Priority ranking

Priorities are not displayed until all twelve current-state statements have been answered.

Dimensions are ranked from the lowest current average to the highest. When two dimensions have the same current average, the published dimension order is used as a fixed tie-break. The workbook highlights the first two dimensions as initial discussion priorities.

The ranking does not consider business value, regulatory exposure, cost, dependencies or implementation effort. Teams should add that context in the improvement register.

## Recommended next control

The workbook selects a next-control prompt using:

- the dimension; and
- the current maturity level.

The prompts follow this general transition pattern:

- Reactive: define ownership, sources and a minimum repeatable control.
- Emerging: document the standard and apply it consistently.
- Established: introduce systematic enforcement and exception capture.
- Advanced: measure outcomes and create a managed feedback loop.
- Intelligent: maintain governance, monitor drift and refine controls using evidence.

Recommendations are discussion prompts, not mandatory implementation instructions.

## Evidence

Users should record evidence that supports the selected response, such as:

- controlled source registers;
- effective-date history;
- contracted-price records;
- calculation specifications;
- override logs;
- approval policies and rule versions;
- decision traces;
- exception and leakage reports.

Evidence quality is not scored. The notes field helps the team distinguish a documented observation from an unsupported impression.

## No overall score

The methodology never sums or averages the six dimension results. It does not calculate:

- an overall Pricing Maturity Score;
- an overall maturity level;
- a Quote Performance Score;
- a market or industry benchmark;
- a comparison with other users.

This boundary keeps the workbook focused on pricing execution and prevents it from competing with the full Quote Performance Scan.
