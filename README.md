# NLP_project

## 📊 Comparación de Modelos: Clasificación de Emociones en Tweets

| Modelo | Accuracy | F1-score (Macro) | F1-score (Weighted) |
|--------|----------|------------------|----------------------|
| **LSTM**  | 0.45     | 0.21             | 0.43                 |
| **GRU**   | 0.45     | 0.09             | 0.28                 |
| **BERT**  | 0.62     | 0.39             | 0.60                 |

- BERT supera claramente a los modelos secuenciales (LSTM y GRU) tanto en accuracy como en F1-score, lo que indica una mejor capacidad para reconocer correctamente emociones en los tweets.

- LSTM ofrece resultados intermedios, con desempeño aceptable en clases como joy y others, pero pobre en emociones minoritarias.

- GRU colapsa completamente al enfocarse casi exclusivamente en la clase mayoritaria (others), lo que lo hace inadecuado para esta tarea sin mejoras.
