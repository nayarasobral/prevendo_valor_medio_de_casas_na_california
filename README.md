# Prevendo o Valor Médio de Casas na Califórnia

Este projeto utiliza dados de habitação da Califórnia para prever o valor médio de casas com base em variáveis como localização, número de quartos, idade das construções, e outras características. Modelos de aprendizado de máquina são usados para realizar as previsões e comparar o desempenho entre diferentes algoritmos.

---

## 📁 Estrutura do Projeto

- **Pré-processamento de Dados:**
  - Tratamento de valores ausentes.
  - Transformação de variáveis categóricas para numéricas.
  - Padronização e análise exploratória dos dados.

- **Análise Estatística e Visualização:**
  - Geração de histogramas para entender a distribuição das variáveis.
  - Correlação entre variáveis usando mapas de calor (heatmaps).
  - Gráficos de dispersão para explorar relações entre atributos e o valor médio das casas.

- **Modelos de Machine Learning:**
  - Comparação de diferentes algoritmos:
    - Regressão Linear.
    - Regressor de Floresta Aleatória (Random Forest).
    - ElasticNet (Combinação de Lasso e Ridge).
    - Suport Vector Regressor (SVR).
    - Ridge Regression.
    - Bayesian Ridge Regression.

- **Métricas de Avaliação:**
  - **R² Score:** Qualidade do ajuste do modelo.
  - **RMSE:** Raiz do Erro Quadrático Médio, que mede a precisão das previsões.

---

## 📊 Ferramentas e Bibliotecas Utilizadas

- **Linguagem:** Python.
- **Bibliotecas:**
  - `numpy`: Operações matemáticas e manipulação de arrays.
  - `pandas`: Manipulação e análise de dados.
  - `matplotlib` e `seaborn`: Visualização de dados.
  - `scikit-learn`: Modelagem e avaliação de aprendizado de máquina.

---

## 🔍 Análise dos Dados

1. **Dataset:** Dados de habitação da Califórnia. Cada linha representa informações sobre uma área geográfica e características de moradia.
2. **Sobre o Dataset:**  
   O conjunto de dados "California House Price", disponibilizado por Shibu Mohapatra no Kaggle, contém informações detalhadas sobre imóveis residenciais na Califórnia. Cada registro representa uma propriedade, com atributos como localização geográfica (latitude e longitude), número de quartos e banheiros, idade da construção, número de cômodos, entre outros. Este dataset é amplamente utilizado para projetos de aprendizado de máquina, especialmente em tarefas de regressão, onde o objetivo é prever o valor médio das casas com base nas características fornecidas.  
   A análise desses dados pode auxiliar no entendimento dos fatores que influenciam os preços dos imóveis na Califórnia, oferecendo insights valiosos para investidores, corretores e pesquisadores do mercado imobiliário.
3. **Tratamento Inicial:**
   - Conversão de variáveis categóricas, como `ocean_proximity`, em variáveis dummy.
   - Remoção de valores ausentes.
4. **Visualizações:**
   - Histogramas de atributos.
   - Mapas de calor para explorar correlação entre variáveis.

---

## 🌐 Dados Trabalhados

Os dados utilizados no projeto estão disponíveis no Kaggle:
[🔗 Acesse os dados aqui](https://www.kaggle.com/datasets/shibumohapatra/house-price?resource=download)

---

## ⚙️ Execução do Projeto

### 1. Clone este repositório:
```bash
git clone https://github.com/nayarasobral/prevendo_valor_medio_de_casas_na_california

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar um pull request.

📜 Licença
Este projeto está licenciado sob a MIT License.

📧 Contato
Para dúvidas ou sugestões, entre em contato:

Email: nayysobrall@gmail.com
LinkedIn: nayarasobral