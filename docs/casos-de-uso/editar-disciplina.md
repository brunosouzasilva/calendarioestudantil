# Caso de Uso: Editar Disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Stakeholders e seus interesses__:

* Usuário: Quer facilidade, sem erros na edição da disciplina, por exemplo grade de horários mal formatada.

__Pré-Condições__: Ao menos uma disciplina deve estar cadastrada.

Quando o usuário tenta editar uma disciplina, ele acessa um local de edição das disciplinas, uma interface bastante prática e rápida. Para edição o usuário bastará clicar no campo e o sistema se encarrega de abrir um janela de campos para que o usuário possa re-preencher o que ele quiser sobre a disciplina.

## Fluxo Básico

1. O estudante aciona o evento editar disciplina.
+ O estudante acessa o campo correspondente a disciplina na grade para reescrever as informações das disciplinas.
+ O sistema salva as informações da disciplina.
+ O sistema atualiza e reorganiza a grade de horários do usuário.
+ O sistema apresenta a nova grade, pós edição.
+ O usuário poderá checar se está tudo certo. E se organizar a partir da sua grade de disciplinas.

## Fluxo Alternativo

*a. Se a qualquer momento, o sistema travar:

  1. O sistema tentará restaurar a sessão anterior.
