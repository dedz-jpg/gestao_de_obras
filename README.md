# Gestão de Obras - DedzCorp
Dashboard de estudo para análise de dados e criação de dashboard.

![gestao de obras.png](https://github.com/dedz-jpg/gestao_de_obras/blob/main/gestão%20de%20obras.png)

🇧🇷 Português

📌 Visão Geral

Este projeto consiste em um dashboard de Gestão de Obras desenvolvido no Power BI, com foco em acompanhamento de prazo, atrasos, riscos de estouro e status de empreendimentos imobiliários.

O objetivo principal é oferecer uma visão clara e executiva para tomada de decisão, permitindo identificar rapidamente:

- Empreendimentos entregues

- Empreendimentos em atraso

- Empreendimentos pendentes com risco

- Desvio médio de obra em meses

O dashboard foi estruturado para atender tanto gestores quanto times operacionais, combinando KPIs, gráficos analíticos e tabela detalhada.

🎯 Principais Indicadores (KPIs)

- Total de Empreendimentos

- Total Entregues

- Total em Atraso

- Total Pendentes

Esses indicadores fornecem uma leitura imediata do cenário geral da carteira de obras.

📈 Visualizações Desenvolvidas

1️⃣ Desvio de Obra (Meses)

- Gráfico de barras horizontais que apresenta o tempo de atraso por empreendimento, ordenado do maior para o menor.

- Destaque visual para obras em estouro

- Facilita a identificação de gargalos críticos

2️⃣ Previsão x Lançamento

- Gráfico combinado de colunas empilhadas + linha, onde:

- Colunas representam a quantidade de empreendimentos por status ao longo dos anos

- Linha representa o Atraso Médio (em meses)

- Esse visual permite analisar a evolução temporal dos atrasos e a relação entre entregas, pendências e riscos.

3️⃣ Tabela Analítica de Empreendimentos

Tabela detalhada contendo:

- Nome do empreendimento

- Status da obra

- Situação de prazo (No prazo, Risco de estouro, Estouro)

- Tempo em atraso (meses)

- Inclui ícones de alerta para facilitar a leitura executiva e priorização.

🧠 Regras de Negócio Aplicadas

- Empreendimentos com tempo em atraso = 0 não podem ter entrega anterior à previsão

- Empreendimentos entregues respeitam a data de previsão

- Empreendimentos pendentes e em atraso podem apresentar estouro de prazo
 
- Cálculo de Atraso Médio considera apenas obras com atraso (> 0)

🛠️ Tecnologias Utilizadas

- Power BI

- DAX para medidas e regras de negócio

- Modelagem de dados orientada à análise temporal

🚀 Futuras Evoluções

- Inclusão de forecast de entrega

- Análise por região ou tipologia

- Indicadores financeiros integrados (custo x atraso)

🇺🇸 English

📌 Overview

This project is a Construction Management Dashboard built in Power BI, focused on monitoring deadlines, delays, overdue risks, and project status in real estate developments.

The main goal is to provide a clear, executive-level view to support decision-making, enabling quick identification of:

- Delivered projects

- Delayed projects

- Pending projects with risk

- Average construction delay (in months)

- The dashboard is designed for both executive stakeholders and operational teams, combining KPIs, analytical charts, and a detailed table.

🎯 Key Indicators (KPIs)

- Total Projects

- Total Delivered

- Total Delayed

- Total Pending

- These KPIs provide an immediate snapshot of the overall construction portfolio.

📈 Developed Visuals

1️⃣ Construction Deviation (Months)

- Horizontal bar chart showing delay time per project, sorted from highest to lowest.

- Visual highlight for overdue projects

- Helps identify critical bottlenecks

2️⃣ Forecast vs Launch

- Combined stacked column + line chart, where:

- Columns represent the number of projects by status over time

- Line represents the Average Delay (months)

- This visual enables temporal analysis of delays and the relationship between deliveries, pending projects, and risks.

3️⃣ Analytical Project Table

Detailed table containing:

- Project name

- Construction status

- Deadline situation (On time, Risk, Overdue)

- Delay time (months)

- Includes alert icons to improve executive readability and prioritization.

🧠 Business Rules Applied

- Projects with delay time = 0 cannot be delivered before the forecast date

- Delivered projects respect forecast dates

- Pending and delayed projects may exceed forecast deadlines

- Average Delay calculation considers only delayed projects (> 0)

🛠️ Technologies Used

- Power BI

- DAX for measures and business logic

- Time-oriented data modeling

🚀 Future Improvements

- Delivery forecasting

- Regional or typology analysis

- Financial indicators integration (cost vs delay)
