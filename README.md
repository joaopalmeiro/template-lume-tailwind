# template-lume-tailwind

Opinionated [Lume](https://lume.land/) + [Tailwind CSS](https://tailwindcss.com/) template for new projects.

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
