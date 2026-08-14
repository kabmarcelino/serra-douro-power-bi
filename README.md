# 🍷 Serra D'Ouro | Análise Comercial & Experiências

## 📌 Sobre o projeto

O Serra D'Ouro é um projeto de análise de dados desenvolvido em Power BI a partir de uma base fictícia de uma vinícola.

O dashboard foi construído com o objetivo de transformar dados comerciais, de vendas e de visitas em informações úteis para acompanhamento do desempenho do negócio, identificação de padrões de sazonalidade e análise das experiências oferecidas aos visitantes.

O projeto é composto por duas páginas: uma visão executiva dos principais indicadores da operação e uma análise detalhada de vendas e experiências.

## 🎯 Objetivos

- Acompanhar os principais indicadores comerciais da vinícola;
- Analisar a evolução mensal do faturamento e do fluxo de visitantes;
- Comparar o desempenho entre 2024 e 2025;
- Identificar períodos de maior e menor demanda;
- Analisar o perfil dos vinhos vendidos;
- Identificar as experiências com maior procura;
- Avaliar o comportamento das experiências em diferentes períodos comerciais.

## 🛠️ Ferramentas utilizadas

- Power BI
- Power Query
- DAX
- Microsoft Excel

## 🗂️ Modelagem e tratamento dos dados

O modelo foi estruturado relacionando tabelas de vendas, produtos, clientes, visitas, experiências e calendário.

Durante o desenvolvimento foram realizados processos de preparação e modelagem dos dados, criação de tabela calendário, definição de relacionamentos entre dimensões e tabelas fato e desenvolvimento de medidas para análise dos indicadores.

Entre os principais recursos utilizados estão:

- Modelagem de dados;
- Relacionamentos entre tabelas;
- Tabela calendário;
- Contexto de filtro;
- Inteligência temporal;
- Parâmetros de campo (Field Parameters);
- Formatação condicional;
- Análises de variação Year over Year (YoY).

## 📊 Principais indicadores

O dashboard acompanha indicadores como:

- Faturamento Líquido;
- Lucro Bruto;
- Margem Bruta;
- Total de Visitantes;
- Garrafas Vendidas;
- Ticket Médio;
- Receita por Visitante;
- Reservas Realizadas;
- Variação YoY de Faturamento e Visitantes;
- Média de Visitantes por Dia.

## 📈 Dashboard

### Visão Executiva

A primeira página apresenta uma visão consolidada da performance da vinícola, permitindo acompanhar faturamento, rentabilidade, fluxo de visitantes, evolução mensal e comportamento dos principais períodos comerciais.

![Dashboard Visão Executiva](VISÃO%20EXECUTIVA.png) 

### Vendas & Experiências

A segunda página aprofunda a análise do perfil das vendas e das experiências oferecidas pela vinícola, incluindo análise dinâmica dos produtos e comparação da procura por experiências entre diferentes períodos comerciais.

![Dashboard Vendas e Experiências](VENDAS%20E%20EXPERIÊNCIAS.png) 


## 💡 Principais insights

- A análise mensal permite identificar diferenças relevantes de desempenho entre 2024 e 2025 e períodos de maior variação no faturamento.
- Vinhos secos representam uma parcela significativa do volume de garrafas comercializadas.
- Degustação Clássica, Tour Essencial e Degustação Harmonizada estão entre as experiências com maior volume de visitantes.
- A análise por média diária demonstrou que períodos comerciais curtos podem apresentar intensidade de visitação superior ao período regular.
- Algumas experiências apresentam maior aderência em períodos específicos, permitindo direcionar campanhas e estratégias comerciais de acordo com a sazonalidade.

## 🧠 Conceitos e funções DAX aplicados

Durante o projeto foram utilizados recursos e funções como:

`CALCULATE` • `DIVIDE` • `DISTINCTCOUNT` • `SUMX` • `RELATED` • `SAMEPERIODLASTYEAR` • `VALUES` • Variáveis (`VAR`)

Além da criação de medidas para indicadores financeiros, operacionais, análise temporal e comparação de períodos.

## 📥 Arquivo do projeto

O arquivo `.pbix` deste projeto está disponível neste repositório para consulta da modelagem, medidas DAX e construção dos dashboards.

➡️ [Acessar arquivo Power BI](Vinícola%20Serra%20D'ouro.pbix) 

## 📁 Sobre os dados

Os dados utilizados neste projeto são fictícios e foram criados exclusivamente para fins de estudo e desenvolvimento de portfólio. Nenhuma informação representa uma empresa ou operação real.

##
 👩‍💻 Autora

**Karoline Marcelino**

Projeto desenvolvido como parte do meu portfólio de Análise de Dados e Business Intelligence.






