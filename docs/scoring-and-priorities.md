# Scoring and priorities

## Answer mapping

The workbook maps each visible response label to one numeric value from 0 through 4. Numeric values are used only for the two statements within their own dimension.

| Response | Value |
| --- | ---: |
| Ad hoc or manual | 0 |
| Partly defined | 1 |
| Documented but inconsistent | 2 |
| System-supported and governed | 3 |
| Measured and continuously improved | 4 |

## Blank handling

Blank-safe calculations are essential because users may complete the workbook over several sessions.

- A blank current response produces no numeric value.
- A current dimension average appears only after both current responses for that dimension are complete.
- Target responses are optional.
- A target dimension average appears only after both target responses for that dimension are complete.
- A gap appears only after both averages exist.
- A maturity level never appears for an incomplete dimension.
- Priority ranking and the two highlighted priorities remain blank until all twelve current responses are complete.

An incomplete response must not be interpreted as zero.

## Dimension calculation

Each dimension has exactly two equally weighted statements:

```text
Dimension average = (statement value A + statement value B) / 2
```

Examples:

| Statement A | Statement B | Average | Level |
| ---: | ---: | ---: | --- |
| 0 | 1 | 0.50 | Reactive |
| 1 | 2 | 1.50 | Emerging |
| 2 | 2 | 2.00 | Established |
| 2 | 3 | 2.50 | Advanced |
| 3 | 4 | 3.50 | Intelligent |

## Level classification

Classification is applied independently to each completed dimension:

```text
0.00 <= average <= 0.79  -> Reactive
0.80 <= average <= 1.59  -> Emerging
1.60 <= average <= 2.39  -> Established
2.40 <= average <= 3.19  -> Advanced
3.20 <= average <= 4.00  -> Intelligent
```

Because two integer statements are averaged, normal workbook results occur in increments of 0.50. The published bands also make the model unambiguous for machine-readable reuse and possible future extensions.

## Current-versus-target gap

```text
Gap = target average - current average
```

Interpretation:

- positive gap: the selected target is above the current state;
- zero gap: current and target selections are the same;
- negative gap: the target is below the current selection and should be reviewed for intent.

The workbook does not convert a gap into cost, benefit, timing or implementation priority.

## Priority rank

When all current-state responses are complete:

1. sort dimensions by current average in ascending order;
2. break equal scores using the fixed dimension order;
3. assign ranks 1 through 6;
4. display ranks 1 and 2 as the two initial improvement priorities.

Fixed tie-break order:

1. Pricing data foundation
2. Customer-specific and contracted pricing
3. Calculations and deal economics
4. Price execution
5. Exception and approval governance
6. Traceability and performance visibility

The tie-break is deterministic, not a statement that earlier dimensions are universally more important.

## Recommended next controls

Recommended controls depend on the current level and dimension. They are intended to help a workshop move from a maturity label to one concrete discussion.

Examples:

| Dimension | Reactive example | Advanced example |
| --- | --- | --- |
| Pricing data foundation | Assign owners and register approved price, cost, floor and currency sources. | Measure source freshness and investigate recurring version or availability failures. |
| Contracted pricing | Create a controlled register with account, product, value, scope and effective dates. | Review expiry, deviation and override patterns and feed findings into agreement controls. |
| Deal economics | Agree calculation definitions and one controlled specification for key measures. | Reconcile calculated and realised outcomes and manage a documented feedback loop. |
| Price execution | Define how the applicable price is selected and how overrides are recorded. | Measure override frequency and leakage and refine execution controls using evidence. |
| Approval governance | Document triggers, authority and the minimum decision evidence. | Measure routing outcomes, delay and rule drift and tune controlled exceptions. |
| Traceability | Define the minimum inputs, calculations, rules and decisions that must be retained. | Monitor recurring exceptions and control gaps and track completed improvements. |

The complete recommendation set is published in `data/assessment-model.json` and implemented in the workbook.

## Prohibited aggregation

Do not create:

```text
sum(all six dimension averages)
average(all six dimension averages)
percentage of maximum across all dimensions
single organisation-wide level
```

These outputs are outside the published methodology and would create a competing assessment rather than a focused module.
