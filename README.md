# Desafio_1
## Desafio de Python proposto pela DIO.me
Criar um sistema bancário com as operações: sacar, depositar e visualizar extrato.

### Contexto:
  Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja mordernizar as suas operações e para isso escolheu a linguagem Python.
  Para a primeira versão do sistema devemos implementar apenas 3 operações: DEPÓSITO, SAQUE e EXTRATO.

### Operação de depósito
  Deve ser possível depositar valores positivos para minha conta bancária. A v1 do projeto trabalha apenas com 1 usuário, dessa forma não precisamos nos preocupar em identificar qual é o número de agência e conta bancária.
  Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

### Operação de saque
  O sistema deve permitir realizar 3 saques diários com o limite máximo de R$ 500,00 por saque. Caso o contrário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possivel sacar dinheiro por falta de saldo.
  Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

### Operação de extrato
  Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem devem ser exibido o saldo atual da conta.
  Os valores devem ser exibidos utilizando o formato R$ xxx.xx, exemplo:
  1500.45 = R$ 1500.45
