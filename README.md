## Inserir dados de planilhas no Banco de Dados Postgres usando Python.

### Enunciado

Inserir dados de planilhas no Banco de Dados usando Python, de forma performatica.

Enunciado: Fazer um script python que leia as fontes de dados e entÃ£o insere os dados no banco de dados postgres. Incluir todas as fontes de dados do dataset da NBA e do dataset top tech startups inclua apenas o arquivo json_data.
Recomendação: Criar schema separado no banco de dados postgres e tabela separada para cada dataset. Armazenar o dado na tabela utilizando o data type que mais faÃ§a sentido (utilizar id autoincremental e data de criação do registro também). Parsear o JSON para incluir cada chave como se fosse uma coluna na tabela do Postgres. Busque utilizar boas prÃ¡ticas de programação para criar o script.
Fonte de dados: https://www.kaggle.com/datasets/loganlauton/nba-players-and-team-data
Fonte de dados: https://www.kaggle.com/datasets/chickooo/top-tech-startups-hiring-2023?select=json_data.json (somente o arquivo json_data.json).
___________________________________________________________________________________________

## Imagens da Tabela carregada

Tabela Nba_Payroll

![](imagens/tabelaNBA_Payroll_Carregada.png)

Tabela NBA_Salaries

![](imagens/tabelaNBA_Salaries_Carregada.png)

Tabela Nba_Score

![](imagens/tabelaNBA_Score_Carregada.png)

Tabela NBA_Star

![](imagens/tabelaNBA_Star_Carregada.png)

Tabela Startup

![](imagens/tabelaStartup_Carregada.png)
