# Mad Dragon Fire Website Context

This document provides project, brand, content, and technical context for Codex while building the Mad Dragon Fire LLC website.

---

# 1. Agent Instructions

## Repository

This repository contains the public website for **Mad Dragon Fire LLC**.

Primary domain:

- `maddragonfire.com`

The site should present Mad Dragon Fire as a professional fire-prop manufacturing and custom metal-fabrication company.

## Company Summary

Mad Dragon Fire LLC manufactures fire-performance props and custom metalwork.

The company combines:

- TIG and MIG welding
- Grinding and finishing
- Steel and stainless-steel fabrication
- Mechanical design
- CAD
- Direct fire-performance experience

Products and projects may include:

- Fire fans
- Dragon staffs
- Contact staffs
- Double staffs
- Palm torches
- Custom performance props
- Fabrication jigs and tooling
- Custom metalwork
- Repair and modification work

## Engineering Priorities

When making technical or design decisions, prioritize:

1. Safety
2. Reliability
3. Structural integrity
4. Repeatability
5. Maintainability
6. Clear documentation
7. Visual quality
8. Performance

Avoid presenting experimental equipment as certified, approved, or suitable for unrestricted public use.

## Website Goals

The website should:

- Establish Mad Dragon Fire as a legitimate professional business
- Showcase fabrication quality
- Explain the engineering behind the work
- Display products and custom builds
- Provide a clear contact method
- Link to GitHub and social media
- Support future product sales
- Support future project documentation
- Load quickly on mobile devices
- Look polished without relying on a heavy framework

## Brand Character

The brand should feel:

- Precise
- Engineered
- Intense
- Premium
- Industrial
- Confident
- Creative
- Fire-oriented without looking reckless

Avoid:

- Generic fantasy styling
- Excessive flame animations
- Cheap-looking gradients
- Overly ornate interfaces
- Unsupported claims
- Language suggesting unsafe or uncontrolled fire use
- Language implying that Mad Dragon Fire currently sells poofers, poofer-as-a-service, or insured flame-effect services

## Code Expectations

- Prefer simple, maintainable implementations
- Use semantic HTML
- Make the site responsive
- Maintain accessible color contrast
- Add meaningful alt text
- Avoid unnecessary JavaScript
- Avoid large dependencies unless justified
- Optimize images
- Keep content editable
- Use descriptive filenames
- Document non-obvious decisions

## Working Style

Before broad architectural changes:

1. Inspect the existing repository
2. Summarize the current structure
3. Identify the smallest useful change
4. Implement incrementally
5. Verify the result
6. Report exactly which files changed

Do not rewrite functioning sections without a clear reason.

## Content Safety

Do not publish:

- Personal home addresses
- Private phone numbers
- Insurance policy numbers
- Private legal documents
- Dangerous propane-system operating instructions
- Unreviewed claims about certifications or code compliance
- Secrets, API keys, credentials, or private repository URLs

---

# 2. Project Context

## Current Objective

Build a polished initial landing page for:

- `maddragonfire.com`

The initial release should be small, fast, professional, and easy to extend.

## Initial Release Scope

Include:

- Header and navigation
- Hero section
- Company summary
- Capabilities section
- Featured work or product categories
- Engineering approach
- About section
- Contact section
- GitHub link
- Instagram link
- Footer
- Responsive mobile layout
- HTTPS-compatible deployment
- Custom-domain support

The first release does not need:

- Shopping cart
- Customer accounts
- Payment processing
- Inventory management
- Complex backend
- Blog CMS
- User authentication

## Positioning

Mad Dragon Fire is not merely a novelty fire-prop brand.

Present it as a fire-prop manufacturing and custom metal-fabrication company producing specialized equipment for fire performers and artists.

Differentiators include:

- Professional software and systems engineering background
- Welding and metal-fabrication capability
- Practical shop capability with welder, grinder, fixtures, and repeatable fabrication processes
- Direct experience using fire-performance equipment
- Ability to prototype, test, revise, and manufacture custom equipment
- Emphasis on repeatability and reliability

