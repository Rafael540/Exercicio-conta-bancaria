# Exercicio-conta-bancaria

Fazer um programa para ler os dados de uma conta bancária e depois realizar um
saque nesta conta bancária, mostrando o novo saldo. Um saque não pode ocorrer
ou se não houver saldo na conta, ou se o valor do saque for superior ao limite de
saque da conta. Implemente a conta bancária conforme projeto abaixo:

```mermaid

classDiagram
    class Account {
        - Integer number
        - String holder
        - Double balance
        - Double withdrawLimit
        + deposit(amount: Double) : void
        + withdraw(amount: Double) : void
    }

```
