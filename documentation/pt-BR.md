<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · pt-BR · no clinical/professional/rights approval -->

# Reticulócitos corrigidos e IPR

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/indice-de-producao-reticulocitaria)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Reticulócitos

`ret`

% · intervalo: 0–50

### Hematócrito

`ht`

% · intervalo: 5–65

## Edição do método

Hillman 1969:Ht referência 45%, maturação 1/1,5/2/2,5 por faixas locais 40/30/20

## Fórmula documentada

Reticulócitos corrigidos (%) = reticulócitos (%) × hematócrito ÷ 45.

IPR = reticulócitos corrigidos ÷ fator de maturação, em que o fator (tempo de maturação no sangue, em dias) é 1,0 com Ht ≥ 40%; 1,5 com 30–39%; 2,0 com 20–29%; 2,5 com \< 20%.

## Limites e população

A correção reticulocitária depende da alteração do tempo de maturação associada à gravidade da anemia. O estudo original usou anemia provocada por flebotomia em pessoas normais; faixas simplificadas locais não foram confirmadas pelo resumo. O índice não determina sozinho etiologia ou reserva medular em qualquer doença.

## Referências

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

IPR < 2: anemia hipoproliferativa (produção insuficiente)

| Detalhes do resultado | |
| --- | --- |
| Reticulócitos corrigidos pelo hematócrito | 3,3% |
| Fator de maturação usado | 2,0 dia(s) |


### 2

IPR ≥ 3: resposta medular adequada (hemólise ou perda aguda)

| Detalhes do resultado | |
| --- | --- |
| Reticulócitos corrigidos pelo hematócrito | 6,7% |
| Fator de maturação usado | 1,5 dia(s) |


### 3

IPR < 2: anemia hipoproliferativa (produção insuficiente)

| Detalhes do resultado | |
| --- | --- |
| Reticulócitos corrigidos pelo hematócrito | 3,0% |
| Fator de maturação usado | 2,0 dia(s) |


### 4

IPR entre 2 e 3: resposta limítrofe

| Detalhes do resultado | |
| --- | --- |
| Reticulócitos corrigidos pelo hematócrito | 4,0% |
| Fator de maturação usado | 2,0 dia(s) |

