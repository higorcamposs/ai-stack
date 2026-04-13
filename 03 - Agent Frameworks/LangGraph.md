---
tipo: ferramenta
nome: LangGraph
categoria: agent framework
status: estudando
opensource: true
licenca: MIT
site: https://docs.langchain.com/oss/python/langgraph/
github: https://github.com/langchain-ai/langgraph
tags: [ferramenta]
---

# LangGraph

## O que é
LangGraph é um framework open source de orquestração para agentes e workflows com estado, baseado em grafos.

## Para que serve
Serve para modelar fluxos agentic e determinísticos com mais controle sobre etapas, transições, persistência e intervenção humana.

## Onde entra na stack
Entra na camada de orquestração de agentes, abaixo de abstrações mais prontas como [[03 - Agent Frameworks/LangChain|LangChain]] e perto de temas como memória, checkpoints e observabilidade.

## Quando faz sentido usar
- Quando o fluxo tem múltiplas etapas e bifurcações claras.
- Quando é preciso persistir estado e retomar execuções.
- Quando há necessidade de combinar regras fixas com decisões do modelo.

## Quando não faz sentido usar
- Quando um chat simples ou um agente básico já resolve.
- Quando o time ainda não entende bem o fluxo e precisa validar a ideia primeiro.
- Quando a prioridade é velocidade de protótipo, não controle.

## Pontos fortes
- Modelo mental forte para workflows complexos.
- Boa aderência a agentes com estado e longa duração.
- Permite explicitar melhor nós, transições e pontos de controle.
- É a base técnica de parte da experiência mais alta do ecossistema LangChain.

## Limitações
- Curva de aprendizagem maior do que frameworks mais diretos.
- Pode ser exagero para automações simples.
- Exige disciplina de modelagem para não virar um grafo difícil de manter.

## Alternativas
- [[03 - Agent Frameworks/LangChain|LangChain]]
- Workflows próprios com SDKs e filas
- [[08 - Automation and Workflows/n8n|n8n]] para automação mais operacional

## Ferramentas relacionadas
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[11 - Observability/Langfuse|Langfuse]]
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]

## Caso de uso real
Um agente de suporte técnico pode usar LangGraph para classificar a solicitação, consultar base interna, pedir aprovação humana em casos sensíveis e só então executar uma ação. O ganho está no controle do fluxo, não apenas na geração de texto.

## Minha leitura
LangGraph parece mais adequado quando a pergunta deixa de ser "como chamar um modelo" e passa a ser "como governar um sistema que usa modelo". É uma ferramenta de arquitetura, não só de produtividade.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
