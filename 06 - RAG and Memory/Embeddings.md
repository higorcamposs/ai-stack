---
tipo: conceito
nome: Embeddings
categoria: rag-memory
tags: [conceito]
---

# Embeddings

## Definição
Embeddings são representações numéricas de texto, imagem ou outro conteúdo em um espaço vetorial. Eles servem para comparar semelhança de significado entre itens.

## Por que isso importa
Sem embeddings, grande parte dos fluxos modernos de busca semântica e RAG não funciona da forma conhecida hoje. Eles permitem buscar por significado, não apenas por palavra exata.

## Como funciona
Um modelo de embedding transforma um texto em uma lista de números.

- Textos com significado parecido tendem a ficar próximos nesse espaço.
- O sistema compara vetores para achar itens relevantes.
- Essa comparação costuma alimentar a recuperação em um [[06 - RAG and Memory/Vector Database|vector database]].

## Relação com outras ideias
Embeddings são base de [[06 - RAG and Memory/RAG|RAG]], trabalham com [[06 - RAG and Memory/Vector Database|Vector Database]] e afetam a qualidade do [[01 - Foundations/Contexto|Contexto]] entregue ao modelo.

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[03 - Agent Frameworks/LangChain|LangChain]]

## Exemplo prático
Uma pergunta como "como pedir férias?" pode recuperar um documento chamado "política de ausência e descanso" mesmo sem repetir exatamente as mesmas palavras.

## Minha interpretação
Embeddings são uma forma prática de aproximar significado por distância matemática. Eles não entendem o texto como uma pessoa entende, mas são muito úteis para busca e recuperação.

