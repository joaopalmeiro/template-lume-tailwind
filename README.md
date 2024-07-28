# template-lume-tailwind

Opinionated [Lume](https://lume.land/) + [Tailwind CSS](https://tailwindcss.com/) template for new projects.

## Getting Started

1. Go to or create the project folder.
2. Get the template files:

```bash
npx degit github:joaopalmeiro/template-lume-tailwind
```

or

```bash
npx degit github:joaopalmeiro/template-lume-tailwind --force
```

3. Search for `template-lume-tailwind` and replace it with the project name. Ignore the template repository URL in the [NOTES.md](NOTES.md) file.
4. Search for `Opinionated Lume + Tailwind CSS template for new projects./Opinionated [Lume](https://lume.land/) + [Tailwind CSS](https://tailwindcss.com/) template for new projects.` and replace it with the (short) project description.
5. Search for `João Palmeiro` and replace it with the author's name.
6. Delete the [TEMPLATE.md](TEMPLATE.md) file.
7. Delete the [`Getting Started`](#getting-started) section.

## Development

Install [vfox](https://vfox.lhan.me/guides/quick-start.html) (if necessary).

```bash
vfox add deno
```

```bash
vfox install --all
```

```bash
vfox current
```

```bash
deno task serve
```

```bash
deno task format
```

```bash
deno lint
```

## Deployment

### Cloudflare Pages

```bash
npx wrangler@3.67.1 login
```

```bash
npx wrangler@3.67.1 whoami
```

```bash
npx wrangler@3.67.1 pages project create template-lume-tailwind
```

```bash
deno task build
```

```bash
npx wrangler@3.67.1 pages deploy _site --project-name=template-lume-tailwind
```
