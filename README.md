# Projeto de Modelagem Conceitual - E-commerce

## 📌 Objetivo

Este projeto apresenta a modelagem conceitual de um sistema de e-commerce para o desafio da DIO, considerando:

- Cadastro de clientes Pessoa Física e Jurídica (um cliente nunca será os dois)
- Registro de pedidos e entrega com status e código de rastreio
- Múltiplas formas de pagamento por pedido
- Controle de estoque
- Vendedores terceiros e fornecedores diretos

## 🧱 Regras de negócio aplicadas

- Uma conta pode ser **Pessoa Física (PF)** ou **Pessoa Jurídica (PJ)**, **nunca ambos**.
- Um **pedido** pode conter **múltiplos produtos**.
- Um **pedido** pode ter **mais de uma forma de pagamento** (cartão, Pix, etc).
- Cada pedido possui **uma entrega**, com **status** e **código de rastreamento**.
- Produtos podem ser disponibilizados por **fornecedores** ou por **terceiros**.

## 🖼️ Modelo Conceitual (MER)

![Diagrama MER](e-commerce%20refinado.png)


## 📁 Estrutura do projeto
📦 ecommerce-modelagem-conceitual
┣ 📄 ecommerce-re.png
┣ 📄 README.md


## 🚀 Tecnologias/Ferramentas

- Ferramenta de modelagem: MySQL Workbench
- Linguagem: Diagrama Entidade-Relacionamento (MER)
- Plataforma de aprendizado: DIO.me

---
