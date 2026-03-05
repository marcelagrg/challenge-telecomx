# Challenge Telecom X

# 📊 Análise de Evasão de Clientes (Churn) – Telecom X
Este projeto apresenta uma análise exploratória de dados com foco na evasão de clientes (churn) da empresa Telecom X.

O objetivo principal é identificar padrões e fatores associados ao cancelamento de clientes, fornecendo insights que possam apoiar estratégias de retenção e melhoria na experiência do cliente.


## 📂 Dicionário de Dados
A base de dados contém as seguintes variáveis:
- id_cliente - Identificador único do cliente
- cancelamento - Indica se o cliente cancelou o serviço (Churn)
- genero - Gênero do cliente
- idoso - Indica se o cliente tem mais de 60 anos
- possui_dependentes - Se o cliente possui dependentes
- meses_de_contrato - Tempo de permanência na empresa (em meses)
- tipo_internet - Tipo de serviço de internet (DSL, Fibra Óptica ou Nenhum)
- seguranca_online - Serviço de segurança online
- backup_online - Serviço de backup online
- protecao_dispositivo - Proteção de dispositivo
- suporte_tecnico - Suporte técnico
- streaming_tv - Serviço de streaming de TV
- streaming_filmes - Serviço de streaming de filmes
- tipo_contrato - Tipo de contrato (Mensal, Anual, Bienal)
- fatura_digital - Se utiliza faturamento digital
- metodo_pagamento - Forma de pagamento
- valor_mensal - Valor pago mensalmente
- total_gasto - Valor total acumulado pago pelo cliente


## Principais Análises Realizadas
- Análise descritiva das variáveis numéricas;
- Distribuição do churn por variáveis categóricas;
- Avaliação da relação entre tempo de contrato e cancelamento;
- Comparação da taxa de evasão por tipo de contrato;
- Impacto dos serviços adicionais na retenção;
- Análise da relação entre forma de pagamento e churn.

## Tecnologias Utilizadas
- Python 3
- Pandas - Manipulação e análise de dados
- NumPy - Operações numéricas e suporte a arrays
- Matplotlib - Visualização de dados
- Seaborn - Visualizações estatísticas
- Plotly Express - Gráficos interativos
- Requests - Requisições HTTP para obtenção da base de dados
- Jupyter Notebook / Google Colab - Ambiente de desenvolvimento

## Como rodar o projeto
  ### 1️⃣ Utilizando Google Colab
  Baixe o arquivo [Challenge_TelecomX.ipynb](https://github.com/marcelagrg/challenge-telecomx/blob/main/Challenge_TelecomX.ipynb) e abra no Colab ou acesse diretamente pelo link 'Open in Colab'.

  ### 2️⃣ Localmente utilizando Jupyter Notebook
  #### Certifique-se de ter o Python 3 instalado.
  Clone o repositório
  ```
  git clone github.com/marcelagrg/challenge-telecomx
  cd challenge-telecomx
  ```
  Instale as dependências
  ```
  pip install -r requirements.txt
  ```
  Execute o Jupyter Notebook
  ```
  jupyter notebook
```


# Principais Resultados

A análise indicou que o churn está principalmente associado a:
- Clientes nos primeiros meses de contrato;
- Contratos mensais;
- Ausência de serviços adicionais;
- Determinados métodos de pagamento (ex: cheque eletrônico).
