## Telecom X - Análise de Evasão de Clientes
---

## 📄 Introdução

Este projeto é um dos requisitos para conclusão da formação "Especialização Data Science" da Alura. 

O desafio apresentado tem como base a empresa Telexom X. O objetivo é que seja analisado os padrões de dados relacionados ao "churn" (evasão de clientes) de contas com a empresa. Deve-se levar em consideração as características dos planos e dos clientes e os custos apresentados.


## 🛠️ Tecnologias utilizadas

- Python
- Biliotecas Pandas, Matplotlib, Seaborn
- Google Colab

## 📄 Arquivos Disponíveis

- `TelecomX_Data.json` — DataBase utilizada para a análise.
- `TelecomX_dicionario.md` - Dicinário com a descrição das colunas da base.
- `TelecomX_BR.ipynb` - Notebook com a análise e gráficos.
- `README.md` — Detalhamento do projeto


## 🛠️ Limpeza e Tratamento de Dados

- Extração da base de dados em JSON;
- Normalização dos dados;
- Verificação da base utilizada a fim de identificar e tratar problemas nos dados;
- Ajuste do dtype das colunas;
- Uso da função lower() para transformar os dados string para letras minúsculas;
- Tratamento de valores nulos e vazios;
- Criação da coluna "contas_diarias";
- Transformação dos dados yes/no para 1/0;
- Renomeação de colunas para facilitar o entendimento.

## 🔍 Análise Exploratória de Dados

- Verificação os principais indicadores de colunas numéricas;
- Análise do Churn por gênero, senioridade, tipo de serviço
tipo de contrato, método de pagamento, tempo de contrato e custo médio mensal;
- Criação de gráficos de pizza e barra a fim de identificar padrões.


## ✅ Conclusões e Insights
As principais características identificadas foram:
- 25,72% dos clientes na base cancelaram seus contratos;
- Os contratos com menos tempo apresentam um maior churn;
- Os serviços e tipos de contrato com maiores custos também apresentam maior churn;
- No geral, o custo médio do público que evadiu é de $74 e o que permaneceu é $61. Ou seja, a evasão está muito relacionada ao custo.
- Já para o tempo de contrato, foi possível identificar que o tempo médio ara o público que deu churn é de 17 meses e para os que permaneceram é de 37 meses. O maior público que cancelou está concentrado nos 3 primeiros meses.
- Eletronic check é o método de pagamento com o maior churn.
- Month-to-month é o tipo de contato com maior evasão.

## 💡 Recomendações

Algumas sugestões para tentar reduzir o percentual de churn:
- Negociar os tipos de contratos para que sejam mais longos, dando maior vantagem de custo para esse público.
- Entender o motivo do método "Eletronic check" estar relacionado a uma maior quantidade de churns.
- Revisão de preços a fim de nivelar com o mercado e nivelar os custos entre os próprios clientes da base que tem um custo mensal menor. E entender a motivação da diferença de valores.

---

## Desenvolvedora

Brenda Assunção (https://br.linkedin.com/in/brenda-mendes)

---

