---
tipo: comparacao
tags: [comparacao]
---

# Qdrant vs Weaviate vs Chroma

## Objetivo da comparação
Comparar [[06 - RAG and Memory/Qdrant|Qdrant]], Weaviate e Chroma como opções para armazenamento vetorial e suporte a sistemas de [[06 - RAG and Memory/RAG|RAG]].

## Semelhanças
- Os três atuam no espaço de vector database.
- Os três podem servir como base de recuperação semântica.
- Os três aparecem em stacks de busca, recomendação e RAG.

## Diferenças
- [[06 - RAG and Memory/Qdrant|Qdrant]] tende a ser uma escolha forte quando se quer um banco vetorial dedicado, claro e focado.
- Weaviate tende a ser mais "batteries included", com mais recursos nativos em torno da base vetorial, busca híbrida e operação mais ampla.
- Chroma tende a ser mais simples e acessível para começar, especialmente em protótipos e ambientes menores.
- Qdrant parece equilibrar foco e robustez.
- Weaviate parece empurrar mais para plataforma.
- Chroma parece melhor como ponto de entrada do que como aposta óbvia para sistemas mais exigentes.

## Melhor para cada caso
- Qdrant: para quem quer banco vetorial especializado e boa clareza arquitetural.
- Weaviate: para quem quer mais recursos integrados e aceita uma solução mais abrangente.
- Chroma: para prototipagem rápida, uso local e cenários menores.

## Pontos de decisão
- Seu time quer simplicidade ou mais recursos nativos?
- O uso é protótipo, piloto ou produção exigente?
- Você quer um banco vetorial enxuto ou uma plataforma mais completa?
- Se o sistema crescer, filtros, multitenancy, híbrido e operação importam muito mais do que no primeiro demo.

## O que eu escolheria e por quê
Hoje eu escolheria [[06 - RAG and Memory/Qdrant|Qdrant]] como default pragmático para estudar e montar algo sério sem exagerar na plataforma. Escolheria Weaviate quando precisasse claramente das capacidades extras e da abordagem mais integrada. Escolheria Chroma apenas quando a prioridade fosse subir um protótipo rápido com o menor atrito possível.
