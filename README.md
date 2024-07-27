# <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> Desafio Intermediário da DIO GFT 03 - Conta Bancária com Construtor em POO


#### Desenvolvido na linguagem Java por:
- [Marcos Shirafuchi](https://github.com/marcosfshirafuchi)

# Principais Tecnologias

- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" title = "Java" /> Java 21 : Utilizaremos a versão LTS mais recente do Java para tirar vantagem das últimas inovações que essa linguagem robusta e amplamente utilizada oferece;
- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" title = "IntelliJ" /> IntelliJ : Usei o IntelliJ como a IDEA.

# Dominando Desafios de Códigos Intermediários em Java
## Desafio 03 / 05 - Conta Bancária com Construtor em POO
### Descrição
Você está desenvolvendo um programa simples em Java para representar uma conta bancária. Utilizando programação orientada a objetos (POO), você criará uma classe <b>ContaBancaria</b> com um construtor que permitirá a inicialização da conta com um saldo inicial.

### Entrada

* O programa solicitará ao usuário que informe o saldo inicial da conta.
* Em seguida, o programa solicitará ao usuário que realize transações de depósito e saque.

### Saída
* A classe <b>ContaBancaria</b> conterá métodos para realizar depósitos e saques, atualizando o saldo da conta.
* O saldo atual será exibido após cada transação.
* Se o valor do saque for maior que o saldo disponível na conta, imprima uma mensagem informando: <b>Saldo insuficiente. Saque não realizado.</b>


### Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.



<table>
  <thead>
    <tr align="left">
      <th>Entrada</th>
      <th>Saída</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>
        50<br>
        50<br>
        100
      </td>
      <td>Deposito feito.<br>
Saldo atual: 100.0<br>
Saque feito.<br>
Saldo atual: 0.0
      </td>
    </tr>
    <tr>
      <td>
        90<br>
        90<br>
        12
      </td>
      <td>Deposito feito.<br>
Saldo atual: 180.0<br>
Saque feito.<br>
Saldo atual: 168.0</td>
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

