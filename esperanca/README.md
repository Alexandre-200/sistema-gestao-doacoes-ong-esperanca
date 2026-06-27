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
esperanca/
│
├── README.md
├── .gitignore
├── .env.example
│
├── docs/
│   ├── Documento-de-Visao.pdf
│   ├── Documento-de-Visao.md
│   ├── DER.png
│   └── Casos-de-Uso.png
│
├── frontend/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── globals.css
│   │
│   ├── components/
│   │   ├── ui/
│   │   ├── forms/
│   │   ├── tables/
│   │   └── layout/
│   │
│   ├── lib/
│   │   ├── prisma.ts
│   │   ├── auth.ts
│   │   └── jwt.ts
│   │
│   ├── middleware.ts
│   ├── package.json
│   ├── tsconfig.json
│   ├── next.config.ts
│   └── public/
│
└── database/
    ├── schema.prisma
    ├── seed.ts
    └── migrations/
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
