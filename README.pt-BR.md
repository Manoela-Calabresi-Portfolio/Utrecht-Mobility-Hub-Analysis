# Utrecht · Hubs de mobilidade e lacunas territoriais

Relatório resumido em português-BR do projeto **Utrecht Mobility Hub Analysis**.

## Pergunta central

Onde reforçar ou implantar hubs de mobilidade na Província de Utrecht para responder ao crescimento da demanda e melhorar o acesso multimodal.

## Síntese do projeto

O estudo cruza demanda urbana, moradia, empregos, transporte público, shared mobility e hubs existentes em uma grade hexagonal de 250 metros. A partir dessas camadas, o projeto identifica áreas com desequilíbrio entre cobertura de infraestrutura e pressão de demanda.

**Relatório completo em PDF:** [3.0_report/Utrecht_Mobility_Hub_Analysis_Full_Report.pdf](3.0_report/Utrecht_Mobility_Hub_Analysis_Full_Report.pdf)

## Método

```mermaid
flowchart LR
    A[Fontes públicas e APIs] --> B[Limpeza e padronização]
    B --> C[Agregação espacial em hexágonos]
    C --> D[Indicadores de demanda e oferta]
    D --> E[UMAP e HDBSCAN]
    E --> F[Mapas de lacunas e priorização]
```

## Bases utilizadas

- moradia e crescimento habitacional;
- empregos ponderados por modo;
- transporte público;
- hubs existentes;
- OV-fiets e shared mobility;
- rede cicloviária.

## Mapas principais

### Empregos ponderados

![Empregos ponderados](2.0_notebooks/0.0_outputs/job_maps/job_weighted_graduated.png)

### Moradia e crescimento

![Moradia e crescimento](2.0_notebooks/0.0_outputs/housing_maps/housing_density_maps.png)

### Shared mobility

![Shared mobility](2.0_notebooks/0.0_outputs/shared_mobility/vehicle_availability_map.png)

### Acesso ao transporte público

![Acesso ao transporte público](2.0_notebooks/0.0_outputs/pt_access/pt_access_score_map.png)

## Resultados

- identificação de áreas com cobertura mais frágil;
- leitura territorial de lacunas de mobilidade;
- priorização de zonas críticas;
- apoio a planejamento de hubs e integração modal.

## Relevância

Mobilidade sustentável, transporte público, acessibilidade urbana, análise espacial e visualização territorial.

## Estrutura do repositório

- `2.0_notebooks/` notebooks e mapas gerados;
- `3.0_report/` relatório completo em PDF;
- `requirements.txt` dependências do projeto.

## Ver arquivos do projeto

[Abrir repositório completo](https://github.com/Manoela-Calabresi-Portfolio/Utrecht-Mobility-Hub-Analysis)
