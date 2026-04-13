---
tipo: caso_real
tags: [caso_real]
---

# RAG para documentação técnica

## Cenário
Uma organização quer responder perguntas sobre documentação técnica, runbooks, APIs e procedimentos internos.

## Problema
A documentação existe, mas está dispersa, grande demais ou difícil de consultar rapidamente. A busca tradicional não encontra bem por significado.

## Ferramentas envolvidas
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[06 - RAG and Memory/RAG|RAG]]
- [[06 - RAG and Memory/Embeddings|Embeddings]]
- [[06 - RAG and Memory/Vector Database|Vector Database]]

## Arquitetura sugerida
- pipeline de ingestão e limpeza de documentos
- chunking e geração de embeddings
- armazenamento vetorial em Qdrant
- orquestração de recuperação com LlamaIndex
- interface de chat ou API para consulta

## Fluxo
1. A documentação é preparada e indexada.
2. A pergunta do usuário é transformada em consulta semântica.
3. O sistema recupera trechos relevantes.
4. O modelo responde com base no contexto recuperado.

## Benefícios
- melhora acesso a conhecimento técnico
- reduz tempo gasto procurando documentação
- cria uma camada de consulta mais natural sobre base existente

## Riscos
- se a base estiver desatualizada, o sistema amplifica documento ruim
- chunking inadequado reduz qualidade da recuperação
- respostas convincentes podem esconder recuperação fraca

## Como eu aplicaria
Eu começaria com um subconjunto de documentação de alta qualidade e alto uso. RAG funciona melhor quando a base é curada, recente e relativamente confiável.
