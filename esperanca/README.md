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
esperanca/
    │
    │
    ├── app/
    │   ├── api/
    │   │   ├── auth/
    │   │   ├── usuarios/
    │   │   ├── doadores/
    │   │   ├── doacoes/
    │   │   ├── familias/
    │   │   └── entregas/
    │   │
    │   ├── login/
    │   ├── doadores/
    │   ├── doacoes/
    │   ├── familias/
    │   ├── entregas/
    │   │
    │   ├── globals.css
    │   ├── layout.tsx
    │   └── page.tsx
    │
    ├── components/
    │
    ├── lib/
    │
    ├── prisma/
    │   ├── schema.prisma
    │   ├── migrations/
    │   └── seed.ts
    │
    ├── public/
    │
    ├── README.md
    ├── .gitignore
    ├── docs/
    ├── middleware.ts
    ├── package.json
    ├── tsconfig.json
    ├── next.config.ts
    └── .env

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
