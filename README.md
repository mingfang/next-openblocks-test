## This repo is to demonstrate the problem with using Openblocks-SDK with NextJS.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

## To see the problem
1. Open [http://localhost:3000](http://localhost:3000) with your browser to see the problem.
2. Open [http://localhost:3000/dynamic](http://localhost:3000/dynamic) to see a partial workaround using [dynamic import](https://nextjs.org/docs/advanced-features/dynamic-import).
   Note now we see `Error: Cannot find module 'https://unpkg.com/openblocks-comps@latest/index.js'`
