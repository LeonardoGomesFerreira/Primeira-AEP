# 📊 AEP - CRUD de Usuários com Criptografia (Linguagem C)

Este projeto foi desenvolvido para a **AEP do primeiro semestre** utilizando a **linguagem C no Dev-C++**.

O sistema é um **CRUD (Create, Read, Update, Delete)** de usuários, com funcionalidades de segurança e navegação no terminal.

---

## 🛡️ Funcionalidades

✅ **Inserção de Usuários:**

* O nome de usuário e a senha são **criptografados** ao serem salvos.
* A senha precisa atender critérios de segurança (letra maiúscula, minúscula, número e caractere especial).

✅ **Edição de Usuários:**

* O sistema localiza o usuário descriptografando o nome.
* Pergunta se você deseja alterar:

  * Apenas o **nome**.
  * Apenas a **senha**.
  * **Ambos**.

✅ **Exclusão de Usuários:**

* Localiza o usuário descriptografando o nome.
* Confirmação antes de excluir.

✅ **Listagem de Usuários:**

* 3 modos de visualização:

  1. **Nome descriptografado**, senha oculta como `*******`.
  2. **Nome criptografado**, senha criptografada.
  3. **Nome descriptografado**, senha descriptografada.

✅ **Persistência em Arquivo:**

* Os dados são salvos em `Usuarios.txt`, sempre criptografados.

✅ **Interface no Terminal:**

* Menus interativos com navegação por setas e realce de seleção.
* Layout de janelas simuladas no console (ASCII Art).

---

## 🧑‍💻 Tecnologias Utilizadas

* Linguagem **C**
* Compilador **Dev-C++**
* Manipulação de arquivos `.txt`
* **Criptografia simples** por deslocamento (Cifra de César)
* **Bibliotecas C:** `<stdio.h>`, `<string.h>`, `<conio.h>`, `<windows.h>`, `<ctype.h>`, `<stdlib.h>`

---

## 🎯 Objetivo

O projeto foi desenvolvido para consolidar os conceitos de:

* Estruturas (`struct`)
* Arrays de registros
* Manipulação de arquivos
* Validação de dados
* Criptografia básica
* Menu interativo no terminal (interface console)
