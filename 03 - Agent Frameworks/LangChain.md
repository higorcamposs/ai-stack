---
tipo: ferramenta
nome: LangChain
categoria: agent framework
status: estudando
opensource: true
licenca: MIT
site: https://www.langchain.com
github: https://github.com/langchain-ai/langchain
tags: [ferramenta]
---

# LangChain

## O que é
LangChain é um framework open source para construir aplicações com LLMs e agentes com uma interface padronizada para modelos, ferramentas, memória e integrações.

## Para que serve
Serve para acelerar a criação de aplicações com IA que precisam chamar modelos, usar ferramentas, estruturar prompts e conectar componentes externos sem começar do zero.

## Onde entra na stack
Entra principalmente em [[03 - Agent Frameworks/LangGraph|LangGraph]], [[03 - Agent Frameworks/LangChain|LangChain]], [[06 - RAG and Memory/LlamaIndex|LlamaIndex]] e [[08 - Automation and Workflows/n8n|n8n]] quando a camada de aplicação precisa orquestrar chamadas de modelo e uso de ferramentas.

## Quando faz sentido usar
- Quando o time quer montar um agente ou app com LLM rapidamente.
- Quando é importante trocar de provedor de modelo sem reescrever tudo.
- Quando o projeto precisa de muitas integrações já prontas.

## Quando não faz sentido usar
- Quando o fluxo é muito simples e um SDK direto do provedor resolve.
- Quando o time quer controle fino de latência e execução em baixo nível.
- Quando a complexidade do framework pode custar mais do que ajudar.

## Pontos fortes
- Ecossistema amplo e documentação extensa.
- Interface comum para múltiplos provedores e ferramentas.
- Bom ponto de partida para protótipos e aplicações em evolução.
- Hoje está claramente conectado ao runtime do [[03 - Agent Frameworks/LangGraph|LangGraph]].

## Limitações
- Pode introduzir abstrações demais para casos simples.
- Mudanças de API e reposicionamento do produto exigem atenção.
- Em projetos críticos, é preciso avaliar com cuidado quanto da stack realmente depende do framework.

## Alternativas
- [[06 - RAG and Memory/LlamaIndex|LlamaIndex]]
- SDKs diretos de provedores
- [[03 - Agent Frameworks/LangGraph|LangGraph]] para controle mais explícito

## Ferramentas relacionadas
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[11 - Observability/Langfuse|Langfuse]]

## Caso de uso real
Um time pode usar LangChain para criar um assistente interno que consulta documentação, chama APIs internas e registra traces em [[11 - Observability/Langfuse|Langfuse]]. O valor aparece quando há integração com várias fontes e troca frequente de modelos.

## Minha leitura
LangChain faz mais sentido como camada de produtividade para construir rápido. Para estudo, vale entender bem onde ele simplifica e onde começa a esconder decisões importantes demais.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
