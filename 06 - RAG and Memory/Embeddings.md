---
tipo: conceito
nome: Embeddings
categoria: rag-memory
tags: [conceito]
---

# Embeddings

## DefiniÃ§Ã£o
Embeddings sÃ£o representaÃ§Ãµes numÃ©ricas de texto, imagem ou outro conteÃºdo em um espaÃ§o vetorial. Eles servem para comparar semelhanÃ§a de significado entre itens.

## Por que isso importa
Sem embeddings, grande parte dos fluxos modernos de busca semÃ¢ntica e RAG nÃ£o funciona da forma conhecida hoje. Eles permitem buscar por significado, nÃ£o apenas por palavra exata.

## Como funciona
Um modelo de embedding transforma um texto em uma lista de nÃºmeros.

- Textos com significado parecido tendem a ficar prÃ³ximos nesse espaÃ§o.
- O sistema compara vetores para achar itens relevantes.
- Essa comparaÃ§Ã£o costuma alimentar a recuperaÃ§Ã£o em um [[06 - RAG and Memory/Vector Database|vector database]].

## RelaÃ§Ã£o com outras ideias
Embeddings sÃ£o base de [[06 - RAG and Memory/RAG|RAG]], trabalham com [[06 - RAG and Memory/Vector Database|Vector Database]] e afetam a qualidade do [[01 - Foundations/Contexto|Contexto]] entregue ao modelo.

## Ferramentas que usam isso
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[03 - Agent Frameworks/LangChain|LangChain]]

## Exemplo prÃ¡tico
Uma pergunta como "como pedir fÃ©rias?" pode recuperar um documento chamado "polÃ­tica de ausÃªncia e descanso" mesmo sem repetir exatamente as mesmas palavras.

## Minha interpretaÃ§Ã£o
Embeddings sÃ£o uma forma prÃ¡tica de aproximar significado por distÃ¢ncia matemÃ¡tica. Eles nÃ£o entendem o texto como uma pessoa entende, mas sÃ£o muito Ãºteis para busca e recuperaÃ§Ã£o.

