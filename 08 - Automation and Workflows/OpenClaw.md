---
tipo: ferramenta
nome: OpenClaw
categoria: automacao e assistente agentico
status: estudando
opensource: true
licenca: MIT
site: https://openclaw.ai
github: https://github.com/openclaw/openclaw
tags: [ferramenta]
---

# OpenClaw

## O que é
OpenClaw é um assistente agentic self-hosted orientado a executar ações por meio de canais de chat, com gateway próprio, memória e integração com ferramentas e modelos.

## Para que serve
Serve para operar um assistente pessoal ou operacional acessível por apps de mensagem, capaz de usar ferramentas, arquivos e rotinas automatizadas.

## Onde entra na stack
Entra entre interface conversacional, automação e agente operacional. Fica próximo de [[08 - Automation and Workflows/n8n|n8n]], mas com foco mais forte em assistente persistente e interação por chat.

## Quando faz sentido usar
- Quando a ideia é ter um assistente acionável no dia a dia.
- Quando chat é o principal ponto de entrada para tarefas.
- Quando self-hosting, controle e personalização são importantes.

## Quando não faz sentido usar
- Quando o time só precisa de automação previsível e auditável.
- Quando os riscos de acesso a sistema e credenciais são altos demais.
- Quando a organização não tem maturidade para operar agentes com poder de ação.

## Pontos fortes
- Propõe um modelo de assistente mais operacional do que apenas conversacional.
- Forte apelo para uso pessoal avançado e automação cotidiana.
- Integra canais de mensagem, memória e execução.

## Limitações
- Projeto muito dinâmico e ainda exigindo leitura constante da documentação.
- A superfície de risco é grande, porque a proposta envolve ação real sobre sistemas.
- Faz sentido validar segurança, isolamento e governança antes de adoção séria.

## Alternativas
- [[08 - Automation and Workflows/n8n|n8n]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]] com integrações
- Soluções próprias com bot + automação

## Ferramentas relacionadas
- [[07 - Local AI/Ollama|Ollama]]
- [[04 - Chat Interfaces/Open WebUI|Open WebUI]]
- [[05 - Coding Agents/Claude Code|Claude Code]]

## Caso de uso real
Um usuário pode configurar o OpenClaw para receber solicitações por mensageria e executar tarefas repetitivas em arquivos, calendários ou rotinas técnicas. Esse tipo de uso pede controles claros de escopo e permissões.

## Minha leitura
OpenClaw parece representar bem a passagem de "ferramenta de IA" para "sistema agentic operando no mundo real". Justamente por isso, o estudo dele deve incluir arquitetura e segurança, não só recursos.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
