---
tipo: conceito
nome: Workflow agentic
categoria: foundations
tags: [conceito]
---

# Workflow agentic

## Definição
Workflow agentic é um fluxo de trabalho que combina etapas definidas com decisões tomadas por modelo, geralmente com uso de ferramentas, estado e múltiplas etapas.

## Por que isso importa
Esse conceito ajuda a sair da oposição simplista entre "automação rígida" e "agente livre demais". Muitas soluções úteis estão no meio: parte determinística, parte agentic.

## Como funciona
O fluxo costuma misturar regras fixas com pontos de decisão orientados por modelo.

- Algumas etapas são previsíveis.
- Outras dependem de interpretação do contexto.
- Ferramentas podem ser chamadas em momentos específicos.
- O fluxo pode registrar estado e pedir aprovação humana.

## Relação com outras ideias
Workflow agentic combina [[01 - Foundations/Agente|Agente]], [[01 - Foundations/Tool Calling|Tool Calling]], [[06 - RAG and Memory/Memória|Memória]] e [[11 - Observability/Observabilidade de IA|Observabilidade de IA]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[08 - Automation and Workflows/n8n|n8n]]
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]
- [[05 - Coding Agents/OpenHands|OpenHands]]

## Exemplo prático
Um fluxo de atendimento pode classificar a solicitação com IA, consultar base interna, pedir revisão humana em casos de risco e só então executar a ação final.

## Minha interpretação
Workflow agentic é uma forma mais realista de pensar sistemas com IA em produção. Em vez de autonomia total, a ideia é combinar flexibilidade com controle.

