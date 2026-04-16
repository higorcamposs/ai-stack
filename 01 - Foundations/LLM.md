---
tipo: conceito
nome: LLM
categoria: foundations
tags: [conceito]
---

# LLM

## Definição
LLM significa "Large Language Model", ou modelo de linguagem de grande porte. É um tipo de modelo treinado para prever e gerar texto com base em grandes volumes de dados e em padrões estatísticos aprendidos.

## Por que isso importa
LLMs são a base de grande parte da stack moderna de IA aplicada. Sem entender LLM, fica difícil entender ferramentas como [[03 - Agent Frameworks/LangChain|LangChain]], [[05 - Coding Agents/Claude Code|Claude Code]], [[05 - Coding Agents/Cursor|Cursor]] ou interfaces como [[04 - Chat Interfaces/LibreChat|LibreChat]].

## Como funciona
De forma simples, o modelo recebe um contexto de entrada, transforma isso em tokens e calcula qual token faz mais sentido vir em seguida.

- Ele não "pensa" como uma pessoa.
- Ele opera por padrões aprendidos durante o treinamento.
- O resultado final depende do contexto fornecido, da qualidade do modelo e da forma como a tarefa foi estruturada.

## Relação com outras ideias
LLM se conecta diretamente com [[01 - Foundations/Contexto|Contexto]], [[01 - Foundations/Tool Calling|Tool Calling]], [[01 - Foundations/Agente|Agente]] e [[06 - RAG and Memory/RAG|RAG]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/Cursor|Cursor]]
- [[07 - Local AI/Ollama|Ollama]]

## Exemplo prático
Quando um usuário pede a [[05 - Coding Agents/Cursor|Cursor]] para alterar um arquivo em linguagem natural, o editor usa um LLM para interpretar o pedido, entender o código e propor a mudança.

## Minha interpretação
LLM é o motor principal da stack, mas não é o sistema completo. O valor real aparece quando o modelo é combinado com contexto, ferramentas, memória e regras de execução.

