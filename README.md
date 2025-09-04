# 📊 Análise de Dados - Queima de Calorias na Academia

Este repositório apresenta uma análise exploratória de dados (EDA) sobre a queima de calorias de homens e mulheres durante treinos na academia. O objetivo principal é entender se há diferença significativa entre os gêneros na quantidade de calorias queimadas.

---

## 📁 Dataset

- **Fonte**: Kaggle  
- **Título**: Gym Members Exercise Dataset  
- **Link para download**: [Clique aqui](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset?resource=download)

---

## 🧪 Tecnologias e Bibliotecas Utilizadas

- Python 3.x  
- pandas  
- numpy  
- seaborn  
- matplotlib  

---

## 🧾 Etapas da Análise

1. **Importação do dataset**
2. **Visualização inicial dos dados (`head`, `info`, `describe`)**
3. **Verificação de dados faltantes**
4. **Análise gráfica com gráfico de dispersão**
5. **Interpretação dos resultados**

---

## ❓ Pergunta Norteadora

> Com base no gênero da pessoa, a queima de calorias tem variações ou são relativamente parecidas quando ambos estão na academia?

---

## 📉 Visualização

Foi gerado um **gráfico de dispersão** relacionando a **idade** dos indivíduos com as **calorias queimadas**, diferenciando-os por **gênero**:

```python
plt.figure(figsize=(10, 6))
sns.scatterplot(data=df, x='Age', y='Calories_Burned', hue='Gender')
plt.title('Calorias queimada em relação à idade')
plt.xlabel('Idade')
plt.ylabel('Calorias queimada')
plt.show()
```

## 🔍 Observações:

Homens e mulheres apresentam níveis semelhantes de queima calórica entre 500 e 1400 calorias.
A maior parte das mulheres entre 20 e 60 anos queimam ligeiramente menos calorias do que os homens da mesma faixa etária.
A diferença entre os gêneros não é extrema, e os dados são relativamente próximos, sem outliers significativos (exceto alguns valores acima de 1650 calorias).

---

## ✅ Conclusão

A análise mostra que a queima de calorias entre homens e mulheres é relativamente parecida, com pequenas variações dependendo da faixa etária. O gráfico evidencia que, apesar de uma leve vantagem dos homens, os valores estão bem distribuídos entre os gêneros.

---

## 📌 Observação

O dataset não possui dados faltantes, portanto não foi necessário aplicar técnicas de tratamento de dados ausentes.

---

## 📂 Estrutura do Projeto
```
📁 gym-calories-analysis
│
├── 📄 README.md
├── 📄 gym_members_exercise_tracking.csv
└── 📄 analise_queima_calorias.ipynb
```

## 📬 Contato

Caso tenha sugestões ou dúvidas, sinta-se à vontade para abrir uma issue ou entrar em contato!


