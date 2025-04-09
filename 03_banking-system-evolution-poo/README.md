# 💼 Banking System – OOP Python

Um sistema bancário orientado a objetos, desenvolvido em Python como parte do Bootcamp **DIO.ME – Python Developer – 2025**. Este projeto reforça conceitos de **POO (Programação Orientada a Objetos)**, uso de **herança**, **polimorfismo**, **abstração**, e **encapsulamento**, além de boas práticas de estruturação de código.

---

## 📌 Funcionalidades

Este sistema permite simular um ambiente bancário com as seguintes operações:

- 📥 **Depósitos** com validação de valor  
- 💸 **Saques** com limite de R$500 por saque e até 3 saques por sessão  
- 📄 **Exibição de extrato** das transações  
- 🧾 **Criação de novos usuários** (clientes pessoa física)  
- 🏦 **Abertura de contas correntes**  
- 📋 **Listagem de contas criadas**  
- ❌ **Saída do sistema**

---

## 🧱 Arquitetura

O código está organizado com o uso de **classes e herança**, promovendo reuso e clareza:

- `Cliente` (classe base)  
- `PessoaFisica` (herda de Cliente)  
- `Conta` (classe base)  
- `ContaCorrente` (herda de Conta, com regras de saque)  
- `Historico` (controla transações)  
- `Transacao` (classe abstrata para `Saque` e `Deposito`)  

---

## 💻 Como Executar

1. Certifique-se de ter o Python instalado.  
2. Salve o código em um arquivo chamado `main.py`.  
3. No terminal, execute:

```bash
python main.py
```

## 🎯 Objetivos de Aprendizado
Este projeto foi construído para reforçar:

- Criação e uso de classes e objetos
- Uso de @property e @classmethod
- Herança e polimorfismo
- Aplicação de métodos abstratos com ABC
- Manipulação de listas e dicionários
- Estruturação de sistemas com clareza e manutenção

## 📁 Arquivo
- main.py – Script principal do sistema bancário orientado a objetos.

Sinta-se à vontade para explorar, testar e aprimorar! 🚀