# Analise de risco de credito

## Descrição do Projeto
A empresa Credito para pessoa fisica determinou este projeto para responder a perguntas de negócios utilizando técnicas de machine learning. O objetivo é gerar insights valiosos para a empresa com base nos dados dos clientes, apoiando a tomada de decisões estratégicas.

## Ferramentas e Bibliotecas Utilizadas 🛠️
* **Python:** Linguagem principal utilizada para a análise
* **Pandas e Numpy:** Biblioteca para manipulação e análise de dados
* **Sklearn:** Biblioteca para construção de modelo de machine learning
* **Seaborn:** Biblioteca para construção de gráficos
* **Matplotlib:** Biblioteca para construção de gráficos
* **Math:** Biblioteca para calculos matematicos

## Dataset 📊
O conjunto de dados possui os seguintes campos:
* `gender` - gênero
* `age` - idade
* `income` - renda
* `family_members` - número de familiares do segurado
* `insurance_benefits` - número de pagamentos de seguro recebidos por um segurado nos últimos cinco anos

## Metodologia 📝

### Análise Exploratória de Dados
* Importar as bibliotecas necessárias
* Carregar e visualizar os dados

### Clientes Similares
* Aplicação do modelo de kNN
* Escalabilidade dos dados
* Cálculo das distâncias Euclidiana e Manhattan

### É provável que o cliente receba um pagamento do seguro?
1. **Aplicação do modelo de kNN**
   * Modelo Dummy
   * Matriz de confusão
2. **Regressão Linear**
   * Criação do modelo utilizando álgebra linear
   * Avaliação do modelo

### Ofuscando Dados
* Ofuscando os dados do conjunto
* Aplicando regressão linear no conjunto ofuscado


## Aprendizados 🎓
* **Análise de dados:** interpretação e extração de insights valiosos a partir de grandes volumes de dados
* **Preparação do conjunto:** separação do conjunto original em teste e treino, além da seleção das features e target do modelo
* **Funções:** construção e aplicação de funções para simplificar o código
* **Regras de negócios:** aplicação de regras de negócio para resolução de problemas
* **Matriz de confusão:** análise dos resultados os modelos
* **Ofuscamento de dados:** garantir a segurança dos dados
* **Álgebra linear:** criação de modelos de machine learning utilizando conceitos matemáticos
* **Machine Learning:** aplicação, seleção de hiperparâmetros, teste e avalição do modelo
* **Documentação:** elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável
* **Bibliotecas Python:** aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python
* **Data-driven decisions:** uso de insights derivados da análise de dados para orientar decisões estratégicas

## 🚀 Como Usar

1. Clone o repositório
```bash
 https://github.com/paulo-santos-ds/analise_risco_credito
```

2. Utilize o arquivo (dados.parquet)

3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Execute o notebook principal
```bash
https://github.com/paulo-santos-ds/analise_risco_credito/blob/main/dados/modelo.ipynb
```