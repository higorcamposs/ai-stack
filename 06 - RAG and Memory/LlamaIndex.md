---
tipo: ferramenta
nome: LlamaIndex
categoria: rag e dados
status: estudando
opensource: true
licenca: MIT
site: https://docs.llamaindex.ai
github: https://github.com/run-llama/llama_index
tags: [ferramenta]
---

# LlamaIndex

## O que é
LlamaIndex é um framework open source voltado para construir aplicações com LLMs sobre dados próprios, com forte foco em ingestão, indexação, recuperação e workflows sobre contexto.

## Para que serve
Serve para conectar documentos, bancos, APIs e outras fontes de conhecimento a aplicações com LLM, especialmente em cenários de RAG.

## Onde entra na stack
Entra na camada de [[06 - RAG and Memory/Qdrant|RAG e memória]], entre a fonte de dados e a aplicação que consulta ou raciocina sobre esse contexto.

## Quando faz sentido usar
- Quando o núcleo do problema é consultar dados próprios.
- Quando há diferentes fontes e formatos de documento.
- Quando o projeto precisa evoluir de busca simples para pipelines mais compostos.

## Quando não faz sentido usar
- Quando não existe base de dados ou corpus relevante.
- Quando um pipeline de busca muito simples resolve.
- Quando o time quer minimizar dependências e controlar cada etapa manualmente.

## Pontos fortes
- Forte encaixe em cenários de RAG.
- Boa coleção de conectores, readers e integrações.
- Ajuda a estruturar ingestão e recuperação sem reinventar tudo.
- Conversa bem com bancos vetoriais como [[06 - RAG and Memory/Qdrant|Qdrant]].

## Limitações
- Pode gerar sensação de caixa-preta se o time não dominar o pipeline.
- Nem todo caso de RAG precisa do framework completo.
- A linha entre framework de dados e framework de agentes pode exigir leitura cuidadosa da documentação.

## Alternativas
- [[03 - Agent Frameworks/LangChain|LangChain]]
- Pipelines próprios de ingestão e busca
- Soluções gerenciadas de busca e indexação

## Ferramentas relacionadas
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[07 - Local AI/Ollama|Ollama]]
- [[11 - Observability/Langfuse|Langfuse]]

## Caso de uso real
Uma equipe pode usar LlamaIndex para indexar políticas internas, contratos e documentação operacional, permitindo perguntas com base em conteúdo da empresa. O valor aumenta quando é preciso atualizar a base com frequência e preservar rastreabilidade do pipeline.

## Minha leitura
LlamaIndex parece mais centrado no problema de contexto e dados do que no problema completo de agent orchestration. Para estudar RAG de forma séria, é uma referência importante.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
