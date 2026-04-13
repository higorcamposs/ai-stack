---
tipo: comparacao
tags: [comparacao]
---

# LangChain vs LlamaIndex

## Objetivo da comparação
Comparar [[03 - Agent Frameworks/LangChain|LangChain]] e [[06 - RAG and Memory/LlamaIndex|LlamaIndex]] como escolhas de base para aplicações com LLM, especialmente quando existe dúvida entre começar por agentes ou por dados.

## Semelhanças
- Ambos ajudam a acelerar o desenvolvimento de aplicações com LLM.
- Ambos se conectam a modelos, ferramentas e fontes externas.
- Ambos aparecem com frequência em projetos de [[06 - RAG and Memory/RAG|RAG]].
- Ambos podem conversar com bancos vetoriais como [[06 - RAG and Memory/Qdrant|Qdrant]].

## Diferenças
- LangChain é mais amplo como framework de aplicação e agente.
- LlamaIndex é mais forte quando o centro do problema é ingestão, indexação e recuperação sobre dados próprios.
- LangChain tende a ser melhor quando o sistema precisa combinar ferramentas, prompts, agentes e múltiplos serviços.
- LlamaIndex tende a ser melhor quando a pergunta principal é "como organizar bem o contexto vindo dos meus dados?".

## Melhor para cada caso
- LangChain: quando o fluxo envolve agente, ferramentas, chamadas externas e composição geral da aplicação.
- LlamaIndex: quando o problema é claramente centrado em base documental, recuperação e qualidade de contexto.
- Uso combinado: quando a aplicação precisa tanto de boa recuperação quanto de orquestração mais ampla.

## Pontos de decisão
- Se o problema principal é dado e recuperação, eu começaria por LlamaIndex.
- Se o problema principal é orquestração de comportamento, eu começaria por LangChain.
- Se o time é pequeno e precisa reduzir superfície de decisão, vale evitar usar os dois cedo demais.
- Se a stack pode crescer para fluxos mais complexos, vale avaliar se [[03 - Agent Frameworks/LangGraph|LangGraph]] entra melhor do que expandir LangChain sem critério.

## O que eu escolheria e por quê
Se o objetivo fosse montar um sistema de busca e resposta sobre documentos internos, eu escolheria [[06 - RAG and Memory/LlamaIndex|LlamaIndex]] primeiro, porque ele parte do problema certo. Se o objetivo fosse criar um sistema mais agentic, com ferramentas, decisões e integração com vários serviços, eu escolheria [[03 - Agent Frameworks/LangChain|LangChain]]. Em dúvida, eu decidiria pela natureza do problema e não pela popularidade do framework.
