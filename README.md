#  Rock Bands API 

API RESTful para gerenciamento de um catálogo de bandas de rock, desenvolvida com foco em performance e organização. O projeto conta com autenticação JWT, filtros avançados e persistência em banco de dados SQLite.

##  Tecnologias Utilizadas
- **Node.js** & **Express.js**
- **SQLite3** & **Knex.js** (Persistência e Query Building)
- **JSON Web Token** (Segurança e Autenticação)
- **BcryptJS** (Criptografia de senhas)
- **Mocha & Supertest** (Testes automatizados)

##  Arquitetura
O projeto utiliza uma estrutura modular inspirada no padrão MVC:
- **Database:** Configuração e inicialização do banco SQLite via Knex.
- **Routes:** Definição dos endpoints e proteção de rotas.
- **Validation:** Uso de middlewares para garantir a integridade dos dados.

