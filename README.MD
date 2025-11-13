# HONO-DRIZZLE-LIBSQL-TEMPLATE

A starter template for building fully documented type-safe JSON APIs with Hono, Open API, Drizzle with libsql local DB. User auth is already implemented.

## Setup

Clone this template without git history

```sh
npx degit jdncst-dev/hono-drizzle-libsql-template
cd my-api
```

Create `.env` file

```sh
cp .env.example .env
```

Install dependencies

```sh
pnpm install
```

Create sqlite db / push schema

```sh
pnpm drizzle-kit push
```

Run

```sh
pnpm dev
```

Lint

```sh
pnpm lint
```

Test

```sh
pnpm test
```