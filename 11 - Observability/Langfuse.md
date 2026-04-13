---
tipo: ferramenta
nome: Langfuse
categoria: observabilidade
status: estudando
opensource: true
licenca: fonte disponivel; confirmar detalhes da licenca em uso antes de adocao
site: https://langfuse.com
github: https://github.com/langfuse/langfuse
tags: [ferramenta]
---

# Langfuse

## O que é
Langfuse é uma plataforma para observabilidade e engenharia de aplicações com LLM, cobrindo tracing, métricas, prompts, datasets e avaliação.

## Para que serve
Serve para enxergar o que acontece em sistemas com IA, depurar fluxos, comparar versões e melhorar qualidade com base em dados.

## Onde entra na stack
Entra na camada de observabilidade, acompanhando aplicações construídas com [[03 - Agent Frameworks/LangChain|LangChain]], [[03 - Agent Frameworks/LangGraph|LangGraph]], [[06 - RAG and Memory/LlamaIndex|LlamaIndex]] e afins.

## Quando faz sentido usar
- Quando o sistema com IA já está indo além de testes manuais.
- Quando é preciso medir qualidade, custo, latência e comportamento.
- Quando prompts, traces e avaliações precisam ser versionados ou comparados.

## Quando não faz sentido usar
- Quando ainda não existe sistema para observar.
- Quando o projeto está em fase muito inicial e o custo de instrumentação é alto demais.
- Quando o time não pretende agir sobre as métricas coletadas.

## Pontos fortes
- Ajuda a tornar sistemas com IA menos opacos.
- Conecta tracing, avaliação e métricas em uma mesma camada.
- Forte relevância para passagem de protótipo para produção.

## Limitações
- Observabilidade sem disciplina de análise vira só coleta de dados.
- É preciso confirmar detalhes atuais de licenciamento e oferta antes de adoção em ambiente sensível.
- Instrumentar bem exige modelar eventos e objetivos com clareza.

## Alternativas
- LangSmith
- Helicone
- Instrumentação própria com OpenTelemetry e dashboards

## Ferramentas relacionadas
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]

## Caso de uso real
Um time que opera RAG em produção pode usar Langfuse para rastrear consultas, latência, custo por chamada e exemplos de falha, reduzindo decisões baseadas apenas em impressão subjetiva.

## Minha leitura
Langfuse representa a maturidade da stack. Ele entra quando a pergunta deixa de ser "funciona?" e passa a ser "como sabemos que funciona bem, quanto custa e onde quebra?".

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
