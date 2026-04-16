---
tipo: conceito
nome: Observabilidade de IA
categoria: observability
tags: [conceito]
---

# Observabilidade de IA

## Definição
Observabilidade de IA é a capacidade de entender como um sistema com IA está se comportando em uso real, incluindo entradas, saídas, chamadas de ferramenta, custo, latência, falhas e qualidade percebida.

## Por que isso importa
Sistemas com IA podem parecer bons em testes manuais e falhar em produção de formas difíceis de enxergar. Sem observabilidade, o time opera no escuro.

## Como funciona
O sistema registra eventos relevantes ao longo da execução.

- Prompt ou entrada recebida.
- Contexto usado.
- Ferramentas chamadas.
- Tempo de resposta.
- Custo, erros e avaliação de qualidade.

## Relação com outras ideias
Observabilidade de IA se conecta com [[01 - Foundations/Workflow agentic|Workflow agentic]], [[01 - Foundations/Tool Calling|Tool Calling]], [[06 - RAG and Memory/RAG|RAG]] e [[06 - RAG and Memory/Memória|Memória]].

## Ferramentas que usam isso
- [[11 - Observability/Langfuse|Langfuse]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]

## Exemplo prático
Um time pode usar [[11 - Observability/Langfuse|Langfuse]] para descobrir que uma etapa de recuperação está trazendo documentos ruins e aumentando custo sem melhorar a resposta final.

## Minha interpretação
Observabilidade de IA é o que transforma experimentação em operação séria. Não basta saber que a resposta saiu; é preciso entender como ela foi produzida e onde pode quebrar.

