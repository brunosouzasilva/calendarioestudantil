# Caso de Uso: Excluir Disciplina

## Ator Primário: 

+ Estudante

## Stakeholders:

+ Estudante: Quer facilidade, sem erros de formatação da disciplina.

## Precondições:

+ O sistema deve conter uma grade, pelo menos, com disciplinas e horários.

Quando o usuário tenta criar uma disciplina, ele acessa um local de criação de disciplinas, uma interface bastante prática e rápida. Que irá formatar o nome da disciplina na grade de horários. A sessão do usuário, no caso o estudante, é atualizada e organizada pós preenchimento.

# Fluxo Básico:

1. O estudante aciona a aplicação.
+ O estudante aciona o evento excluir disciplina (interface prática de opções).
+ O sistema fornece algumas opções para remover.
+ O sistema registra as deleções feitas pelo usuário.
+ O sistema atualize e organiza a grade.
  + Caso não exista mais grade o sistema avisa ao usuário.
  + O sistema entra no modo, esperando por novas criações de disciplina.
     + O sistema verificou que pós deleções ainda existe grade de horários montada.
     + O sistema apresenta a nova grade, pós deleções.
     + O usuário poderá checar se está tudo certo. E se organizar a partir da sua grade de disciplinas.
