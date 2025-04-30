# Desafio-Alura-Store

### 📌 Sobre
Este projeto de análise de dados foi desenvolvido como parte de um desafio da formação Data Science da Alura, com o objetivo de analisar o desempenho de 4 lojas e recomendar qual loja possui o menor desempenho para que o seu João possa vender.

### 🚩 Tecnologias e Bibliotecas Utilizadas
- Python 3.11
- Pandas - Manipulação de dados
- Matplotlib - Visualização gráfica

### 📊 Etapas da Análise
1. 💵 Faturamento Total por Loja
Soma os valores da coluna Preço para estimar o faturamento.
Gráfico de barras para facilitar a visualização
2. 🎯 Categoria doa produtos mais e menos vendidos
Agrupamento por categorias
Gráfico de barras agrupados

4. ✨ Avaliações Médias
Análise da coluna Avaliação da compra.
Gráfico de pizza
5. 🛒 Produtos Mais e Menos Vendidos
Contagem dos produtos que mais se destacam por loja.
Gráfico de de barras horizontal
6. 🚚 Frete Médio
Cálculo da média da coluna Frete de cada loja.
Gráfico de linhas

### 🛠 Como Executar o Projeto
- Clone este repositório:
````
git clone https://github.com/seu-usuario/projeto-analise-lojas.git
````
- Instale os pacotes necessários:
````
pip install -r requirements.txt
````
- Execute o notebook:
````
jupyter notebook analise_lojas.ipynb
````
### ❗ Atenção
- Certifique-se de estar usando a versão correta do Python (3.11 ou superior).
- Conexão com a internet é necessária para carregamento das urls dos datasets das lojas

## 📝 Relatório Final – Recomendação de Venda
### 📊 Introdução
Neste relatório, analisamos os dados de vendas e desempenho das quatro lojas da Alura Store, com o objetivo de recomendar ao Senhor João qual delas deve ser vendida. A análise considera:
- Análise do faturamento;
- quantidade de produtos vendidos por categoria;
- avaliações médias dos clientes;
- produtos com maior e menor saída;
- frete médio por loja.

### 💰 Faturamento Total
**Análise:**
- O gráfico de faturamento revela que a Loja 1 possui o maior volume de vendas, seguida de perto pela Loja 2. Já a Loja 4 apresenta o menor faturamento dentre todas as lojas.


- O baixo faturamento da Loja 4 sugere pouca atratividade comercial, seja por menor tráfego de clientes, problemas de marketing ou limitação de produtos. É um indicativo de ineficiência no desempenho financeiro.

### 📦 Quantidade de Produtos Vendidos por Categoria
**Análise:**
- A Loja 1 se destaca com uma boa distribuição de vendas entre várias categorias, mostrando diversidade acompanhada da Loja 4 . A Loja 2 vendeu menos produtos em praticamente todas as categorias.


- A falta de vendas em categorias com alta demanda indica baixa penetração de mercado e possivelmente mix de produtos pouco atrativo para os clientes da Loja 2.

###🌟 Avaliações Médias dos Clientes
**Análise:**
- Embora a Loja 1 tenha o maior total de vendas, ela tem a menor média de avaliação. Já a Loja 3, com o melhor desempenho em avaliações, tem um total de vendas um pouco menor, mas ainda assim é uma das lojas com bom desempenho em termos de satisfação do cliente.

- Apesar de uma loja ter o maior volume de vendas, ela pode precisar melhorar a qualidade do serviço ou do produto para melhorar a experiência do cliente.

### 🔝 Produtos com Maior e Menor Saída
**Análise:**
- Enquanto a Loja 3 possuem uma lista de produtos com altas quantidades vendidas, as Lojas 2 e 4 tem um número significativo de produtos menos vendidos.

- As Lojas 2 e 4 e pode estar investindo em produtos com pouca saída, resultando em baixa rotatividade e prejuízos.

### 🚚 Frete Médio por Loja
**Análise:**
- O gráfico mostra que a Loja 4 possui o menor custo médio de frete, o que pode ser um diferencial competitivo. Já a Loja 1 apresenta um dos maiores valores.


### ✅ Conclusão e Recomendação

O Senhor João deve vender a Loja 4, pois ela é a menos eficiente da rede. A venda permitirá focar os investimentos nas lojas com maior retorno, como a Loja 1 e Loja 3, maximizando os lucros e o potencial de crescimento do novo empreendimento.
