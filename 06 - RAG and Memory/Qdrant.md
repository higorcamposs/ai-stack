---
tipo: ferramenta
nome: Qdrant
categoria: banco vetorial
status: estudando
opensource: true
licenca: Apache-2.0
site: https://qdrant.tech
github: https://github.com/qdrant/qdrant
tags: [ferramenta]
---

# Qdrant

## O que é
Qdrant é um banco vetorial open source focado em busca por similaridade e recuperação semântica em aplicações de IA.

## Para que serve
Serve para armazenar embeddings e consultar itens semanticamente próximos, algo central em muitos fluxos de RAG.

## Onde entra na stack
Entra na camada de recuperação e memória de longo prazo, ao lado de frameworks como [[06 - RAG and Memory/LlamaIndex|LlamaIndex]].

## Quando faz sentido usar
- Quando a aplicação precisa de busca semântica sobre muitos itens.
- Quando embeddings são parte importante da arquitetura.
- Quando há necessidade de banco vetorial dedicado em vez de adaptação de banco genérico.

## Quando não faz sentido usar
- Quando o volume e a complexidade ainda não justificam um banco vetorial.
- Quando busca lexical simples já resolve.
- Quando o pipeline de dados ainda está mal definido.

## Pontos fortes
- Ferramenta especializada para vetor search.
- Boa adoção no ecossistema de IA aplicada.
- Forte encaixe em pipelines de RAG e recomendação.

## Limitações
- Banco vetorial sozinho não resolve qualidade de RAG.
- A performance percebida depende de embeddings, chunking e estratégia de recuperação.
- Exige pensar também em re-ranking, filtros e avaliação.

## Alternativas
- Pinecone
- Weaviate
- PostgreSQL com extensões vetoriais

## Ferramentas relacionadas
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[11 - Observability/Langfuse|Langfuse]]

## Caso de uso real
Uma base de documentação técnica pode ser vetorizada e consultada por um agente interno. Qdrant entra como camada de recuperação, enquanto o restante do sistema cuida de chunking, ranking e resposta final.

## Minha leitura
Qdrant é importante para estudar infraestrutura de RAG sem cair na abstração excessiva de "RAG mágico". Ele ajuda a separar armazenamento vetorial de estratégia de recuperação.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
