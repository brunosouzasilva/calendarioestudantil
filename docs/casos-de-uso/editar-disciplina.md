# Caso de Uso: Editar Disciplina

## Ator Primário: 

+ Estudante

## Stakeholders:

+ Estudante: Quer facilidade, sem erros na edição da disciplina, por exemplo grade de horários mal formatada.

## Precondições: 

+ O sistema deve conter uma grade, pelo menos, com disciplinas e horários.

Quando o usuário tenta criar uma disciplina, ele acessa um local de criação de disciplinas, uma interface bastante prática e rápida. Que irá formatar o nome da disciplina na grade de horários. A sessão do usuário, no caso o estudante, é atualizada e organizada pós preenchimento.

# Fluxo Básico:

1. O estudante aciona a aplicação.
+ O estudante aciona o evento editar disciplina numa interface prática de opções.
+ O estudante acessa o campo correspondente a disciplina na grade para reescrever as informações das disciplinas.
+ O aplicativo (sistema) salva as informações da disciplina.
+ O aplicativo atualiza, e reorganiza a grade de horários do usuário.
+ O estudante repete os passos 3-4 até que tenha terminado o processo todo.
+ O sistema apresenta a nova grade, pós edição.
+ O sistema faz um log das novas mudanças.
+ O usuário poderá checar se está tudo certo. E se organizar a partir da sua grade de disciplinas.

# Fluxo Alternativo:

- Se a qualquer momento, o sistema travar:

> O sistema irá suportar restauração, para que o usuário possa voltar da onde parou.

1. O usuário acessa o aplicativo.
+ O usuário volta na inteface de opções e tenta editar novamente as disciplinas.
+ O sistema tenta recuperar o que estava sendo escrito.
  + Aquelas disciplinas já posteriormente inseridas e não salvas voltam.
  + Aquelas que o sistema não conseguiu entender e interpretar, saem.
+ Nenhum aviso disso será exposto ao usuário, na edição da disciplina.
