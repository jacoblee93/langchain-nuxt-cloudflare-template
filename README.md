# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

1. Install dependencies:

```bash
npm install
```

2. Create vectorize

```bash
npx wrangler vectorize create langchain_js_nuxt --dimensions 768 --metric cosine
```

3. Copy `.dev.vars.example` to `.dev.vars` and fill in the tokens

4. Build project

```bash
npm run build
```

5. Start in preview mode

```bash
npm run preview
```
