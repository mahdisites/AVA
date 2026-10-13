# AVA Group

Public B2B marketing site for **AVA Group** — Iranian dried fruits, nuts, and boxed confectionery imported and distributed in the UK.

## Stack

- Next.js (App Router) + TypeScript + Tailwind CSS + shadcn/ui
- Static product catalogue in `src/data/products.ts` (no CMS, auth, or database)

## Run locally

```bash
npm install
npm run dev
```

Open [http://127.0.0.1:43123](http://127.0.0.1:43123). The dev server binds to `0.0.0.0:43123`.

## Pages

| Route       | Purpose                                      |
| ----------- | -------------------------------------------- |
| `/`         | Brand-first home hero                        |
| `/products` | Dried fruits & nuts + boxed confectionery    |
| `/contact`  | Placeholder contact details + mailto form    |

All catalogue SKUs use a **£10.00** placeholder price for trade enquiry only.

## Brand assets

- Logo: `public/logo.png`
- Hero: `public/hero-dried-fruit.jpg`
- Product photos: `public/products/` (sourced from [BritNuts](https://britnuts.co.uk/))
