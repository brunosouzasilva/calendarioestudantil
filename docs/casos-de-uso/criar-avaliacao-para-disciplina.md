# Criar avaliação para disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Interessados e interesses__:

* Usuário: deseja cadastrar avaliações para poder consultar suas próximas tarefas com facilidade e ser alertado com antecedência (configurável) sobre próximas avaliações

__Pré-Condições__: Ao menos uma disciplina está cadastrada

__Pós-Condições__: Avaliação é salva; notificações correspondentes são salvas e agendadas para acontecer na data e hora informadas.

## Fluxo básico

1. O usuário seleciona a disciplina para a qual deseja criar a avaliação.
2. O usuário entra com as informações da avaliação: tipo, título, observações, data e hora de realização.
3. Se desejar, o usuário pode criar lembretes para a avaliação.
4. O sistema salva as informações e encerra.

## Fluxo alternativo

`3a`. Caso deseje adicionar lembretes às avaliações, o caso de uso [Gerenciar lembrete de avaliação](gerenciar-lembrete-de-avaliacao.md) é iniciado
