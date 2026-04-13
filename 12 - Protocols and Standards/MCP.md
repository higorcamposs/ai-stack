---
tipo: conceito
nome: MCP
categoria: protocols
tags: [conceito]
---

# MCP

## DefiniÃ§Ã£o
MCP, ou Model Context Protocol, Ã© um protocolo para conectar modelos e agentes a ferramentas, recursos e fontes de contexto de forma padronizada.

## Por que isso importa
Sem um padrÃ£o, cada integraÃ§Ã£o tende a ser feita de forma diferente. MCP ajuda a reduzir acoplamento e tornar ferramentas mais reutilizÃ¡veis entre hosts, agentes e ambientes.

## Como funciona
Em alto nÃ­vel, o protocolo organiza como um cliente ou host conversa com servidores que expÃµem ferramentas e recursos.

- O host descobre o que estÃ¡ disponÃ­vel.
- O agente ou aplicaÃ§Ã£o escolhe recursos ou ferramentas.
- A execuÃ§Ã£o ocorre com uma interface padronizada.
- O resultado volta ao sistema principal.

## RelaÃ§Ã£o com outras ideias
MCP se conecta com [[01 - Foundations/Tool Calling|Tool Calling]], [[01 - Foundations/Agente|Agente]] e desenho de interoperabilidade entre sistemas.

## Ferramentas que usam isso
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- Ferramentas de agente e hosts que adotam o protocolo

## Exemplo prÃ¡tico
Um host compatÃ­vel com MCP pode expor acesso padronizado a arquivos, banco de dados e APIs, permitindo que diferentes agentes usem esses recursos sem integraÃ§Ã£o manual especÃ­fica para cada caso.

## Minha interpretaÃ§Ã£o
MCP Ã© importante porque trata ferramentas e contexto como infraestrutura interoperÃ¡vel. Ele nÃ£o resolve sozinho o comportamento do agente, mas melhora muito a forma de conectar peÃ§as.

