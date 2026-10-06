<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · es · no clinical/professional/rights approval -->

# Reticulocitos corregidos e IPR

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/indice-de-producao-reticulocitaria)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Reticulocitos

`ret`

% · intervalo: 0–50

### Hematocrito

`ht`

% · intervalo: 5–65

## Edición del método

Hillman 1969: hematocrito 45%; maduración 1/1,5/2/2,5 por bandas locales 40/30/20

## Fórmula documentada

Reticulocitos corregidos (%) = reticulocitos (%) × hematocrito ÷ 45.

RPI = Reticulocitos corregidos ÷ factor de maduración, el factor es tiempo de maduración sanguínea en días: 1,0 (hematocrito ≥ 40%); 1,5 (30–39%); 2,0 (20–29%); 2,5 (\< 20%).

## Límites y población

La corrección reticulocitaria depende del cambio del tiempo de maduración asociado a la gravedad de la anemia. El estudio original utilizó anemia provocada por flebotomía en personas normales; el resumen no confirmó los intervalos simplificados locales. El índice no determina por sí solo la etiología ni la reserva medular en cualquier enfermedad.

## Referencias

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

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

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

IPR < 2: anemia hipoproliferativa (producción insuficiente)

| Detalles del resultado | |
| --- | --- |
| Reticulocitos corregidos por el hematocrito | 3,3% |
| Factor de maduración utilizado | 2,0 día(s) |


### 2

IPR ≥ 3: respuesta medular adecuada (hemólisis o pérdida aguda)

| Detalles del resultado | |
| --- | --- |
| Reticulocitos corregidos por el hematocrito | 6,7% |
| Factor de maduración utilizado | 1,5 día(s) |


### 3

IPR < 2: anemia hipoproliferativa (producción insuficiente)

| Detalles del resultado | |
| --- | --- |
| Reticulocitos corregidos por el hematocrito | 3,0% |
| Factor de maduración utilizado | 2,0 día(s) |


### 4

IPR entre 2 y 3: respuesta limítrofe

| Detalles del resultado | |
| --- | --- |
| Reticulocitos corregidos por el hematocrito | 4,0% |
| Factor de maduración utilizado | 2,0 día(s) |

