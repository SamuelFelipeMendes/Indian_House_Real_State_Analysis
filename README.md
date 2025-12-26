#  Indian House Real Estate Analysis

Este projeto realiza uma **Tratamento de valores e de dados** para realizar em sequência uma **análise exploratória e preditiva** de dados de imóveis na Índia, com o objetivo de identificar padrões de preços, características mais relevantes e possíveis anomalias (outliers) nos dados.  

A análise utiliza **Python** e bibliotecas populares de ciência de dados para limpeza, visualização e modelagem.

---

##  Objetivos do Projeto

1. **Explorar** o conjunto de dados de imóveis (`DataHouse.csv`);
2. **Tratar valores ausentes e outliers** para garantir a qualidade dos dados;
3. **Visualizar correlações** entre variáveis (ex.: área, número de quartos, localização, preço);
4. **Gerar insights** úteis para investidores e compradores.

---

##  Estrutura do Repositório

```bash
Indian_House_Real_State_Analysis/
│
├── DataHouse.csv              # Conjunto de dados com informações sobre imóveis
├── main.py                    # Script principal da análise (limpeza, modelagem e visualização)
├── teste_de_outliers.py       # Identificação e tratamento de outliers
├── teste_projeto.py           # Testes ou protótipos para validação de código
└── README.md                  # Documentação do projeto
```

---

## ⚙️ Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** – manipulação e limpeza de dados  
- **NumPy** – cálculos numéricos  
- **Matplotlib / Seaborn** – visualizações gráficas  
- **Scikit-learn** – modelagem e machine learning  

---

##  Detecção de Outliers

O script `teste_de_outliers.py` aplica métodos estatísticos (como IQR ou Z-Score) para identificar e remover valores atípicos do conjunto de dados, garantindo maior precisão nas análises.

---

## 📈 Possíveis Extensões Futuras

- Implementar modelo de **regressão linear ou random forest** para prever preços;  
- Criar **dashboard interativo** (com Streamlit ou Power BI);  
- Adicionar **análise geoespacial** de preços por região.

---

##  Autor

**Samuel Felipe Mendes e Victor Ribeiro Ferreira**  
 Projeto Acadêmico de estudo em análise, Maniopulação e tratamento de dados
🔗 [GitHub Profile](https://github.com/vrferreira20)
🔗 [GitHub Profile](https://github.com/SamuelFelipeMendes)

---

