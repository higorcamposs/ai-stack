---
tipo: conceito
nome: Vector Database
categoria: rag-memory
tags: [conceito]
---

# Vector Database

## Definição
Vector Database é um banco ou sistema especializado em armazenar vetores e consultar itens semelhantes com eficiência, geralmente usado para busca semântica.

## Por que isso importa
Ele é uma peça recorrente em arquiteturas de [[06 - RAG and Memory/RAG|RAG]], porque ajuda a recuperar trechos relevantes a partir de [[06 - RAG and Memory/Embeddings|embeddings]].

## Como funciona
Os conteúdos são convertidos em vetores e armazenados com seus metadados.

- Uma pergunta também pode ser transformada em vetor.
- O sistema calcula quais itens estão mais próximos.
- Os resultados retornam com filtros e metadados para compor o contexto.

## Relação com outras ideias
Vector Database depende de [[06 - RAG and Memory/Embeddings|Embeddings]], serve a [[06 - RAG and Memory/RAG|RAG]] e ajuda a montar [[01 - Foundations/Contexto|Contexto]] para o modelo.

## Ferramentas que usam isso
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]

## Exemplo prático
Uma base com milhares de páginas pode ser indexada em um banco vetorial para que o sistema encontre rapidamente os trechos mais próximos de uma pergunta do usuário.

## Minha interpretação
Vector Database não é sinônimo de RAG. Ele resolve armazenamento e busca vetorial; a qualidade do sistema depende também de indexação, chunking, filtros, re-ranking e uso correto do contexto.

