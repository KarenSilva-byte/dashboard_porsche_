Dashboard Porsche — Análise de Vendas

## 1. Sobre o projeto

Este projeto tem como objetivo desenvolver uma dashboard
interativa para analisar dados de vendas de veículos Porsche.

A dashboard permite identificar os modelos mais vendidos,
analisar o desempenho comercial por cidade e descobrir
quais anos-modelo possuem maior volume de vendas.

O projeto foi desenvolvido utilizando inteligência artificial
como ferramenta de apoio na criação da interface e
na visualização dos dados.

## 2. Objetivo da análise

Transformar os dados de vendas em informações visuais
que facilitem a identificação de tendências de mercado
e apoiem a tomada de decisões comerciais.

## 3. Perguntas de negócio

Para desenvolver a dashboard, foram escolhidas três
perguntas principais:

### 3.1. Quais são os modelos Porsche mais vendidos por cidade?

Essa análise permite identificar quais modelos possuem
maior demanda em cada cidade.

A escolha dessa pergunta tem como objetivo compreender
as preferências dos consumidores em diferentes regiões,
auxiliando no planejamento comercial e na distribuição
de veículos.

### 3.2. Qual ano-modelo apresentou o maior volume de vendas?

Essa pergunta busca identificar quais anos-modelo
registraram o maior número de vendas.

A análise permite compreender a preferência dos
consumidores por determinados anos-modelo e observar
possíveis tendências de mercado.

### 3.3. Quais são os modelos Porsche mais populares em cada cidade?

O objetivo é comparar o desempenho dos diferentes
modelos nas cidades presentes na base de dados.

Essa análise ajuda a identificar padrões regionais
de consumo e oportunidades comerciais.

## 4. Indicadores de desempenho (KPIs)

Foram utilizados os seguintes indicadores:

- Total de veículos vendidos.
- Receita total de vendas.
- Ticket médio por veículo.
- Modelo Porsche mais vendido.

## 5. Utilização da Inteligência Artificial

Para desenvolver a dashboard, utilizei o ChatGPT
como ferramenta de apoio na criação da interface
e na organização das visualizações dos dados.

### 5.1. Prompt utilizado

O prompt utilizado para solicitar a criação
da dashboard foi:

"Utilizando o recurso de Canvas, renderize uma
dashboard em HTML.

Filtros:
- Modelo da Porsche
- Model Year
- City
- Pay Method

Perguntas de negócio e KPIs:

1. Quais os principais modelos de carro vendidos
por cidade?

2. Qual o ano-modelo de carro que mais vendeu
em determinado período?

3. Quais insights podem ser obtidos sobre os
modelos mais populares em cada cidade?

Sobre o UI/UX, utilize como referência o site
oficial da Porsche Brasil.

A interface deve apresentar um visual elegante,
moderno e refinado."

### 5.2. Desenvolvimento da dashboard

A inteligência artificial foi utilizada para
auxiliar na criação do código HTML e na
estruturação das visualizações.

A proposta visual foi inspirada na identidade
da Porsche, priorizando uma interface
minimalista, elegante e organizada.

A dashboard foi disponibilizada em um arquivo
HTML e posteriormente publicada no GitHub.

### 5.3. Alterações no prompt

A dashboard foi desenvolvida a partir de um
prompt principal, que já continha os filtros,
as perguntas de negócio e as orientações
de identidade visual.

Não foram realizadas alterações adicionais
no prompt original durante esta etapa.

## 6. Tratamento da Base de Dados

### 6.1. Origem dos dados

Foi utilizada uma planilha Excel contendo
100 registros de vendas de veículos Porsche.

A base possui informações sobre modelos,
anos-modelo, preços, cidades, formas de
pagamento e datas das vendas.

### 6.2. Preparação dos dados

Para desenvolver a dashboard, foram
selecionadas as seguintes informações:

- Modelo do veículo (PorscheModelSanitized)
- Ano-modelo (ModelYearSanitized)
- Cidade (CitySanitized)
- Estado (StateSanitized)
- Método de pagamento (PayMethodSanitized)
- Preço de venda (SalesPriceSanitized)
- Data da venda (SaleDateSanitized)

Essas informações foram organizadas em
uma estrutura de dados JavaScript e
incorporadas diretamente ao arquivo HTML.

### 6.3. Tratamento de datas inválidas

Durante a análise, foram identificados
24 registros com datas inválidas.

Esses registros foram mantidos nas
análises gerais de vendas.

Entretanto, quando o usuário aplica
um filtro por período, os registros
com datas inválidas são desconsiderados.

Essa decisão permite preservar os dados
disponíveis sem comprometer a análise
temporal.

### 6.4. Organização das informações

Os dados foram utilizados para calcular:

- Quantidade total de veículos vendidos.
- Receita total das vendas.
- Ticket médio por veículo.
- Ranking dos modelos mais vendidos.
- Distribuição de vendas por ano-modelo.
- Modelos mais vendidos por cidade.

Os resultados são atualizados conforme
os filtros selecionados pelo usuário.

### 6.5. Limitações da base

A base contém apenas 100 registros,
o que limita algumas conclusões
sobre preferências regionais.

Por esse motivo, os resultados devem
ser interpretados como tendências
observadas na amostra, e não como
representações definitivas do mercado.

Os valores monetários são apresentados
em dólares americanos (USD), conforme
a base original.

## 7. Ferramentas Utilizadas

### ChatGPT
Utilizado como ferramenta de inteligência
artificial para auxiliar no desenvolvimento
da dashboard, na criação do código HTML
e na organização das análises.

O projeto foi desenvolvido com auxílio
do ChatGPT, sem utilização do Canvas
tradicional ou de agentes com skills.

### HTML, CSS e JavaScript
- HTML: estrutura da dashboard.
- CSS: estilização e identidade visual.
- JavaScript: interatividade, filtros
  e atualização dos indicadores.

### Microsoft Excel
Utilizado como formato da base de dados
original contendo os registros de vendas.

### GitHub
Utilizado para armazenar o código-fonte
em um repositório público.

### GitHub Pages
Utilizado para publicar a dashboard
na internet e permitir seu acesso
por meio de um navegador.

## 8. Acesso ao Projeto

### Repositório GitHub

https://github.com/KarenSilva-byte/dashboard_porsche_

### Dashboard Publicada

https://karensilva-byte.github.io/dashboard_porsche_/

## 9. Conclusão

O desenvolvimento deste projeto permitiu
aplicar conceitos de análise de dados,
indicadores de desempenho e visualização
de informações.

A utilização da inteligência artificial
auxiliou na construção de uma dashboard
interativa, permitindo transformar dados
de vendas em informações úteis para
a tomada de decisões comerciais.



Esses indicadores permitem acompanhar o desempenho
geral das vendas e facilitam a interpretação dos dados.
