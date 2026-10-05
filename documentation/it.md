<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · it · no clinical/professional/rights approval -->

# Scala di Fisher modificata

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-fisher-modificada)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Reperto alla TC di ingresso

`grau`

- `0` — 0 – Nessuna ESA né emorragia intraventricolare
- `1` — 1 – ESA sottile (focale o diffusa), senza emorragia intraventricolare
- `2` — 2 – Emorragia intraventricolare senza ESA o con ESA sottile (focale o diffusa)
- `3` — 3 – ESA spessa (focale o diffusa), senza emorragia intraventricolare
- `4` — 4 – ESA spessa con emorragia intraventricolare

## Edizione del metodo

Fisher modificata — Frontera et al., 2006, tabella 1: ESA assente, sottile o spessa ed emorragia intraventricolare; gradi 0–4

## Formula documentata

Classifica la TC all’ingresso in base alla presenza e allo spessore del sangue subaracnoideo (ESA) e alla presenza di emorragia intraventricolare (IVH). Grado 0: assenza di ESA e IVH; grado 1: ESA sottile senza IVH; grado 2: IVH con ESA assente o sottile; grado 3: ESA spessa senza IVH; grado 4: ESA spessa con IVH. In Frontera et al. (2006), gli sperimentatori locali hanno classificato il sangue come sottile o spesso in base all’impressione globale, senza criteri espliciti di spessore. Lo strumento registra il grado selezionato dall’esaminatore; non interpreta le immagini.

## Limiti e popolazione

Graduazione tomografica studiata per predire il vasospasmo sintomatico dopo emorragia subaracnoidea. Lo studio consultato ha riunito pazienti dei gruppi placebo di quattro studi. Da sola non stabilisce una diagnosi di vasospasmo, non predice tutti gli esiti e non indica un trattamento.

## Riferimenti

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
