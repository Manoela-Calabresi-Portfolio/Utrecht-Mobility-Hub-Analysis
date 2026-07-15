# Ombu · IBGE/SIDRA e indicadores censitários

Caso técnico centrado na estrutura da Ombu para descoberta, coleta e organização de tabelas do IBGE/SIDRA. O objetivo é transformar dados censitários em insumos utilizáveis para leitura territorial, indicadores urbanos e cruzamentos com outras bases públicas.

## Problema que o projeto resolve

O portal SIDRA nem sempre oferece um fluxo simples para descoberta e reaproveitamento de tabelas. O caso organiza um resolvedor híbrido para reduzir atrito entre busca, coleta e uso analítico.

## Bases utilizadas

- tabelas do IBGE/SIDRA;
- catálogos e seeds confirmados;
- dados territoriais para integração posterior.

## Método

- busca por palavra-chave;
- fallback entre API, scraping e seeds;
- cache local para reaproveitar descobertas;
- atualização de catálogo para renda, domicílios e escolaridade;
- integração com leituras territoriais em nível municipal e setorial.

## O que o projeto entrega

- infraestrutura para descoberta de tabelas;
- base censitária mais utilizável;
- apoio à construção de indicadores urbanos;
- conexão entre dado tabular e análise espacial.

## Ferramentas

- Python
- SIDRA API
- resolvedor híbrido
- cache YAML
- catálogo de datasets

## Relevância

- dados censitários e indicadores urbanos;
- bases públicas e dados secundários;
- infraestrutura analítica;
- apoio a mapas, painéis e relatórios territoriais.
