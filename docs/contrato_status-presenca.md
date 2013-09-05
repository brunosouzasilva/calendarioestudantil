# Contrato: status_presença

__Operação__: status(pres:Presença, novo_status)

__Referências Cruzadas__: Caso de uso Editar Presenças de Disciplina

__Pré-Condições__: Pelo menos uma disciplina com pelo menos uma aula deve ter sido criada.

__Pós-Condições__:
* A instância pres da classe Presença tem seu atributo status alterado para o valor de novo_status, que deve ser obrigatoriamente aula cancelada, ausente ou presente.
