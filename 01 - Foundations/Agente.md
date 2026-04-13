---
tipo: conceito
nome: Agente
categoria: foundations
tags: [conceito]
---

# Agente

## DefiniÃ§Ã£o
Um agente Ã© um sistema que usa um modelo para decidir passos, chamar ferramentas, consultar contexto e executar aÃ§Ãµes em direÃ§Ã£o a um objetivo.

## Por que isso importa
A ideia de agente ajuda a distinguir um chat passivo de um sistema que age. Isso Ã© central para entender [[03 - Agent Frameworks/LangGraph|LangGraph]], [[05 - Coding Agents/OpenHands|OpenHands]] e [[08 - Automation and Workflows/OpenClaw|OpenClaw]].

## Como funciona
Em geral, um agente recebe um objetivo, interpreta o estado atual, decide o prÃ³ximo passo e pode repetir esse ciclo.

- Recebe contexto e instruÃ§Ãµes.
- Avalia opÃ§Ãµes ou regras.
- Usa ferramentas quando necessÃ¡rio.
- Atualiza estado ou memÃ³ria.
- Entrega um resultado ou toma uma aÃ§Ã£o.

## RelaÃ§Ã£o com outras ideias
Agente depende de [[01 - Foundations/LLM|LLM]], costuma usar [[01 - Foundations/Tool Calling|Tool Calling]], pode operar com [[06 - RAG and Memory/MemÃ³ria|MemÃ³ria]] e frequentemente Ã© organizado como [[01 - Foundations/Workflow agentic|Workflow agentic]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[05 - Coding Agents/OpenHands|OpenHands]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]

## Exemplo prÃ¡tico
Um agente de suporte pode classificar uma dÃºvida, buscar documentaÃ§Ã£o, pedir confirmaÃ§Ã£o humana em casos sensÃ­veis e entÃ£o responder ou acionar uma automaÃ§Ã£o.

## Minha interpretaÃ§Ã£o
Agente nÃ£o Ã© apenas "chat com nome bonito". A diferenÃ§a real estÃ¡ em perceber, decidir e agir com algum grau de autonomia dentro de limites definidos.

