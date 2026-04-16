---
tipo: conceito
nome: Modelos locais
categoria: local-ai
tags: [conceito]
---

# Modelos locais

## Definição
Modelos locais são modelos executados na máquina do usuário ou em infraestrutura própria, em vez de depender exclusivamente de uma API externa gerenciada.

## Por que isso importa
Essa abordagem muda custo, privacidade, latência, controle e complexidade operacional. É um conceito central para entender [[07 - Local AI/Ollama|Ollama]] e interfaces como [[04 - Chat Interfaces/Open WebUI|Open WebUI]].

## Como funciona
O modelo é baixado, armazenado e executado em hardware local ou controlado pela organização.

- A inferência acontece no próprio ambiente.
- O desempenho depende do modelo, da quantização e do hardware.
- O sistema pode expor o modelo por API local para outras ferramentas.

## Relação com outras ideias
Modelos locais se conectam a [[01 - Foundations/LLM|LLM]], [[01 - Foundations/Contexto|Contexto]], [[06 - RAG and Memory/RAG|RAG]] e ao desenho geral de infraestrutura.

## Ferramentas que usam isso
- [[07 - Local AI/Ollama|Ollama]]
- [[04 - Chat Interfaces/Open WebUI|Open WebUI]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]

## Exemplo prático
Uma equipe pode rodar um modelo local via [[07 - Local AI/Ollama|Ollama]] e expor esse modelo em um ambiente interno com [[04 - Chat Interfaces/Open WebUI|Open WebUI]] para tarefas sensíveis.

## Minha interpretação
Modelos locais são valiosos quando controle e privacidade importam, mas não são uma solução mágica. O ganho vem com custo de operação, escolha de hardware e limitações de qualidade.

