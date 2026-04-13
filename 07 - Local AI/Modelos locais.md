---
tipo: conceito
nome: Modelos locais
categoria: local-ai
tags: [conceito]
---

# Modelos locais

## DefiniÃ§Ã£o
Modelos locais sÃ£o modelos executados na mÃ¡quina do usuÃ¡rio ou em infraestrutura prÃ³pria, em vez de depender exclusivamente de uma API externa gerenciada.

## Por que isso importa
Essa abordagem muda custo, privacidade, latÃªncia, controle e complexidade operacional. Ã‰ um conceito central para entender [[07 - Local AI/Ollama|Ollama]] e interfaces como [[04 - Chat Interfaces/Open WebUI|Open WebUI]].

## Como funciona
O modelo Ã© baixado, armazenado e executado em hardware local ou controlado pela organizaÃ§Ã£o.

- A inferÃªncia acontece no prÃ³prio ambiente.
- O desempenho depende do modelo, da quantizaÃ§Ã£o e do hardware.
- O sistema pode expor o modelo por API local para outras ferramentas.

## RelaÃ§Ã£o com outras ideias
Modelos locais se conectam a [[01 - Foundations/LLM|LLM]], [[01 - Foundations/Contexto|Contexto]], [[06 - RAG and Memory/RAG|RAG]] e ao desenho geral de infraestrutura.

## Ferramentas que usam isso
- [[07 - Local AI/Ollama|Ollama]]
- [[04 - Chat Interfaces/Open WebUI|Open WebUI]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]

## Exemplo prÃ¡tico
Uma equipe pode rodar um modelo local via [[07 - Local AI/Ollama|Ollama]] e expor esse modelo em um ambiente interno com [[04 - Chat Interfaces/Open WebUI|Open WebUI]] para tarefas sensÃ­veis.

## Minha interpretaÃ§Ã£o
Modelos locais sÃ£o valiosos quando controle e privacidade importam, mas nÃ£o sÃ£o uma soluÃ§Ã£o mÃ¡gica. O ganho vem com custo de operaÃ§Ã£o, escolha de hardware e limitaÃ§Ãµes de qualidade.

