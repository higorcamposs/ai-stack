---
tipo: ferramenta
nome: Open WebUI
categoria: interface de chat
status: estudando
opensource: true
licenca: BSD-3 com restricao de branding nas versoes recentes
site: https://www.openwebui.com
github: https://github.com/open-webui/open-webui
tags: [ferramenta]
---

# Open WebUI

## O que é
Open WebUI é uma plataforma self-hosted para usar modelos locais e remotos em uma interface única, com forte associação ao ecossistema do [[07 - Local AI/Ollama|Ollama]].

## Para que serve
Serve para oferecer chat, upload de arquivos, ferramentas e experiências de IA em uma interface privada e extensível.

## Onde entra na stack
Entra na camada de interface de uso, especialmente em stacks locais ou híbridas com [[07 - Local AI/Ollama|Ollama]] e recursos de RAG.

## Quando faz sentido usar
- Quando o objetivo é operar IA localmente ou em ambiente controlado.
- Quando a equipe quer interface pronta para múltiplos modelos.
- Quando há interesse em combinar chat, documentos e ferramentas em um único front-end.

## Quando não faz sentido usar
- Quando o time não quer operar infraestrutura.
- Quando basta um chat simples sem personalização.
- Quando a organização precisa de clareza jurídica total sobre customização de marca e distribuição.

## Pontos fortes
- Forte encaixe com modelos locais.
- Instalação relativamente acessível para self-hosting.
- Boa experiência para laboratório, uso individual e times técnicos.
- Pode funcionar como camada prática para explorar uma stack local de IA.

## Limitações
- A licença recente exige leitura cuidadosa por causa da restrição de branding.
- Pode crescer em complexidade operacional com plugins, usuários e integrações.
- Não substitui por si só uma boa arquitetura de dados ou observabilidade.

## Alternativas
- [[04 - Chat Interfaces/LibreChat|LibreChat]]
- Interfaces oficiais de provedores
- Aplicações customizadas

## Ferramentas relacionadas
- [[07 - Local AI/Ollama|Ollama]]
- [[06 - RAG and Memory/Qdrant|Qdrant]]
- [[11 - Observability/Langfuse|Langfuse]]

## Caso de uso real
Um laboratório interno pode subir Open WebUI conectado a Ollama e a provedores via API para testar modelos, comparar respostas e anexar documentos sem sair da rede controlada da organização.

## Minha leitura
Open WebUI parece especialmente valioso quando a pergunta é "como tornar a IA local utilizável no dia a dia". Vale estudar junto com licença, operação e segurança.

## Status
- [ ] Entendi o conceito
- [ ] Vi exemplos
- [ ] Comparei com alternativas
- [ ] Pensei em uso real
