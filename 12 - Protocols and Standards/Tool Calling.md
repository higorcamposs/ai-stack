---
tipo: conceito
nome: Tool Calling como padrão
categoria: protocols
tags: [conceito]
---

# Tool Calling como padrão

## Definição
Tool Calling é o mecanismo pelo qual um modelo ou agente pede o uso de uma ferramenta externa com parâmetros estruturados, dentro de uma interface controlada.

## Por que isso importa
Na camada de protocolos e padrões, tool calling importa porque transforma uso de ferramenta em algo previsível e integrável. Isso facilita conexão entre modelos, agentes e sistemas externos.

## Como funciona
O sistema descreve as ferramentas disponíveis de maneira estruturada.

- Cada ferramenta tem nome, finalidade e parâmetros.
- O modelo escolhe quando e como chamá-la.
- O host ou runtime executa a ferramenta.
- O resultado retorna para o fluxo.

## Relação com outras ideias
Esta nota complementa [[01 - Foundations/Tool Calling|Tool Calling]] em uma leitura mais voltada a protocolo. Ela também conversa com [[12 - Protocols and Standards/MCP|MCP]] e [[01 - Foundations/Agente|Agente]].

## Ferramentas que usam isso
- [[03 - Agent Frameworks/LangChain|LangChain]]
- [[03 - Agent Frameworks/LangGraph|LangGraph]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/OpenHands|OpenHands]]

## Exemplo prático
Em um agente de código, o modelo pode pedir para ler um arquivo, buscar texto no repositório e executar um teste, cada ação com parâmetros definidos e auditáveis.

## Minha interpretação
Quando tool calling é tratado como padrão e não como improviso, fica mais fácil governar segurança, observabilidade e interoperabilidade entre ferramentas.
