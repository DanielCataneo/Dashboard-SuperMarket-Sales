# Dashboard-SuperMarket-Sales

### Objetivos do Projeto: 
Dashboard criado como projeto final para a conclusão da Eletiva de BI e LGPD na faculdade com o objetivo de aplicar o que foi aplicado em aula e de extrair KPI's importantes com uma base de dados fictícia retirada do Kaggle.

### Ferramentas Usadas:
Excel e PowerBI

### Criação da Coluna Ratings
Utilizando fórmula DAX, criei uma coluna adicional no database chamada Ratings para melhorar a vizualização do usuário acerca das avaliações dos clientes.

Fórmula --> Ratings = IF(fVendas[Rating] <= 5, "Ruim", IF(fVendas[Rating] <= 7 ,"Regular", "Excelente"))

### Dashboard
![DashBoardMyanmar](https://github.com/user-attachments/assets/55e68fd5-ba66-46a9-860a-22d5d5ed0b13)

### KPI's
Por meio desse dashboard, foi possível perceber insights importantes como o Ticket Médio, a Quantidade Média por Caixa, Faturamento durante o primeiro trimestre do ano, entre outros...
