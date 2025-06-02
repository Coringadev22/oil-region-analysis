# 🛢️ Oil Reserve Profit Optimization

Este projeto tem como objetivo **identificar a melhor região para investimento em extração de petróleo**, utilizando técnicas de **regressão linear** e **bootstrapping** para estimar o lucro esperado e avaliar o risco de perda.

---

## 📊 Objetivo

Selecionar uma das três regiões disponíveis (A, B ou C) com base em:

- Volume previsto de extração (em mil barris)
- Custo fixo de investimento (10 milhões de unidades monetárias por região)
- Receita gerada por mil barris extraídos (450 mil unidades monetárias)
- Risco de perdas (probabilidade de lucro abaixo de 0)

---

## ⚙️ Metodologia

1. **Análise dos dados**:
   - Cada região possui dados históricos de 500 campos de petróleo com volume de reservas.
   - Os dados foram explorados, verificados e preparados.

2. **Modelagem com Regressão Linear**:
   - Modelos foram treinados para prever o volume de reservas com base em variáveis fornecidas.

3. **Simulação com Bootstrapping**:
   - 1000 amostragens aleatórias foram feitas para cada região.
   - Para cada amostra, foi estimado o lucro total com base nas previsões.

4. **Avaliação de risco**:
   - Calculamos:
     - Lucro médio esperado
     - Intervalo de confiança
     - Risco de perda (chance do lucro ser negativo)

---

## 🏆 Conclusão

Com base nos resultados obtidos:

- A **Região B** apresentou o **melhor equilíbrio entre lucro médio esperado e baixo risco de perdas**.
- Foi a região **mais recomendada para investimento**, com um bom retorno potencial e risco controlado.

---

## 📁 Estrutura do Projeto
oil-reserve-optimizer/
│
├── data/ # Dados brutos e tratados
├── notebooks/ # Análises exploratórias e modelagem
├── src/ # Scripts e funções auxiliares
├── README.md # Este documento
└── requirements.txt # Bibliotecas utilizadas


---

## 👨‍💻 Autor

**Lucas Coelho**  
Data Scientist | Especialista em Projetos com IA e Análise de Dados   • [GitHub](https://github.com/Coringadev22)

---

## 📌 Observação

Este projeto foi desenvolvido como parte da **Sprint 10** do bootcamp de Data Science da TripleTen, com foco em **aprendizado prático de modelagem preditiva e simulação de risco**.


