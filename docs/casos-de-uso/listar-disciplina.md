# Caso de Uso: Criar Disciplina

* Ator Primário: Estudante
* Stakeholders:

- Estudante: Quer facilidade, sem erros de formatação da disciplina.

## Precondições: A listagem da disciplinas é ordenada em algumas opções.

Quando o usuário tenta listar uma disciplina, ele acessa um local de listagem de disciplinas, uma interface bastante prática e rápida. Que irá fornecer listas de disciplinas, organizadas por nome da disciplina, nome do professor, nome da turma, horário. Dentre outros, a lista gerada aparecerá de maneira não abrupta, mas sob demanda de rolagem.

# Fluxo Básico:

`1.` O estudante aciona a aplicação.
`2.` O estudante aciona o evento criar disciplina (interface prática de opções).
`3.` O estudante acessa o campo para escrever as informações da nova disciplina.
`4.`O aplicativo (sistema) salva as informações da disciplina, atualiza, e organiza a grade.
`6.`o estudante repete os passos 3-4 até que tenha terminado o processo todo.
`7.` O sistema apresenta a nova grade, pós atualização.
`8.` O sistema faz um log das novas mudanças.
`9.` O usuário poderá checar se está tudo certo. E se organizar a partir da sua grade de disciplinas.

# Fluxo Alternativo:

`a.` Se a qualquer momento, o sistema travar:

O sistema irá suportar restauração, para que o usuário possa voltar da onde parou. 

`1.` O usuário acessa o aplicativo.
`2.` O usuário volta na inteface de opções e tenta criar novamente disciplinas.
`3.` O sistema tenta recuperar o que estava sendo escrito.
`3a.` Aquelas disciplinas já posteriormente inseridas e não salvas voltam.
`3b.` Aquelas que o formatador não conseguiu entender e interpretar, saem.
`4.` Nenhum aviso disso será exposto ao usuário, na criação da disciplina.
