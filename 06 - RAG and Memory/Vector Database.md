---
tipo: conceito
nome: Vector Database
categoria: rag-memory
tags: [conceito]
---

# Vector Database

## DefiniÃ§Ã£o
Vector Database Ã© um banco ou sistema especializado em armazenar vetores e consultar itens semelhantes com eficiÃªncia, geralmente usado para busca semÃ¢ntica.

## Por que isso importa
Ele Ã© uma peÃ§a recorrente em arquiteturas de [[06 - RAG and Memory/RAG|RAG]], porque ajuda a recuperar trechos relevantes a partir de [[06 - RAG and Memory/Embeddings|embeddings]].

## Como funciona
Os conteÃºdos sÃ£o convertidos em vetores e armazenados com seus metadados.

- Uma pergunta tambÃ©m pode ser transformada em vetor.
- O sistema calcula quais itens estÃ£o mais prÃ³ximos.
- Os resultados retornam com filtros e metadados para compor o contexto.

## RelaÃ§Ã£o com outras ideias
Vector Database depende de [[06 - RAG and Memory/Embeddings|Embeddings]], serve a [[06 - RAG and Memory/RAG|RAG]] e ajuda a montar [[01 - Foundations/Contexto|Contexto]] para o modelo.

## Ferramentas que usam isso
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]

## Exemplo prÃ¡tico
Uma base com milhares de pÃ¡ginas pode ser indexada em um banco vetorial para que o sistema encontre rapidamente os trechos mais prÃ³ximos de uma pergunta do usuÃ¡rio.

## Minha interpretaÃ§Ã£o
Vector Database nÃ£o Ã© sinÃ´nimo de RAG. Ele resolve armazenamento e busca vetorial; a qualidade do sistema depende tambÃ©m de indexaÃ§Ã£o, chunking, filtros, re-ranking e uso correto do contexto.

