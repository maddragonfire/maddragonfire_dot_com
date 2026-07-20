# Mad Dragon Fire Website

Public website for **Mad Dragon Fire LLC**.

Tagline:

- Fire. Big Fire.

Primary domain:

- https://maddragonfire.com

Repository:

- https://github.com/maddragonfire/maddragonfire_dot_com

## Purpose

This site presents Mad Dragon Fire as a professional metalworking company.

The initial site is intentionally small. It is portably built with plain HTML and CSS, served by GitHub Pages, and fronted by Cloudflare DNS/HTTPS.

## Project Context

Read these files before making broad content, design, or structural changes:

- [MAD_DRAGON_FIRE_WEBSITE_CONTEXT.md](MAD_DRAGON_FIRE_WEBSITE_CONTEXT.md) - project specification and repository context
- [AGENTS.md](AGENTS.md) - agent instructions and repository working rules
- [BRAND.md](BRAND.md) - brand voice, visual direction, and vocabulary
- [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) - release goals and business context

## Site Structure

```text
.
├── index.html
├── style.css
├── CNAME
├── assets/images/logo.png
├── images/logo.png
├── logo.png
├── products/
├── about/
├── gallery/
└── contact/
```

Current pages:

- `/` - homepage
- `/products/` - flow props and custom metalwork overview
- `/about/` - company background
- `/gallery/` - work gallery placeholder
- `/contact/` - contact information

## Deployment

The site is deployed through GitHub Pages from:

- Branch: `main`
- Source path: `/`
- Custom domain: `maddragonfire.com`

The `CNAME` file must remain in the repository root and contain:

```text
maddragonfire.com
```

Cloudflare manages DNS and HTTPS. The canonical public URL is:

```text
https://maddragonfire.com
```

## Development

No build step is currently required.

To view locally, open `index.html` in a browser or run a small static server from the repository root:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Editing Guidelines

- Keep the site static unless a clear need for tooling emerges.
- Use semantic HTML and accessible navigation.
- Keep copy direct, technical, and grounded.
- Avoid unsupported claims about certifications, approvals, or unrestricted public use.
- Do not publish private addresses, credentials, policy numbers, or unsafe operational instructions.
- Optimize images before adding them to production pages.
- Prefer incremental changes over broad rewrites.

## Public Links

- GitHub: https://github.com/maddragonfire
- Instagram: https://instagram.com/mad_dragon_fire
- Email: maddragonfire@gmail.com