## Current Work

- Fire-performance prop fabrication
- Repeatable fire-fan construction
- Custom grip and ring designs
- Palm-torch development
- Fabrication tooling and jigs
- Custom metalwork
- Repair and modification work
- Product documentation
- Shop capability development

## Primary Audience

1. Fire performers
2. Performance troupes
3. Event producers
4. Installation artists
5. Custom-fabrication clients
6. Engineers and collaborators
7. Prospective business partners
8. Insurers and landlords performing business due diligence

## Calls to Action

Primary:

- Contact Mad Dragon Fire
- Discuss a project

Secondary:

- View work
- Explore engineering projects
- Visit GitHub
- Follow on Instagram

## Public Identity

Preferred public email:

- `hello@maddragonfire.com`

Instagram:

- `@mad_dragon_fire`

GitHub organization:

- `MadDragonFire`

Location:

- Seattle, Washington

Do not invent URLs that are not yet configured. Clearly mark placeholders.

## Deployment Direction

Preferred stack:

- Static site
- GitHub repository
- GitHub Pages or another simple static host
- Cloudflare DNS
- Automatic HTTPS
- Cloudflare Email Routing for incoming mail

Keep the implementation portable to another static host.

---

# 3. Brand Guide

## Name

Full legal name:

- Mad Dragon Fire LLC

Public brand name:

- Mad Dragon Fire

## Core Description

Mad Dragon Fire manufactures fire-performance props and custom metalwork through welding, grinding, fabrication, and hands-on performance experience.

## Short Description

Fire props and custom metalwork.

## Official Tagline

Fire. Big Fire.

## GitHub Bio

Mad Dragon Fire LLC manufactures fire-performance props and custom metalwork through welding, grinding, mechanical design, and direct performance experience.

## Brand Promise

Build fire-performance props and custom metalwork with practical fabrication, durable construction, and repeatable shop processes.

## Tone

Use language that is:

- Direct
- Technical
- Confident
- Grounded
- Professional
- Concise

Avoid language that is:

- Reckless
- Mystical
- Overly theatrical
- Hyperbolic
- Corporate and vague
- Filled with unsupported superlatives

## Preferred Vocabulary

Use:

- Design
- Engineer
- Fabricate
- Weld
- Grind
- Build
- Test
- Refine
- Precision
- Durable
- Repeatable
- Custom
- Performance
- Mechanical design
- Fire-performance equipment
- Fire props
- Custom metalwork

Use carefully:

- Professional
- Premium
- Safety
- Reliable
- High-performance

Avoid:

- Indestructible
- Guaranteed safe
- Certified
- Approved
- Best
- Ultimate
- Unbreakable
- Risk-free

## Visual Direction

- Black or near-black background
- Warm white typography
- Orange and red-orange accents
- Steel, stainless steel, sparks, heat, and workshop imagery
- Strong geometric layout
- Spacious composition
- Minimal decorative effects

## Starting Color Palette

```css
:root {
  --color-background: #080808;
  --color-surface: #121212;
  --color-surface-raised: #1a1a1a;
  --color-text: #f4ead7;
  --color-text-muted: #b8afa2;
  --color-accent: #ff6a00;
  --color-accent-hot: #ff3300;
  --color-border: #332820;
}
```

## Typography

Headings:

- Strong condensed or industrial serif/sans-serif
- Bold without becoming difficult to read

Body:

- Clean modern sans-serif
- High readability on mobile

Avoid loading many font weights.

## Logo

The existing logo contains:

- Coiled dragon
- Flame ring
- Orange and red-orange palette
- Large `MAD DRAGON` wordmark
- Smaller `FIRE` wordmark
- Black background

Use the logo prominently, but do not let it dominate every section.

Prepare variants for:

- Header
- Hero
- Social thumbnail
- Favicon
- Light background
- Dark background

Preserve the original asset and optimize web copies.

## Tagline

Official:

- Fire. Big Fire.

