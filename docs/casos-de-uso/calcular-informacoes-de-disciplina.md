# Calcular Informações de Disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Subfunção

__Ator principal__: Sistema

__Pré-Condições__: Ao menos uma disciplina está cadastrada.

## Fluxo básico

1. O aluno seleciona a disciplina para a qual deseja visualizar estatísticas.
2. O sistema calcula a frequência do aluno com base nas presenças e aulas cadastradas.
3. O sistema calcula a média do aluno com base na fórmula da nota final da disciplina e as avaliações cadastradas.
4. O sistema retorna as estatísticas da disciplina.

## Fluxo alternativo

`3a`. Não há todas as notas necessárias para o cálculo da média

  1. O sistema informa ao usuário as notas faltantes.
  2. O caso de uso é encerrado.

`3b`. Nenhuma fórmula foi especificada

  1. O sistema informa ao usuário a não especificação da fórmula.
  2. O caso de uso é encerrado.
