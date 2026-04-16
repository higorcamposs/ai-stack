---
tipo: conceito
nome: Tool Calling
categoria: foundations
tags: [conceito]
---

# Tool Calling

## Definição
Tool Calling é a capacidade de um sistema com modelo escolher e chamar ferramentas externas, como funções, APIs, banco de dados ou comandos.

## Por que isso importa
Sem tool calling, o modelo fica restrito ao que consegue responder só com texto. Com ferramentas, ele pode buscar dados, executar ações e produzir resultados mais úteis no mundo real.

## Como funciona
O sistema descreve quais ferramentas estão disponíveis e o modelo indica quando uma delas deve ser usada.

- A ferramenta é registrada com nome e parâmetros.
- O modelo decide se deve chamá-la.
- O sistema executa a chamada.
- O resultado volta ao modelo ou ao fluxo.

## Relação com outras ideias
Tool Calling é parte importante de [[01 - Foundations/Agente|Agente]], conversa com [[12 - Protocols and Standards/MCP|MCP]] e costuma aparecer em [[01 - Foundations/Workflow agentic|Workflow agentic]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/OpenHands|OpenHands]]

## Exemplo prático
Um agente pode chamar uma ferramenta de busca em documentos, depois uma API interna e por fim registrar o resultado em um sistema de ticket.

## Minha interpretação
Tool Calling é uma das pontes entre linguagem e ação. É o que transforma um modelo de texto em um componente operacional de sistema.

