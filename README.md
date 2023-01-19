# projeto individual BD

Este projeto foi desenvolvido para a aprovação de competencia do módulo 4- Banco de dados da plataforma Resilia em parceria com o Senac no programa Programadores Cariocas através da modelagem de um banco de dados de uma instituição de ensino.

Sobre o projeto:
## Modelo conceitual
![modelo conceitual img](https://user-images.githubusercontent.com/112868366/213519168-954a0535-c35b-4b36-9e87-de5aeda5ada2.png)

## Modelo lógico
![modelo logico img](https://user-images.githubusercontent.com/112868366/213519176-edae2a63-7ab5-44a9-aa7c-160d0255cd20.png)

## Existem outras entidades além dessas três?
Sim. Há também as entidades: disciplina, professor, salas e turnos.

## Quais são os principais campos e tipos?

 Curso(PK) com os tipos: nome e modalidade.
 Disciplina (PK) com os tipos: programação e professor.
 Professor(PK) com os tipos: nome, sexo e especialidade.
 Turnos (PK) com os tipos: turnos.
 Turma (PK) com os tipos: disciplina, curso, data de inicio, salas e turnos.
 Salas (PK) com os tipos: andares e nº de salas.
 Alunos (PK) com os tipo: nome, matricula, endereço, cep e telefone.

## Como essas entidades estão relacionadas?
Curso está relacionado à disciplina e curso.
Disciplina está relacionada ao professor.
Professor está relacionada ao aluno.
Aluno está relacionado às turmas.
Turmas estão relacionadas às salas.
Salas estão relacionadas aos turnos.
Turnos estão relacionados ao curso.
