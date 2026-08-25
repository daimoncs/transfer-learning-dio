# Classificação de Cães e Gatos com Transfer Learning 🐶🐱

Este projeto foi desenvolvido como parte do desafio prático de Redes Neurais da plataforma DIO. O objetivo foi aplicar a técnica de **Transfer Learning** utilizando a arquitetura da rede neural pré-treinada VGG16 para classificar imagens de cães e gatos.

## Ferramentas Utilizadas
* Python
* TensorFlow / Keras (VGG16, ImageDataGenerator)
* Google Colab

## Estrutura do Projeto
A base do modelo VGG16 foi carregada com seus pesos pré-treinados (congelados). Em seguida, adicionamos camadas densas (Dense, Flatten, Dropout) personalizadas no topo para realizar a classificação binária final entre gatos e cachorros.

## Resultados do Treinamento
Abaixo estão as capturas de tela demonstrando a estrutura da rede, o processo de treinamento e a acurácia alcançada:

<img width="876" height="459" alt="Captura de tela 2026-08-24 225634" src="https://github.com/user-attachments/assets/576cc6bc-6f7b-4e20-bc0a-6259c3f075ab" />

<img width="560" height="401" alt="Captura de tela 2026-08-24 225311" src="https://github.com/user-attachments/assets/8ab31e6e-0f18-45c0-97f4-7f5298ea81eb" />

<img width="1364" height="644" alt="Captura de tela 2026-08-24 222908" src="https://github.com/user-attachments/assets/5123b5b6-79c0-4303-b7b3-8ebf6fa2b412" />

