# SG-UNI

Projeto de Extensão da UNINOVE, feito pela equipe da Atena Tech (empresa fictícia criada para o trabalho).
O SG-UNI é um sistema de gestão acadêmica pensado para organizar alunos, professores, cursos, disciplinas, turmas e matrículas. Neste repositório estão o programa em C# e os scripts do banco de dados.

Orientação: Prof. Priscilla Viana Cunha

## Quem fez

- Andrey Rodrigues Campos (RA 2221100108)
- Pedro Hugo Carvalho Rosa (RA 2225200774)
- Vitor Alves da Silva (RA 2225103471)
- Saulo Alves Costa Souza (RA 2225202615)
- Elnatan Cainan de Jesus (RA 2225203024)

## O programa em C#

É um programa de console onde dá para cadastrar alunos, ver as turmas e matricular cada aluno em uma turma. O sistema não deixa matricular o mesmo aluno duas vezes na mesma turma.
Os dados ficam guardados só enquanto o programa está aberto.
Para rodar, é só ter o .NET instalado, abrir a pasta `CSharp` no terminal e usar:

## O banco de dados

Feito no SQL Server, com seis tabelas: Curso, Aluno, Professor, Disciplina, Turma e Matrícula. Os scripts estão na pasta `BancoDeDados` e devem ser executados nesta ordem:

1. `01_Criacao_Banco_Tabelas.sql`
2. `02_Insercao_Dados.sql`
3. `03_Consultas.sql`
