# Neural Networks for Movie Review Sentiment Analysis

## 📖 Overview

Este projeto foi desenvolvido para o curso de Pós-Graduação da USP, ICMC, na disciplina de Redes Neurais. O objetivo é criar um modelo de rede neural capaz de analisar e classificar sentimentos em avaliações de filmes em português e inglês, utilizando embeddings de sentença pré-treinados.

## 🎯 Contexto

O dataset utilizado para este projeto é o `imdb-reviews-pt-br.csv`, que contém avaliações de filmes do site IMDB em português e em inglês. A abordagem envolve a exploração de embeddings de sentença que permitem uma melhor representação semântica dos textos, possibilitando a comparação do desempenho da rede neural nas duas línguas.

## 🛠️ Arquitetura do Modelo

A arquitetura da rede neural seguiu as especificações abaixo:

1. **Normalização em Batch**: Para acelerar o treinamento e estabilizar a aprendizagem.
2. **Camada Densa**: 256 neurônios com ativação ReLU.
3. **Camada Densa**: 256 neurônios com ativação ReLU.
4. **Normalização em Batch**: Para melhorar a eficiência do modelo.
5. **Ativação ReLU**: Para introduzir não linearidade na rede.
6. **Dropout**: 25% para evitar overfitting.
7. **Camada Densa**: 1 neurônio com ativação Sigmoide, para a classificação binária (positivo ou negativo).
