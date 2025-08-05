# Projeto de Transfer Learning: Classificação de Imagens (Gatos vs Cachorros)

Este projeto demonstra a aplicação de **Transfer Learning** usando o modelo **MobileNetV2** para classificar imagens em duas categorias: **gatos** e **cachorros**. Utilizamos o **Google Colab** e a biblioteca **TensorFlow/Keras** para construir, treinar e avaliar o modelo.

## 📌 Objetivos
- Utilizar um modelo pré-treinado em uma nova tarefa (duas classes)
- Aplicar técnicas de aumento de dados e fine-tuning
- Avaliar desempenho e testar com novas imagens

## 🧠 Tecnologias Utilizadas
- Python 3.x
- TensorFlow 2.x
- Google Colab
- Keras
- TensorFlow Datasets

## 📁 Estrutura
```
transfer-learning-cats-vs-dogs/
├── notebook.ipynb
├── README.md
├── model/
│   └── transfer_model.h5
├── images/
│   └── exemplos de testes
```

## 🔗 Dataset Utilizado
- Dataset oficial: [Cats vs Dogs - TensorFlow](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)
- Alternativo: [Microsoft Download - Kaggle](https://www.microsoft.com/en-us/download/details.aspx?id=54765)

## 🚀 Como Executar
1. Acesse o notebook no Colab:  
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/SEU_ID_AQUI)

2. Faça upload do dataset ou use o carregamento automático do TensorFlow Datasets.

3. Treine o modelo com Transfer Learning.

4. Teste com imagens reais.

## 📊 Resultados
- Acurácia esperada: +90%
- Modelo salvo em `.h5` para reuso

