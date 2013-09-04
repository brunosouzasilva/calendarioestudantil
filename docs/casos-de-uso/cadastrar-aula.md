# Cadastrar Aula

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Pré-condições__: Ao menos uma disciplina deve estar cadastrada

__Pós-Condições__: Aula se torna disponível para visualização.

## Fluxo básico

1. Usuário informa a qual disciplina pertence a aula.
2. Usuário preenche o campo do local da aula.
3. Usuário define em qual dia da semana pertence a aula.
4. O usuário informa o horário de inicio e fim da aula.

## Fluxo alternativo

`4a`. Horário informado já está ocupado por outro compromisso.
 1. Informa ao usuário a indisponibilidade de cadastrar aula nesse horário.
 2. Impede a criação da aula.
 3. O caso de uso é encerrado.
