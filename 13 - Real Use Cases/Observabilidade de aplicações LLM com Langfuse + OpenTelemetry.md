---
tipo: caso_real
tags: [caso_real]
---

# Observabilidade de aplicações LLM com Langfuse + OpenTelemetry

## Cenário
Um time já opera aplicações com LLM e precisa entender custo, latência, falhas e qualidade de forma contínua.

## Problema
Sem rastreamento estruturado, é difícil saber por que uma resposta falhou, qual etapa encareceu o sistema ou onde o contexto se perdeu.

## Ferramentas envolvidas
- [[11 - Observability/Langfuse|Langfuse]]
- [[11 - Observability/Observabilidade de IA|Observabilidade de IA]]
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[06 - RAG and Memory/RAG|RAG]]

## Arquitetura sugerida
- aplicação LLM instrumentada com tracing
- Langfuse para capturar prompts, contexto, custo e outputs
- OpenTelemetry para integrar observabilidade de aplicação, infraestrutura e fluxos de IA
- dashboards e alertas sobre falhas e regressões

## Fluxo
1. A aplicação recebe uma solicitação.
2. Cada etapa relevante é rastreada.
3. O Langfuse registra informações específicas de IA.
4. O OpenTelemetry ajuda a conectar isso com o restante da observabilidade do sistema.

## Benefícios
- melhora depuração e análise de regressão
- permite relacionar custo, latência e qualidade
- reduz decisões baseadas só em percepção subjetiva

## Riscos
- instrumentação ruim gera ruído demais
- excesso de coleta sem análise prática vira custo sem retorno
- dados sensíveis precisam de cuidado em logs e traces

## Como eu aplicaria
Eu começaria rastreando apenas os pontos críticos: entrada, recuperação, chamada de modelo, ferramenta e saída. Observabilidade boa nasce de hipóteses claras, não de coleta indiscriminada.
