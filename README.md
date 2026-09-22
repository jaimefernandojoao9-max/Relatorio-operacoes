# Relatório de Operações — versão nuvem

Sistema web (backend + login + base de dados) para o relatório de
operações diárias, preparado para correr no Render com uma base de
dados PostgreSQL gratuita.

## Estado

- ✅ Login, base de dados e API prontos.
- ✅ Criação da primeira conta feita pelo próprio site (sem terminal).
- ⏳ Ainda por fazer: dashboard, aprovação de relatórios, stock — fases
  seguintes do projeto.

## Variáveis de ambiente necessárias (configuradas no Render)

- `DATABASE_URL` — string de ligação à base de dados PostgreSQL
- `JWT_SECRET` — texto longo e aleatório, usado para proteger os logins
- `PORT` — o Render define isto automaticamente

## Comando de arranque

```
npm install
npm start
```
