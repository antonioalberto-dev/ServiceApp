# ServiceHub Backend

Este é o backend da aplicação **ServiceHub**, uma plataforma para conectar usuários a prestadores de serviços em diversas categorias. O projeto segue os princípios de **Clean Architecture** e foi desenvolvido em **.NET** com foco em escalabilidade, manutenibilidade e boas práticas de desenvolvimento.

## 🛠️ Tecnologias Utilizadas

- [.NET 8](https://dotnet.microsoft.com/)
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/)
- [PostgreSQL](https://www.postgresql.org/)
- [FluentValidation](https://docs.fluentvalidation.net/)
- [JWT Authentication](https://jwt.io/)
- [AutoMapper](https://automapper.org/)
- [Swagger](https://swagger.io/) (para documentação da API)

## 📐 Arquitetura

O projeto é estruturado com base nos princípios da **Clean Architecture**, separando responsabilidades em camadas bem definidas:

- `Domain`: Entidades de domínio e interfaces.
- `Application`: Casos de uso, serviços de aplicação e validações.
- `Infrastructure`: Implementações de repositórios, contexto do banco de dados e serviços externos.
- `API`: Camada de apresentação (controllers, middlewares, autenticação).

## 🔐 Funcionalidades

- Cadastro e autenticação de usuários com JWT
- Cadastro de prestadores de serviços
- Definição e listagem de tipos de serviços
- Upload de fotos para serviços
- Consulta de serviços disponíveis

## 📁 Organização do Projeto
```
src/
│
├── ServiceHub.API             # Camada de apresentação
├── ServiceHub.Application     # Lógica de negócio e casos de uso
├── ServiceHub.Domain          # Entidades e contratos
└── ServiceHub.Infrastructure  # Implementações técnicas (DB, services)
```

## 🧪 Testes
Os testes ainda estão sendo implementados para os principais casos de uso da aplicação.

## 📌 Status do Projeto
🚧 Em desenvolvimento — funcionalidades básicas concluídas e próximas features em planejamento.

## 🤝 Contribuição
Sinta-se à vontade para abrir issues ou enviar pull requests. Toda ajuda é bem-vinda!