Use only one primary tagline per page.

---

# 4. Site Specification

## Navigation

Initial items:

- Work
- Capabilities
- About
- Contact
- GitHub

The header must remain readable and usable on mobile.

## Hero

Requirements:

- Mad Dragon Fire logo or wordmark
- Clear one-line positioning statement
- Brief supporting paragraph
- Primary contact CTA
- Secondary work or GitHub CTA
- Strong visual hierarchy
- No autoplay video in the initial version

Suggested headline:

> Fire. Big Fire.

Suggested supporting copy:

> Mad Dragon Fire manufactures fire-performance props and custom metalwork for performers, artists, and fabrication clients through welding, grinding, mechanical design, and direct performance experience.

Primary CTA:

- Discuss a project

Secondary CTA:

- View our work

## Capabilities

### Metal Fabrication

- TIG welding
- MIG welding
- Mild steel
- Stainless steel
- Rings, rods, frames, and custom assemblies
- Jigs and repeatable manufacturing processes

### Fire-Performance Equipment

- Fire fans
- Staffs
- Palm torches
- Custom props
- Wick mounting systems
- Performer-specific geometry

### Custom Metalwork

- Welded steel and stainless components
- Grinding and finishing
- Repairs and modifications
- Brackets, mounts, rings, rods, and frames
- Shop fixtures and practical fabrication support

### Product Development

- Concept development
- CAD and mechanical layout
- Prototype fabrication
- Testing and revision
- Documentation
- Small-batch production

## Featured Work

The first release may use category cards instead of individual product pages if photography is limited.

Suggested categories:

- Fire Fans
- Staffs and Hand Props
- Custom Fabrication
- Custom Metalwork

Each card should include:

- Image
- Category name
- One-sentence description
- Optional detail link

Do not invent products, prices, or availability.

## Engineering Approach

Suggested sequence:

1. Define performer and use-case requirements
2. Design geometry and mechanical interfaces
3. Fabricate and assemble
4. Test balance, handling, durability, and serviceability
5. Revise for repeatable production

## About

The founder is an experienced software and systems engineer with a background in:

- High-performance computing
- Networking
- Systems automation
- Embedded software
- CI/CD
- Linux systems
- Welding and fabrication
- Fire performance

The founder is also a former U.S. Marine.

The site may mention veteran ownership factually and without overstatement.

Do not claim formal VOSB or SDVOSB certification unless completed and verified.

## Contact

Display:

- `hello@maddragonfire.com`
- Instagram
- GitHub
- Seattle, Washington

Do not display a residential address.

The first version should use:

- A `mailto:` link, or
- A static-form provider, or
- A lightweight serverless endpoint

Do not build a backend solely for the first release.

## Footer

Include:

- Mad Dragon Fire LLC
- Seattle, Washington
- Current year
- Email
- GitHub
- Instagram
- Privacy link if analytics or forms collect user data

## Accessibility

Required:

- Semantic headings
- Keyboard-accessible navigation
- Visible focus states
- Sufficient color contrast
- Descriptive link text
- Useful image alt text
- Respect `prefers-reduced-motion`
- Do not convey meaning through color alone

## Performance

- Fast first load on mobile
- No unnecessary framework bundle
- Responsive images
- Lazy-load below-the-fold images
- Compress PNG and JPEG assets
- Prefer WebP or AVIF when appropriate
- Avoid layout shift
- Avoid large background videos

---

# 5. Website Copy

## Hero

### Headline

Fire. Big Fire.

### Supporting Copy

Mad Dragon Fire manufactures fire-performance props and custom metalwork for performers, artists, and fabrication clients through welding, grinding, mechanical design, and direct fire-performance experience.

### Primary CTA

Discuss a project

### Secondary CTA

Explore our work

## Intro

Mad Dragon Fire LLC is a Seattle-based fire-prop manufacturing and custom metal-fabrication company.

We build equipment for performers who care about balance, durability, serviceability, and deliberate design. Our work centers on hands-on welding, grinding, fitting, finishing, and repeatable shop processes.

