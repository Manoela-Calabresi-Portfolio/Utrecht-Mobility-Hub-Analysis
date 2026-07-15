# Utrecht · Hubs de mobilidade e lacunas territoriais

**Repositório original:** https://github.com/Manoela-Calabresi-Portfolio/Utrecht-Mobility-Hub-Analysis

Estudo espacial sobre mobilidade compartilhada, acesso ao transporte público e cobertura territorial na Província de Utrecht.

![Mapa de acesso ao transporte público em Utrecht](../assets/cases/utrecht-pt-access-map.jpg)

## O que este caso mostra

- onde a cobertura de mobilidade é mais frágil;
- onde demanda e infraestrutura estão mais desequilibradas;
- como transformar dados de mobilidade em leitura territorial clara.

## Bases utilizadas

- transporte público;
- shared mobility;
- moradia e empregos;
- grade hexagonal e camadas territoriais.

## Método

```mermaid
flowchart LR
    A[Dados de mobilidade] --> B[Limpeza e padronização]
    B --> C[Agregação espacial]
    C --> D[Scores de demanda e oferta]
    D --> E[Clusters e lacunas]
    E --> F[Mapas e priorização]
```

## Entregas

- mapas temáticos;
- leitura de acessibilidade;
- score de lacunas;
- síntese para planejamento.

## Ferramentas

Python · GeoPandas · QGIS · UMAP · HDBSCAN

## Relevância

Mobilidade sustentável, transporte público, acessibilidade urbana e análise espacial aplicada.
