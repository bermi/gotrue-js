# `gotrue`

An isomorphic JavaScript client library for the [GoTrue](https://github.com/netlify/gotrue) API.
This is a port of [gotrue-js](https://supabase.io/docs/gotrue/client/initializing)

## Docs

- Using `gotrue-js`: https://supabase.io/docs/gotrue/client/initializing
- TypeDoc: https://supabase.github.io/gotrue-js/

## Quick start

Usage

```ts
import { GoTrueClient } from 'https://deno.land/x/gotrue/mod.ts'

const GOTRUE_URL = 'http://localhost:9999'

const auth = new GoTrueClient({ url: GOTRUE_URL })
```

- `signUp()`: https://supabase.io/docs/gotrue/client/signup
- `signIn()`: https://supabase.io/docs/gotrue/client/signin
- `signOut()`: https://supabase.io/docs/gotrue/client/signout
