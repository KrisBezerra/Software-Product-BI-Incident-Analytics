# BI Incident Analytics

Sistema de análise de incidentes de Business Intelligence desenvolvido com **Tableau** utilizando **dados simulados em CSV**.  
O projeto tem como objetivo identificar padrões operacionais em incidentes de BI e apoiar a análise de estabilidade de dashboards e processos de dados.

---

## Objetivo do Projeto

O projeto busca analisar registros de incidentes relacionados a sistemas de Business Intelligence para identificar padrões como:

- Áreas com maior volume de incidentes
- Dashboards que apresentam mais problemas
- Tipos de erro mais recorrentes
- Tempo médio de resolução de incidentes

A proposta é simular um ambiente real de monitoramento de BI, permitindo visualizar problemas operacionais através de dashboards analíticos.

---

## Arquitetura do Projeto

O fluxo de dados do projeto é simples e focado em análise exploratória:

CSV Dataset 

   ↓

Tableau

   ↓

Dashboard Analítico



Os dados são armazenados em um arquivo CSV e conectados diretamente ao Tableau, onde são analisados e visualizados por meio de dashboards interativos.
