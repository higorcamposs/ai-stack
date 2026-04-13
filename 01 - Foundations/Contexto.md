---
tipo: conceito
nome: Contexto
categoria: foundations
tags: [conceito]
---

# Contexto

## DefiniÃ§Ã£o
Contexto Ã© o conjunto de informaÃ§Ãµes disponÃ­veis para o modelo no momento da execuÃ§Ã£o. Pode incluir instruÃ§Ãµes, histÃ³rico da conversa, documentos, estado da tarefa, memÃ³ria e saÃ­da de ferramentas.

## Por que isso importa
Boa parte da qualidade de um sistema com IA depende mais do contexto certo do que de um modelo supostamente mais forte. Isso aparece em [[06 - RAG and Memory/LlamaIndex|LlamaIndex]], [[05 - Coding Agents/Claude Code|Claude Code]] e [[04 - Chat Interfaces/Open WebUI|Open WebUI]].

## Como funciona
O contexto Ã© montado antes da chamada ao modelo.

- Parte dele vem do usuÃ¡rio.
- Parte vem do sistema e das instruÃ§Ãµes.
- Parte pode vir de busca, memÃ³ria, arquivos ou ferramentas.
- Tudo isso entra na janela de contexto que o modelo consegue processar.

## RelaÃ§Ã£o com outras ideias
Contexto estÃ¡ ligado a [[01 - Foundations/LLM|LLM]], [[06 - RAG and Memory/RAG|RAG]], [[06 - RAG and Memory/MemÃ³ria|MemÃ³ria]] e [[06 - RAG and Memory/Embeddings|Embeddings]].

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[05 - Coding Agents/Cursor|Cursor]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]

## Exemplo prÃ¡tico
Quando um agente de cÃ³digo lÃª arquivos do repositÃ³rio antes de propor uma alteraÃ§Ã£o, ele estÃ¡ ampliando o contexto disponÃ­vel para responder melhor.

## Minha interpretaÃ§Ã£o
Contexto Ã© a matÃ©ria-prima imediata do raciocÃ­nio do sistema. Se ele estÃ¡ incompleto, confuso ou excessivo, o resultado tende a piorar.

