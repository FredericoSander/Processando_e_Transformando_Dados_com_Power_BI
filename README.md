# Processando e Tranformando Dados com Power BI





limpeza e transformação dos dados 


## Tabela Departament

Relação de Ações de tratamento de dados
|Ação|Colunas afetadas|
|----|----------------|
|Exclusão de colunas|azure_company.dept_loactions, azure_company.employee,azure_company.project|
|Mesclar tabelas|Inclusão da coluna Dlocations da tabela Dept_locations|
|Renomear colunas| alteração do nome da coluna azure_company dept_locations.Dlocation para D.location
|Mesclar Colunas| União das colunas Dname com a coluna D.locations gerando uma no coluna|

## Tabela Departament locations

Relação de Ações de tratamento de dados
|Ação|Descrição|
|----|----------------|
|Remover colunas|Exclusão da coluna azure_company.departament|


## Tabela Dependent

Relação de Ações de tratamento de dados
|Ação|Colunas afetadas|
|----|----------------|
|Exclusão de coluna|azure_company.employee|

## Tabela Employee

Relação de Ações de tratamento de dados
|Ação|Colunas afetadas|
|----|----------------|
|Exclusão de coluna|azure_company.departament, azure_company.employee(Ssn), azure_company.employee(Super_ssn),azure_company.works_on|

## Tabela Project

Relação de Ações de tratamento de dados
|Ação|Colunas afetadas|
|----|----------------|
|Exclusão de coluna|azure_company.departament,azure_company.works_on|

## Tabela Works_on

Relação de Ações de tratamento de dados
|Ação|Colunas afetadas|
|----|----------------|
|Exclusão de coluna|azure_company.employeet,azure_company.Project|