# ATP_PSI

Neste diagrama, temos as seguintes classes:

-Academia: representa a academia em si, contendo métodos para adicionar e remover clientes e funcionários, bem como listar todos os clientes e funcionários cadastrados.
-Cliente: representa um cliente da academia, com atributos como idCliente, nome, telefone e email. Possui métodos para obter informações do cliente.
-Funcionário: representa um funcionário da academia, com atributos como idFuncionário, nome, telefone e email. Possui métodos para obter informações do funcionário.
-Treino: representa um treino realizado na academia, contendo atributos como idTreino, data de início e data de fim, bem como o cliente associado ao treino. Possui métodos para obter informações do treino, adicionar e remover exercícios e listar os exercícios do treino.
-Exercício: representa um exercício que faz parte de um treino. Possui atributos como idExercício, nome e descrição. Não possui métodos além dos getters.
