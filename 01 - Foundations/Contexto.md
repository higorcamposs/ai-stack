---
tipo: conceito
nome: Contexto
categoria: foundations
tags: [conceito]
---

# Contexto

## Definição
Contexto é o conjunto de informações disponíveis para o modelo no momento da execução. Pode incluir instruções, histórico da conversa, documentos, estado da tarefa, memória e saída de ferramentas.

## Por que isso importa
Boa parte da qualidade de um sistema com IA depende mais do contexto certo do que de um modelo supostamente mais forte. Isso aparece em [[06 - RAG and Memory/LlamaIndex|LlamaIndex]], [[05 - Coding Agents/Claude Code|Claude Code]] e [[04 - Chat Interfaces/Open WebUI|Open WebUI]].

## Como funciona
O contexto é montado antes da chamada ao modelo.

- Parte dele vem do usuário.
- Parte vem do sistema e das instruções.
- Parte pode vir de busca, memória, arquivos ou ferramentas.
- Tudo isso entra na janela de contexto que o modelo consegue processar.

## Relação com outras ideias
Contexto está ligado a [[01 - Foundations/LLM|LLM]], [[06 - RAG and Memory/RAG|RAG]], [[06 - RAG and Memory/Memória|Memória]] e [[06 - RAG and Memory/Embeddings|Embeddings]].

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[05 - Coding Agents/Cursor|Cursor]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]

## Exemplo prático
Quando um agente de código lê arquivos do repositório antes de propor uma alteração, ele está ampliando o contexto disponível para responder melhor.

## Minha interpretação
Contexto é a matéria-prima imediata do raciocínio do sistema. Se ele está incompleto, confuso ou excessivo, o resultado tende a piorar.

