# Ombu · IBGE/SIDRA e indicadores censitários

Estrutura para descobrir, coletar e organizar tabelas do IBGE/SIDRA e transformar dados censitários em indicadores utilizáveis para leitura territorial.

## O que este caso mostra

- como tornar o SIDRA operacional para uso real;
- como ligar tabela censitária a análise espacial;
- como montar uma base para renda, domicílio e escolaridade.

## Esquema do fluxo

```mermaid
flowchart LR
    A[Busca por tema] --> B[API / scraping / seeds]
    B --> C[Cache e catálogo]
    C --> D[Seleção de variáveis]
    D --> E[Indicadores]
    E --> F[Mapas e análise territorial]
```

## Bases utilizadas

- tabelas do IBGE/SIDRA;
- catálogos e seeds confirmados;
- bases territoriais para integração posterior.

## Entregas

- descoberta mais confiável de tabelas;
- base censitária organizada;
- apoio à construção de indicadores;
- conexão entre dado tabular e território.

## Ferramentas

Python · SIDRA API · resolvedor híbrido · cache YAML

## Relevância

Dados censitários, indicadores urbanos, bases públicas e infraestrutura analítica para mapas, painéis e relatórios.
