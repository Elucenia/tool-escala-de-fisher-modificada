<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · es · no clinical/professional/rights approval -->

# Escala de Fisher modificada

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-de-fisher-modificada)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Hallazgo en la tomografía al ingreso

`grau`

- `0` — 0 – Sin HSA ni hemorragia intraventricular
- `1` — 1 – HSA fina (focal o difusa), sin hemorragia intraventricular
- `2` — 2 – Hemorragia intraventricular sin HSA o con HSA fina (focal o difusa)
- `3` — 3 – HSA espesa (focal o difusa), sin hemorragia intraventricular
- `4` — 4 – HSA espesa con hemorragia intraventricular

## Edición del método

Fisher modificada — Frontera et al., 2006, tabla 1: HSA ausente, fina o espesa y hemorragia intraventricular; grados 0–4

## Fórmula documentada

Clasifica la TC de ingreso según la presencia y el espesor de la sangre subaracnoidea (HSA) y la presencia de hemorragia intraventricular (HIV). Grado 0: sin HSA ni HIV; grado 1: HSA fina sin HIV; grado 2: HIV con HSA ausente o fina; grado 3: HSA espesa sin HIV; grado 4: HSA espesa con HIV. En Frontera et al. (2006), los investigadores locales clasificaron la sangre como fina o espesa por impresión global, sin criterios explícitos de espesor. La herramienta registra el grado seleccionado por el examinador; no interpreta imágenes.

## Límites y población

Graduación tomográfica estudiada para predecir vasoespasmo sintomático tras hemorragia subaracnoidea. El estudio consultado reunió pacientes de los brazos placebo de cuatro ensayos. No establece por sí sola un diagnóstico de vasoespasmo, la predicción de todos los desenlaces ni una indicación de tratamiento.

## Referencias

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
