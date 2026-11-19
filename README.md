# Gift store practice application

Initial Next.js foundation. Business features, local Supabase, authentication, and AI integrations have not been implemented yet. The home page is a placeholder, not a working store.

## Run locally

Requires Node.js and npm. Install dependencies from the lockfile and start the development server:

```sh
npm ci
npm run dev
```

Open http://localhost:3000. Run `npm run lint` and `npm run build` for the available checks. Zod and Prettier are installed but not yet integrated into application flows.

## Next stages

Configure local Supabase and authenticated access, then implement the agreed business data and management screens. Gemini, embeddings, RAG, OCR, and text-to-SQL are future integrations and are not executed by this foundation. Do not add credentials to the repository.
