# next-safe-action skills

Skills for the [next-safe-action](https://github.com/next-safe-action/next-safe-action) library, installable via the [Skills CLI](https://github.com/vercel-labs/skills).

## Installation

Install all skills:

```bash
npx skills add next-safe-action/skills --skill '*'
```

Install a specific skill:

```bash
npx skills add next-safe-action/skills --skill 'safe-action-client'
```

Install globally (available across all projects):

```bash
npx skills add next-safe-action/skills -g
```

Target a specific agent:

```bash
npx skills add next-safe-action/skills --agent claude
```

List available skills:

```bash
npx skills add next-safe-action/skills --list
```

## Available skills

| Skill | Description |
| --- | --- |
| `safe-action-client` | Client setup, input/output validation with Standard Schema (Zod, Yup, Valibot), error handling |
| `safe-action-forms` | Form integration with react-hook-form, native HTML forms, bind arguments, file uploads |
| `safe-action-middleware` | Middleware, authentication, authorization, logging, rate limiting, reusable standalone middleware |
| `safe-action-hooks` | React hooks (`useAction`, `useOptimisticAction`), status/callbacks, optimistic UI updates |
| `safe-action-advanced` | Bind arguments, metadata schemas, framework errors, type inference utilities |
| `safe-action-validation-errors` | Validation error handling, formatted/flattened shapes, field-level and form-level errors |
| `safe-action-better-auth` | Better Auth adapter for typed authentication/authorization in safe actions |
| `safe-action-testing` | Testing patterns with Vitest for server actions, middleware, hooks, and error scenarios |

## Structure

Each skill is a directory under `skills/` containing a `SKILL.md` file with the skill's name, description, and content.
