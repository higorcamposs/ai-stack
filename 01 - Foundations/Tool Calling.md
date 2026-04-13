---
tipo: conceito
nome: Tool Calling
categoria: foundations
tags: [conceito]
---

# Tool Calling

## DefiniÃ§Ã£o
Tool Calling Ã© a capacidade de um sistema com modelo escolher e chamar ferramentas externas, como funÃ§Ãµes, APIs, banco de dados ou comandos.

## Por que isso importa
Sem tool calling, o modelo fica restrito ao que consegue responder sÃ³ com texto. Com ferramentas, ele pode buscar dados, executar aÃ§Ãµes e produzir resultados mais Ãºteis no mundo real.

## Como funciona
O sistema descreve quais ferramentas estÃ£o disponÃ­veis e o modelo indica quando uma delas deve ser usada.

- A ferramenta Ã© registrada com nome e parÃ¢metros.
- O modelo decide se deve chamÃ¡-la.
- O sistema executa a chamada.
- O resultado volta ao modelo ou ao fluxo.

## RelaÃ§Ã£o com outras ideias
Tool Calling Ã© parte importante de [[01 - Foundations/Agente|Agente]], conversa com [[12 - Protocols and Standards/MCP|MCP]] e costuma aparecer em [[01 - Foundations/Workflow agentic|Workflow agentic]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/OpenHands|OpenHands]]

## Exemplo prÃ¡tico
Um agente pode chamar uma ferramenta de busca em documentos, depois uma API interna e por fim registrar o resultado em um sistema de ticket.

## Minha interpretaÃ§Ã£o
Tool Calling Ã© uma das pontes entre linguagem e aÃ§Ã£o. Ã‰ o que transforma um modelo de texto em um componente operacional de sistema.

