---
tipo: caso_real
tags: [caso_real]
---

# Stack mínima para estudar agentes localmente

## Cenário
Uma pessoa quer aprender agentes de forma prática em ambiente local, com baixo custo e boa visibilidade da arquitetura.

## Problema
Muita gente tenta aprender agentes a partir de stacks grandes demais, o que gera mais confusão do que entendimento.

## Ferramentas envolvidas
- [[07 - Local AI/Ollama|Ollama]]
- [[04 - Chat Interfaces/Open WebUI|Open WebUI]]
- [[01 - Foundations/Agente|Agente]]
- [[01 - Foundations/Tool Calling|Tool Calling]]
- [[07 - Local AI/Modelos locais|Modelos locais]]

## Arquitetura sugerida
- Ollama para servir modelo local
- Open WebUI como interface
- um conjunto pequeno de ferramentas ou funções controladas
- notas no [[09 - Knowledge and PKM/Obsidian|Obsidian]] para registrar aprendizados

## Fluxo
1. O usuário sobe um modelo local.
2. Usa uma interface para testar prompts, contexto e tarefas.
3. Adiciona poucas ferramentas e observa quando o modelo precisa agir.
4. Registra limites, falhas e hipóteses no cofre.

## Benefícios
- custo inicial baixo
- boa clareza arquitetural
- ambiente adequado para aprender antes de escalar complexidade

## Riscos
- modelos locais pequenos podem dar falsa impressão de limite do conceito
- sem objetivo claro, o laboratório vira só coleção de testes aleatórios
- hardware local pode limitar muito a experiência

## Como eu aplicaria
Eu estudaria agentes em camadas: primeiro chat local, depois tool calling, depois workflows simples. Pular direto para multiagente ou automação complexa normalmente atrapalha.
