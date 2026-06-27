# sistema-gestao-doacoes-ong-esperanca

Sistema web para gerenciamento de doações, famílias beneficiadas e controle de estoque da ONG Esperança, desenvolvido com Next.js, Prisma e PostgreSQL.

# Sistema de Gestão de Doações – ONG Esperança

## Sobre o Projeto

O Sistema de Gestão de Doações foi desenvolvido para informatizar o processo de cadastro e controle de doações da ONG Esperança.

O sistema permite:

- Cadastro de doadores
- Cadastro de famílias beneficiadas
- Registro de doações
- Registro de entregas
- Controle de estoque
- Histórico de movimentações
- Autenticação utilizando JWT

---

## Tecnologias

- Next.js
- Next.js API Routes
- PostgreSQL
- Prisma ORM
- JWT
- Vercel

---

## Estrutura

```
docs/
backend/
frontend/
database/
```

---

## Instalação

### Clonar

```bash
git clone https://github.com/Alexandre-200/sistema-gestao-doacoes-ong-esperanca.git
```

### Instalar dependências

```bash
npm install
```

### Configurar ambiente

Copie:

```
.env.example
```

para

```
.env
```

### Executar

```bash
npm run dev
```

---

## Banco

Execute as migrations

```bash
npx prisma migrate dev
```

---

## Autor

Carlos Alexandre
