# Português

# HR Analytics Dashboard - Power BI

## Visão Geral
Este projeto consiste em um Dashboard de Recursos Humanos desenvolvido no Power BI, com foco em análise de headcount, turnover, salários e perfil demográfico dos colaboradores.
O dashboard foi pensado para apoiar gestores de RH e lideranças na tomada de decisão baseada em dados.

## Objetivo do Projeto
- Monitorar o headcount atual e total
- Analisar turnover absoluto e percentual
- Comparar métricas por Departamento, Cargo, Gênero e Formação
- Avaliar salário médio e idade média dos colaboradores ativos
- Identificar áreas com maior risco de rotatividade

## Dataset
- Fonte: IBM HR Analytics Employee Attrition Dataset
- Tipo de dados: Fictícios
- Formato: CSV
- Quantidade de registros: ~1.470 colaboradores
O dataset contém informações demográficas, organizacionais e salariais dos colaboradores, incluindo status de desligamento (Attrition).

## Modelagem de Dados
- Tabela Fato
  - F_Employee
- Tabelas Dimensão
  - D_Department
  - D_JobRole
  - D_JobLevel
  - D_Education
  - D_EducationField
  - D_Gender
  - D_MaritalStatus
  - D_Overtime
  - D_BusinessTravel
Essa abordagem garante:
- Melhor performance
- Clareza do modelo
- Facilidade de manutenção e escalabilidade

## Métricas DAX Utilizadas
- Headcount Atual
- Headcount Total
- Turnover
- Turnover %
- Headcount por Departamento
- Headcount por Cargo
- Salário Médio (Total e apenas colaboradores ativos)
- Idade Média (Total e apenas colaboradores ativos)
As métricas foram calculadas priorizando medidas DAX, evitando o uso direto de colunas calculadas.

## Visualizações Utilizadas
- Cards: KPIs principais (Headcount, Turnover, Salários, Idade)
- Gráficos de Barras Horizontais: Comparações por Departamento e Cargo
- Gráfico de Rosca: Distribuição por Gênero
- Segmentadores (Slicers): Filtros por Departamento, Cargo, Gênero e Formação
O layout foi organizado seguindo boas práticas de Data Visualization e Storytelling Analítico.

## Ferramentas Utilizadas
- Power BI Desktop
- Power Query
- DAX
- Excel (estrutura original do dataset)
- GitHub

## Como Utilizar o Projeto
1. Faça o download do arquivo .pbix
2. Abra o arquivo no Power BI Desktop
3. Utilize os filtros laterais para segmentar os dados
4. Interaja com os gráficos para explorar os insights

 ## Aprendizados
 - Aplicação prática de modelagem dimensional (modelo estrela)
 - Criação de métricas de RH utilizando DAX
 - Tratamento e organização de dados no Power Query
 - Construção de dashboards orientados à tomada de decisão
 - Desenvolvimento de storytelling analítico focado em negócio

## Dashboard Preview
Imagem

## Dashboard Online
Acesse a Dashboard interativa clicando aqui: [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDkzYTE0ZTYtNzY5My00NmZhLWIyYjQtNWZkNmRkODE2Nzk1IiwidCI6IjM2ODZiNmU4LWI3OTgtNDBkYy04NGI4LTkwOTNkN2FiZWIzYiJ9)

# English

# Overview
This project presents an HR Analytics Dashboard built using Power BI, focused on analyzing headcount, turnover, salary, and employee demographics.
The dashboard was designed to support HR managers and business leaders in data-driven decision-making.

## Project Objectives
- Monitor current and total headcount
- Analyze turnover volume and percentage
- Compare metrics by Department, Job Role, Gender, and Education
- Evaluate average salary and average age of active employees
- Identify departments with higher attrition risk

## Dataset
- Source: IBM HR Analytics Employee Attrition Dataset
- Data Type: Fictional
- Format: CSV
- Records: ~1,470 employees
The dataset includes demographic, organizational, and compensation data, as well as employee attrition status.

## Data Modeling
- Fact Table
  - F_Employee
- Dimension Tables
  - D_Department
  - D_JobRole
  - D_JobLevel
  - D_Education
  - D_EducationField
  - D_Gender
  - D_MaritalStatus
  - D_Overtime
  - D_BusinessTravel
This structure ensures:
- Better performance
- Clear relationships
- Scalability and maintainability

## DAX Measures
- Current Headcount
- Total Headcount
- Turnover
- Turnover %
- Headcount by Department
- Headcount by Job Role
- Average Salary (Total and Active Employees)
- Average Age (Total and Active Employees)
All KPIs were built using DAX measures, following best practices.

## Visualizations
- Cards: Key HR KPIs
- Horizontal Bar Charts: Department and Job Role comparisons
- Donut Chart: Gender distribution
- Slicers: Filters for Department, Job Role, Gender, and Education
The layout follows data visualization best practices with a clear analytical narrative.

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Excel
- GitHub

## How to Use
1. Download the .pbix file
2. Open it using Power BI Desktop
3. Use the slicers to filter the data
4. Interact with the visuals to explore insights

## Key Learnings
- Practical application of dimensional modeling (star schema)
- Development of HR KPIs using DAX
- Data cleaning and preparation with Power Query
- Building dashboards focused on business insights
- Applying analytical storytelling techniques

## Dashboard Preview
Imagem

## Live Dashboard
Access the interactive Power BI dashboard here: [Click to view dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDkzYTE0ZTYtNzY5My00NmZhLWIyYjQtNWZkNmRkODE2Nzk1IiwidCI6IjM2ODZiNmU4LWI3OTgtNDBkYy04NGI4LTkwOTNkN2FiZWIzYiJ9)
