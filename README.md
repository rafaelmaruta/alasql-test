# Teste com AlaSQL

Temos duas tabelas em um servidor SQL, com a seguinte estrutura:

## Tabela A:
   - a: Numeração automática, `primary key`
   - b: `varchar (20)`

## Tabela B:
   - a: `foreign key` contra a **Tabela A**
   - c: `varchar (100)`

1. Fazer **join** das duas tabelas, mostrando as colunas [a, b, c] para todos
registros da **Tabela B**.

2. Fazer **join** das duas tabelas, mostrando as mesmas colunas, mas também para os casos que tenham "a" na **Tabela A**, mas não na **Tabela B**.

3. Contagem de quantas vezes ocorrem diferentes valores de "a" na tabela "b".