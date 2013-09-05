# Editar avaliação de disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Stakeholders e seus interesses__:

* Usuário: deseja alterar informações sobre uma avaliação já cadastrada.

__Pré-Condições__: Ao menos uma avaliação está cadastrada

__Pós-Condições__: Avaliação é atualizada com novas informações; notificações correspondentes são salvas e agendadas para acontecer na data e hora informadas; notificações antigas são excluídas.

## Fluxo básico

1. O usuário seleciona a avaliação que deseja alterar.
2. O usuário entra com as novas informações da avaliação: tipo, título, observações, data e hora de realização.
3. Se desejar, o usuário pode alterar os lembretes da avaliação.
4. O sistema salva as informações e encerra.

## Fluxo alternativo

`3a`. Caso deseje alterar os lembretes da avaliação, o caso de uso [Gerenciar lembrete de avaliação](gerenciar-lembrete-de-avaliacao.md) é iniciado.
