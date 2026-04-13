---
tipo: caso_real
tags: [caso_real]
---

# Assistente corporativo com LibreChat + MCP

## Cenário
Uma empresa quer oferecer um assistente interno para consultar políticas, documentos e sistemas corporativos sem depender de várias interfaces separadas.

## Problema
O conhecimento está fragmentado entre documentos, bases internas e APIs. O usuário perde tempo procurando informação e alternando ferramentas.

## Ferramentas envolvidas
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- [[12 - Protocols and Standards/MCP|MCP]]
- [[01 - Foundations/Contexto|Contexto]]
- [[01 - Foundations/Tool Calling|Tool Calling]]

## Arquitetura sugerida
- LibreChat como interface única para os usuários
- servidores MCP expondo acesso padronizado a documentos, APIs e recursos internos
- camada de autenticação corporativa e auditoria
- opcionalmente uma base de [[06 - RAG and Memory/RAG|RAG]] para documentos de consulta frequente

## Fluxo
1. O usuário faz uma pergunta na interface.
2. O sistema decide se basta responder com o contexto atual ou se precisa buscar dados.
3. O LibreChat usa recursos e ferramentas expostos por MCP.
4. A resposta volta ao usuário com base em dados corporativos atualizados.

## Benefícios
- reduz dispersão de conhecimento
- cria uma porta de entrada única para informação corporativa
- melhora governança em comparação com integrações ad hoc

## Riscos
- se o controle de permissões estiver fraco, o assistente pode expor dados indevidos
- sem curadoria de contexto, a resposta pode parecer confiante demais com base insuficiente
- a qualidade depende da organização dos recursos expostos por MCP

## Como eu aplicaria
Eu começaria com um escopo limitado: RH, políticas internas e perguntas operacionais recorrentes. Só depois expandiria para sistemas mais sensíveis. O ponto principal é tratar o assistente como camada de acesso controlado, não como atalho para abrir tudo.
