
# Desafio de projeto: Criando um sistema bancário com Python (v1)


## Restrições:

* A primeira versão do projeto trabalha apenas com um usuário, portanto não precisa de uma validação de senha, conta ou agência;
* O sistema deve permitir apenas depósitos de valores positivos;
* Existe uma limitação de 3 saques por dia, excedido o limite, o sistema não deve permitir outro saque;
* Existe uma limitação de R$500,00 por saque, mais do que isso o sistema não deve permitir sacar;
* Não existe cheque especial nesta versão, assim que, sem saldo não é possível realizar saques;
* O sistema deve armazenar as transações efetuadas, e possibilitar que o usuário veja o histórico de transações realizadas (saques + depósitos);
* Os valores devem ser exibidos utilizando o formato R$ XXX.XX.

## Funcionalidades:

* O sistema deve ter um menu interativo com o usuário, onde ele decide se quer:
    - Realizar um saque [s];
    - Realizar um depósito [d];
    - Verificar o saldo [e];
    - Encerrar a aplicação [x];
* Qualquer operação diferente disso deve retornar um erro, avisando que a operação é inválida.

* Todos os erros gerados a partir de falha nas operações financeiras, devem gerar uma notificação ao usuário, para que ele entenda o motivo de a operação não ter sido bem sucedida.