---
tipo: conceito
nome: Observabilidade de IA
categoria: observability
tags: [conceito]
---

# Observabilidade de IA

## DefiniÃ§Ã£o
Observabilidade de IA Ã© a capacidade de entender como um sistema com IA estÃ¡ se comportando em uso real, incluindo entradas, saÃ­das, chamadas de ferramenta, custo, latÃªncia, falhas e qualidade percebida.

## Por que isso importa
Sistemas com IA podem parecer bons em testes manuais e falhar em produÃ§Ã£o de formas difÃ­ceis de enxergar. Sem observabilidade, o time opera no escuro.

## Como funciona
O sistema registra eventos relevantes ao longo da execuÃ§Ã£o.

- Prompt ou entrada recebida.
- Contexto usado.
- Ferramentas chamadas.
- Tempo de resposta.
- Custo, erros e avaliaÃ§Ã£o de qualidade.

## RelaÃ§Ã£o com outras ideias
Observabilidade de IA se conecta com [[01 - Foundations/Workflow agentic|Workflow agentic]], [[01 - Foundations/Tool Calling|Tool Calling]], [[06 - RAG and Memory/RAG|RAG]] e [[06 - RAG and Memory/MemÃ³ria|MemÃ³ria]].

## Ferramentas que usam isso
- [[11 - Observability/Langfuse|Langfuse]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]

## Exemplo prÃ¡tico
Um time pode usar [[11 - Observability/Langfuse|Langfuse]] para descobrir que uma etapa de recuperaÃ§Ã£o estÃ¡ trazendo documentos ruins e aumentando custo sem melhorar a resposta final.

## Minha interpretaÃ§Ã£o
Observabilidade de IA Ã© o que transforma experimentaÃ§Ã£o em operaÃ§Ã£o sÃ©ria. NÃ£o basta saber que a resposta saiu; Ã© preciso entender como ela foi produzida e onde pode quebrar.

