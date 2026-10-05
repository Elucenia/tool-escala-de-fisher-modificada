<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · pt-BR · no clinical/professional/rights approval -->

# Escala de Fisher modificada

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-fisher-modificada)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Achado na tomografia de admissão

`grau`

- `0` — 0 – Sem HSA e sem hemorragia intraventricular
- `1` — 1 – HSA fina (focal ou difusa), sem hemorragia intraventricular
- `2` — 2 – Hemorragia intraventricular com HSA ausente ou fina (focal ou difusa)
- `3` — 3 – HSA espessa (focal ou difusa), sem hemorragia intraventricular
- `4` — 4 – HSA espessa, com hemorragia intraventricular

## Edição do método

Fisher modificada — Frontera et al., 2006, tabela 1: HSA ausente, fina ou espessa e hemorragia intraventricular; graus 0–4

## Fórmula documentada

Classifica a tomografia de admissão pela presença e espessura do sangue subaracnóideo (HSA) e pela presença de hemorragia intraventricular (HIV). Grau 0: sem HSA e sem HIV; grau 1: HSA fina sem HIV; grau 2: HIV com HSA ausente ou fina; grau 3: HSA espessa sem HIV; grau 4: HSA espessa com HIV. Em Frontera et al. (2006), os investigadores locais classificaram o sangue como fino ou espesso por impressão global, sem critérios explícitos de espessura. A ferramenta registra o grau selecionado pelo examinador; não interpreta imagens.

## Limites e população

Graduação tomográfica estudada para predizer vasoespasmo sintomático após HSA. O estudo consultado reuniu pacientes dos braços placebo de quatro ensaios. Não confere, por si só, diagnóstico de vasoespasmo, previsão de todos os desfechos ou indicação de tratamento.

## Referências

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
