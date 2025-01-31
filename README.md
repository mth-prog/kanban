<h1>Task Tracker </h1>

Trabalho da materia de laboratorio de engenharia de software utilizando as tecnologias:
  - Next.js 14
  - Server Actions
  - React
  - Prisma
  - Stripe
  - Tailwind
  - MySQL

<h2>Video Apresentação</h2>

https://github.com/mth-prog/kanban/assets/53189625/821ef2b2-7606-49b8-8fc8-e10589732d51


<h2>Características principais:</h2>


- Autenticação
- Organizações/espaços de trabalho
- Criação de quadro
- API Unsplash para lindas imagens de capa aleatórias
- Registro de atividades para toda a organização
- Renomear e excluir quadro
- Criação de lista
- Renomear lista, excluir, arrastar e soltar, reordenar e copiar
- Criação de cartão
- Descrição do cartão, renomear, excluir, arrastar e soltar, reordenar e copiar
- Registro de atividades do cartão
- Limite do conselho para cada organização
- Assinatura Stripe para cada organização para desbloquear painéis ilimitados
- Página de destino
- Banco de dados MySQL
- Prisma ORM
- shadcnUI e TailwindCSS

<h2>Pré requisitos</h2>
<strong>Versão do Node 18.x.x</strong>

<h2>Clone do repositorio</h2>

```
git clone https://github.com/mth-prog/kanban.git
```

<h2>Instalar os packages</h2>

```
npm i
```

<h2>Setup .env file</h2>

```SQL
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_WEBHOOK_SECRET=
```

<h2>Setup Prisma</h2>
Adicionar o MySQL Database (Você usa o PlanetScale)

```
npx prisma generate
npx prisma db push
```
<h2>Para iniciar o app</h2>

```
npm run dev
```

<h2>Comandos disponíveis</h2>

Executando comandos com npm`npm run [command]`


|comando|descrição|
|---|---|
|  `dev` | Inicia uma instância de desenvolvimento do aplicativo  |

*atualizações necessarias para utilização do projeto*
*A
