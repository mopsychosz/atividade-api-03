#API Rock Bands Pro

API com CRUD completo, Autenticação JWT e Banco de Dados SQLite.

Bash
npm install
npm run setup-db
npm start

#Rotas

POST /register: Criar novo usuário.

POST /login: Obter token JWT para acesso.

GET /bands: Listagem de bandas com paginação, filtros e ordenação.

POST /bands: Criar nova banda (Requer Token).

PUT /bands/:id: Atualizar banda existente (Requer Token).

DELETE /bands/:id: Remover banda do sistema (Requer Token).
