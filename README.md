# Criando-um-Dashboard-de-Vendas-do-Xbox
Desafio: Dashboard no Excel – Bootcamp DIO & Heineken 

## Objetivo: 
O objetivo deste desafio foi criar um dashboard de vendas, com foco na organização e visualização de dados, transformando dados brutos em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e tomada de decisões baseadas em dados.

## Contexto:
Criar um dashboard de vendas no Excel, utilizando uma base de dados referente às assinaturas do XBOX Game Pass.

## Descrição:
1) Importação da Base de Dados:  dados obtidos através de um arquivo .xlsx contendo os campos (colunas) com a descrição das assinaturas: Subscriber ID, Name, Plan, Start Date, Day Date, Auto Renewal, Subscription Price, Subscription Type, EA Play Season Pass, EA Play Season Price, Minecraft Season Pass, Minecraft Season Price Coupon Value, Total Value.
2) Limpeza dos Dados: Remoção de duplicatas e correção dos formatos de datas e valores.
3) Criação de Tabelas Dinâmicas e Medidas Importantes: seleção de toda a base de dados, criação das tabelas dinâmicas em uma nova planilha e definição das medidas arrastando os campos para as áreas correspondentes. Esta etapa consistiu em responder as perguntas que gestor poderia fazer em relação à dinâmica das vendas dos assinantes:  Soma do Valor da Assinatura (Total de Vendas), Tipo de Assinatura, Status da Assinatura, Período (Mês/Ano); novas medidas para obter KPIs como Média do valor das assinaturas → =MÉDIA(DadosVendas[Valor]); Número de assinaturas ativas → Contagem de Status = "Yes".
4) Criar Gráficos para o Dashboard: 
•	Gráfico de Colunas: Para comparar vendas por tipo de assinatura;
•	Gráfico de Rosca: Para mostrar a distribuição de assinaturas ativas versus canceladas;
•	Linha do Tempo: Para exibir a evolução temporal das vendas;
•	Indicadores (KPI): Para destacar métricas como Total de Vendas, Assinaturas Ativas e Cancelamentos.

5) Criar Segmentação de Dados e Filtros Interativos: adição de Filtros → Segmentação de Dados para permitir a filtragem da Tabela Dinâmica por campos como Tipo de Assinatura, Status e Período. Isso facilita a navegação e a personalização das informações exibidas.
6) Ajustes Finais e apresentação do Dashboard.

## Resultado:
<img src="https://github.com/user-attachments/assets/8e6ee977-38f1-4c5a-ac17-766d57a6793d">
