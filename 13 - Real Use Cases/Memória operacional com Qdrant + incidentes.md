---
tipo: caso_real
tags: [caso_real]
---

# Memória operacional com Qdrant + incidentes

## Cenário
Uma equipe de operações quer reaproveitar incidentes passados para responder mais rápido a falhas recorrentes.

## Problema
Muito conhecimento operacional fica perdido em tickets, chats, postmortems e documentos soltos. A cada incidente, a equipe reaprende o que já sabia.

## Ferramentas envolvidas
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[06 - RAG and Memory/Embeddings|Embeddings]]
- [[06 - RAG and Memory/Vector Database|Vector Database]]
- [[06 - RAG and Memory/RAG|RAG]]
- [[06 - RAG and Memory/Memória|Memória]]

## Arquitetura sugerida
- pipeline de ingestão de incidentes, postmortems e runbooks
- geração de embeddings por item ou trecho
- armazenamento vetorial no Qdrant
- interface de busca ou assistente para recuperar incidentes semelhantes

## Fluxo
1. Incidentes resolvidos são convertidos em registros estruturados.
2. O conteúdo é vetorizado e armazenado no Qdrant.
3. Diante de um novo incidente, o sistema busca casos semelhantes.
4. A equipe recebe contexto, soluções anteriores e alertas de risco.

## Benefícios
- acelera diagnóstico
- reaproveita conhecimento operacional existente
- melhora consistência entre equipes e turnos

## Riscos
- incidentes mal documentados geram recuperação ruim
- embeddings ruins levam a associações fracas ou enganosas
- buscar incidentes similares não substitui julgamento técnico no caso atual

## Como eu aplicaria
Eu começaria com postmortems e runbooks de maior valor, não com todo o histórico bruto. A memória operacional precisa de curadoria, senão vira acúmulo vetorizado de ruído.
