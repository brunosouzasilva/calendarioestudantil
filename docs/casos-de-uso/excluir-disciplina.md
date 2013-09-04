# Excluir Disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Stakeholders e seus interesses__:

* Usuário: Quer facilidade, sem erros de formatação da disciplina.

__Pré-condições__: Ao menos uma disciplina deve estar cadastrada.

__Pós-condições__: A disciplina e todas as suas referências são excluídas (horários, avaliações, frequência etc).

## Fluxo Básico

1. O usuário seleciona a disciplina que deseja excluir.
+ O sistema pede confirmação da exclusão.
+ O sistema registra as deleções feitas pelo usuário.
+ O sistema atualize e organiza a grade.

## Fluxo alternativo

`2a`. O usuário não confirma a exclusão

  1. O registro da disciplina é mantido. Nada é alterado
  + O caso de uso é encerrado
