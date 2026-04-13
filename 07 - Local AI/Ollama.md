---
tipo: ferramenta
nome: Ollama
categoria: ia local
status: estudando
opensource: true
licenca: MIT
site: https://ollama.com
github: https://github.com/ollama/ollama
tags: [ferramenta]
---

# Ollama

## O que é
Ollama é uma plataforma open source para baixar, executar e servir modelos localmente por CLI, API e aplicações desktop.

## Para que serve
Serve para colocar modelos open weights em uso local com menos atrito, tanto para chat quanto para aplicações e agentes.

## Onde entra na stack
Entra na camada de IA local, servindo como base para ferramentas como [[04 - Chat Interfaces/Open WebUI|Open WebUI]] e experimentos com agentes, RAG e automação.

## Quando faz sentido usar
- Quando privacidade e controle local importam.
- Quando o time quer testar modelos sem depender sempre de API externa.
- Quando a stack precisa de um runtime local simples para modelos.

## Quando não faz sentido usar
- Quando a máquina disponível não suporta os modelos necessários.
- Quando latência, custo ou qualidade favorecem claramente APIs gerenciadas.
- Quando o time não quer lidar com modelos, quantização e recursos de hardware.

## Pontos fortes
- Instalação e uso relativamente simples.
- Interface de linha de comando e API fáceis de integrar.
- Forte efeito de ecossistema na camada local.
- Bom ponto de partida para estudar soberania e privacidade em IA.

## Limitações
- Qualidade final depende muito do modelo e do hardware.
- Rodar local não elimina necessidade de governança e segurança.
- Exposição indevida do serviço pode criar risco operacional se mal configurado.

## Alternativas
- Runtimes locais específicos por modelo
- Provedores de inferência gerenciada
- Ferramentas de desktop fechadas para IA local

## Ferramentas relacionadas
- [[04 - Chat Interfaces/Open WebUI|Open WebUI]]
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]

## Caso de uso real
Uma equipe pode usar Ollama para servir modelos locais em um ambiente privado e conectá-los a uma interface como Open WebUI, reduzindo dependência de APIs externas em tarefas sensíveis.

## Minha leitura
Ollama é uma peça central para entender a stack local de IA. O estudo dele vale tanto pelo uso prático quanto pelas implicações de hardware, segurança e arquitetura.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
