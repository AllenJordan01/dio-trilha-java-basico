# DIO - Trilha Java Básico
# 💻 Desafio: Criando uma Conta Bancária com Java

Este projeto foi desenvolvido como parte do bootcamp da **[DIO (Digital Innovation One)](https://www.dio.me/)**, com o objetivo de praticar conceitos básicos da linguagem **Java**: entrada de dados, variáveis, formatação de saída e estrutura de um programa simples.

---

## 📋 Descrição do desafio

> Crie um programa que simule a abertura de uma conta bancária em um terminal.  
> O programa deve capturar os seguintes dados do usuário:

- ✅ Nome do cliente (permitir espaços, acentos e será exibido em letras maiúsculas)
- ✅ Número da agência (permitir hífen, ex: `1234-5`)
- ✅ Número da conta (apenas números inteiros)
- ✅ Saldo inicial (usar ponto como separador decimal, ex: `243.02`)

Com base nessas informações, o sistema deve exibir a seguinte mensagem:

"Olá [NOME], obrigado por criar uma conta em nosso banco, sua agência é [Agência], conta [Número] e seu saldo [Saldo] já está disponível para saque."
> Note que o nome do cliente será exibido em **letras maiúsculas**.

---

## 🚀 Tecnologias utilizadas

- **Java 21 LTS** (JDK 21)
- **AWS Corretto 21.0.7** (distribuição do OpenJDK mantida pela Amazon)
- IDE: IntelliJ IDEA / Eclipse / VS Code (opcional)
- Terminal para entrada e saída de dados

---

## 📦 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/AllenJordan01/dio-trilha-java-basico.git
```
2. Acesse a pasta do projeto:
```bash
cd dio-trilha-java-basico
```
3. Verifique se possui o Java 21 JDK LTS instalado. Este projeto foi desenvolvido usando o AWS Corretto 21.0.7, uma distribuição do OpenJDK 21 mantida pela Amazon.

4. Compile o programa com o seguinte comando:
```bash
javac ContaTerminal.java
```
5. Execute o programa:
```bash
java ContaTerminal
```
---

## ⚠️ Observações importantes

- O programa foi configurado para aceitar **ponto (`.`)** como separador decimal, conforme exigido pela DIO.  
  → Exemplo válido: `243.02`  
  → Exemplo inválido: `243,02`

- A entrada de **nome** e **agência** aceita caracteres especiais e acentos, como `Érica`, `João`, `1234-5`.

- O nome do cliente será exibido em **letras maiúsculas** na mensagem final.

