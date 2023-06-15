INSERT INTO [NOME DA TABELA] // PARA ADICIONAR ATRIBUTOS NOS ITENS DA TABELA
VALUES // PARA ATRIBUIR OS OS VALORES DO ATRIBUTO DOS ITENS NA TABELA
SELECT * FROM [NOME DA TABELA] // PARA CONSULTAR A TABELA
CREATE DATABASE [NOME DA BANSO DE DADOS] // PARA CRIAR DATABASE
CREATE TABLE [NOME DA TABELA] // PARA CRIAR TABELA
UPDATE[NOME DA TABELA]
SET [SELECIONA O CAMPO DA TABELA] = ADICIONAR O NOVO VALOR
WHERE[O LOCAL ONDE SERA REALIZADA A AUTERAÇÃO] = '544333';
SELECT [SABOR], [PRECO DE LISTA] FROM[TABELA DE PRODUTOS]; // PARA PESQUISAR COLUNAS
DELETE FROM[NOME DA TABELA] WHERE[NOME DA COLUNA A SER DELETADA] = 'NUMERO DE IDENTIDICAÇÃO DA COLUNA';
PRIMARY KEY

alter table [tabela de produto]
alter column [codigo do produto] varchar(20) not null;

ALTER TABLE [tabela de produto]
ADD CONSTRAINT pk_tabela_de_produto PRIMARY KEY CLUSTERED ([codigo de produto]);







a chave primaria nao pode ser repetida, entao uma chave primaria nao se repete 



select *from [Tabela de Produto]

INSERT INTO [Tabela de Produto]
(
[CODIGO DO PRODUTO],
[NOME DO PRODUTO],
[EMBALAGEM],
[TAMANHO],
[SABOR],
[PRECO DE LISTA]
)
VALUES
(
'544931','frescor do verao - 350 ml - limao',
'lata',
'350 ml',
'limao',
3.00
);


delete from [Tabela de Produto]
where [codigo do produto]='1037797';

UPDATE[Tabela de Produto]
SET [EMBALAGEM] = 'PET',[sabor] = 'UVA'
where[codigo do produto] = 1088126;
