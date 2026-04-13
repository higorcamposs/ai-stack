---
tipo: ferramenta
nome: OpenHands
categoria: coding agent
status: estudando
opensource: true
licenca: MIT na base open source; camada enterprise separada
site: https://openhands.dev
github: https://github.com/OpenHands/OpenHands
tags: [ferramenta]
---

# OpenHands

## O que é
OpenHands é uma plataforma open source para desenvolvimento orientado por agentes, focada em tarefas de software como leitura de código, edição, execução e resolução de problemas.

## Para que serve
Serve para delegar partes do trabalho de engenharia a um agente que opera sobre código, terminal e ambiente de execução.

## Onde entra na stack
Entra na camada de [[05 - Coding Agents/Claude Code|agentes de código]], junto com [[05 - Coding Agents/Cursor|Cursor]] e outras ferramentas que atuam diretamente no ciclo de desenvolvimento.

## Quando faz sentido usar
- Quando o objetivo é experimentar automação de tarefas de engenharia.
- Quando há interesse em self-hosting ou maior inspeção da stack.
- Quando o time quer estudar agentes de software além de IDEs fechadas.

## Quando não faz sentido usar
- Quando a equipe precisa de solução pronta com menor custo operacional.
- Quando ainda não existe processo mínimo de revisão humana.
- Quando a segurança do ambiente não suporta execução agentic.

## Pontos fortes
- Projeto open source com foco claro em desenvolvimento.
- Útil para estudar o estado da arte em agentes de software.
- Pode servir como referência arquitetural, não só como ferramenta.

## Limitações
- Operar bem a ferramenta exige mais maturidade técnica.
- A fronteira entre demo impressionante e uso confiável precisa ser validada.
- Parte enterprise tem licenciamento separado.

## Alternativas
- [[05 - Coding Agents/Claude Code|Claude Code]]
- [[05 - Coding Agents/Cursor|Cursor]]
- Fluxos próprios de agentic coding

## Ferramentas relacionadas
- [[11 - Observability/Langfuse|Langfuse]]
- [[07 - Local AI/Ollama|Ollama]]
- [[08 - Automation and Workflows/n8n|n8n]]

## Caso de uso real
Um time pode usar OpenHands em tarefas delimitadas como correção de bugs simples, geração de testes e exploração de base legada, sempre com revisão humana antes do merge.

## Minha leitura
OpenHands é relevante para estudar como agentes de software são montados como sistema e não apenas como recurso de IDE. O valor maior está em entender capacidades e limites reais.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
