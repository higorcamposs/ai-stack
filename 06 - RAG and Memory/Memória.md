---
tipo: conceito
nome: Memória
categoria: rag-memory
tags: [conceito]
---

# Memória

## Definição
Memória é qualquer mecanismo usado para preservar informações relevantes além de uma única resposta imediata. Pode ser memória de sessão, memória persistente, histórico resumido ou estado estruturado.

## Por que isso importa
Sem memória, muitos sistemas com IA recomeçam do zero a cada interação. Com memória, eles podem manter continuidade, personalização e rastreabilidade.

## Como funciona
Memória pode aparecer de várias formas.

- Histórico de conversa mantido no contexto.
- Resumos de interações anteriores.
- Dados persistidos em banco.
- Estado de workflow usado por um agente.

## Relação com outras ideias
Memória conversa com [[01 - Foundations/Contexto|Contexto]], [[01 - Foundations/Agente|Agente]], [[06 - RAG and Memory/RAG|RAG]] e [[01 - Foundations/Workflow agentic|Workflow agentic]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]

## Exemplo prático
Um assistente pessoal pode lembrar preferências do usuário, projetos ativos ou resumos de interações anteriores para não repetir sempre as mesmas perguntas.

## Minha interpretação
Memória é menos sobre "lembrar tudo" e mais sobre decidir o que vale manter. Memória sem critério pode piorar o sistema em vez de ajudar.

