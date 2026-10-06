<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · en · no clinical/professional/rights approval -->

# Modified Fisher Scale

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-fisher-modificada)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Finding on the admission CT scan

`grau`

- `0` — 0 – No SAH and no intraventricular hemorrhage
- `1` — 1 – Thin SAH (focal or diffuse), without intraventricular hemorrhage
- `2` — 2 – Intraventricular hemorrhage with no SAH or thin SAH (focal or diffuse)
- `3` — 3 – Thick SAH (focal or diffuse), without intraventricular hemorrhage
- `4` — 4 – Thick SAH with intraventricular hemorrhage

## Method edition

Modified Fisher — Frontera et al., 2006, Table 1: absent, thin or thick SAH and intraventricular hemorrhage; grades 0–4

## Documented formula

Classifies the admission CT by the presence and thickness of subarachnoid blood (SAH) and the presence of intraventricular hemorrhage (IVH). Grade 0: no SAH and no IVH; grade 1: thin SAH without IVH; grade 2: IVH with either no SAH or thin SAH; grade 3: thick SAH without IVH; grade 4: thick SAH with IVH. In Frontera et al. (2006), local investigators classified blood as thin or thick by global impression, without explicit thickness criteria. The tool records the grade selected by the examiner; it does not interpret images.

## Limits and population

A CT grading system studied to predict symptomatic vasospasm after subarachnoid hemorrhage. The consulted study pooled patients from the placebo arms of four trials. It does not by itself establish a vasospasm diagnosis, predict all outcomes or indicate treatment.

## References

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

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

Grade 0: no subarachnoid or ventricular blood


### 2

Grade 2: symptomatic vasospasm in 33%


### 3

Grade 4: symptomatic vasospasm in 40%

