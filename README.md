Sistema Bancário em Python

Este repositório contém um projeto de um sistema bancário implementado em Python. O sistema permite o gerenciamento de contas bancárias com funcionalidades básicas, incluindo depósito, saque, transferência e visualização de extratos.



Funcionalidades


Criação de Conta: Permite a criação de novas contas bancárias com número, titular e senha.
Depósito: Permite o depósito de valores na conta com registro no extrato.
Saque: Permite o saque de valores, com limites diários e controle do número de saques.
Transferência: Permite a transferência de valores entre contas com autenticação.
Extrato: Exibe o extrato completo das transações realizadas em uma conta.


Estrutura do Projeto


Classes
ContaBancaria: Gerencia operações e informações de uma conta bancária, incluindo saldo, extrato e limites de saque.
Banco: Gerencia a criação e autenticação de contas bancárias.


Métodos Principais
depositar(valor): Adiciona um valor ao saldo da conta e registra a transação.
sacar(valor, senha): Retira um valor do saldo da conta, se os requisitos forem atendidos e a senha for correta.
transferir(valor, conta_destino, senha): Transfere um valor de uma conta para outra, se a autenticação for bem-sucedida e o saldo for suficiente.
mostrar_extrato(): Exibe todas as transações realizadas na conta.
