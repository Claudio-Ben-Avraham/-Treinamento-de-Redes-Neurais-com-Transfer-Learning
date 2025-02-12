# Treinamento de Redes Neurais com Transfer Learning  

## 📌 Sobre o Projeto  

Este projeto tem como objetivo aplicar o método de **Transfer Learning** em uma rede de **Deep Learning** utilizando a linguagem **Python** no ambiente **Google Colab**. O Transfer Learning permite o reaproveitamento de um modelo previamente treinado para acelerar o treinamento de novas tarefas.  

## 🧑‍💻 Implementação  

Para exemplificar, utilizaremos o seguinte notebook que realiza **Transfer Learning** com o dataset **MNIST**:  
🔗 [Notebook de Transfer Learning](https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb)  

O dataset utilizado no projeto inclui duas classes: **gatos** e **cachorros**.  

📄 Descrição do dataset: [Cats vs Dogs Dataset - TensorFlow](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)  

📥 Download do dataset: [Cats vs Dogs - Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=54765)  

## ⚡ Estrutura do Projeto  

1. **Carregamento do dataset**: Baixar e preparar os dados.  
2. **Pré-processamento**: Normalização das imagens e divisão entre treino/validação.  
3. **Carregamento do modelo pré-treinado**: Utilização de redes como VGG16, ResNet ou MobileNet.  
4. **Ajuste do modelo**: Substituição da última camada para adaptar à nova classificação.  
5. **Treinamento e Avaliação**: Ajuste fino do modelo e teste com imagens novas.  

## 🔧 Personalização  

Você pode utilizar sua própria base de dados, como fotos pessoais, de amigos, familiares ou outros tipos de objetos. O exemplo de **gatos e cachorros** pode ser substituído por outras duas classes de sua escolha.  

Caso tenha um dataset criado em um projeto anterior, ele pode ser reutilizado aqui.  

## 🚀 Requisitos  

- Python 3.x  
- TensorFlow  
- Google Colab  
- OpenCV (opcional para pré-processamento de imagens)  

## 📚 Referências  

- [Documentação do TensorFlow](https://www.tensorflow.org/)  
- [Transfer Learning - Guia do TensorFlow](https://www.tensorflow.org/tutorials/images/transfer_learning)  

---

💡 **Dica:** Teste diferentes modelos pré-treinados para comparar o desempenho e a precisão da classificação! 🎯  
