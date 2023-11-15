# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Install dependencies:

```bash
npm install
```

Create a Vectorize index:

```bash
npx wrangler vectorize create langchain_js_nuxt --dimensions 768 --metric cosine
```

Copy `.dev.vars.example` to `.dev.vars` and fill in the tokens:

```ini
# https://platform.openai.com/api-keys
OPENAI_API_KEY=

# https://dash.cloudflare.com/
CLOUDFLARE_ACCOUNT_ID=

# https://developers.cloudflare.com/workers-ai/get-started/rest-api/
CLOUDFLARE_WORKERSAI_API_TOKEN=
```

Build project:

```bash
npm run build
```

Start in preview mode:

```bash
npm run preview
```

