# Modelo 210. Renta 20xx 4T (Octubre, Noviembre y Diciembre)

Este documento es la plantilla que utilizo para rellenar el Modelo 210 trimestralmente.

Los números y las fechas son solo ejemplos.

## Rendimientos Íntegros

```txt
800 * 3 = 2.400 €
```

A rellenar en la **casilla 5**.

## Gastos Deducibles

Los siguientes son los gastos deducibles (los que sean anuales, prorratear a 3 meses, es decir, dividir entre 4).

### 1. IBI (Impuesto de Bienes Inmuebles)

El valor del recibo del __IBI 20xx__ es de `400 €` (Cuota Total Pagada, descontado la bonificación).

```txt
400 / 4 = 100 €
```

> Lo del IBI tiene un poco de truco: Como hasta el final del año no se conoce exactamente yo uso el del año anterior en 1T, 2T y 3T y lo ajusto en 4T.

### 2. Amortización, 3% Valor de Construcción (Gasto Fiscalmente Deducible)

[Referencia: Inmuebles no residentes](https://www.consultingdms.com/no-residentes-inmuebles-espana-hacienda-incumple-la-ley-no-se-lo-pone-facil/)

Los siguientes valores que vienen en el recibo del __IBI 20xx__:

- __Valor de Adquisición__: `150.000 €`
- __Valor Catastral__: `70.000 €`
- __Valor de Construcción__: `20.000€`

```txt
(Valor de Construcción / Valor Catastral) * 100 = %
(20.000 / 70.000) * 100 = 28,57%

(Valor Adquisición * %) = Valor de Adquisición de la Construcción
150.000 * 28,57% = 42.855

Valor de Adquisición de la Construcción * 3%
42.855 * 3% = 1.285,65

Se prorratea a 3 meses (dividir entre 4):
1.285,65 / 4 = 321,41 €
```

### 3. Gastos Comunidad y Derramas

```txt
70 x 3 = 210 €
```

### 4. Impuestos/Intereses Hipoteca/Préstamo

```txt
10/20xx:  5
11/20xx:  5
12/20xx:  5
     Total: 15 €
```

### 5. Seguro de la Vivienda

- N. RECIBO: `xxxxxxx`
- NUM. PÓLIZA: `xxxxxx`
- DURACIÓN: `xx/xx/xxxx` A `xx/xx/xxxx`

```txt
400 / 4 = 100 €
```

### 6. Gastos Conservación/Reparación (Obras)

Total: 0

### TOTAL Gastos deducibles

IBI 20xx + Amor3%   + Comun    + HipInt  + Seguro  + Gastos

```txt
100 € + 321,41 € + 210 € + 15 € + 100 € + 0 € = 746,41 €
```

Total a deducir `746,41 €`

A rellenar en la **casilla 7**.

## Resultado

Utilizo como entrada el fichero exportado del anterior trimestre.

Link [Agencia Tributaria Española](https://www.agenciatributaria.es/).

Pagado: `xxx €`.
