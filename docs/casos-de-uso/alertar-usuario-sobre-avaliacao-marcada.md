# Alertar usuário sobre avaliação marcada

__Escopo__: Calendário Acadêmico

__Nível__: Objetivo do usuário

__Ator principal__: Sistema

__Stakeholders e seus interesses__:

* Usuário: deseja ser avisado sobre avaliação marcada no horário e dia estipulados.

__Pré-Condições__: ter sido criado um lembrete para a avaliação; o sistema deverá observar que existe um lembrete ajustado para o horário e data correntes.

__Pós-Condições__: o sistema pára a execução do lembrete.

## Fluxo básico

1. O sistema dispara um lembrete, podendo este ser sonoro, visual ou ambos, de acordo com as definições ajustadas pelo usuário previamente para o lembrete.
2. O sistema propõe ao usuário a função de postergar o lembrete, para que ele seja disparado novamente após um curto período de tempo predeterminado.
3. O usuário não aceita que o lembrete seja postergado (cancela o alarme).

## Fluxo alternativo

`1a`. Dispositivo incapaz de reproduzir áudio

  1. O alerta sonoro será automaticamente substituído por um vibratório ou similar.

`2a`. Usuário aceita que o alerta seja postergado

  1. O sistema cria um novo alerta que será disparado alguns minutos mais tarde ou em um horário estipulado.
  2. O caso de uso encerrado.
