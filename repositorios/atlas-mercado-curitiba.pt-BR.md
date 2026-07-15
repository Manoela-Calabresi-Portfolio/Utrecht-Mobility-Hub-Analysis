# Ombu · Atlas urbano de Curitiba e definição de submercados

Caso de modelagem territorial em escala de cidade para definir submercados urbanos a partir de zoneamento, oferta, centralidades e eixos estruturais.

![Mapa de submercados territoriais de Curitiba](../assets/cases/atlas-curitiba-submercados.jpg)

## O que este caso mostra

- definição de submercados de forma auditável;
- leitura territorial de centralidades e estrutura urbana;
- cruzamento entre zoneamento, oferta e transporte;
- apoio a decisão locacional e desenvolvimento.

## Como os submercados são construídos

```mermaid
flowchart LR
    A[Zoneamento] --> E[Modelo territorial]
    B[Oferta urbana] --> E
    C[Eixos estruturais] --> E
    D[Cadastro e licenciamento] --> E
    E --> F[Submercados]
    F --> G[Mapa e leitura locacional]
```

## Bases utilizadas

- zoneamento;
- cadastro e licenciamento;
- oferta urbana;
- eixos estruturais e transporte.

## Entregas

- definição de submercados;
- base analítica em PostGIS;
- camadas derivadas para mapas;
- leitura territorial comparável.

## Ferramentas

PostGIS · SQL espacial · Python · GeoJSON

## Relevância

Inteligência territorial aplicada, georreferenciamento, modelagem espacial e leitura urbana em escala de cidade.
