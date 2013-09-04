# Criar Disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Usuário

__Stakeholders e seus interesses__

* Usuário: Quer facilidade, sem erros de formatação da disciplina.

__Pós-condições__: A sessão do usuário é atualizada e reorganizada.

## Fluxo Básico

1. O estudante aciona o evento editar disciplina.
+ O sistema fornece um subnível de opções.
+ O aplicativo (sistema) salva as informações da disciplina, atualiza, e organiza a grade.
+ O estudante repete os passos 3-4 até que tenha terminado o processo todo.
+ O sistema apresenta a nova grade, pós atualização.
+ O sistema faz um log das novas mudanças.
+ O usuário poderá checar se está tudo certo. E se organizar a partir da sua grade de disciplinas.

## Fluxo Alternativo

*a. Se a qualquer momento, o sistema travar:

  1. O sistema irá suportar restauração, para que o usuário possa voltar da onde parou.
  + O usuário acessa o aplicativo.
  + O usuário volta na inteface de opções e tenta criar novamente as disciplinas.
  + O sistema tenta recuperar o que estava sendo escrito.
  + Aquelas disciplinas já posteriormente inseridas e não salvas voltam.
  + Aquelas que o sistema não conseguiu entender e interpretar, saem.
  + Nenhum aviso disso será exposto ao usuário, na criação da disciplina.
