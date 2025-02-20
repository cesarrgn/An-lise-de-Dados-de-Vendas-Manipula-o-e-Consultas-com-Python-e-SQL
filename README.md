Análise de Dados de Vendas com Python e SQL
Este projeto tem como objetivo realizar a manipulação e análise de dados de vendas utilizando Python e SQL. A base de dados utilizada contém informações sobre vendas de produtos, como ID da compra, ID do cliente, produto, valor unitário e quantidade vendida.

Objetivo
O objetivo principal é demonstrar como:

Carregar dados de um arquivo CSV.

Manipular e analisar os dados usando Python e Pandas.

Utilizar SQL para realizar consultas e análises no banco de dados.

Ferramentas Utilizadas
Python: Linguagem de programação utilizada para manipulação de dados.

Pandas: Biblioteca para manipulação e análise de dados.

SQLite: Banco de dados embutido para executar consultas SQL.

Jupyter Notebook: Ambiente interativo para execução do código.

Estrutura do Projeto
O projeto consiste em:

Carregamento dos dados: Leitura do arquivo CSV TB_VENDAS_TAREFA.csv.

Manipulação dos dados: Uso do Pandas para preparar os dados.

Consultas SQL: Execução de consultas SQL para análise dos dados.

Como Executar o Projeto
Pré-requisitos
Python 3.x instalado.

Bibliotecas necessárias: pandas, sqlite3.

Jupyter Notebook (opcional, mas recomendado).

Passos para Execução
Clone o repositório (se aplicável):

bash
Copy
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Instale as dependências:
Se necessário, instale as bibliotecas Python:

bash
Copy
pip install pandas
Execute o código:

Abra o arquivo .ipynb no Jupyter Notebook.

Execute as células na ordem para carregar os dados, manipular e realizar as consultas SQL.

Exemplos de Consultas SQL
Aqui estão algumas consultas SQL realizadas no projeto:

Selecionar todos os dados da tabela:

sql
Copy
SELECT * FROM tb_vendas;
Calcular o valor total gasto por compra:

sql
Copy
SELECT ID_COMPRA, ID_CLIENTE, (VALOR_UNID * UNIDADES) AS valor_total_gasto
FROM tb_vendas;
Calcular a média do valor total gasto:

sql
Copy
SELECT AVG(VALOR_UNID * UNIDADES) AS media_valor_total_gasto
FROM tb_vendas;
Resultados Esperados
Carregamento e manipulação dos dados de vendas.

Execução de consultas SQL para análise dos dados.

Geração de insights a partir dos dados, como valor total gasto por compra e média de gastos.

Contribuição
Se você quiser contribuir para este projeto, siga os passos abaixo:

Faça um fork do repositório.

Crie uma branch para sua feature (git checkout -b feature/nova-feature).

Commit suas mudanças (git commit -m 'Adicionando nova feature').

Push para a branch (git push origin feature/nova-feature).

Abra um Pull Request.


