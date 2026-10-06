<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · en · no clinical/professional/rights approval -->

# Corrected reticulocyte count and RPI

[conditions, sources and permissions](https://elucenia.org/en/tools/indice-de-producao-reticulocitaria)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Reticulocytes

`ret`

% · range: 0–50

### Hematocrit

`ht`

% · range: 5–65

## Method edition

Hillman 1969: reference hematocrit 45%; maturation 1/1.5/2/2.5 with local bands 40/30/20

## Documented formula

Corrected reticulocytes (%) = reticulocytes (%) × hematocrit ÷ 45.

RPI = Corrected reticulocytes ÷ maturation factor, the factor is maturation time in blood, in days: 1.0 (hematocrit ≥ 40%); 1.5 (30–39%); 2.0 (20–29%); 2.5 (\< 20%).

## Limits and population

Reticulocyte correction depends on the change in maturation time associated with anemia severity. The original study used phlebotomy-induced anemia in normal people; simplified local ranges were not confirmed by the abstract. The index alone does not determine the cause or marrow reserve in any disease.

## References

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

IPR < 2: hypoproliferative anemia (insufficient production)

| Result details | |
| --- | --- |
| Reticulocytes corrected by hematocrit | 3.3% |
| Maturation factor used | 2.0 day(s) |


### 2

IPR ≥ 3: adequate marrow response (hemolysis or acute loss)

| Result details | |
| --- | --- |
| Reticulocytes corrected by hematocrit | 6.7% |
| Maturation factor used | 1.5 day(s) |


### 3

IPR < 2: hypoproliferative anemia (insufficient production)

| Result details | |
| --- | --- |
| Reticulocytes corrected by hematocrit | 3.0% |
| Maturation factor used | 2.0 day(s) |


### 4

IPR between 2 and 3: borderline response

| Result details | |
| --- | --- |
| Reticulocytes corrected by hematocrit | 4.0% |
| Maturation factor used | 2.0 day(s) |