## Capabilities

### Precision Fabrication

Steel and stainless-steel components fabricated through TIG and MIG welding, with an emphasis on alignment, structural integrity, repeatability, and clean finishing.

### Performance Equipment

Custom fire fans, staffs, palm torches, grip systems, wick mounts, and related equipment designed around the needs of working performers.

### Custom Metalwork

Welded components, repairs, brackets, rings, rods, frames, fixtures, and custom shop-built metal pieces.

### Product Development

From initial geometry and prototypes through testing, documentation, jigs, and small-batch production.

## Work Categories

### Fire Fans

Balanced steel and stainless-steel fire fans developed around performer-specific grip geometry, wick count, handling characteristics, and visual scale.

### Staffs and Hand Props

Custom staffs, palm torches, and handheld props designed for durable construction and predictable handling.

### Custom Fabrication

One-off and small-batch fabrication for performers, troupes, artists, and specialized creative projects.

### Jigs, Repairs, and Custom Metalwork

Welded fixtures, replacement parts, repair work, and custom fabrication for performers, artists, and practical shop needs.

## Engineering Approach

Every project begins with the use case.

We consider:

- Performer dimensions
- Grip and handling
- Weight distribution
- Wick placement
- Structural loads
- Serviceability
- Fabrication repeatability
- Transport and storage
- Intended performance environment

The result is equipment designed as a system rather than assembled as a collection of parts.

## About

Mad Dragon Fire was founded by a software and systems engineer with more than eight years of experience in high-performance computing, networking, automation, Linux systems, and production software.

That engineering background extends into welding, mechanical fabrication, shop tooling, and fire-performance equipment.

The company is informed by direct performance experience. Design decisions are evaluated not only at the workbench, but also through handling, balance, movement, maintenance, and repeated real-world use.

Mad Dragon Fire LLC is veteran-owned and based in Seattle, Washington.

## Contact

Have a fire prop, repair, jig, or custom metalwork project in mind?

Email:

`hello@maddragonfire.com`

Instagram:

`@mad_dragon_fire`

GitHub:

`MadDragonFire`

---

# 6. Technical Direction

## Preferred Implementation

Build the first release as a static site.

Preferred technologies:

- HTML5
- Modern CSS
- Minimal vanilla JavaScript
- GitHub Pages-compatible output
- Cloudflare-managed DNS

Use a static-site generator only if the existing repository already uses one or it materially improves maintainability.

Avoid introducing React, Next.js, a database, or a server solely for a single-page marketing site.

## DNS

Expected provider:

- Cloudflare

Expected domain:

- `maddragonfire.com`

Support:

- Apex domain
- `www` subdomain
- HTTPS
- Redirect to one canonical hostname

Preferred canonical hostname:

- `https://maddragonfire.com`

## GitHub Pages

Verify current GitHub documentation before configuring production DNS.

A typical GitHub Pages setup may use:

```text
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: <github-organization-or-user>.github.io
```

A published `CNAME` file may contain:

```text
maddragonfire.com
```

## HTTPS

Enforce HTTPS through the hosting platform.

Do not manually manage certificates unless required.

## Email

Preferred initial incoming-mail system:

- Cloudflare Email Routing

Primary address:

- `hello@maddragonfire.com`

Possible aliases:

- `contact@maddragonfire.com`
- `orders@maddragonfire.com`
- `support@maddragonfire.com`

Cloudflare Email Routing handles incoming forwarding only. It does not provide full outbound mailbox hosting.

Possible future outbound providers:

- Google Workspace
- Microsoft 365
- Fastmail
- Proton Mail
- Zoho Mail

Preserve and document:

- MX
- SPF
- DKIM
- DMARC

Do not overwrite mail-related DNS records during deployment.

## Analytics

Do not add invasive analytics by default.

Possible choices:

- Cloudflare Web Analytics
- Plausible
- Simple Analytics

If analytics are added:

