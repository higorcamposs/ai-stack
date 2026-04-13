---
tipo: ferramenta
nome: Claude Code
categoria: coding agent
status: estudando
opensource: false
licenca: proprietaria
site: https://www.anthropic.com/claude-code
github:
tags: [ferramenta]
---

# Claude Code

## O que é
Claude Code é a ferramenta agentic de terminal da Anthropic para navegação de código, edição de arquivos, execução de comandos e apoio ao ciclo de desenvolvimento.

## Para que serve
Serve para transformar instruções em linguagem natural em trabalho técnico sobre um repositório local, com pesquisa, edição, testes e operações no terminal.

## Onde entra na stack
Entra na camada de agentes de código, perto de [[05 - Coding Agents/Cursor|Cursor]] e de propostas open source como [[05 - Coding Agents/OpenHands|OpenHands]].

## Quando faz sentido usar
- Quando o fluxo principal de trabalho já acontece no terminal.
- Quando é importante combinar análise de código e execução com pouca fricção.
- Quando o usuário quer uma experiência mais agentic do que autocomplete tradicional.

## Quando não faz sentido usar
- Quando a política da organização evita ferramentas proprietárias.
- Quando a equipe precisa de self-hosting completo.
- Quando o custo e a dependência de vendor pesam mais do que a produtividade esperada.

## Pontos fortes
- Foco direto em fluxo real de engenharia.
- Boa integração com terminal e raciocínio sobre base de código.
- Arquitetura com permissões explícitas ajuda a manter controle operacional.

## Limitações
- É uma ferramenta proprietária.
- Depende da infraestrutura e política comercial da Anthropic.
- O valor prático depende bastante do modelo disponível e do contexto do projeto.

## Alternativas
- [[05 - Coding Agents/Cursor|Cursor]]
- [[05 - Coding Agents/OpenHands|OpenHands]]
- Soluções com [[07 - Local AI/Ollama|Ollama]] quando compatíveis

## Ferramentas relacionadas
- [[07 - Local AI/Ollama|Ollama]]
- [[11 - Observability/Langfuse|Langfuse]]
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]

## Caso de uso real
Claude Code faz sentido em tarefas como implementar uma feature delimitada, investigar falhas de testes, entender uma base grande ou propor refatorações com execução assistida de comandos.

## Minha leitura
É uma referência importante para estudar a categoria de coding agents. Mesmo sendo proprietário, ajuda a entender o padrão emergente de agente no terminal com permissões, contexto de projeto e fluxo iterativo.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
