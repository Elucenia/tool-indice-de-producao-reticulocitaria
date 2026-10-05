<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · it · no clinical/professional/rights approval -->

# Reticolociti corretti e indice di produzione reticolocitaria

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/indice-de-producao-reticulocitaria)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Reticolociti

`ret`

% · intervallo: 0–50

### Ematocrito

`ht`

% · intervallo: 5–65

## Edizione del metodo

Hillman 1969: ematocrito 45%; maturazione 1/1,5/2/2,5 per fasce locali 40/30/20

## Formula documentata

Reticolociti corretti (%) = reticolociti (%) × ematocrito ÷ 45.

RPI = Reticolociti corretti ÷ fattore di maturazione, fattore è maturazione nel sangue in giorni: 1,0 (ematocrito ≥ 40%); 1,5 (30–39%); 2,0 (20–29%); 2,5 (\< 20%).

## Limiti e popolazione

La correzione reticolocitaria dipende dall’alterazione del tempo di maturazione associata alla gravità dell’anemia. Lo studio originale ha usato anemia provocata da flebotomia in persone normali; gli intervalli locali semplificati non sono stati confermati dall’abstract. L’indice da solo non determina l’eziologia o la riserva midollare in qualsiasi malattia.

## Riferimenti

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

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
