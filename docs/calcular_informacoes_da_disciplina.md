Caso de Uso: Calcular Informações da Disciplina (notas e presenças)
Ator Primário: Sistema

Pré-Condições:
- Disciplina Cadastrada

Fluxo Principal:
1. O sistema percorre todos os dias de aula cadastrados contando o número total de aulas dadas e o número de presenças.
2. O sistema utiliza os dados obtidos no fluxo anterior para obter a média percentual de presença, ou seja, presença = [(número de presenças)/(número total de aulas dadas)]*100
3. O sistema informa a presença calculada.
4. O sistema analisa se todas as notas que compõem a média final foram submetidas pelo usuário.
5. O sistema identifica a ordem das avaliações e seus respectivos pesos para então aplicar na fórmula da média final.
6. O sistema informa a média calculada.

Fluxo Alternativo:
4.a Não há todas as notas necessárias para o cálculo da média.
 1. O sistema informa ao usuário as notas faltantes.
5.a Nenhuma fórmula foi especificada
 1. O sistema informa ao usuário a não especificação da fórmula.
