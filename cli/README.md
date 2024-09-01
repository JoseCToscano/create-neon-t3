<p align="center">
  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/t3-oss/create-t3-app/99286f37324330ecdf75132fae1f246440a88035/www/public/images/t3-light.svg">
  <img src="https://raw.githubusercontent.com/t3-oss/create-t3-app/99286f37324330ecdf75132fae1f246440a88035/www/public/images/t3-dark.svg" width="130" alt="Logo for T3">
</picture>
</p>

<h1 align="center">
  create-neon-t3
</h1>

![Scaffolded app preview](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wxpj6jxni2st7nwwwp42.png)

<p align="center">
  Interactive CLI to start a full-stack, typesafe Next.js app, with database on Neon
</p>


## Why We Forked create-t3-app
The open-source nature of `create-t3-app` allows it to evolve alongside the needs of the community. Our team saw an opportunity to build upon this amazing foundation by integrating Neon as a database provider. The goal of our fork was not to diverge from the original project but to contribute an enhancement that we hope will eventually be merged back into the main repository.

- The original `create-t3-app` offered PlanetScale as the primary database option for MySQL users. However, with PlanetScale's recent deprecation of their free tier, the community needs a strong alternative—especially for those who prefer to build on PostgreSQL. Neon, designed for serverless environments and with its very generous free tier, is the perfect fit for this role.

### Why Neon?
Neon offers a modern, serverless PostgreSQL solution that is perfectly aligned with the needs of developers who prioritize performance, scalability, and simplicity. 

With Neon, you get:

- *Serverless PostgreSQL*: Seamless scaling without the need for managing servers.
- *Cost Efficiency*: A free tier that supports developers from prototyping to production.
- *Developer-Friendly*: A modern approach to database management, making it easy to integrate into existing workflows.

### How to Use the CLI Tool
[![Watch the video](https://img.youtube.com/vi/_CrPRGCYZMM/maxresdefault.jpg)](https://youtu.be/_CrPRGCYZMM)


Our CLI tool retains the simplicity and flexibility of the original `create-t3-app` while offering Neon as the default database provider. 

<h2 id="getting-started">Getting Started</h2>

To scaffold an app using `create-neon-t3`, run any of the following four commands and answer the command prompt questions:

### npm

```bash
npm create neon-t3@latest
```

### yarn

```bash
yarn create neon-t3
```

### pnpm

```bash
pnpm create neon-t3@latest
```

### bun

```bash
bun create neon-t3@latest
```

For more advanced usage, check out the original [CLI docs](https://create.t3.gg/en/installation).



