---
layout: default
title: "Word2Vec Model Implementation"
description: "Implementação do modelo Word2Vec com softmax ingênuo e amostragem negativa."
date: 2024-10-07
technologies:
  - Python
  - NumPy
  - Processamento de Linguagem Natural (PLN)
link: "https://github.com/edsondearaujo/word2vec_model_implementation"
image: "/assets/img/word2vec.jpg"  # Adicione o caminho da imagem, se houver
---

## Word2Vec Model Implementation

Este projeto implementa o modelo **Word2Vec**, amplamente utilizado em **Processamento de Linguagem Natural (PLN)** para gerar representações vetoriais de palavras (word embeddings). A implementação inclui o modelo **Skip-gram** e as funções de custo com **softmax ingênuo** e **amostragem negativa** (negative sampling).

### Funcionalidades do Projeto

- **Funções de Ativação**: Implementação das funções `sigmoid()` e `softmax()`.
- **Funções de Custo**: 
  - `naiveSoftmaxLossAndGradient()`: Função que calcula o custo e gradiente usando o método softmax.
  - `negSamplingLossAndGradient()`: Função que calcula o custo e gradiente usando amostragem negativa.
- **Modelo Skip-gram**: Implementação do modelo `skipgram()` para aprender as representações de palavras a partir de um corpus de texto.
- **Verificação de Gradientes**: Função `gradcheck_naive()` que verifica numericamente a consistência entre gradientes e a função de custo.

### Tecnologias Utilizadas

- **Python**: Linguagem principal para a implementação.
- **NumPy**: Para operações matriciais e cálculos eficientes.
- **Random**: Usado para amostragem de palavras e inicialização de vetores.

### Link para o Código

Você pode acessar o código completo deste projeto no GitHub:
[Veja o projeto no GitHub](https://github.com/edsondearaujo/word2vec_model_implementation)