- Document them
- Avoid unnecessary cookies
- Add a privacy notice when required

## Forms

Preferred initial choices:

1. Direct email link
2. Cloudflare Worker
3. Static-form service

Requirements:

- Spam protection
- No committed API keys
- Clear success and error states
- Accessible labels
- Minimal data collection

## Security

- No secrets in the repository
- Keep third-party scripts minimal
- Add dependency scanning if dependencies are introduced
- Add security headers when supported
- Validate form input
- Do not imply that Mad Dragon Fire currently sells poofers, poofer-as-a-service, or insured flame-effect services

## SEO

Include:

- Unique page title
- Meta description
- Canonical URL
- Open Graph metadata
- Social preview image
- Favicon
- Structured heading hierarchy
- Descriptive content
- Sitemap when the site grows
- `robots.txt`

Suggested title:

> Mad Dragon Fire | Fire-Performance Equipment and Fabrication

Suggested description:

> Mad Dragon Fire manufactures fire-performance props and custom metalwork through welding, grinding, mechanical design, and direct performance experience.

## Social Preview

Use a dedicated landscape image rather than the square GitHub avatar.

Recommended:

- 1200 × 630 pixels
- Logo and brand name
- Dark background
- High contrast
- Minimal text

---

# 7. Roadmap

## Phase 1 — Foundation

- [ ] Inspect existing repository
- [ ] Establish site structure
- [ ] Add brand assets
- [ ] Build responsive header
- [ ] Build hero section
- [ ] Add capabilities section
- [ ] Add work categories
- [ ] Add engineering approach
- [ ] Add about section
- [ ] Add contact section
- [ ] Add footer
- [ ] Verify mobile layout
- [ ] Verify accessibility basics
- [ ] Optimize images
- [ ] Add metadata and favicon

## Phase 2 — Deployment

- [ ] Create production GitHub repository
- [ ] Enable GitHub Pages
- [ ] Add custom domain
- [ ] Configure Cloudflare DNS
- [ ] Configure `www` redirect
- [ ] Enable HTTPS
- [ ] Verify canonical URL
- [ ] Test on mobile and desktop
- [ ] Test all links

## Phase 3 — Email

- [ ] Enable Cloudflare Email Routing
- [ ] Create `hello@maddragonfire.com`
- [ ] Configure forwarding destination
- [ ] Verify forwarding
- [ ] Add SPF
- [ ] Add DKIM when outbound mail is configured
- [ ] Add DMARC
- [ ] Decide whether full mailbox hosting is needed

## Phase 4 — Portfolio

- [ ] Add professional product photography
- [ ] Add individual project pages
- [ ] Add fire-fan portfolio
- [ ] Add staffs and hand props
- [ ] Add custom fabrication projects
- [ ] Add custom metalwork projects
- [ ] Add engineering writeups
- [ ] Add image galleries
- [ ] Add testimonials with permission

## Phase 5 — Commerce

Do not begin until product specifications, insurance, fulfillment, and policies are ready.

- [ ] Define product catalog
- [ ] Define pricing
- [ ] Define lead times
- [ ] Define shipping constraints
- [ ] Define returns and repairs
- [ ] Define terms of sale
- [ ] Add checkout provider
- [ ] Add tax handling
- [ ] Add inventory or made-to-order workflow

## Phase 6 — Documentation

- [ ] Product care instructions
- [ ] Wick replacement guidance
- [ ] Inspection guidance
- [ ] Storage guidance
- [ ] Warranty policy
- [ ] Repair policy
- [ ] Safety disclaimers reviewed for accuracy
- [ ] Downloadable manuals
- [ ] Versioned product specifications

---

# Codex Initial Task

After reading this file, Codex should:

1. Inspect the complete repository.
2. Report the current file tree.
3. Identify the framework, build system, deployment assumptions, and existing design.
4. Compare the current implementation against this context.
5. Propose a small, ordered implementation plan.
6. Do not rewrite working code yet.
7. Identify missing images, links, account names, or deployment values requiring confirmation.
