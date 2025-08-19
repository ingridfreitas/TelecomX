# 📊 Análise de Evasão de Clientes (Churn) - Telecom X

## 📄 Descrição do Projeto
Este projeto faz parte do desafio "Churn de Clientes" da Telecom X. O objetivo principal foi realizar uma análise exploratória de dados (EDA) para identificar os principais fatores que contribuem para a evasão de clientes. Utilizando Python e as bibliotecas pandas, matplotlib e seaborn, o projeto abrangeu as etapas de ETL (Extração, Transformação e Carga) e gerou insights valiosos para a equipe de Data Science, que utilizará essas informações para a construção de modelos preditivos e estratégias de retenção.

## 🚀 O que foi Praticado
- **Extração:** Coleta de dados de uma API utilizando a biblioteca requests.
- **Transformação:** Limpeza e tratamento de dados, incluindo a conversão de tipos, manipulação de valores vazios e criação de novas variáveis.
- **Análise Exploratória de Dados (EDA):** Geração de estatísticas descritivas, criação de visualizações estratégicas e identificação de padrões e tendências.
- **Comunicação de Resultados:** Elaboração de um relatório com insights acionáveis e recomendações para o negócio.

## 📊 Análise e Insights
A análise dos dados revelou insights importantes sobre o comportamento dos clientes que cancelaram o serviço:
- **Taxa de Churn:** A análise inicial revelou uma taxa de churn de aproximadamente XX%, indicando a urgência do problema.
- **Contrato e Fidelidade:** Clientes com contratos mensais apresentam uma taxa de churn significativamente mais alta, sugerindo uma menor fidelização.
- **Forma de Pagamento:** O método de pagamento via Cheque Eletrônico e Cheque Correio está fortemente associado à evasão, enquanto métodos automáticos, como cartão de crédito, estão ligados a uma maior retenção.
- **Tempo de Contrato:** O boxplot de tempo_contrato_meses mostrou que a maior parte da evasão ocorre nos estágios iniciais do relacionamento com o cliente.

## 📈 Visualizações Chave
As seguintes visualizações foram essenciais para a análise:
- **Gráfico de Barras:** Utilizado para comparar a taxa de churn entre diferentes categorias (tipo de contrato, forma de pagamento, etc.).
- **Boxplot:** Empregado para analisar a distribuição de variáveis numéricas, como gasto_total e tempo_contrato_meses, entre clientes que cancelaram e os que não cancelaram.

## 🛠️ Tecnologias e Bibliotecas
`Python`
`pandas`
`requests`
`matplotlib`
`seaborn`

## 🎯 Próximos Passos
Os insights gerados por esta análise exploratória servirão de base para o desenvolvimento de modelos preditivos, que terão como objetivo:
- Identificar clientes com alto risco de churn antes que eles cancelem.
- Permitir que a Telecom X crie ações de retenção proativas e personalizadas.

## 🚀 Como Executar
> Clone este repositório ou baixe o notebook.
> 
> Abra o arquivo TelecomX_BR.ipynb com Jupyter Notebook ou Google Colab.
> 
> Execute as células sequencialmente para acompanhar toda a análise.

## 📎 Arquivo
- `TelecomX_BR.ipynb`
