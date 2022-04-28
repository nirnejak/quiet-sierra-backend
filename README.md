# Quiet Sierra Backend

Quiet Sierra Node.js Backend, built with Node.js, Express, Prisma and TypeScript

> Note: Need to configure `.env` file to use local server

---

## Available Scripts

**Install Dependencies**

```bash
npm install
```

**Setup Pre-commit**

```bash
npm run prepare
```

**Start Development Server**

```bash
npm run develop
```

**Build for Production**

```bash
npm run build
```

**Start Production Server**

```bash
npm start
```

---

## Prisma Commands

**Prisma Pull**

```bash
npx prisma db pull
```

**Prisma Generate**

```bash
npx prisma generate
```

**Prisma Studio**

```bash
npx prisma studio
```

---

## Docker Config

**Build Image**

```bash
docker build
```

**Run Image**

```bash
docker run -p 5000:5000 <image-id>
```
