# Calcular Informações de Disciplina

__Escopo__: Calendário Acadêmico

__Nível__: Subfunção

__Ator principal__: Sistema

__Pré-Condições__: Ao menos uma disciplina está cadastrada.

## Fluxo básico

1. Para cada disciplina existente, o sistema calcula a frequência do usuário naquela disciplina com base em suas presenças.
2. Para cada disciplina existente, o sistema calcula a média parcial do usuário com base na fórmula de avaliação descrita pelo mesmo para aquela disciplina.

## Fluxo alternativo

`2a`. Não há todas as notas necessárias para o cálculo da média

  1. O sistema informa ao usuário as notas faltantes.
  2. O caso de uso é encerrado.

`2b`. Nenhuma fórmula foi especificada pelo usuário

  1. O sistema utiliza como fórmula de avaliação padrão a média aritimética simples entre as avaliações existentes para aquela disciplina.
