# 🏦 Zevo Bank - Simulação Bancária em Java

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

O **Zevo Bank** é um sistema de simulação de operações bancárias desenvolvido para exercitar conceitos fundamentais de **Programação Orientada a Objetos (POO)**. O projeto foca em segurança de dados, validação de lógica de negócios e modularização.

---

## 🚀 Funcionalidades

* **Gestão de Contas:** Criação de contas com titular, número e saldo inicial.
* **Depósitos:** Validação de valores positivos para incremento de saldo.
* **Saques:** Verificação de limite de saldo antes da operação.
* **Transferências:** Lógica segura de transferência entre instâncias de objetos, garantindo a integridade dos dados.
* **Encapsulamento:** Proteção de atributos sensíveis via modificadores `private` e métodos `Getters`.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java (JDK 17+)
* **Paradigma:** Orientação a Objetos (POO)
* **Entrada de Dados:** `java.util.Scanner`

---

## 📦 Estrutura do Projeto

O sistema é dividido em duas classes principais para garantir a separação de responsabilidades:

1.  **`ContaBancaria.java`**: Contém o modelo da conta, atributos e regras de negócio (saque, depósito, transferência).
2.  **`BancoApp.java`**: Classe principal com o método `main`, responsável pela interação com o usuário e execução do fluxo.

---

## ⚙️ Como Executar

Se você tiver o Java instalado, siga os passos abaixo no seu terminal:

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/teagelado/simuladoBancario.git](https://github.com/teagelado/simuladoBancario.git)
