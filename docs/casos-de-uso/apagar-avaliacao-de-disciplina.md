# Apagar avaliação de disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Stakeholders e seus interesses__:

* Usuário: deseja apagar uma avaliação de uma disciplina.

__Pré-Condições__: Ao menos uma avaliação está cadastrada

__Pós-Condições__: Avaliação é excluída; notificações correspondentes são excluídas.

## Fluxo básico

1. O usuário seleciona a avaliação que deseja excluir.
2. O usuário confirma a exclusão.
3. O sistema exclui a avaliação e os lembretes correspondentes.

## Fluxo alternativo

`2a`. O usuário não confirma a exclusão

  1. A avaliação e os lembretes são mantidos. Nada é excluído ou alterado.
  2. O caso de uso é encerrado.
