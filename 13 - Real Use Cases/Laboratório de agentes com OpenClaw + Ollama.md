---
tipo: caso_real
tags: [caso_real]
---

# Laboratório de agentes com OpenClaw + Ollama

## Cenário
Um time técnico quer estudar agentes localmente, com autonomia razoável, sem depender logo de APIs externas pagas.

## Problema
É difícil aprender agentes de forma prática quando tudo fica restrito a demos desconectadas ou a serviços hospedados com pouco controle.

## Ferramentas envolvidas
- [[08 - Automation and Workflows/OpenClaw|OpenClaw]]
- [[07 - Local AI/Ollama|Ollama]]
- [[07 - Local AI/Modelos locais|Modelos locais]]
- [[01 - Foundations/Agente|Agente]]
- [[01 - Foundations/Workflow agentic|Workflow agentic]]

## Arquitetura sugerida
- Ollama como runtime local de modelos
- OpenClaw como camada de agente e assistente acionável
- ambiente isolado para testes, credenciais limitadas e logs básicos
- opcionalmente [[11 - Observability/Langfuse|Langfuse]] em uma segunda fase

## Fluxo
1. O time define um conjunto pequeno de tarefas para o agente.
2. O OpenClaw usa Ollama como backend local de modelo.
3. O agente recebe pedidos por interface de chat ou canal controlado.
4. As execuções são revisadas manualmente até que existam critérios mínimos de segurança.

## Benefícios
- aprendizado prático de agentes com mais controle
- menor dependência de custo variável de API
- boa visibilidade sobre a arquitetura real do sistema

## Riscos
- modelos locais podem limitar qualidade em tarefas mais difíceis
- agentes com ação real ampliam risco operacional
- sem isolamento, o laboratório pode virar um ambiente perigoso demais

## Como eu aplicaria
Eu trataria esse caso como sandbox de aprendizagem. Começaria com tarefas de baixo risco, como organização de notas, consultas locais e rotinas simples. Só depois avaliaria integrações mais poderosas.
