# 🎵 Sistema de Recomendação de Músicas com Grafos (Neo4j)

Este projeto foi desenvolvido como parte do desafio da *DIO (Digital Innovation One)* para demonstrar a aplicação de bancos de dados orientados a grafos na criação de algoritmos de recomendação inteligentes.

## 🎯 Objetivo
O objetivo principal é modelar um ecossistema musical e utilizar a linguagem de consulta *Cypher* para identificar padrões de escuta e sugerir novas faixas aos usuários com base em suas conexões.

## 🏗️ Estrutura do Projeto
O repositório está organizado da seguinte forma:
- *roteiro/*: Contém os scripts Cypher para criação do banco (setup.cypher) e execução das consultas de recomendação (queries.cypher).
- *Imagens*: Capturas de tela que comprovam o funcionamento do sistema no Neo4j.

## 📊 Demonstração dos Resultados

### 1. Modelagem do Grafo
O banco de dados foi populado com um total de *21 nós*, incluindo Artistas, Gêneros, Músicas e Usuários.
![Visualização do Grafo](./Captura%20de%20tela1_console.neo4j.io.jpeg)

### 2. Algoritmo de Recomendação
Abaixo, a execução de uma consulta que recomenda a música "Billie Jean" para o usuário *Carlos, baseando-se no fato de que a usuária **Ana* possui gostos similares.
![Resultado da Recomendação](./Captura%20de%20tela2_console.neo4j.io.jpeg)

## 🛠️ Tecnologias Utilizadas
- *Neo4j*: Banco de dados de grafos.
- *Cypher Query Language*: Linguagem para consulta e manipulação de grafos.

---
Desenvolvido por [Jaciele Freitas] como demonstração técnica de sistemas de recomendação.
