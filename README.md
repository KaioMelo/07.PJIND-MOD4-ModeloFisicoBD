# 07.PJIND-MOD4-ModeloFisicoBD

![BD-fisico](https://user-images.githubusercontent.com/26255727/226489679-27ec8abb-17de-41e3-b9ba-dab4c8033dc8.png)

## Existem outras entidades além dessas três?

Sim, no modelo físico que desenvolvi existem outras 3 que achei necessariamente utilizalas como, endereços e matriculas (utilizadas tanto para alunos e professores) e também tabela de cursos.

## Quais são os principais campos e tipos?

referente ao campo endereço o campo mais importande talvez seja CEP de tipo inteiro, matricula todos os campos são importande como certificado e historico escolar, todos de tipos varchar.

## Como essas entidades estão relacionadas?

As entidades matricula e endereco estão ralacionandas no tipo 1:1 e cursos tem relacionamentos 1:n com professores e 1:1 com turma.
