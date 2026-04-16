---
tipo: conceito
nome: Agente
categoria: foundations
tags: [conceito]
---

# Agente

## Definição
Um agente é um sistema que usa um modelo para decidir os próximos passos, chamar ferramentas, consultar o contexto e executar ações em direção a um objetivo.

## Por que isso importa
A ideia de agente ajuda a distinguir um chat passivo de um sistema que age. Isso é central para entender [[03 - Agent Frameworks/LangGraph|LangGraph]], [[05 - Coding Agents/OpenHands|OpenHands]] e [[08 - Automation and Workflows/OpenClaw|OpenClaw]].

## Como funciona
Em geral, um agente recebe um objetivo, interpreta o estado atual, decide o próximo passo e pode repetir esse ciclo.

- Recebe contexto e instruções.
- Avalia opções ou regras.
- Usa ferramentas quando necessário.
- Atualiza estado ou memória.
- Entrega um resultado ou toma uma ação.

## Relação com outras ideias
Agente depende de [[01 - Foundations/LLM|LLM]], costuma usar [[01 - Foundations/Tool Calling|Tool Calling]], pode operar com [[06 - RAG and Memory/Memória|Memória]] e frequentemente é organizado como [[01 - Foundations/Workflow agentic|Workflow agentic]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[05 - Coding Agents/OpenHands|OpenHands]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]

## Exemplo prático
Um agente de suporte pode classificar uma dúvida, buscar documentação, pedir confirmação humana em casos sensíveis e então responder ou acionar uma automação.

## Minha interpretação
Agente não é apenas "chat com nome bonito". A diferença real está em perceber, decidir e agir com algum grau de autonomia dentro de limites definidos.
