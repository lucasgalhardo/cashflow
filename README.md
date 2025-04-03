# 💰 CashFlow API

&#x20; &#x20;

## 📌 Sobre o Projeto

O **CashFlow API** é uma API desenvolvida para gestão financeira pessoal e empresarial, permitindo o controle de despesas e receitas de forma eficiente. O projeto segue boas práticas de desenvolvimento, garantindo escalabilidade, manutenibilidade e segurança.

## 🚀 Tecnologias Utilizadas

- **.NET 7** (C#)
- **Entity Framework Core**
- **MySQL**
- **Swagger** para documentação
- **AutoMapper** para mapeamento de objetos
- **FluentAssertions** para testes automatizados
- **Exportação de relatórios (Excel e PDF)**

## 📂 Arquitetura do Projeto

O projeto segue os princípios do **DDD (Domain-Driven Design)** e **SOLID**, garantindo um código bem estruturado e de fácil manutenção. As principais camadas são:

- **Application**: Contém os casos de uso e lógica de negócio
- **Domain**: Definição das entidades, interfaces e regras de negócio
- **Infrastructure**: Persistência de dados e configurações do banco
- **Presentation**: Controllers para exposição dos endpoints

## 🛠 Como Rodar o Projeto

### 1️⃣ Clone o repositório

Clone ou baixe o repositório do projeto para seu ambiente local.


### 2️⃣ Configurar o Banco de Dados

Certifique-se de ter um banco MySQL rodando e configure a string de conexão no **appsettings.Development.json**:


### 3️⃣ Rodar a API

Execute a API e aproveite o seu teste :)

A API estará disponível em: [http://localhost:5000](http://localhost:5000)

## 📖 Documentação com Swagger

Após iniciar a API, acesse o Swagger para testar os endpoints: [http://localhost:5000/swagger](http://localhost:5000/swagger)





