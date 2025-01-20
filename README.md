# Ciência de Dados - Projeto Final 8

![Wallpaper](images/wallpaper.png)

## Projeto
**Modelo de deep learning** com processamento de linguagem natural (NLP) para análise de sentimentos em avaliações em uma plataforma de filmes e séries.


## Descrição
Nesse projeto de Ciência de Dados, foi realizada uma análise exploratória a fim de entender as imagens do conjunto de dados e se sua distribuição entre as classes está balanceada. Após isso, foram criados alguns modelos de Deep Learning usando o TensorFlow e o Keras, para que pudesse classificar corretamente as imagens de acordo com o conjunto de 10 classes: Avião, Automóvel, Pássaro, Gato, Cervo, Cachorro, Sapo, Cavalo, Navio e Caminhão. Na criação desses modelos foram utilizadas técnicas de pré processamento, data augmentation, Redes Neurais Convolucionais (CNN), transferência de aprendizado de modelos históricos, otimização de hiperparâmetros usando Fine-Tuning e ajustes para evitar overfitting, usando métricas como loss e accuracy. Após o treinamento de modelos com diferentes características, o modelo com a melhor performance obteve uma acurácia de 79% das imagens classificadas, ou seja, a cada 5 imagens avaliadas o modelo classificou 4 corretamente. Dessa forma, esse modelo permite sua aplicação em um site de buscas, para reconhecer imagens fornecidas por usuários e retornar resultados relevantes para essa busca, por exemplo.


## Overview de um review do dataset
![output_dataset](images/output_dataset.jpg)

## Verificações de overfitting no modelo
![output_overfitting_loss](images/output_overfitting_loss.jpg)

![output_overfitting_accuracy](images/output_overfitting_accuracy.jpg)

## Previsões do dataset realizadas pelo modelo
![output_predictions_dataset](images/output_predictions_dataset.jpg)

## Previsões de reviews manuais realizadas pelo modelo
![output_predictions_real](images/output_predictions_real.jpg)