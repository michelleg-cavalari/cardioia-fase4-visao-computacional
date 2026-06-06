# CardioIA - Fase 4
## Classificação de Imagens Médicas com Visão Computacional

### Integrantes

Michelle Guedes Cavalari - RM564557

---

## Descrição do Projeto

O CardioIA é um protótipo de Assistente Cardiológico Virtual desenvolvido para aplicar técnicas de Visão Computacional na análise de imagens médicas.

Nesta fase do projeto foram utilizadas Redes Neurais Convolucionais (CNNs) para classificar imagens de radiografia de tórax em duas categorias:

- Normal
- Pneumonia

O objetivo é demonstrar como técnicas de Inteligência Artificial podem auxiliar profissionais da saúde na análise de exames médicos.

---

## Dataset Utilizado

Chest X-Ray Images (Pneumonia)

Disponível em:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

O dataset contém imagens médicas classificadas em:

- NORMAL
- PNEUMONIA

---

## Pré-processamento

As seguintes etapas foram aplicadas:

- Redimensionamento para 224x224 pixels
- Normalização dos pixels
- Separação em treino, validação e teste
- Organização das classes para treinamento

---

## Modelos Implementados

### CNN Simples

Rede Neural Convolucional construída do zero utilizando TensorFlow/Keras.

Resultado:

- Accuracy: 79,33%

---

### Transfer Learning - MobileNetV2

Modelo pré-treinado MobileNetV2 utilizando Transfer Learning.

Resultado:

- Accuracy: 88,62%

---

## Comparação dos Resultados

| Modelo | Accuracy |
|----------|----------|
| CNN Simples | 79,33% |
| MobileNetV2 | 88,62% |

O modelo MobileNetV2 apresentou melhor desempenho devido ao aproveitamento de conhecimentos previamente aprendidos em grandes bases de imagens.

---

## Tecnologias Utilizadas

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Google Colab

---

## Estrutura do Projeto

```text
assets/
docs/
notebook/
README.md
requirements.txt
```

---

## Conclusão

Os resultados demonstraram que técnicas modernas de Visão Computacional podem ser aplicadas na análise de imagens médicas simuladas.

O modelo MobileNetV2 apresentou desempenho superior à CNN construída do zero, alcançando 88,62% de acurácia.

Essa abordagem demonstra o potencial da Inteligência Artificial como ferramenta de apoio à análise de exames médicos e à tomada de decisão clínica.
