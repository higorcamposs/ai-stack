---
tipo: conceito
nome: RAG
categoria: rag-memory
tags: [conceito]
---

# RAG

## Definição
RAG significa "Retrieval-Augmented Generation". É uma abordagem em que o sistema busca informações relevantes fora do modelo e usa esse material como contexto antes de gerar a resposta.

## Por que isso importa
RAG ajuda a responder com base em dados mais atualizados, específicos e controláveis. Isso é central para sistemas que trabalham com documentação, políticas internas, bases de conhecimento e arquivos.

## Como funciona
O fluxo mais comum tem algumas etapas.

- Os dados são preparados e divididos em partes.
- Essas partes podem ser transformadas em [[06 - RAG and Memory/Embeddings|embeddings]].
- O sistema busca os trechos mais relevantes em um [[06 - RAG and Memory/Vector Database|vector database]].
- Os trechos encontrados entram no [[01 - Foundations/Contexto|contexto]] do modelo.
- O modelo gera a resposta com base no material recuperado.

## Relação com outras ideias
RAG depende de [[06 - RAG and Memory/Embeddings|Embeddings]], [[06 - RAG and Memory/Vector Database|Vector Database]], [[01 - Foundations/Contexto|Contexto]] e muitas vezes se combina com [[06 - RAG and Memory/Memória|Memória]].

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[11 - Observability/Langfuse|Langfuse]]

## Exemplo prático
Um assistente interno pode buscar políticas da empresa em uma base vetorial antes de responder uma pergunta sobre reembolso, em vez de confiar apenas no conhecimento geral do modelo.

## Minha interpretação
RAG não é um recurso isolado, e sim uma arquitetura de contexto. Ele funciona bem quando a recuperação é boa; quando a busca falha, a resposta final também tende a falhar.

