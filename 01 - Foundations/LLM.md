---
tipo: conceito
nome: LLM
categoria: foundations
tags: [conceito]
---

# LLM

## DefiniÃ§Ã£o
LLM significa "Large Language Model", ou modelo de linguagem de grande porte. Ã‰ um tipo de modelo treinado para prever e gerar texto com base em grandes volumes de dados e em padrÃµes estatÃ­sticos aprendidos.

## Por que isso importa
LLMs sÃ£o a base de grande parte da stack moderna de IA aplicada. Sem entender LLM, fica difÃ­cil entender ferramentas como [[03 - Agent Frameworks/LangChain|LangChain]], [[05 - Coding Agents/Claude Code|Claude Code]], [[05 - Coding Agents/Cursor|Cursor]] ou interfaces como [[04 - Chat Interfaces/LibreChat|LibreChat]].

## Como funciona
De forma simples, o modelo recebe um contexto de entrada, transforma isso em tokens e calcula qual token faz mais sentido vir em seguida.

- Ele nÃ£o "pensa" como uma pessoa.
- Ele opera por padrÃµes aprendidos durante o treinamento.
- O resultado final depende do contexto fornecido, da qualidade do modelo e da forma como a tarefa foi estruturada.

## RelaÃ§Ã£o com outras ideias
LLM se conecta diretamente com [[01 - Foundations/Contexto|Contexto]], [[01 - Foundations/Tool Calling|Tool Calling]], [[01 - Foundations/Agente|Agente]] e [[06 - RAG and Memory/RAG|RAG]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/Cursor|Cursor]]
- [[07 - Local AI/Ollama|Ollama]]

## Exemplo prÃ¡tico
Quando um usuÃ¡rio pede a [[05 - Coding Agents/Cursor|Cursor]] para alterar um arquivo em linguagem natural, o editor usa um LLM para interpretar o pedido, entender o cÃ³digo e propor a mudanÃ§a.

## Minha interpretaÃ§Ã£o
LLM Ã© o motor principal da stack, mas nÃ£o Ã© o sistema completo. O valor real aparece quando o modelo Ã© combinado com contexto, ferramentas, memÃ³ria e regras de execuÃ§Ã£o.

