---
tipo: conceito
nome: RAG
categoria: rag-memory
tags: [conceito]
---

# RAG

## DefiniÃ§Ã£o
RAG significa "Retrieval-Augmented Generation". Ã‰ uma abordagem em que o sistema busca informaÃ§Ãµes relevantes fora do modelo e usa esse material como contexto antes de gerar a resposta.

## Por que isso importa
RAG ajuda a responder com base em dados mais atualizados, especÃ­ficos e controlÃ¡veis. Isso Ã© central para sistemas que trabalham com documentaÃ§Ã£o, polÃ­ticas internas, bases de conhecimento e arquivos.

## Como funciona
O fluxo mais comum tem algumas etapas.

- Os dados sÃ£o preparados e divididos em partes.
- Essas partes podem ser transformadas em [[06 - RAG and Memory/Embeddings|embeddings]].
- O sistema busca os trechos mais relevantes em um [[06 - RAG and Memory/Vector Database|vector database]].
- Os trechos encontrados entram no [[01 - Foundations/Contexto|contexto]] do modelo.
- O modelo gera a resposta com base no material recuperado.

## RelaÃ§Ã£o com outras ideias
RAG depende de [[06 - RAG and Memory/Embeddings|Embeddings]], [[06 - RAG and Memory/Vector Database|Vector Database]], [[01 - Foundations/Contexto|Contexto]] e muitas vezes se combina com [[06 - RAG and Memory/MemÃ³ria|MemÃ³ria]].

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[11 - Observability/Langfuse|Langfuse]]

## Exemplo prÃ¡tico
Um assistente interno pode buscar polÃ­ticas da empresa em uma base vetorial antes de responder uma pergunta sobre reembolso, em vez de confiar apenas no conhecimento geral do modelo.

## Minha interpretaÃ§Ã£o
RAG nÃ£o Ã© um recurso isolado, e sim uma arquitetura de contexto. Ele funciona bem quando a recuperaÃ§Ã£o Ã© boa; quando a busca falha, a resposta final tambÃ©m tende a falhar.

