# 🎬 CineGraph Analytics

Sistema avançado de **análise de dados e recomendação baseado em grafos**, desenvolvido com **Neo4j e Cypher**, simulando a arquitetura de plataformas modernas de streaming.

O projeto explora **modelagem de dados orientada a grafos**, análise de relacionamentos complexos e geração de **recomendações inteligentes baseadas em comportamento**.

---

## 🚀 Tecnologias Utilizadas

- Neo4j
- Cypher Query Language (CQL)
- Graph Data Modeling
- Análise de Dados com Grafos

---

## 🎯 Objetivo do Projeto

Projetar e implementar um sistema capaz de:

- Relacionar **usuários, filmes, séries e gêneros**
- Analisar **padrões de consumo**
- Identificar **afinidade entre usuários**
- Gerar **recomendações automáticas**
- Simular cenários reais usados por plataformas como Netflix, Prime Video e Disney+

---

## 🧠 Modelagem do Grafo

### 🟢 Nós (Nodes)

- `Usuario`
- `Filme`
- `Serie`
- `Genero`

### 🔗 Relacionamentos (Relationships)

- `ASSISTIU` → Usuário assistiu um conteúdo  
- `AVALIOU` → Usuário avaliou um conteúdo  
- `PERTENCE_A` → Conteúdo pertence a um gênero  

---

## 🗺️ Visualização do Grafo

Abaixo estão algumas visualizações reais do banco no **Neo4j Browser**, demonstrando:

- Organização por gêneros  
- Relacionamento entre usuários  
- Interseção de interesses  
- Estrutura de recomendação  

### 🎥 Filmes e Gêneros

![Grafo - Filmes e Gêneros](imagens/visualisation_1.png)

---

### 👥 Usuários e Conteúdos

![Grafo - Usuários](imagens/visualisation_2.png)

---

### 🧠 Conexões e Afinidades

![Grafo - Afinidade](imagens/visualisation_3.png)

---

## 🧩 Estrutura do Projeto

