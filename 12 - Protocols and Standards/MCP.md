---
tipo: conceito
nome: MCP
categoria: protocols
tags: [conceito]
---

# MCP

## Definição
MCP, ou Model Context Protocol, é um protocolo para conectar modelos e agentes a ferramentas, recursos e fontes de contexto de forma padronizada.

## Por que isso importa
Sem um padrão, cada integração tende a ser feita de forma diferente. MCP ajuda a reduzir acoplamento e tornar ferramentas mais reutilizáveis entre hosts, agentes e ambientes.

## Como funciona
Em alto nível, o protocolo organiza como um cliente ou host conversa com servidores que expõem ferramentas e recursos.

- O host descobre o que está disponível.
- O agente ou aplicação escolhe recursos ou ferramentas.
- A execução ocorre com uma interface padronizada.
- O resultado volta ao sistema principal.

## Relação com outras ideias
MCP se conecta com [[01 - Foundations/Tool Calling|Tool Calling]], [[01 - Foundations/Agente|Agente]] e desenho de interoperabilidade entre sistemas.

## Ferramentas que usam isso
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- [[05 - Coding Agents/Claude Code|Claude Code]]
- Ferramentas de agente e hosts que adotam o protocolo

## Exemplo prático
Um host compatível com MCP pode expor acesso padronizado a arquivos, banco de dados e APIs, permitindo que diferentes agentes usem esses recursos sem integração manual específica para cada caso.

## Minha interpretação
MCP é importante porque trata ferramentas e contexto como infraestrutura interoperável. Ele não resolve sozinho o comportamento do agente, mas melhora muito a forma de conectar peças.

