# 🗂️ Sistema CRUD em C

Este projeto é um **CRUD completo em C**, desenvolvido como parte dos meus estudos de lógica de programação e como trabalho acadêmico.  
Ele permite **Cadastrar, Listar, Buscar, Atualizar e Remover** registros de pessoas, salvando tudo em um arquivo binário.

---

## 📌 Funcionalidades

- ✔ **Cadastrar pessoas**  
- ✔ **Listar todos os registros**  
- ✔ **Buscar por CPF**  
- ✔ **Atualizar dados existentes**  
- ✔ **Remover registros com segurança**  
- ✔ **Persistência dos dados** usando arquivo `.bin`

---

## 🗃️ Estrutura de Dados

```c
struct Pessoa {
    char nome[51];
    char sobrenome[51];
    char cpf[12];
    int idade;
    char email[101];
};

