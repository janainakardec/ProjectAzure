# ProjectAzure
Processamento de Dados Simplificado com Power BI
O Desafio consiste na criação de um Banco de Dados MySQL na Azure, com conexão ao Workbench e Power BI. Havia as opções de implementação através do Workbench ou o próprio Bash na Azure, particularmente preferi a segunda. Posteriormente, foi feita uma transformação dos dados utilizando Power BI, desde a limpeza até a construção de relatórios simples.
Tecnologias utilizadas:
Microsoft Azure
MySQL Workbench
Power BI

As etapas seguidas foram:
Criação de uma instância na Azure para MySQL
Criação de um  Banco de dados com base disponível no github (julianazanelatto)
Integração do Power BI com MySQL no Azure 
Verificação de problemas na base a fim de realizar a transformação dos dados
Construção de Relatório utilizando Power BI
Publicação no GitHub.

Diretrizes para transformação dos dados

Verificação dos cabeçalhos e tipos de dados;
Modificação dos valores monetários para o tipo double preciso;
Verificação da existência dos nulos e analise a remoção;
Verificação de gerentes por departamento;
Verificação do número de horas dos projetos;
Separação colunas complexas (exemplo: data e endereço);
Mesclagem de employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla teve como base a tabela employee;
Realização da junção dos colaboradores e respectivos nomes dos gerentes, utilizando o Power BI através da mesclagem de tabelas;
Mesclagem das colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores;
Mesclagem dos nomes de departamentos e localização;
Observação: O comando mesclar cria uma nova tabela à partir das informações enquanto o atribuir cria uma nova coluna em uma mesma tabela. Ao atribuir você pode alterar dados de forma ineficiente na modelagem.
Agrupamento de dados a fim de saber quantos colaboradores existem por gerente;
Eliminação das colunas desnecessárias, que não serão usadas no relatório, de cada tabela.
